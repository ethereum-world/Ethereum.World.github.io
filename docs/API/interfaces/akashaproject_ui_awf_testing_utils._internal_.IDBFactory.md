[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBFactory

# Interface: IDBFactory

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBFactory

In the following code snippet, we make a request to open a database, and include handlers for the success and error cases. For a full working example, see our To-do Notifications app (view example live.)

## Table of contents

### Methods

- [cmp](akashaproject_ui_awf_testing_utils._internal_.IDBFactory.md#cmp)
- [databases](akashaproject_ui_awf_testing_utils._internal_.IDBFactory.md#databases)
- [deleteDatabase](akashaproject_ui_awf_testing_utils._internal_.IDBFactory.md#deletedatabase)
- [open](akashaproject_ui_awf_testing_utils._internal_.IDBFactory.md#open)

## Methods

### cmp

▸ **cmp**(`first`, `second`): `number`

Compares two values as keys. Returns -1 if key1 precedes key2, 1 if key2 precedes key1, and 0 if the keys are equal.

Throws a "DataError" DOMException if either input is not a valid key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | `any` |
| `second` | `any` |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9070

___

### databases

▸ **databases**(): `Promise`<[`IDBDatabaseInfo`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseInfo.md)[]\>

#### Returns

`Promise`<[`IDBDatabaseInfo`](akashaproject_ui_awf_testing_utils._internal_.IDBDatabaseInfo.md)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9071

___

### deleteDatabase

▸ **deleteDatabase**(`name`): [`IDBOpenDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbopendbrequest)

Attempts to delete the named database. If the database already exists and there are open connections that don't close in response to a versionchange event, the request will be blocked until all they close. If the request is successful request's result will be null.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`IDBOpenDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbopendbrequest)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9075

___

### open

▸ **open**(`name`, `version?`): [`IDBOpenDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbopendbrequest)

Attempts to open a connection to the named database with the current version, or 1 if it does not already exist. If the request is successful request's result will be the connection.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `version?` | `number` |

#### Returns

[`IDBOpenDBRequest`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbopendbrequest)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9079
