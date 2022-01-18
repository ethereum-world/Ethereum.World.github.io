[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / IGqlClient

# Interface: IGqlClient<Operation\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).IGqlClient

## Type parameters

| Name |
| :------ |
| `Operation` |

## Implemented by

- [`Gql`](../classes/akashaproject_awf_sdk._internal_.Gql.md)

## Table of contents

### Methods

- [run](akashaproject_awf_sdk._internal_.IGqlClient.md#run)

## Methods

### run

▸ **run**(`operation`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`Operation`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `operation` | [`GraphQLRequest`](akashaproject_awf_sdk._internal_.GraphQLRequest.md) |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`Operation`\>

#### Defined in

sdk/typings/lib/interfaces/gql.d.ts:4
