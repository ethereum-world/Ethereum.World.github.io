[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaKeyStatusMap

# Interface: MediaKeyStatusMap

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaKeyStatusMap

This EncryptedMediaExtensions API interface is a read-only map of media key statuses by key IDs.

## Table of contents

### Properties

- [size](akashaproject_ui_awf_testing_utils._internal_.MediaKeyStatusMap.md#size)

### Methods

- [forEach](akashaproject_ui_awf_testing_utils._internal_.MediaKeyStatusMap.md#foreach)
- [get](akashaproject_ui_awf_testing_utils._internal_.MediaKeyStatusMap.md#get)
- [has](akashaproject_ui_awf_testing_utils._internal_.MediaKeyStatusMap.md#has)

## Properties

### size

• `Readonly` **size**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9830

## Methods

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`value`: [`MediaKeyStatus`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeystatus), `key`: [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource), `parent`: [`MediaKeyStatusMap`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeystatusmap)) => `void` |
| `thisArg?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9833

___

### get

▸ **get**(`keyId`): [`MediaKeyStatus`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeystatus)

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyId` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

[`MediaKeyStatus`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeystatus)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9831

___

### has

▸ **has**(`keyId`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyId` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9832
