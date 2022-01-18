[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / TouchEvent

# Interface: TouchEvent<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).TouchEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `Element` |

## Hierarchy

- [`UIEvent`](akashaproject_design_system._internal_.UIEvent.md)<`T`, [`NativeTouchEvent`](../modules/akashaproject_design_system._internal_.md#nativetouchevent)\>

  ↳ **`TouchEvent`**

## Table of contents

### Properties

- [altKey](akashaproject_design_system._internal_.TouchEvent.md#altkey)
- [bubbles](akashaproject_design_system._internal_.TouchEvent.md#bubbles)
- [cancelable](akashaproject_design_system._internal_.TouchEvent.md#cancelable)
- [changedTouches](akashaproject_design_system._internal_.TouchEvent.md#changedtouches)
- [ctrlKey](akashaproject_design_system._internal_.TouchEvent.md#ctrlkey)
- [currentTarget](akashaproject_design_system._internal_.TouchEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.TouchEvent.md#defaultprevented)
- [detail](akashaproject_design_system._internal_.TouchEvent.md#detail)
- [eventPhase](akashaproject_design_system._internal_.TouchEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.TouchEvent.md#istrusted)
- [metaKey](akashaproject_design_system._internal_.TouchEvent.md#metakey)
- [nativeEvent](akashaproject_design_system._internal_.TouchEvent.md#nativeevent)
- [shiftKey](akashaproject_design_system._internal_.TouchEvent.md#shiftkey)
- [target](akashaproject_design_system._internal_.TouchEvent.md#target)
- [targetTouches](akashaproject_design_system._internal_.TouchEvent.md#targettouches)
- [timeStamp](akashaproject_design_system._internal_.TouchEvent.md#timestamp)
- [touches](akashaproject_design_system._internal_.TouchEvent.md#touches)
- [type](akashaproject_design_system._internal_.TouchEvent.md#type)
- [view](akashaproject_design_system._internal_.TouchEvent.md#view)

### Methods

- [getModifierState](akashaproject_design_system._internal_.TouchEvent.md#getmodifierstate)
- [isDefaultPrevented](akashaproject_design_system._internal_.TouchEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.TouchEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.TouchEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.TouchEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.TouchEvent.md#stoppropagation)

## Properties

### altKey

• **altKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1261

___

### bubbles

• **bubbles**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[bubbles](akashaproject_design_system._internal_.UIEvent.md#bubbles)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### cancelable

• **cancelable**: `boolean`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[cancelable](akashaproject_design_system._internal_.UIEvent.md#cancelable)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### changedTouches

• **changedTouches**: [`TouchList`](akashaproject_design_system._internal_.TouchList.md)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1262

___

### ctrlKey

• **ctrlKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1263

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

ui/design/node_modules/@types/react/index.d.ts:1268

___

### nativeEvent

• **nativeEvent**: `TouchEvent`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[nativeEvent](akashaproject_design_system._internal_.UIEvent.md#nativeevent)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### shiftKey

• **shiftKey**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1269

___

### target

• **target**: `EventTarget`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[target](akashaproject_design_system._internal_.UIEvent.md#target)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### targetTouches

• **targetTouches**: [`TouchList`](akashaproject_design_system._internal_.TouchList.md)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1270

___

### timeStamp

• **timeStamp**: `number`

#### Inherited from

[UIEvent](akashaproject_design_system._internal_.UIEvent.md).[timeStamp](akashaproject_design_system._internal_.UIEvent.md#timestamp)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### touches

• **touches**: [`TouchList`](akashaproject_design_system._internal_.TouchList.md)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1271

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

ui/design/node_modules/@types/react/index.d.ts:1267

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
