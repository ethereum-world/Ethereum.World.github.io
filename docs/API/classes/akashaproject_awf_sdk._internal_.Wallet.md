[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Wallet

# Class: Wallet

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Wallet

## Hierarchy

- [`Signer`](akashaproject_awf_sdk._internal_.Signer.md)

  ↳ **`Wallet`**

## Implements

- [`ExternallyOwnedAccount`](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md)
- [`TypedDataSigner`](../interfaces/akashaproject_awf_sdk._internal_.TypedDataSigner.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Wallet.md#constructor)

### Properties

- [\_isSigner](akashaproject_awf_sdk._internal_.Wallet.md#_issigner)
- [\_mnemonic](akashaproject_awf_sdk._internal_.Wallet.md#_mnemonic)
- [\_signingKey](akashaproject_awf_sdk._internal_.Wallet.md#_signingkey)
- [address](akashaproject_awf_sdk._internal_.Wallet.md#address)
- [provider](akashaproject_awf_sdk._internal_.Wallet.md#provider)

### Accessors

- [mnemonic](akashaproject_awf_sdk._internal_.Wallet.md#mnemonic)
- [privateKey](akashaproject_awf_sdk._internal_.Wallet.md#privatekey)
- [publicKey](akashaproject_awf_sdk._internal_.Wallet.md#publickey)

### Methods

- [\_checkProvider](akashaproject_awf_sdk._internal_.Wallet.md#_checkprovider)
- [\_signTypedData](akashaproject_awf_sdk._internal_.Wallet.md#_signtypeddata)
- [call](akashaproject_awf_sdk._internal_.Wallet.md#call)
- [checkTransaction](akashaproject_awf_sdk._internal_.Wallet.md#checktransaction)
- [connect](akashaproject_awf_sdk._internal_.Wallet.md#connect)
- [encrypt](akashaproject_awf_sdk._internal_.Wallet.md#encrypt)
- [estimateGas](akashaproject_awf_sdk._internal_.Wallet.md#estimategas)
- [getAddress](akashaproject_awf_sdk._internal_.Wallet.md#getaddress)
- [getBalance](akashaproject_awf_sdk._internal_.Wallet.md#getbalance)
- [getChainId](akashaproject_awf_sdk._internal_.Wallet.md#getchainid)
- [getFeeData](akashaproject_awf_sdk._internal_.Wallet.md#getfeedata)
- [getGasPrice](akashaproject_awf_sdk._internal_.Wallet.md#getgasprice)
- [getTransactionCount](akashaproject_awf_sdk._internal_.Wallet.md#gettransactioncount)
- [populateTransaction](akashaproject_awf_sdk._internal_.Wallet.md#populatetransaction)
- [resolveName](akashaproject_awf_sdk._internal_.Wallet.md#resolvename)
- [sendTransaction](akashaproject_awf_sdk._internal_.Wallet.md#sendtransaction)
- [signMessage](akashaproject_awf_sdk._internal_.Wallet.md#signmessage)
- [signTransaction](akashaproject_awf_sdk._internal_.Wallet.md#signtransaction)
- [createRandom](akashaproject_awf_sdk._internal_.Wallet.md#createrandom)
- [fromEncryptedJson](akashaproject_awf_sdk._internal_.Wallet.md#fromencryptedjson)
- [fromEncryptedJsonSync](akashaproject_awf_sdk._internal_.Wallet.md#fromencryptedjsonsync)
- [fromMnemonic](akashaproject_awf_sdk._internal_.Wallet.md#frommnemonic)
- [isSigner](akashaproject_awf_sdk._internal_.Wallet.md#issigner)

## Constructors

### constructor

• **new Wallet**(`privateKey`, `provider?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKey` | [`BytesLike`](../modules/akashaproject_awf_sdk._internal_.md#byteslike) \| [`ExternallyOwnedAccount`](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md) \| [`SigningKey`](akashaproject_awf_sdk._internal_.SigningKey.md) |
| `provider?` | [`Provider`](akashaproject_awf_sdk._internal_.Provider.md) |

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[constructor](akashaproject_awf_sdk._internal_.Signer.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:13

## Properties

### \_isSigner

• `Readonly` **\_isSigner**: `boolean`

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[_isSigner](akashaproject_awf_sdk._internal_.Signer.md#_issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:29

___

### \_mnemonic

• `Readonly` **\_mnemonic**: () => [`Mnemonic`](../interfaces/akashaproject_awf_sdk._internal_.Mnemonic.md)

#### Type declaration

▸ (): [`Mnemonic`](../interfaces/akashaproject_awf_sdk._internal_.Mnemonic.md)

##### Returns

[`Mnemonic`](../interfaces/akashaproject_awf_sdk._internal_.Mnemonic.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:12

___

### \_signingKey

• `Readonly` **\_signingKey**: () => [`SigningKey`](akashaproject_awf_sdk._internal_.SigningKey.md)

#### Type declaration

▸ (): [`SigningKey`](akashaproject_awf_sdk._internal_.SigningKey.md)

##### Returns

[`SigningKey`](akashaproject_awf_sdk._internal_.SigningKey.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:11

___

### address

• `Readonly` **address**: `string`

#### Implementation of

[ExternallyOwnedAccount](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md).[address](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md#address)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:9

___

### provider

• `Readonly` **provider**: [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[provider](akashaproject_awf_sdk._internal_.Signer.md#provider)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:10

## Accessors

### mnemonic

• `get` **mnemonic**(): [`Mnemonic`](../interfaces/akashaproject_awf_sdk._internal_.Mnemonic.md)

#### Returns

[`Mnemonic`](../interfaces/akashaproject_awf_sdk._internal_.Mnemonic.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:14

___

### privateKey

• `get` **privateKey**(): `string`

#### Returns

`string`

#### Implementation of

[ExternallyOwnedAccount](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md).[privateKey](../interfaces/akashaproject_awf_sdk._internal_.ExternallyOwnedAccount.md#privatekey)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:15

___

### publicKey

• `get` **publicKey**(): `string`

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:16

## Methods

### \_checkProvider

▸ **_checkProvider**(`operation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `operation?` | `string` |

#### Returns

`void`

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[_checkProvider](akashaproject_awf_sdk._internal_.Signer.md#_checkprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:42

___

### \_signTypedData

▸ **_signTypedData**(`domain`, `types`, `value`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `domain` | [`TypedDataDomain`](../interfaces/akashaproject_awf_sdk._internal_.TypedDataDomain.md) |
| `types` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, [`TypedDataField`](../interfaces/akashaproject_awf_sdk._internal_.TypedDataField.md)[]\> |
| `value` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |

#### Returns

`Promise`<`string`\>

#### Implementation of

[TypedDataSigner](../interfaces/akashaproject_awf_sdk._internal_.TypedDataSigner.md).[_signTypedData](../interfaces/akashaproject_awf_sdk._internal_.TypedDataSigner.md#_signtypeddata)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:21

___

### call

▸ **call**(`transaction`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) |

#### Returns

`Promise`<`string`\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[call](akashaproject_awf_sdk._internal_.Signer.md#call)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:34

___

### checkTransaction

▸ **checkTransaction**(`transaction`): [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

[`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[checkTransaction](akashaproject_awf_sdk._internal_.Signer.md#checktransaction)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:40

___

### connect

▸ **connect**(`provider`): [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`Provider`](akashaproject_awf_sdk._internal_.Provider.md) |

#### Returns

[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[connect](akashaproject_awf_sdk._internal_.Signer.md#connect)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:18

___

### encrypt

▸ **encrypt**(`password`, `options?`, `progressCallback?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |
| `options?` | `any` |
| `progressCallback?` | [`ProgressCallback`](../modules/akashaproject_awf_sdk._internal_.md#progresscallback) |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:22

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[estimateGas](akashaproject_awf_sdk._internal_.Signer.md#estimategas)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:33

___

### getAddress

▸ **getAddress**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getAddress](akashaproject_awf_sdk._internal_.Signer.md#getaddress)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:17

___

### getBalance

▸ **getBalance**(`blockTag?`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getBalance](akashaproject_awf_sdk._internal_.Signer.md#getbalance)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:31

___

### getChainId

▸ **getChainId**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getChainId](akashaproject_awf_sdk._internal_.Signer.md#getchainid)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:36

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getFeeData](akashaproject_awf_sdk._internal_.Signer.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:38

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getGasPrice](akashaproject_awf_sdk._internal_.Signer.md#getgasprice)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:37

___

### getTransactionCount

▸ **getTransactionCount**(`blockTag?`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) |

#### Returns

`Promise`<`number`\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[getTransactionCount](akashaproject_awf_sdk._internal_.Signer.md#gettransactioncount)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:32

___

### populateTransaction

▸ **populateTransaction**(`transaction`): `Promise`<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[populateTransaction](akashaproject_awf_sdk._internal_.Signer.md#populatetransaction)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:41

___

### resolveName

▸ **resolveName**(`name`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`string`\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[resolveName](akashaproject_awf_sdk._internal_.Signer.md#resolvename)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:39

___

### sendTransaction

▸ **sendTransaction**(`transaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[sendTransaction](akashaproject_awf_sdk._internal_.Signer.md#sendtransaction)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:35

___

### signMessage

▸ **signMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[signMessage](akashaproject_awf_sdk._internal_.Signer.md#signmessage)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:20

___

### signTransaction

▸ **signTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest) |

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[signTransaction](akashaproject_awf_sdk._internal_.Signer.md#signtransaction)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:19

___

### createRandom

▸ `Static` **createRandom**(`options?`): [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

 Static methods to create Wallet instances.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `any` |

#### Returns

[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:26

___

### fromEncryptedJson

▸ `Static` **fromEncryptedJson**(`json`, `password`, `progressCallback?`): `Promise`<[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `password` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |
| `progressCallback?` | [`ProgressCallback`](../modules/akashaproject_awf_sdk._internal_.md#progresscallback) |

#### Returns

`Promise`<[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)\>

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:27

___

### fromEncryptedJsonSync

▸ `Static` **fromEncryptedJsonSync**(`json`, `password`): [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `json` | `string` |
| `password` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |

#### Returns

[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:28

___

### fromMnemonic

▸ `Static` **fromMnemonic**(`mnemonic`, `path?`, `wordlist?`): [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `mnemonic` | `string` |
| `path?` | `string` |
| `wordlist?` | [`Wordlist`](akashaproject_awf_sdk._internal_.Wordlist.md) |

#### Returns

[`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Defined in

sdk/node_modules/@ethersproject/wallet/lib/index.d.ts:29

___

### isSigner

▸ `Static` **isSigner**(`value`): value is Signer

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is Signer

#### Inherited from

[Signer](akashaproject_awf_sdk._internal_.Signer.md).[isSigner](akashaproject_awf_sdk._internal_.Signer.md#issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:43
