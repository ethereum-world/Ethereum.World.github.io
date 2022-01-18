[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IEntry

# Interface: AWF\_IEntry

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IEntry

## Table of contents

### Methods

- [editEntry](akashaproject_sdk_typings._internal_.AWF_IEntry.md#editentry)
- [entriesByAuthor](akashaproject_sdk_typings._internal_.AWF_IEntry.md#entriesbyauthor)
- [entriesByTag](akashaproject_sdk_typings._internal_.AWF_IEntry.md#entriesbytag)
- [getEntries](akashaproject_sdk_typings._internal_.AWF_IEntry.md#getentries)
- [getEntry](akashaproject_sdk_typings._internal_.AWF_IEntry.md#getentry)
- [getFeedEntries](akashaproject_sdk_typings._internal_.AWF_IEntry.md#getfeedentries)
- [getLinkPreview](akashaproject_sdk_typings._internal_.AWF_IEntry.md#getlinkpreview)
- [postEntry](akashaproject_sdk_typings._internal_.AWF_IEntry.md#postentry)
- [removeEntry](akashaproject_sdk_typings._internal_.AWF_IEntry.md#removeentry)

## Methods

### editEntry

▸ **editEntry**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |
| `opt.entryID` | `string` |
| `opt.post` | `Object` |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/posts.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L26)

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

[sdk/typings/src/interfaces/posts.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L34)

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

[sdk/typings/src/interfaces/posts.ts:40](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L40)

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

[sdk/typings/src/interfaces/posts.ts:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L15)

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

[sdk/typings/src/interfaces/posts.ts:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L9)

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

[sdk/typings/src/interfaces/posts.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L52)

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

[sdk/typings/src/interfaces/posts.ts:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L46)

___

### postEntry

▸ **postEntry**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |
| `opt.post` | `Object` |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/posts.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L21)

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

[sdk/typings/src/interfaces/posts.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L32)
