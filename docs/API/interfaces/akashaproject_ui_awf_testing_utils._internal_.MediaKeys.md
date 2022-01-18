[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaKeys

# Interface: MediaKeys

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaKeys

This EncryptedMediaExtensions API interface the represents a set of keys that an associated HTMLMediaElement can use for decryption of media data during playback.

## Table of contents

### Methods

- [createSession](akashaproject_ui_awf_testing_utils._internal_.MediaKeys.md#createsession)
- [setServerCertificate](akashaproject_ui_awf_testing_utils._internal_.MediaKeys.md#setservercertificate)

## Methods

### createSession

▸ **createSession**(`sessionType?`): [`MediaKeySession`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysession)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sessionType?` | [`MediaKeySessionType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysessiontype) |

#### Returns

[`MediaKeySession`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysession)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9855

___

### setServerCertificate

▸ **setServerCertificate**(`serverCertificate`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `serverCertificate` | [`BufferSource`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#buffersource) |

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9856
