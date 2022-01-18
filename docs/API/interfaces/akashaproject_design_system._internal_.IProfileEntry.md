[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IProfileEntry

# Interface: IProfileEntry

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IProfileEntry

## Hierarchy

- **`IProfileEntry`**

  ↳ [`IStatModal`](akashaproject_design_system._internal_.IStatModal.md)

## Table of contents

### Properties

- [followLabel](akashaproject_design_system._internal_.IProfileEntry.md#followlabel)
- [followedProfiles](akashaproject_design_system._internal_.IProfileEntry.md#followedprofiles)
- [followingLabel](akashaproject_design_system._internal_.IProfileEntry.md#followinglabel)
- [hasNextPage](akashaproject_design_system._internal_.IProfileEntry.md#hasnextpage)
- [ipfsGateway](akashaproject_design_system._internal_.IProfileEntry.md#ipfsgateway)
- [loadingMoreLabel](akashaproject_design_system._internal_.IProfileEntry.md#loadingmorelabel)
- [loggedUser](akashaproject_design_system._internal_.IProfileEntry.md#loggeduser)
- [pages](akashaproject_design_system._internal_.IProfileEntry.md#pages)
- [profileAnchorLink](akashaproject_design_system._internal_.IProfileEntry.md#profileanchorlink)
- [status](akashaproject_design_system._internal_.IProfileEntry.md#status)
- [unfollowLabel](akashaproject_design_system._internal_.IProfileEntry.md#unfollowlabel)

### Methods

- [handleFollowProfile](akashaproject_design_system._internal_.IProfileEntry.md#handlefollowprofile)
- [handleUnfollowProfile](akashaproject_design_system._internal_.IProfileEntry.md#handleunfollowprofile)
- [onClickProfile](akashaproject_design_system._internal_.IProfileEntry.md#onclickprofile)
- [onLoadMore](akashaproject_design_system._internal_.IProfileEntry.md#onloadmore)

## Properties

### followLabel

• **followLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L19)

___

### followedProfiles

• `Optional` **followedProfiles**: `string`[]

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L17)

___

### followingLabel

• **followingLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L21)

___

### hasNextPage

• `Optional` **hasNextPage**: `boolean`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:29](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L29)

___

### ipfsGateway

• `Optional` **ipfsGateway**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L12)

___

### loadingMoreLabel

• `Optional` **loadingMoreLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:30](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L30)

___

### loggedUser

• `Optional` **loggedUser**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L15)

___

### pages

• `Optional` **pages**: [`UserFollowers_Response`](akashaproject_design_system._internal_.UserFollowers_Response.md)[]

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L27)

___

### profileAnchorLink

• **profileAnchorLink**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L24)

___

### status

• `Optional` **status**: ``"error"`` \| ``"loading"`` \| ``"success"`` \| ``"idle"``

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L28)

___

### unfollowLabel

• **unfollowLabel**: `string`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L20)

## Methods

### handleFollowProfile

▸ **handleFollowProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L35)

___

### handleUnfollowProfile

▸ **handleUnfollowProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L36)

___

### onClickProfile

▸ **onClickProfile**(`ethAddress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L34)

___

### onLoadMore

▸ `Optional` **onLoadMore**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/StatModal/profile-entry.tsx:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/StatModal/profile-entry.tsx#L31)
