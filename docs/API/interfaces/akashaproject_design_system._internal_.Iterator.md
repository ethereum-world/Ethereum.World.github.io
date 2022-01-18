[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / Iterator

# Interface: Iterator<T, TReturn, TNext\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).Iterator

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `T` |
| `TReturn` | `any` |
| `TNext` | `undefined` |

## Hierarchy

- **`Iterator`**

  ↳ [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)

## Table of contents

### Methods

- [next](akashaproject_design_system._internal_.Iterator.md#next)
- [return](akashaproject_design_system._internal_.Iterator.md#return)
- [throw](akashaproject_design_system._internal_.Iterator.md#throw)

## Methods

### next

▸ **next**(...`args`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [] \| [`TNext`] |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:45

___

### return

▸ `Optional` **return**(`value?`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `value?` | `TReturn` |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:46

___

### throw

▸ `Optional` **throw**(`e?`): [`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `e?` | `any` |

#### Returns

[`IteratorResult`](../modules/akashaproject_design_system._internal_.md#iteratorresult)<`T`, `TReturn`\>

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:47
