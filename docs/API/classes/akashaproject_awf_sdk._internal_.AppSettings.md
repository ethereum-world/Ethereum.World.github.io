[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AppSettings

# Class: AppSettings

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AppSettings

## Implements

- [`IAppSettings`](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.AppSettings.md#constructor)

### Methods

- [get](akashaproject_awf_sdk._internal_.AppSettings.md#get)
- [getAll](akashaproject_awf_sdk._internal_.AppSettings.md#getall)
- [install](akashaproject_awf_sdk._internal_.AppSettings.md#install)
- [uninstall](akashaproject_awf_sdk._internal_.AppSettings.md#uninstall)

## Constructors

### constructor

• **new AppSettings**(`log`, `db`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_awf_sdk._internal_.Logging.md) |
| `db` | [`DB`](akashaproject_awf_sdk._internal_.DB.md) |

#### Defined in

[sdk/src/settings/apps.ts:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/apps.ts#L18)

## Methods

### get

▸ **get**(`appName`): `Observable`<{ `data`: [`AppsSchema`](../interfaces/akashaproject_awf_sdk._internal_.AppsSchema.md) & {} & `Instance`  }\>

Returns an app configuration object

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `appName` | `string` | Name of the app |

#### Returns

`Observable`<{ `data`: [`AppsSchema`](../interfaces/akashaproject_awf_sdk._internal_.AppsSchema.md) & {} & `Instance`  }\>

#### Implementation of

[IAppSettings](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md).[get](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md#get)

#### Defined in

[sdk/src/settings/apps.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/apps.ts#L27)

___

### getAll

▸ **getAll**(): `Observable`<{ `data`: [`AppsSchema`](../interfaces/akashaproject_awf_sdk._internal_.AppsSchema.md) & {} & `Instance`[]  }\>

Returns all installed apps

#### Returns

`Observable`<{ `data`: [`AppsSchema`](../interfaces/akashaproject_awf_sdk._internal_.AppsSchema.md) & {} & `Instance`[]  }\>

#### Implementation of

[IAppSettings](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md).[getAll](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md#getall)

#### Defined in

[sdk/src/settings/apps.ts:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/apps.ts#L39)

___

### install

▸ **install**(`app`): `Observable`<`boolean` \| { `data`: `string`[]  }\>

Persist installed app configuration for the current user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `app` | [`AppsSchema`](../interfaces/akashaproject_awf_sdk._internal_.AppsSchema.md) | Object |

#### Returns

`Observable`<`boolean` \| { `data`: `string`[]  }\>

#### Implementation of

[IAppSettings](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md).[install](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md#install)

#### Defined in

[sdk/src/settings/apps.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/apps.ts#L52)

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

#### Implementation of

[IAppSettings](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md).[uninstall](../interfaces/akashaproject_awf_sdk._internal_.IAppSettings.md#uninstall)

#### Defined in

[sdk/src/settings/apps.ts:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/settings/apps.ts#L72)
