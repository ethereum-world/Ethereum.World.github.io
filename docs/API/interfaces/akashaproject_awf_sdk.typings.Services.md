[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [typings](../modules/akashaproject_awf_sdk.typings.md) / Services

# Interface: Services

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[typings](../modules/akashaproject_awf_sdk.typings.md).Services

## Table of contents

### Properties

- [appSettings](akashaproject_awf_sdk.typings.Services.md#appsettings)
- [common](akashaproject_awf_sdk.typings.Services.md#common)
- [db](akashaproject_awf_sdk.typings.Services.md#db)
- [gql](akashaproject_awf_sdk.typings.Services.md#gql)
- [log](akashaproject_awf_sdk.typings.Services.md#log)
- [settings](akashaproject_awf_sdk.typings.Services.md#settings)
- [stash](akashaproject_awf_sdk.typings.Services.md#stash)

## Properties

### appSettings

• **appSettings**: [`IAppSettings`](akashaproject_awf_sdk._internal_.IAppSettings.md)

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:13

___

### common

• **common**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `ipfs` | [`AWF_IIpfsConnector`](akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md) |
| `web3` | [`IWeb3Connector`](akashaproject_awf_sdk._internal_.IWeb3Connector.md)<`unknown`\> |

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:15

___

### db

• **db**: [`IDBService`](akashaproject_awf_sdk._internal_.IDBService.md)<`unknown`, `unknown`\>

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:14

___

### gql

• **gql**: [`IGqlClient`](akashaproject_awf_sdk._internal_.IGqlClient.md)<`unknown`\>

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:9

___

### log

• **log**: [`ILogService`](akashaproject_awf_sdk._internal_.ILogService.md)

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:10

___

### settings

• **settings**: [`ISettingsService`](akashaproject_awf_sdk._internal_.ISettingsService.md)

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:12

___

### stash

• **stash**: [`IStashService`](akashaproject_awf_sdk._internal_.IStashService.md)<`unknown`\>

#### Defined in

sdk/typings/lib/service.interfaces.d.ts:11
