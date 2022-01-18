[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / RefetchPageFilters

# Interface: RefetchPageFilters<TPageData\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).RefetchPageFilters

## Type parameters

| Name | Type |
| :------ | :------ |
| `TPageData` | `unknown` |

## Hierarchy

- **`RefetchPageFilters`**

  ↳ [`RefetchQueryFilters`](akashaproject_ui_awf_hooks._internal_.RefetchQueryFilters.md)

  ↳ [`ResetQueryFilters`](akashaproject_ui_awf_hooks._internal_.ResetQueryFilters.md)

  ↳ [`InvalidateQueryFilters`](akashaproject_ui_awf_hooks._internal_.InvalidateQueryFilters.md)

## Table of contents

### Methods

- [refetchPage](akashaproject_ui_awf_hooks._internal_.RefetchPageFilters.md#refetchpage)

## Methods

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

#### Defined in

ui/hooks/node_modules/react-query/types/core/types.d.ts:184
