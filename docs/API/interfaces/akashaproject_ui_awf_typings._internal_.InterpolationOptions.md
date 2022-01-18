[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / InterpolationOptions

# Interface: InterpolationOptions

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).InterpolationOptions

## Table of contents

### Properties

- [alwaysFormat](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#alwaysformat)
- [defaultVariables](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#defaultvariables)
- [escapeValue](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#escapevalue)
- [format](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#format)
- [formatSeparator](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#formatseparator)
- [maxReplaces](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#maxreplaces)
- [nestingOptionsSeparator](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#nestingoptionsseparator)
- [nestingPrefix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#nestingprefix)
- [nestingPrefixEscaped](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#nestingprefixescaped)
- [nestingSuffix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#nestingsuffix)
- [nestingSuffixEscaped](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#nestingsuffixescaped)
- [prefix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#prefix)
- [prefixEscaped](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#prefixescaped)
- [skipOnVariables](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#skiponvariables)
- [suffix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#suffix)
- [suffixEscaped](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#suffixescaped)
- [unescapePrefix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#unescapeprefix)
- [unescapeSuffix](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#unescapesuffix)
- [useRawValueToEscape](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#userawvaluetoescape)

### Methods

- [escape](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md#escape)

## Properties

### alwaysFormat

• `Optional` **alwaysFormat**: `boolean`

Always format interpolated values.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:42

___

### defaultVariables

• `Optional` **defaultVariables**: `Object`

Global variables to use in interpolation replacements

**`default`** undefined

#### Index signature

▪ [index: `string`]: `any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:113

___

### escapeValue

• `Optional` **escapeValue**: `boolean`

Escape passed in values to avoid xss injection

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:47

___

### format

• `Optional` **format**: [`FormatFunction`](../modules/akashaproject_ui_awf_typings._internal_.md#formatfunction)

Format function see formatting for details

**`default`** noop

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:26

___

### formatSeparator

• `Optional` **formatSeparator**: `string`

Used to separate format from interpolation value

**`default`** ','

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:31

___

### maxReplaces

• `Optional` **maxReplaces**: `number`

After how many interpolation runs to break out before throwing a stack overflow

**`default`** 1000

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:118

___

### nestingOptionsSeparator

• `Optional` **nestingOptionsSeparator**: `string`

Separates options from key

**`default`** ','

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:107

___

### nestingPrefix

• `Optional` **nestingPrefix**: `string`

Prefix for nesting

**`default`** '$t('

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:87

___

### nestingPrefixEscaped

• `Optional` **nestingPrefixEscaped**: `string`

Escaped prefix for nesting (regexSafe)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:97

___

### nestingSuffix

• `Optional` **nestingSuffix**: `string`

Suffix for nesting

**`default`** ')'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:92

___

### nestingSuffixEscaped

• `Optional` **nestingSuffixEscaped**: `string`

Escaped suffix for nesting (regexSafe)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:102

___

### prefix

• `Optional` **prefix**: `string`

Prefix for interpolation

**`default`** '{{'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:57

___

### prefixEscaped

• `Optional` **prefixEscaped**: `string`

Escaped prefix for interpolation (regexSafe)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:67

___

### skipOnVariables

• `Optional` **skipOnVariables**: `boolean`

If true, it will skip to interpolate the variables

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:124

___

### suffix

• `Optional` **suffix**: `string`

Suffix for interpolation

**`default`** '}}'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:62

___

### suffixEscaped

• `Optional` **suffixEscaped**: `string`

Escaped suffix for interpolation (regexSafe)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:72

___

### unescapePrefix

• `Optional` **unescapePrefix**: `string`

Prefix to unescaped mode

**`default`** '-'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:82

___

### unescapeSuffix

• `Optional` **unescapeSuffix**: `string`

Suffix to unescaped mode

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:77

___

### useRawValueToEscape

• `Optional` **useRawValueToEscape**: `boolean`

If true, then value passed into escape function is not casted to string, use with custom escape function that does its own type check

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:52

## Methods

### escape

▸ `Optional` **escape**(`str`): `string`

Escape function

**`default`** str => str

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`string`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:36
