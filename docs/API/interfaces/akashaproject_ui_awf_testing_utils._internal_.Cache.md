[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Cache

# Interface: Cache

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Cache

Provides a storage mechanism for Request / Response object pairs that are cached, for example as part of the ServiceWorker life cycle. Note that the Cache interface is exposed to windowed scopes as well as workers. You don't have to use it in conjunction with service workers, even though it is defined in the service worker spec.

## Table of contents

### Methods

- [add](akashaproject_ui_awf_testing_utils._internal_.Cache.md#add)
- [addAll](akashaproject_ui_awf_testing_utils._internal_.Cache.md#addall)
- [delete](akashaproject_ui_awf_testing_utils._internal_.Cache.md#delete)
- [keys](akashaproject_ui_awf_testing_utils._internal_.Cache.md#keys)
- [match](akashaproject_ui_awf_testing_utils._internal_.Cache.md#match)
- [matchAll](akashaproject_ui_awf_testing_utils._internal_.Cache.md#matchall)
- [put](akashaproject_ui_awf_testing_utils._internal_.Cache.md#put)

## Methods

### add

▸ **add**(`request`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3264

___

### addAll

▸ **addAll**(`requests`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `requests` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo)[] |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3265

___

### delete

▸ **delete**(`request`, `options?`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `options?` | [`CacheQueryOptions`](akashaproject_ui_awf_testing_utils._internal_.CacheQueryOptions.md) |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3266

___

### keys

▸ **keys**(`request?`, `options?`): `Promise`<readonly [`Request`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#request)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request?` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `options?` | [`CacheQueryOptions`](akashaproject_ui_awf_testing_utils._internal_.CacheQueryOptions.md) |

#### Returns

`Promise`<readonly [`Request`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#request)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3267

___

### match

▸ **match**(`request`, `options?`): `Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `options?` | [`CacheQueryOptions`](akashaproject_ui_awf_testing_utils._internal_.CacheQueryOptions.md) |

#### Returns

`Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3268

___

### matchAll

▸ **matchAll**(`request?`, `options?`): `Promise`<readonly [`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request?` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `options?` | [`CacheQueryOptions`](akashaproject_ui_awf_testing_utils._internal_.CacheQueryOptions.md) |

#### Returns

`Promise`<readonly [`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3269

___

### put

▸ **put**(`request`, `response`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `response` | [`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3270
