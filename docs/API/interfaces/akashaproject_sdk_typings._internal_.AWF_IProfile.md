[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IProfile

# Interface: AWF\_IProfile

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IProfile

## Table of contents

### Properties

- [graphQLDocs](akashaproject_sdk_typings._internal_.AWF_IProfile.md#graphqldocs)

### Methods

- [addProfileProvider](akashaproject_sdk_typings._internal_.AWF_IProfile.md#addprofileprovider)
- [follow](akashaproject_sdk_typings._internal_.AWF_IProfile.md#follow)
- [getFollowers](akashaproject_sdk_typings._internal_.AWF_IProfile.md#getfollowers)
- [getFollowing](akashaproject_sdk_typings._internal_.AWF_IProfile.md#getfollowing)
- [getInterests](akashaproject_sdk_typings._internal_.AWF_IProfile.md#getinterests)
- [getProfile](akashaproject_sdk_typings._internal_.AWF_IProfile.md#getprofile)
- [getTagSubscriptions](akashaproject_sdk_typings._internal_.AWF_IProfile.md#gettagsubscriptions)
- [getTrending](akashaproject_sdk_typings._internal_.AWF_IProfile.md#gettrending)
- [globalSearch](akashaproject_sdk_typings._internal_.AWF_IProfile.md#globalsearch)
- [isFollowing](akashaproject_sdk_typings._internal_.AWF_IProfile.md#isfollowing)
- [isSubscribedToTag](akashaproject_sdk_typings._internal_.AWF_IProfile.md#issubscribedtotag)
- [makeDefaultProvider](akashaproject_sdk_typings._internal_.AWF_IProfile.md#makedefaultprovider)
- [registerUserName](akashaproject_sdk_typings._internal_.AWF_IProfile.md#registerusername)
- [saveMediaFile](akashaproject_sdk_typings._internal_.AWF_IProfile.md#savemediafile)
- [searchProfiles](akashaproject_sdk_typings._internal_.AWF_IProfile.md#searchprofiles)
- [toggleTagSubscription](akashaproject_sdk_typings._internal_.AWF_IProfile.md#toggletagsubscription)
- [unFollow](akashaproject_sdk_typings._internal_.AWF_IProfile.md#unfollow)

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

[sdk/typings/src/interfaces/profile.ts:4](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L4)

## Methods

### addProfileProvider

▸ **addProfileProvider**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/profile.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L22)

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

[sdk/typings/src/interfaces/profile.ts:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L46)

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

[sdk/typings/src/interfaces/profile.ts:120](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L120)

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

[sdk/typings/src/interfaces/profile.ts:128](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L128)

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

[sdk/typings/src/interfaces/profile.ts:134](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L134)

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

[sdk/typings/src/interfaces/profile.ts:40](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L40)

___

### getTagSubscriptions

▸ **getTagSubscriptions**(): `unknown`

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/profile.ts:100](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L100)

___

### getTrending

▸ **getTrending**(): `unknown`

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/profile.ts:89](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L89)

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

[sdk/typings/src/interfaces/profile.ts:112](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L112)

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

[sdk/typings/src/interfaces/profile.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L58)

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

[sdk/typings/src/interfaces/profile.ts:106](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L106)

___

### makeDefaultProvider

▸ **makeDefaultProvider**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/profile.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L28)

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

[sdk/typings/src/interfaces/profile.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L34)

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

[sdk/typings/src/interfaces/profile.ts:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L64)

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

[sdk/typings/src/interfaces/profile.ts:84](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L84)

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

[sdk/typings/src/interfaces/profile.ts:95](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L95)

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

[sdk/typings/src/interfaces/profile.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/profile.ts#L52)
