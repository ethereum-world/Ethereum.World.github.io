[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / HTMLCollectionOf

# Interface: HTMLCollectionOf<T\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).HTMLCollectionOf

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Element` |

## Hierarchy

- [`HTMLCollectionBase`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionBase.md)

  ↳ **`HTMLCollectionOf`**

## Indexable

▪ [index: `number`]: `T`

## Table of contents

### Properties

- [length](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md#length)

### Methods

- [item](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md#item)
- [namedItem](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md#nameditem)

## Properties

### length

• `Readonly` **length**: `number`

Sets or retrieves the number of objects in a collection.

#### Inherited from

[HTMLCollectionBase](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionBase.md).[length](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionBase.md#length)

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

[HTMLCollectionBase](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionBase.md).[item](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionBase.md#item)

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
