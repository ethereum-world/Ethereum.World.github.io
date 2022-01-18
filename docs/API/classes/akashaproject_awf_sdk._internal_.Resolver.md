[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Resolver

# Class: Resolver

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Resolver

## Implements

- [`EnsResolver`](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Resolver.md#constructor)

### Properties

- [\_resolvedAddress](akashaproject_awf_sdk._internal_.Resolver.md#_resolvedaddress)
- [address](akashaproject_awf_sdk._internal_.Resolver.md#address)
- [name](akashaproject_awf_sdk._internal_.Resolver.md#name)
- [provider](akashaproject_awf_sdk._internal_.Resolver.md#provider)

### Methods

- [\_fetchBytes](akashaproject_awf_sdk._internal_.Resolver.md#_fetchbytes)
- [\_getAddress](akashaproject_awf_sdk._internal_.Resolver.md#_getaddress)
- [getAddress](akashaproject_awf_sdk._internal_.Resolver.md#getaddress)
- [getAvatar](akashaproject_awf_sdk._internal_.Resolver.md#getavatar)
- [getContentHash](akashaproject_awf_sdk._internal_.Resolver.md#getcontenthash)
- [getText](akashaproject_awf_sdk._internal_.Resolver.md#gettext)

## Constructors

### constructor

• **new Resolver**(`provider`, `address`, `name`, `resolvedAddress?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md) |
| `address` | `string` |
| `name` | `string` |
| `resolvedAddress?` | `string` |

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:43

## Properties

### \_resolvedAddress

• `Readonly` **\_resolvedAddress**: `string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:42

___

### address

• `Readonly` **address**: `string`

#### Implementation of

[EnsResolver](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md).[address](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md#address)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:41

___

### name

• `Readonly` **name**: `string`

#### Implementation of

[EnsResolver](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md).[name](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md#name)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:40

___

### provider

• `Readonly` **provider**: [`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:39

## Methods

### \_fetchBytes

▸ **_fetchBytes**(`selector`, `parameters?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector` | `string` |
| `parameters?` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:44

___

### \_getAddress

▸ **_getAddress**(`coinType`, `hexBytes`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `coinType` | `number` |
| `hexBytes` | `string` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:45

___

### getAddress

▸ **getAddress**(`coinType?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `coinType?` | `number` |

#### Returns

`Promise`<`string`\>

#### Implementation of

[EnsResolver](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md).[getAddress](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md#getaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:46

___

### getAvatar

▸ **getAvatar**(): `Promise`<[`Avatar`](../interfaces/akashaproject_awf_sdk._internal_.Avatar.md)\>

#### Returns

`Promise`<[`Avatar`](../interfaces/akashaproject_awf_sdk._internal_.Avatar.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:47

___

### getContentHash

▸ **getContentHash**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Implementation of

[EnsResolver](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md).[getContentHash](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md#getcontenthash)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:48

___

### getText

▸ **getText**(`key`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<`string`\>

#### Implementation of

[EnsResolver](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md).[getText](../interfaces/akashaproject_awf_sdk._internal_.EnsResolver.md#gettext)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:49
