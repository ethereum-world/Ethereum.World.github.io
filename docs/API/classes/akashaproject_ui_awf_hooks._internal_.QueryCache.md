[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryCache

# Class: QueryCache

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryCache

## Hierarchy

- [`Subscribable`](akashaproject_ui_awf_hooks._internal_.Subscribable.md)<[`QueryCacheListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#querycachelistener)\>

  ↳ **`QueryCache`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.QueryCache.md#constructor)

### Properties

- [config](akashaproject_ui_awf_hooks._internal_.QueryCache.md#config)

### Methods

- [add](akashaproject_ui_awf_hooks._internal_.QueryCache.md#add)
- [build](akashaproject_ui_awf_hooks._internal_.QueryCache.md#build)
- [clear](akashaproject_ui_awf_hooks._internal_.QueryCache.md#clear)
- [find](akashaproject_ui_awf_hooks._internal_.QueryCache.md#find)
- [findAll](akashaproject_ui_awf_hooks._internal_.QueryCache.md#findall)
- [get](akashaproject_ui_awf_hooks._internal_.QueryCache.md#get)
- [getAll](akashaproject_ui_awf_hooks._internal_.QueryCache.md#getall)
- [hasListeners](akashaproject_ui_awf_hooks._internal_.QueryCache.md#haslisteners)
- [notify](akashaproject_ui_awf_hooks._internal_.QueryCache.md#notify)
- [onFocus](akashaproject_ui_awf_hooks._internal_.QueryCache.md#onfocus)
- [onOnline](akashaproject_ui_awf_hooks._internal_.QueryCache.md#ononline)
- [remove](akashaproject_ui_awf_hooks._internal_.QueryCache.md#remove)
- [subscribe](akashaproject_ui_awf_hooks._internal_.QueryCache.md#subscribe)

## Constructors

### constructor

• **new QueryCache**(`config?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `config?` | [`QueryCacheConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryCacheConfig.md) |

#### Overrides

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[constructor](akashaproject_ui_awf_hooks._internal_.Subscribable.md#constructor)

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:44

## Properties

### config

• **config**: [`QueryCacheConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryCacheConfig.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:41

## Methods

### add

▸ **add**(`query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:46

___

### build

▸ **build**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`client`, `options`, `state?`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `TQueryFnData` |
| `TError` | `TError` |
| `TData` | `TData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`QueryClient`](akashaproject_ui_awf_hooks._internal_.QueryClient.md) |
| `options` | [`QueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |
| `state?` | [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\> |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:45

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:48

___

### find

▸ **find**<`TQueryFnData`, `TError`, `TData`\>(`arg1`, `arg2?`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg1` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `arg2?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:51

___

### findAll

▸ **findAll**(`queryKey?`, `filters?`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:52

▸ **findAll**(`filters?`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:53

▸ **findAll**(`arg1?`, `arg2?`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg1?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) \| [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |
| `arg2?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:54

___

### get

▸ **get**<`TQueryFnData`, `TError`, `TData`, `TQueyKey`\>(`queryHash`): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, `TQueyKey`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueyKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryHash` | `string` |

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TData`, `TQueyKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:49

___

### getAll

▸ **getAll**(): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>[]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:50

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

▸ **notify**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`QueryCacheNotifyEvent`](../modules/akashaproject_ui_awf_hooks._internal_.md#querycachenotifyevent) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:55

___

### onFocus

▸ **onFocus**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:56

___

### onOnline

▸ **onOnline**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:57

___

### remove

▸ **remove**(`query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:47

___

### subscribe

▸ **subscribe**(`listener?`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener?` | [`QueryCacheListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#querycachelistener) |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[subscribe](akashaproject_ui_awf_hooks._internal_.Subscribable.md#subscribe)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:5
