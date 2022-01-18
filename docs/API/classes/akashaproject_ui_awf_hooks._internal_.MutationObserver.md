[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationObserver

# Class: MutationObserver<TData, TError, TVariables, TContext\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationObserver

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `unknown` |
| `TError` | `unknown` |
| `TVariables` | `void` |
| `TContext` | `unknown` |

## Hierarchy

- [`Subscribable`](akashaproject_ui_awf_hooks._internal_.Subscribable.md)<[`MutationObserverListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationobserverlistener)<`TData`, `TError`, `TVariables`, `TContext`\>\>

  ↳ **`MutationObserver`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#constructor)

### Properties

- [options](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#options)

### Methods

- [getCurrentResult](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#getcurrentresult)
- [hasListeners](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#haslisteners)
- [mutate](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#mutate)
- [onMutationUpdate](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#onmutationupdate)
- [reset](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#reset)
- [setOptions](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#setoptions)
- [subscribe](akashaproject_ui_awf_hooks._internal_.MutationObserver.md#subscribe)

## Constructors

### constructor

• **new MutationObserver**<`TData`, `TError`, `TVariables`, `TContext`\>(`client`, `options`)

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
| `client` | [`QueryClient`](akashaproject_ui_awf_hooks._internal_.QueryClient.md) |
| `options` | [`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Overrides

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[constructor](akashaproject_ui_awf_hooks._internal_.Subscribable.md#constructor)

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:12

## Properties

### options

• **options**: [`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:7

## Methods

### getCurrentResult

▸ **getCurrentResult**(): [`MutationObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationobserverresult)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Returns

[`MutationObserverResult`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationobserverresult)<`TData`, `TError`, `TVariables`, `TContext`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:17

___

### hasListeners

▸ **hasListeners**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[hasListeners](akashaproject_ui_awf_hooks._internal_.Subscribable.md#haslisteners)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:6

___

### mutate

▸ **mutate**(`variables?`, `options?`): `Promise`<`TData`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `variables?` | `TVariables` |
| `options?` | [`MutateOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutateOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`Promise`<`TData`\>

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:19

___

### onMutationUpdate

▸ **onMutationUpdate**(`action`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `action` | [`Action`](../modules/akashaproject_ui_awf_hooks._internal_.md#action)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:16

___

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:18

___

### setOptions

▸ **setOptions**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`MutationObserverOptions`](../interfaces/akashaproject_ui_awf_hooks._internal_.MutationObserverOptions.md)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationObserver.d.ts:14

___

### subscribe

▸ **subscribe**(`listener?`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener?` | [`MutationObserverListener`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationobserverlistener)<`TData`, `TError`, `TVariables`, `TContext`\> |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Inherited from

[Subscribable](akashaproject_ui_awf_hooks._internal_.Subscribable.md).[subscribe](akashaproject_ui_awf_hooks._internal_.Subscribable.md#subscribe)

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:5
