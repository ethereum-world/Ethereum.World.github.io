[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / HttpLink

# Class: HttpLink

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).HttpLink

## Hierarchy

- [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

  ↳ **`HttpLink`**

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.HttpLink.md#constructor)

### Properties

- [options](akashaproject_awf_sdk._internal_.HttpLink.md#options)
- [requester](akashaproject_awf_sdk._internal_.HttpLink.md#requester)

### Methods

- [concat](akashaproject_awf_sdk._internal_.HttpLink.md#concat)
- [request](akashaproject_awf_sdk._internal_.HttpLink.md#request)
- [setOnError](akashaproject_awf_sdk._internal_.HttpLink.md#setonerror)
- [split](akashaproject_awf_sdk._internal_.HttpLink.md#split)
- [concat](akashaproject_awf_sdk._internal_.HttpLink.md#concat)
- [empty](akashaproject_awf_sdk._internal_.HttpLink.md#empty)
- [execute](akashaproject_awf_sdk._internal_.HttpLink.md#execute)
- [from](akashaproject_awf_sdk._internal_.HttpLink.md#from)
- [split](akashaproject_awf_sdk._internal_.HttpLink.md#split)

## Constructors

### constructor

• **new HttpLink**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`HttpOptions`](../interfaces/akashaproject_awf_sdk._internal_.HttpOptions.md) |

#### Overrides

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[constructor](akashaproject_awf_sdk._internal_.ApolloLink.md#constructor)

#### Defined in

sdk/node_modules/@apollo/client/link/http/HttpLink.d.ts:6

## Properties

### options

• **options**: [`HttpOptions`](../interfaces/akashaproject_awf_sdk._internal_.HttpOptions.md)

#### Defined in

sdk/node_modules/@apollo/client/link/http/HttpLink.d.ts:4

___

### requester

• **requester**: [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler)

#### Defined in

sdk/node_modules/@apollo/client/link/http/HttpLink.d.ts:5

## Methods

### concat

▸ **concat**(`next`): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `next` | [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_awf_sdk._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[concat](akashaproject_awf_sdk._internal_.ApolloLink.md#concat)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[request](akashaproject_awf_sdk._internal_.ApolloLink.md#request)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:12

___

### setOnError

▸ **setOnError**(`fn`): [`HttpLink`](akashaproject_awf_sdk._internal_.HttpLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | (`error`: `any`, `observer?`: [`Observer`](../interfaces/akashaproject_awf_sdk._internal_.Observer.md)<[`FetchResult`](../interfaces/akashaproject_awf_sdk._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\>\>) => ``false`` \| `void` |

#### Returns

[`HttpLink`](akashaproject_awf_sdk._internal_.HttpLink.md)

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[setOnError](akashaproject_awf_sdk._internal_.ApolloLink.md#setonerror)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[split](akashaproject_awf_sdk._internal_.ApolloLink.md#split)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[concat](akashaproject_awf_sdk._internal_.ApolloLink.md#concat)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:8

___

### empty

▸ `Static` **empty**(): [`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Returns

[`ApolloLink`](akashaproject_awf_sdk._internal_.ApolloLink.md)

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[empty](akashaproject_awf_sdk._internal_.ApolloLink.md#empty)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[execute](akashaproject_awf_sdk._internal_.ApolloLink.md#execute)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[from](akashaproject_awf_sdk._internal_.ApolloLink.md#from)

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

#### Inherited from

[ApolloLink](akashaproject_awf_sdk._internal_.ApolloLink.md).[split](akashaproject_awf_sdk._internal_.ApolloLink.md#split)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:6
