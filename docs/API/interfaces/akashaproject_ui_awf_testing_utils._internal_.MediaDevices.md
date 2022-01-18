[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaDevices

# Interface: MediaDevices

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaDevices

Provides access to connected media input devices like cameras and microphones, as well as screen sharing. In essence, it lets you obtain access to any hardware source of media data.

## Hierarchy

- `EventTarget`

  ↳ **`MediaDevices`**

## Table of contents

### Properties

- [ondevicechange](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#ondevicechange)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#dispatchevent)
- [enumerateDevices](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#enumeratedevices)
- [getDisplayMedia](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#getdisplaymedia)
- [getSupportedConstraints](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#getsupportedconstraints)
- [getUserMedia](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#getusermedia)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaDevices.md#removeeventlistener)

## Properties

### ondevicechange

• **ondevicechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9733

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"devicechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaDevicesEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaDevicesEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9738

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

node_modules/typescript/lib/lib.dom.d.ts:9739

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

### enumerateDevices

▸ **enumerateDevices**(): `Promise`<[`MediaDeviceInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediadeviceinfo)[]\>

#### Returns

`Promise`<[`MediaDeviceInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediadeviceinfo)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9734

___

### getDisplayMedia

▸ **getDisplayMedia**(`constraints?`): `Promise`<[`MediaStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastream)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `constraints?` | [`DisplayMediaStreamConstraints`](akashaproject_ui_awf_testing_utils._internal_.DisplayMediaStreamConstraints.md) |

#### Returns

`Promise`<[`MediaStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastream)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9735

___

### getSupportedConstraints

▸ **getSupportedConstraints**(): [`MediaTrackSupportedConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackSupportedConstraints.md)

#### Returns

[`MediaTrackSupportedConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaTrackSupportedConstraints.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9736

___

### getUserMedia

▸ **getUserMedia**(`constraints?`): `Promise`<[`MediaStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastream)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `constraints?` | [`MediaStreamConstraints`](akashaproject_ui_awf_testing_utils._internal_.MediaStreamConstraints.md) |

#### Returns

`Promise`<[`MediaStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediastream)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9737

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"devicechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaDevicesEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaDevicesEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9740

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

node_modules/typescript/lib/lib.dom.d.ts:9741
