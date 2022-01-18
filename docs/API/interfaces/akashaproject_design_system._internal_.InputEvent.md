[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / InputEvent

# Interface: InputEvent

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).InputEvent

## Hierarchy

- `UIEvent`

  ↳ **`InputEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_design_system._internal_.InputEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_design_system._internal_.InputEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_design_system._internal_.InputEvent.md#capturing_phase)
- [NONE](akashaproject_design_system._internal_.InputEvent.md#none)
- [bubbles](akashaproject_design_system._internal_.InputEvent.md#bubbles)
- [cancelBubble](akashaproject_design_system._internal_.InputEvent.md#cancelbubble)
- [cancelable](akashaproject_design_system._internal_.InputEvent.md#cancelable)
- [composed](akashaproject_design_system._internal_.InputEvent.md#composed)
- [currentTarget](akashaproject_design_system._internal_.InputEvent.md#currenttarget)
- [data](akashaproject_design_system._internal_.InputEvent.md#data)
- [dataTransfer](akashaproject_design_system._internal_.InputEvent.md#datatransfer)
- [defaultPrevented](akashaproject_design_system._internal_.InputEvent.md#defaultprevented)
- [detail](akashaproject_design_system._internal_.InputEvent.md#detail)
- [eventPhase](akashaproject_design_system._internal_.InputEvent.md#eventphase)
- [inputType](akashaproject_design_system._internal_.InputEvent.md#inputtype)
- [isComposing](akashaproject_design_system._internal_.InputEvent.md#iscomposing)
- [isTrusted](akashaproject_design_system._internal_.InputEvent.md#istrusted)
- [returnValue](akashaproject_design_system._internal_.InputEvent.md#returnvalue)
- [srcElement](akashaproject_design_system._internal_.InputEvent.md#srcelement)
- [target](akashaproject_design_system._internal_.InputEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.InputEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.InputEvent.md#type)
- [view](akashaproject_design_system._internal_.InputEvent.md#view)
- [which](akashaproject_design_system._internal_.InputEvent.md#which)

### Methods

- [composedPath](akashaproject_design_system._internal_.InputEvent.md#composedpath)
- [getTargetRanges](akashaproject_design_system._internal_.InputEvent.md#gettargetranges)
- [initEvent](akashaproject_design_system._internal_.InputEvent.md#initevent)
- [initUIEvent](akashaproject_design_system._internal_.InputEvent.md#inituievent)
- [preventDefault](akashaproject_design_system._internal_.InputEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_design_system._internal_.InputEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_design_system._internal_.InputEvent.md#stoppropagation)

## Properties

### AT\_TARGET

• `Readonly` **AT\_TARGET**: `number`

#### Inherited from

UIEvent.AT\_TARGET

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5123

___

### BUBBLING\_PHASE

• `Readonly` **BUBBLING\_PHASE**: `number`

#### Inherited from

UIEvent.BUBBLING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5124

___

### CAPTURING\_PHASE

• `Readonly` **CAPTURING\_PHASE**: `number`

#### Inherited from

UIEvent.CAPTURING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5125

___

### NONE

• `Readonly` **NONE**: `number`

#### Inherited from

UIEvent.NONE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5126

___

### bubbles

• `Readonly` **bubbles**: `boolean`

Returns true or false depending on how event was initialized. True if event goes through its target's ancestors in reverse tree order, and false otherwise.

#### Inherited from

UIEvent.bubbles

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5063

___

### cancelBubble

• **cancelBubble**: `boolean`

#### Inherited from

UIEvent.cancelBubble

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5064

___

### cancelable

• `Readonly` **cancelable**: `boolean`

Returns true or false depending on how event was initialized. Its return value does not always carry meaning, but true can indicate that part of the operation during which event was dispatched, can be canceled by invoking the preventDefault() method.

#### Inherited from

UIEvent.cancelable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5068

___

### composed

• `Readonly` **composed**: `boolean`

Returns true or false depending on how event was initialized. True if event invokes listeners past a ShadowRoot node that is the root of its target, and false otherwise.

#### Inherited from

UIEvent.composed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5072

___

### currentTarget

• `Readonly` **currentTarget**: `EventTarget`

Returns the object whose event listener's callback is currently being invoked.

#### Inherited from

UIEvent.currentTarget

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5076

___

### data

• `Readonly` **data**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9510

___

### dataTransfer

• `Readonly` **dataTransfer**: `DataTransfer`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9511

___

### defaultPrevented

• `Readonly` **defaultPrevented**: `boolean`

Returns true if preventDefault() was invoked successfully to indicate cancelation, and false otherwise.

#### Inherited from

UIEvent.defaultPrevented

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5080

___

### detail

• `Readonly` **detail**: `number`

#### Inherited from

UIEvent.detail

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14905

___

### eventPhase

• `Readonly` **eventPhase**: `number`

Returns the event's phase, which is one of NONE, CAPTURING_PHASE, AT_TARGET, and BUBBLING_PHASE.

#### Inherited from

UIEvent.eventPhase

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5084

___

### inputType

• `Readonly` **inputType**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9512

___

### isComposing

• `Readonly` **isComposing**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9513

___

### isTrusted

• `Readonly` **isTrusted**: `boolean`

Returns true if event was dispatched by the user agent, and false otherwise.

#### Inherited from

UIEvent.isTrusted

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5088

___

### returnValue

• **returnValue**: `boolean`

**`deprecated`**

#### Inherited from

UIEvent.returnValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5090

___

### srcElement

• `Readonly` **srcElement**: `EventTarget`

**`deprecated`**

#### Inherited from

UIEvent.srcElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5092

___

### target

• `Readonly` **target**: `EventTarget`

Returns the object to which event is dispatched (its target).

#### Inherited from

UIEvent.target

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5096

___

### timeStamp

• `Readonly` **timeStamp**: `number`

Returns the event's timestamp as the number of milliseconds measured relative to the time origin.

#### Inherited from

UIEvent.timeStamp

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5100

___

### type

• `Readonly` **type**: `string`

Returns the type of event, e.g. "click", "hashchange", or "submit".

#### Inherited from

UIEvent.type

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5104

___

### view

• `Readonly` **view**: `Window`

#### Inherited from

UIEvent.view

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14906

___

### which

• `Readonly` **which**: `number`

**`deprecated`**

#### Inherited from

UIEvent.which

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14908

## Methods

### composedPath

▸ **composedPath**(): `EventTarget`[]

Returns the invocation target objects of event's path (objects on which listeners will be invoked), except for any nodes in shadow trees of which the shadow root's mode is "closed" that are not reachable from event's currentTarget.

#### Returns

`EventTarget`[]

#### Inherited from

UIEvent.composedPath

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5108

___

### getTargetRanges

▸ **getTargetRanges**(): [`StaticRange`](../modules/akashaproject_design_system._internal_.md#staticrange)[]

#### Returns

[`StaticRange`](../modules/akashaproject_design_system._internal_.md#staticrange)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9514

___

### initEvent

▸ **initEvent**(`type`, `bubbles?`, `cancelable?`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `bubbles?` | `boolean` |
| `cancelable?` | `boolean` |

#### Returns

`void`

#### Inherited from

UIEvent.initEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5110

___

### initUIEvent

▸ **initUIEvent**(`typeArg`, `bubblesArg?`, `cancelableArg?`, `viewArg?`, `detailArg?`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `typeArg` | `string` |
| `bubblesArg?` | `boolean` |
| `cancelableArg?` | `boolean` |
| `viewArg?` | `Window` |
| `detailArg?` | `number` |

#### Returns

`void`

#### Inherited from

UIEvent.initUIEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14910

___

### preventDefault

▸ **preventDefault**(): `void`

If invoked when the cancelable attribute value is true, and while executing a listener for the event with passive set to false, signals to the operation that caused event to be dispatched that it needs to be canceled.

#### Returns

`void`

#### Inherited from

UIEvent.preventDefault

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5114

___

### stopImmediatePropagation

▸ **stopImmediatePropagation**(): `void`

Invoking this method prevents event from reaching any registered event listeners after the current one finishes running and, when dispatched in a tree, also prevents event from reaching any other objects.

#### Returns

`void`

#### Inherited from

UIEvent.stopImmediatePropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5118

___

### stopPropagation

▸ **stopPropagation**(): `void`

When dispatched in a tree, invoking this method prevents event from reaching any objects other than the current object.

#### Returns

`void`

#### Inherited from

UIEvent.stopPropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5122
