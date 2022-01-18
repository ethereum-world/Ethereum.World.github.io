[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AbstractWorker

# Interface: AbstractWorker

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AbstractWorker

## Hierarchy

- **`AbstractWorker`**

  ↳ [`ServiceWorker`](akashaproject_awf_sdk._internal_.ServiceWorker.md)

## Table of contents

### Properties

- [onerror](akashaproject_awf_sdk._internal_.AbstractWorker.md#onerror)

### Methods

- [addEventListener](akashaproject_awf_sdk._internal_.AbstractWorker.md#addeventlistener)
- [removeEventListener](akashaproject_awf_sdk._internal_.AbstractWorker.md#removeeventlistener)

## Properties

### onerror

• **onerror**: (`ev`: [`ErrorEvent`](../modules/akashaproject_awf_sdk._internal_.md#errorevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`ErrorEvent`](../modules/akashaproject_awf_sdk._internal_.md#errorevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1970

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"error"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`AbstractWorkerEventMap`](akashaproject_awf_sdk._internal_.AbstractWorkerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_awf_sdk._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1971

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_awf_sdk._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_awf_sdk._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1972

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"error"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`AbstractWorkerEventMap`](akashaproject_awf_sdk._internal_.AbstractWorkerEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_awf_sdk._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1973

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_awf_sdk._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_awf_sdk._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1974
