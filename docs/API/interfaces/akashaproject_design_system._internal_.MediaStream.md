[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / MediaStream

# Interface: MediaStream

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).MediaStream

A stream of media content. A stream consists of several tracks such as video or audio tracks. Each track is specified as an instance of MediaStreamTrack.

## Hierarchy

- `EventTarget`

  ↳ **`MediaStream`**

## Table of contents

### Properties

- [active](akashaproject_design_system._internal_.MediaStream.md#active)
- [id](akashaproject_design_system._internal_.MediaStream.md#id)
- [onaddtrack](akashaproject_design_system._internal_.MediaStream.md#onaddtrack)
- [onremovetrack](akashaproject_design_system._internal_.MediaStream.md#onremovetrack)

### Methods

- [addEventListener](akashaproject_design_system._internal_.MediaStream.md#addeventlistener)
- [addTrack](akashaproject_design_system._internal_.MediaStream.md#addtrack)
- [clone](akashaproject_design_system._internal_.MediaStream.md#clone)
- [dispatchEvent](akashaproject_design_system._internal_.MediaStream.md#dispatchevent)
- [getAudioTracks](akashaproject_design_system._internal_.MediaStream.md#getaudiotracks)
- [getTrackById](akashaproject_design_system._internal_.MediaStream.md#gettrackbyid)
- [getTracks](akashaproject_design_system._internal_.MediaStream.md#gettracks)
- [getVideoTracks](akashaproject_design_system._internal_.MediaStream.md#getvideotracks)
- [removeEventListener](akashaproject_design_system._internal_.MediaStream.md#removeeventlistener)
- [removeTrack](akashaproject_design_system._internal_.MediaStream.md#removetrack)

## Properties

### active

• `Readonly` **active**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10023

___

### id

• `Readonly` **id**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10024

___

### onaddtrack

• **onaddtrack**: (`ev`: [`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10025

___

### onremovetrack

• **onremovetrack**: (`ev`: [`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MediaStreamTrackEvent`](../modules/akashaproject_design_system._internal_.md#mediastreamtrackevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10026

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaStreamEventMap`](akashaproject_design_system._internal_.MediaStreamEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaStreamEventMap`](akashaproject_design_system._internal_.MediaStreamEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10034

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10035

___

### addTrack

▸ **addTrack**(`track`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `track` | [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10027

___

### clone

▸ **clone**(): [`MediaStream`](../modules/akashaproject_design_system._internal_.md#mediastream)

#### Returns

[`MediaStream`](../modules/akashaproject_design_system._internal_.md#mediastream)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10028

___

### dispatchEvent

▸ **dispatchEvent**(`event`): `boolean`

Dispatches a synthetic event event to target and returns true if either event's cancelable attribute value is false or its preventDefault() method was not invoked, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`boolean`

#### Inherited from

EventTarget.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### getAudioTracks

▸ **getAudioTracks**(): [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Returns

[`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10029

___

### getTrackById

▸ **getTrackById**(`trackId`): [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)

#### Parameters

| Name | Type |
| :------ | :------ |
| `trackId` | `string` |

#### Returns

[`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10030

___

### getTracks

▸ **getTracks**(): [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Returns

[`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10031

___

### getVideoTracks

▸ **getVideoTracks**(): [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Returns

[`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10032

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaStreamEventMap`](akashaproject_design_system._internal_.MediaStreamEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaStreamEventMap`](akashaproject_design_system._internal_.MediaStreamEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10036

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10037

___

### removeTrack

▸ **removeTrack**(`track`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `track` | [`MediaStreamTrack`](../modules/akashaproject_design_system._internal_.md#mediastreamtrack) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10033
