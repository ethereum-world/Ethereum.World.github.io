[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / FetchResult

# Interface: FetchResult<TData, TContext, TExtensions\>

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).FetchResult

## Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |
| `TContext` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |
| `TExtensions` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |

## Hierarchy

- [`ExecutionResult`](akashaproject_ui_app_loader._internal_.ExecutionResult.md)<`TData`, `TExtensions`\>

  ↳ **`FetchResult`**

## Table of contents

### Properties

- [context](akashaproject_ui_app_loader._internal_.FetchResult.md#context)
- [data](akashaproject_ui_app_loader._internal_.FetchResult.md#data)
- [errors](akashaproject_ui_app_loader._internal_.FetchResult.md#errors)
- [extensions](akashaproject_ui_app_loader._internal_.FetchResult.md#extensions)

## Properties

### context

• `Optional` **context**: `TContext`

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:22

___

### data

• `Optional` **data**: `TData`

#### Overrides

[ExecutionResult](akashaproject_ui_app_loader._internal_.ExecutionResult.md).[data](akashaproject_ui_app_loader._internal_.ExecutionResult.md#data)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:20

___

### errors

• `Optional` **errors**: readonly [`GraphQLError`](../classes/akashaproject_ui_app_loader._internal_.GraphQLError.md)[]

#### Inherited from

[ExecutionResult](akashaproject_ui_app_loader._internal_.ExecutionResult.md).[errors](akashaproject_ui_app_loader._internal_.ExecutionResult.md#errors)

#### Defined in

sdk/node_modules/graphql/execution/execute.d.ts:53

___

### extensions

• `Optional` **extensions**: `TExtensions`

#### Overrides

[ExecutionResult](akashaproject_ui_app_loader._internal_.ExecutionResult.md).[extensions](akashaproject_ui_app_loader._internal_.ExecutionResult.md#extensions)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:21
