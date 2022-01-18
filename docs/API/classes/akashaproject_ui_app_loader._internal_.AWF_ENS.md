[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_ENS

# Class: AWF\_ENS

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_ENS

## Implements

- [`AWF_IENS`](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.AWF_ENS.md#constructor)

### Properties

- [ENS\_ADDRESS](akashaproject_ui_app_loader._internal_.AWF_ENS.md#ens_address)
- [INTEGRATION\_REGISTRY\_ADDRESS](akashaproject_ui_app_loader._internal_.AWF_ENS.md#integration_registry_address)
- [REGISTRAR\_ADDRESS](akashaproject_ui_app_loader._internal_.AWF_ENS.md#registrar_address)
- [RESOLVER\_ADDRESS](akashaproject_ui_app_loader._internal_.AWF_ENS.md#resolver_address)
- [REVERSE\_STRING](akashaproject_ui_app_loader._internal_.AWF_ENS.md#reverse_string)

### Methods

- [claimName](akashaproject_ui_app_loader._internal_.AWF_ENS.md#claimname)
- [getAllIntegrationsIds](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getallintegrationsids)
- [getContracts](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getcontracts)
- [getIntegrationId](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getintegrationid)
- [getIntegrationInfo](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getintegrationinfo)
- [getIntegrationReleaseId](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getintegrationreleaseid)
- [getIntegrationReleaseInfo](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getintegrationreleaseinfo)
- [getIntegrationsCount](akashaproject_ui_app_loader._internal_.AWF_ENS.md#getintegrationscount)
- [isAvailable](akashaproject_ui_app_loader._internal_.AWF_ENS.md#isavailable)
- [registerName](akashaproject_ui_app_loader._internal_.AWF_ENS.md#registername)
- [resolveAddress](akashaproject_ui_app_loader._internal_.AWF_ENS.md#resolveaddress)
- [resolveName](akashaproject_ui_app_loader._internal_.AWF_ENS.md#resolvename)
- [setupContracts](akashaproject_ui_app_loader._internal_.AWF_ENS.md#setupcontracts)
- [userIsOwnerOf](akashaproject_ui_app_loader._internal_.AWF_ENS.md#userisownerof)

## Constructors

### constructor

• **new AWF_ENS**(`log`, `gql`, `auth`, `settings`, `globalChannel`, `web3`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_ui_app_loader._internal_.Logging.md) |
| `gql` | [`Gql`](akashaproject_ui_app_loader._internal_.Gql.md) |
| `auth` | [`AWF_Auth`](akashaproject_ui_app_loader._internal_.AWF_Auth.md) |
| `settings` | [`Settings`](akashaproject_ui_app_loader._internal_.Settings.md) |
| `globalChannel` | [`EventBus`](akashaproject_ui_app_loader._internal_.EventBus.md) |
| `web3` | [`Web3Connector`](akashaproject_ui_app_loader._internal_.Web3Connector.md) |

#### Defined in

[sdk/src/registry/index.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L58)

## Properties

### ENS\_ADDRESS

• `Readonly` **ENS\_ADDRESS**: ``"0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e"``

#### Defined in

[sdk/src/registry/index.ts:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L53)

___

### INTEGRATION\_REGISTRY\_ADDRESS

• `Readonly` **INTEGRATION\_REGISTRY\_ADDRESS**: ``"0x5E49595D7B3593a61Ed8e947c2cC23091cAB8BfC"``

#### Defined in

[sdk/src/registry/index.ts:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L57)

___

### REGISTRAR\_ADDRESS

• `Readonly` **REGISTRAR\_ADDRESS**: ``"0x9005a15eb865e8378e5cb9f45e8849ef1eC4F90B"``

#### Defined in

[sdk/src/registry/index.ts:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L51)

___

### RESOLVER\_ADDRESS

• `Readonly` **RESOLVER\_ADDRESS**: ``"0xf6305c19e814d2a75429Fd637d01F7ee0E77d615"``

#### Defined in

[sdk/src/registry/index.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L52)

___

### REVERSE\_STRING

• `Readonly` **REVERSE\_STRING**: ``"0x91d1777781884d03a6757a803996e38de2a42967fb37eeaca72729271025a9e2"``

#### Defined in

[sdk/src/registry/index.ts:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L54)

## Methods

### claimName

▸ **claimName**(`name`): `Observable`<{ `data`: `any`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Observable`<{ `data`: `any`  }\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[claimName](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#claimname)

#### Defined in

[sdk/src/registry/index.ts:101](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L101)

___

### getAllIntegrationsIds

▸ **getAllIntegrationsIds**(`offset?`, `limit?`): `Promise`<{ `data`: { `integrationIds`: `any` = data.packageIds; `nextIndex`: `any` = data.pointer }  }\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `offset` | `number` | `0` |
| `limit` | `number` | `5` |

#### Returns

`Promise`<{ `data`: { `integrationIds`: `any` = data.packageIds; `nextIndex`: `any` = data.pointer }  }\>

#### Defined in

[sdk/src/registry/index.ts:216](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L216)

___

### getContracts

▸ **getContracts**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `AkashaRegistrarInstance` | `any` |
| `ENSinstance` | `any` |
| `IntegrationRegistryInstance` | `any` |
| `ReverseRegistrarInstance` | `any` |

#### Defined in

[sdk/src/registry/index.ts:234](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L234)

___

### getIntegrationId

▸ **getIntegrationId**(`name`): `Promise`<{ `data`: { `id`: `any` = data }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<{ `data`: { `id`: `any` = data }  }\>

#### Defined in

[sdk/src/registry/index.ts:224](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L224)

___

### getIntegrationInfo

▸ **getIntegrationInfo**(`packageId`): `Promise`<{ `data`: { `author`: `any` = data.author; `enabled`: `any` = data.latestReleaseId; `integrationName`: `any` = data.integrationName; `latestReleaseId`: `any` = data.latestReleaseId }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `packageId` | `string` |

#### Returns

`Promise`<{ `data`: { `author`: `any` = data.author; `enabled`: `any` = data.latestReleaseId; `integrationName`: `any` = data.integrationName; `latestReleaseId`: `any` = data.latestReleaseId }  }\>

#### Defined in

[sdk/src/registry/index.ts:190](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L190)

___

### getIntegrationReleaseId

▸ **getIntegrationReleaseId**(`name`, `version`): `Promise`<{ `data`: { `id`: `any` = data.releaseId }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `version` | `string` |

#### Returns

`Promise`<{ `data`: { `id`: `any` = data.releaseId }  }\>

#### Defined in

[sdk/src/registry/index.ts:229](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L229)

___

### getIntegrationReleaseInfo

▸ **getIntegrationReleaseInfo**(`releaseId`): `Promise`<{ `data`: { `integrationName`: `any` = data.integrationName; `manifestHash`: `any` = data.manifestHash; `version`: `any` = data.version }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `releaseId` | `string` |

#### Returns

`Promise`<{ `data`: { `integrationName`: `any` = data.integrationName; `manifestHash`: `any` = data.manifestHash; `version`: `any` = data.version }  }\>

#### Defined in

[sdk/src/registry/index.ts:200](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L200)

___

### getIntegrationsCount

▸ **getIntegrationsCount**(): `Promise`<{ `data`: { `totalCount`: `any` = data.totalCount }  }\>

#### Returns

`Promise`<{ `data`: { `totalCount`: `any` = data.totalCount }  }\>

#### Defined in

[sdk/src/registry/index.ts:209](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L209)

___

### isAvailable

▸ **isAvailable**(`name`): `Promise`<{ `data`: `any`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<{ `data`: `any`  }\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[isAvailable](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#isavailable)

#### Defined in

[sdk/src/registry/index.ts:134](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L134)

___

### registerName

▸ **registerName**(`name`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`any`\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[registerName](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#registername)

#### Defined in

[sdk/src/registry/index.ts:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L74)

___

### resolveAddress

▸ **resolveAddress**(`ethAddress`): `Promise`<{ `data`: `string`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`Promise`<{ `data`: `string`  }\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[resolveAddress](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#resolveaddress)

#### Defined in

[sdk/src/registry/index.ts:146](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L146)

___

### resolveName

▸ **resolveName**(`name`): `Promise`<{ `data`: `string`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<{ `data`: `string`  }\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[resolveName](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#resolvename)

#### Defined in

[sdk/src/registry/index.ts:154](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L154)

___

### setupContracts

▸ **setupContracts**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

[sdk/src/registry/index.ts:159](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L159)

___

### userIsOwnerOf

▸ **userIsOwnerOf**(`name`): `Promise`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<{ `data`: `boolean`  }\>

#### Implementation of

[AWF_IENS](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md).[userIsOwnerOf](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IENS.md#userisownerof)

#### Defined in

[sdk/src/registry/index.ts:123](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/registry/index.ts#L123)
