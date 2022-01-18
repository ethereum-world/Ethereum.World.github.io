[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Location

# Class: Location

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Location

Contains a range of UTF-8 character offsets and token references that
identify the region of the source from which the AST derived.

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Location.md#constructor)

### Properties

- [end](akashaproject_awf_sdk._internal_.Location.md#end)
- [endToken](akashaproject_awf_sdk._internal_.Location.md#endtoken)
- [source](akashaproject_awf_sdk._internal_.Location.md#source)
- [start](akashaproject_awf_sdk._internal_.Location.md#start)
- [startToken](akashaproject_awf_sdk._internal_.Location.md#starttoken)

### Methods

- [toJSON](akashaproject_awf_sdk._internal_.Location.md#tojson)

## Constructors

### constructor

• **new Location**(`startToken`, `endToken`, `source`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `startToken` | [`Token`](akashaproject_awf_sdk._internal_.Token.md) |
| `endToken` | [`Token`](akashaproject_awf_sdk._internal_.Token.md) |
| `source` | [`Source`](akashaproject_awf_sdk._internal_.Source.md) |

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:34

## Properties

### end

• `Readonly` **end**: `number`

The character offset at which this Node ends.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:17

___

### endToken

• `Readonly` **endToken**: [`Token`](akashaproject_awf_sdk._internal_.Token.md)

The Token at which this Node ends.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:27

___

### source

• `Readonly` **source**: [`Source`](akashaproject_awf_sdk._internal_.Source.md)

The Source document the AST represents.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:32

___

### start

• `Readonly` **start**: `number`

The character offset at which this Node begins.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:12

___

### startToken

• `Readonly` **startToken**: [`Token`](akashaproject_awf_sdk._internal_.Token.md)

The Token at which this Node begins.

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:22

## Methods

### toJSON

▸ **toJSON**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `end` | `number` |
| `start` | `number` |

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:36
