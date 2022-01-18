[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / WritableStream

# Interface: WritableStream<W\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).WritableStream

This Streams API interface provides a standard abstraction for writing streaming data to a destination, known as a sink. This object comes with built-in backpressure and queuing.

## Type parameters

| Name | Type |
| :------ | :------ |
| `W` | `any` |

## Table of contents

### Properties

- [locked](akashaproject_awf_sdk._internal_.WritableStream.md#locked)

### Methods

- [abort](akashaproject_awf_sdk._internal_.WritableStream.md#abort)
- [close](akashaproject_awf_sdk._internal_.WritableStream.md#close)
- [getWriter](akashaproject_awf_sdk._internal_.WritableStream.md#getwriter)

## Properties

### locked

• `Readonly` **locked**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17472

## Methods

### abort

▸ **abort**(`reason?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `reason?` | `any` |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17473

___

### close

▸ **close**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17474

___

### getWriter

▸ **getWriter**(): [`WritableStreamDefaultWriter`](../modules/akashaproject_awf_sdk._internal_.md#writablestreamdefaultwriter)<`W`\>

#### Returns

[`WritableStreamDefaultWriter`](../modules/akashaproject_awf_sdk._internal_.md#writablestreamdefaultwriter)<`W`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17475
