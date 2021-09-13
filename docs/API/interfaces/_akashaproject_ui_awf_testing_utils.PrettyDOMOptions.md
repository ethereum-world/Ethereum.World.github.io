[AWF](../README.md) / [Exports](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/_akashaproject_ui_awf_testing_utils.md) / PrettyDOMOptions

# Interface: PrettyDOMOptions

[@akashaproject/ui-awf-testing-utils](../modules/_akashaproject_ui_awf_testing_utils.md).PrettyDOMOptions

## Hierarchy

- [`OptionsReceived`](../modules/_akashaproject_ui_awf_testing_utils.prettyFormat.md#optionsreceived)

  ↳ **`PrettyDOMOptions`**

## Table of contents

### Properties

- [callToJSON](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#calltojson)
- [escapeRegex](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#escaperegex)
- [escapeString](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#escapestring)
- [highlight](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#highlight)
- [indent](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#indent)
- [maxDepth](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#maxdepth)
- [min](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#min)
- [plugins](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#plugins)
- [printBasicPrototype](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#printbasicprototype)
- [printFunctionName](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#printfunctionname)
- [theme](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#theme)

### Methods

- [filterNode](_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md#filternode)

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

• `Optional` **plugins**: [`Plugins`](../modules/_akashaproject_ui_awf_testing_utils.prettyFormat.md#plugins)

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

• `Optional` **theme**: `ThemeReceived`

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
| `node` | `Node` |

#### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/pretty-dom.d.ts:8
