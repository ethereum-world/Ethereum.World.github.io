[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / AWF\_SDK

# Interface: AWF\_SDK

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).AWF_SDK

## Table of contents

### Properties

- [api](akashaproject_awf_sdk.AWF_SDK.md#api)
- [services](akashaproject_awf_sdk.AWF_SDK.md#services)

## Properties

### api

• **api**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `auth` | [`AWF_Auth`](../classes/akashaproject_awf_sdk._internal_.AWF_Auth.md) |
| `comments` | [`AWF_Comments`](../classes/akashaproject_awf_sdk._internal_.AWF_Comments.md) |
| `ens` | [`AWF_ENS`](../classes/akashaproject_awf_sdk._internal_.AWF_ENS.md) |
| `entries` | [`AWF_Entry`](../classes/akashaproject_awf_sdk._internal_.AWF_Entry.md) |
| `globalChannel` | [`EventBus`](../classes/akashaproject_awf_sdk._internal_.EventBus.md) |
| `profile` | [`AWF_Profile`](../classes/akashaproject_awf_sdk._internal_.AWF_Profile.md) |
| `tags` | [`AWF_Tags`](../classes/akashaproject_awf_sdk._internal_.AWF_Tags.md) |

#### Defined in

[sdk/src/index.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/index.ts#L33)

___

### services

• **services**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `appSettings` | [`AppSettings`](../classes/akashaproject_awf_sdk._internal_.AppSettings.md) |
| `common` | `Object` |
| `common.ipfs` | [`AWF_IpfsConnector`](../classes/akashaproject_awf_sdk._internal_.AWF_IpfsConnector.md) |
| `common.web3` | [`Web3Connector`](../classes/akashaproject_awf_sdk._internal_.Web3Connector.md) |
| `db` | [`DB`](../classes/akashaproject_awf_sdk._internal_.DB.md) |
| `gql` | [`Gql`](../classes/akashaproject_awf_sdk._internal_.Gql.md) |
| `log` | [`Logging`](../classes/akashaproject_awf_sdk._internal_.Logging.md) |
| `settings` | [`Settings`](../classes/akashaproject_awf_sdk._internal_.Settings.md) |
| `stash` | [`Stash`](../classes/akashaproject_awf_sdk._internal_.Stash.md) |

#### Defined in

[sdk/src/index.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/index.ts#L21)
