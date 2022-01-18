[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / AWF\_IAuth

# Interface: AWF\_IAuth

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).AWF_IAuth

## Table of contents

### Methods

- [authenticateMutationData](akashaproject_sdk_typings._internal_.AWF_IAuth.md#authenticatemutationdata)
- [checkIfSignedUp](akashaproject_sdk_typings._internal_.AWF_IAuth.md#checkifsignedup)
- [decryptMessage](akashaproject_sdk_typings._internal_.AWF_IAuth.md#decryptmessage)
- [deleteMessage](akashaproject_sdk_typings._internal_.AWF_IAuth.md#deletemessage)
- [enableSync](akashaproject_sdk_typings._internal_.AWF_IAuth.md#enablesync)
- [getCurrentUser](akashaproject_sdk_typings._internal_.AWF_IAuth.md#getcurrentuser)
- [getMessages](akashaproject_sdk_typings._internal_.AWF_IAuth.md#getmessages)
- [getSession](akashaproject_sdk_typings._internal_.AWF_IAuth.md#getsession)
- [getToken](akashaproject_sdk_typings._internal_.AWF_IAuth.md#gettoken)
- [hasNewNotifications](akashaproject_sdk_typings._internal_.AWF_IAuth.md#hasnewnotifications)
- [markMessageAsRead](akashaproject_sdk_typings._internal_.AWF_IAuth.md#markmessageasread)
- [signData](akashaproject_sdk_typings._internal_.AWF_IAuth.md#signdata)
- [signIn](akashaproject_sdk_typings._internal_.AWF_IAuth.md#signin)
- [signOut](akashaproject_sdk_typings._internal_.AWF_IAuth.md#signout)
- [validateInvite](akashaproject_sdk_typings._internal_.AWF_IAuth.md#validateinvite)
- [verifySignature](akashaproject_sdk_typings._internal_.AWF_IAuth.md#verifysignature)

## Methods

### authenticateMutationData

▸ **authenticateMutationData**(`data`): `Observable`<{ `signedData`: `unknown` ; `token`: `unknown`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\>[] |

#### Returns

`Observable`<{ `signedData`: `unknown` ; `token`: `unknown`  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:44](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L44)

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

[sdk/typings/src/interfaces/auth.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L12)

___

### decryptMessage

▸ **decryptMessage**(`message`): `Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |

#### Returns

`Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L48)

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

[sdk/typings/src/interfaces/auth.ts:72](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L72)

___

### enableSync

▸ **enableSync**(): `void`

enable key sync between opened tabs

#### Returns

`void`

#### Defined in

[sdk/typings/src/interfaces/auth.ts:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L10)

___

### getCurrentUser

▸ **getCurrentUser**(): `Observable`<{ `data`: [`CurrentUser`](akashaproject_sdk_typings._internal_.CurrentUser.md)  }\>

#### Returns

`Observable`<{ `data`: [`CurrentUser`](akashaproject_sdk_typings._internal_.CurrentUser.md)  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:29](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L29)

___

### getMessages

▸ **getMessages**(`args`): `Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `InboxListOptions` |

#### Returns

`Observable`<{ `data`: { `body`: [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L58)

___

### getSession

▸ **getSession**(): `Observable`<{ `data`: { `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }  }\>

#### Returns

`Observable`<{ `data`: { `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L19)

___

### getToken

▸ **getToken**(): `Observable`<{ `data`: `string`  }\>

#### Returns

`Observable`<{ `data`: `string`  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L27)

___

### hasNewNotifications

▸ **hasNewNotifications**(): `Observable`<{ `data`: `boolean`  }\>

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:68](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L68)

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

[sdk/typings/src/interfaces/auth.ts:70](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L70)

___

### signData

▸ **signData**(`data`, `base64Format?`): `Observable`<{ `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\>[] |
| `base64Format?` | `boolean` |

#### Returns

`Observable`<{ `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array`  }  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L33)

___

### signIn

▸ **signIn**(`args`): `Observable`<{ `data`: [`CurrentUser`](akashaproject_sdk_typings._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.checkRegistered` | `boolean` |
| `args.provider?` | [`EthProviders`](../enums/akashaproject_sdk_typings._internal_.EthProviders.md) |

#### Returns

`Observable`<{ `data`: [`CurrentUser`](akashaproject_sdk_typings._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L14)

___

### signOut

▸ **signOut**(): `Observable`<{ `data`: `boolean`  }\>

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L31)

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

[sdk/typings/src/interfaces/auth.ts:74](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L74)

___

### verifySignature

▸ **verifySignature**(`args`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.data` | `string` \| [`Record`](../modules/akashaproject_sdk_typings._internal_.md#record)<`string`, `unknown`\> \| `Uint8Array` |
| `args.pubKey` | `string` |
| `args.signature` | `string` \| `Uint8Array` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Defined in

[sdk/typings/src/interfaces/auth.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/auth.ts#L38)
