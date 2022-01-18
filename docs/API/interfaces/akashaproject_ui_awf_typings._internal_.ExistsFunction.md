[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / ExistsFunction

# Interface: ExistsFunction<TKeys, TInterpolationMap\>

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).ExistsFunction

## Type parameters

| Name | Type |
| :------ | :------ |
| `TKeys` | extends `string` = `string` |
| `TInterpolationMap` | extends `object` = [`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap) |

## Callable

### ExistsFunction

▸ **ExistsFunction**(`key`, `options?`): `boolean`

Uses similar args as the t function and returns true if a key exists.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `TKeys` \| `TKeys`[] |
| `options?` | [`TOptions`](../modules/akashaproject_ui_awf_typings._internal_.md#toptions)<`TInterpolationMap`\> |

#### Returns

`boolean`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:694
