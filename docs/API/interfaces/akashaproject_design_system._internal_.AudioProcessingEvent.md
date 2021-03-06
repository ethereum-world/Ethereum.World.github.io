[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / AudioProcessingEvent

# Interface: AudioProcessingEvent

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).AudioProcessingEvent

The Web Audio API events that occur when a ScriptProcessorNode input buffer is ready to be processed.

**`deprecated`** As of the August 29 2014 Web Audio API spec publication, this feature has been marked as deprecated, and is soon to be replaced by AudioWorklet.

## Hierarchy

- `Event`

  ↳ **`AudioProcessingEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_design_system._internal_.AudioProcessingEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_design_system._internal_.AudioProcessingEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_design_system._internal_.AudioProcessingEvent.md#capturing_phase)
- [NONE](akashaproject_design_system._internal_.AudioProcessingEvent.md#none)
- [bubbles](akashaproject_design_system._internal_.AudioProcessingEvent.md#bubbles)
- [cancelBubble](akashaproject_design_system._internal_.AudioProcessingEvent.md#cancelbubble)
- [cancelable](akashaproject_design_system._internal_.AudioProcessingEvent.md#cancelable)
- [composed](akashaproject_design_system._internal_.AudioProcessingEvent.md#composed)
- [currentTarget](akashaproject_design_system._internal_.AudioProcessingEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.AudioProcessingEvent.md#defaultprevented)
- [eventPhase](akashaproject_design_system._internal_.AudioProcessingEvent.md#eventphase)
- [inputBuffer](akashaproject_design_system._internal_.AudioProcessingEvent.md#inputbuffer)
- [isTrusted](akashaproject_design_system._internal_.AudioProcessingEvent.md#istrusted)
- [outputBuffer](akashaproject_design_system._internal_.AudioProcessingEvent.md#outputbuffer)
- [playbackTime](akashaproject_design_system._internal_.AudioProcessingEvent.md#playbacktime)
- [returnValue](akashaproject_design_system._internal_.AudioProcessingEvent.md#returnvalue)
- [srcElement](akashaproject_design_system._internal_.AudioProcessingEvent.md#srcelement)
- [target](akashaproject_design_system._internal_.AudioProcessingEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.AudioProcessingEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.AudioProcessingEvent.md#type)

### Methods

- [composedPath](akashaproject_design_system._internal_.AudioProcessingEvent.md#composedpath)
- [initEvent](akashaproject_design_system._internal_.AudioProcessingEvent.md#initevent)
- [preventDefault](akashaproject_design_system._internal_.AudioProcessingEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_design_system._internal_.AudioProcessingEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_design_system._internal_.AudioProcessingEvent.md#stoppropagation)

## Properties

### AT\_TARGET

• `Readonly` **AT\_TARGET**: `number`

#### Inherited from

Event.AT\_TARGET

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5123

___

### BUBBLING\_PHASE

• `Readonly` **BUBBLING\_PHASE**: `number`

#### Inherited from

Event.BUBBLING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5124

___

### CAPTURING\_PHASE

• `Readonly` **CAPTURING\_PHASE**: `number`

#### Inherited from

Event.CAPTURING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5125

___

### NONE

• `Readonly` **NONE**: `number`

#### Inherited from

Event.NONE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5126

___

### bubbles

• `Readonly` **bubbles**: `boolean`

Returns true or false depending on how event was initialized. True if event goes through its target's ancestors in reverse tree order, and false otherwise.

#### Inherited from

Event.bubbles

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5063

___

### cancelBubble

• **cancelBubble**: `boolean`

#### Inherited from

Event.cancelBubble

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5064

___

### cancelable

• `Readonly` **cancelable**: `boolean`

Returns true or false depending on how event was initialized. Its return value does not always carry meaning, but true can indicate that part of the operation during which event was dispatched, can be canceled by invoking the preventDefault() method.

#### Inherited from

Event.cancelable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5068

___

### composed

• `Readonly` **composed**: `boolean`

Returns true or false depending on how event was initialized. True if event invokes listeners past a ShadowRoot node that is the root of its target, and false otherwise.

#### Inherited from

Event.composed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5072

___

### currentTarget

• `Readonly` **currentTarget**: `EventTarget`

Returns the object whose event listener's callback is currently being invoked.

#### Inherited from

Event.currentTarget

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5076

___

### defaultPrevented

• `Readonly` **defaultPrevented**: `boolean`

Returns true if preventDefault() was invoked successfully to indicate cancelation, and false otherwise.

#### Inherited from

Event.defaultPrevented

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5080

___

### eventPhase

• `Readonly` **eventPhase**: `number`

Returns the event's phase, which is one of NONE, CAPTURING_PHASE, AT_TARGET, and BUBBLING_PHASE.

#### Inherited from

Event.eventPhase

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5084

___

### inputBuffer

• `Readonly` **inputBuffer**: [`AudioBuffer`](../modules/akashaproject_design_system._internal_.md#audiobuffer)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2253

___

### isTrusted

• `Readonly` **isTrusted**: `boolean`

Returns true if event was dispatched by the user agent, and false otherwise.

#### Inherited from

Event.isTrusted

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5088

___

### outputBuffer

• `Readonly` **outputBuffer**: [`AudioBuffer`](../modules/akashaproject_design_system._internal_.md#audiobuffer)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2255

___

### playbackTime

• `Readonly` **playbackTime**: `number`

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2257

___

### returnValue

• **returnValue**: `boolean`

**`deprecated`**

#### Inherited from

Event.returnValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5090

___

### srcElement

• `Readonly` **srcElement**: `EventTarget`

**`deprecated`**

#### Inherited from

Event.srcElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5092

___

### target

• `Readonly` **target**: `EventTarget`

Returns the object to which event is dispatched (its target).

#### Inherited from

Event.target

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5096

___

### timeStamp

• `Readonly` **timeStamp**: `number`

Returns the event's timestamp as the number of milliseconds measured relative to the time origin.

#### Inherited from

Event.timeStamp

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5100

___

### type

• `Readonly` **type**: `string`

Returns the type of event, e.g. "click", "hashchange", or "submit".

#### Inherited from

Event.type

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5104

## Methods

### composedPath

▸ **composedPath**(): `EventTarget`[]

Returns the invocation target objects of event's path (objects on which listeners will be invoked), except for any nodes in shadow trees of which the shadow root's mode is "closed" that are not reachable from event's currentTarget.

#### Returns

`EventTarget`[]

#### Inherited from

Event.composedPath

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5108

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

Event.initEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5110

___

### preventDefault

▸ **preventDefault**(): `void`

If invoked when the cancelable attribute value is true, and while executing a listener for the event with passive set to false, signals to the operation that caused event to be dispatched that it needs to be canceled.

#### Returns

`void`

#### Inherited from

Event.preventDefault

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5114

___

### stopImmediatePropagation

▸ **stopImmediatePropagation**(): `void`

Invoking this method prevents event from reaching any registered event listeners after the current one finishes running and, when dispatched in a tree, also prevents event from reaching any other objects.

#### Returns

`void`

#### Inherited from

Event.stopImmediatePropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5118

___

### stopPropagation

▸ **stopPropagation**(): `void`

When dispatched in a tree, invoking this method prevents event from reaching any objects other than the current object.

#### Returns

`void`

#### Inherited from

Event.stopPropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5122
