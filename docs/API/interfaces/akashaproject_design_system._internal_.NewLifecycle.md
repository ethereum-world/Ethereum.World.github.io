[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / NewLifecycle

# Interface: NewLifecycle<P, S, SS\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).NewLifecycle

## Type parameters

| Name |
| :------ |
| `P` |
| `S` |
| `SS` |

## Hierarchy

- **`NewLifecycle`**

  ↳ [`ComponentLifecycle`](akashaproject_design_system._internal_.ComponentLifecycle.md)

## Table of contents

### Methods

- [componentDidUpdate](akashaproject_design_system._internal_.NewLifecycle.md#componentdidupdate)
- [getSnapshotBeforeUpdate](akashaproject_design_system._internal_.NewLifecycle.md#getsnapshotbeforeupdate)

## Methods

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `snapshot?`): `void`

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<`P`\> |
| `prevState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<`S`\> |
| `snapshot?` | `SS` |

#### Returns

`void`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:682

___

### getSnapshotBeforeUpdate

▸ `Optional` **getSnapshotBeforeUpdate**(`prevProps`, `prevState`): `SS`

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<`P`\> |
| `prevState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<`S`\> |

#### Returns

`SS`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:676
