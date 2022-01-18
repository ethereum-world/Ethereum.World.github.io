[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationFilters

# Interface: MutationFilters

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationFilters

## Table of contents

### Properties

- [exact](akashaproject_ui_awf_hooks._internal_.MutationFilters.md#exact)
- [fetching](akashaproject_ui_awf_hooks._internal_.MutationFilters.md#fetching)
- [mutationKey](akashaproject_ui_awf_hooks._internal_.MutationFilters.md#mutationkey)

### Methods

- [predicate](akashaproject_ui_awf_hooks._internal_.MutationFilters.md#predicate)

## Properties

### exact

• `Optional` **exact**: `boolean`

Match mutation key exactly

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:39

___

### fetching

• `Optional` **fetching**: `boolean`

Include or exclude fetching mutations

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:51

___

### mutationKey

• `Optional` **mutationKey**: [`MutationKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#mutationkey)

Include mutations matching this mutation key

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:47

## Methods

### predicate

▸ `Optional` **predicate**(`mutation`): `boolean`

Include mutations matching this predicate function

#### Parameters

| Name | Type |
| :------ | :------ |
| `mutation` | [`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`any`, `any`, `any`, `unknown`\> |

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:43
