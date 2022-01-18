[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / BaseProvider

# Class: BaseProvider

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).BaseProvider

## Hierarchy

- [`Provider`](akashaproject_ui_app_loader._internal_.Provider.md)

  ↳ **`BaseProvider`**

  ↳↳ [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

## Implements

- [`EnsProvider`](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.BaseProvider.md#constructor)

### Properties

- [\_bootstrapPoll](akashaproject_ui_app_loader._internal_.BaseProvider.md#_bootstrappoll)
- [\_emitted](akashaproject_ui_app_loader._internal_.BaseProvider.md#_emitted)
- [\_events](akashaproject_ui_app_loader._internal_.BaseProvider.md#_events)
- [\_fastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastblocknumber)
- [\_fastBlockNumberPromise](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastblocknumberpromise)
- [\_fastQueryDate](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastquerydate)
- [\_internalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_internalblocknumber)
- [\_isProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md#_isprovider)
- [\_lastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_lastblocknumber)
- [\_maxInternalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_maxinternalblocknumber)
- [\_network](akashaproject_ui_app_loader._internal_.BaseProvider.md#_network)
- [\_networkPromise](akashaproject_ui_app_loader._internal_.BaseProvider.md#_networkpromise)
- [\_poller](akashaproject_ui_app_loader._internal_.BaseProvider.md#_poller)
- [\_pollingInterval](akashaproject_ui_app_loader._internal_.BaseProvider.md#_pollinginterval)
- [anyNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#anynetwork)
- [formatter](akashaproject_ui_app_loader._internal_.BaseProvider.md#formatter)

### Accessors

- [blockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#blocknumber)
- [network](akashaproject_ui_app_loader._internal_.BaseProvider.md#network)
- [polling](akashaproject_ui_app_loader._internal_.BaseProvider.md#polling)
- [pollingInterval](akashaproject_ui_app_loader._internal_.BaseProvider.md#pollinginterval)
- [ready](akashaproject_ui_app_loader._internal_.BaseProvider.md#ready)

### Methods

- [\_addEventListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#_addeventlistener)
- [\_getAddress](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getaddress)
- [\_getBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getblock)
- [\_getBlockTag](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getblocktag)
- [\_getFastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getfastblocknumber)
- [\_getFilter](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getfilter)
- [\_getInternalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getinternalblocknumber)
- [\_getResolver](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getresolver)
- [\_getTransactionRequest](akashaproject_ui_app_loader._internal_.BaseProvider.md#_gettransactionrequest)
- [\_ready](akashaproject_ui_app_loader._internal_.BaseProvider.md#_ready)
- [\_setFastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_setfastblocknumber)
- [\_startEvent](akashaproject_ui_app_loader._internal_.BaseProvider.md#_startevent)
- [\_stopEvent](akashaproject_ui_app_loader._internal_.BaseProvider.md#_stopevent)
- [\_waitForTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#_waitfortransaction)
- [\_wrapTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#_wraptransaction)
- [addListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#addlistener)
- [call](akashaproject_ui_app_loader._internal_.BaseProvider.md#call)
- [detectNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#detectnetwork)
- [emit](akashaproject_ui_app_loader._internal_.BaseProvider.md#emit)
- [estimateGas](akashaproject_ui_app_loader._internal_.BaseProvider.md#estimategas)
- [getAvatar](akashaproject_ui_app_loader._internal_.BaseProvider.md#getavatar)
- [getBalance](akashaproject_ui_app_loader._internal_.BaseProvider.md#getbalance)
- [getBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblock)
- [getBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblocknumber)
- [getBlockWithTransactions](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblockwithtransactions)
- [getCode](akashaproject_ui_app_loader._internal_.BaseProvider.md#getcode)
- [getEtherPrice](akashaproject_ui_app_loader._internal_.BaseProvider.md#getetherprice)
- [getFeeData](akashaproject_ui_app_loader._internal_.BaseProvider.md#getfeedata)
- [getGasPrice](akashaproject_ui_app_loader._internal_.BaseProvider.md#getgasprice)
- [getLogs](akashaproject_ui_app_loader._internal_.BaseProvider.md#getlogs)
- [getNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#getnetwork)
- [getResolver](akashaproject_ui_app_loader._internal_.BaseProvider.md#getresolver)
- [getStorageAt](akashaproject_ui_app_loader._internal_.BaseProvider.md#getstorageat)
- [getTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransaction)
- [getTransactionCount](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransactioncount)
- [getTransactionReceipt](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransactionreceipt)
- [listenerCount](akashaproject_ui_app_loader._internal_.BaseProvider.md#listenercount)
- [listeners](akashaproject_ui_app_loader._internal_.BaseProvider.md#listeners)
- [lookupAddress](akashaproject_ui_app_loader._internal_.BaseProvider.md#lookupaddress)
- [off](akashaproject_ui_app_loader._internal_.BaseProvider.md#off)
- [on](akashaproject_ui_app_loader._internal_.BaseProvider.md#on)
- [once](akashaproject_ui_app_loader._internal_.BaseProvider.md#once)
- [perform](akashaproject_ui_app_loader._internal_.BaseProvider.md#perform)
- [poll](akashaproject_ui_app_loader._internal_.BaseProvider.md#poll)
- [removeAllListeners](akashaproject_ui_app_loader._internal_.BaseProvider.md#removealllisteners)
- [removeListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#removelistener)
- [resetEventsBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#reseteventsblock)
- [resolveName](akashaproject_ui_app_loader._internal_.BaseProvider.md#resolvename)
- [sendTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#sendtransaction)
- [waitForTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#waitfortransaction)
- [getFormatter](akashaproject_ui_app_loader._internal_.BaseProvider.md#getformatter)
- [getNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#getnetwork)
- [isProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md#isprovider)

## Constructors

### constructor

• **new BaseProvider**(`network`)

 ready

 A Promise<Network> that resolves only once the provider is ready.

 Sub-classes that call the super with a network without a chainId
 MUST set this. Standard named networks have a known chainId.

#### Parameters

| Name | Type |
| :------ | :------ |
| `network` | [`Networkish`](../modules/akashaproject_ui_app_loader._internal_.md#networkish) \| `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\> |

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[constructor](akashaproject_ui_app_loader._internal_.Provider.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:82

## Properties

### \_bootstrapPoll

• **\_bootstrapPoll**: [`Timer`](../interfaces/akashaproject_ui_app_loader._internal_.Timer.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:61

___

### \_emitted

• **\_emitted**: `Object`

#### Index signature

▪ [eventName: `string`]: `number` \| ``"pending"``

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:56

___

### \_events

• **\_events**: [`Event`](akashaproject_ui_app_loader._internal_.Event.md)[]

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:54

___

### \_fastBlockNumber

• **\_fastBlockNumber**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:63

___

### \_fastBlockNumberPromise

• **\_fastBlockNumberPromise**: `Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:64

___

### \_fastQueryDate

• **\_fastQueryDate**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:65

___

### \_internalBlockNumber

• **\_internalBlockNumber**: `Promise`<{ `blockNumber`: `number` ; `reqTime`: `number` ; `respTime`: `number`  }\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:67

___

### \_isProvider

• `Readonly` **\_isProvider**: `boolean`

#### Inherited from

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[_isProvider](akashaproject_ui_app_loader._internal_.Provider.md#_isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:150

___

### \_lastBlockNumber

• **\_lastBlockNumber**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:62

___

### \_maxInternalBlockNumber

• **\_maxInternalBlockNumber**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:66

___

### \_network

• **\_network**: [`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:53

___

### \_networkPromise

• **\_networkPromise**: `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:52

___

### \_poller

• **\_poller**: [`Timer`](../interfaces/akashaproject_ui_app_loader._internal_.Timer.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:60

___

### \_pollingInterval

• **\_pollingInterval**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:59

___

### anyNetwork

• `Readonly` **anyNetwork**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:72

___

### formatter

• **formatter**: [`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:55

## Accessors

### blockNumber

• `get` **blockNumber**(): `number`

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:93

___

### network

• `get` **network**(): [`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Returns

[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:90

___

### polling

• `get` **polling**(): `boolean`

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:94

• `set` **polling**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:95

___

### pollingInterval

• `get` **pollingInterval**(): `number`

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:96

• `set` **pollingInterval**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:97

___

### ready

• `get` **ready**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:84

## Methods

### \_addEventListener

▸ **_addEventListener**(`eventName`, `listener`, `once`): [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |
| `once` | `boolean` |

#### Returns

[`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:138

___

### \_getAddress

▸ **_getAddress**(`addressOrName`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:121

___

### \_getBlock

▸ **_getBlock**(`blockHashOrBlockTag`, `includeTransactions?`): `Promise`<[`Block`](../interfaces/akashaproject_ui_app_loader._internal_.Block.md) \| [`BlockWithTransactions`](../interfaces/akashaproject_ui_app_loader._internal_.BlockWithTransactions.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |
| `includeTransactions?` | `boolean` |

#### Returns

`Promise`<[`Block`](../interfaces/akashaproject_ui_app_loader._internal_.Block.md) \| [`BlockWithTransactions`](../interfaces/akashaproject_ui_app_loader._internal_.BlockWithTransactions.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:122

___

### \_getBlockTag

▸ **_getBlockTag**(`blockTag`): `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:129

___

### \_getFastBlockNumber

▸ **_getFastBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:98

___

### \_getFilter

▸ **_getFilter**(`filter`): `Promise`<[`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md) \| `Promise`<[`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md)\> |

#### Returns

`Promise`<[`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:118

___

### \_getInternalBlockNumber

▸ **_getInternalBlockNumber**(`maxAge`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `maxAge` | `number` |

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:87

___

### \_getResolver

▸ **_getResolver**(`name`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:131

___

### \_getTransactionRequest

▸ **_getTransactionRequest**(`transaction`): `Promise`<[`Transaction`](../interfaces/akashaproject_ui_app_loader._internal_.Transaction.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`Transaction`](../interfaces/akashaproject_ui_app_loader._internal_.Transaction.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:117

___

### \_ready

▸ **_ready**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:83

___

### \_setFastBlockNumber

▸ **_setFastBlockNumber**(`blockNumber`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockNumber` | `number` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:99

___

### \_startEvent

▸ **_startEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Event`](akashaproject_ui_app_loader._internal_.Event.md) |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:136

___

### \_stopEvent

▸ **_stopEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Event`](akashaproject_ui_app_loader._internal_.Event.md) |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:137

___

### \_waitForTransaction

▸ **_waitForTransaction**(`transactionHash`, `confirmations`, `timeout`, `replaceable`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations` | `number` |
| `timeout` | `number` |
| `replaceable` | `Object` |
| `replaceable.data` | `string` |
| `replaceable.from` | `string` |
| `replaceable.nonce` | `number` |
| `replaceable.startBlock` | `number` |
| `replaceable.to` | `string` |
| `replaceable.value` | [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md) |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:101

___

### \_wrapTransaction

▸ **_wrapTransaction**(`tx`, `hash?`, `startBlock?`): [`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | [`Transaction`](../interfaces/akashaproject_ui_app_loader._internal_.Transaction.md) |
| `hash?` | `string` |
| `startBlock?` | `number` |

#### Returns

[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:115

___

### addListener

▸ **addListener**(`eventName`, `listener`): [`Provider`](akashaproject_ui_app_loader._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_ui_app_loader._internal_.Provider.md)

#### Inherited from

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[addListener](akashaproject_ui_app_loader._internal_.Provider.md#addlistener)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:147

___

### call

▸ **call**(`transaction`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[call](akashaproject_ui_app_loader._internal_.Provider.md#call)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:119

___

### detectNetwork

▸ **detectNetwork**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:91

___

### emit

▸ **emit**(`eventName`, ...`args`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[emit](akashaproject_ui_app_loader._internal_.Provider.md#emit)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:141

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_ui_app_loader._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[estimateGas](akashaproject_ui_app_loader._internal_.Provider.md#estimategas)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:120

___

### getAvatar

▸ **getAvatar**(`nameOrAddress`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `nameOrAddress` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:134

___

### getBalance

▸ **getBalance**(`addressOrName`, `blockTag?`): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getBalance](akashaproject_ui_app_loader._internal_.Provider.md#getbalance)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:111

___

### getBlock

▸ **getBlock**(`blockHashOrBlockTag`): `Promise`<[`Block`](../interfaces/akashaproject_ui_app_loader._internal_.Block.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`Block`](../interfaces/akashaproject_ui_app_loader._internal_.Block.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getBlock](akashaproject_ui_app_loader._internal_.Provider.md#getblock)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:123

___

### getBlockNumber

▸ **getBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getBlockNumber](akashaproject_ui_app_loader._internal_.Provider.md#getblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:109

___

### getBlockWithTransactions

▸ **getBlockWithTransactions**(`blockHashOrBlockTag`): `Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_ui_app_loader._internal_.BlockWithTransactions.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_ui_app_loader._internal_.BlockWithTransactions.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getBlockWithTransactions](akashaproject_ui_app_loader._internal_.Provider.md#getblockwithtransactions)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:124

___

### getCode

▸ **getCode**(`addressOrName`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getCode](akashaproject_ui_app_loader._internal_.Provider.md#getcode)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:113

___

### getEtherPrice

▸ **getEtherPrice**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:128

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Inherited from

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getFeeData](akashaproject_ui_app_loader._internal_.Provider.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:125

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getGasPrice](akashaproject_ui_app_loader._internal_.Provider.md#getgasprice)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:110

___

### getLogs

▸ **getLogs**(`filter`): `Promise`<[`Log`](../interfaces/akashaproject_ui_app_loader._internal_.Log.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md) \| `Promise`<[`Filter`](../interfaces/akashaproject_ui_app_loader._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_ui_app_loader._internal_.FilterByBlockHash.md)\> |

#### Returns

`Promise`<[`Log`](../interfaces/akashaproject_ui_app_loader._internal_.Log.md)[]\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getLogs](akashaproject_ui_app_loader._internal_.Provider.md#getlogs)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:127

___

### getNetwork

▸ **getNetwork**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getNetwork](akashaproject_ui_app_loader._internal_.Provider.md#getnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:92

___

### getResolver

▸ **getResolver**(`name`): `Promise`<[`Resolver`](akashaproject_ui_app_loader._internal_.Resolver.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<[`Resolver`](akashaproject_ui_app_loader._internal_.Resolver.md)\>

#### Implementation of

[EnsProvider](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md).[getResolver](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md#getresolver)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:130

___

### getStorageAt

▸ **getStorageAt**(`addressOrName`, `position`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `position` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) \| `Promise`<[`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getStorageAt](akashaproject_ui_app_loader._internal_.Provider.md#getstorageat)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:114

___

### getTransaction

▸ **getTransaction**(`transactionHash`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getTransaction](akashaproject_ui_app_loader._internal_.Provider.md#gettransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:125

___

### getTransactionCount

▸ **getTransactionCount**(`addressOrName`, `blockTag?`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_ui_app_loader._internal_.md#blocktag)\> |

#### Returns

`Promise`<`number`\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getTransactionCount](akashaproject_ui_app_loader._internal_.Provider.md#gettransactioncount)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:112

___

### getTransactionReceipt

▸ **getTransactionReceipt**(`transactionHash`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[getTransactionReceipt](akashaproject_ui_app_loader._internal_.Provider.md#gettransactionreceipt)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:126

___

### listenerCount

▸ **listenerCount**(`eventName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |

#### Returns

`number`

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[listenerCount](akashaproject_ui_app_loader._internal_.Provider.md#listenercount)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:142

___

### listeners

▸ **listeners**(`eventName?`): [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |

#### Returns

[`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener)[]

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[listeners](akashaproject_ui_app_loader._internal_.Provider.md#listeners)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:143

___

### lookupAddress

▸ **lookupAddress**(`address`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<`string`\>

#### Implementation of

[EnsProvider](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md).[lookupAddress](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md#lookupaddress)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[lookupAddress](akashaproject_ui_app_loader._internal_.Provider.md#lookupaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:133

___

### off

▸ **off**(`eventName`, `listener?`): [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener?` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[off](akashaproject_ui_app_loader._internal_.Provider.md#off)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:144

___

### on

▸ **on**(`eventName`, `listener`): [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[on](akashaproject_ui_app_loader._internal_.Provider.md#on)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:139

___

### once

▸ **once**(`eventName`, `listener`): [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[once](akashaproject_ui_app_loader._internal_.Provider.md#once)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:140

___

### perform

▸ **perform**(`method`, `params`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any` |

#### Returns

`Promise`<`any`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:135

___

### poll

▸ **poll**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:88

___

### removeAllListeners

▸ **removeAllListeners**(`eventName?`): [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |

#### Returns

[`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[removeAllListeners](akashaproject_ui_app_loader._internal_.Provider.md#removealllisteners)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:145

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): [`Provider`](akashaproject_ui_app_loader._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_ui_app_loader._internal_.Provider.md)

#### Inherited from

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[removeListener](akashaproject_ui_app_loader._internal_.Provider.md#removelistener)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:148

___

### resetEventsBlock

▸ **resetEventsBlock**(`blockNumber`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockNumber` | `number` |

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:89

___

### resolveName

▸ **resolveName**(`name`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<`string`\>

#### Implementation of

[EnsProvider](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md).[resolveName](../interfaces/akashaproject_ui_app_loader._internal_.EnsProvider.md#resolvename)

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[resolveName](akashaproject_ui_app_loader._internal_.Provider.md#resolvename)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:132

___

### sendTransaction

▸ **sendTransaction**(`signedTransaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signedTransaction` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[sendTransaction](akashaproject_ui_app_loader._internal_.Provider.md#sendtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:116

___

### waitForTransaction

▸ **waitForTransaction**(`transactionHash`, `confirmations?`, `timeout?`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations?` | `number` |
| `timeout?` | `number` |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionReceipt.md)\>

#### Overrides

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[waitForTransaction](akashaproject_ui_app_loader._internal_.Provider.md#waitfortransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:100

___

### getFormatter

▸ `Static` **getFormatter**(): [`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Returns

[`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:85

___

### getNetwork

▸ `Static` **getNetwork**(`network`): [`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Parameters

| Name | Type |
| :------ | :------ |
| `network` | [`Networkish`](../modules/akashaproject_ui_app_loader._internal_.md#networkish) |

#### Returns

[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:86

___

### isProvider

▸ `Static` **isProvider**(`value`): value is Provider

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is Provider

#### Inherited from

[Provider](akashaproject_ui_app_loader._internal_.Provider.md).[isProvider](akashaproject_ui_app_loader._internal_.Provider.md#isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:152
