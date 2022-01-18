[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Provider

# Class: Provider

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Provider

## Hierarchy

- **`Provider`**

  ↳ [`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md)

## Implements

- [`OnceBlockable`](../interfaces/akashaproject_awf_sdk._internal_.OnceBlockable.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Provider.md#constructor)

### Properties

- [\_isProvider](akashaproject_awf_sdk._internal_.Provider.md#_isprovider)

### Methods

- [addListener](akashaproject_awf_sdk._internal_.Provider.md#addlistener)
- [call](akashaproject_awf_sdk._internal_.Provider.md#call)
- [emit](akashaproject_awf_sdk._internal_.Provider.md#emit)
- [estimateGas](akashaproject_awf_sdk._internal_.Provider.md#estimategas)
- [getBalance](akashaproject_awf_sdk._internal_.Provider.md#getbalance)
- [getBlock](akashaproject_awf_sdk._internal_.Provider.md#getblock)
- [getBlockNumber](akashaproject_awf_sdk._internal_.Provider.md#getblocknumber)
- [getBlockWithTransactions](akashaproject_awf_sdk._internal_.Provider.md#getblockwithtransactions)
- [getCode](akashaproject_awf_sdk._internal_.Provider.md#getcode)
- [getFeeData](akashaproject_awf_sdk._internal_.Provider.md#getfeedata)
- [getGasPrice](akashaproject_awf_sdk._internal_.Provider.md#getgasprice)
- [getLogs](akashaproject_awf_sdk._internal_.Provider.md#getlogs)
- [getNetwork](akashaproject_awf_sdk._internal_.Provider.md#getnetwork)
- [getStorageAt](akashaproject_awf_sdk._internal_.Provider.md#getstorageat)
- [getTransaction](akashaproject_awf_sdk._internal_.Provider.md#gettransaction)
- [getTransactionCount](akashaproject_awf_sdk._internal_.Provider.md#gettransactioncount)
- [getTransactionReceipt](akashaproject_awf_sdk._internal_.Provider.md#gettransactionreceipt)
- [listenerCount](akashaproject_awf_sdk._internal_.Provider.md#listenercount)
- [listeners](akashaproject_awf_sdk._internal_.Provider.md#listeners)
- [lookupAddress](akashaproject_awf_sdk._internal_.Provider.md#lookupaddress)
- [off](akashaproject_awf_sdk._internal_.Provider.md#off)
- [on](akashaproject_awf_sdk._internal_.Provider.md#on)
- [once](akashaproject_awf_sdk._internal_.Provider.md#once)
- [removeAllListeners](akashaproject_awf_sdk._internal_.Provider.md#removealllisteners)
- [removeListener](akashaproject_awf_sdk._internal_.Provider.md#removelistener)
- [resolveName](akashaproject_awf_sdk._internal_.Provider.md#resolvename)
- [sendTransaction](akashaproject_awf_sdk._internal_.Provider.md#sendtransaction)
- [waitForTransaction](akashaproject_awf_sdk._internal_.Provider.md#waitfortransaction)
- [isProvider](akashaproject_awf_sdk._internal_.Provider.md#isprovider)

## Constructors

### constructor

• **new Provider**()

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:151

## Properties

### \_isProvider

• `Readonly` **\_isProvider**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:150

## Methods

### addListener

▸ **addListener**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:147

___

### call

▸ `Abstract` **call**(`transaction`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:131

___

### emit

▸ `Abstract` **emit**(`eventName`, ...`args`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:142

___

### estimateGas

▸ `Abstract` **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:132

___

### getBalance

▸ `Abstract` **getBalance**(`addressOrName`, `blockTag?`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:126

___

### getBlock

▸ `Abstract` **getBlock**(`blockHashOrBlockTag`): `Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:133

___

### getBlockNumber

▸ `Abstract` **getBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:123

___

### getBlockWithTransactions

▸ `Abstract` **getBlockWithTransactions**(`blockHashOrBlockTag`): `Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:134

___

### getCode

▸ `Abstract` **getCode**(`addressOrName`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:128

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:125

___

### getGasPrice

▸ `Abstract` **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:124

___

### getLogs

▸ `Abstract` **getLogs**(`filter`): `Promise`<[`Log`](../interfaces/akashaproject_awf_sdk._internal_.Log.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) |

#### Returns

`Promise`<[`Log`](../interfaces/akashaproject_awf_sdk._internal_.Log.md)[]\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:137

___

### getNetwork

▸ `Abstract` **getNetwork**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:122

___

### getStorageAt

▸ `Abstract` **getStorageAt**(`addressOrName`, `position`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `position` | [`BigNumberish`](../modules/akashaproject_awf_sdk._internal_.md#bignumberish) \| `Promise`<[`BigNumberish`](../modules/akashaproject_awf_sdk._internal_.md#bignumberish)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:129

___

### getTransaction

▸ `Abstract` **getTransaction**(`transactionHash`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:135

___

### getTransactionCount

▸ `Abstract` **getTransactionCount**(`addressOrName`, `blockTag?`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:127

___

### getTransactionReceipt

▸ `Abstract` **getTransactionReceipt**(`transactionHash`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:136

___

### listenerCount

▸ `Abstract` **listenerCount**(`eventName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:143

___

### listeners

▸ `Abstract` **listeners**(`eventName?`): [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

[`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener)[]

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:144

___

### lookupAddress

▸ `Abstract` **lookupAddress**(`address`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:139

___

### off

▸ `Abstract` **off**(`eventName`, `listener?`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener?` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:145

___

### on

▸ `Abstract` **on**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:140

___

### once

▸ `Abstract` **once**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Implementation of

[OnceBlockable](../interfaces/akashaproject_awf_sdk._internal_.OnceBlockable.md).[once](../interfaces/akashaproject_awf_sdk._internal_.OnceBlockable.md#once)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:141

___

### removeAllListeners

▸ `Abstract` **removeAllListeners**(`eventName?`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:146

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:148

___

### resolveName

▸ `Abstract` **resolveName**(`name`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:138

___

### sendTransaction

▸ `Abstract` **sendTransaction**(`signedTransaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signedTransaction` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:130

___

### waitForTransaction

▸ `Abstract` **waitForTransaction**(`transactionHash`, `confirmations?`, `timeout?`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations?` | `number` |
| `timeout?` | `number` |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:149

___

### isProvider

▸ `Static` **isProvider**(`value`): value is Provider

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is Provider

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:152
