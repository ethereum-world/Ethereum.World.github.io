[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md) / [<internal\>](../modules/akashaproject_sdk_typings._internal_.md) / IWeb3Connector

# Interface: IWeb3Connector<T\>

[@akashaproject/sdk-typings](../modules/akashaproject_sdk_typings.md).[<internal>](../modules/akashaproject_sdk_typings._internal_.md).IWeb3Connector

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Properties

- [network](akashaproject_sdk_typings._internal_.IWeb3Connector.md#network)
- [networkId](akashaproject_sdk_typings._internal_.IWeb3Connector.md#networkid)
- [provider](akashaproject_sdk_typings._internal_.IWeb3Connector.md#provider)

### Methods

- [checkCurrentNetwork](akashaproject_sdk_typings._internal_.IWeb3Connector.md#checkcurrentnetwork)
- [connect](akashaproject_sdk_typings._internal_.IWeb3Connector.md#connect)
- [disconnect](akashaproject_sdk_typings._internal_.IWeb3Connector.md#disconnect)
- [getCurrentAddress](akashaproject_sdk_typings._internal_.IWeb3Connector.md#getcurrentaddress)
- [signMessage](akashaproject_sdk_typings._internal_.IWeb3Connector.md#signmessage)

## Properties

### network

• **network**: `string`

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L12)

___

### networkId

• **networkId**: [`Readonly`](../modules/akashaproject_sdk_typings._internal_.md#readonly)<{ `goerli`: `number` ; `kovan`: `number` ; `mainnet`: `number` ; `rinkeby`: `number` ; `ropsten`: `number`  }\>

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L13)

___

### provider

• `Readonly` **provider**: `T`

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L20)

## Methods

### checkCurrentNetwork

▸ **checkCurrentNetwork**(): `Observable`<{ `data`: `void`  }\>

#### Returns

`Observable`<{ `data`: `void`  }\>

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:30](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L30)

___

### connect

▸ **connect**(`provider`): `Promise`<`boolean`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`EthProviders`](../enums/akashaproject_sdk_typings._internal_.EthProviders.md) |

#### Returns

`Promise`<`boolean`\>

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L22)

___

### disconnect

▸ **disconnect**(): `void`

#### Returns

`void`

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L24)

___

### getCurrentAddress

▸ **getCurrentAddress**(): `Observable`<{ `data`: `string`  }\>

#### Returns

`Observable`<{ `data`: `string`  }\>

#### Defined in

[sdk/typings/src/interfaces/web3.connector.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L28)

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

[sdk/typings/src/interfaces/web3.connector.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/typings/src/interfaces/web3.connector.ts#L26)
