[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Signer

# Class: Signer

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Signer

## Hierarchy

- **`Signer`**

  ↳ [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

  ↳ [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Signer.md#constructor)

### Properties

- [\_isSigner](akashaproject_awf_sdk._internal_.Signer.md#_issigner)
- [provider](akashaproject_awf_sdk._internal_.Signer.md#provider)

### Methods

- [\_checkProvider](akashaproject_awf_sdk._internal_.Signer.md#_checkprovider)
- [call](akashaproject_awf_sdk._internal_.Signer.md#call)
- [checkTransaction](akashaproject_awf_sdk._internal_.Signer.md#checktransaction)
- [connect](akashaproject_awf_sdk._internal_.Signer.md#connect)
- [estimateGas](akashaproject_awf_sdk._internal_.Signer.md#estimategas)
- [getAddress](akashaproject_awf_sdk._internal_.Signer.md#getaddress)
- [getBalance](akashaproject_awf_sdk._internal_.Signer.md#getbalance)
- [getChainId](akashaproject_awf_sdk._internal_.Signer.md#getchainid)
- [getFeeData](akashaproject_awf_sdk._internal_.Signer.md#getfeedata)
- [getGasPrice](akashaproject_awf_sdk._internal_.Signer.md#getgasprice)
- [getTransactionCount](akashaproject_awf_sdk._internal_.Signer.md#gettransactioncount)
- [populateTransaction](akashaproject_awf_sdk._internal_.Signer.md#populatetransaction)
- [resolveName](akashaproject_awf_sdk._internal_.Signer.md#resolvename)
- [sendTransaction](akashaproject_awf_sdk._internal_.Signer.md#sendtransaction)
- [signMessage](akashaproject_awf_sdk._internal_.Signer.md#signmessage)
- [signTransaction](akashaproject_awf_sdk._internal_.Signer.md#signtransaction)
- [isSigner](akashaproject_awf_sdk._internal_.Signer.md#issigner)

## Constructors

### constructor

• **new Signer**()

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:30

## Properties

### \_isSigner

• `Readonly` **\_isSigner**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:29

___

### provider

• `Optional` `Readonly` **provider**: [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:24

## Methods

### \_checkProvider

▸ **_checkProvider**(`operation?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `operation?` | `string` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:42

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

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:40

___

### connect

▸ `Abstract` **connect**(`provider`): [`Signer`](akashaproject_awf_sdk._internal_.Signer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`Provider`](akashaproject_awf_sdk._internal_.Provider.md) |

#### Returns

[`Signer`](akashaproject_awf_sdk._internal_.Signer.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:28

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:33

___

### getAddress

▸ `Abstract` **getAddress**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:25

___

### getBalance

▸ **getBalance**(`blockTag?`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:31

___

### getChainId

▸ **getChainId**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:36

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:38

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

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

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:35

___

### signMessage

▸ `Abstract` **signMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_awf_sdk._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:26

___

### signTransaction

▸ `Abstract` **signTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:27

___

### isSigner

▸ `Static` **isSigner**(`value`): value is Signer

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is Signer

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:43
