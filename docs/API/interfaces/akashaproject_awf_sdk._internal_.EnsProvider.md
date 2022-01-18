[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / EnsProvider

# Interface: EnsProvider

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).EnsProvider

## Implemented by

- [`BaseProvider`](../classes/akashaproject_awf_sdk._internal_.BaseProvider.md)

## Table of contents

### Methods

- [getResolver](akashaproject_awf_sdk._internal_.EnsProvider.md#getresolver)
- [lookupAddress](akashaproject_awf_sdk._internal_.EnsProvider.md#lookupaddress)
- [resolveName](akashaproject_awf_sdk._internal_.EnsProvider.md#resolvename)

## Methods

### getResolver

▸ **getResolver**(`name`): `Promise`<[`EnsResolver`](akashaproject_awf_sdk._internal_.EnsResolver.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<[`EnsResolver`](akashaproject_awf_sdk._internal_.EnsResolver.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:29

___

### lookupAddress

▸ **lookupAddress**(`address`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:28

___

### resolveName

▸ **resolveName**(`name`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:27
