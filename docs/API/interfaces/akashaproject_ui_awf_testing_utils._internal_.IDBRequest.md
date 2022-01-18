[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBRequest

# Interface: IDBRequest<T\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBRequest

The request object does not initially contain any information about the result of the operation, but once information becomes available, an event is fired on the request, and the information becomes available through the properties of the IDBRequest instance.

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `any` |

## Hierarchy

- `EventTarget`

  ↳ **`IDBRequest`**

## Table of contents

### Properties

- [error](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#error)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#onerror)
- [onsuccess](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#onsuccess)
- [readyState](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#readystate)
- [result](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#result)
- [source](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#source)
- [transaction](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#transaction)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBRequest.md#removeeventlistener)

## Properties

### error

• `Readonly` **error**: [`DOMException`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domexception)

When a request is completed, returns the error (a DOMException), or null if the request succeeded. Throws a "InvalidStateError" DOMException if the request is still pending.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9340

___

### onerror

• **onerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9341

___

### onsuccess

• **onsuccess**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9342

___

### readyState

• `Readonly` **readyState**: [`IDBRequestReadyState`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequestreadystate)

Returns "pending" until a request is complete, then returns "done".

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9346

___

### result

• `Readonly` **result**: `T`

When a request is completed, returns the result, or undefined if the request failed. Throws a "InvalidStateError" DOMException if the request is still pending.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9350

___

### source

• `Readonly` **source**: [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore) \| [`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex) \| [`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)

Returns the IDBObjectStore, IDBIndex, or IDBCursor the request was made against, or null if is was an open request.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9354

___

### transaction

• `Readonly` **transaction**: [`IDBTransaction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransaction)

Returns the IDBTransaction the request was made within. If this as an open request, then it returns an upgrade transaction while it is running, or null otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9358

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBRequestEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBRequestEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9359

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9360

___

### dispatchEvent

▸ **dispatchEvent**(`event`): `boolean`

Dispatches a synthetic event event to target and returns true if either event's cancelable attribute value is false or its preventDefault() method was not invoked, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`boolean`

#### Inherited from

EventTarget.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBRequestEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBRequestEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9361

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9362
