[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SVGElementEventMap

# Interface: SVGElementEventMap

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SVGElementEventMap

## Hierarchy

- [`ElementEventMap`](akashaproject_ui_awf_testing_utils._internal_.ElementEventMap.md)

- [`DocumentAndElementEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md)

- [`GlobalEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md)

  ↳ **`SVGElementEventMap`**

## Table of contents

### Properties

- [abort](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#abort)
- [animationcancel](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#animationcancel)
- [animationend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#animationend)
- [animationiteration](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#animationiteration)
- [animationstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#animationstart)
- [auxclick](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#auxclick)
- [beforeinput](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#beforeinput)
- [blur](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#blur)
- [canplay](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#canplay)
- [canplaythrough](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#canplaythrough)
- [change](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#change)
- [click](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#click)
- [close](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#close)
- [compositionend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#compositionend)
- [compositionstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#compositionstart)
- [compositionupdate](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#compositionupdate)
- [contextmenu](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#contextmenu)
- [copy](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#copy)
- [cuechange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#cuechange)
- [cut](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#cut)
- [dblclick](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dblclick)
- [drag](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#drag)
- [dragend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dragend)
- [dragenter](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dragenter)
- [dragleave](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dragleave)
- [dragover](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dragover)
- [dragstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#dragstart)
- [drop](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#drop)
- [durationchange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#durationchange)
- [emptied](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#emptied)
- [ended](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#ended)
- [error](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#error)
- [focus](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#focus)
- [focusin](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#focusin)
- [focusout](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#focusout)
- [formdata](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#formdata)
- [fullscreenchange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#fullscreenchange)
- [fullscreenerror](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#fullscreenerror)
- [gotpointercapture](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#gotpointercapture)
- [input](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#input)
- [invalid](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#invalid)
- [keydown](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#keydown)
- [keypress](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#keypress)
- [keyup](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#keyup)
- [load](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#load)
- [loadeddata](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#loadeddata)
- [loadedmetadata](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#loadedmetadata)
- [loadstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#loadstart)
- [lostpointercapture](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#lostpointercapture)
- [mousedown](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mousedown)
- [mouseenter](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mouseenter)
- [mouseleave](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mouseleave)
- [mousemove](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mousemove)
- [mouseout](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mouseout)
- [mouseover](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mouseover)
- [mouseup](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#mouseup)
- [paste](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#paste)
- [pause](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pause)
- [play](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#play)
- [playing](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#playing)
- [pointercancel](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointercancel)
- [pointerdown](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerdown)
- [pointerenter](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerenter)
- [pointerleave](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerleave)
- [pointermove](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointermove)
- [pointerout](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerout)
- [pointerover](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerover)
- [pointerup](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#pointerup)
- [progress](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#progress)
- [ratechange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#ratechange)
- [reset](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#reset)
- [resize](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#resize)
- [scroll](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#scroll)
- [securitypolicyviolation](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#securitypolicyviolation)
- [seeked](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#seeked)
- [seeking](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#seeking)
- [select](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#select)
- [selectionchange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#selectionchange)
- [selectstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#selectstart)
- [stalled](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#stalled)
- [submit](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#submit)
- [suspend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#suspend)
- [timeupdate](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#timeupdate)
- [toggle](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#toggle)
- [touchcancel](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#touchcancel)
- [touchend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#touchend)
- [touchmove](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#touchmove)
- [touchstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#touchstart)
- [transitioncancel](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#transitioncancel)
- [transitionend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#transitionend)
- [transitionrun](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#transitionrun)
- [transitionstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#transitionstart)
- [volumechange](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#volumechange)
- [waiting](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#waiting)
- [webkitanimationend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#webkitanimationend)
- [webkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#webkitanimationiteration)
- [webkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#webkitanimationstart)
- [webkittransitionend](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#webkittransitionend)
- [wheel](akashaproject_ui_awf_testing_utils._internal_.SVGElementEventMap.md#wheel)

## Properties

### abort

• **abort**: `UIEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[abort](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#abort)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5576

___

### animationcancel

• **animationcancel**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[animationcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#animationcancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5577

___

### animationend

• **animationend**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[animationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#animationend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5578

___

### animationiteration

• **animationiteration**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[animationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#animationiteration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5579

___

### animationstart

• **animationstart**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[animationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#animationstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5580

___

### auxclick

• **auxclick**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[auxclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#auxclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5581

___

### beforeinput

• **beforeinput**: [`InputEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#inputevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[beforeinput](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#beforeinput)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5582

___

### blur

• **blur**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[blur](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#blur)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5583

___

### canplay

• **canplay**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[canplay](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#canplay)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5584

___

### canplaythrough

• **canplaythrough**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[canplaythrough](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#canplaythrough)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5585

___

### change

• **change**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[change](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#change)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5586

___

### click

• **click**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[click](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#click)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5587

___

### close

• **close**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[close](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#close)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5588

___

### compositionend

• **compositionend**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[compositionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#compositionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5589

___

### compositionstart

• **compositionstart**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[compositionstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#compositionstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5590

___

### compositionupdate

• **compositionupdate**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[compositionupdate](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#compositionupdate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5591

___

### contextmenu

• **contextmenu**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[contextmenu](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#contextmenu)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5592

___

### copy

• **copy**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md).[copy](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md#copy)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4724

___

### cuechange

• **cuechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[cuechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#cuechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5593

___

### cut

• **cut**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md).[cut](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md#cut)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4725

___

### dblclick

• **dblclick**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dblclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dblclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5594

___

### drag

• **drag**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[drag](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#drag)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5595

___

### dragend

• **dragend**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dragend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dragend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5596

___

### dragenter

• **dragenter**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dragenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dragenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5597

___

### dragleave

• **dragleave**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dragleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dragleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5598

___

### dragover

• **dragover**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dragover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dragover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5599

___

### dragstart

• **dragstart**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[dragstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#dragstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5600

___

### drop

• **drop**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[drop](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#drop)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5601

___

### durationchange

• **durationchange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[durationchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#durationchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5602

___

### emptied

• **emptied**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[emptied](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#emptied)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5603

___

### ended

• **ended**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[ended](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#ended)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5604

___

### error

• **error**: [`ErrorEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#errorevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[error](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#error)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5605

___

### focus

• **focus**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[focus](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#focus)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5606

___

### focusin

• **focusin**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[focusin](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#focusin)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5607

___

### focusout

• **focusout**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[focusout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#focusout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5608

___

### formdata

• **formdata**: [`FormDataEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#formdataevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[formdata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#formdata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5609

___

### fullscreenchange

• **fullscreenchange**: `Event`

#### Inherited from

[ElementEventMap](akashaproject_ui_awf_testing_utils._internal_.ElementEventMap.md).[fullscreenchange](akashaproject_ui_awf_testing_utils._internal_.ElementEventMap.md#fullscreenchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4867

___

### fullscreenerror

• **fullscreenerror**: `Event`

#### Inherited from

[ElementEventMap](akashaproject_ui_awf_testing_utils._internal_.ElementEventMap.md).[fullscreenerror](akashaproject_ui_awf_testing_utils._internal_.ElementEventMap.md#fullscreenerror)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4868

___

### gotpointercapture

• **gotpointercapture**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[gotpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#gotpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5610

___

### input

• **input**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[input](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#input)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5611

___

### invalid

• **invalid**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[invalid](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#invalid)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5612

___

### keydown

• **keydown**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[keydown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#keydown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5613

___

### keypress

• **keypress**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[keypress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#keypress)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5614

___

### keyup

• **keyup**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[keyup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#keyup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5615

___

### load

• **load**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[load](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#load)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5616

___

### loadeddata

• **loadeddata**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[loadeddata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#loadeddata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5617

___

### loadedmetadata

• **loadedmetadata**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[loadedmetadata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#loadedmetadata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5618

___

### loadstart

• **loadstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[loadstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#loadstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5619

___

### lostpointercapture

• **lostpointercapture**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[lostpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#lostpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5620

___

### mousedown

• **mousedown**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mousedown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mousedown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5621

___

### mouseenter

• **mouseenter**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mouseenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mouseenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5622

___

### mouseleave

• **mouseleave**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mouseleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mouseleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5623

___

### mousemove

• **mousemove**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mousemove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mousemove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5624

___

### mouseout

• **mouseout**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mouseout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mouseout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5625

___

### mouseover

• **mouseover**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mouseover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mouseover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5626

___

### mouseup

• **mouseup**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[mouseup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#mouseup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5627

___

### paste

• **paste**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md).[paste](akashaproject_ui_awf_testing_utils._internal_.DocumentAndElementEventHandlersEventMap.md#paste)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4726

___

### pause

• **pause**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pause](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pause)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5628

___

### play

• **play**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[play](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#play)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5629

___

### playing

• **playing**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[playing](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#playing)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5630

___

### pointercancel

• **pointercancel**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointercancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointercancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5631

___

### pointerdown

• **pointerdown**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerdown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerdown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5632

___

### pointerenter

• **pointerenter**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5633

___

### pointerleave

• **pointerleave**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5634

___

### pointermove

• **pointermove**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointermove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointermove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5635

___

### pointerout

• **pointerout**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5636

___

### pointerover

• **pointerover**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5637

___

### pointerup

• **pointerup**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[pointerup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#pointerup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5638

___

### progress

• **progress**: [`ProgressEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#progressevent)<`EventTarget`\>

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[progress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#progress)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5639

___

### ratechange

• **ratechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[ratechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#ratechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5640

___

### reset

• **reset**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[reset](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#reset)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5641

___

### resize

• **resize**: `UIEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[resize](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#resize)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5642

___

### scroll

• **scroll**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[scroll](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#scroll)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5643

___

### securitypolicyviolation

• **securitypolicyviolation**: [`SecurityPolicyViolationEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#securitypolicyviolationevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[securitypolicyviolation](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#securitypolicyviolation)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5644

___

### seeked

• **seeked**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[seeked](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#seeked)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5645

___

### seeking

• **seeking**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[seeking](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#seeking)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5646

___

### select

• **select**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[select](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#select)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5647

___

### selectionchange

• **selectionchange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[selectionchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#selectionchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5648

___

### selectstart

• **selectstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[selectstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#selectstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5649

___

### stalled

• **stalled**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[stalled](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#stalled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5650

___

### submit

• **submit**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[submit](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#submit)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5651

___

### suspend

• **suspend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[suspend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#suspend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5652

___

### timeupdate

• **timeupdate**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[timeupdate](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#timeupdate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5653

___

### toggle

• **toggle**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[toggle](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#toggle)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5654

___

### touchcancel

• **touchcancel**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[touchcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#touchcancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5655

___

### touchend

• **touchend**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[touchend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#touchend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5656

___

### touchmove

• **touchmove**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[touchmove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#touchmove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5657

___

### touchstart

• **touchstart**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[touchstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#touchstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5658

___

### transitioncancel

• **transitioncancel**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[transitioncancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#transitioncancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5659

___

### transitionend

• **transitionend**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[transitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#transitionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5660

___

### transitionrun

• **transitionrun**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[transitionrun](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#transitionrun)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5661

___

### transitionstart

• **transitionstart**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[transitionstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#transitionstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5662

___

### volumechange

• **volumechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[volumechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#volumechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5663

___

### waiting

• **waiting**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[waiting](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#waiting)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5664

___

### webkitanimationend

• **webkitanimationend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[webkitanimationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#webkitanimationend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5665

___

### webkitanimationiteration

• **webkitanimationiteration**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[webkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#webkitanimationiteration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5666

___

### webkitanimationstart

• **webkitanimationstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[webkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#webkitanimationstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5667

___

### webkittransitionend

• **webkittransitionend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[webkittransitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#webkittransitionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5668

___

### wheel

• **wheel**: `WheelEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md).[wheel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md#wheel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5669
