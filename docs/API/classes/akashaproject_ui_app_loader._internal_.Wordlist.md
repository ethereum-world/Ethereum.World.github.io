[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Wordlist

# Class: Wordlist

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Wordlist

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Wordlist.md#constructor)

### Properties

- [locale](akashaproject_ui_app_loader._internal_.Wordlist.md#locale)

### Methods

- [getWord](akashaproject_ui_app_loader._internal_.Wordlist.md#getword)
- [getWordIndex](akashaproject_ui_app_loader._internal_.Wordlist.md#getwordindex)
- [join](akashaproject_ui_app_loader._internal_.Wordlist.md#join)
- [split](akashaproject_ui_app_loader._internal_.Wordlist.md#split)
- [check](akashaproject_ui_app_loader._internal_.Wordlist.md#check)
- [register](akashaproject_ui_app_loader._internal_.Wordlist.md#register)

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
| `wordlist` | [`Wordlist`](akashaproject_ui_app_loader._internal_.Wordlist.md) |

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
| `lang` | [`Wordlist`](akashaproject_ui_app_loader._internal_.Wordlist.md) |
| `name?` | `string` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/wordlists/lib/wordlist.d.ts:11
