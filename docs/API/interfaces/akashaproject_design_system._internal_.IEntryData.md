[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEntryData

# Interface: IEntryData

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEntryData

## Table of contents

### Properties

- [CID](akashaproject_design_system._internal_.IEntryData.md#cid)
- [author](akashaproject_design_system._internal_.IEntryData.md#author)
- [delisted](akashaproject_design_system._internal_.IEntryData.md#delisted)
- [entryId](akashaproject_design_system._internal_.IEntryData.md#entryid)
- [images](akashaproject_design_system._internal_.IEntryData.md#images)
- [ipfsLink](akashaproject_design_system._internal_.IEntryData.md#ipfslink)
- [isPublishing](akashaproject_design_system._internal_.IEntryData.md#ispublishing)
- [isRemoved](akashaproject_design_system._internal_.IEntryData.md#isremoved)
- [linkPreview](akashaproject_design_system._internal_.IEntryData.md#linkpreview)
- [moderated](akashaproject_design_system._internal_.IEntryData.md#moderated)
- [permalink](akashaproject_design_system._internal_.IEntryData.md#permalink)
- [postId](akashaproject_design_system._internal_.IEntryData.md#postid)
- [quote](akashaproject_design_system._internal_.IEntryData.md#quote)
- [quotedBy](akashaproject_design_system._internal_.IEntryData.md#quotedby)
- [quotedByAuthors](akashaproject_design_system._internal_.IEntryData.md#quotedbyauthors)
- [reason](akashaproject_design_system._internal_.IEntryData.md#reason)
- [replies](akashaproject_design_system._internal_.IEntryData.md#replies)
- [reported](akashaproject_design_system._internal_.IEntryData.md#reported)
- [reposts](akashaproject_design_system._internal_.IEntryData.md#reposts)
- [slateContent](akashaproject_design_system._internal_.IEntryData.md#slatecontent)
- [time](akashaproject_design_system._internal_.IEntryData.md#time)
- [type](akashaproject_design_system._internal_.IEntryData.md#type)
- [updatedAt](akashaproject_design_system._internal_.IEntryData.md#updatedat)

## Properties

### CID

• `Optional` **CID**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:23

___

### author

• **author**: [`IProfileData`](akashaproject_design_system._internal_.IProfileData.md)

#### Defined in

ui/typings/lib/entry.d.ts:34

___

### delisted

• `Optional` **delisted**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:38

___

### entryId

• **entryId**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:33

___

### images

• `Optional` **images**: { `id`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } ; `src`: `string`  }[]

#### Defined in

ui/typings/lib/entry.d.ts:25

___

### ipfsLink

• `Optional` **ipfsLink**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:31

___

### isPublishing

• `Optional` **isPublishing**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:44

___

### isRemoved

• `Optional` **isRemoved**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:42

___

### linkPreview

• `Optional` **linkPreview**: [`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)

#### Defined in

ui/typings/lib/entry.d.ts:24

___

### moderated

• `Optional` **moderated**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:40

___

### permalink

• `Optional` **permalink**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:32

___

### postId

• `Optional` **postId**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:45

___

### quote

• `Optional` **quote**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Defined in

ui/typings/lib/entry.d.ts:37

___

### quotedBy

• `Optional` **quotedBy**: `string`[]

#### Defined in

ui/typings/lib/entry.d.ts:36

___

### quotedByAuthors

• `Optional` **quotedByAuthors**: [`IProfileData`](akashaproject_design_system._internal_.IProfileData.md)[]

#### Defined in

ui/typings/lib/entry.d.ts:35

___

### reason

• `Optional` **reason**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:41

___

### replies

• `Optional` **replies**: `number`

#### Defined in

ui/typings/lib/entry.d.ts:29

___

### reported

• `Optional` **reported**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:39

___

### reposts

• `Optional` **reposts**: `number`

#### Defined in

ui/typings/lib/entry.d.ts:30

___

### slateContent

• **slateContent**: `Descendant`[]

#### Defined in

ui/typings/lib/entry.d.ts:26

___

### time

• `Optional` **time**: `string` \| `number` \| `Date`

#### Defined in

ui/typings/lib/entry.d.ts:27

___

### type

• `Optional` **type**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:43

___

### updatedAt

• `Optional` **updatedAt**: `string` \| `number` \| `Date`

#### Defined in

ui/typings/lib/entry.d.ts:28
