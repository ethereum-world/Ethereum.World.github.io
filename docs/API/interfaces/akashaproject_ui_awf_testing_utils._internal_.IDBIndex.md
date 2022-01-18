[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBIndex

# Interface: IDBIndex

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBIndex

IDBIndex interface of the IndexedDB API provides asynchronous access to an index in a database. An index is a kind of object store for looking up records in another object store, called the referenced object store. You use this interface to retrieve data.

## Table of contents

### Properties

- [keyPath](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#keypath)
- [multiEntry](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#multientry)
- [name](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#name)
- [objectStore](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#objectstore)
- [unique](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#unique)

### Methods

- [count](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#count)
- [get](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#get)
- [getAll](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#getall)
- [getAllKeys](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#getallkeys)
- [getKey](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#getkey)
- [openCursor](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#opencursor)
- [openKeyCursor](akashaproject_ui_awf_testing_utils._internal_.IDBIndex.md#openkeycursor)

## Properties

### keyPath

• `Readonly` **keyPath**: `string` \| `string`[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9089

___

### multiEntry

• `Readonly` **multiEntry**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9090

___

### name

• **name**: `string`

Returns the name of the index.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9094

___

### objectStore

• `Readonly` **objectStore**: [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore)

Returns the IDBObjectStore the index belongs to.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9098

___

### unique

• `Readonly` **unique**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9099

## Methods

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

node_modules/typescript/lib/lib.dom.d.ts:9105

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

node_modules/typescript/lib/lib.dom.d.ts:9111

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

node_modules/typescript/lib/lib.dom.d.ts:9117

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

node_modules/typescript/lib/lib.dom.d.ts:9123

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

node_modules/typescript/lib/lib.dom.d.ts:9129

___

### openCursor

▸ **openCursor**(`query?`, `direction?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursorWithValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursorwithvalue)\>

Opens a cursor over the records matching query, ordered by direction. If query is null, all records in index are matched.

If successful, request's result will be an IDBCursorWithValue, or null if there were no matching records.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `direction?` | [`IDBCursorDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursordirection) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursorWithValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursorwithvalue)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9135

___

### openKeyCursor

▸ **openKeyCursor**(`query?`, `direction?`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)\>

Opens a cursor with key only flag set over the records matching query, ordered by direction. If query is null, all records in index are matched.

If successful, request's result will be an IDBCursor, or null if there were no matching records.

#### Parameters

| Name | Type |
| :------ | :------ |
| `query?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) \| [`IDBKeyRange`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbkeyrange) |
| `direction?` | [`IDBCursorDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursordirection) |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBCursor`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursor)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9141
