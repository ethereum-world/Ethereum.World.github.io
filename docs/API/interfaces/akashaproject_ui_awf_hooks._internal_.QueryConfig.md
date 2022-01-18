[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryConfig

# Interface: QueryConfig<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryConfig

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `TQueryFnData` |
| `TError` | `TError` |
| `TData` | `TData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Table of contents

### Properties

- [cache](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#cache)
- [defaultOptions](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#defaultoptions)
- [meta](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#meta)
- [options](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#options)
- [queryHash](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#queryhash)
- [queryKey](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#querykey)
- [state](akashaproject_ui_awf_hooks._internal_.QueryConfig.md#state)

## Properties

### cache

• **cache**: [`QueryCache`](../classes/akashaproject_ui_awf_hooks._internal_.QueryCache.md)

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:6

___

### defaultOptions

• `Optional` **defaultOptions**: [`QueryOptions`](akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:10

___

### meta

• **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:12

___

### options

• `Optional` **options**: [`QueryOptions`](akashaproject_ui_awf_hooks._internal_.QueryOptions.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:9

___

### queryHash

• **queryHash**: `string`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:8

___

### queryKey

• **queryKey**: `TQueryKey`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:7

___

### state

• `Optional` **state**: [`QueryState`](akashaproject_ui_awf_hooks._internal_.QueryState.md)<`TData`, `TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:11
