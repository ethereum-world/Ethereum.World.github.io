[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / URLSearchParams

# Interface: URLSearchParams

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).URLSearchParams

## Table of contents

### Methods

- [append](akashaproject_awf_sdk._internal_.URLSearchParams.md#append)
- [delete](akashaproject_awf_sdk._internal_.URLSearchParams.md#delete)
- [forEach](akashaproject_awf_sdk._internal_.URLSearchParams.md#foreach)
- [get](akashaproject_awf_sdk._internal_.URLSearchParams.md#get)
- [getAll](akashaproject_awf_sdk._internal_.URLSearchParams.md#getall)
- [has](akashaproject_awf_sdk._internal_.URLSearchParams.md#has)
- [set](akashaproject_awf_sdk._internal_.URLSearchParams.md#set)
- [sort](akashaproject_awf_sdk._internal_.URLSearchParams.md#sort)
- [toString](akashaproject_awf_sdk._internal_.URLSearchParams.md#tostring)

## Methods

### append

▸ **append**(`name`, `value`): `void`

Appends a specified key/value pair as a new search parameter.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `value` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14950

___

### delete

▸ **delete**(`name`): `void`

Deletes the given search parameter, and its associated value, from the list of all search parameters.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14954

___

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`value`: `string`, `key`: `string`, `parent`: [`URLSearchParams`](../modules/akashaproject_awf_sdk._internal_.md#urlsearchparams)) => `void` |
| `thisArg?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14976

___

### get

▸ **get**(`name`): `string`

Returns the first value associated to the given search parameter.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14958

___

### getAll

▸ **getAll**(`name`): `string`[]

Returns all the values association with a given search parameter.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`string`[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14962

___

### has

▸ **has**(`name`): `boolean`

Returns a Boolean indicating if such a search parameter exists.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14966

___

### set

▸ **set**(`name`, `value`): `void`

Sets the value associated to a given search parameter to the given value. If there were several values, delete the others.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `value` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14970

___

### sort

▸ **sort**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14971

___

### toString

▸ **toString**(): `string`

Returns a string containing a query string suitable for use in a URL. Does not include the question mark.

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14975
