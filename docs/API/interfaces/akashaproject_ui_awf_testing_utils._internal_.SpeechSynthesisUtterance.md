[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SpeechSynthesisUtterance

# Interface: SpeechSynthesisUtterance

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SpeechSynthesisUtterance

This Web Speech API interface represents a speech request. It contains the content the speech service should read and information about how to read it (e.g. language, pitch and volume.)

## Hierarchy

- `EventTarget`

  ↳ **`SpeechSynthesisUtterance`**

## Table of contents

### Properties

- [lang](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#lang)
- [onboundary](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onboundary)
- [onend](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onend)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onerror)
- [onmark](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onmark)
- [onpause](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onpause)
- [onresume](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onresume)
- [onstart](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#onstart)
- [pitch](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#pitch)
- [rate](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#rate)
- [text](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#text)
- [voice](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#voice)
- [volume](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#volume)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtterance.md#removeeventlistener)

## Properties

### lang

• **lang**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14260

___

### onboundary

• **onboundary**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14261

___

### onend

• **onend**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14262

___

### onerror

• **onerror**: (`ev`: [`SpeechSynthesisErrorEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesiserrorevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisErrorEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesiserrorevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14263

___

### onmark

• **onmark**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14264

___

### onpause

• **onpause**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14265

___

### onresume

• **onresume**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14266

___

### onstart

• **onstart**: (`ev`: [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`SpeechSynthesisEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14267

___

### pitch

• **pitch**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14268

___

### rate

• **rate**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14269

___

### text

• **text**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14270

___

### voice

• **voice**: [`SpeechSynthesisVoice`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisvoice)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14271

___

### volume

• **volume**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14272

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`SpeechSynthesisUtteranceEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtteranceEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SpeechSynthesisUtteranceEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtteranceEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14273

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

node_modules/typescript/lib/lib.dom.d.ts:14274

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
| `K` | extends keyof [`SpeechSynthesisUtteranceEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtteranceEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SpeechSynthesisUtteranceEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisUtteranceEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14275

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

node_modules/typescript/lib/lib.dom.d.ts:14276
