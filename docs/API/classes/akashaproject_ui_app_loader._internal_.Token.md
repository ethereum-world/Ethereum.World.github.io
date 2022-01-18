[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Token

# Class: Token

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Token

Represents a range of characters represented by a lexical token
within a Source.

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Token.md#constructor)

### Properties

- [column](akashaproject_ui_app_loader._internal_.Token.md#column)
- [end](akashaproject_ui_app_loader._internal_.Token.md#end)
- [kind](akashaproject_ui_app_loader._internal_.Token.md#kind)
- [line](akashaproject_ui_app_loader._internal_.Token.md#line)
- [next](akashaproject_ui_app_loader._internal_.Token.md#next)
- [prev](akashaproject_ui_app_loader._internal_.Token.md#prev)
- [start](akashaproject_ui_app_loader._internal_.Token.md#start)
- [value](akashaproject_ui_app_loader._internal_.Token.md#value)

### Methods

- [toJSON](akashaproject_ui_app_loader._internal_.Token.md#tojson)

## Constructors

### constructor

• **new Token**(`kind`, `start`, `end`, `line`, `column`, `prev`, `value?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `kind` | [`TokenKindEnum`](../modules/akashaproject_ui_app_loader._internal_.md#tokenkindenum) |
| `start` | `number` |
| `end` | `number` |
| `line` | `number` |
| `column` | `number` |
| `prev` | [`Token`](akashaproject_ui_app_loader._internal_.Token.md) |
| `value?` | `string` |

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:82

## Properties

### column

• `Readonly` **column**: `number`

The 1-indexed column number at which this Token begins.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:67

___

### end

• `Readonly` **end**: `number`

The character offset at which this Node ends.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:57

___

### kind

• `Readonly` **kind**: [`TokenKindEnum`](../modules/akashaproject_ui_app_loader._internal_.md#tokenkindenum)

The kind of Token.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:47

___

### line

• `Readonly` **line**: `number`

The 1-indexed line number on which this Token appears.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:62

___

### next

• `Readonly` **next**: [`Token`](akashaproject_ui_app_loader._internal_.Token.md)

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:80

___

### prev

• `Readonly` **prev**: [`Token`](akashaproject_ui_app_loader._internal_.Token.md)

Tokens exist as nodes in a double-linked-list amongst all tokens
including ignored tokens. <SOF> is always the first node and <EOF>
the last.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:79

___

### start

• `Readonly` **start**: `number`

The character offset at which this Node begins.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:52

___

### value

• `Readonly` **value**: `string`

For non-punctuation tokens, represents the interpreted value of the token.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:72

## Methods

### toJSON

▸ **toJSON**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `column` | `number` |
| `kind` | [`TokenKindEnum`](../modules/akashaproject_ui_app_loader._internal_.md#tokenkindenum) |
| `line` | `number` |
| `value` | `string` |

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:92
