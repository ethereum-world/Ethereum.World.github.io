[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryObserver

# Class: QueryObserver<TQueryFnData, TError, TData, TQueryData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryObserver

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Hierarchy

- [`Subscribable`](akashaproject_ui_awf_hooks._internal_.Subscribable.md)<[`QueryObserverListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverlistener)<`TData`, `TError`\>\>

  ↳ **`QueryObserver`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#constructor)

### Properties

- [options](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#options)

### Methods

- [destroy](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#destroy)
- [fetchOptimistic](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#fetchoptimistic)
- [getCurrentQuery](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#getcurrentquery)
- [getCurrentResult](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#getcurrentresult)
- [getNextResult](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#getnextresult)
- [getOptimisticResult](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#getoptimisticresult)
- [hasListeners](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#haslisteners)
- [onQueryUpdate](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#onqueryupdate)
- [refetch](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#refetch)
- [remove](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#remove)
- [setOptions](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#setoptions)
- [shouldFetchOnReconnect](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#shouldfetchonreconnect)
- [shouldFetchOnWindowFocus](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#shouldfetchonwindowfocus)
- [subscribe](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#subscribe)
- [trackResult](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#trackresult)
- [updateResult](akashaproject_ui_awf_hooks._internal_.QueryObserver.md#updateresult)

## Constructors

### constructor

• **new QueryObserver**<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>(`client`, `options`)

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`QueryClient`](akashaproject_ui_awf_hooks._internal_.QueryClient.md) |
| `options` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Overrides

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[constructor](akashaproject_ui_awf_hooks._internal_.Subscribable.md#constructor)

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:31

## Properties

### options

• **options**: [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:17

## Methods

### destroy

▸ **destroy**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:37

___

### fetchOptimistic

▸ **fetchOptimistic**(`options`): `Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Returns

`Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:46

___

### getCurrentQuery

▸ **getCurrentQuery**(): [`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TQueryData`, `TQueryKey`\>

#### Returns

[`Query`](akashaproject_ui_awf_hooks._internal_.Query.md)<`TQueryFnData`, `TError`, `TQueryData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:43

___

### getCurrentResult

▸ **getCurrentResult**(): [`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Returns

[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:40

___

### getNextResult

▸ **getNextResult**(`options?`): `Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ResultOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.ResultOptions.md) |

#### Returns

`Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:42

___

### getOptimisticResult

▸ **getOptimisticResult**(`options`): [`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Returns

[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:39

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

### onQueryUpdate

▸ **onQueryUpdate**(`action`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `action` | [`Action`](../modules/akashaproject_ui_awf_hooks._internal_.md#action)<`TData`, `TError`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:60

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
| `options?` | [`RefetchOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchOptions.md) & [`RefetchQueryFilters`](../interfaces/akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)<`TPageData`\> |

#### Returns

`Promise`<[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:45

___

### remove

▸ **remove**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:44

___

### setOptions

▸ **setOptions**(`options?`, `notifyOptions?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |
| `notifyOptions?` | [`NotifyOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.NotifyOptions.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:38

___

### shouldFetchOnReconnect

▸ **shouldFetchOnReconnect**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:35

___

### shouldFetchOnWindowFocus

▸ **shouldFetchOnWindowFocus**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:36

___

### subscribe

▸ **subscribe**(`listener?`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener?` | [`QueryObserverListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverlistener)<`TData`, `TError`\> |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[subscribe](akashaproject_ui_awf_hooks._internal_.Subscribable.md#subscribe)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:5

___

### trackResult

▸ **trackResult**(`result`, `defaultedOptions`): [`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `result` | [`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\> |
| `defaultedOptions` | [`QueryObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryObserverOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryData`, `TQueryKey`\> |

#### Returns

[`QueryObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:41

___

### updateResult

▸ **updateResult**(`notifyOptions?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `notifyOptions?` | [`NotifyOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.NotifyOptions.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryObserver.d.ts:58
