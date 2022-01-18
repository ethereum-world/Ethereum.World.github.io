[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Formatter

# Class: Formatter

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Formatter

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Formatter.md#constructor)

### Properties

- [formats](akashaproject_awf_sdk._internal_.Formatter.md#formats)

### Methods

- [\_block](akashaproject_awf_sdk._internal_.Formatter.md#_block)
- [accessList](akashaproject_awf_sdk._internal_.Formatter.md#accesslist)
- [address](akashaproject_awf_sdk._internal_.Formatter.md#address)
- [bigNumber](akashaproject_awf_sdk._internal_.Formatter.md#bignumber)
- [block](akashaproject_awf_sdk._internal_.Formatter.md#block)
- [blockTag](akashaproject_awf_sdk._internal_.Formatter.md#blocktag)
- [blockWithTransactions](akashaproject_awf_sdk._internal_.Formatter.md#blockwithtransactions)
- [boolean](akashaproject_awf_sdk._internal_.Formatter.md#boolean)
- [callAddress](akashaproject_awf_sdk._internal_.Formatter.md#calladdress)
- [contractAddress](akashaproject_awf_sdk._internal_.Formatter.md#contractaddress)
- [data](akashaproject_awf_sdk._internal_.Formatter.md#data)
- [difficulty](akashaproject_awf_sdk._internal_.Formatter.md#difficulty)
- [filter](akashaproject_awf_sdk._internal_.Formatter.md#filter)
- [filterLog](akashaproject_awf_sdk._internal_.Formatter.md#filterlog)
- [getDefaultFormats](akashaproject_awf_sdk._internal_.Formatter.md#getdefaultformats)
- [hash](akashaproject_awf_sdk._internal_.Formatter.md#hash)
- [hex](akashaproject_awf_sdk._internal_.Formatter.md#hex)
- [number](akashaproject_awf_sdk._internal_.Formatter.md#number)
- [receipt](akashaproject_awf_sdk._internal_.Formatter.md#receipt)
- [receiptLog](akashaproject_awf_sdk._internal_.Formatter.md#receiptlog)
- [topics](akashaproject_awf_sdk._internal_.Formatter.md#topics)
- [transaction](akashaproject_awf_sdk._internal_.Formatter.md#transaction)
- [transactionRequest](akashaproject_awf_sdk._internal_.Formatter.md#transactionrequest)
- [transactionResponse](akashaproject_awf_sdk._internal_.Formatter.md#transactionresponse)
- [type](akashaproject_awf_sdk._internal_.Formatter.md#type)
- [uint256](akashaproject_awf_sdk._internal_.Formatter.md#uint256)
- [allowFalsish](akashaproject_awf_sdk._internal_.Formatter.md#allowfalsish)
- [allowNull](akashaproject_awf_sdk._internal_.Formatter.md#allownull)
- [arrayOf](akashaproject_awf_sdk._internal_.Formatter.md#arrayof)
- [check](akashaproject_awf_sdk._internal_.Formatter.md#check)

## Constructors

### constructor

• **new Formatter**()

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:20

## Properties

### formats

• `Readonly` **formats**: [`Formats`](../modules/akashaproject_awf_sdk._internal_.md#formats)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:19

## Methods

### \_block

▸ **_block**(`value`, `format`): [`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `format` | `any` |

#### Returns

[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:36

___

### accessList

▸ **accessList**(`accessList`): [`AccessList`](../modules/akashaproject_awf_sdk._internal_.md#accesslist)

#### Parameters

| Name | Type |
| :------ | :------ |
| `accessList` | `any`[] |

#### Returns

[`AccessList`](../modules/akashaproject_awf_sdk._internal_.md#accesslist)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:22

___

### address

▸ **address**(`value`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:29

___

### bigNumber

▸ **bigNumber**(`value`): [`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:25

___

### block

▸ **block**(`value`): [`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:37

___

### blockTag

▸ **blockTag**(`blockTag`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag` | `any` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:32

___

### blockWithTransactions

▸ **blockWithTransactions**(`value`): [`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:38

___

### boolean

▸ **boolean**(`value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:26

___

### callAddress

▸ **callAddress**(`value`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:30

___

### contractAddress

▸ **contractAddress**(`value`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:31

___

### data

▸ **data**(`value`, `strict?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `strict?` | `boolean` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:28

___

### difficulty

▸ **difficulty**(`value`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:34

___

### filter

▸ **filter**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:45

___

### filterLog

▸ **filterLog**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:46

___

### getDefaultFormats

▸ **getDefaultFormats**(): [`Formats`](../modules/akashaproject_awf_sdk._internal_.md#formats)

#### Returns

[`Formats`](../modules/akashaproject_awf_sdk._internal_.md#formats)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:21

___

### hash

▸ **hash**(`value`, `strict?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `strict?` | `boolean` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:33

___

### hex

▸ **hex**(`value`, `strict?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `strict?` | `boolean` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:27

___

### number

▸ **number**(`number`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `any` |

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:23

___

### receipt

▸ **receipt**(`value`): [`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:43

___

### receiptLog

▸ **receiptLog**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:42

___

### topics

▸ **topics**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:44

___

### transaction

▸ **transaction**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:41

___

### transactionRequest

▸ **transactionRequest**(`value`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:39

___

### transactionResponse

▸ **transactionResponse**(`transaction`): [`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | `any` |

#### Returns

[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:40

___

### type

▸ **type**(`number`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `number` | `any` |

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:24

___

### uint256

▸ **uint256**(`value`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:35

___

### allowFalsish

▸ `Static` **allowFalsish**(`format`, `replaceValue`): [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc) |
| `replaceValue` | `any` |

#### Returns

[`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:51

___

### allowNull

▸ `Static` **allowNull**(`format`, `nullValue?`): [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc) |
| `nullValue?` | `any` |

#### Returns

[`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:50

___

### arrayOf

▸ `Static` **arrayOf**(`format`): [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | [`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc) |

#### Returns

[`FormatFunc`](../modules/akashaproject_awf_sdk._internal_.md#formatfunc)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:52

___

### check

▸ `Static` **check**(`format`, `object`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | `Object` |
| `object` | `any` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/formatter.d.ts:47
