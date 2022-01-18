[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / PrettyDOMOptions

# Interface: PrettyDOMOptions

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).PrettyDOMOptions

## Hierarchy

- [`OptionsReceived`](../modules/akashaproject_ui_awf_testing_utils.prettyFormat.md#optionsreceived)

  ↳ **`PrettyDOMOptions`**

## Table of contents

### Properties

- [callToJSON](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#calltojson)
- [escapeRegex](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#escaperegex)
- [escapeString](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#escapestring)
- [highlight](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#highlight)
- [indent](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#indent)
- [maxDepth](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#maxdepth)
- [min](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#min)
- [plugins](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#plugins)
- [printBasicPrototype](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#printbasicprototype)
- [printFunctionName](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#printfunctionname)
- [theme](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#theme)

### Methods

- [filterNode](akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#filternode)

## Properties

### callToJSON

• `Optional` **callToJSON**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.callToJSON

#### Defined in

node_modules/pretty-format/build/types.d.ts:60

___

### escapeRegex

• `Optional` **escapeRegex**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.escapeRegex

#### Defined in

node_modules/pretty-format/build/types.d.ts:61

___

### escapeString

• `Optional` **escapeString**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.escapeString

#### Defined in

node_modules/pretty-format/build/types.d.ts:62

___

### highlight

• `Optional` **highlight**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.highlight

#### Defined in

node_modules/pretty-format/build/types.d.ts:63

___

### indent

• `Optional` **indent**: `number`

#### Inherited from

prettyFormat.OptionsReceived.indent

#### Defined in

node_modules/pretty-format/build/types.d.ts:64

___

### maxDepth

• `Optional` **maxDepth**: `number`

#### Inherited from

prettyFormat.OptionsReceived.maxDepth

#### Defined in

node_modules/pretty-format/build/types.d.ts:65

___

### min

• `Optional` **min**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.min

#### Defined in

node_modules/pretty-format/build/types.d.ts:66

___

### plugins

• `Optional` **plugins**: [`Plugins`](../modules/akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)

#### Inherited from

prettyFormat.OptionsReceived.plugins

#### Defined in

node_modules/pretty-format/build/types.d.ts:67

___

### printBasicPrototype

• `Optional` **printBasicPrototype**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.printBasicPrototype

#### Defined in

node_modules/pretty-format/build/types.d.ts:68

___

### printFunctionName

• `Optional` **printFunctionName**: `boolean`

#### Inherited from

prettyFormat.OptionsReceived.printFunctionName

#### Defined in

node_modules/pretty-format/build/types.d.ts:69

___

### theme

• `Optional` **theme**: [`ThemeReceived`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#themereceived)

#### Inherited from

prettyFormat.OptionsReceived.theme

#### Defined in

node_modules/pretty-format/build/types.d.ts:70

## Methods

### filterNode

▸ `Optional` **filterNode**(`node`): `boolean`

Given a `Node` return `false` if you wish to ignore that node in the output.
By default, ignores `<style />`, `<script />` and comment nodes.

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/pretty-dom.d.ts:8
