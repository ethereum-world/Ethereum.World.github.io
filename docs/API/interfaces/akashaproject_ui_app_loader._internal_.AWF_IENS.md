[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_IENS

# Interface: AWF\_IENS

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_IENS

## Implemented by

- [`AWF_ENS`](../classes/akashaproject_ui_app_loader._internal_.AWF_ENS.md)

## Table of contents

### Methods

- [claimName](akashaproject_ui_app_loader._internal_.AWF_IENS.md#claimname)
- [isAvailable](akashaproject_ui_app_loader._internal_.AWF_IENS.md#isavailable)
- [registerName](akashaproject_ui_app_loader._internal_.AWF_IENS.md#registername)
- [resolveAddress](akashaproject_ui_app_loader._internal_.AWF_IENS.md#resolveaddress)
- [resolveName](akashaproject_ui_app_loader._internal_.AWF_IENS.md#resolvename)
- [userIsOwnerOf](akashaproject_ui_app_loader._internal_.AWF_IENS.md#userisownerof)

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

sdk/typings/lib/interfaces/registry.d.ts:4

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

sdk/typings/lib/interfaces/registry.d.ts:6

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

sdk/typings/lib/interfaces/registry.d.ts:3

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

sdk/typings/lib/interfaces/registry.d.ts:7

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

sdk/typings/lib/interfaces/registry.d.ts:8

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

sdk/typings/lib/interfaces/registry.d.ts:5
