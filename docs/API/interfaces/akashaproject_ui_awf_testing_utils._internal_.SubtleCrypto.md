[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / SubtleCrypto

# Interface: SubtleCrypto

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).SubtleCrypto

This Web Crypto API interface provides a number of low-level cryptographic functions. It is accessed via the Crypto.subtle properties available in a window context (via Window.crypto).

## Table of contents

### Methods

- [decrypt](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#decrypt)
- [deriveBits](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#derivebits)
- [deriveKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#derivekey)
- [digest](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#digest)
- [encrypt](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#encrypt)
- [exportKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#exportkey)
- [generateKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#generatekey)
- [importKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#importkey)
- [sign](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#sign)
- [unwrapKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#unwrapkey)
- [verify](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#verify)
- [wrapKey](akashaproject_ui_awf_testing_utils._internal_.SubtleCrypto.md#wrapkey)

## Methods

### decrypt

▸ **decrypt**(`algorithm`, `key`, `data`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaOaepParams`](akashaproject_ui_awf_testing_utils._internal_.RsaOaepParams.md) \| [`AesCtrParams`](akashaproject_ui_awf_testing_utils._internal_.AesCtrParams.md) \| [`AesCbcParams`](akashaproject_ui_awf_testing_utils._internal_.AesCbcParams.md) \| [`AesGcmParams`](akashaproject_ui_awf_testing_utils._internal_.AesGcmParams.md) |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `data` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14447

___

### deriveBits

▸ **deriveBits**(`algorithm`, `baseKey`, `length`): `Promise`<`ArrayBuffer`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`EcdhKeyDeriveParams`](akashaproject_ui_awf_testing_utils._internal_.EcdhKeyDeriveParams.md) \| [`HkdfParams`](akashaproject_ui_awf_testing_utils._internal_.HkdfParams.md) \| [`Pbkdf2Params`](akashaproject_ui_awf_testing_utils._internal_.Pbkdf2Params.md) |
| `baseKey` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `length` | `number` |

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14448

___

### deriveKey

▸ **deriveKey**(`algorithm`, `baseKey`, `derivedKeyType`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`EcdhKeyDeriveParams`](akashaproject_ui_awf_testing_utils._internal_.EcdhKeyDeriveParams.md) \| [`HkdfParams`](akashaproject_ui_awf_testing_utils._internal_.HkdfParams.md) \| [`Pbkdf2Params`](akashaproject_ui_awf_testing_utils._internal_.Pbkdf2Params.md) |
| `baseKey` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `derivedKeyType` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`HkdfParams`](akashaproject_ui_awf_testing_utils._internal_.HkdfParams.md) \| [`Pbkdf2Params`](akashaproject_ui_awf_testing_utils._internal_.Pbkdf2Params.md) \| [`AesDerivedKeyParams`](akashaproject_ui_awf_testing_utils._internal_.AesDerivedKeyParams.md) \| [`HmacImportParams`](akashaproject_ui_awf_testing_utils._internal_.HmacImportParams.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14449

___

### digest

▸ **digest**(`algorithm`, `data`): `Promise`<`ArrayBuffer`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) |
| `data` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14450

___

### encrypt

▸ **encrypt**(`algorithm`, `key`, `data`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaOaepParams`](akashaproject_ui_awf_testing_utils._internal_.RsaOaepParams.md) \| [`AesCtrParams`](akashaproject_ui_awf_testing_utils._internal_.AesCtrParams.md) \| [`AesCbcParams`](akashaproject_ui_awf_testing_utils._internal_.AesCbcParams.md) \| [`AesGcmParams`](akashaproject_ui_awf_testing_utils._internal_.AesGcmParams.md) |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `data` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`any`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14451

___

### exportKey

▸ **exportKey**(`format`, `key`): `Promise`<[`JsonWebKey`](akashaproject_ui_awf_testing_utils._internal_.JsonWebKey.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | ``"jwk"`` |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |

#### Returns

`Promise`<[`JsonWebKey`](akashaproject_ui_awf_testing_utils._internal_.JsonWebKey.md)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14452

▸ **exportKey**(`format`, `key`): `Promise`<`ArrayBuffer`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | ``"pkcs8"`` \| ``"raw"`` \| ``"spki"`` |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14453

___

### generateKey

▸ **generateKey**(`algorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKeyPair`](akashaproject_ui_awf_testing_utils._internal_.CryptoKeyPair.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`RsaHashedKeyGenParams`](akashaproject_ui_awf_testing_utils._internal_.RsaHashedKeyGenParams.md) \| [`EcKeyGenParams`](akashaproject_ui_awf_testing_utils._internal_.EcKeyGenParams.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKeyPair`](akashaproject_ui_awf_testing_utils._internal_.CryptoKeyPair.md)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14454

▸ **generateKey**(`algorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`Pbkdf2Params`](akashaproject_ui_awf_testing_utils._internal_.Pbkdf2Params.md) \| [`AesKeyGenParams`](akashaproject_ui_awf_testing_utils._internal_.AesKeyGenParams.md) \| [`HmacKeyGenParams`](akashaproject_ui_awf_testing_utils._internal_.HmacKeyGenParams.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14455

▸ **generateKey**(`algorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) \| [`CryptoKeyPair`](akashaproject_ui_awf_testing_utils._internal_.CryptoKeyPair.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) \| [`CryptoKeyPair`](akashaproject_ui_awf_testing_utils._internal_.CryptoKeyPair.md)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14456

___

### importKey

▸ **importKey**(`format`, `keyData`, `algorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | ``"jwk"`` |
| `keyData` | [`JsonWebKey`](akashaproject_ui_awf_testing_utils._internal_.JsonWebKey.md) |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`HmacImportParams`](akashaproject_ui_awf_testing_utils._internal_.HmacImportParams.md) \| [`RsaHashedImportParams`](akashaproject_ui_awf_testing_utils._internal_.RsaHashedImportParams.md) \| [`EcKeyImportParams`](akashaproject_ui_awf_testing_utils._internal_.EcKeyImportParams.md) \| [`AesKeyAlgorithm`](akashaproject_ui_awf_testing_utils._internal_.AesKeyAlgorithm.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14457

▸ **importKey**(`format`, `keyData`, `algorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | ``"pkcs8"`` \| ``"raw"`` \| ``"spki"`` |
| `keyData` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`HmacImportParams`](akashaproject_ui_awf_testing_utils._internal_.HmacImportParams.md) \| [`RsaHashedImportParams`](akashaproject_ui_awf_testing_utils._internal_.RsaHashedImportParams.md) \| [`EcKeyImportParams`](akashaproject_ui_awf_testing_utils._internal_.EcKeyImportParams.md) \| [`AesKeyAlgorithm`](akashaproject_ui_awf_testing_utils._internal_.AesKeyAlgorithm.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14458

___

### sign

▸ **sign**(`algorithm`, `key`, `data`): `Promise`<`ArrayBuffer`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaPssParams`](akashaproject_ui_awf_testing_utils._internal_.RsaPssParams.md) \| [`EcdsaParams`](akashaproject_ui_awf_testing_utils._internal_.EcdsaParams.md) |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `data` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14459

___

### unwrapKey

▸ **unwrapKey**(`format`, `wrappedKey`, `unwrappingKey`, `unwrapAlgorithm`, `unwrappedKeyAlgorithm`, `extractable`, `keyUsages`): `Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | [`KeyFormat`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyformat) |
| `wrappedKey` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |
| `unwrappingKey` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `unwrapAlgorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaOaepParams`](akashaproject_ui_awf_testing_utils._internal_.RsaOaepParams.md) \| [`AesCtrParams`](akashaproject_ui_awf_testing_utils._internal_.AesCtrParams.md) \| [`AesCbcParams`](akashaproject_ui_awf_testing_utils._internal_.AesCbcParams.md) \| [`AesGcmParams`](akashaproject_ui_awf_testing_utils._internal_.AesGcmParams.md) |
| `unwrappedKeyAlgorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`HmacImportParams`](akashaproject_ui_awf_testing_utils._internal_.HmacImportParams.md) \| [`RsaHashedImportParams`](akashaproject_ui_awf_testing_utils._internal_.RsaHashedImportParams.md) \| [`EcKeyImportParams`](akashaproject_ui_awf_testing_utils._internal_.EcKeyImportParams.md) \| [`AesKeyAlgorithm`](akashaproject_ui_awf_testing_utils._internal_.AesKeyAlgorithm.md) |
| `extractable` | `boolean` |
| `keyUsages` | [`KeyUsage`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyusage)[] |

#### Returns

`Promise`<[`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14460

___

### verify

▸ **verify**(`algorithm`, `key`, `signature`, `data`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `algorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaPssParams`](akashaproject_ui_awf_testing_utils._internal_.RsaPssParams.md) \| [`EcdsaParams`](akashaproject_ui_awf_testing_utils._internal_.EcdsaParams.md) |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `signature` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |
| `data` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14461

___

### wrapKey

▸ **wrapKey**(`format`, `key`, `wrappingKey`, `wrapAlgorithm`): `Promise`<`ArrayBuffer`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | [`KeyFormat`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#keyformat) |
| `key` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `wrappingKey` | [`CryptoKey`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cryptokey) |
| `wrapAlgorithm` | [`AlgorithmIdentifier`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#algorithmidentifier) \| [`RsaOaepParams`](akashaproject_ui_awf_testing_utils._internal_.RsaOaepParams.md) \| [`AesCtrParams`](akashaproject_ui_awf_testing_utils._internal_.AesCtrParams.md) \| [`AesCbcParams`](akashaproject_ui_awf_testing_utils._internal_.AesCbcParams.md) \| [`AesGcmParams`](akashaproject_ui_awf_testing_utils._internal_.AesGcmParams.md) |

#### Returns

`Promise`<`ArrayBuffer`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14462
