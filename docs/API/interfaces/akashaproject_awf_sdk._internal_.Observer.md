[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Observer

# Interface: Observer<T\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Observer

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Methods

- [complete](akashaproject_awf_sdk._internal_.Observer.md#complete)
- [error](akashaproject_awf_sdk._internal_.Observer.md#error)
- [next](akashaproject_awf_sdk._internal_.Observer.md#next)
- [start](akashaproject_awf_sdk._internal_.Observer.md#start)

## Methods

### complete

▸ `Optional` **complete**(): `void`

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:17

___

### error

▸ `Optional` **error**(`errorValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `errorValue` | `any` |

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:16

___

### next

▸ `Optional` **next**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `T` |

#### Returns

`void`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:15

___

### start

▸ `Optional` **start**(`subscription`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `subscription` | [`Subscription`](akashaproject_awf_sdk._internal_.Subscription.md) |

#### Returns

`any`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:14
