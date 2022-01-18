[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / TypedDataSigner

# Interface: TypedDataSigner

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).TypedDataSigner

## Implemented by

- [`JsonRpcSigner`](../classes/akashaproject_awf_sdk._internal_.JsonRpcSigner.md)
- [`Wallet`](../classes/akashaproject_awf_sdk._internal_.Wallet.md)

## Table of contents

### Methods

- [\_signTypedData](akashaproject_awf_sdk._internal_.TypedDataSigner.md#_signtypeddata)

## Methods

### \_signTypedData

▸ **_signTypedData**(`domain`, `types`, `value`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `domain` | [`TypedDataDomain`](akashaproject_awf_sdk._internal_.TypedDataDomain.md) |
| `types` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, [`TypedDataField`](akashaproject_awf_sdk._internal_.TypedDataField.md)[]\> |
| `value` | [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:21
