[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / HttpOptions

# Interface: HttpOptions

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).HttpOptions

## Table of contents

### Properties

- [credentials](akashaproject_awf_sdk._internal_.HttpOptions.md#credentials)
- [fetch](akashaproject_awf_sdk._internal_.HttpOptions.md#fetch)
- [fetchOptions](akashaproject_awf_sdk._internal_.HttpOptions.md#fetchoptions)
- [headers](akashaproject_awf_sdk._internal_.HttpOptions.md#headers)
- [includeExtensions](akashaproject_awf_sdk._internal_.HttpOptions.md#includeextensions)
- [includeUnusedVariables](akashaproject_awf_sdk._internal_.HttpOptions.md#includeunusedvariables)
- [print](akashaproject_awf_sdk._internal_.HttpOptions.md#print)
- [uri](akashaproject_awf_sdk._internal_.HttpOptions.md#uri)
- [useGETForQueries](akashaproject_awf_sdk._internal_.HttpOptions.md#usegetforqueries)

## Properties

### credentials

• `Optional` **credentials**: `string`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:20

___

### fetch

• `Optional` **fetch**: (`input`: [`RequestInfo`](../modules/akashaproject_awf_sdk._internal_.md#requestinfo), `init?`: [`RequestInit`](akashaproject_awf_sdk._internal_.RequestInit.md)) => `Promise`<[`Response`](../modules/akashaproject_awf_sdk._internal_.md#response)\>

#### Type declaration

▸ (`input`, `init?`): `Promise`<[`Response`](../modules/akashaproject_awf_sdk._internal_.md#response)\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `input` | [`RequestInfo`](../modules/akashaproject_awf_sdk._internal_.md#requestinfo) |
| `init?` | [`RequestInit`](akashaproject_awf_sdk._internal_.RequestInit.md) |

##### Returns

`Promise`<[`Response`](../modules/akashaproject_awf_sdk._internal_.md#response)\>

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:18

___

### fetchOptions

• `Optional` **fetchOptions**: `any`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:21

___

### headers

• `Optional` **headers**: `any`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:19

___

### includeExtensions

• `Optional` **includeExtensions**: `boolean`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:17

___

### includeUnusedVariables

• `Optional` **includeUnusedVariables**: `boolean`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:23

___

### print

• `Optional` **print**: [`Printer`](akashaproject_awf_sdk._internal_.Printer.md)

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:24

___

### uri

• `Optional` **uri**: `string` \| [`UriFunction`](akashaproject_awf_sdk._internal_.UriFunction.md)

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:16

___

### useGETForQueries

• `Optional` **useGETForQueries**: `boolean`

#### Defined in

sdk/node_modules/@apollo/client/link/http/selectHttpOptionsAndBody.d.ts:22
