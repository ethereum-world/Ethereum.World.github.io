[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / SigningKey

# Class: SigningKey

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).SigningKey

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.SigningKey.md#constructor)

### Properties

- [\_isSigningKey](akashaproject_ui_app_loader._internal_.SigningKey.md#_issigningkey)
- [compressedPublicKey](akashaproject_ui_app_loader._internal_.SigningKey.md#compressedpublickey)
- [curve](akashaproject_ui_app_loader._internal_.SigningKey.md#curve)
- [privateKey](akashaproject_ui_app_loader._internal_.SigningKey.md#privatekey)
- [publicKey](akashaproject_ui_app_loader._internal_.SigningKey.md#publickey)

### Methods

- [\_addPoint](akashaproject_ui_app_loader._internal_.SigningKey.md#_addpoint)
- [computeSharedSecret](akashaproject_ui_app_loader._internal_.SigningKey.md#computesharedsecret)
- [signDigest](akashaproject_ui_app_loader._internal_.SigningKey.md#signdigest)
- [isSigningKey](akashaproject_ui_app_loader._internal_.SigningKey.md#issigningkey)

## Constructors

### constructor

• **new SigningKey**(`privateKey`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKey` | [`BytesLike`](../modules/akashaproject_ui_app_loader._internal_.md#byteslike) |

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:8

## Properties

### \_isSigningKey

• `Readonly` **\_isSigningKey**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:7

___

### compressedPublicKey

• `Readonly` **compressedPublicKey**: `string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:6

___

### curve

• `Readonly` **curve**: `string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:3

___

### privateKey

• `Readonly` **privateKey**: `string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:4

___

### publicKey

• `Readonly` **publicKey**: `string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:5

## Methods

### \_addPoint

▸ **_addPoint**(`other`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BytesLike`](../modules/akashaproject_ui_app_loader._internal_.md#byteslike) |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:9

___

### computeSharedSecret

▸ **computeSharedSecret**(`otherKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `otherKey` | [`BytesLike`](../modules/akashaproject_ui_app_loader._internal_.md#byteslike) |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:11

___

### signDigest

▸ **signDigest**(`digest`): [`Signature`](../interfaces/akashaproject_ui_app_loader._internal_.Signature.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `digest` | [`BytesLike`](../modules/akashaproject_ui_app_loader._internal_.md#byteslike) |

#### Returns

[`Signature`](../interfaces/akashaproject_ui_app_loader._internal_.Signature.md)

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:10

___

### isSigningKey

▸ `Static` **isSigningKey**(`value`): value is SigningKey

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is SigningKey

#### Defined in

sdk/node_modules/@ethersproject/signing-key/lib/index.d.ts:12
