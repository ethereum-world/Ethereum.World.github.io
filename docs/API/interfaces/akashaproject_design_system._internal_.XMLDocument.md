[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / XMLDocument

# Interface: XMLDocument

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).XMLDocument

An XML document. It inherits from the generic Document and does not add any specific methods or properties to it: nevertheless, several algorithms behave differently with the two types of documents.

## Hierarchy

- `Document`

  ↳ **`XMLDocument`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_design_system._internal_.XMLDocument.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_design_system._internal_.XMLDocument.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_design_system._internal_.XMLDocument.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_design_system._internal_.XMLDocument.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_design_system._internal_.XMLDocument.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_design_system._internal_.XMLDocument.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_design_system._internal_.XMLDocument.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_design_system._internal_.XMLDocument.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_design_system._internal_.XMLDocument.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_design_system._internal_.XMLDocument.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_design_system._internal_.XMLDocument.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_design_system._internal_.XMLDocument.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_design_system._internal_.XMLDocument.md#element_node)
- [ENTITY\_NODE](akashaproject_design_system._internal_.XMLDocument.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_design_system._internal_.XMLDocument.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_design_system._internal_.XMLDocument.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_design_system._internal_.XMLDocument.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_design_system._internal_.XMLDocument.md#text_node)
- [URL](akashaproject_design_system._internal_.XMLDocument.md#url)
- [activeElement](akashaproject_design_system._internal_.XMLDocument.md#activeelement)
- [alinkColor](akashaproject_design_system._internal_.XMLDocument.md#alinkcolor)
- [all](akashaproject_design_system._internal_.XMLDocument.md#all)
- [anchors](akashaproject_design_system._internal_.XMLDocument.md#anchors)
- [applets](akashaproject_design_system._internal_.XMLDocument.md#applets)
- [baseURI](akashaproject_design_system._internal_.XMLDocument.md#baseuri)
- [bgColor](akashaproject_design_system._internal_.XMLDocument.md#bgcolor)
- [body](akashaproject_design_system._internal_.XMLDocument.md#body)
- [characterSet](akashaproject_design_system._internal_.XMLDocument.md#characterset)
- [charset](akashaproject_design_system._internal_.XMLDocument.md#charset)
- [childElementCount](akashaproject_design_system._internal_.XMLDocument.md#childelementcount)
- [childNodes](akashaproject_design_system._internal_.XMLDocument.md#childnodes)
- [children](akashaproject_design_system._internal_.XMLDocument.md#children)
- [compatMode](akashaproject_design_system._internal_.XMLDocument.md#compatmode)
- [contentType](akashaproject_design_system._internal_.XMLDocument.md#contenttype)
- [cookie](akashaproject_design_system._internal_.XMLDocument.md#cookie)
- [currentScript](akashaproject_design_system._internal_.XMLDocument.md#currentscript)
- [defaultView](akashaproject_design_system._internal_.XMLDocument.md#defaultview)
- [designMode](akashaproject_design_system._internal_.XMLDocument.md#designmode)
- [dir](akashaproject_design_system._internal_.XMLDocument.md#dir)
- [doctype](akashaproject_design_system._internal_.XMLDocument.md#doctype)
- [documentElement](akashaproject_design_system._internal_.XMLDocument.md#documentelement)
- [documentURI](akashaproject_design_system._internal_.XMLDocument.md#documenturi)
- [domain](akashaproject_design_system._internal_.XMLDocument.md#domain)
- [embeds](akashaproject_design_system._internal_.XMLDocument.md#embeds)
- [fgColor](akashaproject_design_system._internal_.XMLDocument.md#fgcolor)
- [firstChild](akashaproject_design_system._internal_.XMLDocument.md#firstchild)
- [firstElementChild](akashaproject_design_system._internal_.XMLDocument.md#firstelementchild)
- [fonts](akashaproject_design_system._internal_.XMLDocument.md#fonts)
- [forms](akashaproject_design_system._internal_.XMLDocument.md#forms)
- [fullscreen](akashaproject_design_system._internal_.XMLDocument.md#fullscreen)
- [fullscreenElement](akashaproject_design_system._internal_.XMLDocument.md#fullscreenelement)
- [fullscreenEnabled](akashaproject_design_system._internal_.XMLDocument.md#fullscreenenabled)
- [head](akashaproject_design_system._internal_.XMLDocument.md#head)
- [hidden](akashaproject_design_system._internal_.XMLDocument.md#hidden)
- [images](akashaproject_design_system._internal_.XMLDocument.md#images)
- [implementation](akashaproject_design_system._internal_.XMLDocument.md#implementation)
- [inputEncoding](akashaproject_design_system._internal_.XMLDocument.md#inputencoding)
- [isConnected](akashaproject_design_system._internal_.XMLDocument.md#isconnected)
- [lastChild](akashaproject_design_system._internal_.XMLDocument.md#lastchild)
- [lastElementChild](akashaproject_design_system._internal_.XMLDocument.md#lastelementchild)
- [lastModified](akashaproject_design_system._internal_.XMLDocument.md#lastmodified)
- [linkColor](akashaproject_design_system._internal_.XMLDocument.md#linkcolor)
- [links](akashaproject_design_system._internal_.XMLDocument.md#links)
- [nextSibling](akashaproject_design_system._internal_.XMLDocument.md#nextsibling)
- [nodeName](akashaproject_design_system._internal_.XMLDocument.md#nodename)
- [nodeType](akashaproject_design_system._internal_.XMLDocument.md#nodetype)
- [nodeValue](akashaproject_design_system._internal_.XMLDocument.md#nodevalue)
- [onabort](akashaproject_design_system._internal_.XMLDocument.md#onabort)
- [onanimationcancel](akashaproject_design_system._internal_.XMLDocument.md#onanimationcancel)
- [onanimationend](akashaproject_design_system._internal_.XMLDocument.md#onanimationend)
- [onanimationiteration](akashaproject_design_system._internal_.XMLDocument.md#onanimationiteration)
- [onanimationstart](akashaproject_design_system._internal_.XMLDocument.md#onanimationstart)
- [onauxclick](akashaproject_design_system._internal_.XMLDocument.md#onauxclick)
- [onblur](akashaproject_design_system._internal_.XMLDocument.md#onblur)
- [oncanplay](akashaproject_design_system._internal_.XMLDocument.md#oncanplay)
- [oncanplaythrough](akashaproject_design_system._internal_.XMLDocument.md#oncanplaythrough)
- [onchange](akashaproject_design_system._internal_.XMLDocument.md#onchange)
- [onclick](akashaproject_design_system._internal_.XMLDocument.md#onclick)
- [onclose](akashaproject_design_system._internal_.XMLDocument.md#onclose)
- [oncontextmenu](akashaproject_design_system._internal_.XMLDocument.md#oncontextmenu)
- [oncopy](akashaproject_design_system._internal_.XMLDocument.md#oncopy)
- [oncuechange](akashaproject_design_system._internal_.XMLDocument.md#oncuechange)
- [oncut](akashaproject_design_system._internal_.XMLDocument.md#oncut)
- [ondblclick](akashaproject_design_system._internal_.XMLDocument.md#ondblclick)
- [ondrag](akashaproject_design_system._internal_.XMLDocument.md#ondrag)
- [ondragend](akashaproject_design_system._internal_.XMLDocument.md#ondragend)
- [ondragenter](akashaproject_design_system._internal_.XMLDocument.md#ondragenter)
- [ondragleave](akashaproject_design_system._internal_.XMLDocument.md#ondragleave)
- [ondragover](akashaproject_design_system._internal_.XMLDocument.md#ondragover)
- [ondragstart](akashaproject_design_system._internal_.XMLDocument.md#ondragstart)
- [ondrop](akashaproject_design_system._internal_.XMLDocument.md#ondrop)
- [ondurationchange](akashaproject_design_system._internal_.XMLDocument.md#ondurationchange)
- [onemptied](akashaproject_design_system._internal_.XMLDocument.md#onemptied)
- [onended](akashaproject_design_system._internal_.XMLDocument.md#onended)
- [onerror](akashaproject_design_system._internal_.XMLDocument.md#onerror)
- [onfocus](akashaproject_design_system._internal_.XMLDocument.md#onfocus)
- [onformdata](akashaproject_design_system._internal_.XMLDocument.md#onformdata)
- [onfullscreenchange](akashaproject_design_system._internal_.XMLDocument.md#onfullscreenchange)
- [onfullscreenerror](akashaproject_design_system._internal_.XMLDocument.md#onfullscreenerror)
- [ongotpointercapture](akashaproject_design_system._internal_.XMLDocument.md#ongotpointercapture)
- [oninput](akashaproject_design_system._internal_.XMLDocument.md#oninput)
- [oninvalid](akashaproject_design_system._internal_.XMLDocument.md#oninvalid)
- [onkeydown](akashaproject_design_system._internal_.XMLDocument.md#onkeydown)
- [onkeypress](akashaproject_design_system._internal_.XMLDocument.md#onkeypress)
- [onkeyup](akashaproject_design_system._internal_.XMLDocument.md#onkeyup)
- [onload](akashaproject_design_system._internal_.XMLDocument.md#onload)
- [onloadeddata](akashaproject_design_system._internal_.XMLDocument.md#onloadeddata)
- [onloadedmetadata](akashaproject_design_system._internal_.XMLDocument.md#onloadedmetadata)
- [onloadstart](akashaproject_design_system._internal_.XMLDocument.md#onloadstart)
- [onlostpointercapture](akashaproject_design_system._internal_.XMLDocument.md#onlostpointercapture)
- [onmousedown](akashaproject_design_system._internal_.XMLDocument.md#onmousedown)
- [onmouseenter](akashaproject_design_system._internal_.XMLDocument.md#onmouseenter)
- [onmouseleave](akashaproject_design_system._internal_.XMLDocument.md#onmouseleave)
- [onmousemove](akashaproject_design_system._internal_.XMLDocument.md#onmousemove)
- [onmouseout](akashaproject_design_system._internal_.XMLDocument.md#onmouseout)
- [onmouseover](akashaproject_design_system._internal_.XMLDocument.md#onmouseover)
- [onmouseup](akashaproject_design_system._internal_.XMLDocument.md#onmouseup)
- [onpaste](akashaproject_design_system._internal_.XMLDocument.md#onpaste)
- [onpause](akashaproject_design_system._internal_.XMLDocument.md#onpause)
- [onplay](akashaproject_design_system._internal_.XMLDocument.md#onplay)
- [onplaying](akashaproject_design_system._internal_.XMLDocument.md#onplaying)
- [onpointercancel](akashaproject_design_system._internal_.XMLDocument.md#onpointercancel)
- [onpointerdown](akashaproject_design_system._internal_.XMLDocument.md#onpointerdown)
- [onpointerenter](akashaproject_design_system._internal_.XMLDocument.md#onpointerenter)
- [onpointerleave](akashaproject_design_system._internal_.XMLDocument.md#onpointerleave)
- [onpointerlockchange](akashaproject_design_system._internal_.XMLDocument.md#onpointerlockchange)
- [onpointerlockerror](akashaproject_design_system._internal_.XMLDocument.md#onpointerlockerror)
- [onpointermove](akashaproject_design_system._internal_.XMLDocument.md#onpointermove)
- [onpointerout](akashaproject_design_system._internal_.XMLDocument.md#onpointerout)
- [onpointerover](akashaproject_design_system._internal_.XMLDocument.md#onpointerover)
- [onpointerup](akashaproject_design_system._internal_.XMLDocument.md#onpointerup)
- [onprogress](akashaproject_design_system._internal_.XMLDocument.md#onprogress)
- [onratechange](akashaproject_design_system._internal_.XMLDocument.md#onratechange)
- [onreadystatechange](akashaproject_design_system._internal_.XMLDocument.md#onreadystatechange)
- [onreset](akashaproject_design_system._internal_.XMLDocument.md#onreset)
- [onresize](akashaproject_design_system._internal_.XMLDocument.md#onresize)
- [onscroll](akashaproject_design_system._internal_.XMLDocument.md#onscroll)
- [onseeked](akashaproject_design_system._internal_.XMLDocument.md#onseeked)
- [onseeking](akashaproject_design_system._internal_.XMLDocument.md#onseeking)
- [onselect](akashaproject_design_system._internal_.XMLDocument.md#onselect)
- [onselectionchange](akashaproject_design_system._internal_.XMLDocument.md#onselectionchange)
- [onselectstart](akashaproject_design_system._internal_.XMLDocument.md#onselectstart)
- [onstalled](akashaproject_design_system._internal_.XMLDocument.md#onstalled)
- [onsubmit](akashaproject_design_system._internal_.XMLDocument.md#onsubmit)
- [onsuspend](akashaproject_design_system._internal_.XMLDocument.md#onsuspend)
- [ontimeupdate](akashaproject_design_system._internal_.XMLDocument.md#ontimeupdate)
- [ontoggle](akashaproject_design_system._internal_.XMLDocument.md#ontoggle)
- [ontouchcancel](akashaproject_design_system._internal_.XMLDocument.md#ontouchcancel)
- [ontouchend](akashaproject_design_system._internal_.XMLDocument.md#ontouchend)
- [ontouchmove](akashaproject_design_system._internal_.XMLDocument.md#ontouchmove)
- [ontouchstart](akashaproject_design_system._internal_.XMLDocument.md#ontouchstart)
- [ontransitioncancel](akashaproject_design_system._internal_.XMLDocument.md#ontransitioncancel)
- [ontransitionend](akashaproject_design_system._internal_.XMLDocument.md#ontransitionend)
- [ontransitionrun](akashaproject_design_system._internal_.XMLDocument.md#ontransitionrun)
- [ontransitionstart](akashaproject_design_system._internal_.XMLDocument.md#ontransitionstart)
- [onvisibilitychange](akashaproject_design_system._internal_.XMLDocument.md#onvisibilitychange)
- [onvolumechange](akashaproject_design_system._internal_.XMLDocument.md#onvolumechange)
- [onwaiting](akashaproject_design_system._internal_.XMLDocument.md#onwaiting)
- [onwebkitanimationend](akashaproject_design_system._internal_.XMLDocument.md#onwebkitanimationend)
- [onwebkitanimationiteration](akashaproject_design_system._internal_.XMLDocument.md#onwebkitanimationiteration)
- [onwebkitanimationstart](akashaproject_design_system._internal_.XMLDocument.md#onwebkitanimationstart)
- [onwebkittransitionend](akashaproject_design_system._internal_.XMLDocument.md#onwebkittransitionend)
- [onwheel](akashaproject_design_system._internal_.XMLDocument.md#onwheel)
- [ownerDocument](akashaproject_design_system._internal_.XMLDocument.md#ownerdocument)
- [parentElement](akashaproject_design_system._internal_.XMLDocument.md#parentelement)
- [parentNode](akashaproject_design_system._internal_.XMLDocument.md#parentnode)
- [pictureInPictureElement](akashaproject_design_system._internal_.XMLDocument.md#pictureinpictureelement)
- [pictureInPictureEnabled](akashaproject_design_system._internal_.XMLDocument.md#pictureinpictureenabled)
- [plugins](akashaproject_design_system._internal_.XMLDocument.md#plugins)
- [pointerLockElement](akashaproject_design_system._internal_.XMLDocument.md#pointerlockelement)
- [previousSibling](akashaproject_design_system._internal_.XMLDocument.md#previoussibling)
- [readyState](akashaproject_design_system._internal_.XMLDocument.md#readystate)
- [referrer](akashaproject_design_system._internal_.XMLDocument.md#referrer)
- [rootElement](akashaproject_design_system._internal_.XMLDocument.md#rootelement)
- [scripts](akashaproject_design_system._internal_.XMLDocument.md#scripts)
- [scrollingElement](akashaproject_design_system._internal_.XMLDocument.md#scrollingelement)
- [styleSheets](akashaproject_design_system._internal_.XMLDocument.md#stylesheets)
- [textContent](akashaproject_design_system._internal_.XMLDocument.md#textcontent)
- [timeline](akashaproject_design_system._internal_.XMLDocument.md#timeline)
- [title](akashaproject_design_system._internal_.XMLDocument.md#title)
- [visibilityState](akashaproject_design_system._internal_.XMLDocument.md#visibilitystate)
- [vlinkColor](akashaproject_design_system._internal_.XMLDocument.md#vlinkcolor)

### Accessors

- [location](akashaproject_design_system._internal_.XMLDocument.md#location)

### Methods

- [addEventListener](akashaproject_design_system._internal_.XMLDocument.md#addeventlistener)
- [adoptNode](akashaproject_design_system._internal_.XMLDocument.md#adoptnode)
- [append](akashaproject_design_system._internal_.XMLDocument.md#append)
- [appendChild](akashaproject_design_system._internal_.XMLDocument.md#appendchild)
- [captureEvents](akashaproject_design_system._internal_.XMLDocument.md#captureevents)
- [caretRangeFromPoint](akashaproject_design_system._internal_.XMLDocument.md#caretrangefrompoint)
- [clear](akashaproject_design_system._internal_.XMLDocument.md#clear)
- [cloneNode](akashaproject_design_system._internal_.XMLDocument.md#clonenode)
- [close](akashaproject_design_system._internal_.XMLDocument.md#close)
- [compareDocumentPosition](akashaproject_design_system._internal_.XMLDocument.md#comparedocumentposition)
- [contains](akashaproject_design_system._internal_.XMLDocument.md#contains)
- [createAttribute](akashaproject_design_system._internal_.XMLDocument.md#createattribute)
- [createAttributeNS](akashaproject_design_system._internal_.XMLDocument.md#createattributens)
- [createCDATASection](akashaproject_design_system._internal_.XMLDocument.md#createcdatasection)
- [createComment](akashaproject_design_system._internal_.XMLDocument.md#createcomment)
- [createDocumentFragment](akashaproject_design_system._internal_.XMLDocument.md#createdocumentfragment)
- [createElement](akashaproject_design_system._internal_.XMLDocument.md#createelement)
- [createElementNS](akashaproject_design_system._internal_.XMLDocument.md#createelementns)
- [createEvent](akashaproject_design_system._internal_.XMLDocument.md#createevent)
- [createExpression](akashaproject_design_system._internal_.XMLDocument.md#createexpression)
- [createNSResolver](akashaproject_design_system._internal_.XMLDocument.md#creatensresolver)
- [createNodeIterator](akashaproject_design_system._internal_.XMLDocument.md#createnodeiterator)
- [createProcessingInstruction](akashaproject_design_system._internal_.XMLDocument.md#createprocessinginstruction)
- [createRange](akashaproject_design_system._internal_.XMLDocument.md#createrange)
- [createTextNode](akashaproject_design_system._internal_.XMLDocument.md#createtextnode)
- [createTreeWalker](akashaproject_design_system._internal_.XMLDocument.md#createtreewalker)
- [dispatchEvent](akashaproject_design_system._internal_.XMLDocument.md#dispatchevent)
- [elementFromPoint](akashaproject_design_system._internal_.XMLDocument.md#elementfrompoint)
- [elementsFromPoint](akashaproject_design_system._internal_.XMLDocument.md#elementsfrompoint)
- [evaluate](akashaproject_design_system._internal_.XMLDocument.md#evaluate)
- [execCommand](akashaproject_design_system._internal_.XMLDocument.md#execcommand)
- [exitFullscreen](akashaproject_design_system._internal_.XMLDocument.md#exitfullscreen)
- [exitPictureInPicture](akashaproject_design_system._internal_.XMLDocument.md#exitpictureinpicture)
- [exitPointerLock](akashaproject_design_system._internal_.XMLDocument.md#exitpointerlock)
- [getAnimations](akashaproject_design_system._internal_.XMLDocument.md#getanimations)
- [getElementById](akashaproject_design_system._internal_.XMLDocument.md#getelementbyid)
- [getElementsByClassName](akashaproject_design_system._internal_.XMLDocument.md#getelementsbyclassname)
- [getElementsByName](akashaproject_design_system._internal_.XMLDocument.md#getelementsbyname)
- [getElementsByTagName](akashaproject_design_system._internal_.XMLDocument.md#getelementsbytagname)
- [getElementsByTagNameNS](akashaproject_design_system._internal_.XMLDocument.md#getelementsbytagnamens)
- [getRootNode](akashaproject_design_system._internal_.XMLDocument.md#getrootnode)
- [getSelection](akashaproject_design_system._internal_.XMLDocument.md#getselection)
- [hasChildNodes](akashaproject_design_system._internal_.XMLDocument.md#haschildnodes)
- [hasFocus](akashaproject_design_system._internal_.XMLDocument.md#hasfocus)
- [hasStorageAccess](akashaproject_design_system._internal_.XMLDocument.md#hasstorageaccess)
- [importNode](akashaproject_design_system._internal_.XMLDocument.md#importnode)
- [insertBefore](akashaproject_design_system._internal_.XMLDocument.md#insertbefore)
- [isDefaultNamespace](akashaproject_design_system._internal_.XMLDocument.md#isdefaultnamespace)
- [isEqualNode](akashaproject_design_system._internal_.XMLDocument.md#isequalnode)
- [isSameNode](akashaproject_design_system._internal_.XMLDocument.md#issamenode)
- [lookupNamespaceURI](akashaproject_design_system._internal_.XMLDocument.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_design_system._internal_.XMLDocument.md#lookupprefix)
- [normalize](akashaproject_design_system._internal_.XMLDocument.md#normalize)
- [open](akashaproject_design_system._internal_.XMLDocument.md#open)
- [prepend](akashaproject_design_system._internal_.XMLDocument.md#prepend)
- [queryCommandEnabled](akashaproject_design_system._internal_.XMLDocument.md#querycommandenabled)
- [queryCommandIndeterm](akashaproject_design_system._internal_.XMLDocument.md#querycommandindeterm)
- [queryCommandState](akashaproject_design_system._internal_.XMLDocument.md#querycommandstate)
- [queryCommandSupported](akashaproject_design_system._internal_.XMLDocument.md#querycommandsupported)
- [queryCommandValue](akashaproject_design_system._internal_.XMLDocument.md#querycommandvalue)
- [querySelector](akashaproject_design_system._internal_.XMLDocument.md#queryselector)
- [querySelectorAll](akashaproject_design_system._internal_.XMLDocument.md#queryselectorall)
- [releaseEvents](akashaproject_design_system._internal_.XMLDocument.md#releaseevents)
- [removeChild](akashaproject_design_system._internal_.XMLDocument.md#removechild)
- [removeEventListener](akashaproject_design_system._internal_.XMLDocument.md#removeeventlistener)
- [replaceChild](akashaproject_design_system._internal_.XMLDocument.md#replacechild)
- [replaceChildren](akashaproject_design_system._internal_.XMLDocument.md#replacechildren)
- [requestStorageAccess](akashaproject_design_system._internal_.XMLDocument.md#requeststorageaccess)
- [write](akashaproject_design_system._internal_.XMLDocument.md#write)
- [writeln](akashaproject_design_system._internal_.XMLDocument.md#writeln)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Inherited from

Document.ATTRIBUTE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Inherited from

Document.CDATA\_SECTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Inherited from

Document.COMMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Inherited from

Document.DOCUMENT\_FRAGMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Inherited from

Document.DOCUMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Inherited from

Document.DOCUMENT\_POSITION\_CONTAINED\_BY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Inherited from

Document.DOCUMENT\_POSITION\_CONTAINS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Inherited from

Document.DOCUMENT\_POSITION\_DISCONNECTED

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Inherited from

Document.DOCUMENT\_POSITION\_FOLLOWING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Inherited from

Document.DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Inherited from

Document.DOCUMENT\_POSITION\_PRECEDING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Inherited from

Document.DOCUMENT\_TYPE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Inherited from

Document.ELEMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Inherited from

Document.ENTITY\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Inherited from

Document.ENTITY\_REFERENCE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Inherited from

Document.NOTATION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Inherited from

Document.PROCESSING\_INSTRUCTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Inherited from

Document.TEXT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### URL

• `Readonly` **URL**: `string`

Sets or gets the URL for the current document.

#### Inherited from

Document.URL

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4260

___

### activeElement

• `Readonly` **activeElement**: `Element`

Returns the deepest element in the document through which or to which key events are being routed. This is, roughly speaking, the focused element in the document.

For the purposes of this API, when a child browsing context is focused, its container is focused in the parent browsing context. For example, if the user moves the focus to a text control in an iframe, the iframe is the element returned by the activeElement API in the iframe's node document.

Similarly, when the focused element is in a different node tree than documentOrShadowRoot, the element returned will be the host that's located in the same node tree as documentOrShadowRoot if documentOrShadowRoot is a shadow-including inclusive ancestor of the focused element, and null if not.

#### Inherited from

Document.activeElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4758

___

### alinkColor

• **alinkColor**: `string`

Sets or gets the color of all active links in the document.

**`deprecated`**

#### Inherited from

Document.alinkColor

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4265

___

### all

• `Readonly` **all**: [`HTMLAllCollection`](../modules/akashaproject_design_system._internal_.md#htmlallcollection)

Returns a reference to the collection of elements contained by the object.

**`deprecated`**

#### Inherited from

Document.all

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4270

___

### anchors

• `Readonly` **anchors**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLAnchorElement`\>

Retrieves a collection of all a objects that have a name and/or id property. Objects in this collection are in HTML source order.

**`deprecated`**

#### Inherited from

Document.anchors

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4275

___

### applets

• `Readonly` **applets**: [`HTMLCollection`](../modules/akashaproject_design_system._internal_.md#htmlcollection)

Retrieves a collection of all applet objects in the document.

**`deprecated`**

#### Inherited from

Document.applets

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4280

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Inherited from

Document.baseURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### bgColor

• **bgColor**: `string`

Deprecated. Sets or retrieves a value that indicates the background color behind the object.

**`deprecated`**

#### Inherited from

Document.bgColor

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4285

___

### body

• **body**: `HTMLElement`

Specifies the beginning and end of the document body.

#### Inherited from

Document.body

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4289

___

### characterSet

• `Readonly` **characterSet**: `string`

Returns document's encoding.

#### Inherited from

Document.characterSet

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4293

___

### charset

• `Readonly` **charset**: `string`

Gets or sets the character set used to encode the object.

**`deprecated`** This is a legacy alias of `characterSet`.

#### Inherited from

Document.charset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4298

___

### childElementCount

• `Readonly` **childElementCount**: `number`

#### Inherited from

Document.childElementCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10958

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)\>

Returns the children.

#### Inherited from

Document.childNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### children

• `Readonly` **children**: [`HTMLCollection`](../modules/akashaproject_design_system._internal_.md#htmlcollection)

Returns the child elements.

#### Inherited from

Document.children

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10962

___

### compatMode

• `Readonly` **compatMode**: `string`

Gets a value that indicates whether standards-compliant mode is switched on for the object.

#### Inherited from

Document.compatMode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4302

___

### contentType

• `Readonly` **contentType**: `string`

Returns document's content type.

#### Inherited from

Document.contentType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4306

___

### cookie

• **cookie**: `string`

Returns the HTTP cookies that apply to the Document. If there are no cookies or cookies can't be applied to this resource, the empty string will be returned.

Can be set, to add a new cookie to the element's set of HTTP cookies.

If the contents are sandboxed into a unique origin (e.g. in an iframe with the sandbox attribute), a "SecurityError" DOMException will be thrown on getting and setting.

#### Inherited from

Document.cookie

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4314

___

### currentScript

• `Readonly` **currentScript**: [`HTMLOrSVGScriptElement`](../modules/akashaproject_design_system._internal_.md#htmlorsvgscriptelement)

Returns the script element, or the SVG script element, that is currently executing, as long as the element represents a classic script. In the case of reentrant script execution, returns the one that most recently started executing amongst those that have not yet finished executing.

Returns null if the Document is not currently executing a script or SVG script element (e.g., because the running script is an event handler, or a timeout), or if the currently executing script or SVG script element represents a module script.

#### Inherited from

Document.currentScript

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4320

___

### defaultView

• `Readonly` **defaultView**: `Window` & typeof `globalThis`

Returns the Window object of the active document.

#### Inherited from

Document.defaultView

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4324

___

### designMode

• **designMode**: `string`

Sets or gets a value that indicates whether the document can be edited.

#### Inherited from

Document.designMode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4328

___

### dir

• **dir**: `string`

Sets or retrieves a value that indicates the reading order of the object.

#### Inherited from

Document.dir

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4332

___

### doctype

• `Readonly` **doctype**: [`DocumentType`](../modules/akashaproject_design_system._internal_.md#documenttype)

Gets an object representing the document type declaration associated with the current document.

#### Inherited from

Document.doctype

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4336

___

### documentElement

• `Readonly` **documentElement**: `HTMLElement`

Gets a reference to the root node of the document.

#### Inherited from

Document.documentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4340

___

### documentURI

• `Readonly` **documentURI**: `string`

Returns document's URL.

#### Inherited from

Document.documentURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4344

___

### domain

• **domain**: `string`

Sets or gets the security domain of the document.

#### Inherited from

Document.domain

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4348

___

### embeds

• `Readonly` **embeds**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLEmbedElement`\>

Retrieves a collection of all embed objects in the document.

#### Inherited from

Document.embeds

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4352

___

### fgColor

• **fgColor**: `string`

Sets or gets the foreground (text) color of the document.

**`deprecated`**

#### Inherited from

Document.fgColor

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4357

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the first child.

#### Inherited from

Document.firstChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### firstElementChild

• `Readonly` **firstElementChild**: `Element`

Returns the first child that is an element, and null otherwise.

#### Inherited from

Document.firstElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10966

___

### fonts

• `Readonly` **fonts**: [`FontFaceSet`](../modules/akashaproject_design_system._internal_.md#fontfaceset)

#### Inherited from

Document.fonts

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5427

___

### forms

• `Readonly` **forms**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLFormElement`\>

Retrieves a collection, in source order, of all form objects in the document.

#### Inherited from

Document.forms

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4361

___

### fullscreen

• `Readonly` **fullscreen**: `boolean`

**`deprecated`**

#### Inherited from

Document.fullscreen

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4363

___

### fullscreenElement

• `Readonly` **fullscreenElement**: `Element`

Returns document's fullscreen element.

#### Inherited from

Document.fullscreenElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4762

___

### fullscreenEnabled

• `Readonly` **fullscreenEnabled**: `boolean`

Returns true if document has the ability to display elements fullscreen and fullscreen is supported, or false otherwise.

#### Inherited from

Document.fullscreenEnabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4367

___

### head

• `Readonly` **head**: `HTMLHeadElement`

Returns the head element.

#### Inherited from

Document.head

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4371

___

### hidden

• `Readonly` **hidden**: `boolean`

#### Inherited from

Document.hidden

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4372

___

### images

• `Readonly` **images**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLImageElement`\>

Retrieves a collection, in source order, of img objects in the document.

#### Inherited from

Document.images

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4376

___

### implementation

• `Readonly` **implementation**: [`DOMImplementation`](../modules/akashaproject_design_system._internal_.md#domimplementation)

Gets the implementation object of the current document.

#### Inherited from

Document.implementation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4380

___

### inputEncoding

• `Readonly` **inputEncoding**: `string`

Returns the character encoding used to create the webpage that is loaded into the document object.

**`deprecated`** This is a legacy alias of `characterSet`.

#### Inherited from

Document.inputEncoding

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4385

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Inherited from

Document.isConnected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the last child.

#### Inherited from

Document.lastChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### lastElementChild

• `Readonly` **lastElementChild**: `Element`

Returns the last child that is an element, and null otherwise.

#### Inherited from

Document.lastElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10970

___

### lastModified

• `Readonly` **lastModified**: `string`

Gets the date that the page was last modified, if the page supplies one.

#### Inherited from

Document.lastModified

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4389

___

### linkColor

• **linkColor**: `string`

Sets or gets the color of the document links.

**`deprecated`**

#### Inherited from

Document.linkColor

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4394

___

### links

• `Readonly` **links**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLAnchorElement` \| `HTMLAreaElement`\>

Retrieves a collection of all a objects that specify the href property and all area objects in the document.

#### Inherited from

Document.links

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4398

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the next sibling.

#### Inherited from

Document.nextSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Inherited from

Document.nodeName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Inherited from

Document.nodeType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Inherited from

Document.nodeValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### onabort

• **onabort**: (`ev`: `UIEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user aborts the download.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `UIEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.onabort

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5677

___

### onanimationcancel

• **onanimationcancel**: (`ev`: `AnimationEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `AnimationEvent` |

##### Returns

`any`

#### Inherited from

Document.onanimationcancel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5678

___

### onanimationend

• **onanimationend**: (`ev`: `AnimationEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `AnimationEvent` |

##### Returns

`any`

#### Inherited from

Document.onanimationend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5679

___

### onanimationiteration

• **onanimationiteration**: (`ev`: `AnimationEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `AnimationEvent` |

##### Returns

`any`

#### Inherited from

Document.onanimationiteration

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5680

___

### onanimationstart

• **onanimationstart**: (`ev`: `AnimationEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `AnimationEvent` |

##### Returns

`any`

#### Inherited from

Document.onanimationstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5681

___

### onauxclick

• **onauxclick**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `MouseEvent` |

##### Returns

`any`

#### Inherited from

Document.onauxclick

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5682

___

### onblur

• **onblur**: (`ev`: `FocusEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the object loses the input focus.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `FocusEvent` | The focus event. |

##### Returns

`any`

#### Inherited from

Document.onblur

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5687

___

### oncanplay

• **oncanplay**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when playback is possible, but would require further buffering.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.oncanplay

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5692

___

### oncanplaythrough

• **oncanplaythrough**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.oncanplaythrough

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5693

___

### onchange

• **onchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the contents of the object or selection have changed.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5698

___

### onclick

• **onclick**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user clicks the left mouse button on the object

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onclick

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5703

___

### onclose

• **onclose**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onclose

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5704

___

### oncontextmenu

• **oncontextmenu**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user clicks the right mouse button in the client area, opening the context menu.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.oncontextmenu

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5709

___

### oncopy

• **oncopy**: (`ev`: `ClipboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `ClipboardEvent` |

##### Returns

`any`

#### Inherited from

Document.oncopy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4730

___

### oncuechange

• **oncuechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.oncuechange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5710

___

### oncut

• **oncut**: (`ev`: `ClipboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `ClipboardEvent` |

##### Returns

`any`

#### Inherited from

Document.oncut

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4731

___

### ondblclick

• **ondblclick**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user double-clicks the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.ondblclick

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5715

___

### ondrag

• **ondrag**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the source object continuously during a drag operation.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.ondrag

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5720

___

### ondragend

• **ondragend**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the source object when the user releases the mouse at the close of a drag operation.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.ondragend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5725

___

### ondragenter

• **ondragenter**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the target element when the user drags the object to a valid drop target.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The drag event. |

##### Returns

`any`

#### Inherited from

Document.ondragenter

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5730

___

### ondragleave

• **ondragleave**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the target object when the user moves the mouse out of a valid drop target during a drag operation.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The drag event. |

##### Returns

`any`

#### Inherited from

Document.ondragleave

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5735

___

### ondragover

• **ondragover**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the target element continuously while the user drags the object over a valid drop target.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.ondragover

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5740

___

### ondragstart

• **ondragstart**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires on the source object when the user starts to drag a text selection or selected object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `DragEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.ondragstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5745

___

### ondrop

• **ondrop**: (`ev`: `DragEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `DragEvent` |

##### Returns

`any`

#### Inherited from

Document.ondrop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5746

___

### ondurationchange

• **ondurationchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the duration attribute is updated.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.ondurationchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5751

___

### onemptied

• **onemptied**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the media element is reset to its initial state.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onemptied

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5756

___

### onended

• **onended**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the end of playback is reached.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event |

##### Returns

`any`

#### Inherited from

Document.onended

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5761

___

### onerror

• **onerror**: [`OnErrorEventHandlerNonNull`](akashaproject_design_system._internal_.OnErrorEventHandlerNonNull.md)

Fires when an error occurs during object loading.

**`param`** The event.

#### Inherited from

Document.onerror

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5766

___

### onfocus

• **onfocus**: (`ev`: `FocusEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the object receives focus.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `FocusEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.onfocus

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5771

___

### onformdata

• **onformdata**: (`ev`: [`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent) |

##### Returns

`any`

#### Inherited from

Document.onformdata

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5772

___

### onfullscreenchange

• **onfullscreenchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onfullscreenchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4404

___

### onfullscreenerror

• **onfullscreenerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onfullscreenerror

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4405

___

### ongotpointercapture

• **ongotpointercapture**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.ongotpointercapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5773

___

### oninput

• **oninput**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.oninput

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5774

___

### oninvalid

• **oninvalid**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.oninvalid

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5775

___

### onkeydown

• **onkeydown**: (`ev`: `KeyboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user presses a key.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `KeyboardEvent` | The keyboard event |

##### Returns

`any`

#### Inherited from

Document.onkeydown

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5780

___

### onkeypress

• **onkeypress**: (`ev`: `KeyboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user presses an alphanumeric key.

**`deprecated`**

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `KeyboardEvent` | The event. |

##### Returns

`any`

#### Inherited from

Document.onkeypress

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5786

___

### onkeyup

• **onkeyup**: (`ev`: `KeyboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user releases a key.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `KeyboardEvent` | The keyboard event |

##### Returns

`any`

#### Inherited from

Document.onkeyup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5791

___

### onload

• **onload**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires immediately after the browser loads the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onload

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5796

___

### onloadeddata

• **onloadeddata**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when media data is loaded at the current playback position.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onloadeddata

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5801

___

### onloadedmetadata

• **onloadedmetadata**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the duration and dimensions of the media have been determined.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onloadedmetadata

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5806

___

### onloadstart

• **onloadstart**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when Internet Explorer begins looking for media data.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onloadstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5811

___

### onlostpointercapture

• **onlostpointercapture**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onlostpointercapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5812

___

### onmousedown

• **onmousedown**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user clicks the object with either mouse button.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onmousedown

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5817

___

### onmouseenter

• **onmouseenter**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `MouseEvent` |

##### Returns

`any`

#### Inherited from

Document.onmouseenter

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5818

___

### onmouseleave

• **onmouseleave**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `MouseEvent` |

##### Returns

`any`

#### Inherited from

Document.onmouseleave

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5819

___

### onmousemove

• **onmousemove**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user moves the mouse over the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onmousemove

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5824

___

### onmouseout

• **onmouseout**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user moves the mouse pointer outside the boundaries of the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onmouseout

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5829

___

### onmouseover

• **onmouseover**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user moves the mouse pointer into the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onmouseover

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5834

___

### onmouseup

• **onmouseup**: (`ev`: `MouseEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user releases a mouse button while the mouse is over the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `MouseEvent` | The mouse event. |

##### Returns

`any`

#### Inherited from

Document.onmouseup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5839

___

### onpaste

• **onpaste**: (`ev`: `ClipboardEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `ClipboardEvent` |

##### Returns

`any`

#### Inherited from

Document.onpaste

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4732

___

### onpause

• **onpause**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when playback is paused.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onpause

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5844

___

### onplay

• **onplay**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the play method is requested.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onplay

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5849

___

### onplaying

• **onplaying**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the audio or video has started playing.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onplaying

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5854

___

### onpointercancel

• **onpointercancel**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointercancel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5855

___

### onpointerdown

• **onpointerdown**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerdown

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5856

___

### onpointerenter

• **onpointerenter**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerenter

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5857

___

### onpointerleave

• **onpointerleave**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerleave

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5858

___

### onpointerlockchange

• **onpointerlockchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onpointerlockchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4406

___

### onpointerlockerror

• **onpointerlockerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onpointerlockerror

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4407

___

### onpointermove

• **onpointermove**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointermove

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5859

___

### onpointerout

• **onpointerout**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerout

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5860

___

### onpointerover

• **onpointerover**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerover

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5861

___

### onpointerup

• **onpointerup**: (`ev`: `PointerEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `PointerEvent` |

##### Returns

`any`

#### Inherited from

Document.onpointerup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5862

___

### onprogress

• **onprogress**: (`ev`: [`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs to indicate progress while downloading media data.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | [`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\> | The event. |

##### Returns

`any`

#### Inherited from

Document.onprogress

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5867

___

### onratechange

• **onratechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the playback rate is increased or decreased.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onratechange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5872

___

### onreadystatechange

• **onreadystatechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the state of the object has changed.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event |

##### Returns

`any`

#### Inherited from

Document.onreadystatechange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4412

___

### onreset

• **onreset**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user resets a form.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onreset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5877

___

### onresize

• **onresize**: (`ev`: `UIEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `UIEvent` |

##### Returns

`any`

#### Inherited from

Document.onresize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5878

___

### onscroll

• **onscroll**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the user repositions the scroll box in the scroll bar on the object.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onscroll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5883

___

### onseeked

• **onseeked**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the seek operation ends.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onseeked

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5888

___

### onseeking

• **onseeking**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the current playback position is moved.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onseeking

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5893

___

### onselect

• **onselect**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Fires when the current selection changes.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onselect

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5898

___

### onselectionchange

• **onselectionchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onselectionchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5899

___

### onselectstart

• **onselectstart**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onselectstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5900

___

### onstalled

• **onstalled**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the download has stopped.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onstalled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5905

___

### onsubmit

• **onsubmit**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onsubmit

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5906

___

### onsuspend

• **onsuspend**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs if the load operation has been intentionally halted.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onsuspend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5911

___

### ontimeupdate

• **ontimeupdate**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs to indicate the current playback position.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.ontimeupdate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5916

___

### ontoggle

• **ontoggle**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.ontoggle

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5917

___

### ontouchcancel

• `Optional` **ontouchcancel**: (`ev`: `TouchEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TouchEvent` |

##### Returns

`any`

#### Inherited from

Document.ontouchcancel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5918

___

### ontouchend

• `Optional` **ontouchend**: (`ev`: `TouchEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TouchEvent` |

##### Returns

`any`

#### Inherited from

Document.ontouchend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5919

___

### ontouchmove

• `Optional` **ontouchmove**: (`ev`: `TouchEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TouchEvent` |

##### Returns

`any`

#### Inherited from

Document.ontouchmove

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5920

___

### ontouchstart

• `Optional` **ontouchstart**: (`ev`: `TouchEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TouchEvent` |

##### Returns

`any`

#### Inherited from

Document.ontouchstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5921

___

### ontransitioncancel

• **ontransitioncancel**: (`ev`: `TransitionEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TransitionEvent` |

##### Returns

`any`

#### Inherited from

Document.ontransitioncancel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5922

___

### ontransitionend

• **ontransitionend**: (`ev`: `TransitionEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TransitionEvent` |

##### Returns

`any`

#### Inherited from

Document.ontransitionend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5923

___

### ontransitionrun

• **ontransitionrun**: (`ev`: `TransitionEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TransitionEvent` |

##### Returns

`any`

#### Inherited from

Document.ontransitionrun

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5924

___

### ontransitionstart

• **ontransitionstart**: (`ev`: `TransitionEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `TransitionEvent` |

##### Returns

`any`

#### Inherited from

Document.ontransitionstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5925

___

### onvisibilitychange

• **onvisibilitychange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onvisibilitychange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4413

___

### onvolumechange

• **onvolumechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when the volume is changed, or playback is muted or unmuted.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onvolumechange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5930

___

### onwaiting

• **onwaiting**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs when playback stops because the next frame of a video resource is not available.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | `Event` | The event. |

##### Returns

`any`

#### Inherited from

Document.onwaiting

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5935

___

### onwebkitanimationend

• **onwebkitanimationend**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onwebkitanimationend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5936

___

### onwebkitanimationiteration

• **onwebkitanimationiteration**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onwebkitanimationiteration

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5937

___

### onwebkitanimationstart

• **onwebkitanimationstart**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onwebkitanimationstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5938

___

### onwebkittransitionend

• **onwebkittransitionend**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

Document.onwebkittransitionend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5939

___

### onwheel

• **onwheel**: (`ev`: `WheelEvent`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `WheelEvent` |

##### Returns

`any`

#### Inherited from

Document.onwheel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5940

___

### ownerDocument

• `Readonly` **ownerDocument**: ``null``

#### Inherited from

Document.ownerDocument

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4414

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Inherited from

Document.parentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_design_system._internal_.ParentNode.md)

Returns the parent.

#### Inherited from

Document.parentNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### pictureInPictureElement

• `Readonly` **pictureInPictureElement**: `Element`

#### Inherited from

Document.pictureInPictureElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4763

___

### pictureInPictureEnabled

• `Readonly` **pictureInPictureEnabled**: `boolean`

#### Inherited from

Document.pictureInPictureEnabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4415

___

### plugins

• `Readonly` **plugins**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLEmbedElement`\>

Return an HTMLCollection of the embed elements in the Document.

#### Inherited from

Document.plugins

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4419

___

### pointerLockElement

• `Readonly` **pointerLockElement**: `Element`

#### Inherited from

Document.pointerLockElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4764

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the previous sibling.

#### Inherited from

Document.previousSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### readyState

• `Readonly` **readyState**: [`DocumentReadyState`](../modules/akashaproject_design_system._internal_.md#documentreadystate)

Retrieves a value that indicates the current state of the object.

#### Inherited from

Document.readyState

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4423

___

### referrer

• `Readonly` **referrer**: `string`

Gets the URL of the location that referred the user to the current page.

#### Inherited from

Document.referrer

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4427

___

### rootElement

• `Readonly` **rootElement**: `SVGSVGElement`

**`deprecated`**

#### Inherited from

Document.rootElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4429

___

### scripts

• `Readonly` **scripts**: [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLScriptElement`\>

Retrieves a collection of all script objects in the document.

#### Inherited from

Document.scripts

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4433

___

### scrollingElement

• `Readonly` **scrollingElement**: `Element`

#### Inherited from

Document.scrollingElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4434

___

### styleSheets

• `Readonly` **styleSheets**: [`StyleSheetList`](../modules/akashaproject_design_system._internal_.md#stylesheetlist)

Retrieves a collection of styleSheet objects representing the style sheets that correspond to each instance of a link or style object in the document.

#### Inherited from

Document.styleSheets

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4768

___

### textContent

• **textContent**: `string`

#### Inherited from

Document.textContent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10541

___

### timeline

• `Readonly` **timeline**: [`DocumentTimeline`](../modules/akashaproject_design_system._internal_.md#documenttimeline)

#### Inherited from

Document.timeline

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4435

___

### title

• **title**: `string`

Contains the title of the document.

#### Inherited from

Document.title

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4439

___

### visibilityState

• `Readonly` **visibilityState**: [`VisibilityState`](../modules/akashaproject_design_system._internal_.md#visibilitystate)

#### Inherited from

Document.visibilityState

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4440

___

### vlinkColor

• **vlinkColor**: `string`

Sets or gets the color of the links that the user has visited.

**`deprecated`**

#### Inherited from

Document.vlinkColor

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4445

## Accessors

### location

• `get` **location**(): [`Location`](../modules/akashaproject_design_system._internal_.md#location)

Contains information about the current URL.

#### Returns

[`Location`](../modules/akashaproject_design_system._internal_.md#location)

#### Inherited from

Document.location

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4402

• `set` **location**(`href`): `void`

Contains information about the current URL.

#### Parameters

| Name | Type |
| :------ | :------ |
| `href` | `string` \| [`Location`](../modules/akashaproject_design_system._internal_.md#location) |

#### Returns

`void`

#### Inherited from

Document.location

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4403

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`DocumentEventMap`](akashaproject_design_system._internal_.DocumentEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`DocumentEventMap`](akashaproject_design_system._internal_.DocumentEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

Document.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17511

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

Document.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17512

___

### adoptNode

▸ **adoptNode**<`T`\>(`node`): `T`

Moves node from another document and returns it.

If node is a document, throws a "NotSupportedError" DOMException or, if node is a shadow root, throws a "HierarchyRequestError" DOMException.

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

Document.adoptNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4451

___

### append

▸ **append**(...`nodes`): `void`

Inserts nodes after the last child of node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

Document.append

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10976

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

Document.appendChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10542

___

### captureEvents

▸ **captureEvents**(): `void`

**`deprecated`**

#### Returns

`void`

#### Inherited from

Document.captureEvents

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4453

___

### caretRangeFromPoint

▸ **caretRangeFromPoint**(`x`, `y`): [`Range`](../modules/akashaproject_design_system._internal_.md#range)

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

[`Range`](../modules/akashaproject_design_system._internal_.md#range)

#### Inherited from

Document.caretRangeFromPoint

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4455

___

### clear

▸ **clear**(): `void`

**`deprecated`**

#### Returns

`void`

#### Inherited from

Document.clear

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4457

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

Document.cloneNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10546

___

### close

▸ **close**(): `void`

Closes an output stream and forces the sent data to display.

#### Returns

`void`

#### Inherited from

Document.close

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4461

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

Document.compareDocumentPosition

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

Document.contains

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10554

___

### createAttribute

▸ **createAttribute**(`localName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

Creates an attribute object with a specified name.

#### Parameters

| Name | Type |
| :------ | :------ |
| `localName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

Document.createAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4466

___

### createAttributeNS

▸ **createAttributeNS**(`namespace`, `qualifiedName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `qualifiedName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

Document.createAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4467

___

### createCDATASection

▸ **createCDATASection**(`data`): [`CDATASection`](../modules/akashaproject_design_system._internal_.md#cdatasection)

Returns a CDATASection node whose data is data.

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

[`CDATASection`](../modules/akashaproject_design_system._internal_.md#cdatasection)

#### Inherited from

Document.createCDATASection

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4471

___

### createComment

▸ **createComment**(`data`): [`Comment`](../modules/akashaproject_design_system._internal_.md#comment)

Creates a comment object with the specified data.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `data` | `string` | Sets the comment object's data. |

#### Returns

[`Comment`](../modules/akashaproject_design_system._internal_.md#comment)

#### Inherited from

Document.createComment

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4476

___

### createDocumentFragment

▸ **createDocumentFragment**(): `DocumentFragment`

Creates a new document.

#### Returns

`DocumentFragment`

#### Inherited from

Document.createDocumentFragment

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4480

___

### createElement

▸ **createElement**<`K`\>(`tagName`, `options?`): [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

Creates an instance of the element for the specified tag.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagName` | `K` | The name of an element. |
| `options?` | [`ElementCreationOptions`](akashaproject_design_system._internal_.ElementCreationOptions.md) | - |

#### Returns

[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

#### Inherited from

Document.createElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4485

▸ **createElement**<`K`\>(`tagName`, `options?`): [`HTMLElementDeprecatedTagNameMap`](akashaproject_design_system._internal_.HTMLElementDeprecatedTagNameMap.md)[`K`]

**`deprecated`**

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementDeprecatedTagNameMap`](akashaproject_design_system._internal_.HTMLElementDeprecatedTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `K` |
| `options?` | [`ElementCreationOptions`](akashaproject_design_system._internal_.ElementCreationOptions.md) |

#### Returns

[`HTMLElementDeprecatedTagNameMap`](akashaproject_design_system._internal_.HTMLElementDeprecatedTagNameMap.md)[`K`]

#### Inherited from

Document.createElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4487

▸ **createElement**(`tagName`, `options?`): `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |
| `options?` | [`ElementCreationOptions`](akashaproject_design_system._internal_.ElementCreationOptions.md) |

#### Returns

`HTMLElement`

#### Inherited from

Document.createElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4488

___

### createElementNS

▸ **createElementNS**(`namespaceURI`, `qualifiedName`): `HTMLElement`

Returns an element with namespace namespace. Its namespace prefix will be everything before ":" (U+003E) in qualifiedName or null. Its local name will be everything after ":" (U+003E) in qualifiedName or qualifiedName.

If localName does not match the Name production an "InvalidCharacterError" DOMException will be thrown.

If one of the following conditions is true a "NamespaceError" DOMException will be thrown:

localName does not match the QName production.
Namespace prefix is not null and namespace is the empty string.
Namespace prefix is "xml" and namespace is not the XML namespace.
qualifiedName or namespace prefix is "xmlns" and namespace is not the XMLNS namespace.
namespace is the XMLNS namespace and neither qualifiedName nor namespace prefix is "xmlns".

When supplied, options's is can be used to create a customized built-in element.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/1999/xhtml"`` |
| `qualifiedName` | `string` |

#### Returns

`HTMLElement`

#### Inherited from

Document.createElementNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4504

▸ **createElementNS**<`K`\>(`namespaceURI`, `qualifiedName`): [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/2000/svg"`` |
| `qualifiedName` | `K` |

#### Returns

[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Inherited from

Document.createElementNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4505

▸ **createElementNS**(`namespaceURI`, `qualifiedName`): `SVGElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/2000/svg"`` |
| `qualifiedName` | `string` |

#### Returns

`SVGElement`

#### Inherited from

Document.createElementNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4506

▸ **createElementNS**(`namespaceURI`, `qualifiedName`, `options?`): `Element`

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | `string` |
| `qualifiedName` | `string` |
| `options?` | [`ElementCreationOptions`](akashaproject_design_system._internal_.ElementCreationOptions.md) |

#### Returns

`Element`

#### Inherited from

Document.createElementNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4507

▸ **createElementNS**(`namespace`, `qualifiedName`, `options?`): `Element`

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `qualifiedName` | `string` |
| `options?` | `string` \| [`ElementCreationOptions`](akashaproject_design_system._internal_.ElementCreationOptions.md) |

#### Returns

`Element`

#### Inherited from

Document.createElementNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4508

___

### createEvent

▸ **createEvent**(`eventInterface`): `AnimationEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"AnimationEvent"`` |

#### Returns

`AnimationEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4509

▸ **createEvent**(`eventInterface`): [`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"AnimationPlaybackEvent"`` |

#### Returns

[`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4510

▸ **createEvent**(`eventInterface`): [`AudioProcessingEvent`](../modules/akashaproject_design_system._internal_.md#audioprocessingevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"AudioProcessingEvent"`` |

#### Returns

[`AudioProcessingEvent`](../modules/akashaproject_design_system._internal_.md#audioprocessingevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4511

▸ **createEvent**(`eventInterface`): [`BeforeUnloadEvent`](../modules/akashaproject_design_system._internal_.md#beforeunloadevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"BeforeUnloadEvent"`` |

#### Returns

[`BeforeUnloadEvent`](../modules/akashaproject_design_system._internal_.md#beforeunloadevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4512

▸ **createEvent**(`eventInterface`): [`BlobEvent`](../modules/akashaproject_design_system._internal_.md#blobevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"BlobEvent"`` |

#### Returns

[`BlobEvent`](../modules/akashaproject_design_system._internal_.md#blobevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4513

▸ **createEvent**(`eventInterface`): `ClipboardEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"ClipboardEvent"`` |

#### Returns

`ClipboardEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4514

▸ **createEvent**(`eventInterface`): [`CloseEvent`](../modules/akashaproject_design_system._internal_.md#closeevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"CloseEvent"`` |

#### Returns

[`CloseEvent`](../modules/akashaproject_design_system._internal_.md#closeevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4515

▸ **createEvent**(`eventInterface`): `CompositionEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"CompositionEvent"`` |

#### Returns

`CompositionEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4516

▸ **createEvent**(`eventInterface`): [`CustomEvent`](../modules/akashaproject_design_system._internal_.md#customevent)<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"CustomEvent"`` |

#### Returns

[`CustomEvent`](../modules/akashaproject_design_system._internal_.md#customevent)<`any`\>

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4517

▸ **createEvent**(`eventInterface`): [`DeviceMotionEvent`](../modules/akashaproject_design_system._internal_.md#devicemotionevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"DeviceMotionEvent"`` |

#### Returns

[`DeviceMotionEvent`](../modules/akashaproject_design_system._internal_.md#devicemotionevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4518

▸ **createEvent**(`eventInterface`): [`DeviceOrientationEvent`](../modules/akashaproject_design_system._internal_.md#deviceorientationevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"DeviceOrientationEvent"`` |

#### Returns

[`DeviceOrientationEvent`](../modules/akashaproject_design_system._internal_.md#deviceorientationevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4519

▸ **createEvent**(`eventInterface`): `DragEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"DragEvent"`` |

#### Returns

`DragEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4520

▸ **createEvent**(`eventInterface`): [`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"ErrorEvent"`` |

#### Returns

[`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4521

▸ **createEvent**(`eventInterface`): `FocusEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"FocusEvent"`` |

#### Returns

`FocusEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4522

▸ **createEvent**(`eventInterface`): [`FontFaceSetLoadEvent`](../modules/akashaproject_design_system._internal_.md#fontfacesetloadevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"FontFaceSetLoadEvent"`` |

#### Returns

[`FontFaceSetLoadEvent`](../modules/akashaproject_design_system._internal_.md#fontfacesetloadevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4523

▸ **createEvent**(`eventInterface`): [`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"FormDataEvent"`` |

#### Returns

[`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4524

▸ **createEvent**(`eventInterface`): [`GamepadEvent`](../modules/akashaproject_design_system._internal_.md#gamepadevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"GamepadEvent"`` |

#### Returns

[`GamepadEvent`](../modules/akashaproject_design_system._internal_.md#gamepadevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4525

▸ **createEvent**(`eventInterface`): [`HashChangeEvent`](../modules/akashaproject_design_system._internal_.md#hashchangeevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"HashChangeEvent"`` |

#### Returns

[`HashChangeEvent`](../modules/akashaproject_design_system._internal_.md#hashchangeevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4526

▸ **createEvent**(`eventInterface`): [`IDBVersionChangeEvent`](../modules/akashaproject_design_system._internal_.md#idbversionchangeevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"IDBVersionChangeEvent"`` |

#### Returns

[`IDBVersionChangeEvent`](../modules/akashaproject_design_system._internal_.md#idbversionchangeevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4527

▸ **createEvent**(`eventInterface`): [`InputEvent`](../modules/akashaproject_design_system._internal_.md#inputevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"InputEvent"`` |

#### Returns

[`InputEvent`](../modules/akashaproject_design_system._internal_.md#inputevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4528

▸ **createEvent**(`eventInterface`): `KeyboardEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"KeyboardEvent"`` |

#### Returns

`KeyboardEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4529

▸ **createEvent**(`eventInterface`): [`MediaEncryptedEvent`](../modules/akashaproject_design_system._internal_.md#mediaencryptedevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MediaEncryptedEvent"`` |

#### Returns

[`MediaEncryptedEvent`](../modules/akashaproject_design_system._internal_.md#mediaencryptedevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4530

▸ **createEvent**(`eventInterface`): [`MediaKeyMessageEvent`](../modules/akashaproject_design_system._internal_.md#mediakeymessageevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MediaKeyMessageEvent"`` |

#### Returns

[`MediaKeyMessageEvent`](../modules/akashaproject_design_system._internal_.md#mediakeymessageevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4531

▸ **createEvent**(`eventInterface`): [`MediaQueryListEvent`](../modules/akashaproject_design_system._internal_.md#mediaquerylistevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MediaQueryListEvent"`` |

#### Returns

[`MediaQueryListEvent`](../modules/akashaproject_design_system._internal_.md#mediaquerylistevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4532

▸ **createEvent**(`eventInterface`): [`MediaRecorderErrorEvent`](../modules/akashaproject_design_system._internal_.md#mediarecordererrorevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MediaRecorderErrorEvent"`` |

#### Returns

[`MediaRecorderErrorEvent`](../modules/akashaproject_design_system._internal_.md#mediarecordererrorevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4533

▸ **createEvent**(`eventInterface`): [`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MediaStreamTrackEvent"`` |

#### Returns

[`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4534

▸ **createEvent**(`eventInterface`): [`MessageEvent`](../modules/akashaproject_design_system._internal_.md#messageevent)<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MessageEvent"`` |

#### Returns

[`MessageEvent`](../modules/akashaproject_design_system._internal_.md#messageevent)<`any`\>

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4535

▸ **createEvent**(`eventInterface`): `MouseEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MouseEvent"`` |

#### Returns

`MouseEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4536

▸ **createEvent**(`eventInterface`): `MouseEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MouseEvents"`` |

#### Returns

`MouseEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4537

▸ **createEvent**(`eventInterface`): [`MutationEvent`](../modules/akashaproject_design_system._internal_.md#mutationevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MutationEvent"`` |

#### Returns

[`MutationEvent`](../modules/akashaproject_design_system._internal_.md#mutationevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4538

▸ **createEvent**(`eventInterface`): [`MutationEvent`](../modules/akashaproject_design_system._internal_.md#mutationevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"MutationEvents"`` |

#### Returns

[`MutationEvent`](../modules/akashaproject_design_system._internal_.md#mutationevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4539

▸ **createEvent**(`eventInterface`): [`OfflineAudioCompletionEvent`](../modules/akashaproject_design_system._internal_.md#offlineaudiocompletionevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"OfflineAudioCompletionEvent"`` |

#### Returns

[`OfflineAudioCompletionEvent`](../modules/akashaproject_design_system._internal_.md#offlineaudiocompletionevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4540

▸ **createEvent**(`eventInterface`): [`PageTransitionEvent`](../modules/akashaproject_design_system._internal_.md#pagetransitionevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PageTransitionEvent"`` |

#### Returns

[`PageTransitionEvent`](../modules/akashaproject_design_system._internal_.md#pagetransitionevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4541

▸ **createEvent**(`eventInterface`): [`PaymentMethodChangeEvent`](../modules/akashaproject_design_system._internal_.md#paymentmethodchangeevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PaymentMethodChangeEvent"`` |

#### Returns

[`PaymentMethodChangeEvent`](../modules/akashaproject_design_system._internal_.md#paymentmethodchangeevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4542

▸ **createEvent**(`eventInterface`): [`PaymentRequestUpdateEvent`](../modules/akashaproject_design_system._internal_.md#paymentrequestupdateevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PaymentRequestUpdateEvent"`` |

#### Returns

[`PaymentRequestUpdateEvent`](../modules/akashaproject_design_system._internal_.md#paymentrequestupdateevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4543

▸ **createEvent**(`eventInterface`): `PointerEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PointerEvent"`` |

#### Returns

`PointerEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4544

▸ **createEvent**(`eventInterface`): [`PopStateEvent`](../modules/akashaproject_design_system._internal_.md#popstateevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PopStateEvent"`` |

#### Returns

[`PopStateEvent`](../modules/akashaproject_design_system._internal_.md#popstateevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4545

▸ **createEvent**(`eventInterface`): [`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"ProgressEvent"`` |

#### Returns

[`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\>

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4546

▸ **createEvent**(`eventInterface`): [`PromiseRejectionEvent`](../modules/akashaproject_design_system._internal_.md#promiserejectionevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"PromiseRejectionEvent"`` |

#### Returns

[`PromiseRejectionEvent`](../modules/akashaproject_design_system._internal_.md#promiserejectionevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4547

▸ **createEvent**(`eventInterface`): [`RTCDTMFToneChangeEvent`](../modules/akashaproject_design_system._internal_.md#rtcdtmftonechangeevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"RTCDTMFToneChangeEvent"`` |

#### Returns

[`RTCDTMFToneChangeEvent`](../modules/akashaproject_design_system._internal_.md#rtcdtmftonechangeevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4548

▸ **createEvent**(`eventInterface`): [`RTCDataChannelEvent`](../modules/akashaproject_design_system._internal_.md#rtcdatachannelevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"RTCDataChannelEvent"`` |

#### Returns

[`RTCDataChannelEvent`](../modules/akashaproject_design_system._internal_.md#rtcdatachannelevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4549

▸ **createEvent**(`eventInterface`): [`RTCPeerConnectionIceErrorEvent`](../modules/akashaproject_design_system._internal_.md#rtcpeerconnectioniceerrorevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"RTCPeerConnectionIceErrorEvent"`` |

#### Returns

[`RTCPeerConnectionIceErrorEvent`](../modules/akashaproject_design_system._internal_.md#rtcpeerconnectioniceerrorevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4550

▸ **createEvent**(`eventInterface`): [`RTCPeerConnectionIceEvent`](../modules/akashaproject_design_system._internal_.md#rtcpeerconnectioniceevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"RTCPeerConnectionIceEvent"`` |

#### Returns

[`RTCPeerConnectionIceEvent`](../modules/akashaproject_design_system._internal_.md#rtcpeerconnectioniceevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4551

▸ **createEvent**(`eventInterface`): [`RTCTrackEvent`](../modules/akashaproject_design_system._internal_.md#rtctrackevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"RTCTrackEvent"`` |

#### Returns

[`RTCTrackEvent`](../modules/akashaproject_design_system._internal_.md#rtctrackevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4552

▸ **createEvent**(`eventInterface`): [`SecurityPolicyViolationEvent`](../modules/akashaproject_design_system._internal_.md#securitypolicyviolationevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"SecurityPolicyViolationEvent"`` |

#### Returns

[`SecurityPolicyViolationEvent`](../modules/akashaproject_design_system._internal_.md#securitypolicyviolationevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4553

▸ **createEvent**(`eventInterface`): [`SpeechSynthesisErrorEvent`](../modules/akashaproject_design_system._internal_.md#speechsynthesiserrorevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"SpeechSynthesisErrorEvent"`` |

#### Returns

[`SpeechSynthesisErrorEvent`](../modules/akashaproject_design_system._internal_.md#speechsynthesiserrorevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4554

▸ **createEvent**(`eventInterface`): [`SpeechSynthesisEvent`](../modules/akashaproject_design_system._internal_.md#speechsynthesisevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"SpeechSynthesisEvent"`` |

#### Returns

[`SpeechSynthesisEvent`](../modules/akashaproject_design_system._internal_.md#speechsynthesisevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4555

▸ **createEvent**(`eventInterface`): [`StorageEvent`](../modules/akashaproject_design_system._internal_.md#storageevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"StorageEvent"`` |

#### Returns

[`StorageEvent`](../modules/akashaproject_design_system._internal_.md#storageevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4556

▸ **createEvent**(`eventInterface`): [`SubmitEvent`](../modules/akashaproject_design_system._internal_.md#submitevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"SubmitEvent"`` |

#### Returns

[`SubmitEvent`](../modules/akashaproject_design_system._internal_.md#submitevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4557

▸ **createEvent**(`eventInterface`): `TouchEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"TouchEvent"`` |

#### Returns

`TouchEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4558

▸ **createEvent**(`eventInterface`): [`TrackEvent`](../modules/akashaproject_design_system._internal_.md#trackevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"TrackEvent"`` |

#### Returns

[`TrackEvent`](../modules/akashaproject_design_system._internal_.md#trackevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4559

▸ **createEvent**(`eventInterface`): `TransitionEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"TransitionEvent"`` |

#### Returns

`TransitionEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4560

▸ **createEvent**(`eventInterface`): `UIEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"UIEvent"`` |

#### Returns

`UIEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4561

▸ **createEvent**(`eventInterface`): `UIEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"UIEvents"`` |

#### Returns

`UIEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4562

▸ **createEvent**(`eventInterface`): [`WebGLContextEvent`](../modules/akashaproject_design_system._internal_.md#webglcontextevent)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"WebGLContextEvent"`` |

#### Returns

[`WebGLContextEvent`](../modules/akashaproject_design_system._internal_.md#webglcontextevent)

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4563

▸ **createEvent**(`eventInterface`): `WheelEvent`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | ``"WheelEvent"`` |

#### Returns

`WheelEvent`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4564

▸ **createEvent**(`eventInterface`): `Event`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventInterface` | `string` |

#### Returns

`Event`

#### Inherited from

Document.createEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4565

___

### createExpression

▸ **createExpression**(`expression`, `resolver?`): [`XPathExpression`](../modules/akashaproject_design_system._internal_.md#xpathexpression)

#### Parameters

| Name | Type |
| :------ | :------ |
| `expression` | `string` |
| `resolver?` | [`XPathNSResolver`](../modules/akashaproject_design_system._internal_.md#xpathnsresolver) |

#### Returns

[`XPathExpression`](../modules/akashaproject_design_system._internal_.md#xpathexpression)

#### Inherited from

Document.createExpression

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17699

___

### createNSResolver

▸ **createNSResolver**(`nodeResolver`): [`XPathNSResolver`](../modules/akashaproject_design_system._internal_.md#xpathnsresolver)

#### Parameters

| Name | Type |
| :------ | :------ |
| `nodeResolver` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Returns

[`XPathNSResolver`](../modules/akashaproject_design_system._internal_.md#xpathnsresolver)

#### Inherited from

Document.createNSResolver

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17700

___

### createNodeIterator

▸ **createNodeIterator**(`root`, `whatToShow?`, `filter?`): [`NodeIterator`](../modules/akashaproject_design_system._internal_.md#nodeiterator)

Creates a NodeIterator object that you can use to traverse filtered lists of nodes or elements in a document.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `root` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) | The root element or node to start traversing on. |
| `whatToShow?` | `number` | The type of nodes or elements to appear in the node list |
| `filter?` | [`NodeFilter`](../modules/akashaproject_design_system._internal_.md#nodefilter) | A custom NodeFilter function to use. For more information, see filter. Use null for no filter. |

#### Returns

[`NodeIterator`](../modules/akashaproject_design_system._internal_.md#nodeiterator)

#### Inherited from

Document.createNodeIterator

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4572

___

### createProcessingInstruction

▸ **createProcessingInstruction**(`target`, `data`): [`ProcessingInstruction`](../modules/akashaproject_design_system._internal_.md#processinginstruction)

Returns a ProcessingInstruction node whose target is target and data is data. If target does not match the Name production an "InvalidCharacterError" DOMException will be thrown. If data contains "?>" an "InvalidCharacterError" DOMException will be thrown.

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `string` |
| `data` | `string` |

#### Returns

[`ProcessingInstruction`](../modules/akashaproject_design_system._internal_.md#processinginstruction)

#### Inherited from

Document.createProcessingInstruction

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4576

___

### createRange

▸ **createRange**(): [`Range`](../modules/akashaproject_design_system._internal_.md#range)

 Returns an empty range object that has both of its boundary points positioned at the beginning of the document.

#### Returns

[`Range`](../modules/akashaproject_design_system._internal_.md#range)

#### Inherited from

Document.createRange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4580

___

### createTextNode

▸ **createTextNode**(`data`): `Text`

Creates a text string from the specified value.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `data` | `string` | String that specifies the nodeValue property of the text node. |

#### Returns

`Text`

#### Inherited from

Document.createTextNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4585

___

### createTreeWalker

▸ **createTreeWalker**(`root`, `whatToShow?`, `filter?`): [`TreeWalker`](../modules/akashaproject_design_system._internal_.md#treewalker)

Creates a TreeWalker object that you can use to traverse filtered lists of nodes or elements in a document.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `root` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) | The root element or node to start traversing on. |
| `whatToShow?` | `number` | The type of nodes or elements to appear in the node list. For more information, see whatToShow. |
| `filter?` | [`NodeFilter`](../modules/akashaproject_design_system._internal_.md#nodefilter) | A custom NodeFilter function to use. |

#### Returns

[`TreeWalker`](../modules/akashaproject_design_system._internal_.md#treewalker)

#### Inherited from

Document.createTreeWalker

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4592

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

Document.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### elementFromPoint

▸ **elementFromPoint**(`x`, `y`): `Element`

Returns the element for the specified x coordinate and the specified y coordinate.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | `number` | The x-offset |
| `y` | `number` | The y-offset |

#### Returns

`Element`

#### Inherited from

Document.elementFromPoint

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4598

___

### elementsFromPoint

▸ **elementsFromPoint**(`x`, `y`): `Element`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`Element`[]

#### Inherited from

Document.elementsFromPoint

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4599

___

### evaluate

▸ **evaluate**(`expression`, `contextNode`, `resolver?`, `type?`, `result?`): [`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `expression` | `string` |
| `contextNode` | [`Node`](../modules/akashaproject_design_system._internal_.md#node) |
| `resolver?` | [`XPathNSResolver`](../modules/akashaproject_design_system._internal_.md#xpathnsresolver) |
| `type?` | `number` |
| `result?` | [`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult) |

#### Returns

[`XPathResult`](../modules/akashaproject_design_system._internal_.md#xpathresult)

#### Inherited from

Document.evaluate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17701

___

### execCommand

▸ **execCommand**(`commandId`, `showUI?`, `value?`): `boolean`

Executes a command on the current document, current selection, or the given range.

**`deprecated`**

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | String that specifies the command to execute. This command can be any of the command identifiers that can be executed in script. |
| `showUI?` | `boolean` | Display the user interface, defaults to false. |
| `value?` | `string` | Value to assign. |

#### Returns

`boolean`

#### Inherited from

Document.execCommand

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4607

___

### exitFullscreen

▸ **exitFullscreen**(): `Promise`<`void`\>

Stops document's fullscreen element from being displayed fullscreen and resolves promise when done.

#### Returns

`Promise`<`void`\>

#### Inherited from

Document.exitFullscreen

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4611

___

### exitPictureInPicture

▸ **exitPictureInPicture**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Inherited from

Document.exitPictureInPicture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4612

___

### exitPointerLock

▸ **exitPointerLock**(): `void`

#### Returns

`void`

#### Inherited from

Document.exitPointerLock

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4613

___

### getAnimations

▸ **getAnimations**(): [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Returns

[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Inherited from

Document.getAnimations

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4769

___

### getElementById

▸ **getElementById**(`elementId`): `HTMLElement`

Returns a reference to the first object with the specified value of the ID attribute.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `elementId` | `string` | String that specifies the ID value. |

#### Returns

`HTMLElement`

#### Inherited from

Document.getElementById

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4618

___

### getElementsByClassName

▸ **getElementsByClassName**(`classNames`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

Returns a HTMLCollection of the elements in the object on which the method was invoked (a document or an element) that have all the classes given by classNames. The classNames argument is interpreted as a space-separated list of classes.

#### Parameters

| Name | Type |
| :------ | :------ |
| `classNames` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

Document.getElementsByClassName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4622

___

### getElementsByName

▸ **getElementsByName**(`elementName`): [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<`HTMLElement`\>

Gets a collection of objects based on the value of the NAME or ID attribute.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `elementName` | `string` | Gets a collection of objects based on the value of the NAME or ID attribute. |

#### Returns

[`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<`HTMLElement`\>

#### Inherited from

Document.getElementsByName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4627

___

### getElementsByTagName

▸ **getElementsByTagName**<`K`\>(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]\>

Retrieves a collection of objects based on the specified element name.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `K` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]\>

#### Inherited from

Document.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4632

▸ **getElementsByTagName**<`K`\>(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `K` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Inherited from

Document.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4633

▸ **getElementsByTagName**(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

Document.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4634

___

### getElementsByTagNameNS

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

If namespace and localName are "*" returns a HTMLCollection of all descendant elements.

If only namespace is "*" returns a HTMLCollection of all descendant elements whose local name is localName.

If only localName is "*" returns a HTMLCollection of all descendant elements whose namespace is namespace.

Otherwise, returns a HTMLCollection of all descendant elements whose namespace is namespace and local name is localName.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/1999/xhtml"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

#### Inherited from

Document.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4644

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/2000/svg"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Inherited from

Document.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4645

▸ **getElementsByTagNameNS**(`namespace`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

Document.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4646

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

Document.getRootNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### getSelection

▸ **getSelection**(): [`Selection`](../modules/akashaproject_design_system._internal_.md#selection)

Returns an object representing the current selection of the document that is loaded into the object displaying a webpage.

#### Returns

[`Selection`](../modules/akashaproject_design_system._internal_.md#selection)

#### Inherited from

Document.getSelection

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4650

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Inherited from

Document.hasChildNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10562

___

### hasFocus

▸ **hasFocus**(): `boolean`

Gets a value indicating whether the object currently has focus.

#### Returns

`boolean`

#### Inherited from

Document.hasFocus

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4654

___

### hasStorageAccess

▸ **hasStorageAccess**(): `Promise`<`boolean`\>

#### Returns

`Promise`<`boolean`\>

#### Inherited from

Document.hasStorageAccess

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4655

___

### importNode

▸ **importNode**<`T`\>(`node`, `deep?`): `T`

Returns a copy of node. If deep is true, the copy also includes the node's descendants.

If node is a document or a shadow root, throws a "NotSupportedError" DOMException.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Node`](../modules/akashaproject_design_system._internal_.md#node) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `T` |
| `deep?` | `boolean` |

#### Returns

`T`

#### Inherited from

Document.importNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4661

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

Document.insertBefore

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

Document.isDefaultNamespace

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

Document.isEqualNode

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

Document.isSameNode

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

Document.lookupNamespaceURI

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

Document.lookupPrefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10571

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Inherited from

Document.normalize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10575

___

### open

▸ **open**(`unused1?`, `unused2?`): `Document`

Opens a new window and loads a document specified by a given URL. Also, opens a new window that uses the url parameter and the name parameter to collect the output of the write method and the writeln method.

#### Parameters

| Name | Type |
| :------ | :------ |
| `unused1?` | `string` |
| `unused2?` | `string` |

#### Returns

`Document`

#### Inherited from

Document.open

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4669

▸ **open**(`url`, `name`, `features`): `Window`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` \| [`URL`](../modules/akashaproject_design_system._internal_.md#url) |
| `name` | `string` |
| `features` | `string` |

#### Returns

`Window`

#### Inherited from

Document.open

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4670

___

### prepend

▸ **prepend**(...`nodes`): `void`

Inserts nodes before the first child of node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

Document.prepend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10982

___

### queryCommandEnabled

▸ **queryCommandEnabled**(`commandId`): `boolean`

Returns a Boolean value that indicates whether a specified command can be successfully executed using execCommand, given the current state of the document.

**`deprecated`**

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | Specifies a command identifier. |

#### Returns

`boolean`

#### Inherited from

Document.queryCommandEnabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4676

___

### queryCommandIndeterm

▸ **queryCommandIndeterm**(`commandId`): `boolean`

Returns a Boolean value that indicates whether the specified command is in the indeterminate state.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | String that specifies a command identifier. |

#### Returns

`boolean`

#### Inherited from

Document.queryCommandIndeterm

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4681

___

### queryCommandState

▸ **queryCommandState**(`commandId`): `boolean`

Returns a Boolean value that indicates the current state of the command.

**`deprecated`**

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | String that specifies a command identifier. |

#### Returns

`boolean`

#### Inherited from

Document.queryCommandState

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4687

___

### queryCommandSupported

▸ **queryCommandSupported**(`commandId`): `boolean`

Returns a Boolean value that indicates whether the current command is supported on the current range.

**`deprecated`**

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | Specifies a command identifier. |

#### Returns

`boolean`

#### Inherited from

Document.queryCommandSupported

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4693

___

### queryCommandValue

▸ **queryCommandValue**(`commandId`): `string`

Returns the current value of the document, range, or current selection for the given command.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commandId` | `string` | String that specifies a command identifier. |

#### Returns

`string`

#### Inherited from

Document.queryCommandValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4698

___

### querySelector

▸ **querySelector**<`K`\>(`selectors`): [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

Returns the first element that is a descendant of node that matches selectors.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

#### Inherited from

Document.querySelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10986

▸ **querySelector**<`K`\>(`selectors`): [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Inherited from

Document.querySelector

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

Document.querySelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10988

___

### querySelectorAll

▸ **querySelectorAll**<`K`\>(`selectors`): [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]\>

Returns all element descendants of node that match selectors.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]\>

#### Inherited from

Document.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10992

▸ **querySelectorAll**<`K`\>(`selectors`): [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `K` |

#### Returns

[`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Inherited from

Document.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10993

▸ **querySelectorAll**<`E`\>(`selectors`): [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<`E`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `E` | extends `Element` = `Element` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `string` |

#### Returns

[`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<`E`\>

#### Inherited from

Document.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10994

___

### releaseEvents

▸ **releaseEvents**(): `void`

**`deprecated`**

#### Returns

`void`

#### Inherited from

Document.releaseEvents

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4700

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

Document.removeChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10576

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`DocumentEventMap`](akashaproject_design_system._internal_.DocumentEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`DocumentEventMap`](akashaproject_design_system._internal_.DocumentEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

Document.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17513

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

Document.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17514

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

Document.replaceChild

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
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

Document.replaceChildren

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11000

___

### requestStorageAccess

▸ **requestStorageAccess**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Inherited from

Document.requestStorageAccess

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4701

___

### write

▸ **write**(...`text`): `void`

Writes one or more HTML expressions to a document in the specified window.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...text` | `string`[] |

#### Returns

`void`

#### Inherited from

Document.write

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4706

___

### writeln

▸ **writeln**(...`text`): `void`

Writes one or more HTML expressions, followed by a carriage return, to a document in the specified window.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...text` | `string`[] |

#### Returns

`void`

#### Inherited from

Document.writeln

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4711
