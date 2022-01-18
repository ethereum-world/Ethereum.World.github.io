[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Stash

# Class: Stash

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Stash

## Implements

- [`IStashService`](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md)<[`IQuickLRU`](../modules/akashaproject_ui_app_loader._internal_.md#iquicklru)\>

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Stash.md#constructor)

### Methods

- [computeKey](akashaproject_ui_app_loader._internal_.Stash.md#computekey)
- [create](akashaproject_ui_app_loader._internal_.Stash.md#create)
- [getUiStash](akashaproject_ui_app_loader._internal_.Stash.md#getuistash)

## Constructors

### constructor

• **new Stash**()

## Methods

### computeKey

▸ **computeKey**(`objKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `objKey` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`never`, `unknown`\> |

#### Returns

`string`

#### Implementation of

[IStashService](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md).[computeKey](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md#computekey)

#### Defined in

[sdk/src/stash/index.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/stash/index.ts#L32)

___

### create

▸ **create**(`args`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<[`IQuickLRU`](../modules/akashaproject_ui_app_loader._internal_.md#iquicklru)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `args` | [`LRUOptions`](../interfaces/akashaproject_ui_app_loader._internal_.LRUOptions.md) | Object with props maxSize: number and maxAge: number |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<[`IQuickLRU`](../modules/akashaproject_ui_app_loader._internal_.md#iquicklru)\>

a new instance of QuickLRU

#### Implementation of

[IStashService](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md).[create](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md#create)

#### Defined in

[sdk/src/stash/index.ts:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/stash/index.ts#L17)

___

### getUiStash

▸ **getUiStash**(): [`default`](akashaproject_ui_app_loader._internal_.default.md)<`string`, `unknown`\>

General purpose stash for caching ui related data

#### Returns

[`default`](akashaproject_ui_app_loader._internal_.default.md)<`string`, `unknown`\>

#### Implementation of

[IStashService](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md).[getUiStash](../interfaces/akashaproject_ui_app_loader._internal_.IStashService.md#getuistash)

#### Defined in

[sdk/src/stash/index.ts:25](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/stash/index.ts#L25)
