[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / Query

# Class: Query<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).Query

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.Query.md#constructor)

### Properties

- [cacheTime](akashaproject_ui_awf_hooks._internal_.Query.md#cachetime)
- [initialState](akashaproject_ui_awf_hooks._internal_.Query.md#initialstate)
- [meta](akashaproject_ui_awf_hooks._internal_.Query.md#meta)
- [options](akashaproject_ui_awf_hooks._internal_.Query.md#options)
- [queryHash](akashaproject_ui_awf_hooks._internal_.Query.md#queryhash)
- [queryKey](akashaproject_ui_awf_hooks._internal_.Query.md#querykey)
- [revertState](akashaproject_ui_awf_hooks._internal_.Query.md#revertstate)
- [state](akashaproject_ui_awf_hooks._internal_.Query.md#state)

### Methods

- [addObserver](akashaproject_ui_awf_hooks._internal_.Query.md#addobserver)
- [cancel](akashaproject_ui_awf_hooks._internal_.Query.md#cancel)
- [destroy](akashaproject_ui_awf_hooks._internal_.Query.md#destroy)
- [fetch](akashaproject_ui_awf_hooks._internal_.Query.md#fetch)
- [getObserversCount](akashaproject_ui_awf_hooks._internal_.Query.md#getobserverscount)
- [invalidate](akashaproject_ui_awf_hooks._internal_.Query.md#invalidate)
- [isActive](akashaproject_ui_awf_hooks._internal_.Query.md#isactive)
- [isFetching](akashaproject_ui_awf_hooks._internal_.Query.md#isfetching)
- [isStale](akashaproject_ui_awf_hooks._internal_.Query.md#isstale)
- [isStaleByTime](akashaproject_ui_awf_hooks._internal_.Query.md#isstalebytime)
- [onFocus](akashaproject_ui_awf_hooks._internal_.Query.md#onfocus)
- [onOnline](akashaproject_ui_awf_hooks._internal_.Query.md#ononline)
- [removeObserver](akashaproject_ui_awf_hooks._internal_.Query.md#removeobserver)
- [reset](akashaproject_ui_awf_hooks._internal_.Query.md#reset)
- [setData](akashaproject_ui_awf_hooks._internal_.Query.md#setdata)
- [setDefaultOptions](akashaproject_ui_awf_hooks._internal_.Query.md#setdefaultoptions)
- [setState](akashaproject_ui_awf_hooks._internal_.Query.md#setstate)

## Constructors

### constructor

• **new Query**<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>(`config`)

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
| `config` | [`QueryConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryConfig.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:94

## Properties

### cacheTime

• **cacheTime**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:84

___

### initialState

• **initialState**: [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:81

___

### meta

• **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:85

___

### options

• **options**: [`QueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:80

___

### queryHash

• **queryHash**: `string`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:79

___

### queryKey

• **queryKey**: `TQueryKey`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:78

___

### revertState

• `Optional` **revertState**: [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:82

___

### state

• **state**: [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:83

## Methods

### addObserver

▸ **addObserver**(`observer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `observer` | [`QueryObserver`](akashaproject_ui_awf_hooks._internal_.QueryObserver.md)<`any`, `any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:111

___

### cancel

▸ **cancel**(`options?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`CancelOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.CancelOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:102

___

### destroy

▸ **destroy**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:103

___

### fetch

▸ **fetch**(`options?`, `fetchOptions?`): `Promise`<`TData`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`QueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |
| `fetchOptions?` | [`FetchOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.FetchOptions.md) |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:115

___

### getObserversCount

▸ **getObserversCount**(): `number`

#### Returns

`number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:113

___

### invalidate

▸ **invalidate**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:114

___

### isActive

▸ **isActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:105

___

### isFetching

▸ **isFetching**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:106

___

### isStale

▸ **isStale**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:107

___

### isStaleByTime

▸ **isStaleByTime**(`staleTime?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `staleTime?` | `number` |

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:108

___

### onFocus

▸ **onFocus**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:109

___

### onOnline

▸ **onOnline**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:110

___

### removeObserver

▸ **removeObserver**(`observer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `observer` | [`QueryObserver`](akashaproject_ui_awf_hooks._internal_.QueryObserver.md)<`any`, `any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:112

___

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:104

___

### setData

▸ **setData**(`updater`, `options?`): `TData`

#### Parameters

| Name | Type |
| :------ | :------ |
| `updater` | [`Updater`](../modules/akashaproject_ui_awf_hooks._internal_.md#updater)<`TData`, `TData`\> |
| `options?` | [`SetDataOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.SetDataOptions.md) |

#### Returns

`TData`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:100

___

### setDefaultOptions

▸ **setDefaultOptions**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`QueryOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:96

___

### setState

▸ **setState**(`state`, `setStateOptions?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | [`QueryState`](../interfaces/akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\> |
| `setStateOptions?` | [`SetStateOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.SetStateOptions.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:101
