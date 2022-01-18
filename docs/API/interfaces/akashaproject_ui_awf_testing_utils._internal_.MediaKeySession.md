[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaKeySession

# Interface: MediaKeySession

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaKeySession

This EncryptedMediaExtensions API interface represents a context for message exchange with a content decryption module (CDM).

## Hierarchy

- `EventTarget`

  ↳ **`MediaKeySession`**

## Table of contents

### Properties

- [closed](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#closed)
- [expiration](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#expiration)
- [keyStatuses](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#keystatuses)
- [onkeystatuseschange](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#onkeystatuseschange)
- [onmessage](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#onmessage)
- [sessionId](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#sessionid)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#addeventlistener)
- [close](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#close)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#dispatchevent)
- [generateRequest](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#generaterequest)
- [load](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#load)
- [remove](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#remove)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#removeeventlistener)
- [update](akashaproject_ui_awf_testing_utils._internal_.MediaKeySession.md#update)

## Properties

### closed

• `Readonly` **closed**: `Promise`<[`MediaKeySessionClosedReason`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysessionclosedreason)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9806

___

### expiration

• `Readonly` **expiration**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9807

___

### keyStatuses

• `Readonly` **keyStatuses**: [`MediaKeyStatusMap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeystatusmap)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9808

___

### onkeystatuseschange

• **onkeystatuseschange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9809

___

### onmessage

• **onmessage**: (`ev`: [`MediaKeyMessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeymessageevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MediaKeyMessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeymessageevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9810

___

### sessionId

• `Readonly` **sessionId**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9811

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaKeySessionEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySessionEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaKeySessionEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySessionEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9817

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

node_modules/typescript/lib/lib.dom.d.ts:9818

___

### close

▸ **close**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9812

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

### generateRequest

▸ **generateRequest**(`initDataType`, `initData`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `initDataType` | `string` |
| `initData` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9813

___

### load

▸ **load**(`sessionId`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `sessionId` | `string` |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9814

___

### remove

▸ **remove**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9815

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MediaKeySessionEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySessionEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaKeySessionEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySessionEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9819

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

node_modules/typescript/lib/lib.dom.d.ts:9820

___

### update

▸ **update**(`response`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9816
