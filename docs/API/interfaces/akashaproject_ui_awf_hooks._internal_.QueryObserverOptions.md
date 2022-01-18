[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryObserverOptions

# Interface: QueryObserverOptions<TQueryFnData, TError, TData, TQueryData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryObserverOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Hierarchy

- [`QueryOptions`](akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TQueryData`, `TQueryKey`\>

  ↳ **`QueryObserverOptions`**

## Table of contents

### Properties

- [\_defaulted](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#_defaulted)
- [behavior](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#behavior)
- [cacheTime](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#cachetime)
- [enabled](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#enabled)
- [getNextPageParam](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#getnextpageparam)
- [getPreviousPageParam](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#getpreviouspageparam)
- [initialData](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#initialdata)
- [initialDataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#initialdataupdatedat)
- [keepPreviousData](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#keeppreviousdata)
- [meta](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#meta)
- [notifyOnChangeProps](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#notifyonchangeprops)
- [notifyOnChangePropsExclusions](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#notifyonchangepropsexclusions)
- [optimisticResults](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#optimisticresults)
- [placeholderData](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#placeholderdata)
- [queryFn](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#queryfn)
- [queryHash](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#queryhash)
- [queryKey](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#querykey)
- [queryKeyHashFn](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#querykeyhashfn)
- [refetchInterval](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#refetchinterval)
- [refetchIntervalInBackground](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#refetchintervalinbackground)
- [refetchOnMount](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#refetchonmount)
- [refetchOnReconnect](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#refetchonreconnect)
- [refetchOnWindowFocus](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#refetchonwindowfocus)
- [retry](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#retry)
- [retryDelay](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#retrydelay)
- [retryOnMount](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#retryonmount)
- [staleTime](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#staletime)
- [structuralSharing](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#structuralsharing)
- [suspense](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#suspense)
- [useErrorBoundary](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#useerrorboundary)

### Methods

- [isDataEqual](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#isdataequal)
- [onError](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#onerror)
- [onSettled](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#onsettled)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#onsuccess)
- [select](akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md#select)

## Properties

### \_defaulted

• `Optional` **\_defaulted**: `boolean`

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[_defaulted](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#_defaulted)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:57

___

### behavior

• `Optional` **behavior**: [`QueryBehavior`](akashaproject_ui_awf_hooks._internal_.QueryBehavior.md)<`TQueryFnData`, `TError`, `TQueryData`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\>

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[behavior](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#behavior)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:41

___

### cacheTime

• `Optional` **cacheTime**: `number`

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[cacheTime](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#cachetime)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:33

___

### enabled

• `Optional` **enabled**: `boolean`

Set this to `false` to disable automatic refetching when the query mounts or changes query keys.
To refetch the query, use the `refetch` method returned from the `useQuery` instance.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:70

___

### getNextPageParam

• `Optional` **getNextPageParam**: [`GetNextPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getnextpageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the next cursor for infinite queries.
The result will also be used to determine the value of `hasNextPage`.

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[getNextPageParam](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#getnextpageparam)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:56

___

### getPreviousPageParam

• `Optional` **getPreviousPageParam**: [`GetPreviousPageParamFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#getpreviouspageparamfunction)<`TQueryFnData`\>

This function can be set to automatically get the previous cursor for infinite queries.
The result will also be used to determine the value of `hasPreviousPage`.

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[getPreviousPageParam](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#getpreviouspageparam)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:51

___

### initialData

• `Optional` **initialData**: `TQueryData` \| [`InitialDataFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#initialdatafunction)<`TQueryData`\>

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[initialData](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#initialdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:39

___

### initialDataUpdatedAt

• `Optional` **initialDataUpdatedAt**: `number` \| () => `number`

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[initialDataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#initialdataupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:40

___

### keepPreviousData

• `Optional` **keepPreviousData**: `boolean`

Set this to `true` to keep the previous `data` when fetching based on a new query key.
Defaults to `false`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:157

___

### meta

• `Optional` **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

Additional payload to be stored on each query.
Use this property to pass information that can be used in other places.

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[meta](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#meta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:62

___

### notifyOnChangeProps

• `Optional` **notifyOnChangeProps**: (``"error"`` \| ``"data"`` \| ``"isError"`` \| ``"isIdle"`` \| ``"isLoading"`` \| ``"isSuccess"`` \| ``"status"`` \| ``"failureCount"`` \| ``"remove"`` \| ``"isLoadingError"`` \| ``"isRefetchError"`` \| ``"fetchNextPage"`` \| ``"fetchPreviousPage"`` \| ``"hasNextPage"`` \| ``"hasPreviousPage"`` \| ``"isFetchingNextPage"`` \| ``"isFetchingPreviousPage"`` \| ``"dataUpdatedAt"`` \| ``"errorUpdatedAt"`` \| ``"isFetched"`` \| ``"isFetchedAfterMount"`` \| ``"isFetching"`` \| ``"isPlaceholderData"`` \| ``"isPreviousData"`` \| ``"isRefetching"`` \| ``"isStale"`` \| ``"refetch"``)[] \| ``"tracked"``

If set, the component will only re-render if any of the listed properties change.
When set to `['data', 'error']`, the component will only re-render when the `data` or `error` properties change.
When set to `tracked`, access to properties will be tracked, and the component will only re-render when one of the tracked properties change.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:118

___

### notifyOnChangePropsExclusions

• `Optional` **notifyOnChangePropsExclusions**: (``"error"`` \| ``"data"`` \| ``"isError"`` \| ``"isIdle"`` \| ``"isLoading"`` \| ``"isSuccess"`` \| ``"status"`` \| ``"failureCount"`` \| ``"remove"`` \| ``"isLoadingError"`` \| ``"isRefetchError"`` \| ``"fetchNextPage"`` \| ``"fetchPreviousPage"`` \| ``"hasNextPage"`` \| ``"hasPreviousPage"`` \| ``"isFetchingNextPage"`` \| ``"isFetchingPreviousPage"`` \| ``"dataUpdatedAt"`` \| ``"errorUpdatedAt"`` \| ``"isFetched"`` \| ``"isFetchedAfterMount"`` \| ``"isFetching"`` \| ``"isPlaceholderData"`` \| ``"isPreviousData"`` \| ``"isRefetching"`` \| ``"isStale"`` \| ``"refetch"``)[]

If set, the component will not re-render if any of the listed properties change.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:122

___

### optimisticResults

• `Optional` **optimisticResults**: `boolean`

If set, the observer will optimistically set the result in fetching state before the query has actually started fetching.
This is to make sure the results are not lagging behind.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:167

___

### placeholderData

• `Optional` **placeholderData**: `TQueryData` \| [`PlaceholderDataFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#placeholderdatafunction)<`TQueryData`\>

If set, this value will be used as the placeholder data for this particular query observer while the query is still in the `loading` data and no initialData has been provided.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:161

___

### queryFn

• `Optional` **queryFn**: [`QueryFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryfunction)<`TQueryFnData`, `TQueryKey`\>

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[queryFn](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#queryfn)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:35

___

### queryHash

• `Optional` **queryHash**: `string`

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[queryHash](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#queryhash)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:36

___

### queryKey

• `Optional` **queryKey**: `TQueryKey`

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[queryKey](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#querykey)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:37

___

### queryKeyHashFn

• `Optional` **queryKeyHashFn**: [`QueryKeyHashFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykeyhashfunction)<`TQueryKey`\>

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[queryKeyHashFn](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#querykeyhashfn)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:38

___

### refetchInterval

• `Optional` **refetchInterval**: `number` \| ``false`` \| (`data`: `TData`, `query`: [`Query`](../classes/akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TQueryData`, `TQueryKey`\>) => `number` \| ``false``

If set to a number, the query will continuously refetch at this frequency in milliseconds.
If set to a function, the function will be executed with the latest data and query to compute a frequency
Defaults to `false`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:81

___

### refetchIntervalInBackground

• `Optional` **refetchIntervalInBackground**: `boolean`

If set to `true`, the query will continue to refetch while their tab/window is in the background.
Defaults to `false`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:86

___

### refetchOnMount

• `Optional` **refetchOnMount**: `boolean` \| ``"always"``

If set to `true`, the query will refetch on mount if the data is stale.
If set to `false`, will disable additional instances of a query to trigger background refetches.
If set to `'always'`, the query will always refetch on mount.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:107

___

### refetchOnReconnect

• `Optional` **refetchOnReconnect**: `boolean` \| ``"always"``

If set to `true`, the query will refetch on reconnect if the data is stale.
If set to `false`, the query will not refetch on reconnect.
If set to `'always'`, the query will always refetch on reconnect.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:100

___

### refetchOnWindowFocus

• `Optional` **refetchOnWindowFocus**: `boolean` \| ``"always"``

If set to `true`, the query will refetch on window focus if the data is stale.
If set to `false`, the query will not refetch on window focus.
If set to `'always'`, the query will always refetch on window focus.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:93

___

### retry

• `Optional` **retry**: [`RetryValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retryvalue)<`TError`\>

If `false`, failed queries will not retry by default.
If `true`, failed queries will retry infinitely., failureCount: num
If set to an integer number, e.g. 3, failed queries will retry until the failed query count meets that number.
If set to a function `(failureCount, error) => boolean` failed queries will retry until the function returns false.

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[retry](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#retry)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:31

___

### retryDelay

• `Optional` **retryDelay**: [`RetryDelayValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retrydelayvalue)<`TError`\>

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[retryDelay](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#retrydelay)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:32

___

### retryOnMount

• `Optional` **retryOnMount**: `boolean`

If set to `false`, the query will not be retried on mount if it contains an error.
Defaults to `true`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:112

___

### staleTime

• `Optional` **staleTime**: `number`

The time in milliseconds after data is considered stale.
If set to `Infinity`, the data will never be considered stale.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:75

___

### structuralSharing

• `Optional` **structuralSharing**: `boolean`

Set this to `false` to disable structural sharing between query results.
Defaults to `true`.

#### Inherited from

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[structuralSharing](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#structuralsharing)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:46

___

### suspense

• `Optional` **suspense**: `boolean`

If set to `true`, the query will suspend when `status === 'loading'`
and throw errors when `status === 'error'`.
Defaults to `false`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:152

___

### useErrorBoundary

• `Optional` **useErrorBoundary**: `boolean` \| (`error`: `TError`) => `boolean`

Whether errors should be thrown instead of setting the `error` property.
If set to `true` or `suspense` is `true`, all errors will be thrown to the error boundary.
If set to `false` and `suspense` is `false`, errors are returned as state.
If set to a function, it will be passed the error and should return a boolean indicating whether to show the error in an error boundary (`true`) or return the error as state (`false`).
Defaults to `false`.

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:142

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

[QueryOptions](akashaproject_ui_awf_hooks._internal_.QueryOptions.md).[isDataEqual](akashaproject_ui_awf_hooks._internal_.QueryOptions.md#isdataequal)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:34

___

### onError

▸ `Optional` **onError**(`err`): `void`

This callback will fire if the query encounters an error and will be passed the error.

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `TError` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:130

___

### onSettled

▸ `Optional` **onSettled**(`data`, `error`): `void`

This callback will fire any time the query is either successfully fetched or errors and be passed either the data or error.

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `TData` |
| `error` | `TError` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:134

___

### onSuccess

▸ `Optional` **onSuccess**(`data`): `void`

This callback will fire any time the query successfully fetches new data or the cache is updated via `setQueryData`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `TData` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:126

___

### select

▸ `Optional` **select**(`data`): `TData`

This option can be used to transform or select a part of the data returned by the query function.

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `TQueryData` |

#### Returns

`TData`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:146
