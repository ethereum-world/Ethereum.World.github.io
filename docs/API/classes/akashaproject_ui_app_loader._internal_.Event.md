[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Event

# Class: Event

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Event

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Event.md#constructor)

### Properties

- [listener](akashaproject_ui_app_loader._internal_.Event.md#listener)
- [once](akashaproject_ui_app_loader._internal_.Event.md#once)
- [tag](akashaproject_ui_app_loader._internal_.Event.md#tag)

### Accessors

- [event](akashaproject_ui_app_loader._internal_.Event.md#event)
- [filter](akashaproject_ui_app_loader._internal_.Event.md#filter)
- [hash](akashaproject_ui_app_loader._internal_.Event.md#hash)
- [type](akashaproject_ui_app_loader._internal_.Event.md#type)

### Methods

- [pollable](akashaproject_ui_app_loader._internal_.Event.md#pollable)

## Constructors

### constructor

• **new Event**(`tag`, `listener`, `once`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tag` | `string` |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |
| `once` | `boolean` |

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:12

## Properties

### listener

• `Readonly` **listener**: [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:9

___

### once

• `Readonly` **once**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:10

___

### tag

• `Readonly` **tag**: `string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:11

## Accessors

### event

• `get` **event**(): [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype)

#### Returns

[`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:13

___

### filter

• `get` **filter**(): [`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md)

#### Returns

[`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:16

___

### hash

• `get` **hash**(): `string`

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:15

___

### type

• `get` **type**(): `string`

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:14

## Methods

### pollable

▸ **pollable**(): `boolean`

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:17
