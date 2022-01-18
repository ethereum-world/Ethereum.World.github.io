[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SecurityPolicyViolationEvent

# Interface: SecurityPolicyViolationEvent

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SecurityPolicyViolationEvent

Inherits from Event, and represents the event object of an event sent on a document or worker when its content security policy is violated.

## Hierarchy

- `Event`

  ↳ **`SecurityPolicyViolationEvent`**

## Table of contents

### Properties

- [AT\_TARGET](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#at_target)
- [BUBBLING\_PHASE](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#bubbling_phase)
- [CAPTURING\_PHASE](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#capturing_phase)
- [NONE](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#none)
- [blockedURI](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#blockeduri)
- [bubbles](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#bubbles)
- [cancelBubble](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#cancelbubble)
- [cancelable](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#cancelable)
- [columnNumber](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#columnnumber)
- [composed](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#composed)
- [currentTarget](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#currenttarget)
- [defaultPrevented](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#defaultprevented)
- [disposition](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#disposition)
- [documentURI](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#documenturi)
- [effectiveDirective](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#effectivedirective)
- [eventPhase](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#eventphase)
- [isTrusted](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#istrusted)
- [lineNumber](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#linenumber)
- [originalPolicy](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#originalpolicy)
- [referrer](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#referrer)
- [returnValue](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#returnvalue)
- [sample](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#sample)
- [sourceFile](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#sourcefile)
- [srcElement](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#srcelement)
- [statusCode](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#statuscode)
- [target](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#target)
- [timeStamp](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#timestamp)
- [type](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#type)
- [violatedDirective](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#violateddirective)

### Methods

- [composedPath](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#composedpath)
- [initEvent](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#initevent)
- [preventDefault](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#preventdefault)
- [stopImmediatePropagation](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#stopimmediatepropagation)
- [stopPropagation](akashaproject_ui_awf_testing_utils._internal_.SecurityPolicyViolationEvent.md#stoppropagation)

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

### blockedURI

• `Readonly` **blockedURI**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13945

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

### columnNumber

• `Readonly` **columnNumber**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13946

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

### disposition

• `Readonly` **disposition**: [`SecurityPolicyViolationEventDisposition`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#securitypolicyviolationeventdisposition)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13947

___

### documentURI

• `Readonly` **documentURI**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13948

___

### effectiveDirective

• `Readonly` **effectiveDirective**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13949

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

### lineNumber

• `Readonly` **lineNumber**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13950

___

### originalPolicy

• `Readonly` **originalPolicy**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13951

___

### referrer

• `Readonly` **referrer**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13952

___

### returnValue

• **returnValue**: `boolean`

**`deprecated`**

#### Inherited from

Event.returnValue

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5090

___

### sample

• `Readonly` **sample**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13953

___

### sourceFile

• `Readonly` **sourceFile**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13954

___

### srcElement

• `Readonly` **srcElement**: `EventTarget`

**`deprecated`**

#### Inherited from

Event.srcElement

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5092

___

### statusCode

• `Readonly` **statusCode**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13955

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

### violatedDirective

• `Readonly` **violatedDirective**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13956

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
