[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / IAppSettings

# Interface: IAppSettings

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).IAppSettings

## Table of contents

### Methods

- [get](akashaproject_sdk_typings._internal_.IAppSettings.md#get)
- [getAll](akashaproject_sdk_typings._internal_.IAppSettings.md#getall)
- [install](akashaproject_sdk_typings._internal_.IAppSettings.md#install)
- [uninstall](akashaproject_sdk_typings._internal_.IAppSettings.md#uninstall)

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

[sdk/typings/src/interfaces/settings.ts:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L17)

___

### getAll

▸ **getAll**(): `any`

Returns all installed apps

#### Returns

`any`

#### Defined in

[sdk/typings/src/interfaces/settings.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L22)

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

[sdk/typings/src/interfaces/settings.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L28)

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

[sdk/typings/src/interfaces/settings.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/settings.ts#L34)
