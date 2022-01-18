[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_Tags

# Class: AWF\_Tags

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_Tags

## Implements

- [`AWF_ITags`](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.AWF_Tags.md#constructor)

### Properties

- [graphQLDocs](akashaproject_ui_app_loader._internal_.AWF_Tags.md#graphqldocs)

### Methods

- [createTag](akashaproject_ui_app_loader._internal_.AWF_Tags.md#createtag)
- [getTag](akashaproject_ui_app_loader._internal_.AWF_Tags.md#gettag)
- [getTags](akashaproject_ui_app_loader._internal_.AWF_Tags.md#gettags)
- [getTrending](akashaproject_ui_app_loader._internal_.AWF_Tags.md#gettrending)
- [searchTags](akashaproject_ui_app_loader._internal_.AWF_Tags.md#searchtags)

## Constructors

### constructor

• **new AWF_Tags**(`log`, `gql`, `auth`, `globalChannel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_ui_app_loader._internal_.Logging.md) |
| `gql` | [`Gql`](akashaproject_ui_app_loader._internal_.Gql.md) |
| `auth` | [`AWF_Auth`](akashaproject_ui_app_loader._internal_.AWF_Auth.md) |
| `globalChannel` | [`EventBus`](akashaproject_ui_app_loader._internal_.EventBus.md) |

#### Defined in

[sdk/src/posts/tags.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L27)

## Properties

### graphQLDocs

• `Readonly` **graphQLDocs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `CreateTag` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `GetTag` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GetTags` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `SearchTags` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

[sdk/src/posts/tags.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L26)

## Methods

### createTag

▸ **createTag**(`tagName`): `Observable`<{ `data`: { `createTag`: `string`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`Observable`<{ `data`: { `createTag`: `string`  }  }\>

#### Implementation of

[AWF_ITags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md).[createTag](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md#createtag)

#### Defined in

[sdk/src/posts/tags.ts:88](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L88)

___

### getTag

▸ **getTag**(`tagName`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getTag`: [`Tag_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Tag_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getTag`: [`Tag_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Tag_Response.md)  }\>

#### Implementation of

[AWF_ITags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md).[getTag](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md#gettag)

#### Defined in

[sdk/src/posts/tags.ts:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L43)

___

### getTags

▸ **getTags**(`opt`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `tags`: [`TagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.TagsResult_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `tags`: [`TagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.TagsResult_Response.md)  }\>

#### Implementation of

[AWF_ITags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md).[getTags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md#gettags)

#### Defined in

[sdk/src/posts/tags.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L58)

___

### getTrending

▸ **getTrending**(): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchTags`: [`SearchTagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.SearchTagsResult_Response.md)[]  }\>

Returns most recent used tags

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchTags`: [`SearchTagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.SearchTagsResult_Response.md)[]  }\>

#### Implementation of

[AWF_ITags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md).[getTrending](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md#gettrending)

#### Defined in

[sdk/src/posts/tags.ts:124](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L124)

___

### searchTags

▸ **searchTags**(`name`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchTags`: [`SearchTagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.SearchTagsResult_Response.md)[]  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `searchTags`: [`SearchTagsResult_Response`](../interfaces/akashaproject_ui_app_loader._internal_.SearchTagsResult_Response.md)[]  }\>

#### Implementation of

[AWF_ITags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md).[searchTags](../interfaces/akashaproject_ui_app_loader._internal_.AWF_ITags.md#searchtags)

#### Defined in

[sdk/src/posts/tags.ts:73](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/tags.ts#L73)
