[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](akashaproject_ui_awf_testing_utils.md) / queries

# Namespace: queries

[@akashaproject/ui-awf-testing-utils](akashaproject_ui_awf_testing_utils.md).queries

## Table of contents

### Interfaces

- [ByRoleOptions](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)

### Type aliases

- [AllByBoundAttribute](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)
- [AllByRole](akashaproject_ui_awf_testing_utils.queries.md#allbyrole)
- [AllByText](akashaproject_ui_awf_testing_utils.queries.md#allbytext)
- [FindAllByBoundAttribute](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)
- [FindAllByRole](akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)
- [FindAllByText](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)
- [FindByBoundAttribute](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)
- [FindByRole](akashaproject_ui_awf_testing_utils.queries.md#findbyrole)
- [FindByText](akashaproject_ui_awf_testing_utils.queries.md#findbytext)
- [GetByBoundAttribute](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)
- [GetByRole](akashaproject_ui_awf_testing_utils.queries.md#getbyrole)
- [GetByText](akashaproject_ui_awf_testing_utils.queries.md#getbytext)
- [QueryByBoundAttribute](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)
- [QueryByRole](akashaproject_ui_awf_testing_utils.queries.md#querybyrole)
- [QueryByText](akashaproject_ui_awf_testing_utils.queries.md#querybytext)

### Functions

- [findAllByAltText](akashaproject_ui_awf_testing_utils.queries.md#findallbyalttext)
- [findAllByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#findallbydisplayvalue)
- [findAllByLabelText](akashaproject_ui_awf_testing_utils.queries.md#findallbylabeltext)
- [findAllByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#findallbyplaceholdertext)
- [findAllByRole](akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)
- [findAllByTestId](akashaproject_ui_awf_testing_utils.queries.md#findallbytestid)
- [findAllByText](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)
- [findAllByTitle](akashaproject_ui_awf_testing_utils.queries.md#findallbytitle)
- [findByAltText](akashaproject_ui_awf_testing_utils.queries.md#findbyalttext)
- [findByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#findbydisplayvalue)
- [findByLabelText](akashaproject_ui_awf_testing_utils.queries.md#findbylabeltext)
- [findByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#findbyplaceholdertext)
- [findByRole](akashaproject_ui_awf_testing_utils.queries.md#findbyrole)
- [findByTestId](akashaproject_ui_awf_testing_utils.queries.md#findbytestid)
- [findByText](akashaproject_ui_awf_testing_utils.queries.md#findbytext)
- [findByTitle](akashaproject_ui_awf_testing_utils.queries.md#findbytitle)
- [getAllByAltText](akashaproject_ui_awf_testing_utils.queries.md#getallbyalttext)
- [getAllByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#getallbydisplayvalue)
- [getAllByLabelText](akashaproject_ui_awf_testing_utils.queries.md#getallbylabeltext)
- [getAllByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#getallbyplaceholdertext)
- [getAllByRole](akashaproject_ui_awf_testing_utils.queries.md#getallbyrole)
- [getAllByTestId](akashaproject_ui_awf_testing_utils.queries.md#getallbytestid)
- [getAllByText](akashaproject_ui_awf_testing_utils.queries.md#getallbytext)
- [getAllByTitle](akashaproject_ui_awf_testing_utils.queries.md#getallbytitle)
- [getByAltText](akashaproject_ui_awf_testing_utils.queries.md#getbyalttext)
- [getByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#getbydisplayvalue)
- [getByLabelText](akashaproject_ui_awf_testing_utils.queries.md#getbylabeltext)
- [getByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#getbyplaceholdertext)
- [getByRole](akashaproject_ui_awf_testing_utils.queries.md#getbyrole)
- [getByTestId](akashaproject_ui_awf_testing_utils.queries.md#getbytestid)
- [getByText](akashaproject_ui_awf_testing_utils.queries.md#getbytext)
- [getByTitle](akashaproject_ui_awf_testing_utils.queries.md#getbytitle)
- [queryAllByAltText](akashaproject_ui_awf_testing_utils.queries.md#queryallbyalttext)
- [queryAllByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#queryallbydisplayvalue)
- [queryAllByLabelText](akashaproject_ui_awf_testing_utils.queries.md#queryallbylabeltext)
- [queryAllByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#queryallbyplaceholdertext)
- [queryAllByRole](akashaproject_ui_awf_testing_utils.queries.md#queryallbyrole)
- [queryAllByTestId](akashaproject_ui_awf_testing_utils.queries.md#queryallbytestid)
- [queryAllByText](akashaproject_ui_awf_testing_utils.queries.md#queryallbytext)
- [queryAllByTitle](akashaproject_ui_awf_testing_utils.queries.md#queryallbytitle)
- [queryByAltText](akashaproject_ui_awf_testing_utils.queries.md#querybyalttext)
- [queryByDisplayValue](akashaproject_ui_awf_testing_utils.queries.md#querybydisplayvalue)
- [queryByLabelText](akashaproject_ui_awf_testing_utils.queries.md#querybylabeltext)
- [queryByPlaceholderText](akashaproject_ui_awf_testing_utils.queries.md#querybyplaceholdertext)
- [queryByRole](akashaproject_ui_awf_testing_utils.queries.md#querybyrole)
- [queryByTestId](akashaproject_ui_awf_testing_utils.queries.md#querybytestid)
- [queryByText](akashaproject_ui_awf_testing_utils.queries.md#querybytext)
- [queryByTitle](akashaproject_ui_awf_testing_utils.queries.md#querybytitle)

## Type aliases

### AllByBoundAttribute

Ƭ **AllByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:11

___

### AllByRole

Ƭ **AllByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:120

___

### AllByText

Ƭ **AllByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:43

___

### FindAllByBoundAttribute

Ƭ **FindAllByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:17

___

### FindAllByRole

Ƭ **FindAllByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:145

___

### FindAllByText

Ƭ **FindAllByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:49

___

### FindByBoundAttribute

Ƭ **FindByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:30

___

### FindByRole

Ƭ **FindByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:138

___

### FindByText

Ƭ **FindByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:62

___

### GetByBoundAttribute

Ƭ **GetByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:24

___

### GetByRole

Ƭ **GetByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:126

___

### GetByText

Ƭ **GetByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

##### Returns

`T`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:56

___

### QueryByBoundAttribute

Ƭ **QueryByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:5

___

### QueryByRole

Ƭ **QueryByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:132

___

### QueryByText

Ƭ **QueryByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

##### Returns

`T` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:37

## Functions

### findAllByAltText

▸ **findAllByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:221

___

### findAllByDisplayValue

▸ **findAllByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:257

___

### findAllByLabelText

▸ **findAllByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByText`](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByText`](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:167

___

### findAllByPlaceholderText

▸ **findAllByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:185

___

### findAllByRole

▸ **findAllByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByRole`](akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByRole`](akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:275

___

### findAllByTestId

▸ **findAllByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:293

___

### findAllByText

▸ **findAllByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByText`](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByText`](akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:203

___

### findAllByTitle

▸ **findAllByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindAllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:239

___

### findByAltText

▸ **findByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:218

___

### findByDisplayValue

▸ **findByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:254

___

### findByLabelText

▸ **findByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByText`](akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByText`](akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:164

___

### findByPlaceholderText

▸ **findByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:182

___

### findByRole

▸ **findByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByRole`](akashaproject_ui_awf_testing_utils.queries.md#findbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByRole`](akashaproject_ui_awf_testing_utils.queries.md#findbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:272

___

### findByTestId

▸ **findByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:290

___

### findByText

▸ **findByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByText`](akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByText`](akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:200

___

### findByTitle

▸ **findByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`FindByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:236

___

### getAllByAltText

▸ **getAllByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:209

___

### getAllByDisplayValue

▸ **getAllByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:245

___

### getAllByLabelText

▸ **getAllByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:155

___

### getAllByPlaceholderText

▸ **getAllByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:173

___

### getAllByRole

▸ **getAllByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByRole`](akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByRole`](akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:263

___

### getAllByTestId

▸ **getAllByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:281

___

### getAllByText

▸ **getAllByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:191

___

### getAllByTitle

▸ **getAllByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:227

___

### getByAltText

▸ **getByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:206

___

### getByDisplayValue

▸ **getByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:242

___

### getByLabelText

▸ **getByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByText`](akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByText`](akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:152

___

### getByPlaceholderText

▸ **getByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:170

___

### getByRole

▸ **getByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByRole`](akashaproject_ui_awf_testing_utils.queries.md#getbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByRole`](akashaproject_ui_awf_testing_utils.queries.md#getbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:260

___

### getByTestId

▸ **getByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:278

___

### getByText

▸ **getByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByText`](akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByText`](akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:188

___

### getByTitle

▸ **getByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`GetByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:224

___

### queryAllByAltText

▸ **queryAllByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:215

___

### queryAllByDisplayValue

▸ **queryAllByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:251

___

### queryAllByLabelText

▸ **queryAllByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:161

___

### queryAllByPlaceholderText

▸ **queryAllByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:179

___

### queryAllByRole

▸ **queryAllByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByRole`](akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByRole`](akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:269

___

### queryAllByTestId

▸ **queryAllByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:287

___

### queryAllByText

▸ **queryAllByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByText`](akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:197

___

### queryAllByTitle

▸ **queryAllByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`AllByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:233

___

### queryByAltText

▸ **queryByAltText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:212

___

### queryByDisplayValue

▸ **queryByDisplayValue**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:248

___

### queryByLabelText

▸ **queryByLabelText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByText`](akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByText`](akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:158

___

### queryByPlaceholderText

▸ **queryByPlaceholderText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:176

___

### queryByRole

▸ **queryByRole**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByRole`](akashaproject_ui_awf_testing_utils.queries.md#querybyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, role: ByRoleMatcher, options?: ByRoleOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByRole`](akashaproject_ui_awf_testing_utils.queries.md#querybyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:266

___

### queryByTestId

▸ **queryByTestId**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:284

___

### queryByText

▸ **queryByText**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByText`](akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: SelectorMatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByText`](akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:194

___

### queryByTitle

▸ **queryByTitle**<`T`\>(...`args`): [`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | [container: HTMLElement, id: Matcher, options?: MatcherOptions] |

#### Returns

[`ReturnType`](akashaproject_ui_awf_testing_utils._internal_.md#returntype)<[`QueryByBoundAttribute`](akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:230
