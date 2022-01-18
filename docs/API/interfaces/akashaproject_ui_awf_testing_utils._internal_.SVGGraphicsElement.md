[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SVGGraphicsElement

# Interface: SVGGraphicsElement

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SVGGraphicsElement

SVG elements whose primary purpose is to directly render graphics into a group.

## Hierarchy

- `SVGElement`

- [`SVGTests`](akashaproject_ui_awf_testing_utils._internal_.SVGTests.md)

  ↳ **`SVGGraphicsElement`**

## Table of contents

### Properties

- [ATTRIBUTE\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#attribute_node)
- [CDATA\_SECTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#cdata_section_node)
- [COMMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#comment_node)
- [DOCUMENT\_FRAGMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_fragment_node)
- [DOCUMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_node)
- [DOCUMENT\_POSITION\_CONTAINED\_BY](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_contained_by)
- [DOCUMENT\_POSITION\_CONTAINS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_contains)
- [DOCUMENT\_POSITION\_DISCONNECTED](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_disconnected)
- [DOCUMENT\_POSITION\_FOLLOWING](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_following)
- [DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_implementation_specific)
- [DOCUMENT\_POSITION\_PRECEDING](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_position_preceding)
- [DOCUMENT\_TYPE\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#document_type_node)
- [ELEMENT\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#element_node)
- [ENTITY\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#entity_node)
- [ENTITY\_REFERENCE\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#entity_reference_node)
- [NOTATION\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#notation_node)
- [PROCESSING\_INSTRUCTION\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#processing_instruction_node)
- [TEXT\_NODE](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#text_node)
- [ariaAtomic](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaatomic)
- [ariaAutoComplete](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaautocomplete)
- [ariaBusy](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariabusy)
- [ariaChecked](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariachecked)
- [ariaColCount](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariacolcount)
- [ariaColIndex](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariacolindex)
- [ariaColSpan](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariacolspan)
- [ariaCurrent](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariacurrent)
- [ariaDisabled](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariadisabled)
- [ariaExpanded](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaexpanded)
- [ariaHasPopup](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariahaspopup)
- [ariaHidden](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariahidden)
- [ariaKeyShortcuts](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariakeyshortcuts)
- [ariaLabel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#arialabel)
- [ariaLevel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#arialevel)
- [ariaLive](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#arialive)
- [ariaModal](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariamodal)
- [ariaMultiLine](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariamultiline)
- [ariaMultiSelectable](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariamultiselectable)
- [ariaOrientation](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaorientation)
- [ariaPlaceholder](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaplaceholder)
- [ariaPosInSet](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaposinset)
- [ariaPressed](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariapressed)
- [ariaReadOnly](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariareadonly)
- [ariaRequired](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariarequired)
- [ariaRoleDescription](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaroledescription)
- [ariaRowCount](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariarowcount)
- [ariaRowIndex](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariarowindex)
- [ariaRowSpan](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariarowspan)
- [ariaSelected](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariaselected)
- [ariaSetSize](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariasetsize)
- [ariaSort](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariasort)
- [ariaValueMax](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariavaluemax)
- [ariaValueMin](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariavaluemin)
- [ariaValueNow](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariavaluenow)
- [ariaValueText](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ariavaluetext)
- [assignedSlot](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#assignedslot)
- [attributes](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#attributes)
- [baseURI](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#baseuri)
- [childElementCount](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#childelementcount)
- [childNodes](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#childnodes)
- [children](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#children)
- [classList](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#classlist)
- [className](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#classname)
- [clientHeight](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#clientheight)
- [clientLeft](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#clientleft)
- [clientTop](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#clienttop)
- [clientWidth](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#clientwidth)
- [dataset](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#dataset)
- [firstChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#firstchild)
- [firstElementChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#firstelementchild)
- [id](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#id)
- [innerHTML](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#innerhtml)
- [isConnected](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#isconnected)
- [lastChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#lastchild)
- [lastElementChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#lastelementchild)
- [localName](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#localname)
- [namespaceURI](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#namespaceuri)
- [nextElementSibling](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nextelementsibling)
- [nextSibling](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nextsibling)
- [nodeName](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nodename)
- [nodeType](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nodetype)
- [nodeValue](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nodevalue)
- [nonce](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#nonce)
- [onabort](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onabort)
- [onanimationcancel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onanimationcancel)
- [onanimationend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onanimationend)
- [onanimationiteration](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onanimationiteration)
- [onanimationstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onanimationstart)
- [onauxclick](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onauxclick)
- [onblur](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onblur)
- [oncanplay](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncanplay)
- [oncanplaythrough](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncanplaythrough)
- [onchange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onchange)
- [onclick](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onclick)
- [onclose](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onclose)
- [oncontextmenu](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncontextmenu)
- [oncopy](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncopy)
- [oncuechange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncuechange)
- [oncut](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oncut)
- [ondblclick](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondblclick)
- [ondrag](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondrag)
- [ondragend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondragend)
- [ondragenter](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondragenter)
- [ondragleave](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondragleave)
- [ondragover](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondragover)
- [ondragstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondragstart)
- [ondrop](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondrop)
- [ondurationchange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ondurationchange)
- [onemptied](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onemptied)
- [onended](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onended)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onerror)
- [onfocus](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onfocus)
- [onformdata](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onformdata)
- [onfullscreenchange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onfullscreenchange)
- [onfullscreenerror](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onfullscreenerror)
- [ongotpointercapture](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ongotpointercapture)
- [oninput](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oninput)
- [oninvalid](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#oninvalid)
- [onkeydown](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onkeydown)
- [onkeypress](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onkeypress)
- [onkeyup](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onkeyup)
- [onload](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onload)
- [onloadeddata](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onloadeddata)
- [onloadedmetadata](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onloadedmetadata)
- [onloadstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onloadstart)
- [onlostpointercapture](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onlostpointercapture)
- [onmousedown](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmousedown)
- [onmouseenter](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmouseenter)
- [onmouseleave](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmouseleave)
- [onmousemove](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmousemove)
- [onmouseout](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmouseout)
- [onmouseover](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmouseover)
- [onmouseup](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onmouseup)
- [onpaste](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpaste)
- [onpause](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpause)
- [onplay](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onplay)
- [onplaying](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onplaying)
- [onpointercancel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointercancel)
- [onpointerdown](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerdown)
- [onpointerenter](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerenter)
- [onpointerleave](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerleave)
- [onpointermove](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointermove)
- [onpointerout](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerout)
- [onpointerover](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerover)
- [onpointerup](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onpointerup)
- [onprogress](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onprogress)
- [onratechange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onratechange)
- [onreset](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onreset)
- [onresize](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onresize)
- [onscroll](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onscroll)
- [onseeked](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onseeked)
- [onseeking](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onseeking)
- [onselect](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onselect)
- [onselectionchange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onselectionchange)
- [onselectstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onselectstart)
- [onstalled](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onstalled)
- [onsubmit](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onsubmit)
- [onsuspend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onsuspend)
- [ontimeupdate](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontimeupdate)
- [ontoggle](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontoggle)
- [ontouchcancel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontouchcancel)
- [ontouchend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontouchend)
- [ontouchmove](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontouchmove)
- [ontouchstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontouchstart)
- [ontransitioncancel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontransitioncancel)
- [ontransitionend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontransitionend)
- [ontransitionrun](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontransitionrun)
- [ontransitionstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ontransitionstart)
- [onvolumechange](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onvolumechange)
- [onwaiting](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwaiting)
- [onwebkitanimationend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwebkitanimationend)
- [onwebkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwebkitanimationiteration)
- [onwebkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwebkitanimationstart)
- [onwebkittransitionend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwebkittransitionend)
- [onwheel](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#onwheel)
- [outerHTML](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#outerhtml)
- [ownerDocument](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ownerdocument)
- [ownerSVGElement](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#ownersvgelement)
- [parentElement](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#parentelement)
- [parentNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#parentnode)
- [part](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#part)
- [prefix](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#prefix)
- [previousElementSibling](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#previouselementsibling)
- [previousSibling](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#previoussibling)
- [requiredExtensions](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#requiredextensions)
- [scrollHeight](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollheight)
- [scrollLeft](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollleft)
- [scrollTop](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrolltop)
- [scrollWidth](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollwidth)
- [shadowRoot](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#shadowroot)
- [slot](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#slot)
- [style](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#style)
- [systemLanguage](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#systemlanguage)
- [tabIndex](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#tabindex)
- [tagName](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#tagname)
- [textContent](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#textcontent)
- [transform](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#transform)
- [viewportElement](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#viewportelement)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#addeventlistener)
- [after](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#after)
- [animate](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#animate)
- [append](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#append)
- [appendChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#appendchild)
- [attachShadow](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#attachshadow)
- [before](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#before)
- [blur](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#blur)
- [cloneNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#clonenode)
- [closest](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#closest)
- [compareDocumentPosition](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#comparedocumentposition)
- [contains](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#contains)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#dispatchevent)
- [focus](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#focus)
- [getAnimations](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getanimations)
- [getAttribute](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getattribute)
- [getAttributeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getattributens)
- [getAttributeNames](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getattributenames)
- [getAttributeNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getattributenode)
- [getAttributeNodeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getattributenodens)
- [getBBox](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getbbox)
- [getBoundingClientRect](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getboundingclientrect)
- [getCTM](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getctm)
- [getClientRects](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getclientrects)
- [getElementsByClassName](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getelementsbyclassname)
- [getElementsByTagName](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getelementsbytagname)
- [getElementsByTagNameNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getelementsbytagnamens)
- [getRootNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getrootnode)
- [getScreenCTM](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#getscreenctm)
- [hasAttribute](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#hasattribute)
- [hasAttributeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#hasattributens)
- [hasAttributes](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#hasattributes)
- [hasChildNodes](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#haschildnodes)
- [hasPointerCapture](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#haspointercapture)
- [insertAdjacentElement](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#insertadjacentelement)
- [insertAdjacentHTML](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#insertadjacenthtml)
- [insertAdjacentText](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#insertadjacenttext)
- [insertBefore](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#insertbefore)
- [isDefaultNamespace](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#isdefaultnamespace)
- [isEqualNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#isequalnode)
- [isSameNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#issamenode)
- [lookupNamespaceURI](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#lookupnamespaceuri)
- [lookupPrefix](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#lookupprefix)
- [matches](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#matches)
- [normalize](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#normalize)
- [prepend](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#prepend)
- [querySelector](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#queryselector)
- [querySelectorAll](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#queryselectorall)
- [releasePointerCapture](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#releasepointercapture)
- [remove](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#remove)
- [removeAttribute](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#removeattribute)
- [removeAttributeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#removeattributens)
- [removeAttributeNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#removeattributenode)
- [removeChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#removechild)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#removeeventlistener)
- [replaceChild](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#replacechild)
- [replaceChildren](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#replacechildren)
- [replaceWith](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#replacewith)
- [requestFullscreen](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#requestfullscreen)
- [requestPointerLock](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#requestpointerlock)
- [scroll](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scroll)
- [scrollBy](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollby)
- [scrollIntoView](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollintoview)
- [scrollTo](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#scrollto)
- [setAttribute](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#setattribute)
- [setAttributeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#setattributens)
- [setAttributeNode](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#setattributenode)
- [setAttributeNodeNS](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#setattributenodens)
- [setPointerCapture](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#setpointercapture)
- [toggleAttribute](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#toggleattribute)
- [webkitMatchesSelector](akashaproject_ui_awf_testing_utils._internal_.SVGGraphicsElement.md#webkitmatchesselector)

## Properties

### ATTRIBUTE\_NODE

• `Readonly` **ATTRIBUTE\_NODE**: `number`

#### Inherited from

SVGElement.ATTRIBUTE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10578

___

### CDATA\_SECTION\_NODE

• `Readonly` **CDATA\_SECTION\_NODE**: `number`

node is a CDATASection node.

#### Inherited from

SVGElement.CDATA\_SECTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10582

___

### COMMENT\_NODE

• `Readonly` **COMMENT\_NODE**: `number`

node is a Comment node.

#### Inherited from

SVGElement.COMMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10586

___

### DOCUMENT\_FRAGMENT\_NODE

• `Readonly` **DOCUMENT\_FRAGMENT\_NODE**: `number`

node is a DocumentFragment node.

#### Inherited from

SVGElement.DOCUMENT\_FRAGMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10590

___

### DOCUMENT\_NODE

• `Readonly` **DOCUMENT\_NODE**: `number`

node is a document.

#### Inherited from

SVGElement.DOCUMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10594

___

### DOCUMENT\_POSITION\_CONTAINED\_BY

• `Readonly` **DOCUMENT\_POSITION\_CONTAINED\_BY**: `number`

Set when other is a descendant of node.

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_CONTAINED\_BY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10598

___

### DOCUMENT\_POSITION\_CONTAINS

• `Readonly` **DOCUMENT\_POSITION\_CONTAINS**: `number`

Set when other is an ancestor of node.

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_CONTAINS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10602

___

### DOCUMENT\_POSITION\_DISCONNECTED

• `Readonly` **DOCUMENT\_POSITION\_DISCONNECTED**: `number`

Set when node and other are not in the same tree.

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_DISCONNECTED

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10606

___

### DOCUMENT\_POSITION\_FOLLOWING

• `Readonly` **DOCUMENT\_POSITION\_FOLLOWING**: `number`

Set when other is following node.

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_FOLLOWING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10610

___

### DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

• `Readonly` **DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC**: `number`

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_IMPLEMENTATION\_SPECIFIC

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10611

___

### DOCUMENT\_POSITION\_PRECEDING

• `Readonly` **DOCUMENT\_POSITION\_PRECEDING**: `number`

Set when other is preceding node.

#### Inherited from

SVGElement.DOCUMENT\_POSITION\_PRECEDING

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10615

___

### DOCUMENT\_TYPE\_NODE

• `Readonly` **DOCUMENT\_TYPE\_NODE**: `number`

node is a doctype.

#### Inherited from

SVGElement.DOCUMENT\_TYPE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10619

___

### ELEMENT\_NODE

• `Readonly` **ELEMENT\_NODE**: `number`

node is an element.

#### Inherited from

SVGElement.ELEMENT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10623

___

### ENTITY\_NODE

• `Readonly` **ENTITY\_NODE**: `number`

#### Inherited from

SVGElement.ENTITY\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10624

___

### ENTITY\_REFERENCE\_NODE

• `Readonly` **ENTITY\_REFERENCE\_NODE**: `number`

#### Inherited from

SVGElement.ENTITY\_REFERENCE\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10625

___

### NOTATION\_NODE

• `Readonly` **NOTATION\_NODE**: `number`

#### Inherited from

SVGElement.NOTATION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10626

___

### PROCESSING\_INSTRUCTION\_NODE

• `Readonly` **PROCESSING\_INSTRUCTION\_NODE**: `number`

node is a ProcessingInstruction node.

#### Inherited from

SVGElement.PROCESSING\_INSTRUCTION\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10630

___

### TEXT\_NODE

• `Readonly` **TEXT\_NODE**: `number`

node is a Text node.

#### Inherited from

SVGElement.TEXT\_NODE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10634

___

### ariaAtomic

• **ariaAtomic**: `string`

#### Inherited from

SVGElement.ariaAtomic

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1860

___

### ariaAutoComplete

• **ariaAutoComplete**: `string`

#### Inherited from

SVGElement.ariaAutoComplete

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1861

___

### ariaBusy

• **ariaBusy**: `string`

#### Inherited from

SVGElement.ariaBusy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1862

___

### ariaChecked

• **ariaChecked**: `string`

#### Inherited from

SVGElement.ariaChecked

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1863

___

### ariaColCount

• **ariaColCount**: `string`

#### Inherited from

SVGElement.ariaColCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1864

___

### ariaColIndex

• **ariaColIndex**: `string`

#### Inherited from

SVGElement.ariaColIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1865

___

### ariaColSpan

• **ariaColSpan**: `string`

#### Inherited from

SVGElement.ariaColSpan

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1866

___

### ariaCurrent

• **ariaCurrent**: `string`

#### Inherited from

SVGElement.ariaCurrent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1867

___

### ariaDisabled

• **ariaDisabled**: `string`

#### Inherited from

SVGElement.ariaDisabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1868

___

### ariaExpanded

• **ariaExpanded**: `string`

#### Inherited from

SVGElement.ariaExpanded

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1869

___

### ariaHasPopup

• **ariaHasPopup**: `string`

#### Inherited from

SVGElement.ariaHasPopup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1870

___

### ariaHidden

• **ariaHidden**: `string`

#### Inherited from

SVGElement.ariaHidden

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1871

___

### ariaKeyShortcuts

• **ariaKeyShortcuts**: `string`

#### Inherited from

SVGElement.ariaKeyShortcuts

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1872

___

### ariaLabel

• **ariaLabel**: `string`

#### Inherited from

SVGElement.ariaLabel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1873

___

### ariaLevel

• **ariaLevel**: `string`

#### Inherited from

SVGElement.ariaLevel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1874

___

### ariaLive

• **ariaLive**: `string`

#### Inherited from

SVGElement.ariaLive

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1875

___

### ariaModal

• **ariaModal**: `string`

#### Inherited from

SVGElement.ariaModal

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1876

___

### ariaMultiLine

• **ariaMultiLine**: `string`

#### Inherited from

SVGElement.ariaMultiLine

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1877

___

### ariaMultiSelectable

• **ariaMultiSelectable**: `string`

#### Inherited from

SVGElement.ariaMultiSelectable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1878

___

### ariaOrientation

• **ariaOrientation**: `string`

#### Inherited from

SVGElement.ariaOrientation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1879

___

### ariaPlaceholder

• **ariaPlaceholder**: `string`

#### Inherited from

SVGElement.ariaPlaceholder

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1880

___

### ariaPosInSet

• **ariaPosInSet**: `string`

#### Inherited from

SVGElement.ariaPosInSet

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1881

___

### ariaPressed

• **ariaPressed**: `string`

#### Inherited from

SVGElement.ariaPressed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1882

___

### ariaReadOnly

• **ariaReadOnly**: `string`

#### Inherited from

SVGElement.ariaReadOnly

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1883

___

### ariaRequired

• **ariaRequired**: `string`

#### Inherited from

SVGElement.ariaRequired

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1884

___

### ariaRoleDescription

• **ariaRoleDescription**: `string`

#### Inherited from

SVGElement.ariaRoleDescription

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1885

___

### ariaRowCount

• **ariaRowCount**: `string`

#### Inherited from

SVGElement.ariaRowCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1886

___

### ariaRowIndex

• **ariaRowIndex**: `string`

#### Inherited from

SVGElement.ariaRowIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1887

___

### ariaRowSpan

• **ariaRowSpan**: `string`

#### Inherited from

SVGElement.ariaRowSpan

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1888

___

### ariaSelected

• **ariaSelected**: `string`

#### Inherited from

SVGElement.ariaSelected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1889

___

### ariaSetSize

• **ariaSetSize**: `string`

#### Inherited from

SVGElement.ariaSetSize

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1890

___

### ariaSort

• **ariaSort**: `string`

#### Inherited from

SVGElement.ariaSort

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1891

___

### ariaValueMax

• **ariaValueMax**: `string`

#### Inherited from

SVGElement.ariaValueMax

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1892

___

### ariaValueMin

• **ariaValueMin**: `string`

#### Inherited from

SVGElement.ariaValueMin

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1893

___

### ariaValueNow

• **ariaValueNow**: `string`

#### Inherited from

SVGElement.ariaValueNow

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1894

___

### ariaValueText

• **ariaValueText**: `string`

#### Inherited from

SVGElement.ariaValueText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1895

___

### assignedSlot

• `Readonly` **assignedSlot**: `HTMLSlotElement`

#### Inherited from

SVGElement.assignedSlot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14105

___

### attributes

• `Readonly` **attributes**: [`NamedNodeMap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#namednodemap)

#### Inherited from

SVGElement.attributes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4873

___

### baseURI

• `Readonly` **baseURI**: `string`

Returns node's node document's document base URL.

#### Inherited from

SVGElement.baseURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10495

___

### childElementCount

• `Readonly` **childElementCount**: `number`

#### Inherited from

SVGElement.childElementCount

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10958

___

### childNodes

• `Readonly` **childNodes**: [`NodeListOf`](akashaproject_ui_awf_testing_utils._internal_.NodeListOf.md)<[`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)\>

Returns the children.

#### Inherited from

SVGElement.childNodes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10499

___

### children

• `Readonly` **children**: [`HTMLCollection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#htmlcollection)

Returns the child elements.

#### Inherited from

SVGElement.children

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10962

___

### classList

• `Readonly` **classList**: [`DOMTokenList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domtokenlist)

Allows for manipulation of element's class content attribute as a set of whitespace-separated tokens through a DOMTokenList object.

#### Inherited from

SVGElement.classList

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4877

___

### className

• `Readonly` **className**: `any`

**`deprecated`**

#### Inherited from

SVGElement.className

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12489

___

### clientHeight

• `Readonly` **clientHeight**: `number`

#### Inherited from

SVGElement.clientHeight

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4882

___

### clientLeft

• `Readonly` **clientLeft**: `number`

#### Inherited from

SVGElement.clientLeft

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4883

___

### clientTop

• `Readonly` **clientTop**: `number`

#### Inherited from

SVGElement.clientTop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4884

___

### clientWidth

• `Readonly` **clientWidth**: `number`

#### Inherited from

SVGElement.clientWidth

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4885

___

### dataset

• `Readonly` **dataset**: [`DOMStringMap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domstringmap)

#### Inherited from

SVGElement.dataset

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7897

___

### firstChild

• `Readonly` **firstChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the first child.

#### Inherited from

SVGElement.firstChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10503

___

### firstElementChild

• `Readonly` **firstElementChild**: `Element`

Returns the first child that is an element, and null otherwise.

#### Inherited from

SVGElement.firstElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10966

___

### id

• **id**: `string`

Returns the value of element's id content attribute. Can be set to change it.

#### Inherited from

SVGElement.id

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4889

___

### innerHTML

• **innerHTML**: `string`

#### Inherited from

SVGElement.innerHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9506

___

### isConnected

• `Readonly` **isConnected**: `boolean`

Returns true if node is connected and false otherwise.

#### Inherited from

SVGElement.isConnected

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10507

___

### lastChild

• `Readonly` **lastChild**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the last child.

#### Inherited from

SVGElement.lastChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10511

___

### lastElementChild

• `Readonly` **lastElementChild**: `Element`

Returns the last child that is an element, and null otherwise.

#### Inherited from

SVGElement.lastElementChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10970

___

### localName

• `Readonly` **localName**: `string`

Returns the local name.

#### Inherited from

SVGElement.localName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4893

___

### namespaceURI

• `Readonly` **namespaceURI**: `string`

Returns the namespace.

#### Inherited from

SVGElement.namespaceURI

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4897

___

### nextElementSibling

• `Readonly` **nextElementSibling**: `Element`

Returns the first following sibling that is an element, and null otherwise.

#### Inherited from

SVGElement.nextElementSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10756

___

### nextSibling

• `Readonly` **nextSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the next sibling.

#### Inherited from

SVGElement.nextSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10515

___

### nodeName

• `Readonly` **nodeName**: `string`

Returns a string appropriate for the type of node.

#### Inherited from

SVGElement.nodeName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10519

___

### nodeType

• `Readonly` **nodeType**: `number`

Returns the type of node.

#### Inherited from

SVGElement.nodeType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10523

___

### nodeValue

• **nodeValue**: `string`

#### Inherited from

SVGElement.nodeValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10524

___

### nonce

• `Optional` **nonce**: `string`

#### Inherited from

SVGElement.nonce

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7898

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

SVGElement.onabort

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

SVGElement.onanimationcancel

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

SVGElement.onanimationend

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

SVGElement.onanimationiteration

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

SVGElement.onanimationstart

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

SVGElement.onauxclick

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

SVGElement.onblur

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

SVGElement.oncanplay

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

SVGElement.oncanplaythrough

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

SVGElement.onchange

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

SVGElement.onclick

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

SVGElement.onclose

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

SVGElement.oncontextmenu

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

SVGElement.oncopy

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

SVGElement.oncuechange

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

SVGElement.oncut

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

SVGElement.ondblclick

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

SVGElement.ondrag

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

SVGElement.ondragend

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

SVGElement.ondragenter

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

SVGElement.ondragleave

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

SVGElement.ondragover

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

SVGElement.ondragstart

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

SVGElement.ondrop

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

SVGElement.ondurationchange

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

SVGElement.onemptied

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

SVGElement.onended

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5761

___

### onerror

• **onerror**: [`OnErrorEventHandlerNonNull`](akashaproject_ui_awf_testing_utils._internal_.OnErrorEventHandlerNonNull.md)

Fires when an error occurs during object loading.

**`param`** The event.

#### Inherited from

SVGElement.onerror

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

SVGElement.onfocus

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5771

___

### onformdata

• **onformdata**: (`ev`: [`FormDataEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#formdataevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`FormDataEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#formdataevent) |

##### Returns

`any`

#### Inherited from

SVGElement.onformdata

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

SVGElement.onfullscreenchange

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

SVGElement.onfullscreenerror

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

SVGElement.ongotpointercapture

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

SVGElement.oninput

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

SVGElement.oninvalid

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

SVGElement.onkeydown

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

SVGElement.onkeypress

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

SVGElement.onkeyup

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

SVGElement.onload

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

SVGElement.onloadeddata

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

SVGElement.onloadedmetadata

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

SVGElement.onloadstart

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

SVGElement.onlostpointercapture

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

SVGElement.onmousedown

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

SVGElement.onmouseenter

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

SVGElement.onmouseleave

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

SVGElement.onmousemove

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

SVGElement.onmouseout

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

SVGElement.onmouseover

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

SVGElement.onmouseup

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

SVGElement.onpaste

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

SVGElement.onpause

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

SVGElement.onplay

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

SVGElement.onplaying

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

SVGElement.onpointercancel

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

SVGElement.onpointerdown

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

SVGElement.onpointerenter

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

SVGElement.onpointerleave

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

SVGElement.onpointermove

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

SVGElement.onpointerout

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

SVGElement.onpointerover

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

SVGElement.onpointerup

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5862

___

### onprogress

• **onprogress**: (`ev`: [`ProgressEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#progressevent)<`EventTarget`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

Occurs to indicate progress while downloading media data.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ev` | [`ProgressEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#progressevent)<`EventTarget`\> | The event. |

##### Returns

`any`

#### Inherited from

SVGElement.onprogress

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

SVGElement.onratechange

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

SVGElement.onreset

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

SVGElement.onresize

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

SVGElement.onscroll

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

SVGElement.onseeked

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

SVGElement.onseeking

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

SVGElement.onselect

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

SVGElement.onselectionchange

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

SVGElement.onselectstart

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

SVGElement.onstalled

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

SVGElement.onsubmit

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

SVGElement.onsuspend

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

SVGElement.ontimeupdate

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

SVGElement.ontoggle

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

SVGElement.ontouchcancel

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

SVGElement.ontouchend

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

SVGElement.ontouchmove

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

SVGElement.ontouchstart

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

SVGElement.ontransitioncancel

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

SVGElement.ontransitionend

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

SVGElement.ontransitionrun

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

SVGElement.ontransitionstart

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

SVGElement.onvolumechange

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

SVGElement.onwaiting

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

SVGElement.onwebkitanimationend

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

SVGElement.onwebkitanimationiteration

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

SVGElement.onwebkitanimationstart

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

SVGElement.onwebkittransitionend

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

SVGElement.onwheel

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5940

___

### outerHTML

• **outerHTML**: `string`

#### Inherited from

SVGElement.outerHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4900

___

### ownerDocument

• `Readonly` **ownerDocument**: `Document`

#### Inherited from

SVGElement.ownerDocument

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4901

___

### ownerSVGElement

• `Readonly` **ownerSVGElement**: `SVGSVGElement`

#### Inherited from

SVGElement.ownerSVGElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12490

___

### parentElement

• `Readonly` **parentElement**: `HTMLElement`

Returns the parent element.

#### Inherited from

SVGElement.parentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10532

___

### parentNode

• `Readonly` **parentNode**: [`ParentNode`](akashaproject_ui_awf_testing_utils._internal_.ParentNode.md)

Returns the parent.

#### Inherited from

SVGElement.parentNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10536

___

### part

• `Readonly` **part**: [`DOMTokenList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domtokenlist)

#### Inherited from

SVGElement.part

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4902

___

### prefix

• `Readonly` **prefix**: `string`

Returns the namespace prefix.

#### Inherited from

SVGElement.prefix

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4906

___

### previousElementSibling

• `Readonly` **previousElementSibling**: `Element`

Returns the first preceding sibling that is an element, and null otherwise.

#### Inherited from

SVGElement.previousElementSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10760

___

### previousSibling

• `Readonly` **previousSibling**: [`ChildNode`](akashaproject_ui_awf_testing_utils._internal_.ChildNode.md)

Returns the previous sibling.

#### Inherited from

SVGElement.previousSibling

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10540

___

### requiredExtensions

• `Readonly` **requiredExtensions**: [`SVGStringList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#svgstringlist)

#### Inherited from

[SVGTests](akashaproject_ui_awf_testing_utils._internal_.SVGTests.md).[requiredExtensions](akashaproject_ui_awf_testing_utils._internal_.SVGTests.md#requiredextensions)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13672

___

### scrollHeight

• `Readonly` **scrollHeight**: `number`

#### Inherited from

SVGElement.scrollHeight

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4907

___

### scrollLeft

• **scrollLeft**: `number`

#### Inherited from

SVGElement.scrollLeft

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4908

___

### scrollTop

• **scrollTop**: `number`

#### Inherited from

SVGElement.scrollTop

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4909

___

### scrollWidth

• `Readonly` **scrollWidth**: `number`

#### Inherited from

SVGElement.scrollWidth

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4910

___

### shadowRoot

• `Readonly` **shadowRoot**: [`ShadowRoot`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#shadowroot)

Returns element's shadow root, if any, and if shadow root's mode is "open", and null otherwise.

#### Inherited from

SVGElement.shadowRoot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4914

___

### slot

• **slot**: `string`

Returns the value of element's slot content attribute. Can be set to change it.

#### Inherited from

SVGElement.slot

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4918

___

### style

• `Readonly` **style**: [`CSSStyleDeclaration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssstyledeclaration)

#### Inherited from

SVGElement.style

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5034

___

### systemLanguage

• `Readonly` **systemLanguage**: [`SVGStringList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#svgstringlist)

#### Inherited from

[SVGTests](akashaproject_ui_awf_testing_utils._internal_.SVGTests.md).[systemLanguage](akashaproject_ui_awf_testing_utils._internal_.SVGTests.md#systemlanguage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13673

___

### tabIndex

• **tabIndex**: `number`

#### Inherited from

SVGElement.tabIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7899

___

### tagName

• `Readonly` **tagName**: `string`

Returns the HTML-uppercased qualified name.

#### Inherited from

SVGElement.tagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4922

___

### textContent

• **textContent**: `string`

#### Inherited from

SVGElement.textContent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10541

___

### transform

• `Readonly` **transform**: [`SVGAnimatedTransformList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#svganimatedtransformlist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13124

___

### viewportElement

• `Readonly` **viewportElement**: `SVGElement`

#### Inherited from

SVGElement.viewportElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12491

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementEventMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SVGElementEventMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

SVGElement.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13128

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

SVGElement.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13129

___

### after

▸ **after**(...`nodes`): `void`

Inserts nodes just after node, while replacing strings in nodes with equivalent Text nodes.

Throws a "HierarchyRequestError" DOMException if the constraints of the node tree are violated.

#### Parameters

| Name | Type |
| :------ | :------ |
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

SVGElement.after

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3491

___

### animate

▸ **animate**(`keyframes`, `options?`): [`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyframes` | [`Keyframe`](akashaproject_ui_awf_testing_utils._internal_.Keyframe.md)[] \| [`PropertyIndexedKeyframes`](akashaproject_ui_awf_testing_utils._internal_.PropertyIndexedKeyframes.md) |
| `options?` | `number` \| [`KeyframeAnimationOptions`](akashaproject_ui_awf_testing_utils._internal_.KeyframeAnimationOptions.md) |

#### Returns

[`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)

#### Inherited from

SVGElement.animate

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
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

SVGElement.append

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

SVGElement.appendChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10542

___

### attachShadow

▸ **attachShadow**(`init`): [`ShadowRoot`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#shadowroot)

Creates a shadow root for element and returns it.

#### Parameters

| Name | Type |
| :------ | :------ |
| `init` | [`ShadowRootInit`](akashaproject_ui_awf_testing_utils._internal_.ShadowRootInit.md) |

#### Returns

[`ShadowRoot`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#shadowroot)

#### Inherited from

SVGElement.attachShadow

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
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

SVGElement.before

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3497

___

### blur

▸ **blur**(): `void`

#### Returns

`void`

#### Inherited from

SVGElement.blur

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7900

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

SVGElement.cloneNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10546

___

### closest

▸ **closest**<`K`\>(`selector`): [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]

Returns the first (starting at element) inclusive ancestor that matches selectors, and null otherwise.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector` | `K` |

#### Returns

[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]

#### Inherited from

SVGElement.closest

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4930

▸ **closest**<`K`\>(`selector`): [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector` | `K` |

#### Returns

[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]

#### Inherited from

SVGElement.closest

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

SVGElement.closest

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4932

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

SVGElement.compareDocumentPosition

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

SVGElement.contains

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

SVGElement.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### focus

▸ **focus**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`FocusOptions`](akashaproject_ui_awf_testing_utils._internal_.FocusOptions.md) |

#### Returns

`void`

#### Inherited from

SVGElement.focus

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:7901

___

### getAnimations

▸ **getAnimations**(`options?`): [`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`GetAnimationsOptions`](akashaproject_ui_awf_testing_utils._internal_.GetAnimationsOptions.md) |

#### Returns

[`Animation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#animation)[]

#### Inherited from

SVGElement.getAnimations

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

SVGElement.getAttribute

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

SVGElement.getAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4940

___

### getAttributeNames

▸ **getAttributeNames**(): `string`[]

Returns the qualified names of all element's attributes. Can contain duplicates.

#### Returns

`string`[]

#### Inherited from

SVGElement.getAttributeNames

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4944

___

### getAttributeNode

▸ **getAttributeNode**(`qualifiedName`): [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Inherited from

SVGElement.getAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4945

___

### getAttributeNodeNS

▸ **getAttributeNodeNS**(`namespace`, `localName`): [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Inherited from

SVGElement.getAttributeNodeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4946

___

### getBBox

▸ **getBBox**(`options?`): [`DOMRect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrect)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`SVGBoundingBoxOptions`](akashaproject_ui_awf_testing_utils._internal_.SVGBoundingBoxOptions.md) |

#### Returns

[`DOMRect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrect)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13125

___

### getBoundingClientRect

▸ **getBoundingClientRect**(): [`DOMRect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrect)

#### Returns

[`DOMRect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrect)

#### Inherited from

SVGElement.getBoundingClientRect

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4947

___

### getCTM

▸ **getCTM**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13126

___

### getClientRects

▸ **getClientRects**(): [`DOMRectList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrectlist)

#### Returns

[`DOMRectList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#domrectlist)

#### Inherited from

SVGElement.getClientRects

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4948

___

### getElementsByClassName

▸ **getElementsByClassName**(`classNames`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

Returns a HTMLCollection of the elements in the object on which the method was invoked (a document or an element) that have all the classes given by classNames. The classNames argument is interpreted as a space-separated list of classes.

#### Parameters

| Name | Type |
| :------ | :------ |
| `classNames` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

SVGElement.getElementsByClassName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4952

___

### getElementsByTagName

▸ **getElementsByTagName**<`K`\>(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `K` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<[`HTMLElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.HTMLElementTagNameMap.md)[`K`]\>

#### Inherited from

SVGElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4953

▸ **getElementsByTagName**<`K`\>(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `K` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<[`SVGElementTagNameMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementTagNameMap.md)[`K`]\>

#### Inherited from

SVGElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4954

▸ **getElementsByTagName**(`qualifiedName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

SVGElement.getElementsByTagName

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4955

___

### getElementsByTagNameNS

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/1999/xhtml"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`HTMLElement`\>

#### Inherited from

SVGElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4956

▸ **getElementsByTagNameNS**(`namespaceURI`, `localName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespaceURI` | ``"http://www.w3.org/2000/svg"`` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`SVGElement`\>

#### Inherited from

SVGElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4957

▸ **getElementsByTagNameNS**(`namespace`, `localName`): [`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `localName` | `string` |

#### Returns

[`HTMLCollectionOf`](akashaproject_ui_awf_testing_utils._internal_.HTMLCollectionOf.md)<`Element`\>

#### Inherited from

SVGElement.getElementsByTagNameNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4958

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

SVGElement.getRootNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10558

___

### getScreenCTM

▸ **getScreenCTM**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13127

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

SVGElement.hasAttribute

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

SVGElement.hasAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4966

___

### hasAttributes

▸ **hasAttributes**(): `boolean`

Returns true if element has attributes, and false otherwise.

#### Returns

`boolean`

#### Inherited from

SVGElement.hasAttributes

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4970

___

### hasChildNodes

▸ **hasChildNodes**(): `boolean`

Returns whether node has children.

#### Returns

`boolean`

#### Inherited from

SVGElement.hasChildNodes

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

SVGElement.hasPointerCapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4971

___

### insertAdjacentElement

▸ **insertAdjacentElement**(`where`, `element`): `Element`

#### Parameters

| Name | Type |
| :------ | :------ |
| `where` | [`InsertPosition`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#insertposition) |
| `element` | `Element` |

#### Returns

`Element`

#### Inherited from

SVGElement.insertAdjacentElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4972

___

### insertAdjacentHTML

▸ **insertAdjacentHTML**(`position`, `text`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | [`InsertPosition`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#insertposition) |
| `text` | `string` |

#### Returns

`void`

#### Inherited from

SVGElement.insertAdjacentHTML

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4973

___

### insertAdjacentText

▸ **insertAdjacentText**(`where`, `data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `where` | [`InsertPosition`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#insertposition) |
| `data` | `string` |

#### Returns

`void`

#### Inherited from

SVGElement.insertAdjacentText

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4974

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

SVGElement.insertBefore

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

SVGElement.isDefaultNamespace

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

SVGElement.isEqualNode

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

SVGElement.isSameNode

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

SVGElement.lookupNamespaceURI

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

SVGElement.lookupPrefix

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

SVGElement.matches

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4978

___

### normalize

▸ **normalize**(): `void`

Removes empty exclusive Text nodes and concatenates the data of remaining contiguous exclusive Text nodes into the first of their nodes.

#### Returns

`void`

#### Inherited from

SVGElement.normalize

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

SVGElement.prepend

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

SVGElement.querySelector

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

SVGElement.querySelector

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

SVGElement.querySelector

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

SVGElement.querySelectorAll

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

SVGElement.querySelectorAll

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

SVGElement.querySelectorAll

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

SVGElement.releasePointerCapture

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4979

___

### remove

▸ **remove**(): `void`

Removes node.

#### Returns

`void`

#### Inherited from

SVGElement.remove

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

SVGElement.removeAttribute

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

SVGElement.removeAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4987

___

### removeAttributeNode

▸ **removeAttributeNode**(`attr`): [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Inherited from

SVGElement.removeAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4988

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

SVGElement.removeChild

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10576

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SVGElementEventMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SVGElementEventMap`](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

SVGElement.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13130

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

SVGElement.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13131

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

SVGElement.replaceChild

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

SVGElement.replaceChildren

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
| `...nodes` | (`string` \| [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node))[] |

#### Returns

`void`

#### Inherited from

SVGElement.replaceWith

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
| `options?` | [`FullscreenOptions`](akashaproject_ui_awf_testing_utils._internal_.FullscreenOptions.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

SVGElement.requestFullscreen

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4994

___

### requestPointerLock

▸ **requestPointerLock**(): `void`

#### Returns

`void`

#### Inherited from

SVGElement.requestPointerLock

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4995

___

### scroll

▸ **scroll**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

SVGElement.scroll

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

SVGElement.scroll

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4997

___

### scrollBy

▸ **scrollBy**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

SVGElement.scrollBy

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

SVGElement.scrollBy

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4999

___

### scrollIntoView

▸ **scrollIntoView**(`arg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg?` | `boolean` \| [`ScrollIntoViewOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollIntoViewOptions.md) |

#### Returns

`void`

#### Inherited from

SVGElement.scrollIntoView

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5000

___

### scrollTo

▸ **scrollTo**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Inherited from

SVGElement.scrollTo

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

SVGElement.scrollTo

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

SVGElement.setAttribute

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

SVGElement.setAttributeNS

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5010

___

### setAttributeNode

▸ **setAttributeNode**(`attr`): [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Inherited from

SVGElement.setAttributeNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5011

___

### setAttributeNodeNS

▸ **setAttributeNodeNS**(`attr`): [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | [`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr) |

#### Returns

[`Attr`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#attr)

#### Inherited from

SVGElement.setAttributeNodeNS

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

SVGElement.setPointerCapture

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

SVGElement.toggleAttribute

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

SVGElement.webkitMatchesSelector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5021
