[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ITagSearchCard

# Interface: ITagSearchCard

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ITagSearchCard

## Table of contents

### Properties

- [loggedEthAddress](akashaproject_design_system._internal_.ITagSearchCard.md#loggedethaddress)
- [mentionsLabel](akashaproject_design_system._internal_.ITagSearchCard.md#mentionslabel)
- [onClickTag](akashaproject_design_system._internal_.ITagSearchCard.md#onclicktag)
- [subscribeLabel](akashaproject_design_system._internal_.ITagSearchCard.md#subscribelabel)
- [subscribedLabel](akashaproject_design_system._internal_.ITagSearchCard.md#subscribedlabel)
- [subscribedTags](akashaproject_design_system._internal_.ITagSearchCard.md#subscribedtags)
- [tag](akashaproject_design_system._internal_.ITagSearchCard.md#tag)
- [tagAnchorLink](akashaproject_design_system._internal_.ITagSearchCard.md#taganchorlink)
- [unsubscribeLabel](akashaproject_design_system._internal_.ITagSearchCard.md#unsubscribelabel)

### Methods

- [handleSubscribeTag](akashaproject_design_system._internal_.ITagSearchCard.md#handlesubscribetag)
- [handleUnsubscribeTag](akashaproject_design_system._internal_.ITagSearchCard.md#handleunsubscribetag)

## Properties

### loggedEthAddress

• `Optional` **loggedEthAddress**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L17)

___

### mentionsLabel

• `Optional` **mentionsLabel**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L19)

___

### onClickTag

• `Optional` **onClickTag**: (`event`: [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\>) => `void`

#### Type declaration

▸ (`event`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`SyntheticEvent`](akashaproject_design_system._internal_.SyntheticEvent.md)<`Element`, `Event`\> |

##### Returns

`void`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L26)

___

### subscribeLabel

• `Optional` **subscribeLabel**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L20)

___

### subscribedLabel

• `Optional` **subscribedLabel**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L22)

___

### subscribedTags

• **subscribedTags**: `string`[]

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L16)

___

### tag

• **tag**: [`ITag`](akashaproject_design_system._internal_.ITag.md)

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L15)

___

### tagAnchorLink

• **tagAnchorLink**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L24)

___

### unsubscribeLabel

• `Optional` **unsubscribeLabel**: `string`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L21)

## Methods

### handleSubscribeTag

▸ **handleSubscribeTag**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L27)

___

### handleUnsubscribeTag

▸ **handleUnsubscribeTag**(`tagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/TagCard/tag-search-card.tsx:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TagCard/tag-search-card.tsx#L28)
