[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Node

# Interface: Node

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Node

Node is an interface from which a number of DOM API object types inherit. It allows those types to be treated similarly; for example, inheriting the same set of methods, or being tested in the same way.

## Hierarchy

- `EventTarget`

  ↳ **`Node`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#element_node)
- [ENTITY\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_ui_awf_testing_utils._internal_.Node.md#text_node)
- [baseURI](akashaproject_ui_awf_testing_utils._internal_.Node.md#baseuri)
- [childNodes](akashaproject_ui_awf_testing_utils._internal_.Node.md#childnodes)
- [firstChild](akashaproject_ui_awf_testing_utils._internal_.Node.md#firstchild)
- [isConnected](akashaproject_ui_awf_testing_utils._internal_.Node.md#isconnected)
- [lastChild](akashaproject_ui_awf_testing_utils._internal_.Node.md#lastchild)
- [nextSibling](akashaproject_ui_awf_testing_utils._internal_.Node.md#nextsibling)
- [nodeName](akashaproject_ui_awf_testing_utils._internal_.Node.md#nodename)
- [nodeType](akashaproject_ui_awf_testing_utils._internal_.Node.md#nodetype)
- [nodeValue](akashaproject_ui_awf_testing_utils._internal_.Node.md#nodevalue)
- [ownerDocument](akashaproject_ui_awf_testing_utils._internal_.Node.md#ownerdocument)
- [parentElement](akashaproject_ui_awf_testing_utils._internal_.Node.md#parentelement)
- [parentNode](akashaproject_ui_awf_testing_utils._internal_.Node.md#parentnode)
- [previousSibling](akashaproject_ui_awf_testing_utils._internal_.Node.md#previoussibling)
- [textContent](akashaproject_ui_awf_testing_utils._internal_.Node.md#textcontent)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.Node.md#addeventlistener)
- [appendChild](akashaproject_ui_awf_testing_utils._internal_.Node.md#appendchild)
- [cloneNode](akashaproject_ui_awf_testing_utils._internal_.Node.md#clonenode)
- [compareDocumentPosition](akashaproject_ui_awf_testing_utils._internal_.Node.md#comparedocumentposition)
- [contains](akashaproject_ui_awf_testing_utils._internal_.Node.md#contains)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.Node.md#dispatchevent)
- [getRootNode](akashaproject_ui_awf_testing_utils._internal_.Node.md#getrootnode)
- [hasChildNodes](akashaproject_ui_awf_testing_utils._internal_.Node.md#haschildnodes)
- [insertBefore](akashaproject_ui_awf_testing_utils._internal_.Node.md#insertbefore)
- [isDefaultNamespace](akashaproject_ui_awf_testing_utils._internal_.Node.md#isdefaultnamespace)
- [isEqualNode](akashaproject_ui_awf_testing_utils._internal_.Node.md#isequalnode)
- [isSameNode](akashaproject_ui_awf_testing_utils._internal_.Node.md#issamenode)
- [lookupNamespaceURI](akashaproject_ui_awf_testing_utils._internal_.Node.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_ui_awf_testing_utils._internal_.Node.md#lookupprefix)
- [normalize](akashaproject_ui_awf_testing_utils._internal_.Node.md#normalize)
- [removeChild](akashaproject_ui_awf_testing_utils._internal_.Node.md#removechild)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.Node.md#removeeventlistener)
- [replaceChild](akashaproject_ui_awf_testing_utils._internal_.Node.md#replacechild)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)\>

Returns the children.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the first child.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the last child.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the next sibling.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### ownerDocument

• `Readonly` **ownerDocument**: `Document`

Returns the node document. Returns null for documents.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10528

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_ui_awf_testing_utils._internal_.ParentNode.md)

Returns the parent.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the previous sibling.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### textContent

• **textContent**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10541

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
| `callback` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Inherited from

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5206

___

### appendChild

▸ **appendChild**<`T`\>(`node`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `T` |

#### Returns

`T`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10542

___

### cloneNode

▸ **cloneNode**(`deep?`): [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

Returns a copy of node. If deep is true, the copy also includes the node's descendants.

#### Parameters

| Name | Type |
| :------ | :------ |
| `deep?` | `boolean` |

#### Returns

[`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10546

___

### compareDocumentPosition

▸ **compareDocumentPosition**(`other`): `number`

Returns a bitmask indicating the position of other relative to node.

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10550

___

### contains

▸ **contains**(`other`): `boolean`

Returns true if other is an inclusive descendant of node, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`boolean`

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

EventTarget.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### getRootNode

▸ **getRootNode**(`options?`): [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

Returns node's root.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`GetRootNodeOptions`](akashaproject_ui_awf_testing_utils._internal_.GetRootNodeOptions.md) |

#### Returns

[`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10562

___

### insertBefore

▸ **insertBefore**<`T`\>(`node`, `child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `T` |
| `child` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`T`

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10564

___

### isEqualNode

▸ **isEqualNode**(`otherNode`): `boolean`

Returns whether node and otherNode have the same properties.

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherNode` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10568

___

### isSameNode

▸ **isSameNode**(`otherNode`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherNode` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`boolean`

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10571

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10575

___

### removeChild

▸ **removeChild**<`T`\>(`child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `child` | `T` |

#### Returns

`T`

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
| `callback` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Inherited from

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5214

___

### replaceChild

▸ **replaceChild**<`T`\>(`node`, `child`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `child` | `T` |

#### Returns

`T`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10577
