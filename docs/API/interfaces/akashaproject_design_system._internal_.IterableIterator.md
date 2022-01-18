[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IterableIterator

# Interface: IterableIterator<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IterableIterator

## Type parameters

| Name |
| :------ |
| `T` |

## Hierarchy

- [`Iterator`](akashaproject_design_system._internal_.Iterator.md)<`T`\>

  ↳ **`IterableIterator`**

## Table of contents

### Methods

- [[iterator]](akashaproject_design_system._internal_.IterableIterator.md#[iterator])
- [next](akashaproject_design_system._internal_.IterableIterator.md#next)
- [return](akashaproject_design_system._internal_.IterableIterator.md#return)
- [throw](akashaproject_design_system._internal_.IterableIterator.md#throw)

## Methods

### [iterator]

▸ **[iterator]**(): [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<`T`\>

#### Returns

[`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<`T`\>

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:55

___

### next

▸ **next**(...`args`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [] \| [`undefined`] |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Inherited from

[Iterator](akashaproject_design_system._internal_.Iterator.md).[next](akashaproject_design_system._internal_.Iterator.md#next)

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:45

___

### return

▸ `Optional` **return**(`value?`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `value?` | `any` |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Inherited from

[Iterator](akashaproject_design_system._internal_.Iterator.md).[return](akashaproject_design_system._internal_.Iterator.md#return)

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:46

___

### throw

▸ `Optional` **throw**(`e?`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `e?` | `any` |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `any`\>

#### Inherited from

[Iterator](akashaproject_design_system._internal_.Iterator.md).[throw](akashaproject_design_system._internal_.Iterator.md#throw)

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:47
