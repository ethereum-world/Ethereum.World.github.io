[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEntryBoxProps

# Interface: IEntryBoxProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEntryBoxProps

## Hierarchy

- **`IEntryBoxProps`**

  ↳ [`IEntryCardProps`](akashaproject_design_system._internal_.IEntryCardProps.md)

## Table of contents

### Properties

- [bookmarkLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#bookmarklabel)
- [bookmarkedLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#bookmarkedlabel)
- [cancelLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#cancellabel)
- [comment](akashaproject_design_system._internal_.IEntryBoxProps.md#comment)
- [contentClickable](akashaproject_design_system._internal_.IEntryBoxProps.md#contentclickable)
- [copyLinkLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#copylinklabel)
- [ctaLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#ctalabel)
- [disableActions](akashaproject_design_system._internal_.IEntryBoxProps.md#disableactions)
- [disableReporting](akashaproject_design_system._internal_.IEntryBoxProps.md#disablereporting)
- [disableReposting](akashaproject_design_system._internal_.IEntryBoxProps.md#disablereposting)
- [editedLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#editedlabel)
- [entryData](akashaproject_design_system._internal_.IEntryBoxProps.md#entrydata)
- [flagAsLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#flagaslabel)
- [footerTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#footertextlabel)
- [headerMenuExt](akashaproject_design_system._internal_.IEntryBoxProps.md#headermenuext)
- [headerTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#headertextlabel)
- [hideActionButtons](akashaproject_design_system._internal_.IEntryBoxProps.md#hideactionbuttons)
- [hidePublishTime](akashaproject_design_system._internal_.IEntryBoxProps.md#hidepublishtime)
- [isBookmarked](akashaproject_design_system._internal_.IEntryBoxProps.md#isbookmarked)
- [isFollowingAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#isfollowingauthor)
- [isModerated](akashaproject_design_system._internal_.IEntryBoxProps.md#ismoderated)
- [isRemoved](akashaproject_design_system._internal_.IEntryBoxProps.md#isremoved)
- [locale](akashaproject_design_system._internal_.IEntryBoxProps.md#locale)
- [loggedProfileEthAddress](akashaproject_design_system._internal_.IEntryBoxProps.md#loggedprofileethaddress)
- [modalSlotId](akashaproject_design_system._internal_.IEntryBoxProps.md#modalslotid)
- [moderatedContentLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#moderatedcontentlabel)
- [onClickAvatar](akashaproject_design_system._internal_.IEntryBoxProps.md#onclickavatar)
- [profileAnchorLink](akashaproject_design_system._internal_.IEntryBoxProps.md#profileanchorlink)
- [removeEntryLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removeentrylabel)
- [removedByAuthorLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removedbyauthorlabel)
- [removedByMeLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removedbymelabel)
- [repliesAnchorLink](akashaproject_design_system._internal_.IEntryBoxProps.md#repliesanchorlink)
- [repliesLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#replieslabel)
- [repostLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostlabel)
- [repostWithCommentLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostwithcommentlabel)
- [repostsLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostslabel)
- [scrollHiddenContent](akashaproject_design_system._internal_.IEntryBoxProps.md#scrollhiddencontent)
- [shareLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharelabel)
- [sharePostLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharepostlabel)
- [sharePostUrl](akashaproject_design_system._internal_.IEntryBoxProps.md#shareposturl)
- [shareTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharetextlabel)
- [showMore](akashaproject_design_system._internal_.IEntryBoxProps.md#showmore)
- [style](akashaproject_design_system._internal_.IEntryBoxProps.md#style)

### Methods

- [handleFlipCard](akashaproject_design_system._internal_.IEntryBoxProps.md#handleflipcard)
- [handleFollowAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#handlefollowauthor)
- [handleUnfollowAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#handleunfollowauthor)
- [onContentClick](akashaproject_design_system._internal_.IEntryBoxProps.md#oncontentclick)
- [onEntryBookmark](akashaproject_design_system._internal_.IEntryBoxProps.md#onentrybookmark)
- [onEntryFlag](akashaproject_design_system._internal_.IEntryBoxProps.md#onentryflag)
- [onEntryRemove](akashaproject_design_system._internal_.IEntryBoxProps.md#onentryremove)
- [onMentionClick](akashaproject_design_system._internal_.IEntryBoxProps.md#onmentionclick)
- [onRepost](akashaproject_design_system._internal_.IEntryBoxProps.md#onrepost)
- [onTagClick](akashaproject_design_system._internal_.IEntryBoxProps.md#ontagclick)
- [singleSpaNavigate](akashaproject_design_system._internal_.IEntryBoxProps.md#singlespanavigate)

## Properties

### bookmarkLabel

• `Optional` **bookmarkLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L59)

___

### bookmarkedLabel

• `Optional` **bookmarkedLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L60)

___

### cancelLabel

• `Optional` **cancelLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L53)

___

### comment

• `Optional` **comment**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L58)

___

### contentClickable

• `Optional` **contentClickable**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:86](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L86)

___

### copyLinkLabel

• `Optional` **copyLinkLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L57)

___

### ctaLabel

• `Optional` **ctaLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:65](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L65)

___

### disableActions

• `Optional` **disableActions**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:94](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L94)

___

### disableReporting

• `Optional` **disableReporting**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:93](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L93)

___

### disableReposting

• `Optional` **disableReposting**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:92](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L92)

___

### editedLabel

• `Optional` **editedLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L61)

___

### entryData

• **entryData**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L42)

___

### flagAsLabel

• `Optional` **flagAsLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L56)

___

### footerTextLabel

• `Optional` **footerTextLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:63](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L63)

___

### headerMenuExt

• `Optional` **headerMenuExt**: [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:103](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L103)

___

### headerTextLabel

• `Optional` **headerTextLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:62](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L62)

___

### hideActionButtons

• `Optional` **hideActionButtons**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:95](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L95)

___

### hidePublishTime

• `Optional` **hidePublishTime**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:96](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L96)

___

### isBookmarked

• `Optional` **isBookmarked**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L74)

___

### isFollowingAuthor

• `Optional` **isFollowingAuthor**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:82](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L82)

___

### isModerated

• `Optional` **isModerated**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:98](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L98)

___

### isRemoved

• `Optional` **isRemoved**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:102](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L102)

___

### locale

• **locale**: [`ILocale`](../modules/akashaproject_design_system._internal_.md#ilocale)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L43)

___

### loggedProfileEthAddress

• `Optional` **loggedProfileEthAddress**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L44)

___

### modalSlotId

• **modalSlotId**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:104](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L104)

___

### moderatedContentLabel

• `Optional` **moderatedContentLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L64)

___

### onClickAvatar

• `Optional` **onClickAvatar**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:76](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L76)

___

### profileAnchorLink

• `Optional` **profileAnchorLink**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:71](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L71)

___

### removeEntryLabel

• `Optional` **removeEntryLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:100](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L100)

___

### removedByAuthorLabel

• `Optional` **removedByAuthorLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:67](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L67)

___

### removedByMeLabel

• `Optional` **removedByMeLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:66](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L66)

___

### repliesAnchorLink

• `Optional` **repliesAnchorLink**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L72)

___

### repliesLabel

• **repliesLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L50)

___

### repostLabel

• `Optional` **repostLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L52)

___

### repostWithCommentLabel

• `Optional` **repostWithCommentLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L54)

___

### repostsLabel

• **repostsLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L51)

___

### scrollHiddenContent

• `Optional` **scrollHiddenContent**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:99](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L99)

___

### shareLabel

• `Optional` **shareLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L55)

___

### sharePostLabel

• `Optional` **sharePostLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L46)

___

### sharePostUrl

• `Optional` **sharePostUrl**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L48)

___

### shareTextLabel

• `Optional` **shareTextLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L47)

___

### showMore

• **showMore**: `boolean`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:69](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L69)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:91](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L91)

## Methods

### handleFlipCard

▸ `Optional` **handleFlipCard**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:97](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L97)

___

### handleFollowAuthor

▸ `Optional` **handleFollowAuthor**(`profileEthAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `profileEthAddress` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L80)

___

### handleUnfollowAuthor

▸ `Optional` **handleUnfollowAuthor**(`profileEthAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `profileEthAddress` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:81](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L81)

___

### onContentClick

▸ `Optional` **onContentClick**(`details`, `itemType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `details` | [`IContentClickDetails`](akashaproject_design_system._internal_.IContentClickDetails.md) |
| `itemType?` | [`ItemTypes`](../enums/akashaproject_design_system._internal_.ItemTypes.md) |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:84](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L84)

___

### onEntryBookmark

▸ `Optional` **onEntryBookmark**(`entryId`, `isBookmarked?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryId` | `string` |
| `isBookmarked?` | `boolean` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L75)

___

### onEntryFlag

▸ `Optional` **onEntryFlag**(`entryId?`, `itemType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryId?` | `string` |
| `itemType?` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:78](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L78)

___

### onEntryRemove

▸ `Optional` **onEntryRemove**(`entryId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryId` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:101](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L101)

___

### onMentionClick

▸ `Optional` **onMentionClick**(`pubKey`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pubKey` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:87](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L87)

___

### onRepost

▸ `Optional` **onRepost**(`withComment`, `entryId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `withComment` | `boolean` |
| `entryId` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:77](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L77)

___

### onTagClick

▸ `Optional` **onTagClick**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:88](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L88)

___

### singleSpaNavigate

▸ `Optional` **singleSpaNavigate**(`url`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:89](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L89)
