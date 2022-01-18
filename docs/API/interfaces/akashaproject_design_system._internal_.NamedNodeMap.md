[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / NamedNodeMap

# Interface: NamedNodeMap

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).NamedNodeMap

A collection of Attr objects. Objects inside a NamedNodeMap are not in any particular order, unlike NodeList, although they may be accessed by an index as in an array.

## Indexable

▪ [index: `number`]: [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

## Table of contents

### Properties

- [length](akashaproject_design_system._internal_.NamedNodeMap.md#length)

### Methods

- [getNamedItem](akashaproject_design_system._internal_.NamedNodeMap.md#getnameditem)
- [getNamedItemNS](akashaproject_design_system._internal_.NamedNodeMap.md#getnameditemns)
- [item](akashaproject_design_system._internal_.NamedNodeMap.md#item)
- [removeNamedItem](akashaproject_design_system._internal_.NamedNodeMap.md#removenameditem)
- [removeNamedItemNS](akashaproject_design_system._internal_.NamedNodeMap.md#removenameditemns)
- [setNamedItem](akashaproject_design_system._internal_.NamedNodeMap.md#setnameditem)
- [setNamedItemNS](akashaproject_design_system._internal_.NamedNodeMap.md#setnameditemns)

## Properties

### length

• `Readonly` **length**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10379

## Methods

### getNamedItem

▸ **getNamedItem**(`qualifiedName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10380

___

### getNamedItemNS

▸ **getNamedItemNS**(`namespace`, `localName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10381

___

### item

▸ **item**(`index`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10382

___

### removeNamedItem

▸ **removeNamedItem**(`qualifiedName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10383

___

### removeNamedItemNS

▸ **removeNamedItemNS**(`namespace`, `localName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10384

___

### setNamedItem

▸ **setNamedItem**(`attr`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_design_system._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10385

___

### setNamedItemNS

▸ **setNamedItemNS**(`attr`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_design_system._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10386
