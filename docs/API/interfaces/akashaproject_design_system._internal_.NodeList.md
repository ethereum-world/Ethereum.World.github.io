[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / NodeList

# Interface: NodeList

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).NodeList

NodeList objects are collections of nodes, usually returned by properties such as Node.childNodes and methods such as document.querySelectorAll().

## Indexable

▪ [index: `number`]: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

## Table of contents

### Properties

- [length](akashaproject_design_system._internal_.NodeList.md#length)

### Methods

- [forEach](akashaproject_design_system._internal_.NodeList.md#foreach)
- [item](akashaproject_design_system._internal_.NodeList.md#item)

## Properties

### length

• `Readonly` **length**: `number`

Returns the number of nodes in the collection.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10722

## Methods

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

Performs the specified action for each node in an list.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`value`: [`Node`](../modules/akashaproject_design_system._internal_.md#node), `key`: `number`, `parent`: [`NodeList`](../modules/akashaproject_design_system._internal_.md#nodelist)) => `void` | A function that accepts up to three arguments. forEach calls the callbackfn function one time for each element in the list. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10732

___

### item

▸ **item**(`index`): [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns the node with index index from the collection. The nodes are sorted in tree order.

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10726
