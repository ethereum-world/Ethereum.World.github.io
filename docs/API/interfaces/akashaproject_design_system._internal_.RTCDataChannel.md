[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / RTCDataChannel

# Interface: RTCDataChannel

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).RTCDataChannel

## Hierarchy

- `EventTarget`

  ↳ **`RTCDataChannel`**

## Table of contents

### Properties

- [binaryType](akashaproject_design_system._internal_.RTCDataChannel.md#binarytype)
- [bufferedAmount](akashaproject_design_system._internal_.RTCDataChannel.md#bufferedamount)
- [bufferedAmountLowThreshold](akashaproject_design_system._internal_.RTCDataChannel.md#bufferedamountlowthreshold)
- [id](akashaproject_design_system._internal_.RTCDataChannel.md#id)
- [label](akashaproject_design_system._internal_.RTCDataChannel.md#label)
- [maxPacketLifeTime](akashaproject_design_system._internal_.RTCDataChannel.md#maxpacketlifetime)
- [maxRetransmits](akashaproject_design_system._internal_.RTCDataChannel.md#maxretransmits)
- [negotiated](akashaproject_design_system._internal_.RTCDataChannel.md#negotiated)
- [onbufferedamountlow](akashaproject_design_system._internal_.RTCDataChannel.md#onbufferedamountlow)
- [onclose](akashaproject_design_system._internal_.RTCDataChannel.md#onclose)
- [onerror](akashaproject_design_system._internal_.RTCDataChannel.md#onerror)
- [onmessage](akashaproject_design_system._internal_.RTCDataChannel.md#onmessage)
- [onopen](akashaproject_design_system._internal_.RTCDataChannel.md#onopen)
- [ordered](akashaproject_design_system._internal_.RTCDataChannel.md#ordered)
- [protocol](akashaproject_design_system._internal_.RTCDataChannel.md#protocol)
- [readyState](akashaproject_design_system._internal_.RTCDataChannel.md#readystate)

### Methods

- [addEventListener](akashaproject_design_system._internal_.RTCDataChannel.md#addeventlistener)
- [close](akashaproject_design_system._internal_.RTCDataChannel.md#close)
- [dispatchEvent](akashaproject_design_system._internal_.RTCDataChannel.md#dispatchevent)
- [removeEventListener](akashaproject_design_system._internal_.RTCDataChannel.md#removeeventlistener)
- [send](akashaproject_design_system._internal_.RTCDataChannel.md#send)

## Properties

### binaryType

• **binaryType**: [`BinaryType`](../modules/akashaproject_design_system._internal_.md#binarytype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11646

___

### bufferedAmount

• `Readonly` **bufferedAmount**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11647

___

### bufferedAmountLowThreshold

• **bufferedAmountLowThreshold**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11648

___

### id

• `Readonly` **id**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11649

___

### label

• `Readonly` **label**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11650

___

### maxPacketLifeTime

• `Readonly` **maxPacketLifeTime**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11651

___

### maxRetransmits

• `Readonly` **maxRetransmits**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11652

___

### negotiated

• `Readonly` **negotiated**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11653

___

### onbufferedamountlow

• **onbufferedamountlow**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11654

___

### onclose

• **onclose**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11655

___

### onerror

• **onerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11656

___

### onmessage

• **onmessage**: (`ev`: [`MessageEvent`](../modules/akashaproject_design_system._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_design_system._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11657

___

### onopen

• **onopen**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11658

___

### ordered

• `Readonly` **ordered**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11659

___

### protocol

• `Readonly` **protocol**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11660

___

### readyState

• `Readonly` **readyState**: [`RTCDataChannelState`](../modules/akashaproject_design_system._internal_.md#rtcdatachannelstate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11661

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`RTCDataChannelEventMap`](akashaproject_design_system._internal_.RTCDataChannelEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`RTCDataChannelEventMap`](akashaproject_design_system._internal_.RTCDataChannelEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11667

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

node_modules/typescript/lib/lib.dom.d.ts:11668

___

### close

▸ **close**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11662

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

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`RTCDataChannelEventMap`](akashaproject_design_system._internal_.RTCDataChannelEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`RTCDataChannelEventMap`](akashaproject_design_system._internal_.RTCDataChannelEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11669

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

node_modules/typescript/lib/lib.dom.d.ts:11670

___

### send

▸ **send**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11663

▸ **send**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Blob` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11664

▸ **send**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `ArrayBuffer` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11665

▸ **send**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`ArrayBufferView`](akashaproject_design_system._internal_.ArrayBufferView.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11666
