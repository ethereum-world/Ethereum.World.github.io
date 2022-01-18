[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEditorModal

# Interface: IEditorModal

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEditorModal

## Hierarchy

- [`Omit`](../modules/akashaproject_design_system._internal_.md#omit)<[`IEditorCard`](akashaproject_design_system._internal_.IEditorCard.md), ``"setEditorState"``\>

  ↳ **`IEditorModal`**

## Table of contents

### Properties

- [avatar](akashaproject_design_system._internal_.IEditorModal.md#avatar)
- [cancelButtonLabel](akashaproject_design_system._internal_.IEditorModal.md#cancelbuttonlabel)
- [className](akashaproject_design_system._internal_.IEditorModal.md#classname)
- [disablePublish](akashaproject_design_system._internal_.IEditorModal.md#disablepublish)
- [disablePublishLabel](akashaproject_design_system._internal_.IEditorModal.md#disablepublishlabel)
- [discardPostInfoLabel](akashaproject_design_system._internal_.IEditorModal.md#discardpostinfolabel)
- [discardPostLabel](akashaproject_design_system._internal_.IEditorModal.md#discardpostlabel)
- [editorState](akashaproject_design_system._internal_.IEditorModal.md#editorstate)
- [embedEntryData](akashaproject_design_system._internal_.IEditorModal.md#embedentrydata)
- [emojiPlaceholderLabel](akashaproject_design_system._internal_.IEditorModal.md#emojiplaceholderlabel)
- [ethAddress](akashaproject_design_system._internal_.IEditorModal.md#ethaddress)
- [keepEditingLabel](akashaproject_design_system._internal_.IEditorModal.md#keepeditinglabel)
- [linkPreview](akashaproject_design_system._internal_.IEditorModal.md#linkpreview)
- [mentions](akashaproject_design_system._internal_.IEditorModal.md#mentions)
- [minHeight](akashaproject_design_system._internal_.IEditorModal.md#minheight)
- [placeholderLabel](akashaproject_design_system._internal_.IEditorModal.md#placeholderlabel)
- [postLabel](akashaproject_design_system._internal_.IEditorModal.md#postlabel)
- [publishingApp](akashaproject_design_system._internal_.IEditorModal.md#publishingapp)
- [ref](akashaproject_design_system._internal_.IEditorModal.md#ref)
- [showCancelButton](akashaproject_design_system._internal_.IEditorModal.md#showcancelbutton)
- [style](akashaproject_design_system._internal_.IEditorModal.md#style)
- [tags](akashaproject_design_system._internal_.IEditorModal.md#tags)
- [titleLabel](akashaproject_design_system._internal_.IEditorModal.md#titlelabel)
- [uploadFailedLabel](akashaproject_design_system._internal_.IEditorModal.md#uploadfailedlabel)
- [uploadedImages](akashaproject_design_system._internal_.IEditorModal.md#uploadedimages)
- [uploadingImageLabel](akashaproject_design_system._internal_.IEditorModal.md#uploadingimagelabel)
- [withMeter](akashaproject_design_system._internal_.IEditorModal.md#withmeter)

### Methods

- [getLinkPreview](akashaproject_design_system._internal_.IEditorModal.md#getlinkpreview)
- [getMentions](akashaproject_design_system._internal_.IEditorModal.md#getmentions)
- [getTags](akashaproject_design_system._internal_.IEditorModal.md#gettags)
- [handleNavigateBack](akashaproject_design_system._internal_.IEditorModal.md#handlenavigateback)
- [onCancelClick](akashaproject_design_system._internal_.IEditorModal.md#oncancelclick)
- [onPublish](akashaproject_design_system._internal_.IEditorModal.md#onpublish)
- [uploadRequest](akashaproject_design_system._internal_.IEditorModal.md#uploadrequest)

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Inherited from

Omit.avatar

#### Defined in

[ui/design/src/components/Editor/index.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L42)

___

### cancelButtonLabel

• `Optional` **cancelButtonLabel**: `string`

#### Inherited from

Omit.cancelButtonLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L80)

___

### className

• `Optional` **className**: `string`

#### Inherited from

Omit.className

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L9)

___

### disablePublish

• `Optional` **disablePublish**: `boolean`

#### Inherited from

Omit.disablePublish

#### Defined in

[ui/design/src/components/Editor/index.tsx:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L51)

___

### disablePublishLabel

• `Optional` **disablePublishLabel**: `string`

#### Inherited from

Omit.disablePublishLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L49)

___

### discardPostInfoLabel

• `Optional` **discardPostInfoLabel**: `string`

#### Defined in

[ui/design/src/components/EditorModal/index.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorModal/index.tsx#L13)

___

### discardPostLabel

• `Optional` **discardPostLabel**: `string`

#### Defined in

[ui/design/src/components/EditorModal/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorModal/index.tsx#L12)

___

### editorState

• `Optional` **editorState**: `Descendant`[]

#### Inherited from

Omit.editorState

#### Defined in

[ui/design/src/components/Editor/index.tsx:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L75)

___

### embedEntryData

• `Optional` **embedEntryData**: [`IEntryData`](akashaproject_design_system._internal_.IEntryData.md)

#### Inherited from

Omit.embedEntryData

#### Defined in

[ui/design/src/components/Editor/index.tsx:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L52)

___

### emojiPlaceholderLabel

• `Optional` **emojiPlaceholderLabel**: `string`

#### Inherited from

Omit.emojiPlaceholderLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L46)

___

### ethAddress

• **ethAddress**: `string`

#### Inherited from

Omit.ethAddress

#### Defined in

[ui/design/src/components/Editor/index.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L43)

___

### keepEditingLabel

• `Optional` **keepEditingLabel**: `string`

#### Defined in

[ui/design/src/components/EditorModal/index.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorModal/index.tsx#L14)

___

### linkPreview

• `Optional` **linkPreview**: [`LinkPreview_Response`](akashaproject_design_system._internal_.LinkPreview_Response.md)

#### Inherited from

Omit.linkPreview

#### Defined in

[ui/design/src/components/Editor/index.tsx:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L55)

___

### mentions

• `Optional` **mentions**: { `avatar?`: `string` ; `coverImage?`: `string` ; `description?`: `string` ; `ethAddress`: `string` ; `name?`: `string` ; `pubKey`: `string` ; `userName?`: `string`  }[]

#### Inherited from

Omit.mentions

#### Defined in

[ui/design/src/components/Editor/index.tsx:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L60)

___

### minHeight

• `Optional` **minHeight**: `string`

#### Inherited from

Omit.minHeight

#### Defined in

[ui/design/src/components/Editor/index.tsx:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L53)

___

### placeholderLabel

• `Optional` **placeholderLabel**: `string`

#### Inherited from

Omit.placeholderLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L45)

___

### postLabel

• `Optional` **postLabel**: `string`

#### Inherited from

Omit.postLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L44)

___

### publishingApp

• `Optional` **publishingApp**: `string`

#### Inherited from

Omit.publishingApp

#### Defined in

[ui/design/src/components/Editor/index.tsx:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L74)

___

### ref

• `Optional` **ref**: [`Ref`](../modules/akashaproject_design_system._internal_.md#ref)<`unknown`\>

#### Inherited from

Omit.ref

#### Defined in

[ui/design/src/components/Editor/index.tsx:77](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L77)

___

### showCancelButton

• `Optional` **showCancelButton**: `boolean`

#### Inherited from

Omit.showCancelButton

#### Defined in

[ui/design/src/components/Editor/index.tsx:78](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L78)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Inherited from

Omit.style

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L11)

___

### tags

• `Optional` **tags**: { `name`: `string` ; `totalPosts`: `number`  }[]

#### Inherited from

Omit.tags

#### Defined in

[ui/design/src/components/Editor/index.tsx:69](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L69)

___

### titleLabel

• `Optional` **titleLabel**: `string`

#### Inherited from

Omit.titleLabel

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L10)

___

### uploadFailedLabel

• `Optional` **uploadFailedLabel**: `string`

#### Inherited from

Omit.uploadFailedLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L47)

___

### uploadedImages

• `Optional` **uploadedImages**: { `id`: `string` ; `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } ; `src`: `string`  }[]

#### Inherited from

Omit.uploadedImages

#### Defined in

[ui/design/src/components/Editor/index.tsx:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L56)

___

### uploadingImageLabel

• `Optional` **uploadingImageLabel**: `string`

#### Inherited from

Omit.uploadingImageLabel

#### Defined in

[ui/design/src/components/Editor/index.tsx:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L48)

___

### withMeter

• `Optional` **withMeter**: `boolean`

#### Inherited from

Omit.withMeter

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

Omit.getLinkPreview

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

Omit.getMentions

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

Omit.getTags

#### Defined in

[ui/design/src/components/Editor/index.tsx:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L59)

___

### handleNavigateBack

▸ **handleNavigateBack**(): `void`

#### Returns

`void`

#### Inherited from

Omit.handleNavigateBack

#### Defined in

[ui/design/src/components/EditorCard/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EditorCard/index.tsx#L12)

___

### onCancelClick

▸ `Optional` **onCancelClick**(): `void`

#### Returns

`void`

#### Inherited from

Omit.onCancelClick

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

Omit.onPublish

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

Omit.uploadRequest

#### Defined in

[ui/design/src/components/Editor/index.tsx:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/Editor/index.tsx#L70)
