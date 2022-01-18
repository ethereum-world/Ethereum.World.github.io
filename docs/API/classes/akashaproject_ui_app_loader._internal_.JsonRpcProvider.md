[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / JsonRpcProvider

# Class: JsonRpcProvider

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).JsonRpcProvider

## Hierarchy

- [`BaseProvider`](akashaproject_ui_app_loader._internal_.BaseProvider.md)

  ↳ **`JsonRpcProvider`**

  ↳↳ [`Web3Provider`](akashaproject_ui_app_loader._internal_.Web3Provider.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#constructor)

### Properties

- [\_bootstrapPoll](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_bootstrappoll)
- [\_emitted](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_emitted)
- [\_eventLoopCache](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_eventloopcache)
- [\_events](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_events)
- [\_fastBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_fastblocknumber)
- [\_fastBlockNumberPromise](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_fastblocknumberpromise)
- [\_fastQueryDate](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_fastquerydate)
- [\_internalBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_internalblocknumber)
- [\_isProvider](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_isprovider)
- [\_lastBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_lastblocknumber)
- [\_maxInternalBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_maxinternalblocknumber)
- [\_network](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_network)
- [\_networkPromise](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_networkpromise)
- [\_nextId](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_nextid)
- [\_pendingFilter](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_pendingfilter)
- [\_poller](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_poller)
- [\_pollingInterval](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_pollinginterval)
- [anyNetwork](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#anynetwork)
- [connection](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#connection)
- [formatter](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#formatter)

### Accessors

- [\_cache](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_cache)
- [blockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#blocknumber)
- [network](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#network)
- [polling](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#polling)
- [pollingInterval](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#pollinginterval)
- [ready](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#ready)

### Methods

- [\_addEventListener](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_addeventlistener)
- [\_getAddress](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getaddress)
- [\_getBlock](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getblock)
- [\_getBlockTag](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getblocktag)
- [\_getFastBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getfastblocknumber)
- [\_getFilter](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getfilter)
- [\_getInternalBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getinternalblocknumber)
- [\_getResolver](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_getresolver)
- [\_getTransactionRequest](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_gettransactionrequest)
- [\_ready](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_ready)
- [\_setFastBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_setfastblocknumber)
- [\_startEvent](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_startevent)
- [\_startPending](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_startpending)
- [\_stopEvent](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_stopevent)
- [\_uncachedDetectNetwork](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_uncacheddetectnetwork)
- [\_waitForTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_waitfortransaction)
- [\_wrapTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#_wraptransaction)
- [addListener](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#addlistener)
- [call](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#call)
- [detectNetwork](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#detectnetwork)
- [emit](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#emit)
- [estimateGas](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#estimategas)
- [getAvatar](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getavatar)
- [getBalance](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getbalance)
- [getBlock](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getblock)
- [getBlockNumber](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getblocknumber)
- [getBlockWithTransactions](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getblockwithtransactions)
- [getCode](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getcode)
- [getEtherPrice](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getetherprice)
- [getFeeData](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getfeedata)
- [getGasPrice](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getgasprice)
- [getLogs](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getlogs)
- [getNetwork](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getnetwork)
- [getResolver](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getresolver)
- [getSigner](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getsigner)
- [getStorageAt](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getstorageat)
- [getTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#gettransaction)
- [getTransactionCount](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#gettransactioncount)
- [getTransactionReceipt](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#gettransactionreceipt)
- [getUncheckedSigner](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getuncheckedsigner)
- [listAccounts](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#listaccounts)
- [listenerCount](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#listenercount)
- [listeners](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#listeners)
- [lookupAddress](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#lookupaddress)
- [off](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#off)
- [on](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#on)
- [once](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#once)
- [perform](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#perform)
- [poll](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#poll)
- [prepareRequest](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#preparerequest)
- [removeAllListeners](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#removealllisteners)
- [removeListener](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#removelistener)
- [resetEventsBlock](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#reseteventsblock)
- [resolveName](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#resolvename)
- [send](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#send)
- [sendTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#sendtransaction)
- [waitForTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#waitfortransaction)
- [defaultUrl](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#defaulturl)
- [getFormatter](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getformatter)
- [getNetwork](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#getnetwork)
- [hexlifyTransaction](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#hexlifytransaction)
- [isProvider](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md#isprovider)

## Constructors

### constructor

• **new JsonRpcProvider**(`url?`, `network?`)

 ready

 A Promise<Network> that resolves only once the provider is ready.

 Sub-classes that call the super with a network without a chainId
 MUST set this. Standard named networks have a known chainId.

#### Parameters

| Name | Type |
| :------ | :------ |
| `url?` | `string` \| [`ConnectionInfo`](../modules/akashaproject_ui_app_loader._internal_.md#connectioninfo) |
| `network?` | [`Networkish`](../modules/akashaproject_ui_app_loader._internal_.md#networkish) |

#### Overrides

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[constructor](akashaproject_ui_app_loader._internal_.BaseProvider.md#constructor)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:34

## Properties

### \_bootstrapPoll

• **\_bootstrapPoll**: [`Timer`](../interfaces/akashaproject_ui_app_loader._internal_.Timer.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_bootstrapPoll](akashaproject_ui_app_loader._internal_.BaseProvider.md#_bootstrappoll)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:61

___

### \_emitted

• **\_emitted**: `Object`

#### Index signature

▪ [eventName: `string`]: `number` \| ``"pending"``

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_emitted](akashaproject_ui_app_loader._internal_.BaseProvider.md#_emitted)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:56

___

### \_eventLoopCache

• **\_eventLoopCache**: [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:32

___

### \_events

• **\_events**: [`Event`](akashaproject_ui_app_loader._internal_.Event.md)[]

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_events](akashaproject_ui_app_loader._internal_.BaseProvider.md#_events)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:54

___

### \_fastBlockNumber

• **\_fastBlockNumber**: `number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_fastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:63

___

### \_fastBlockNumberPromise

• **\_fastBlockNumberPromise**: `Promise`<`number`\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_fastBlockNumberPromise](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastblocknumberpromise)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:64

___

### \_fastQueryDate

• **\_fastQueryDate**: `number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_fastQueryDate](akashaproject_ui_app_loader._internal_.BaseProvider.md#_fastquerydate)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:65

___

### \_internalBlockNumber

• **\_internalBlockNumber**: `Promise`<{ `blockNumber`: `number` ; `reqTime`: `number` ; `respTime`: `number`  }\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_internalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_internalblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:67

___

### \_isProvider

• `Readonly` **\_isProvider**: `boolean`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_isProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md#_isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:150

___

### \_lastBlockNumber

• **\_lastBlockNumber**: `number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_lastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_lastblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:62

___

### \_maxInternalBlockNumber

• **\_maxInternalBlockNumber**: `number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_maxInternalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_maxinternalblocknumber)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:66

___

### \_network

• **\_network**: [`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_network](akashaproject_ui_app_loader._internal_.BaseProvider.md#_network)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:53

___

### \_networkPromise

• **\_networkPromise**: `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_networkPromise](akashaproject_ui_app_loader._internal_.BaseProvider.md#_networkpromise)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:52

___

### \_nextId

• **\_nextId**: `number`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:31

___

### \_pendingFilter

• **\_pendingFilter**: `Promise`<`number`\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:30

___

### \_poller

• **\_poller**: [`Timer`](../interfaces/akashaproject_ui_app_loader._internal_.Timer.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_poller](akashaproject_ui_app_loader._internal_.BaseProvider.md#_poller)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:60

___

### \_pollingInterval

• **\_pollingInterval**: `number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_pollingInterval](akashaproject_ui_app_loader._internal_.BaseProvider.md#_pollinginterval)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:59

___

### anyNetwork

• `Readonly` **anyNetwork**: `boolean`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[anyNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#anynetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:72

___

### connection

• `Readonly` **connection**: [`ConnectionInfo`](../modules/akashaproject_ui_app_loader._internal_.md#connectioninfo)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:29

___

### formatter

• **formatter**: [`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[formatter](akashaproject_ui_app_loader._internal_.BaseProvider.md#formatter)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:55

## Accessors

### \_cache

• `get` **_cache**(): [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Returns

[`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `Promise`<`any`\>\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:33

___

### blockNumber

• `get` **blockNumber**(): `number`

#### Returns

`number`

#### Inherited from

BaseProvider.blockNumber

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:93

___

### network

• `get` **network**(): [`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Returns

[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)

#### Inherited from

BaseProvider.network

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:90

___

### polling

• `get` **polling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

BaseProvider.polling

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

BaseProvider.polling

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:95

___

### pollingInterval

• `get` **pollingInterval**(): `number`

#### Returns

`number`

#### Inherited from

BaseProvider.pollingInterval

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

BaseProvider.pollingInterval

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:97

___

### ready

• `get` **ready**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Inherited from

BaseProvider.ready

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:84

## Methods

### \_addEventListener

▸ **_addEventListener**(`eventName`, `listener`, `once`): [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |
| `once` | `boolean` |

#### Returns

[`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_addEventListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#_addeventlistener)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getAddress](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getaddress)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getblock)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getBlockTag](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getblocktag)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:129

___

### \_getFastBlockNumber

▸ **_getFastBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getFastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getfastblocknumber)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getFilter](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getfilter)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getInternalBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getinternalblocknumber)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getResolver](akashaproject_ui_app_loader._internal_.BaseProvider.md#_getresolver)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_getTransactionRequest](akashaproject_ui_app_loader._internal_.BaseProvider.md#_gettransactionrequest)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:117

___

### \_ready

▸ **_ready**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_ready](akashaproject_ui_app_loader._internal_.BaseProvider.md#_ready)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_setFastBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#_setfastblocknumber)

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

#### Overrides

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_startEvent](akashaproject_ui_app_loader._internal_.BaseProvider.md#_startevent)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:44

___

### \_startPending

▸ **_startPending**(): `void`

#### Returns

`void`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:45

___

### \_stopEvent

▸ **_stopEvent**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`Event`](akashaproject_ui_app_loader._internal_.Event.md) |

#### Returns

`void`

#### Overrides

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_stopEvent](akashaproject_ui_app_loader._internal_.BaseProvider.md#_stopevent)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:46

___

### \_uncachedDetectNetwork

▸ **_uncachedDetectNetwork**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:37

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_waitForTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#_waitfortransaction)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[_wrapTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#_wraptransaction)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[addListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#addlistener)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[call](akashaproject_ui_app_loader._internal_.BaseProvider.md#call)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:119

___

### detectNetwork

▸ **detectNetwork**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Overrides

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[detectNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#detectnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:36

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[emit](akashaproject_ui_app_loader._internal_.BaseProvider.md#emit)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[estimateGas](akashaproject_ui_app_loader._internal_.BaseProvider.md#estimategas)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getAvatar](akashaproject_ui_app_loader._internal_.BaseProvider.md#getavatar)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getBalance](akashaproject_ui_app_loader._internal_.BaseProvider.md#getbalance)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblock)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:123

___

### getBlockNumber

▸ **getBlockNumber**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getBlockNumber](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblocknumber)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getBlockWithTransactions](akashaproject_ui_app_loader._internal_.BaseProvider.md#getblockwithtransactions)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getCode](akashaproject_ui_app_loader._internal_.BaseProvider.md#getcode)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:113

___

### getEtherPrice

▸ **getEtherPrice**(): `Promise`<`number`\>

#### Returns

`Promise`<`number`\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getEtherPrice](akashaproject_ui_app_loader._internal_.BaseProvider.md#getetherprice)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:128

___

### getFeeData

▸ **getFeeData**(): `Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Returns

`Promise`<[`FeeData`](../interfaces/akashaproject_ui_app_loader._internal_.FeeData.md)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getFeeData](akashaproject_ui_app_loader._internal_.BaseProvider.md#getfeedata)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:125

___

### getGasPrice

▸ **getGasPrice**(): `Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Returns

`Promise`<[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getGasPrice](akashaproject_ui_app_loader._internal_.BaseProvider.md#getgasprice)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getLogs](akashaproject_ui_app_loader._internal_.BaseProvider.md#getlogs)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:127

___

### getNetwork

▸ **getNetwork**(): `Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Returns

`Promise`<[`Network`](../modules/akashaproject_ui_app_loader._internal_.md#network)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#getnetwork)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getResolver](akashaproject_ui_app_loader._internal_.BaseProvider.md#getresolver)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:130

___

### getSigner

▸ **getSigner**(`addressOrIndex?`): [`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

[`JsonRpcSigner`](akashaproject_ui_app_loader._internal_.JsonRpcSigner.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:38

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getStorageAt](akashaproject_ui_app_loader._internal_.BaseProvider.md#getstorageat)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransaction)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getTransactionCount](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransactioncount)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getTransactionReceipt](akashaproject_ui_app_loader._internal_.BaseProvider.md#gettransactionreceipt)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:126

___

### getUncheckedSigner

▸ **getUncheckedSigner**(`addressOrIndex?`): [`UncheckedJsonRpcSigner`](akashaproject_ui_app_loader._internal_.UncheckedJsonRpcSigner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `addressOrIndex?` | `string` \| `number` |

#### Returns

[`UncheckedJsonRpcSigner`](akashaproject_ui_app_loader._internal_.UncheckedJsonRpcSigner.md)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:39

___

### listAccounts

▸ **listAccounts**(): `Promise`<`string`[]\>

#### Returns

`Promise`<`string`[]\>

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:40

___

### listenerCount

▸ **listenerCount**(`eventName?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |

#### Returns

`number`

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[listenerCount](akashaproject_ui_app_loader._internal_.BaseProvider.md#listenercount)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[listeners](akashaproject_ui_app_loader._internal_.BaseProvider.md#listeners)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[lookupAddress](akashaproject_ui_app_loader._internal_.BaseProvider.md#lookupaddress)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:133

___

### off

▸ **off**(`eventName`, `listener?`): [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener?` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[off](akashaproject_ui_app_loader._internal_.BaseProvider.md#off)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:144

___

### on

▸ **on**(`eventName`, `listener`): [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[on](akashaproject_ui_app_loader._internal_.BaseProvider.md#on)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:139

___

### once

▸ **once**(`eventName`, `listener`): [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |
| `listener` | [`Listener`](../modules/akashaproject_ui_app_loader._internal_.md#listener) |

#### Returns

[`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[once](akashaproject_ui_app_loader._internal_.BaseProvider.md#once)

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

#### Overrides

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[perform](akashaproject_ui_app_loader._internal_.BaseProvider.md#perform)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:43

___

### poll

▸ **poll**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[poll](akashaproject_ui_app_loader._internal_.BaseProvider.md#poll)

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

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:42

___

### removeAllListeners

▸ **removeAllListeners**(`eventName?`): [`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | [`EventType`](../modules/akashaproject_ui_app_loader._internal_.md#eventtype) |

#### Returns

[`JsonRpcProvider`](akashaproject_ui_app_loader._internal_.JsonRpcProvider.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[removeAllListeners](akashaproject_ui_app_loader._internal_.BaseProvider.md#removealllisteners)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[removeListener](akashaproject_ui_app_loader._internal_.BaseProvider.md#removelistener)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[resetEventsBlock](akashaproject_ui_app_loader._internal_.BaseProvider.md#reseteventsblock)

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[resolveName](akashaproject_ui_app_loader._internal_.BaseProvider.md#resolvename)

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

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:41

___

### sendTransaction

▸ **sendTransaction**(`signedTransaction`): `Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `signedTransaction` | `string` \| `Promise`<`string`\> |

#### Returns

`Promise`<[`TransactionResponse`](../interfaces/akashaproject_ui_app_loader._internal_.TransactionResponse.md)\>

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[sendTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#sendtransaction)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[waitForTransaction](akashaproject_ui_app_loader._internal_.BaseProvider.md#waitfortransaction)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:100

___

### defaultUrl

▸ `Static` **defaultUrl**(): `string`

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/json-rpc-provider.d.ts:35

___

### getFormatter

▸ `Static` **getFormatter**(): [`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Returns

[`Formatter`](akashaproject_ui_app_loader._internal_.Formatter.md)

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getFormatter](akashaproject_ui_app_loader._internal_.BaseProvider.md#getformatter)

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

#### Inherited from

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[getNetwork](akashaproject_ui_app_loader._internal_.BaseProvider.md#getnetwork)

#### Defined in

sdk/node_modules/@ethersproject/providers/lib/base-provider.d.ts:86

___

### hexlifyTransaction

▸ `Static` **hexlifyTransaction**(`transaction`, `allowExtra?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `transaction` | [`TransactionRequest`](../modules/akashaproject_ui_app_loader._internal_.md#transactionrequest) |
| `allowExtra?` | `Object` |

#### Returns

`Object`

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

[BaseProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md).[isProvider](akashaproject_ui_app_loader._internal_.BaseProvider.md#isprovider)

#### Defined in

sdk/node_modules/@ethersproject/abstract-provider/lib/index.d.ts:152
