[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / Attr

# Interface: Attr

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).Attr

A DOM element's attribute as an object. In most DOM methods, you will probably directly retrieve the attribute as a string (e.g., Element.getAttribute(), but certain functions (e.g., Element.getAttributeNode()) or means of iterating give Attr types.

## Hierarchy

- [`Node`](../modules/akashaproject_design_system._internal_.md#node)

  ↳ **`Attr`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_design_system._internal_.Attr.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_design_system._internal_.Attr.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_design_system._internal_.Attr.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_design_system._internal_.Attr.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_design_system._internal_.Attr.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_design_system._internal_.Attr.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_design_system._internal_.Attr.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_design_system._internal_.Attr.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_design_system._internal_.Attr.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_design_system._internal_.Attr.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_design_system._internal_.Attr.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_design_system._internal_.Attr.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_design_system._internal_.Attr.md#element_node)
- [ENTITY\_NODE](akashaproject_design_system._internal_.Attr.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_design_system._internal_.Attr.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_design_system._internal_.Attr.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_design_system._internal_.Attr.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_design_system._internal_.Attr.md#text_node)
- [baseURI](akashaproject_design_system._internal_.Attr.md#baseuri)
- [childNodes](akashaproject_design_system._internal_.Attr.md#childnodes)
- [firstChild](akashaproject_design_system._internal_.Attr.md#firstchild)
- [isConnected](akashaproject_design_system._internal_.Attr.md#isconnected)
- [lastChild](akashaproject_design_system._internal_.Attr.md#lastchild)
- [localName](akashaproject_design_system._internal_.Attr.md#localname)
- [name](akashaproject_design_system._internal_.Attr.md#name)
- [namespaceURI](akashaproject_design_system._internal_.Attr.md#namespaceuri)
- [nextSibling](akashaproject_design_system._internal_.Attr.md#nextsibling)
- [nodeName](akashaproject_design_system._internal_.Attr.md#nodename)
- [nodeType](akashaproject_design_system._internal_.Attr.md#nodetype)
- [nodeValue](akashaproject_design_system._internal_.Attr.md#nodevalue)
- [ownerDocument](akashaproject_design_system._internal_.Attr.md#ownerdocument)
- [ownerElement](akashaproject_design_system._internal_.Attr.md#ownerelement)
- [parentElement](akashaproject_design_system._internal_.Attr.md#parentelement)
- [parentNode](akashaproject_design_system._internal_.Attr.md#parentnode)
- [prefix](akashaproject_design_system._internal_.Attr.md#prefix)
- [previousSibling](akashaproject_design_system._internal_.Attr.md#previoussibling)
- [specified](akashaproject_design_system._internal_.Attr.md#specified)
- [textContent](akashaproject_design_system._internal_.Attr.md#textcontent)
- [value](akashaproject_design_system._internal_.Attr.md#value)

### Methods

- [addEventListener](akashaproject_design_system._internal_.Attr.md#addeventlistener)
- [appendChild](akashaproject_design_system._internal_.Attr.md#appendchild)
- [cloneNode](akashaproject_design_system._internal_.Attr.md#clonenode)
- [compareDocumentPosition](akashaproject_design_system._internal_.Attr.md#comparedocumentposition)
- [contains](akashaproject_design_system._internal_.Attr.md#contains)
- [dispatchEvent](akashaproject_design_system._internal_.Attr.md#dispatchevent)
- [getRootNode](akashaproject_design_system._internal_.Attr.md#getrootnode)
- [hasChildNodes](akashaproject_design_system._internal_.Attr.md#haschildnodes)
- [insertBefore](akashaproject_design_system._internal_.Attr.md#insertbefore)
- [isDefaultNamespace](akashaproject_design_system._internal_.Attr.md#isdefaultnamespace)
- [isEqualNode](akashaproject_design_system._internal_.Attr.md#isequalnode)
- [isSameNode](akashaproject_design_system._internal_.Attr.md#issamenode)
- [lookupNamespaceURI](akashaproject_design_system._internal_.Attr.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_design_system._internal_.Attr.md#lookupprefix)
- [normalize](akashaproject_design_system._internal_.Attr.md#normalize)
- [removeChild](akashaproject_design_system._internal_.Attr.md#removechild)
- [removeEventListener](akashaproject_design_system._internal_.Attr.md#removeeventlistener)
- [replaceChild](akashaproject_design_system._internal_.Attr.md#replacechild)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Inherited from

Node.ATTRIBUTE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Inherited from

Node.CDATA\_SECTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Inherited from

Node.COMMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Inherited from

Node.DOCUMENT\_FRAGMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Inherited from

Node.DOCUMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Inherited from

Node.DOCUMENT\_POSITION\_CONTAINED\_BY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Inherited from

Node.DOCUMENT\_POSITION\_CONTAINS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Inherited from

Node.DOCUMENT\_POSITION\_DISCONNECTED

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Inherited from

Node.DOCUMENT\_POSITION\_FOLLOWING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Inherited from

Node.DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Inherited from

Node.DOCUMENT\_POSITION\_PRECEDING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Inherited from

Node.DOCUMENT\_TYPE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Inherited from

Node.ELEMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Inherited from

Node.ENTITY\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Inherited from

Node.ENTITY\_REFERENCE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Inherited from

Node.NOTATION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Inherited from

Node.PROCESSING\_INSTRUCTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Inherited from

Node.TEXT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Inherited from

Node.baseURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)\>

Returns the children.

#### Inherited from

Node.childNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the first child.

#### Inherited from

Node.firstChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Inherited from

Node.isConnected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the last child.

#### Inherited from

Node.lastChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### localName

• `Readonly` **localName**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2089

___

### name

• `Readonly` **name**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2090

___

### namespaceURI

• `Readonly` **namespaceURI**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2091

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the next sibling.

#### Inherited from

Node.nextSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Inherited from

Node.nodeName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Inherited from

Node.nodeType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Inherited from

Node.nodeValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### ownerDocument

• `Readonly` **ownerDocument**: `Document`

#### Overrides

Node.ownerDocument

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2092

___

### ownerElement

• `Readonly` **ownerElement**: `Element`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2093

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Inherited from

Node.parentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_design_system._internal_.ParentNode.md)

Returns the parent.

#### Inherited from

Node.parentNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### prefix

• `Readonly` **prefix**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2094

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the previous sibling.

#### Inherited from

Node.previousSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### specified

• `Readonly` **specified**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2095

___

### textContent

• **textContent**: `string`

#### Inherited from

Node.textContent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10541

___

### value

• **value**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2096

## Methods

### addEventListener

▸ **addEventListener**(`type`, `callback`, `options?`): `void`

Appends an event listener for events whose type attribute value is type. The callback argument sets the callback that will be invoked when the event is dispatched.

The options argument sets listener-specific options. For compatibility this can be a boolean, in which case the method behaves exactly as if the value was specified as options's capture.

When set to true, options's capture prevents callback from being invoked when the event's eventPhase attribute value is BUBBLING_PHASE. When false (or not present), callback will not be invoked when event's eventPhase attribute value is CAPTURING_PHASE. Either way, callback will be invoked if event's eventPhase attribute value is AT_TARGET.

When set to true, options's passive indicates that the callback will not cancel the event by invoking preventDefault(). This is used to enable performance optimizations described in § 2.8 Observing event listeners.

When set to true, options's once indicates that the callback will only be invoked once after which the event listener will be removed.

If an AbortSignal is passed for options's signal, then the event listener will be removed when signal is aborted.

The event listener is appended to target's event listener list and is not appended if it has the same type, callback, and capture.

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `callback` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Inherited from

Node.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5206

___

### appendChild

▸ **appendChild**<`T`\>(`node`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `T` |

#### Returns

`T`

#### Inherited from

Node.appendChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10542

___

### cloneNode

▸ **cloneNode**(`deep?`): [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns a copy of node. If deep is true, the copy also includes the node's descendants.

#### Parameters

| Name | Type |
| :------ | :------ |
| `deep?` | `boolean` |

#### Returns

[`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Inherited from

Node.cloneNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10546

___

### compareDocumentPosition

▸ **compareDocumentPosition**(`other`): `number`

Returns a bitmask indicating the position of other relative to node.

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`number`

#### Inherited from

Node.compareDocumentPosition

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10550

___

### contains

▸ **contains**(`other`): `boolean`

Returns true if other is an inclusive descendant of node, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`boolean`

#### Inherited from

Node.contains

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10554

___

### dispatchEvent

▸ **dispatchEvent**(`event`): `boolean`

Dispatches a synthetic event event to target and returns true if either event's cancelable attribute value is false or its preventDefault() method was not invoked, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`boolean`

#### Inherited from

Node.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### getRootNode

▸ **getRootNode**(`options?`): [`Node`](../modules/akashaproject_design_system._internal_.md#node)

Returns node's root.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`GetRootNodeOptions`](akashaproject_design_system._internal_.GetRootNodeOptions.md) |

#### Returns

[`Node`](../modules/akashaproject_design_system._internal_.md#node)

#### Inherited from

Node.getRootNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Inherited from

Node.hasChildNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10562

___

### insertBefore

▸ **insertBefore**<`T`\>(`node`, `child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `T` |
| `child` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`T`

#### Inherited from

Node.insertBefore

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10563

___

### isDefaultNamespace

▸ **isDefaultNamespace**(`namespace`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |

#### Returns

`boolean`

#### Inherited from

Node.isDefaultNamespace

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10564

___

### isEqualNode

▸ **isEqualNode**(`otherNode`): `boolean`

Returns whether node and otherNode have the same properties.

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherNode` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`boolean`

#### Inherited from

Node.isEqualNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10568

___

### isSameNode

▸ **isSameNode**(`otherNode`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherNode` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

`boolean`

#### Inherited from

Node.isSameNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10569

___

### lookupNamespaceURI

▸ **lookupNamespaceURI**(`prefix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prefix` | `string` |

#### Returns

`string`

#### Inherited from

Node.lookupNamespaceURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10570

___

### lookupPrefix

▸ **lookupPrefix**(`namespace`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |

#### Returns

`string`

#### Inherited from

Node.lookupPrefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10571

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Inherited from

Node.normalize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10575

___

### removeChild

▸ **removeChild**<`T`\>(`child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `child` | `T` |

#### Returns

`T`

#### Inherited from

Node.removeChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10576

___

### removeEventListener

▸ **removeEventListener**(`type`, `callback`, `options?`): `void`

Removes the event listener in target's event listener list with the same type, callback, and options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `callback` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Inherited from

Node.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5214

___

### replaceChild

▸ **replaceChild**<`T`\>(`node`, `child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `child` | `T` |

#### Returns

`T`

#### Inherited from

Node.replaceChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10577
