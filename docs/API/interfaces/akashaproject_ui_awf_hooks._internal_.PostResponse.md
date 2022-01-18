[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / PostResponse

# Interface: PostResponse

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).PostResponse

## Hierarchy

- [`Post_Response`](akashaproject_ui_awf_hooks._internal_.Post_Response.md)

  ↳ **`PostResponse`**

## Table of contents

### Properties

- [\_id](akashaproject_ui_awf_hooks._internal_.PostResponse.md#_id)
- [author](akashaproject_ui_awf_hooks._internal_.PostResponse.md#author)
- [content](akashaproject_ui_awf_hooks._internal_.PostResponse.md#content)
- [creationDate](akashaproject_ui_awf_hooks._internal_.PostResponse.md#creationdate)
- [delisted](akashaproject_ui_awf_hooks._internal_.PostResponse.md#delisted)
- [isPublishing](akashaproject_ui_awf_hooks._internal_.PostResponse.md#ispublishing)
- [mentions](akashaproject_ui_awf_hooks._internal_.PostResponse.md#mentions)
- [moderated](akashaproject_ui_awf_hooks._internal_.PostResponse.md#moderated)
- [quotedBy](akashaproject_ui_awf_hooks._internal_.PostResponse.md#quotedby)
- [quotedByAuthors](akashaproject_ui_awf_hooks._internal_.PostResponse.md#quotedbyauthors)
- [quotes](akashaproject_ui_awf_hooks._internal_.PostResponse.md#quotes)
- [reason](akashaproject_ui_awf_hooks._internal_.PostResponse.md#reason)
- [reported](akashaproject_ui_awf_hooks._internal_.PostResponse.md#reported)
- [tags](akashaproject_ui_awf_hooks._internal_.PostResponse.md#tags)
- [title](akashaproject_ui_awf_hooks._internal_.PostResponse.md#title)
- [totalComments](akashaproject_ui_awf_hooks._internal_.PostResponse.md#totalcomments)
- [type](akashaproject_ui_awf_hooks._internal_.PostResponse.md#type)
- [updatedAt](akashaproject_ui_awf_hooks._internal_.PostResponse.md#updatedat)

## Properties

### \_id

• **\_id**: `string`

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[_id](akashaproject_ui_awf_hooks._internal_.Post_Response.md#_id)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:22

___

### author

• **author**: [`UserProfile_Response`](akashaproject_ui_awf_hooks._internal_.UserProfile_Response.md)

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[author](akashaproject_ui_awf_hooks._internal_.Post_Response.md#author)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:26

___

### content

• **content**: [[`DataProviderInput`](akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[content](akashaproject_ui_awf_hooks._internal_.Post_Response.md#content)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:28

___

### creationDate

• **creationDate**: `string`

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[creationDate](akashaproject_ui_awf_hooks._internal_.Post_Response.md#creationdate)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:24

___

### delisted

• `Optional` **delisted**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:8

___

### isPublishing

• `Optional` **isPublishing**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:9

___

### mentions

• **mentions**: [`string`]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[mentions](akashaproject_ui_awf_hooks._internal_.Post_Response.md#mentions)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:32

___

### moderated

• `Optional` **moderated**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:5

___

### quotedBy

• **quotedBy**: [`string`]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[quotedBy](akashaproject_ui_awf_hooks._internal_.Post_Response.md#quotedby)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:31

___

### quotedByAuthors

• **quotedByAuthors**: [[`UserProfile_Response`](akashaproject_ui_awf_hooks._internal_.UserProfile_Response.md)]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[quotedByAuthors](akashaproject_ui_awf_hooks._internal_.Post_Response.md#quotedbyauthors)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:34

___

### quotes

• **quotes**: [[`Post_Response`](akashaproject_ui_awf_hooks._internal_.Post_Response.md)]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[quotes](akashaproject_ui_awf_hooks._internal_.Post_Response.md#quotes)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:29

___

### reason

• `Optional` **reason**: `string`

#### Defined in

ui/typings/lib/entry.d.ts:6

___

### reported

• `Optional` **reported**: `boolean`

#### Defined in

ui/typings/lib/entry.d.ts:7

___

### tags

• **tags**: [`string`]

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[tags](akashaproject_ui_awf_hooks._internal_.Post_Response.md#tags)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:30

___

### title

• **title**: `string`

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[title](akashaproject_ui_awf_hooks._internal_.Post_Response.md#title)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:27

___

### totalComments

• **totalComments**: `string`

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[totalComments](akashaproject_ui_awf_hooks._internal_.Post_Response.md#totalcomments)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:33

___

### type

• **type**: [`PostType`](../enums/akashaproject_ui_awf_hooks._internal_.PostType.md)

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[type](akashaproject_ui_awf_hooks._internal_.Post_Response.md#type)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:23

___

### updatedAt

• **updatedAt**: `string`

#### Inherited from

[Post_Response](akashaproject_ui_awf_hooks._internal_.Post_Response.md).[updatedAt](akashaproject_ui_awf_hooks._internal_.Post_Response.md#updatedat)

#### Defined in

sdk/typings/lib/interfaces/responses.d.ts:25
