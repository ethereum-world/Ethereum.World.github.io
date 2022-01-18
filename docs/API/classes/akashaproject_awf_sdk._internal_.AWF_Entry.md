[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_Entry

# Class: AWF\_Entry

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_Entry

## Implements

- [`AWF_IEntry`](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.AWF_Entry.md#constructor)

### Properties

- [graphQLDocs](akashaproject_awf_sdk._internal_.AWF_Entry.md#graphqldocs)

### Methods

- [editEntry](akashaproject_awf_sdk._internal_.AWF_Entry.md#editentry)
- [entriesByAuthor](akashaproject_awf_sdk._internal_.AWF_Entry.md#entriesbyauthor)
- [entriesByTag](akashaproject_awf_sdk._internal_.AWF_Entry.md#entriesbytag)
- [getEntries](akashaproject_awf_sdk._internal_.AWF_Entry.md#getentries)
- [getEntry](akashaproject_awf_sdk._internal_.AWF_Entry.md#getentry)
- [getFeedEntries](akashaproject_awf_sdk._internal_.AWF_Entry.md#getfeedentries)
- [getLinkPreview](akashaproject_awf_sdk._internal_.AWF_Entry.md#getlinkpreview)
- [postEntry](akashaproject_awf_sdk._internal_.AWF_Entry.md#postentry)
- [removeEntry](akashaproject_awf_sdk._internal_.AWF_Entry.md#removeentry)

## Constructors

### constructor

• **new AWF_Entry**(`log`, `gql`, `auth`, `globalChannel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_awf_sdk._internal_.Logging.md) |
| `gql` | [`Gql`](akashaproject_awf_sdk._internal_.Gql.md) |
| `auth` | [`AWF_Auth`](akashaproject_awf_sdk._internal_.AWF_Auth.md) |
| `globalChannel` | [`EventBus`](akashaproject_awf_sdk._internal_.EventBus.md) |

#### Defined in

[sdk/src/posts/entry.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L48)

## Properties

### graphQLDocs

• `Readonly` **graphQLDocs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `CreateEntry` | [`DocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.DocumentNode.md) |
| `EditEntry` | [`DocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.DocumentNode.md) |
| `GetCustomFeed` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `GetEntries` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `GetEntry` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `GetLinkPreview` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `GetPostsByAuthor` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `GetPostsByTag` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\>\> |
| `RemoveEntry` | [`DocumentNode`](../interfaces/akashaproject_awf_sdk._internal_.DocumentNode.md) |

#### Defined in

[sdk/src/posts/entry.ts:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L36)

## Methods

### editEntry

▸ **editEntry**(`opt`): `Observable`<{ `data`: { `editPost`: `boolean`  }  }\>

Update an existing entry

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](../interfaces/akashaproject_awf_sdk._internal_.DataProviderInput.md)[] |
| `opt.entryID` | `string` |
| `opt.post` | `Object` |
| `opt.post.mentions?` | `string`[] |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`Observable`<{ `data`: { `editPost`: `boolean`  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[editEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#editentry)

#### Defined in

[sdk/src/posts/entry.ts:149](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L149)

___

### entriesByAuthor

▸ **entriesByAuthor**(`opt`): `Observable`<{ `data`: { `getPostsByAuthor`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `number` |
| `opt.pubKey` | `string` |

#### Returns

`Observable`<{ `data`: { `getPostsByAuthor`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[entriesByAuthor](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#entriesbyauthor)

#### Defined in

[sdk/src/posts/entry.ts:191](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L191)

___

### entriesByTag

▸ **entriesByTag**(`opt`): `Observable`<{ `data`: { `getPostsByTag`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.name` | `string` |
| `opt.offset?` | `string` |

#### Returns

`Observable`<{ `data`: { `getPostsByTag`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[entriesByTag](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#entriesbytag)

#### Defined in

[sdk/src/posts/entry.ts:216](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L216)

___

### getEntries

▸ **getEntries**(`opt`): `Observable`<{ `data`: { `posts`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |

#### Returns

`Observable`<{ `data`: { `posts`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[getEntries](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#getentries)

#### Defined in

[sdk/src/posts/entry.ts:84](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L84)

___

### getEntry

▸ **getEntry**(`entryId`): `Observable`<{ `data`: { `getPost`: [`Post_Response`](../interfaces/akashaproject_awf_sdk._internal_.Post_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryId` | `string` |

#### Returns

`Observable`<{ `data`: { `getPost`: [`Post_Response`](../interfaces/akashaproject_awf_sdk._internal_.Post_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[getEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#getentry)

#### Defined in

[sdk/src/posts/entry.ts:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L64)

___

### getFeedEntries

▸ **getFeedEntries**(`opt`): `Observable`<{ `data`: { `getCustomFeed`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `number` |

#### Returns

`Observable`<{ `data`: { `getCustomFeed`: [`PostsResult_Response`](../interfaces/akashaproject_awf_sdk._internal_.PostsResult_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[getFeedEntries](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#getfeedentries)

#### Defined in

[sdk/src/posts/entry.ts:299](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L299)

___

### getLinkPreview

▸ **getLinkPreview**(`link`): `Observable`<{ `data`: { `getLinkPreview`: [`LinkPreview_Response`](../interfaces/akashaproject_awf_sdk._internal_.LinkPreview_Response.md)  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `link` | `string` |

#### Returns

`Observable`<{ `data`: { `getLinkPreview`: [`LinkPreview_Response`](../interfaces/akashaproject_awf_sdk._internal_.LinkPreview_Response.md)  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[getLinkPreview](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#getlinkpreview)

#### Defined in

[sdk/src/posts/entry.ts:277](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L277)

___

### postEntry

▸ **postEntry**(`opt`): `Observable`<{ `data`: { `createPost`: `string`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.data` | [`DataProviderInput`](../interfaces/akashaproject_awf_sdk._internal_.DataProviderInput.md)[] |
| `opt.post` | `Object` |
| `opt.post.mentions?` | `string`[] |
| `opt.post.quotes?` | `string`[] |
| `opt.post.tags?` | `string`[] |
| `opt.post.title?` | `string` |

#### Returns

`Observable`<{ `data`: { `createPost`: `string`  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[postEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#postentry)

#### Defined in

[sdk/src/posts/entry.ts:104](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L104)

___

### removeEntry

▸ **removeEntry**(`entryID`): `Observable`<{ `data`: { `removePost`: `boolean`  }  }\>

Remove an entry's content by ID

#### Parameters

| Name | Type |
| :------ | :------ |
| `entryID` | `string` |

#### Returns

`Observable`<{ `data`: { `removePost`: `boolean`  }  }\>

#### Implementation of

[AWF_IEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md).[removeEntry](../interfaces/akashaproject_awf_sdk._internal_.AWF_IEntry.md#removeentry)

#### Defined in

[sdk/src/posts/entry.ts:241](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/entry.ts#L241)
