[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / BaseSyntheticEvent

# Interface: BaseSyntheticEvent<E, C, T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).BaseSyntheticEvent

## Type parameters

| Name | Type |
| :------ | :------ |
| `E` | `object` |
| `C` | `any` |
| `T` | `any` |

## Hierarchy

- **`BaseSyntheticEvent`**

  ↳ [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)

## Table of contents

### Properties

- [bubbles](akashaproject_design_system._internal_.BaseSyntheticEvent.md#bubbles)
- [cancelable](akashaproject_design_system._internal_.BaseSyntheticEvent.md#cancelable)
- [currentTarget](akashaproject_design_system._internal_.BaseSyntheticEvent.md#currenttarget)
- [defaultPrevented](akashaproject_design_system._internal_.BaseSyntheticEvent.md#defaultprevented)
- [eventPhase](akashaproject_design_system._internal_.BaseSyntheticEvent.md#eventphase)
- [isTrusted](akashaproject_design_system._internal_.BaseSyntheticEvent.md#istrusted)
- [nativeEvent](akashaproject_design_system._internal_.BaseSyntheticEvent.md#nativeevent)
- [target](akashaproject_design_system._internal_.BaseSyntheticEvent.md#target)
- [timeStamp](akashaproject_design_system._internal_.BaseSyntheticEvent.md#timestamp)
- [type](akashaproject_design_system._internal_.BaseSyntheticEvent.md#type)

### Methods

- [isDefaultPrevented](akashaproject_design_system._internal_.BaseSyntheticEvent.md#isdefaultprevented)
- [isPropagationStopped](akashaproject_design_system._internal_.BaseSyntheticEvent.md#ispropagationstopped)
- [persist](akashaproject_design_system._internal_.BaseSyntheticEvent.md#persist)
- [preventDefault](akashaproject_design_system._internal_.BaseSyntheticEvent.md#preventdefault)
- [stopPropagation](akashaproject_design_system._internal_.BaseSyntheticEvent.md#stoppropagation)

## Properties

### bubbles

• **bubbles**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1149

___

### cancelable

• **cancelable**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1150

___

### currentTarget

• **currentTarget**: `C`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1147

___

### defaultPrevented

• **defaultPrevented**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1151

___

### eventPhase

• **eventPhase**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1152

___

### isTrusted

• **isTrusted**: `boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1153

___

### nativeEvent

• **nativeEvent**: `E`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1146

___

### target

• **target**: `T`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1148

___

### timeStamp

• **timeStamp**: `number`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1159

___

### type

• **type**: `string`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1160

## Methods

### isDefaultPrevented

▸ **isDefaultPrevented**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1155

___

### isPropagationStopped

▸ **isPropagationStopped**(): `boolean`

#### Returns

`boolean`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1157

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1158

___

### preventDefault

▸ **preventDefault**(): `void`

#### Returns

`void`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1154

___

### stopPropagation

▸ **stopPropagation**(): `void`

#### Returns

`void`

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:1156
