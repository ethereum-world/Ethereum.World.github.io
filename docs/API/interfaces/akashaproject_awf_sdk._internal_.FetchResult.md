[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / FetchResult

# Interface: FetchResult<TData, TContext, TExtensions\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).FetchResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |
| `TContext` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |
| `TExtensions` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |

## Hierarchy

- [`ExecutionResult`](akashaproject_awf_sdk._internal_.ExecutionResult.md)<`TData`, `TExtensions`\>

  ↳ **`FetchResult`**

## Table of contents

### Properties

- [context](akashaproject_awf_sdk._internal_.FetchResult.md#context)
- [data](akashaproject_awf_sdk._internal_.FetchResult.md#data)
- [errors](akashaproject_awf_sdk._internal_.FetchResult.md#errors)
- [extensions](akashaproject_awf_sdk._internal_.FetchResult.md#extensions)

## Properties

### context

• `Optional` **context**: `TContext`

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:22

___

### data

• `Optional` **data**: `TData`

#### Overrides

[ExecutionResult](akashaproject_awf_sdk._internal_.ExecutionResult.md).[data](akashaproject_awf_sdk._internal_.ExecutionResult.md#data)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:20

___

### errors

• `Optional` **errors**: readonly [`GraphQLError`](../classes/akashaproject_awf_sdk._internal_.GraphQLError.md)[]

#### Inherited from

[ExecutionResult](akashaproject_awf_sdk._internal_.ExecutionResult.md).[errors](akashaproject_awf_sdk._internal_.ExecutionResult.md#errors)

#### Defined in

sdk/node_modules/graphql/execution/execute.d.ts:53

___

### extensions

• `Optional` **extensions**: `TExtensions`

#### Overrides

[ExecutionResult](akashaproject_awf_sdk._internal_.ExecutionResult.md).[extensions](akashaproject_awf_sdk._internal_.ExecutionResult.md#extensions)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:21
