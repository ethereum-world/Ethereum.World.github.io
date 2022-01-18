[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / HTMLCollectionOf

# Interface: HTMLCollectionOf<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).HTMLCollectionOf

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Element` |

## Hierarchy

- [`HTMLCollectionBase`](akashaproject_design_system._internal_.HTMLCollectionBase.md)

  ↳ **`HTMLCollectionOf`**

## Indexable

▪ [index: `number`]: `T`

## Table of contents

### Properties

- [length](akashaproject_design_system._internal_.HTMLCollectionOf.md#length)

### Methods

- [item](akashaproject_design_system._internal_.HTMLCollectionOf.md#item)
- [namedItem](akashaproject_design_system._internal_.HTMLCollectionOf.md#nameditem)

## Properties

### length

• `Readonly` **length**: `number`

Sets or retrieves the number of objects in a collection.

#### Inherited from

[HTMLCollectionBase](akashaproject_design_system._internal_.HTMLCollectionBase.md).[length](akashaproject_design_system._internal_.HTMLCollectionBase.md#length)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6268

## Methods

### item

▸ **item**(`index`): `T`

Retrieves an object from various collections.

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

`T`

#### Overrides

[HTMLCollectionBase](akashaproject_design_system._internal_.HTMLCollectionBase.md).[item](akashaproject_design_system._internal_.HTMLCollectionBase.md#item)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6289

___

### namedItem

▸ **namedItem**(`name`): `T`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`T`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6290
