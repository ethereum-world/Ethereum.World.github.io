[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / ExtensionPointDefinition

# Interface: ExtensionPointDefinition

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).ExtensionPointDefinition

## Table of contents

### Properties

- [activeWhen](akashaproject_ui_awf_typings._internal_.ExtensionPointDefinition.md#activewhen)
- [mountsIn](akashaproject_ui_awf_typings._internal_.ExtensionPointDefinition.md#mountsin)
- [parentApp](akashaproject_ui_awf_typings._internal_.ExtensionPointDefinition.md#parentapp)

### Methods

- [loadingFn](akashaproject_ui_awf_typings._internal_.ExtensionPointDefinition.md#loadingfn)

## Properties

### activeWhen

• `Optional` **activeWhen**: [`ActivityFn`](../modules/akashaproject_ui_awf_typings._internal_.md#activityfn)

#### Defined in

[ui/typings/src/app-loader.ts:88](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L88)

___

### mountsIn

• **mountsIn**: `string` \| (`opts`: [`IntegrationRegistrationOptions`](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md)) => `string`

#### Defined in

[ui/typings/src/app-loader.ts:85](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L85)

___

### parentApp

• `Optional` **parentApp**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:87](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L87)

## Methods

### loadingFn

▸ **loadingFn**(): `Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Returns

`Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Defined in

[ui/typings/src/app-loader.ts:86](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L86)
