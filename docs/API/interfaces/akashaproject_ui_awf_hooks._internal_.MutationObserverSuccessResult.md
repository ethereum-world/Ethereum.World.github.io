[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserverSuccessResult

# Interface: MutationObserverSuccessResult<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserverSuccessResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`MutationObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md)<`TData`, `TError`, `TVariables`, `TContext`\>

  ↳ **`MutationObserverSuccessResult`**

## Table of contents

### Properties

- [context](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#context)
- [data](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#data)
- [error](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#error)
- [failureCount](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#iserror)
- [isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#isloading)
- [isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#ispaused)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#issuccess)
- [mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#mutate)
- [status](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#status)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#variables)

### Methods

- [reset](akashaproject_ui_awf_hooks._internal_.MutationObserverSuccessResult.md#reset)

## Properties

### context

• **context**: `TContext`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[context](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#context)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:13

___

### data

• **data**: `TData`

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[data](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:415

___

### error

• **error**: ``null``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:416

___

### failureCount

• **failureCount**: `number`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[failureCount](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#failurecount)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:16

___

### isError

• **isError**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isError](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#iserror)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:417

___

### isIdle

• **isIdle**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:418

___

### isLoading

• **isLoading**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:419

___

### isPaused

• **isPaused**: `boolean`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#ispaused)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:17

___

### isSuccess

• **isSuccess**: ``true``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#issuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:420

___

### mutate

• **mutate**: [`MutateFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutatefunction)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#mutate)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:384

___

### status

• **status**: ``"success"``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:421

___

### variables

• **variables**: `TVariables`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[variables](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#variables)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:19

## Methods

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[reset](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#reset)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:385
