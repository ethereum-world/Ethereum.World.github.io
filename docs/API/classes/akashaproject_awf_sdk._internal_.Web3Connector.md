[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Web3Connector

# Class: Web3Connector

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Web3Connector

## Implements

- [`IWeb3Connector`](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md)<[`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md) \| [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)\>

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Web3Connector.md#constructor)

### Properties

- [network](akashaproject_awf_sdk._internal_.Web3Connector.md#network)
- [networkId](akashaproject_awf_sdk._internal_.Web3Connector.md#networkid)

### Accessors

- [provider](akashaproject_awf_sdk._internal_.Web3Connector.md#provider)

### Methods

- [checkCurrentNetwork](akashaproject_awf_sdk._internal_.Web3Connector.md#checkcurrentnetwork)
- [connect](akashaproject_awf_sdk._internal_.Web3Connector.md#connect)
- [detectInjectedProvider](akashaproject_awf_sdk._internal_.Web3Connector.md#detectinjectedprovider)
- [disconnect](akashaproject_awf_sdk._internal_.Web3Connector.md#disconnect)
- [getCurrentAddress](akashaproject_awf_sdk._internal_.Web3Connector.md#getcurrentaddress)
- [getRequiredNetworkName](akashaproject_awf_sdk._internal_.Web3Connector.md#getrequirednetworkname)
- [getSigner](akashaproject_awf_sdk._internal_.Web3Connector.md#getsigner)
- [requestWalletPermissions](akashaproject_awf_sdk._internal_.Web3Connector.md#requestwalletpermissions)
- [signMessage](akashaproject_awf_sdk._internal_.Web3Connector.md#signmessage)
- [switchToRequiredNetwork](akashaproject_awf_sdk._internal_.Web3Connector.md#switchtorequirednetwork)

## Constructors

### constructor

• **new Web3Connector**(`logFactory`, `globalChannel`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `logFactory` | [`Logging`](akashaproject_awf_sdk._internal_.Logging.md) |
| `globalChannel` | [`EventBus`](akashaproject_awf_sdk._internal_.EventBus.md) |

#### Defined in

[sdk/src/common/web3.connector.ts:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L46)

## Properties

### network

• `Readonly` **network**: ``"rinkeby"``

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[network](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#network)

#### Defined in

[sdk/src/common/web3.connector.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L32)

___

### networkId

• `Readonly` **networkId**: [`Readonly`](../modules/akashaproject_awf_sdk._internal_.md#readonly)<{ `goerli`: `number` = 5; `kovan`: `number` = 42; `mainnet`: `number` = 1; `rinkeby`: `number` = 4; `ropsten`: `number` = 3 }\>

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[networkId](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#networkid)

#### Defined in

[sdk/src/common/web3.connector.ts:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L35)

## Accessors

### provider

• `get` **provider**(): [`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md) \| [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

Get access to the web3 provider instance

#### Returns

[`BaseProvider`](akashaproject_awf_sdk._internal_.BaseProvider.md) \| [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[provider](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#provider)

#### Defined in

[sdk/src/common/web3.connector.ts:88](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L88)

## Methods

### checkCurrentNetwork

▸ **checkCurrentNetwork**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`void`\>

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[checkCurrentNetwork](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#checkcurrentnetwork)

#### Defined in

[sdk/src/common/web3.connector.ts:167](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L167)

___

### connect

▸ **connect**(`provider?`): `Promise`<`boolean`\>

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) | `EthProviders.None` | Number representing the provider option |

#### Returns

`Promise`<`boolean`\>

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[connect](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#connect)

#### Defined in

[sdk/src/common/web3.connector.ts:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L59)

___

### detectInjectedProvider

▸ **detectInjectedProvider**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`INJECTED_PROVIDERS`](../enums/akashaproject_awf_sdk._internal_.INJECTED_PROVIDERS.md)\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<[`INJECTED_PROVIDERS`](../enums/akashaproject_awf_sdk._internal_.INJECTED_PROVIDERS.md)\>

#### Defined in

[sdk/src/common/web3.connector.ts:170](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L170)

___

### disconnect

▸ **disconnect**(): `Promise`<`void`\>

Remove the web3 connection

#### Returns

`Promise`<`void`\>

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[disconnect](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#disconnect)

#### Defined in

[sdk/src/common/web3.connector.ts:98](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L98)

___

### getCurrentAddress

▸ **getCurrentAddress**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

the current eth address that is connected to the provider

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[getCurrentAddress](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#getcurrentaddress)

#### Defined in

[sdk/src/common/web3.connector.ts:134](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L134)

___

### getRequiredNetworkName

▸ **getRequiredNetworkName**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`string`\>

#### Defined in

[sdk/src/common/web3.connector.ts:138](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L138)

___

### getSigner

▸ **getSigner**(): [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md) \| [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Returns

[`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md) \| [`Wallet`](akashaproject_awf_sdk._internal_.Wallet.md)

#### Defined in

[sdk/src/common/web3.connector.ts:121](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L121)

___

### requestWalletPermissions

▸ **requestWalletPermissions**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`any`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`any`\>

#### Defined in

[sdk/src/common/web3.connector.ts:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L75)

___

### signMessage

▸ **signMessage**(`message`): `Promise`<`string`\>

Enforce personal_sign method for message signature

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | Human readable string to sign |

#### Returns

`Promise`<`string`\>

#### Implementation of

[IWeb3Connector](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md).[signMessage](../interfaces/akashaproject_awf_sdk._internal_.IWeb3Connector.md#signmessage)

#### Defined in

[sdk/src/common/web3.connector.ts:117](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L117)

___

### switchToRequiredNetwork

▸ **switchToRequiredNetwork**(): [`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`any`\>

#### Returns

[`ServiceCallResult`](../modules/akashaproject_awf_sdk._internal_.md#servicecallresult)<`any`\>

#### Defined in

[sdk/src/common/web3.connector.ts:145](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/web3.connector.ts#L145)
