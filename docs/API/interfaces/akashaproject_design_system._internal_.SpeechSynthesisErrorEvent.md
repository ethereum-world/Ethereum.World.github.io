[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / SpeechSynthesisErrorEvent

# Interface: SpeechSynthesisErrorEvent

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).SpeechSynthesisErrorEvent

## Hierarchy

- [`SpeechSynthesisEvent`](../modules/akashaproject_design_system._internal_.md#speechsynthesisevent)

  ↳ **`SpeechSynthesisErrorEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#capturing_phase)
- [NONE](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#none)
- [bubbles](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#bubbles)
- [cancelBubble](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#cancelbubble)
- [cancelable](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#cancelable)
- [charIndex](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#charindex)
- [charLength](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#charlength)
- [composed](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#composed)
- [currentTarget](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#defaultprevented)
- [elapsedTime](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#elapsedtime)
- [error](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#error)
- [eventPhase](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#istrusted)
- [name](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#name)
- [returnValue](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#returnvalue)
- [srcElement](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#srcelement)
- [target](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#type)
- [utterance](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#utterance)

### Methods

- [composedPath](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#composedpath)
- [initEvent](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#initevent)
- [preventDefault](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_design_system._internal_.SpeechSynthesisErrorEvent.md#stoppropagation)

## Properties

### AT\_TARGET

• `Readonly` **AT\_TARGET**: `number`

#### Inherited from

SpeechSynthesisEvent.AT\_TARGET

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5123

___

### BUBBLING\_PHASE

• `Readonly` **BUBBLING\_PHASE**: `number`

#### Inherited from

SpeechSynthesisEvent.BUBBLING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5124

___

### CAPTURING\_PHASE

• `Readonly` **CAPTURING\_PHASE**: `number`

#### Inherited from

SpeechSynthesisEvent.CAPTURING\_PHASE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5125

___

### NONE

• `Readonly` **NONE**: `number`

#### Inherited from

SpeechSynthesisEvent.NONE

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5126

___

### bubbles

• `Readonly` **bubbles**: `boolean`

Returns true or false depending on how event was initialized. True if event goes through its target's ancestors in reverse tree order, and false otherwise.

#### Inherited from

SpeechSynthesisEvent.bubbles

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5063

___

### cancelBubble

• **cancelBubble**: `boolean`

#### Inherited from

SpeechSynthesisEvent.cancelBubble

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5064

___

### cancelable

• `Readonly` **cancelable**: `boolean`

Returns true or false depending on how event was initialized. Its return value does not always carry meaning, but true can indicate that part of the operation during which event was dispatched, can be canceled by invoking the preventDefault() method.

#### Inherited from

SpeechSynthesisEvent.cancelable

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5068

___

### charIndex

• `Readonly` **charIndex**: `number`

#### Inherited from

SpeechSynthesisEvent.charIndex

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14236

___

### charLength

• `Readonly` **charLength**: `number`

#### Inherited from

SpeechSynthesisEvent.charLength

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14237

___

### composed

• `Readonly` **composed**: `boolean`

Returns true or false depending on how event was initialized. True if event invokes listeners past a ShadowRoot node that is the root of its target, and false otherwise.

#### Inherited from

SpeechSynthesisEvent.composed

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5072

___

### currentTarget

• `Readonly` **currentTarget**: `EventTarget`

Returns the object whose event listener's callback is currently being invoked.

#### Inherited from

SpeechSynthesisEvent.currentTarget

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5076

___

### defaultPrevented

• `Readonly` **defaultPrevented**: `boolean`

Returns true if preventDefault() was invoked successfully to indicate cancelation, and false otherwise.

#### Inherited from

SpeechSynthesisEvent.defaultPrevented

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5080

___

### elapsedTime

• `Readonly` **elapsedTime**: `number`

#### Inherited from

SpeechSynthesisEvent.elapsedTime

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14238

___

### error

• `Readonly` **error**: [`SpeechSynthesisErrorCode`](../modules/akashaproject_design_system._internal_.md#speechsynthesiserrorcode)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14226

___

### eventPhase

• `Readonly` **eventPhase**: `number`

Returns the event's phase, which is one of NONE, CAPTURING_PHASE, AT_TARGET, and BUBBLING_PHASE.

#### Inherited from

SpeechSynthesisEvent.eventPhase

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5084

___

### isTrusted

• `Readonly` **isTrusted**: `boolean`

Returns true if event was dispatched by the user agent, and false otherwise.

#### Inherited from

SpeechSynthesisEvent.isTrusted

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5088

___

### name

• `Readonly` **name**: `string`

#### Inherited from

SpeechSynthesisEvent.name

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14239

___

### returnValue

• **returnValue**: `boolean`

**`deprecated`**

#### Inherited from

SpeechSynthesisEvent.returnValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5090

___

### srcElement

• `Readonly` **srcElement**: `EventTarget`

**`deprecated`**

#### Inherited from

SpeechSynthesisEvent.srcElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5092

___

### target

• `Readonly` **target**: `EventTarget`

Returns the object to which event is dispatched (its target).

#### Inherited from

SpeechSynthesisEvent.target

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5096

___

### timeStamp

• `Readonly` **timeStamp**: `number`

Returns the event's timestamp as the number of milliseconds measured relative to the time origin.

#### Inherited from

SpeechSynthesisEvent.timeStamp

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5100

___

### type

• `Readonly` **type**: `string`

Returns the type of event, e.g. "click", "hashchange", or "submit".

#### Inherited from

SpeechSynthesisEvent.type

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5104

___

### utterance

• `Readonly` **utterance**: [`SpeechSynthesisUtterance`](../modules/akashaproject_design_system._internal_.md#speechsynthesisutterance)

#### Inherited from

SpeechSynthesisEvent.utterance

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14240

## Methods

### composedPath

▸ **composedPath**(): `EventTarget`[]

Returns the invocation target objects of event's path (objects on which listeners will be invoked), except for any nodes in shadow trees of which the shadow root's mode is "closed" that are not reachable from event's currentTarget.

#### Returns

`EventTarget`[]

#### Inherited from

SpeechSynthesisEvent.composedPath

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

SpeechSynthesisEvent.initEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5110

___

### preventDefault

▸ **preventDefault**(): `void`

If invoked when the cancelable attribute value is true, and while executing a listener for the event with passive set to false, signals to the operation that caused event to be dispatched that it needs to be canceled.

#### Returns

`void`

#### Inherited from

SpeechSynthesisEvent.preventDefault

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5114

___

### stopImmediatePropagation

▸ **stopImmediatePropagation**(): `void`

Invoking this method prevents event from reaching any registered event listeners after the current one finishes running and, when dispatched in a tree, also prevents event from reaching any other objects.

#### Returns

`void`

#### Inherited from

SpeechSynthesisEvent.stopImmediatePropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5118

___

### stopPropagation

▸ **stopPropagation**(): `void`

When dispatched in a tree, invoking this method prevents event from reaching any objects other than the current object.

#### Returns

`void`

#### Inherited from

SpeechSynthesisEvent.stopPropagation

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5122
