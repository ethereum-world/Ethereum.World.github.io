[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / TemplateStringsArray

# Interface: TemplateStringsArray

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).TemplateStringsArray

## Hierarchy

- `ReadonlyArray`<`string`\>

  ↳ **`TemplateStringsArray`**

## Table of contents

### Properties

- [length](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#length)
- [raw](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#raw)

### Methods

- [[iterator]](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#[iterator])
- [concat](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#concat)
- [entries](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#entries)
- [every](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#every)
- [filter](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#filter)
- [find](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#find)
- [findIndex](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#findindex)
- [flat](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#flat)
- [flatMap](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#flatmap)
- [forEach](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#foreach)
- [includes](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#includes)
- [indexOf](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#indexof)
- [join](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#join)
- [keys](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#keys)
- [lastIndexOf](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#lastindexof)
- [map](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#map)
- [reduce](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#reduce)
- [reduceRight](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#reduceright)
- [slice](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#slice)
- [some](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#some)
- [toLocaleString](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#tolocalestring)
- [toString](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#tostring)
- [values](akashaproject_ui_awf_typings._internal_.TemplateStringsArray.md#values)

## Properties

### length

• `Readonly` **length**: `number`

Gets the length of the array. This is a number one higher than the highest element defined in an array.

#### Inherited from

ReadonlyArray.length

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1090

___

### raw

• `Readonly` **raw**: readonly `string`[]

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:605

## Methods

### [iterator]

▸ **[iterator]**(): [`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`string`\>

Iterator of values in the array.

#### Returns

[`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`string`\>

#### Inherited from

ReadonlyArray.\_\_@iterator@338057

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:96

___

### concat

▸ **concat**(...`items`): `string`[]

Combines two or more arrays.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | [`ConcatArray`](akashaproject_ui_awf_typings._internal_.ConcatArray.md)<`string`\>[] | Additional items to add to the end of array1. |

#### Returns

`string`[]

#### Inherited from

ReadonlyArray.concat

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1103

▸ **concat**(...`items`): `string`[]

Combines two or more arrays.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...items` | (`string` \| [`ConcatArray`](akashaproject_ui_awf_typings._internal_.ConcatArray.md)<`string`\>)[] | Additional items to add to the end of array1. |

#### Returns

`string`[]

#### Inherited from

ReadonlyArray.concat

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1108

___

### entries

▸ **entries**(): [`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<[`number`, `string`]\>

Returns an iterable of key, value pairs for every entry in the array

#### Returns

[`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<[`number`, `string`]\>

#### Inherited from

ReadonlyArray.entries

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:101

___

### every

▸ **every**<`S`\>(`predicate`, `thisArg?`): this is readonly S[]

Determines whether all the members of an array satisfy the specified test.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends `string` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => value is S | A function that accepts up to three arguments. The every method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value false, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

this is readonly S[]

#### Inherited from

ReadonlyArray.every

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1140

▸ **every**(`predicate`, `thisArg?`): `boolean`

Determines whether all the members of an array satisfy the specified test.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => `unknown` | A function that accepts up to three arguments. The every method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value false, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`boolean`

#### Inherited from

ReadonlyArray.every

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1149

___

### filter

▸ **filter**<`S`\>(`predicate`, `thisArg?`): `S`[]

Returns the elements of an array that meet the condition specified in a callback function.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends `string` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => value is S | A function that accepts up to three arguments. The filter method calls the predicate function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`S`[]

#### Inherited from

ReadonlyArray.filter

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1176

▸ **filter**(`predicate`, `thisArg?`): `string`[]

Returns the elements of an array that meet the condition specified in a callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => `unknown` | A function that accepts up to three arguments. The filter method calls the predicate function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`string`[]

#### Inherited from

ReadonlyArray.filter

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1182

___

### find

▸ **find**<`S`\>(`predicate`, `thisArg?`): `S`

Returns the value of the first element in the array where predicate is true, and undefined
otherwise.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends `string` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `obj`: readonly `string`[]) => value is S | find calls predicate once for each element of the array, in ascending order, until it finds one where predicate returns true. If such an element is found, find immediately returns that element value. Otherwise, find returns undefined. |
| `thisArg?` | `any` | If provided, it will be used as the this value for each invocation of predicate. If it is not provided, undefined is used instead. |

#### Returns

`S`

#### Inherited from

ReadonlyArray.find

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:352

▸ **find**(`predicate`, `thisArg?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `obj`: readonly `string`[]) => `unknown` |
| `thisArg?` | `any` |

#### Returns

`string`

#### Inherited from

ReadonlyArray.find

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:353

___

### findIndex

▸ **findIndex**(`predicate`, `thisArg?`): `number`

Returns the index of the first element in the array where predicate is true, and -1
otherwise.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `obj`: readonly `string`[]) => `unknown` | find calls predicate once for each element of the array, in ascending order, until it finds one where predicate returns true. If such an element is found, findIndex immediately returns that element index. Otherwise, findIndex returns -1. |
| `thisArg?` | `any` | If provided, it will be used as the this value for each invocation of predicate. If it is not provided, undefined is used instead. |

#### Returns

`number`

#### Inherited from

ReadonlyArray.findIndex

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:364

___

### flat

▸ **flat**<`A`, `D`\>(`depth?`): [`FlatArray`](../modules/akashaproject_ui_awf_typings._internal_.md#flatarray)<`A`, `D`\>[]

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

[`FlatArray`](../modules/akashaproject_ui_awf_typings._internal_.md#flatarray)<`A`, `D`\>[]

#### Inherited from

ReadonlyArray.flat

#### Defined in

node_modules/typescript/lib/lib.es2019.array.d.ts:52

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
| `callback` | (`value`: `string`, `index`: `number`, `array`: `string`[]) => `U` \| readonly `U`[] | A function that accepts up to three arguments. The flatMap method calls the callback function one time for each element in the array. |
| `thisArg?` | `This` | An object to which the this keyword can refer in the callback function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`U`[]

#### Inherited from

ReadonlyArray.flatMap

#### Defined in

node_modules/typescript/lib/lib.es2019.array.d.ts:40

___

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

Performs the specified action for each element in an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => `void` | A function that accepts up to three arguments. forEach calls the callbackfn function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`void`

#### Inherited from

ReadonlyArray.forEach

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1164

___

### includes

▸ **includes**(`searchElement`, `fromIndex?`): `boolean`

Determines whether an array includes a certain element, returning true or false as appropriate.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | `string` | The element to search for. |
| `fromIndex?` | `number` | The position in this array at which to begin searching for searchElement. |

#### Returns

`boolean`

#### Inherited from

ReadonlyArray.includes

#### Defined in

node_modules/typescript/lib/lib.es2016.array.include.d.ts:36

___

### indexOf

▸ **indexOf**(`searchElement`, `fromIndex?`): `number`

Returns the index of the first occurrence of a value in an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | `string` | The value to locate in the array. |
| `fromIndex?` | `number` | The array index at which to begin the search. If fromIndex is omitted, the search starts at index 0. |

#### Returns

`number`

#### Inherited from

ReadonlyArray.indexOf

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1125

___

### join

▸ **join**(`separator?`): `string`

Adds all the elements of an array separated by the specified separator string.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `separator?` | `string` | A string used to separate one element of an array from the next in the resulting String. If omitted, the array elements are separated with a comma. |

#### Returns

`string`

#### Inherited from

ReadonlyArray.join

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1113

___

### keys

▸ **keys**(): [`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`number`\>

Returns an iterable of keys in the array

#### Returns

[`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`number`\>

#### Inherited from

ReadonlyArray.keys

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:106

___

### lastIndexOf

▸ **lastIndexOf**(`searchElement`, `fromIndex?`): `number`

Returns the index of the last occurrence of a specified value in an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchElement` | `string` | The value to locate in the array. |
| `fromIndex?` | `number` | The array index at which to begin the search. If fromIndex is omitted, the search starts at the last index in the array. |

#### Returns

`number`

#### Inherited from

ReadonlyArray.lastIndexOf

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1131

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
| `callbackfn` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => `U` | A function that accepts up to three arguments. The map method calls the callbackfn function one time for each element in the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`U`[]

#### Inherited from

ReadonlyArray.map

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1170

___

### reduce

▸ **reduce**(`callbackfn`): `string`

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `string`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `string` | A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array. |

#### Returns

`string`

#### Inherited from

ReadonlyArray.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1188

▸ **reduce**(`callbackfn`, `initialValue`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`previousValue`: `string`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `string` |
| `initialValue` | `string` |

#### Returns

`string`

#### Inherited from

ReadonlyArray.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1189

▸ **reduce**<`U`\>(`callbackfn`, `initialValue`): `U`

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Type parameters

| Name |
| :------ |
| `U` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `U`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `U` | A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array. |
| `initialValue` | `U` | If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value. |

#### Returns

`U`

#### Inherited from

ReadonlyArray.reduce

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1195

___

### reduceRight

▸ **reduceRight**(`callbackfn`): `string`

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `string`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `string` | A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array. |

#### Returns

`string`

#### Inherited from

ReadonlyArray.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1201

▸ **reduceRight**(`callbackfn`, `initialValue`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`previousValue`: `string`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `string` |
| `initialValue` | `string` |

#### Returns

`string`

#### Inherited from

ReadonlyArray.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1202

▸ **reduceRight**<`U`\>(`callbackfn`, `initialValue`): `U`

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

#### Type parameters

| Name |
| :------ |
| `U` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callbackfn` | (`previousValue`: `U`, `currentValue`: `string`, `currentIndex`: `number`, `array`: readonly `string`[]) => `U` | A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array. |
| `initialValue` | `U` | If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value. |

#### Returns

`U`

#### Inherited from

ReadonlyArray.reduceRight

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1208

___

### slice

▸ **slice**(`start?`, `end?`): `string`[]

Returns a section of an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `start?` | `number` | The beginning of the specified portion of the array. |
| `end?` | `number` | The end of the specified portion of the array. This is exclusive of the element at the index 'end'. |

#### Returns

`string`[]

#### Inherited from

ReadonlyArray.slice

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1119

___

### some

▸ **some**(`predicate`, `thisArg?`): `boolean`

Determines whether the specified callback function returns true for any element of an array.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`value`: `string`, `index`: `number`, `array`: readonly `string`[]) => `unknown` | A function that accepts up to three arguments. The some method calls the predicate function for each element in the array until the predicate returns a value which is coercible to the Boolean value true, or until the end of the array. |
| `thisArg?` | `any` | An object to which the this keyword can refer in the predicate function. If thisArg is omitted, undefined is used as the this value. |

#### Returns

`boolean`

#### Inherited from

ReadonlyArray.some

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1158

___

### toLocaleString

▸ **toLocaleString**(): `string`

Returns a string representation of an array. The elements are converted to string using their toLocaleString methods.

#### Returns

`string`

#### Inherited from

ReadonlyArray.toLocaleString

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1098

___

### toString

▸ **toString**(): `string`

Returns a string representation of an array.

#### Returns

`string`

#### Inherited from

ReadonlyArray.toString

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1094

___

### values

▸ **values**(): [`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`string`\>

Returns an iterable of values in the array

#### Returns

[`IterableIterator`](akashaproject_ui_awf_typings._internal_.IterableIterator.md)<`string`\>

#### Inherited from

ReadonlyArray.values

#### Defined in

node_modules/typescript/lib/lib.es2015.iterable.d.ts:111
