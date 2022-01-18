[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / GraphQLError

# Class: GraphQLError

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).GraphQLError

A GraphQLError describes an Error found during the parse, validate, or
execute phases of performing a GraphQL operation. In addition to a message
and stack trace, it also includes information about the locations in a
GraphQL document and/or execution result that correspond to the Error.

## Hierarchy

- [`Error`](../modules/akashaproject_awf_sdk._internal_.md#error)

  ↳ **`GraphQLError`**

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.GraphQLError.md#constructor)

### Properties

- [extensions](akashaproject_awf_sdk._internal_.GraphQLError.md#extensions)
- [locations](akashaproject_awf_sdk._internal_.GraphQLError.md#locations)
- [message](akashaproject_awf_sdk._internal_.GraphQLError.md#message)
- [name](akashaproject_awf_sdk._internal_.GraphQLError.md#name)
- [nodes](akashaproject_awf_sdk._internal_.GraphQLError.md#nodes)
- [originalError](akashaproject_awf_sdk._internal_.GraphQLError.md#originalerror)
- [path](akashaproject_awf_sdk._internal_.GraphQLError.md#path)
- [positions](akashaproject_awf_sdk._internal_.GraphQLError.md#positions)
- [source](akashaproject_awf_sdk._internal_.GraphQLError.md#source)
- [stack](akashaproject_awf_sdk._internal_.GraphQLError.md#stack)
- [prepareStackTrace](akashaproject_awf_sdk._internal_.GraphQLError.md#preparestacktrace)
- [stackTraceLimit](akashaproject_awf_sdk._internal_.GraphQLError.md#stacktracelimit)

### Methods

- [captureStackTrace](akashaproject_awf_sdk._internal_.GraphQLError.md#capturestacktrace)

## Constructors

### constructor

• **new GraphQLError**(`message`, `nodes?`, `source?`, `positions?`, `path?`, `originalError?`, `extensions?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `nodes?` | [`ASTNode`](../modules/akashaproject_awf_sdk._internal_.md#astnode) \| readonly [`ASTNode`](../modules/akashaproject_awf_sdk._internal_.md#astnode)[] |
| `source?` | [`Source`](akashaproject_awf_sdk._internal_.Source.md) |
| `positions?` | readonly `number`[] |
| `path?` | readonly (`string` \| `number`)[] |
| `originalError?` | [`Error`](../modules/akashaproject_awf_sdk._internal_.md#error) |
| `extensions?` | [`GraphQLErrorExtensions`](../interfaces/akashaproject_awf_sdk._internal_.GraphQLErrorExtensions.md) |

#### Overrides

Error.constructor

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:27

## Properties

### extensions

• `Readonly` **extensions**: `Object`

Extension fields to add to the formatted error.

#### Index signature

▪ [key: `string`]: `any`

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:84

___

### locations

• `Readonly` **locations**: readonly [`SourceLocation`](../interfaces/akashaproject_awf_sdk._internal_.SourceLocation.md)[]

An array of { line, column } locations within the source GraphQL document
which correspond to this error.

Errors during validation often contain multiple locations, for example to
point out two things with the same name. Errors during execution include a
single location, the field which produced the error.

Enumerable, and appears in the result of JSON.stringify().

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:47

___

### message

• **message**: `string`

#### Inherited from

Error.message

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:974

___

### name

• **name**: `string`

#### Inherited from

Error.name

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:973

___

### nodes

• `Readonly` **nodes**: readonly [`ASTNode`](../modules/akashaproject_awf_sdk._internal_.md#astnode)[]

An array of GraphQL AST Nodes corresponding to this error.

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:60

___

### originalError

• `Readonly` **originalError**: [`Error`](../modules/akashaproject_awf_sdk._internal_.md#error)

The original error thrown from a field resolver during execution.

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:79

___

### path

• `Readonly` **path**: readonly (`string` \| `number`)[]

An array describing the JSON-path into the execution response which
corresponds to this error. Only included for errors during execution.

Enumerable, and appears in the result of JSON.stringify().

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:55

___

### positions

• `Readonly` **positions**: readonly `number`[]

An array of character offsets within the source GraphQL document
which correspond to this error.

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:74

___

### source

• `Readonly` **source**: [`Source`](akashaproject_awf_sdk._internal_.Source.md)

The source GraphQL document corresponding to this error.

Note that if this Error represents more than one node, the source may not
represent nodes after the first node.

#### Defined in

sdk/node_modules/graphql/error/GraphQLError.d.ts:68

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

Error.stack

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:975

___

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: [`Error`](../modules/akashaproject_awf_sdk._internal_.md#error), `stackTraces`: [`CallSite`](../interfaces/akashaproject_awf_sdk._internal_.CallSite.md)[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`see`** https://v8.dev/docs/stack-trace-api#customizing-stack-traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | [`Error`](../modules/akashaproject_awf_sdk._internal_.md#error) |
| `stackTraces` | [`CallSite`](../interfaces/akashaproject_awf_sdk._internal_.CallSite.md)[] |

##### Returns

`any`

#### Inherited from

Error.prepareStackTrace

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

Error.stackTraceLimit

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:13

## Methods

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

Error.captureStackTrace

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:4
