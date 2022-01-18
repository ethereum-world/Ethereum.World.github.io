[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Web3Provider

# Class: Web3Provider

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Web3Provider

## Hierarchy

- [`JsonRpcProvider`](akashaproject_awf_sdk._internal_.JsonRpcProvider.md)

  ↳ **`Web3Provider`**

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.Web3Provider.md#constructor)

### Properties

- [\_bootstrapPoll](akashaproject_awf_sdk._internal_.Web3Provider.md#_bootstrappoll)
- [\_emitted](akashaproject_awf_sdk._internal_.Web3Provider.md#_emitted)
- [\_eventLoopCache](akashaproject_awf_sdk._internal_.Web3Provider.md#_eventloopcache)
- [\_events](akashaproject_awf_sdk._internal_.Web3Provider.md#_events)
- [\_fastBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_fastblocknumber)
- [\_fastBlockNumberPromise](akashaproject_awf_sdk._internal_.Web3Provider.md#_fastblocknumberpromise)
- [\_fastQueryDate](akashaproject_awf_sdk._internal_.Web3Provider.md#_fastquerydate)
- [\_internalBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_internalblocknumber)
- [\_isProvider](akashaproject_awf_sdk._internal_.Web3Provider.md#_isprovider)
- [\_lastBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_lastblocknumber)
- [\_maxInternalBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_maxinternalblocknumber)
- [\_network](akashaproject_awf_sdk._internal_.Web3Provider.md#_network)
- [\_networkPromise](akashaproject_awf_sdk._internal_.Web3Provider.md#_networkpromise)
- [\_nextId](akashaproject_awf_sdk._internal_.Web3Provider.md#_nextid)
- [\_pendingFilter](akashaproject_awf_sdk._internal_.Web3Provider.md#_pendingfilter)
- [\_poller](akashaproject_awf_sdk._internal_.Web3Provider.md#_poller)
- [\_pollingInterval](akashaproject_awf_sdk._internal_.Web3Provider.md#_pollinginterval)
- [anyNetwork](akashaproject_awf_sdk._internal_.Web3Provider.md#anynetwork)
- [connection](akashaproject_awf_sdk._internal_.Web3Provider.md#connection)
- [formatter](akashaproject_awf_sdk._internal_.Web3Provider.md#formatter)
- [jsonRpcFetchFunc](akashaproject_awf_sdk._internal_.Web3Provider.md#jsonrpcfetchfunc)
- [provider](akashaproject_awf_sdk._internal_.Web3Provider.md#provider)

### Accessors

- [\_cache](akashaproject_awf_sdk._internal_.Web3Provider.md#_cache)
- [blockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#blocknumber)
- [network](akashaproject_awf_sdk._internal_.Web3Provider.md#network)
- [polling](akashaproject_awf_sdk._internal_.Web3Provider.md#polling)
- [pollingInterval](akashaproject_awf_sdk._internal_.Web3Provider.md#pollinginterval)
- [ready](akashaproject_awf_sdk._internal_.Web3Provider.md#ready)

### Methods

- [\_addEventListener](akashaproject_awf_sdk._internal_.Web3Provider.md#_addeventlistener)
- [\_getAddress](akashaproject_awf_sdk._internal_.Web3Provider.md#_getaddress)
- [\_getBlock](akashaproject_awf_sdk._internal_.Web3Provider.md#_getblock)
- [\_getBlockTag](akashaproject_awf_sdk._internal_.Web3Provider.md#_getblocktag)
- [\_getFastBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_getfastblocknumber)
- [\_getFilter](akashaproject_awf_sdk._internal_.Web3Provider.md#_getfilter)
- [\_getInternalBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_getinternalblocknumber)
- [\_getResolver](akashaproject_awf_sdk._internal_.Web3Provider.md#_getresolver)
- [\_getTransactionRequest](akashaproject_awf_sdk._internal_.Web3Provider.md#_gettransactionrequest)
- [\_ready](akashaproject_awf_sdk._internal_.Web3Provider.md#_ready)
- [\_setFastBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#_setfastblocknumber)
- [\_startEvent](akashaproject_awf_sdk._internal_.Web3Provider.md#_startevent)
- [\_startPending](akashaproject_awf_sdk._internal_.Web3Provider.md#_startpending)
- [\_stopEvent](akashaproject_awf_sdk._internal_.Web3Provider.md#_stopevent)
- [\_uncachedDetectNetwork](akashaproject_awf_sdk._internal_.Web3Provider.md#_uncacheddetectnetwork)
- [\_waitForTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#_waitfortransaction)
- [\_wrapTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#_wraptransaction)
- [addListener](akashaproject_awf_sdk._internal_.Web3Provider.md#addlistener)
- [call](akashaproject_awf_sdk._internal_.Web3Provider.md#call)
- [detectNetwork](akashaproject_awf_sdk._internal_.Web3Provider.md#detectnetwork)
- [emit](akashaproject_awf_sdk._internal_.Web3Provider.md#emit)
- [estimateGas](akashaproject_awf_sdk._internal_.Web3Provider.md#estimategas)
- [getAvatar](akashaproject_awf_sdk._internal_.Web3Provider.md#getavatar)
- [getBalance](akashaproject_awf_sdk._internal_.Web3Provider.md#getbalance)
- [getBlock](akashaproject_awf_sdk._internal_.Web3Provider.md#getblock)
- [getBlockNumber](akashaproject_awf_sdk._internal_.Web3Provider.md#getblocknumber)
- [getBlockWithTransactions](akashaproject_awf_sdk._internal_.Web3Provider.md#getblockwithtransactions)
- [getCode](akashaproject_awf_sdk._internal_.Web3Provider.md#getcode)
- [getEtherPrice](akashaproject_awf_sdk._internal_.Web3Provider.md#getetherprice)
- [getFeeData](akashaproject_awf_sdk._internal_.Web3Provider.md#getfeedata)
- [getGasPrice](akashaproject_awf_sdk._internal_.Web3Provider.md#getgasprice)
- [getLogs](akashaproject_awf_sdk._internal_.Web3Provider.md#getlogs)
- [getNetwork](akashaproject_awf_sdk._internal_.Web3Provider.md#getnetwork)
- [getResolver](akashaproject_awf_sdk._internal_.Web3Provider.md#getresolver)
- [getSigner](akashaproject_awf_sdk._internal_.Web3Provider.md#getsigner)
- [getStorageAt](akashaproject_awf_sdk._internal_.Web3Provider.md#getstorageat)
- [getTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#gettransaction)
- [getTransactionCount](akashaproject_awf_sdk._internal_.Web3Provider.md#gettransactioncount)
- [getTransactionReceipt](akashaproject_awf_sdk._internal_.Web3Provider.md#gettransactionreceipt)
- [getUncheckedSigner](akashaproject_awf_sdk._internal_.Web3Provider.md#getuncheckedsigner)
- [listAccounts](akashaproject_awf_sdk._internal_.Web3Provider.md#listaccounts)
- [listenerCount](akashaproject_awf_sdk._internal_.Web3Provider.md#listenercount)
- [listeners](akashaproject_awf_sdk._internal_.Web3Provider.md#listeners)
- [lookupAddress](akashaproject_awf_sdk._internal_.Web3Provider.md#lookupaddress)
- [off](akashaproject_awf_sdk._internal_.Web3Provider.md#off)
- [on](akashaproject_awf_sdk._internal_.Web3Provider.md#on)
- [once](akashaproject_awf_sdk._internal_.Web3Provider.md#once)
- [perform](akashaproject_awf_sdk._internal_.Web3Provider.md#perform)
- [poll](akashaproject_awf_sdk._internal_.Web3Provider.md#poll)
- [prepareRequest](akashaproject_awf_sdk._internal_.Web3Provider.md#preparerequest)
- [removeAllListeners](akashaproject_awf_sdk._internal_.Web3Provider.md#removealllisteners)
- [removeListener](akashaproject_awf_sdk._internal_.Web3Provider.md#removelistener)
- [resetEventsBlock](akashaproject_awf_sdk._internal_.Web3Provider.md#reseteventsblock)
- [resolveName](akashaproject_awf_sdk._internal_.Web3Provider.md#resolvename)
- [send](akashaproject_awf_sdk._internal_.Web3Provider.md#send)
- [sendTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#sendtransaction)
- [waitForTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#waitfortransaction)
- [defaultUrl](akashaproject_awf_sdk._internal_.Web3Provider.md#defaulturl)
- [getFormatter](akashaproject_awf_sdk._internal_.Web3Provider.md#getformatter)
- [getNetwork](akashaproject_awf_sdk._internal_.Web3Provider.md#getnetwork)
- [hexlifyTransaction](akashaproject_awf_sdk._internal_.Web3Provider.md#hexlifytransaction)
- [isProvider](akashaproject_awf_sdk._internal_.Web3Provider.md#isprovider)

## Constructors

### constructor

• **new Web3Provider**(`provider`, `network?`)

 ready

 A Promise<Network> that resolves only once the provider is ready.

 Sub-classes that call the super with a network without a chainId
 MUST set this. Standard named networks have a known chainId.

#### Parameters

| Name | Type |
| :------ | :------ |
| `provider` | [`ExternalProvider`](../modules/akashaproject_awf_sdk._internal_.md#externalprovider) \| [`JsonRpcFetchFunc`](../modules/akashaproject_awf_sdk._internal_.md#jsonrpcfetchfunc) |
| `network?` | [`Networkish`](../modules/akashaproject_awf_sdk._internal_.md#networkish) |

#### Overrides

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[constructor](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/web3-provider.d.ts:25

## Properties

### \_bootstrapPoll

• **\_bootstrapPoll**: [`Timer`](../interfaces/akashaproject_awf_sdk._internal_.Timer.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_bootstrapPoll](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_bootstrappoll)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:61

___

### \_emitted

• **\_emitted**: `Object`

#### Index signature

▪ [eventName: `string`]: `number` \| ``"pending"``

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_emitted](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_emitted)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:56

___

### \_eventLoopCache

• **\_eventLoopCache**: [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_eventLoopCache](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_eventloopcache)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:32

___

### \_events

• **\_events**: [`Event`](akashaproject_awf_sdk._internal_.Event.md)[]

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_events](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_events)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:54

___

### \_fastBlockNumber

• **\_fastBlockNumber**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_fastBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_fastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:63

___

### \_fastBlockNumberPromise

• **\_fastBlockNumberPromise**: `Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_fastBlockNumberPromise](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_fastblocknumberpromise)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:64

___

### \_fastQueryDate

• **\_fastQueryDate**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_fastQueryDate](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_fastquerydate)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:65

___

### \_internalBlockNumber

• **\_internalBlockNumber**: `Promise`<{ `blockNumber`: `number` ; `reqTime`: `number` ; `respTime`: `number`  }\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_internalBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_internalblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:67

___

### \_isProvider

• `Readonly` **\_isProvider**: `boolean`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_isProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:150

___

### \_lastBlockNumber

• **\_lastBlockNumber**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_lastBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_lastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:62

___

### \_maxInternalBlockNumber

• **\_maxInternalBlockNumber**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_maxInternalBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_maxinternalblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:66

___

### \_network

• **\_network**: [`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_network](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_network)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:53

___

### \_networkPromise

• **\_networkPromise**: `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_networkPromise](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_networkpromise)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:52

___

### \_nextId

• **\_nextId**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_nextId](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_nextid)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:31

___

### \_pendingFilter

• **\_pendingFilter**: `Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_pendingFilter](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_pendingfilter)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:30

___

### \_poller

• **\_poller**: [`Timer`](../interfaces/akashaproject_awf_sdk._internal_.Timer.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_poller](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_poller)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:60

___

### \_pollingInterval

• **\_pollingInterval**: `number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_pollingInterval](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_pollinginterval)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:59

___

### anyNetwork

• `Readonly` **anyNetwork**: `boolean`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[anyNetwork](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#anynetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:72

___

### connection

• `Readonly` **connection**: [`ConnectionInfo`](../modules/akashaproject_awf_sdk._internal_.md#connectioninfo)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[connection](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#connection)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:29

___

### formatter

• **formatter**: [`Formatter`](akashaproject_awf_sdk._internal_.Formatter.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[formatter](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#formatter)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:55

___

### jsonRpcFetchFunc

• `Readonly` **jsonRpcFetchFunc**: [`JsonRpcFetchFunc`](../modules/akashaproject_awf_sdk._internal_.md#jsonrpcfetchfunc)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/web3-provider.d.ts:24

___

### provider

• `Readonly` **provider**: [`ExternalProvider`](../modules/akashaproject_awf_sdk._internal_.md#externalprovider)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/web3-provider.d.ts:23

## Accessors

### \_cache

• `get` **_cache**(): [`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Returns

[`Record`](../modules/akashaproject_awf_sdk._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Inherited from

JsonRpcProvider.\_cache

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:33

___

### blockNumber

• `get` **blockNumber**(): `number`

#### Returns

`number`

#### Inherited from

JsonRpcProvider.blockNumber

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:93

___

### network

• `get` **network**(): [`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)

#### Returns

[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)

#### Inherited from

JsonRpcProvider.network

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:90

___

### polling

• `get` **polling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

JsonRpcProvider.polling

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:94

• `set` **polling**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

#### Inherited from

JsonRpcProvider.polling

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:95

___

### pollingInterval

• `get` **pollingInterval**(): `number`

#### Returns

`number`

#### Inherited from

JsonRpcProvider.pollingInterval

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:96

• `set` **pollingInterval**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

`void`

#### Inherited from

JsonRpcProvider.pollingInterval

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:97

___

### ready

• `get` **ready**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

JsonRpcProvider.ready

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:84

## Methods

### \_addEventListener

▸ **_addEventListener**(`eventName`, `listener`, `once`): [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |
| `once` | `boolean` |

#### Returns

[`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_addEventListener](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_addeventlistener)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getAddress](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:121

___

### \_getBlock

▸ **_getBlock**(`blockHashOrBlockTag`, `includeTransactions?`): `Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md) \| [`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |
| `includeTransactions?` | `boolean` |

#### Returns

`Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md) \| [`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getBlock](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getblock)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:122

___

### \_getBlockTag

▸ **_getBlockTag**(`blockTag`): `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getBlockTag](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getblocktag)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:129

___

### \_getFastBlockNumber

▸ **_getFastBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getFastBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getfastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:98

___

### \_getFilter

▸ **_getFilter**(`filter`): `Promise`<[`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md) \| `Promise`<[`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md)\> |

#### Returns

`Promise`<[`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getFilter](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getfilter)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getInternalBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getinternalblocknumber)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getResolver](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_getresolver)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:131

___

### \_getTransactionRequest

▸ **_getTransactionRequest**(`transaction`): `Promise`<[`Transaction`](../interfaces/akashaproject_awf_sdk._internal_.Transaction.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`Transaction`](../interfaces/akashaproject_awf_sdk._internal_.Transaction.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_getTransactionRequest](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_gettransactionrequest)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:117

___

### \_ready

▸ **_ready**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_ready](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_ready)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_setFastBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_setfastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:99

___

### \_startEvent

▸ **_startEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Event`](akashaproject_awf_sdk._internal_.Event.md) |

#### Returns

`void`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_startEvent](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_startevent)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:44

___

### \_startPending

▸ **_startPending**(): `void`

#### Returns

`void`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_startPending](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_startpending)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:45

___

### \_stopEvent

▸ **_stopEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Event`](akashaproject_awf_sdk._internal_.Event.md) |

#### Returns

`void`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_stopEvent](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_stopevent)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:46

___

### \_uncachedDetectNetwork

▸ **_uncachedDetectNetwork**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_uncachedDetectNetwork](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_uncacheddetectnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:37

___

### \_waitForTransaction

▸ **_waitForTransaction**(`transactionHash`, `confirmations`, `timeout`, `replaceable`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

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
| `replaceable.value` | [`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md) |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_waitForTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_waitfortransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:101

___

### \_wrapTransaction

▸ **_wrapTransaction**(`tx`, `hash?`, `startBlock?`): [`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | [`Transaction`](../interfaces/akashaproject_awf_sdk._internal_.Transaction.md) |
| `hash?` | `string` |
| `startBlock?` | `number` |

#### Returns

[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[_wrapTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#_wraptransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:115

___

### addListener

▸ **addListener**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[addListener](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#addlistener)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:147

___

### call

▸ **call**(`transaction`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[call](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#call)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:119

___

### detectNetwork

▸ **detectNetwork**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[detectNetwork](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#detectnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:36

___

### emit

▸ **emit**(`eventName`, ...`args`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[emit](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#emit)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:141

___

### estimateGas

▸ **estimateGas**(`transaction`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`Deferrable`](../modules/akashaproject_awf_sdk._internal_.md#deferrable)<[`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[estimateGas](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#estimategas)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getAvatar](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getavatar)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:134

___

### getBalance

▸ **getBalance**(`addressOrName`, `blockTag?`): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getBalance](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getbalance)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:111

___

### getBlock

▸ **getBlock**(`blockHashOrBlockTag`): `Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`Block`](../interfaces/akashaproject_awf_sdk._internal_.Block.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getBlock](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getblock)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:123

___

### getBlockNumber

▸ **getBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getBlockNumber](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:109

___

### getBlockWithTransactions

▸ **getBlockWithTransactions**(`blockHashOrBlockTag`): `Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `blockHashOrBlockTag` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<[`BlockWithTransactions`](../interfaces/akashaproject_awf_sdk._internal_.BlockWithTransactions.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getBlockWithTransactions](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getblockwithtransactions)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:124

___

### getCode

▸ **getCode**(`addressOrName`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getCode](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getcode)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:113

___

### getEtherPrice

▸ **getEtherPrice**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getEtherPrice](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getetherprice)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:128

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_awf_sdk._internal_.FeeData.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getFeeData](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:125

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_awf_sdk._internal_.BigNumber.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getGasPrice](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getgasprice)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:110

___

### getLogs

▸ **getLogs**(`filter`): `Promise`<[`Log`](../interfaces/akashaproject_awf_sdk._internal_.Log.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `filter` | [`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md) \| `Promise`<[`Filter`](../interfaces/akashaproject_awf_sdk._internal_.Filter.md) \| [`FilterByBlockHash`](../interfaces/akashaproject_awf_sdk._internal_.FilterByBlockHash.md)\> |

#### Returns

`Promise`<[`Log`](../interfaces/akashaproject_awf_sdk._internal_.Log.md)[]\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getLogs](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getlogs)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:127

___

### getNetwork

▸ **getNetwork**(): `Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getNetwork](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:92

___

### getResolver

▸ **getResolver**(`name`): `Promise`<[`Resolver`](akashaproject_awf_sdk._internal_.Resolver.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<[`Resolver`](akashaproject_awf_sdk._internal_.Resolver.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getResolver](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getresolver)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:130

___

### getSigner

▸ **getSigner**(`addressOrIndex?`): [`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

[`JsonRpcSigner`](akashaproject_awf_sdk._internal_.JsonRpcSigner.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getSigner](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getsigner)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:38

___

### getStorageAt

▸ **getStorageAt**(`addressOrName`, `position`, `blockTag?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `position` | [`BigNumberish`](../modules/akashaproject_awf_sdk._internal_.md#bignumberish) \| `Promise`<[`BigNumberish`](../modules/akashaproject_awf_sdk._internal_.md#bignumberish)\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`string`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getStorageAt](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getstorageat)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:114

___

### getTransaction

▸ **getTransaction**(`transactionHash`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#gettransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:125

___

### getTransactionCount

▸ **getTransactionCount**(`addressOrName`, `blockTag?`): `Promise`<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrName` | `string` \| `Promise`<`string`\> |
| `blockTag?` | [`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag) \| `Promise`<[`BlockTag`](../modules/akashaproject_awf_sdk._internal_.md#blocktag)\> |

#### Returns

`Promise`<`number`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getTransactionCount](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#gettransactioncount)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:112

___

### getTransactionReceipt

▸ **getTransactionReceipt**(`transactionHash`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getTransactionReceipt](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#gettransactionreceipt)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:126

___

### getUncheckedSigner

▸ **getUncheckedSigner**(`addressOrIndex?`): [`UncheckedJsonRpcSigner`](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

[`UncheckedJsonRpcSigner`](akashaproject_awf_sdk._internal_.UncheckedJsonRpcSigner.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getUncheckedSigner](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getuncheckedsigner)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:39

___

### listAccounts

▸ **listAccounts**(): `Promise`<`string`[]\>

#### Returns

`Promise`<`string`[]\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[listAccounts](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#listaccounts)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:40

___

### listenerCount

▸ **listenerCount**(`eventName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

`number`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[listenerCount](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#listenercount)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:142

___

### listeners

▸ **listeners**(`eventName?`): [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

[`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener)[]

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[listeners](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#listeners)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[lookupAddress](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#lookupaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:133

___

### off

▸ **off**(`eventName`, `listener?`): [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener?` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[off](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#off)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:144

___

### on

▸ **on**(`eventName`, `listener`): [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[on](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#on)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:139

___

### once

▸ **once**(`eventName`, `listener`): [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[once](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#once)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[perform](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#perform)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:43

___

### poll

▸ **poll**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[poll](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#poll)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:88

___

### prepareRequest

▸ **prepareRequest**(`method`, `params`): [`string`, `any`[]]

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any` |

#### Returns

[`string`, `any`[]]

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[prepareRequest](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#preparerequest)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:42

___

### removeAllListeners

▸ **removeAllListeners**(`eventName?`): [`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |

#### Returns

[`Web3Provider`](akashaproject_awf_sdk._internal_.Web3Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[removeAllListeners](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#removealllisteners)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:145

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): [`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_awf_sdk._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_awf_sdk._internal_.md#listener) |

#### Returns

[`Provider`](akashaproject_awf_sdk._internal_.Provider.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[removeListener](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#removelistener)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[resetEventsBlock](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#reseteventsblock)

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

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[resolveName](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#resolvename)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:132

___

### send

▸ **send**(`method`, `params`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `params` | `any`[] |

#### Returns

`Promise`<`any`\>

#### Overrides

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[send](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#send)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/web3-provider.d.ts:26

___

### sendTransaction

▸ **sendTransaction**(`signedTransaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signedTransaction` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_awf_sdk._internal_.TransactionResponse.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[sendTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#sendtransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:116

___

### waitForTransaction

▸ **waitForTransaction**(`transactionHash`, `confirmations?`, `timeout?`): `Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `transactionHash` | `string` |
| `confirmations?` | `number` |
| `timeout?` | `number` |

#### Returns

`Promise`<[`TransactionReceipt`](../interfaces/akashaproject_awf_sdk._internal_.TransactionReceipt.md)\>

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[waitForTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#waitfortransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:100

___

### defaultUrl

▸ `Static` **defaultUrl**(): `string`

#### Returns

`string`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[defaultUrl](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#defaulturl)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:35

___

### getFormatter

▸ `Static` **getFormatter**(): [`Formatter`](akashaproject_awf_sdk._internal_.Formatter.md)

#### Returns

[`Formatter`](akashaproject_awf_sdk._internal_.Formatter.md)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getFormatter](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getformatter)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:85

___

### getNetwork

▸ `Static` **getNetwork**(`network`): [`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)

#### Parameters

| Name | Type |
| :------ | :------ |
| `network` | [`Networkish`](../modules/akashaproject_awf_sdk._internal_.md#networkish) |

#### Returns

[`Network`](../modules/akashaproject_awf_sdk._internal_.md#network)

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[getNetwork](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#getnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:86

___

### hexlifyTransaction

▸ `Static` **hexlifyTransaction**(`transaction`, `allowExtra?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`TransactionRequest`](../modules/akashaproject_awf_sdk._internal_.md#transactionrequest) |
| `allowExtra?` | `Object` |

#### Returns

`Object`

#### Inherited from

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[hexlifyTransaction](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#hexlifytransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:47

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

[JsonRpcProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md).[isProvider](akashaproject_awf_sdk._internal_.JsonRpcProvider.md#isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:152
