[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / ReactOptions

# Interface: ReactOptions

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).ReactOptions

## Table of contents

### Properties

- [bindI18n](akashaproject_ui_awf_typings._internal_.ReactOptions.md#bindi18n)
- [bindI18nStore](akashaproject_ui_awf_typings._internal_.ReactOptions.md#bindi18nstore)
- [defaultTransParent](akashaproject_ui_awf_typings._internal_.ReactOptions.md#defaulttransparent)
- [nsMode](akashaproject_ui_awf_typings._internal_.ReactOptions.md#nsmode)
- [transEmptyNodeValue](akashaproject_ui_awf_typings._internal_.ReactOptions.md#transemptynodevalue)
- [transKeepBasicHtmlNodesFor](akashaproject_ui_awf_typings._internal_.ReactOptions.md#transkeepbasichtmlnodesfor)
- [transSupportBasicHtmlNodes](akashaproject_ui_awf_typings._internal_.ReactOptions.md#transsupportbasichtmlnodes)
- [transWrapTextNodes](akashaproject_ui_awf_typings._internal_.ReactOptions.md#transwraptextnodes)
- [useSuspense](akashaproject_ui_awf_typings._internal_.ReactOptions.md#usesuspense)
- [wait](akashaproject_ui_awf_typings._internal_.ReactOptions.md#wait)

### Methods

- [hashTransKey](akashaproject_ui_awf_typings._internal_.ReactOptions.md#hashtranskey)

## Properties

### bindI18n

• `Optional` **bindI18n**: `string` \| ``false``

Set which events trigger a re-render, can be set to false or string of events

**`default`** 'languageChanged'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:147

___

### bindI18nStore

• `Optional` **bindI18nStore**: `string` \| ``false``

Set which events on store trigger a re-render, can be set to false or string of events

**`default`** ''

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:152

___

### defaultTransParent

• `Optional` **defaultTransParent**: `string`

Set it to the default parent element created by the Trans component.

**`default`** 'div'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:142

___

### nsMode

• `Optional` **nsMode**: ``"fallback"`` \| ``"default"``

Set it to fallback to let passed namespaces to translated hoc act as fallbacks

**`default`** 'default'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:137

___

### transEmptyNodeValue

• `Optional` **transEmptyNodeValue**: `string`

Set fallback value for Trans components without children

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:157

___

### transKeepBasicHtmlNodesFor

• `Optional` **transKeepBasicHtmlNodesFor**: readonly `string`[]

Which nodes not to convert in defaultValue generation in the Trans component.

**`default`** ['br', 'strong', 'i', 'p']

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:181

___

### transSupportBasicHtmlNodes

• `Optional` **transSupportBasicHtmlNodes**: `boolean`

Convert eg. <br/> found in translations to a react component of type br

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:176

___

### transWrapTextNodes

• `Optional` **transWrapTextNodes**: `string`

Wrap text nodes in a user-specified element.

**`default`** ''

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:186

___

### useSuspense

• `Optional` **useSuspense**: `boolean`

Set it to false if you do not want to use Suspense

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:162

___

### wait

• `Optional` **wait**: `boolean`

Set to true if you like to wait for loaded in every translated hoc

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:132

## Methods

### hashTransKey

▸ `Optional` **hashTransKey**(`defaultValue`): `any`

Function to generate an i18nKey from the defaultValue (or Trans children)
when no key is provided.
By default, the defaultValue (Trans text) itself is used as the key.
If you want to require keys for all translations, supply a function
that always throws an error.

**`default`** undefined

#### Parameters

| Name | Type |
| :------ | :------ |
| `defaultValue` | `any` |

#### Returns

`any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:171
