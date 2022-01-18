[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / CSSStyleSheet

# Interface: CSSStyleSheet

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).CSSStyleSheet

A single CSS style sheet. It inherits properties and methods from its parent, StyleSheet.

## Hierarchy

- [`StyleSheet`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#stylesheet)

  ↳ **`CSSStyleSheet`**

## Table of contents

### Properties

- [cssRules](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#cssrules)
- [disabled](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#disabled)
- [href](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#href)
- [media](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#media)
- [ownerNode](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#ownernode)
- [ownerRule](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#ownerrule)
- [parentStyleSheet](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#parentstylesheet)
- [rules](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#rules)
- [title](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#title)
- [type](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#type)

### Methods

- [addRule](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#addrule)
- [deleteRule](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#deleterule)
- [insertRule](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#insertrule)
- [removeRule](akashaproject_ui_awf_testing_utils._internal_.CSSStyleSheet.md#removerule)

## Properties

### cssRules

• `Readonly` **cssRules**: [`CSSRuleList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssrulelist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3223

___

### disabled

• **disabled**: `boolean`

#### Inherited from

StyleSheet.disabled

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14407

___

### href

• `Readonly` **href**: `string`

#### Inherited from

StyleSheet.href

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14408

___

### media

• `Readonly` **media**: [`MediaList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#medialist)

#### Inherited from

StyleSheet.media

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14409

___

### ownerNode

• `Readonly` **ownerNode**: `Element` \| [`ProcessingInstruction`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#processinginstruction)

#### Inherited from

StyleSheet.ownerNode

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14410

___

### ownerRule

• `Readonly` **ownerRule**: [`CSSRule`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssrule)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3224

___

### parentStyleSheet

• `Readonly` **parentStyleSheet**: [`CSSStyleSheet`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssstylesheet)

#### Inherited from

StyleSheet.parentStyleSheet

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14411

___

### rules

• `Readonly` **rules**: [`CSSRuleList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#cssrulelist)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3226

___

### title

• `Readonly` **title**: `string`

#### Inherited from

StyleSheet.title

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14412

___

### type

• `Readonly` **type**: `string`

#### Inherited from

StyleSheet.type

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14413

## Methods

### addRule

▸ **addRule**(`selector?`, `style?`, `index?`): `number`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `selector?` | `string` |
| `style?` | `string` |
| `index?` | `number` |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3228

___

### deleteRule

▸ **deleteRule**(`index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3229

___

### insertRule

▸ **insertRule**(`rule`, `index?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `rule` | `string` |
| `index?` | `number` |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3230

___

### removeRule

▸ **removeRule**(`index?`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `index?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3232
