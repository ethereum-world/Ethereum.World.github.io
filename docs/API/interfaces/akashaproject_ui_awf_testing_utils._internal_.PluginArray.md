[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PluginArray

# Interface: PluginArray

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PluginArray

Used to store a list of Plugin objects describing the available plugins; it's returned by the window.navigator.plugins property. The PluginArray is not a JavaScript array, but has the length property and supports accessing individual items using bracket notation (plugins[2]), as well as via item(index) and namedItem("name") methods.

**`deprecated`**

## Indexable

▪ [index: `number`]: [`Plugin`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#plugin)

## Table of contents

### Properties

- [length](akashaproject_ui_awf_testing_utils._internal_.PluginArray.md#length)

### Methods

- [item](akashaproject_ui_awf_testing_utils._internal_.PluginArray.md#item)
- [namedItem](akashaproject_ui_awf_testing_utils._internal_.PluginArray.md#nameditem)
- [refresh](akashaproject_ui_awf_testing_utils._internal_.PluginArray.md#refresh)

## Properties

### length

• `Readonly` **length**: `number`

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11465

## Methods

### item

▸ **item**(`index`): [`Plugin`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#plugin)

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`Plugin`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#plugin)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11467

___

### namedItem

▸ **namedItem**(`name`): [`Plugin`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#plugin)

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`Plugin`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#plugin)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11469

___

### refresh

▸ **refresh**(): `void`

**`deprecated`**

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11471
