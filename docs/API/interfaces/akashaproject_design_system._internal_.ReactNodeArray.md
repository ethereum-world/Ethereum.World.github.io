[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ReactNodeArray

# Interface: ReactNodeArray

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ReactNodeArray

## Hierarchy

- `Array`<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>

  ↳ **`ReactNodeArray`**

## Table of contents

### Properties

- [length](akashaproject_design_system._internal_.ReactNodeArray.md#length)

### Methods

- [[iterator]](akashaproject_design_system._internal_.ReactNodeArray.md#[iterator])
- [[unscopables]](akashaproject_design_system._internal_.ReactNodeArray.md#[unscopables])
- [at](akashaproject_design_system._internal_.ReactNodeArray.md#at)
- [concat](akashaproject_design_system._internal_.ReactNodeArray.md#concat)
- [copyWithin](akashaproject_design_system._internal_.ReactNodeArray.md#copywithin)
- [entries](akashaproject_design_system._internal_.ReactNodeArray.md#entries)
- [every](akashaproject_design_system._internal_.ReactNodeArray.md#every)
- [fill](akashaproject_design_system._internal_.ReactNodeArray.md#fill)
- [filter](akashaproject_design_system._internal_.ReactNodeArray.md#filter)
- [find](akashaproject_design_system._internal_.ReactNodeArray.md#find)
- [findIndex](akashaproject_design_system._internal_.ReactNodeArray.md#findindex)
- [flat](akashaproject_design_system._internal_.ReactNodeArray.md#flat)
- [flatMap](akashaproject_design_system._internal_.ReactNodeArray.md#flatmap)
- [forEach](akashaproject_design_system._internal_.ReactNodeArray.md#foreach)
- [includes](akashaproject_design_system._internal_.ReactNodeArray.md#includes)
- [indexOf](akashaproject_design_system._internal_.ReactNodeArray.md#indexof)
- [join](akashaproject_design_system._internal_.ReactNodeArray.md#join)
- [keys](akashaproject_design_system._internal_.ReactNodeArray.md#keys)
- [lastIndexOf](akashaproject_design_system._internal_.ReactNodeArray.md#lastindexof)
- [map](akashaproject_design_system._internal_.ReactNodeArray.md#map)
- [pop](akashaproject_design_system._internal_.ReactNodeArray.md#pop)
- [push](akashaproject_design_system._internal_.ReactNodeArray.md#push)
- [reduce](akashaproject_design_system._internal_.ReactNodeArray.md#reduce)
- [reduceRight](akashaproject_design_system._internal_.ReactNodeArray.md#reduceright)
- [reverse](akashaproject_design_system._internal_.ReactNodeArray.md#reverse)
- [shift](akashaproject_design_system._internal_.ReactNodeArray.md#shift)
- [slice](akashaproject_design_system._internal_.ReactNodeArray.md#slice)
- [some](akashaproject_design_system._internal_.ReactNodeArray.md#some)
- [sort](akashaproject_design_system._internal_.ReactNodeArray.md#sort)
- [splice](akashaproject_design_system._internal_.ReactNodeArray.md#splice)
- [toLocaleString](akashaproject_design_system._internal_.ReactNodeArray.md#tolocalestring)
- [toString](akashaproject_design_system._internal_.ReactNodeArray.md#tostring)
- [unshift](akashaproject_design_system._internal_.ReactNodeArray.md#unshift)
- [values](akashaproject_design_system._internal_.ReactNodeArray.md#values)

## Properties

### length

• **length**: `number`

Gets or sets the length of the array. This is a number one higher than the highest index in the array.

#### Inherited from

Array.length

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1224

## Methods

### [iterator]

▸ **[iterator]**(): [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>

Iterator

#### Returns

[`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>

#### Inherited from

Array.\_\_@iterator@33237

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:60

___

### [unscopables]

▸ **[unscopables]**(): `Object`

Returns an object whose properties have the value 'true'
when they will be absent when used in a 'with' statement.

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `copyWithin` | `boolean` |
| `entries` | `boolean` |
| `fill` | `boolean` |
| `find` | `boolean` |
| `findIndex` | `boolean` |
| `keys` | `boolean` |
| `values` | `boolean` |

#### Inherited from

Array.\_\_@unscopables@34691

#### Defined in

node_modules/typescript/lib/lib.es2015.symbol.wellknown.d.ts:99

___

### at

▸ **at**(`index`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Takes an integer value and returns the item at that index,
allowing for positive and negative integers.
Negative integers count back from the last item in the array.

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.at

#### Defined in

ui/design/node_modules/@types/node/globals.d.ts:86

___

### concat

▸ **concat**(...`items`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Combines two or more arrays.
This method returns a new array without modifying any existing arrays.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | [`ConcatArray`](akashaproject_design_system._internal_.ConcatArray.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>[] | Additional arrays and/or items to add to the end of the array. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

#### Inherited from

Array.concat

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1248

▸ **concat**(...`items`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Combines two or more arrays.
This method returns a new array without modifying any existing arrays.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | ([`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) \| [`ConcatArray`](akashaproject_design_system._internal_.ConcatArray.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>)[] | Additional arrays and/or items to add to the end of the array. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

#### Inherited from

Array.concat

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1254

___

### copyWithin

▸ **copyWithin**(`target`, `start`, `end?`): [`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

Returns the this object after copying a section of the array identified by start and end
to the same array starting at position target

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `number` | If target is negative, it is treated as length+target where length is the length of the array. |
| `start` | `number` | If start is negative, it is treated as length+start. If end is negative, it is treated as length+end. |
| `end?` | `number` | If not specified, length of the this object is used as its default value. |

#### Returns

[`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

#### Inherited from

Array.copyWithin

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:64

___

### entries

▸ **entries**(): [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`number`, [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)]\>

Returns an iterable of key, value pairs for every entry in the array

#### Returns

[`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`number`, [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)]\>

#### Inherited from

Array.entries

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:65

___

### every

▸ **every**<`S`\>(`predicate`, `thisArg?`): this is S[]

Determines whether all the members of an array satisfy the specified test.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => value is S | A function that accepts up to three arguments. The every method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value false, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

this is S[]

#### Inherited from

Array.every

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1331

▸ **every**(`predicate`, `thisArg?`): `boolean`

Determines whether all the members of an array satisfy the specified test.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `unknown` | A function that accepts up to three arguments. The every method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value false, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`boolean`

#### Inherited from

Array.every

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1340

___

### fill

▸ **fill**(`value`, `start?`, `end?`): [`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

Changes all array elements from `start` to `end` index to a static `value` and returns the modified array

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | value to fill array section with |
| `start?` | `number` | index to start filling the array at. If start is negative, it is treated as length+start where length is the length of the array. |
| `end?` | `number` | index to stop filling the array at. If end is negative, it is treated as length+end. |

#### Returns

[`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

#### Inherited from

Array.fill

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:53

___

### filter

▸ **filter**<`S`\>(`predicate`, `thisArg?`): `S`[]

Returns the elements of an array that meet the condition specified in a callback function.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => value is S | A function that accepts up to three arguments. The filter method calls the predicate function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`S`[]

#### Inherited from

Array.filter

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1367

▸ **filter**(`predicate`, `thisArg?`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Returns the elements of an array that meet the condition specified in a callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `unknown` | A function that accepts up to three arguments. The filter method calls the predicate function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

#### Inherited from

Array.filter

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1373

___

### find

▸ **find**<`S`\>(`predicate`, `thisArg?`): `S`

Returns the value of the first element in the array where predicate is true, and undefined
otherwise.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `obj`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => value is S | find calls predicate once for each element of the array, in ascending order, until it finds one where predicate returns true. If such an element is found, find immediately returns that element value. Otherwise, find returns undefined. |
| `thisArg?` | `any` | If provided, it will be used as the this value for each invocation of predicate. If it is not provided, undefined is used instead. |

#### Returns

`S`

#### Inherited from

Array.find

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:31

▸ **find**(`predicate`, `thisArg?`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Parameters

| Name | Type |
| :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `obj`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `unknown` |
| `thisArg?` | `any` |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.find

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:32

___

### findIndex

▸ **findIndex**(`predicate`, `thisArg?`): `number`

Returns the index of the first element in the array where predicate is true, and -1
otherwise.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `obj`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `unknown` | find calls predicate once for each element of the array, in ascending order, until it finds one where predicate returns true. If such an element is found, findIndex immediately returns that element index. Otherwise, findIndex returns -1. |
| `thisArg?` | `any` | If provided, it will be used as the this value for each invocation of predicate. If it is not provided, undefined is used instead. |

#### Returns

`number`

#### Inherited from

Array.findIndex

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:43

___

### flat

▸ **flat**<`A`, `D`\>(`depth?`): [`FlatArray`](../modules/akashaproject_design_system._internal_.md#flatarray)<`A`, `D`\>[]

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `A` | `A` |
| `D` | extends `number` = ``1`` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `depth?` | `D` | The maximum recursion depth |

#### Returns

[`FlatArray`](../modules/akashaproject_design_system._internal_.md#flatarray)<`A`, `D`\>[]

#### Inherited from

Array.flat

#### Defined in

node_modules/typescript/lib/lib.es2019.array.d.ts:81

___

### flatMap

▸ **flatMap**<`U`, `This`\>(`callback`, `thisArg?`): `U`[]

Calls a defined callback function on each element of an array. Then, flattens the result into
a new array.
This is identical to a map followed by flat with depth 1.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `U` | `U` |
| `This` | `undefined` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `U` \| readonly `U`[] | A function that accepts up to three arguments. The flatMap method calls the callback function one time for each element in the array. |
| `thisArg?` | `This` | An object to which the this keyword can refer in the callback function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`U`[]

#### Inherited from

Array.flatMap

#### Defined in

node_modules/typescript/lib/lib.es2019.array.d.ts:70

___

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

Performs the specified action for each element in an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `void` | A function that accepts up to three arguments. forEach calls the callbackfn function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`void`

#### Inherited from

Array.forEach

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1355

___

### includes

▸ **includes**(`searchElement`, `fromIndex?`): `boolean`

Determines whether an array includes a certain element, returning true or false as appropriate.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | The element to search for. |
| `fromIndex?` | `number` | The position in this array at which to begin searching for searchElement. |

#### Returns

`boolean`

#### Inherited from

Array.includes

#### Defined in

node_modules/typescript/lib/lib.es2016.array.include.d.ts:27

___

### indexOf

▸ **indexOf**(`searchElement`, `fromIndex?`): `number`

Returns the index of the first occurrence of a value in an array, or -1 if it is not present.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | The value to locate in the array. |
| `fromIndex?` | `number` | The array index at which to begin the search. If fromIndex is omitted, the search starts at index 0. |

#### Returns

`number`

#### Inherited from

Array.indexOf

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1316

___

### join

▸ **join**(`separator?`): `string`

Adds all the elements of an array into a string, separated by the specified separator string.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `separator?` | `string` | A string used to separate one element of the array from the next in the resulting string. If omitted, the array elements are separated with a comma. |

#### Returns

`string`

#### Inherited from

Array.join

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1259

___

### keys

▸ **keys**(): [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<`number`\>

Returns an iterable of keys in the array

#### Returns

[`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<`number`\>

#### Inherited from

Array.keys

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:70

___

### lastIndexOf

▸ **lastIndexOf**(`searchElement`, `fromIndex?`): `number`

Returns the index of the last occurrence of a specified value in an array, or -1 if it is not present.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | The value to locate in the array. |
| `fromIndex?` | `number` | The array index at which to begin searching backward. If fromIndex is omitted, the search starts at the last index in the array. |

#### Returns

`number`

#### Inherited from

Array.lastIndexOf

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1322

___

### map

▸ **map**<`U`\>(`callbackfn`, `thisArg?`): `U`[]

Calls a defined callback function on each element of an array, and returns an array that contains the results.

#### Type parameters

| Name |
| :------ |
| `U` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `U` | A function that accepts up to three arguments. The map method calls the callbackfn function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`U`[]

#### Inherited from

Array.map

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1361

___

### pop

▸ **pop**(): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Removes the last element from an array and returns it.
If the array is empty, undefined is returned and the array is not modified.

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.pop

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1237

___

### push

▸ **push**(...`items`): `number`

Appends new elements to the end of an array, and returns the new length of the array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[] | New elements to add to the array. |

#### Returns

`number`

#### Inherited from

Array.push

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1242

___

### reduce

▸ **reduce**(`callbackfn`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1379

▸ **reduce**(`callbackfn`, `initialValue`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`previousValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `initialValue` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1380

▸ **reduce**<`U`\>(`callbackfn`, `initialValue`): `U`

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Type parameters

| Name |
| :------ |
| `U` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `U`, `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `U` | A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array. |
| `initialValue` | `U` | If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value. |

#### Returns

`U`

#### Inherited from

Array.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1386

___

### reduceRight

▸ **reduceRight**(`callbackfn`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) | A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1392

▸ **reduceRight**(`callbackfn`, `initialValue`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`previousValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `initialValue` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1393

▸ **reduceRight**<`U`\>(`callbackfn`, `initialValue`): `U`

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Type parameters

| Name |
| :------ |
| `U` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `U`, `currentValue`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `currentIndex`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `U` | A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array. |
| `initialValue` | `U` | If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value. |

#### Returns

`U`

#### Inherited from

Array.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1399

___

### reverse

▸ **reverse**(): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Reverses the elements in an array in place.
This method mutates the array and returns a reference to the same array.

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

#### Inherited from

Array.reverse

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1264

___

### shift

▸ **shift**(): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Removes the first element from an array and returns it.
If the array is empty, undefined is returned and the array is not modified.

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

Array.shift

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1269

___

### slice

▸ **slice**(`start?`, `end?`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Returns a copy of a section of an array.
For both start and end, a negative index can be used to indicate an offset from the end of the array.
For example, -2 refers to the second to last element of the array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `start?` | `number` | The beginning index of the specified portion of the array. If start is undefined, then the slice begins at index 0. |
| `end?` | `number` | The end index of the specified portion of the array. This is exclusive of the element at the index 'end'. If end is undefined, then the slice extends to the end of the array. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

#### Inherited from

Array.slice

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1279

___

### some

▸ **some**(`predicate`, `thisArg?`): `boolean`

Determines whether the specified callback function returns true for any element of an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `index`: `number`, `array`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]) => `unknown` | A function that accepts up to three arguments. The some method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value true, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`boolean`

#### Inherited from

Array.some

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1349

___

### sort

▸ **sort**(`compareFn?`): [`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

Sorts an array in place.
This method mutates the array and returns a reference to the same array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `compareFn?` | (`a`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode), `b`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)) => `number` | Function used to determine the order of the elements. It is expected to return a negative value if first argument is less than second argument, zero if they're equal and a positive value otherwise. If omitted, the elements are sorted in ascending, ASCII character order. ```ts [11,2,22,1].sort((a, b) => a - b) ``` |

#### Returns

[`ReactNodeArray`](akashaproject_design_system._internal_.ReactNodeArray.md)

#### Inherited from

Array.sort

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1290

___

### splice

▸ **splice**(`start`, `deleteCount?`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Removes elements from an array and, if necessary, inserts new elements in their place, returning the deleted elements.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `start` | `number` | The zero-based location in the array from which to start removing elements. |
| `deleteCount?` | `number` | The number of elements to remove. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

An array containing the elements that were deleted.

#### Inherited from

Array.splice

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1297

▸ **splice**(`start`, `deleteCount`, ...`items`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

Removes elements from an array and, if necessary, inserts new elements in their place, returning the deleted elements.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `start` | `number` | The zero-based location in the array from which to start removing elements. |
| `deleteCount` | `number` | The number of elements to remove. |
| `...items` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[] | Elements to insert into the array in place of the deleted elements. |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[]

An array containing the elements that were deleted.

#### Inherited from

Array.splice

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1305

___

### toLocaleString

▸ **toLocaleString**(): `string`

Returns a string representation of an array. The elements are converted to string using their toLocaleString methods.

#### Returns

`string`

#### Inherited from

Array.toLocaleString

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1232

___

### toString

▸ **toString**(): `string`

Returns a string representation of an array.

#### Returns

`string`

#### Inherited from

Array.toString

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1228

___

### unshift

▸ **unshift**(...`items`): `number`

Inserts new elements at the start of an array, and returns the new length of the array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)[] | Elements to insert at the start of the array. |

#### Returns

`number`

#### Inherited from

Array.unshift

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1310

___

### values

▸ **values**(): [`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>

Returns an iterable of values in the array

#### Returns

[`IterableIterator`](akashaproject_design_system._internal_.IterableIterator.md)<[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)\>

#### Inherited from

Array.values

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:75
