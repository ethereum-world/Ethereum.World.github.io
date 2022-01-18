[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationCache

# Class: MutationCache

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationCache

## Hierarchy

- [`Subscribable`](akashaproject_ui_awf_hooks._internal_.Subscribable.md)<[`MutationCacheListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationcachelistener)\>

  ↳ **`MutationCache`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.MutationCache.md#constructor)

### Properties

- [config](akashaproject_ui_awf_hooks._internal_.MutationCache.md#config)

### Methods

- [add](akashaproject_ui_awf_hooks._internal_.MutationCache.md#add)
- [build](akashaproject_ui_awf_hooks._internal_.MutationCache.md#build)
- [clear](akashaproject_ui_awf_hooks._internal_.MutationCache.md#clear)
- [find](akashaproject_ui_awf_hooks._internal_.MutationCache.md#find)
- [findAll](akashaproject_ui_awf_hooks._internal_.MutationCache.md#findall)
- [getAll](akashaproject_ui_awf_hooks._internal_.MutationCache.md#getall)
- [hasListeners](akashaproject_ui_awf_hooks._internal_.MutationCache.md#haslisteners)
- [notify](akashaproject_ui_awf_hooks._internal_.MutationCache.md#notify)
- [onFocus](akashaproject_ui_awf_hooks._internal_.MutationCache.md#onfocus)
- [onOnline](akashaproject_ui_awf_hooks._internal_.MutationCache.md#ononline)
- [remove](akashaproject_ui_awf_hooks._internal_.MutationCache.md#remove)
- [resumePausedMutations](akashaproject_ui_awf_hooks._internal_.MutationCache.md#resumepausedmutations)
- [subscribe](akashaproject_ui_awf_hooks._internal_.MutationCache.md#subscribe)

## Constructors

### constructor

• **new MutationCache**(`config?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `config?` | [`MutationCacheConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationCacheConfig.md) |

#### Overrides

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[constructor](akashaproject_ui_awf_hooks._internal_.Subscribable.md#constructor)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:16

## Properties

### config

• **config**: [`MutationCacheConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationCacheConfig.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:13

## Methods

### add

▸ **add**(`mutation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutation` | [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:18

___

### build

▸ **build**<`TData`, `TError`, `TVariables`, `TContext`\>(`client`, `options`, `state?`): [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Type parameters

| Name |
| :------ |
| `TData` |
| `TError` |
| `TVariables` |
| `TContext` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`QueryClient`](akashaproject_ui_awf_hooks._internal_.QueryClient.md) |
| `options` | [`MutationOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\> |
| `state?` | [`MutationState`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationState.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

[`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:17

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:20

___

### find

▸ **find**<`TData`, `TError`, `TVariables`, `TContext`\>(`filters`): [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `any` |
| `TContext` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters` | [`MutationFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationFilters.md) |

#### Returns

[`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:22

___

### findAll

▸ **findAll**(`filters`): [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `void`, `unknown`\>[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters` | [`MutationFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationFilters.md) |

#### Returns

[`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `void`, `unknown`\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:23

___

### getAll

▸ **getAll**(): [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `void`, `unknown`\>[]

#### Returns

[`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `void`, `unknown`\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:21

___

### hasListeners

▸ **hasListeners**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[hasListeners](akashaproject_ui_awf_hooks._internal_.Subscribable.md#haslisteners)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:6

___

### notify

▸ **notify**(`mutation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutation?` | [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:24

___

### onFocus

▸ **onFocus**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:25

___

### onOnline

▸ **onOnline**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:26

___

### remove

▸ **remove**(`mutation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutation` | [`Mutation`](akashaproject_ui_awf_hooks._internal_.Mutation.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:19

___

### resumePausedMutations

▸ **resumePausedMutations**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:27

___

### subscribe

▸ **subscribe**(`listener?`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener?` | [`MutationCacheListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationcachelistener) |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[subscribe](akashaproject_ui_awf_hooks._internal_.Subscribable.md#subscribe)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:5
