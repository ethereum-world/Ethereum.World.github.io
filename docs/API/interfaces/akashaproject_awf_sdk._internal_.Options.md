[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / Options

# Interface: Options<KeyType, ValueType\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).Options

## Type parameters

| Name |
| :------ |
| `KeyType` |
| `ValueType` |

## Table of contents

### Properties

- [maxAge](akashaproject_awf_sdk._internal_.Options.md#maxage)
- [maxSize](akashaproject_awf_sdk._internal_.Options.md#maxsize)

### Methods

- [onEviction](akashaproject_awf_sdk._internal_.Options.md#oneviction)

## Properties

### maxAge

• `Optional` `Readonly` **maxAge**: `number`

The maximum number of milliseconds an item should remain in the cache.

**`default`** Infinity

By default, `maxAge` will be `Infinity`, which means that items will never expire.
Lazy expiration upon the next write or read call.

Individual expiration of an item can be specified by the `set(key, value, maxAge)` method.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:12

___

### maxSize

• `Readonly` **maxSize**: `number`

The maximum number of items before evicting the least recently used items.

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:17

## Methods

### onEviction

▸ `Optional` **onEviction**(`key`, `value`): `void`

Called right before an item is evicted from the cache.

Useful for side effects or for items like object URLs that need explicit cleanup (`revokeObjectURL`).

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `KeyType` |
| `value` | `ValueType` |

#### Returns

`void`

#### Defined in

sdk/node_modules/quick-lru/index.d.ts:24
