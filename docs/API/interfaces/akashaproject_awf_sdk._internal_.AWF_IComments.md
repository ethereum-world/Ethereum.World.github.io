[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_IComments

# Interface: AWF\_IComments

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_IComments

## Implemented by

- [`AWF_Comments`](../classes/akashaproject_awf_sdk._internal_.AWF_Comments.md)

## Table of contents

### Methods

- [addComment](akashaproject_awf_sdk._internal_.AWF_IComments.md#addcomment)
- [editComment](akashaproject_awf_sdk._internal_.AWF_IComments.md#editcomment)
- [getComment](akashaproject_awf_sdk._internal_.AWF_IComments.md#getcomment)
- [getComments](akashaproject_awf_sdk._internal_.AWF_IComments.md#getcomments)
- [removeComment](akashaproject_awf_sdk._internal_.AWF_IComments.md#removecomment)

## Methods

### addComment

▸ **addComment**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.comment` | `Object` |
| `opt.comment.mentions?` | `string`[] |
| `opt.comment.postID` | `string` |
| `opt.comment.replyTo?` | `string` |
| `opt.comment.tags?` | `string`[] |
| `opt.data` | [`DataProviderInput`](akashaproject_awf_sdk._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:86

___

### editComment

▸ **editComment**(`opt`): `unknown`

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
| `opt.data` | [`DataProviderInput`](akashaproject_awf_sdk._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:95

___

### getComment

▸ **getComment**(`commentID`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `commentID` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:72

___

### getComments

▸ **getComments**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |
| `opt.postID` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:77

___

### removeComment

▸ **removeComment**(`commentID`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `commentID` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:105
