[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_IpfsConnector

# Class: AWF\_IpfsConnector

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_IpfsConnector

## Implements

- [`AWF_IIpfsConnector`](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md#constructor)

### Properties

- [gateway](akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md#gateway)

### Methods

- [catDocument](akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md#catdocument)
- [getLegalDoc](akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md#getlegaldoc)
- [getSettings](akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md#getsettings)

## Constructors

### constructor

• **new AWF_IpfsConnector**(`log`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_awf_sdk._internal_.Logging.md) |

#### Defined in

[sdk/src/common/ipfs.connector.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/ipfs.connector.ts#L21)

## Properties

### gateway

• `Readonly` **gateway**: ``"https://hub.textile.io/ipfs"``

#### Implementation of

[AWF_IIpfsConnector](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md).[gateway](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#gateway)

#### Defined in

[sdk/src/common/ipfs.connector.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/ipfs.connector.ts#L12)

## Methods

### catDocument

▸ **catDocument**(`doc`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `doc` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Implementation of

[AWF_IIpfsConnector](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md).[catDocument](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#catdocument)

#### Defined in

[sdk/src/common/ipfs.connector.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/ipfs.connector.ts#L31)

___

### getLegalDoc

▸ **getLegalDoc**(`doc`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `doc` | [`LEGAL_DOCS`](../enums/akashaproject_awf_sdk._internal_.LEGAL_DOCS.md) | legal docs |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Implementation of

[AWF_IIpfsConnector](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md).[getLegalDoc](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#getlegaldoc)

#### Defined in

[sdk/src/common/ipfs.connector.ts:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/ipfs.connector.ts#L44)

___

### getSettings

▸ **getSettings**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `gateway` | `string` |

#### Implementation of

[AWF_IIpfsConnector](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md).[getSettings](../interfaces/akashaproject_awf_sdk._internal_.AWF_IIpfsConnector.md#getsettings)

#### Defined in

[sdk/src/common/ipfs.connector.ts:25](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/ipfs.connector.ts#L25)
