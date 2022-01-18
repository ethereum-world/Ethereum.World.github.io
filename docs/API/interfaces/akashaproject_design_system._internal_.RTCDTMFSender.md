[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / RTCDTMFSender

# Interface: RTCDTMFSender

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).RTCDTMFSender

## Hierarchy

- `EventTarget`

  ↳ **`RTCDTMFSender`**

## Table of contents

### Properties

- [canInsertDTMF](akashaproject_design_system._internal_.RTCDTMFSender.md#caninsertdtmf)
- [ontonechange](akashaproject_design_system._internal_.RTCDTMFSender.md#ontonechange)
- [toneBuffer](akashaproject_design_system._internal_.RTCDTMFSender.md#tonebuffer)

### Methods

- [addEventListener](akashaproject_design_system._internal_.RTCDTMFSender.md#addeventlistener)
- [dispatchEvent](akashaproject_design_system._internal_.RTCDTMFSender.md#dispatchevent)
- [insertDTMF](akashaproject_design_system._internal_.RTCDTMFSender.md#insertdtmf)
- [removeEventListener](akashaproject_design_system._internal_.RTCDTMFSender.md#removeeventlistener)

## Properties

### canInsertDTMF

• `Readonly` **canInsertDTMF**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11612

___

### ontonechange

• **ontonechange**: (`ev`: [`RTCDTMFToneChangeEvent`](../modules/akashaproject_design_system._internal_.md#rtcdtmftonechangeevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`RTCDTMFToneChangeEvent`](../modules/akashaproject_design_system._internal_.md#rtcdtmftonechangeevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11613

___

### toneBuffer

• `Readonly` **toneBuffer**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11614

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"tonechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`RTCDTMFSenderEventMap`](akashaproject_design_system._internal_.RTCDTMFSenderEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11616

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

node_modules/typescript/lib/lib.dom.d.ts:11617

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

### insertDTMF

▸ **insertDTMF**(`tones`, `duration?`, `interToneGap?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tones` | `string` |
| `duration?` | `number` |
| `interToneGap?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11615

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"tonechange"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`RTCDTMFSenderEventMap`](akashaproject_design_system._internal_.RTCDTMFSenderEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11618

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

node_modules/typescript/lib/lib.dom.d.ts:11619
