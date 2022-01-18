[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBOpenDBRequest

# Interface: IDBOpenDBRequest

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBOpenDBRequest

Also inherits methods from its parents IDBRequest and EventTarget.

## Hierarchy

- [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBDatabase`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbdatabase)\>

  ↳ **`IDBOpenDBRequest`**

## Table of contents

### Properties

- [error](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#error)
- [onblocked](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#onblocked)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#onerror)
- [onsuccess](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#onsuccess)
- [onupgradeneeded](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#onupgradeneeded)
- [readyState](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#readystate)
- [result](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#result)
- [source](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#source)
- [transaction](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#transaction)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequest.md#removeeventlistener)

## Properties

### error

• `Readonly` **error**: [`DOMException`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domexception)

When a request is completed, returns the error (a DOMException), or null if the request succeeded. Throws a "InvalidStateError" DOMException if the request is still pending.

#### Inherited from

IDBRequest.error

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9340

___

### onblocked

• **onblocked**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9317

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

#### Inherited from

IDBRequest.onerror

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

#### Inherited from

IDBRequest.onsuccess

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9342

___

### onupgradeneeded

• **onupgradeneeded**: (`ev`: [`IDBVersionChangeEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbversionchangeevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`IDBVersionChangeEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbversionchangeevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9318

___

### readyState

• `Readonly` **readyState**: [`IDBRequestReadyState`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequestreadystate)

Returns "pending" until a request is complete, then returns "done".

#### Inherited from

IDBRequest.readyState

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9346

___

### result

• `Readonly` **result**: [`IDBDatabase`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbdatabase)

When a request is completed, returns the result, or undefined if the request failed. Throws a "InvalidStateError" DOMException if the request is still pending.

#### Inherited from

IDBRequest.result

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9350

___

### source

• `Readonly` **source**: [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore) \| [`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex) \| [`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)

Returns the IDBObjectStore, IDBIndex, or IDBCursor the request was made against, or null if is was an open request.

#### Inherited from

IDBRequest.source

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9354

___

### transaction

• `Readonly` **transaction**: [`IDBTransaction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransaction)

Returns the IDBTransaction the request was made within. If this as an open request, then it returns an upgrade transaction while it is running, or null otherwise.

#### Inherited from

IDBRequest.transaction

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9358

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBOpenDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequestEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBOpenDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequestEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

IDBRequest.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9319

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

IDBRequest.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9320

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

IDBRequest.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBOpenDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequestEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBOpenDBRequestEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBOpenDBRequestEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

IDBRequest.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9321

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

IDBRequest.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9322
