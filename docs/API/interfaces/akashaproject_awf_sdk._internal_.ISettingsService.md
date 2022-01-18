[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / ISettingsService

# Interface: ISettingsService

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).ISettingsService

## Implemented by

- [`Settings`](../classes/akashaproject_awf_sdk._internal_.Settings.md)

## Table of contents

### Methods

- [get](akashaproject_awf_sdk._internal_.ISettingsService.md#get)
- [remove](akashaproject_awf_sdk._internal_.ISettingsService.md#remove)
- [set](akashaproject_awf_sdk._internal_.ISettingsService.md#set)

## Methods

### get

▸ **get**(`moduleName`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:4

___

### remove

▸ **remove**(`moduleName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |

#### Returns

`void`

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:5

___

### set

▸ **set**(`moduleName`, `value`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |
| `value` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| [[`string`, `unknown`]] |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:3
