[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / GlobalEventHandlersEventMap

# Interface: GlobalEventHandlersEventMap

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).GlobalEventHandlersEventMap

## Hierarchy

- **`GlobalEventHandlersEventMap`**

  ↳ [`DocumentEventMap`](akashaproject_design_system._internal_.DocumentEventMap.md)

  ↳ [`SVGElementEventMap`](akashaproject_design_system._internal_.SVGElementEventMap.md)

  ↳ [`HTMLElementEventMap`](akashaproject_design_system._internal_.HTMLElementEventMap.md)

## Table of contents

### Properties

- [abort](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#abort)
- [animationcancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationcancel)
- [animationend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationend)
- [animationiteration](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationiteration)
- [animationstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#animationstart)
- [auxclick](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#auxclick)
- [beforeinput](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#beforeinput)
- [blur](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#blur)
- [canplay](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#canplay)
- [canplaythrough](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#canplaythrough)
- [change](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#change)
- [click](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#click)
- [close](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#close)
- [compositionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionend)
- [compositionstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionstart)
- [compositionupdate](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#compositionupdate)
- [contextmenu](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#contextmenu)
- [cuechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#cuechange)
- [dblclick](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dblclick)
- [drag](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#drag)
- [dragend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragend)
- [dragenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragenter)
- [dragleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragleave)
- [dragover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragover)
- [dragstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#dragstart)
- [drop](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#drop)
- [durationchange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#durationchange)
- [emptied](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#emptied)
- [ended](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#ended)
- [error](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#error)
- [focus](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focus)
- [focusin](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focusin)
- [focusout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#focusout)
- [formdata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#formdata)
- [gotpointercapture](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#gotpointercapture)
- [input](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#input)
- [invalid](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#invalid)
- [keydown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keydown)
- [keypress](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keypress)
- [keyup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#keyup)
- [load](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#load)
- [loadeddata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadeddata)
- [loadedmetadata](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadedmetadata)
- [loadstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#loadstart)
- [lostpointercapture](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#lostpointercapture)
- [mousedown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mousedown)
- [mouseenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseenter)
- [mouseleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseleave)
- [mousemove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mousemove)
- [mouseout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseout)
- [mouseover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseover)
- [mouseup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#mouseup)
- [pause](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pause)
- [play](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#play)
- [playing](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#playing)
- [pointercancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointercancel)
- [pointerdown](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerdown)
- [pointerenter](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerenter)
- [pointerleave](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerleave)
- [pointermove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointermove)
- [pointerout](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerout)
- [pointerover](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerover)
- [pointerup](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#pointerup)
- [progress](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#progress)
- [ratechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#ratechange)
- [reset](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#reset)
- [resize](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#resize)
- [scroll](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#scroll)
- [securitypolicyviolation](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#securitypolicyviolation)
- [seeked](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#seeked)
- [seeking](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#seeking)
- [select](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#select)
- [selectionchange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#selectionchange)
- [selectstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#selectstart)
- [stalled](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#stalled)
- [submit](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#submit)
- [suspend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#suspend)
- [timeupdate](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#timeupdate)
- [toggle](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#toggle)
- [touchcancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchcancel)
- [touchend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchend)
- [touchmove](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchmove)
- [touchstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#touchstart)
- [transitioncancel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitioncancel)
- [transitionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionend)
- [transitionrun](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionrun)
- [transitionstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#transitionstart)
- [volumechange](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#volumechange)
- [waiting](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#waiting)
- [webkitanimationend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationend)
- [webkitanimationiteration](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationiteration)
- [webkitanimationstart](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkitanimationstart)
- [webkittransitionend](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#webkittransitionend)
- [wheel](akashaproject_design_system._internal_.GlobalEventHandlersEventMap.md#wheel)

## Properties

### abort

• **abort**: `UIEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5576

___

### animationcancel

• **animationcancel**: `AnimationEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5577

___

### animationend

• **animationend**: `AnimationEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5578

___

### animationiteration

• **animationiteration**: `AnimationEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5579

___

### animationstart

• **animationstart**: `AnimationEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5580

___

### auxclick

• **auxclick**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5581

___

### beforeinput

• **beforeinput**: [`InputEvent`](../modules/akashaproject_design_system._internal_.md#inputevent)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5582

___

### blur

• **blur**: `FocusEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5583

___

### canplay

• **canplay**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5584

___

### canplaythrough

• **canplaythrough**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5585

___

### change

• **change**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5586

___

### click

• **click**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5587

___

### close

• **close**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5588

___

### compositionend

• **compositionend**: `CompositionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5589

___

### compositionstart

• **compositionstart**: `CompositionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5590

___

### compositionupdate

• **compositionupdate**: `CompositionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5591

___

### contextmenu

• **contextmenu**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5592

___

### cuechange

• **cuechange**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5593

___

### dblclick

• **dblclick**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5594

___

### drag

• **drag**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5595

___

### dragend

• **dragend**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5596

___

### dragenter

• **dragenter**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5597

___

### dragleave

• **dragleave**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5598

___

### dragover

• **dragover**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5599

___

### dragstart

• **dragstart**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5600

___

### drop

• **drop**: `DragEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5601

___

### durationchange

• **durationchange**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5602

___

### emptied

• **emptied**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5603

___

### ended

• **ended**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5604

___

### error

• **error**: [`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5605

___

### focus

• **focus**: `FocusEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5606

___

### focusin

• **focusin**: `FocusEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5607

___

### focusout

• **focusout**: `FocusEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5608

___

### formdata

• **formdata**: [`FormDataEvent`](../modules/akashaproject_design_system._internal_.md#formdataevent)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5609

___

### gotpointercapture

• **gotpointercapture**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5610

___

### input

• **input**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5611

___

### invalid

• **invalid**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5612

___

### keydown

• **keydown**: `KeyboardEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5613

___

### keypress

• **keypress**: `KeyboardEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5614

___

### keyup

• **keyup**: `KeyboardEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5615

___

### load

• **load**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5616

___

### loadeddata

• **loadeddata**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5617

___

### loadedmetadata

• **loadedmetadata**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5618

___

### loadstart

• **loadstart**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5619

___

### lostpointercapture

• **lostpointercapture**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5620

___

### mousedown

• **mousedown**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5621

___

### mouseenter

• **mouseenter**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5622

___

### mouseleave

• **mouseleave**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5623

___

### mousemove

• **mousemove**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5624

___

### mouseout

• **mouseout**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5625

___

### mouseover

• **mouseover**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5626

___

### mouseup

• **mouseup**: `MouseEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5627

___

### pause

• **pause**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5628

___

### play

• **play**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5629

___

### playing

• **playing**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5630

___

### pointercancel

• **pointercancel**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5631

___

### pointerdown

• **pointerdown**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5632

___

### pointerenter

• **pointerenter**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5633

___

### pointerleave

• **pointerleave**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5634

___

### pointermove

• **pointermove**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5635

___

### pointerout

• **pointerout**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5636

___

### pointerover

• **pointerover**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5637

___

### pointerup

• **pointerup**: `PointerEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5638

___

### progress

• **progress**: [`ProgressEvent`](../modules/akashaproject_design_system._internal_.md#progressevent)<`EventTarget`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5639

___

### ratechange

• **ratechange**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5640

___

### reset

• **reset**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5641

___

### resize

• **resize**: `UIEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5642

___

### scroll

• **scroll**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5643

___

### securitypolicyviolation

• **securitypolicyviolation**: [`SecurityPolicyViolationEvent`](../modules/akashaproject_design_system._internal_.md#securitypolicyviolationevent)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5644

___

### seeked

• **seeked**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5645

___

### seeking

• **seeking**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5646

___

### select

• **select**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5647

___

### selectionchange

• **selectionchange**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5648

___

### selectstart

• **selectstart**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5649

___

### stalled

• **stalled**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5650

___

### submit

• **submit**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5651

___

### suspend

• **suspend**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5652

___

### timeupdate

• **timeupdate**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5653

___

### toggle

• **toggle**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5654

___

### touchcancel

• **touchcancel**: `TouchEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5655

___

### touchend

• **touchend**: `TouchEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5656

___

### touchmove

• **touchmove**: `TouchEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5657

___

### touchstart

• **touchstart**: `TouchEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5658

___

### transitioncancel

• **transitioncancel**: `TransitionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5659

___

### transitionend

• **transitionend**: `TransitionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5660

___

### transitionrun

• **transitionrun**: `TransitionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5661

___

### transitionstart

• **transitionstart**: `TransitionEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5662

___

### volumechange

• **volumechange**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5663

___

### waiting

• **waiting**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5664

___

### webkitanimationend

• **webkitanimationend**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5665

___

### webkitanimationiteration

• **webkitanimationiteration**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5666

___

### webkitanimationstart

• **webkitanimationstart**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5667

___

### webkittransitionend

• **webkittransitionend**: `Event`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5668

___

### wheel

• **wheel**: `WheelEvent`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5669
