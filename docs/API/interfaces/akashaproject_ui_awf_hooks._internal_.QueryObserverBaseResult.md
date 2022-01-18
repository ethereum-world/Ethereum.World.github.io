[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryObserverBaseResult

# Interface: QueryObserverBaseResult<TData, TError\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryObserverBaseResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |

## Hierarchy

- **`QueryObserverBaseResult`**

  ↳ [`QueryObserverIdleResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverIdleResult.md)

  ↳ [`QueryObserverLoadingErrorResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverLoadingErrorResult.md)

  ↳ [`QueryObserverLoadingResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverLoadingResult.md)

  ↳ [`QueryObserverRefetchErrorResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md)

  ↳ [`QueryObserverSuccessResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverSuccessResult.md)

  ↳ [`InfiniteQueryObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.InfiniteQueryObserverBaseResult.md)

## Table of contents

### Properties

- [data](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#data)
- [dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#dataupdatedat)
- [error](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#error)
- [errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#errorupdatedat)
- [failureCount](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#iserror)
- [isFetched](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetched)
- [isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetchedaftermount)
- [isFetching](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isfetching)
- [isIdle](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloading)
- [isLoadingError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloadingerror)
- [isPlaceholderData](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isplaceholderdata)
- [isPreviousData](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#ispreviousdata)
- [isRefetchError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isrefetcherror)
- [isRefetching](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isrefetching)
- [isStale](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isstale)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#issuccess)
- [status](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#status)

### Methods

- [refetch](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#refetch)
- [remove](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#remove)

## Properties

### data

• **data**: `TData`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:211

___

### dataUpdatedAt

• **dataUpdatedAt**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:212

___

### error

• **error**: `TError`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:213

___

### errorUpdatedAt

• **errorUpdatedAt**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:214

___

### failureCount

• **failureCount**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:215

___

### isError

• **isError**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:216

___

### isFetched

• **isFetched**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:217

___

### isFetchedAfterMount

• **isFetchedAfterMount**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:218

___

### isFetching

• **isFetching**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:219

___

### isIdle

• **isIdle**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:220

___

### isLoading

• **isLoading**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:221

___

### isLoadingError

• **isLoadingError**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:222

___

### isPlaceholderData

• **isPlaceholderData**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:223

___

### isPreviousData

• **isPreviousData**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:224

___

### isRefetchError

• **isRefetchError**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:225

___

### isRefetching

• **isRefetching**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:226

___

### isStale

• **isStale**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:227

___

### isSuccess

• **isSuccess**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:228

___

### status

• **status**: [`QueryStatus`](../modules/akashaproject_ui_awf_hooks._internal_.md#querystatus)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:231

## Methods

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

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:229

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:230
