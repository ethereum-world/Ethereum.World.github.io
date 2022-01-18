[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / TypedDataSigner

# Interface: TypedDataSigner

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).TypedDataSigner

## Implemented by

- [`JsonRpcSigner`](../classes/akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)
- [`Wallet`](../classes/akashaproject_ui_app_loader._internal_.Wallet.md)

## Table of contents

### Methods

- [\_signTypedData](akashaproject_ui_app_loader._internal_.TypedDataSigner.md#_signtypeddata)

## Methods

### \_signTypedData

▸ **_signTypedData**(`domain`, `types`, `value`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `domain` | [`TypedDataDomain`](akashaproject_ui_app_loader._internal_.TypedDataDomain.md) |
| `types` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, [`TypedDataField`](akashaproject_ui_app_loader._internal_.TypedDataField.md)[]\> |
| `value` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/abstract-signer/lib/index.d.ts:21
