[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / BaseIntegration

# Class: BaseIntegration

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).BaseIntegration

## Hierarchy

- **`BaseIntegration`**

  ↳ [`Apps`](akashaproject_ui_app_loader._internal_.Apps.md)

  ↳ [`Widgets`](akashaproject_ui_app_loader._internal_.Widgets.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.BaseIntegration.md#constructor)

### Properties

- [addMenuItem](akashaproject_ui_app_loader._internal_.BaseIntegration.md#addmenuitem)
- [getMenuItems](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getmenuitems)
- [layoutConfig](akashaproject_ui_app_loader._internal_.BaseIntegration.md#layoutconfig)
- [logger](akashaproject_ui_app_loader._internal_.BaseIntegration.md#logger)
- [navigateTo](akashaproject_ui_app_loader._internal_.BaseIntegration.md#navigateto)
- [sdk](akashaproject_ui_app_loader._internal_.BaseIntegration.md#sdk)
- [uiEvents](akashaproject_ui_app_loader._internal_.BaseIntegration.md#uievents)
- [worldConfig](akashaproject_ui_app_loader._internal_.BaseIntegration.md#worldconfig)

### Methods

- [checkActivityFn](akashaproject_ui_app_loader._internal_.BaseIntegration.md#checkactivityfn)
- [filterAppsByMountPoint](akashaproject_ui_app_loader._internal_.BaseIntegration.md#filterappsbymountpoint)
- [filterWidgetsByMountPoint](akashaproject_ui_app_loader._internal_.BaseIntegration.md#filterwidgetsbymountpoint)
- [getAppsForLocation](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getappsforlocation)
- [getDomElement](akashaproject_ui_app_loader._internal_.BaseIntegration.md#getdomelement)

## Constructors

### constructor

• **new BaseIntegration**(`opts`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | [`BaseIntegrationClassOptions`](../interfaces/akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md) |

#### Defined in

[ui/app-loader/src/base-integration.ts:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L39)

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

#### Defined in

[ui/app-loader/src/base-integration.ts:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L35)

___

### getMenuItems

• **getMenuItems**: () => [`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Type declaration

▸ (): [`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

##### Returns

[`IMenuList`](../interfaces/akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L36)

___

### layoutConfig

• **layoutConfig**: [`LayoutConfig`](../interfaces/akashaproject_ui_app_loader._internal_.LayoutConfig.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L31)

___

### logger

• **logger**: [`ILogger`](../interfaces/akashaproject_ui_app_loader._internal_.ILogger.md)

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

#### Defined in

[ui/app-loader/src/base-integration.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L38)

___

### sdk

• **sdk**: [`IAwfSDK`](../interfaces/akashaproject_ui_app_loader._internal_.IAwfSDK.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L34)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](../interfaces/akashaproject_ui_app_loader._internal_.UIEventData.md)\>

#### Defined in

[ui/app-loader/src/base-integration.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L32)

___

### worldConfig

• **worldConfig**: [`ISdkConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ISdkConfig.md) & [`ILoaderConfig`](../interfaces/akashaproject_ui_app_loader._internal_.ILoaderConfig.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L33)

## Methods

### checkActivityFn

▸ **checkActivityFn**(`integrationConfig`, `location`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `integrationConfig` | [`IAppConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IAppConfig.md) \| [`IWidgetConfig`](../interfaces/akashaproject_ui_app_loader._internal_.IWidgetConfig.md) |
| `location` | [`Location`](../modules/akashaproject_ui_app_loader._internal_.md#location) |

#### Returns

`boolean`

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

#### Defined in

[ui/app-loader/src/base-integration.ts:97](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L97)
