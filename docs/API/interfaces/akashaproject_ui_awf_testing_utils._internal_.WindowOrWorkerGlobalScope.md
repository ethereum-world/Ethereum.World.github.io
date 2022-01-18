[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / WindowOrWorkerGlobalScope

# Interface: WindowOrWorkerGlobalScope

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).WindowOrWorkerGlobalScope

## Hierarchy

- **`WindowOrWorkerGlobalScope`**

  ↳ [`Window`](akashaproject_ui_awf_testing_utils._internal_.Window.md)

## Table of contents

### Properties

- [caches](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#caches)
- [crossOriginIsolated](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#crossoriginisolated)
- [crypto](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#crypto)
- [indexedDB](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#indexeddb)
- [isSecureContext](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#issecurecontext)
- [origin](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#origin)
- [performance](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#performance)

### Methods

- [atob](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#atob)
- [btoa](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#btoa)
- [clearInterval](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#clearinterval)
- [clearTimeout](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#cleartimeout)
- [createImageBitmap](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#createimagebitmap)
- [fetch](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#fetch)
- [queueMicrotask](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#queuemicrotask)
- [setInterval](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#setinterval)
- [setTimeout](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#settimeout)

## Properties

### caches

• `Readonly` **caches**: [`CacheStorage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cachestorage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17402

___

### crossOriginIsolated

• `Readonly` **crossOriginIsolated**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17403

___

### crypto

• `Readonly` **crypto**: [`Crypto`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#crypto)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17404

___

### indexedDB

• `Readonly` **indexedDB**: [`IDBFactory`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbfactory)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17405

___

### isSecureContext

• `Readonly` **isSecureContext**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17406

___

### origin

• `Readonly` **origin**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17407

___

### performance

• `Readonly` **performance**: [`Performance`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performance)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17408

## Methods

### atob

▸ **atob**(`data`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17409

___

### btoa

▸ **btoa**(`data`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17410

___

### clearInterval

▸ **clearInterval**(`handle?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17411

___

### clearTimeout

▸ **clearTimeout**(`handle?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17412

___

### createImageBitmap

▸ **createImageBitmap**(`image`, `options?`): `Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `image` | [`ImageBitmapSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmapsource) |
| `options?` | [`ImageBitmapOptions`](akashaproject_ui_awf_testing_utils._internal_.ImageBitmapOptions.md) |

#### Returns

`Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17413

▸ **createImageBitmap**(`image`, `sx`, `sy`, `sw`, `sh`, `options?`): `Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `image` | [`ImageBitmapSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmapsource) |
| `sx` | `number` |
| `sy` | `number` |
| `sw` | `number` |
| `sh` | `number` |
| `options?` | [`ImageBitmapOptions`](akashaproject_ui_awf_testing_utils._internal_.ImageBitmapOptions.md) |

#### Returns

`Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17414

___

### fetch

▸ **fetch**(`input`, `init?`): `Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `input` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `init?` | [`RequestInit`](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md) |

#### Returns

`Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17415

___

### queueMicrotask

▸ **queueMicrotask**(`callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | [`VoidFunction`](akashaproject_ui_awf_testing_utils._internal_.VoidFunction.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17416

___

### setInterval

▸ **setInterval**(`handler`, `timeout?`, ...`arguments`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | [`TimerHandler`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#timerhandler) |
| `timeout?` | `number` |
| `...arguments` | `any`[] |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17417

___

### setTimeout

▸ **setTimeout**(`handler`, `timeout?`, ...`arguments`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | [`TimerHandler`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#timerhandler) |
| `timeout?` | `number` |
| `...arguments` | `any`[] |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17418
