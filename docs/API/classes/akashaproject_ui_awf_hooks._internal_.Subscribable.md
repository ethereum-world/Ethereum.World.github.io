[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / Subscribable

# Class: Subscribable<TListener\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).Subscribable

## Type parameters

| Name | Type |
| :------ | :------ |
| `TListener` | extends `Function` = [`Listener`](../modules/akashaproject_ui_awf_hooks._internal_.md#listener) |

## Hierarchy

- **`Subscribable`**

  ↳ [`MutationObserver`](akashaproject_ui_awf_hooks._internal_.MutationObserver.md)

  ↳ [`MutationCache`](akashaproject_ui_awf_hooks._internal_.MutationCache.md)

  ↳ [`QueryCache`](akashaproject_ui_awf_hooks._internal_.QueryCache.md)

  ↳ [`QueryObserver`](akashaproject_ui_awf_hooks._internal_.QueryObserver.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.Subscribable.md#constructor)

### Methods

- [hasListeners](akashaproject_ui_awf_hooks._internal_.Subscribable.md#haslisteners)
- [subscribe](akashaproject_ui_awf_hooks._internal_.Subscribable.md#subscribe)

## Constructors

### constructor

• **new Subscribable**<`TListener`\>()

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TListener` | extends `Function` = [`Listener`](../modules/akashaproject_ui_awf_hooks._internal_.md#listener) |

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:4

## Methods

### hasListeners

▸ **hasListeners**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:6

___

### subscribe

▸ **subscribe**(`listener?`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener?` | `TListener` |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/subscribable.d.ts:5
