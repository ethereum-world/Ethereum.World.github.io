[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / LanguageDetectorAsyncModule

# Interface: LanguageDetectorAsyncModule

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).LanguageDetectorAsyncModule

Used to detect language in user land.
Can be provided as a singleton or as a prototype constructor (preferred for supporting multiple instances of i18next).
For singleton set property `type` to `'languageDetector'` For a prototype constructor set static property.

## Hierarchy

- [`Module`](akashaproject_ui_awf_typings._internal_.Module.md)

  ↳ **`LanguageDetectorAsyncModule`**

## Table of contents

### Properties

- [async](akashaproject_ui_awf_typings._internal_.LanguageDetectorAsyncModule.md#async)
- [type](akashaproject_ui_awf_typings._internal_.LanguageDetectorAsyncModule.md#type)

### Methods

- [cacheUserLanguage](akashaproject_ui_awf_typings._internal_.LanguageDetectorAsyncModule.md#cacheuserlanguage)
- [detect](akashaproject_ui_awf_typings._internal_.LanguageDetectorAsyncModule.md#detect)
- [init](akashaproject_ui_awf_typings._internal_.LanguageDetectorAsyncModule.md#init)

## Properties

### async

• **async**: ``true``

Set to true to enable async detection

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:842

___

### type

• **type**: ``"languageDetector"``

#### Overrides

[Module](akashaproject_ui_awf_typings._internal_.Module.md).[type](akashaproject_ui_awf_typings._internal_.Module.md#type)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:840

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

ui/typings/node_modules/i18next/index.d.ts:846

___

### detect

▸ **detect**(`callback`): `void`

Must call callback passing detected language

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`lng`: `string` \| readonly `string`[]) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:845

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

ui/typings/node_modules/i18next/index.d.ts:843
