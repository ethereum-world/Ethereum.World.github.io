[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PushManager

# Interface: PushManager

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PushManager

This Push API interface provides a way to receive notifications from third-party servers as well as request URLs for push notifications.

## Table of contents

### Methods

- [getSubscription](akashaproject_ui_awf_testing_utils._internal_.PushManager.md#getsubscription)
- [permissionState](akashaproject_ui_awf_testing_utils._internal_.PushManager.md#permissionstate)
- [subscribe](akashaproject_ui_awf_testing_utils._internal_.PushManager.md#subscribe)

## Methods

### getSubscription

▸ **getSubscription**(): `Promise`<[`PushSubscription`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushsubscription)\>

#### Returns

`Promise`<[`PushSubscription`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushsubscription)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11563

___

### permissionState

▸ **permissionState**(`options?`): `Promise`<[`PushPermissionState`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushpermissionstate)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`PushSubscriptionOptionsInit`](akashaproject_ui_awf_testing_utils._internal_.PushSubscriptionOptionsInit.md) |

#### Returns

`Promise`<[`PushPermissionState`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushpermissionstate)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11564

___

### subscribe

▸ **subscribe**(`options?`): `Promise`<[`PushSubscription`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushsubscription)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`PushSubscriptionOptionsInit`](akashaproject_ui_awf_testing_utils._internal_.PushSubscriptionOptionsInit.md) |

#### Returns

`Promise`<[`PushSubscription`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pushsubscription)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11565
