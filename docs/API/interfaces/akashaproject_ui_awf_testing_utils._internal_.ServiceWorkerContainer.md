[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ServiceWorkerContainer

# Interface: ServiceWorkerContainer

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ServiceWorkerContainer

The ServiceWorkerContainer interface of the ServiceWorker API provides an object representing the service worker as an overall unit in the network ecosystem, including facilities to register, unregister and update service workers, and access the state of service workers and their registrations.

## Hierarchy

- `EventTarget`

  ↳ **`ServiceWorkerContainer`**

## Table of contents

### Properties

- [controller](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#controller)
- [oncontrollerchange](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#oncontrollerchange)
- [onmessage](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#onmessage)
- [onmessageerror](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#onmessageerror)
- [ready](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#ready)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#dispatchevent)
- [getRegistration](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#getregistration)
- [getRegistrations](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#getregistrations)
- [register](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#register)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#removeeventlistener)
- [startMessages](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainer.md#startmessages)

## Properties

### controller

• `Readonly` **controller**: [`ServiceWorker`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworker)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14026

___

### oncontrollerchange

• **oncontrollerchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14027

___

### onmessage

• **onmessage**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14028

___

### onmessageerror

• **onmessageerror**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14029

___

### ready

• `Readonly` **ready**: `Promise`<[`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14030

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`ServiceWorkerContainerEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainerEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerContainerEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14035

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

node_modules/typescript/lib/lib.dom.d.ts:14036

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

### getRegistration

▸ **getRegistration**(`clientURL?`): `Promise`<[`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `clientURL?` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |

#### Returns

`Promise`<[`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14031

___

### getRegistrations

▸ **getRegistrations**(): `Promise`<readonly [`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)[]\>

#### Returns

`Promise`<readonly [`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14032

___

### register

▸ **register**(`scriptURL`, `options?`): `Promise`<[`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `scriptURL` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |
| `options?` | [`RegistrationOptions`](akashaproject_ui_awf_testing_utils._internal_.RegistrationOptions.md) |

#### Returns

`Promise`<[`ServiceWorkerRegistration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkerregistration)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14033

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`ServiceWorkerContainerEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainerEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerContainerEventMap`](akashaproject_ui_awf_testing_utils._internal_.ServiceWorkerContainerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14037

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

node_modules/typescript/lib/lib.dom.d.ts:14038

___

### startMessages

▸ **startMessages**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14034
