[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryBehavior

# Interface: QueryBehavior<TQueryFnData, TError, TData, TQueryKey\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryBehavior

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryFnData` | `unknown` |
| `TError` | `unknown` |
| `TData` | `TQueryFnData` |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |

## Table of contents

### Methods

- [onFetch](akashaproject_ui_awf_hooks._internal_.QueryBehavior.md#onfetch)

## Methods

### onFetch

▸ **onFetch**(`context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | [`FetchContext`](akashaproject_ui_awf_hooks._internal_.FetchContext.md)<`TQueryFnData`, `TError`, `TData`, `TQueryKey`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/query.d.ts:37
