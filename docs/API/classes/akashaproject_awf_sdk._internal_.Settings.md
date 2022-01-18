[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Settings

# Class: Settings

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Settings

## Implements

- [`ISettingsService`](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Settings.md#constructor)

### Methods

- [get](akashaproject_awf_sdk._internal_.Settings.md#get)
- [remove](akashaproject_awf_sdk._internal_.Settings.md#remove)
- [set](akashaproject_awf_sdk._internal_.Settings.md#set)

## Constructors

### constructor

• **new Settings**()

## Methods

### get

▸ **get**(`service`): `Observable`<{ `data`: [`SettingsSchema`](../interfaces/akashaproject_awf_sdk._internal_.SettingsSchema.md) & {} & `Instance`  }\>

Returns the settings object for a specified service name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `service` | `string` | The service name |

#### Returns

`Observable`<{ `data`: [`SettingsSchema`](../interfaces/akashaproject_awf_sdk._internal_.SettingsSchema.md) & {} & `Instance`  }\>

#### Implementation of

[ISettingsService](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md).[get](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md#get)

#### Defined in

[sdk/src/settings/index.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/index.ts#L20)

___

### remove

▸ **remove**(`serviceName`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `serviceName` | `string` |

#### Returns

`Promise`<`void`\>

#### Implementation of

[ISettingsService](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md).[remove](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md#remove)

#### Defined in

[sdk/src/settings/index.ts:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/index.ts#L54)

___

### set

▸ **set**(`service`, `options`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`[]\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `service` | `string` | The service name |
| `options` | [[`string`, `unknown`]] | Array of option pairs [optionName, value] |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`[]\>

ServiceCallResult

#### Implementation of

[ISettingsService](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md).[set](../interfaces/akashaproject_awf_sdk._internal_.ISettingsService.md#set)

#### Defined in

[sdk/src/settings/index.ts:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/index.ts#L37)
