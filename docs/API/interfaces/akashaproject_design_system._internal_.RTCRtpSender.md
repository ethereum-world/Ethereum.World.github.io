[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / RTCRtpSender

# Interface: RTCRtpSender

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).RTCRtpSender

Provides the ability to control and obtain details about how a particular MediaStreamTrack is encoded and sent to a remote peer.

## Table of contents

### Properties

- [dtmf](akashaproject_design_system._internal_.RTCRtpSender.md#dtmf)
- [track](akashaproject_design_system._internal_.RTCRtpSender.md#track)
- [transport](akashaproject_design_system._internal_.RTCRtpSender.md#transport)

### Methods

- [getParameters](akashaproject_design_system._internal_.RTCRtpSender.md#getparameters)
- [getStats](akashaproject_design_system._internal_.RTCRtpSender.md#getstats)
- [replaceTrack](akashaproject_design_system._internal_.RTCRtpSender.md#replacetrack)
- [setParameters](akashaproject_design_system._internal_.RTCRtpSender.md#setparameters)
- [setStreams](akashaproject_design_system._internal_.RTCRtpSender.md#setstreams)

## Properties

### dtmf

• `Readonly` **dtmf**: [`RTCDTMFSender`](../modules/akashaproject_design_system._internal_.md#rtcdtmfsender)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11854

___

### track

• `Readonly` **track**: [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11855

___

### transport

• `Readonly` **transport**: [`RTCDtlsTransport`](../modules/akashaproject_design_system._internal_.md#rtcdtlstransport)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11856

## Methods

### getParameters

▸ **getParameters**(): [`RTCRtpSendParameters`](akashaproject_design_system._internal_.RTCRtpSendParameters.md)

#### Returns

[`RTCRtpSendParameters`](akashaproject_design_system._internal_.RTCRtpSendParameters.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11857

___

### getStats

▸ **getStats**(): `Promise`<[`RTCStatsReport`](../modules/akashaproject_design_system._internal_.md#rtcstatsreport)\>

#### Returns

`Promise`<[`RTCStatsReport`](../modules/akashaproject_design_system._internal_.md#rtcstatsreport)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11858

___

### replaceTrack

▸ **replaceTrack**(`withTrack`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `withTrack` | [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11859

___

### setParameters

▸ **setParameters**(`parameters`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `parameters` | [`RTCRtpSendParameters`](akashaproject_design_system._internal_.RTCRtpSendParameters.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11860

___

### setStreams

▸ **setStreams**(...`streams`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...streams` | [`MediaStream`](../modules/akashaproject_design_system._internal_.md#mediastream)[] |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11861
