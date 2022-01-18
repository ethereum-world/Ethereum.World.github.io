[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / ISettingsService

# Interface: ISettingsService

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).ISettingsService

## Table of contents

### Methods

- [get](akashaproject_sdk_typings._internal_.ISettingsService.md#get)
- [remove](akashaproject_sdk_typings._internal_.ISettingsService.md#remove)
- [set](akashaproject_sdk_typings._internal_.ISettingsService.md#set)

## Methods

### get

▸ **get**(`moduleName`): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/settings.ts:8](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L8)

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

[sdk/typings/src/interfaces/settings.ts:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L9)

___

### set

▸ **set**(`moduleName`, `value`): [`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |
| `value` | [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\> \| [[`string`, `unknown`]] |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_sdk_typings._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/settings.ts:4](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L4)
