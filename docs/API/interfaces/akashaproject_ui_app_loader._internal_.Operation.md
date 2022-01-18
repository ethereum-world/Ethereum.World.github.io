[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / Operation

# Interface: Operation

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).Operation

## Table of contents

### Properties

- [extensions](akashaproject_ui_app_loader._internal_.Operation.md#extensions)
- [operationName](akashaproject_ui_app_loader._internal_.Operation.md#operationname)
- [query](akashaproject_ui_app_loader._internal_.Operation.md#query)
- [variables](akashaproject_ui_app_loader._internal_.Operation.md#variables)

### Methods

- [getContext](akashaproject_ui_app_loader._internal_.Operation.md#getcontext)
- [setContext](akashaproject_ui_app_loader._internal_.Operation.md#setcontext)

## Properties

### extensions

• **extensions**: [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:15

___

### operationName

• **operationName**: `string`

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:14

___

### query

• **query**: [`DocumentNode`](akashaproject_ui_app_loader._internal_.DocumentNode.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:12

___

### variables

• **variables**: [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:13

## Methods

### getContext

▸ **getContext**(): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:17

___

### setContext

▸ **setContext**(`context`): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:16
