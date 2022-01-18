[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Gql

# Class: Gql

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Gql

## Implements

- [`IGqlClient`](../interfaces/akashaproject_awf_sdk._internal_.IGqlClient.md)<`unknown`\>

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Gql.md#constructor)

### Properties

- [\_link](akashaproject_awf_sdk._internal_.Gql.md#_link)

### Methods

- [clearCache](akashaproject_awf_sdk._internal_.Gql.md#clearcache)
- [getCache](akashaproject_awf_sdk._internal_.Gql.md#getcache)
- [makeOperation](akashaproject_awf_sdk._internal_.Gql.md#makeoperation)
- [run](akashaproject_awf_sdk._internal_.Gql.md#run)

## Constructors

### constructor

• **new Gql**(`stash`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `stash` | [`Stash`](akashaproject_awf_sdk._internal_.Stash.md) |

#### Defined in

[sdk/src/gql/index.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L26)

## Properties

### \_link

• `Readonly` **\_link**: [`HttpLink`](akashaproject_awf_sdk._internal_.HttpLink.md)

#### Defined in

[sdk/src/gql/index.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L22)

## Methods

### clearCache

▸ **clearCache**(): `void`

#### Returns

`void`

#### Defined in

[sdk/src/gql/index.ts:83](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L83)

___

### getCache

▸ **getCache**(): [`IQuickLRU`](../modules/akashaproject_awf_sdk._internal_.md#iquicklru)

#### Returns

[`IQuickLRU`](../modules/akashaproject_awf_sdk._internal_.md#iquicklru)

cache container for graphQL results

#### Defined in

[sdk/src/gql/index.ts:79](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L79)

___

### makeOperation

▸ **makeOperation**(`operation`): [`GraphQLRequest`](../interfaces/akashaproject_awf_sdk._internal_.GraphQLRequest.md)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `operation` | [`GqlOperation`](../interfaces/akashaproject_awf_sdk._internal_.GqlOperation.md) | graphQL request object |

#### Returns

[`GraphQLRequest`](../interfaces/akashaproject_awf_sdk._internal_.GraphQLRequest.md)

an object with the transformed graphQL template string for query

#### Defined in

[sdk/src/gql/index.ts:66](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L66)

___

### run

▸ **run**<`T`\>(`operation`, `saveCache?`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `operation` | [`GraphQLRequest`](../interfaces/akashaproject_awf_sdk._internal_.GraphQLRequest.md) | `undefined` | graphQL request object |
| `saveCache` | `boolean` | `true` | Cache the result |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`T`\>

ServiceCallResult

#### Implementation of

[IGqlClient](../interfaces/akashaproject_awf_sdk._internal_.IGqlClient.md).[run](../interfaces/akashaproject_awf_sdk._internal_.IGqlClient.md#run)

#### Defined in

[sdk/src/gql/index.ts:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/gql/index.ts#L43)
