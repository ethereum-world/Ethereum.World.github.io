[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AWF\_Auth

# Class: AWF\_Auth

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AWF_Auth

## Implements

- [`AWF_IAuth`](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md)

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.AWF_Auth.md#constructor)

### Properties

- [SIGN\_OUT\_EVENT](akashaproject_awf_sdk._internal_.AWF_Auth.md#sign_out_event)
- [SYNC\_CHANNEL](akashaproject_awf_sdk._internal_.AWF_Auth.md#sync_channel)
- [SYNC\_REQUEST](akashaproject_awf_sdk._internal_.AWF_Auth.md#sync_request)
- [SYNC\_RESPONSE](akashaproject_awf_sdk._internal_.AWF_Auth.md#sync_response)
- [currentUserKey](akashaproject_awf_sdk._internal_.AWF_Auth.md#currentuserkey)
- [encoder](akashaproject_awf_sdk._internal_.AWF_Auth.md#encoder)
- [providerKey](akashaproject_awf_sdk._internal_.AWF_Auth.md#providerkey)
- [waitForAuth](akashaproject_awf_sdk._internal_.AWF_Auth.md#waitforauth)

### Methods

- [\_connectAddress](akashaproject_awf_sdk._internal_.AWF_Auth.md#_connectaddress)
- [authenticateMutationData](akashaproject_awf_sdk._internal_.AWF_Auth.md#authenticatemutationdata)
- [checkIfSignedUp](akashaproject_awf_sdk._internal_.AWF_Auth.md#checkifsignedup)
- [connectAddress](akashaproject_awf_sdk._internal_.AWF_Auth.md#connectaddress)
- [decryptMessage](akashaproject_awf_sdk._internal_.AWF_Auth.md#decryptmessage)
- [deleteMessage](akashaproject_awf_sdk._internal_.AWF_Auth.md#deletemessage)
- [enableSync](akashaproject_awf_sdk._internal_.AWF_Auth.md#enablesync)
- [getCurrentUser](akashaproject_awf_sdk._internal_.AWF_Auth.md#getcurrentuser)
- [getMessages](akashaproject_awf_sdk._internal_.AWF_Auth.md#getmessages)
- [getSession](akashaproject_awf_sdk._internal_.AWF_Auth.md#getsession)
- [getToken](akashaproject_awf_sdk._internal_.AWF_Auth.md#gettoken)
- [hasNewNotifications](akashaproject_awf_sdk._internal_.AWF_Auth.md#hasnewnotifications)
- [markMessageAsRead](akashaproject_awf_sdk._internal_.AWF_Auth.md#markmessageasread)
- [signAuthMessage](akashaproject_awf_sdk._internal_.AWF_Auth.md#signauthmessage)
- [signComposedMessage](akashaproject_awf_sdk._internal_.AWF_Auth.md#signcomposedmessage)
- [signData](akashaproject_awf_sdk._internal_.AWF_Auth.md#signdata)
- [signIn](akashaproject_awf_sdk._internal_.AWF_Auth.md#signin)
- [signOut](akashaproject_awf_sdk._internal_.AWF_Auth.md#signout)
- [signTokenMessage](akashaproject_awf_sdk._internal_.AWF_Auth.md#signtokenmessage)
- [validateInvite](akashaproject_awf_sdk._internal_.AWF_Auth.md#validateinvite)
- [verifySignature](akashaproject_awf_sdk._internal_.AWF_Auth.md#verifysignature)

## Constructors

### constructor

• **new AWF_Auth**(`db`, `web3`, `globalChannel`, `log`, `settings`, `gql`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `db` | [`DB`](akashaproject_awf_sdk._internal_.DB.md) |
| `web3` | [`Web3Connector`](akashaproject_awf_sdk._internal_.Web3Connector.md) |
| `globalChannel` | [`EventBus`](akashaproject_awf_sdk._internal_.EventBus.md) |
| `log` | [`Logging`](akashaproject_awf_sdk._internal_.Logging.md) |
| `settings` | [`Settings`](akashaproject_awf_sdk._internal_.Settings.md) |
| `gql` | [`Gql`](akashaproject_awf_sdk._internal_.Gql.md) |

#### Defined in

[sdk/src/auth/index.ts:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L64)

## Properties

### SIGN\_OUT\_EVENT

• `Readonly` **SIGN\_OUT\_EVENT**: ``"@sign_out"``

#### Defined in

[sdk/src/auth/index.ts:62](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L62)

___

### SYNC\_CHANNEL

• `Readonly` **SYNC\_CHANNEL**: ``"@sync_data"``

#### Defined in

[sdk/src/auth/index.ts:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L61)

___

### SYNC\_REQUEST

• `Readonly` **SYNC\_REQUEST**: ``"@sync_request"``

#### Defined in

[sdk/src/auth/index.ts:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L59)

___

### SYNC\_RESPONSE

• `Readonly` **SYNC\_RESPONSE**: ``"@sync_response"``

#### Defined in

[sdk/src/auth/index.ts:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L60)

___

### currentUserKey

• `Readonly` **currentUserKey**: ``"@currentUserType"``

#### Defined in

[sdk/src/auth/index.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L58)

___

### encoder

• `Readonly` **encoder**: [`TextEncoder`](../modules/akashaproject_awf_sdk._internal_.md#textencoder)

#### Defined in

[sdk/src/auth/index.ts:63](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L63)

___

### providerKey

• `Readonly` **providerKey**: ``"@providerType"``

#### Defined in

[sdk/src/auth/index.ts:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L57)

___

### waitForAuth

• `Readonly` **waitForAuth**: ``"waitForAuth"``

#### Defined in

[sdk/src/auth/index.ts:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L56)

## Methods

### \_connectAddress

▸ **_connectAddress**(`provider`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) |

#### Returns

`Promise`<`string`\>

#### Defined in

[sdk/src/auth/index.ts:270](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L270)

___

### authenticateMutationData

▸ **authenticateMutationData**(`data`): `Observable`<{ `signedData`: { `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array` = sig }  } ; `token`: { `data`: `string`  }  }\>

Utility method for sending mutation graphql requests

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\>[] |

#### Returns

`Observable`<{ `signedData`: { `data`: { `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array` = sig }  } ; `token`: { `data`: `string`  }  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[authenticateMutationData](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#authenticatemutationdata)

#### Defined in

[sdk/src/auth/index.ts:543](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L543)

___

### checkIfSignedUp

▸ **checkIfSignedUp**(`ethAddress`): `Observable`<{ `data`: { `errors?`: `never`  }  }\>

Verifies if an ethereum address is already registered
Throws an UserNotRegistered error for addresses that are not registered

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress` | `string` |

#### Returns

`Observable`<{ `data`: { `errors?`: `never`  }  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[checkIfSignedUp](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#checkifsignedup)

#### Defined in

[sdk/src/auth/index.ts:125](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L125)

___

### connectAddress

▸ **connectAddress**(`provider`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Defined in

[sdk/src/auth/index.ts:285](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L285)

___

### decryptMessage

▸ **decryptMessage**(`message`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }\>

Allows decryption of privately sent messages to the current identity

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[decryptMessage](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#decryptmessage)

#### Defined in

[sdk/src/auth/index.ts:555](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L555)

___

### deleteMessage

▸ **deleteMessage**(`messageId`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[deleteMessage](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#deletemessage)

#### Defined in

[sdk/src/auth/index.ts:659](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L659)

___

### enableSync

▸ **enableSync**(): `void`

enable key sync between opened tabs

#### Returns

`void`

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[enableSync](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#enablesync)

#### Defined in

[sdk/src/auth/index.ts:84](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L84)

___

### getCurrentUser

▸ **getCurrentUser**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`CurrentUser`](../interfaces/akashaproject_awf_sdk._internal_.CurrentUser.md)\>

Returns the currently logged in user object
It will try to login if there is a previous session detected

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`CurrentUser`](../interfaces/akashaproject_awf_sdk._internal_.CurrentUser.md)\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[getCurrentUser](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#getcurrentuser)

#### Defined in

[sdk/src/auth/index.ts:425](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L425)

___

### getMessages

▸ **getMessages**(`args`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]\>

Returns all the inbox messages from Textile Users

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `args` | `InboxListOptions` | InboxListOptions |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `body`: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `any`\> ; `createdAt`: `number` ; `from`: `string` ; `id`: `string` ; `readAt`: `number`  }[]\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[getMessages](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#getmessages)

#### Defined in

[sdk/src/auth/index.ts:581](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L581)

___

### getSession

▸ **getSession**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }\>

Returns current session objects for textile

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `buck`: `Buckets` ; `client`: `Client` ; `user`: `Users`  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[getSession](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#getsession)

#### Defined in

[sdk/src/auth/index.ts:378](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L378)

___

### getToken

▸ **getToken**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

Generate a textile access token

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[getToken](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#gettoken)

#### Defined in

[sdk/src/auth/index.ts:405](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L405)

___

### hasNewNotifications

▸ **hasNewNotifications**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

Checks the Textile Users inbox and looks for specific
notification message type

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[hasNewNotifications](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#hasnewnotifications)

#### Defined in

[sdk/src/auth/index.ts:628](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L628)

___

### markMessageAsRead

▸ **markMessageAsRead**(`messageId`): `Observable`<{ `data`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `messageId` | `string` |

#### Returns

`Observable`<{ `data`: `boolean`  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[markMessageAsRead](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#markmessageasread)

#### Defined in

[sdk/src/auth/index.ts:639](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L639)

___

### signAuthMessage

▸ **signAuthMessage**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Defined in

[sdk/src/auth/index.ts:289](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L289)

___

### signComposedMessage

▸ **signComposedMessage**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Defined in

[sdk/src/auth/index.ts:304](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L304)

___

### signData

▸ **signData**(`data`, `base64Format?`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array` = sig }\>

Sign data with the identity key

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\>[] | `undefined` |
| `base64Format` | `boolean` | `false` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<{ `pubKey`: `string` ; `serializedData`: `any` ; `signature`: `string` \| `Uint8Array` = sig }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[signData](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#signdata)

#### Defined in

[sdk/src/auth/index.ts:477](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L477)

___

### signIn

▸ **signIn**(`args`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`CurrentUser`](../interfaces/akashaproject_awf_sdk._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.checkRegistered` | `boolean` |
| `args.provider?` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) |
| `args.resumeSignIn?` | `boolean` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`CurrentUser`](../interfaces/akashaproject_awf_sdk._internal_.CurrentUser.md) & { `isNewUser`: `boolean`  }\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[signIn](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#signin)

#### Defined in

[sdk/src/auth/index.ts:146](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L146)

___

### signOut

▸ **signOut**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

Destroy all the session objects

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[signOut](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#signout)

#### Defined in

[sdk/src/auth/index.ts:449](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L449)

___

### signTokenMessage

▸ **signTokenMessage**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Defined in

[sdk/src/auth/index.ts:323](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L323)

___

### validateInvite

▸ **validateInvite**(`inviteCode`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `inviteCode` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[validateInvite](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#validateinvite)

#### Defined in

[sdk/src/auth/index.ts:672](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L672)

___

### verifySignature

▸ **verifySignature**(`args`): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

Verify if a signature was made by a specific Public Key

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.data` | `string` \| [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `unknown`\> \| `Uint8Array` |
| `args.pubKey` | `string` |
| `args.signature` | `string` \| `Uint8Array` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`boolean`\>

#### Implementation of

[AWF_IAuth](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md).[verifySignature](../interfaces/akashaproject_awf_sdk._internal_.AWF_IAuth.md#verifysignature)

#### Defined in

[sdk/src/auth/index.ts:507](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/auth/index.ts#L507)
