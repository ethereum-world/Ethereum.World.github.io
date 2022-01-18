[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / NodeListOf

# Interface: NodeListOf<TNode\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).NodeListOf

## Type parameters

| Name | Type |
| :------ | :------ |
| `TNode` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

## Hierarchy

- [`NodeList`](../modules/akashaproject_design_system._internal_.md#nodelist)

  ↳ **`NodeListOf`**

## Indexable

▪ [index: `number`]: `TNode`

## Table of contents

### Properties

- [length](akashaproject_design_system._internal_.NodeListOf.md#length)

### Methods

- [forEach](akashaproject_design_system._internal_.NodeListOf.md#foreach)
- [item](akashaproject_design_system._internal_.NodeListOf.md#item)

## Properties

### length

• `Readonly` **length**: `number`

Returns the number of nodes in the collection.

#### Inherited from

NodeList.length

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10722

## Methods

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

Performs the specified action for each node in an list.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`value`: `TNode`, `key`: `number`, `parent`: [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<`TNode`\>) => `void` | A function that accepts up to three arguments. forEach calls the callbackfn function one time for each element in the list. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`void`

#### Overrides

NodeList.forEach

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10748

___

### item

▸ **item**(`index`): `TNode`

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

`TNode`

#### Overrides

NodeList.item

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10742
