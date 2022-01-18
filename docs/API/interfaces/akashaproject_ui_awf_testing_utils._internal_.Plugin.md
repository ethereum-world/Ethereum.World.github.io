[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Plugin

# Interface: Plugin

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Plugin

Provides information about a browser plugin.

**`deprecated`**

## Indexable

▪ [index: `number`]: [`MimeType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetype)

## Table of contents

### Properties

- [description](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#description)
- [filename](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#filename)
- [length](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#length)
- [name](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#name)

### Methods

- [item](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#item)
- [namedItem](akashaproject_ui_awf_testing_utils._internal_.Plugin.md#nameditem)

## Properties

### description

• `Readonly` **description**: `string`

Returns the plugin's description.

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11427

___

### filename

• `Readonly` **filename**: `string`

Returns the plugin library's filename, if applicable on the current platform.

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11432

___

### length

• `Readonly` **length**: `number`

Returns the number of MIME types, represented by MimeType objects, supported by the plugin.

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11437

___

### name

• `Readonly` **name**: `string`

Returns the plugin's name.

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11442

## Methods

### item

▸ **item**(`index`): [`MimeType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetype)

Returns the specified MimeType object.

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`MimeType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11447

___

### namedItem

▸ **namedItem**(`name`): [`MimeType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetype)

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`MimeType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11449
