[AWF](../README.md) / [Exports](../modules.md) / [@akashaproject/ui-awf-testing-utils](_akashaproject_ui_awf_testing_utils.md) / prettyFormat

# Namespace: prettyFormat

[@akashaproject/ui-awf-testing-utils](_akashaproject_ui_awf_testing_utils.md).prettyFormat

## Table of contents

### References

- [default](_akashaproject_ui_awf_testing_utils.prettyFormat.md#default)

### Type aliases

- [Colors](_akashaproject_ui_awf_testing_utils.prettyFormat.md#colors)
- [Config](_akashaproject_ui_awf_testing_utils.prettyFormat.md#config)
- [NewPlugin](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin)
- [OldPlugin](_akashaproject_ui_awf_testing_utils.prettyFormat.md#oldplugin)
- [Options](_akashaproject_ui_awf_testing_utils.prettyFormat.md#options)
- [OptionsReceived](_akashaproject_ui_awf_testing_utils.prettyFormat.md#optionsreceived)
- [Plugin](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugin)
- [Plugins](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)
- [Printer](_akashaproject_ui_awf_testing_utils.prettyFormat.md#printer)
- [Refs](_akashaproject_ui_awf_testing_utils.prettyFormat.md#refs)
- [Theme](_akashaproject_ui_awf_testing_utils.prettyFormat.md#theme)

### Variables

- [DEFAULT\_OPTIONS](_akashaproject_ui_awf_testing_utils.prettyFormat.md#default_options)
- [plugins](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)

### Functions

- [format](_akashaproject_ui_awf_testing_utils.prettyFormat.md#format)

## References

### default

Renames and exports: [format](_akashaproject_ui_awf_testing_utils.prettyFormat.md#format)

## Type aliases

### Colors

Ƭ **Colors**: `Object`

Copyright (c) Facebook, Inc. and its affiliates. All Rights Reserved.

This source code is licensed under the MIT license found in the
LICENSE file in the root directory of this source tree.

#### Type declaration

| Name | Type |
| :------ | :------ |
| `comment` | `Object` |
| `comment.close` | `string` |
| `comment.open` | `string` |
| `content` | `Object` |
| `content.close` | `string` |
| `content.open` | `string` |
| `prop` | `Object` |
| `prop.close` | `string` |
| `prop.open` | `string` |
| `tag` | `Object` |
| `tag.close` | `string` |
| `tag.open` | `string` |
| `value` | `Object` |
| `value.close` | `string` |
| `value.open` | `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:7

___

### Config

Ƭ **Config**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `callToJSON` | `boolean` |
| `colors` | [`Colors`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#colors) |
| `escapeRegex` | `boolean` |
| `escapeString` | `boolean` |
| `indent` | `string` |
| `maxDepth` | `number` |
| `min` | `boolean` |
| `plugins` | [`Plugins`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins) |
| `printBasicPrototype` | `boolean` |
| `printFunctionName` | `boolean` |
| `spacingInner` | `string` |
| `spacingOuter` | `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:73

___

### NewPlugin

Ƭ **NewPlugin**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `test` | `Test` |
| `serialize` | (`val`: `any`, `config`: [`Config`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#config), `indentation`: `string`, `depth`: `number`, `refs`: [`Refs`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#refs), `printer`: [`Printer`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#printer)) => `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:89

___

### OldPlugin

Ƭ **OldPlugin**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `test` | `Test` |
| `print` | (`val`: `unknown`, `print`: `Print`, `indent`: `Indent`, `options`: `PluginOptions`, `colors`: [`Colors`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#colors)) => `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:98

___

### Options

Ƭ **Options**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `callToJSON` | `boolean` |
| `escapeRegex` | `boolean` |
| `escapeString` | `boolean` |
| `highlight` | `boolean` |
| `indent` | `number` |
| `maxDepth` | `number` |
| `min` | `boolean` |
| `plugins` | [`Plugins`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins) |
| `printBasicPrototype` | `boolean` |
| `printFunctionName` | `boolean` |
| `theme` | [`Theme`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#theme) |

#### Defined in

node_modules/pretty-format/build/types.d.ts:46

___

### OptionsReceived

Ƭ **OptionsReceived**: `PrettyFormatOptions`

#### Defined in

node_modules/pretty-format/build/types.d.ts:72

___

### Plugin

Ƭ **Plugin**: [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) \| [`OldPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#oldplugin)

#### Defined in

node_modules/pretty-format/build/types.d.ts:102

___

### Plugins

Ƭ **Plugins**: [`Plugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugin)[]

#### Defined in

node_modules/pretty-format/build/types.d.ts:103

___

### Printer

Ƭ **Printer**: (`val`: `unknown`, `config`: [`Config`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#config), `indentation`: `string`, `depth`: `number`, `refs`: [`Refs`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#refs), `hasCalledToJSON?`: `boolean`) => `string`

#### Type declaration

▸ (`val`, `config`, `indentation`, `depth`, `refs`, `hasCalledToJSON?`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `unknown` |
| `config` | [`Config`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#config) |
| `indentation` | `string` |
| `depth` | `number` |
| `refs` | [`Refs`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#refs) |
| `hasCalledToJSON?` | `boolean` |

##### Returns

`string`

#### Defined in

node_modules/pretty-format/build/types.d.ts:87

___

### Refs

Ƭ **Refs**: `unknown`[]

#### Defined in

node_modules/pretty-format/build/types.d.ts:30

___

### Theme

Ƭ **Theme**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `comment` | `string` |
| `content` | `string` |
| `prop` | `string` |
| `tag` | `string` |
| `value` | `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:32

## Variables

### DEFAULT\_OPTIONS

• `Const` **DEFAULT\_OPTIONS**: [`Options`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#options)

#### Defined in

node_modules/pretty-format/build/index.d.ts:9

___

### plugins

• `Const` **plugins**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AsymmetricMatcher` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ConvertAnsi` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `DOMCollection` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `DOMElement` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `Immutable` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ReactElement` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ReactTestComponent` | [`NewPlugin`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |

#### Defined in

node_modules/pretty-format/build/index.d.ts:16

## Functions

### format

▸ **format**(`val`, `options?`): `string`

Returns a presentation string of your `val` object

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `val` | `unknown` | any potential JavaScript object |
| `options?` | [`OptionsReceived`](_akashaproject_ui_awf_testing_utils.prettyFormat.md#optionsreceived) | Custom settings |

#### Returns

`string`

#### Defined in

node_modules/pretty-format/build/index.d.ts:15
