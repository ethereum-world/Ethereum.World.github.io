[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaStreamTrack

# Interface: MediaStreamTrack

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaStreamTrack

A single media track within a stream; typically, these are audio or video tracks, but other track types may exist as well.

## Hierarchy

- `EventTarget`

  ↳ **`MediaStreamTrack`**

## Table of contents

### Properties

- [contentHint](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#contenthint)
- [enabled](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#enabled)
- [id](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#id)
- [kind](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#kind)
- [label](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#label)
- [muted](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#muted)
- [onended](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#onended)
- [onmute](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#onmute)
- [onunmute](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#onunmute)
- [readyState](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#readystate)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#addeventlistener)
- [applyConstraints](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#applyconstraints)
- [clone](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#clone)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#dispatchevent)
- [getCapabilities](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#getcapabilities)
- [getConstraints](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#getconstraints)
- [getSettings](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#getsettings)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#removeeventlistener)
- [stop](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrack.md#stop)

## Properties

### contentHint

• **contentHint**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10074

___

### enabled

• **enabled**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10075

___

### id

• `Readonly` **id**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10076

___

### kind

• `Readonly` **kind**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10077

___

### label

• `Readonly` **label**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10078

___

### muted

• `Readonly` **muted**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10079

___

### onended

• **onended**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10080

___

### onmute

• **onmute**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10081

___

### onunmute

• **onunmute**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10082

___

### readyState

• `Readonly` **readyState**: [`MediaStreamTrackState`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastreamtrackstate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10083

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaStreamTrackEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrackEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaStreamTrackEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrackEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10090

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10091

___

### applyConstraints

▸ **applyConstraints**(`constraints?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `constraints?` | [`MediaTrackConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackConstraints.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10084

___

### clone

▸ **clone**(): [`MediaStreamTrack`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastreamtrack)

#### Returns

[`MediaStreamTrack`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastreamtrack)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10085

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

### getCapabilities

▸ **getCapabilities**(): [`MediaTrackCapabilities`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackCapabilities.md)

#### Returns

[`MediaTrackCapabilities`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackCapabilities.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10086

___

### getConstraints

▸ **getConstraints**(): [`MediaTrackConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackConstraints.md)

#### Returns

[`MediaTrackConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackConstraints.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10087

___

### getSettings

▸ **getSettings**(): [`MediaTrackSettings`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackSettings.md)

#### Returns

[`MediaTrackSettings`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackSettings.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10088

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaStreamTrackEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrackEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaStreamTrackEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaStreamTrackEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10092

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10093

___

### stop

▸ **stop**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10089
