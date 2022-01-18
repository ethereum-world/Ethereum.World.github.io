[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / Range

# Interface: Range

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).Range

A fragment of a document that can contain nodes and parts of text nodes.

## Hierarchy

- [`AbstractRange`](../modules/akashaproject_design_system._internal_.md#abstractrange)

  ↳ **`Range`**

## Table of contents

### Properties

- [END\_TO\_END](akashaproject_design_system._internal_.Range.md#end_to_end)
- [END\_TO\_START](akashaproject_design_system._internal_.Range.md#end_to_start)
- [START\_TO\_END](akashaproject_design_system._internal_.Range.md#start_to_end)
- [START\_TO\_START](akashaproject_design_system._internal_.Range.md#start_to_start)
- [collapsed](akashaproject_design_system._internal_.Range.md#collapsed)
- [commonAncestorContainer](akashaproject_design_system._internal_.Range.md#commonancestorcontainer)
- [endContainer](akashaproject_design_system._internal_.Range.md#endcontainer)
- [endOffset](akashaproject_design_system._internal_.Range.md#endoffset)
- [startContainer](akashaproject_design_system._internal_.Range.md#startcontainer)
- [startOffset](akashaproject_design_system._internal_.Range.md#startoffset)

### Methods

- [cloneContents](akashaproject_design_system._internal_.Range.md#clonecontents)
- [cloneRange](akashaproject_design_system._internal_.Range.md#clonerange)
- [collapse](akashaproject_design_system._internal_.Range.md#collapse)
- [compareBoundaryPoints](akashaproject_design_system._internal_.Range.md#compareboundarypoints)
- [comparePoint](akashaproject_design_system._internal_.Range.md#comparepoint)
- [createContextualFragment](akashaproject_design_system._internal_.Range.md#createcontextualfragment)
- [deleteContents](akashaproject_design_system._internal_.Range.md#deletecontents)
- [detach](akashaproject_design_system._internal_.Range.md#detach)
- [extractContents](akashaproject_design_system._internal_.Range.md#extractcontents)
- [getBoundingClientRect](akashaproject_design_system._internal_.Range.md#getboundingclientrect)
- [getClientRects](akashaproject_design_system._internal_.Range.md#getclientrects)
- [insertNode](akashaproject_design_system._internal_.Range.md#insertnode)
- [intersectsNode](akashaproject_design_system._internal_.Range.md#intersectsnode)
- [isPointInRange](akashaproject_design_system._internal_.Range.md#ispointinrange)
- [selectNode](akashaproject_design_system._internal_.Range.md#selectnode)
- [selectNodeContents](akashaproject_design_system._internal_.Range.md#selectnodecontents)
- [setEnd](akashaproject_design_system._internal_.Range.md#setend)
- [setEndAfter](akashaproject_design_system._internal_.Range.md#setendafter)
- [setEndBefore](akashaproject_design_system._internal_.Range.md#setendbefore)
- [setStart](akashaproject_design_system._internal_.Range.md#setstart)
- [setStartAfter](akashaproject_design_system._internal_.Range.md#setstartafter)
- [setStartBefore](akashaproject_design_system._internal_.Range.md#setstartbefore)
- [surroundContents](akashaproject_design_system._internal_.Range.md#surroundcontents)
- [toString](akashaproject_design_system._internal_.Range.md#tostring)

## Properties

### END\_TO\_END

• `Readonly` **END\_TO\_END**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11962

___

### END\_TO\_START

• `Readonly` **END\_TO\_START**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11963

___

### START\_TO\_END

• `Readonly` **START\_TO\_END**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11964

___

### START\_TO\_START

• `Readonly` **START\_TO\_START**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11965

___

### collapsed

• `Readonly` **collapsed**: `boolean`

Returns true if range is collapsed, and false otherwise.

#### Inherited from

AbstractRange.collapsed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1941

___

### commonAncestorContainer

• `Readonly` **commonAncestorContainer**: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns the node, furthest away from the document, that is an ancestor of both range's start node and end node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11931

___

### endContainer

• `Readonly` **endContainer**: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns range's end node.

#### Inherited from

AbstractRange.endContainer

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1945

___

### endOffset

• `Readonly` **endOffset**: `number`

Returns range's end offset.

#### Inherited from

AbstractRange.endOffset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1949

___

### startContainer

• `Readonly` **startContainer**: [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns range's start node.

#### Inherited from

AbstractRange.startContainer

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1953

___

### startOffset

• `Readonly` **startOffset**: `number`

Returns range's start offset.

#### Inherited from

AbstractRange.startOffset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1957

## Methods

### cloneContents

▸ **cloneContents**(): `DocumentFragment`

#### Returns

`DocumentFragment`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11932

___

### cloneRange

▸ **cloneRange**(): [`Range`](../modules/akashaproject_design_system._internal_.md#range)

#### Returns

[`Range`](../modules/akashaproject_design_system._internal_.md#range)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11933

___

### collapse

▸ **collapse**(`toStart?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `toStart?` | `boolean` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11934

___

### compareBoundaryPoints

▸ **compareBoundaryPoints**(`how`, `sourceRange`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `how` | `number` |
| `sourceRange` | [`Range`](../modules/akashaproject_design_system._internal_.md#range) |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11935

___

### comparePoint

▸ **comparePoint**(`node`, `offset`): `number`

Returns −1 if the point is before the range, 0 if the point is in the range, and 1 if the point is after the range.

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `offset` | `number` |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11939

___

### createContextualFragment

▸ **createContextualFragment**(`fragment`): `DocumentFragment`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fragment` | `string` |

#### Returns

`DocumentFragment`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11940

___

### deleteContents

▸ **deleteContents**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11941

___

### detach

▸ **detach**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11942

___

### extractContents

▸ **extractContents**(): `DocumentFragment`

#### Returns

`DocumentFragment`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11943

___

### getBoundingClientRect

▸ **getBoundingClientRect**(): [`DOMRect`](../modules/akashaproject_design_system._internal_.md#domrect)

#### Returns

[`DOMRect`](../modules/akashaproject_design_system._internal_.md#domrect)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11944

___

### getClientRects

▸ **getClientRects**(): [`DOMRectList`](../modules/akashaproject_design_system._internal_.md#domrectlist)

#### Returns

[`DOMRectList`](../modules/akashaproject_design_system._internal_.md#domrectlist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11945

___

### insertNode

▸ **insertNode**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11946

___

### intersectsNode

▸ **intersectsNode**(`node`): `boolean`

Returns whether range intersects node.

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11950

___

### isPointInRange

▸ **isPointInRange**(`node`, `offset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `offset` | `number` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11951

___

### selectNode

▸ **selectNode**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11952

___

### selectNodeContents

▸ **selectNodeContents**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11953

___

### setEnd

▸ **setEnd**(`node`, `offset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `offset` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11954

___

### setEndAfter

▸ **setEndAfter**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11955

___

### setEndBefore

▸ **setEndBefore**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11956

___

### setStart

▸ **setStart**(`node`, `offset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `offset` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11957

___

### setStartAfter

▸ **setStartAfter**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11958

___

### setStartBefore

▸ **setStartBefore**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11959

___

### surroundContents

▸ **surroundContents**(`newParent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newParent` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11960

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11961
