[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / IDBService

# Interface: IDBService<DB, Collection\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).IDBService

## Type parameters

| Name |
| :------ |
| `DB` |
| `Collection` |

## Implemented by

- [`DB`](../classes/akashaproject_awf_sdk._internal_.DB.md)

## Table of contents

### Methods

- [getCollection](akashaproject_awf_sdk._internal_.IDBService.md#getcollection)
- [getDb](akashaproject_awf_sdk._internal_.IDBService.md#getdb)
- [open](akashaproject_awf_sdk._internal_.IDBService.md#open)

## Methods

### getCollection

▸ **getCollection**(`name`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`Collection`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`Collection`\>

#### Defined in

sdk/typings/lib/interfaces/db.d.ts:5

___

### getDb

▸ **getDb**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`DB`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`DB`\>

#### Defined in

sdk/typings/lib/interfaces/db.d.ts:4

___

### open

▸ **open**(`version`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`DB`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `version` | `number` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`DB`\>

#### Defined in

sdk/typings/lib/interfaces/db.d.ts:3
