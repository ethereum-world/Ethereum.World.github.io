[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / ApolloLink

# Class: ApolloLink

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).ApolloLink

## Hierarchy

- **`ApolloLink`**

  ↳ [`HttpLink`](akashaproject_awf_sdk._internal_.HttpLink.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.ApolloLink.md#constructor)

### Methods

- [concat](akashaproject_awf_sdk._internal_.ApolloLink.md#concat)
- [request](akashaproject_awf_sdk._internal_.ApolloLink.md#request)
- [setOnError](akashaproject_awf_sdk._internal_.ApolloLink.md#setonerror)
- [split](akashaproject_awf_sdk._internal_.ApolloLink.md#split)
- [concat](akashaproject_awf_sdk._internal_.ApolloLink.md#concat)
- [empty](akashaproject_awf_sdk._internal_.ApolloLink.md#empty)
- [execute](akashaproject_awf_sdk._internal_.ApolloLink.md#execute)
- [from](akashaproject_awf_sdk._internal_.ApolloLink.md#from)
- [split](akashaproject_awf_sdk._internal_.ApolloLink.md#split)

## Constructors

### constructor

• **new ApolloLink**(`request?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `request?` | [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:9

## Methods

### concat

▸ **concat**(`next`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `next` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:11

___

### request

▸ **request**(`operation`, `forward?`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `operation` | [`Operation`](../interfaces/akashaproject_awf_sdk._internal_.Operation.md) |
| `forward?` | [`NextLink`](../modules/akashaproject_awf_sdk._internal_.md#nextlink) |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:12

___

### setOnError

▸ **setOnError**(`fn`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | (`error`: `any`, `observer?`: [`Observer`](../interfaces/akashaproject_awf_sdk._internal_.Observer.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>) => ``false`` \| `void` |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:14

___

### split

▸ **split**(`test`, `left`, `right?`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `test` | (`op`: [`Operation`](../interfaces/akashaproject_awf_sdk._internal_.Operation.md)) => `boolean` |
| `left` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |
| `right?` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:10

___

### concat

▸ `Static` **concat**(`first`, `second`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |
| `second` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:8

___

### empty

▸ `Static` **empty**(): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:4

___

### execute

▸ `Static` **execute**(`link`, `operation`): [`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `link` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) |
| `operation` | [`GraphQLRequest`](../interfaces/akashaproject_awf_sdk._internal_.GraphQLRequest.md) |

#### Returns

[`Observable`](akashaproject_awf_sdk._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:7

___

### from

▸ `Static` **from**(`links`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `links` | ([`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler))[] |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:5

___

### split

▸ `Static` **split**(`test`, `left`, `right?`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `test` | (`op`: [`Operation`](../interfaces/akashaproject_awf_sdk._internal_.Operation.md)) => `boolean` |
| `left` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |
| `right?` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:6
