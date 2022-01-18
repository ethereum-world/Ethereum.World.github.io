[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / SharedArrayBuffer

# Interface: SharedArrayBuffer

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).SharedArrayBuffer

## Table of contents

### Properties

- [[species]](akashaproject_awf_sdk._internal_.SharedArrayBuffer.md#[species])
- [[toStringTag]](akashaproject_awf_sdk._internal_.SharedArrayBuffer.md#[tostringtag])
- [byteLength](akashaproject_awf_sdk._internal_.SharedArrayBuffer.md#bytelength)

### Methods

- [slice](akashaproject_awf_sdk._internal_.SharedArrayBuffer.md#slice)

## Properties

### [species]

• `Readonly` **[species]**: [`SharedArrayBuffer`](../modules/akashaproject_awf_sdk._internal_.md#sharedarraybuffer)

#### Defined in

node_modules/typescript/lib/lib.es2017.sharedmemory.d.ts:34

___

### [toStringTag]

• `Readonly` **[toStringTag]**: ``"SharedArrayBuffer"``

#### Defined in

node_modules/typescript/lib/lib.es2017.sharedmemory.d.ts:35

___

### byteLength

• `Readonly` **byteLength**: `number`

Read-only. The length of the ArrayBuffer (in bytes).

#### Defined in

node_modules/typescript/lib/lib.es2017.sharedmemory.d.ts:28

## Methods

### slice

▸ **slice**(`begin`, `end?`): [`SharedArrayBuffer`](../modules/akashaproject_awf_sdk._internal_.md#sharedarraybuffer)

Returns a section of an SharedArrayBuffer.

#### Parameters

| Name | Type |
| :------ | :------ |
| `begin` | `number` |
| `end?` | `number` |

#### Returns

[`SharedArrayBuffer`](../modules/akashaproject_awf_sdk._internal_.md#sharedarraybuffer)

#### Defined in

node_modules/typescript/lib/lib.es2017.sharedmemory.d.ts:33
