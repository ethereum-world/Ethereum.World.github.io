[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEditorCard

# Interface: IEditorCard

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEditorCard

## Hierarchy

- [`IEditorBox`](akashaproject_design_system._internal_.IEditorBox.md)

  ↳ **`IEditorCard`**

## Table of contents

### Properties

- [avatar](akashaproject_design_system._internal_.IEditorCard.md#avatar)
- [cancelButtonLabel](akashaproject_design_system._internal_.IEditorCard.md#cancelbuttonlabel)
- [className](akashaproject_design_system._internal_.IEditorCard.md#classname)
- [disablePublish](akashaproject_design_system._internal_.IEditorCard.md#disablepublish)
- [disablePublishLabel](akashaproject_design_system._internal_.IEditorCard.md#disablepublishlabel)
- [editorState](akashaproject_design_system._internal_.IEditorCard.md#editorstate)
- [embedEntryData](akashaproject_design_system._internal_.IEditorCard.md#embedentrydata)
- [emojiPlaceholderLabel](akashaproject_design_system._internal_.IEditorCard.md#emojiplaceholderlabel)
- [ethAddress](akashaproject_design_system._internal_.IEditorCard.md#ethaddress)
- [linkPreview](akashaproject_design_system._internal_.IEditorCard.md#linkpreview)
- [mentions](akashaproject_design_system._internal_.IEditorCard.md#mentions)
- [minHeight](akashaproject_design_system._internal_.IEditorCard.md#minheight)
- [placeholderLabel](akashaproject_design_system._internal_.IEditorCard.md#placeholderlabel)
- [postLabel](akashaproject_design_system._internal_.IEditorCard.md#postlabel)
- [publishingApp](akashaproject_design_system._internal_.IEditorCard.md#publishingapp)
- [ref](akashaproject_design_system._internal_.IEditorCard.md#ref)
- [setEditorState](akashaproject_design_system._internal_.IEditorCard.md#seteditorstate)
- [showCancelButton](akashaproject_design_system._internal_.IEditorCard.md#showcancelbutton)
- [style](akashaproject_design_system._internal_.IEditorCard.md#style)
- [tags](akashaproject_design_system._internal_.IEditorCard.md#tags)
- [titleLabel](akashaproject_design_system._internal_.IEditorCard.md#titlelabel)
- [uploadFailedLabel](akashaproject_design_system._internal_.IEditorCard.md#uploadfailedlabel)
- [uploadedImages](akashaproject_design_system._internal_.IEditorCard.md#uploadedimages)
- [uploadingImageLabel](akashaproject_design_system._internal_.IEditorCard.md#uploadingimagelabel)
- [withMeter](akashaproject_design_system._internal_.IEditorCard.md#withmeter)

### Methods

- [getLinkPreview](akashaproject_design_system._internal_.IEditorCard.md#getlinkpreview)
- [getMentions](akashaproject_design_system._internal_.IEditorCard.md#getmentions)
- [getTags](akashaproject_design_system._internal_.IEditorCard.md#gettags)
- [handleNavigateBack](akashaproject_design_system._internal_.IEditorCard.md#handlenavigateback)
- [onCancelClick](akashaproject_design_system._internal_.IEditorCard.md#oncancelclick)
- [onPublish](akashaproject_design_system._internal_.IEditorCard.md#onpublish)
- [uploadRequest](akashaproject_design_system._internal_.IEditorCard.md#uploadrequest)

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[avatar](akashaproject_design_system._internal_.IEditorBox.md#avatar)

#### Defined in

[ui/design/src/components/Editor/index.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L42)

___

### cancelButtonLabel

• `Optional` **cancelButtonLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[cancelButtonLabel](akashaproject_design_system._internal_.IEditorBox.md#cancelbuttonlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L80)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L9)

___

### disablePublish

• `Optional` **disablePublish**: `boolean`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[disablePublish](akashaproject_design_system._internal_.IEditorBox.md#disablepublish)

#### Defined in

[ui/design/src/components/Editor/index.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L51)

___

### disablePublishLabel

• `Optional` **disablePublishLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[disablePublishLabel](akashaproject_design_system._internal_.IEditorBox.md#disablepublishlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L49)

___

### editorState

• `Optional` **editorState**: `Descendant`[]

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[editorState](akashaproject_design_system._internal_.IEditorBox.md#editorstate)

#### Defined in

[ui/design/src/components/Editor/index.tsx:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L75)

___

### embedEntryData

• `Optional` **embedEntryData**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[embedEntryData](akashaproject_design_system._internal_.IEditorBox.md#embedentrydata)

#### Defined in

[ui/design/src/components/Editor/index.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L52)

___

### emojiPlaceholderLabel

• `Optional` **emojiPlaceholderLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[emojiPlaceholderLabel](akashaproject_design_system._internal_.IEditorBox.md#emojiplaceholderlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L46)

___

### ethAddress

• **ethAddress**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[ethAddress](akashaproject_design_system._internal_.IEditorBox.md#ethaddress)

#### Defined in

[ui/design/src/components/Editor/index.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L43)

___

### linkPreview

• `Optional` **linkPreview**: [`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[linkPreview](akashaproject_design_system._internal_.IEditorBox.md#linkpreview)

#### Defined in

[ui/design/src/components/Editor/index.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L55)

___

### mentions

• `Optional` **mentions**: { `avatar?`: `string` ; `coverImage?`: `string` ; `description?`: `string` ; `ethAddress`: `string` ; `name?`: `string` ; `pubKey`: `string` ; `userName?`: `string`  }[]

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[mentions](akashaproject_design_system._internal_.IEditorBox.md#mentions)

#### Defined in

[ui/design/src/components/Editor/index.tsx:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L60)

___

### minHeight

• `Optional` **minHeight**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[minHeight](akashaproject_design_system._internal_.IEditorBox.md#minheight)

#### Defined in

[ui/design/src/components/Editor/index.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L53)

___

### placeholderLabel

• `Optional` **placeholderLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[placeholderLabel](akashaproject_design_system._internal_.IEditorBox.md#placeholderlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L45)

___

### postLabel

• `Optional` **postLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[postLabel](akashaproject_design_system._internal_.IEditorBox.md#postlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L44)

___

### publishingApp

• `Optional` **publishingApp**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[publishingApp](akashaproject_design_system._internal_.IEditorBox.md#publishingapp)

#### Defined in

[ui/design/src/components/Editor/index.tsx:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L74)

___

### ref

• `Optional` **ref**: [`Ref`](../modules/akashaproject_design_system._internal_.md#ref)<`unknown`\>

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[ref](akashaproject_design_system._internal_.IEditorBox.md#ref)

#### Defined in

[ui/design/src/components/Editor/index.tsx:77](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L77)

___

### setEditorState

• **setEditorState**: [`Dispatch`](../modules/akashaproject_design_system._internal_.md#dispatch)<[`SetStateAction`](../modules/akashaproject_design_system._internal_.md#setstateaction)<`Descendant`[]\>\>

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[setEditorState](akashaproject_design_system._internal_.IEditorBox.md#seteditorstate)

#### Defined in

[ui/design/src/components/Editor/index.tsx:76](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L76)

___

### showCancelButton

• `Optional` **showCancelButton**: `boolean`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[showCancelButton](akashaproject_design_system._internal_.IEditorBox.md#showcancelbutton)

#### Defined in

[ui/design/src/components/Editor/index.tsx:78](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L78)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L11)

___

### tags

• `Optional` **tags**: { `name`: `string` ; `totalPosts`: `number`  }[]

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[tags](akashaproject_design_system._internal_.IEditorBox.md#tags)

#### Defined in

[ui/design/src/components/Editor/index.tsx:69](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L69)

___

### titleLabel

• `Optional` **titleLabel**: `string`

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L10)

___

### uploadFailedLabel

• `Optional` **uploadFailedLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[uploadFailedLabel](akashaproject_design_system._internal_.IEditorBox.md#uploadfailedlabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L47)

___

### uploadedImages

• `Optional` **uploadedImages**: { `id`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } ; `src`: `string`  }[]

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[uploadedImages](akashaproject_design_system._internal_.IEditorBox.md#uploadedimages)

#### Defined in

[ui/design/src/components/Editor/index.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L56)

___

### uploadingImageLabel

• `Optional` **uploadingImageLabel**: `string`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[uploadingImageLabel](akashaproject_design_system._internal_.IEditorBox.md#uploadingimagelabel)

#### Defined in

[ui/design/src/components/Editor/index.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L48)

___

### withMeter

• `Optional` **withMeter**: `boolean`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[withMeter](akashaproject_design_system._internal_.IEditorBox.md#withmeter)

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

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[getLinkPreview](akashaproject_design_system._internal_.IEditorBox.md#getlinkpreview)

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

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[getMentions](akashaproject_design_system._internal_.IEditorBox.md#getmentions)

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

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[getTags](akashaproject_design_system._internal_.IEditorBox.md#gettags)

#### Defined in

[ui/design/src/components/Editor/index.tsx:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L59)

___

### handleNavigateBack

▸ **handleNavigateBack**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L12)

___

### onCancelClick

▸ `Optional` **onCancelClick**(): `void`

#### Returns

`void`

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[onCancelClick](akashaproject_design_system._internal_.IEditorBox.md#oncancelclick)

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

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[onPublish](akashaproject_design_system._internal_.IEditorBox.md#onpublish)

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

#### Inherited from

[IEditorBox](akashaproject_design_system._internal_.IEditorBox.md).[uploadRequest](akashaproject_design_system._internal_.IEditorBox.md#uploadrequest)

#### Defined in

[ui/design/src/components/Editor/index.tsx:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L70)
