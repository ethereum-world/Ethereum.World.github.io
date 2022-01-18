[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / IAppSettings

# Interface: IAppSettings

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).IAppSettings

## Implemented by

- [`AppSettings`](../classes/akashaproject_awf_sdk._internal_.AppSettings.md)

## Table of contents

### Methods

- [get](akashaproject_awf_sdk._internal_.IAppSettings.md#get)
- [getAll](akashaproject_awf_sdk._internal_.IAppSettings.md#getall)
- [install](akashaproject_awf_sdk._internal_.IAppSettings.md#install)
- [uninstall](akashaproject_awf_sdk._internal_.IAppSettings.md#uninstall)

## Methods

### get

▸ **get**(`appName`): `any`

Returns an app configuration object

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `appName` | `string` | Name of the app |

#### Returns

`any`

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:12

___

### getAll

▸ **getAll**(): `any`

Returns all installed apps

#### Returns

`any`

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:16

___

### install

▸ **install**(`app`): `any`

Persist installed app configuration for the current user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `app` | `unknown` | Object |

#### Returns

`any`

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:21

___

### uninstall

▸ **uninstall**(`appName`): `Promise`<`void`\>

Uninstall app by name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `appName` | `string` | Name of the app |

#### Returns

`Promise`<`void`\>

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:26
