[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBTransaction

# Interface: IDBTransaction

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBTransaction

## Hierarchy

- `EventTarget`

  ↳ **`IDBTransaction`**

## Table of contents

### Properties

- [db](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#db)
- [error](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#error)
- [mode](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#mode)
- [objectStoreNames](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#objectstorenames)
- [onabort](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#onabort)
- [oncomplete](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#oncomplete)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#onerror)

### Methods

- [abort](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#abort)
- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#addeventlistener)
- [commit](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#commit)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#dispatchevent)
- [objectStore](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#objectstore)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBTransaction.md#removeeventlistener)

## Properties

### db

• `Readonly` **db**: [`IDBDatabase`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbdatabase)

Returns the transaction's connection.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9380

___

### error

• `Readonly` **error**: [`DOMException`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domexception)

If the transaction was aborted, returns the error (a DOMException) providing the reason.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9384

___

### mode

• `Readonly` **mode**: [`IDBTransactionMode`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransactionmode)

Returns the mode the transaction was created with ("readonly" or "readwrite"), or "versionchange" for an upgrade transaction.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9388

___

### objectStoreNames

• `Readonly` **objectStoreNames**: [`DOMStringList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domstringlist)

Returns a list of the names of object stores in the transaction's scope. For an upgrade transaction this is all object stores in the database.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9392

___

### onabort

• **onabort**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9393

___

### oncomplete

• **oncomplete**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9394

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

node_modules/typescript/lib/lib.dom.d.ts:9395

## Methods

### abort

▸ **abort**(): `void`

Aborts the transaction. All pending requests will fail with a "AbortError" DOMException and all changes made to the database will be reverted.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9399

___

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBTransactionEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBTransactionEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBTransactionEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBTransactionEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9405

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

node_modules/typescript/lib/lib.dom.d.ts:9406

___

### commit

▸ **commit**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9400

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

### objectStore

▸ **objectStore**(`name`): [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore)

Returns an IDBObjectStore in the transaction's scope.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9404

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBTransactionEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBTransactionEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBTransactionEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBTransactionEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9407

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

node_modules/typescript/lib/lib.dom.d.ts:9408
