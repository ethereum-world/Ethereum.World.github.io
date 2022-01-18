[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / Mutation

# Class: Mutation<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).Mutation

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.Mutation.md#constructor)

### Properties

- [meta](akashaproject_ui_awf_hooks._internal_.Mutation.md#meta)
- [mutationId](akashaproject_ui_awf_hooks._internal_.Mutation.md#mutationid)
- [options](akashaproject_ui_awf_hooks._internal_.Mutation.md#options)
- [state](akashaproject_ui_awf_hooks._internal_.Mutation.md#state)

### Methods

- [addObserver](akashaproject_ui_awf_hooks._internal_.Mutation.md#addobserver)
- [cancel](akashaproject_ui_awf_hooks._internal_.Mutation.md#cancel)
- [continue](akashaproject_ui_awf_hooks._internal_.Mutation.md#continue)
- [execute](akashaproject_ui_awf_hooks._internal_.Mutation.md#execute)
- [removeObserver](akashaproject_ui_awf_hooks._internal_.Mutation.md#removeobserver)
- [setState](akashaproject_ui_awf_hooks._internal_.Mutation.md#setstate)

## Constructors

### constructor

• **new Mutation**<`TData`, `TError`, `TVariables`, `TContext`\>(`config`)

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`MutationConfig`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationConfig.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:56

## Properties

### meta

• **meta**: [`MutationMeta`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationmeta)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:52

___

### mutationId

• **mutationId**: `number`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:51

___

### options

• **options**: [`MutationOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:50

___

### state

• **state**: [`MutationState`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationState.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:49

## Methods

### addObserver

▸ **addObserver**(`observer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `observer` | [`MutationObserver`](akashaproject_ui_awf_hooks._internal_.MutationObserver.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:58

___

### cancel

▸ **cancel**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:60

___

### continue

▸ **continue**(): `Promise`<`TData`\>

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:61

___

### execute

▸ **execute**(): `Promise`<`TData`\>

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:62

___

### removeObserver

▸ **removeObserver**(`observer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `observer` | [`MutationObserver`](akashaproject_ui_awf_hooks._internal_.MutationObserver.md)<`any`, `any`, `any`, `any`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:59

___

### setState

▸ **setState**(`state`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | [`MutationState`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationState.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutation.d.ts:57
