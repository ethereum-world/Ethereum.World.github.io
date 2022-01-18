[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserverOptions

# Interface: MutationObserverOptions<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserverOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`MutationOptions`](akashaproject_ui_awf_hooks._internal_.MutationOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\>

  ↳ **`MutationObserverOptions`**

## Table of contents

### Properties

- [\_defaulted](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#_defaulted)
- [meta](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#meta)
- [mutationFn](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#mutationfn)
- [mutationKey](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#mutationkey)
- [retry](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#retry)
- [retryDelay](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#retrydelay)
- [useErrorBoundary](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#useerrorboundary)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#variables)

### Methods

- [onError](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#onerror)
- [onMutate](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#onmutate)
- [onSettled](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#onsettled)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md#onsuccess)

## Properties

### \_defaulted

• `Optional` **\_defaulted**: `boolean`

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[_defaulted](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#_defaulted)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:367

___

### meta

• `Optional` **meta**: [`MutationMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationmeta)

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[meta](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#meta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:368

___

### mutationFn

• `Optional` **mutationFn**: [`MutationFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationfunction)<`TData`, `TVariables`\>

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[mutationFn](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#mutationfn)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:358

___

### mutationKey

• `Optional` **mutationKey**: [`MutationKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationkey)

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[mutationKey](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#mutationkey)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:359

___

### retry

• `Optional` **retry**: [`RetryValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retryvalue)<`TError`\>

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[retry](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#retry)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:365

___

### retryDelay

• `Optional` **retryDelay**: [`RetryDelayValue`](../modules/akashaproject_ui_awf_hooks._internal_.md#retrydelayvalue)<`TError`\>

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[retryDelay](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#retrydelay)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:366

___

### useErrorBoundary

• `Optional` **useErrorBoundary**: `boolean` \| (`error`: `TError`) => `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:371

___

### variables

• `Optional` **variables**: `TVariables`

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[variables](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#variables)

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

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[onError](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onerror)

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

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[onMutate](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onmutate)

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

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[onSettled](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onsettled)

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

#### Inherited from

[MutationOptions](akashaproject_ui_awf_hooks._internal_.MutationOptions.md).[onSuccess](akashaproject_ui_awf_hooks._internal_.MutationOptions.md#onsuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:362
