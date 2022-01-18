[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_IProfile

# Interface: AWF\_IProfile

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_IProfile

## Implemented by

- [`AWF_Profile`](../classes/akashaproject_ui_app_loader._internal_.AWF_Profile.md)

## Table of contents

### Properties

- [graphQLDocs](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#graphqldocs)

### Methods

- [addProfileProvider](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#addprofileprovider)
- [follow](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#follow)
- [getFollowers](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getfollowers)
- [getFollowing](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getfollowing)
- [getInterests](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getinterests)
- [getProfile](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#getprofile)
- [getTagSubscriptions](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#gettagsubscriptions)
- [getTrending](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#gettrending)
- [globalSearch](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#globalsearch)
- [isFollowing](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#isfollowing)
- [isSubscribedToTag](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#issubscribedtotag)
- [makeDefaultProvider](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#makedefaultprovider)
- [registerUserName](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#registerusername)
- [saveMediaFile](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#savemediafile)
- [searchProfiles](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#searchprofiles)
- [toggleTagSubscription](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#toggletagsubscription)
- [unFollow](akashaproject_ui_app_loader._internal_.AWF_IProfile.md#unfollow)

## Properties

### graphQLDocs

• **graphQLDocs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AddProfileProvider` | `any` |
| `Follow` | `any` |
| `GetProfile` | `any` |
| `GlobalSearch` | `any` |
| `IsFollowing` | `any` |
| `MakeDefaultProvider` | `any` |
| `RegisterUsername` | `any` |
| `ResolveProfile` | `any` |
| `SaveMetaData` | `any` |
| `SearchProfiles` | `any` |
| `UnFollow` | `any` |

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:4

## Methods

### addProfileProvider

▸ **addProfileProvider**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:21

___

### follow

▸ **follow**(`ethAddress`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:45

___

### getFollowers

▸ **getFollowers**(`pubKey`, `limit`, `offset?`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |
| `limit` | `number` |
| `offset?` | `number` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:117

___

### getFollowing

▸ **getFollowing**(`pubKey`, `limit`, `offset?`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |
| `limit` | `number` |
| `offset?` | `number` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:124

___

### getInterests

▸ **getInterests**(`pubKey`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:129

___

### getProfile

▸ **getProfile**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.ethAddress?` | `string` |
| `opt.fields?` | `string`[] |
| `opt.pubKey?` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:36

___

### getTagSubscriptions

▸ **getTagSubscriptions**(): `unknown`

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:100

___

### getTrending

▸ **getTrending**(): `unknown`

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:91

___

### globalSearch

▸ **globalSearch**(`keyword`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `keyword` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:110

___

### isFollowing

▸ **isFollowing**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.follower` | `string` |
| `opt.following` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:55

___

### isSubscribedToTag

▸ **isSubscribedToTag**(`tagName`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:105

___

### makeDefaultProvider

▸ **makeDefaultProvider**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:26

___

### registerUserName

▸ **registerUserName**(`userName`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `userName` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:31

___

### saveMediaFile

▸ **saveMediaFile**(`data`): `Promise`<{ `CID`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  }  }\>

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

`Promise`<{ `CID`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  }  }\>

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:63

___

### searchProfiles

▸ **searchProfiles**(`name`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:87

___

### toggleTagSubscription

▸ **toggleTagSubscription**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:96

___

### unFollow

▸ **unFollow**(`ethAddress`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/profile.d.ts:50
