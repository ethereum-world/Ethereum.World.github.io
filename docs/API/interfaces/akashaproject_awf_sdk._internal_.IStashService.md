[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / IStashService

# Interface: IStashService<IStash\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).IStashService

## Type parameters

| Name |
| :------ |
| `IStash` |

## Implemented by

- [`Stash`](../classes/akashaproject_awf_sdk._internal_.Stash.md)

## Table of contents

### Methods

- [computeKey](akashaproject_awf_sdk._internal_.IStashService.md#computekey)
- [create](akashaproject_awf_sdk._internal_.IStashService.md#create)
- [getUiStash](akashaproject_awf_sdk._internal_.IStashService.md#getuistash)

## Methods

### computeKey

▸ **computeKey**(`objKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `objKey` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> |

#### Returns

`string`

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:9

___

### create

▸ **create**(`args`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`IStash`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | [`LRUOptions`](akashaproject_awf_sdk._internal_.LRUOptions.md) |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`IStash`\>

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:7

___

### getUiStash

▸ **getUiStash**(): `IStash`

#### Returns

`IStash`

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:8
