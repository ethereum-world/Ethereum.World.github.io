[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / UncheckedJsonRpcSigner

# Class: UncheckedJsonRpcSigner

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).UncheckedJsonRpcSigner

## Hierarchy

- [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

  ↳ **`UncheckedJsonRpcSigner`**

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#constructor)

### Properties

- [\_address](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_address)
- [\_index](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_index)
- [\_isSigner](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_issigner)
- [provider](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#provider)

### Methods

- [\_checkProvider](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_checkprovider)
- [\_legacySignMessage](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_legacysignmessage)
- [\_signTypedData](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#_signtypeddata)
- [call](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#call)
- [checkTransaction](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#checktransaction)
- [connect](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#connect)
- [connectUnchecked](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#connectunchecked)
- [estimateGas](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#estimategas)
- [getAddress](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#getaddress)
- [getBalance](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#getbalance)
- [getChainId](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#getchainid)
- [getFeeData](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#getfeedata)
- [getGasPrice](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#getgasprice)
- [getTransactionCount](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#gettransactioncount)
- [populateTransaction](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#populatetransaction)
- [resolveName](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#resolvename)
- [sendTransaction](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#sendtransaction)
- [sendUncheckedTransaction](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#senduncheckedtransaction)
- [signMessage](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#signmessage)
- [signTransaction](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#signtransaction)
- [unlock](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#unlock)
- [isSigner](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md#issigner)

## Constructors

### constructor

• **new UncheckedJsonRpcSigner**(`constructorGuard`, `provider`, `addressOrIndex?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `constructorGuard` | `any` |
| `provider` | [`JsonRpcProvider`](akashaproject_awf_sdk._internal_.JsonRpcProvider.md) |
| `addressOrIndex?` | `string` \| `number` |

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[constructor](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:13

## Properties

### \_address

• **\_address**: `string`

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_address](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_address)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:12

___

### \_index

• **\_index**: `number`

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_index](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_index)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:11

___

### \_isSigner

• `Readonly` **\_isSigner**: `boolean`

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_isSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:29

___

### provider

• `Readonly` **provider**: [`JsonRpcProvider`](akashaproject_awf_sdk._internal_.JsonRpcProvider.md)

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[provider](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#provider)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:10

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_checkProvider](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_checkprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:42

___

### \_legacySignMessage

▸ **_legacySignMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_legacySignMessage](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_legacysignmessage)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:21

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

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[_signTypedData](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#_signtypeddata)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:22

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[call](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#call)

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[checkTransaction](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#checktransaction)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:40

___

### connect

▸ **connect**(`provider`): [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`Provider`](akashaproject_awf_sdk._internal_.Provider.md) |

#### Returns

[`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[connect](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#connect)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:14

___

### connectUnchecked

▸ **connectUnchecked**(): [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Returns

[`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[connectUnchecked](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#connectunchecked)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:15

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[estimateGas](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#estimategas)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:33

___

### getAddress

▸ **getAddress**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getAddress](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#getaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:16

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getBalance](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#getbalance)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:31

___

### getChainId

▸ **getChainId**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getChainId](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#getchainid)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:36

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getFeeData](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:38

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getGasPrice](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#getgasprice)

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[getTransactionCount](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#gettransactioncount)

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[populateTransaction](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#populatetransaction)

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[resolveName](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#resolvename)

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

#### Overrides

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[sendTransaction](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#sendtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:26

___

### sendUncheckedTransaction

▸ **sendUncheckedTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[sendUncheckedTransaction](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#senduncheckedtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:17

___

### signMessage

▸ **signMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[signMessage](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#signmessage)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:20

___

### signTransaction

▸ **signTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[signTransaction](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#signtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:18

___

### unlock

▸ **unlock**(`password`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `string` |

#### Returns

`Promise`<`boolean`\>

#### Inherited from

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[unlock](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#unlock)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:23

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

[JsonRpcSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md).[isSigner](akashaproject_awf_sdk._internal_.JsonRpcSigner.md#issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:43
