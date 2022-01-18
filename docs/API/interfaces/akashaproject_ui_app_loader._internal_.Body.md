[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Body

# Interface: Body

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Body

## Hierarchy

- **`Body`**

  ↳ [`Response`](akashaproject_ui_app_loader._internal_.Response.md)

  ↳ [`Request`](akashaproject_ui_app_loader._internal_.Request.md)

## Table of contents

### Properties

- [body](akashaproject_ui_app_loader._internal_.Body.md#body)
- [bodyUsed](akashaproject_ui_app_loader._internal_.Body.md#bodyused)

### Methods

- [arrayBuffer](akashaproject_ui_app_loader._internal_.Body.md#arraybuffer)
- [blob](akashaproject_ui_app_loader._internal_.Body.md#blob)
- [formData](akashaproject_ui_app_loader._internal_.Body.md#formdata)
- [json](akashaproject_ui_app_loader._internal_.Body.md#json)
- [text](akashaproject_ui_app_loader._internal_.Body.md#text)

## Properties

### body

• `Readonly` **body**: [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`Uint8Array`\>

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

▸ **blob**(): `Promise`<[`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob)\>

#### Returns

`Promise`<[`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2447

___

### formData

▸ **formData**(): `Promise`<[`FormData`](../modules/akashaproject_ui_app_loader._internal_.md#formdata)\>

#### Returns

`Promise`<[`FormData`](../modules/akashaproject_ui_app_loader._internal_.md#formdata)\>

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
