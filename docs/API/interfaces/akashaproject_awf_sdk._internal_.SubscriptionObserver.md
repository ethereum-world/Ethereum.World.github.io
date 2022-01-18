[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / SubscriptionObserver

# Interface: SubscriptionObserver<T\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).SubscriptionObserver

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Properties

- [closed](akashaproject_awf_sdk._internal_.SubscriptionObserver.md#closed)

### Methods

- [complete](akashaproject_awf_sdk._internal_.SubscriptionObserver.md#complete)
- [error](akashaproject_awf_sdk._internal_.SubscriptionObserver.md#error)
- [next](akashaproject_awf_sdk._internal_.SubscriptionObserver.md#next)

## Properties

### closed

• **closed**: `boolean`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:7

## Methods

### complete

▸ **complete**(): `void`

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:10

___

### error

▸ **error**(`errorValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `errorValue` | `any` |

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:9

___

### next

▸ **next**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `T` |

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:8
