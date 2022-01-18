[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserverBaseResult

# Interface: MutationObserverBaseResult<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserverBaseResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`MutationState`](akashaproject_ui_awf_hooks._internal_.MutationState.md)<`TData`, `TError`, `TVariables`, `TContext`\>

  ↳ **`MutationObserverBaseResult`**

  ↳↳ [`MutationObserverIdleResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md)

  ↳↳ [`MutationObserverLoadingResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md)

  ↳↳ [`MutationObserverErrorResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverErrorResult.md)

  ↳↳ [`MutationObserverSuccessResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md)

## Table of contents

### Properties

- [context](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#context)
- [data](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#data)
- [error](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#error)
- [failureCount](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#iserror)
- [isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isloading)
- [isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#ispaused)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#issuccess)
- [mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#mutate)
- [status](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#status)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#variables)

### Methods

- [reset](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#reset)

## Properties

### context

• **context**: `TContext`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[context](akashaproject_ui_awf_hooks._internal_.MutationState.md#context)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:13

___

### data

• **data**: `TData`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[data](akashaproject_ui_awf_hooks._internal_.MutationState.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:14

___

### error

• **error**: `TError`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[error](akashaproject_ui_awf_hooks._internal_.MutationState.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:15

___

### failureCount

• **failureCount**: `number`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[failureCount](akashaproject_ui_awf_hooks._internal_.MutationState.md#failurecount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:16

___

### isError

• **isError**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:380

___

### isIdle

• **isIdle**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:381

___

### isLoading

• **isLoading**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:382

___

### isPaused

• **isPaused**: `boolean`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[isPaused](akashaproject_ui_awf_hooks._internal_.MutationState.md#ispaused)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:17

___

### isSuccess

• **isSuccess**: `boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:383

___

### mutate

• **mutate**: [`MutateFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutatefunction)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:384

___

### status

• **status**: [`MutationStatus`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationstatus)

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[status](akashaproject_ui_awf_hooks._internal_.MutationState.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:18

___

### variables

• **variables**: `TVariables`

#### Inherited from

[MutationState](akashaproject_ui_awf_hooks._internal_.MutationState.md).[variables](akashaproject_ui_awf_hooks._internal_.MutationState.md#variables)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:19

## Methods

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:385
