[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Widgets

# Class: Widgets

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Widgets

## Hierarchy

- [`BaseIntegration`](akashaproject_ui_app_loader._internal_.BaseIntegration.md)

  ↳ **`Widgets`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Widgets.md#constructor)

### Properties

- [addMenuItem](akashaproject_ui_app_loader._internal_.Widgets.md#addmenuitem)
- [getMenuItems](akashaproject_ui_app_loader._internal_.Widgets.md#getmenuitems)
- [layoutConfig](akashaproject_ui_app_loader._internal_.Widgets.md#layoutconfig)
- [logger](akashaproject_ui_app_loader._internal_.Widgets.md#logger)
- [navigateTo](akashaproject_ui_app_loader._internal_.Widgets.md#navigateto)
- [sdk](akashaproject_ui_app_loader._internal_.Widgets.md#sdk)
- [uiEvents](akashaproject_ui_app_loader._internal_.Widgets.md#uievents)
- [worldConfig](akashaproject_ui_app_loader._internal_.Widgets.md#worldconfig)

### Accessors

- [configs](akashaproject_ui_app_loader._internal_.Widgets.md#configs)
- [infos](akashaproject_ui_app_loader._internal_.Widgets.md#infos)

### Methods

- [add](akashaproject_ui_app_loader._internal_.Widgets.md#add)
- [checkActivityFn](akashaproject_ui_app_loader._internal_.Widgets.md#checkactivityfn)
- [filterAppsByMountPoint](akashaproject_ui_app_loader._internal_.Widgets.md#filterappsbymountpoint)
- [filterWidgetsByMountPoint](akashaproject_ui_app_loader._internal_.Widgets.md#filterwidgetsbymountpoint)
- [getAppsForLocation](akashaproject_ui_app_loader._internal_.Widgets.md#getappsforlocation)
- [getDomElement](akashaproject_ui_app_loader._internal_.Widgets.md#getdomelement)
- [getExtensions](akashaproject_ui_app_loader._internal_.Widgets.md#getextensions)
- [import](akashaproject_ui_app_loader._internal_.Widgets.md#import)
- [importConfigs](akashaproject_ui_app_loader._internal_.Widgets.md#importconfigs)
- [install](akashaproject_ui_app_loader._internal_.Widgets.md#install)
- [onExtensionPointMount](akashaproject_ui_app_loader._internal_.Widgets.md#onextensionpointmount)
- [onExtensionPointUnmount](akashaproject_ui_app_loader._internal_.Widgets.md#onextensionpointunmount)
- [registerWidget](akashaproject_ui_app_loader._internal_.Widgets.md#registerwidget)
- [uninstall](akashaproject_ui_app_loader._internal_.Widgets.md#uninstall)

## Constructors

### constructor

• **new Widgets**(`opts`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | [`BaseIntegrationClassOptions`](../interfaces/akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md) & { `getAppRoutes`: (`appId`: `string`) => { [key: string]: `string`; `rootRoute`: `string`  }  } |

#### Overrides

[BaseIntegration](akashaproject_ui_app_loader._internal_.BaseIntegration.md).[constructor](akashaproject_ui_app_loader._internal_.BaseIntegration.md#constructor)

#### Defined in

[ui/app-loader/src/widgets.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L20)

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

• `get` **configs**(): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md)\>

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md)\>

#### Defined in

[ui/app-loader/src/widgets.ts:218](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L218)

___

### infos

• `get` **infos**(): [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)[]

#### Returns

[`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md)[]

#### Defined in

[ui/app-loader/src/widgets.ts:221](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L221)

## Methods

### add

▸ **add**(`integration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `integration` | [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/widgets.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L33)

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

[ui/app-loader/src/widgets.ts:139](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L139)

___

### import

▸ **import**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/widgets.ts:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L37)

___

### importConfigs

▸ **importConfigs**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/widgets.ts:116](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L116)

___

### install

▸ **install**(`widgetInfo`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `widgetInfo` | [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/widgets.ts:165](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L165)

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

[ui/app-loader/src/widgets.ts:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L50)

___

### onExtensionPointUnmount

▸ **onExtensionPointUnmount**(`extensionData?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `extensionData?` | [`EventDataTypes`](../modules/akashaproject_ui_app_loader._internal_.md#eventdatatypes) |

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/app-loader/src/widgets.ts:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L61)

___

### registerWidget

▸ **registerWidget**(`widgetName`): `Promise`<``null``\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `widgetName` | `string` |

#### Returns

`Promise`<``null``\>

#### Defined in

[ui/app-loader/src/widgets.ts:73](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L73)

___

### uninstall

▸ **uninstall**(`info`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`WidgetRegistryInfo`](../interfaces/akashaproject_ui_app_loader._internal_.WidgetRegistryInfo.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/widgets.ts:193](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/widgets.ts#L193)
