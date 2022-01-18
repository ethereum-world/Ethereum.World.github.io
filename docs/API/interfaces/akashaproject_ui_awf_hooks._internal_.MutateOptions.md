[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutateOptions

# Interface: MutateOptions<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutateOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Table of contents

### Methods

- [onError](akashaproject_ui_awf_hooks._internal_.MutateOptions.md#onerror)
- [onSettled](akashaproject_ui_awf_hooks._internal_.MutateOptions.md#onsettled)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.MutateOptions.md#onsuccess)

## Methods

### onError

▸ `Optional` **onError**(`error`, `variables`, `context`): `void` \| `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | `TError` |
| `variables` | `TVariables` |
| `context` | `TContext` |

#### Returns

`void` \| `Promise`<`unknown`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:375

___

### onSettled

▸ `Optional` **onSettled**(`data`, `error`, `variables`, `context`): `void` \| `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `TData` |
| `error` | `TError` |
| `variables` | `TVariables` |
| `context` | `TContext` |

#### Returns

`void` \| `Promise`<`unknown`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:376

___

### onSuccess

▸ `Optional` **onSuccess**(`data`, `variables`, `context`): `void` \| `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `TData` |
| `variables` | `TVariables` |
| `context` | `TContext` |

#### Returns

`void` \| `Promise`<`unknown`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:374
