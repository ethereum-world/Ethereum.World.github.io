[AWF](../README.md) / [Modules](../modules.md) / @akashaproject/ui-awf-typings

# Module: @akashaproject/ui-awf-typings

## Table of contents

### Namespaces

- [&lt;internal\&gt;](akashaproject_ui_awf_typings._internal_.md)

### Enumerations

- [AUTH\_EVENTS](../enums/akashaproject_ui_awf_typings.AUTH_EVENTS.md)
- [ButtonValues](../enums/akashaproject_ui_awf_typings.ButtonValues.md)
- [COMMENTS\_EVENTS](../enums/akashaproject_ui_awf_typings.COMMENTS_EVENTS.md)
- [ENS\_EVENTS](../enums/akashaproject_ui_awf_typings.ENS_EVENTS.md)
- [ENTRY\_EVENTS](../enums/akashaproject_ui_awf_typings.ENTRY_EVENTS.md)
- [EthProviders](../enums/akashaproject_ui_awf_typings.EthProviders.md)
- [LEGAL\_DOCS](../enums/akashaproject_ui_awf_typings.LEGAL_DOCS.md)
- [LogoTypeSource](../enums/akashaproject_ui_awf_typings.LogoTypeSource.md)
- [ModerationItemTypes](../enums/akashaproject_ui_awf_typings.ModerationItemTypes.md)
- [PROFILE\_EVENTS](../enums/akashaproject_ui_awf_typings.PROFILE_EVENTS.md)
- [TAG\_EVENTS](../enums/akashaproject_ui_awf_typings.TAG_EVENTS.md)
- [WEB3\_EVENTS](../enums/akashaproject_ui_awf_typings.WEB3_EVENTS.md)

### Interfaces

- [IAkashaError](../interfaces/akashaproject_ui_awf_typings.IAkashaError.md)
- [LogoSourceType](../interfaces/akashaproject_ui_awf_typings.LogoSourceType.md)
- [NavigationOptions](../interfaces/akashaproject_ui_awf_typings.NavigationOptions.md)
- [QueryStringType](../interfaces/akashaproject_ui_awf_typings.QueryStringType.md)
- [RootComponentProps](../interfaces/akashaproject_ui_awf_typings.RootComponentProps.md)

### Type aliases

- [AppNameSelector](akashaproject_ui_awf_typings.md#appnameselector)
- [Awaited](akashaproject_ui_awf_typings.md#awaited)
- [NavigationFn](akashaproject_ui_awf_typings.md#navigationfn)
- [PathNameSelector](akashaproject_ui_awf_typings.md#pathnameselector)
- [QueryStatus](akashaproject_ui_awf_typings.md#querystatus)

## Type aliases

### AppNameSelector

Ƭ **AppNameSelector**: (`apps`: [`IAppConfig`](../interfaces/akashaproject_ui_awf_typings._internal_.IAppConfig.md)[]) => `string`

#### Type declaration

▸ (`apps`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `apps` | [`IAppConfig`](../interfaces/akashaproject_ui_awf_typings._internal_.IAppConfig.md)[] |

##### Returns

`string`

#### Defined in

[ui/typings/src/index.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L27)

___

### Awaited

Ƭ **Awaited**<`T`\>: `T` extends [`PromiseLike`](../interfaces/akashaproject_ui_awf_typings._internal_.PromiseLike.md)<infer U\> ? [`Awaited`](akashaproject_ui_awf_typings.md#awaited)<`U`\> : `T`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Defined in

[ui/typings/src/index.ts:82](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L82)

___

### NavigationFn

Ƭ **NavigationFn**: (`stringfyFn`: (`obj`: `unknown`) => `string`, `currentRedirect?`: `string`) => `string`

#### Type declaration

▸ (`stringfyFn`, `currentRedirect?`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `stringfyFn` | (`obj`: `unknown`) => `string` |
| `currentRedirect?` | `string` |

##### Returns

`string`

#### Defined in

[ui/typings/src/index.ts:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L36)

___

### PathNameSelector

Ƭ **PathNameSelector**: (`appRoutes`: [`IAppConfig`](../interfaces/akashaproject_ui_awf_typings._internal_.IAppConfig.md)[``"routes"``]) => `string`

#### Type declaration

▸ (`appRoutes`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `appRoutes` | [`IAppConfig`](../interfaces/akashaproject_ui_awf_typings._internal_.IAppConfig.md)[``"routes"``] |

##### Returns

`string`

#### Defined in

[ui/typings/src/index.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L28)

___

### QueryStatus

Ƭ **QueryStatus**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `error?` | ``null`` \| `unknown` |
| `hasNextPage?` | `boolean` |
| `isError?` | `boolean` |
| `isFetched?` | `boolean` |
| `isFetchedAfterMount?` | `boolean` |
| `isFetching?` | `boolean` |
| `isIdle?` | `boolean` |
| `isLoading?` | `boolean` |
| `isLoadingError?` | `boolean` |
| `isPlaceholderData?` | `boolean` |
| `isPreviousData?` | `boolean` |
| `isRefetchError?` | `boolean` |
| `isStale?` | `boolean` |
| `isSuccess?` | `boolean` |
| `status?` | ``"idle"`` \| ``"loading"`` \| ``"success"`` \| ``"error"`` |

#### Defined in

[ui/typings/src/index.ts:84](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L84)
