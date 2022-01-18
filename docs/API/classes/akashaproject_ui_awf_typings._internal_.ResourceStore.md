[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / ResourceStore

# Class: ResourceStore

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).ResourceStore

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_typings._internal_.ResourceStore.md#constructor)

### Properties

- [data](akashaproject_ui_awf_typings._internal_.ResourceStore.md#data)
- [options](akashaproject_ui_awf_typings._internal_.ResourceStore.md#options)

### Methods

- [off](akashaproject_ui_awf_typings._internal_.ResourceStore.md#off)
- [on](akashaproject_ui_awf_typings._internal_.ResourceStore.md#on)

## Constructors

### constructor

• **new ResourceStore**(`data`, `options`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`Resource`](../interfaces/akashaproject_ui_awf_typings._internal_.Resource.md) |
| `options` | [`InitOptions`](../interfaces/akashaproject_ui_awf_typings._internal_.InitOptions.md) |

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:749

## Properties

### data

• **data**: [`Resource`](../interfaces/akashaproject_ui_awf_typings._internal_.Resource.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:751

___

### options

• **options**: [`InitOptions`](../interfaces/akashaproject_ui_awf_typings._internal_.InitOptions.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:752

## Methods

### off

▸ **off**(`event`, `callback?`): `void`

Remove event listener
removes all callback when callback not specified

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"added"`` \| ``"removed"`` |
| `callback?` | (`lng`: `string`, `ns`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:762

___

### on

▸ **on**(`event`, `callback`): `void`

Gets fired when resources got added or removed

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"added"`` \| ``"removed"`` |
| `callback` | (`lng`: `string`, `ns`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:757
