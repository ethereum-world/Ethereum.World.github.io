[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / UseGlobalLoginProps

# Interface: UseGlobalLoginProps

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).UseGlobalLoginProps

## Table of contents

### Properties

- [onError](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#onerror)
- [onLogin](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#onlogin)
- [onLogout](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#onlogout)

### Methods

- [onLoadFromCache](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#onloadfromcache)
- [onReady](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#onready)
- [waitForAuth](akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md#waitforauth)

## Properties

### onError

• `Optional` **onError**: [`OnErrorHandler`](../modules/akashaproject_ui_awf_hooks._internal_.md#onerrorhandler)

#### Defined in

[ui/hooks/src/use-global-login.ts:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L18)

___

### onLogin

• **onLogin**: [`OnLoginSuccessHandler`](../modules/akashaproject_ui_awf_hooks._internal_.md#onloginsuccesshandler)

#### Defined in

[ui/hooks/src/use-global-login.ts:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L16)

___

### onLogout

• **onLogout**: [`OnLogoutSuccessHandler`](../modules/akashaproject_ui_awf_hooks._internal_.md#onlogoutsuccesshandler)

#### Defined in

[ui/hooks/src/use-global-login.ts:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L17)

## Methods

### onLoadFromCache

▸ `Optional` **onLoadFromCache**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`CurrentUser`](akashaproject_ui_awf_hooks._internal_.CurrentUser.md) |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-global-login.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L21)

___

### onReady

▸ `Optional` **onReady**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Object` |
| `data.ethAddress` | `string` |
| `data.pubKey` | `string` |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-global-login.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L20)

___

### waitForAuth

▸ `Optional` **waitForAuth**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `boolean` |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-global-login.ts:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L19)
