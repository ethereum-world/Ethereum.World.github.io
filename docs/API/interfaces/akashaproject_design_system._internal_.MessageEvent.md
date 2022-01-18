[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / MessageEvent

# Interface: MessageEvent<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).MessageEvent

A message received by a target object.

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `any` |

## Hierarchy

- `Event`

  ↳ **`MessageEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_design_system._internal_.MessageEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_design_system._internal_.MessageEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_design_system._internal_.MessageEvent.md#capturing_phase)
- [NONE](akashaproject_design_system._internal_.MessageEvent.md#none)
- [bubbles](akashaproject_design_system._internal_.MessageEvent.md#bubbles)
- [cancelBubble](akashaproject_design_system._internal_.MessageEvent.md#cancelbubble)
- [cancelable](akashaproject_design_system._internal_.MessageEvent.md#cancelable)
- [composed](akashaproject_design_system._internal_.MessageEvent.md#composed)
- [currentTarget](akashaproject_design_system._internal_.MessageEvent.md#currenttarget)
- [data](akashaproject_design_system._internal_.MessageEvent.md#data)
- [defaultPrevented](akashaproject_design_system._internal_.MessageEvent.md#defaultprevented)
- [eventPhase](akashaproject_design_system._internal_.MessageEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.MessageEvent.md#istrusted)
- [lastEventId](akashaproject_design_system._internal_.MessageEvent.md#lasteventid)
- [origin](akashaproject_design_system._internal_.MessageEvent.md#origin)
- [ports](akashaproject_design_system._internal_.MessageEvent.md#ports)
- [returnValue](akashaproject_design_system._internal_.MessageEvent.md#returnvalue)
- [source](akashaproject_design_system._internal_.MessageEvent.md#source)
- [srcElement](akashaproject_design_system._internal_.MessageEvent.md#srcelement)
- [target](akashaproject_design_system._internal_.MessageEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.MessageEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.MessageEvent.md#type)

### Methods

- [composedPath](akashaproject_design_system._internal_.MessageEvent.md#composedpath)
- [initEvent](akashaproject_design_system._internal_.MessageEvent.md#initevent)
- [initMessageEvent](akashaproject_design_system._internal_.MessageEvent.md#initmessageevent)
- [preventDefault](akashaproject_design_system._internal_.MessageEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_design_system._internal_.MessageEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_design_system._internal_.MessageEvent.md#stoppropagation)

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

### data

• `Readonly` **data**: `T`

Returns the data of the message.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10133

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

### lastEventId

• `Readonly` **lastEventId**: `string`

Returns the last event ID string, for server-sent events.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10137

___

### origin

• `Readonly` **origin**: `string`

Returns the origin of the message, for server-sent events and cross-document messaging.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10141

___

### ports

• `Readonly` **ports**: readonly [`MessagePort`](../modules/akashaproject_design_system._internal_.md#messageport)[]

Returns the MessagePort array sent with the message, for cross-document messaging and channel messaging.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10145

___

### returnValue

• **returnValue**: `boolean`

**`deprecated`**

#### Inherited from

Event.returnValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5090

___

### source

• `Readonly` **source**: [`MessageEventSource`](../modules/akashaproject_design_system._internal_.md#messageeventsource)

Returns the WindowProxy of the source window, for cross-document messaging, and the MessagePort being attached, in the connect event fired at SharedWorkerGlobalScope objects.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10149

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

### initMessageEvent

▸ **initMessageEvent**(`type`, `bubbles?`, `cancelable?`, `data?`, `origin?`, `lastEventId?`, `source?`, `ports?`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `bubbles?` | `boolean` |
| `cancelable?` | `boolean` |
| `data?` | `any` |
| `origin?` | `string` |
| `lastEventId?` | `string` |
| `source?` | [`MessageEventSource`](../modules/akashaproject_design_system._internal_.md#messageeventsource) |
| `ports?` | [`MessagePort`](../modules/akashaproject_design_system._internal_.md#messageport)[] |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10151

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
