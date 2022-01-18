[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_IIpfsConnector

# Interface: AWF\_IIpfsConnector

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_IIpfsConnector

## Implemented by

- [`AWF_IpfsConnector`](../classes/akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md)

## Table of contents

### Properties

- [gateway](akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#gateway)

### Methods

- [catDocument](akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#catdocument)
- [getLegalDoc](akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#getlegaldoc)
- [getSettings](akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#getsettings)

## Properties

### gateway

• **gateway**: `string`

#### Defined in

sdk/typings/lib/interfaces/ipfs.connector.d.ts:4

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

sdk/typings/lib/interfaces/ipfs.connector.d.ts:8

___

### getLegalDoc

▸ **getLegalDoc**(`doc`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `doc` | [`LEGAL_DOCS`](../enums/akashaproject_awf_sdk._internal_.LEGAL_DOCS.md) |

#### Returns

`any`

#### Defined in

sdk/typings/lib/interfaces/ipfs.connector.d.ts:15

___

### getSettings

▸ **getSettings**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `gateway` | `any` |

#### Defined in

sdk/typings/lib/interfaces/ipfs.connector.d.ts:5
