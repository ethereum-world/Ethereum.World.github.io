[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / XPathExpression

# Interface: XPathExpression

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).XPathExpression

This interface is a compiled XPath expression that can be evaluated on a document or specific node to return information its DOM tree.

## Table of contents

### Methods

- [evaluate](akashaproject_design_system._internal_.XPathExpression.md#evaluate)

## Methods

### evaluate

▸ **evaluate**(`contextNode`, `type?`, `result?`): [`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `contextNode` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `type?` | `number` |
| `result?` | [`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult) |

#### Returns

[`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17706
