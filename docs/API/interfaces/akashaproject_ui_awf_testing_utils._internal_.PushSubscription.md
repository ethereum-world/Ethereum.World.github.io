[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PushSubscription

# Interface: PushSubscription

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PushSubscription

This Push API interface provides a subcription's URL endpoint and allows unsubscription from a push service.

## Table of contents

### Properties

- [endpoint](akashaproject_ui_awf_testing_utils._internal_.PushSubscription.md#endpoint)
- [options](akashaproject_ui_awf_testing_utils._internal_.PushSubscription.md#options)

### Methods

- [getKey](akashaproject_ui_awf_testing_utils._internal_.PushSubscription.md#getkey)
- [toJSON](akashaproject_ui_awf_testing_utils._internal_.PushSubscription.md#tojson)
- [unsubscribe](akashaproject_ui_awf_testing_utils._internal_.PushSubscription.md#unsubscribe)

## Properties

### endpoint

• `Readonly` **endpoint**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11576

___

### options

• `Readonly` **options**: [`PushSubscriptionOptions`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushsubscriptionoptions)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11577

## Methods

### getKey

▸ **getKey**(`name`): `ArrayBuffer`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | [`PushEncryptionKeyName`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushencryptionkeyname) |

#### Returns

`ArrayBuffer`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11578

___

### toJSON

▸ **toJSON**(): [`PushSubscriptionJSON`](akashaproject_ui_awf_testing_utils._internal_.PushSubscriptionJSON.md)

#### Returns

[`PushSubscriptionJSON`](akashaproject_ui_awf_testing_utils._internal_.PushSubscriptionJSON.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11579

___

### unsubscribe

▸ **unsubscribe**(): `Promise`<`boolean`\>

#### Returns

`Promise`<`boolean`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11580
