[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / AnimationEvent

# Interface: AnimationEvent<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).AnimationEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |

## Hierarchy

- [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`T`, [`NativeAnimationEvent`](../modules/akashaproject_design_system._internal_.md#nativeanimationevent)\>

  ↳ **`AnimationEvent`**

## Table of contents

### Properties

- [animationName](akashaproject_design_system._internal_.AnimationEvent.md#animationname)
- [bubbles](akashaproject_design_system._internal_.AnimationEvent.md#bubbles)
- [cancelable](akashaproject_design_system._internal_.AnimationEvent.md#cancelable)
- [currentTarget](akashaproject_design_system._internal_.AnimationEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.AnimationEvent.md#defaultprevented)
- [elapsedTime](akashaproject_design_system._internal_.AnimationEvent.md#elapsedtime)
- [eventPhase](akashaproject_design_system._internal_.AnimationEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.AnimationEvent.md#istrusted)
- [nativeEvent](akashaproject_design_system._internal_.AnimationEvent.md#nativeevent)
- [pseudoElement](akashaproject_design_system._internal_.AnimationEvent.md#pseudoelement)
- [target](akashaproject_design_system._internal_.AnimationEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.AnimationEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.AnimationEvent.md#type)

### Methods

- [isDefaultPrevented](akashaproject_design_system._internal_.AnimationEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.AnimationEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.AnimationEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.AnimationEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.AnimationEvent.md#stoppropagation)

## Properties

### animationName

• **animationName**: `string`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1287

___

### bubbles

• **bubbles**: `boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[bubbles](akashaproject_design_system._internal_.SyntheticEvent.md#bubbles)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### cancelable

• **cancelable**: `boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[cancelable](akashaproject_design_system._internal_.SyntheticEvent.md#cancelable)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### currentTarget

• **currentTarget**: `EventTarget` & `T`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[currentTarget](akashaproject_design_system._internal_.SyntheticEvent.md#currenttarget)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1147

___

### defaultPrevented

• **defaultPrevented**: `boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[defaultPrevented](akashaproject_design_system._internal_.SyntheticEvent.md#defaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1151

___

### elapsedTime

• **elapsedTime**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1288

___

### eventPhase

• **eventPhase**: `number`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[eventPhase](akashaproject_design_system._internal_.SyntheticEvent.md#eventphase)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1152

___

### isTrusted

• **isTrusted**: `boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[isTrusted](akashaproject_design_system._internal_.SyntheticEvent.md#istrusted)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1153

___

### nativeEvent

• **nativeEvent**: `AnimationEvent`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[nativeEvent](akashaproject_design_system._internal_.SyntheticEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### pseudoElement

• **pseudoElement**: `string`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1289

___

### target

• **target**: `EventTarget`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[target](akashaproject_design_system._internal_.SyntheticEvent.md#target)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### timeStamp

• **timeStamp**: `number`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[timeStamp](akashaproject_design_system._internal_.SyntheticEvent.md#timestamp)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### type

• **type**: `string`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[type](akashaproject_design_system._internal_.SyntheticEvent.md#type)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1160

## Methods

### isDefaultPrevented

▸ **isDefaultPrevented**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[isDefaultPrevented](akashaproject_design_system._internal_.SyntheticEvent.md#isdefaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1155

___

### isPropagationStopped

▸ **isPropagationStopped**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[isPropagationStopped](akashaproject_design_system._internal_.SyntheticEvent.md#ispropagationstopped)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1157

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[persist](akashaproject_design_system._internal_.SyntheticEvent.md#persist)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1158

___

### preventDefault

▸ **preventDefault**(): `void`

#### Returns

`void`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[preventDefault](akashaproject_design_system._internal_.SyntheticEvent.md#preventdefault)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1154

___

### stopPropagation

▸ **stopPropagation**(): `void`

#### Returns

`void`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[stopPropagation](akashaproject_design_system._internal_.SyntheticEvent.md#stoppropagation)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1156
