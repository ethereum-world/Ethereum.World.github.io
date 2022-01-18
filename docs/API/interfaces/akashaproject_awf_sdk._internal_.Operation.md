[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Operation

# Interface: Operation

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Operation

## Table of contents

### Properties

- [extensions](akashaproject_awf_sdk._internal_.Operation.md#extensions)
- [operationName](akashaproject_awf_sdk._internal_.Operation.md#operationname)
- [query](akashaproject_awf_sdk._internal_.Operation.md#query)
- [variables](akashaproject_awf_sdk._internal_.Operation.md#variables)

### Methods

- [getContext](akashaproject_awf_sdk._internal_.Operation.md#getcontext)
- [setContext](akashaproject_awf_sdk._internal_.Operation.md#setcontext)

## Properties

### extensions

• **extensions**: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:15

___

### operationName

• **operationName**: `string`

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:14

___

### query

• **query**: [`DocumentNode`](akashaproject_awf_sdk._internal_.DocumentNode.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:12

___

### variables

• **variables**: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:13

## Methods

### getContext

▸ **getContext**(): [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Returns

[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:17

___

### setContext

▸ **setContext**(`context`): [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |

#### Returns

[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/types.d.ts:16
