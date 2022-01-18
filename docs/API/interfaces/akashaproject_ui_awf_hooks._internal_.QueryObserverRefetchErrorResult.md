[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryObserverRefetchErrorResult

# Interface: QueryObserverRefetchErrorResult<TData, TError\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryObserverRefetchErrorResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |

## Hierarchy

- [`QueryObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md)<`TData`, `TError`\>

  ↳ **`QueryObserverRefetchErrorResult`**

## Table of contents

### Properties

- [data](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#data)
- [dataUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#dataupdatedat)
- [error](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#error)
- [errorUpdatedAt](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#errorupdatedat)
- [failureCount](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#iserror)
- [isFetched](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isfetched)
- [isFetchedAfterMount](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isfetchedaftermount)
- [isFetching](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isfetching)
- [isIdle](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isloading)
- [isLoadingError](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isloadingerror)
- [isPlaceholderData](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isplaceholderdata)
- [isPreviousData](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#ispreviousdata)
- [isRefetchError](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isrefetcherror)
- [isRefetching](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isrefetching)
- [isStale](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#isstale)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#issuccess)
- [status](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#status)

### Methods

- [refetch](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#refetch)
- [remove](akashaproject_ui_awf_hooks._internal_.QueryObserverRefetchErrorResult.md#remove)

## Properties

### data

• **data**: `TData`

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[data](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:267

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

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:268

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

### isError

• **isError**: ``true``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#iserror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:269

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

### isIdle

• **isIdle**: ``false``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:270

___

### isLoading

• **isLoading**: ``false``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:271

___

### isLoadingError

• **isLoadingError**: ``false``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isLoadingError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isloadingerror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:272

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

• **isRefetchError**: ``true``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isRefetchError](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#isrefetcherror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:273

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

• **isSuccess**: ``false``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[isSuccess](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#issuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:274

___

### status

• **status**: ``"error"``

#### Overrides

[QueryObserverBaseResult](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.QueryObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:275

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
