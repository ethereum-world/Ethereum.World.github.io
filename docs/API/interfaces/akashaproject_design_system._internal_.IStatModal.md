[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IStatModal

# Interface: IStatModal

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IStatModal

## Hierarchy

- [`IProfileEntry`](akashaproject_design_system._internal_.IProfileEntry.md)

- [`ITagEntry`](akashaproject_design_system._internal_.ITagEntry.md)

  ↳ **`IStatModal`**

## Table of contents

### Properties

- [activeIndex](akashaproject_design_system._internal_.IStatModal.md#activeindex)
- [buttonLabel](akashaproject_design_system._internal_.IStatModal.md#buttonlabel)
- [className](akashaproject_design_system._internal_.IStatModal.md#classname)
- [errorSubtitleLabel](akashaproject_design_system._internal_.IStatModal.md#errorsubtitlelabel)
- [errorTitleLabel](akashaproject_design_system._internal_.IStatModal.md#errortitlelabel)
- [followLabel](akashaproject_design_system._internal_.IStatModal.md#followlabel)
- [followedProfiles](akashaproject_design_system._internal_.IStatModal.md#followedprofiles)
- [followers](akashaproject_design_system._internal_.IStatModal.md#followers)
- [followersPages](akashaproject_design_system._internal_.IStatModal.md#followerspages)
- [followersReqStatus](akashaproject_design_system._internal_.IStatModal.md#followersreqstatus)
- [following](akashaproject_design_system._internal_.IStatModal.md#following)
- [followingLabel](akashaproject_design_system._internal_.IStatModal.md#followinglabel)
- [followingPages](akashaproject_design_system._internal_.IStatModal.md#followingpages)
- [followingReqStatus](akashaproject_design_system._internal_.IStatModal.md#followingreqstatus)
- [hasNextPage](akashaproject_design_system._internal_.IStatModal.md#hasnextpage)
- [interests](akashaproject_design_system._internal_.IStatModal.md#interests)
- [interestsReqStatus](akashaproject_design_system._internal_.IStatModal.md#interestsreqstatus)
- [ipfsGateway](akashaproject_design_system._internal_.IStatModal.md#ipfsgateway)
- [loadingMoreLabel](akashaproject_design_system._internal_.IStatModal.md#loadingmorelabel)
- [loggedUser](akashaproject_design_system._internal_.IStatModal.md#loggeduser)
- [pages](akashaproject_design_system._internal_.IStatModal.md#pages)
- [placeholderSubtitleLabel](akashaproject_design_system._internal_.IStatModal.md#placeholdersubtitlelabel)
- [placeholderTitleLabel](akashaproject_design_system._internal_.IStatModal.md#placeholdertitlelabel)
- [profileAnchorLink](akashaproject_design_system._internal_.IStatModal.md#profileanchorlink)
- [setActiveIndex](akashaproject_design_system._internal_.IStatModal.md#setactiveindex)
- [stats](akashaproject_design_system._internal_.IStatModal.md#stats)
- [status](akashaproject_design_system._internal_.IStatModal.md#status)
- [subscribeLabel](akashaproject_design_system._internal_.IStatModal.md#subscribelabel)
- [subscribedLabel](akashaproject_design_system._internal_.IStatModal.md#subscribedlabel)
- [subscribedTags](akashaproject_design_system._internal_.IStatModal.md#subscribedtags)
- [tabLabelsArr](akashaproject_design_system._internal_.IStatModal.md#tablabelsarr)
- [tagAnchorLink](akashaproject_design_system._internal_.IStatModal.md#taganchorlink)
- [tags](akashaproject_design_system._internal_.IStatModal.md#tags)
- [titleLabel](akashaproject_design_system._internal_.IStatModal.md#titlelabel)
- [unfollowLabel](akashaproject_design_system._internal_.IStatModal.md#unfollowlabel)
- [unsubscribeLabel](akashaproject_design_system._internal_.IStatModal.md#unsubscribelabel)

### Methods

- [closeModal](akashaproject_design_system._internal_.IStatModal.md#closemodal)
- [handleButtonClick](akashaproject_design_system._internal_.IStatModal.md#handlebuttonclick)
- [handleFollowProfile](akashaproject_design_system._internal_.IStatModal.md#handlefollowprofile)
- [handleSubscribeTag](akashaproject_design_system._internal_.IStatModal.md#handlesubscribetag)
- [handleUnfollowProfile](akashaproject_design_system._internal_.IStatModal.md#handleunfollowprofile)
- [handleUnsubscribeTag](akashaproject_design_system._internal_.IStatModal.md#handleunsubscribetag)
- [loadMoreFollowers](akashaproject_design_system._internal_.IStatModal.md#loadmorefollowers)
- [loadMoreFollowing](akashaproject_design_system._internal_.IStatModal.md#loadmorefollowing)
- [onClickProfile](akashaproject_design_system._internal_.IStatModal.md#onclickprofile)
- [onClickTag](akashaproject_design_system._internal_.IStatModal.md#onclicktag)
- [onLoadMore](akashaproject_design_system._internal_.IStatModal.md#onloadmore)

## Properties

### activeIndex

• **activeIndex**: `number`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L23)

___

### buttonLabel

• **buttonLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L34)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L22)

___

### errorSubtitleLabel

• **errorSubtitleLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L31)

___

### errorTitleLabel

• **errorTitleLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:30](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L30)

___

### followLabel

• **followLabel**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[followLabel](akashaproject_design_system._internal_.IProfileEntry.md#followlabel)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L19)

___

### followedProfiles

• `Optional` **followedProfiles**: `string`[]

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[followedProfiles](akashaproject_design_system._internal_.IProfileEntry.md#followedprofiles)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L17)

___

### followers

• `Optional` **followers**: [`IProfileData`](akashaproject_design_system._internal_.IProfileData.md)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L36)

___

### followersPages

• **followersPages**: [`UserFollowers_Response`](akashaproject_design_system._internal_.UserFollowers_Response.md)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L44)

___

### followersReqStatus

• **followersReqStatus**: [`QueryStatus`](../modules/akashaproject_design_system._internal_.md#querystatus)

#### Defined in

[ui/design/src/components/StatModal/index.tsx:40](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L40)

___

### following

• `Optional` **following**: [`IProfileData`](akashaproject_design_system._internal_.IProfileData.md)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L37)

___

### followingLabel

• **followingLabel**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[followingLabel](akashaproject_design_system._internal_.IProfileEntry.md#followinglabel)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L21)

___

### followingPages

• **followingPages**: [`UserFollowers_Response`](akashaproject_design_system._internal_.UserFollowers_Response.md)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L45)

___

### followingReqStatus

• **followingReqStatus**: [`QueryStatus`](../modules/akashaproject_design_system._internal_.md#querystatus)

#### Defined in

[ui/design/src/components/StatModal/index.tsx:41](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L41)

___

### hasNextPage

• `Optional` **hasNextPage**: `boolean`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[hasNextPage](akashaproject_design_system._internal_.IProfileEntry.md#hasnextpage)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:29](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L29)

___

### interests

• `Optional` **interests**: [`ITag`](akashaproject_design_system._internal_.ITag.md)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L38)

___

### interestsReqStatus

• **interestsReqStatus**: [`QueryStatus`](../modules/akashaproject_design_system._internal_.md#querystatus)

#### Defined in

[ui/design/src/components/StatModal/index.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L42)

___

### ipfsGateway

• `Optional` **ipfsGateway**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[ipfsGateway](akashaproject_design_system._internal_.IProfileEntry.md#ipfsgateway)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L12)

___

### loadingMoreLabel

• `Optional` **loadingMoreLabel**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[loadingMoreLabel](akashaproject_design_system._internal_.IProfileEntry.md#loadingmorelabel)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:30](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L30)

___

### loggedUser

• `Optional` **loggedUser**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[loggedUser](akashaproject_design_system._internal_.IProfileEntry.md#loggeduser)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L15)

___

### pages

• `Optional` **pages**: [`UserFollowers_Response`](akashaproject_design_system._internal_.UserFollowers_Response.md)[]

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[pages](akashaproject_design_system._internal_.IProfileEntry.md#pages)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L27)

___

### placeholderSubtitleLabel

• **placeholderSubtitleLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L33)

___

### placeholderTitleLabel

• **placeholderTitleLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L32)

___

### profileAnchorLink

• **profileAnchorLink**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[profileAnchorLink](akashaproject_design_system._internal_.IProfileEntry.md#profileanchorlink)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L24)

___

### setActiveIndex

• **setActiveIndex**: [`Dispatch`](../modules/akashaproject_design_system._internal_.md#dispatch)<[`SetStateAction`](../modules/akashaproject_design_system._internal_.md#setstateaction)<`number`\>\>

#### Defined in

[ui/design/src/components/StatModal/index.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L24)

___

### stats

• **stats**: (`string` \| `number`)[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L26)

___

### status

• `Optional` **status**: ``"error"`` \| ``"loading"`` \| ``"success"`` \| ``"idle"``

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[status](akashaproject_design_system._internal_.IProfileEntry.md#status)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L28)

___

### subscribeLabel

• **subscribeLabel**: `string`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[subscribeLabel](akashaproject_design_system._internal_.ITagEntry.md#subscribelabel)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L14)

___

### subscribedLabel

• **subscribedLabel**: `string`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[subscribedLabel](akashaproject_design_system._internal_.ITagEntry.md#subscribedlabel)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L16)

___

### subscribedTags

• `Optional` **subscribedTags**: `string`[]

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[subscribedTags](akashaproject_design_system._internal_.ITagEntry.md#subscribedtags)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L12)

___

### tabLabelsArr

• **tabLabelsArr**: `string`[]

#### Defined in

[ui/design/src/components/StatModal/index.tsx:29](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L29)

___

### tagAnchorLink

• **tagAnchorLink**: `string`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[tagAnchorLink](akashaproject_design_system._internal_.ITagEntry.md#taganchorlink)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L19)

___

### tags

• `Optional` **tags**: [`ITag`](akashaproject_design_system._internal_.ITag.md)[]

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[tags](akashaproject_design_system._internal_.ITagEntry.md#tags)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L11)

___

### titleLabel

• **titleLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L28)

___

### unfollowLabel

• **unfollowLabel**: `string`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[unfollowLabel](akashaproject_design_system._internal_.IProfileEntry.md#unfollowlabel)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L20)

___

### unsubscribeLabel

• **unsubscribeLabel**: `string`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[unsubscribeLabel](akashaproject_design_system._internal_.ITagEntry.md#unsubscribelabel)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L15)

## Methods

### closeModal

▸ **closeModal**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L51)

___

### handleButtonClick

▸ **handleButtonClick**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L50)

___

### handleFollowProfile

▸ **handleFollowProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[handleFollowProfile](akashaproject_design_system._internal_.IProfileEntry.md#handlefollowprofile)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L35)

___

### handleSubscribeTag

▸ **handleSubscribeTag**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[handleSubscribeTag](akashaproject_design_system._internal_.ITagEntry.md#handlesubscribetag)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L23)

___

### handleUnfollowProfile

▸ **handleUnfollowProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[handleUnfollowProfile](akashaproject_design_system._internal_.IProfileEntry.md#handleunfollowprofile)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L36)

___

### handleUnsubscribeTag

▸ **handleUnsubscribeTag**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[handleUnsubscribeTag](akashaproject_design_system._internal_.ITagEntry.md#handleunsubscribetag)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L24)

___

### loadMoreFollowers

▸ **loadMoreFollowers**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L47)

___

### loadMoreFollowing

▸ **loadMoreFollowing**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/index.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/index.tsx#L48)

___

### onClickProfile

▸ **onClickProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[onClickProfile](akashaproject_design_system._internal_.IProfileEntry.md#onclickprofile)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L34)

___

### onClickTag

▸ **onClickTag**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Inherited from

[ITagEntry](akashaproject_design_system._internal_.ITagEntry.md).[onClickTag](akashaproject_design_system._internal_.ITagEntry.md#onclicktag)

#### Defined in

[ui/design/src/components/StatModal/tag-entry.tsx:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/tag-entry.tsx#L22)

___

### onLoadMore

▸ `Optional` **onLoadMore**(): `void`

#### Returns

`void`

#### Inherited from

[IProfileEntry](akashaproject_design_system._internal_.IProfileEntry.md).[onLoadMore](akashaproject_design_system._internal_.IProfileEntry.md#onloadmore)

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L31)
