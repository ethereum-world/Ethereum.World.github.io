[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / ReadableStream

# Interface: ReadableStream<R\>

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).ReadableStream

This Streams API interface represents a readable stream of byte data. The Fetch API offers a concrete instance of a ReadableStream through the body property of a Response object.

## Type parameters

| Name | Type |
| :------ | :------ |
| `R` | `any` |

## Table of contents

### Properties

- [locked](akashaproject_ui_app_loader._internal_.ReadableStream.md#locked)

### Methods

- [cancel](akashaproject_ui_app_loader._internal_.ReadableStream.md#cancel)
- [forEach](akashaproject_ui_app_loader._internal_.ReadableStream.md#foreach)
- [getReader](akashaproject_ui_app_loader._internal_.ReadableStream.md#getreader)
- [pipeThrough](akashaproject_ui_app_loader._internal_.ReadableStream.md#pipethrough)
- [pipeTo](akashaproject_ui_app_loader._internal_.ReadableStream.md#pipeto)
- [tee](akashaproject_ui_app_loader._internal_.ReadableStream.md#tee)

## Properties

### locked

• `Readonly` **locked**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11980

## Methods

### cancel

▸ **cancel**(`reason?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `reason?` | `any` |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11981

___

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`value`: `any`, `key`: `number`, `parent`: [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`R`\>) => `void` |
| `thisArg?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11986

___

### getReader

▸ **getReader**(): [`ReadableStreamDefaultReader`](../modules/akashaproject_ui_app_loader._internal_.md#readablestreamdefaultreader)<`R`\>

#### Returns

[`ReadableStreamDefaultReader`](../modules/akashaproject_ui_app_loader._internal_.md#readablestreamdefaultreader)<`R`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11982

___

### pipeThrough

▸ **pipeThrough**<`T`\>(`transform`, `options?`): [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `transform` | [`ReadableWritablePair`](akashaproject_ui_app_loader._internal_.ReadableWritablePair.md)<`T`, `R`\> |
| `options?` | [`StreamPipeOptions`](akashaproject_ui_app_loader._internal_.StreamPipeOptions.md) |

#### Returns

[`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`T`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11983

___

### pipeTo

▸ **pipeTo**(`destination`, `options?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `destination` | [`WritableStream`](../modules/akashaproject_ui_app_loader._internal_.md#writablestream)<`R`\> |
| `options?` | [`StreamPipeOptions`](akashaproject_ui_app_loader._internal_.StreamPipeOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11984

___

### tee

▸ **tee**(): [[`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`R`\>, [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`R`\>]

#### Returns

[[`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`R`\>, [`ReadableStream`](../modules/akashaproject_ui_app_loader._internal_.md#readablestream)<`R`\>]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11985
