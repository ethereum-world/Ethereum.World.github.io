[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / default

# Class: default<KeyType, ValueType\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).default

## Type parameters

| Name |
| :------ |
| `KeyType` |
| `ValueType` |

## Implements

- [`Iterable`](../interfaces/akashaproject_awf_sdk._internal_.Iterable.md)<[`KeyType`, `ValueType`]\>

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.default.md#constructor)

### Properties

- [size](akashaproject_awf_sdk._internal_.default.md#size)

### Methods

- [[iterator]](akashaproject_awf_sdk._internal_.default.md#[iterator])
- [clear](akashaproject_awf_sdk._internal_.default.md#clear)
- [delete](akashaproject_awf_sdk._internal_.default.md#delete)
- [entriesAscending](akashaproject_awf_sdk._internal_.default.md#entriesascending)
- [entriesDescending](akashaproject_awf_sdk._internal_.default.md#entriesdescending)
- [get](akashaproject_awf_sdk._internal_.default.md#get)
- [has](akashaproject_awf_sdk._internal_.default.md#has)
- [keys](akashaproject_awf_sdk._internal_.default.md#keys)
- [peek](akashaproject_awf_sdk._internal_.default.md#peek)
- [resize](akashaproject_awf_sdk._internal_.default.md#resize)
- [set](akashaproject_awf_sdk._internal_.default.md#set)
- [values](akashaproject_awf_sdk._internal_.default.md#values)

## Constructors

### constructor

• **new default**<`KeyType`, `ValueType`\>(`options`)

Simple ["Least Recently Used" (LRU) cache](https://en.m.wikipedia.org/wiki/Cache_replacement_policies#Least_Recently_Used_.28LRU.29).

The instance is an [`Iterable`](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Iteration_protocols) of `[key, value]` pairs so you can use it directly in a [`for…of`](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/for...of) loop.

**`example`**
```
import QuickLRU from 'quick-lru';

const lru = new QuickLRU({maxSize: 1000});

lru.set('🦄', '🌈');

lru.has('🦄');
//=> true

lru.get('🦄');
//=> '🌈'
```

#### Type parameters

| Name |
| :------ |
| `KeyType` |
| `ValueType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`Options`](../interfaces/akashaproject_awf_sdk._internal_.Options.md)<`KeyType`, `ValueType`\> |

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:53

## Properties

### size

• `Readonly` **size**: `number`

The stored item count.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:31

## Methods

### [iterator]

▸ **[iterator]**(): [`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

#### Returns

[`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

#### Implementation of

[Iterable](../interfaces/akashaproject_awf_sdk._internal_.Iterable.md).[[iterator]](../interfaces/akashaproject_awf_sdk._internal_.Iterable.md#[iterator])

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:55

___

### clear

▸ **clear**(): `void`

Delete all items.

#### Returns

`void`

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:95

___

### delete

▸ **delete**(`key`): `boolean`

Delete an item.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |

#### Returns

`boolean`

`true` if the item is removed or `false` if the item doesn't exist.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:90

___

### entriesAscending

▸ **entriesAscending**(): [`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

Iterable for all entries, starting with the oldest (ascending in recency).

#### Returns

[`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:117

___

### entriesDescending

▸ **entriesDescending**(): [`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

Iterable for all entries, starting with the newest (descending in recency).

#### Returns

[`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<[`KeyType`, `ValueType`]\>

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:122

___

### get

▸ **get**(`key`): `ValueType`

Get an item.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |

#### Returns

`ValueType`

The stored item or `undefined`.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:71

___

### has

▸ **has**(`key`): `boolean`

Check if an item exists.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:76

___

### keys

▸ **keys**(): [`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<`KeyType`\>

Iterable for all the keys.

#### Returns

[`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<`KeyType`\>

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:107

___

### peek

▸ **peek**(`key`): `ValueType`

Get an item without marking it as recently used.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |

#### Returns

`ValueType`

The stored item or `undefined`.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:83

___

### resize

▸ **resize**(`maxSize`): `void`

Update the `maxSize` in-place, discarding items as necessary. Insertion order is mostly preserved, though this is not a strong guarantee.

Useful for on-the-fly tuning of cache sizes in live systems.

#### Parameters

| Name | Type |
| :------ | :------ |
| `maxSize` | `number` |

#### Returns

`void`

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:102

___

### set

▸ **set**(`key`, `value`, `options?`): [`default`](akashaproject_awf_sdk._internal_.default.md)<`KeyType`, `ValueType`\>

Set an item. Returns the instance.

Individual expiration of an item can be specified with the `maxAge` option. If not specified, the global `maxAge` value will be used in case it is specified in the constructor, otherwise the item will never expire.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |
| `value` | `ValueType` |
| `options?` | `Object` |
| `options.maxAge?` | `number` |

#### Returns

[`default`](akashaproject_awf_sdk._internal_.default.md)<`KeyType`, `ValueType`\>

The list instance.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:64

___

### values

▸ **values**(): [`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<`ValueType`\>

Iterable for all the values.

#### Returns

[`IterableIterator`](../interfaces/akashaproject_awf_sdk._internal_.IterableIterator.md)<`ValueType`\>

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:112
