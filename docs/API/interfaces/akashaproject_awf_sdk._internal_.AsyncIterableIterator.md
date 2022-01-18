[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / AsyncIterableIterator

# Interface: AsyncIterableIterator<T\>

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).AsyncIterableIterator

## Type parameters

| Name |
| :------ |
| `T` |

## Hierarchy

- [`AsyncIterator`](akashaproject_awf_sdk._internal_.AsyncIterator.md)<`T`\>

  ↳ **`AsyncIterableIterator`**

## Table of contents

### Methods

- [[asyncIterator]](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md#[asynciterator])
- [next](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md#next)
- [return](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md#return)
- [throw](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md#throw)

## Methods

### [asyncIterator]

▸ **[asyncIterator]**(): [`AsyncIterableIterator`](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md)<`T`\>

#### Returns

[`AsyncIterableIterator`](akashaproject_awf_sdk._internal_.AsyncIterableIterator.md)<`T`\>

#### Defined in

node_modules/typescript/lib/lib.es2018.asynciterable.d.ts:44

___

### next

▸ **next**(...`args`): `Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [] \| [`undefined`] |

#### Returns

`Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Inherited from

[AsyncIterator](akashaproject_awf_sdk._internal_.AsyncIterator.md).[next](akashaproject_awf_sdk._internal_.AsyncIterator.md#next)

#### Defined in

node_modules/typescript/lib/lib.es2018.asynciterable.d.ts:34

___

### return

▸ `Optional` **return**(`value?`): `Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `value?` | `any` |

#### Returns

`Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Inherited from

[AsyncIterator](akashaproject_awf_sdk._internal_.AsyncIterator.md).[return](akashaproject_awf_sdk._internal_.AsyncIterator.md#return)

#### Defined in

node_modules/typescript/lib/lib.es2018.asynciterable.d.ts:35

___

### throw

▸ `Optional` **throw**(`e?`): `Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `e?` | `any` |

#### Returns

`Promise`<[`IteratorResult`](../modules/akashaproject_awf_sdk._internal_.md#iteratorresult)<`T`, `any`\>\>

#### Inherited from

[AsyncIterator](akashaproject_awf_sdk._internal_.AsyncIterator.md).[throw](akashaproject_awf_sdk._internal_.AsyncIterator.md#throw)

#### Defined in

node_modules/typescript/lib/lib.es2018.asynciterable.d.ts:36
