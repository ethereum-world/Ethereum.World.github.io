[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IProfileWidgetCard

# Interface: IProfileWidgetCard

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IProfileWidgetCard

## Hierarchy

- **`IProfileWidgetCard`**

  ↳ [`IProfileCardProps`](akashaproject_design_system._internal_.IProfileCardProps.md)

## Table of contents

### Properties

- [className](akashaproject_design_system._internal_.IProfileWidgetCard.md#classname)
- [descriptionLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#descriptionlabel)
- [followLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#followlabel)
- [followersLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#followerslabel)
- [followingLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#followinglabel)
- [handleFollow](akashaproject_design_system._internal_.IProfileWidgetCard.md#handlefollow)
- [handleUnfollow](akashaproject_design_system._internal_.IProfileWidgetCard.md#handleunfollow)
- [interestsLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#interestslabel)
- [isFollowing](akashaproject_design_system._internal_.IProfileWidgetCard.md#isfollowing)
- [loggedEthAddress](akashaproject_design_system._internal_.IProfileWidgetCard.md#loggedethaddress)
- [onClickFollowers](akashaproject_design_system._internal_.IProfileWidgetCard.md#onclickfollowers)
- [onClickFollowing](akashaproject_design_system._internal_.IProfileWidgetCard.md#onclickfollowing)
- [onClickInterests](akashaproject_design_system._internal_.IProfileWidgetCard.md#onclickinterests)
- [onClickPosts](akashaproject_design_system._internal_.IProfileWidgetCard.md#onclickposts)
- [onClickProfile](akashaproject_design_system._internal_.IProfileWidgetCard.md#onclickprofile)
- [postsLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#postslabel)
- [profileAnchorLink](akashaproject_design_system._internal_.IProfileWidgetCard.md#profileanchorlink)
- [profileData](akashaproject_design_system._internal_.IProfileWidgetCard.md#profiledata)
- [shareProfileLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#shareprofilelabel)
- [unfollowLabel](akashaproject_design_system._internal_.IProfileWidgetCard.md#unfollowlabel)

## Properties

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L38)

___

### descriptionLabel

• **descriptionLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L49)

___

### followLabel

• `Optional` **followLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L54)

___

### followersLabel

• **followersLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L53)

___

### followingLabel

• **followingLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L52)

___

### handleFollow

• `Optional` **handleFollow**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L46)

___

### handleUnfollow

• `Optional` **handleUnfollow**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L45)

___

### interestsLabel

• `Optional` **interestsLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L51)

___

### isFollowing

• `Optional` **isFollowing**: `boolean`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L47)

___

### loggedEthAddress

• `Optional` **loggedEthAddress**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L39)

___

### onClickFollowers

• `Optional` **onClickFollowers**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:41](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L41)

___

### onClickFollowing

• `Optional` **onClickFollowing**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L42)

___

### onClickInterests

• `Optional` **onClickInterests**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L44)

___

### onClickPosts

• `Optional` **onClickPosts**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L43)

___

### onClickProfile

• `Optional` **onClickProfile**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:40](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L40)

___

### postsLabel

• **postsLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L50)

___

### profileAnchorLink

• `Optional` **profileAnchorLink**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L58)

___

### profileData

• **profileData**: [`IProfileData`](akashaproject_design_system._internal_.IProfileData.md)

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L48)

___

### shareProfileLabel

• **shareProfileLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L56)

___

### unfollowLabel

• `Optional` **unfollowLabel**: `string`

#### Defined in

[ui/design/src/components/ProfileCard/profile-widget-card.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/ProfileCard/profile-widget-card.tsx#L55)
