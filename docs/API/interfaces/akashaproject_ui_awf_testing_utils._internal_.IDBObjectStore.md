[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBObjectStore

# Interface: IDBObjectStore

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBObjectStore

This example shows a variety of different uses of object stores, from updating the data structure with IDBObjectStore.createIndex inside an onupgradeneeded function, to adding a new item to our object store with IDBObjectStore.add. For a full working example, see our To-do Notifications app (view example live.)

## Table of contents

### Properties

- [autoIncrement](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#autoincrement)
- [indexNames](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#indexnames)
- [keyPath](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#keypath)
- [name](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#name)
- [transaction](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#transaction)

### Methods

- [add](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#add)
- [clear](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#clear)
- [count](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#count)
- [createIndex](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#createindex)
- [delete](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#delete)
- [deleteIndex](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#deleteindex)
- [get](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#get)
- [getAll](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#getall)
- [getAllKeys](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#getallkeys)
- [getKey](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#getkey)
- [index](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#index)
- [openCursor](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#opencursor)
- [openKeyCursor](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#openkeycursor)
- [put](akashaproject_ui_awf_testing_utils._internal_.IDBObjectStore.md#put)

## Properties

### autoIncrement

• `Readonly` **autoIncrement**: `boolean`

Returns true if the store has a key generator, and false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9199

___

### indexNames

• `Readonly` **indexNames**: [`DOMStringList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domstringlist)

Returns a list of the names of indexes in the store.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9203

___

### keyPath

• `Readonly` **keyPath**: `string` \| `string`[]

Returns the key path of the store, or null if none.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9207

___

### name

• **name**: `string`

Returns the name of the store.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9211

___

### transaction

• `Readonly` **transaction**: [`IDBTransaction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbtransaction)

Returns the associated transaction.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9215

## Methods

### add

▸ **add**(`value`, `key?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

Adds or updates a record in store with the given value and key.

If the store uses in-line keys and key is specified a "DataError" DOMException will be thrown.

If put() is used, any existing record with the key will be replaced. If add() is used, and if a record with the key already exists the request will fail, with request's error set to a "ConstraintError" DOMException.

If successful, request's result will be the record's key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `key?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9225

___

### clear

▸ **clear**(): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

Deletes all records in store.

If successful, request's result will be undefined.

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9231

___

### count

▸ **count**(`query?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`number`\>

Retrieves the number of records matching the given key or key range in query.

If successful, request's result will be the count.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`number`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9237

___

### createIndex

▸ **createIndex**(`name`, `keyPath`, `options?`): [`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex)

Creates a new index in store with the given name, keyPath and options and returns a new IDBIndex. If the keyPath and options define constraints that cannot be satisfied with the data already in store the upgrade transaction will abort with a "ConstraintError" DOMException.

Throws an "InvalidStateError" DOMException if not called within an upgrade transaction.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `keyPath` | `string` \| `string`[] |
| `options?` | [`IDBIndexParameters`](akashaproject_ui_awf_testing_utils._internal_.IDBIndexParameters.md) |

#### Returns

[`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9243

___

### delete

▸ **delete**(`query`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

Deletes records in store with the given key or in the given key range in query.

If successful, request's result will be undefined.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9249

___

### deleteIndex

▸ **deleteIndex**(`name`): `void`

Deletes the index in store with the given name.

Throws an "InvalidStateError" DOMException if not called within an upgrade transaction.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9255

___

### get

▸ **get**(`query`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`any`\>

Retrieves the value of the first record matching the given key or key range in query.

If successful, request's result will be the value, or undefined if there was no matching record.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9261

___

### getAll

▸ **getAll**(`query?`, `count?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`any`[]\>

Retrieves the values of the records matching the given key or key range in query (up to count if given).

If successful, request's result will be an Array of the values.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `count?` | `number` |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`any`[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9267

___

### getAllKeys

▸ **getAllKeys**(`query?`, `count?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)[]\>

Retrieves the keys of records matching the given key or key range in query (up to count if given).

If successful, request's result will be an Array of the keys.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `count?` | `number` |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9273

___

### getKey

▸ **getKey**(`query`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

Retrieves the key of the first record matching the given key or key range in query.

If successful, request's result will be the key, or undefined if there was no matching record.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9279

___

### index

▸ **index**(`name`): [`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9280

___

### openCursor

▸ **openCursor**(`query?`, `direction?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursorWithValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursorwithvalue)\>

Opens a cursor over the records matching query, ordered by direction. If query is null, all records in store are matched.

If successful, request's result will be an IDBCursorWithValue pointing at the first matching record, or null if there were no matching records.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `direction?` | [`IDBCursorDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursordirection) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursorWithValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursorwithvalue)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9286

___

### openKeyCursor

▸ **openKeyCursor**(`query?`, `direction?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)\>

Opens a cursor with key only flag set over the records matching query, ordered by direction. If query is null, all records in store are matched.

If successful, request's result will be an IDBCursor pointing at the first matching record, or null if there were no matching records.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `direction?` | [`IDBCursorDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursordirection) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9292

___

### put

▸ **put**(`value`, `key?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

Adds or updates a record in store with the given value and key.

If the store uses in-line keys and key is specified a "DataError" DOMException will be thrown.

If put() is used, any existing record with the key will be replaced. If add() is used, and if a record with the key already exists the request will fail, with request's error set to a "ConstraintError" DOMException.

If successful, request's result will be the record's key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `key?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9302
