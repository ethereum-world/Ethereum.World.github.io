[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](akashaproject_ui_awf_testing_utils.md) / prettyFormat

# Namespace: prettyFormat

[@akashaproject/ui-awf-testing-utils](akashaproject_ui_awf_testing_utils.md).prettyFormat

## Table of contents

### References

- [default](akashaproject_ui_awf_testing_utils.prettyFormat.md#default)

### Type aliases

- [Colors](akashaproject_ui_awf_testing_utils.prettyFormat.md#colors)
- [Config](akashaproject_ui_awf_testing_utils.prettyFormat.md#config)
- [NewPlugin](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin)
- [OldPlugin](akashaproject_ui_awf_testing_utils.prettyFormat.md#oldplugin)
- [Options](akashaproject_ui_awf_testing_utils.prettyFormat.md#options)
- [OptionsReceived](akashaproject_ui_awf_testing_utils.prettyFormat.md#optionsreceived)
- [Plugin](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugin)
- [Plugins](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)
- [Printer](akashaproject_ui_awf_testing_utils.prettyFormat.md#printer)
- [Refs](akashaproject_ui_awf_testing_utils.prettyFormat.md#refs)
- [Theme](akashaproject_ui_awf_testing_utils.prettyFormat.md#theme)

### Variables

- [DEFAULT\_OPTIONS](akashaproject_ui_awf_testing_utils.prettyFormat.md#default_options)
- [plugins](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)

### Functions

- [format](akashaproject_ui_awf_testing_utils.prettyFormat.md#format)

## References

### default

Renames and re-exports [format](akashaproject_ui_awf_testing_utils.prettyFormat.md#format)

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
| `colors` | [`Colors`](akashaproject_ui_awf_testing_utils.prettyFormat.md#colors) |
| `escapeRegex` | `boolean` |
| `escapeString` | `boolean` |
| `indent` | `string` |
| `maxDepth` | `number` |
| `min` | `boolean` |
| `plugins` | [`Plugins`](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins) |
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
| `test` | [`Test`](akashaproject_ui_awf_testing_utils._internal_.md#test) |
| `serialize` | (`val`: `any`, `config`: [`Config`](akashaproject_ui_awf_testing_utils.prettyFormat.md#config), `indentation`: `string`, `depth`: `number`, `refs`: [`Refs`](akashaproject_ui_awf_testing_utils.prettyFormat.md#refs), `printer`: [`Printer`](akashaproject_ui_awf_testing_utils.prettyFormat.md#printer)) => `string` |

#### Defined in

node_modules/pretty-format/build/types.d.ts:89

___

### OldPlugin

Ƭ **OldPlugin**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `test` | [`Test`](akashaproject_ui_awf_testing_utils._internal_.md#test) |
| `print` | (`val`: `unknown`, `print`: [`Print`](akashaproject_ui_awf_testing_utils._internal_.md#print), `indent`: [`Indent`](akashaproject_ui_awf_testing_utils._internal_.md#indent), `options`: [`PluginOptions`](akashaproject_ui_awf_testing_utils._internal_.md#pluginoptions), `colors`: [`Colors`](akashaproject_ui_awf_testing_utils.prettyFormat.md#colors)) => `string` |

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
| `plugins` | [`Plugins`](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins) |
| `printBasicPrototype` | `boolean` |
| `printFunctionName` | `boolean` |
| `theme` | [`Theme`](akashaproject_ui_awf_testing_utils.prettyFormat.md#theme) |

#### Defined in

node_modules/pretty-format/build/types.d.ts:46

___

### OptionsReceived

Ƭ **OptionsReceived**: [`PrettyFormatOptions`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.PrettyFormatOptions.md)

#### Defined in

node_modules/pretty-format/build/types.d.ts:72

___

### Plugin

Ƭ **Plugin**: [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) \| [`OldPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#oldplugin)

#### Defined in

node_modules/pretty-format/build/types.d.ts:102

___

### Plugins

Ƭ **Plugins**: [`Plugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#plugin)[]

#### Defined in

node_modules/pretty-format/build/types.d.ts:103

___

### Printer

Ƭ **Printer**: (`val`: `unknown`, `config`: [`Config`](akashaproject_ui_awf_testing_utils.prettyFormat.md#config), `indentation`: `string`, `depth`: `number`, `refs`: [`Refs`](akashaproject_ui_awf_testing_utils.prettyFormat.md#refs), `hasCalledToJSON?`: `boolean`) => `string`

#### Type declaration

▸ (`val`, `config`, `indentation`, `depth`, `refs`, `hasCalledToJSON?`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `unknown` |
| `config` | [`Config`](akashaproject_ui_awf_testing_utils.prettyFormat.md#config) |
| `indentation` | `string` |
| `depth` | `number` |
| `refs` | [`Refs`](akashaproject_ui_awf_testing_utils.prettyFormat.md#refs) |
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

• **DEFAULT\_OPTIONS**: [`Options`](akashaproject_ui_awf_testing_utils.prettyFormat.md#options)

#### Defined in

node_modules/pretty-format/build/index.d.ts:9

___

### plugins

• **plugins**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AsymmetricMatcher` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ConvertAnsi` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `DOMCollection` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `DOMElement` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `Immutable` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ReactElement` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |
| `ReactTestComponent` | [`NewPlugin`](akashaproject_ui_awf_testing_utils.prettyFormat.md#newplugin) |

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
| `options?` | [`PrettyFormatOptions`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.PrettyFormatOptions.md) | Custom settings |

#### Returns

`string`

#### Defined in

node_modules/pretty-format/build/index.d.ts:15
