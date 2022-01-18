[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / InfiniteQueryObserverBaseResult

# Interface: InfiniteQueryObserverBaseResult<TData, TError\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).InfiniteQueryObserverBaseResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |

## Hierarchy

- [`QueryObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md)<[`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>, `TError`\>

  ↳ **`InfiniteQueryObserverBaseResult`**

  ↳↳ [`InfiniteQueryObserverIdleResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverIdleResult.md)

  ↳↳ [`InfiniteQueryObserverLoadingErrorResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverLoadingErrorResult.md)

  ↳↳ [`InfiniteQueryObserverLoadingResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverLoadingResult.md)

  ↳↳ [`InfiniteQueryObserverRefetchErrorResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverRefetchErrorResult.md)

  ↳↳ [`InfiniteQueryObserverSuccessResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md)

## Table of contents

### Properties

- [data](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#data)
- [dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#dataupdatedat)
- [error](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#error)
- [errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#errorupdatedat)
- [failureCount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#failurecount)
- [hasNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#hasnextpage)
- [hasPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#haspreviouspage)
- [isError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#iserror)
- [isFetched](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetched)
- [isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchedaftermount)
- [isFetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetching)
- [isFetchingNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchingnextpage)
- [isFetchingPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchingpreviouspage)
- [isIdle](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isloading)
- [isLoadingError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isloadingerror)
- [isPlaceholderData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isplaceholderdata)
- [isPreviousData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#ispreviousdata)
- [isRefetchError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isrefetcherror)
- [isRefetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isrefetching)
- [isStale](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isstale)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#issuccess)
- [status](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#status)

### Methods

- [fetchNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#fetchnextpage)
- [fetchPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#fetchpreviouspage)
- [refetch](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#refetch)
- [remove](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#remove)

## Properties

### data

• **data**: [`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[data](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:211

___

### dataUpdatedAt

• **dataUpdatedAt**: `number`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#dataupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:212

___

### error

• **error**: `TError`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:213

___

### errorUpdatedAt

• **errorUpdatedAt**: `number`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#errorupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:214

___

### failureCount

• **failureCount**: `number`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[failureCount](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#failurecount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:215

___

### hasNextPage

• `Optional` **hasNextPage**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:292

___

### hasPreviousPage

• `Optional` **hasPreviousPage**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:293

___

### isError

• **isError**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#iserror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:216

___

### isFetched

• **isFetched**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isFetched](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetched)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:217

___

### isFetchedAfterMount

• **isFetchedAfterMount**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetchedaftermount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:218

___

### isFetching

• **isFetching**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isFetching](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetching)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:219

___

### isFetchingNextPage

• **isFetchingNextPage**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:294

___

### isFetchingPreviousPage

• **isFetchingPreviousPage**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:295

___

### isIdle

• **isIdle**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:220

___

### isLoading

• **isLoading**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:221

___

### isLoadingError

• **isLoadingError**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isLoadingError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloadingerror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:222

___

### isPlaceholderData

• **isPlaceholderData**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isPlaceholderData](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isplaceholderdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:223

___

### isPreviousData

• **isPreviousData**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isPreviousData](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#ispreviousdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:224

___

### isRefetchError

• **isRefetchError**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isRefetchError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isrefetcherror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:225

___

### isRefetching

• **isRefetching**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isRefetching](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isrefetching)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:226

___

### isStale

• **isStale**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isStale](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isstale)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:227

___

### isSuccess

• **isSuccess**: `boolean`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isSuccess](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#issuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:228

___

### status

• **status**: [`QueryStatus`](../modules/akashaproject_ui_awf_hooks._internal_.md#querystatus)

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:231

## Methods

### fetchNextPage

▸ **fetchNextPage**(`options?`): `Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FetchNextPageOptions`](akashaproject_ui_awf_hooks._internal_.FetchNextPageOptions.md) |

#### Returns

`Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:290

___

### fetchPreviousPage

▸ **fetchPreviousPage**(`options?`): `Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FetchPreviousPageOptions`](akashaproject_ui_awf_hooks._internal_.FetchPreviousPageOptions.md) |

#### Returns

`Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:291

___

### refetch

▸ **refetch**<`TPageData`\>(`options?`): `Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Type parameters

| Name |
| :------ |
| `TPageData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`RefetchOptions`](akashaproject_ui_awf_hooks._internal_.RefetchOptions.md) & [`RefetchQueryFilters`](akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)<`TPageData`\> |

#### Returns

`Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[refetch](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#refetch)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:229

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Inherited from

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[remove](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#remove)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:230
