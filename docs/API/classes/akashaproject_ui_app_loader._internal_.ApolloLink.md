[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / ApolloLink

# Class: ApolloLink

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).ApolloLink

## Hierarchy

- **`ApolloLink`**

  ↳ [`HttpLink`](akashaproject_ui_app_loader._internal_.HttpLink.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.ApolloLink.md#constructor)

### Methods

- [concat](akashaproject_ui_app_loader._internal_.ApolloLink.md#concat)
- [request](akashaproject_ui_app_loader._internal_.ApolloLink.md#request)
- [setOnError](akashaproject_ui_app_loader._internal_.ApolloLink.md#setonerror)
- [split](akashaproject_ui_app_loader._internal_.ApolloLink.md#split)
- [concat](akashaproject_ui_app_loader._internal_.ApolloLink.md#concat)
- [empty](akashaproject_ui_app_loader._internal_.ApolloLink.md#empty)
- [execute](akashaproject_ui_app_loader._internal_.ApolloLink.md#execute)
- [from](akashaproject_ui_app_loader._internal_.ApolloLink.md#from)
- [split](akashaproject_ui_app_loader._internal_.ApolloLink.md#split)

## Constructors

### constructor

• **new ApolloLink**(`request?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `request?` | [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:9

## Methods

### concat

▸ **concat**(`next`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `next` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:11

___

### request

▸ **request**(`operation`, `forward?`): [`Observable`](akashaproject_ui_app_loader._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_ui_app_loader._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `operation` | [`Operation`](../interfaces/akashaproject_ui_app_loader._internal_.Operation.md) |
| `forward?` | [`NextLink`](../modules/akashaproject_ui_app_loader._internal_.md#nextlink) |

#### Returns

[`Observable`](akashaproject_ui_app_loader._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_ui_app_loader._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\>\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:12

___

### setOnError

▸ **setOnError**(`fn`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | (`error`: `any`, `observer?`: [`Observer`](../interfaces/akashaproject_ui_app_loader._internal_.Observer.md)<[`FetchResult`](../interfaces/akashaproject_ui_app_loader._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\>\>) => ``false`` \| `void` |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:14

___

### split

▸ **split**(`test`, `left`, `right?`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `test` | (`op`: [`Operation`](../interfaces/akashaproject_ui_app_loader._internal_.Operation.md)) => `boolean` |
| `left` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |
| `right?` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:10

___

### concat

▸ `Static` **concat**(`first`, `second`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |
| `second` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:8

___

### empty

▸ `Static` **empty**(): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:4

___

### execute

▸ `Static` **execute**(`link`, `operation`): [`Observable`](akashaproject_ui_app_loader._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_ui_app_loader._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `link` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) |
| `operation` | [`GraphQLRequest`](../interfaces/akashaproject_ui_app_loader._internal_.GraphQLRequest.md) |

#### Returns

[`Observable`](akashaproject_ui_app_loader._internal_.Observable.md)<[`FetchResult`](../interfaces/akashaproject_ui_app_loader._internal_.FetchResult.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\>\>

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:7

___

### from

▸ `Static` **from**(`links`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `links` | ([`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler))[] |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:5

___

### split

▸ `Static` **split**(`test`, `left`, `right?`): [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `test` | (`op`: [`Operation`](../interfaces/akashaproject_ui_app_loader._internal_.Operation.md)) => `boolean` |
| `left` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |
| `right?` | [`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md) \| [`RequestHandler`](../modules/akashaproject_ui_app_loader._internal_.md#requesthandler) |

#### Returns

[`ApolloLink`](akashaproject_ui_app_loader._internal_.ApolloLink.md)

#### Defined in

sdk/node_modules/@apollo/client/link/core/ApolloLink.d.ts:6
