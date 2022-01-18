[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / File

# Interface: File

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).File

Provides information about files and allows JavaScript in a web page to access their content.

## Hierarchy

- `Blob`

  ↳ **`File`**

## Table of contents

### Properties

- [lastModified](akashaproject_ui_awf_testing_utils._internal_.File.md#lastmodified)
- [name](akashaproject_ui_awf_testing_utils._internal_.File.md#name)
- [size](akashaproject_ui_awf_testing_utils._internal_.File.md#size)
- [type](akashaproject_ui_awf_testing_utils._internal_.File.md#type)
- [webkitRelativePath](akashaproject_ui_awf_testing_utils._internal_.File.md#webkitrelativepath)

### Methods

- [arrayBuffer](akashaproject_ui_awf_testing_utils._internal_.File.md#arraybuffer)
- [slice](akashaproject_ui_awf_testing_utils._internal_.File.md#slice)
- [stream](akashaproject_ui_awf_testing_utils._internal_.File.md#stream)
- [text](akashaproject_ui_awf_testing_utils._internal_.File.md#text)

## Properties

### lastModified

• `Readonly` **lastModified**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5238

___

### name

• `Readonly` **name**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5239

___

### size

• `Readonly` **size**: `number`

#### Inherited from

Blob.size

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2420

___

### type

• `Readonly` **type**: `string`

#### Inherited from

Blob.type

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2421

___

### webkitRelativePath

• `Readonly` **webkitRelativePath**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5240

## Methods

### arrayBuffer

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Inherited from

Blob.arrayBuffer

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2422

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Inherited from

Blob.arrayBuffer

#### Defined in

node_modules/@types/node/stream/consumers.d.ts:9

___

### slice

▸ **slice**(`start?`, `end?`, `contentType?`): `Blob`

#### Parameters

| Name | Type |
| :------ | :------ |
| `start?` | `number` |
| `end?` | `number` |
| `contentType?` | `string` |

#### Returns

`Blob`

#### Inherited from

Blob.slice

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2423

▸ **slice**(`start?`, `end?`, `contentType?`): `Blob`

#### Parameters

| Name | Type |
| :------ | :------ |
| `start?` | `number` |
| `end?` | `number` |
| `contentType?` | `string` |

#### Returns

`Blob`

#### Inherited from

Blob.slice

#### Defined in

node_modules/@types/node/stream/consumers.d.ts:10

___

### stream

▸ **stream**(): [`ReadableStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#readablestream)<`any`\>

#### Returns

[`ReadableStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#readablestream)<`any`\>

#### Inherited from

Blob.stream

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2424

▸ **stream**(): `ReadableStream`

#### Returns

`ReadableStream`

#### Inherited from

Blob.stream

#### Defined in

node_modules/@types/node/stream/consumers.d.ts:11

___

### text

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Inherited from

Blob.text

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2425

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Inherited from

Blob.text

#### Defined in

node_modules/@types/node/stream/consumers.d.ts:12
