[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / HTMLElementEventMap

# Interface: HTMLElementEventMap

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).HTMLElementEventMap

## Hierarchy

- [`ElementEventMap`](akashaproject_design_system._internal_.ElementEventMap.md)

- [`DocumentAndElementEventHandlersEventMap`](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md)

- [`GlobalEventHandlersEventMap`](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md)

  ↳ **`HTMLElementEventMap`**

  ↳↳ [`HTMLFrameSetElementEventMap`](akashaproject_design_system._internal_.HTMLFrameSetElementEventMap.md)

## Table of contents

### Properties

- [abort](akashaproject_design_system._internal_.HTMLElementEventMap.md#abort)
- [animationcancel](akashaproject_design_system._internal_.HTMLElementEventMap.md#animationcancel)
- [animationend](akashaproject_design_system._internal_.HTMLElementEventMap.md#animationend)
- [animationiteration](akashaproject_design_system._internal_.HTMLElementEventMap.md#animationiteration)
- [animationstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#animationstart)
- [auxclick](akashaproject_design_system._internal_.HTMLElementEventMap.md#auxclick)
- [beforeinput](akashaproject_design_system._internal_.HTMLElementEventMap.md#beforeinput)
- [blur](akashaproject_design_system._internal_.HTMLElementEventMap.md#blur)
- [canplay](akashaproject_design_system._internal_.HTMLElementEventMap.md#canplay)
- [canplaythrough](akashaproject_design_system._internal_.HTMLElementEventMap.md#canplaythrough)
- [change](akashaproject_design_system._internal_.HTMLElementEventMap.md#change)
- [click](akashaproject_design_system._internal_.HTMLElementEventMap.md#click)
- [close](akashaproject_design_system._internal_.HTMLElementEventMap.md#close)
- [compositionend](akashaproject_design_system._internal_.HTMLElementEventMap.md#compositionend)
- [compositionstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#compositionstart)
- [compositionupdate](akashaproject_design_system._internal_.HTMLElementEventMap.md#compositionupdate)
- [contextmenu](akashaproject_design_system._internal_.HTMLElementEventMap.md#contextmenu)
- [copy](akashaproject_design_system._internal_.HTMLElementEventMap.md#copy)
- [cuechange](akashaproject_design_system._internal_.HTMLElementEventMap.md#cuechange)
- [cut](akashaproject_design_system._internal_.HTMLElementEventMap.md#cut)
- [dblclick](akashaproject_design_system._internal_.HTMLElementEventMap.md#dblclick)
- [drag](akashaproject_design_system._internal_.HTMLElementEventMap.md#drag)
- [dragend](akashaproject_design_system._internal_.HTMLElementEventMap.md#dragend)
- [dragenter](akashaproject_design_system._internal_.HTMLElementEventMap.md#dragenter)
- [dragleave](akashaproject_design_system._internal_.HTMLElementEventMap.md#dragleave)
- [dragover](akashaproject_design_system._internal_.HTMLElementEventMap.md#dragover)
- [dragstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#dragstart)
- [drop](akashaproject_design_system._internal_.HTMLElementEventMap.md#drop)
- [durationchange](akashaproject_design_system._internal_.HTMLElementEventMap.md#durationchange)
- [emptied](akashaproject_design_system._internal_.HTMLElementEventMap.md#emptied)
- [ended](akashaproject_design_system._internal_.HTMLElementEventMap.md#ended)
- [error](akashaproject_design_system._internal_.HTMLElementEventMap.md#error)
- [focus](akashaproject_design_system._internal_.HTMLElementEventMap.md#focus)
- [focusin](akashaproject_design_system._internal_.HTMLElementEventMap.md#focusin)
- [focusout](akashaproject_design_system._internal_.HTMLElementEventMap.md#focusout)
- [formdata](akashaproject_design_system._internal_.HTMLElementEventMap.md#formdata)
- [fullscreenchange](akashaproject_design_system._internal_.HTMLElementEventMap.md#fullscreenchange)
- [fullscreenerror](akashaproject_design_system._internal_.HTMLElementEventMap.md#fullscreenerror)
- [gotpointercapture](akashaproject_design_system._internal_.HTMLElementEventMap.md#gotpointercapture)
- [input](akashaproject_design_system._internal_.HTMLElementEventMap.md#input)
- [invalid](akashaproject_design_system._internal_.HTMLElementEventMap.md#invalid)
- [keydown](akashaproject_design_system._internal_.HTMLElementEventMap.md#keydown)
- [keypress](akashaproject_design_system._internal_.HTMLElementEventMap.md#keypress)
- [keyup](akashaproject_design_system._internal_.HTMLElementEventMap.md#keyup)
- [load](akashaproject_design_system._internal_.HTMLElementEventMap.md#load)
- [loadeddata](akashaproject_design_system._internal_.HTMLElementEventMap.md#loadeddata)
- [loadedmetadata](akashaproject_design_system._internal_.HTMLElementEventMap.md#loadedmetadata)
- [loadstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#loadstart)
- [lostpointercapture](akashaproject_design_system._internal_.HTMLElementEventMap.md#lostpointercapture)
- [mousedown](akashaproject_design_system._internal_.HTMLElementEventMap.md#mousedown)
- [mouseenter](akashaproject_design_system._internal_.HTMLElementEventMap.md#mouseenter)
- [mouseleave](akashaproject_design_system._internal_.HTMLElementEventMap.md#mouseleave)
- [mousemove](akashaproject_design_system._internal_.HTMLElementEventMap.md#mousemove)
- [mouseout](akashaproject_design_system._internal_.HTMLElementEventMap.md#mouseout)
- [mouseover](akashaproject_design_system._internal_.HTMLElementEventMap.md#mouseover)
- [mouseup](akashaproject_design_system._internal_.HTMLElementEventMap.md#mouseup)
- [paste](akashaproject_design_system._internal_.HTMLElementEventMap.md#paste)
- [pause](akashaproject_design_system._internal_.HTMLElementEventMap.md#pause)
- [play](akashaproject_design_system._internal_.HTMLElementEventMap.md#play)
- [playing](akashaproject_design_system._internal_.HTMLElementEventMap.md#playing)
- [pointercancel](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointercancel)
- [pointerdown](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerdown)
- [pointerenter](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerenter)
- [pointerleave](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerleave)
- [pointermove](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointermove)
- [pointerout](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerout)
- [pointerover](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerover)
- [pointerup](akashaproject_design_system._internal_.HTMLElementEventMap.md#pointerup)
- [progress](akashaproject_design_system._internal_.HTMLElementEventMap.md#progress)
- [ratechange](akashaproject_design_system._internal_.HTMLElementEventMap.md#ratechange)
- [reset](akashaproject_design_system._internal_.HTMLElementEventMap.md#reset)
- [resize](akashaproject_design_system._internal_.HTMLElementEventMap.md#resize)
- [scroll](akashaproject_design_system._internal_.HTMLElementEventMap.md#scroll)
- [securitypolicyviolation](akashaproject_design_system._internal_.HTMLElementEventMap.md#securitypolicyviolation)
- [seeked](akashaproject_design_system._internal_.HTMLElementEventMap.md#seeked)
- [seeking](akashaproject_design_system._internal_.HTMLElementEventMap.md#seeking)
- [select](akashaproject_design_system._internal_.HTMLElementEventMap.md#select)
- [selectionchange](akashaproject_design_system._internal_.HTMLElementEventMap.md#selectionchange)
- [selectstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#selectstart)
- [stalled](akashaproject_design_system._internal_.HTMLElementEventMap.md#stalled)
- [submit](akashaproject_design_system._internal_.HTMLElementEventMap.md#submit)
- [suspend](akashaproject_design_system._internal_.HTMLElementEventMap.md#suspend)
- [timeupdate](akashaproject_design_system._internal_.HTMLElementEventMap.md#timeupdate)
- [toggle](akashaproject_design_system._internal_.HTMLElementEventMap.md#toggle)
- [touchcancel](akashaproject_design_system._internal_.HTMLElementEventMap.md#touchcancel)
- [touchend](akashaproject_design_system._internal_.HTMLElementEventMap.md#touchend)
- [touchmove](akashaproject_design_system._internal_.HTMLElementEventMap.md#touchmove)
- [touchstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#touchstart)
- [transitioncancel](akashaproject_design_system._internal_.HTMLElementEventMap.md#transitioncancel)
- [transitionend](akashaproject_design_system._internal_.HTMLElementEventMap.md#transitionend)
- [transitionrun](akashaproject_design_system._internal_.HTMLElementEventMap.md#transitionrun)
- [transitionstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#transitionstart)
- [volumechange](akashaproject_design_system._internal_.HTMLElementEventMap.md#volumechange)
- [waiting](akashaproject_design_system._internal_.HTMLElementEventMap.md#waiting)
- [webkitanimationend](akashaproject_design_system._internal_.HTMLElementEventMap.md#webkitanimationend)
- [webkitanimationiteration](akashaproject_design_system._internal_.HTMLElementEventMap.md#webkitanimationiteration)
- [webkitanimationstart](akashaproject_design_system._internal_.HTMLElementEventMap.md#webkitanimationstart)
- [webkittransitionend](akashaproject_design_system._internal_.HTMLElementEventMap.md#webkittransitionend)
- [wheel](akashaproject_design_system._internal_.HTMLElementEventMap.md#wheel)

## Properties

### abort

• **abort**: `UIEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[abort](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#abort)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5576

___

### animationcancel

• **animationcancel**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[animationcancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationcancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5577

___

### animationend

• **animationend**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[animationend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5578

___

### animationiteration

• **animationiteration**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[animationiteration](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationiteration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5579

___

### animationstart

• **animationstart**: `AnimationEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[animationstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5580

___

### auxclick

• **auxclick**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[auxclick](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#auxclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5581

___

### beforeinput

• **beforeinput**: [`InputEvent`](../modules/akashaproject_design_system._internal_.md#inputevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[beforeinput](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#beforeinput)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5582

___

### blur

• **blur**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[blur](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#blur)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5583

___

### canplay

• **canplay**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[canplay](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#canplay)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5584

___

### canplaythrough

• **canplaythrough**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[canplaythrough](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#canplaythrough)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5585

___

### change

• **change**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[change](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#change)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5586

___

### click

• **click**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[click](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#click)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5587

___

### close

• **close**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[close](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#close)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5588

___

### compositionend

• **compositionend**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[compositionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5589

___

### compositionstart

• **compositionstart**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[compositionstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5590

___

### compositionupdate

• **compositionupdate**: `CompositionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[compositionupdate](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionupdate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5591

___

### contextmenu

• **contextmenu**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[contextmenu](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#contextmenu)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5592

___

### copy

• **copy**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md).[copy](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md#copy)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4724

___

### cuechange

• **cuechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[cuechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#cuechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5593

___

### cut

• **cut**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md).[cut](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md#cut)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4725

___

### dblclick

• **dblclick**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dblclick](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dblclick)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5594

___

### drag

• **drag**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[drag](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#drag)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5595

___

### dragend

• **dragend**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dragend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5596

___

### dragenter

• **dragenter**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dragenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5597

___

### dragleave

• **dragleave**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dragleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5598

___

### dragover

• **dragover**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dragover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5599

___

### dragstart

• **dragstart**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[dragstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5600

___

### drop

• **drop**: `DragEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[drop](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#drop)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5601

___

### durationchange

• **durationchange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[durationchange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#durationchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5602

___

### emptied

• **emptied**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[emptied](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#emptied)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5603

___

### ended

• **ended**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[ended](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#ended)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5604

___

### error

• **error**: [`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[error](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#error)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5605

___

### focus

• **focus**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[focus](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focus)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5606

___

### focusin

• **focusin**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[focusin](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focusin)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5607

___

### focusout

• **focusout**: `FocusEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[focusout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focusout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5608

___

### formdata

• **formdata**: [`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[formdata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#formdata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5609

___

### fullscreenchange

• **fullscreenchange**: `Event`

#### Inherited from

[ElementEventMap](akashaproject_design_system._internal_.ElementEventMap.md).[fullscreenchange](akashaproject_design_system._internal_.ElementEventMap.md#fullscreenchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4867

___

### fullscreenerror

• **fullscreenerror**: `Event`

#### Inherited from

[ElementEventMap](akashaproject_design_system._internal_.ElementEventMap.md).[fullscreenerror](akashaproject_design_system._internal_.ElementEventMap.md#fullscreenerror)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4868

___

### gotpointercapture

• **gotpointercapture**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[gotpointercapture](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#gotpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5610

___

### input

• **input**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[input](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#input)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5611

___

### invalid

• **invalid**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[invalid](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#invalid)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5612

___

### keydown

• **keydown**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[keydown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keydown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5613

___

### keypress

• **keypress**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[keypress](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keypress)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5614

___

### keyup

• **keyup**: `KeyboardEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[keyup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keyup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5615

___

### load

• **load**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[load](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#load)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5616

___

### loadeddata

• **loadeddata**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[loadeddata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadeddata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5617

___

### loadedmetadata

• **loadedmetadata**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[loadedmetadata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadedmetadata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5618

___

### loadstart

• **loadstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[loadstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5619

___

### lostpointercapture

• **lostpointercapture**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[lostpointercapture](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#lostpointercapture)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5620

___

### mousedown

• **mousedown**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mousedown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mousedown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5621

___

### mouseenter

• **mouseenter**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mouseenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5622

___

### mouseleave

• **mouseleave**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mouseleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5623

___

### mousemove

• **mousemove**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mousemove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mousemove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5624

___

### mouseout

• **mouseout**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mouseout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5625

___

### mouseover

• **mouseover**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mouseover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5626

___

### mouseup

• **mouseup**: `MouseEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[mouseup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5627

___

### paste

• **paste**: `ClipboardEvent`

#### Inherited from

[DocumentAndElementEventHandlersEventMap](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md).[paste](akashaproject_design_system._internal_.DocumentAndElementEventHandlersEventMap.md#paste)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4726

___

### pause

• **pause**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pause](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pause)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5628

___

### play

• **play**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[play](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#play)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5629

___

### playing

• **playing**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[playing](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#playing)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5630

___

### pointercancel

• **pointercancel**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointercancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointercancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5631

___

### pointerdown

• **pointerdown**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerdown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerdown)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5632

___

### pointerenter

• **pointerenter**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerenter)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5633

___

### pointerleave

• **pointerleave**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerleave)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5634

___

### pointermove

• **pointermove**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointermove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointermove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5635

___

### pointerout

• **pointerout**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerout)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5636

___

### pointerover

• **pointerover**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerover)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5637

___

### pointerup

• **pointerup**: `PointerEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[pointerup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerup)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5638

___

### progress

• **progress**: [`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\>

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[progress](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#progress)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5639

___

### ratechange

• **ratechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[ratechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#ratechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5640

___

### reset

• **reset**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[reset](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#reset)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5641

___

### resize

• **resize**: `UIEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[resize](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#resize)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5642

___

### scroll

• **scroll**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[scroll](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#scroll)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5643

___

### securitypolicyviolation

• **securitypolicyviolation**: [`SecurityPolicyViolationEvent`](../modules/akashaproject_design_system._internal_.md#securitypolicyviolationevent)

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[securitypolicyviolation](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#securitypolicyviolation)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5644

___

### seeked

• **seeked**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[seeked](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#seeked)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5645

___

### seeking

• **seeking**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[seeking](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#seeking)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5646

___

### select

• **select**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[select](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#select)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5647

___

### selectionchange

• **selectionchange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[selectionchange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#selectionchange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5648

___

### selectstart

• **selectstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[selectstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#selectstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5649

___

### stalled

• **stalled**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[stalled](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#stalled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5650

___

### submit

• **submit**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[submit](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#submit)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5651

___

### suspend

• **suspend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[suspend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#suspend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5652

___

### timeupdate

• **timeupdate**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[timeupdate](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#timeupdate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5653

___

### toggle

• **toggle**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[toggle](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#toggle)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5654

___

### touchcancel

• **touchcancel**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[touchcancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchcancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5655

___

### touchend

• **touchend**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[touchend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5656

___

### touchmove

• **touchmove**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[touchmove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchmove)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5657

___

### touchstart

• **touchstart**: `TouchEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[touchstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5658

___

### transitioncancel

• **transitioncancel**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[transitioncancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitioncancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5659

___

### transitionend

• **transitionend**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[transitionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5660

___

### transitionrun

• **transitionrun**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[transitionrun](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionrun)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5661

___

### transitionstart

• **transitionstart**: `TransitionEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[transitionstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5662

___

### volumechange

• **volumechange**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[volumechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#volumechange)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5663

___

### waiting

• **waiting**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[waiting](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#waiting)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5664

___

### webkitanimationend

• **webkitanimationend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[webkitanimationend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5665

___

### webkitanimationiteration

• **webkitanimationiteration**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[webkitanimationiteration](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationiteration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5666

___

### webkitanimationstart

• **webkitanimationstart**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[webkitanimationstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationstart)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5667

___

### webkittransitionend

• **webkittransitionend**: `Event`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[webkittransitionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkittransitionend)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5668

___

### wheel

• **wheel**: `WheelEvent`

#### Inherited from

[GlobalEventHandlersEventMap](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md).[wheel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#wheel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5669
