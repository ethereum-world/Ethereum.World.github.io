[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationOptions

# Interface: MutationOptions<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- **`MutationOptions`**

  ↳ [`MutationObserverOptions`](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)

## Table of contents

### Properties

- [\_defaulted](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#_defaulted)
- [meta](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#meta)
- [mutationFn](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#mutationfn)
- [mutationKey](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#mutationkey)
- [retry](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#retry)
- [retryDelay](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#retrydelay)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#variables)

### Methods

- [onError](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onerror)
- [onMutate](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onmutate)
- [onSettled](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onsettled)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onsuccess)

## Properties

### \_defaulted

• `Optional` **\_defaulted**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:367

___

### meta

• `Optional` **meta**: [`MutationMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationmeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:368

___

### mutationFn

• `Optional` **mutationFn**: [`MutationFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationfunction)<`TData`, `TVariables`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:358

___

### mutationKey

• `Optional` **mutationKey**: [`MutationKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationkey)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:359

___

### retry

• `Optional` **retry**: [`RetryValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retryvalue)<`TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:365

___

### retryDelay

• `Optional` **retryDelay**: [`RetryDelayValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retrydelayvalue)<`TError`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:366

___

### variables

• `Optional` **variables**: `TVariables`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:360

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:363

___

### onMutate

▸ `Optional` **onMutate**(`variables`): `TContext` \| `Promise`<`TContext`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `variables` | `TVariables` |

#### Returns

`TContext` \| `Promise`<`TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:361

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:364

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:362
