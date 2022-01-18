[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / KeyboardEvent

# Interface: KeyboardEvent<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).KeyboardEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |

## Hierarchy

- [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`T`, [`NativeKeyboardEvent`](../modules/akashaproject_design_system._internal_.md#nativekeyboardevent)\>

  ↳ **`KeyboardEvent`**

## Table of contents

### Properties

- [altKey](akashaproject_design_system._internal_.KeyboardEvent.md#altkey)
- [bubbles](akashaproject_design_system._internal_.KeyboardEvent.md#bubbles)
- [cancelable](akashaproject_design_system._internal_.KeyboardEvent.md#cancelable)
- [charCode](akashaproject_design_system._internal_.KeyboardEvent.md#charcode)
- [code](akashaproject_design_system._internal_.KeyboardEvent.md#code)
- [ctrlKey](akashaproject_design_system._internal_.KeyboardEvent.md#ctrlkey)
- [currentTarget](akashaproject_design_system._internal_.KeyboardEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.KeyboardEvent.md#defaultprevented)
- [eventPhase](akashaproject_design_system._internal_.KeyboardEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.KeyboardEvent.md#istrusted)
- [key](akashaproject_design_system._internal_.KeyboardEvent.md#key)
- [keyCode](akashaproject_design_system._internal_.KeyboardEvent.md#keycode)
- [locale](akashaproject_design_system._internal_.KeyboardEvent.md#locale)
- [location](akashaproject_design_system._internal_.KeyboardEvent.md#location)
- [metaKey](akashaproject_design_system._internal_.KeyboardEvent.md#metakey)
- [nativeEvent](akashaproject_design_system._internal_.KeyboardEvent.md#nativeevent)
- [repeat](akashaproject_design_system._internal_.KeyboardEvent.md#repeat)
- [shiftKey](akashaproject_design_system._internal_.KeyboardEvent.md#shiftkey)
- [target](akashaproject_design_system._internal_.KeyboardEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.KeyboardEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.KeyboardEvent.md#type)
- [which](akashaproject_design_system._internal_.KeyboardEvent.md#which)

### Methods

- [getModifierState](akashaproject_design_system._internal_.KeyboardEvent.md#getmodifierstate)
- [isDefaultPrevented](akashaproject_design_system._internal_.KeyboardEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.KeyboardEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.KeyboardEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.KeyboardEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.KeyboardEvent.md#stoppropagation)

## Properties

### altKey

• **altKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1214

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

### charCode

• **charCode**: `number`

**`deprecated`**

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1216

___

### code

• **code**: `string`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1218

___

### ctrlKey

• **ctrlKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1217

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

### key

• **key**: `string`

See the [DOM Level 3 Events spec](https://www.w3.org/TR/uievents-key/#named-key-attribute-values). for possible values

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1226

___

### keyCode

• **keyCode**: `number`

**`deprecated`**

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1228

___

### locale

• **locale**: `string`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1229

___

### location

• **location**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1230

___

### metaKey

• **metaKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1231

___

### nativeEvent

• **nativeEvent**: `KeyboardEvent`

#### Inherited from

[SyntheticEvent](akashaproject_design_system._internal_.SyntheticEvent.md).[nativeEvent](akashaproject_design_system._internal_.SyntheticEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### repeat

• **repeat**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1232

___

### shiftKey

• **shiftKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1233

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

___

### which

• **which**: `number`

**`deprecated`**

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1235

## Methods

### getModifierState

▸ **getModifierState**(`key`): `boolean`

See [DOM Level 3 Events spec](https://www.w3.org/TR/uievents-key/#keys-modifier). for a list of valid (case-sensitive) arguments to this method.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1222

___

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
