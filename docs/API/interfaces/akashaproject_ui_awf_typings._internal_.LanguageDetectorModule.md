[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / LanguageDetectorModule

# Interface: LanguageDetectorModule

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).LanguageDetectorModule

Used to detect language in user land.
Can be provided as a singleton or as a prototype constructor (preferred for supporting multiple instances of i18next).
For singleton set property `type` to `'languageDetector'` For a prototype constructor set static property.

## Hierarchy

- [`Module`](akashaproject_ui_awf_typings._internal_.Module.md)

  ↳ **`LanguageDetectorModule`**

## Table of contents

### Properties

- [type](akashaproject_ui_awf_typings._internal_.LanguageDetectorModule.md#type)

### Methods

- [cacheUserLanguage](akashaproject_ui_awf_typings._internal_.LanguageDetectorModule.md#cacheuserlanguage)
- [detect](akashaproject_ui_awf_typings._internal_.LanguageDetectorModule.md#detect)
- [init](akashaproject_ui_awf_typings._internal_.LanguageDetectorModule.md#init)

## Properties

### type

• **type**: ``"languageDetector"``

#### Overrides

[Module](akashaproject_ui_awf_typings._internal_.Module.md).[type](akashaproject_ui_awf_typings._internal_.Module.md#type)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:827

## Methods

### cacheUserLanguage

▸ **cacheUserLanguage**(`lng`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:831

___

### detect

▸ **detect**(): `string` \| readonly `string`[]

Must return detected language

#### Returns

`string` \| readonly `string`[]

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:830

___

### init

▸ **init**(`services`, `detectorOptions`, `i18nextOptions`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `services` | [`Services`](akashaproject_ui_awf_typings._internal_.Services.md) |
| `detectorOptions` | `object` |
| `i18nextOptions` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:828
