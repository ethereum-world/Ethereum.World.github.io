[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / TFunction

# Interface: TFunction

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).TFunction

## Callable

### TFunction

▸ **TFunction**<`TResult`, `TKeys`, `TInterpolationMap`\>(`key`, `options?`): `TResult`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TResult` | extends [`TFunctionResult`](../modules/akashaproject_ui_awf_typings._internal_.md#tfunctionresult) = `string` |
| `TKeys` | extends [`TFunctionKeys`](../modules/akashaproject_ui_awf_typings._internal_.md#tfunctionkeys) = `string` |
| `TInterpolationMap` | extends `object` = [`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `TKeys` \| `TKeys`[] |
| `options?` | `string` \| [`TOptions`](../modules/akashaproject_ui_awf_typings._internal_.md#toptions)<`TInterpolationMap`\> |

#### Returns

`TResult`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:706

### TFunction

▸ **TFunction**<`TResult`, `TKeys`, `TInterpolationMap`\>(`key`, `defaultValue?`, `options?`): `TResult`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TResult` | extends [`TFunctionResult`](../modules/akashaproject_ui_awf_typings._internal_.md#tfunctionresult) = `string` |
| `TKeys` | extends [`TFunctionKeys`](../modules/akashaproject_ui_awf_typings._internal_.md#tfunctionkeys) = `string` |
| `TInterpolationMap` | extends `object` = [`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `TKeys` \| `TKeys`[] |
| `defaultValue?` | `string` |
| `options?` | `string` \| [`TOptions`](../modules/akashaproject_ui_awf_typings._internal_.md#toptions)<`TInterpolationMap`\> |

#### Returns

`TResult`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:715
