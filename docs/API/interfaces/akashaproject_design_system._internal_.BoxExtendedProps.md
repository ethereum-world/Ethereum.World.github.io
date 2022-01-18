[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / BoxExtendedProps

# Interface: BoxExtendedProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).BoxExtendedProps

## Hierarchy

- [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md)

- [`Omit`](../modules/akashaproject_design_system._internal_.md#omit)<`JSX.IntrinsicElements`[``"div"``], keyof [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md)\>

  ↳ **`BoxExtendedProps`**

## Table of contents

### Properties

- [a11yTitle](akashaproject_design_system._internal_.BoxExtendedProps.md#a11ytitle)
- [about](akashaproject_design_system._internal_.BoxExtendedProps.md#about)
- [accessKey](akashaproject_design_system._internal_.BoxExtendedProps.md#accesskey)
- [align](akashaproject_design_system._internal_.BoxExtendedProps.md#align)
- [alignContent](akashaproject_design_system._internal_.BoxExtendedProps.md#aligncontent)
- [alignSelf](akashaproject_design_system._internal_.BoxExtendedProps.md#alignself)
- [animation](akashaproject_design_system._internal_.BoxExtendedProps.md#animation)
- [aria-activedescendant](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-activedescendant)
- [aria-atomic](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-atomic)
- [aria-autocomplete](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-autocomplete)
- [aria-busy](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-busy)
- [aria-checked](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-checked)
- [aria-colcount](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-colcount)
- [aria-colindex](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-colindex)
- [aria-colspan](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-colspan)
- [aria-controls](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-controls)
- [aria-current](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-current)
- [aria-describedby](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-describedby)
- [aria-details](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-details)
- [aria-disabled](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-disabled)
- [aria-dropeffect](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-dropeffect)
- [aria-errormessage](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-errormessage)
- [aria-expanded](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-expanded)
- [aria-flowto](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-flowto)
- [aria-grabbed](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-grabbed)
- [aria-haspopup](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-haspopup)
- [aria-hidden](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-hidden)
- [aria-invalid](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-invalid)
- [aria-keyshortcuts](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-keyshortcuts)
- [aria-label](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-label)
- [aria-labelledby](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-labelledby)
- [aria-level](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-level)
- [aria-live](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-live)
- [aria-modal](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-modal)
- [aria-multiline](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-multiline)
- [aria-multiselectable](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-multiselectable)
- [aria-orientation](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-orientation)
- [aria-owns](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-owns)
- [aria-placeholder](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-placeholder)
- [aria-posinset](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-posinset)
- [aria-pressed](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-pressed)
- [aria-readonly](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-readonly)
- [aria-relevant](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-relevant)
- [aria-required](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-required)
- [aria-roledescription](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-roledescription)
- [aria-rowcount](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-rowcount)
- [aria-rowindex](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-rowindex)
- [aria-rowspan](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-rowspan)
- [aria-selected](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-selected)
- [aria-setsize](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-setsize)
- [aria-sort](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-sort)
- [aria-valuemax](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-valuemax)
- [aria-valuemin](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-valuemin)
- [aria-valuenow](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-valuenow)
- [aria-valuetext](akashaproject_design_system._internal_.BoxExtendedProps.md#aria-valuetext)
- [as](akashaproject_design_system._internal_.BoxExtendedProps.md#as)
- [autoCapitalize](akashaproject_design_system._internal_.BoxExtendedProps.md#autocapitalize)
- [autoCorrect](akashaproject_design_system._internal_.BoxExtendedProps.md#autocorrect)
- [autoSave](akashaproject_design_system._internal_.BoxExtendedProps.md#autosave)
- [background](akashaproject_design_system._internal_.BoxExtendedProps.md#background)
- [basis](akashaproject_design_system._internal_.BoxExtendedProps.md#basis)
- [border](akashaproject_design_system._internal_.BoxExtendedProps.md#border)
- [children](akashaproject_design_system._internal_.BoxExtendedProps.md#children)
- [className](akashaproject_design_system._internal_.BoxExtendedProps.md#classname)
- [color](akashaproject_design_system._internal_.BoxExtendedProps.md#color)
- [contentEditable](akashaproject_design_system._internal_.BoxExtendedProps.md#contenteditable)
- [contextMenu](akashaproject_design_system._internal_.BoxExtendedProps.md#contextmenu)
- [css](akashaproject_design_system._internal_.BoxExtendedProps.md#css)
- [dangerouslySetInnerHTML](akashaproject_design_system._internal_.BoxExtendedProps.md#dangerouslysetinnerhtml)
- [datatype](akashaproject_design_system._internal_.BoxExtendedProps.md#datatype)
- [defaultChecked](akashaproject_design_system._internal_.BoxExtendedProps.md#defaultchecked)
- [defaultValue](akashaproject_design_system._internal_.BoxExtendedProps.md#defaultvalue)
- [dir](akashaproject_design_system._internal_.BoxExtendedProps.md#dir)
- [direction](akashaproject_design_system._internal_.BoxExtendedProps.md#direction)
- [draggable](akashaproject_design_system._internal_.BoxExtendedProps.md#draggable)
- [elevation](akashaproject_design_system._internal_.BoxExtendedProps.md#elevation)
- [fill](akashaproject_design_system._internal_.BoxExtendedProps.md#fill)
- [flex](akashaproject_design_system._internal_.BoxExtendedProps.md#flex)
- [focusIndicator](akashaproject_design_system._internal_.BoxExtendedProps.md#focusindicator)
- [gap](akashaproject_design_system._internal_.BoxExtendedProps.md#gap)
- [gridArea](akashaproject_design_system._internal_.BoxExtendedProps.md#gridarea)
- [height](akashaproject_design_system._internal_.BoxExtendedProps.md#height)
- [hidden](akashaproject_design_system._internal_.BoxExtendedProps.md#hidden)
- [hoverIndicator](akashaproject_design_system._internal_.BoxExtendedProps.md#hoverindicator)
- [id](akashaproject_design_system._internal_.BoxExtendedProps.md#id)
- [inlist](akashaproject_design_system._internal_.BoxExtendedProps.md#inlist)
- [inputMode](akashaproject_design_system._internal_.BoxExtendedProps.md#inputmode)
- [is](akashaproject_design_system._internal_.BoxExtendedProps.md#is)
- [itemID](akashaproject_design_system._internal_.BoxExtendedProps.md#itemid)
- [itemProp](akashaproject_design_system._internal_.BoxExtendedProps.md#itemprop)
- [itemRef](akashaproject_design_system._internal_.BoxExtendedProps.md#itemref)
- [itemScope](akashaproject_design_system._internal_.BoxExtendedProps.md#itemscope)
- [itemType](akashaproject_design_system._internal_.BoxExtendedProps.md#itemtype)
- [justify](akashaproject_design_system._internal_.BoxExtendedProps.md#justify)
- [key](akashaproject_design_system._internal_.BoxExtendedProps.md#key)
- [lang](akashaproject_design_system._internal_.BoxExtendedProps.md#lang)
- [margin](akashaproject_design_system._internal_.BoxExtendedProps.md#margin)
- [onAbort](akashaproject_design_system._internal_.BoxExtendedProps.md#onabort)
- [onAbortCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onabortcapture)
- [onAnimationEnd](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationend)
- [onAnimationEndCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationendcapture)
- [onAnimationIteration](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationiteration)
- [onAnimationIterationCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationiterationcapture)
- [onAnimationStart](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationstart)
- [onAnimationStartCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onanimationstartcapture)
- [onAuxClick](akashaproject_design_system._internal_.BoxExtendedProps.md#onauxclick)
- [onAuxClickCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onauxclickcapture)
- [onBeforeInput](akashaproject_design_system._internal_.BoxExtendedProps.md#onbeforeinput)
- [onBeforeInputCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onbeforeinputcapture)
- [onBlur](akashaproject_design_system._internal_.BoxExtendedProps.md#onblur)
- [onBlurCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onblurcapture)
- [onCanPlay](akashaproject_design_system._internal_.BoxExtendedProps.md#oncanplay)
- [onCanPlayCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncanplaycapture)
- [onCanPlayThrough](akashaproject_design_system._internal_.BoxExtendedProps.md#oncanplaythrough)
- [onCanPlayThroughCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncanplaythroughcapture)
- [onChange](akashaproject_design_system._internal_.BoxExtendedProps.md#onchange)
- [onChangeCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onchangecapture)
- [onClickCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onclickcapture)
- [onCompositionEnd](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionend)
- [onCompositionEndCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionendcapture)
- [onCompositionStart](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionstart)
- [onCompositionStartCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionstartcapture)
- [onCompositionUpdate](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionupdate)
- [onCompositionUpdateCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncompositionupdatecapture)
- [onContextMenu](akashaproject_design_system._internal_.BoxExtendedProps.md#oncontextmenu)
- [onContextMenuCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncontextmenucapture)
- [onCopy](akashaproject_design_system._internal_.BoxExtendedProps.md#oncopy)
- [onCopyCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncopycapture)
- [onCut](akashaproject_design_system._internal_.BoxExtendedProps.md#oncut)
- [onCutCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oncutcapture)
- [onDoubleClick](akashaproject_design_system._internal_.BoxExtendedProps.md#ondoubleclick)
- [onDoubleClickCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondoubleclickcapture)
- [onDrag](akashaproject_design_system._internal_.BoxExtendedProps.md#ondrag)
- [onDragCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragcapture)
- [onDragEnd](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragend)
- [onDragEndCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragendcapture)
- [onDragEnter](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragenter)
- [onDragEnterCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragentercapture)
- [onDragExit](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragexit)
- [onDragExitCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragexitcapture)
- [onDragLeave](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragleave)
- [onDragLeaveCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragleavecapture)
- [onDragOver](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragover)
- [onDragOverCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragovercapture)
- [onDragStart](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragstart)
- [onDragStartCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondragstartcapture)
- [onDrop](akashaproject_design_system._internal_.BoxExtendedProps.md#ondrop)
- [onDropCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondropcapture)
- [onDurationChange](akashaproject_design_system._internal_.BoxExtendedProps.md#ondurationchange)
- [onDurationChangeCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ondurationchangecapture)
- [onEmptied](akashaproject_design_system._internal_.BoxExtendedProps.md#onemptied)
- [onEmptiedCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onemptiedcapture)
- [onEncrypted](akashaproject_design_system._internal_.BoxExtendedProps.md#onencrypted)
- [onEncryptedCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onencryptedcapture)
- [onEnded](akashaproject_design_system._internal_.BoxExtendedProps.md#onended)
- [onEndedCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onendedcapture)
- [onError](akashaproject_design_system._internal_.BoxExtendedProps.md#onerror)
- [onErrorCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onerrorcapture)
- [onFocus](akashaproject_design_system._internal_.BoxExtendedProps.md#onfocus)
- [onFocusCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onfocuscapture)
- [onGotPointerCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ongotpointercapture)
- [onGotPointerCaptureCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ongotpointercapturecapture)
- [onInput](akashaproject_design_system._internal_.BoxExtendedProps.md#oninput)
- [onInputCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oninputcapture)
- [onInvalid](akashaproject_design_system._internal_.BoxExtendedProps.md#oninvalid)
- [onInvalidCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#oninvalidcapture)
- [onKeyDown](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeydown)
- [onKeyDownCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeydowncapture)
- [onKeyPress](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeypress)
- [onKeyPressCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeypresscapture)
- [onKeyUp](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeyup)
- [onKeyUpCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onkeyupcapture)
- [onLoad](akashaproject_design_system._internal_.BoxExtendedProps.md#onload)
- [onLoadCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadcapture)
- [onLoadStart](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadstart)
- [onLoadStartCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadstartcapture)
- [onLoadedData](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadeddata)
- [onLoadedDataCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadeddatacapture)
- [onLoadedMetadata](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadedmetadata)
- [onLoadedMetadataCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onloadedmetadatacapture)
- [onLostPointerCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onlostpointercapture)
- [onLostPointerCaptureCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onlostpointercapturecapture)
- [onMouseDown](akashaproject_design_system._internal_.BoxExtendedProps.md#onmousedown)
- [onMouseDownCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onmousedowncapture)
- [onMouseEnter](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseenter)
- [onMouseLeave](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseleave)
- [onMouseMove](akashaproject_design_system._internal_.BoxExtendedProps.md#onmousemove)
- [onMouseMoveCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onmousemovecapture)
- [onMouseOut](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseout)
- [onMouseOutCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseoutcapture)
- [onMouseOver](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseover)
- [onMouseOverCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseovercapture)
- [onMouseUp](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseup)
- [onMouseUpCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onmouseupcapture)
- [onPaste](akashaproject_design_system._internal_.BoxExtendedProps.md#onpaste)
- [onPasteCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpastecapture)
- [onPause](akashaproject_design_system._internal_.BoxExtendedProps.md#onpause)
- [onPauseCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpausecapture)
- [onPlay](akashaproject_design_system._internal_.BoxExtendedProps.md#onplay)
- [onPlayCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onplaycapture)
- [onPlaying](akashaproject_design_system._internal_.BoxExtendedProps.md#onplaying)
- [onPlayingCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onplayingcapture)
- [onPointerCancel](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointercancel)
- [onPointerCancelCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointercancelcapture)
- [onPointerDown](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerdown)
- [onPointerDownCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerdowncapture)
- [onPointerEnter](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerenter)
- [onPointerEnterCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerentercapture)
- [onPointerLeave](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerleave)
- [onPointerLeaveCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerleavecapture)
- [onPointerMove](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointermove)
- [onPointerMoveCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointermovecapture)
- [onPointerOut](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerout)
- [onPointerOutCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointeroutcapture)
- [onPointerOver](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerover)
- [onPointerOverCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerovercapture)
- [onPointerUp](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerup)
- [onPointerUpCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onpointerupcapture)
- [onProgress](akashaproject_design_system._internal_.BoxExtendedProps.md#onprogress)
- [onProgressCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onprogresscapture)
- [onRateChange](akashaproject_design_system._internal_.BoxExtendedProps.md#onratechange)
- [onRateChangeCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onratechangecapture)
- [onReset](akashaproject_design_system._internal_.BoxExtendedProps.md#onreset)
- [onResetCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onresetcapture)
- [onScroll](akashaproject_design_system._internal_.BoxExtendedProps.md#onscroll)
- [onScrollCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onscrollcapture)
- [onSeeked](akashaproject_design_system._internal_.BoxExtendedProps.md#onseeked)
- [onSeekedCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onseekedcapture)
- [onSeeking](akashaproject_design_system._internal_.BoxExtendedProps.md#onseeking)
- [onSeekingCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onseekingcapture)
- [onSelect](akashaproject_design_system._internal_.BoxExtendedProps.md#onselect)
- [onSelectCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onselectcapture)
- [onStalled](akashaproject_design_system._internal_.BoxExtendedProps.md#onstalled)
- [onStalledCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onstalledcapture)
- [onSubmit](akashaproject_design_system._internal_.BoxExtendedProps.md#onsubmit)
- [onSubmitCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onsubmitcapture)
- [onSuspend](akashaproject_design_system._internal_.BoxExtendedProps.md#onsuspend)
- [onSuspendCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onsuspendcapture)
- [onTimeUpdate](akashaproject_design_system._internal_.BoxExtendedProps.md#ontimeupdate)
- [onTimeUpdateCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontimeupdatecapture)
- [onTouchCancel](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchcancel)
- [onTouchCancelCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchcancelcapture)
- [onTouchEnd](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchend)
- [onTouchEndCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchendcapture)
- [onTouchMove](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchmove)
- [onTouchMoveCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchmovecapture)
- [onTouchStart](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchstart)
- [onTouchStartCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontouchstartcapture)
- [onTransitionEnd](akashaproject_design_system._internal_.BoxExtendedProps.md#ontransitionend)
- [onTransitionEndCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#ontransitionendcapture)
- [onVolumeChange](akashaproject_design_system._internal_.BoxExtendedProps.md#onvolumechange)
- [onVolumeChangeCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onvolumechangecapture)
- [onWaiting](akashaproject_design_system._internal_.BoxExtendedProps.md#onwaiting)
- [onWaitingCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onwaitingcapture)
- [onWheel](akashaproject_design_system._internal_.BoxExtendedProps.md#onwheel)
- [onWheelCapture](akashaproject_design_system._internal_.BoxExtendedProps.md#onwheelcapture)
- [overflow](akashaproject_design_system._internal_.BoxExtendedProps.md#overflow)
- [pad](akashaproject_design_system._internal_.BoxExtendedProps.md#pad)
- [placeholder](akashaproject_design_system._internal_.BoxExtendedProps.md#placeholder)
- [prefix](akashaproject_design_system._internal_.BoxExtendedProps.md#prefix)
- [property](akashaproject_design_system._internal_.BoxExtendedProps.md#property)
- [radioGroup](akashaproject_design_system._internal_.BoxExtendedProps.md#radiogroup)
- [ref](akashaproject_design_system._internal_.BoxExtendedProps.md#ref)
- [resource](akashaproject_design_system._internal_.BoxExtendedProps.md#resource)
- [responsive](akashaproject_design_system._internal_.BoxExtendedProps.md#responsive)
- [results](akashaproject_design_system._internal_.BoxExtendedProps.md#results)
- [role](akashaproject_design_system._internal_.BoxExtendedProps.md#role)
- [round](akashaproject_design_system._internal_.BoxExtendedProps.md#round)
- [security](akashaproject_design_system._internal_.BoxExtendedProps.md#security)
- [slot](akashaproject_design_system._internal_.BoxExtendedProps.md#slot)
- [spellCheck](akashaproject_design_system._internal_.BoxExtendedProps.md#spellcheck)
- [style](akashaproject_design_system._internal_.BoxExtendedProps.md#style)
- [suppressContentEditableWarning](akashaproject_design_system._internal_.BoxExtendedProps.md#suppresscontenteditablewarning)
- [suppressHydrationWarning](akashaproject_design_system._internal_.BoxExtendedProps.md#suppresshydrationwarning)
- [tabIndex](akashaproject_design_system._internal_.BoxExtendedProps.md#tabindex)
- [tag](akashaproject_design_system._internal_.BoxExtendedProps.md#tag)
- [title](akashaproject_design_system._internal_.BoxExtendedProps.md#title)
- [translate](akashaproject_design_system._internal_.BoxExtendedProps.md#translate)
- [typeof](akashaproject_design_system._internal_.BoxExtendedProps.md#typeof)
- [unselectable](akashaproject_design_system._internal_.BoxExtendedProps.md#unselectable)
- [vocab](akashaproject_design_system._internal_.BoxExtendedProps.md#vocab)
- [width](akashaproject_design_system._internal_.BoxExtendedProps.md#width)
- [wrap](akashaproject_design_system._internal_.BoxExtendedProps.md#wrap)

### Methods

- [onClick](akashaproject_design_system._internal_.BoxExtendedProps.md#onclick)

## Properties

### a11yTitle

• `Optional` **a11yTitle**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[a11yTitle](akashaproject_design_system._internal_.BoxProps.md#a11ytitle)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:24

___

### about

• `Optional` **about**: `string`

#### Inherited from

Omit.about

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1854

___

### accessKey

• `Optional` **accessKey**: `string`

#### Inherited from

Omit.accessKey

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1830

___

### align

• `Optional` **align**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[align](akashaproject_design_system._internal_.BoxProps.md#align)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:28

___

### alignContent

• `Optional` **alignContent**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[alignContent](akashaproject_design_system._internal_.BoxProps.md#aligncontent)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:29

___

### alignSelf

• `Optional` **alignSelf**: [`AlignSelfType`](../modules/akashaproject_design_system._internal_.md#alignselftype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[alignSelf](akashaproject_design_system._internal_.BoxProps.md#alignself)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:25

___

### animation

• `Optional` **animation**: ``"zoomIn"`` \| ``"zoomOut"`` \| ``"fadeIn"`` \| ``"fadeOut"`` \| ``"jiggle"`` \| ``"pulse"`` \| ``"rotateLeft"`` \| ``"rotateRight"`` \| ``"slideUp"`` \| ``"slideDown"`` \| ``"slideLeft"`` \| ``"slideRight"`` \| { `delay?`: `number` ; `duration?`: `number` ; `size?`: ``"small"`` \| ``"xsmall"`` \| ``"medium"`` \| ``"large"`` \| ``"xlarge"`` ; `type?`: ``"zoomIn"`` \| ``"zoomOut"`` \| ``"fadeIn"`` \| ``"fadeOut"`` \| ``"jiggle"`` \| ``"pulse"`` \| ``"rotateLeft"`` \| ``"rotateRight"`` \| ``"slideUp"`` \| ``"slideDown"`` \| ``"slideLeft"`` \| ``"slideRight"``  } \| (``"zoomIn"`` \| ``"zoomOut"`` \| ``"fadeIn"`` \| ``"fadeOut"`` \| ``"jiggle"`` \| ``"pulse"`` \| ``"slideUp"`` \| ``"slideDown"`` \| ``"slideLeft"`` \| ``"slideRight"`` \| { `delay?`: `number` ; `duration?`: `number` ; `size?`: ``"small"`` \| ``"xsmall"`` \| ``"medium"`` \| ``"large"`` \| ``"xlarge"`` ; `type?`: ``"zoomIn"`` \| ``"zoomOut"`` \| ``"fadeIn"`` \| ``"fadeOut"`` \| ``"jiggle"`` \| ``"pulse"`` \| ``"slideUp"`` \| ``"slideDown"`` \| ``"slideLeft"`` \| ``"slideRight"``  })[]

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[animation](akashaproject_design_system._internal_.BoxProps.md#animation)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:30

___

### aria-activedescendant

• `Optional` **aria-activedescendant**: `string`

Identifies the currently active element when DOM focus is on a composite widget, textbox, group, or application.

#### Inherited from

Omit.aria-activedescendant

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1564

___

### aria-atomic

• `Optional` **aria-atomic**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates whether assistive technologies will present all, or only parts of, the changed region based on the change notifications defined by the aria-relevant attribute.

#### Inherited from

Omit.aria-atomic

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1566

___

### aria-autocomplete

• `Optional` **aria-autocomplete**: ``"list"`` \| ``"none"`` \| ``"inline"`` \| ``"both"``

Indicates whether inputting text could trigger display of one or more predictions of the user's intended value for an input and specifies how predictions would be
presented if they are made.

#### Inherited from

Omit.aria-autocomplete

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1571

___

### aria-busy

• `Optional` **aria-busy**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates an element is being modified and that assistive technologies MAY want to wait until the modifications are complete before exposing them to the user.

#### Inherited from

Omit.aria-busy

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1573

___

### aria-checked

• `Optional` **aria-checked**: `boolean` \| ``"true"`` \| ``"false"`` \| ``"mixed"``

Indicates the current "checked" state of checkboxes, radio buttons, and other widgets.

**`see`** aria-pressed @see aria-selected.

#### Inherited from

Omit.aria-checked

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1578

___

### aria-colcount

• `Optional` **aria-colcount**: `number`

Defines the total number of columns in a table, grid, or treegrid.

**`see`** aria-colindex.

#### Inherited from

Omit.aria-colcount

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1583

___

### aria-colindex

• `Optional` **aria-colindex**: `number`

Defines an element's column index or position with respect to the total number of columns within a table, grid, or treegrid.

**`see`** aria-colcount @see aria-colspan.

#### Inherited from

Omit.aria-colindex

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1588

___

### aria-colspan

• `Optional` **aria-colspan**: `number`

Defines the number of columns spanned by a cell or gridcell within a table, grid, or treegrid.

**`see`** aria-colindex @see aria-rowspan.

#### Inherited from

Omit.aria-colspan

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1593

___

### aria-controls

• `Optional` **aria-controls**: `string`

Identifies the element (or elements) whose contents or presence are controlled by the current element.

**`see`** aria-owns.

#### Inherited from

Omit.aria-controls

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1598

___

### aria-current

• `Optional` **aria-current**: `boolean` \| ``"time"`` \| ``"true"`` \| ``"false"`` \| ``"step"`` \| ``"date"`` \| ``"page"`` \| ``"location"``

Indicates the element that represents the current item within a container or set of related elements.

#### Inherited from

Omit.aria-current

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1600

___

### aria-describedby

• `Optional` **aria-describedby**: `string`

Identifies the element (or elements) that describes the object.

**`see`** aria-labelledby

#### Inherited from

Omit.aria-describedby

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1605

___

### aria-details

• `Optional` **aria-details**: `string`

Identifies the element that provides a detailed, extended description for the object.

**`see`** aria-describedby.

#### Inherited from

Omit.aria-details

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1610

___

### aria-disabled

• `Optional` **aria-disabled**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates that the element is perceivable but disabled, so it is not editable or otherwise operable.

**`see`** aria-hidden @see aria-readonly.

#### Inherited from

Omit.aria-disabled

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1615

___

### aria-dropeffect

• `Optional` **aria-dropeffect**: ``"copy"`` \| ``"link"`` \| ``"none"`` \| ``"execute"`` \| ``"move"`` \| ``"popup"``

Indicates what functions can be performed when a dragged object is released on the drop target.

**`deprecated`** in ARIA 1.1

#### Inherited from

Omit.aria-dropeffect

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1620

___

### aria-errormessage

• `Optional` **aria-errormessage**: `string`

Identifies the element that provides an error message for the object.

**`see`** aria-invalid @see aria-describedby.

#### Inherited from

Omit.aria-errormessage

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1625

___

### aria-expanded

• `Optional` **aria-expanded**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates whether the element, or another grouping element it controls, is currently expanded or collapsed.

#### Inherited from

Omit.aria-expanded

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1627

___

### aria-flowto

• `Optional` **aria-flowto**: `string`

Identifies the next element (or elements) in an alternate reading order of content which, at the user's discretion,
allows assistive technology to override the general default of reading in document source order.

#### Inherited from

Omit.aria-flowto

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1632

___

### aria-grabbed

• `Optional` **aria-grabbed**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates an element's "grabbed" state in a drag-and-drop operation.

**`deprecated`** in ARIA 1.1

#### Inherited from

Omit.aria-grabbed

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1637

___

### aria-haspopup

• `Optional` **aria-haspopup**: `boolean` \| ``"menu"`` \| ``"dialog"`` \| ``"grid"`` \| ``"listbox"`` \| ``"tree"`` \| ``"true"`` \| ``"false"``

Indicates the availability and type of interactive popup element, such as menu or dialog, that can be triggered by an element.

#### Inherited from

Omit.aria-haspopup

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1639

___

### aria-hidden

• `Optional` **aria-hidden**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates whether the element is exposed to an accessibility API.

**`see`** aria-disabled.

#### Inherited from

Omit.aria-hidden

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1644

___

### aria-invalid

• `Optional` **aria-invalid**: `boolean` \| ``"true"`` \| ``"false"`` \| ``"grammar"`` \| ``"spelling"``

Indicates the entered value does not conform to the format expected by the application.

**`see`** aria-errormessage.

#### Inherited from

Omit.aria-invalid

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1649

___

### aria-keyshortcuts

• `Optional` **aria-keyshortcuts**: `string`

Indicates keyboard shortcuts that an author has implemented to activate or give focus to an element.

#### Inherited from

Omit.aria-keyshortcuts

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1651

___

### aria-label

• `Optional` **aria-label**: `string`

Defines a string value that labels the current element.

**`see`** aria-labelledby.

#### Inherited from

Omit.aria-label

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1656

___

### aria-labelledby

• `Optional` **aria-labelledby**: `string`

Identifies the element (or elements) that labels the current element.

**`see`** aria-describedby.

#### Inherited from

Omit.aria-labelledby

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1661

___

### aria-level

• `Optional` **aria-level**: `number`

Defines the hierarchical level of an element within a structure.

#### Inherited from

Omit.aria-level

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1663

___

### aria-live

• `Optional` **aria-live**: ``"off"`` \| ``"assertive"`` \| ``"polite"``

Indicates that an element will be updated, and describes the types of updates the user agents, assistive technologies, and user can expect from the live region.

#### Inherited from

Omit.aria-live

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1665

___

### aria-modal

• `Optional` **aria-modal**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates whether an element is modal when displayed.

#### Inherited from

Omit.aria-modal

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1667

___

### aria-multiline

• `Optional` **aria-multiline**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates whether a text box accepts multiple lines of input or only a single line.

#### Inherited from

Omit.aria-multiline

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1669

___

### aria-multiselectable

• `Optional` **aria-multiselectable**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates that the user may select more than one item from the current selectable descendants.

#### Inherited from

Omit.aria-multiselectable

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1671

___

### aria-orientation

• `Optional` **aria-orientation**: ``"horizontal"`` \| ``"vertical"``

Indicates whether the element's orientation is horizontal, vertical, or unknown/ambiguous.

#### Inherited from

Omit.aria-orientation

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1673

___

### aria-owns

• `Optional` **aria-owns**: `string`

Identifies an element (or elements) in order to define a visual, functional, or contextual parent/child relationship
between DOM elements where the DOM hierarchy cannot be used to represent the relationship.

**`see`** aria-controls.

#### Inherited from

Omit.aria-owns

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1679

___

### aria-placeholder

• `Optional` **aria-placeholder**: `string`

Defines a short hint (a word or short phrase) intended to aid the user with data entry when the control has no value.
A hint could be a sample value or a brief description of the expected format.

#### Inherited from

Omit.aria-placeholder

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1684

___

### aria-posinset

• `Optional` **aria-posinset**: `number`

Defines an element's number or position in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM.

**`see`** aria-setsize.

#### Inherited from

Omit.aria-posinset

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1689

___

### aria-pressed

• `Optional` **aria-pressed**: `boolean` \| ``"true"`` \| ``"false"`` \| ``"mixed"``

Indicates the current "pressed" state of toggle buttons.

**`see`** aria-checked @see aria-selected.

#### Inherited from

Omit.aria-pressed

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1694

___

### aria-readonly

• `Optional` **aria-readonly**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates that the element is not editable, but is otherwise operable.

**`see`** aria-disabled.

#### Inherited from

Omit.aria-readonly

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1699

___

### aria-relevant

• `Optional` **aria-relevant**: ``"text"`` \| ``"additions"`` \| ``"additions removals"`` \| ``"additions text"`` \| ``"all"`` \| ``"removals"`` \| ``"removals additions"`` \| ``"removals text"`` \| ``"text additions"`` \| ``"text removals"``

Indicates what notifications the user agent will trigger when the accessibility tree within a live region is modified.

**`see`** aria-atomic.

#### Inherited from

Omit.aria-relevant

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1704

___

### aria-required

• `Optional` **aria-required**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates that user input is required on the element before a form may be submitted.

#### Inherited from

Omit.aria-required

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1706

___

### aria-roledescription

• `Optional` **aria-roledescription**: `string`

Defines a human-readable, author-localized description for the role of an element.

#### Inherited from

Omit.aria-roledescription

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1708

___

### aria-rowcount

• `Optional` **aria-rowcount**: `number`

Defines the total number of rows in a table, grid, or treegrid.

**`see`** aria-rowindex.

#### Inherited from

Omit.aria-rowcount

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1713

___

### aria-rowindex

• `Optional` **aria-rowindex**: `number`

Defines an element's row index or position with respect to the total number of rows within a table, grid, or treegrid.

**`see`** aria-rowcount @see aria-rowspan.

#### Inherited from

Omit.aria-rowindex

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1718

___

### aria-rowspan

• `Optional` **aria-rowspan**: `number`

Defines the number of rows spanned by a cell or gridcell within a table, grid, or treegrid.

**`see`** aria-rowindex @see aria-colspan.

#### Inherited from

Omit.aria-rowspan

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1723

___

### aria-selected

• `Optional` **aria-selected**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

Indicates the current "selected" state of various widgets.

**`see`** aria-checked @see aria-pressed.

#### Inherited from

Omit.aria-selected

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1728

___

### aria-setsize

• `Optional` **aria-setsize**: `number`

Defines the number of items in the current set of listitems or treeitems. Not required if all elements in the set are present in the DOM.

**`see`** aria-posinset.

#### Inherited from

Omit.aria-setsize

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1733

___

### aria-sort

• `Optional` **aria-sort**: ``"none"`` \| ``"ascending"`` \| ``"descending"`` \| ``"other"``

Indicates if items in a table or grid are sorted in ascending or descending order.

#### Inherited from

Omit.aria-sort

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1735

___

### aria-valuemax

• `Optional` **aria-valuemax**: `number`

Defines the maximum allowed value for a range widget.

#### Inherited from

Omit.aria-valuemax

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1737

___

### aria-valuemin

• `Optional` **aria-valuemin**: `number`

Defines the minimum allowed value for a range widget.

#### Inherited from

Omit.aria-valuemin

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1739

___

### aria-valuenow

• `Optional` **aria-valuenow**: `number`

Defines the current value for a range widget.

**`see`** aria-valuetext.

#### Inherited from

Omit.aria-valuenow

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1744

___

### aria-valuetext

• `Optional` **aria-valuetext**: `string`

Defines the human readable text alternative of aria-valuenow for a range widget.

#### Inherited from

Omit.aria-valuetext

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1746

___

### as

• `Optional` **as**: [`PolymorphicType`](../modules/akashaproject_design_system._internal_.md#polymorphictype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[as](akashaproject_design_system._internal_.BoxProps.md#as)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:126

___

### autoCapitalize

• `Optional` **autoCapitalize**: `string`

#### Inherited from

Omit.autoCapitalize

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1864

___

### autoCorrect

• `Optional` **autoCorrect**: `string`

#### Inherited from

Omit.autoCorrect

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1865

___

### autoSave

• `Optional` **autoSave**: `string`

#### Inherited from

Omit.autoSave

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1866

___

### background

• `Optional` **background**: [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[background](akashaproject_design_system._internal_.BoxProps.md#background)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:89

___

### basis

• `Optional` **basis**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[basis](akashaproject_design_system._internal_.BoxProps.md#basis)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:90

___

### border

• `Optional` **border**: [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[border](akashaproject_design_system._internal_.BoxProps.md#border)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:91

___

### children

• `Optional` **children**: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Omit.children

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1354

___

### className

• `Optional` **className**: `string`

#### Inherited from

Omit.className

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1831

___

### color

• `Optional` **color**: `string`

#### Inherited from

Omit.color

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1867

___

### contentEditable

• `Optional` **contentEditable**: ``"inherit"`` \| [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

#### Inherited from

Omit.contentEditable

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1832

___

### contextMenu

• `Optional` **contextMenu**: `string`

#### Inherited from

Omit.contextMenu

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1833

___

### css

• `Optional` **css**: [`InterpolationWithTheme`](../modules/akashaproject_design_system._internal_.md#interpolationwiththeme)<`any`\>

#### Inherited from

Omit.css

#### Defined in

ui/design/node_modules/@emotion/core/types/index.d.ts:84

___

### dangerouslySetInnerHTML

• `Optional` **dangerouslySetInnerHTML**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `__html` | `string` |

#### Inherited from

Omit.dangerouslySetInnerHTML

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1355

___

### datatype

• `Optional` **datatype**: `string`

#### Inherited from

Omit.datatype

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1855

___

### defaultChecked

• `Optional` **defaultChecked**: `boolean`

#### Inherited from

Omit.defaultChecked

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1824

___

### defaultValue

• `Optional` **defaultValue**: `string` \| `number` \| readonly `string`[]

#### Inherited from

Omit.defaultValue

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1825

___

### dir

• `Optional` **dir**: `string`

#### Inherited from

Omit.dir

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1834

___

### direction

• `Optional` **direction**: [`DirectionType`](../modules/akashaproject_design_system._internal_.md#directiontype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[direction](akashaproject_design_system._internal_.BoxProps.md#direction)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:92

___

### draggable

• `Optional` **draggable**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

#### Inherited from

Omit.draggable

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1835

___

### elevation

• `Optional` **elevation**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[elevation](akashaproject_design_system._internal_.BoxProps.md#elevation)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:93

___

### fill

• `Optional` **fill**: [`FillType`](../modules/akashaproject_design_system._internal_.md#filltype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[fill](akashaproject_design_system._internal_.BoxProps.md#fill)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:95

___

### flex

• `Optional` **flex**: `boolean` \| ``"grow"`` \| ``"shrink"`` \| { `grow?`: `number` ; `shrink?`: `number`  }

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[flex](akashaproject_design_system._internal_.BoxProps.md#flex)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:94

___

### focusIndicator

• `Optional` **focusIndicator**: `boolean`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[focusIndicator](akashaproject_design_system._internal_.BoxProps.md#focusindicator)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:96

___

### gap

• `Optional` **gap**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[gap](akashaproject_design_system._internal_.BoxProps.md#gap)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:97

___

### gridArea

• `Optional` **gridArea**: `string`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[gridArea](akashaproject_design_system._internal_.BoxProps.md#gridarea)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:26

___

### height

• `Optional` **height**: [`HeightType`](../modules/akashaproject_design_system._internal_.md#heighttype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[height](akashaproject_design_system._internal_.BoxProps.md#height)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:98

___

### hidden

• `Optional` **hidden**: `boolean`

#### Inherited from

Omit.hidden

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1836

___

### hoverIndicator

• `Optional` **hoverIndicator**: `boolean` \| [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) \| { `background?`: [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) ; `elevation?`: `string`  }

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[hoverIndicator](akashaproject_design_system._internal_.BoxProps.md#hoverindicator)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:99

___

### id

• `Optional` **id**: `string`

#### Inherited from

Omit.id

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1837

___

### inlist

• `Optional` **inlist**: `any`

#### Inherited from

Omit.inlist

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1856

___

### inputMode

• `Optional` **inputMode**: ``"email"`` \| ``"search"`` \| ``"text"`` \| ``"none"`` \| ``"tel"`` \| ``"url"`` \| ``"numeric"`` \| ``"decimal"``

Hints at the type of data that might be entered by the user while editing the element or its contents

**`see`** https://html.spec.whatwg.org/multipage/interaction.html#input-modalities:-the-inputmode-attribute

#### Inherited from

Omit.inputMode

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1882

___

### is

• `Optional` **is**: `string`

Specify that a standard HTML element should behave like a defined custom built-in element

**`see`** https://html.spec.whatwg.org/multipage/custom-elements.html#attr-is

#### Inherited from

Omit.is

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1887

___

### itemID

• `Optional` **itemID**: `string`

#### Inherited from

Omit.itemID

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1871

___

### itemProp

• `Optional` **itemProp**: `string`

#### Inherited from

Omit.itemProp

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1868

___

### itemRef

• `Optional` **itemRef**: `string`

#### Inherited from

Omit.itemRef

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1872

___

### itemScope

• `Optional` **itemScope**: `boolean`

#### Inherited from

Omit.itemScope

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1869

___

### itemType

• `Optional` **itemType**: `string`

#### Inherited from

Omit.itemType

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1870

___

### justify

• `Optional` **justify**: ``"end"`` \| ``"start"`` \| ``"center"`` \| ``"stretch"`` \| ``"around"`` \| ``"between"`` \| ``"evenly"``

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[justify](akashaproject_design_system._internal_.BoxProps.md#justify)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:103

___

### key

• `Optional` **key**: [`Key`](../modules/akashaproject_design_system._internal_.md#key)

#### Inherited from

Omit.key

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:137

___

### lang

• `Optional` **lang**: `string`

#### Inherited from

Omit.lang

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1838

___

### margin

• `Optional` **margin**: [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[margin](akashaproject_design_system._internal_.BoxProps.md#margin)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:27

___

### onAbort

• `Optional` **onAbort**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAbort

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1410

___

### onAbortCapture

• `Optional` **onAbortCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAbortCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1411

___

### onAnimationEnd

• `Optional` **onAnimationEnd**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationEnd

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1540

___

### onAnimationEndCapture

• `Optional` **onAnimationEndCapture**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationEndCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1541

___

### onAnimationIteration

• `Optional` **onAnimationIteration**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationIteration

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1542

___

### onAnimationIterationCapture

• `Optional` **onAnimationIterationCapture**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationIterationCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1543

___

### onAnimationStart

• `Optional` **onAnimationStart**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationStart

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1538

___

### onAnimationStartCapture

• `Optional` **onAnimationStartCapture**: [`AnimationEventHandler`](../modules/akashaproject_design_system._internal_.md#animationeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAnimationStartCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1539

___

### onAuxClick

• `Optional` **onAuxClick**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAuxClick

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1456

___

### onAuxClickCapture

• `Optional` **onAuxClickCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onAuxClickCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1457

___

### onBeforeInput

• `Optional` **onBeforeInput**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onBeforeInput

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1384

___

### onBeforeInputCapture

• `Optional` **onBeforeInputCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onBeforeInputCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1385

___

### onBlur

• `Optional` **onBlur**: [`FocusEventHandler`](../modules/akashaproject_design_system._internal_.md#focuseventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onBlur

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1378

___

### onBlurCapture

• `Optional` **onBlurCapture**: [`FocusEventHandler`](../modules/akashaproject_design_system._internal_.md#focuseventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onBlurCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1379

___

### onCanPlay

• `Optional` **onCanPlay**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCanPlay

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1412

___

### onCanPlayCapture

• `Optional` **onCanPlayCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCanPlayCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1413

___

### onCanPlayThrough

• `Optional` **onCanPlayThrough**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCanPlayThrough

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1414

___

### onCanPlayThroughCapture

• `Optional` **onCanPlayThroughCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCanPlayThroughCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1415

___

### onChange

• `Optional` **onChange**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onChange

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1382

___

### onChangeCapture

• `Optional` **onChangeCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onChangeCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1383

___

### onClickCapture

• `Optional` **onClickCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onClickCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1459

___

### onCompositionEnd

• `Optional` **onCompositionEnd**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionEnd

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1368

___

### onCompositionEndCapture

• `Optional` **onCompositionEndCapture**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionEndCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1369

___

### onCompositionStart

• `Optional` **onCompositionStart**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionStart

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1370

___

### onCompositionStartCapture

• `Optional` **onCompositionStartCapture**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionStartCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1371

___

### onCompositionUpdate

• `Optional` **onCompositionUpdate**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionUpdate

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1372

___

### onCompositionUpdateCapture

• `Optional` **onCompositionUpdateCapture**: [`CompositionEventHandler`](../modules/akashaproject_design_system._internal_.md#compositioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCompositionUpdateCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1373

___

### onContextMenu

• `Optional` **onContextMenu**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onContextMenu

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1460

___

### onContextMenuCapture

• `Optional` **onContextMenuCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onContextMenuCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1461

___

### onCopy

• `Optional` **onCopy**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCopy

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1360

___

### onCopyCapture

• `Optional` **onCopyCapture**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCopyCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1361

___

### onCut

• `Optional` **onCut**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCut

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1362

___

### onCutCapture

• `Optional` **onCutCapture**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onCutCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1363

___

### onDoubleClick

• `Optional` **onDoubleClick**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDoubleClick

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1462

___

### onDoubleClickCapture

• `Optional` **onDoubleClickCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDoubleClickCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1463

___

### onDrag

• `Optional` **onDrag**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDrag

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1464

___

### onDragCapture

• `Optional` **onDragCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1465

___

### onDragEnd

• `Optional` **onDragEnd**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragEnd

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1466

___

### onDragEndCapture

• `Optional` **onDragEndCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragEndCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1467

___

### onDragEnter

• `Optional` **onDragEnter**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragEnter

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1468

___

### onDragEnterCapture

• `Optional` **onDragEnterCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragEnterCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1469

___

### onDragExit

• `Optional` **onDragExit**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragExit

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1470

___

### onDragExitCapture

• `Optional` **onDragExitCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragExitCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1471

___

### onDragLeave

• `Optional` **onDragLeave**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragLeave

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1472

___

### onDragLeaveCapture

• `Optional` **onDragLeaveCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragLeaveCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1473

___

### onDragOver

• `Optional` **onDragOver**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragOver

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1474

___

### onDragOverCapture

• `Optional` **onDragOverCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragOverCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1475

___

### onDragStart

• `Optional` **onDragStart**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragStart

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1476

___

### onDragStartCapture

• `Optional` **onDragStartCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDragStartCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1477

___

### onDrop

• `Optional` **onDrop**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDrop

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1478

___

### onDropCapture

• `Optional` **onDropCapture**: [`DragEventHandler`](../modules/akashaproject_design_system._internal_.md#drageventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDropCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1479

___

### onDurationChange

• `Optional` **onDurationChange**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDurationChange

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1416

___

### onDurationChangeCapture

• `Optional` **onDurationChangeCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onDurationChangeCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1417

___

### onEmptied

• `Optional` **onEmptied**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEmptied

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1418

___

### onEmptiedCapture

• `Optional` **onEmptiedCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEmptiedCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1419

___

### onEncrypted

• `Optional` **onEncrypted**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEncrypted

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1420

___

### onEncryptedCapture

• `Optional` **onEncryptedCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEncryptedCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1421

___

### onEnded

• `Optional` **onEnded**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEnded

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1422

___

### onEndedCapture

• `Optional` **onEndedCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onEndedCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1423

___

### onError

• `Optional` **onError**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onError

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1398

___

### onErrorCapture

• `Optional` **onErrorCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onErrorCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1399

___

### onFocus

• `Optional` **onFocus**: [`FocusEventHandler`](../modules/akashaproject_design_system._internal_.md#focuseventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onFocus

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1376

___

### onFocusCapture

• `Optional` **onFocusCapture**: [`FocusEventHandler`](../modules/akashaproject_design_system._internal_.md#focuseventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onFocusCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1377

___

### onGotPointerCapture

• `Optional` **onGotPointerCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onGotPointerCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1524

___

### onGotPointerCaptureCapture

• `Optional` **onGotPointerCaptureCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onGotPointerCaptureCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1525

___

### onInput

• `Optional` **onInput**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onInput

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1386

___

### onInputCapture

• `Optional` **onInputCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onInputCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1387

___

### onInvalid

• `Optional` **onInvalid**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onInvalid

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1392

___

### onInvalidCapture

• `Optional` **onInvalidCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onInvalidCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1393

___

### onKeyDown

• `Optional` **onKeyDown**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyDown

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1402

___

### onKeyDownCapture

• `Optional` **onKeyDownCapture**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyDownCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1403

___

### onKeyPress

• `Optional` **onKeyPress**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyPress

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1404

___

### onKeyPressCapture

• `Optional` **onKeyPressCapture**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyPressCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1405

___

### onKeyUp

• `Optional` **onKeyUp**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyUp

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1406

___

### onKeyUpCapture

• `Optional` **onKeyUpCapture**: [`KeyboardEventHandler`](../modules/akashaproject_design_system._internal_.md#keyboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onKeyUpCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1407

___

### onLoad

• `Optional` **onLoad**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoad

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1396

___

### onLoadCapture

• `Optional` **onLoadCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1397

___

### onLoadStart

• `Optional` **onLoadStart**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadStart

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1428

___

### onLoadStartCapture

• `Optional` **onLoadStartCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadStartCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1429

___

### onLoadedData

• `Optional` **onLoadedData**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadedData

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1424

___

### onLoadedDataCapture

• `Optional` **onLoadedDataCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadedDataCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1425

___

### onLoadedMetadata

• `Optional` **onLoadedMetadata**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadedMetadata

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1426

___

### onLoadedMetadataCapture

• `Optional` **onLoadedMetadataCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLoadedMetadataCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1427

___

### onLostPointerCapture

• `Optional` **onLostPointerCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLostPointerCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1526

___

### onLostPointerCaptureCapture

• `Optional` **onLostPointerCaptureCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onLostPointerCaptureCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1527

___

### onMouseDown

• `Optional` **onMouseDown**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseDown

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1480

___

### onMouseDownCapture

• `Optional` **onMouseDownCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseDownCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1481

___

### onMouseEnter

• `Optional` **onMouseEnter**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseEnter

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1482

___

### onMouseLeave

• `Optional` **onMouseLeave**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseLeave

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1483

___

### onMouseMove

• `Optional` **onMouseMove**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseMove

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1484

___

### onMouseMoveCapture

• `Optional` **onMouseMoveCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseMoveCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1485

___

### onMouseOut

• `Optional` **onMouseOut**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseOut

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1486

___

### onMouseOutCapture

• `Optional` **onMouseOutCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseOutCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1487

___

### onMouseOver

• `Optional` **onMouseOver**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseOver

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1488

___

### onMouseOverCapture

• `Optional` **onMouseOverCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseOverCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1489

___

### onMouseUp

• `Optional` **onMouseUp**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseUp

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1490

___

### onMouseUpCapture

• `Optional` **onMouseUpCapture**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onMouseUpCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1491

___

### onPaste

• `Optional` **onPaste**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPaste

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1364

___

### onPasteCapture

• `Optional` **onPasteCapture**: [`ClipboardEventHandler`](../modules/akashaproject_design_system._internal_.md#clipboardeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPasteCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1365

___

### onPause

• `Optional` **onPause**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPause

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1430

___

### onPauseCapture

• `Optional` **onPauseCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPauseCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1431

___

### onPlay

• `Optional` **onPlay**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPlay

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1432

___

### onPlayCapture

• `Optional` **onPlayCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPlayCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1433

___

### onPlaying

• `Optional` **onPlaying**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPlaying

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1434

___

### onPlayingCapture

• `Optional` **onPlayingCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPlayingCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1435

___

### onPointerCancel

• `Optional` **onPointerCancel**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerCancel

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1514

___

### onPointerCancelCapture

• `Optional` **onPointerCancelCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerCancelCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1515

___

### onPointerDown

• `Optional` **onPointerDown**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerDown

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1508

___

### onPointerDownCapture

• `Optional` **onPointerDownCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerDownCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1509

___

### onPointerEnter

• `Optional` **onPointerEnter**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerEnter

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1516

___

### onPointerEnterCapture

• `Optional` **onPointerEnterCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerEnterCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1517

___

### onPointerLeave

• `Optional` **onPointerLeave**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerLeave

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1518

___

### onPointerLeaveCapture

• `Optional` **onPointerLeaveCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerLeaveCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1519

___

### onPointerMove

• `Optional` **onPointerMove**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerMove

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1510

___

### onPointerMoveCapture

• `Optional` **onPointerMoveCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerMoveCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1511

___

### onPointerOut

• `Optional` **onPointerOut**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerOut

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1522

___

### onPointerOutCapture

• `Optional` **onPointerOutCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerOutCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1523

___

### onPointerOver

• `Optional` **onPointerOver**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerOver

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1520

___

### onPointerOverCapture

• `Optional` **onPointerOverCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerOverCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1521

___

### onPointerUp

• `Optional` **onPointerUp**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerUp

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1512

___

### onPointerUpCapture

• `Optional` **onPointerUpCapture**: [`PointerEventHandler`](../modules/akashaproject_design_system._internal_.md#pointereventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onPointerUpCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1513

___

### onProgress

• `Optional` **onProgress**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onProgress

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1436

___

### onProgressCapture

• `Optional` **onProgressCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onProgressCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1437

___

### onRateChange

• `Optional` **onRateChange**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onRateChange

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1438

___

### onRateChangeCapture

• `Optional` **onRateChangeCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onRateChangeCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1439

___

### onReset

• `Optional` **onReset**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onReset

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1388

___

### onResetCapture

• `Optional` **onResetCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onResetCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1389

___

### onScroll

• `Optional` **onScroll**: [`UIEventHandler`](../modules/akashaproject_design_system._internal_.md#uieventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onScroll

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1530

___

### onScrollCapture

• `Optional` **onScrollCapture**: [`UIEventHandler`](../modules/akashaproject_design_system._internal_.md#uieventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onScrollCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1531

___

### onSeeked

• `Optional` **onSeeked**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSeeked

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1440

___

### onSeekedCapture

• `Optional` **onSeekedCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSeekedCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1441

___

### onSeeking

• `Optional` **onSeeking**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSeeking

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1442

___

### onSeekingCapture

• `Optional` **onSeekingCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSeekingCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1443

___

### onSelect

• `Optional` **onSelect**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSelect

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1494

___

### onSelectCapture

• `Optional` **onSelectCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSelectCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1495

___

### onStalled

• `Optional` **onStalled**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onStalled

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1444

___

### onStalledCapture

• `Optional` **onStalledCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onStalledCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1445

___

### onSubmit

• `Optional` **onSubmit**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSubmit

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1390

___

### onSubmitCapture

• `Optional` **onSubmitCapture**: [`FormEventHandler`](../modules/akashaproject_design_system._internal_.md#formeventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSubmitCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1391

___

### onSuspend

• `Optional` **onSuspend**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSuspend

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1446

___

### onSuspendCapture

• `Optional` **onSuspendCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onSuspendCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1447

___

### onTimeUpdate

• `Optional` **onTimeUpdate**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTimeUpdate

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1448

___

### onTimeUpdateCapture

• `Optional` **onTimeUpdateCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTimeUpdateCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1449

___

### onTouchCancel

• `Optional` **onTouchCancel**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchCancel

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1498

___

### onTouchCancelCapture

• `Optional` **onTouchCancelCapture**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchCancelCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1499

___

### onTouchEnd

• `Optional` **onTouchEnd**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchEnd

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1500

___

### onTouchEndCapture

• `Optional` **onTouchEndCapture**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchEndCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1501

___

### onTouchMove

• `Optional` **onTouchMove**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchMove

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1502

___

### onTouchMoveCapture

• `Optional` **onTouchMoveCapture**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchMoveCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1503

___

### onTouchStart

• `Optional` **onTouchStart**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchStart

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1504

___

### onTouchStartCapture

• `Optional` **onTouchStartCapture**: [`TouchEventHandler`](../modules/akashaproject_design_system._internal_.md#toucheventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTouchStartCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1505

___

### onTransitionEnd

• `Optional` **onTransitionEnd**: [`TransitionEventHandler`](../modules/akashaproject_design_system._internal_.md#transitioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTransitionEnd

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1546

___

### onTransitionEndCapture

• `Optional` **onTransitionEndCapture**: [`TransitionEventHandler`](../modules/akashaproject_design_system._internal_.md#transitioneventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onTransitionEndCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1547

___

### onVolumeChange

• `Optional` **onVolumeChange**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onVolumeChange

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1450

___

### onVolumeChangeCapture

• `Optional` **onVolumeChangeCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onVolumeChangeCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1451

___

### onWaiting

• `Optional` **onWaiting**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onWaiting

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1452

___

### onWaitingCapture

• `Optional` **onWaitingCapture**: [`ReactEventHandler`](../modules/akashaproject_design_system._internal_.md#reacteventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onWaitingCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1453

___

### onWheel

• `Optional` **onWheel**: [`WheelEventHandler`](../modules/akashaproject_design_system._internal_.md#wheeleventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onWheel

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1534

___

### onWheelCapture

• `Optional` **onWheelCapture**: [`WheelEventHandler`](../modules/akashaproject_design_system._internal_.md#wheeleventhandler)<`HTMLDivElement`\>

#### Inherited from

Omit.onWheelCapture

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1535

___

### overflow

• `Optional` **overflow**: `string` \| { `horizontal?`: ``"hidden"`` \| ``"auto"`` \| ``"scroll"`` \| ``"visible"`` ; `vertical?`: ``"hidden"`` \| ``"auto"`` \| ``"scroll"`` \| ``"visible"``  }

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[overflow](akashaproject_design_system._internal_.BoxProps.md#overflow)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:112

___

### pad

• `Optional` **pad**: [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[pad](akashaproject_design_system._internal_.BoxProps.md#pad)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:122

___

### placeholder

• `Optional` **placeholder**: `string`

#### Inherited from

Omit.placeholder

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1839

___

### prefix

• `Optional` **prefix**: `string`

#### Inherited from

Omit.prefix

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1857

___

### property

• `Optional` **property**: `string`

#### Inherited from

Omit.property

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1858

___

### radioGroup

• `Optional` **radioGroup**: `string`

#### Inherited from

Omit.radioGroup

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1848

___

### ref

• `Optional` **ref**: [`LegacyRef`](../modules/akashaproject_design_system._internal_.md#legacyref)<`HTMLDivElement`\>

#### Inherited from

Omit.ref

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:143

___

### resource

• `Optional` **resource**: `string`

#### Inherited from

Omit.resource

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1859

___

### responsive

• `Optional` **responsive**: `boolean`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[responsive](akashaproject_design_system._internal_.BoxProps.md#responsive)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:123

___

### results

• `Optional` **results**: `number`

#### Inherited from

Omit.results

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1873

___

### role

• `Optional` **role**: [`AriaRole`](../modules/akashaproject_design_system._internal_.md#ariarole)

#### Inherited from

Omit.role

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1851

___

### round

• `Optional` **round**: [`RoundType`](../modules/akashaproject_design_system._internal_.md#roundtype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[round](akashaproject_design_system._internal_.BoxProps.md#round)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:124

___

### security

• `Optional` **security**: `string`

#### Inherited from

Omit.security

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1874

___

### slot

• `Optional` **slot**: `string`

#### Inherited from

Omit.slot

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1840

___

### spellCheck

• `Optional` **spellCheck**: [`Booleanish`](../modules/akashaproject_design_system._internal_.md#booleanish)

#### Inherited from

Omit.spellCheck

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1841

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Inherited from

Omit.style

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1842

___

### suppressContentEditableWarning

• `Optional` **suppressContentEditableWarning**: `boolean`

#### Inherited from

Omit.suppressContentEditableWarning

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1826

___

### suppressHydrationWarning

• `Optional` **suppressHydrationWarning**: `boolean`

#### Inherited from

Omit.suppressHydrationWarning

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1827

___

### tabIndex

• `Optional` **tabIndex**: `number`

#### Inherited from

Omit.tabIndex

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1843

___

### tag

• `Optional` **tag**: [`PolymorphicType`](../modules/akashaproject_design_system._internal_.md#polymorphictype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[tag](akashaproject_design_system._internal_.BoxProps.md#tag)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:125

___

### title

• `Optional` **title**: `string`

#### Inherited from

Omit.title

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1844

___

### translate

• `Optional` **translate**: ``"no"`` \| ``"yes"``

#### Inherited from

Omit.translate

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1845

___

### typeof

• `Optional` **typeof**: `string`

#### Inherited from

Omit.typeof

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1860

___

### unselectable

• `Optional` **unselectable**: ``"on"`` \| ``"off"``

#### Inherited from

Omit.unselectable

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1875

___

### vocab

• `Optional` **vocab**: `string`

#### Inherited from

Omit.vocab

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1861

___

### width

• `Optional` **width**: [`WidthType`](../modules/akashaproject_design_system._internal_.md#widthtype)

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[width](akashaproject_design_system._internal_.BoxProps.md#width)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:127

___

### wrap

• `Optional` **wrap**: `boolean` \| ``"reverse"``

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[wrap](akashaproject_design_system._internal_.BoxProps.md#wrap)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:128

## Methods

### onClick

▸ `Optional` **onClick**(...`args`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Returns

`any`

#### Inherited from

[BoxProps](akashaproject_design_system._internal_.BoxProps.md).[onClick](akashaproject_design_system._internal_.BoxProps.md#onclick)

#### Defined in

ui/design/node_modules/grommet/components/Box/index.d.ts:111
