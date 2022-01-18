[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Blob

# Interface: Blob

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Blob

A file-like object of immutable, raw data. Blobs represent data that isn't necessarily in a JavaScript-native format. The File interface is based on Blob, inheriting blob functionality and expanding it to support files on the user's system.

## Table of contents

### Properties

- [size](akashaproject_ui_app_loader._internal_.Blob.md#size)
- [type](akashaproject_ui_app_loader._internal_.Blob.md#type)

### Methods

- [arrayBuffer](akashaproject_ui_app_loader._internal_.Blob.md#arraybuffer)
- [slice](akashaproject_ui_app_loader._internal_.Blob.md#slice)
- [stream](akashaproject_ui_app_loader._internal_.Blob.md#stream)
- [text](akashaproject_ui_app_loader._internal_.Blob.md#text)

## Properties

### size

• `Readonly` **size**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2420

___

### type

• `Readonly` **type**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2421

## Methods

### arrayBuffer

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2422

___

### slice

▸ **slice**(`start?`, `end?`, `contentType?`): [`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob)

#### Parameters

| Name | Type |
| :------ | :------ |
| `start?` | `number` |
| `end?` | `number` |
| `contentType?` | `string` |

#### Returns

[`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2423

___

### stream

▸ **stream**(): [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`any`\>

#### Returns

[`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2424

___

### text

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2425
