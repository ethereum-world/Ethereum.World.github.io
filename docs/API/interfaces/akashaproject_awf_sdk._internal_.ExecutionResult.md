[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / ExecutionResult

# Interface: ExecutionResult<TData, TExtensions\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).ExecutionResult

The result of GraphQL execution.

  - `errors` is included when any errors occurred as a non-empty array.
  - `data` is the result of a successful execution of the query.
  - `extensions` is reserved for adding non-standard properties.

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | { [key: string]: `any`;  } |
| `TExtensions` | { [key: string]: `any`;  } |

## Hierarchy

- **`ExecutionResult`**

  ↳ [`FetchResult`](akashaproject_awf_sdk._internal_.FetchResult.md)

## Table of contents

### Properties

- [data](akashaproject_awf_sdk._internal_.ExecutionResult.md#data)
- [errors](akashaproject_awf_sdk._internal_.ExecutionResult.md#errors)
- [extensions](akashaproject_awf_sdk._internal_.ExecutionResult.md#extensions)

## Properties

### data

• `Optional` **data**: `TData`

#### Defined in

sdk/node_modules/graphql/execution/execute.d.ts:55

___

### errors

• `Optional` **errors**: readonly [`GraphQLError`](../classes/akashaproject_awf_sdk._internal_.GraphQLError.md)[]

#### Defined in

sdk/node_modules/graphql/execution/execute.d.ts:53

___

### extensions

• `Optional` **extensions**: `TExtensions`

#### Defined in

sdk/node_modules/graphql/execution/execute.d.ts:56
