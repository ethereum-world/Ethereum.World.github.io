[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / NodeIterator

# Interface: NodeIterator

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).NodeIterator

An iterator over the members of a list of the nodes in a subtree of the DOM. The nodes will be returned in document order.

## Table of contents

### Properties

- [filter](akashaproject_design_system._internal_.NodeIterator.md#filter)
- [pointerBeforeReferenceNode](akashaproject_design_system._internal_.NodeIterator.md#pointerbeforereferencenode)
- [referenceNode](akashaproject_design_system._internal_.NodeIterator.md#referencenode)
- [root](akashaproject_design_system._internal_.NodeIterator.md#root)
- [whatToShow](akashaproject_design_system._internal_.NodeIterator.md#whattoshow)

### Methods

- [detach](akashaproject_design_system._internal_.NodeIterator.md#detach)
- [nextNode](akashaproject_design_system._internal_.NodeIterator.md#nextnode)
- [previousNode](akashaproject_design_system._internal_.NodeIterator.md#previousnode)

## Properties

### filter

• `Readonly` **filter**: [`NodeFilter`](../modules/akashaproject_design_system._internal_.md#nodefilter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10701

___

### pointerBeforeReferenceNode

• `Readonly` **pointerBeforeReferenceNode**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10702

___

### referenceNode

• `Readonly` **referenceNode**: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10703

___

### root

• `Readonly` **root**: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10704

___

### whatToShow

• `Readonly` **whatToShow**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10705

## Methods

### detach

▸ **detach**(): `void`

**`deprecated`**

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10707

___

### nextNode

▸ **nextNode**(): [`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Returns

[`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10708

___

### previousNode

▸ **previousNode**(): [`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Returns

[`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10709
