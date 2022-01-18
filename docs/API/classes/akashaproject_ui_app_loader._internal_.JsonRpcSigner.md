[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / JsonRpcSigner

# Class: JsonRpcSigner

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).JsonRpcSigner

## Hierarchy

- [`Signer`](akashaproject_ui_app_loader._internal_.Signer.md)

  ↳ **`JsonRpcSigner`**

  ↳↳ [`UncheckedJsonRpcSigner`](akashaproject_ui_app_loader._internal_.UncheckedJsonRpcSigner.md)

## Implements

- [`TypedDataSigner`](../interfaces/akashaproject_ui_app_loader._internal_.TypedDataSigner.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#constructor)

### Properties

- [\_address](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_address)
- [\_index](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_index)
- [\_isSigner](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_issigner)
- [provider](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#provider)

### Methods

- [\_checkProvider](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_checkprovider)
- [\_legacySignMessage](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_legacysignmessage)
- [\_signTypedData](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#_signtypeddata)
- [call](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#call)
- [checkTransaction](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#checktransaction)
- [connect](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#connect)
- [connectUnchecked](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#connectunchecked)
- [estimateGas](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#estimategas)
- [getAddress](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#getaddress)
- [getBalance](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#getbalance)
- [getChainId](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#getchainid)
- [getFeeData](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#getfeedata)
- [getGasPrice](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#getgasprice)
- [getTransactionCount](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#gettransactioncount)
- [populateTransaction](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#populatetransaction)
- [resolveName](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#resolvename)
- [sendTransaction](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#sendtransaction)
- [sendUncheckedTransaction](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#senduncheckedtransaction)
- [signMessage](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#signmessage)
- [signTransaction](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#signtransaction)
- [unlock](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#unlock)
- [isSigner](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md#issigner)

## Constructors

### constructor

• **new JsonRpcSigner**(`constructorGuard`, `provider`, `addressOrIndex?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `constructorGuard` | `any` |
| `provider` | [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md) |
| `addressOrIndex?` | `string` \| `number` |

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[constructor](akashaproject_ui_app_loader._internal_.Signer.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:13

## Properties

### \_address

• **\_address**: `string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:12

___

### \_index

• **\_index**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:11

___

### \_isSigner

• `Readonly` **\_isSigner**: `boolean`

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[_isSigner](akashaproject_ui_app_loader._internal_.Signer.md#_issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:29

___

### provider

• `Readonly` **provider**: [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[provider](akashaproject_ui_app_loader._internal_.Signer.md#provider)

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

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[_checkProvider](akashaproject_ui_app_loader._internal_.Signer.md#_checkprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:42

___

### \_legacySignMessage

▸ **_legacySignMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_ui_app_loader._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:21

___

### \_signTypedData

▸ **_signTypedData**(`domain`, `types`, `value`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `domain` | [`TypedDataDomain`](../interfaces/akashaproject_ui_app_loader._internal_.TypedDataDomain.md) |
| `types` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`TypedDataField`](../interfaces/akashaproject_ui_app_loader._internal_.TypedDataField.md)[]\> |
| `value` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |

#### Returns

`Promise`<`string`\>

#### Implementation of

[TypedDataSigner](../interfaces/akashaproject_ui_app_loader._internal_.TypedDataSigner.md).[_signTypedData](../interfaces/akashaproject_ui_app_loader._internal_.TypedDataSigner.md#_signtypeddata)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:22

___

### call

▸ **call**(`transaction`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) |

#### Returns

`Promise`<`string`\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[call](akashaproject_ui_app_loader._internal_.Signer.md#call)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:34

___

### checkTransaction

▸ **checkTransaction**(`transaction`): [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

[`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[checkTransaction](akashaproject_ui_app_loader._internal_.Signer.md#checktransaction)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:40

___

### connect

▸ **connect**(`provider`): [`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`Provider`](akashaproject_ui_app_loader._internal_.Provider.md) |

#### Returns

[`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[connect](akashaproject_ui_app_loader._internal_.Signer.md#connect)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:14

___

### connectUnchecked

▸ **connectUnchecked**(): [`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Returns

[`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:15

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[estimateGas](akashaproject_ui_app_loader._internal_.Signer.md#estimategas)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:33

___

### getAddress

▸ **getAddress**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getAddress](akashaproject_ui_app_loader._internal_.Signer.md#getaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:16

___

### getBalance

▸ **getBalance**(`blockTag?`): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) |

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getBalance](akashaproject_ui_app_loader._internal_.Signer.md#getbalance)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:31

___

### getChainId

▸ **getChainId**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getChainId](akashaproject_ui_app_loader._internal_.Signer.md#getchainid)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:36

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getFeeData](akashaproject_ui_app_loader._internal_.Signer.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:38

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getGasPrice](akashaproject_ui_app_loader._internal_.Signer.md#getgasprice)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:37

___

### getTransactionCount

▸ **getTransactionCount**(`blockTag?`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) |

#### Returns

`Promise`<`number`\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[getTransactionCount](akashaproject_ui_app_loader._internal_.Signer.md#gettransactioncount)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:32

___

### populateTransaction

▸ **populateTransaction**(`transaction`): `Promise`<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\>

#### Inherited from

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[populateTransaction](akashaproject_ui_app_loader._internal_.Signer.md#populatetransaction)

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

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[resolveName](akashaproject_ui_app_loader._internal_.Signer.md#resolvename)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:39

___

### sendTransaction

▸ **sendTransaction**(`transaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[sendTransaction](akashaproject_ui_app_loader._internal_.Signer.md#sendtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:19

___

### sendUncheckedTransaction

▸ **sendUncheckedTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:17

___

### signMessage

▸ **signMessage**(`message`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| [`Bytes`](../modules/akashaproject_ui_app_loader._internal_.md#bytes) |

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[signMessage](akashaproject_ui_app_loader._internal_.Signer.md#signmessage)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:20

___

### signTransaction

▸ **signTransaction**(`transaction`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<`string`\>

#### Overrides

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[signTransaction](akashaproject_ui_app_loader._internal_.Signer.md#signtransaction)

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

[Signer](akashaproject_ui_app_loader._internal_.Signer.md).[isSigner](akashaproject_ui_app_loader._internal_.Signer.md#issigner)

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:43
