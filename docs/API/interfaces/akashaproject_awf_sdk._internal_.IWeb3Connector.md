[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / IWeb3Connector

# Interface: IWeb3Connector<T\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).IWeb3Connector

## Type parameters

| Name |
| :------ |
| `T` |

## Implemented by

- [`Web3Connector`](../classes/akashaproject_awf_sdk._internal_.Web3Connector.md)

## Table of contents

### Properties

- [network](akashaproject_awf_sdk._internal_.IWeb3Connector.md#network)
- [networkId](akashaproject_awf_sdk._internal_.IWeb3Connector.md#networkid)
- [provider](akashaproject_awf_sdk._internal_.IWeb3Connector.md#provider)

### Methods

- [checkCurrentNetwork](akashaproject_awf_sdk._internal_.IWeb3Connector.md#checkcurrentnetwork)
- [connect](akashaproject_awf_sdk._internal_.IWeb3Connector.md#connect)
- [disconnect](akashaproject_awf_sdk._internal_.IWeb3Connector.md#disconnect)
- [getCurrentAddress](akashaproject_awf_sdk._internal_.IWeb3Connector.md#getcurrentaddress)
- [signMessage](akashaproject_awf_sdk._internal_.IWeb3Connector.md#signmessage)

## Properties

### network

• **network**: `string`

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:10

___

### networkId

• **networkId**: [`Readonly`](../modules/akashaproject_awf_sdk._internal_.md#readonly)<{ `goerli`: `number` ; `kovan`: `number` ; `mainnet`: `number` ; `rinkeby`: `number` ; `ropsten`: `number`  }\>

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:11

___

### provider

• `Readonly` **provider**: `T`

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:18

## Methods

### checkCurrentNetwork

▸ **checkCurrentNetwork**(): `Observable`<{ `data`: `void`  }\>

#### Returns

`Observable`<{ `data`: `void`  }\>

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:25

___

### connect

▸ **connect**(`provider`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_awf_sdk._internal_.EthProviders.md) |

#### Returns

`Promise`<`boolean`\>

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:19

___

### disconnect

▸ **disconnect**(): `void`

#### Returns

`void`

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:20

___

### getCurrentAddress

▸ **getCurrentAddress**(): `Observable`<{ `data`: `string`  }\>

#### Returns

`Observable`<{ `data`: `string`  }\>

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:22

___

### signMessage

▸ **signMessage**(`message`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |

#### Returns

`Promise`<`any`\>

#### Defined in

sdk/typings/lib/interfaces/web3.connector.d.ts:21
