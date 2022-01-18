[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / UseAnalyticsActions

# Interface: UseAnalyticsActions

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).UseAnalyticsActions

## Table of contents

### Methods

- [acceptConsent](akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md#acceptconsent)
- [enableTracking](akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md#enabletracking)
- [rejectConsent](akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md#rejectconsent)
- [trackEvent](akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md#trackevent)

## Methods

### acceptConsent

▸ **acceptConsent**(`type`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`CookieConsentTypes`](../enums/akashaproject_ui_awf_hooks.CookieConsentTypes.md) |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-analytics.ts:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-analytics.ts#L14)

___

### enableTracking

▸ **enableTracking**(): `void`

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-analytics.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-analytics.ts#L12)

___

### rejectConsent

▸ **rejectConsent**(): `void`

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-analytics.ts:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-analytics.ts#L16)

___

### trackEvent

▸ **trackEvent**(`category`, `action`, `name`, `value?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `category` | `string` |
| `action` | `string` |
| `name` | `string` |
| `value?` | `string` \| `number` |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-analytics.ts:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-analytics.ts#L18)
