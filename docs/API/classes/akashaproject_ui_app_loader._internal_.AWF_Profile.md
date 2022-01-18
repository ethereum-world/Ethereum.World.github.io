[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_Profile

# Class: AWF\_Profile

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_Profile

## Implements

- [`AWF_IProfile`](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.AWF_Profile.md#constructor)

### Properties

- [TagSubscriptions](akashaproject_ui_app_loader._internal_.AWF_Profile.md#tagsubscriptions)
- [graphQLDocs](akashaproject_ui_app_loader._internal_.AWF_Profile.md#graphqldocs)

### Methods

- [addProfileProvider](akashaproject_ui_app_loader._internal_.AWF_Profile.md#addprofileprovider)
- [follow](akashaproject_ui_app_loader._internal_.AWF_Profile.md#follow)
- [getFollowers](akashaproject_ui_app_loader._internal_.AWF_Profile.md#getfollowers)
- [getFollowing](akashaproject_ui_app_loader._internal_.AWF_Profile.md#getfollowing)
- [getInterests](akashaproject_ui_app_loader._internal_.AWF_Profile.md#getinterests)
- [getProfile](akashaproject_ui_app_loader._internal_.AWF_Profile.md#getprofile)
- [getTagSubscriptions](akashaproject_ui_app_loader._internal_.AWF_Profile.md#gettagsubscriptions)
- [getTrending](akashaproject_ui_app_loader._internal_.AWF_Profile.md#gettrending)
- [globalSearch](akashaproject_ui_app_loader._internal_.AWF_Profile.md#globalsearch)
- [isFollowing](akashaproject_ui_app_loader._internal_.AWF_Profile.md#isfollowing)
- [isSubscribedToTag](akashaproject_ui_app_loader._internal_.AWF_Profile.md#issubscribedtotag)
- [makeDefaultProvider](akashaproject_ui_app_loader._internal_.AWF_Profile.md#makedefaultprovider)
- [registerUserName](akashaproject_ui_app_loader._internal_.AWF_Profile.md#registerusername)
- [saveMediaFile](akashaproject_ui_app_loader._internal_.AWF_Profile.md#savemediafile)
- [searchProfiles](akashaproject_ui_app_loader._internal_.AWF_Profile.md#searchprofiles)
- [toggleTagSubscription](akashaproject_ui_app_loader._internal_.AWF_Profile.md#toggletagsubscription)
- [unFollow](akashaproject_ui_app_loader._internal_.AWF_Profile.md#unfollow)

## Constructors

### constructor

• **new AWF_Profile**(`log`, `gql`, `auth`, `settings`, `globalChannel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_ui_app_loader._internal_.Logging.md) |
| `gql` | [`Gql`](akashaproject_ui_app_loader._internal_.Gql.md) |
| `auth` | [`AWF_Auth`](akashaproject_ui_app_loader._internal_.AWF_Auth.md) |
| `settings` | [`Settings`](akashaproject_ui_app_loader._internal_.Settings.md) |
| `globalChannel` | [`EventBus`](akashaproject_ui_app_loader._internal_.EventBus.md) |

#### Defined in

[sdk/src/profiles/index.ts:71](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L71)

## Properties

### TagSubscriptions

• `Readonly` **TagSubscriptions**: ``"@TagSubscriptions"``

#### Defined in

[sdk/src/profiles/index.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L52)

___

### graphQLDocs

• `Readonly` **graphQLDocs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AddProfileProvider` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `Follow` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `GetFollowers` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GetFollowing` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GetInterests` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GetProfile` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GlobalSearch` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `IsFollowing` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `MakeDefaultProvider` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `RegisterUsername` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `ResolveProfile` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `SaveMetaData` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `SearchProfiles` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `ToggleInterestSub` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `UnFollow` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[graphQLDocs](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#graphqldocs)

#### Defined in

[sdk/src/profiles/index.ts:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L53)

## Methods

### addProfileProvider

▸ **addProfileProvider**(`opt`): `Observable`<{ `data`: { `addProfileProvider`: `string`  }  }\>

Mutation request to add a profile provider to the profile object

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](../interfaces/akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`Observable`<{ `data`: { `addProfileProvider`: `string`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[addProfileProvider](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#addprofileprovider)

#### Defined in

[sdk/src/profiles/index.ts:89](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L89)

___

### follow

▸ **follow**(`ethAddress`): `Observable`<{ `data`: { `follow`: `boolean`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`Observable`<{ `data`: { `follow`: `boolean`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[follow](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#follow)

#### Defined in

[sdk/src/profiles/index.ts:237](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L237)

___

### getFollowers

▸ **getFollowers**(`pubKey`, `limit`, `offset?`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getFollowers`: [`UserFollowers_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserFollowers_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |
| `limit` | `number` |
| `offset?` | `number` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getFollowers`: [`UserFollowers_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserFollowers_Response.md)  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getFollowers](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getfollowers)

#### Defined in

[sdk/src/profiles/index.ts:534](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L534)

___

### getFollowing

▸ **getFollowing**(`pubKey`, `limit`, `offset?`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getFollowing`: [`UserFollowers_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserFollowers_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |
| `limit` | `number` |
| `offset?` | `number` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getFollowing`: [`UserFollowers_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserFollowers_Response.md)  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getFollowing](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getfollowing)

#### Defined in

[sdk/src/profiles/index.ts:551](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L551)

___

### getInterests

▸ **getInterests**(`pubKey`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getInterests`: `string`[]  }\>

Retrieve subscription list

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getInterests`: `string`[]  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getInterests](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getinterests)

#### Defined in

[sdk/src/profiles/index.ts:566](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L566)

___

### getProfile

▸ **getProfile**(`opt`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getProfile?`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)  } & { `resolveProfile`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.ethAddress?` | `string` |
| `opt.pubKey?` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getProfile?`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)  } & { `resolveProfile`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getprofile)

#### Defined in

[sdk/src/profiles/index.ts:206](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L206)

___

### getTagSubscriptions

▸ **getTagSubscriptions**(): `Observable`<{ `data`: { `getInterests`: `string`[]  }  }\>

#### Returns

`Observable`<{ `data`: { `getInterests`: `string`[]  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getTagSubscriptions](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#gettagsubscriptions)

#### Defined in

[sdk/src/profiles/index.ts:490](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L490)

___

### getTrending

▸ **getTrending**(): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchProfiles`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)[]  }\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchProfiles`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)[]  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[getTrending](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#gettrending)

#### Defined in

[sdk/src/profiles/index.ts:445](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L445)

___

### globalSearch

▸ **globalSearch**(`keyword`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `globalSearch`: [`GlobalSearchResult`](../interfaces/akashaproject_ui_app_loader._internal_.GlobalSearchResult.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyword` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `globalSearch`: [`GlobalSearchResult`](../interfaces/akashaproject_ui_app_loader._internal_.GlobalSearchResult.md)  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[globalSearch](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#globalsearch)

#### Defined in

[sdk/src/profiles/index.ts:517](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L517)

___

### isFollowing

▸ **isFollowing**(`opt`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `isFollowing`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.follower` | `string` |
| `opt.following` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `isFollowing`: `boolean`  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[isFollowing](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#isfollowing)

#### Defined in

[sdk/src/profiles/index.ts:313](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L313)

___

### isSubscribedToTag

▸ **isSubscribedToTag**(`tagName`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[isSubscribedToTag](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#issubscribedtotag)

#### Defined in

[sdk/src/profiles/index.ts:501](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L501)

___

### makeDefaultProvider

▸ **makeDefaultProvider**(`opt`): `Observable`<{ `data`: { `makeDefaultProvider`: `string`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](../interfaces/akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`Observable`<{ `data`: { `makeDefaultProvider`: `string`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[makeDefaultProvider](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#makedefaultprovider)

#### Defined in

[sdk/src/profiles/index.ts:126](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L126)

___

### registerUserName

▸ **registerUserName**(`userName`): `Observable`<{ `data`: { `registerUserName`: `string`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userName` | `string` |

#### Returns

`Observable`<{ `data`: { `registerUserName`: `string`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[registerUserName](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#registerusername)

#### Defined in

[sdk/src/profiles/index.ts:163](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L163)

___

### saveMediaFile

▸ **saveMediaFile**(`data`): `Promise`<{ `CID`: `string` = cid; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } = resized.size }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Object` |
| `data.config?` | `Object` |
| `data.config.autoRotate?` | `boolean` |
| `data.config.maxHeight` | `number` |
| `data.config.maxWidth` | `number` |
| `data.config.mimeType?` | `string` |
| `data.config.quality?` | `number` |
| `data.content` | `any` |
| `data.isUrl?` | `boolean` |
| `data.name?` | `string` |

#### Returns

`Promise`<{ `CID`: `string` = cid; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } = resized.size }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[saveMediaFile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#savemediafile)

#### Defined in

[sdk/src/profiles/index.ts:328](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L328)

___

### searchProfiles

▸ **searchProfiles**(`name`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchProfiles`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)[]  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchProfiles`: [`UserProfile_Response`](../interfaces/akashaproject_ui_app_loader._internal_.UserProfile_Response.md)[]  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[searchProfiles](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#searchprofiles)

#### Defined in

[sdk/src/profiles/index.ts:431](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L431)

___

### toggleTagSubscription

▸ **toggleTagSubscription**(`tagName`): `Observable`<{ `data`: { `toggleInterestSub`: `boolean`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`Observable`<{ `data`: { `toggleInterestSub`: `boolean`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[toggleTagSubscription](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#toggletagsubscription)

#### Defined in

[sdk/src/profiles/index.ts:453](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L453)

___

### unFollow

▸ **unFollow**(`ethAddress`): `Observable`<{ `data`: { `unFollow`: `boolean`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`Observable`<{ `data`: { `unFollow`: `boolean`  }  }\>

#### Implementation of

[AWF_IProfile](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md).[unFollow](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IProfile.md#unfollow)

#### Defined in

[sdk/src/profiles/index.ts:275](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/profiles/index.ts#L275)
