[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaKeySystemAccess

# Interface: MediaKeySystemAccess

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaKeySystemAccess

This EncryptedMediaExtensions API interface provides access to a Key System for decryption and/or a content protection provider. You can request an instance of this object using the Navigator.requestMediaKeySystemAccess method.

## Table of contents

### Properties

- [keySystem](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemAccess.md#keysystem)

### Methods

- [createMediaKeys](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemAccess.md#createmediakeys)
- [getConfiguration](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemAccess.md#getconfiguration)

## Properties

### keySystem

• `Readonly` **keySystem**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9843

## Methods

### createMediaKeys

▸ **createMediaKeys**(): `Promise`<[`MediaKeys`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeys)\>

#### Returns

`Promise`<[`MediaKeys`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeys)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9844

___

### getConfiguration

▸ **getConfiguration**(): [`MediaKeySystemConfiguration`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemConfiguration.md)

#### Returns

[`MediaKeySystemConfiguration`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemConfiguration.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9845
