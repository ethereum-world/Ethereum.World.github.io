[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / QueryCacheConfig

# Interface: QueryCacheConfig

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).QueryCacheConfig

## Table of contents

### Methods

- [onError](akashaproject_ui_awf_hooks._internal_.QueryCacheConfig.md#onerror)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.QueryCacheConfig.md#onsuccess)

## Methods

### onError

▸ `Optional` **onError**(`error`, `query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | `unknown` |
| `query` | [`Query`](../classes/akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:8

___

### onSuccess

▸ `Optional` **onSuccess**(`data`, `query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `unknown` |
| `query` | [`Query`](../classes/akashaproject_ui_awf_hooks._internal_.Query.md)<`unknown`, `unknown`, `unknown`, [`QueryKey`](../modules/akashaproject_ui_awf_hooks._internal_.md#querykey)\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/queryCache.d.ts:9
