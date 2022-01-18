[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IComments

# Interface: AWF\_IComments

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IComments

## Table of contents

### Methods

- [addComment](akashaproject_sdk_typings._internal_.AWF_IComments.md#addcomment)
- [editComment](akashaproject_sdk_typings._internal_.AWF_IComments.md#editcomment)
- [getComment](akashaproject_sdk_typings._internal_.AWF_IComments.md#getcomment)
- [getComments](akashaproject_sdk_typings._internal_.AWF_IComments.md#getcomments)
- [removeComment](akashaproject_sdk_typings._internal_.AWF_IComments.md#removecomment)

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
| `opt.data` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/posts.ts:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L72)

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
| `opt.data` | [`DataProviderInput`](akashaproject_sdk_typings._internal_.DataProviderInput.md)[] |

#### Returns

`unknown`

#### Defined in

[sdk/typings/src/interfaces/posts.ts:77](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L77)

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

[sdk/typings/src/interfaces/posts.ts:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L60)

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

[sdk/typings/src/interfaces/posts.ts:66](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L66)

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

[sdk/typings/src/interfaces/posts.ts:83](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/posts.ts#L83)
