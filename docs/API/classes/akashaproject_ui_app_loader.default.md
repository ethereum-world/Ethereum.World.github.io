[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / default

# Class: default

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).default

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader.default.md#constructor)

### Properties

- [layoutConfig](akashaproject_ui_app_loader.default.md#layoutconfig)
- [uiEvents](akashaproject_ui_app_loader.default.md#uievents)

### Methods

- [addMenuItem](akashaproject_ui_app_loader.default.md#addmenuitem)
- [createImportMaps](akashaproject_ui_app_loader.default.md#createimportmaps)
- [filterExtensionsByMountPoint](akashaproject_ui_app_loader.default.md#filterextensionsbymountpoint)
- [getMenuItems](akashaproject_ui_app_loader.default.md#getmenuitems)
- [getPackageInfo](akashaproject_ui_app_loader.default.md#getpackageinfo)
- [getPackageInfos](akashaproject_ui_app_loader.default.md#getpackageinfos)
- [getUserIntegrations](akashaproject_ui_app_loader.default.md#getuserintegrations)
- [importLayoutConfig](akashaproject_ui_app_loader.default.md#importlayoutconfig)
- [installIntegration](akashaproject_ui_app_loader.default.md#installintegration)
- [loadLayout](akashaproject_ui_app_loader.default.md#loadlayout)
- [mountExtension](akashaproject_ui_app_loader.default.md#mountextension)
- [navigateTo](akashaproject_ui_app_loader.default.md#navigateto)
- [onExtensionPointMount](akashaproject_ui_app_loader.default.md#onextensionpointmount)
- [onExtensionPointUnmount](akashaproject_ui_app_loader.default.md#onextensionpointunmount)
- [onModalMount](akashaproject_ui_app_loader.default.md#onmodalmount)
- [onModalUnmount](akashaproject_ui_app_loader.default.md#onmodalunmount)
- [start](akashaproject_ui_app_loader.default.md#start)
- [uninstallIntegration](akashaproject_ui_app_loader.default.md#uninstallintegration)

## Constructors

### constructor

• **new default**(`worldConfig`, `sdk`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `worldConfig` | [`ILoaderConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ILoaderConfig.md) & [`ISdkConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ISdkConfig.md) |
| `sdk` | [`AWF_SDK`](../interfaces/akashaproject_ui_app_loader._internal_.AWF_SDK.md) |

#### Defined in

[ui/app-loader/src/index.ts:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L70)

## Properties

### layoutConfig

• `Optional` **layoutConfig**: [`LayoutConfig`](../interfaces/akashaproject_ui_app_loader._internal_.LayoutConfig.md)

#### Defined in

[ui/app-loader/src/index.ts:62](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L62)

___

### uiEvents

• `Readonly` **uiEvents**: `BehaviorSubject`<[`UIEventData`](../interfaces/akashaproject_ui_app_loader._internal_.UIEventData.md)\>

#### Defined in

[ui/app-loader/src/index.ts:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L53)

## Methods

### addMenuItem

▸ **addMenuItem**(`menuItem`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuItem` | [`IMenuItem`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuItem.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:674](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L674)

___

### createImportMaps

▸ **createImportMaps**(`infos`, `scriptId`): `Promise`<`void`\>

Get the infos about the apps and register them into systemjs

#### Parameters

| Name | Type |
| :------ | :------ |
| `infos` | ([`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md))[] |
| `scriptId` | `string` |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/index.ts:500](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L500)

___

### filterExtensionsByMountPoint

▸ **filterExtensionsByMountPoint**(`appAndWidgetExtensions`, `integrationConfigs`, `integrationInfos`, `extensionData`): [`ExtensionPointDefinition`](../interfaces/akashaproject_ui_app_loader._internal_.ExtensionPointDefinition.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `appAndWidgetExtensions` | [`ExtensionPointDefinition`](../interfaces/akashaproject_ui_app_loader._internal_.ExtensionPointDefinition.md)[] |
| `integrationConfigs` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md) \| [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md)\> |
| `integrationInfos` | ([`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md))[] |
| `extensionData` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

[`ExtensionPointDefinition`](../interfaces/akashaproject_ui_app_loader._internal_.ExtensionPointDefinition.md)[]

#### Defined in

[ui/app-loader/src/index.ts:323](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L323)

___

### getMenuItems

▸ **getMenuItems**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `items` | [`IMenuItem`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuItem.md)[] |
| `nextIndex` | `number` |

#### Defined in

[ui/app-loader/src/index.ts:670](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L670)

___

### getPackageInfo

▸ **getPackageInfo**(`pack`): `Promise`<[`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `pack` | [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition) |

#### Returns

`Promise`<[`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)\>

#### Defined in

[ui/app-loader/src/index.ts:471](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L471)

___

### getPackageInfos

▸ **getPackageInfos**(`packages`): `Promise`<([`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md))[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `packages` | [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition)[] |

#### Returns

`Promise`<([`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md))[]\>

#### Defined in

[ui/app-loader/src/index.ts:483](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L483)

___

### getUserIntegrations

▸ **getUserIntegrations**(): `void`

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:195](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L195)

___

### importLayoutConfig

▸ **importLayoutConfig**(`integrationInfos`): `Promise`<[`LayoutConfig`](../interfaces/akashaproject_ui_app_loader._internal_.LayoutConfig.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `integrationInfos` | ([`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md))[] |

#### Returns

`Promise`<[`LayoutConfig`](../interfaces/akashaproject_ui_app_loader._internal_.LayoutConfig.md)\>

#### Defined in

[ui/app-loader/src/index.ts:518](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L518)

___

### installIntegration

▸ **installIntegration**(`integration?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `integration?` | `Object` |
| `integration.name` | `string` |
| `integration.version?` | `string` |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/index.ts:581](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L581)

___

### loadLayout

▸ **loadLayout**(): `Promise`<``null``\>

#### Returns

`Promise`<``null``\>

#### Defined in

[ui/app-loader/src/index.ts:545](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L545)

___

### mountExtension

▸ **mountExtension**(`config`, `info`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md) \| [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md) |
| `info` | [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/index.ts:626](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L626)

___

### navigateTo

▸ **navigateTo**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `string` \| [`NavigationOptions`](../interfaces/akashaproject_ui_app_loader._internal_.NavigationOptions.md) \| [`NavigationFn`](../modules/akashaproject_ui_app_loader._internal_.md#navigationfn) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:395](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L395)

___

### onExtensionPointMount

▸ **onExtensionPointMount**(`extensionData?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `extensionData?` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:357](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L357)

___

### onExtensionPointUnmount

▸ **onExtensionPointUnmount**(`extensionData?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `extensionData?` | `Object` |
| `extensionData.name` | `string` |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:451](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L451)

___

### onModalMount

▸ **onModalMount**(`modalData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `modalData` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:257](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L257)

___

### onModalUnmount

▸ **onModalUnmount**(`modalData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `modalData` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/index.ts:292](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L292)

___

### start

▸ **start**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/index.ts:135](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L135)

___

### uninstallIntegration

▸ **uninstallIntegration**(`integration?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `integration?` | `Object` |
| `integration.name` | `string` |
| `integration.version?` | `string` |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/index.ts:643](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/index.ts#L643)
