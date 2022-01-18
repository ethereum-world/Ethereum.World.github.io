[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MockInstance

# Interface: MockInstance<T, Y\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MockInstance

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `T` |
| `Y` | extends `any`[] |

## Hierarchy

- **`MockInstance`**

  ↳ [`Mock`](akashaproject_ui_awf_testing_utils._internal_.Mock.md)

## Table of contents

### Properties

- [mock](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mock)

### Methods

- [getMockImplementation](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#getmockimplementation)
- [getMockName](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#getmockname)
- [mockClear](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockclear)
- [mockImplementation](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockimplementation)
- [mockImplementationOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockimplementationonce)
- [mockName](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockname)
- [mockRejectedValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrejectedvalue)
- [mockRejectedValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrejectedvalueonce)
- [mockReset](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreset)
- [mockResolvedValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockresolvedvalue)
- [mockResolvedValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockresolvedvalueonce)
- [mockRestore](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockrestore)
- [mockReturnThis](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnthis)
- [mockReturnValue](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnvalue)
- [mockReturnValueOnce](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md#mockreturnvalueonce)

## Properties

### mock

• **mock**: [`MockContext`](akashaproject_ui_awf_testing_utils._internal_.MockContext.md)<`T`, `Y`\>

Provides access to the mock's metadata

#### Defined in

node_modules/@types/jest/index.d.ts:1146

## Methods

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

#### Defined in

node_modules/@types/jest/index.d.ts:1182

___

### getMockName

▸ **getMockName**(): `string`

Returns the mock name string set by calling `mockFn.mockName(value)`.

#### Returns

`string`

#### Defined in

node_modules/@types/jest/index.d.ts:1144

___

### mockClear

▸ **mockClear**(): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Resets all information stored in the mockFn.mock.calls and mockFn.mock.instances arrays.

Often this is useful when you want to clean up a mock's usage data between two assertions.

Beware that `mockClear` will replace `mockFn.mock`, not just `mockFn.mock.calls` and `mockFn.mock.instances`.
You should therefore avoid assigning mockFn.mock to other variables, temporary or not, to make sure you
don't access stale data.

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1156

___

### mockImplementation

▸ **mockImplementation**(`fn?`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Accepts a function that should be used as the implementation of the mock. The mock itself will still record
all calls that go into and instances that come from itself – the only difference is that the implementation
will also be executed when the mock is called.

Note: `jest.fn(implementation)` is a shorthand for `jest.fn().mockImplementation(implementation)`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn?` | (...`args`: `Y`) => `T` |

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1190

___

### mockImplementationOnce

▸ **mockImplementationOnce**(`fn`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1206

___

### mockName

▸ **mockName**(`name`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Sets the name of the mock`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1208

___

### mockRejectedValue

▸ **mockRejectedValue**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1283

___

### mockRejectedValueOnce

▸ **mockRejectedValueOnce**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1301

___

### mockReset

▸ **mockReset**(): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Resets all information stored in the mock, including any initial implementation and mock name given.

This is useful when you want to completely restore a mock back to its initial state.

Beware that `mockReset` will replace `mockFn.mock`, not just `mockFn.mock.calls` and `mockFn.mock.instances`.
You should therefore avoid assigning mockFn.mock to other variables, temporary or not, to make sure you
don't access stale data.

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1166

___

### mockResolvedValue

▸ **mockResolvedValue**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Simple sugar function for: `jest.fn().mockImplementation(() => Promise.resolve(value));`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`ResolvedValue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#resolvedvalue)<`T`\> |

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1251

___

### mockResolvedValueOnce

▸ **mockResolvedValueOnce**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

#### Defined in

node_modules/@types/jest/index.d.ts:1178

___

### mockReturnThis

▸ **mockReturnThis**(): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

Just a simple sugar function for:

**`example`**

  jest.fn(function() {
    return this;
  });

#### Returns

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1218

___

### mockReturnValue

▸ **mockReturnValue**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1230

___

### mockReturnValueOnce

▸ **mockReturnValueOnce**(`value`): [`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

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

[`MockInstance`](akashaproject_ui_awf_testing_utils._internal_.MockInstance.md)<`T`, `Y`\>

#### Defined in

node_modules/@types/jest/index.d.ts:1247
