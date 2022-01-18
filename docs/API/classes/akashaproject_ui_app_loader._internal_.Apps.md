[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Apps

# Class: Apps

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Apps

## Hierarchy

- [`BaseIntegration`](akashaproject_ui_app_loader._internal_.BaseIntegration.md)

  ↳ **`Apps`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Apps.md#constructor)

### Properties

- [addMenuItem](akashaproject_ui_app_loader._internal_.Apps.md#addmenuitem)
- [getMenuItems](akashaproject_ui_app_loader._internal_.Apps.md#getmenuitems)
- [layoutConfig](akashaproject_ui_app_loader._internal_.Apps.md#layoutconfig)
- [logger](akashaproject_ui_app_loader._internal_.Apps.md#logger)
- [navigateTo](akashaproject_ui_app_loader._internal_.Apps.md#navigateto)
- [sdk](akashaproject_ui_app_loader._internal_.Apps.md#sdk)
- [uiEvents](akashaproject_ui_app_loader._internal_.Apps.md#uievents)
- [worldConfig](akashaproject_ui_app_loader._internal_.Apps.md#worldconfig)

### Accessors

- [configs](akashaproject_ui_app_loader._internal_.Apps.md#configs)
- [infos](akashaproject_ui_app_loader._internal_.Apps.md#infos)
- [modules](akashaproject_ui_app_loader._internal_.Apps.md#modules)

### Methods

- [add](akashaproject_ui_app_loader._internal_.Apps.md#add)
- [checkActivityFn](akashaproject_ui_app_loader._internal_.Apps.md#checkactivityfn)
- [filterAppsByMountPoint](akashaproject_ui_app_loader._internal_.Apps.md#filterappsbymountpoint)
- [filterWidgetsByMountPoint](akashaproject_ui_app_loader._internal_.Apps.md#filterwidgetsbymountpoint)
- [getAppRoutes](akashaproject_ui_app_loader._internal_.Apps.md#getapproutes)
- [getAppsCount](akashaproject_ui_app_loader._internal_.Apps.md#getappscount)
- [getAppsForLocation](akashaproject_ui_app_loader._internal_.Apps.md#getappsforlocation)
- [getDomElement](akashaproject_ui_app_loader._internal_.Apps.md#getdomelement)
- [getExtensions](akashaproject_ui_app_loader._internal_.Apps.md#getextensions)
- [import](akashaproject_ui_app_loader._internal_.Apps.md#import)
- [importConfigs](akashaproject_ui_app_loader._internal_.Apps.md#importconfigs)
- [install](akashaproject_ui_app_loader._internal_.Apps.md#install)
- [onExtensionPointMount](akashaproject_ui_app_loader._internal_.Apps.md#onextensionpointmount)
- [onFirstMount](akashaproject_ui_app_loader._internal_.Apps.md#onfirstmount)
- [onRouting](akashaproject_ui_app_loader._internal_.Apps.md#onrouting)
- [registerApp](akashaproject_ui_app_loader._internal_.Apps.md#registerapp)
- [uninstall](akashaproject_ui_app_loader._internal_.Apps.md#uninstall)

## Constructors

### constructor

• **new Apps**(`opts`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | [`BaseIntegrationClassOptions`](../interfaces/akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md) |

#### Overrides

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[constructor](akashaproject_ui_app_loader._internal_.BaseIntegration.md#constructor)

#### Defined in

[ui/app-loader/src/apps.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L23)

## Properties

### addMenuItem

• **addMenuItem**: (`menuItem`: [`IMenuItem`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuItem.md)) => `void`

#### Type declaration

▸ (`menuItem`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `menuItem` | [`IMenuItem`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuItem.md) |

##### Returns

`void`

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[addMenuItem](akashaproject_ui_app_loader._internal_.BaseIntegration.md#addmenuitem)

#### Defined in

[ui/app-loader/src/base-integration.ts:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L35)

___

### getMenuItems

• **getMenuItems**: () => [`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Type declaration

▸ (): [`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

##### Returns

[`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[getMenuItems](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getmenuitems)

#### Defined in

[ui/app-loader/src/base-integration.ts:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L36)

___

### layoutConfig

• **layoutConfig**: [`LayoutConfig`](../interfaces/akashaproject_ui_app_loader._internal_.LayoutConfig.md)

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[layoutConfig](akashaproject_ui_app_loader._internal_.BaseIntegration.md#layoutconfig)

#### Defined in

[ui/app-loader/src/base-integration.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L31)

___

### logger

• **logger**: [`ILogger`](../interfaces/akashaproject_ui_app_loader._internal_.ILogger.md)

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[logger](akashaproject_ui_app_loader._internal_.BaseIntegration.md#logger)

#### Defined in

[ui/app-loader/src/base-integration.ts:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L37)

___

### navigateTo

• **navigateTo**: (`options`: [`NavigationOptions`](../interfaces/akashaproject_ui_app_loader._internal_.NavigationOptions.md)) => `void`

#### Type declaration

▸ (`options`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`NavigationOptions`](../interfaces/akashaproject_ui_app_loader._internal_.NavigationOptions.md) |

##### Returns

`void`

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[navigateTo](akashaproject_ui_app_loader._internal_.BaseIntegration.md#navigateto)

#### Defined in

[ui/app-loader/src/base-integration.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L38)

___

### sdk

• **sdk**: [`IAwfSDK`](../interfaces/akashaproject_ui_app_loader._internal_.IAwfSDK.md)

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[sdk](akashaproject_ui_app_loader._internal_.BaseIntegration.md#sdk)

#### Defined in

[ui/app-loader/src/base-integration.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L34)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](../interfaces/akashaproject_ui_app_loader._internal_.UIEventData.md)\>

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[uiEvents](akashaproject_ui_app_loader._internal_.BaseIntegration.md#uievents)

#### Defined in

[ui/app-loader/src/base-integration.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L32)

___

### worldConfig

• **worldConfig**: [`ISdkConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ISdkConfig.md) & [`ILoaderConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ILoaderConfig.md)

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[worldConfig](akashaproject_ui_app_loader._internal_.BaseIntegration.md#worldconfig)

#### Defined in

[ui/app-loader/src/base-integration.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L33)

## Accessors

### configs

• `get` **configs**(): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md)\>

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md)\>

#### Defined in

[ui/app-loader/src/apps.ts:248](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L248)

___

### infos

• `get` **infos**(): [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md)[]

#### Returns

[`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md)[]

#### Defined in

[ui/app-loader/src/apps.ts:251](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L251)

___

### modules

• `get` **modules**(): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IntegrationModule`](../interfaces/akashaproject_ui_app_loader._internal_.IntegrationModule.md)\>

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IntegrationModule`](../interfaces/akashaproject_ui_app_loader._internal_.IntegrationModule.md)\>

#### Defined in

[ui/app-loader/src/apps.ts:254](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L254)

## Methods

### add

▸ **add**(`appInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `appInfo` | [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/apps.ts:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L35)

___

### checkActivityFn

▸ **checkActivityFn**(`integrationConfig`, `location`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `integrationConfig` | [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md) \| [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md) |
| `location` | [`Location`](../modules/akashaproject_ui_app_loader._internal_.md#location) |

#### Returns

`boolean`

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[checkActivityFn](akashaproject_ui_app_loader._internal_.BaseIntegration.md#checkactivityfn)

#### Defined in

[ui/app-loader/src/base-integration.ts:88](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L88)

___

### filterAppsByMountPoint

▸ **filterAppsByMountPoint**(`appInfos`, `appConfigs`, `extension?`): [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `appInfos` | [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md)[] |
| `appConfigs` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md)\> |
| `extension?` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

[`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md)[]

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[filterAppsByMountPoint](akashaproject_ui_app_loader._internal_.BaseIntegration.md#filterappsbymountpoint)

#### Defined in

[ui/app-loader/src/base-integration.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L52)

___

### filterWidgetsByMountPoint

▸ **filterWidgetsByMountPoint**(`widgetInfos`, `widgetConfigs`, `widgetParcels`, `extension?`): [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `widgetInfos` | [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)[] |
| `widgetConfigs` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md)\> |
| `widgetParcels` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`Parcel`](../modules/akashaproject_ui_app_loader._internal_.md#parcel)<[`CustomProps`](../interfaces/akashaproject_ui_app_loader._internal_.CustomProps.md)\>\> |
| `extension?` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

[`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)[]

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[filterWidgetsByMountPoint](akashaproject_ui_app_loader._internal_.BaseIntegration.md#filterwidgetsbymountpoint)

#### Defined in

[ui/app-loader/src/base-integration.ts:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L70)

___

### getAppRoutes

▸ **getAppRoutes**(`appId`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `appId` | `string` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `rootRoute` | `string` |

#### Defined in

[ui/app-loader/src/apps.ts:240](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L240)

___

### getAppsCount

▸ **getAppsCount**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `configs` | `number` |
| `infos` | `number` |
| `modules` | `number` |

#### Defined in

[ui/app-loader/src/apps.ts:146](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L146)

___

### getAppsForLocation

▸ **getAppsForLocation**(`location`): `string`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](../modules/akashaproject_ui_app_loader._internal_.md#location) |

#### Returns

`string`[]

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[getAppsForLocation](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getappsforlocation)

#### Defined in

[ui/app-loader/src/base-integration.ts:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L49)

___

### getDomElement

▸ **getDomElement**(`integrationConfig`, `name`, `idPrefix`): `void` \| `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `integrationConfig` | [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md) \| [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md) |
| `name` | `string` |
| `idPrefix` | ``"app"`` \| ``"widget"`` \| ``"extension"`` |

#### Returns

`void` \| `HTMLElement`

#### Inherited from

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[getDomElement](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getdomelement)

#### Defined in

[ui/app-loader/src/base-integration.ts:97](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L97)

___

### getExtensions

▸ **getExtensions**(): [`ExtensionPointDefinition`](../interfaces/akashaproject_ui_app_loader._internal_.ExtensionPointDefinition.md)[]

#### Returns

[`ExtensionPointDefinition`](../interfaces/akashaproject_ui_app_loader._internal_.ExtensionPointDefinition.md)[]

#### Defined in

[ui/app-loader/src/apps.ts:113](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L113)

___

### import

▸ **import**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/apps.ts:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L39)

___

### importConfigs

▸ **importConfigs**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/apps.ts:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L54)

___

### install

▸ **install**(`appInfo`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `appInfo` | [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/apps.ts:197](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L197)

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

[ui/app-loader/src/apps.ts:140](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L140)

___

### onFirstMount

▸ **onFirstMount**(`location`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](../modules/akashaproject_ui_app_loader._internal_.md#location) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/apps.ts:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L74)

___

### onRouting

▸ **onRouting**(`location`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](../modules/akashaproject_ui_app_loader._internal_.md#location) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/apps.ts:96](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L96)

___

### registerApp

▸ **registerApp**(`appName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `appName` | `string` |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/apps.ts:153](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L153)

___

### uninstall

▸ **uninstall**(`info`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`AppRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.AppRegistryInfo.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/apps.ts:224](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/apps.ts#L224)
