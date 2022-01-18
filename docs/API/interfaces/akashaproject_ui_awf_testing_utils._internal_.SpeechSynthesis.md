[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SpeechSynthesis

# Interface: SpeechSynthesis

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SpeechSynthesis

This Web Speech API interface is the controller interface for the speech service; this can be used to retrieve information about the synthesis voices available on the device, start and pause speech, and other commands besides.

## Hierarchy

- `EventTarget`

  ↳ **`SpeechSynthesis`**

## Table of contents

### Properties

- [onvoiceschanged](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#onvoiceschanged)
- [paused](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#paused)
- [pending](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#pending)
- [speaking](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#speaking)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#addeventlistener)
- [cancel](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#cancel)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#dispatchevent)
- [getVoices](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#getvoices)
- [pause](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#pause)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#removeeventlistener)
- [resume](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#resume)
- [speak](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesis.md#speak)

## Properties

### onvoiceschanged

• **onvoiceschanged**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14205

___

### paused

• `Readonly` **paused**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14206

___

### pending

• `Readonly` **pending**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14207

___

### speaking

• `Readonly` **speaking**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14208

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"voiceschanged"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SpeechSynthesisEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14214

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

node_modules/typescript/lib/lib.dom.d.ts:14215

___

### cancel

▸ **cancel**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14209

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

### getVoices

▸ **getVoices**(): [`SpeechSynthesisVoice`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisvoice)[]

#### Returns

[`SpeechSynthesisVoice`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisvoice)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14210

___

### pause

▸ **pause**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14211

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"voiceschanged"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`SpeechSynthesisEventMap`](akashaproject_ui_awf_testing_utils._internal_.SpeechSynthesisEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14216

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

node_modules/typescript/lib/lib.dom.d.ts:14217

___

### resume

▸ **resume**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14212

___

### speak

▸ **speak**(`utterance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `utterance` | [`SpeechSynthesisUtterance`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#speechsynthesisutterance) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14213
