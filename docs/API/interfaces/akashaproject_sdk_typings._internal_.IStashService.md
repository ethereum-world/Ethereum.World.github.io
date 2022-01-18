[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / IStashService

# Interface: IStashService<IStash\>

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).IStashService

## Type parameters

| Name |
| :------ |
| `IStash` |

## Table of contents

### Methods

- [computeKey](akashaproject_sdk_typings._internal_.IStashService.md#computekey)
- [create](akashaproject_sdk_typings._internal_.IStashService.md#create)
- [getUiStash](akashaproject_sdk_typings._internal_.IStashService.md#getuistash)

## Methods

### computeKey

▸ **computeKey**(`objKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `objKey` | [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\> |

#### Returns

`string`

#### Defined in

[sdk/typings/src/interfaces/stash.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/stash.ts#L12)

___

### create

▸ **create**(`args`): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`IStash`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | [`LRUOptions`](akashaproject_sdk_typings._internal_.LRUOptions.md) |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`IStash`\>

#### Defined in

[sdk/typings/src/interfaces/stash.ts:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/stash.ts#L10)

___

### getUiStash

▸ **getUiStash**(): `IStash`

#### Returns

`IStash`

#### Defined in

[sdk/typings/src/interfaces/stash.ts:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/stash.ts#L11)
