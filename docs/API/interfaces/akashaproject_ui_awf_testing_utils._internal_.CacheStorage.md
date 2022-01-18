[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / CacheStorage

# Interface: CacheStorage

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).CacheStorage

The storage for Cache objects.

## Table of contents

### Methods

- [delete](akashaproject_ui_awf_testing_utils._internal_.CacheStorage.md#delete)
- [has](akashaproject_ui_awf_testing_utils._internal_.CacheStorage.md#has)
- [keys](akashaproject_ui_awf_testing_utils._internal_.CacheStorage.md#keys)
- [match](akashaproject_ui_awf_testing_utils._internal_.CacheStorage.md#match)
- [open](akashaproject_ui_awf_testing_utils._internal_.CacheStorage.md#open)

## Methods

### delete

▸ **delete**(`cacheName`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cacheName` | `string` |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3280

___

### has

▸ **has**(`cacheName`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cacheName` | `string` |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3281

___

### keys

▸ **keys**(): `Promise`<`string`[]\>

#### Returns

`Promise`<`string`[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3282

___

### match

▸ **match**(`request`, `options?`): `Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`RequestInfo`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestinfo) |
| `options?` | [`MultiCacheQueryOptions`](akashaproject_ui_awf_testing_utils._internal_.MultiCacheQueryOptions.md) |

#### Returns

`Promise`<[`Response`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#response)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3283

___

### open

▸ **open**(`cacheName`): `Promise`<[`Cache`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cache)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cacheName` | `string` |

#### Returns

`Promise`<[`Cache`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cache)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3284
