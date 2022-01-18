[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / WritableStreamDefaultWriter

# Interface: WritableStreamDefaultWriter<W\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).WritableStreamDefaultWriter

This Streams API interface is the object returned by WritableStream.getWriter() and once created locks the < writer to the WritableStream ensuring that no other streams can write to the underlying sink.

## Type parameters

| Name | Type |
| :------ | :------ |
| `W` | `any` |

## Table of contents

### Properties

- [closed](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#closed)
- [desiredSize](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#desiredsize)
- [ready](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#ready)

### Methods

- [abort](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#abort)
- [close](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#close)
- [releaseLock](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#releaselock)
- [write](akashaproject_awf_sdk._internal_.WritableStreamDefaultWriter.md#write)

## Properties

### closed

• `Readonly` **closed**: `Promise`<`undefined`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17495

___

### desiredSize

• `Readonly` **desiredSize**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17496

___

### ready

• `Readonly` **ready**: `Promise`<`undefined`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17497

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

node_modules/typescript/lib/lib.dom.d.ts:17498

___

### close

▸ **close**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17499

___

### releaseLock

▸ **releaseLock**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17500

___

### write

▸ **write**(`chunk?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `chunk?` | `W` |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17501
