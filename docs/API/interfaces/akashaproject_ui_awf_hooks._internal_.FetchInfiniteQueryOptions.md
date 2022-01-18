[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / FetchInfiniteQueryOptions

# Interface: FetchInfiniteQueryOptions<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).FetchInfiniteQueryOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Hierarchy

- [`FetchQueryOptions`](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)<`TQueryFnData`, `TError`, [`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>, `TQueryKey`\>

  ↳ **`FetchInfiniteQueryOptions`**

## Table of contents

### Properties

- [\_defaulted](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#_defaulted)
- [behavior](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#behavior)
- [cacheTime](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#cachetime)
- [getNextPageParam](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#getnextpageparam)
- [getPreviousPageParam](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#getpreviouspageparam)
- [initialData](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#initialdata)
- [initialDataUpdatedAt](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#initialdataupdatedat)
- [meta](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#meta)
- [queryFn](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#queryfn)
- [queryHash](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#queryhash)
- [queryKey](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#querykey)
- [queryKeyHashFn](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#querykeyhashfn)
- [retry](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#retry)
- [retryDelay](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#retrydelay)
- [staleTime](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#staletime)
- [structuralSharing](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#structuralsharing)

### Methods

- [isDataEqual](akashaproject_ui_awf_hooks._internal_.FetchInfiniteQueryOptions.md#isdataequal)

## Properties

### \_defaulted

• `Optional` **\_defaulted**: `boolean`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[_defaulted](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#_defaulted)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:57

___

### behavior

• `Optional` **behavior**: [`QueryBehavior`](akashaproject_ui_awf_hooks._internal_.QueryBehavior.md)<`TQueryFnData`, `TError`, [`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[behavior](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#behavior)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:41

___

### cacheTime

• `Optional` **cacheTime**: `number`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[cacheTime](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#cachetime)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:33

___

### getNextPageParam

• `Optional` **getNextPageParam**: [`GetNextPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getnextpageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the next cursor for infinite queries.
The result will also be used to determine the value of `hasNextPage`.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[getNextPageParam](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#getnextpageparam)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:56

___

### getPreviousPageParam

• `Optional` **getPreviousPageParam**: [`GetPreviousPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getpreviouspageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the previous cursor for infinite queries.
The result will also be used to determine the value of `hasPreviousPage`.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[getPreviousPageParam](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#getpreviouspageparam)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:51

___

### initialData

• `Optional` **initialData**: [`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\> \| [`InitialDataFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#initialdatafunction)<[`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>\>

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[initialData](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#initialdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:39

___

### initialDataUpdatedAt

• `Optional` **initialDataUpdatedAt**: `number` \| () => `number`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[initialDataUpdatedAt](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#initialdataupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:40

___

### meta

• `Optional` **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

Additional payload to be stored on each query.
Use this property to pass information that can be used in other places.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[meta](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#meta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:62

___

### queryFn

• `Optional` **queryFn**: [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\>

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[queryFn](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#queryfn)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:35

___

### queryHash

• `Optional` **queryHash**: `string`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[queryHash](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#queryhash)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:36

___

### queryKey

• `Optional` **queryKey**: `TQueryKey`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[queryKey](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#querykey)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:37

___

### queryKeyHashFn

• `Optional` **queryKeyHashFn**: [`QueryKeyHashFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykeyhashfunction)<`TQueryKey`\>

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[queryKeyHashFn](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#querykeyhashfn)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:38

___

### retry

• `Optional` **retry**: [`RetryValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retryvalue)<`TError`\>

If `false`, failed queries will not retry by default.
If `true`, failed queries will retry infinitely., failureCount: num
If set to an integer number, e.g. 3, failed queries will retry until the failed query count meets that number.
If set to a function `(failureCount, error) => boolean` failed queries will retry until the function returns false.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[retry](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#retry)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:31

___

### retryDelay

• `Optional` **retryDelay**: [`RetryDelayValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retrydelayvalue)<`TError`\>

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[retryDelay](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#retrydelay)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:32

___

### staleTime

• `Optional` **staleTime**: `number`

The time in milliseconds after data is considered stale.
If the data is fresh it will be returned from the cache.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[staleTime](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#staletime)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:176

___

### structuralSharing

• `Optional` **structuralSharing**: `boolean`

Set this to `false` to disable structural sharing between query results.
Defaults to `true`.

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[structuralSharing](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#structuralsharing)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:46

## Methods

### isDataEqual

▸ `Optional` **isDataEqual**(`oldData`, `newData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `oldData` | `TData` |
| `newData` | `TData` |

#### Returns

`boolean`

#### Inherited from

[FetchQueryOptions](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md).[isDataEqual](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md#isdataequal)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:34
