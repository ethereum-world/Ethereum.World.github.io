[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Source

# Class: Source

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Source

A representation of source input to GraphQL. The `name` and `locationOffset` parameters are
optional, but they are useful for clients who store GraphQL documents in source files.
For example, if the GraphQL input starts at line 40 in a file named `Foo.graphql`, it might
be useful for `name` to be `"Foo.graphql"` and location to be `{ line: 40, column: 1 }`.
The `line` and `column` properties in `locationOffset` are 1-indexed.

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.Source.md#constructor)

### Properties

- [body](akashaproject_ui_app_loader._internal_.Source.md#body)
- [locationOffset](akashaproject_ui_app_loader._internal_.Source.md#locationoffset)
- [name](akashaproject_ui_app_loader._internal_.Source.md#name)

## Constructors

### constructor

• **new Source**(`body`, `name?`, `locationOffset?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `body` | `string` |
| `name?` | `string` |
| `locationOffset?` | [`Location`](../interfaces/akashaproject_ui_app_loader._internal_.Location-2.md) |

#### Defined in

sdk/node_modules/graphql/language/source.d.ts:17

## Properties

### body

• **body**: `string`

#### Defined in

sdk/node_modules/graphql/language/source.d.ts:14

___

### locationOffset

• **locationOffset**: [`Location`](../interfaces/akashaproject_ui_app_loader._internal_.Location-2.md)

#### Defined in

sdk/node_modules/graphql/language/source.d.ts:16

___

### name

• **name**: `string`

#### Defined in

sdk/node_modules/graphql/language/source.d.ts:15
