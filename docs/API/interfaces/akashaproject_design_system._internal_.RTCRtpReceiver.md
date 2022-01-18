[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / RTCRtpReceiver

# Interface: RTCRtpReceiver

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).RTCRtpReceiver

This WebRTC API interface manages the reception and decoding of data for a MediaStreamTrack on an RTCPeerConnection.

## Table of contents

### Properties

- [track](akashaproject_design_system._internal_.RTCRtpReceiver.md#track)
- [transport](akashaproject_design_system._internal_.RTCRtpReceiver.md#transport)

### Methods

- [getContributingSources](akashaproject_design_system._internal_.RTCRtpReceiver.md#getcontributingsources)
- [getParameters](akashaproject_design_system._internal_.RTCRtpReceiver.md#getparameters)
- [getStats](akashaproject_design_system._internal_.RTCRtpReceiver.md#getstats)
- [getSynchronizationSources](akashaproject_design_system._internal_.RTCRtpReceiver.md#getsynchronizationsources)

## Properties

### track

• `Readonly` **track**: [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11838

___

### transport

• `Readonly` **transport**: [`RTCDtlsTransport`](../modules/akashaproject_design_system._internal_.md#rtcdtlstransport)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11839

## Methods

### getContributingSources

▸ **getContributingSources**(): [`RTCRtpContributingSource`](akashaproject_design_system._internal_.RTCRtpContributingSource.md)[]

#### Returns

[`RTCRtpContributingSource`](akashaproject_design_system._internal_.RTCRtpContributingSource.md)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11840

___

### getParameters

▸ **getParameters**(): [`RTCRtpReceiveParameters`](akashaproject_design_system._internal_.RTCRtpReceiveParameters.md)

#### Returns

[`RTCRtpReceiveParameters`](akashaproject_design_system._internal_.RTCRtpReceiveParameters.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11841

___

### getStats

▸ **getStats**(): `Promise`<[`RTCStatsReport`](../modules/akashaproject_design_system._internal_.md#rtcstatsreport)\>

#### Returns

`Promise`<[`RTCStatsReport`](../modules/akashaproject_design_system._internal_.md#rtcstatsreport)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11842

___

### getSynchronizationSources

▸ **getSynchronizationSources**(): [`RTCRtpSynchronizationSource`](akashaproject_design_system._internal_.RTCRtpSynchronizationSource.md)[]

#### Returns

[`RTCRtpSynchronizationSource`](akashaproject_design_system._internal_.RTCRtpSynchronizationSource.md)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11843
