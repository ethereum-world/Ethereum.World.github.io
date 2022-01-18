[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / EnsResolver

# Interface: EnsResolver

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).EnsResolver

## Implemented by

- [`Resolver`](../classes/akashaproject_ui_app_loader._internal_.Resolver.md)

## Table of contents

### Properties

- [address](akashaproject_ui_app_loader._internal_.EnsResolver.md#address)
- [name](akashaproject_ui_app_loader._internal_.EnsResolver.md#name)

### Methods

- [getAddress](akashaproject_ui_app_loader._internal_.EnsResolver.md#getaddress)
- [getContentHash](akashaproject_ui_app_loader._internal_.EnsResolver.md#getcontenthash)
- [getText](akashaproject_ui_app_loader._internal_.EnsResolver.md#gettext)

## Properties

### address

• `Readonly` **address**: `string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:21

___

### name

• `Readonly` **name**: `string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:20

## Methods

### getAddress

▸ **getAddress**(`coinType?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `coinType?` | ``60`` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:22

___

### getContentHash

▸ **getContentHash**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:23

___

### getText

▸ **getText**(`key`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:24
