[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / FormData

# Interface: FormData

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).FormData

Provides a way to easily construct a set of key/value pairs representing form fields and their values, which can then be easily sent using the XMLHttpRequest.send() method. It uses the same format a form would use if the encoding type were set to "multipart/form-data".

## Table of contents

### Methods

- [append](akashaproject_ui_app_loader._internal_.FormData.md#append)
- [delete](akashaproject_ui_app_loader._internal_.FormData.md#delete)
- [forEach](akashaproject_ui_app_loader._internal_.FormData.md#foreach)
- [get](akashaproject_ui_app_loader._internal_.FormData.md#get)
- [getAll](akashaproject_ui_app_loader._internal_.FormData.md#getall)
- [has](akashaproject_ui_app_loader._internal_.FormData.md#has)
- [set](akashaproject_ui_app_loader._internal_.FormData.md#set)

## Methods

### append

▸ **append**(`name`, `value`, `fileName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `value` | `string` \| [`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob) |
| `fileName?` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5432

___

### delete

▸ **delete**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5433

___

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`value`: [`FormDataEntryValue`](../modules/akashaproject_ui_app_loader._internal_.md#formdataentryvalue), `key`: `string`, `parent`: [`FormData`](../modules/akashaproject_ui_app_loader._internal_.md#formdata)) => `void` |
| `thisArg?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5438

___

### get

▸ **get**(`name`): [`FormDataEntryValue`](../modules/akashaproject_ui_app_loader._internal_.md#formdataentryvalue)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`FormDataEntryValue`](../modules/akashaproject_ui_app_loader._internal_.md#formdataentryvalue)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5434

___

### getAll

▸ **getAll**(`name`): [`FormDataEntryValue`](../modules/akashaproject_ui_app_loader._internal_.md#formdataentryvalue)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`FormDataEntryValue`](../modules/akashaproject_ui_app_loader._internal_.md#formdataentryvalue)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5435

___

### has

▸ **has**(`name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5436

___

### set

▸ **set**(`name`, `value`, `fileName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `value` | `string` \| [`Blob`](../modules/akashaproject_ui_app_loader._internal_.md#blob) |
| `fileName?` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5437
