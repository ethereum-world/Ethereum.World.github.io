[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEntryCardProps

# Interface: IEntryCardProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEntryCardProps

## Hierarchy

- [`IEntryBoxProps`](akashaproject_design_system._internal_.IEntryBoxProps.md)

  ↳ **`IEntryCardProps`**

## Table of contents

### Properties

- [andLabel](akashaproject_design_system._internal_.IEntryCardProps.md#andlabel)
- [bookmarkLabel](akashaproject_design_system._internal_.IEntryCardProps.md#bookmarklabel)
- [bookmarkedLabel](akashaproject_design_system._internal_.IEntryCardProps.md#bookmarkedlabel)
- [cancelLabel](akashaproject_design_system._internal_.IEntryCardProps.md#cancellabel)
- [className](akashaproject_design_system._internal_.IEntryCardProps.md#classname)
- [comment](akashaproject_design_system._internal_.IEntryCardProps.md#comment)
- [contentClickable](akashaproject_design_system._internal_.IEntryCardProps.md#contentclickable)
- [copyLinkLabel](akashaproject_design_system._internal_.IEntryCardProps.md#copylinklabel)
- [ctaLabel](akashaproject_design_system._internal_.IEntryCardProps.md#ctalabel)
- [disableActions](akashaproject_design_system._internal_.IEntryCardProps.md#disableactions)
- [disableReporting](akashaproject_design_system._internal_.IEntryCardProps.md#disablereporting)
- [disableReposting](akashaproject_design_system._internal_.IEntryCardProps.md#disablereposting)
- [editedLabel](akashaproject_design_system._internal_.IEntryCardProps.md#editedlabel)
- [entryData](akashaproject_design_system._internal_.IEntryCardProps.md#entrydata)
- [flagAsLabel](akashaproject_design_system._internal_.IEntryCardProps.md#flagaslabel)
- [footerTextLabel](akashaproject_design_system._internal_.IEntryCardProps.md#footertextlabel)
- [headerMenuExt](akashaproject_design_system._internal_.IEntryCardProps.md#headermenuext)
- [headerTextLabel](akashaproject_design_system._internal_.IEntryCardProps.md#headertextlabel)
- [hideActionButtons](akashaproject_design_system._internal_.IEntryCardProps.md#hideactionbuttons)
- [hidePublishTime](akashaproject_design_system._internal_.IEntryCardProps.md#hidepublishtime)
- [isBookmarked](akashaproject_design_system._internal_.IEntryCardProps.md#isbookmarked)
- [isFollowingAuthor](akashaproject_design_system._internal_.IEntryCardProps.md#isfollowingauthor)
- [isModerated](akashaproject_design_system._internal_.IEntryCardProps.md#ismoderated)
- [isRemoved](akashaproject_design_system._internal_.IEntryCardProps.md#isremoved)
- [locale](akashaproject_design_system._internal_.IEntryCardProps.md#locale)
- [loggedProfileEthAddress](akashaproject_design_system._internal_.IEntryCardProps.md#loggedprofileethaddress)
- [modalSlotId](akashaproject_design_system._internal_.IEntryCardProps.md#modalslotid)
- [moderatedContentLabel](akashaproject_design_system._internal_.IEntryCardProps.md#moderatedcontentlabel)
- [onClickAvatar](akashaproject_design_system._internal_.IEntryCardProps.md#onclickavatar)
- [othersLabel](akashaproject_design_system._internal_.IEntryCardProps.md#otherslabel)
- [profileAnchorLink](akashaproject_design_system._internal_.IEntryCardProps.md#profileanchorlink)
- [removeEntryLabel](akashaproject_design_system._internal_.IEntryCardProps.md#removeentrylabel)
- [removedByAuthorLabel](akashaproject_design_system._internal_.IEntryCardProps.md#removedbyauthorlabel)
- [removedByMeLabel](akashaproject_design_system._internal_.IEntryCardProps.md#removedbymelabel)
- [repliesAnchorLink](akashaproject_design_system._internal_.IEntryCardProps.md#repliesanchorlink)
- [repliesLabel](akashaproject_design_system._internal_.IEntryCardProps.md#replieslabel)
- [repostLabel](akashaproject_design_system._internal_.IEntryCardProps.md#repostlabel)
- [repostWithCommentLabel](akashaproject_design_system._internal_.IEntryCardProps.md#repostwithcommentlabel)
- [repostedThisLabel](akashaproject_design_system._internal_.IEntryCardProps.md#repostedthislabel)
- [repostsLabel](akashaproject_design_system._internal_.IEntryCardProps.md#repostslabel)
- [rootNodeRef](akashaproject_design_system._internal_.IEntryCardProps.md#rootnoderef)
- [scrollHiddenContent](akashaproject_design_system._internal_.IEntryCardProps.md#scrollhiddencontent)
- [shareLabel](akashaproject_design_system._internal_.IEntryCardProps.md#sharelabel)
- [sharePostLabel](akashaproject_design_system._internal_.IEntryCardProps.md#sharepostlabel)
- [sharePostUrl](akashaproject_design_system._internal_.IEntryCardProps.md#shareposturl)
- [shareTextLabel](akashaproject_design_system._internal_.IEntryCardProps.md#sharetextlabel)
- [showMore](akashaproject_design_system._internal_.IEntryCardProps.md#showmore)
- [style](akashaproject_design_system._internal_.IEntryCardProps.md#style)

### Methods

- [handleFlipCard](akashaproject_design_system._internal_.IEntryCardProps.md#handleflipcard)
- [handleFollowAuthor](akashaproject_design_system._internal_.IEntryCardProps.md#handlefollowauthor)
- [handleUnfollowAuthor](akashaproject_design_system._internal_.IEntryCardProps.md#handleunfollowauthor)
- [onContentClick](akashaproject_design_system._internal_.IEntryCardProps.md#oncontentclick)
- [onEntryBookmark](akashaproject_design_system._internal_.IEntryCardProps.md#onentrybookmark)
- [onEntryFlag](akashaproject_design_system._internal_.IEntryCardProps.md#onentryflag)
- [onEntryRemove](akashaproject_design_system._internal_.IEntryCardProps.md#onentryremove)
- [onMentionClick](akashaproject_design_system._internal_.IEntryCardProps.md#onmentionclick)
- [onRepost](akashaproject_design_system._internal_.IEntryCardProps.md#onrepost)
- [onTagClick](akashaproject_design_system._internal_.IEntryCardProps.md#ontagclick)
- [singleSpaNavigate](akashaproject_design_system._internal_.IEntryCardProps.md#singlespanavigate)

## Properties

### andLabel

• `Optional` **andLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L9)

___

### bookmarkLabel

• `Optional` **bookmarkLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[bookmarkLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#bookmarklabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L59)

___

### bookmarkedLabel

• `Optional` **bookmarkedLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[bookmarkedLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#bookmarkedlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L60)

___

### cancelLabel

• `Optional` **cancelLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[cancelLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#cancellabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L53)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L12)

___

### comment

• `Optional` **comment**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[comment](akashaproject_design_system._internal_.IEntryBoxProps.md#comment)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L58)

___

### contentClickable

• `Optional` **contentClickable**: `boolean`

#### Overrides

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[contentClickable](akashaproject_design_system._internal_.IEntryBoxProps.md#contentclickable)

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L15)

___

### copyLinkLabel

• `Optional` **copyLinkLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[copyLinkLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#copylinklabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L57)

___

### ctaLabel

• `Optional` **ctaLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[ctaLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#ctalabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:65](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L65)

___

### disableActions

• `Optional` **disableActions**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[disableActions](akashaproject_design_system._internal_.IEntryBoxProps.md#disableactions)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:94](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L94)

___

### disableReporting

• `Optional` **disableReporting**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[disableReporting](akashaproject_design_system._internal_.IEntryBoxProps.md#disablereporting)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:93](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L93)

___

### disableReposting

• `Optional` **disableReposting**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[disableReposting](akashaproject_design_system._internal_.IEntryBoxProps.md#disablereposting)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:92](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L92)

___

### editedLabel

• `Optional` **editedLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[editedLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#editedlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L61)

___

### entryData

• **entryData**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[entryData](akashaproject_design_system._internal_.IEntryBoxProps.md#entrydata)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L42)

___

### flagAsLabel

• `Optional` **flagAsLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[flagAsLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#flagaslabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L56)

___

### footerTextLabel

• `Optional` **footerTextLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[footerTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#footertextlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:63](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L63)

___

### headerMenuExt

• `Optional` **headerMenuExt**: [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[headerMenuExt](akashaproject_design_system._internal_.IEntryBoxProps.md#headermenuext)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:103](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L103)

___

### headerTextLabel

• `Optional` **headerTextLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[headerTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#headertextlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:62](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L62)

___

### hideActionButtons

• `Optional` **hideActionButtons**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[hideActionButtons](akashaproject_design_system._internal_.IEntryBoxProps.md#hideactionbuttons)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:95](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L95)

___

### hidePublishTime

• `Optional` **hidePublishTime**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[hidePublishTime](akashaproject_design_system._internal_.IEntryBoxProps.md#hidepublishtime)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:96](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L96)

___

### isBookmarked

• `Optional` **isBookmarked**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[isBookmarked](akashaproject_design_system._internal_.IEntryBoxProps.md#isbookmarked)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L74)

___

### isFollowingAuthor

• `Optional` **isFollowingAuthor**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[isFollowingAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#isfollowingauthor)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:82](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L82)

___

### isModerated

• `Optional` **isModerated**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[isModerated](akashaproject_design_system._internal_.IEntryBoxProps.md#ismoderated)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:98](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L98)

___

### isRemoved

• `Optional` **isRemoved**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[isRemoved](akashaproject_design_system._internal_.IEntryBoxProps.md#isremoved)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:102](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L102)

___

### locale

• **locale**: [`ILocale`](../modules/akashaproject_design_system._internal_.md#ilocale)

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[locale](akashaproject_design_system._internal_.IEntryBoxProps.md#locale)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L43)

___

### loggedProfileEthAddress

• `Optional` **loggedProfileEthAddress**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[loggedProfileEthAddress](akashaproject_design_system._internal_.IEntryBoxProps.md#loggedprofileethaddress)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L44)

___

### modalSlotId

• **modalSlotId**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[modalSlotId](akashaproject_design_system._internal_.IEntryBoxProps.md#modalslotid)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:104](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L104)

___

### moderatedContentLabel

• `Optional` **moderatedContentLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[moderatedContentLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#moderatedcontentlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L64)

___

### onClickAvatar

• `Optional` **onClickAvatar**: [`MouseEventHandler`](../modules/akashaproject_design_system._internal_.md#mouseeventhandler)<`HTMLDivElement`\>

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onClickAvatar](akashaproject_design_system._internal_.IEntryBoxProps.md#onclickavatar)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:76](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L76)

___

### othersLabel

• `Optional` **othersLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L10)

___

### profileAnchorLink

• `Optional` **profileAnchorLink**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[profileAnchorLink](akashaproject_design_system._internal_.IEntryBoxProps.md#profileanchorlink)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:71](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L71)

___

### removeEntryLabel

• `Optional` **removeEntryLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[removeEntryLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removeentrylabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:100](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L100)

___

### removedByAuthorLabel

• `Optional` **removedByAuthorLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[removedByAuthorLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removedbyauthorlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:67](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L67)

___

### removedByMeLabel

• `Optional` **removedByMeLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[removedByMeLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#removedbymelabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:66](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L66)

___

### repliesAnchorLink

• `Optional` **repliesAnchorLink**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[repliesAnchorLink](akashaproject_design_system._internal_.IEntryBoxProps.md#repliesanchorlink)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L72)

___

### repliesLabel

• **repliesLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[repliesLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#replieslabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L50)

___

### repostLabel

• `Optional` **repostLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[repostLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L52)

___

### repostWithCommentLabel

• `Optional` **repostWithCommentLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[repostWithCommentLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostwithcommentlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L54)

___

### repostedThisLabel

• `Optional` **repostedThisLabel**: `string`

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:8](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L8)

___

### repostsLabel

• **repostsLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[repostsLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#repostslabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L51)

___

### rootNodeRef

• `Optional` **rootNodeRef**: [`Ref`](../modules/akashaproject_design_system._internal_.md#ref)<`HTMLDivElement`\>

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L14)

___

### scrollHiddenContent

• `Optional` **scrollHiddenContent**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[scrollHiddenContent](akashaproject_design_system._internal_.IEntryBoxProps.md#scrollhiddencontent)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:99](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L99)

___

### shareLabel

• `Optional` **shareLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[shareLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharelabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L55)

___

### sharePostLabel

• `Optional` **sharePostLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[sharePostLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharepostlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L46)

___

### sharePostUrl

• `Optional` **sharePostUrl**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[sharePostUrl](akashaproject_design_system._internal_.IEntryBoxProps.md#shareposturl)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L48)

___

### shareTextLabel

• `Optional` **shareTextLabel**: `string`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[shareTextLabel](akashaproject_design_system._internal_.IEntryBoxProps.md#sharetextlabel)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L47)

___

### showMore

• **showMore**: `boolean`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[showMore](akashaproject_design_system._internal_.IEntryBoxProps.md#showmore)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:69](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L69)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Overrides

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[style](akashaproject_design_system._internal_.IEntryBoxProps.md#style)

#### Defined in

[ui/design/src/components/EntryCard/index.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/index.tsx#L13)

## Methods

### handleFlipCard

▸ `Optional` **handleFlipCard**(): `void`

#### Returns

`void`

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[handleFlipCard](akashaproject_design_system._internal_.IEntryBoxProps.md#handleflipcard)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[handleFollowAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#handlefollowauthor)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[handleUnfollowAuthor](akashaproject_design_system._internal_.IEntryBoxProps.md#handleunfollowauthor)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onContentClick](akashaproject_design_system._internal_.IEntryBoxProps.md#oncontentclick)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onEntryBookmark](akashaproject_design_system._internal_.IEntryBoxProps.md#onentrybookmark)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onEntryFlag](akashaproject_design_system._internal_.IEntryBoxProps.md#onentryflag)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onEntryRemove](akashaproject_design_system._internal_.IEntryBoxProps.md#onentryremove)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onMentionClick](akashaproject_design_system._internal_.IEntryBoxProps.md#onmentionclick)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onRepost](akashaproject_design_system._internal_.IEntryBoxProps.md#onrepost)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[onTagClick](akashaproject_design_system._internal_.IEntryBoxProps.md#ontagclick)

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

#### Inherited from

[IEntryBoxProps](akashaproject_design_system._internal_.IEntryBoxProps.md).[singleSpaNavigate](akashaproject_design_system._internal_.IEntryBoxProps.md#singlespanavigate)

#### Defined in

[ui/design/src/components/EntryCard/entry-box.tsx:89](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EntryCard/entry-box.tsx#L89)
