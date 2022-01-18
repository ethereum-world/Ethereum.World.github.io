[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / InfiniteQueryObserverSuccessResult

# Interface: InfiniteQueryObserverSuccessResult<TData, TError\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).InfiniteQueryObserverSuccessResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |

## Hierarchy

- [`InfiniteQueryObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md)<`TData`, `TError`\>

  ↳ **`InfiniteQueryObserverSuccessResult`**

## Table of contents

### Properties

- [data](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#data)
- [dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#dataupdatedat)
- [error](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#error)
- [errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#errorupdatedat)
- [failureCount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#failurecount)
- [hasNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#hasnextpage)
- [hasPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#haspreviouspage)
- [isError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#iserror)
- [isFetched](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isfetched)
- [isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isfetchedaftermount)
- [isFetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isfetching)
- [isFetchingNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isfetchingnextpage)
- [isFetchingPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isfetchingpreviouspage)
- [isIdle](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isloading)
- [isLoadingError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isloadingerror)
- [isPlaceholderData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isplaceholderdata)
- [isPreviousData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#ispreviousdata)
- [isRefetchError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isrefetcherror)
- [isRefetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isrefetching)
- [isStale](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#isstale)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#issuccess)
- [status](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#status)

### Methods

- [fetchNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#fetchnextpage)
- [fetchPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#fetchpreviouspage)
- [refetch](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#refetch)
- [remove](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverSuccessResult.md#remove)

## Properties

### data

• **data**: [`InfiniteData`](akashaproject_ui_awf_hooks._internal_.InfiniteData.md)<`TData`\>

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[data](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:342

___

### dataUpdatedAt

• **dataUpdatedAt**: `number`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#dataupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:212

___

### error

• **error**: ``null``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:343

___

### errorUpdatedAt

• **errorUpdatedAt**: `number`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#errorupdatedat)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:214

___

### failureCount

• **failureCount**: `number`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[failureCount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#failurecount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:215

___

### hasNextPage

• `Optional` **hasNextPage**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[hasNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#hasnextpage)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:292

___

### hasPreviousPage

• `Optional` **hasPreviousPage**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[hasPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#haspreviouspage)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:293

___

### isError

• **isError**: ``false``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#iserror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:344

___

### isFetched

• **isFetched**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isFetched](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetched)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:217

___

### isFetchedAfterMount

• **isFetchedAfterMount**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchedaftermount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:218

___

### isFetching

• **isFetching**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isFetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetching)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:219

___

### isFetchingNextPage

• **isFetchingNextPage**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isFetchingNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchingnextpage)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:294

___

### isFetchingPreviousPage

• **isFetchingPreviousPage**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isFetchingPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isfetchingpreviouspage)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:295

___

### isIdle

• **isIdle**: ``false``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:345

___

### isLoading

• **isLoading**: ``false``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:346

___

### isLoadingError

• **isLoadingError**: ``false``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isLoadingError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isloadingerror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:347

___

### isPlaceholderData

• **isPlaceholderData**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isPlaceholderData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isplaceholderdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:223

___

### isPreviousData

• **isPreviousData**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isPreviousData](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#ispreviousdata)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:224

___

### isRefetchError

• **isRefetchError**: ``false``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isRefetchError](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isrefetcherror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:348

___

### isRefetching

• **isRefetching**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isRefetching](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isrefetching)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:226

___

### isStale

• **isStale**: `boolean`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isStale](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#isstale)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:227

___

### isSuccess

• **isSuccess**: ``true``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[isSuccess](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#issuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:349

___

### status

• **status**: ``"success"``

#### Overrides

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:350

## Methods

### fetchNextPage

▸ **fetchNextPage**(`options?`): `Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FetchNextPageOptions`](akashaproject_ui_awf_hooks._internal_.FetchNextPageOptions.md) |

#### Returns

`Promise`<[`InfiniteQueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#infinitequeryobserverresult)<`TData`, `TError`\>\>

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[fetchNextPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#fetchnextpage)

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

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[fetchPreviousPage](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#fetchpreviouspage)

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

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[refetch](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#refetch)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:229

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Inherited from

[InfiniteQueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md).[remove](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md#remove)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:230
