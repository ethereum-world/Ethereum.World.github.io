[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Observer

# Interface: Observer<T\>

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Observer

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Methods

- [complete](akashaproject_ui_app_loader._internal_.Observer.md#complete)
- [error](akashaproject_ui_app_loader._internal_.Observer.md#error)
- [next](akashaproject_ui_app_loader._internal_.Observer.md#next)
- [start](akashaproject_ui_app_loader._internal_.Observer.md#start)

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
| `subscription` | [`Subscription`](akashaproject_ui_app_loader._internal_.Subscription.md) |

#### Returns

`any`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:14
