[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Geolocation

# Interface: Geolocation

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Geolocation

An object able to programmatically obtain the position of the device. It gives Web content access to the location of the device. This allows a Web site or app to offer customized results based on the user's location.

## Table of contents

### Methods

- [clearWatch](akashaproject_ui_awf_testing_utils._internal_.Geolocation.md#clearwatch)
- [getCurrentPosition](akashaproject_ui_awf_testing_utils._internal_.Geolocation.md#getcurrentposition)
- [watchPosition](akashaproject_ui_awf_testing_utils._internal_.Geolocation.md#watchposition)

## Methods

### clearWatch

▸ **clearWatch**(`watchId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `watchId` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5524

___

### getCurrentPosition

▸ **getCurrentPosition**(`successCallback`, `errorCallback?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `successCallback` | [`PositionCallback`](akashaproject_ui_awf_testing_utils._internal_.PositionCallback.md) |
| `errorCallback?` | [`PositionErrorCallback`](akashaproject_ui_awf_testing_utils._internal_.PositionErrorCallback.md) |
| `options?` | [`PositionOptions`](akashaproject_ui_awf_testing_utils._internal_.PositionOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5525

___

### watchPosition

▸ **watchPosition**(`successCallback`, `errorCallback?`, `options?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `successCallback` | [`PositionCallback`](akashaproject_ui_awf_testing_utils._internal_.PositionCallback.md) |
| `errorCallback?` | [`PositionErrorCallback`](akashaproject_ui_awf_testing_utils._internal_.PositionErrorCallback.md) |
| `options?` | [`PositionOptions`](akashaproject_ui_awf_testing_utils._internal_.PositionOptions.md) |

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5526
