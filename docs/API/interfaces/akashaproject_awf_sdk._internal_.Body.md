[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Body

# Interface: Body

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Body

## Hierarchy

- **`Body`**

  ↳ [`Response`](akashaproject_awf_sdk._internal_.Response.md)

  ↳ [`Request`](akashaproject_awf_sdk._internal_.Request.md)

## Table of contents

### Properties

- [body](akashaproject_awf_sdk._internal_.Body.md#body)
- [bodyUsed](akashaproject_awf_sdk._internal_.Body.md#bodyused)

### Methods

- [arrayBuffer](akashaproject_awf_sdk._internal_.Body.md#arraybuffer)
- [blob](akashaproject_awf_sdk._internal_.Body.md#blob)
- [formData](akashaproject_awf_sdk._internal_.Body.md#formdata)
- [json](akashaproject_awf_sdk._internal_.Body.md#json)
- [text](akashaproject_awf_sdk._internal_.Body.md#text)

## Properties

### body

• `Readonly` **body**: [`ReadableStream`](../modules/akashaproject_awf_sdk._internal_.md#readablestream)<`Uint8Array`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2444

___

### bodyUsed

• `Readonly` **bodyUsed**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2445

## Methods

### arrayBuffer

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2446

___

### blob

▸ **blob**(): `Promise`<`Blob`\>

#### Returns

`Promise`<`Blob`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2447

___

### formData

▸ **formData**(): `Promise`<[`FormData`](../modules/akashaproject_awf_sdk._internal_.md#formdata)\>

#### Returns

`Promise`<[`FormData`](../modules/akashaproject_awf_sdk._internal_.md#formdata)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2448

___

### json

▸ **json**(): `Promise`<`any`\>

#### Returns

`Promise`<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2449

___

### text

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2450
