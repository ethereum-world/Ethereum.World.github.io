[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Response

# Interface: Response

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Response

This Fetch API interface represents the response to a request.

## Hierarchy

- [`Body`](akashaproject_awf_sdk._internal_.Body.md)

  ↳ **`Response`**

## Table of contents

### Properties

- [body](akashaproject_awf_sdk._internal_.Response.md#body)
- [bodyUsed](akashaproject_awf_sdk._internal_.Response.md#bodyused)
- [headers](akashaproject_awf_sdk._internal_.Response.md#headers)
- [ok](akashaproject_awf_sdk._internal_.Response.md#ok)
- [redirected](akashaproject_awf_sdk._internal_.Response.md#redirected)
- [status](akashaproject_awf_sdk._internal_.Response.md#status)
- [statusText](akashaproject_awf_sdk._internal_.Response.md#statustext)
- [type](akashaproject_awf_sdk._internal_.Response.md#type)
- [url](akashaproject_awf_sdk._internal_.Response.md#url)

### Methods

- [arrayBuffer](akashaproject_awf_sdk._internal_.Response.md#arraybuffer)
- [blob](akashaproject_awf_sdk._internal_.Response.md#blob)
- [clone](akashaproject_awf_sdk._internal_.Response.md#clone)
- [formData](akashaproject_awf_sdk._internal_.Response.md#formdata)
- [json](akashaproject_awf_sdk._internal_.Response.md#json)
- [text](akashaproject_awf_sdk._internal_.Response.md#text)

## Properties

### body

• `Readonly` **body**: [`ReadableStream`](../modules/akashaproject_awf_sdk._internal_.md#readablestream)<`Uint8Array`\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[body](akashaproject_awf_sdk._internal_.Body.md#body)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2444

___

### bodyUsed

• `Readonly` **bodyUsed**: `boolean`

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[bodyUsed](akashaproject_awf_sdk._internal_.Body.md#bodyused)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2445

___

### headers

• `Readonly` **headers**: [`Headers`](../modules/akashaproject_awf_sdk._internal_.md#headers)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12143

___

### ok

• `Readonly` **ok**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12144

___

### redirected

• `Readonly` **redirected**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12145

___

### status

• `Readonly` **status**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12146

___

### statusText

• `Readonly` **statusText**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12147

___

### type

• `Readonly` **type**: [`ResponseType`](../modules/akashaproject_awf_sdk._internal_.md#responsetype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12148

___

### url

• `Readonly` **url**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12149

## Methods

### arrayBuffer

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[arrayBuffer](akashaproject_awf_sdk._internal_.Body.md#arraybuffer)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2446

___

### blob

▸ **blob**(): `Promise`<`Blob`\>

#### Returns

`Promise`<`Blob`\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[blob](akashaproject_awf_sdk._internal_.Body.md#blob)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2447

___

### clone

▸ **clone**(): [`Response`](../modules/akashaproject_awf_sdk._internal_.md#response)

#### Returns

[`Response`](../modules/akashaproject_awf_sdk._internal_.md#response)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12150

___

### formData

▸ **formData**(): `Promise`<[`FormData`](../modules/akashaproject_awf_sdk._internal_.md#formdata)\>

#### Returns

`Promise`<[`FormData`](../modules/akashaproject_awf_sdk._internal_.md#formdata)\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[formData](akashaproject_awf_sdk._internal_.Body.md#formdata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2448

___

### json

▸ **json**(): `Promise`<`any`\>

#### Returns

`Promise`<`any`\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[json](akashaproject_awf_sdk._internal_.Body.md#json)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2449

___

### text

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Inherited from

[Body](akashaproject_awf_sdk._internal_.Body.md).[text](akashaproject_awf_sdk._internal_.Body.md#text)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2450
