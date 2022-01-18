[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / DB

# Class: DB

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).DB

## Implements

- [`IDBService`](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md)<`Database`, `Collection`\>

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.DB.md#constructor)

### Methods

- [create](akashaproject_ui_app_loader._internal_.DB.md#create)
- [getCollection](akashaproject_ui_app_loader._internal_.DB.md#getcollection)
- [getDb](akashaproject_ui_app_loader._internal_.DB.md#getdb)
- [open](akashaproject_ui_app_loader._internal_.DB.md#open)

## Constructors

### constructor

• **new DB**()

## Methods

### create

▸ **create**(`name`): `Database`

Create a new DB instance

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | database name |

#### Returns

`Database`

Database

#### Defined in

[sdk/src/db/index.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/db/index.ts#L26)

___

### getCollection

▸ **getCollection**(`name`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Collection`<`unknown`\>\>

Get access to the db collection by name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | string representing the collection name |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Collection`<`unknown`\>\>

ServiceCallResult<Collection>

#### Implementation of

[IDBService](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md).[getCollection](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md#getcollection)

#### Defined in

[sdk/src/db/index.ts:63](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/db/index.ts#L63)

___

### getDb

▸ **getDb**(): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Database`\>

Get access to the local db

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Database`\>

ServiceCallResult<Database>

#### Implementation of

[IDBService](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md).[getDb](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md#getdb)

#### Defined in

[sdk/src/db/index.ts:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/db/index.ts#L53)

___

### open

▸ **open**(`version?`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Database`\>

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `version` | `number` | `1` | number representing the db version |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`Database`\>

ServiceCallResult<Database>

#### Implementation of

[IDBService](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md).[open](../interfaces/akashaproject_ui_app_loader._internal_.IDBService.md#open)

#### Defined in

[sdk/src/db/index.ts:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/db/index.ts#L37)
