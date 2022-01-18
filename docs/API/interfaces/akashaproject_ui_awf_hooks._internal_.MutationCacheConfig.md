[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / MutationCacheConfig

# Interface: MutationCacheConfig

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).MutationCacheConfig

## Table of contents

### Methods

- [onError](akashaproject_ui_awf_hooks._internal_.MutationCacheConfig.md#onerror)
- [onMutate](akashaproject_ui_awf_hooks._internal_.MutationCacheConfig.md#onmutate)
- [onSuccess](akashaproject_ui_awf_hooks._internal_.MutationCacheConfig.md#onsuccess)

## Methods

### onError

▸ `Optional` **onError**(`error`, `variables`, `context`, `mutation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | `unknown` |
| `variables` | `unknown` |
| `context` | `unknown` |
| `mutation` | [`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `unknown`, `unknown`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:7

___

### onMutate

▸ `Optional` **onMutate**(`variables`, `mutation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `variables` | `unknown` |
| `mutation` | [`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `unknown`, `unknown`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:9

___

### onSuccess

▸ `Optional` **onSuccess**(`data`, `variables`, `context`, `mutation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `unknown` |
| `variables` | `unknown` |
| `context` | `unknown` |
| `mutation` | [`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `unknown`, `unknown`\> |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/react-query/types/core/mutationCache.d.ts:8
