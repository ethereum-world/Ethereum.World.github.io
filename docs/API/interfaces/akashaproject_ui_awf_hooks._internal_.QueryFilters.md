[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryFilters

# Interface: QueryFilters

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryFilters

## Hierarchy

- **`QueryFilters`**

  ↳ [`RefetchQueryFilters`](akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)

  ↳ [`ResetQueryFilters`](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md)

  ↳ [`InvalidateQueryFilters`](akashaproject_ui_awf_hooks._internal_.InvalidateQueryFilters.md)

## Table of contents

### Properties

- [active](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#active)
- [exact](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#exact)
- [fetching](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#fetching)
- [inactive](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#inactive)
- [queryKey](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#querykey)
- [stale](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#stale)

### Methods

- [predicate](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#predicate)

## Properties

### active

• `Optional` **active**: `boolean`

Include or exclude active queries

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:9

___

### exact

• `Optional` **exact**: `boolean`

Match query key exactly

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:13

___

### fetching

• `Optional` **fetching**: `boolean`

Include or exclude fetching queries

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:33

___

### inactive

• `Optional` **inactive**: `boolean`

Include or exclude inactive queries

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:17

___

### queryKey

• `Optional` **queryKey**: [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)

Include queries matching this query key

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:25

___

### stale

• `Optional` **stale**: `boolean`

Include or exclude stale queries

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:29

## Methods

### predicate

▸ `Optional` **predicate**(`query`): `boolean`

Include queries matching this predicate function

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | [`Query`](../classes/akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\> |

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:21
