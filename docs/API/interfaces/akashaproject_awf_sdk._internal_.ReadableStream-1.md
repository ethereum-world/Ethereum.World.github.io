[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / ReadableStream

# Interface: ReadableStream

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).ReadableStream

## Hierarchy

- [`EventEmitter`](akashaproject_awf_sdk._internal_.EventEmitter.md)

  ↳ **`ReadableStream`**

## Table of contents

### Properties

- [readable](akashaproject_awf_sdk._internal_.ReadableStream-1.md#readable)

### Methods

- [[asyncIterator]](akashaproject_awf_sdk._internal_.ReadableStream-1.md#[asynciterator])
- [addListener](akashaproject_awf_sdk._internal_.ReadableStream-1.md#addlistener)
- [emit](akashaproject_awf_sdk._internal_.ReadableStream-1.md#emit)
- [eventNames](akashaproject_awf_sdk._internal_.ReadableStream-1.md#eventnames)
- [getMaxListeners](akashaproject_awf_sdk._internal_.ReadableStream-1.md#getmaxlisteners)
- [isPaused](akashaproject_awf_sdk._internal_.ReadableStream-1.md#ispaused)
- [listenerCount](akashaproject_awf_sdk._internal_.ReadableStream-1.md#listenercount)
- [listeners](akashaproject_awf_sdk._internal_.ReadableStream-1.md#listeners)
- [off](akashaproject_awf_sdk._internal_.ReadableStream-1.md#off)
- [on](akashaproject_awf_sdk._internal_.ReadableStream-1.md#on)
- [once](akashaproject_awf_sdk._internal_.ReadableStream-1.md#once)
- [pause](akashaproject_awf_sdk._internal_.ReadableStream-1.md#pause)
- [pipe](akashaproject_awf_sdk._internal_.ReadableStream-1.md#pipe)
- [prependListener](akashaproject_awf_sdk._internal_.ReadableStream-1.md#prependlistener)
- [prependOnceListener](akashaproject_awf_sdk._internal_.ReadableStream-1.md#prependoncelistener)
- [rawListeners](akashaproject_awf_sdk._internal_.ReadableStream-1.md#rawlisteners)
- [read](akashaproject_awf_sdk._internal_.ReadableStream-1.md#read)
- [removeAllListeners](akashaproject_awf_sdk._internal_.ReadableStream-1.md#removealllisteners)
- [removeListener](akashaproject_awf_sdk._internal_.ReadableStream-1.md#removelistener)
- [resume](akashaproject_awf_sdk._internal_.ReadableStream-1.md#resume)
- [setEncoding](akashaproject_awf_sdk._internal_.ReadableStream-1.md#setencoding)
- [setMaxListeners](akashaproject_awf_sdk._internal_.ReadableStream-1.md#setmaxlisteners)
- [unpipe](akashaproject_awf_sdk._internal_.ReadableStream-1.md#unpipe)
- [unshift](akashaproject_awf_sdk._internal_.ReadableStream-1.md#unshift)
- [wrap](akashaproject_awf_sdk._internal_.ReadableStream-1.md#wrap)

## Properties

### readable

• **readable**: `boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:191

## Methods

### [asyncIterator]

▸ **[asyncIterator]**(): [`AsyncIterableIterator`](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md)<`string` \| [`Buffer`](../modules/akashaproject_awf_sdk._internal_.md#buffer)\>

#### Returns

[`AsyncIterableIterator`](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md)<`string` \| [`Buffer`](../modules/akashaproject_awf_sdk._internal_.md#buffer)\>

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:201

___

### addListener

▸ **addListener**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Alias for `emitter.on(eventName, listener)`.

**`since`** v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[addListener](akashaproject_awf_sdk._internal_.EventEmitter.md#addlistener)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:299

___

### emit

▸ **emit**(`eventName`, ...`args`): `boolean`

Synchronously calls each of the listeners registered for the event named`eventName`, in the order they were registered, passing the supplied arguments
to each.

Returns `true` if the event had listeners, `false` otherwise.

```js
const EventEmitter = require('events');
const myEmitter = new EventEmitter();

// First listener
myEmitter.on('event', function firstListener() {
  console.log('Helloooo! first listener');
});
// Second listener
myEmitter.on('event', function secondListener(arg1, arg2) {
  console.log(`event with parameters ${arg1}, ${arg2} in second listener`);
});
// Third listener
myEmitter.on('event', function thirdListener(...args) {
  const parameters = args.join(', ');
  console.log(`event with parameters ${parameters} in third listener`);
});

console.log(myEmitter.listeners('event'));

myEmitter.emit('event', 1, 2, 3, 4, 5);

// Prints:
// [
//   [Function: firstListener],
//   [Function: secondListener],
//   [Function: thirdListener]
// ]
// Helloooo! first listener
// event with parameters 1, 2 in second listener
// event with parameters 1, 2, 3, 4, 5 in third listener
```

**`since`** v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `...args` | `any`[] |

#### Returns

`boolean`

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[emit](akashaproject_awf_sdk._internal_.EventEmitter.md#emit)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:555

___

### eventNames

▸ **eventNames**(): (`string` \| `symbol`)[]

Returns an array listing the events for which the emitter has registered
listeners. The values in the array are strings or `Symbol`s.

```js
const EventEmitter = require('events');
const myEE = new EventEmitter();
myEE.on('foo', () => {});
myEE.on('bar', () => {});

const sym = Symbol('symbol');
myEE.on(sym, () => {});

console.log(myEE.eventNames());
// Prints: [ 'foo', 'bar', Symbol(symbol) ]
```

**`since`** v6.0.0

#### Returns

(`string` \| `symbol`)[]

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[eventNames](akashaproject_awf_sdk._internal_.EventEmitter.md#eventnames)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:614

___

### getMaxListeners

▸ **getMaxListeners**(): `number`

Returns the current max listener value for the `EventEmitter` which is either
set by `emitter.setMaxListeners(n)` or defaults to {@link defaultMaxListeners}.

**`since`** v1.0.0

#### Returns

`number`

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[getMaxListeners](akashaproject_awf_sdk._internal_.EventEmitter.md#getmaxlisteners)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:471

___

### isPaused

▸ **isPaused**(): `boolean`

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:196

___

### listenerCount

▸ **listenerCount**(`eventName`): `number`

Returns the number of listeners listening to the event named `eventName`.

**`since`** v3.2.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event being listened for |

#### Returns

`number`

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[listenerCount](akashaproject_awf_sdk._internal_.EventEmitter.md#listenercount)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:561

___

### listeners

▸ **listeners**(`eventName`): `Function`[]

Returns a copy of the array of listeners for the event named `eventName`.

```js
server.on('connection', (stream) => {
  console.log('someone connected!');
});
console.log(util.inspect(server.listeners('connection')));
// Prints: [ [Function] ]
```

**`since`** v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |

#### Returns

`Function`[]

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[listeners](akashaproject_awf_sdk._internal_.EventEmitter.md#listeners)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:484

___

### off

▸ **off**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Alias for `emitter.removeListener()`.

**`since`** v10.0.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[off](akashaproject_awf_sdk._internal_.EventEmitter.md#off)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:444

___

### on

▸ **on**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Adds the `listener` function to the end of the listeners array for the
event named `eventName`. No checks are made to see if the `listener` has
already been added. Multiple calls passing the same combination of `eventName`and `listener` will result in the `listener` being added, and called, multiple
times.

```js
server.on('connection', (stream) => {
  console.log('someone connected!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

By default, event listeners are invoked in the order they are added. The`emitter.prependListener()` method can be used as an alternative to add the
event listener to the beginning of the listeners array.

```js
const myEE = new EventEmitter();
myEE.on('foo', () => console.log('a'));
myEE.prependListener('foo', () => console.log('b'));
myEE.emit('foo');
// Prints:
//   b
//   a
```

**`since`** v0.1.101

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[on](akashaproject_awf_sdk._internal_.EventEmitter.md#on)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:330

___

### once

▸ **once**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Adds a **one-time**`listener` function for the event named `eventName`. The
next time `eventName` is triggered, this listener is removed and then invoked.

```js
server.once('connection', (stream) => {
  console.log('Ah, we have our first user!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

By default, event listeners are invoked in the order they are added. The`emitter.prependOnceListener()` method can be used as an alternative to add the
event listener to the beginning of the listeners array.

```js
const myEE = new EventEmitter();
myEE.once('foo', () => console.log('a'));
myEE.prependOnceListener('foo', () => console.log('b'));
myEE.emit('foo');
// Prints:
//   b
//   a
```

**`since`** v0.3.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[once](akashaproject_awf_sdk._internal_.EventEmitter.md#once)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:359

___

### pause

▸ **pause**(): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:194

___

### pipe

▸ **pipe**<`T`\>(`destination`, `options?`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`WritableStream`](akashaproject_awf_sdk._internal_.WritableStream-1.md)<`T`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `destination` | `T` |
| `options?` | `Object` |
| `options.end?` | `boolean` |

#### Returns

`T`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:197

___

### prependListener

▸ **prependListener**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Adds the `listener` function to the _beginning_ of the listeners array for the
event named `eventName`. No checks are made to see if the `listener` has
already been added. Multiple calls passing the same combination of `eventName`and `listener` will result in the `listener` being added, and called, multiple
times.

```js
server.prependListener('connection', (stream) => {
  console.log('someone connected!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`since`** v6.0.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[prependListener](akashaproject_awf_sdk._internal_.EventEmitter.md#prependlistener)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:579

___

### prependOnceListener

▸ **prependOnceListener**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Adds a **one-time**`listener` function for the event named `eventName` to the_beginning_ of the listeners array. The next time `eventName` is triggered, this
listener is removed, and then invoked.

```js
server.prependOnceListener('connection', (stream) => {
  console.log('Ah, we have our first user!');
});
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`since`** v6.0.0

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `string` \| `symbol` | The name of the event. |
| `listener` | (...`args`: `any`[]) => `void` | The callback function |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[prependOnceListener](akashaproject_awf_sdk._internal_.EventEmitter.md#prependoncelistener)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:595

___

### rawListeners

▸ **rawListeners**(`eventName`): `Function`[]

Returns a copy of the array of listeners for the event named `eventName`,
including any wrappers (such as those created by `.once()`).

```js
const emitter = new EventEmitter();
emitter.once('log', () => console.log('log once'));

// Returns a new Array with a function `onceWrapper` which has a property
// `listener` which contains the original listener bound above
const listeners = emitter.rawListeners('log');
const logFnWrapper = listeners[0];

// Logs "log once" to the console and does not unbind the `once` event
logFnWrapper.listener();

// Logs "log once" to the console and removes the listener
logFnWrapper();

emitter.on('log', () => console.log('log persistently'));
// Will return a new Array with a single function bound by `.on()` above
const newListeners = emitter.rawListeners('log');

// Logs "log persistently" twice
newListeners[0]();
emitter.emit('log');
```

**`since`** v9.4.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |

#### Returns

`Function`[]

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[rawListeners](akashaproject_awf_sdk._internal_.EventEmitter.md#rawlisteners)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:514

___

### read

▸ **read**(`size?`): `string` \| [`Buffer`](../modules/akashaproject_awf_sdk._internal_.md#buffer)

#### Parameters

| Name | Type |
| :------ | :------ |
| `size?` | `number` |

#### Returns

`string` \| [`Buffer`](../modules/akashaproject_awf_sdk._internal_.md#buffer)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:192

___

### removeAllListeners

▸ **removeAllListeners**(`event?`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Removes all listeners, or those of the specified `eventName`.

It is bad practice to remove listeners added elsewhere in the code,
particularly when the `EventEmitter` instance was created by some other
component or module (e.g. sockets or file streams).

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`since`** v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `event?` | `string` \| `symbol` |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[removeAllListeners](akashaproject_awf_sdk._internal_.EventEmitter.md#removealllisteners)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:455

___

### removeListener

▸ **removeListener**(`eventName`, `listener`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

Removes the specified `listener` from the listener array for the event named`eventName`.

```js
const callback = (stream) => {
  console.log('someone connected!');
};
server.on('connection', callback);
// ...
server.removeListener('connection', callback);
```

`removeListener()` will remove, at most, one instance of a listener from the
listener array. If any single listener has been added multiple times to the
listener array for the specified `eventName`, then `removeListener()` must be
called multiple times to remove each instance.

Once an event is emitted, all listeners attached to it at the
time of emitting are called in order. This implies that any`removeListener()` or `removeAllListeners()` calls _after_ emitting and_before_ the last listener finishes execution will
not remove them from`emit()` in progress. Subsequent events behave as expected.

```js
const myEmitter = new MyEmitter();

const callbackA = () => {
  console.log('A');
  myEmitter.removeListener('event', callbackB);
};

const callbackB = () => {
  console.log('B');
};

myEmitter.on('event', callbackA);

myEmitter.on('event', callbackB);

// callbackA removes listener callbackB but it will still be called.
// Internal listener array at time of emit [callbackA, callbackB]
myEmitter.emit('event');
// Prints:
//   A
//   B

// callbackB is now removed.
// Internal listener array [callbackA]
myEmitter.emit('event');
// Prints:
//   A
```

Because listeners are managed using an internal array, calling this will
change the position indices of any listener registered _after_ the listener
being removed. This will not impact the order in which listeners are called,
but it means that any copies of the listener array as returned by
the `emitter.listeners()` method will need to be recreated.

When a single function has been added as a handler multiple times for a single
event (as in the example below), `removeListener()` will remove the most
recently added instance. In the example the `once('ping')`listener is removed:

```js
const ee = new EventEmitter();

function pong() {
  console.log('pong');
}

ee.on('ping', pong);
ee.once('ping', pong);
ee.removeListener('ping', pong);

ee.emit('ping');
ee.emit('ping');
```

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`since`** v0.1.26

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` \| `symbol` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[removeListener](akashaproject_awf_sdk._internal_.EventEmitter.md#removelistener)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:439

___

### resume

▸ **resume**(): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:195

___

### setEncoding

▸ **setEncoding**(`encoding`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `encoding` | [`BufferEncoding`](../modules/akashaproject_awf_sdk._internal_.md#bufferencoding) |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:193

___

### setMaxListeners

▸ **setMaxListeners**(`n`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

By default `EventEmitter`s will print a warning if more than `10` listeners are
added for a particular event. This is a useful default that helps finding
memory leaks. The `emitter.setMaxListeners()` method allows the limit to be
modified for this specific `EventEmitter` instance. The value can be set to`Infinity` (or `0`) to indicate an unlimited number of listeners.

Returns a reference to the `EventEmitter`, so that calls can be chained.

**`since`** v0.3.5

#### Parameters

| Name | Type |
| :------ | :------ |
| `n` | `number` |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Inherited from

[EventEmitter](akashaproject_awf_sdk._internal_.EventEmitter.md).[setMaxListeners](akashaproject_awf_sdk._internal_.EventEmitter.md#setmaxlisteners)

#### Defined in

sdk/node_modules/@types/node/events.d.ts:465

___

### unpipe

▸ **unpipe**(`destination?`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `destination?` | [`WritableStream`](akashaproject_awf_sdk._internal_.WritableStream-1.md) |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:198

___

### unshift

▸ **unshift**(`chunk`, `encoding?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `chunk` | `string` \| `Uint8Array` |
| `encoding?` | [`BufferEncoding`](../modules/akashaproject_awf_sdk._internal_.md#bufferencoding) |

#### Returns

`void`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:199

___

### wrap

▸ **wrap**(`oldStream`): [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `oldStream` | [`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md) |

#### Returns

[`ReadableStream`](akashaproject_awf_sdk._internal_.ReadableStream-1.md)

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:200
