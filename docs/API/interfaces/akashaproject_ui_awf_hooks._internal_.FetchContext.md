[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / FetchContext

# Interface: FetchContext<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).FetchContext

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `TQueryFnData` |
| `TError` | `TError` |
| `TData` | `TData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Table of contents

### Properties

- [fetchOptions](akashaproject_ui_awf_hooks._internal_.FetchContext.md#fetchoptions)
- [meta](akashaproject_ui_awf_hooks._internal_.FetchContext.md#meta)
- [options](akashaproject_ui_awf_hooks._internal_.FetchContext.md#options)
- [queryKey](akashaproject_ui_awf_hooks._internal_.FetchContext.md#querykey)
- [state](akashaproject_ui_awf_hooks._internal_.FetchContext.md#state)

### Methods

- [fetchFn](akashaproject_ui_awf_hooks._internal_.FetchContext.md#fetchfn)

## Properties

### fetchOptions

• `Optional` **fetchOptions**: [`FetchOptions`](akashaproject_ui_awf_hooks._internal_.FetchOptions.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:30

___

### meta

• **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:34

___

### options

• **options**: [`QueryOptions`](akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `any`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:31

___

### queryKey

• **queryKey**: [`EnsuredQueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#ensuredquerykey)<`TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:32

___

### state

• **state**: [`QueryState`](akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:33

## Methods

### fetchFn

▸ **fetchFn**(): `unknown`

#### Returns

`unknown`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:29
