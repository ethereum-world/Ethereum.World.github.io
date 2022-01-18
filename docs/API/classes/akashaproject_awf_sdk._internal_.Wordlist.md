[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Wordlist

# Class: Wordlist

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Wordlist

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Wordlist.md#constructor)

### Properties

- [locale](akashaproject_awf_sdk._internal_.Wordlist.md#locale)

### Methods

- [getWord](akashaproject_awf_sdk._internal_.Wordlist.md#getword)
- [getWordIndex](akashaproject_awf_sdk._internal_.Wordlist.md#getwordindex)
- [join](akashaproject_awf_sdk._internal_.Wordlist.md#join)
- [split](akashaproject_awf_sdk._internal_.Wordlist.md#split)
- [check](akashaproject_awf_sdk._internal_.Wordlist.md#check)
- [register](akashaproject_awf_sdk._internal_.Wordlist.md#register)

## Constructors

### constructor

• **new Wordlist**(`locale`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `locale` | `string` |

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:5

## Properties

### locale

• `Readonly` **locale**: `string`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:4

## Methods

### getWord

▸ `Abstract` **getWord**(`index`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:6

___

### getWordIndex

▸ `Abstract` **getWordIndex**(`word`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `word` | `string` |

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:7

___

### join

▸ **join**(`words`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `words` | `string`[] |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:9

___

### split

▸ **split**(`mnemonic`): `string`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `mnemonic` | `string` |

#### Returns

`string`[]

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:8

___

### check

▸ `Static` **check**(`wordlist`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `wordlist` | [`Wordlist`](akashaproject_awf_sdk._internal_.Wordlist.md) |

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:10

___

### register

▸ `Static` **register**(`lang`, `name?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lang` | [`Wordlist`](akashaproject_awf_sdk._internal_.Wordlist.md) |
| `name?` | `string` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:11
