[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / TextTrack

# Interface: TextTrack

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).TextTrack

This interface also inherits properties from EventTarget.

## Hierarchy

- `EventTarget`

  ↳ **`TextTrack`**

## Table of contents

### Properties

- [activeCues](akashaproject_design_system._internal_.TextTrack.md#activecues)
- [cues](akashaproject_design_system._internal_.TextTrack.md#cues)
- [id](akashaproject_design_system._internal_.TextTrack.md#id)
- [inBandMetadataTrackDispatchType](akashaproject_design_system._internal_.TextTrack.md#inbandmetadatatrackdispatchtype)
- [kind](akashaproject_design_system._internal_.TextTrack.md#kind)
- [label](akashaproject_design_system._internal_.TextTrack.md#label)
- [language](akashaproject_design_system._internal_.TextTrack.md#language)
- [mode](akashaproject_design_system._internal_.TextTrack.md#mode)
- [oncuechange](akashaproject_design_system._internal_.TextTrack.md#oncuechange)

### Methods

- [addCue](akashaproject_design_system._internal_.TextTrack.md#addcue)
- [addEventListener](akashaproject_design_system._internal_.TextTrack.md#addeventlistener)
- [dispatchEvent](akashaproject_design_system._internal_.TextTrack.md#dispatchevent)
- [removeCue](akashaproject_design_system._internal_.TextTrack.md#removecue)
- [removeEventListener](akashaproject_design_system._internal_.TextTrack.md#removeeventlistener)

## Properties

### activeCues

• `Readonly` **activeCues**: [`TextTrackCueList`](../modules/akashaproject_design_system._internal_.md#texttrackcuelist)

Returns the text track cues from the text track list of cues that are currently active (i.e. that start before the current playback position and end after it), as a TextTrackCueList object.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14616

___

### cues

• `Readonly` **cues**: [`TextTrackCueList`](../modules/akashaproject_design_system._internal_.md#texttrackcuelist)

Returns the text track list of cues, as a TextTrackCueList object.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14620

___

### id

• `Readonly` **id**: `string`

Returns the ID of the given track.

For in-band tracks, this is the ID that can be used with a fragment if the format supports media fragment syntax, and that can be used with the getTrackById() method.

For TextTrack objects corresponding to track elements, this is the ID of the track element.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14628

___

### inBandMetadataTrackDispatchType

• `Readonly` **inBandMetadataTrackDispatchType**: `string`

Returns the text track in-band metadata track dispatch type string.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14632

___

### kind

• `Readonly` **kind**: [`TextTrackKind`](../modules/akashaproject_design_system._internal_.md#texttrackkind)

Returns the text track kind string.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14636

___

### label

• `Readonly` **label**: `string`

Returns the text track label, if there is one, or the empty string otherwise (indicating that a custom label probably needs to be generated from the other attributes of the object if the object is exposed to the user).

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14640

___

### language

• `Readonly` **language**: `string`

Returns the text track language string.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14644

___

### mode

• **mode**: [`TextTrackMode`](../modules/akashaproject_design_system._internal_.md#texttrackmode)

Returns the text track mode, represented by a string from the following list:

Can be set, to change the mode.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14650

___

### oncuechange

• **oncuechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14651

## Methods

### addCue

▸ **addCue**(`cue`): `void`

Adds the given cue to textTrack's text track list of cues.

#### Parameters

| Name | Type |
| :------ | :------ |
| `cue` | [`TextTrackCue`](../modules/akashaproject_design_system._internal_.md#texttrackcue) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14655

___

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"cuechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`TextTrackEventMap`](akashaproject_design_system._internal_.TextTrackEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14660

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

node_modules/typescript/lib/lib.dom.d.ts:14661

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

### removeCue

▸ **removeCue**(`cue`): `void`

Removes the given cue from textTrack's text track list of cues.

#### Parameters

| Name | Type |
| :------ | :------ |
| `cue` | [`TextTrackCue`](../modules/akashaproject_design_system._internal_.md#texttrackcue) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14659

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"cuechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`TextTrackEventMap`](akashaproject_design_system._internal_.TextTrackEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14662

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

node_modules/typescript/lib/lib.dom.d.ts:14663
