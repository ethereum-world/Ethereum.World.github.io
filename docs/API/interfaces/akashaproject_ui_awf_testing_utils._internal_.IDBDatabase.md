[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBDatabase

# Interface: IDBDatabase

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBDatabase

This IndexedDB API interface provides a connection to a database; you can use an IDBDatabase object to open a transaction on your database then create, manipulate, and delete objects (data) in that database. The interface provides the only way to get and manage versions of the database.

## Hierarchy

- `EventTarget`

  ↳ **`IDBDatabase`**

## Table of contents

### Properties

- [name](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#name)
- [objectStoreNames](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#objectstorenames)
- [onabort](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#onabort)
- [onclose](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#onclose)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#onerror)
- [onversionchange](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#onversionchange)
- [version](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#version)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#addeventlistener)
- [close](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#close)
- [createObjectStore](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#createobjectstore)
- [deleteObjectStore](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#deleteobjectstore)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#removeeventlistener)
- [transaction](akashaproject_ui_awf_testing_utils._internal_.IDBDatabase.md#transaction)

## Properties

### name

• `Readonly` **name**: `string`

Returns the name of the database.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9019

___

### objectStoreNames

• `Readonly` **objectStoreNames**: [`DOMStringList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domstringlist)

Returns a list of the names of object stores in the database.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9023

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

node_modules/typescript/lib/lib.dom.d.ts:9024

___

### onclose

• **onclose**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9025

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

node_modules/typescript/lib/lib.dom.d.ts:9026

___

### onversionchange

• **onversionchange**: (`ev`: [`IDBVersionChangeEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbversionchangeevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`IDBVersionChangeEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbversionchangeevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9027

___

### version

• `Readonly` **version**: `number`

Returns the version of the database.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9031

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`IDBDatabaseEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBDatabaseEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9052

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

node_modules/typescript/lib/lib.dom.d.ts:9053

___

### close

▸ **close**(): `void`

Closes the connection once all running transactions have finished.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9035

___

### createObjectStore

▸ **createObjectStore**(`name`, `options?`): [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore)

Creates a new object store with the given name and options and returns a new IDBObjectStore.

Throws a "InvalidStateError" DOMException if not called within an upgrade transaction.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `options?` | [`IDBObjectStoreParameters`](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStoreParameters.md) |

#### Returns

[`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9041

___

### deleteObjectStore

▸ **deleteObjectStore**(`name`): `void`

Deletes the object store with the given name.

Throws a "InvalidStateError" DOMException if not called within an upgrade transaction.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9047

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
| `K` | extends keyof [`IDBDatabaseEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`IDBDatabaseEventMap`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9054

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

node_modules/typescript/lib/lib.dom.d.ts:9055

___

### transaction

▸ **transaction**(`storeNames`, `mode?`): [`IDBTransaction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransaction)

Returns a new transaction with the given mode ("readonly" or "readwrite") and scope which can be a single object store name or an array of names.

#### Parameters

| Name | Type |
| :------ | :------ |
| `storeNames` | `string` \| `string`[] |
| `mode?` | [`IDBTransactionMode`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransactionmode) |

#### Returns

[`IDBTransaction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransaction)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9051
