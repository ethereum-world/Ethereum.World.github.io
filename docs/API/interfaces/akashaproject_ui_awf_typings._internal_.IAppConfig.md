[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / IAppConfig

# Interface: IAppConfig

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).IAppConfig

## Table of contents

### Properties

- [activeWhen](akashaproject_ui_awf_typings._internal_.IAppConfig.md#activewhen)
- [extends](akashaproject_ui_awf_typings._internal_.IAppConfig.md#extends)
- [extensions](akashaproject_ui_awf_typings._internal_.IAppConfig.md#extensions)
- [menuItems](akashaproject_ui_awf_typings._internal_.IAppConfig.md#menuitems)
- [mountsIn](akashaproject_ui_awf_typings._internal_.IAppConfig.md#mountsin)
- [name](akashaproject_ui_awf_typings._internal_.IAppConfig.md#name)
- [routes](akashaproject_ui_awf_typings._internal_.IAppConfig.md#routes)
- [tags](akashaproject_ui_awf_typings._internal_.IAppConfig.md#tags)
- [title](akashaproject_ui_awf_typings._internal_.IAppConfig.md#title)

### Methods

- [loadingFn](akashaproject_ui_awf_typings._internal_.IAppConfig.md#loadingfn)

## Properties

### activeWhen

• **activeWhen**: [`ActivityFn`](../modules/akashaproject_ui_awf_typings._internal_.md#activityfn)

#### Defined in

[ui/typings/src/app-loader.ts:92](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L92)

___

### extends

• `Optional` **extends**: [`ExtensionPointDefinition`](akashaproject_ui_awf_typings._internal_.ExtensionPointDefinition.md)[]

Defines the component that will be mounted into an extension point

#### Defined in

[ui/typings/src/app-loader.ts:117](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L117)

___

### extensions

• `Optional` **extensions**: [`Record`](../modules/akashaproject_ui_awf_typings._internal_.md#record)<`string`, `string`\>

A simple mapping of the extension points exposed by this widget

#### Defined in

[ui/typings/src/app-loader.ts:112](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L112)

___

### menuItems

• `Optional` **menuItems**: [`IMenuItem`](akashaproject_ui_awf_typings._internal_.IMenuItem.md)

Only used for topbar.
Warning: we may deprecate this property

#### Defined in

[ui/typings/src/app-loader.ts:133](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L133)

___

### mountsIn

• `Optional` **mountsIn**: `string`

The id of the html element
that this app will mount in

#### Defined in

[ui/typings/src/app-loader.ts:97](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L97)

___

### name

• **name**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:108](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L108)

___

### routes

• **routes**: `Object`

routes that are defined here can be used
by other apps for navigation

#### Index signature

▪ [key: `string`]: `string`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `rootRoute` | `string` |

#### Defined in

[ui/typings/src/app-loader.ts:103](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L103)

___

### tags

• `Optional` **tags**: `string`[]

Keywords that defines this widget.
Useful for filtering through integrations

#### Defined in

[ui/typings/src/app-loader.ts:123](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L123)

___

### title

• **title**: `string`

Used for page title

#### Defined in

[ui/typings/src/app-loader.ts:128](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L128)

## Methods

### loadingFn

▸ **loadingFn**(): `Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Returns

`Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Defined in

[ui/typings/src/app-loader.ts:107](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L107)
