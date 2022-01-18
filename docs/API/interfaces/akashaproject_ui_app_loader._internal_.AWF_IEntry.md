[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_IEntry

# Interface: AWF\_IEntry

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_IEntry

## Implemented by

- [`AWF_Entry`](../classes/akashaproject_ui_app_loader._internal_.AWF_Entry.md)

## Table of contents

### Methods

- [editEntry](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#editentry)
- [entriesByAuthor](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#entriesbyauthor)
- [entriesByTag](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#entriesbytag)
- [getEntries](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#getentries)
- [getEntry](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#getentry)
- [getFeedEntries](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#getfeedentries)
- [getLinkPreview](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#getlinkpreview)
- [postEntry](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#postentry)
- [removeEntry](akashaproject_ui_app_loader._internal_.AWF_IEntry.md#removeentry)

## Methods

### editEntry

▸ **editEntry**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |
| `opt.entryID` | `string` |
| `opt.post` | `Object` |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:29

___

### entriesByAuthor

▸ **entriesByAuthor**(`opt`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `number` |
| `opt.pubKey` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:39

___

### entriesByTag

▸ **entriesByTag**(`opt`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.name` | `string` |
| `opt.offset?` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:48

___

### getEntries

▸ **getEntries**(`opt`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:13

___

### getEntry

▸ **getEntry**(`entryId`): `Observable`<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryId` | `string` |

#### Returns

`Observable`<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:8

___

### getFeedEntries

▸ **getFeedEntries**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `number` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:62

___

### getLinkPreview

▸ **getLinkPreview**(`link`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `link` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:57

___

### postEntry

▸ **postEntry**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |
| `opt.post` | `Object` |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:21

___

### removeEntry

▸ **removeEntry**(`entryID`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryID` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:38
