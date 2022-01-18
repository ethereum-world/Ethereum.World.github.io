[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / CloseEvent

# Interface: CloseEvent

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).CloseEvent

A CloseEvent is sent to clients using WebSockets when the connection is closed. This is delivered to the listener indicated by the WebSocket object's onclose attribute.

## Hierarchy

- `Event`

  ↳ **`CloseEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#capturing_phase)
- [NONE](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#none)
- [bubbles](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#bubbles)
- [cancelBubble](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#cancelbubble)
- [cancelable](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#cancelable)
- [code](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#code)
- [composed](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#composed)
- [currentTarget](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#currenttarget)
- [defaultPrevented](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#defaultprevented)
- [eventPhase](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#eventphase)
- [isTrusted](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#istrusted)
- [reason](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#reason)
- [returnValue](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#returnvalue)
- [srcElement](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#srcelement)
- [target](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#target)
- [timeStamp](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#timestamp)
- [type](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#type)
- [wasClean](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#wasclean)

### Methods

- [composedPath](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#composedpath)
- [initEvent](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#initevent)
- [preventDefault](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_ui_awf_testing_utils._internal_.CloseEvent.md#stoppropagation)

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

### code

• `Readonly` **code**: `number`

Returns the WebSocket connection close code provided by the server.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3551

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

### isTrusted

• `Readonly` **isTrusted**: `boolean`

Returns true if event was dispatched by the user agent, and false otherwise.

#### Inherited from

Event.isTrusted

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5088

___

### reason

• `Readonly` **reason**: `string`

Returns the WebSocket connection close reason provided by the server.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3555

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

___

### wasClean

• `Readonly` **wasClean**: `boolean`

Returns true if the connection closed cleanly; false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3559

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
