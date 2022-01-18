[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryFunctionContext

# Interface: QueryFunctionContext<TQueryKey, TPageParam\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryFunctionContext

## Type parameters

| Name | Type |
| :------ | :------ |
| `TQueryKey` | extends [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) = [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey) |
| `TPageParam` | `any` |

## Table of contents

### Properties

- [meta](akashaproject_ui_awf_hooks._internal_.QueryFunctionContext.md#meta)
- [pageParam](akashaproject_ui_awf_hooks._internal_.QueryFunctionContext.md#pageparam)
- [queryKey](akashaproject_ui_awf_hooks._internal_.QueryFunctionContext.md#querykey)
- [signal](akashaproject_ui_awf_hooks._internal_.QueryFunctionContext.md#signal)

## Properties

### meta

• **meta**: [`QueryMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#querymeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:12

___

### pageParam

• `Optional` **pageParam**: `TPageParam`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:11

___

### queryKey

• **queryKey**: [`EnsuredQueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#ensuredquerykey)<`TQueryKey`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:9

___

### signal

• `Optional` **signal**: `AbortSignal`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:10
