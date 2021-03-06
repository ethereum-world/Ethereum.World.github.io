[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ShadowRoot

# Interface: ShadowRoot

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ShadowRoot

## Hierarchy

- `DocumentFragment`

- [`DocumentOrShadowRoot`](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md)

- [`InnerHTML`](akashaproject_ui_awf_testing_utils._internal_.InnerHTML.md)

  ↳ **`ShadowRoot`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#element_node)
- [ENTITY\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#text_node)
- [activeElement](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#activeelement)
- [baseURI](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#baseuri)
- [childElementCount](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#childelementcount)
- [childNodes](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#childnodes)
- [children](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#children)
- [delegatesFocus](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#delegatesfocus)
- [firstChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#firstchild)
- [firstElementChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#firstelementchild)
- [fullscreenElement](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#fullscreenelement)
- [host](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#host)
- [innerHTML](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#innerhtml)
- [isConnected](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#isconnected)
- [lastChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#lastchild)
- [lastElementChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#lastelementchild)
- [mode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#mode)
- [nextSibling](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#nextsibling)
- [nodeName](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#nodename)
- [nodeType](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#nodetype)
- [nodeValue](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#nodevalue)
- [ownerDocument](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#ownerdocument)
- [parentElement](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#parentelement)
- [parentNode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#parentnode)
- [pictureInPictureElement](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#pictureinpictureelement)
- [pointerLockElement](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#pointerlockelement)
- [previousSibling](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#previoussibling)
- [styleSheets](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#stylesheets)
- [textContent](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#textcontent)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#addeventlistener)
- [append](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#append)
- [appendChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#appendchild)
- [cloneNode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#clonenode)
- [compareDocumentPosition](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#comparedocumentposition)
- [contains](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#contains)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#dispatchevent)
- [getAnimations](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#getanimations)
- [getElementById](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#getelementbyid)
- [getRootNode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#getrootnode)
- [hasChildNodes](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#haschildnodes)
- [insertBefore](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#insertbefore)
- [isDefaultNamespace](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#isdefaultnamespace)
- [isEqualNode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#isequalnode)
- [isSameNode](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#issamenode)
- [lookupNamespaceURI](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#lookupprefix)
- [normalize](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#normalize)
- [prepend](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#prepend)
- [querySelector](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#queryselector)
- [querySelectorAll](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#queryselectorall)
- [removeChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#removechild)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#removeeventlistener)
- [replaceChild](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#replacechild)
- [replaceChildren](akashaproject_ui_awf_testing_utils._internal_.ShadowRoot.md#replacechildren)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Inherited from

DocumentFragment.ATTRIBUTE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Inherited from

DocumentFragment.CDATA\_SECTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Inherited from

DocumentFragment.COMMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Inherited from

DocumentFragment.DOCUMENT\_FRAGMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Inherited from

DocumentFragment.DOCUMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_CONTAINED\_BY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_CONTAINS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_DISCONNECTED

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_FOLLOWING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Inherited from

DocumentFragment.DOCUMENT\_POSITION\_PRECEDING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Inherited from

DocumentFragment.DOCUMENT\_TYPE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Inherited from

DocumentFragment.ELEMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Inherited from

DocumentFragment.ENTITY\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Inherited from

DocumentFragment.ENTITY\_REFERENCE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Inherited from

DocumentFragment.NOTATION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Inherited from

DocumentFragment.PROCESSING\_INSTRUCTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Inherited from

DocumentFragment.TEXT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### activeElement

• `Readonly` **activeElement**: `Element`

Returns the deepest element in the document through which or to which key events are being routed. This is, roughly speaking, the focused element in the document.

For the purposes of this API, when a child browsing context is focused, its container is focused in the parent browsing context. For example, if the user moves the focus to a text control in an iframe, the iframe is the element returned by the activeElement API in the iframe's node document.

Similarly, when the focused element is in a different node tree than documentOrShadowRoot, the element returned will be the host that's located in the same node tree as documentOrShadowRoot if documentOrShadowRoot is a shadow-including inclusive ancestor of the focused element, and null if not.

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[activeElement](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#activeelement)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4758

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Inherited from

DocumentFragment.baseURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### childElementCount

• `Readonly` **childElementCount**: `number`

#### Inherited from

DocumentFragment.childElementCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10958

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)\>

Returns the children.

#### Inherited from

DocumentFragment.childNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### children

• `Readonly` **children**: [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

Returns the child elements.

#### Inherited from

DocumentFragment.children

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10962

___

### delegatesFocus

• `Readonly` **delegatesFocus**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14075

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the first child.

#### Inherited from

DocumentFragment.firstChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### firstElementChild

• `Readonly` **firstElementChild**: `Element`

Returns the first child that is an element, and null otherwise.

#### Inherited from

DocumentFragment.firstElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10966

___

### fullscreenElement

• `Readonly` **fullscreenElement**: `Element`

Returns document's fullscreen element.

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[fullscreenElement](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#fullscreenelement)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4762

___

### host

• `Readonly` **host**: `Element`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14076

___

### innerHTML

• **innerHTML**: `string`

#### Inherited from

[InnerHTML](akashaproject_ui_awf_testing_utils._internal_.InnerHTML.md).[innerHTML](akashaproject_ui_awf_testing_utils._internal_.InnerHTML.md#innerhtml)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9506

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Inherited from

DocumentFragment.isConnected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the last child.

#### Inherited from

DocumentFragment.lastChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### lastElementChild

• `Readonly` **lastElementChild**: `Element`

Returns the last child that is an element, and null otherwise.

#### Inherited from

DocumentFragment.lastElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10970

___

### mode

• `Readonly` **mode**: [`ShadowRootMode`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#shadowrootmode)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14077

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the next sibling.

#### Inherited from

DocumentFragment.nextSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Inherited from

DocumentFragment.nodeName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Inherited from

DocumentFragment.nodeType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Inherited from

DocumentFragment.nodeValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### ownerDocument

• `Readonly` **ownerDocument**: `Document`

#### Inherited from

DocumentFragment.ownerDocument

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4741

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Inherited from

DocumentFragment.parentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_ui_awf_testing_utils._internal_.ParentNode.md)

Returns the parent.

#### Inherited from

DocumentFragment.parentNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### pictureInPictureElement

• `Readonly` **pictureInPictureElement**: `Element`

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[pictureInPictureElement](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#pictureinpictureelement)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4763

___

### pointerLockElement

• `Readonly` **pointerLockElement**: `Element`

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[pointerLockElement](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#pointerlockelement)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4764

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the previous sibling.

#### Inherited from

DocumentFragment.previousSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### styleSheets

• `Readonly` **styleSheets**: [`StyleSheetList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#stylesheetlist)

Retrieves a collection of styleSheet objects representing the style sheets that correspond to each instance of a link or style object in the document.

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[styleSheets](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#stylesheets)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4768

___

### textContent

• **textContent**: `string`

#### Inherited from

DocumentFragment.textContent

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

DocumentFragment.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5206

___

### append

▸ **append**(...`nodes`): `void`

Inserts nodes after the last child of node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

DocumentFragment.append

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10976

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

#### Inherited from

DocumentFragment.appendChild

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

#### Inherited from

DocumentFragment.cloneNode

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

#### Inherited from

DocumentFragment.compareDocumentPosition

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

#### Inherited from

DocumentFragment.contains

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

DocumentFragment.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### getAnimations

▸ **getAnimations**(): [`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)[]

#### Returns

[`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)[]

#### Inherited from

[DocumentOrShadowRoot](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md).[getAnimations](akashaproject_ui_awf_testing_utils._internal_.DocumentOrShadowRoot.md#getanimations)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4769

___

### getElementById

▸ **getElementById**(`elementId`): `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `elementId` | `string` |

#### Returns

`HTMLElement`

#### Inherited from

DocumentFragment.getElementById

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4742

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

#### Inherited from

DocumentFragment.getRootNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Inherited from

DocumentFragment.hasChildNodes

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

#### Inherited from

DocumentFragment.insertBefore

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

DocumentFragment.isDefaultNamespace

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

#### Inherited from

DocumentFragment.isEqualNode

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

#### Inherited from

DocumentFragment.isSameNode

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

DocumentFragment.lookupNamespaceURI

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

DocumentFragment.lookupPrefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10571

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Inherited from

DocumentFragment.normalize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10575

___

### prepend

▸ **prepend**(...`nodes`): `void`

Inserts nodes before the first child of node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

DocumentFragment.prepend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10982

___

### querySelector

▸ **querySelector**<`K`\>(`selectors`): [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]

Returns the first element that is a descendant of node that matches selectors.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]

#### Inherited from

DocumentFragment.querySelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10986

▸ **querySelector**<`K`\>(`selectors`): [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]

#### Inherited from

DocumentFragment.querySelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10987

▸ **querySelector**<`E`\>(`selectors`): `E`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `E` | extends `Element` = `Element` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `string` |

#### Returns

`E`

#### Inherited from

DocumentFragment.querySelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10988

___

### querySelectorAll

▸ **querySelectorAll**<`K`\>(`selectors`): [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]\>

Returns all element descendants of node that match selectors.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]\>

#### Inherited from

DocumentFragment.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10992

▸ **querySelectorAll**<`K`\>(`selectors`): [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Inherited from

DocumentFragment.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10993

▸ **querySelectorAll**<`E`\>(`selectors`): [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<`E`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `E` | extends `Element` = `Element` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `string` |

#### Returns

[`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<`E`\>

#### Inherited from

DocumentFragment.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10994

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

#### Inherited from

DocumentFragment.removeChild

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

DocumentFragment.removeEventListener

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

#### Inherited from

DocumentFragment.replaceChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10577

___

### replaceChildren

▸ **replaceChildren**(...`nodes`): `void`

Replace all children of node with nodes, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

DocumentFragment.replaceChildren

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11000
