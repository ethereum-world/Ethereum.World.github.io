[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_ITags

# Interface: AWF\_ITags

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_ITags

## Implemented by

- [`AWF_Tags`](../classes/akashaproject_awf_sdk._internal_.AWF_Tags.md)

## Table of contents

### Methods

- [createTag](akashaproject_awf_sdk._internal_.AWF_ITags.md#createtag)
- [getTag](akashaproject_awf_sdk._internal_.AWF_ITags.md#gettag)
- [getTags](akashaproject_awf_sdk._internal_.AWF_ITags.md#gettags)
- [getTrending](akashaproject_awf_sdk._internal_.AWF_ITags.md#gettrending)
- [searchTags](akashaproject_awf_sdk._internal_.AWF_ITags.md#searchtags)

## Methods

### createTag

▸ **createTag**(`tagName`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:130

___

### getTag

▸ **getTag**(`tagName`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tagName` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:112

___

### getTags

▸ **getTags**(`opt`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opt` | `Object` |
| `opt.limit` | `number` |
| `opt.offset?` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:117

___

### getTrending

▸ **getTrending**(): `unknown`

Returns most recent used tags

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:134

___

### searchTags

▸ **searchTags**(`name`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`unknown`

#### Defined in

sdk/typings/lib/interfaces/posts.d.ts:125
