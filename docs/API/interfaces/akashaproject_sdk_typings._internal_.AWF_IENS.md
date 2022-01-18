[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IENS

# Interface: AWF\_IENS

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IENS

## Table of contents

### Methods

- [claimName](akashaproject_sdk_typings._internal_.AWF_IENS.md#claimname)
- [isAvailable](akashaproject_sdk_typings._internal_.AWF_IENS.md#isavailable)
- [registerName](akashaproject_sdk_typings._internal_.AWF_IENS.md#registername)
- [resolveAddress](akashaproject_sdk_typings._internal_.AWF_IENS.md#resolveaddress)
- [resolveName](akashaproject_sdk_typings._internal_.AWF_IENS.md#resolvename)
- [userIsOwnerOf](akashaproject_sdk_typings._internal_.AWF_IENS.md#userisownerof)

## Methods

### claimName

▸ **claimName**(`name`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:6](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L6)

___

### isAvailable

▸ **isAvailable**(`name`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L10)

___

### registerName

▸ **registerName**(`name`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:4](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L4)

___

### resolveAddress

▸ **resolveAddress**(`ethAddress`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L12)

___

### resolveName

▸ **resolveName**(`name`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L14)

___

### userIsOwnerOf

▸ **userIsOwnerOf**(`name`): `Promise`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`unknown`\>

#### Defined in

[sdk/typings/src/interfaces/registry.ts:8](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/registry.ts#L8)
