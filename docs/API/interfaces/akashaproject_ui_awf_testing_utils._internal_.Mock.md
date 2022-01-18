[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Mock

# Interface: Mock<T, Y\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Mock

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `any` |
| `Y` | extends `any`[] = `any` |

## Hierarchy

- `Function`

- [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

  ↳ **`Mock`**

## Callable

### Mock

▸ **Mock**(...`args`): `T`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Y` |

#### Returns

`T`

#### Defined in

node_modules/@types/jest/index.d.ts:1078

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_testing_utils._internal_.Mock.md#constructor)

### Properties

- [arguments](akashaproject_ui_awf_testing_utils._internal_.Mock.md#arguments)
- [caller](akashaproject_ui_awf_testing_utils._internal_.Mock.md#caller)
- [length](akashaproject_ui_awf_testing_utils._internal_.Mock.md#length)
- [mock](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mock)
- [name](akashaproject_ui_awf_testing_utils._internal_.Mock.md#name)
- [prototype](akashaproject_ui_awf_testing_utils._internal_.Mock.md#prototype)

### Methods

- [[hasInstance]](akashaproject_ui_awf_testing_utils._internal_.Mock.md#[hasinstance])
- [apply](akashaproject_ui_awf_testing_utils._internal_.Mock.md#apply)
- [bind](akashaproject_ui_awf_testing_utils._internal_.Mock.md#bind)
- [call](akashaproject_ui_awf_testing_utils._internal_.Mock.md#call)
- [getMockImplementation](akashaproject_ui_awf_testing_utils._internal_.Mock.md#getmockimplementation)
- [getMockName](akashaproject_ui_awf_testing_utils._internal_.Mock.md#getmockname)
- [mockClear](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockclear)
- [mockImplementation](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockimplementation)
- [mockImplementationOnce](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockimplementationonce)
- [mockName](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockname)
- [mockRejectedValue](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockrejectedvalue)
- [mockRejectedValueOnce](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockrejectedvalueonce)
- [mockReset](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockreset)
- [mockResolvedValue](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockresolvedvalue)
- [mockResolvedValueOnce](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockresolvedvalueonce)
- [mockRestore](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockrestore)
- [mockReturnThis](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockreturnthis)
- [mockReturnValue](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockreturnvalue)
- [mockReturnValueOnce](akashaproject_ui_awf_testing_utils._internal_.Mock.md#mockreturnvalueonce)
- [toString](akashaproject_ui_awf_testing_utils._internal_.Mock.md#tostring)

## Constructors

### constructor

• **new Mock**(...`args`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Y` |

#### Inherited from

Function.constructor

#### Defined in

node_modules/@types/jest/index.d.ts:1077

## Properties

### arguments

• **arguments**: `any`

#### Inherited from

Function.arguments

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:302

___

### caller

• **caller**: `Function`

#### Inherited from

Function.caller

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:303

___

### length

• `Readonly` **length**: `number`

#### Inherited from

Function.length

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:299

___

### mock

• **mock**: [`MockContext`](akashaproject_ui_awf_testing_utils._internal_.MockContext.md)<`T`, `Y`\>

Provides access to the mock's metadata

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mock](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mock)

#### Defined in

node_modules/@types/jest/index.d.ts:1146

___

### name

• `Readonly` **name**: `string`

Returns the name of the function. Function names are read-only and can not be changed.

#### Inherited from

Function.name

#### Defined in

node_modules/typescript/lib/lib.es2015.core.d.ts:97

___

### prototype

• **prototype**: `any`

#### Inherited from

Function.prototype

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:298

## Methods

### [hasInstance]

▸ **[hasInstance]**(`value`): `boolean`

Determines whether the given value inherits from this function if this function was used
as a constructor function.

A constructor function can control which objects are recognized as its instances by
'instanceof' by overriding this method.

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`boolean`

#### Inherited from

Function.\_\_@hasInstance@97703

#### Defined in

node_modules/typescript/lib/lib.es2015.symbol.wellknown.d.ts:162

___

### apply

▸ **apply**(`thisArg`, `argArray?`): `any`

Calls the function, substituting the specified object for the this value of the function, and the specified array for the arguments of the function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `thisArg` | `any` | The object to be used as the this object. |
| `argArray?` | `any` | A set of arguments to be passed to the function. |

#### Returns

`any`

#### Inherited from

Function.apply

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:278

___

### bind

▸ **bind**(`thisArg`, ...`argArray`): `any`

For a given function, creates a bound function that has the same body as the original function.
The this object of the bound function is associated with the specified object, and has the specified initial parameters.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `thisArg` | `any` | An object to which the this keyword can refer inside the new function. |
| `...argArray` | `any`[] | A list of arguments to be passed to the new function. |

#### Returns

`any`

#### Inherited from

Function.bind

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:293

___

### call

▸ **call**(`thisArg`, ...`argArray`): `any`

Calls a method of an object, substituting another object for the current object.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `thisArg` | `any` | The object to be used as the current object. |
| `...argArray` | `any`[] | A list of arguments to be passed to the method. |

#### Returns

`any`

#### Inherited from

Function.call

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:285

___

### getMockImplementation

▸ **getMockImplementation**(): (...`args`: `Y`) => `T`

Returns the function that was set as the implementation of the mock (using mockImplementation).

#### Returns

`fn`

▸ (...`args`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Y` |

##### Returns

`T`

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[getMockImplementation](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#getmockimplementation)

#### Defined in

node_modules/@types/jest/index.d.ts:1182

___

### getMockName

▸ **getMockName**(): `string`

Returns the mock name string set by calling `mockFn.mockName(value)`.

#### Returns

`string`

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[getMockName](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#getmockname)

#### Defined in

node_modules/@types/jest/index.d.ts:1144

___

### mockClear

▸ **mockClear**(): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Resets all information stored in the mockFn.mock.calls and mockFn.mock.instances arrays.

Often this is useful when you want to clean up a mock's usage data between two assertions.

Beware that `mockClear` will replace `mockFn.mock`, not just `mockFn.mock.calls` and `mockFn.mock.instances`.
You should therefore avoid assigning mockFn.mock to other variables, temporary or not, to make sure you
don't access stale data.

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockClear](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockclear)

#### Defined in

node_modules/@types/jest/index.d.ts:1156

___

### mockImplementation

▸ **mockImplementation**(`fn?`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Accepts a function that should be used as the implementation of the mock. The mock itself will still record
all calls that go into and instances that come from itself – the only difference is that the implementation
will also be executed when the mock is called.

Note: `jest.fn(implementation)` is a shorthand for `jest.fn().mockImplementation(implementation)`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn?` | (...`args`: `Y`) => `T` |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockImplementation](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockimplementation)

#### Defined in

node_modules/@types/jest/index.d.ts:1190

___

### mockImplementationOnce

▸ **mockImplementationOnce**(`fn`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Accepts a function that will be used as an implementation of the mock for one call to the mocked function.
Can be chained so that multiple function calls produce different results.

**`example`**

const myMockFn = jest
  .fn()
   .mockImplementationOnce(cb => cb(null, true))
   .mockImplementationOnce(cb => cb(null, false));

myMockFn((err, val) => console.log(val)); // true

myMockFn((err, val) => console.log(val)); // false

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | (...`args`: `Y`) => `T` |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockImplementationOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockimplementationonce)

#### Defined in

node_modules/@types/jest/index.d.ts:1206

___

### mockName

▸ **mockName**(`name`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Sets the name of the mock`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockName](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockname)

#### Defined in

node_modules/@types/jest/index.d.ts:1208

___

### mockRejectedValue

▸ **mockRejectedValue**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Simple sugar function for: `jest.fn().mockImplementation(() => Promise.reject(value));`

**`example`**

test('async test', async () => {
  const asyncMock = jest.fn().mockRejectedValue(new Error('Async error'));

  await asyncMock(); // throws "Async error"
});

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`RejectedValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#rejectedvalue)<`T`\> |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockRejectedValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrejectedvalue)

#### Defined in

node_modules/@types/jest/index.d.ts:1283

___

### mockRejectedValueOnce

▸ **mockRejectedValueOnce**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Simple sugar function for: `jest.fn().mockImplementationOnce(() => Promise.reject(value));`

**`example`**

test('async test', async () => {
 const asyncMock = jest
   .fn()
   .mockResolvedValueOnce('first call')
   .mockRejectedValueOnce(new Error('Async error'));

 await asyncMock(); // first call
 await asyncMock(); // throws "Async error"
});

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`RejectedValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#rejectedvalue)<`T`\> |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockRejectedValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrejectedvalueonce)

#### Defined in

node_modules/@types/jest/index.d.ts:1301

___

### mockReset

▸ **mockReset**(): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Resets all information stored in the mock, including any initial implementation and mock name given.

This is useful when you want to completely restore a mock back to its initial state.

Beware that `mockReset` will replace `mockFn.mock`, not just `mockFn.mock.calls` and `mockFn.mock.instances`.
You should therefore avoid assigning mockFn.mock to other variables, temporary or not, to make sure you
don't access stale data.

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockReset](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreset)

#### Defined in

node_modules/@types/jest/index.d.ts:1166

___

### mockResolvedValue

▸ **mockResolvedValue**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Simple sugar function for: `jest.fn().mockImplementation(() => Promise.resolve(value));`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`ResolvedValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#resolvedvalue)<`T`\> |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockResolvedValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockresolvedvalue)

#### Defined in

node_modules/@types/jest/index.d.ts:1251

___

### mockResolvedValueOnce

▸ **mockResolvedValueOnce**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Simple sugar function for: `jest.fn().mockImplementationOnce(() => Promise.resolve(value));`

**`example`**

test('async test', async () => {
 const asyncMock = jest
   .fn()
   .mockResolvedValue('default')
   .mockResolvedValueOnce('first call')
   .mockResolvedValueOnce('second call');

 await asyncMock(); // first call
 await asyncMock(); // second call
 await asyncMock(); // default
 await asyncMock(); // default
});

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`ResolvedValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#resolvedvalue)<`T`\> |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockResolvedValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockresolvedvalueonce)

#### Defined in

node_modules/@types/jest/index.d.ts:1271

___

### mockRestore

▸ **mockRestore**(): `void`

Does everything that `mockFn.mockReset()` does, and also restores the original (non-mocked) implementation.

This is useful when you want to mock functions in certain test cases and restore the original implementation in others.

Beware that `mockFn.mockRestore` only works when mock was created with `jest.spyOn`. Thus you have to take care of restoration
yourself when manually assigning `jest.fn()`.

The [`restoreMocks`](https://jestjs.io/docs/en/configuration.html#restoremocks-boolean) configuration option is available
to restore mocks automatically between tests.

#### Returns

`void`

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockRestore](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrestore)

#### Defined in

node_modules/@types/jest/index.d.ts:1178

___

### mockReturnThis

▸ **mockReturnThis**(): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Just a simple sugar function for:

**`example`**

  jest.fn(function() {
    return this;
  });

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockReturnThis](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnthis)

#### Defined in

node_modules/@types/jest/index.d.ts:1218

___

### mockReturnValue

▸ **mockReturnValue**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Accepts a value that will be returned whenever the mock function is called.

**`example`**

const mock = jest.fn();
mock.mockReturnValue(42);
mock(); // 42
mock.mockReturnValue(43);
mock(); // 43

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `T` |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockReturnValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnvalue)

#### Defined in

node_modules/@types/jest/index.d.ts:1230

___

### mockReturnValueOnce

▸ **mockReturnValueOnce**(`value`): [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

Accepts a value that will be returned for one call to the mock function. Can be chained so that
successive calls to the mock function return different values. When there are no more
`mockReturnValueOnce` values to use, calls will return a value specified by `mockReturnValue`.

**`example`**

const myMockFn = jest.fn()
  .mockReturnValue('default')
  .mockReturnValueOnce('first call')
  .mockReturnValueOnce('second call');

// 'first call', 'second call', 'default', 'default'
console.log(myMockFn(), myMockFn(), myMockFn(), myMockFn());

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `T` |

#### Returns

[`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`T`, `Y`\>

#### Inherited from

[MockInstance](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md).[mockReturnValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnvalueonce)

#### Defined in

node_modules/@types/jest/index.d.ts:1247

___

### toString

▸ **toString**(): `string`

Returns a string representation of a function.

#### Returns

`string`

#### Inherited from

Function.toString

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:296
