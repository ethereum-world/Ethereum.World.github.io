[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / HTMLAllCollection

# Interface: HTMLAllCollection

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).HTMLAllCollection

## Indexable

▪ [index: `number`]: `Element`

## Table of contents

### Properties

- [length](akashaproject_ui_awf_testing_utils._internal_.HTMLAllCollection.md#length)

### Methods

- [item](akashaproject_ui_awf_testing_utils._internal_.HTMLAllCollection.md#item)
- [namedItem](akashaproject_ui_awf_testing_utils._internal_.HTMLAllCollection.md#nameditem)

## Properties

### length

• `Readonly` **length**: `number`

Returns the number of elements in the collection.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5951

## Methods

### item

▸ **item**(`nameOrIndex?`): `Element` \| [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

Returns the item with index index from the collection (determined by tree order).

#### Parameters

| Name | Type |
| :------ | :------ |
| `nameOrIndex?` | `string` |

#### Returns

`Element` \| [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5955

___

### namedItem

▸ **namedItem**(`name`): `Element` \| [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

Returns the item with ID or name name from the collection.

If there are multiple matching items, then an HTMLCollection object containing all those elements is returned.

Only button, form, iframe, input, map, meta, object, select, and textarea elements can have a name for the purpose of this method; their name is given by the value of their name attribute.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Element` \| [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5963
