[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / SyntheticEvent

# Interface: SyntheticEvent<T, E\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).SyntheticEvent

currentTarget - a reference to the element on which the event listener is registered.

target - a reference to the element from which the event was originally dispatched.
This might be a child element to the element on which the event listener is registered.
If you thought this should be `EventTarget & T`, see https://github.com/DefinitelyTyped/DefinitelyTyped/issues/11508#issuecomment-256045682

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |
| `E` | `Event` |

## Hierarchy

- [`BaseSyntheticEvent`](akashaproject_design_system._internal_.BaseSyntheticEvent.md)<`E`, `EventTarget` & `T`, `EventTarget`\>

  ↳ **`SyntheticEvent`**

  ↳↳ [`ChangeEvent`](akashaproject_design_system._internal_.ChangeEvent.md)

  ↳↳ [`UIEvent`](akashaproject_design_system._internal_.UIEvent.md)

  ↳↳ [`ClipboardEvent`](akashaproject_design_system._internal_.ClipboardEvent.md)

  ↳↳ [`CompositionEvent`](akashaproject_design_system._internal_.CompositionEvent.md)

  ↳↳ [`FocusEvent`](akashaproject_design_system._internal_.FocusEvent.md)

  ↳↳ [`FormEvent`](akashaproject_design_system._internal_.FormEvent.md)

  ↳↳ [`KeyboardEvent`](akashaproject_design_system._internal_.KeyboardEvent.md)

  ↳↳ [`AnimationEvent`](akashaproject_design_system._internal_.AnimationEvent.md)

  ↳↳ [`TransitionEvent`](akashaproject_design_system._internal_.TransitionEvent.md)

## Table of contents

### Properties

- [bubbles](akashaproject_design_system._internal_.SyntheticEvent.md#bubbles)
- [cancelable](akashaproject_design_system._internal_.SyntheticEvent.md#cancelable)
- [currentTarget](akashaproject_design_system._internal_.SyntheticEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.SyntheticEvent.md#defaultprevented)
- [eventPhase](akashaproject_design_system._internal_.SyntheticEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.SyntheticEvent.md#istrusted)
- [nativeEvent](akashaproject_design_system._internal_.SyntheticEvent.md#nativeevent)
- [target](akashaproject_design_system._internal_.SyntheticEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.SyntheticEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.SyntheticEvent.md#type)

### Methods

- [isDefaultPrevented](akashaproject_design_system._internal_.SyntheticEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.SyntheticEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.SyntheticEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.SyntheticEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.SyntheticEvent.md#stoppropagation)

## Properties

### bubbles

• **bubbles**: `boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[bubbles](akashaproject_design_system._internal_.BaseSyntheticEvent.md#bubbles)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### cancelable

• **cancelable**: `boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[cancelable](akashaproject_design_system._internal_.BaseSyntheticEvent.md#cancelable)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### currentTarget

• **currentTarget**: `EventTarget` & `T`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[currentTarget](akashaproject_design_system._internal_.BaseSyntheticEvent.md#currenttarget)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1147

___

### defaultPrevented

• **defaultPrevented**: `boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[defaultPrevented](akashaproject_design_system._internal_.BaseSyntheticEvent.md#defaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1151

___

### eventPhase

• **eventPhase**: `number`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[eventPhase](akashaproject_design_system._internal_.BaseSyntheticEvent.md#eventphase)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1152

___

### isTrusted

• **isTrusted**: `boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[isTrusted](akashaproject_design_system._internal_.BaseSyntheticEvent.md#istrusted)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1153

___

### nativeEvent

• **nativeEvent**: `E`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[nativeEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### target

• **target**: `EventTarget`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[target](akashaproject_design_system._internal_.BaseSyntheticEvent.md#target)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### timeStamp

• **timeStamp**: `number`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[timeStamp](akashaproject_design_system._internal_.BaseSyntheticEvent.md#timestamp)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### type

• **type**: `string`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[type](akashaproject_design_system._internal_.BaseSyntheticEvent.md#type)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1160

## Methods

### isDefaultPrevented

▸ **isDefaultPrevented**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[isDefaultPrevented](akashaproject_design_system._internal_.BaseSyntheticEvent.md#isdefaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1155

___

### isPropagationStopped

▸ **isPropagationStopped**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[isPropagationStopped](akashaproject_design_system._internal_.BaseSyntheticEvent.md#ispropagationstopped)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1157

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[persist](akashaproject_design_system._internal_.BaseSyntheticEvent.md#persist)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1158

___

### preventDefault

▸ **preventDefault**(): `void`

#### Returns

`void`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[preventDefault](akashaproject_design_system._internal_.BaseSyntheticEvent.md#preventdefault)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1154

___

### stopPropagation

▸ **stopPropagation**(): `void`

#### Returns

`void`

#### Inherited from

[BaseSyntheticEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md).[stopPropagation](akashaproject_design_system._internal_.BaseSyntheticEvent.md#stoppropagation)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1156
