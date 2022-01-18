[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBCursor

# Interface: IDBCursor

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBCursor

This IndexedDB API interface represents a cursor for traversing or iterating over multiple records in a database.

## Table of contents

### Properties

- [direction](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#direction)
- [key](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#key)
- [primaryKey](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#primarykey)
- [request](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#request)
- [source](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#source)

### Methods

- [advance](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#advance)
- [continue](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#continue)
- [continuePrimaryKey](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#continueprimarykey)
- [delete](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#delete)
- [update](akashaproject_ui_awf_testing_utils._internal_.IDBCursor.md#update)

## Properties

### direction

• `Readonly` **direction**: [`IDBCursorDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbcursordirection)

Returns the direction ("next", "nextunique", "prev" or "prevunique") of the cursor.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8947

___

### key

• `Readonly` **key**: [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)

Returns the key of the cursor. Throws a "InvalidStateError" DOMException if the cursor is advancing or is finished.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8951

___

### primaryKey

• `Readonly` **primaryKey**: [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)

Returns the effective key of the cursor. Throws a "InvalidStateError" DOMException if the cursor is advancing or is finished.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8955

___

### request

• `Readonly` **request**: [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8956

___

### source

• `Readonly` **source**: [`IDBObjectStore`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbobjectstore) \| [`IDBIndex`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbindex)

Returns the IDBObjectStore or IDBIndex the cursor was opened from.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8960

## Methods

### advance

▸ **advance**(`count`): `void`

Advances the cursor through the next count records in range.

#### Parameters

| Name | Type |
| :------ | :------ |
| `count` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8964

___

### continue

▸ **continue**(`key?`): `void`

Advances the cursor to the next record in range.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key?` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8968

___

### continuePrimaryKey

▸ **continuePrimaryKey**(`key`, `primaryKey`): `void`

Advances the cursor to the next record in range matching or after key and primaryKey. Throws an "InvalidAccessError" DOMException if the source is not an index.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) |
| `primaryKey` | [`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8972

___

### delete

▸ **delete**(): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

Delete the record pointed at by the cursor with a new value.

If successful, request's result will be undefined.

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<`undefined`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8978

___

### update

▸ **update**(`value`): [`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

Updated the record pointed at by the cursor with a new value.

Throws a "DataError" DOMException if the effective object store uses in-line keys and the key would have changed.

If successful, request's result will be the record's key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`IDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbrequest)<[`IDBValidKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbvalidkey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8986
