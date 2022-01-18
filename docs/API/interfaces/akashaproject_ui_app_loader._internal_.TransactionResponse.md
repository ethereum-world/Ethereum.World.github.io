[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / TransactionResponse

# Interface: TransactionResponse

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).TransactionResponse

## Hierarchy

- [`Transaction`](akashaproject_ui_app_loader._internal_.Transaction.md)

  ↳ **`TransactionResponse`**

## Table of contents

### Properties

- [accessList](akashaproject_ui_app_loader._internal_.TransactionResponse.md#accesslist)
- [blockHash](akashaproject_ui_app_loader._internal_.TransactionResponse.md#blockhash)
- [blockNumber](akashaproject_ui_app_loader._internal_.TransactionResponse.md#blocknumber)
- [chainId](akashaproject_ui_app_loader._internal_.TransactionResponse.md#chainid)
- [confirmations](akashaproject_ui_app_loader._internal_.TransactionResponse.md#confirmations)
- [data](akashaproject_ui_app_loader._internal_.TransactionResponse.md#data)
- [from](akashaproject_ui_app_loader._internal_.TransactionResponse.md#from)
- [gasLimit](akashaproject_ui_app_loader._internal_.TransactionResponse.md#gaslimit)
- [gasPrice](akashaproject_ui_app_loader._internal_.TransactionResponse.md#gasprice)
- [hash](akashaproject_ui_app_loader._internal_.TransactionResponse.md#hash)
- [maxFeePerGas](akashaproject_ui_app_loader._internal_.TransactionResponse.md#maxfeepergas)
- [maxPriorityFeePerGas](akashaproject_ui_app_loader._internal_.TransactionResponse.md#maxpriorityfeepergas)
- [nonce](akashaproject_ui_app_loader._internal_.TransactionResponse.md#nonce)
- [r](akashaproject_ui_app_loader._internal_.TransactionResponse.md#r)
- [raw](akashaproject_ui_app_loader._internal_.TransactionResponse.md#raw)
- [s](akashaproject_ui_app_loader._internal_.TransactionResponse.md#s)
- [timestamp](akashaproject_ui_app_loader._internal_.TransactionResponse.md#timestamp)
- [to](akashaproject_ui_app_loader._internal_.TransactionResponse.md#to)
- [type](akashaproject_ui_app_loader._internal_.TransactionResponse.md#type)
- [v](akashaproject_ui_app_loader._internal_.TransactionResponse.md#v)
- [value](akashaproject_ui_app_loader._internal_.TransactionResponse.md#value)

### Methods

- [wait](akashaproject_ui_app_loader._internal_.TransactionResponse.md#wait)

## Properties

### accessList

• `Optional` **accessList**: [`AccessList`](../modules/akashaproject_ui_app_loader._internal_.md#accesslist)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[accessList](akashaproject_ui_app_loader._internal_.Transaction.md#accesslist)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:40

___

### blockHash

• `Optional` **blockHash**: `string`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:25

___

### blockNumber

• `Optional` **blockNumber**: `number`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:24

___

### chainId

• **chainId**: `number`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[chainId](akashaproject_ui_app_loader._internal_.Transaction.md#chainid)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:35

___

### confirmations

• **confirmations**: `number`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:27

___

### data

• **data**: `string`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[data](akashaproject_ui_app_loader._internal_.Transaction.md#data)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:33

___

### from

• **from**: `string`

#### Overrides

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[from](akashaproject_ui_app_loader._internal_.Transaction.md#from)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:28

___

### gasLimit

• **gasLimit**: [`BigNumber`](../classes/akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[gasLimit](akashaproject_ui_app_loader._internal_.Transaction.md#gaslimit)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:31

___

### gasPrice

• `Optional` **gasPrice**: [`BigNumber`](../classes/akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[gasPrice](akashaproject_ui_app_loader._internal_.Transaction.md#gasprice)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:32

___

### hash

• **hash**: `string`

#### Overrides

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[hash](akashaproject_ui_app_loader._internal_.Transaction.md#hash)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:23

___

### maxFeePerGas

• `Optional` **maxFeePerGas**: [`BigNumber`](../classes/akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[maxFeePerGas](akashaproject_ui_app_loader._internal_.Transaction.md#maxfeepergas)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:42

___

### maxPriorityFeePerGas

• `Optional` **maxPriorityFeePerGas**: [`BigNumber`](../classes/akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[maxPriorityFeePerGas](akashaproject_ui_app_loader._internal_.Transaction.md#maxpriorityfeepergas)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:41

___

### nonce

• **nonce**: `number`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[nonce](akashaproject_ui_app_loader._internal_.Transaction.md#nonce)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:30

___

### r

• `Optional` **r**: `string`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[r](akashaproject_ui_app_loader._internal_.Transaction.md#r)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:36

___

### raw

• `Optional` **raw**: `string`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:29

___

### s

• `Optional` **s**: `string`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[s](akashaproject_ui_app_loader._internal_.Transaction.md#s)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:37

___

### timestamp

• `Optional` **timestamp**: `number`

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:26

___

### to

• `Optional` **to**: `string`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[to](akashaproject_ui_app_loader._internal_.Transaction.md#to)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:28

___

### type

• `Optional` **type**: `number`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[type](akashaproject_ui_app_loader._internal_.Transaction.md#type)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:39

___

### v

• `Optional` **v**: `number`

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[v](akashaproject_ui_app_loader._internal_.Transaction.md#v)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:38

___

### value

• **value**: [`BigNumber`](../classes/akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Inherited from

[Transaction](akashaproject_ui_app_loader._internal_.Transaction.md).[value](akashaproject_ui_app_loader._internal_.Transaction.md#value)

#### Defined in

sdk/node_modules/@ethersproject/transactions/lib/index.d.ts:34

## Methods

### wait

▸ **wait**(`confirmations?`): `Promise`<[`TransactionReceipt`](akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `confirmations?` | `number` |

#### Returns

`Promise`<[`TransactionReceipt`](akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:30
