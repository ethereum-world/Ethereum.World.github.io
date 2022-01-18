[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / TypedQueryDocumentNode

# Interface: TypedQueryDocumentNode<TResponseData, TRequestVariables\>

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).TypedQueryDocumentNode

Wrapper type that contains DocumentNode and types that can be deduced from it.

## Type parameters

| Name | Type |
| :------ | :------ |
| `TResponseData` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |
| `TRequestVariables` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |

## Hierarchy

- [`DocumentNode`](akashaproject_ui_app_loader._internal_.DocumentNode.md)

  ↳ **`TypedQueryDocumentNode`**

## Table of contents

### Properties

- [definitions](akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md#definitions)
- [kind](akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md#kind)
- [loc](akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md#loc)

### Methods

- [\_\_ensureTypesOfVariablesAndResultMatching](akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md#__ensuretypesofvariablesandresultmatching)

## Properties

### definitions

• `Readonly` **definitions**: readonly [`ExecutableDefinitionNode`](../modules/akashaproject_ui_app_loader._internal_.md#executabledefinitionnode)[]

#### Overrides

[DocumentNode](akashaproject_ui_app_loader._internal_.DocumentNode.md).[definitions](akashaproject_ui_app_loader._internal_.DocumentNode.md#definitions)

#### Defined in

sdk/node_modules/graphql/utilities/typedQueryDocumentNode.d.ts:10

___

### kind

• `Readonly` **kind**: ``"Document"``

#### Inherited from

[DocumentNode](akashaproject_ui_app_loader._internal_.DocumentNode.md).[kind](akashaproject_ui_app_loader._internal_.DocumentNode.md#kind)

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:213

___

### loc

• `Optional` `Readonly` **loc**: [`Location`](../classes/akashaproject_ui_app_loader._internal_.Location.md)

#### Inherited from

[DocumentNode](akashaproject_ui_app_loader._internal_.DocumentNode.md).[loc](akashaproject_ui_app_loader._internal_.DocumentNode.md#loc)

#### Defined in

sdk/node_modules/graphql/language/ast.d.ts:214

## Methods

### \_\_ensureTypesOfVariablesAndResultMatching

▸ `Optional` **__ensureTypesOfVariablesAndResultMatching**(`variables`): `TResponseData`

This type is used to ensure that the variables you pass in to the query are assignable to Variables
and that the Result is assignable to whatever you pass your result to. The method is never actually
implemented, but the type is valid because we list it as optional

#### Parameters

| Name | Type |
| :------ | :------ |
| `variables` | `TRequestVariables` |

#### Returns

`TResponseData`

#### Defined in

sdk/node_modules/graphql/utilities/typedQueryDocumentNode.d.ts:17
