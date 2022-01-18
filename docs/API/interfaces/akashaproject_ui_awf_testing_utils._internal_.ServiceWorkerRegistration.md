[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ServiceWorkerRegistration

# Interface: ServiceWorkerRegistration

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ServiceWorkerRegistration

This ServiceWorker API interface represents the service worker registration. You register a service worker to control one or more pages that share the same origin.

## Hierarchy

- `EventTarget`

  ↳ **`ServiceWorkerRegistration`**

## Table of contents

### Properties

- [active](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#active)
- [installing](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#installing)
- [onupdatefound](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#onupdatefound)
- [pushManager](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#pushmanager)
- [scope](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#scope)
- [updateViaCache](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#updateviacache)
- [waiting](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#waiting)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#dispatchevent)
- [getNotifications](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#getnotifications)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#removeeventlistener)
- [showNotification](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#shownotification)
- [unregister](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#unregister)
- [update](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistration.md#update)

## Properties

### active

• `Readonly` **active**: [`ServiceWorker`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworker)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14052

___

### installing

• `Readonly` **installing**: [`ServiceWorker`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworker)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14053

___

### onupdatefound

• **onupdatefound**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14054

___

### pushManager

• `Readonly` **pushManager**: [`PushManager`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushmanager)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14055

___

### scope

• `Readonly` **scope**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14056

___

### updateViaCache

• `Readonly` **updateViaCache**: [`ServiceWorkerUpdateViaCache`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerupdateviacache)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14057

___

### waiting

• `Readonly` **waiting**: [`ServiceWorker`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworker)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14058

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"updatefound"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerRegistrationEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistrationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14063

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

node_modules/typescript/lib/lib.dom.d.ts:14064

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

### getNotifications

▸ **getNotifications**(`filter?`): `Promise`<[`Notification`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#notification)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter?` | [`GetNotificationOptions`](akashaproject_ui_awf_testing_utils._internal_.GetNotificationOptions.md) |

#### Returns

`Promise`<[`Notification`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#notification)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14059

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"updatefound"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerRegistrationEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerRegistrationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14065

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

node_modules/typescript/lib/lib.dom.d.ts:14066

___

### showNotification

▸ **showNotification**(`title`, `options?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `title` | `string` |
| `options?` | [`NotificationOptions`](akashaproject_ui_awf_testing_utils._internal_.NotificationOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14060

___

### unregister

▸ **unregister**(): `Promise`<`boolean`\>

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14061

___

### update

▸ **update**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14062
