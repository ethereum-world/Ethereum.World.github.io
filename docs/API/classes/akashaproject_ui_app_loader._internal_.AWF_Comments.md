[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / AWF\_Comments

# Class: AWF\_Comments

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).AWF_Comments

## Implements

- [`AWF_IComments`](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.AWF_Comments.md#constructor)

### Properties

- [graphQLDocs](akashaproject_ui_app_loader._internal_.AWF_Comments.md#graphqldocs)

### Methods

- [addComment](akashaproject_ui_app_loader._internal_.AWF_Comments.md#addcomment)
- [editComment](akashaproject_ui_app_loader._internal_.AWF_Comments.md#editcomment)
- [getComment](akashaproject_ui_app_loader._internal_.AWF_Comments.md#getcomment)
- [getComments](akashaproject_ui_app_loader._internal_.AWF_Comments.md#getcomments)
- [removeComment](akashaproject_ui_app_loader._internal_.AWF_Comments.md#removecomment)

## Constructors

### constructor

• **new AWF_Comments**(`log`, `gql`, `auth`, `globalChannel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `log` | [`Logging`](akashaproject_ui_app_loader._internal_.Logging.md) |
| `gql` | [`Gql`](akashaproject_ui_app_loader._internal_.Gql.md) |
| `auth` | [`AWF_Auth`](akashaproject_ui_app_loader._internal_.AWF_Auth.md) |
| `globalChannel` | [`EventBus`](akashaproject_ui_app_loader._internal_.EventBus.md) |

#### Defined in

[sdk/src/posts/comments.ts:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L39)

## Properties

### graphQLDocs

• `Readonly` **graphQLDocs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AddComment` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `EditComment` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |
| `GetComment` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `GetComments` | [`TypedQueryDocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.TypedQueryDocumentNode.md)<[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>, [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `any`\>\> |
| `RemoveComment` | [`DocumentNode`](../interfaces/akashaproject_ui_app_loader._internal_.DocumentNode.md) |

#### Defined in

[sdk/src/posts/comments.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L31)

## Methods

### addComment

▸ **addComment**(`opt`): `Observable`<{ `data`: { `addComment`: `string`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.comment` | `Object` |
| `opt.comment.mentions?` | `string`[] |
| `opt.comment.postID` | `string` |
| `opt.comment.replyTo?` | `string` |
| `opt.comment.tags?` | `string`[] |
| `opt.data` | [`DataProviderInput`](../interfaces/akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`Observable`<{ `data`: { `addComment`: `string`  }  }\>

#### Implementation of

[AWF_IComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md).[addComment](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md#addcomment)

#### Defined in

[sdk/src/posts/comments.ts:85](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L85)

___

### editComment

▸ **editComment**(`opt`): `Observable`<{ `data`: { `editComment`: `boolean`  }  }\>

Update an existing comment

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.comment` | `Object` |
| `opt.comment.mentions?` | `string`[] |
| `opt.comment.postID` | `string` |
| `opt.comment.replyTo?` | `string` |
| `opt.comment.tags?` | `string`[] |
| `opt.commentID` | `string` |
| `opt.data` | [`DataProviderInput`](../interfaces/akashaproject_ui_app_loader._internal_.DataProviderInput.md)[] |

#### Returns

`Observable`<{ `data`: { `editComment`: `boolean`  }  }\>

#### Implementation of

[AWF_IComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md).[editComment](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md#editcomment)

#### Defined in

[sdk/src/posts/comments.ts:130](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L130)

___

### getComment

▸ **getComment**(`commentID`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getComment`: [`Comment_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Comment_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `commentID` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getComment`: [`Comment_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Comment_Response.md)  }\>

#### Implementation of

[AWF_IComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md).[getComment](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md#getcomment)

#### Defined in

[sdk/src/posts/comments.ts:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L55)

___

### getComments

▸ **getComments**(`opt`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getComments`: [`Comments_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Comments_Response.md)  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |
| `opt.postID` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<{ `getComments`: [`Comments_Response`](../interfaces/akashaproject_ui_app_loader._internal_.Comments_Response.md)  }\>

#### Implementation of

[AWF_IComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md).[getComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md#getcomments)

#### Defined in

[sdk/src/posts/comments.ts:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L70)

___

### removeComment

▸ **removeComment**(`commentID`): `Observable`<{ `data`: { `removeComment`: `boolean`  }  }\>

Remove a comment's data by ID

#### Parameters

| Name | Type |
| :------ | :------ |
| `commentID` | `string` |

#### Returns

`Observable`<{ `data`: { `removeComment`: `boolean`  }  }\>

#### Implementation of

[AWF_IComments](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md).[removeComment](../interfaces/akashaproject_ui_app_loader._internal_.AWF_IComments.md#removecomment)

#### Defined in

[sdk/src/posts/comments.ts:173](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/posts/comments.ts#L173)
