[AWF](../README.md) / [Exports](../modules.md) / [@akashaproject/ui-awf-testing-utils](_akashaproject_ui_awf_testing_utils.md) / queryHelpers

# Namespace: queryHelpers

[@akashaproject/ui-awf-testing-utils](_akashaproject_ui_awf_testing_utils.md).queryHelpers

## Table of contents

### Interfaces

- [SelectorMatcherOptions](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)

### Type aliases

- [AllByAttribute](_akashaproject_ui_awf_testing_utils.queryHelpers.md#allbyattribute)
- [BuiltQueryMethods](_akashaproject_ui_awf_testing_utils.queryHelpers.md#builtquerymethods)
- [FindAllBy](_akashaproject_ui_awf_testing_utils.queryHelpers.md#findallby)
- [FindBy](_akashaproject_ui_awf_testing_utils.queryHelpers.md#findby)
- [GetAllBy](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getallby)
- [GetBy](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getby)
- [GetErrorFunction](_akashaproject_ui_awf_testing_utils.queryHelpers.md#geterrorfunction)
- [QueryBy](_akashaproject_ui_awf_testing_utils.queryHelpers.md#queryby)
- [QueryByAttribute](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querybyattribute)
- [QueryMethod](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)
- [WithSuggest](_akashaproject_ui_awf_testing_utils.queryHelpers.md#withsuggest)

### Functions

- [buildQueries](_akashaproject_ui_awf_testing_utils.queryHelpers.md#buildqueries)
- [getElementError](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getelementerror)
- [queryAllByAttribute](_akashaproject_ui_awf_testing_utils.queryHelpers.md#queryallbyattribute)
- [queryByAttribute](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querybyattribute)

## Type aliases

### AllByAttribute

Ƭ **AllByAttribute**: (`attribute`: `string`, `container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `HTMLElement`[]

#### Type declaration

▸ (`attribute`, `container`, `id`, `options?`): `HTMLElement`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`HTMLElement`[]

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:23

___

### BuiltQueryMethods

Ƭ **BuiltQueryMethods**<`Arguments`\>: [[`QueryBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#queryby)<`Arguments`\>, [`GetAllBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getallby)<`Arguments`\>, [`GetBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getby)<`Arguments`\>, [`FindAllBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#findallby)<`Arguments`\>, [`FindBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#findby)<`Arguments`\>]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:62

___

### FindAllBy

Ƭ **FindAllBy**<`Arguments`\>: [`QueryMethod`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<[`Arguments`[``0``], Arguments[1]?, waitForOptions?], `Promise`<`HTMLElement`[]\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:52

___

### FindBy

Ƭ **FindBy**<`Arguments`\>: [`QueryMethod`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<[`Arguments`[``0``], Arguments[1]?, waitForOptions?], `Promise`<`HTMLElement`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:57

___

### GetAllBy

Ƭ **GetAllBy**<`Arguments`\>: [`QueryMethod`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:48

___

### GetBy

Ƭ **GetBy**<`Arguments`\>: [`QueryMethod`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:56

___

### GetErrorFunction

Ƭ **GetErrorFunction**<`Arguments`\>: (`c`: `Element` \| ``null``, ...`args`: `Arguments`) => `string`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[][`string`] |

#### Type declaration

▸ (`c`, ...`args`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `c` | `Element` \| ``null`` |
| `...args` | `Arguments` |

##### Returns

`string`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:6

___

### QueryBy

Ƭ **QueryBy**<`Arguments`\>: [`QueryMethod`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement` \| ``null``\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:44

___

### QueryByAttribute

Ƭ **QueryByAttribute**: (`attribute`: `string`, `container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `HTMLElement` \| ``null``

#### Type declaration

▸ (`attribute`, `container`, `id`, `options?`): `HTMLElement` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`HTMLElement` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:16

___

### QueryMethod

Ƭ **QueryMethod**<`Arguments`, `Return`\>: (`container`: `HTMLElement`, ...`args`: `Arguments`) => `Return`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |
| `Return` | `Return` |

#### Type declaration

▸ (`container`, ...`args`): `Return`

query methods have a common call signature. Only the return type differs.

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `...args` | `Arguments` |

##### Returns

`Return`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:40

___

### WithSuggest

Ƭ **WithSuggest**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `suggest?` | `boolean` |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:4

## Functions

### buildQueries

▸ **buildQueries**<`Arguments`\>(`queryAllBy`, `getMultipleError`, `getMissingError`): [`BuiltQueryMethods`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#builtquerymethods)<`Arguments`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryAllBy` | [`GetAllBy`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#getallby)<`Arguments`\> |
| `getMultipleError` | [`GetErrorFunction`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#geterrorfunction) |
| `getMissingError` | [`GetErrorFunction`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#geterrorfunction) |

#### Returns

[`BuiltQueryMethods`](_akashaproject_ui_awf_testing_utils.queryHelpers.md#builtquerymethods)<`Arguments`\>

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:70

___

### getElementError

▸ **getElementError**(`message`, `container`): `Error`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` \| ``null`` |
| `container` | `HTMLElement` |

#### Returns

`Error`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:32

___

### queryAllByAttribute

▸ `Const` **queryAllByAttribute**(`attribute`, `container`, `id`, `options?`): `HTMLElement`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`[]

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:31

___

### queryByAttribute

▸ `Const` **queryByAttribute**(`attribute`, `container`, `id`, `options?`): `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:30
