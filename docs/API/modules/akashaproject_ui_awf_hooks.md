[AWF](../README.md) / [Modules](../modules.md) / @akashaproject/ui-awf-hooks

# Module: @akashaproject/ui-awf-hooks

## Table of contents

### Namespaces

- [&lt;internal\&gt;](akashaproject_ui_awf_hooks._internal_.md)

### Enumerations

- [CookieConsentTypes](../enums/akashaproject_ui_awf_hooks.CookieConsentTypes.md)

### Interfaces

- [EntryReport](../interfaces/akashaproject_ui_awf_hooks.EntryReport.md)
- [FormProfileData](../interfaces/akashaproject_ui_awf_hooks.FormProfileData.md)
- [ICount](../interfaces/akashaproject_ui_awf_hooks.ICount.md)
- [ILogItem](../interfaces/akashaproject_ui_awf_hooks.ILogItem.md)
- [IModeratedItem](../interfaces/akashaproject_ui_awf_hooks.IModeratedItem.md)
- [IPendingItem](../interfaces/akashaproject_ui_awf_hooks.IPendingItem.md)
- [LoginState](../interfaces/akashaproject_ui_awf_hooks.LoginState.md)

### Properties

- [constants](akashaproject_ui_awf_hooks.md#constants)

### Variables

- [COMMENTS\_KEY](akashaproject_ui_awf_hooks.md#comments_key)
- [COMMENT\_KEY](akashaproject_ui_awf_hooks.md#comment_key)
- [CREATE\_POST\_MUTATION\_KEY](akashaproject_ui_awf_hooks.md#create_post_mutation_key)
- [ENTRY\_KEY](akashaproject_ui_awf_hooks.md#entry_key)
- [PROFILE\_KEY](akashaproject_ui_awf_hooks.md#profile_key)
- [UPDATE\_PROFILE\_STATUS](akashaproject_ui_awf_hooks.md#update_profile_status)

### Functions

- [createPendingEntry](akashaproject_ui_awf_hooks.md#creatependingentry)
- [getLinkPreview](akashaproject_ui_awf_hooks.md#getlinkpreview)
- [getMediaUrl](akashaproject_ui_awf_hooks.md#getmediaurl)
- [mapEntry](akashaproject_ui_awf_hooks.md#mapentry)
- [switchToRequiredNetwork](akashaproject_ui_awf_hooks.md#switchtorequirednetwork)
- [uploadMediaToTextile](akashaproject_ui_awf_hooks.md#uploadmediatotextile)
- [useAnalytics](akashaproject_ui_awf_hooks.md#useanalytics)
- [useCheckModerator](akashaproject_ui_awf_hooks.md#usecheckmoderator)
- [useCheckNewNotifications](akashaproject_ui_awf_hooks.md#usechecknewnotifications)
- [useComment](akashaproject_ui_awf_hooks.md#usecomment)
- [useConnectProvider](akashaproject_ui_awf_hooks.md#useconnectprovider)
- [useCreateComment](akashaproject_ui_awf_hooks.md#usecreatecomment)
- [useCreatePost](akashaproject_ui_awf_hooks.md#usecreatepost)
- [useDeleteBookmark](akashaproject_ui_awf_hooks.md#usedeletebookmark)
- [useDeleteComment](akashaproject_ui_awf_hooks.md#usedeletecomment)
- [useDeletePost](akashaproject_ui_awf_hooks.md#usedeletepost)
- [useEditComment](akashaproject_ui_awf_hooks.md#useeditcomment)
- [useEditPost](akashaproject_ui_awf_hooks.md#useeditpost)
- [useEnsByAddress](akashaproject_ui_awf_hooks.md#useensbyaddress)
- [useEnsRegistration](akashaproject_ui_awf_hooks.md#useensregistration)
- [useFetchNotifications](akashaproject_ui_awf_hooks.md#usefetchnotifications)
- [useFollow](akashaproject_ui_awf_hooks.md#usefollow)
- [useFollowers](akashaproject_ui_awf_hooks.md#usefollowers)
- [useFollowing](akashaproject_ui_awf_hooks.md#usefollowing)
- [useGetBookmarks](akashaproject_ui_awf_hooks.md#usegetbookmarks)
- [useGetCount](akashaproject_ui_awf_hooks.md#usegetcount)
- [useGetEntryAuthor](akashaproject_ui_awf_hooks.md#usegetentryauthor)
- [useGetFlags](akashaproject_ui_awf_hooks.md#usegetflags)
- [useGetLogin](akashaproject_ui_awf_hooks.md#usegetlogin)
- [useGetProfile](akashaproject_ui_awf_hooks.md#usegetprofile)
- [useGetTag](akashaproject_ui_awf_hooks.md#usegettag)
- [useGlobalLogin](akashaproject_ui_awf_hooks.md#usegloballogin)
- [useHandleNavigation](akashaproject_ui_awf_hooks.md#usehandlenavigation)
- [useInfiniteComments](akashaproject_ui_awf_hooks.md#useinfinitecomments)
- [useInfiniteDelisted](akashaproject_ui_awf_hooks.md#useinfinitedelisted)
- [useInfiniteKept](akashaproject_ui_awf_hooks.md#useinfinitekept)
- [useInfiniteLog](akashaproject_ui_awf_hooks.md#useinfinitelog)
- [useInfinitePending](akashaproject_ui_awf_hooks.md#useinfinitepending)
- [useInfinitePosts](akashaproject_ui_awf_hooks.md#useinfiniteposts)
- [useInfinitePostsByAuthor](akashaproject_ui_awf_hooks.md#useinfinitepostsbyauthor)
- [useInfinitePostsByTag](akashaproject_ui_awf_hooks.md#useinfinitepostsbytag)
- [useInjectedProvider](akashaproject_ui_awf_hooks.md#useinjectedprovider)
- [useInterests](akashaproject_ui_awf_hooks.md#useinterests)
- [useIsFollowingMultiple](akashaproject_ui_awf_hooks.md#useisfollowingmultiple)
- [useIsSubscribedToTag](akashaproject_ui_awf_hooks.md#useissubscribedtotag)
- [useIsValidToken](akashaproject_ui_awf_hooks.md#useisvalidtoken)
- [useLegalDoc](akashaproject_ui_awf_hooks.md#uselegaldoc)
- [useLogin](akashaproject_ui_awf_hooks.md#uselogin)
- [useLogout](akashaproject_ui_awf_hooks.md#uselogout)
- [useMarkAsRead](akashaproject_ui_awf_hooks.md#usemarkasread)
- [useMentionSearch](akashaproject_ui_awf_hooks.md#usementionsearch)
- [useModeration](akashaproject_ui_awf_hooks.md#usemoderation)
- [useMutationListener](akashaproject_ui_awf_hooks.md#usemutationlistener)
- [useNetworkState](akashaproject_ui_awf_hooks.md#usenetworkstate)
- [usePost](akashaproject_ui_awf_hooks.md#usepost)
- [useProfileUpdate](akashaproject_ui_awf_hooks.md#useprofileupdate)
- [useQueryListener](akashaproject_ui_awf_hooks.md#usequerylistener)
- [useReasons](akashaproject_ui_awf_hooks.md#usereasons)
- [useReport](akashaproject_ui_awf_hooks.md#usereport)
- [useRequiredNetworkName](akashaproject_ui_awf_hooks.md#userequirednetworkname)
- [useSaveBookmark](akashaproject_ui_awf_hooks.md#usesavebookmark)
- [useSearch](akashaproject_ui_awf_hooks.md#usesearch)
- [useSearchComments](akashaproject_ui_awf_hooks.md#usesearchcomments)
- [useSearchPosts](akashaproject_ui_awf_hooks.md#usesearchposts)
- [useSearchProfiles](akashaproject_ui_awf_hooks.md#usesearchprofiles)
- [useSearchTags](akashaproject_ui_awf_hooks.md#usesearchtags)
- [useTagSearch](akashaproject_ui_awf_hooks.md#usetagsearch)
- [useTagSubscriptions](akashaproject_ui_awf_hooks.md#usetagsubscriptions)
- [useToggleTagSubscription](akashaproject_ui_awf_hooks.md#usetoggletagsubscription)
- [useTrendingProfiles](akashaproject_ui_awf_hooks.md#usetrendingprofiles)
- [useTrendingTags](akashaproject_ui_awf_hooks.md#usetrendingtags)
- [useUnfollow](akashaproject_ui_awf_hooks.md#useunfollow)
- [useUpdateUsernameProvider](akashaproject_ui_awf_hooks.md#useupdateusernameprovider)
- [useUsernameValidation](akashaproject_ui_awf_hooks.md#useusernamevalidation)
- [withProviders](akashaproject_ui_awf_hooks.md#withproviders)

## Properties

### constants

• **constants**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `BASE_DECISION_URL` | `string` |
| `BASE_MODERATOR_URL` | `string` |
| `BASE_REASONS_URL` | `string` |
| `BASE_REPORT_URL` | `string` |
| `BASE_STATUS_URL` | `string` |
| `CHECK_MODERATOR_KEY` | `string` |
| `CONNECT_PROVIDER_KEY` | `string` |
| `DEFAULT_FETCH_TIMEOUT` | `number` |
| `DELISTED_ITEMS_KEY` | `string` |
| `INJECTED_PROVIDER_KEY` | `string` |
| `KEPT_ITEMS_KEY` | `string` |
| `LOG_ITEMS_KEY` | `string` |
| `MODERATED_CACHE_KEY_PREFIX` | `string` |
| `MODERATION_COUNT_CACHE_KEY_PREFIX` | `string` |
| `MODERATION_ITEMS_COUNT_KEY` | `string` |
| `MODERATION_ITEM_FLAGS_KEY` | `string` |
| `MODERATION_STATUS_KEY` | `string` |
| `PENDING_CACHE_KEY_PREFIX` | `string` |
| `PENDING_ITEMS_KEY` | `string` |
| `REQUIRED_NETWORK_KEY` | `string` |
| `TOKEN_VALIDATION_KEY` | `string` |

## Variables

### COMMENTS\_KEY

• **COMMENTS\_KEY**: ``"Comments"``

#### Defined in

[ui/hooks/src/use-comments.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L20)

___

### COMMENT\_KEY

• **COMMENT\_KEY**: ``"Comment"``

#### Defined in

[ui/hooks/src/use-comments.ts:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L19)

___

### CREATE\_POST\_MUTATION\_KEY

• **CREATE\_POST\_MUTATION\_KEY**: ``"CreatePost"``

#### Defined in

[ui/hooks/src/use-posts.ts:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L18)

___

### ENTRY\_KEY

• **ENTRY\_KEY**: ``"Entry"``

#### Defined in

[ui/hooks/src/use-posts.ts:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L14)

___

### PROFILE\_KEY

• **PROFILE\_KEY**: ``"PROFILE"``

#### Defined in

[ui/hooks/src/use-profile.ts:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L18)

___

### UPDATE\_PROFILE\_STATUS

• **UPDATE\_PROFILE\_STATUS**: ``"UPDATE_PROFILE_STATUS"``

#### Defined in

[ui/hooks/src/use-profile.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L23)

## Functions

### createPendingEntry

▸ `Const` **createPendingEntry**(`author`, `entryPublishData`): [`PendingEntry`](../interfaces/akashaproject_ui_awf_hooks._internal_.PendingEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `author` | [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md) |
| `entryPublishData` | [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `entryId?`: `string`  } |

#### Returns

[`PendingEntry`](../interfaces/akashaproject_ui_awf_hooks._internal_.PendingEntry.md)

#### Defined in

[ui/hooks/src/utils/entry-utils.ts:173](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/entry-utils.ts#L173)

___

### getLinkPreview

▸ `Const` **getLinkPreview**(`url`): `Promise`<[`LinkPreview_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.LinkPreview_Response.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`Promise`<[`LinkPreview_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.LinkPreview_Response.md)\>

#### Defined in

[ui/hooks/src/utils/media-utils.ts:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/media-utils.ts#L80)

___

### getMediaUrl

▸ `Const` **getMediaUrl**(`hash?`, `data?`): `string`

Utility to append an ipfs gateway to an ipfs hash

#### Parameters

| Name | Type |
| :------ | :------ |
| `hash?` | `string` |
| `data?` | `any` |

#### Returns

`string`

#### Defined in

[ui/hooks/src/utils/media-utils.ts:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/media-utils.ts#L15)

___

### mapEntry

▸ `Const` **mapEntry**(`entry`, `logger?`): [`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)

Remap entry data coming from a response to the format expected by EntryCard
content - from b64 to slate format
profile images - append ipfs gateway
entry images - append ipfs gateway

#### Parameters

| Name | Type |
| :------ | :------ |
| `entry` | [`PostResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.PostResponse.md) \| [`CommentResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.CommentResponse.md) |
| `logger?` | [`ILogger`](../interfaces/akashaproject_ui_awf_hooks._internal_.ILogger.md) |

#### Returns

[`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)

#### Defined in

[ui/hooks/src/utils/entry-utils.ts:71](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/entry-utils.ts#L71)

___

### switchToRequiredNetwork

▸ `Const` **switchToRequiredNetwork**(): `Promise`<`void`\>

An utility function to switch to required network - Metamask

#### Returns

`Promise`<`void`\>

#### Defined in

[ui/hooks/src/use-injected-provider.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-injected-provider.ts#L38)

___

### uploadMediaToTextile

▸ `Const` **uploadMediaToTextile**(`data`, `isUrl?`): `Promise`<{ `data`: { `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } = res.size; `src`: `string`  } ; `error`: `undefined` = error } \| { `data`: `undefined` ; `error`: `any` = error }\>

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `data` | `any` | `undefined` |
| `isUrl` | `boolean` | `false` |

#### Returns

`Promise`<{ `data`: { `size`: { `height`: `number` ; `naturalHeight`: `number` ; `naturalWidth`: `number` ; `width`: `number`  } = res.size; `src`: `string`  } ; `error`: `undefined` = error } \| { `data`: `undefined` ; `error`: `any` = error }\>

#### Defined in

[ui/hooks/src/utils/media-utils.ts:41](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/media-utils.ts#L41)

___

### useAnalytics

▸ `Const` **useAnalytics**(): [[`UseAnalyticsState`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseAnalyticsState.md), [`UseAnalyticsActions`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md)]

#### Returns

[[`UseAnalyticsState`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseAnalyticsState.md), [`UseAnalyticsActions`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseAnalyticsActions.md)]

#### Defined in

[ui/hooks/src/use-analytics.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-analytics.ts#L28)

___

### useCheckModerator

▸ **useCheckModerator**(`loggedUser`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to check if a user is a moderator

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `loggedUser` | `string` | textile public key of the user |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:188](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L188)

___

### useCheckNewNotifications

▸ **useCheckNewNotifications**(`loggedEthAddress`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to check for new notifications

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `loggedEthAddress` | `string` | currently logged in user's eth address |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-notifications.ts:119](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-notifications.ts#L119)

___

### useComment

▸ **useComment**(`commentID`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`CommentResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.CommentResponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook for fetching data for a specific comment

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `commentID` | `string` | `undefined` | id of comment to fetch data for |
| `enabler` | `boolean` | `true` | flag for allowing the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`CommentResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.CommentResponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-comments.ts:90](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L90)

___

### useConnectProvider

▸ **useConnectProvider**(`provider`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, `unknown`\>

A hook to connect to injected provider

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_ui_awf_hooks._internal_.EthProviders.md) | -: any of type EthProviders |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, `unknown`\>

#### Defined in

[ui/hooks/src/use-injected-provider.ts:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-injected-provider.ts#L64)

___

### useCreateComment

▸ **useCreateComment**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }, { `entryId`: `string` = pendingID; `optimisticComment`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }  }\>

Hook for creating a new comment

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }, { `entryId`: `string` = pendingID; `optimisticComment`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }  }\>

#### Defined in

[ui/hooks/src/use-comments.ts:174](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L174)

___

### useCreatePost

▸ **useCreatePost**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md), { `entryId`: `string` = pendingID; `optimisticEntry`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `isPublishing`: `boolean` = true }  }\>

Hook to create a new post
pass the publish data from the editor to the mutate function

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md), { `entryId`: `string` = pendingID; `optimisticEntry`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `isPublishing`: `boolean` = true }  }\>

#### Defined in

[ui/hooks/src/use-posts.ts:235](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L235)

___

### useDeleteBookmark

▸ **useDeleteBookmark**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: `string`[]  }, `unknown`, `string`, { `prevBmks`: { `entryId`: `string` ; `type`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }[]  }\>

Hook used to delete a bookmark

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: `string`[]  }, `unknown`, `string`, { `prevBmks`: { `entryId`: `string` ; `type`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }[]  }\>

#### Defined in

[ui/hooks/src/use-bookmarks.ts:93](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-bookmarks.ts#L93)

___

### useDeleteComment

▸ **useDeleteComment**(`commentID`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<``true``, `unknown`, `string`, { `previousComment`: [`CommentResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.CommentResponse.md)  }\>

Hook for deleting a specific comment

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `commentID` | `string` | id of the comment to be deleted |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<``true``, `unknown`, `string`, { `previousComment`: [`CommentResponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.CommentResponse.md)  }\>

#### Defined in

[ui/hooks/src/use-comments.ts:121](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L121)

___

### useDeletePost

▸ **useDeletePost**(`postID`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `removePost`: `boolean`  }  }, `unknown`, `string`, { `previousPost`: [`Post_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Post_Response.md)  }\>

Hook to delete a post

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `postID` | `string` | id of the post to be deleted |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `removePost`: `boolean`  }  }, `unknown`, `string`, { `previousPost`: [`Post_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Post_Response.md)  }\>

#### Defined in

[ui/hooks/src/use-posts.ts:175](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L175)

___

### useEditComment

▸ **useEditComment**(`commentID`, `hasCommentData`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void` \| { `data`: { `editComment`: `boolean`  }  }, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }, { `comment`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }  }\>

Hook for editing a comment

#### Parameters

| Name | Type |
| :------ | :------ |
| `commentID` | `string` |
| `hasCommentData` | `boolean` |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void` \| { `data`: { `editComment`: `boolean`  }  }, `unknown`, [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }, { `comment`: [`IPublishData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IPublishData.md) & { `postID`: `string`  }  }\>

#### Defined in

[ui/hooks/src/use-comments.ts:219](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L219)

___

### useEditPost

▸ `Const` **useEditPost**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), `any`, { `editedPost`: `any`  }\>

Hook to edit a post
pass the edited post data to the mutation function

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), `any`, { `editedPost`: `any`  }\>

#### Defined in

[ui/hooks/src/use-posts.ts:283](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L283)

___

### useEnsByAddress

▸ **useEnsByAddress**(`ethAddress`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to resolve an ethAddress to an ENS name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ethAddress` | `string` | ethereum address to resolve |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-username.ts:212](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-username.ts#L212)

___

### useEnsRegistration

▸ **useEnsRegistration**(`pubKey?`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `makeDefaultProvider`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `userName`: `string`  }, { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

Hook to register a new ENS name

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey?` | `string` | textile public key of the user |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `makeDefaultProvider`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `userName`: `string`  }, { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

#### Defined in

[ui/hooks/src/use-username.ts:144](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-username.ts#L144)

___

### useFetchNotifications

▸ **useFetchNotifications**(`loggedEthAddress`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get a user's notifications

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `loggedEthAddress` | `string` | currently logged in user's eth address |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-notifications.ts:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-notifications.ts#L60)

___

### useFollow

▸ **useFollow**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `follow`: `boolean`  }  }, `unknown`, `string`, { `previousFollowedProfiles`: `string`[]  }\>

Hook to follow another user

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `follow`: `boolean`  }  }, `unknown`, `string`, { `previousFollowedProfiles`: `string`[]  }\>

#### Defined in

[ui/hooks/src/use-follow.ts:153](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-follow.ts#L153)

___

### useFollowers

▸ **useFollowers**(`pubKey`, `limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`UserFollowers_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserFollowers_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get followers for a user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey` | `string` | textile generated public key of the user |
| `limit` | `number` | number of followers to return per page |
| `offset?` | `number` | offset for query |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`UserFollowers_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserFollowers_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-profile.ts:116](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L116)

___

### useFollowing

▸ **useFollowing**(`pubKey`, `limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`UserFollowers_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserFollowers_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get a list of profiles following the user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey` | `string` | textile generated public key of the user |
| `limit` | `number` | number of profiles following the user to return per page |
| `offset?` | `number` | offset for query |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`UserFollowers_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserFollowers_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-profile.ts:145](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L145)

___

### useGetBookmarks

▸ **useGetBookmarks**(`loggedEthAddress`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, `unknown`\>

Hook for gettting a user's saved posts and comments

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `loggedEthAddress` | `string` | `undefined` | currently logged in user's ethereum address |
| `enabler` | `boolean` | `true` | flag for allowing the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, `unknown`\>

#### Defined in

[ui/hooks/src/use-bookmarks.ts:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-bookmarks.ts#L16)

___

### useGetCount

▸ **useGetCount**(): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `delisted`: `number` = 0; `kept`: `number` = 0; `pending`: `number` = 0 }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get moderation counters

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `delisted`: `number` = 0; `kept`: `number` = 0; `pending`: `number` = 0 }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:199](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L199)

___

### useGetEntryAuthor

▸ **useGetEntryAuthor**(`entryId`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get an entry author's profile data

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entryId` | `string` | the id of the specific post |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-profile.ts:91](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L91)

___

### useGetFlags

▸ **useGetFlags**(`entryId`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`EntryReport`](../interfaces/akashaproject_ui_awf_hooks.EntryReport.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get report flags for a specific entry

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entryId` | `string` | id of the entry |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`EntryReport`](../interfaces/akashaproject_ui_awf_hooks.EntryReport.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:210](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L210)

___

### useGetLogin

▸ **useGetLogin**(`onError?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`LoginState`](../interfaces/akashaproject_ui_awf_hooks.LoginState.md), `unknown`\>

Hook for retrieving the current authentication state of the user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `onError?` | (`error`: [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)) => `void` | outside error handler |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`LoginState`](../interfaces/akashaproject_ui_awf_hooks.LoginState.md), `unknown`\>

#### Defined in

[ui/hooks/src/use-login.ts:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-login.ts#L42)

___

### useGetProfile

▸ **useGetProfile**(`pubKey`, `loggedUser?`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get a user's profile data

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `pubKey` | `string` | `undefined` | the textile generated public key of the user |
| `loggedUser?` | `string` | `undefined` | the textile generated public key of the currently logged in user |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-profile.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L58)

___

### useGetTag

▸ **useGetTag**(`tagName`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`Tag_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Tag_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get a specific tag by name

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `tagName` | `string` | `undefined` | name of the tag |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`Tag_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Tag_Response.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-tag.ts:120](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-tag.ts#L120)

___

### useGlobalLogin

▸ `Const` **useGlobalLogin**(`props`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`UseGlobalLoginProps`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseGlobalLoginProps.md) |

#### Returns

`void`

#### Defined in

[ui/hooks/src/use-global-login.ts:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-global-login.ts#L24)

___

### useHandleNavigation

▸ `Const` **useHandleNavigation**(`navigateFn`, `currentPostId?`): (`navigationDetails`: [`IContentClickDetails`](../interfaces/akashaproject_ui_awf_hooks._internal_.IContentClickDetails.md), `itemType`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)) => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `navigateFn` | (`url`: `string`) => `void` |
| `currentPostId?` | `string` |

#### Returns

`fn`

▸ (`navigationDetails`, `itemType`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `navigationDetails` | [`IContentClickDetails`](../interfaces/akashaproject_ui_awf_hooks._internal_.IContentClickDetails.md) |
| `itemType` | [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md) |

##### Returns

`void`

#### Defined in

[ui/hooks/src/use-navigation.ts:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-navigation.ts#L15)

___

### useInfiniteComments

▸ **useInfiniteComments**(`limit`, `postID`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get the comments for a specific post

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `limit` | `number` | number of comments to fetch on a page |
| `postID` | `string` | id of the parent post |
| `offset?` | `string` | id of where to start |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-comments.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-comments.ts#L48)

___

### useInfiniteDelisted

▸ **useInfiniteDelisted**(`limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`ModeratedItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.ModeratedItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get delisted moderated items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `limit` | `number` | number of items per page |
| `offset?` | `string` | index of query offset |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`ModeratedItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.ModeratedItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:289](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L289)

___

### useInfiniteKept

▸ **useInfiniteKept**(`limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`ModeratedItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.ModeratedItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get kept moderated items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `limit` | `number` | number of items per page |
| `offset?` | `string` | index of query offset |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`ModeratedItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.ModeratedItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:265](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L265)

___

### useInfiniteLog

▸ **useInfiniteLog**(`limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`LogItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.LogItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get log of moderated items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `limit` | `number` | number of items per page |
| `offset?` | `string` | index of query offset |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`LogItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.LogItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:223](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L223)

___

### useInfinitePending

▸ **useInfinitePending**(`limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`PendingItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.PendingItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get pending moderation items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `limit` | `number` | number of items per page |
| `offset?` | `string` | index of query offset |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<[`PendingItemsReponse`](../interfaces/akashaproject_ui_awf_hooks._internal_.PendingItemsReponse.md), [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-moderation.ts:246](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L246)

___

### useInfinitePosts

▸ **useInfinitePosts**(`limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get posts for feed, sorted chronologically

#### Parameters

| Name | Type |
| :------ | :------ |
| `limit` | `number` |
| `offset?` | `string` |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-posts.ts:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L45)

___

### useInfinitePostsByAuthor

▸ **useInfinitePostsByAuthor**(`pubKey`, `limit`, `enabled?`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get an author's posts

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `pubKey` | `string` | `undefined` | textile public key of the user |
| `limit` | `number` | `undefined` | - |
| `enabled` | `boolean` | `true` | - |
| `offset?` | `number` | `undefined` | - |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-posts.ts:119](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L119)

___

### useInfinitePostsByTag

▸ **useInfinitePostsByTag**(`name`, `limit`, `offset?`): [`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get posts that contain a specific tag

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | tag name |
| `limit` | `number` | - |
| `offset?` | `string` | - |

#### Returns

[`UseInfiniteQueryResult`](akashaproject_ui_awf_hooks._internal_.md#useinfinitequeryresult)<{ `nextIndex`: `string` ; `results`: `string`[] ; `total`: `number`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-posts.ts:83](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L83)

___

### useInjectedProvider

▸ **useInjectedProvider**(): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `details`: { `iconType`: `string` = ''; `subtitleLabel`: `string` = ''; `titleLabel`: `string` = '' } ; `name`: [`INJECTED_PROVIDERS`](../enums/akashaproject_ui_awf_hooks._internal_.INJECTED_PROVIDERS.md) = INJECTED\_PROVIDERS.NOT\_DETECTED }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

A hook to get injected provider from the SDK

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `details`: { `iconType`: `string` = ''; `subtitleLabel`: `string` = ''; `titleLabel`: `string` = '' } ; `name`: [`INJECTED_PROVIDERS`](../enums/akashaproject_ui_awf_hooks._internal_.INJECTED_PROVIDERS.md) = INJECTED\_PROVIDERS.NOT\_DETECTED }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-injected-provider.ts:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-injected-provider.ts#L46)

___

### useInterests

▸ **useInterests**(`pubKey`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`Tag_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Tag_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Fetch the list of subscribed tags for a specific pub key

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey` | `any` | the textile generated public key of the user |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`Tag_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Tag_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-profile.ts:182](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L182)

___

### useIsFollowingMultiple

▸ **useIsFollowingMultiple**(`followerEthAddress`, `followingEthAddressArray`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to check if a user is following other users

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `followerEthAddress` | `string` | ethereum address of user to check for |
| `followingEthAddressArray` | `string`[] | array of ethereum addresses to check if followed |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-follow.ts:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-follow.ts#L57)

___

### useIsSubscribedToTag

▸ **useIsSubscribedToTag**(`tagName`, `loggedEthAddress`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to check if a user subscribes to a tag

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagName` | `string` | name of the tag |
| `loggedEthAddress` | `string` | eth address of the logged in user |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`boolean`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-tag.ts:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-tag.ts#L42)

___

### useIsValidToken

▸ **useIsValidToken**(`props`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`void`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`IUseIsValidTokenProps`](../interfaces/akashaproject_ui_awf_hooks._internal_.IUseIsValidTokenProps.md) |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`void`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-invite-token-validation.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-invite-token-validation.ts#L22)

___

### useLegalDoc

▸ **useLegalDoc**(`docName`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get legal docs stored on ipfs

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `docName` | [`LEGAL_DOCS`](../enums/akashaproject_ui_awf_hooks._internal_.LEGAL_DOCS.md) | type of document to retrieve |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-legal.ts:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-legal.ts#L19)

___

### useLogin

▸ **useLogin**(`onError?`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<[`CurrentUser`](../interfaces/akashaproject_ui_awf_hooks._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `checkRegistered`: `boolean` ; `selectedProvider`: [`EthProviders`](../enums/akashaproject_ui_awf_hooks._internal_.EthProviders.md)  }, `unknown`\>

Hook to sign in a user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `onError?` | (`err`: [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)) => `void` | outside error handler |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<[`CurrentUser`](../interfaces/akashaproject_ui_awf_hooks._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `checkRegistered`: `boolean` ; `selectedProvider`: [`EthProviders`](../enums/akashaproject_ui_awf_hooks._internal_.EthProviders.md)  }, `unknown`\>

#### Defined in

[ui/hooks/src/use-login.ts:104](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-login.ts#L104)

___

### useLogout

▸ **useLogout**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<``true``, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), `void`, `unknown`\>

Hook to sign out the current user

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<``true``, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), `void`, `unknown`\>

#### Defined in

[ui/hooks/src/use-login.ts:250](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-login.ts#L250)

___

### useMarkAsRead

▸ **useMarkAsRead**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: `boolean`  }, `unknown`, `string`, { `previousCheckNotifs`: `boolean` ; `previousNotifs`: `any`  }\>

Hook to mark a notification as read
pass the messageId to the mutate function

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: `boolean`  }, `unknown`, `string`, { `previousCheckNotifs`: `boolean` ; `previousNotifs`: `any`  }\>

#### Defined in

[ui/hooks/src/use-notifications.ts:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-notifications.ts#L72)

___

### useMentionSearch

▸ **useMentionSearch**(`mention`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for profiles

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mention` | `string` | profile name to search for |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-mentions.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-mentions.ts#L38)

___

### useModeration

▸ **useModeration**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), [`UseModerationParam`](akashaproject_ui_awf_hooks._internal_.md#usemoderationparam), `unknown`\>

Hook for creating a moderation decision

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), [`UseModerationParam`](akashaproject_ui_awf_hooks._internal_.md#usemoderationparam), `unknown`\>

#### Defined in

[ui/hooks/src/use-moderation.ts:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L72)

___

### useMutationListener

▸ `Const` **useMutationListener**<`TVars`\>(`mutationKey`): [`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `TVars`, `unknown`\>

Hook to detect changes to a mutation

#### Type parameters

| Name |
| :------ |
| `TVars` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mutationKey` | [`MutationKey`](akashaproject_ui_awf_hooks._internal_.md#mutationkey) | the key of the mutation to listen to |

#### Returns

[`Mutation`](../classes/akashaproject_ui_awf_hooks._internal_.Mutation.md)<`unknown`, `unknown`, `TVars`, `unknown`\>

Mutation | undefined

#### Defined in

[ui/hooks/src/use-query-listener.ts:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-query-listener.ts#L16)

___

### useNetworkState

▸ **useNetworkState**(`enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `networkNotSupported`: `boolean` = true }, `unknown`\>

Hook to check if the web3 provider is set to function on the Rinkeby test network

#### Parameters

| Name | Type |
| :------ | :------ |
| `enabler?` | `boolean` |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `networkNotSupported`: `boolean` = true }, `unknown`\>

networkNotSupported: true if web3 provider on another network

#### Defined in

[ui/hooks/src/use-network-state.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-network-state.ts#L22)

___

### usePost

▸ **usePost**(`__namedParameters`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `_id`: `string` ; `author`: { `_id`: `string` ; `avatar`: `string` ; `contentId`: `string` ; `coverImage`: `string` ; `creationDate`: `string` ; `default`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `delisted`: `boolean` ; `description`: `string` ; `ethAddress`: `string` ; `moderated`: `boolean` ; `name`: `string` ; `providers`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `pubKey`: `string` ; `reason`: `string` ; `reported`: `boolean` ; `totalFollowers`: `number` ; `totalFollowing`: `number` ; `totalInterests`: `number` ; `totalPosts`: `string` ; `userName`: `string`  } ; `content`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `contentId`: `string` ; `creationDate`: `string` ; `delisted`: `boolean` ; `mentions`: [`string`] ; `moderated`: `boolean` ; `quotedBy`: [`string`] ; `quotedByAuthors`: [[`UserProfile_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserProfile_Response.md)] ; `quotes`: [[`Post_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Post_Response.md)] ; `reason`: `string` ; `reported`: `boolean` ; `tags`: [`string`] ; `title`: `string` ; `totalComments`: `string` ; `type`: [`PostType`](../enums/akashaproject_ui_awf_hooks._internal_.PostType.md) ; `updatedAt`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get data for a specific post

#### Parameters

| Name | Type |
| :------ | :------ |
| `__namedParameters` | [`usePostParam`](akashaproject_ui_awf_hooks._internal_.md#usepostparam) |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `_id`: `string` ; `author`: { `_id`: `string` ; `avatar`: `string` ; `contentId`: `string` ; `coverImage`: `string` ; `creationDate`: `string` ; `default`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `delisted`: `boolean` ; `description`: `string` ; `ethAddress`: `string` ; `moderated`: `boolean` ; `name`: `string` ; `providers`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `pubKey`: `string` ; `reason`: `string` ; `reported`: `boolean` ; `totalFollowers`: `number` ; `totalFollowing`: `number` ; `totalInterests`: `number` ; `totalPosts`: `string` ; `userName`: `string`  } ; `content`: [[`DataProviderInput`](../interfaces/akashaproject_ui_awf_hooks._internal_.DataProviderInput.md)] ; `contentId`: `string` ; `creationDate`: `string` ; `delisted`: `boolean` ; `mentions`: [`string`] ; `moderated`: `boolean` ; `quotedBy`: [`string`] ; `quotedByAuthors`: [[`UserProfile_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.UserProfile_Response.md)] ; `quotes`: [[`Post_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.Post_Response.md)] ; `reason`: `string` ; `reported`: `boolean` ; `tags`: [`string`] ; `title`: `string` ; `totalComments`: `string` ; `type`: [`PostType`](../enums/akashaproject_ui_awf_hooks._internal_.PostType.md) ; `updatedAt`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-posts.ts:163](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-posts.ts#L163)

___

### useProfileUpdate

▸ **useProfileUpdate**(`pubKey`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void`, `unknown`, [`UpdateProfileFormData`](../interfaces/akashaproject_ui_awf_hooks._internal_.UpdateProfileFormData.md), { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

Hook to update a user's profile data

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey` | `string` | the textile generated public key of the user |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void`, `unknown`, [`UpdateProfileFormData`](../interfaces/akashaproject_ui_awf_hooks._internal_.UpdateProfileFormData.md), { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

#### Defined in

[ui/hooks/src/use-profile.ts:331](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-profile.ts#L331)

___

### useQueryListener

▸ `Const` **useQueryListener**<`TData`\>(`queryKey`): [`QueryObserverResult`](akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `unknown`\>

#### Type parameters

| Name |
| :------ |
| `TData` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryKey` | [`QueryKey`](akashaproject_ui_awf_hooks._internal_.md#querykey) |

#### Returns

[`QueryObserverResult`](akashaproject_ui_awf_hooks._internal_.md#queryobserverresult)<`TData`, `unknown`\>

#### Defined in

[ui/hooks/src/use-query-listener.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-query-listener.ts#L33)

___

### useReasons

▸ `Const` **useReasons**(): [`string`[], [`UseReasonsActions`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseReasonsActions.md)]

A hook to get predefined reasons from moderation API

#### Returns

[`string`[], [`UseReasonsActions`](../interfaces/akashaproject_ui_awf_hooks._internal_.UseReasonsActions.md)]

#### Defined in

[ui/hooks/src/use-reasons.ts:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-reasons.ts#L47)

___

### useReport

▸ **useReport**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), [`UseModerationParam`](akashaproject_ui_awf_hooks._internal_.md#usemoderationparam), `unknown`\>

Hook for reporting a post, reply or account

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`number`, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), [`UseModerationParam`](akashaproject_ui_awf_hooks._internal_.md#usemoderationparam), `unknown`\>

#### Defined in

[ui/hooks/src/use-moderation.ts:129](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-moderation.ts#L129)

___

### useRequiredNetworkName

▸ **useRequiredNetworkName**(): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, `unknown`\>

A hook to get required network name from the SDK

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`, `unknown`\>

#### Defined in

[ui/hooks/src/use-injected-provider.ts:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-injected-provider.ts#L75)

___

### useSaveBookmark

▸ **useSaveBookmark**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`[], `unknown`, { `entryId`: `string` ; `itemType`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }, { `prevBmks`: { `entryId`: `string` ; `type`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }[]  }\>

Hook used to save bookmarks
can be used to bookmark replies and posts (itemType is passed to mutate()).

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`string`[], `unknown`, { `entryId`: `string` ; `itemType`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }, { `prevBmks`: { `entryId`: `string` ; `type`: [`ItemTypes`](../enums/akashaproject_ui_awf_hooks._internal_.ItemTypes.md)  }[]  }\>

#### Defined in

[ui/hooks/src/use-bookmarks.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-bookmarks.ts#L48)

___

### useSearch

▸ **useSearch**(`searchQuery`, `loggedUser?`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `comments`: [`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[] ; `entries`: [`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[] ; `profiles`: `any`[] ; `tags`: [[`GlobalSearchResultTagItem`](../interfaces/akashaproject_ui_awf_hooks._internal_.GlobalSearchResultTagItem.md)] \| []  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook for fetching search results for a specific query

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `searchQuery` | `string` | `undefined` | query for the search |
| `loggedUser?` | `string` | `undefined` | pubKey of the logged in user |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<{ `comments`: [`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[] ; `entries`: [`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[] ; `profiles`: `any`[] ; `tags`: [[`GlobalSearchResultTagItem`](../interfaces/akashaproject_ui_awf_hooks._internal_.GlobalSearchResultTagItem.md)] \| []  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

search results for posts, comments, tags and profiles

#### Defined in

[ui/hooks/src/use-search.ts:296](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-search.ts#L296)

___

### useSearchComments

▸ **useSearchComments**(`searchQuery`, `loggedUser?`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for comments

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `searchQuery` | `string` | `undefined` | query for the search |
| `loggedUser?` | `string` | `undefined` | pubKey of the logged in user |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

search results for comments

#### Defined in

[ui/hooks/src/use-search.ts:155](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-search.ts#L155)

___

### useSearchPosts

▸ **useSearchPosts**(`searchQuery`, `loggedUser?`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for posts

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `searchQuery` | `string` | `undefined` | query for the search |
| `loggedUser?` | `string` | `undefined` | pubKey of the logged in user |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IEntryData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IEntryData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

search results for posts

#### Defined in

[ui/hooks/src/use-search.ts:108](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-search.ts#L108)

___

### useSearchProfiles

▸ **useSearchProfiles**(`searchQuery`, `loggedUser?`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for profiles

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `searchQuery` | `string` | `undefined` | query for the search |
| `loggedUser?` | `string` | `undefined` | pubKey of the logged in user |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

search results for profiles, containing full profile data

#### Defined in

[ui/hooks/src/use-search.ts:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-search.ts#L60)

___

### useSearchTags

▸ **useSearchTags**(`searchQuery`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for tags

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `searchQuery` | `string` | `undefined` | query for the search |
| `enabler` | `boolean` | `true` | flag to allow the query |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

search results for posts, comments, tags and profiles

#### Defined in

[ui/hooks/src/use-search.ts:184](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-search.ts#L184)

___

### useTagSearch

▸ **useTagSearch**(`tagName`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to search for tags

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagName` | `string` | name of the tag |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-tag.ts:140](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-tag.ts#L140)

___

### useTagSubscriptions

▸ **useTagSubscriptions**(`loggedEthAddress`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to get a user's subscribed tags

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `loggedEthAddress` | `string` | eth address of the logged in user |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`string`[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-tag.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-tag.ts#L22)

___

### useToggleTagSubscription

▸ **useToggleTagSubscription**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `toggleInterestSub`: `boolean`  }  }, `unknown`, `string`, { `previousTagSubs`: `string`[]  }\>

Hook to toggle a user's tag subscription
pass the tagName to the mutation function

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `toggleInterestSub`: `boolean`  }  }, `unknown`, `string`, { `previousTagSubs`: `string`[]  }\>

#### Defined in

[ui/hooks/src/use-tag.ts:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-tag.ts#L54)

___

### useTrendingProfiles

▸ **useTrendingProfiles**(): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to fetch trending profiles

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-trending.ts:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-trending.ts#L56)

___

### useTrendingTags

▸ **useTrendingTags**(): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

Hook to fetch trending tags

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<[`SearchTagsResult_Response`](../interfaces/akashaproject_ui_awf_hooks._internal_.SearchTagsResult_Response.md)[], [`Error`](akashaproject_ui_awf_hooks._internal_.md#error)\>

#### Defined in

[ui/hooks/src/use-trending.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-trending.ts#L21)

___

### useUnfollow

▸ **useUnfollow**(): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `unFollow`: `boolean`  }  }, `unknown`, `string`, { `previousFollowedProfiles`: `string`[]  }\>

Hook to unfollow another user

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<{ `data`: { `unFollow`: `boolean`  }  }, `unknown`, `string`, { `previousFollowedProfiles`: `string`[]  }\>

#### Defined in

[ui/hooks/src/use-follow.ts:225](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-follow.ts#L225)

___

### useUpdateUsernameProvider

▸ **useUpdateUsernameProvider**(`pubKey?`): [`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void` \| { `makeDefaultProvider`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `provider`: [`ProfileProviders`](../enums/akashaproject_ui_awf_hooks._internal_.ProfileProviders.md) ; `userName`: `string`  }, { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

Hook to register a username for the user

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pubKey?` | `string` | textile public key of the user |

#### Returns

[`UseMutationResult`](akashaproject_ui_awf_hooks._internal_.md#usemutationresult)<`void` \| { `makeDefaultProvider`: `string`  }, [`Error`](akashaproject_ui_awf_hooks._internal_.md#error), { `provider`: [`ProfileProviders`](../enums/akashaproject_ui_awf_hooks._internal_.ProfileProviders.md) ; `userName`: `string`  }, { `currentProfile`: [`IProfileData`](../interfaces/akashaproject_ui_awf_hooks._internal_.IProfileData.md)  }\>

#### Defined in

[ui/hooks/src/use-username.ts:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-username.ts#L70)

___

### useUsernameValidation

▸ **useUsernameValidation**(`username`, `enabler?`): [`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, `unknown`\>

Hook to check if a username is available

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `username` | `string` | `undefined` | name to check for |
| `enabler` | `boolean` | `true` | prevent hook from running in passed falsy |

#### Returns

[`UseQueryResult`](akashaproject_ui_awf_hooks._internal_.md#usequeryresult)<`any`, `unknown`\>

#### Defined in

[ui/hooks/src/use-username.ts:202](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/use-username.ts#L202)

___

### withProviders

▸ **withProviders**<`T`\>(`WrappedComponent`): (`props`: `any`) => `Element`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `WrappedComponent` | [`ComponentType`](akashaproject_ui_awf_hooks._internal_.md#componenttype)<`T`\> |

#### Returns

`fn`

▸ (`props`): `Element`

##### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `any` |

##### Returns

`Element`

| Name | Type |
| :------ | :------ |
| `displayName` | `string` |

#### Defined in

[ui/hooks/src/utils/provider-hoc.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/hooks/src/utils/provider-hoc.tsx#L21)
