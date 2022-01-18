[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / GlobalEventHandlers

# Interface: GlobalEventHandlers

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).GlobalEventHandlers

## Hierarchy

- **`GlobalEventHandlers`**

  ↳ [`Window`](akashaproject_ui_awf_testing_utils._internal_.Window.md)

## Table of contents

### Properties

- [onabort](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onabort)
- [onanimationcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationcancel)
- [onanimationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationend)
- [onanimationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationiteration)
- [onanimationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onanimationstart)
- [onauxclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onauxclick)
- [onblur](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onblur)
- [oncanplay](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncanplay)
- [oncanplaythrough](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncanplaythrough)
- [onchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onchange)
- [onclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onclick)
- [onclose](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onclose)
- [oncontextmenu](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncontextmenu)
- [oncuechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oncuechange)
- [ondblclick](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondblclick)
- [ondrag](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondrag)
- [ondragend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragend)
- [ondragenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragenter)
- [ondragleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragleave)
- [ondragover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragover)
- [ondragstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondragstart)
- [ondrop](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondrop)
- [ondurationchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ondurationchange)
- [onemptied](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onemptied)
- [onended](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onended)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onerror)
- [onfocus](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onfocus)
- [onformdata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onformdata)
- [ongotpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ongotpointercapture)
- [oninput](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oninput)
- [oninvalid](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#oninvalid)
- [onkeydown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeydown)
- [onkeypress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeypress)
- [onkeyup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onkeyup)
- [onload](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onload)
- [onloadeddata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadeddata)
- [onloadedmetadata](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadedmetadata)
- [onloadstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onloadstart)
- [onlostpointercapture](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onlostpointercapture)
- [onmousedown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmousedown)
- [onmouseenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseenter)
- [onmouseleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseleave)
- [onmousemove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmousemove)
- [onmouseout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseout)
- [onmouseover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseover)
- [onmouseup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onmouseup)
- [onpause](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpause)
- [onplay](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onplay)
- [onplaying](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onplaying)
- [onpointercancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointercancel)
- [onpointerdown](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerdown)
- [onpointerenter](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerenter)
- [onpointerleave](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerleave)
- [onpointermove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointermove)
- [onpointerout](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerout)
- [onpointerover](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerover)
- [onpointerup](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onpointerup)
- [onprogress](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onprogress)
- [onratechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onratechange)
- [onreset](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onreset)
- [onresize](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onresize)
- [onscroll](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onscroll)
- [onseeked](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onseeked)
- [onseeking](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onseeking)
- [onselect](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselect)
- [onselectionchange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselectionchange)
- [onselectstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onselectstart)
- [onstalled](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onstalled)
- [onsubmit](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onsubmit)
- [onsuspend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onsuspend)
- [ontimeupdate](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontimeupdate)
- [ontoggle](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontoggle)
- [ontouchcancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchcancel)
- [ontouchend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchend)
- [ontouchmove](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchmove)
- [ontouchstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontouchstart)
- [ontransitioncancel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitioncancel)
- [ontransitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionend)
- [ontransitionrun](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionrun)
- [ontransitionstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#ontransitionstart)
- [onvolumechange](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onvolumechange)
- [onwaiting](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwaiting)
- [onwebkitanimationend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationend)
- [onwebkitanimationiteration](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationiteration)
- [onwebkitanimationstart](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkitanimationstart)
- [onwebkittransitionend](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwebkittransitionend)
- [onwheel](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#onwheel)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#addeventlistener)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlers.md#removeeventlistener)

## Properties

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5761

___

### onerror

• **onerror**: [`OnErrorEventHandlerNonNull`](akashaproject_ui_awf_testing_utils._internal_.OnErrorEventHandlerNonNull.md)

Fires when an error occurs during object loading.

**`param`** The event.

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5772

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5839

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

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5940

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`GlobalEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`GlobalEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5941

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5942

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`GlobalEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`GlobalEventHandlersEventMap`](akashaproject_ui_awf_testing_utils._internal_.GlobalEventHandlersEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5943

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5944
