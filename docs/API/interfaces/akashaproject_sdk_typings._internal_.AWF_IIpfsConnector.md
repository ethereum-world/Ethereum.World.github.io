[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IIpfsConnector

# Interface: AWF\_IIpfsConnector

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IIpfsConnector

## Table of contents

### Properties

- [gateway](akashaproject_sdk_typings._internal_.AWF_IIpfsConnector.md#gateway)

### Methods

- [catDocument](akashaproject_sdk_typings._internal_.AWF_IIpfsConnector.md#catdocument)
- [getLegalDoc](akashaproject_sdk_typings._internal_.AWF_IIpfsConnector.md#getlegaldoc)
- [getSettings](akashaproject_sdk_typings._internal_.AWF_IIpfsConnector.md#getsettings)

## Properties

### gateway

• **gateway**: `string`

#### Defined in

[sdk/typings/src/interfaces/ipfs.connector.ts:5](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/ipfs.connector.ts#L5)

## Methods

### catDocument

▸ **catDocument**(`doc`): `Observable`<{ `data`: `string`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `doc` | `string` |

#### Returns

`Observable`<{ `data`: `string`  }\>

#### Defined in

[sdk/typings/src/interfaces/ipfs.connector.ts:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/ipfs.connector.ts#L9)

___

### getLegalDoc

▸ **getLegalDoc**(`doc`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `doc` | [`LEGAL_DOCS`](../enums/akashaproject_sdk_typings._internal_.LEGAL_DOCS.md) |

#### Returns

`any`

#### Defined in

[sdk/typings/src/interfaces/ipfs.connector.ts:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/ipfs.connector.ts#L15)

___

### getSettings

▸ **getSettings**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `gateway` | `any` |

#### Defined in

[sdk/typings/src/interfaces/ipfs.connector.ts:7](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/ipfs.connector.ts#L7)
