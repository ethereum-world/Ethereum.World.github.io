[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEditorBox

# Interface: IEditorBox

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEditorBox

**`param`** upload a file and returns a promise that resolves to an array

**`param`** the state of the editor is controlled from the parent component

## Hierarchy

- **`IEditorBox`**

  ↳ [`IEditorCard`](akashaproject_design_system._internal_.IEditorCard.md)

## Table of contents

### Properties

- [avatar](akashaproject_design_system._internal_.IEditorBox.md#avatar)
- [cancelButtonLabel](akashaproject_design_system._internal_.IEditorBox.md#cancelbuttonlabel)
- [disablePublish](akashaproject_design_system._internal_.IEditorBox.md#disablepublish)
- [disablePublishLabel](akashaproject_design_system._internal_.IEditorBox.md#disablepublishlabel)
- [editorState](akashaproject_design_system._internal_.IEditorBox.md#editorstate)
- [embedEntryData](akashaproject_design_system._internal_.IEditorBox.md#embedentrydata)
- [emojiPlaceholderLabel](akashaproject_design_system._internal_.IEditorBox.md#emojiplaceholderlabel)
- [ethAddress](akashaproject_design_system._internal_.IEditorBox.md#ethaddress)
- [linkPreview](akashaproject_design_system._internal_.IEditorBox.md#linkpreview)
- [mentions](akashaproject_design_system._internal_.IEditorBox.md#mentions)
- [minHeight](akashaproject_design_system._internal_.IEditorBox.md#minheight)
- [placeholderLabel](akashaproject_design_system._internal_.IEditorBox.md#placeholderlabel)
- [postLabel](akashaproject_design_system._internal_.IEditorBox.md#postlabel)
- [publishingApp](akashaproject_design_system._internal_.IEditorBox.md#publishingapp)
- [ref](akashaproject_design_system._internal_.IEditorBox.md#ref)
- [setEditorState](akashaproject_design_system._internal_.IEditorBox.md#seteditorstate)
- [showCancelButton](akashaproject_design_system._internal_.IEditorBox.md#showcancelbutton)
- [tags](akashaproject_design_system._internal_.IEditorBox.md#tags)
- [uploadFailedLabel](akashaproject_design_system._internal_.IEditorBox.md#uploadfailedlabel)
- [uploadedImages](akashaproject_design_system._internal_.IEditorBox.md#uploadedimages)
- [uploadingImageLabel](akashaproject_design_system._internal_.IEditorBox.md#uploadingimagelabel)
- [withMeter](akashaproject_design_system._internal_.IEditorBox.md#withmeter)

### Methods

- [getLinkPreview](akashaproject_design_system._internal_.IEditorBox.md#getlinkpreview)
- [getMentions](akashaproject_design_system._internal_.IEditorBox.md#getmentions)
- [getTags](akashaproject_design_system._internal_.IEditorBox.md#gettags)
- [onCancelClick](akashaproject_design_system._internal_.IEditorBox.md#oncancelclick)
- [onPublish](akashaproject_design_system._internal_.IEditorBox.md#onpublish)
- [uploadRequest](akashaproject_design_system._internal_.IEditorBox.md#uploadrequest)

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L42)

___

### cancelButtonLabel

• `Optional` **cancelButtonLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L80)

___

### disablePublish

• `Optional` **disablePublish**: `boolean`

#### Defined in

[ui/design/src/components/Editor/index.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L51)

___

### disablePublishLabel

• `Optional` **disablePublishLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L49)

___

### editorState

• `Optional` **editorState**: `Descendant`[]

#### Defined in

[ui/design/src/components/Editor/index.tsx:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L75)

___

### embedEntryData

• `Optional` **embedEntryData**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Defined in

[ui/design/src/components/Editor/index.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L52)

___

### emojiPlaceholderLabel

• `Optional` **emojiPlaceholderLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L46)

___

### ethAddress

• **ethAddress**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L43)

___

### linkPreview

• `Optional` **linkPreview**: [`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)

#### Defined in

[ui/design/src/components/Editor/index.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L55)

___

### mentions

• `Optional` **mentions**: { `avatar?`: `string` ; `coverImage?`: `string` ; `description?`: `string` ; `ethAddress`: `string` ; `name?`: `string` ; `pubKey`: `string` ; `userName?`: `string`  }[]

#### Defined in

[ui/design/src/components/Editor/index.tsx:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L60)

___

### minHeight

• `Optional` **minHeight**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L53)

___

### placeholderLabel

• `Optional` **placeholderLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L45)

___

### postLabel

• `Optional` **postLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L44)

___

### publishingApp

• `Optional` **publishingApp**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L74)

___

### ref

• `Optional` **ref**: [`Ref`](../modules/akashaproject_design_system._internal_.md#ref)<`unknown`\>

#### Defined in

[ui/design/src/components/Editor/index.tsx:77](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L77)

___

### setEditorState

• **setEditorState**: [`Dispatch`](../modules/akashaproject_design_system._internal_.md#dispatch)<[`SetStateAction`](../modules/akashaproject_design_system._internal_.md#setstateaction)<`Descendant`[]\>\>

#### Defined in

[ui/design/src/components/Editor/index.tsx:76](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L76)

___

### showCancelButton

• `Optional` **showCancelButton**: `boolean`

#### Defined in

[ui/design/src/components/Editor/index.tsx:78](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L78)

___

### tags

• `Optional` **tags**: { `name`: `string` ; `totalPosts`: `number`  }[]

#### Defined in

[ui/design/src/components/Editor/index.tsx:69](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L69)

___

### uploadFailedLabel

• `Optional` **uploadFailedLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L47)

___

### uploadedImages

• `Optional` **uploadedImages**: { `id`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } ; `src`: `string`  }[]

#### Defined in

[ui/design/src/components/Editor/index.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L56)

___

### uploadingImageLabel

• `Optional` **uploadingImageLabel**: `string`

#### Defined in

[ui/design/src/components/Editor/index.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L48)

___

### withMeter

• `Optional` **withMeter**: `boolean`

#### Defined in

[ui/design/src/components/Editor/index.tsx:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L54)

## Methods

### getLinkPreview

▸ **getLinkPreview**(`url`): `Promise`<[`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`Promise`<[`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)\>

#### Defined in

[ui/design/src/components/Editor/index.tsx:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L57)

___

### getMentions

▸ **getMentions**(`query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/Editor/index.tsx:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L58)

___

### getTags

▸ **getTags**(`query`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/Editor/index.tsx:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L59)

___

### onCancelClick

▸ `Optional` **onCancelClick**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/Editor/index.tsx:79](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L79)

___

### onPublish

▸ **onPublish**(`publishData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `publishData` | [`IPublishData`](akashaproject_design_system._internal_.IPublishData.md) |

#### Returns

`void`

#### Defined in

[ui/design/src/components/Editor/index.tsx:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L50)

___

### uploadRequest

▸ `Optional` **uploadRequest**(`data`, `isUrl?`): `Promise`<{ `data?`: [`ImageData`](akashaproject_design_system._internal_.ImageData.md) ; `error?`: [`Error`](../modules/akashaproject_design_system._internal_.md#error)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`File`](../modules/akashaproject_design_system._internal_.md#file) |
| `isUrl?` | `boolean` |

#### Returns

`Promise`<{ `data?`: [`ImageData`](akashaproject_design_system._internal_.ImageData.md) ; `error?`: [`Error`](../modules/akashaproject_design_system._internal_.md#error)  }\>

#### Defined in

[ui/design/src/components/Editor/index.tsx:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L70)
