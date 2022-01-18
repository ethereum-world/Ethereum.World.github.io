[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Window

# Interface: Window

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Window

A window containing a DOM document; the document property points to the DOM document loaded in that window.

## Hierarchy

- `EventTarget`

- [`AnimationFrameProvider`](akashaproject_ui_awf_testing_utils._internal_.AnimationFrameProvider.md)

- [`GlobalEventHandlers`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md)

- [`WindowEventHandlers`](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md)

- [`WindowLocalStorage`](akashaproject_ui_awf_testing_utils._internal_.WindowLocalStorage.md)

- [`WindowOrWorkerGlobalScope`](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md)

- [`WindowSessionStorage`](akashaproject_ui_awf_testing_utils._internal_.WindowSessionStorage.md)

  ↳ **`Window`**

## Indexable

▪ [index: `number`]: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

## Table of contents

### Properties

- [caches](akashaproject_ui_awf_testing_utils._internal_.Window.md#caches)
- [clientInformation](akashaproject_ui_awf_testing_utils._internal_.Window.md#clientinformation)
- [closed](akashaproject_ui_awf_testing_utils._internal_.Window.md#closed)
- [crossOriginIsolated](akashaproject_ui_awf_testing_utils._internal_.Window.md#crossoriginisolated)
- [crypto](akashaproject_ui_awf_testing_utils._internal_.Window.md#crypto)
- [customElements](akashaproject_ui_awf_testing_utils._internal_.Window.md#customelements)
- [devicePixelRatio](akashaproject_ui_awf_testing_utils._internal_.Window.md#devicepixelratio)
- [document](akashaproject_ui_awf_testing_utils._internal_.Window.md#document)
- [event](akashaproject_ui_awf_testing_utils._internal_.Window.md#event)
- [external](akashaproject_ui_awf_testing_utils._internal_.Window.md#external)
- [frameElement](akashaproject_ui_awf_testing_utils._internal_.Window.md#frameelement)
- [frames](akashaproject_ui_awf_testing_utils._internal_.Window.md#frames)
- [history](akashaproject_ui_awf_testing_utils._internal_.Window.md#history)
- [indexedDB](akashaproject_ui_awf_testing_utils._internal_.Window.md#indexeddb)
- [innerHeight](akashaproject_ui_awf_testing_utils._internal_.Window.md#innerheight)
- [innerWidth](akashaproject_ui_awf_testing_utils._internal_.Window.md#innerwidth)
- [isSecureContext](akashaproject_ui_awf_testing_utils._internal_.Window.md#issecurecontext)
- [length](akashaproject_ui_awf_testing_utils._internal_.Window.md#length)
- [localStorage](akashaproject_ui_awf_testing_utils._internal_.Window.md#localstorage)
- [locationbar](akashaproject_ui_awf_testing_utils._internal_.Window.md#locationbar)
- [menubar](akashaproject_ui_awf_testing_utils._internal_.Window.md#menubar)
- [name](akashaproject_ui_awf_testing_utils._internal_.Window.md#name)
- [navigator](akashaproject_ui_awf_testing_utils._internal_.Window.md#navigator)
- [onabort](akashaproject_ui_awf_testing_utils._internal_.Window.md#onabort)
- [onafterprint](akashaproject_ui_awf_testing_utils._internal_.Window.md#onafterprint)
- [onanimationcancel](akashaproject_ui_awf_testing_utils._internal_.Window.md#onanimationcancel)
- [onanimationend](akashaproject_ui_awf_testing_utils._internal_.Window.md#onanimationend)
- [onanimationiteration](akashaproject_ui_awf_testing_utils._internal_.Window.md#onanimationiteration)
- [onanimationstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#onanimationstart)
- [onauxclick](akashaproject_ui_awf_testing_utils._internal_.Window.md#onauxclick)
- [onbeforeprint](akashaproject_ui_awf_testing_utils._internal_.Window.md#onbeforeprint)
- [onbeforeunload](akashaproject_ui_awf_testing_utils._internal_.Window.md#onbeforeunload)
- [onblur](akashaproject_ui_awf_testing_utils._internal_.Window.md#onblur)
- [oncanplay](akashaproject_ui_awf_testing_utils._internal_.Window.md#oncanplay)
- [oncanplaythrough](akashaproject_ui_awf_testing_utils._internal_.Window.md#oncanplaythrough)
- [onchange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onchange)
- [onclick](akashaproject_ui_awf_testing_utils._internal_.Window.md#onclick)
- [onclose](akashaproject_ui_awf_testing_utils._internal_.Window.md#onclose)
- [oncontextmenu](akashaproject_ui_awf_testing_utils._internal_.Window.md#oncontextmenu)
- [oncuechange](akashaproject_ui_awf_testing_utils._internal_.Window.md#oncuechange)
- [ondblclick](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondblclick)
- [ondevicemotion](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondevicemotion)
- [ondeviceorientation](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondeviceorientation)
- [ondrag](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondrag)
- [ondragend](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondragend)
- [ondragenter](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondragenter)
- [ondragleave](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondragleave)
- [ondragover](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondragover)
- [ondragstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondragstart)
- [ondrop](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondrop)
- [ondurationchange](akashaproject_ui_awf_testing_utils._internal_.Window.md#ondurationchange)
- [onemptied](akashaproject_ui_awf_testing_utils._internal_.Window.md#onemptied)
- [onended](akashaproject_ui_awf_testing_utils._internal_.Window.md#onended)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.Window.md#onerror)
- [onfocus](akashaproject_ui_awf_testing_utils._internal_.Window.md#onfocus)
- [onformdata](akashaproject_ui_awf_testing_utils._internal_.Window.md#onformdata)
- [ongamepadconnected](akashaproject_ui_awf_testing_utils._internal_.Window.md#ongamepadconnected)
- [ongamepaddisconnected](akashaproject_ui_awf_testing_utils._internal_.Window.md#ongamepaddisconnected)
- [ongotpointercapture](akashaproject_ui_awf_testing_utils._internal_.Window.md#ongotpointercapture)
- [onhashchange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onhashchange)
- [oninput](akashaproject_ui_awf_testing_utils._internal_.Window.md#oninput)
- [oninvalid](akashaproject_ui_awf_testing_utils._internal_.Window.md#oninvalid)
- [onkeydown](akashaproject_ui_awf_testing_utils._internal_.Window.md#onkeydown)
- [onkeypress](akashaproject_ui_awf_testing_utils._internal_.Window.md#onkeypress)
- [onkeyup](akashaproject_ui_awf_testing_utils._internal_.Window.md#onkeyup)
- [onlanguagechange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onlanguagechange)
- [onload](akashaproject_ui_awf_testing_utils._internal_.Window.md#onload)
- [onloadeddata](akashaproject_ui_awf_testing_utils._internal_.Window.md#onloadeddata)
- [onloadedmetadata](akashaproject_ui_awf_testing_utils._internal_.Window.md#onloadedmetadata)
- [onloadstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#onloadstart)
- [onlostpointercapture](akashaproject_ui_awf_testing_utils._internal_.Window.md#onlostpointercapture)
- [onmessage](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmessage)
- [onmessageerror](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmessageerror)
- [onmousedown](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmousedown)
- [onmouseenter](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmouseenter)
- [onmouseleave](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmouseleave)
- [onmousemove](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmousemove)
- [onmouseout](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmouseout)
- [onmouseover](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmouseover)
- [onmouseup](akashaproject_ui_awf_testing_utils._internal_.Window.md#onmouseup)
- [onoffline](akashaproject_ui_awf_testing_utils._internal_.Window.md#onoffline)
- [ononline](akashaproject_ui_awf_testing_utils._internal_.Window.md#ononline)
- [onorientationchange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onorientationchange)
- [onpagehide](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpagehide)
- [onpageshow](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpageshow)
- [onpause](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpause)
- [onplay](akashaproject_ui_awf_testing_utils._internal_.Window.md#onplay)
- [onplaying](akashaproject_ui_awf_testing_utils._internal_.Window.md#onplaying)
- [onpointercancel](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointercancel)
- [onpointerdown](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerdown)
- [onpointerenter](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerenter)
- [onpointerleave](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerleave)
- [onpointermove](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointermove)
- [onpointerout](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerout)
- [onpointerover](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerover)
- [onpointerup](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpointerup)
- [onpopstate](akashaproject_ui_awf_testing_utils._internal_.Window.md#onpopstate)
- [onprogress](akashaproject_ui_awf_testing_utils._internal_.Window.md#onprogress)
- [onratechange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onratechange)
- [onrejectionhandled](akashaproject_ui_awf_testing_utils._internal_.Window.md#onrejectionhandled)
- [onreset](akashaproject_ui_awf_testing_utils._internal_.Window.md#onreset)
- [onresize](akashaproject_ui_awf_testing_utils._internal_.Window.md#onresize)
- [onscroll](akashaproject_ui_awf_testing_utils._internal_.Window.md#onscroll)
- [onseeked](akashaproject_ui_awf_testing_utils._internal_.Window.md#onseeked)
- [onseeking](akashaproject_ui_awf_testing_utils._internal_.Window.md#onseeking)
- [onselect](akashaproject_ui_awf_testing_utils._internal_.Window.md#onselect)
- [onselectionchange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onselectionchange)
- [onselectstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#onselectstart)
- [onstalled](akashaproject_ui_awf_testing_utils._internal_.Window.md#onstalled)
- [onstorage](akashaproject_ui_awf_testing_utils._internal_.Window.md#onstorage)
- [onsubmit](akashaproject_ui_awf_testing_utils._internal_.Window.md#onsubmit)
- [onsuspend](akashaproject_ui_awf_testing_utils._internal_.Window.md#onsuspend)
- [ontimeupdate](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontimeupdate)
- [ontoggle](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontoggle)
- [ontouchcancel](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontouchcancel)
- [ontouchend](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontouchend)
- [ontouchmove](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontouchmove)
- [ontouchstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontouchstart)
- [ontransitioncancel](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontransitioncancel)
- [ontransitionend](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontransitionend)
- [ontransitionrun](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontransitionrun)
- [ontransitionstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#ontransitionstart)
- [onunhandledrejection](akashaproject_ui_awf_testing_utils._internal_.Window.md#onunhandledrejection)
- [onunload](akashaproject_ui_awf_testing_utils._internal_.Window.md#onunload)
- [onvolumechange](akashaproject_ui_awf_testing_utils._internal_.Window.md#onvolumechange)
- [onwaiting](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwaiting)
- [onwebkitanimationend](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwebkitanimationend)
- [onwebkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwebkitanimationiteration)
- [onwebkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwebkitanimationstart)
- [onwebkittransitionend](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwebkittransitionend)
- [onwheel](akashaproject_ui_awf_testing_utils._internal_.Window.md#onwheel)
- [opener](akashaproject_ui_awf_testing_utils._internal_.Window.md#opener)
- [orientation](akashaproject_ui_awf_testing_utils._internal_.Window.md#orientation)
- [origin](akashaproject_ui_awf_testing_utils._internal_.Window.md#origin)
- [outerHeight](akashaproject_ui_awf_testing_utils._internal_.Window.md#outerheight)
- [outerWidth](akashaproject_ui_awf_testing_utils._internal_.Window.md#outerwidth)
- [pageXOffset](akashaproject_ui_awf_testing_utils._internal_.Window.md#pagexoffset)
- [pageYOffset](akashaproject_ui_awf_testing_utils._internal_.Window.md#pageyoffset)
- [parent](akashaproject_ui_awf_testing_utils._internal_.Window.md#parent)
- [performance](akashaproject_ui_awf_testing_utils._internal_.Window.md#performance)
- [personalbar](akashaproject_ui_awf_testing_utils._internal_.Window.md#personalbar)
- [screen](akashaproject_ui_awf_testing_utils._internal_.Window.md#screen)
- [screenLeft](akashaproject_ui_awf_testing_utils._internal_.Window.md#screenleft)
- [screenTop](akashaproject_ui_awf_testing_utils._internal_.Window.md#screentop)
- [screenX](akashaproject_ui_awf_testing_utils._internal_.Window.md#screenx)
- [screenY](akashaproject_ui_awf_testing_utils._internal_.Window.md#screeny)
- [scrollX](akashaproject_ui_awf_testing_utils._internal_.Window.md#scrollx)
- [scrollY](akashaproject_ui_awf_testing_utils._internal_.Window.md#scrolly)
- [scrollbars](akashaproject_ui_awf_testing_utils._internal_.Window.md#scrollbars)
- [self](akashaproject_ui_awf_testing_utils._internal_.Window.md#self)
- [sessionStorage](akashaproject_ui_awf_testing_utils._internal_.Window.md#sessionstorage)
- [speechSynthesis](akashaproject_ui_awf_testing_utils._internal_.Window.md#speechsynthesis)
- [status](akashaproject_ui_awf_testing_utils._internal_.Window.md#status)
- [statusbar](akashaproject_ui_awf_testing_utils._internal_.Window.md#statusbar)
- [toolbar](akashaproject_ui_awf_testing_utils._internal_.Window.md#toolbar)
- [top](akashaproject_ui_awf_testing_utils._internal_.Window.md#top)
- [visualViewport](akashaproject_ui_awf_testing_utils._internal_.Window.md#visualviewport)
- [window](akashaproject_ui_awf_testing_utils._internal_.Window.md#window)

### Accessors

- [location](akashaproject_ui_awf_testing_utils._internal_.Window.md#location)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.Window.md#addeventlistener)
- [alert](akashaproject_ui_awf_testing_utils._internal_.Window.md#alert)
- [atob](akashaproject_ui_awf_testing_utils._internal_.Window.md#atob)
- [blur](akashaproject_ui_awf_testing_utils._internal_.Window.md#blur)
- [btoa](akashaproject_ui_awf_testing_utils._internal_.Window.md#btoa)
- [cancelAnimationFrame](akashaproject_ui_awf_testing_utils._internal_.Window.md#cancelanimationframe)
- [cancelIdleCallback](akashaproject_ui_awf_testing_utils._internal_.Window.md#cancelidlecallback)
- [captureEvents](akashaproject_ui_awf_testing_utils._internal_.Window.md#captureevents)
- [clearInterval](akashaproject_ui_awf_testing_utils._internal_.Window.md#clearinterval)
- [clearTimeout](akashaproject_ui_awf_testing_utils._internal_.Window.md#cleartimeout)
- [close](akashaproject_ui_awf_testing_utils._internal_.Window.md#close)
- [confirm](akashaproject_ui_awf_testing_utils._internal_.Window.md#confirm)
- [createImageBitmap](akashaproject_ui_awf_testing_utils._internal_.Window.md#createimagebitmap)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.Window.md#dispatchevent)
- [fetch](akashaproject_ui_awf_testing_utils._internal_.Window.md#fetch)
- [focus](akashaproject_ui_awf_testing_utils._internal_.Window.md#focus)
- [getComputedStyle](akashaproject_ui_awf_testing_utils._internal_.Window.md#getcomputedstyle)
- [getSelection](akashaproject_ui_awf_testing_utils._internal_.Window.md#getselection)
- [matchMedia](akashaproject_ui_awf_testing_utils._internal_.Window.md#matchmedia)
- [moveBy](akashaproject_ui_awf_testing_utils._internal_.Window.md#moveby)
- [moveTo](akashaproject_ui_awf_testing_utils._internal_.Window.md#moveto)
- [open](akashaproject_ui_awf_testing_utils._internal_.Window.md#open)
- [postMessage](akashaproject_ui_awf_testing_utils._internal_.Window.md#postmessage)
- [print](akashaproject_ui_awf_testing_utils._internal_.Window.md#print)
- [prompt](akashaproject_ui_awf_testing_utils._internal_.Window.md#prompt)
- [queueMicrotask](akashaproject_ui_awf_testing_utils._internal_.Window.md#queuemicrotask)
- [releaseEvents](akashaproject_ui_awf_testing_utils._internal_.Window.md#releaseevents)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.Window.md#removeeventlistener)
- [requestAnimationFrame](akashaproject_ui_awf_testing_utils._internal_.Window.md#requestanimationframe)
- [requestIdleCallback](akashaproject_ui_awf_testing_utils._internal_.Window.md#requestidlecallback)
- [resizeBy](akashaproject_ui_awf_testing_utils._internal_.Window.md#resizeby)
- [resizeTo](akashaproject_ui_awf_testing_utils._internal_.Window.md#resizeto)
- [scroll](akashaproject_ui_awf_testing_utils._internal_.Window.md#scroll)
- [scrollBy](akashaproject_ui_awf_testing_utils._internal_.Window.md#scrollby)
- [scrollTo](akashaproject_ui_awf_testing_utils._internal_.Window.md#scrollto)
- [setInterval](akashaproject_ui_awf_testing_utils._internal_.Window.md#setinterval)
- [setTimeout](akashaproject_ui_awf_testing_utils._internal_.Window.md#settimeout)
- [stop](akashaproject_ui_awf_testing_utils._internal_.Window.md#stop)

## Properties

### caches

• `Readonly` **caches**: [`CacheStorage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cachestorage)

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[caches](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#caches)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17402

___

### clientInformation

• `Readonly` **clientInformation**: [`Navigator`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#navigator)

**`deprecated`** This is a legacy alias of `navigator`.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17211

___

### closed

• `Readonly` **closed**: `boolean`

Returns true if the window has been closed, false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17215

___

### crossOriginIsolated

• `Readonly` **crossOriginIsolated**: `boolean`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[crossOriginIsolated](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#crossoriginisolated)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17403

___

### crypto

• `Readonly` **crypto**: [`Crypto`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#crypto)

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[crypto](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#crypto)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17404

___

### customElements

• `Readonly` **customElements**: [`CustomElementRegistry`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#customelementregistry)

Defines a new custom element, mapping the given name to the given constructor as an autonomous custom element.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17219

___

### devicePixelRatio

• `Readonly` **devicePixelRatio**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17220

___

### document

• `Readonly` **document**: `Document`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17221

___

### event

• `Readonly` **event**: `Event`

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17223

___

### external

• `Readonly` **external**: [`External`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#external)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17225

___

### frameElement

• `Readonly` **frameElement**: `Element`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17226

___

### frames

• `Readonly` **frames**: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17227

___

### history

• `Readonly` **history**: [`History`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#history)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17228

___

### indexedDB

• `Readonly` **indexedDB**: [`IDBFactory`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#idbfactory)

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[indexedDB](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#indexeddb)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17405

___

### innerHeight

• `Readonly` **innerHeight**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17229

___

### innerWidth

• `Readonly` **innerWidth**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17230

___

### isSecureContext

• `Readonly` **isSecureContext**: `boolean`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[isSecureContext](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#issecurecontext)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17406

___

### length

• `Readonly` **length**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17231

___

### localStorage

• `Readonly` **localStorage**: [`Storage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#storage)

#### Inherited from

[WindowLocalStorage](akashaproject_ui_awf_testing_utils._internal_.WindowLocalStorage.md).[localStorage](akashaproject_ui_awf_testing_utils._internal_.WindowLocalStorage.md#localstorage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17398

___

### locationbar

• `Readonly` **locationbar**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the location bar is visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17237

___

### menubar

• `Readonly` **menubar**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the menu bar is visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17241

___

### name

• **name**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17242

___

### navigator

• `Readonly` **navigator**: [`Navigator`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#navigator)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17243

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onabort](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onabort)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5677

___

### onafterprint

• **onafterprint**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onafterprint](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onafterprint)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17373

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onanimationcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationcancel)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onanimationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onanimationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationiteration)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onanimationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onauxclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onauxclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5682

___

### onbeforeprint

• **onbeforeprint**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onbeforeprint](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onbeforeprint)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17374

___

### onbeforeunload

• **onbeforeunload**: (`ev`: [`BeforeUnloadEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#beforeunloadevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`BeforeUnloadEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#beforeunloadevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onbeforeunload](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onbeforeunload)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17375

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onblur](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onblur)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oncanplay](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncanplay)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oncanplaythrough](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncanplaythrough)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onchange)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onclick)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onclose](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onclose)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oncontextmenu](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncontextmenu)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5709

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oncuechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncuechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5710

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondblclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondblclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5715

___

### ondevicemotion

• **ondevicemotion**: (`ev`: [`DeviceMotionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#devicemotionevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`DeviceMotionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#devicemotionevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17244

___

### ondeviceorientation

• **ondeviceorientation**: (`ev`: [`DeviceOrientationEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#deviceorientationevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`DeviceOrientationEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#deviceorientationevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17245

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondrag](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondrag)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondragend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondragenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragenter)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondragleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragleave)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondragover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragover)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondragstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondrop](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondrop)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ondurationchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondurationchange)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onemptied](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onemptied)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onended](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onended)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5761

___

### onerror

• **onerror**: [`OnErrorEventHandlerNonNull`](akashaproject_ui_awf_testing_utils._internal_.OnErrorEventHandlerNonNull.md)

Fires when an error occurs during object loading.

**`param`** The event.

#### Inherited from

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onerror](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onerror)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onfocus](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onfocus)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onformdata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onformdata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5772

___

### ongamepadconnected

• **ongamepadconnected**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[ongamepadconnected](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#ongamepadconnected)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17376

___

### ongamepaddisconnected

• **ongamepaddisconnected**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[ongamepaddisconnected](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#ongamepaddisconnected)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17377

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ongotpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ongotpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5773

___

### onhashchange

• **onhashchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onhashchange](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onhashchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17378

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oninput](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oninput)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[oninvalid](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oninvalid)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onkeydown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeydown)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onkeypress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeypress)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onkeyup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeyup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5791

___

### onlanguagechange

• **onlanguagechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onlanguagechange](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onlanguagechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17379

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onload](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onload)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onloadeddata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadeddata)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onloadedmetadata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadedmetadata)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onloadstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onlostpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onlostpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5812

___

### onmessage

• **onmessage**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onmessage](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onmessage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17380

___

### onmessageerror

• **onmessageerror**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onmessageerror](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onmessageerror)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17381

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmousedown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmousedown)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmouseenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseenter)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmouseleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseleave)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmousemove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmousemove)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmouseout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseout)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmouseover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseover)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onmouseup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5839

___

### onoffline

• **onoffline**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onoffline](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onoffline)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17382

___

### ononline

• **ononline**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[ononline](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#ononline)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17383

___

### onorientationchange

• **onorientationchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

**`deprecated`**

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17247

___

### onpagehide

• **onpagehide**: (`ev`: [`PageTransitionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pagetransitionevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`PageTransitionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pagetransitionevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onpagehide](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onpagehide)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17384

___

### onpageshow

• **onpageshow**: (`ev`: [`PageTransitionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pagetransitionevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`PageTransitionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pagetransitionevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onpageshow](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onpageshow)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17385

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpause](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpause)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onplay](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onplay)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onplaying](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onplaying)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointercancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointercancel)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerdown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerdown)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerenter)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerleave)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointermove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointermove)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerout)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerover)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onpointerup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5862

___

### onpopstate

• **onpopstate**: (`ev`: [`PopStateEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#popstateevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`PopStateEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#popstateevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onpopstate](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onpopstate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17386

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onprogress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onprogress)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onratechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onratechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5872

___

### onrejectionhandled

• **onrejectionhandled**: (`ev`: [`PromiseRejectionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#promiserejectionevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`PromiseRejectionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#promiserejectionevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onrejectionhandled](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onrejectionhandled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17387

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onreset](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onreset)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onresize](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onresize)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onscroll](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onscroll)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onseeked](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onseeked)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onseeking](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onseeking)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onselect](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselect)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onselectionchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselectionchange)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onselectstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselectstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onstalled](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onstalled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5905

___

### onstorage

• **onstorage**: (`ev`: [`StorageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#storageevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`StorageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#storageevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onstorage](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onstorage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17388

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onsubmit](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onsubmit)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onsuspend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onsuspend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontimeupdate](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontimeupdate)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontoggle](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontoggle)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontouchcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchcancel)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontouchend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontouchmove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchmove)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontouchstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontransitioncancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitioncancel)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontransitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontransitionrun](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionrun)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[ontransitionstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5925

___

### onunhandledrejection

• **onunhandledrejection**: (`ev`: [`PromiseRejectionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#promiserejectionevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`PromiseRejectionEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#promiserejectionevent) |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onunhandledrejection](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onunhandledrejection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17389

___

### onunload

• **onunload**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Inherited from

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[onunload](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#onunload)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17390

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onvolumechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onvolumechange)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwaiting](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwaiting)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwebkitanimationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwebkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationiteration)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwebkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationstart)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwebkittransitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkittransitionend)

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

[GlobalEventHandlers](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md).[onwheel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwheel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5940

___

### opener

• **opener**: `any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17248

___

### orientation

• `Readonly` **orientation**: `number`

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17250

___

### origin

• `Readonly` **origin**: `string`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[origin](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#origin)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17407

___

### outerHeight

• `Readonly` **outerHeight**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17251

___

### outerWidth

• `Readonly` **outerWidth**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17252

___

### pageXOffset

• `Readonly` **pageXOffset**: `number`

**`deprecated`** This is a legacy alias of `scrollX`.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17254

___

### pageYOffset

• `Readonly` **pageYOffset**: `number`

**`deprecated`** This is a legacy alias of `scrollY`.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17256

___

### parent

• `Readonly` **parent**: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

Refers to either the parent WindowProxy, or itself. It can rarely be null e.g. for contentWindow of an iframe that is already removed from the parent.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17258

___

### performance

• `Readonly` **performance**: [`Performance`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performance)

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[performance](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#performance)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17408

___

### personalbar

• `Readonly` **personalbar**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the personal bar is visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17262

___

### screen

• `Readonly` **screen**: [`Screen`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#screen)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17263

___

### screenLeft

• `Readonly` **screenLeft**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17264

___

### screenTop

• `Readonly` **screenTop**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17265

___

### screenX

• `Readonly` **screenX**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17266

___

### screenY

• `Readonly` **screenY**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17267

___

### scrollX

• `Readonly` **scrollX**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17268

___

### scrollY

• `Readonly` **scrollY**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17269

___

### scrollbars

• `Readonly` **scrollbars**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the scrollbars are visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17273

___

### self

• `Readonly` **self**: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window) & typeof `globalThis`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17274

___

### sessionStorage

• `Readonly` **sessionStorage**: [`Storage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#storage)

#### Inherited from

[WindowSessionStorage](akashaproject_ui_awf_testing_utils._internal_.WindowSessionStorage.md).[sessionStorage](akashaproject_ui_awf_testing_utils._internal_.WindowSessionStorage.md#sessionstorage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17422

___

### speechSynthesis

• `Readonly` **speechSynthesis**: [`SpeechSynthesis`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesis)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17275

___

### status

• **status**: `string`

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17277

___

### statusbar

• `Readonly` **statusbar**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the status bar is visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17281

___

### toolbar

• `Readonly` **toolbar**: [`BarProp`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#barprop)

Returns true if the toolbar is visible; otherwise, returns false.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17285

___

### top

• `Readonly` **top**: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17286

___

### visualViewport

• `Readonly` **visualViewport**: [`VisualViewport`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#visualviewport)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17287

___

### window

• `Readonly` **window**: [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window) & typeof `globalThis`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17288

## Accessors

### location

• `get` **location**(): [`Location`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#location)

#### Returns

[`Location`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#location)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17232

• `set` **location**(`href`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `href` | `string` \| [`Location`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#location) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17233

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`WindowEventMap`](akashaproject_ui_awf_testing_utils._internal_.WindowEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`WindowEventMap`](akashaproject_ui_awf_testing_utils._internal_.WindowEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[addEventListener](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#addeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17339

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

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[addEventListener](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#addeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17340

___

### alert

▸ **alert**(`message?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17289

___

### atob

▸ **atob**(`data`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`string`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[atob](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#atob)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17409

___

### blur

▸ **blur**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17290

___

### btoa

▸ **btoa**(`data`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`string`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[btoa](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#btoa)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17410

___

### cancelAnimationFrame

▸ **cancelAnimationFrame**(`handle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle` | `number` |

#### Returns

`void`

#### Inherited from

[AnimationFrameProvider](akashaproject_ui_awf_testing_utils._internal_.AnimationFrameProvider.md).[cancelAnimationFrame](akashaproject_ui_awf_testing_utils._internal_.AnimationFrameProvider.md#cancelanimationframe)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2064

___

### cancelIdleCallback

▸ **cancelIdleCallback**(`handle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17291

___

### captureEvents

▸ **captureEvents**(): `void`

**`deprecated`**

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17293

___

### clearInterval

▸ **clearInterval**(`handle?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle?` | `number` |

#### Returns

`void`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[clearInterval](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#clearinterval)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17411

___

### clearTimeout

▸ **clearTimeout**(`handle?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handle?` | `number` |

#### Returns

`void`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[clearTimeout](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#cleartimeout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17412

___

### close

▸ **close**(): `void`

Closes the window.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17297

___

### confirm

▸ **confirm**(`message?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17298

___

### createImageBitmap

▸ **createImageBitmap**(`image`, `options?`): `Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `image` | [`ImageBitmapSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmapsource) |
| `options?` | [`ImageBitmapOptions`](akashaproject_ui_awf_testing_utils._internal_.ImageBitmapOptions.md) |

#### Returns

`Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[createImageBitmap](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#createimagebitmap)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17413

▸ **createImageBitmap**(`image`, `sx`, `sy`, `sw`, `sh`, `options?`): `Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `image` | [`ImageBitmapSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmapsource) |
| `sx` | `number` |
| `sy` | `number` |
| `sw` | `number` |
| `sh` | `number` |
| `options?` | [`ImageBitmapOptions`](akashaproject_ui_awf_testing_utils._internal_.ImageBitmapOptions.md) |

#### Returns

`Promise`<[`ImageBitmap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#imagebitmap)\>

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[createImageBitmap](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#createimagebitmap)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17414

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

### fetch

▸ **fetch**(`input`, `init?`): `Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `input` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `init?` | [`RequestInit`](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md) |

#### Returns

`Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[fetch](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#fetch)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17415

___

### focus

▸ **focus**(): `void`

Moves the focus to the window's browsing context, if any.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17302

___

### getComputedStyle

▸ **getComputedStyle**(`elt`, `pseudoElt?`): [`CSSStyleDeclaration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssstyledeclaration)

#### Parameters

| Name | Type |
| :------ | :------ |
| `elt` | `Element` |
| `pseudoElt?` | `string` |

#### Returns

[`CSSStyleDeclaration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssstyledeclaration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17303

___

### getSelection

▸ **getSelection**(): [`Selection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#selection)

#### Returns

[`Selection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#selection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17304

___

### matchMedia

▸ **matchMedia**(`query`): [`MediaQueryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylist)

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `string` |

#### Returns

[`MediaQueryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17305

___

### moveBy

▸ **moveBy**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17306

___

### moveTo

▸ **moveTo**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17307

___

### open

▸ **open**(`url?`, `target?`, `features?`): [`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

#### Parameters

| Name | Type |
| :------ | :------ |
| `url?` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |
| `target?` | `string` |
| `features?` | `string` |

#### Returns

[`Window`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#window)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17308

___

### postMessage

▸ **postMessage**(`message`, `targetOrigin`, `transfer?`): `void`

Posts a message to the given window. Messages can be structured objects, e.g. nested objects and arrays, can contain JavaScript values (strings, numbers, Date objects, etc), and can contain certain data objects such as File Blob, FileList, and ArrayBuffer objects.

Objects listed in the transfer member of options are transferred, not just cloned, meaning that they are no longer usable on the sending side.

A target origin can be specified using the targetOrigin member of options. If not provided, it defaults to "/". This default restricts the message to same-origin targets only.

If the origin of the target window doesn't match the given target origin, the message is discarded, to avoid information leakage. To send the message to the target regardless of origin, set the target origin to "*".

Throws a "DataCloneError" DOMException if transfer array contains duplicate objects or if message could not be cloned.

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `targetOrigin` | `string` |
| `transfer?` | [`Transferable`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#transferable)[] |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17320

▸ **postMessage**(`message`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `options?` | [`WindowPostMessageOptions`](akashaproject_ui_awf_testing_utils._internal_.WindowPostMessageOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17321

___

### print

▸ **print**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17322

___

### prompt

▸ **prompt**(`message?`, `_default?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `string` |
| `_default?` | `string` |

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17323

___

### queueMicrotask

▸ **queueMicrotask**(`callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | [`VoidFunction`](akashaproject_ui_awf_testing_utils._internal_.VoidFunction.md) |

#### Returns

`void`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[queueMicrotask](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#queuemicrotask)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17416

___

### releaseEvents

▸ **releaseEvents**(): `void`

**`deprecated`**

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17325

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`WindowEventMap`](akashaproject_ui_awf_testing_utils._internal_.WindowEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`WindowEventMap`](akashaproject_ui_awf_testing_utils._internal_.WindowEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[removeEventListener](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#removeeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17341

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

[WindowEventHandlers](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md).[removeEventListener](akashaproject_ui_awf_testing_utils._internal_.WindowEventHandlers.md#removeeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17342

___

### requestAnimationFrame

▸ **requestAnimationFrame**(`callback`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | [`FrameRequestCallback`](akashaproject_ui_awf_testing_utils._internal_.FrameRequestCallback.md) |

#### Returns

`number`

#### Inherited from

[AnimationFrameProvider](akashaproject_ui_awf_testing_utils._internal_.AnimationFrameProvider.md).[requestAnimationFrame](akashaproject_ui_awf_testing_utils._internal_.AnimationFrameProvider.md#requestanimationframe)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2065

___

### requestIdleCallback

▸ **requestIdleCallback**(`callback`, `options?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | [`IdleRequestCallback`](akashaproject_ui_awf_testing_utils._internal_.IdleRequestCallback.md) |
| `options?` | [`IdleRequestOptions`](akashaproject_ui_awf_testing_utils._internal_.IdleRequestOptions.md) |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17326

___

### resizeBy

▸ **resizeBy**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17327

___

### resizeTo

▸ **resizeTo**(`width`, `height`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `width` | `number` |
| `height` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17328

___

### scroll

▸ **scroll**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17329

▸ **scroll**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17330

___

### scrollBy

▸ **scrollBy**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17331

▸ **scrollBy**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17332

___

### scrollTo

▸ **scrollTo**(`options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`ScrollToOptions`](akashaproject_ui_awf_testing_utils._internal_.ScrollToOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17333

▸ **scrollTo**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17334

___

### setInterval

▸ **setInterval**(`handler`, `timeout?`, ...`arguments`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | [`TimerHandler`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#timerhandler) |
| `timeout?` | `number` |
| `...arguments` | `any`[] |

#### Returns

`number`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[setInterval](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#setinterval)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17417

___

### setTimeout

▸ **setTimeout**(`handler`, `timeout?`, ...`arguments`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | [`TimerHandler`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#timerhandler) |
| `timeout?` | `number` |
| `...arguments` | `any`[] |

#### Returns

`number`

#### Inherited from

[WindowOrWorkerGlobalScope](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md).[setTimeout](akashaproject_ui_awf_testing_utils._internal_.WindowOrWorkerGlobalScope.md#settimeout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17418

___

### stop

▸ **stop**(): `void`

Cancels the document load.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:17338
