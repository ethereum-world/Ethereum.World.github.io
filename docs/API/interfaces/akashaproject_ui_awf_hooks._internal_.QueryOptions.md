[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryOptions

# Interface: QueryOptions<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Hierarchy

- **`QueryOptions`**

  ↳ [`QueryObserverOptions`](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)

  ↳ [`FetchQueryOptions`](akashaproject_ui_awf_hooks._internal_.FetchQueryOptions.md)

## Table of contents

### Properties

- [\_defaulted](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#_defaulted)
- [behavior](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#behavior)
- [cacheTime](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#cachetime)
- [getNextPageParam](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#getnextpageparam)
- [getPreviousPageParam](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#getpreviouspageparam)
- [initialData](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#initialdata)
- [initialDataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#initialdataupdatedat)
- [meta](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#meta)
- [queryFn](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#queryfn)
- [queryHash](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#queryhash)
- [queryKey](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#querykey)
- [queryKeyHashFn](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#querykeyhashfn)
- [retry](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#retry)
- [retryDelay](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#retrydelay)
- [structuralSharing](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#structuralsharing)

### Methods

- [isDataEqual](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#isdataequal)

## Properties

### \_defaulted

• `Optional` **\_defaulted**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:57

___

### behavior

• `Optional` **behavior**: [`QueryBehavior`](akashaproject_ui_awf_hooks._internal_.QueryBehavior.md)<`TQueryFnData`, `TError`, `TData`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:41

___

### cacheTime

• `Optional` **cacheTime**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:33

___

### getNextPageParam

• `Optional` **getNextPageParam**: [`GetNextPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getnextpageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the next cursor for infinite queries.
The result will also be used to determine the value of `hasNextPage`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:56

___

### getPreviousPageParam

• `Optional` **getPreviousPageParam**: [`GetPreviousPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getpreviouspageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the previous cursor for infinite queries.
The result will also be used to determine the value of `hasPreviousPage`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:51

___

### initialData

• `Optional` **initialData**: `TData` \| [`InitialDataFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#initialdatafunction)<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:39

___

### initialDataUpdatedAt

• `Optional` **initialDataUpdatedAt**: `number` \| () => `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:40

___

### meta

• `Optional` **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

Additional payload to be stored on each query.
Use this property to pass information that can be used in other places.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:62

___

### queryFn

• `Optional` **queryFn**: [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:35

___

### queryHash

• `Optional` **queryHash**: `string`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:36

___

### queryKey

• `Optional` **queryKey**: `TQueryKey`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:37

___

### queryKeyHashFn

• `Optional` **queryKeyHashFn**: [`QueryKeyHashFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykeyhashfunction)<`TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:38

___

### retry

• `Optional` **retry**: [`RetryValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retryvalue)<`TError`\>

If `false`, failed queries will not retry by default.
If `true`, failed queries will retry infinitely., failureCount: num
If set to an integer number, e.g. 3, failed queries will retry until the failed query count meets that number.
If set to a function `(failureCount, error) => boolean` failed queries will retry until the function returns false.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:31

___

### retryDelay

• `Optional` **retryDelay**: [`RetryDelayValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retrydelayvalue)<`TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:32

___

### structuralSharing

• `Optional` **structuralSharing**: `boolean`

Set this to `false` to disable structural sharing between query results.
Defaults to `true`.

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

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:34
