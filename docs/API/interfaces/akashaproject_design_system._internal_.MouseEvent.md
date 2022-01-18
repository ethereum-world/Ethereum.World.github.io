[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / MouseEvent

# Interface: MouseEvent<T, E\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).MouseEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |
| `E` | [`NativeMouseEvent`](../modules/akashaproject_design_system._internal_.md#nativemouseevent) |

## Hierarchy

- [`UIEvent`](akashaproject_design_system._internal_.UIEvent.md)<`T`, `E`\>

  ↳ **`MouseEvent`**

  ↳↳ [`DragEvent`](akashaproject_design_system._internal_.DragEvent.md)

  ↳↳ [`PointerEvent`](akashaproject_design_system._internal_.PointerEvent.md)

  ↳↳ [`WheelEvent`](akashaproject_design_system._internal_.WheelEvent.md)

## Table of contents

### Properties

- [altKey](akashaproject_design_system._internal_.MouseEvent.md#altkey)
- [bubbles](akashaproject_design_system._internal_.MouseEvent.md#bubbles)
- [button](akashaproject_design_system._internal_.MouseEvent.md#button)
- [buttons](akashaproject_design_system._internal_.MouseEvent.md#buttons)
- [cancelable](akashaproject_design_system._internal_.MouseEvent.md#cancelable)
- [clientX](akashaproject_design_system._internal_.MouseEvent.md#clientx)
- [clientY](akashaproject_design_system._internal_.MouseEvent.md#clienty)
- [ctrlKey](akashaproject_design_system._internal_.MouseEvent.md#ctrlkey)
- [currentTarget](akashaproject_design_system._internal_.MouseEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.MouseEvent.md#defaultprevented)
- [detail](akashaproject_design_system._internal_.MouseEvent.md#detail)
- [eventPhase](akashaproject_design_system._internal_.MouseEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.MouseEvent.md#istrusted)
- [metaKey](akashaproject_design_system._internal_.MouseEvent.md#metakey)
- [movementX](akashaproject_design_system._internal_.MouseEvent.md#movementx)
- [movementY](akashaproject_design_system._internal_.MouseEvent.md#movementy)
- [nativeEvent](akashaproject_design_system._internal_.MouseEvent.md#nativeevent)
- [pageX](akashaproject_design_system._internal_.MouseEvent.md#pagex)
- [pageY](akashaproject_design_system._internal_.MouseEvent.md#pagey)
- [relatedTarget](akashaproject_design_system._internal_.MouseEvent.md#relatedtarget)
- [screenX](akashaproject_design_system._internal_.MouseEvent.md#screenx)
- [screenY](akashaproject_design_system._internal_.MouseEvent.md#screeny)
- [shiftKey](akashaproject_design_system._internal_.MouseEvent.md#shiftkey)
- [target](akashaproject_design_system._internal_.MouseEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.MouseEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.MouseEvent.md#type)
- [view](akashaproject_design_system._internal_.MouseEvent.md#view)

### Methods

- [getModifierState](akashaproject_design_system._internal_.MouseEvent.md#getmodifierstate)
- [isDefaultPrevented](akashaproject_design_system._internal_.MouseEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.MouseEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.MouseEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.MouseEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.MouseEvent.md#stoppropagation)

## Properties

### altKey

• **altKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1239

___

### bubbles

• **bubbles**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[bubbles](akashaproject_design_system._internal_.UIEvent.md#bubbles)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### button

• **button**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1240

___

### buttons

• **buttons**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1241

___

### cancelable

• **cancelable**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[cancelable](akashaproject_design_system._internal_.UIEvent.md#cancelable)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### clientX

• **clientX**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1242

___

### clientY

• **clientY**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1243

___

### ctrlKey

• **ctrlKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1244

___

### currentTarget

• **currentTarget**: `EventTarget` & `T`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[currentTarget](akashaproject_design_system._internal_.UIEvent.md#currenttarget)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1147

___

### defaultPrevented

• **defaultPrevented**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[defaultPrevented](akashaproject_design_system._internal_.UIEvent.md#defaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1151

___

### detail

• **detail**: `number`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[detail](akashaproject_design_system._internal_.UIEvent.md#detail)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1275

___

### eventPhase

• **eventPhase**: `number`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[eventPhase](akashaproject_design_system._internal_.UIEvent.md#eventphase)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1152

___

### isTrusted

• **isTrusted**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[isTrusted](akashaproject_design_system._internal_.UIEvent.md#istrusted)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1153

___

### metaKey

• **metaKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1249

___

### movementX

• **movementX**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1250

___

### movementY

• **movementY**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1251

___

### nativeEvent

• **nativeEvent**: `E`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[nativeEvent](akashaproject_design_system._internal_.UIEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### pageX

• **pageX**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1252

___

### pageY

• **pageY**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1253

___

### relatedTarget

• **relatedTarget**: `EventTarget`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1254

___

### screenX

• **screenX**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1255

___

### screenY

• **screenY**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1256

___

### shiftKey

• **shiftKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1257

___

### target

• **target**: `EventTarget`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[target](akashaproject_design_system._internal_.UIEvent.md#target)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### timeStamp

• **timeStamp**: `number`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[timeStamp](akashaproject_design_system._internal_.UIEvent.md#timestamp)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### type

• **type**: `string`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[type](akashaproject_design_system._internal_.UIEvent.md#type)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1160

___

### view

• **view**: [`AbstractView`](akashaproject_design_system._internal_.AbstractView.md)

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[view](akashaproject_design_system._internal_.UIEvent.md#view)

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

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1248

___

### isDefaultPrevented

▸ **isDefaultPrevented**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[isDefaultPrevented](akashaproject_design_system._internal_.UIEvent.md#isdefaultprevented)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1155

___

### isPropagationStopped

▸ **isPropagationStopped**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[isPropagationStopped](akashaproject_design_system._internal_.UIEvent.md#ispropagationstopped)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1157

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[persist](akashaproject_design_system._internal_.UIEvent.md#persist)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1158

___

### preventDefault

▸ **preventDefault**(): `void`

#### Returns

`void`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[preventDefault](akashaproject_design_system._internal_.UIEvent.md#preventdefault)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1154

___

### stopPropagation

▸ **stopPropagation**(): `void`

#### Returns

`void`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[stopPropagation](akashaproject_design_system._internal_.UIEvent.md#stoppropagation)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1156
