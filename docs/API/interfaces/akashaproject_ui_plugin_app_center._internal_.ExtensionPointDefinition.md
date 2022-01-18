[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-plugin-app-center](../modules/akashaproject_ui_plugin_app_center.md) / [<internal\>](../modules/akashaproject_ui_plugin_app_center._internal_.md) / ExtensionPointDefinition

# Interface: ExtensionPointDefinition

[@akashaproject/ui-plugin-app-center](../modules/akashaproject_ui_plugin_app_center.md).[<internal>](../modules/akashaproject_ui_plugin_app_center._internal_.md).ExtensionPointDefinition

## Table of contents

### Properties

- [activeWhen](akashaproject_ui_plugin_app_center._internal_.ExtensionPointDefinition.md#activewhen)
- [mountsIn](akashaproject_ui_plugin_app_center._internal_.ExtensionPointDefinition.md#mountsin)
- [parentApp](akashaproject_ui_plugin_app_center._internal_.ExtensionPointDefinition.md#parentapp)

### Methods

- [loadingFn](akashaproject_ui_plugin_app_center._internal_.ExtensionPointDefinition.md#loadingfn)

## Properties

### activeWhen

• `Optional` **activeWhen**: [`ActivityFn`](../modules/akashaproject_ui_plugin_app_center._internal_.md#activityfn)

#### Defined in

ui/typings/lib/app-loader.d.ts:75

___

### mountsIn

• **mountsIn**: `string` \| (`opts`: [`IntegrationRegistrationOptions`](akashaproject_ui_plugin_app_center._internal_.IntegrationRegistrationOptions.md)) => `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:72

___

### parentApp

• `Optional` **parentApp**: `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:74

## Methods

### loadingFn

▸ **loadingFn**(): `Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_plugin_app_center._internal_.ISingleSpaLifecycle.md)\>

#### Returns

`Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_plugin_app_center._internal_.ISingleSpaLifecycle.md)\>

#### Defined in

ui/typings/lib/app-loader.d.ts:73
