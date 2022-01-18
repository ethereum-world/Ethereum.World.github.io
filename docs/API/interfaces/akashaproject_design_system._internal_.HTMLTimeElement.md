[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / HTMLTimeElement

# Interface: HTMLTimeElement

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).HTMLTimeElement

Provides special properties (beyond the regular HTMLElement interface it also has available to it by inheritance) for manipulating <time> elements.

## Hierarchy

- `HTMLElement`

  ↳ **`HTMLTimeElement`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_design_system._internal_.HTMLTimeElement.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#element_node)
- [ENTITY\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_design_system._internal_.HTMLTimeElement.md#text_node)
- [accessKey](akashaproject_design_system._internal_.HTMLTimeElement.md#accesskey)
- [accessKeyLabel](akashaproject_design_system._internal_.HTMLTimeElement.md#accesskeylabel)
- [ariaAtomic](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaatomic)
- [ariaAutoComplete](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaautocomplete)
- [ariaBusy](akashaproject_design_system._internal_.HTMLTimeElement.md#ariabusy)
- [ariaChecked](akashaproject_design_system._internal_.HTMLTimeElement.md#ariachecked)
- [ariaColCount](akashaproject_design_system._internal_.HTMLTimeElement.md#ariacolcount)
- [ariaColIndex](akashaproject_design_system._internal_.HTMLTimeElement.md#ariacolindex)
- [ariaColSpan](akashaproject_design_system._internal_.HTMLTimeElement.md#ariacolspan)
- [ariaCurrent](akashaproject_design_system._internal_.HTMLTimeElement.md#ariacurrent)
- [ariaDisabled](akashaproject_design_system._internal_.HTMLTimeElement.md#ariadisabled)
- [ariaExpanded](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaexpanded)
- [ariaHasPopup](akashaproject_design_system._internal_.HTMLTimeElement.md#ariahaspopup)
- [ariaHidden](akashaproject_design_system._internal_.HTMLTimeElement.md#ariahidden)
- [ariaKeyShortcuts](akashaproject_design_system._internal_.HTMLTimeElement.md#ariakeyshortcuts)
- [ariaLabel](akashaproject_design_system._internal_.HTMLTimeElement.md#arialabel)
- [ariaLevel](akashaproject_design_system._internal_.HTMLTimeElement.md#arialevel)
- [ariaLive](akashaproject_design_system._internal_.HTMLTimeElement.md#arialive)
- [ariaModal](akashaproject_design_system._internal_.HTMLTimeElement.md#ariamodal)
- [ariaMultiLine](akashaproject_design_system._internal_.HTMLTimeElement.md#ariamultiline)
- [ariaMultiSelectable](akashaproject_design_system._internal_.HTMLTimeElement.md#ariamultiselectable)
- [ariaOrientation](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaorientation)
- [ariaPlaceholder](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaplaceholder)
- [ariaPosInSet](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaposinset)
- [ariaPressed](akashaproject_design_system._internal_.HTMLTimeElement.md#ariapressed)
- [ariaReadOnly](akashaproject_design_system._internal_.HTMLTimeElement.md#ariareadonly)
- [ariaRequired](akashaproject_design_system._internal_.HTMLTimeElement.md#ariarequired)
- [ariaRoleDescription](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaroledescription)
- [ariaRowCount](akashaproject_design_system._internal_.HTMLTimeElement.md#ariarowcount)
- [ariaRowIndex](akashaproject_design_system._internal_.HTMLTimeElement.md#ariarowindex)
- [ariaRowSpan](akashaproject_design_system._internal_.HTMLTimeElement.md#ariarowspan)
- [ariaSelected](akashaproject_design_system._internal_.HTMLTimeElement.md#ariaselected)
- [ariaSetSize](akashaproject_design_system._internal_.HTMLTimeElement.md#ariasetsize)
- [ariaSort](akashaproject_design_system._internal_.HTMLTimeElement.md#ariasort)
- [ariaValueMax](akashaproject_design_system._internal_.HTMLTimeElement.md#ariavaluemax)
- [ariaValueMin](akashaproject_design_system._internal_.HTMLTimeElement.md#ariavaluemin)
- [ariaValueNow](akashaproject_design_system._internal_.HTMLTimeElement.md#ariavaluenow)
- [ariaValueText](akashaproject_design_system._internal_.HTMLTimeElement.md#ariavaluetext)
- [assignedSlot](akashaproject_design_system._internal_.HTMLTimeElement.md#assignedslot)
- [attributes](akashaproject_design_system._internal_.HTMLTimeElement.md#attributes)
- [autocapitalize](akashaproject_design_system._internal_.HTMLTimeElement.md#autocapitalize)
- [baseURI](akashaproject_design_system._internal_.HTMLTimeElement.md#baseuri)
- [childElementCount](akashaproject_design_system._internal_.HTMLTimeElement.md#childelementcount)
- [childNodes](akashaproject_design_system._internal_.HTMLTimeElement.md#childnodes)
- [children](akashaproject_design_system._internal_.HTMLTimeElement.md#children)
- [classList](akashaproject_design_system._internal_.HTMLTimeElement.md#classlist)
- [className](akashaproject_design_system._internal_.HTMLTimeElement.md#classname)
- [clientHeight](akashaproject_design_system._internal_.HTMLTimeElement.md#clientheight)
- [clientLeft](akashaproject_design_system._internal_.HTMLTimeElement.md#clientleft)
- [clientTop](akashaproject_design_system._internal_.HTMLTimeElement.md#clienttop)
- [clientWidth](akashaproject_design_system._internal_.HTMLTimeElement.md#clientwidth)
- [contentEditable](akashaproject_design_system._internal_.HTMLTimeElement.md#contenteditable)
- [dataset](akashaproject_design_system._internal_.HTMLTimeElement.md#dataset)
- [dateTime](akashaproject_design_system._internal_.HTMLTimeElement.md#datetime)
- [dir](akashaproject_design_system._internal_.HTMLTimeElement.md#dir)
- [draggable](akashaproject_design_system._internal_.HTMLTimeElement.md#draggable)
- [enterKeyHint](akashaproject_design_system._internal_.HTMLTimeElement.md#enterkeyhint)
- [firstChild](akashaproject_design_system._internal_.HTMLTimeElement.md#firstchild)
- [firstElementChild](akashaproject_design_system._internal_.HTMLTimeElement.md#firstelementchild)
- [hidden](akashaproject_design_system._internal_.HTMLTimeElement.md#hidden)
- [id](akashaproject_design_system._internal_.HTMLTimeElement.md#id)
- [innerHTML](akashaproject_design_system._internal_.HTMLTimeElement.md#innerhtml)
- [innerText](akashaproject_design_system._internal_.HTMLTimeElement.md#innertext)
- [inputMode](akashaproject_design_system._internal_.HTMLTimeElement.md#inputmode)
- [isConnected](akashaproject_design_system._internal_.HTMLTimeElement.md#isconnected)
- [isContentEditable](akashaproject_design_system._internal_.HTMLTimeElement.md#iscontenteditable)
- [lang](akashaproject_design_system._internal_.HTMLTimeElement.md#lang)
- [lastChild](akashaproject_design_system._internal_.HTMLTimeElement.md#lastchild)
- [lastElementChild](akashaproject_design_system._internal_.HTMLTimeElement.md#lastelementchild)
- [localName](akashaproject_design_system._internal_.HTMLTimeElement.md#localname)
- [namespaceURI](akashaproject_design_system._internal_.HTMLTimeElement.md#namespaceuri)
- [nextElementSibling](akashaproject_design_system._internal_.HTMLTimeElement.md#nextelementsibling)
- [nextSibling](akashaproject_design_system._internal_.HTMLTimeElement.md#nextsibling)
- [nodeName](akashaproject_design_system._internal_.HTMLTimeElement.md#nodename)
- [nodeType](akashaproject_design_system._internal_.HTMLTimeElement.md#nodetype)
- [nodeValue](akashaproject_design_system._internal_.HTMLTimeElement.md#nodevalue)
- [nonce](akashaproject_design_system._internal_.HTMLTimeElement.md#nonce)
- [offsetHeight](akashaproject_design_system._internal_.HTMLTimeElement.md#offsetheight)
- [offsetLeft](akashaproject_design_system._internal_.HTMLTimeElement.md#offsetleft)
- [offsetParent](akashaproject_design_system._internal_.HTMLTimeElement.md#offsetparent)
- [offsetTop](akashaproject_design_system._internal_.HTMLTimeElement.md#offsettop)
- [offsetWidth](akashaproject_design_system._internal_.HTMLTimeElement.md#offsetwidth)
- [onabort](akashaproject_design_system._internal_.HTMLTimeElement.md#onabort)
- [onanimationcancel](akashaproject_design_system._internal_.HTMLTimeElement.md#onanimationcancel)
- [onanimationend](akashaproject_design_system._internal_.HTMLTimeElement.md#onanimationend)
- [onanimationiteration](akashaproject_design_system._internal_.HTMLTimeElement.md#onanimationiteration)
- [onanimationstart](akashaproject_design_system._internal_.HTMLTimeElement.md#onanimationstart)
- [onauxclick](akashaproject_design_system._internal_.HTMLTimeElement.md#onauxclick)
- [onblur](akashaproject_design_system._internal_.HTMLTimeElement.md#onblur)
- [oncanplay](akashaproject_design_system._internal_.HTMLTimeElement.md#oncanplay)
- [oncanplaythrough](akashaproject_design_system._internal_.HTMLTimeElement.md#oncanplaythrough)
- [onchange](akashaproject_design_system._internal_.HTMLTimeElement.md#onchange)
- [onclick](akashaproject_design_system._internal_.HTMLTimeElement.md#onclick)
- [onclose](akashaproject_design_system._internal_.HTMLTimeElement.md#onclose)
- [oncontextmenu](akashaproject_design_system._internal_.HTMLTimeElement.md#oncontextmenu)
- [oncopy](akashaproject_design_system._internal_.HTMLTimeElement.md#oncopy)
- [oncuechange](akashaproject_design_system._internal_.HTMLTimeElement.md#oncuechange)
- [oncut](akashaproject_design_system._internal_.HTMLTimeElement.md#oncut)
- [ondblclick](akashaproject_design_system._internal_.HTMLTimeElement.md#ondblclick)
- [ondrag](akashaproject_design_system._internal_.HTMLTimeElement.md#ondrag)
- [ondragend](akashaproject_design_system._internal_.HTMLTimeElement.md#ondragend)
- [ondragenter](akashaproject_design_system._internal_.HTMLTimeElement.md#ondragenter)
- [ondragleave](akashaproject_design_system._internal_.HTMLTimeElement.md#ondragleave)
- [ondragover](akashaproject_design_system._internal_.HTMLTimeElement.md#ondragover)
- [ondragstart](akashaproject_design_system._internal_.HTMLTimeElement.md#ondragstart)
- [ondrop](akashaproject_design_system._internal_.HTMLTimeElement.md#ondrop)
- [ondurationchange](akashaproject_design_system._internal_.HTMLTimeElement.md#ondurationchange)
- [onemptied](akashaproject_design_system._internal_.HTMLTimeElement.md#onemptied)
- [onended](akashaproject_design_system._internal_.HTMLTimeElement.md#onended)
- [onerror](akashaproject_design_system._internal_.HTMLTimeElement.md#onerror)
- [onfocus](akashaproject_design_system._internal_.HTMLTimeElement.md#onfocus)
- [onformdata](akashaproject_design_system._internal_.HTMLTimeElement.md#onformdata)
- [onfullscreenchange](akashaproject_design_system._internal_.HTMLTimeElement.md#onfullscreenchange)
- [onfullscreenerror](akashaproject_design_system._internal_.HTMLTimeElement.md#onfullscreenerror)
- [ongotpointercapture](akashaproject_design_system._internal_.HTMLTimeElement.md#ongotpointercapture)
- [oninput](akashaproject_design_system._internal_.HTMLTimeElement.md#oninput)
- [oninvalid](akashaproject_design_system._internal_.HTMLTimeElement.md#oninvalid)
- [onkeydown](akashaproject_design_system._internal_.HTMLTimeElement.md#onkeydown)
- [onkeypress](akashaproject_design_system._internal_.HTMLTimeElement.md#onkeypress)
- [onkeyup](akashaproject_design_system._internal_.HTMLTimeElement.md#onkeyup)
- [onload](akashaproject_design_system._internal_.HTMLTimeElement.md#onload)
- [onloadeddata](akashaproject_design_system._internal_.HTMLTimeElement.md#onloadeddata)
- [onloadedmetadata](akashaproject_design_system._internal_.HTMLTimeElement.md#onloadedmetadata)
- [onloadstart](akashaproject_design_system._internal_.HTMLTimeElement.md#onloadstart)
- [onlostpointercapture](akashaproject_design_system._internal_.HTMLTimeElement.md#onlostpointercapture)
- [onmousedown](akashaproject_design_system._internal_.HTMLTimeElement.md#onmousedown)
- [onmouseenter](akashaproject_design_system._internal_.HTMLTimeElement.md#onmouseenter)
- [onmouseleave](akashaproject_design_system._internal_.HTMLTimeElement.md#onmouseleave)
- [onmousemove](akashaproject_design_system._internal_.HTMLTimeElement.md#onmousemove)
- [onmouseout](akashaproject_design_system._internal_.HTMLTimeElement.md#onmouseout)
- [onmouseover](akashaproject_design_system._internal_.HTMLTimeElement.md#onmouseover)
- [onmouseup](akashaproject_design_system._internal_.HTMLTimeElement.md#onmouseup)
- [onpaste](akashaproject_design_system._internal_.HTMLTimeElement.md#onpaste)
- [onpause](akashaproject_design_system._internal_.HTMLTimeElement.md#onpause)
- [onplay](akashaproject_design_system._internal_.HTMLTimeElement.md#onplay)
- [onplaying](akashaproject_design_system._internal_.HTMLTimeElement.md#onplaying)
- [onpointercancel](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointercancel)
- [onpointerdown](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerdown)
- [onpointerenter](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerenter)
- [onpointerleave](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerleave)
- [onpointermove](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointermove)
- [onpointerout](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerout)
- [onpointerover](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerover)
- [onpointerup](akashaproject_design_system._internal_.HTMLTimeElement.md#onpointerup)
- [onprogress](akashaproject_design_system._internal_.HTMLTimeElement.md#onprogress)
- [onratechange](akashaproject_design_system._internal_.HTMLTimeElement.md#onratechange)
- [onreset](akashaproject_design_system._internal_.HTMLTimeElement.md#onreset)
- [onresize](akashaproject_design_system._internal_.HTMLTimeElement.md#onresize)
- [onscroll](akashaproject_design_system._internal_.HTMLTimeElement.md#onscroll)
- [onseeked](akashaproject_design_system._internal_.HTMLTimeElement.md#onseeked)
- [onseeking](akashaproject_design_system._internal_.HTMLTimeElement.md#onseeking)
- [onselect](akashaproject_design_system._internal_.HTMLTimeElement.md#onselect)
- [onselectionchange](akashaproject_design_system._internal_.HTMLTimeElement.md#onselectionchange)
- [onselectstart](akashaproject_design_system._internal_.HTMLTimeElement.md#onselectstart)
- [onstalled](akashaproject_design_system._internal_.HTMLTimeElement.md#onstalled)
- [onsubmit](akashaproject_design_system._internal_.HTMLTimeElement.md#onsubmit)
- [onsuspend](akashaproject_design_system._internal_.HTMLTimeElement.md#onsuspend)
- [ontimeupdate](akashaproject_design_system._internal_.HTMLTimeElement.md#ontimeupdate)
- [ontoggle](akashaproject_design_system._internal_.HTMLTimeElement.md#ontoggle)
- [ontouchcancel](akashaproject_design_system._internal_.HTMLTimeElement.md#ontouchcancel)
- [ontouchend](akashaproject_design_system._internal_.HTMLTimeElement.md#ontouchend)
- [ontouchmove](akashaproject_design_system._internal_.HTMLTimeElement.md#ontouchmove)
- [ontouchstart](akashaproject_design_system._internal_.HTMLTimeElement.md#ontouchstart)
- [ontransitioncancel](akashaproject_design_system._internal_.HTMLTimeElement.md#ontransitioncancel)
- [ontransitionend](akashaproject_design_system._internal_.HTMLTimeElement.md#ontransitionend)
- [ontransitionrun](akashaproject_design_system._internal_.HTMLTimeElement.md#ontransitionrun)
- [ontransitionstart](akashaproject_design_system._internal_.HTMLTimeElement.md#ontransitionstart)
- [onvolumechange](akashaproject_design_system._internal_.HTMLTimeElement.md#onvolumechange)
- [onwaiting](akashaproject_design_system._internal_.HTMLTimeElement.md#onwaiting)
- [onwebkitanimationend](akashaproject_design_system._internal_.HTMLTimeElement.md#onwebkitanimationend)
- [onwebkitanimationiteration](akashaproject_design_system._internal_.HTMLTimeElement.md#onwebkitanimationiteration)
- [onwebkitanimationstart](akashaproject_design_system._internal_.HTMLTimeElement.md#onwebkitanimationstart)
- [onwebkittransitionend](akashaproject_design_system._internal_.HTMLTimeElement.md#onwebkittransitionend)
- [onwheel](akashaproject_design_system._internal_.HTMLTimeElement.md#onwheel)
- [outerHTML](akashaproject_design_system._internal_.HTMLTimeElement.md#outerhtml)
- [outerText](akashaproject_design_system._internal_.HTMLTimeElement.md#outertext)
- [ownerDocument](akashaproject_design_system._internal_.HTMLTimeElement.md#ownerdocument)
- [parentElement](akashaproject_design_system._internal_.HTMLTimeElement.md#parentelement)
- [parentNode](akashaproject_design_system._internal_.HTMLTimeElement.md#parentnode)
- [part](akashaproject_design_system._internal_.HTMLTimeElement.md#part)
- [prefix](akashaproject_design_system._internal_.HTMLTimeElement.md#prefix)
- [previousElementSibling](akashaproject_design_system._internal_.HTMLTimeElement.md#previouselementsibling)
- [previousSibling](akashaproject_design_system._internal_.HTMLTimeElement.md#previoussibling)
- [scrollHeight](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollheight)
- [scrollLeft](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollleft)
- [scrollTop](akashaproject_design_system._internal_.HTMLTimeElement.md#scrolltop)
- [scrollWidth](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollwidth)
- [shadowRoot](akashaproject_design_system._internal_.HTMLTimeElement.md#shadowroot)
- [slot](akashaproject_design_system._internal_.HTMLTimeElement.md#slot)
- [spellcheck](akashaproject_design_system._internal_.HTMLTimeElement.md#spellcheck)
- [style](akashaproject_design_system._internal_.HTMLTimeElement.md#style)
- [tabIndex](akashaproject_design_system._internal_.HTMLTimeElement.md#tabindex)
- [tagName](akashaproject_design_system._internal_.HTMLTimeElement.md#tagname)
- [textContent](akashaproject_design_system._internal_.HTMLTimeElement.md#textcontent)
- [title](akashaproject_design_system._internal_.HTMLTimeElement.md#title)
- [translate](akashaproject_design_system._internal_.HTMLTimeElement.md#translate)

### Methods

- [addEventListener](akashaproject_design_system._internal_.HTMLTimeElement.md#addeventlistener)
- [after](akashaproject_design_system._internal_.HTMLTimeElement.md#after)
- [animate](akashaproject_design_system._internal_.HTMLTimeElement.md#animate)
- [append](akashaproject_design_system._internal_.HTMLTimeElement.md#append)
- [appendChild](akashaproject_design_system._internal_.HTMLTimeElement.md#appendchild)
- [attachShadow](akashaproject_design_system._internal_.HTMLTimeElement.md#attachshadow)
- [before](akashaproject_design_system._internal_.HTMLTimeElement.md#before)
- [blur](akashaproject_design_system._internal_.HTMLTimeElement.md#blur)
- [click](akashaproject_design_system._internal_.HTMLTimeElement.md#click)
- [cloneNode](akashaproject_design_system._internal_.HTMLTimeElement.md#clonenode)
- [closest](akashaproject_design_system._internal_.HTMLTimeElement.md#closest)
- [compareDocumentPosition](akashaproject_design_system._internal_.HTMLTimeElement.md#comparedocumentposition)
- [contains](akashaproject_design_system._internal_.HTMLTimeElement.md#contains)
- [dispatchEvent](akashaproject_design_system._internal_.HTMLTimeElement.md#dispatchevent)
- [focus](akashaproject_design_system._internal_.HTMLTimeElement.md#focus)
- [getAnimations](akashaproject_design_system._internal_.HTMLTimeElement.md#getanimations)
- [getAttribute](akashaproject_design_system._internal_.HTMLTimeElement.md#getattribute)
- [getAttributeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#getattributens)
- [getAttributeNames](akashaproject_design_system._internal_.HTMLTimeElement.md#getattributenames)
- [getAttributeNode](akashaproject_design_system._internal_.HTMLTimeElement.md#getattributenode)
- [getAttributeNodeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#getattributenodens)
- [getBoundingClientRect](akashaproject_design_system._internal_.HTMLTimeElement.md#getboundingclientrect)
- [getClientRects](akashaproject_design_system._internal_.HTMLTimeElement.md#getclientrects)
- [getElementsByClassName](akashaproject_design_system._internal_.HTMLTimeElement.md#getelementsbyclassname)
- [getElementsByTagName](akashaproject_design_system._internal_.HTMLTimeElement.md#getelementsbytagname)
- [getElementsByTagNameNS](akashaproject_design_system._internal_.HTMLTimeElement.md#getelementsbytagnamens)
- [getRootNode](akashaproject_design_system._internal_.HTMLTimeElement.md#getrootnode)
- [hasAttribute](akashaproject_design_system._internal_.HTMLTimeElement.md#hasattribute)
- [hasAttributeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#hasattributens)
- [hasAttributes](akashaproject_design_system._internal_.HTMLTimeElement.md#hasattributes)
- [hasChildNodes](akashaproject_design_system._internal_.HTMLTimeElement.md#haschildnodes)
- [hasPointerCapture](akashaproject_design_system._internal_.HTMLTimeElement.md#haspointercapture)
- [insertAdjacentElement](akashaproject_design_system._internal_.HTMLTimeElement.md#insertadjacentelement)
- [insertAdjacentHTML](akashaproject_design_system._internal_.HTMLTimeElement.md#insertadjacenthtml)
- [insertAdjacentText](akashaproject_design_system._internal_.HTMLTimeElement.md#insertadjacenttext)
- [insertBefore](akashaproject_design_system._internal_.HTMLTimeElement.md#insertbefore)
- [isDefaultNamespace](akashaproject_design_system._internal_.HTMLTimeElement.md#isdefaultnamespace)
- [isEqualNode](akashaproject_design_system._internal_.HTMLTimeElement.md#isequalnode)
- [isSameNode](akashaproject_design_system._internal_.HTMLTimeElement.md#issamenode)
- [lookupNamespaceURI](akashaproject_design_system._internal_.HTMLTimeElement.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_design_system._internal_.HTMLTimeElement.md#lookupprefix)
- [matches](akashaproject_design_system._internal_.HTMLTimeElement.md#matches)
- [normalize](akashaproject_design_system._internal_.HTMLTimeElement.md#normalize)
- [prepend](akashaproject_design_system._internal_.HTMLTimeElement.md#prepend)
- [querySelector](akashaproject_design_system._internal_.HTMLTimeElement.md#queryselector)
- [querySelectorAll](akashaproject_design_system._internal_.HTMLTimeElement.md#queryselectorall)
- [releasePointerCapture](akashaproject_design_system._internal_.HTMLTimeElement.md#releasepointercapture)
- [remove](akashaproject_design_system._internal_.HTMLTimeElement.md#remove)
- [removeAttribute](akashaproject_design_system._internal_.HTMLTimeElement.md#removeattribute)
- [removeAttributeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#removeattributens)
- [removeAttributeNode](akashaproject_design_system._internal_.HTMLTimeElement.md#removeattributenode)
- [removeChild](akashaproject_design_system._internal_.HTMLTimeElement.md#removechild)
- [removeEventListener](akashaproject_design_system._internal_.HTMLTimeElement.md#removeeventlistener)
- [replaceChild](akashaproject_design_system._internal_.HTMLTimeElement.md#replacechild)
- [replaceChildren](akashaproject_design_system._internal_.HTMLTimeElement.md#replacechildren)
- [replaceWith](akashaproject_design_system._internal_.HTMLTimeElement.md#replacewith)
- [requestFullscreen](akashaproject_design_system._internal_.HTMLTimeElement.md#requestfullscreen)
- [requestPointerLock](akashaproject_design_system._internal_.HTMLTimeElement.md#requestpointerlock)
- [scroll](akashaproject_design_system._internal_.HTMLTimeElement.md#scroll)
- [scrollBy](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollby)
- [scrollIntoView](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollintoview)
- [scrollTo](akashaproject_design_system._internal_.HTMLTimeElement.md#scrollto)
- [setAttribute](akashaproject_design_system._internal_.HTMLTimeElement.md#setattribute)
- [setAttributeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#setattributens)
- [setAttributeNode](akashaproject_design_system._internal_.HTMLTimeElement.md#setattributenode)
- [setAttributeNodeNS](akashaproject_design_system._internal_.HTMLTimeElement.md#setattributenodens)
- [setPointerCapture](akashaproject_design_system._internal_.HTMLTimeElement.md#setpointercapture)
- [toggleAttribute](akashaproject_design_system._internal_.HTMLTimeElement.md#toggleattribute)
- [webkitMatchesSelector](akashaproject_design_system._internal_.HTMLTimeElement.md#webkitmatchesselector)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Inherited from

HTMLElement.ATTRIBUTE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Inherited from

HTMLElement.CDATA\_SECTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Inherited from

HTMLElement.COMMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Inherited from

HTMLElement.DOCUMENT\_FRAGMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Inherited from

HTMLElement.DOCUMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_CONTAINED\_BY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_CONTAINS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_DISCONNECTED

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_FOLLOWING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Inherited from

HTMLElement.DOCUMENT\_POSITION\_PRECEDING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Inherited from

HTMLElement.DOCUMENT\_TYPE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Inherited from

HTMLElement.ELEMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Inherited from

HTMLElement.ENTITY\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Inherited from

HTMLElement.ENTITY\_REFERENCE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Inherited from

HTMLElement.NOTATION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Inherited from

HTMLElement.PROCESSING\_INSTRUCTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Inherited from

HTMLElement.TEXT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### accessKey

• **accessKey**: `string`

#### Inherited from

HTMLElement.accessKey

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6414

___

### accessKeyLabel

• `Readonly` **accessKeyLabel**: `string`

#### Inherited from

HTMLElement.accessKeyLabel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6415

___

### ariaAtomic

• **ariaAtomic**: `string`

#### Inherited from

HTMLElement.ariaAtomic

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1860

___

### ariaAutoComplete

• **ariaAutoComplete**: `string`

#### Inherited from

HTMLElement.ariaAutoComplete

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1861

___

### ariaBusy

• **ariaBusy**: `string`

#### Inherited from

HTMLElement.ariaBusy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1862

___

### ariaChecked

• **ariaChecked**: `string`

#### Inherited from

HTMLElement.ariaChecked

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1863

___

### ariaColCount

• **ariaColCount**: `string`

#### Inherited from

HTMLElement.ariaColCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1864

___

### ariaColIndex

• **ariaColIndex**: `string`

#### Inherited from

HTMLElement.ariaColIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1865

___

### ariaColSpan

• **ariaColSpan**: `string`

#### Inherited from

HTMLElement.ariaColSpan

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1866

___

### ariaCurrent

• **ariaCurrent**: `string`

#### Inherited from

HTMLElement.ariaCurrent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1867

___

### ariaDisabled

• **ariaDisabled**: `string`

#### Inherited from

HTMLElement.ariaDisabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1868

___

### ariaExpanded

• **ariaExpanded**: `string`

#### Inherited from

HTMLElement.ariaExpanded

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1869

___

### ariaHasPopup

• **ariaHasPopup**: `string`

#### Inherited from

HTMLElement.ariaHasPopup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1870

___

### ariaHidden

• **ariaHidden**: `string`

#### Inherited from

HTMLElement.ariaHidden

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1871

___

### ariaKeyShortcuts

• **ariaKeyShortcuts**: `string`

#### Inherited from

HTMLElement.ariaKeyShortcuts

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1872

___

### ariaLabel

• **ariaLabel**: `string`

#### Inherited from

HTMLElement.ariaLabel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1873

___

### ariaLevel

• **ariaLevel**: `string`

#### Inherited from

HTMLElement.ariaLevel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1874

___

### ariaLive

• **ariaLive**: `string`

#### Inherited from

HTMLElement.ariaLive

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1875

___

### ariaModal

• **ariaModal**: `string`

#### Inherited from

HTMLElement.ariaModal

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1876

___

### ariaMultiLine

• **ariaMultiLine**: `string`

#### Inherited from

HTMLElement.ariaMultiLine

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1877

___

### ariaMultiSelectable

• **ariaMultiSelectable**: `string`

#### Inherited from

HTMLElement.ariaMultiSelectable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1878

___

### ariaOrientation

• **ariaOrientation**: `string`

#### Inherited from

HTMLElement.ariaOrientation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1879

___

### ariaPlaceholder

• **ariaPlaceholder**: `string`

#### Inherited from

HTMLElement.ariaPlaceholder

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1880

___

### ariaPosInSet

• **ariaPosInSet**: `string`

#### Inherited from

HTMLElement.ariaPosInSet

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1881

___

### ariaPressed

• **ariaPressed**: `string`

#### Inherited from

HTMLElement.ariaPressed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1882

___

### ariaReadOnly

• **ariaReadOnly**: `string`

#### Inherited from

HTMLElement.ariaReadOnly

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1883

___

### ariaRequired

• **ariaRequired**: `string`

#### Inherited from

HTMLElement.ariaRequired

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1884

___

### ariaRoleDescription

• **ariaRoleDescription**: `string`

#### Inherited from

HTMLElement.ariaRoleDescription

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1885

___

### ariaRowCount

• **ariaRowCount**: `string`

#### Inherited from

HTMLElement.ariaRowCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1886

___

### ariaRowIndex

• **ariaRowIndex**: `string`

#### Inherited from

HTMLElement.ariaRowIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1887

___

### ariaRowSpan

• **ariaRowSpan**: `string`

#### Inherited from

HTMLElement.ariaRowSpan

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1888

___

### ariaSelected

• **ariaSelected**: `string`

#### Inherited from

HTMLElement.ariaSelected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1889

___

### ariaSetSize

• **ariaSetSize**: `string`

#### Inherited from

HTMLElement.ariaSetSize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1890

___

### ariaSort

• **ariaSort**: `string`

#### Inherited from

HTMLElement.ariaSort

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1891

___

### ariaValueMax

• **ariaValueMax**: `string`

#### Inherited from

HTMLElement.ariaValueMax

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1892

___

### ariaValueMin

• **ariaValueMin**: `string`

#### Inherited from

HTMLElement.ariaValueMin

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1893

___

### ariaValueNow

• **ariaValueNow**: `string`

#### Inherited from

HTMLElement.ariaValueNow

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1894

___

### ariaValueText

• **ariaValueText**: `string`

#### Inherited from

HTMLElement.ariaValueText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1895

___

### assignedSlot

• `Readonly` **assignedSlot**: `HTMLSlotElement`

#### Inherited from

HTMLElement.assignedSlot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14105

___

### attributes

• `Readonly` **attributes**: [`NamedNodeMap`](../modules/akashaproject_design_system._internal_.md#namednodemap)

#### Inherited from

HTMLElement.attributes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4873

___

### autocapitalize

• **autocapitalize**: `string`

#### Inherited from

HTMLElement.autocapitalize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6416

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Inherited from

HTMLElement.baseURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### childElementCount

• `Readonly` **childElementCount**: `number`

#### Inherited from

HTMLElement.childElementCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10958

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_design_system._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)\>

Returns the children.

#### Inherited from

HTMLElement.childNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### children

• `Readonly` **children**: [`HTMLCollection`](../modules/akashaproject_design_system._internal_.md#htmlcollection)

Returns the child elements.

#### Inherited from

HTMLElement.children

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10962

___

### classList

• `Readonly` **classList**: [`DOMTokenList`](../modules/akashaproject_design_system._internal_.md#domtokenlist)

Allows for manipulation of element's class content attribute as a set of whitespace-separated tokens through a DOMTokenList object.

#### Inherited from

HTMLElement.classList

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4877

___

### className

• **className**: `string`

Returns the value of element's class content attribute. Can be set to change it.

#### Inherited from

HTMLElement.className

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4881

___

### clientHeight

• `Readonly` **clientHeight**: `number`

#### Inherited from

HTMLElement.clientHeight

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4882

___

### clientLeft

• `Readonly` **clientLeft**: `number`

#### Inherited from

HTMLElement.clientLeft

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4883

___

### clientTop

• `Readonly` **clientTop**: `number`

#### Inherited from

HTMLElement.clientTop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4884

___

### clientWidth

• `Readonly` **clientWidth**: `number`

#### Inherited from

HTMLElement.clientWidth

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4885

___

### contentEditable

• **contentEditable**: `string`

#### Inherited from

HTMLElement.contentEditable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5038

___

### dataset

• `Readonly` **dataset**: [`DOMStringMap`](../modules/akashaproject_design_system._internal_.md#domstringmap)

#### Inherited from

HTMLElement.dataset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7897

___

### dateTime

• **dateTime**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8756

___

### dir

• **dir**: `string`

#### Inherited from

HTMLElement.dir

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6417

___

### draggable

• **draggable**: `boolean`

#### Inherited from

HTMLElement.draggable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6418

___

### enterKeyHint

• **enterKeyHint**: `string`

#### Inherited from

HTMLElement.enterKeyHint

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5039

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the first child.

#### Inherited from

HTMLElement.firstChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### firstElementChild

• `Readonly` **firstElementChild**: `Element`

Returns the first child that is an element, and null otherwise.

#### Inherited from

HTMLElement.firstElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10966

___

### hidden

• **hidden**: `boolean`

#### Inherited from

HTMLElement.hidden

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6419

___

### id

• **id**: `string`

Returns the value of element's id content attribute. Can be set to change it.

#### Inherited from

HTMLElement.id

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4889

___

### innerHTML

• **innerHTML**: `string`

#### Inherited from

HTMLElement.innerHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9506

___

### innerText

• **innerText**: `string`

#### Inherited from

HTMLElement.innerText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6420

___

### inputMode

• **inputMode**: `string`

#### Inherited from

HTMLElement.inputMode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5040

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Inherited from

HTMLElement.isConnected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### isContentEditable

• `Readonly` **isContentEditable**: `boolean`

#### Inherited from

HTMLElement.isContentEditable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5041

___

### lang

• **lang**: `string`

#### Inherited from

HTMLElement.lang

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6421

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the last child.

#### Inherited from

HTMLElement.lastChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### lastElementChild

• `Readonly` **lastElementChild**: `Element`

Returns the last child that is an element, and null otherwise.

#### Inherited from

HTMLElement.lastElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10970

___

### localName

• `Readonly` **localName**: `string`

Returns the local name.

#### Inherited from

HTMLElement.localName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4893

___

### namespaceURI

• `Readonly` **namespaceURI**: `string`

Returns the namespace.

#### Inherited from

HTMLElement.namespaceURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4897

___

### nextElementSibling

• `Readonly` **nextElementSibling**: `Element`

Returns the first following sibling that is an element, and null otherwise.

#### Inherited from

HTMLElement.nextElementSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10756

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the next sibling.

#### Inherited from

HTMLElement.nextSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Inherited from

HTMLElement.nodeName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Inherited from

HTMLElement.nodeType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Inherited from

HTMLElement.nodeValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### nonce

• `Optional` **nonce**: `string`

#### Inherited from

HTMLElement.nonce

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7898

___

### offsetHeight

• `Readonly` **offsetHeight**: `number`

#### Inherited from

HTMLElement.offsetHeight

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6422

___

### offsetLeft

• `Readonly` **offsetLeft**: `number`

#### Inherited from

HTMLElement.offsetLeft

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6423

___

### offsetParent

• `Readonly` **offsetParent**: `Element`

#### Inherited from

HTMLElement.offsetParent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6424

___

### offsetTop

• `Readonly` **offsetTop**: `number`

#### Inherited from

HTMLElement.offsetTop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6425

___

### offsetWidth

• `Readonly` **offsetWidth**: `number`

#### Inherited from

HTMLElement.offsetWidth

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6426

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

HTMLElement.onabort

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

HTMLElement.onanimationcancel

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

HTMLElement.onanimationend

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

HTMLElement.onanimationiteration

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

HTMLElement.onanimationstart

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

HTMLElement.onauxclick

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

HTMLElement.onblur

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

HTMLElement.oncanplay

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

HTMLElement.oncanplaythrough

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

HTMLElement.onchange

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

HTMLElement.onclick

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

HTMLElement.onclose

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

HTMLElement.oncontextmenu

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

HTMLElement.oncopy

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

HTMLElement.oncuechange

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

HTMLElement.oncut

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

HTMLElement.ondblclick

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

HTMLElement.ondrag

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

HTMLElement.ondragend

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

HTMLElement.ondragenter

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

HTMLElement.ondragleave

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

HTMLElement.ondragover

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

HTMLElement.ondragstart

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

HTMLElement.ondrop

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

HTMLElement.ondurationchange

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

HTMLElement.onemptied

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

HTMLElement.onended

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5761

___

### onerror

• **onerror**: [`OnErrorEventHandlerNonNull`](akashaproject_design_system._internal_.OnErrorEventHandlerNonNull.md)

Fires when an error occurs during object loading.

**`param`** The event.

#### Inherited from

HTMLElement.onerror

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

HTMLElement.onfocus

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

HTMLElement.onformdata

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

HTMLElement.onfullscreenchange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4898

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

HTMLElement.onfullscreenerror

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4899

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

HTMLElement.ongotpointercapture

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

HTMLElement.oninput

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

HTMLElement.oninvalid

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

HTMLElement.onkeydown

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

HTMLElement.onkeypress

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

HTMLElement.onkeyup

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

HTMLElement.onload

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

HTMLElement.onloadeddata

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

HTMLElement.onloadedmetadata

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

HTMLElement.onloadstart

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

HTMLElement.onlostpointercapture

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

HTMLElement.onmousedown

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

HTMLElement.onmouseenter

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

HTMLElement.onmouseleave

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

HTMLElement.onmousemove

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

HTMLElement.onmouseout

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

HTMLElement.onmouseover

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

HTMLElement.onmouseup

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

HTMLElement.onpaste

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

HTMLElement.onpause

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

HTMLElement.onplay

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

HTMLElement.onplaying

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

HTMLElement.onpointercancel

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

HTMLElement.onpointerdown

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

HTMLElement.onpointerenter

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

HTMLElement.onpointerleave

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5858

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

HTMLElement.onpointermove

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

HTMLElement.onpointerout

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

HTMLElement.onpointerover

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

HTMLElement.onpointerup

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

HTMLElement.onprogress

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

HTMLElement.onratechange

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5872

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

HTMLElement.onreset

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

HTMLElement.onresize

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

HTMLElement.onscroll

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

HTMLElement.onseeked

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

HTMLElement.onseeking

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

HTMLElement.onselect

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

HTMLElement.onselectionchange

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

HTMLElement.onselectstart

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

HTMLElement.onstalled

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

HTMLElement.onsubmit

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

HTMLElement.onsuspend

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

HTMLElement.ontimeupdate

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

HTMLElement.ontoggle

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

HTMLElement.ontouchcancel

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

HTMLElement.ontouchend

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

HTMLElement.ontouchmove

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

HTMLElement.ontouchstart

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

HTMLElement.ontransitioncancel

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

HTMLElement.ontransitionend

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

HTMLElement.ontransitionrun

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

HTMLElement.ontransitionstart

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5925

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

HTMLElement.onvolumechange

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

HTMLElement.onwaiting

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

HTMLElement.onwebkitanimationend

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

HTMLElement.onwebkitanimationiteration

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

HTMLElement.onwebkitanimationstart

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

HTMLElement.onwebkittransitionend

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

HTMLElement.onwheel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5940

___

### outerHTML

• **outerHTML**: `string`

#### Inherited from

HTMLElement.outerHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4900

___

### outerText

• **outerText**: `string`

#### Inherited from

HTMLElement.outerText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6427

___

### ownerDocument

• `Readonly` **ownerDocument**: `Document`

#### Inherited from

HTMLElement.ownerDocument

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4901

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Inherited from

HTMLElement.parentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_design_system._internal_.ParentNode.md)

Returns the parent.

#### Inherited from

HTMLElement.parentNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### part

• `Readonly` **part**: [`DOMTokenList`](../modules/akashaproject_design_system._internal_.md#domtokenlist)

#### Inherited from

HTMLElement.part

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4902

___

### prefix

• `Readonly` **prefix**: `string`

Returns the namespace prefix.

#### Inherited from

HTMLElement.prefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4906

___

### previousElementSibling

• `Readonly` **previousElementSibling**: `Element`

Returns the first preceding sibling that is an element, and null otherwise.

#### Inherited from

HTMLElement.previousElementSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10760

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_design_system._internal_.ChildNode.md)

Returns the previous sibling.

#### Inherited from

HTMLElement.previousSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### scrollHeight

• `Readonly` **scrollHeight**: `number`

#### Inherited from

HTMLElement.scrollHeight

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4907

___

### scrollLeft

• **scrollLeft**: `number`

#### Inherited from

HTMLElement.scrollLeft

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4908

___

### scrollTop

• **scrollTop**: `number`

#### Inherited from

HTMLElement.scrollTop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4909

___

### scrollWidth

• `Readonly` **scrollWidth**: `number`

#### Inherited from

HTMLElement.scrollWidth

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4910

___

### shadowRoot

• `Readonly` **shadowRoot**: [`ShadowRoot`](../modules/akashaproject_design_system._internal_.md#shadowroot)

Returns element's shadow root, if any, and if shadow root's mode is "open", and null otherwise.

#### Inherited from

HTMLElement.shadowRoot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4914

___

### slot

• **slot**: `string`

Returns the value of element's slot content attribute. Can be set to change it.

#### Inherited from

HTMLElement.slot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4918

___

### spellcheck

• **spellcheck**: `boolean`

#### Inherited from

HTMLElement.spellcheck

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6428

___

### style

• `Readonly` **style**: [`CSSStyleDeclaration`](../modules/akashaproject_design_system._internal_.md#cssstyledeclaration)

#### Inherited from

HTMLElement.style

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5034

___

### tabIndex

• **tabIndex**: `number`

#### Inherited from

HTMLElement.tabIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7899

___

### tagName

• `Readonly` **tagName**: `string`

Returns the HTML-uppercased qualified name.

#### Inherited from

HTMLElement.tagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4922

___

### textContent

• **textContent**: `string`

#### Inherited from

HTMLElement.textContent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10541

___

### title

• **title**: `string`

#### Inherited from

HTMLElement.title

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6429

___

### translate

• **translate**: `boolean`

#### Inherited from

HTMLElement.translate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6430

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementEventMap`](akashaproject_design_system._internal_.HTMLElementEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`HTMLElementEventMap`](akashaproject_design_system._internal_.HTMLElementEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

HTMLElement.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8757

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

HTMLElement.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8758

___

### after

▸ **after**(...`nodes`): `void`

Inserts nodes just after node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

HTMLElement.after

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3491

___

### animate

▸ **animate**(`keyframes`, `options?`): [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyframes` | [`Keyframe`](akashaproject_design_system._internal_.Keyframe.md)[] \| [`PropertyIndexedKeyframes`](akashaproject_design_system._internal_.PropertyIndexedKeyframes.md) |
| `options?` | `number` \| [`KeyframeAnimationOptions`](akashaproject_design_system._internal_.KeyframeAnimationOptions.md) |

#### Returns

[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)

#### Inherited from

HTMLElement.animate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1996

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

HTMLElement.append

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

HTMLElement.appendChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10542

___

### attachShadow

▸ **attachShadow**(`init`): [`ShadowRoot`](../modules/akashaproject_design_system._internal_.md#shadowroot)

Creates a shadow root for element and returns it.

#### Parameters

| Name | Type |
| :------ | :------ |
| `init` | [`ShadowRootInit`](akashaproject_design_system._internal_.ShadowRootInit.md) |

#### Returns

[`ShadowRoot`](../modules/akashaproject_design_system._internal_.md#shadowroot)

#### Inherited from

HTMLElement.attachShadow

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4926

___

### before

▸ **before**(...`nodes`): `void`

Inserts nodes just before node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

HTMLElement.before

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3497

___

### blur

▸ **blur**(): `void`

#### Returns

`void`

#### Inherited from

HTMLElement.blur

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7900

___

### click

▸ **click**(): `void`

#### Returns

`void`

#### Inherited from

HTMLElement.click

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:6431

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

HTMLElement.cloneNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10546

___

### closest

▸ **closest**<`K`\>(`selector`): [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

Returns the first (starting at element) inclusive ancestor that matches selectors, and null otherwise.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector` | `K` |

#### Returns

[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]

#### Inherited from

HTMLElement.closest

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4930

▸ **closest**<`K`\>(`selector`): [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector` | `K` |

#### Returns

[`SVGElementTagNameMap`](akashaproject_design_system._internal_.SVGElementTagNameMap.md)[`K`]

#### Inherited from

HTMLElement.closest

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4931

▸ **closest**<`E`\>(`selectors`): `E`

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

HTMLElement.closest

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4932

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

HTMLElement.compareDocumentPosition

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

HTMLElement.contains

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

HTMLElement.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### focus

▸ **focus**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FocusOptions`](akashaproject_design_system._internal_.FocusOptions.md) |

#### Returns

`void`

#### Inherited from

HTMLElement.focus

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7901

___

### getAnimations

▸ **getAnimations**(`options?`): [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`GetAnimationsOptions`](akashaproject_design_system._internal_.GetAnimationsOptions.md) |

#### Returns

[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Inherited from

HTMLElement.getAnimations

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1997

___

### getAttribute

▸ **getAttribute**(`qualifiedName`): `string`

Returns element's first attribute whose qualified name is qualifiedName, and null if there is no such attribute otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

`string`

#### Inherited from

HTMLElement.getAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4936

___

### getAttributeNS

▸ **getAttributeNS**(`namespace`, `localName`): `string`

Returns element's attribute whose namespace is namespace and local name is localName, and null if there is no such attribute otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

`string`

#### Inherited from

HTMLElement.getAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4940

___

### getAttributeNames

▸ **getAttributeNames**(): `string`[]

Returns the qualified names of all element's attributes. Can contain duplicates.

#### Returns

`string`[]

#### Inherited from

HTMLElement.getAttributeNames

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4944

___

### getAttributeNode

▸ **getAttributeNode**(`qualifiedName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

HTMLElement.getAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4945

___

### getAttributeNodeNS

▸ **getAttributeNodeNS**(`namespace`, `localName`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

HTMLElement.getAttributeNodeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4946

___

### getBoundingClientRect

▸ **getBoundingClientRect**(): [`DOMRect`](../modules/akashaproject_design_system._internal_.md#domrect)

#### Returns

[`DOMRect`](../modules/akashaproject_design_system._internal_.md#domrect)

#### Inherited from

HTMLElement.getBoundingClientRect

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4947

___

### getClientRects

▸ **getClientRects**(): [`DOMRectList`](../modules/akashaproject_design_system._internal_.md#domrectlist)

#### Returns

[`DOMRectList`](../modules/akashaproject_design_system._internal_.md#domrectlist)

#### Inherited from

HTMLElement.getClientRects

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4948

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

HTMLElement.getElementsByClassName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4952

___

### getElementsByTagName

▸ **getElementsByTagName**<`K`\>(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<[`HTMLElementTagNameMap`](akashaproject_design_system._internal_.HTMLElementTagNameMap.md)[`K`]\>

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

HTMLElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4953

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

HTMLElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4954

▸ **getElementsByTagName**(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

HTMLElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4955

___

### getElementsByTagNameNS

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/1999/xhtml"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

#### Inherited from

HTMLElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4956

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/2000/svg"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Inherited from

HTMLElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4957

▸ **getElementsByTagNameNS**(`namespace`, `localName`): [`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_design_system._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

HTMLElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4958

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

HTMLElement.getRootNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### hasAttribute

▸ **hasAttribute**(`qualifiedName`): `boolean`

Returns true if element has an attribute whose qualified name is qualifiedName, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.hasAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4962

___

### hasAttributeNS

▸ **hasAttributeNS**(`namespace`, `localName`): `boolean`

Returns true if element has an attribute whose namespace is namespace and local name is localName.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.hasAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4966

___

### hasAttributes

▸ **hasAttributes**(): `boolean`

Returns true if element has attributes, and false otherwise.

#### Returns

`boolean`

#### Inherited from

HTMLElement.hasAttributes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4970

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Inherited from

HTMLElement.hasChildNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10562

___

### hasPointerCapture

▸ **hasPointerCapture**(`pointerId`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointerId` | `number` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.hasPointerCapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4971

___

### insertAdjacentElement

▸ **insertAdjacentElement**(`where`, `element`): `Element`

#### Parameters

| Name | Type |
| :------ | :------ |
| `where` | [`InsertPosition`](../modules/akashaproject_design_system._internal_.md#insertposition) |
| `element` | `Element` |

#### Returns

`Element`

#### Inherited from

HTMLElement.insertAdjacentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4972

___

### insertAdjacentHTML

▸ **insertAdjacentHTML**(`position`, `text`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | [`InsertPosition`](../modules/akashaproject_design_system._internal_.md#insertposition) |
| `text` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.insertAdjacentHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4973

___

### insertAdjacentText

▸ **insertAdjacentText**(`where`, `data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `where` | [`InsertPosition`](../modules/akashaproject_design_system._internal_.md#insertposition) |
| `data` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.insertAdjacentText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4974

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

HTMLElement.insertBefore

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

HTMLElement.isDefaultNamespace

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

HTMLElement.isEqualNode

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

HTMLElement.isSameNode

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

HTMLElement.lookupNamespaceURI

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

HTMLElement.lookupPrefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10571

___

### matches

▸ **matches**(`selectors`): `boolean`

Returns true if matching selectors against element's root yields element, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `string` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.matches

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4978

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Inherited from

HTMLElement.normalize

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
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

HTMLElement.prepend

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10982

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

HTMLElement.querySelector

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

HTMLElement.querySelector

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

HTMLElement.querySelector

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

HTMLElement.querySelectorAll

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

HTMLElement.querySelectorAll

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

HTMLElement.querySelectorAll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10994

___

### releasePointerCapture

▸ **releasePointerCapture**(`pointerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointerId` | `number` |

#### Returns

`void`

#### Inherited from

HTMLElement.releasePointerCapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4979

___

### remove

▸ **remove**(): `void`

Removes node.

#### Returns

`void`

#### Inherited from

HTMLElement.remove

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3501

___

### removeAttribute

▸ **removeAttribute**(`qualifiedName`): `void`

Removes element's first attribute whose qualified name is qualifiedName.

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.removeAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4983

___

### removeAttributeNS

▸ **removeAttributeNS**(`namespace`, `localName`): `void`

Removes element's attribute whose namespace is namespace and local name is localName.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.removeAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4987

___

### removeAttributeNode

▸ **removeAttributeNode**(`attr`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_design_system._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

HTMLElement.removeAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4988

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

HTMLElement.removeChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10576

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementEventMap`](akashaproject_design_system._internal_.HTMLElementEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`HTMLElementEventMap`](akashaproject_design_system._internal_.HTMLElementEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

HTMLElement.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8759

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

HTMLElement.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8760

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

HTMLElement.replaceChild

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

HTMLElement.replaceChildren

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11000

___

### replaceWith

▸ **replaceWith**(...`nodes`): `void`

Replaces node with nodes, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_design_system._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

HTMLElement.replaceWith

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3507

___

### requestFullscreen

▸ **requestFullscreen**(`options?`): `Promise`<`void`\>

Displays element fullscreen and resolves promise when done.

When supplied, options's navigationUI member indicates whether showing navigation UI while in fullscreen is preferred or not. If set to "show", navigation simplicity is preferred over screen space, and if set to "hide", more screen space is preferred. User agents are always free to honor user preference over the application's. The default value "auto" indicates no application preference.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FullscreenOptions`](akashaproject_design_system._internal_.FullscreenOptions.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

HTMLElement.requestFullscreen

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4994

___

### requestPointerLock

▸ **requestPointerLock**(): `void`

#### Returns

`void`

#### Inherited from

HTMLElement.requestPointerLock

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4995

___

### scroll

▸ **scroll**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_design_system._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

HTMLElement.scroll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4996

▸ **scroll**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Inherited from

HTMLElement.scroll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4997

___

### scrollBy

▸ **scrollBy**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_design_system._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

HTMLElement.scrollBy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4998

▸ **scrollBy**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Inherited from

HTMLElement.scrollBy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4999

___

### scrollIntoView

▸ **scrollIntoView**(`arg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg?` | `boolean` \| [`ScrollIntoViewOptions`](akashaproject_design_system._internal_.ScrollIntoViewOptions.md) |

#### Returns

`void`

#### Inherited from

HTMLElement.scrollIntoView

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5000

___

### scrollTo

▸ **scrollTo**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_design_system._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

HTMLElement.scrollTo

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5001

▸ **scrollTo**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Inherited from

HTMLElement.scrollTo

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5002

___

### setAttribute

▸ **setAttribute**(`qualifiedName`, `value`): `void`

Sets the value of element's first attribute whose qualified name is qualifiedName to value.

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |
| `value` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.setAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5006

___

### setAttributeNS

▸ **setAttributeNS**(`namespace`, `qualifiedName`, `value`): `void`

Sets the value of element's attribute whose namespace is namespace and local name is localName to value.

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `qualifiedName` | `string` |
| `value` | `string` |

#### Returns

`void`

#### Inherited from

HTMLElement.setAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5010

___

### setAttributeNode

▸ **setAttributeNode**(`attr`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_design_system._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

HTMLElement.setAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5011

___

### setAttributeNodeNS

▸ **setAttributeNodeNS**(`attr`): [`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_design_system._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_design_system._internal_.md#attr)

#### Inherited from

HTMLElement.setAttributeNodeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5012

___

### setPointerCapture

▸ **setPointerCapture**(`pointerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointerId` | `number` |

#### Returns

`void`

#### Inherited from

HTMLElement.setPointerCapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5013

___

### toggleAttribute

▸ **toggleAttribute**(`qualifiedName`, `force?`): `boolean`

If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName. If force is false, removes qualifiedName.

Returns true if qualifiedName is now present, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |
| `force?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.toggleAttribute

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5019

___

### webkitMatchesSelector

▸ **webkitMatchesSelector**(`selectors`): `boolean`

**`deprecated`** This is a legacy alias of `matches`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `selectors` | `string` |

#### Returns

`boolean`

#### Inherited from

HTMLElement.webkitMatchesSelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5021
