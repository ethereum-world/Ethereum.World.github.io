[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserverLoadingResult

# Interface: MutationObserverLoadingResult<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserverLoadingResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`MutationObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md)<`TData`, `TError`, `TVariables`, `TContext`\>

  ↳ **`MutationObserverLoadingResult`**

## Table of contents

### Properties

- [context](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#context)
- [data](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#data)
- [error](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#error)
- [failureCount](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#iserror)
- [isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#isloading)
- [isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#ispaused)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#issuccess)
- [mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#mutate)
- [status](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#status)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#variables)

### Methods

- [reset](akashaproject_ui_awf_hooks._internal_.MutationObserverLoadingResult.md#reset)

## Properties

### context

• **context**: `TContext`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[context](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#context)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:13

___

### data

• **data**: `undefined`

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[data](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#data)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:397

___

### error

• **error**: ``null``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:398

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:399

___

### isIdle

• **isIdle**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:400

___

### isLoading

• **isLoading**: ``true``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:401

___

### isPaused

• **isPaused**: `boolean`

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#ispaused)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:17

___

### isSuccess

• **isSuccess**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#issuccess)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:402

___

### mutate

• **mutate**: [`MutateFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutatefunction)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#mutate)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:384

___

### status

• **status**: ``"loading"``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:403

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
