[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / IDBService

# Interface: IDBService<DB, Collection\>

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).IDBService

## Type parameters

| Name |
| :------ |
| `DB` |
| `Collection` |

## Table of contents

### Methods

- [getCollection](akashaproject_sdk_typings._internal_.IDBService.md#getcollection)
- [getDb](akashaproject_sdk_typings._internal_.IDBService.md#getdb)
- [open](akashaproject_sdk_typings._internal_.IDBService.md#open)

## Methods

### getCollection

▸ **getCollection**(`name`): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`Collection`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`Collection`\>

#### Defined in

[sdk/typings/src/interfaces/db.ts:6](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/db.ts#L6)

___

### getDb

▸ **getDb**(): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`DB`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`DB`\>

#### Defined in

[sdk/typings/src/interfaces/db.ts:5](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/db.ts#L5)

___

### open

▸ **open**(`version`): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`DB`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `version` | `number` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`DB`\>

#### Defined in

[sdk/typings/src/interfaces/db.ts:4](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/db.ts#L4)
