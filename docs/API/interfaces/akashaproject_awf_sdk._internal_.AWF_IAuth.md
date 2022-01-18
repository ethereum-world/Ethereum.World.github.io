[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_IAuth

# Interface: AWF\_IAuth

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_IAuth

## Implemented by

- [`AWF_Auth`](../classes/akashaproject_awf_sdk._internal_.AWF_Auth.md)

## Table of contents

### Methods

- [authenticateMutationData](akashaproject_awf_sdk._internal_.AWF_IAuth.md#authenticatemutationdata)
- [checkIfSignedUp](akashaproject_awf_sdk._internal_.AWF_IAuth.md#checkifsignedup)
- [decryptMessage](akashaproject_awf_sdk._internal_.AWF_IAuth.md#decryptmessage)
- [deleteMessage](akashaproject_awf_sdk._internal_.AWF_IAuth.md#deletemessage)
- [enableSync](akashaproject_awf_sdk._internal_.AWF_IAuth.md#enablesync)
- [getCurrentUser](akashaproject_awf_sdk._internal_.AWF_IAuth.md#getcurrentuser)
- [getMessages](akashaproject_awf_sdk._internal_.AWF_IAuth.md#getmessages)
- [getSession](akashaproject_awf_sdk._internal_.AWF_IAuth.md#getsession)
- [getToken](akashaproject_awf_sdk._internal_.AWF_IAuth.md#gettoken)
- [hasNewNotifications](akashaproject_awf_sdk._internal_.AWF_IAuth.md#hasnewnotifications)
- [markMessageAsRead](akashaproject_awf_sdk._internal_.AWF_IAuth.md#markmessageasread)
- [signData](akashaproject_awf_sdk._internal_.AWF_IAuth.md#signdata)
- [signIn](akashaproject_awf_sdk._internal_.AWF_IAuth.md#signin)
- [signOut](akashaproject_awf_sdk._internal_.AWF_IAuth.md#signout)
- [validateInvite](akashaproject_awf_sdk._internal_.AWF_IAuth.md#validateinvite)
- [verifySignature](akashaproject_awf_sdk._internal_.AWF_IAuth.md#verifysignature)

## Methods

### authenticateMutationData

▸ **authenticateMutationData**(`data`): `Observable`<{ `signedData`: `unknown` ; `token`: `unknown`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\>[] |

#### Returns

`Observable`<{ `signedData`: `unknown` ; `token`: `unknown`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:49

___

### checkIfSignedUp

▸ **checkIfSignedUp**(`ethAddress`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`any`

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:10

___

### decryptMessage

▸ **decryptMessage**(`message`): `Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |

#### Returns

`Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:53

___

### deleteMessage

▸ **deleteMessage**(`messageId`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:77

___

### enableSync

▸ **enableSync**(): `void`

enable key sync between opened tabs

#### Returns

`void`

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:9

___

### getCurrentUser

▸ **getCurrentUser**(): `Observable`<{ `data`: [`CurrentUser`](akashaproject_awf_sdk._internal_.CurrentUser.md)  }\>

#### Returns

`Observable`<{ `data`: [`CurrentUser`](akashaproject_awf_sdk._internal_.CurrentUser.md)  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:29

___

### getMessages

▸ **getMessages**(`args`): `Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `InboxListOptions` |

#### Returns

`Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:62

___

### getSession

▸ **getSession**(): `Observable`<{ `data`: { `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }  }\>

#### Returns

`Observable`<{ `data`: { `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:19

___

### getToken

▸ **getToken**(): `Observable`<{ `data`: `string`  }\>

#### Returns

`Observable`<{ `data`: `string`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:26

___

### hasNewNotifications

▸ **hasNewNotifications**(): `Observable`<{ `data`: `boolean`  }\>

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:71

___

### markMessageAsRead

▸ **markMessageAsRead**(`messageId`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:74

___

### signData

▸ **signData**(`data`, `base64Format?`): `Observable`<{ `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\>[] |
| `base64Format?` | `boolean` |

#### Returns

`Observable`<{ `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:35

___

### signIn

▸ **signIn**(`args`): `Observable`<{ `data`: [`CurrentUser`](akashaproject_awf_sdk._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.checkRegistered` | `boolean` |
| `args.provider?` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) |

#### Returns

`Observable`<{ `data`: [`CurrentUser`](akashaproject_awf_sdk._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:11

___

### signOut

▸ **signOut**(): `Observable`<{ `data`: `boolean`  }\>

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:32

___

### validateInvite

▸ **validateInvite**(`inviteCode`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `inviteCode` | `string` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:80

___

### verifySignature

▸ **verifySignature**(`args`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| `Uint8Array` |
| `args.pubKey` | `string` |
| `args.signature` | `string` \| `Uint8Array` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

sdk/typings/lib/interfaces/auth.d.ts:42
