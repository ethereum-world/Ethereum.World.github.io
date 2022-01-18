[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / AudioBuffer

# Interface: AudioBuffer

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).AudioBuffer

A short audio asset residing in memory, created from an audio file using the AudioContext.decodeAudioData() method, or from raw data using AudioContext.createBuffer(). Once put into an AudioBuffer, the audio can then be played by being passed into an AudioBufferSourceNode.

## Table of contents

### Properties

- [duration](akashaproject_design_system._internal_.AudioBuffer.md#duration)
- [length](akashaproject_design_system._internal_.AudioBuffer.md#length)
- [numberOfChannels](akashaproject_design_system._internal_.AudioBuffer.md#numberofchannels)
- [sampleRate](akashaproject_design_system._internal_.AudioBuffer.md#samplerate)

### Methods

- [copyFromChannel](akashaproject_design_system._internal_.AudioBuffer.md#copyfromchannel)
- [copyToChannel](akashaproject_design_system._internal_.AudioBuffer.md#copytochannel)
- [getChannelData](akashaproject_design_system._internal_.AudioBuffer.md#getchanneldata)

## Properties

### duration

• `Readonly` **duration**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2106

___

### length

• `Readonly` **length**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2107

___

### numberOfChannels

• `Readonly` **numberOfChannels**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2108

___

### sampleRate

• `Readonly` **sampleRate**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2109

## Methods

### copyFromChannel

▸ **copyFromChannel**(`destination`, `channelNumber`, `bufferOffset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `destination` | `Float32Array` |
| `channelNumber` | `number` |
| `bufferOffset?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2110

___

### copyToChannel

▸ **copyToChannel**(`source`, `channelNumber`, `bufferOffset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | `Float32Array` |
| `channelNumber` | `number` |
| `bufferOffset?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2111

___

### getChannelData

▸ **getChannelData**(`channel`): `Float32Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `channel` | `number` |

#### Returns

`Float32Array`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2112
