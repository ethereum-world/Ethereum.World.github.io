[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / ResetQueryFilters

# Interface: ResetQueryFilters<TPageData\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).ResetQueryFilters

## Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

## Hierarchy

- [`QueryFilters`](akashaproject_ui_awf_hooks._internal_.QueryFilters.md)

- [`RefetchPageFilters`](akashaproject_ui_awf_hooks._internal_.RefetchPageFilters.md)<`TPageData`\>

  ↳ **`ResetQueryFilters`**

## Table of contents

### Properties

- [active](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#active)
- [exact](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#exact)
- [fetching](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#fetching)
- [inactive](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#inactive)
- [queryKey](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#querykey)
- [stale](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#stale)

### Methods

- [predicate](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#predicate)
- [refetchPage](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md#refetchpage)

## Properties

### active

• `Optional` **active**: `boolean`

Include or exclude active queries

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[active](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#active)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:9

___

### exact

• `Optional` **exact**: `boolean`

Match query key exactly

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[exact](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#exact)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:13

___

### fetching

• `Optional` **fetching**: `boolean`

Include or exclude fetching queries

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[fetching](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#fetching)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:33

___

### inactive

• `Optional` **inactive**: `boolean`

Include or exclude inactive queries

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[inactive](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#inactive)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:17

___

### queryKey

• `Optional` **queryKey**: [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)

Include queries matching this query key

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[queryKey](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#querykey)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:25

___

### stale

• `Optional` **stale**: `boolean`

Include or exclude stale queries

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[stale](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#stale)

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

#### Inherited from

[QueryFilters](akashaproject_ui_awf_hooks._internal_.QueryFilters.md).[predicate](akashaproject_ui_awf_hooks._internal_.QueryFilters.md#predicate)

#### Defined in

ui/hooks/node_modules/react-query/types/core/utils.d.ts:21

___

### refetchPage

▸ `Optional` **refetchPage**(`lastPage`, `index`, `allPages`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lastPage` | `TPageData` |
| `index` | `number` |
| `allPages` | `TPageData`[] |

#### Returns

`boolean`

#### Inherited from

[RefetchPageFilters](akashaproject_ui_awf_hooks._internal_.RefetchPageFilters.md).[refetchPage](akashaproject_ui_awf_hooks._internal_.RefetchPageFilters.md#refetchpage)

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:184
