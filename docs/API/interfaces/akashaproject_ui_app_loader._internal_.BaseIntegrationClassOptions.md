[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / BaseIntegrationClassOptions

# Interface: BaseIntegrationClassOptions

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).BaseIntegrationClassOptions

## Table of contents

### Properties

- [layoutConfig](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#layoutconfig)
- [sdk](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#sdk)
- [uiEvents](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#uievents)
- [worldConfig](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#worldconfig)

### Methods

- [addMenuItem](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#addmenuitem)
- [getMenuItems](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#getmenuitems)
- [navigateTo](akashaproject_ui_app_loader._internal_.BaseIntegrationClassOptions.md#navigateto)

## Properties

### layoutConfig

• **layoutConfig**: [`LayoutConfig`](akashaproject_ui_app_loader._internal_.LayoutConfig.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L21)

___

### sdk

• **sdk**: [`IAwfSDK`](akashaproject_ui_app_loader._internal_.IAwfSDK.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L24)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](akashaproject_ui_app_loader._internal_.UIEventData.md)\>

#### Defined in

[ui/app-loader/src/base-integration.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L22)

___

### worldConfig

• **worldConfig**: [`ISdkConfig`](akashaproject_ui_app_loader._internal_.ISdkConfig.md) & [`ILoaderConfig`](akashaproject_ui_app_loader._internal_.ILoaderConfig.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L23)

## Methods

### addMenuItem

▸ **addMenuItem**(`menuItem`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuItem` | [`IMenuItem`](akashaproject_ui_app_loader._internal_.IMenuItem.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/base-integration.ts:25](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L25)

___

### getMenuItems

▸ **getMenuItems**(): [`IMenuList`](akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Returns

[`IMenuList`](akashaproject_ui_app_loader._internal_.IMenuList.md)

#### Defined in

[ui/app-loader/src/base-integration.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L26)

___

### navigateTo

▸ **navigateTo**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`NavigationOptions`](akashaproject_ui_app_loader._internal_.NavigationOptions.md) |

#### Returns

`void`

#### Defined in

[ui/app-loader/src/base-integration.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/app-loader/src/base-integration.ts#L27)
