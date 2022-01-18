[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryClient

# Class: QueryClient

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryClient

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.QueryClient.md#constructor)

### Methods

- [cancelMutations](akashaproject_ui_awf_hooks._internal_.QueryClient.md#cancelmutations)
- [cancelQueries](akashaproject_ui_awf_hooks._internal_.QueryClient.md#cancelqueries)
- [clear](akashaproject_ui_awf_hooks._internal_.QueryClient.md#clear)
- [defaultMutationOptions](akashaproject_ui_awf_hooks._internal_.QueryClient.md#defaultmutationoptions)
- [defaultQueryObserverOptions](akashaproject_ui_awf_hooks._internal_.QueryClient.md#defaultqueryobserveroptions)
- [defaultQueryOptions](akashaproject_ui_awf_hooks._internal_.QueryClient.md#defaultqueryoptions)
- [executeMutation](akashaproject_ui_awf_hooks._internal_.QueryClient.md#executemutation)
- [fetchInfiniteQuery](akashaproject_ui_awf_hooks._internal_.QueryClient.md#fetchinfinitequery)
- [fetchQuery](akashaproject_ui_awf_hooks._internal_.QueryClient.md#fetchquery)
- [getDefaultOptions](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getdefaultoptions)
- [getMutationCache](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getmutationcache)
- [getMutationDefaults](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getmutationdefaults)
- [getQueriesData](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getqueriesdata)
- [getQueryCache](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getquerycache)
- [getQueryData](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getquerydata)
- [getQueryDefaults](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getquerydefaults)
- [getQueryState](akashaproject_ui_awf_hooks._internal_.QueryClient.md#getquerystate)
- [invalidateQueries](akashaproject_ui_awf_hooks._internal_.QueryClient.md#invalidatequeries)
- [isFetching](akashaproject_ui_awf_hooks._internal_.QueryClient.md#isfetching)
- [isMutating](akashaproject_ui_awf_hooks._internal_.QueryClient.md#ismutating)
- [mount](akashaproject_ui_awf_hooks._internal_.QueryClient.md#mount)
- [prefetchInfiniteQuery](akashaproject_ui_awf_hooks._internal_.QueryClient.md#prefetchinfinitequery)
- [prefetchQuery](akashaproject_ui_awf_hooks._internal_.QueryClient.md#prefetchquery)
- [refetchQueries](akashaproject_ui_awf_hooks._internal_.QueryClient.md#refetchqueries)
- [removeQueries](akashaproject_ui_awf_hooks._internal_.QueryClient.md#removequeries)
- [resetQueries](akashaproject_ui_awf_hooks._internal_.QueryClient.md#resetqueries)
- [resumePausedMutations](akashaproject_ui_awf_hooks._internal_.QueryClient.md#resumepausedmutations)
- [setDefaultOptions](akashaproject_ui_awf_hooks._internal_.QueryClient.md#setdefaultoptions)
- [setMutationDefaults](akashaproject_ui_awf_hooks._internal_.QueryClient.md#setmutationdefaults)
- [setQueriesData](akashaproject_ui_awf_hooks._internal_.QueryClient.md#setqueriesdata)
- [setQueryData](akashaproject_ui_awf_hooks._internal_.QueryClient.md#setquerydata)
- [setQueryDefaults](akashaproject_ui_awf_hooks._internal_.QueryClient.md#setquerydefaults)
- [unmount](akashaproject_ui_awf_hooks._internal_.QueryClient.md#unmount)

## Constructors

### constructor

• **new QueryClient**(`config?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `config?` | [`QueryClientConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryClientConfig.md) |

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:20

## Methods

### cancelMutations

▸ **cancelMutations**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:55

___

### cancelQueries

▸ **cancelQueries**(`filters?`, `options?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |
| `options?` | [`CancelOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.CancelOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:37

▸ **cancelQueries**(`queryKey?`, `filters?`, `options?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |
| `options?` | [`CancelOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.CancelOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:38

___

### clear

▸ **clear**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:69

___

### defaultMutationOptions

▸ **defaultMutationOptions**<`T`\>(`options?`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`MutationOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationOptions.md)<`any`, `any`, `any`, `any`, `T`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `T` |

#### Returns

`T`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:68

___

### defaultQueryObserverOptions

▸ **defaultQueryObserverOptions**<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>(`options?`): [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `TQueryFnData` |
| `TError` | `TError` |
| `TData` | `TData` |
| `TQueryData` | `TQueryData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Returns

[`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:67

___

### defaultQueryOptions

▸ **defaultQueryOptions**<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>(`options?`): [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `TQueryFnData` |
| `TError` | `TError` |
| `TData` | `TData` |
| `TQueryData` | `TQueryData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Returns

[`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:66

___

### executeMutation

▸ **executeMutation**<`TData`, `TError`, `TVariables`, `TContext`\>(`options`): `Promise`<`TData`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`MutationOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:57

___

### fetchInfiniteQuery

▸ **fetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`options`): `Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:49

▸ **fetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `options?`): `Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `options?` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:50

▸ **fetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `queryFn`, `options?`): `Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `queryFn` | [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\> |
| `options?` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<[`InfiniteData`](../interfaces/akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:51

___

### fetchQuery

▸ **fetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`options`): `Promise`<`TData`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:43

▸ **fetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `options?`): `Promise`<`TData`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `options?` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:44

▸ **fetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `queryFn`, `options?`): `Promise`<`TData`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `queryFn` | [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\> |
| `options?` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:45

___

### getDefaultOptions

▸ **getDefaultOptions**(): [`DefaultOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.DefaultOptions.md)<`unknown`\>

#### Returns

[`DefaultOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.DefaultOptions.md)<`unknown`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:60

___

### getMutationCache

▸ **getMutationCache**(): [`MutationCache`](akashaproject_ui_awf_hooks._internal_.MutationCache.md)

#### Returns

[`MutationCache`](akashaproject_ui_awf_hooks._internal_.MutationCache.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:59

___

### getMutationDefaults

▸ **getMutationDefaults**(`mutationKey?`): [`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`any`, `any`, `any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutationKey?` | [`MutationKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationkey) |

#### Returns

[`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`any`, `any`, `any`, `any`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:65

___

### getQueriesData

▸ **getQueriesData**<`TData`\>(`queryKey`): [[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Returns

[[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:27

▸ **getQueriesData**<`TData`\>(`filters`): [[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:28

___

### getQueryCache

▸ **getQueryCache**(): [`QueryCache`](akashaproject_ui_awf_hooks._internal_.QueryCache.md)

#### Returns

[`QueryCache`](akashaproject_ui_awf_hooks._internal_.QueryCache.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:58

___

### getQueryData

▸ **getQueryData**<`TData`\>(`queryKey`, `filters?`): `TData`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

`TData`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:26

___

### getQueryDefaults

▸ **getQueryDefaults**(`queryKey?`): [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`any`, `any`, `any`, `any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Returns

[`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`any`, `any`, `any`, `any`, `any`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:63

___

### getQueryState

▸ **getQueryState**<`TData`, `TError`\>(`queryKey`, `filters?`): [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `undefined` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

[`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:32

___

### invalidateQueries

▸ **invalidateQueries**<`TPageData`\>(`filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`InvalidateQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.InvalidateQueryFilters.md)<`TPageData`\> |
| `options?` | [`InvalidateOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.InvalidateOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:39

▸ **invalidateQueries**<`TPageData`\>(`queryKey?`, `filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`InvalidateQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.InvalidateQueryFilters.md)<`TPageData`\> |
| `options?` | [`InvalidateOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.InvalidateOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:40

___

### isFetching

▸ **isFetching**(`filters?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

`number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:23

▸ **isFetching**(`queryKey?`, `filters?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

`number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:24

___

### isMutating

▸ **isMutating**(`filters?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`MutationFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationFilters.md) |

#### Returns

`number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:25

___

### mount

▸ **mount**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:21

___

### prefetchInfiniteQuery

▸ **prefetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`options`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:52

▸ **prefetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `options?` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:53

▸ **prefetchInfiniteQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `queryFn`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `queryFn` | [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\> |
| `options?` | [`FetchInfiniteQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:54

___

### prefetchQuery

▸ **prefetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`options`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:46

▸ **prefetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `options?` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:47

▸ **prefetchQuery**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`queryKey`, `queryFn`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | `TQueryKey` |
| `queryFn` | [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\> |
| `options?` | [`FetchQueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:48

___

### refetchQueries

▸ **refetchQueries**<`TPageData`\>(`filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`RefetchQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)<`TPageData`\> |
| `options?` | [`RefetchOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:41

▸ **refetchQueries**<`TPageData`\>(`queryKey?`, `filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`RefetchQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)<`TPageData`\> |
| `options?` | [`RefetchOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:42

___

### removeQueries

▸ **removeQueries**(`filters?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:33

▸ **removeQueries**(`queryKey?`, `filters?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:34

___

### resetQueries

▸ **resetQueries**<`TPageData`\>(`filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters?` | [`ResetQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md)<`TPageData`\> |
| `options?` | [`ResetOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.ResetOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:35

▸ **resetQueries**<`TPageData`\>(`queryKey?`, `filters?`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey?` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `filters?` | [`ResetQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md)<`TPageData`\> |
| `options?` | [`ResetOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.ResetOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:36

___

### resumePausedMutations

▸ **resumePausedMutations**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:56

___

### setDefaultOptions

▸ **setDefaultOptions**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`DefaultOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.DefaultOptions.md)<`unknown`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:61

___

### setMutationDefaults

▸ **setMutationDefaults**(`mutationKey`, `options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutationKey` | [`MutationKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationkey) |
| `options` | [`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:64

___

### setQueriesData

▸ **setQueriesData**<`TData`\>(`queryKey`, `updater`, `options?`): [[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Type parameters

| Name |
| :------ |
| `TData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `updater` | [`Updater`](../modules/akashaproject_ui_awf_hooks._internal_.md#updater)<`TData`, `TData`\> |
| `options?` | [`SetDataOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.SetDataOptions.md) |

#### Returns

[[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:30

▸ **setQueriesData**<`TData`\>(`filters`, `updater`, `options?`): [[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Type parameters

| Name |
| :------ |
| `TData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters` | [`QueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryFilters.md) |
| `updater` | [`Updater`](../modules/akashaproject_ui_awf_hooks._internal_.md#updater)<`TData`, `TData`\> |
| `options?` | [`SetDataOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.SetDataOptions.md) |

#### Returns

[[`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey), `TData`][]

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:31

___

### setQueryData

▸ **setQueryData**<`TData`\>(`queryKey`, `updater`, `options?`): `TData`

#### Type parameters

| Name |
| :------ |
| `TData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `updater` | [`Updater`](../modules/akashaproject_ui_awf_hooks._internal_.md#updater)<`TData`, `TData`\> |
| `options?` | [`SetDataOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.SetDataOptions.md) |

#### Returns

`TData`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:29

___

### setQueryDefaults

▸ **setQueryDefaults**(`queryKey`, `options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `options` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`any`, `any`, `any`, `any`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:62

___

### unmount

▸ **unmount**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryClient.d.ts:22
