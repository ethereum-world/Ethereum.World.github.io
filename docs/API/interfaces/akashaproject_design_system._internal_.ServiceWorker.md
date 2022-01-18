[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ServiceWorker

# Interface: ServiceWorker

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ServiceWorker

This ServiceWorker API interface provides a reference to a service worker. Multiple browsing contexts (e.g. pages, workers, etc.) can be associated with the same service worker, each through a unique ServiceWorker object.

## Hierarchy

- `EventTarget`

- [`AbstractWorker`](akashaproject_design_system._internal_.AbstractWorker.md)

  ↳ **`ServiceWorker`**

## Table of contents

### Properties

- [onerror](akashaproject_design_system._internal_.ServiceWorker.md#onerror)
- [onstatechange](akashaproject_design_system._internal_.ServiceWorker.md#onstatechange)
- [scriptURL](akashaproject_design_system._internal_.ServiceWorker.md#scripturl)
- [state](akashaproject_design_system._internal_.ServiceWorker.md#state)

### Methods

- [addEventListener](akashaproject_design_system._internal_.ServiceWorker.md#addeventlistener)
- [dispatchEvent](akashaproject_design_system._internal_.ServiceWorker.md#dispatchevent)
- [postMessage](akashaproject_design_system._internal_.ServiceWorker.md#postmessage)
- [removeEventListener](akashaproject_design_system._internal_.ServiceWorker.md#removeeventlistener)

## Properties

### onerror

• **onerror**: (`ev`: [`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`ErrorEvent`](../modules/akashaproject_design_system._internal_.md#errorevent) |

##### Returns

`any`

#### Inherited from

[AbstractWorker](akashaproject_design_system._internal_.AbstractWorker.md).[onerror](akashaproject_design_system._internal_.AbstractWorker.md#onerror)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1970

___

### onstatechange

• **onstatechange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14002

___

### scriptURL

• `Readonly` **scriptURL**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14003

___

### state

• `Readonly` **state**: [`ServiceWorkerState`](../modules/akashaproject_design_system._internal_.md#serviceworkerstate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14004

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`ServiceWorkerEventMap`](akashaproject_design_system._internal_.ServiceWorkerEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerEventMap`](akashaproject_design_system._internal_.ServiceWorkerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

[AbstractWorker](akashaproject_design_system._internal_.AbstractWorker.md).[addEventListener](akashaproject_design_system._internal_.AbstractWorker.md#addeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14007

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

[AbstractWorker](akashaproject_design_system._internal_.AbstractWorker.md).[addEventListener](akashaproject_design_system._internal_.AbstractWorker.md#addeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14008

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

### postMessage

▸ **postMessage**(`message`, `transfer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `transfer` | [`Transferable`](../modules/akashaproject_design_system._internal_.md#transferable)[] |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14005

▸ **postMessage**(`message`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `options?` | [`PostMessageOptions`](akashaproject_design_system._internal_.PostMessageOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14006

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`ServiceWorkerEventMap`](akashaproject_design_system._internal_.ServiceWorkerEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ServiceWorkerEventMap`](akashaproject_design_system._internal_.ServiceWorkerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

[AbstractWorker](akashaproject_design_system._internal_.AbstractWorker.md).[removeEventListener](akashaproject_design_system._internal_.AbstractWorker.md#removeeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14009

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

[AbstractWorker](akashaproject_design_system._internal_.AbstractWorker.md).[removeEventListener](akashaproject_design_system._internal_.AbstractWorker.md#removeeventlistener)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14010
