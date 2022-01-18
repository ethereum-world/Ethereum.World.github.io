[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserverIdleResult

# Interface: MutationObserverIdleResult<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserverIdleResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`MutationObserverBaseResult`](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md)<`TData`, `TError`, `TVariables`, `TContext`\>

  ↳ **`MutationObserverIdleResult`**

## Table of contents

### Properties

- [context](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#context)
- [data](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#data)
- [error](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#error)
- [failureCount](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#failurecount)
- [isError](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#iserror)
- [isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#isidle)
- [isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#isloading)
- [isPaused](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#ispaused)
- [isSuccess](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#issuccess)
- [mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#mutate)
- [status](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#status)
- [variables](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#variables)

### Methods

- [reset](akashaproject_ui_awf_hooks._internal_.MutationObserverIdleResult.md#reset)

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:388

___

### error

• **error**: ``null``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[error](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#error)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:389

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:390

___

### isIdle

• **isIdle**: ``true``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isIdle](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isidle)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:391

___

### isLoading

• **isLoading**: ``false``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[isLoading](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#isloading)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:392

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

ui/hooks/node_modules/react-query/types/core/types.d.ts:393

___

### mutate

• **mutate**: [`MutateFunction`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutatefunction)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Inherited from

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[mutate](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#mutate)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:384

___

### status

• **status**: ``"idle"``

#### Overrides

[MutationObserverBaseResult](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md).[status](akashaproject_ui_awf_hooks._internal_.MutationObserverBaseResult.md#status)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:394

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
