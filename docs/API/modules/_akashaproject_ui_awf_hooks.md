[AWF](../README.md) / [Exports](../modules.md) / @akashaproject/ui-awf-hooks

# Module: @akashaproject/ui-awf-hooks

## Table of contents

### Properties

- [constants](_akashaproject_ui_awf_hooks.md#constants)
- [moderationRequest](_akashaproject_ui_awf_hooks.md#moderationrequest)

### Functions

- [useAnalytics](_akashaproject_ui_awf_hooks.md#useanalytics)
- [useENSRegistration](_akashaproject_ui_awf_hooks.md#useensregistration)
- [useErrors](_akashaproject_ui_awf_hooks.md#useerrors)
- [useGlobalLogin](_akashaproject_ui_awf_hooks.md#usegloballogin)
- [useLoginState](_akashaproject_ui_awf_hooks.md#useloginstate)
- [useReasons](_akashaproject_ui_awf_hooks.md#usereasons)
- [useSignData](_akashaproject_ui_awf_hooks.md#usesigndata)
- [withProviders](_akashaproject_ui_awf_hooks.md#withproviders)

## Properties

### constants

• **constants**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `BASE_DECISION_URL` | `string` |
| `BASE_MODERATOR_URL` | `string` |
| `BASE_REASONS_URL` | `string` |
| `BASE_REPORT_URL` | `string` |
| `BASE_STATUS_URL` | `string` |

___

### moderationRequest

• **moderationRequest**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `checkModerator` | (`loggedUser`: `string`) => `Promise`<`any`\> |
| `checkStatus` | (`isBatch`: `boolean`, `data`: `Record`<`string`, `unknown`\>, `entryId?`: `string`) => `Promise`<`any`\> |
| `getAllModerated` | () => `Promise`<`any`\> |
| `getAllPending` | () => `Promise`<`any`\> |
| `getCount` | () => `Promise`<`any`\> |
| `getFlags` | (`entryId`: `string`) => `Promise`<`any`\> |
| `getLog` | (`data?`: { `limit?`: `number` ; `offset?`: `string`  }) => `Promise`<`any`\> |

## Functions

### useAnalytics

▸ `Const` **useAnalytics**(): [`UseAnalyticsState`, `UseAnalyticsActions`]

#### Returns

[`UseAnalyticsState`, `UseAnalyticsActions`]

#### Defined in

[ui/hooks/src/use-analytics.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-analytics.ts#L28)

___

### useENSRegistration

▸ `Const` **useENSRegistration**(`props`): [`UseENSRegistrationState`, `UseENSRegistrationActions`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseENSRegistrationProps` |

#### Returns

[`UseENSRegistrationState`, `UseENSRegistrationActions`]

#### Defined in

[ui/hooks/src/use-ens-registration.ts:216](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-ens-registration.ts#L216)

___

### useErrors

▸ `Const` **useErrors**(`props`): [`ErrorState`, `ErrorActions`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseErrorStateProps` |

#### Returns

[`ErrorState`, `ErrorActions`]

#### Defined in

[ui/hooks/src/use-error-state.ts:16](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-error-state.ts#L16)

___

### useGlobalLogin

▸ `Const` **useGlobalLogin**(`props`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseGlobalLoginProps` |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-global-login.ts:24](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-global-login.ts#L24)

___

### useLoginState

▸ `Const` **useLoginState**(`props`): [`ILoginState`, `UseLoginActions`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseLoginProps` |

#### Returns

[`ILoginState`, `UseLoginActions`]

#### Defined in

[ui/hooks/src/use-login-state.ts:97](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-login-state.ts#L97)

___

### useReasons

▸ `Const` **useReasons**(`props`): [`string`[], `UseReasonsActions`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseReasonsProps` |

#### Returns

[`string`[], `UseReasonsActions`]

#### Defined in

[ui/hooks/src/use-reasons.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-reasons.ts#L48)

___

### useSignData

▸ `Const` **useSignData**(`props`): [{ `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }, `UseSignDataActions`]

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `UseSignDataProps` |

#### Returns

[{ `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }, `UseSignDataActions`]

#### Defined in

[ui/hooks/src/use-sign-data.ts:74](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/use-sign-data.ts#L74)

___

### withProviders

▸ **withProviders**<`T`\>(`WrappedComponent`): (`props`: `any`) => `Element`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `WrappedComponent` | `React.ComponentType`<`T`\> |

#### Returns

`fn`

▸ (`props`): `Element`

##### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `any` |

##### Returns

`Element`

| Name | Type |
| :------ | :------ |
| `displayName` | `string` |

#### Defined in

[ui/hooks/src/utils/provider-hoc.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/hooks/src/utils/provider-hoc.tsx#L9)
