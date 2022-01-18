[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / IStashService

# Interface: IStashService<IStash\>

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).IStashService

## Type parameters

| Name |
| :------ |
| `IStash` |

## Implemented by

- [`Stash`](../classes/akashaproject_ui_app_loader._internal_.Stash.md)

## Table of contents

### Methods

- [computeKey](akashaproject_ui_app_loader._internal_.IStashService.md#computekey)
- [create](akashaproject_ui_app_loader._internal_.IStashService.md#create)
- [getUiStash](akashaproject_ui_app_loader._internal_.IStashService.md#getuistash)

## Methods

### computeKey

▸ **computeKey**(`objKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `objKey` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `unknown`\> |

#### Returns

`string`

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:9

___

### create

▸ **create**(`args`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`IStash`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | [`LRUOptions`](akashaproject_ui_app_loader._internal_.LRUOptions.md) |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`IStash`\>

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:7

___

### getUiStash

▸ **getUiStash**(): `IStash`

#### Returns

`IStash`

#### Defined in

sdk/typings/lib/interfaces/stash.d.ts:8
