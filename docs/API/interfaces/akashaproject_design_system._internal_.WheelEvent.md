[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / WheelEvent

# Interface: WheelEvent<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).WheelEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |

## Hierarchy

- [`MouseEvent`](akashaproject_design_system._internal_.MouseEvent.md)<`T`, [`NativeWheelEvent`](../modules/akashaproject_design_system._internal_.md#nativewheelevent)\>

  ↳ **`WheelEvent`**

## Table of contents

### Properties

- [altKey](akashaproject_design_system._internal_.WheelEvent.md#altkey)
- [bubbles](akashaproject_design_system._internal_.WheelEvent.md#bubbles)
- [button](akashaproject_design_system._internal_.WheelEvent.md#button)
- [buttons](akashaproject_design_system._internal_.WheelEvent.md#buttons)
- [cancelable](akashaproject_design_system._internal_.WheelEvent.md#cancelable)
- [clientX](akashaproject_design_system._internal_.WheelEvent.md#clientx)
- [clientY](akashaproject_design_system._internal_.WheelEvent.md#clienty)
- [ctrlKey](akashaproject_design_system._internal_.WheelEvent.md#ctrlkey)
- [currentTarget](akashaproject_design_system._internal_.WheelEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.WheelEvent.md#defaultprevented)
- [deltaMode](akashaproject_design_system._internal_.WheelEvent.md#deltamode)
- [deltaX](akashaproject_design_system._internal_.WheelEvent.md#deltax)
- [deltaY](akashaproject_design_system._internal_.WheelEvent.md#deltay)
- [deltaZ](akashaproject_design_system._internal_.WheelEvent.md#deltaz)
- [detail](akashaproject_design_system._internal_.WheelEvent.md#detail)
- [eventPhase](akashaproject_design_system._internal_.WheelEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.WheelEvent.md#istrusted)
- [metaKey](akashaproject_design_system._internal_.WheelEvent.md#metakey)
- [movementX](akashaproject_design_system._internal_.WheelEvent.md#movementx)
- [movementY](akashaproject_design_system._internal_.WheelEvent.md#movementy)
- [nativeEvent](akashaproject_design_system._internal_.WheelEvent.md#nativeevent)
- [pageX](akashaproject_design_system._internal_.WheelEvent.md#pagex)
- [pageY](akashaproject_design_system._internal_.WheelEvent.md#pagey)
- [relatedTarget](akashaproject_design_system._internal_.WheelEvent.md#relatedtarget)
- [screenX](akashaproject_design_system._internal_.WheelEvent.md#screenx)
- [screenY](akashaproject_design_system._internal_.WheelEvent.md#screeny)
- [shiftKey](akashaproject_design_system._internal_.WheelEvent.md#shiftkey)
- [target](akashaproject_design_system._internal_.WheelEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.WheelEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.WheelEvent.md#type)
- [view](akashaproject_design_system._internal_.WheelEvent.md#view)

### Methods

- [getModifierState](akashaproject_design_system._internal_.WheelEvent.md#getmodifierstate)
- [isDefaultPrevented](akashaproject_design_system._internal_.WheelEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.WheelEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.WheelEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.WheelEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.WheelEvent.md#stoppropagation)

## Properties

### altKey

• **altKey**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[altKey](akashaproject_design_system._internal_.MouseEvent.md#altkey)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1239

___

### bubbles

• **bubbles**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[bubbles](akashaproject_design_system._internal_.MouseEvent.md#bubbles)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### button

• **button**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[button](akashaproject_design_system._internal_.MouseEvent.md#button)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1240

___

### buttons

• **buttons**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[buttons](akashaproject_design_system._internal_.MouseEvent.md#buttons)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1241

___

### cancelable

• **cancelable**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[cancelable](akashaproject_design_system._internal_.MouseEvent.md#cancelable)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### clientX

• **clientX**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[clientX](akashaproject_design_system._internal_.MouseEvent.md#clientx)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1242

___

### clientY

• **clientY**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[clientY](akashaproject_design_system._internal_.MouseEvent.md#clienty)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1243

___

### ctrlKey

• **ctrlKey**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[ctrlKey](akashaproject_design_system._internal_.MouseEvent.md#ctrlkey)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1244

___

### currentTarget

• **currentTarget**: `EventTarget` & `T`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[currentTarget](akashaproject_design_system._internal_.MouseEvent.md#currenttarget)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1147

___

### defaultPrevented

• **defaultPrevented**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[defaultPrevented](akashaproject_design_system._internal_.MouseEvent.md#defaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1151

___

### deltaMode

• **deltaMode**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1280

___

### deltaX

• **deltaX**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1281

___

### deltaY

• **deltaY**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1282

___

### deltaZ

• **deltaZ**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1283

___

### detail

• **detail**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[detail](akashaproject_design_system._internal_.MouseEvent.md#detail)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1275

___

### eventPhase

• **eventPhase**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[eventPhase](akashaproject_design_system._internal_.MouseEvent.md#eventphase)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1152

___

### isTrusted

• **isTrusted**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[isTrusted](akashaproject_design_system._internal_.MouseEvent.md#istrusted)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1153

___

### metaKey

• **metaKey**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[metaKey](akashaproject_design_system._internal_.MouseEvent.md#metakey)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1249

___

### movementX

• **movementX**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[movementX](akashaproject_design_system._internal_.MouseEvent.md#movementx)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1250

___

### movementY

• **movementY**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[movementY](akashaproject_design_system._internal_.MouseEvent.md#movementy)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1251

___

### nativeEvent

• **nativeEvent**: `WheelEvent`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[nativeEvent](akashaproject_design_system._internal_.MouseEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### pageX

• **pageX**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[pageX](akashaproject_design_system._internal_.MouseEvent.md#pagex)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1252

___

### pageY

• **pageY**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[pageY](akashaproject_design_system._internal_.MouseEvent.md#pagey)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1253

___

### relatedTarget

• **relatedTarget**: `EventTarget`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[relatedTarget](akashaproject_design_system._internal_.MouseEvent.md#relatedtarget)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1254

___

### screenX

• **screenX**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[screenX](akashaproject_design_system._internal_.MouseEvent.md#screenx)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1255

___

### screenY

• **screenY**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[screenY](akashaproject_design_system._internal_.MouseEvent.md#screeny)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1256

___

### shiftKey

• **shiftKey**: `boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[shiftKey](akashaproject_design_system._internal_.MouseEvent.md#shiftkey)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1257

___

### target

• **target**: `EventTarget`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[target](akashaproject_design_system._internal_.MouseEvent.md#target)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### timeStamp

• **timeStamp**: `number`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[timeStamp](akashaproject_design_system._internal_.MouseEvent.md#timestamp)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### type

• **type**: `string`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[type](akashaproject_design_system._internal_.MouseEvent.md#type)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1160

___

### view

• **view**: [`AbstractView`](akashaproject_design_system._internal_.AbstractView.md)

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[view](akashaproject_design_system._internal_.MouseEvent.md#view)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1276

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

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[getModifierState](akashaproject_design_system._internal_.MouseEvent.md#getmodifierstate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1248

___

### isDefaultPrevented

▸ **isDefaultPrevented**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[isDefaultPrevented](akashaproject_design_system._internal_.MouseEvent.md#isdefaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1155

___

### isPropagationStopped

▸ **isPropagationStopped**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[isPropagationStopped](akashaproject_design_system._internal_.MouseEvent.md#ispropagationstopped)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1157

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[persist](akashaproject_design_system._internal_.MouseEvent.md#persist)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1158

___

### preventDefault

▸ **preventDefault**(): `void`

#### Returns

`void`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[preventDefault](akashaproject_design_system._internal_.MouseEvent.md#preventdefault)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1154

___

### stopPropagation

▸ **stopPropagation**(): `void`

#### Returns

`void`

#### Inherited from

[MouseEvent](akashaproject_design_system._internal_.MouseEvent.md).[stopPropagation](akashaproject_design_system._internal_.MouseEvent.md#stoppropagation)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1156
