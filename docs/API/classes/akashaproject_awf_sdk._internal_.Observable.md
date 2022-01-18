[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Observable

# Class: Observable<T\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Observable

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Observable.md#constructor)

### Methods

- [[observable]](akashaproject_awf_sdk._internal_.Observable.md#[observable])
- [concat](akashaproject_awf_sdk._internal_.Observable.md#concat)
- [filter](akashaproject_awf_sdk._internal_.Observable.md#filter)
- [flatMap](akashaproject_awf_sdk._internal_.Observable.md#flatmap)
- [forEach](akashaproject_awf_sdk._internal_.Observable.md#foreach)
- [map](akashaproject_awf_sdk._internal_.Observable.md#map)
- [reduce](akashaproject_awf_sdk._internal_.Observable.md#reduce)
- [subscribe](akashaproject_awf_sdk._internal_.Observable.md#subscribe)
- [apply](akashaproject_awf_sdk._internal_.Observable.md#apply)
- [call](akashaproject_awf_sdk._internal_.Observable.md#call)
- [from](akashaproject_awf_sdk._internal_.Observable.md#from)
- [of](akashaproject_awf_sdk._internal_.Observable.md#of)

## Constructors

### constructor

• **new Observable**<`T`\>(`subscriber`)

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `subscriber` | [`Subscriber`](../modules/akashaproject_awf_sdk._internal_.md#subscriber)<`T`\> |

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:30

## Methods

### [observable]

▸ **[observable]**(): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:45

___

### concat

▸ **concat**<`R`\>(...`observable`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...observable` | [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>[] |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:54

___

### filter

▸ **filter**<`S`\>(`callback`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`S`\>

#### Type parameters

| Name |
| :------ |
| `S` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`value`: `T`) => value is S |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`S`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:49

▸ **filter**(`callback`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`value`: `T`) => `boolean` |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:50

___

### flatMap

▸ **flatMap**<`R`\>(`callback`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`value`: `T`) => [`ObservableLike`](../interfaces/akashaproject_awf_sdk._internal_.ObservableLike.md)<`R`\> |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:53

___

### forEach

▸ **forEach**(`callback`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`value`: `T`) => `void` |

#### Returns

`Promise`<`void`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:47

___

### map

▸ **map**<`R`\>(`callback`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`value`: `T`) => `R` |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:48

___

### reduce

▸ **reduce**(`callback`, `initialValue?`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`previousValue`: `T`, `currentValue`: `T`) => `T` |
| `initialValue?` | `T` |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`T`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:51

▸ **reduce**<`R`\>(`callback`, `initialValue?`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`previousValue`: `R`, `currentValue`: `T`) => `R` |
| `initialValue?` | `R` |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:52

___

### subscribe

▸ **subscribe**(`observer`): [`Subscription`](../interfaces/akashaproject_awf_sdk._internal_.Subscription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `observer` | [`Observer`](../interfaces/akashaproject_awf_sdk._internal_.Observer.md)<`T`\> |

#### Returns

[`Subscription`](../interfaces/akashaproject_awf_sdk._internal_.Subscription.md)

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:38

▸ **subscribe**(`onNext`, `onError?`, `onComplete?`): [`Subscription`](../interfaces/akashaproject_awf_sdk._internal_.Subscription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `onNext` | (`value`: `T`) => `void` |
| `onError?` | (`error`: `any`) => `void` |
| `onComplete?` | () => `void` |

#### Returns

[`Subscription`](../interfaces/akashaproject_awf_sdk._internal_.Subscription.md)

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:39

___

### apply

▸ `Static` **apply**<`R`\>(`instance`, `args`): `undefined`

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\> |
| `args` | `IArguments` \| [[`Subscriber`](../modules/akashaproject_awf_sdk._internal_.md#subscriber)<`R`\>] |

#### Returns

`undefined`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:36

___

### call

▸ `Static` **call**<`R`\>(`instance`, `subscriber`): `undefined`

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\> |
| `subscriber` | [`Subscriber`](../modules/akashaproject_awf_sdk._internal_.md#subscriber)<`R`\> |

#### Returns

`undefined`

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:35

___

### from

▸ `Static` **from**<`R`\>(`observable`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `observable` | [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\> \| [`ObservableLike`](../interfaces/akashaproject_awf_sdk._internal_.ObservableLike.md)<`R`\> \| [`ArrayLike`](../interfaces/akashaproject_awf_sdk._internal_.ArrayLike.md)<`R`\> |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:56

___

### of

▸ `Static` **of**<`R`\>(...`items`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...items` | `R`[] |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<`R`\>

#### Defined in

sdk/node_modules/zen-observable-ts/module.d.ts:57
