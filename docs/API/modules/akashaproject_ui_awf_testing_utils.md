[AWF](../README.md) / [Modules](../modules.md) / @akashaproject/ui-awf-testing-utils

# Module: @akashaproject/ui-awf-testing-utils

## Table of contents

### Namespaces

- [&lt;internal\&gt;](akashaproject_ui_awf_testing_utils._internal_.md)
- [prettyFormat](akashaproject_ui_awf_testing_utils.prettyFormat.md)
- [queries](akashaproject_ui_awf_testing_utils.queries.md)
- [queryHelpers](akashaproject_ui_awf_testing_utils.queryHelpers.md)

### Interfaces

- [ByRoleOptions](../interfaces/akashaproject_ui_awf_testing_utils.ByRoleOptions.md)
- [ChannelOverrides](../interfaces/akashaproject_ui_awf_testing_utils.ChannelOverrides.md)
- [Config](../interfaces/akashaproject_ui_awf_testing_utils.Config.md)
- [ConfigFn](../interfaces/akashaproject_ui_awf_testing_utils.ConfigFn.md)
- [DefaultNormalizerOptions](../interfaces/akashaproject_ui_awf_testing_utils.DefaultNormalizerOptions.md)
- [MatcherOptions](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)
- [NormalizerOptions](../interfaces/akashaproject_ui_awf_testing_utils.NormalizerOptions.md)
- [PrettyDOMOptions](../interfaces/akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md)
- [Queries](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md)
- [QueryOptions](../interfaces/akashaproject_ui_awf_testing_utils.QueryOptions.md)
- [RenderOptions](../interfaces/akashaproject_ui_awf_testing_utils.RenderOptions.md)
- [SelectorMatcherOptions](../interfaces/akashaproject_ui_awf_testing_utils.SelectorMatcherOptions.md)
- [Suggestion](../interfaces/akashaproject_ui_awf_testing_utils.Suggestion.md)
- [waitForOptions](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md)

### Type aliases

- [AllByAttribute](akashaproject_ui_awf_testing_utils.md#allbyattribute)
- [AllByBoundAttribute](akashaproject_ui_awf_testing_utils.md#allbyboundattribute)
- [AllByRole](akashaproject_ui_awf_testing_utils.md#allbyrole)
- [AllByText](akashaproject_ui_awf_testing_utils.md#allbytext)
- [BoundFunction](akashaproject_ui_awf_testing_utils.md#boundfunction)
- [BoundFunctions](akashaproject_ui_awf_testing_utils.md#boundfunctions)
- [BuiltQueryMethods](akashaproject_ui_awf_testing_utils.md#builtquerymethods)
- [ByRoleMatcher](akashaproject_ui_awf_testing_utils.md#byrolematcher)
- [CreateFunction](akashaproject_ui_awf_testing_utils.md#createfunction)
- [CreateObject](akashaproject_ui_awf_testing_utils.md#createobject)
- [EventType](akashaproject_ui_awf_testing_utils.md#eventtype)
- [FindAllBy](akashaproject_ui_awf_testing_utils.md#findallby)
- [FindAllByBoundAttribute](akashaproject_ui_awf_testing_utils.md#findallbyboundattribute)
- [FindAllByRole](akashaproject_ui_awf_testing_utils.md#findallbyrole)
- [FindAllByText](akashaproject_ui_awf_testing_utils.md#findallbytext)
- [FindBy](akashaproject_ui_awf_testing_utils.md#findby)
- [FindByBoundAttribute](akashaproject_ui_awf_testing_utils.md#findbyboundattribute)
- [FindByRole](akashaproject_ui_awf_testing_utils.md#findbyrole)
- [FindByText](akashaproject_ui_awf_testing_utils.md#findbytext)
- [FireFunction](akashaproject_ui_awf_testing_utils.md#firefunction)
- [FireObject](akashaproject_ui_awf_testing_utils.md#fireobject)
- [GetAllBy](akashaproject_ui_awf_testing_utils.md#getallby)
- [GetBy](akashaproject_ui_awf_testing_utils.md#getby)
- [GetByBoundAttribute](akashaproject_ui_awf_testing_utils.md#getbyboundattribute)
- [GetByRole](akashaproject_ui_awf_testing_utils.md#getbyrole)
- [GetByText](akashaproject_ui_awf_testing_utils.md#getbytext)
- [GetErrorFunction](akashaproject_ui_awf_testing_utils.md#geterrorfunction)
- [Match](akashaproject_ui_awf_testing_utils.md#match)
- [Matcher](akashaproject_ui_awf_testing_utils.md#matcher)
- [MatcherFunction](akashaproject_ui_awf_testing_utils.md#matcherfunction)
- [Method](akashaproject_ui_awf_testing_utils.md#method)
- [NormalizerFn](akashaproject_ui_awf_testing_utils.md#normalizerfn)
- [Query](akashaproject_ui_awf_testing_utils.md#query)
- [QueryArgs](akashaproject_ui_awf_testing_utils.md#queryargs)
- [QueryBy](akashaproject_ui_awf_testing_utils.md#queryby)
- [QueryByAttribute](akashaproject_ui_awf_testing_utils.md#querybyattribute)
- [QueryByBoundAttribute](akashaproject_ui_awf_testing_utils.md#querybyboundattribute)
- [QueryByRole](akashaproject_ui_awf_testing_utils.md#querybyrole)
- [QueryByText](akashaproject_ui_awf_testing_utils.md#querybytext)
- [QueryMethod](akashaproject_ui_awf_testing_utils.md#querymethod)
- [RenderResult](akashaproject_ui_awf_testing_utils.md#renderresult)
- [Screen](akashaproject_ui_awf_testing_utils.md#screen)
- [Variant](akashaproject_ui_awf_testing_utils.md#variant)
- [WithSuggest](akashaproject_ui_awf_testing_utils.md#withsuggest)

### Variables

- [createEvent](akashaproject_ui_awf_testing_utils.md#createevent)
- [fireEvent](akashaproject_ui_awf_testing_utils.md#fireevent)
- [globalChannelMock](akashaproject_ui_awf_testing_utils.md#globalchannelmock)
- [screen](akashaproject_ui_awf_testing_utils.md#screen)

### Functions

- [act](akashaproject_ui_awf_testing_utils.md#act)
- [buildQueries](akashaproject_ui_awf_testing_utils.md#buildqueries)
- [cleanup](akashaproject_ui_awf_testing_utils.md#cleanup)
- [computeHeadingLevel](akashaproject_ui_awf_testing_utils.md#computeheadinglevel)
- [configure](akashaproject_ui_awf_testing_utils.md#configure)
- [findAllByAltText](akashaproject_ui_awf_testing_utils.md#findallbyalttext)
- [findAllByDisplayValue](akashaproject_ui_awf_testing_utils.md#findallbydisplayvalue)
- [findAllByLabelText](akashaproject_ui_awf_testing_utils.md#findallbylabeltext)
- [findAllByPlaceholderText](akashaproject_ui_awf_testing_utils.md#findallbyplaceholdertext)
- [findAllByRole](akashaproject_ui_awf_testing_utils.md#findallbyrole)
- [findAllByTestId](akashaproject_ui_awf_testing_utils.md#findallbytestid)
- [findAllByText](akashaproject_ui_awf_testing_utils.md#findallbytext)
- [findAllByTitle](akashaproject_ui_awf_testing_utils.md#findallbytitle)
- [findByAltText](akashaproject_ui_awf_testing_utils.md#findbyalttext)
- [findByDisplayValue](akashaproject_ui_awf_testing_utils.md#findbydisplayvalue)
- [findByLabelText](akashaproject_ui_awf_testing_utils.md#findbylabeltext)
- [findByPlaceholderText](akashaproject_ui_awf_testing_utils.md#findbyplaceholdertext)
- [findByRole](akashaproject_ui_awf_testing_utils.md#findbyrole)
- [findByTestId](akashaproject_ui_awf_testing_utils.md#findbytestid)
- [findByText](akashaproject_ui_awf_testing_utils.md#findbytext)
- [findByTitle](akashaproject_ui_awf_testing_utils.md#findbytitle)
- [genEthAddress](akashaproject_ui_awf_testing_utils.md#genethaddress)
- [genLoggedUser](akashaproject_ui_awf_testing_utils.md#genloggeduser)
- [genMockOp](akashaproject_ui_awf_testing_utils.md#genmockop)
- [genPostData](akashaproject_ui_awf_testing_utils.md#genpostdata)
- [genSlatePost](akashaproject_ui_awf_testing_utils.md#genslatepost)
- [genUser](akashaproject_ui_awf_testing_utils.md#genuser)
- [getAllByAltText](akashaproject_ui_awf_testing_utils.md#getallbyalttext)
- [getAllByDisplayValue](akashaproject_ui_awf_testing_utils.md#getallbydisplayvalue)
- [getAllByLabelText](akashaproject_ui_awf_testing_utils.md#getallbylabeltext)
- [getAllByPlaceholderText](akashaproject_ui_awf_testing_utils.md#getallbyplaceholdertext)
- [getAllByRole](akashaproject_ui_awf_testing_utils.md#getallbyrole)
- [getAllByTestId](akashaproject_ui_awf_testing_utils.md#getallbytestid)
- [getAllByText](akashaproject_ui_awf_testing_utils.md#getallbytext)
- [getAllByTitle](akashaproject_ui_awf_testing_utils.md#getallbytitle)
- [getByAltText](akashaproject_ui_awf_testing_utils.md#getbyalttext)
- [getByDisplayValue](akashaproject_ui_awf_testing_utils.md#getbydisplayvalue)
- [getByLabelText](akashaproject_ui_awf_testing_utils.md#getbylabeltext)
- [getByPlaceholderText](akashaproject_ui_awf_testing_utils.md#getbyplaceholdertext)
- [getByRole](akashaproject_ui_awf_testing_utils.md#getbyrole)
- [getByTestId](akashaproject_ui_awf_testing_utils.md#getbytestid)
- [getByText](akashaproject_ui_awf_testing_utils.md#getbytext)
- [getByTitle](akashaproject_ui_awf_testing_utils.md#getbytitle)
- [getConfig](akashaproject_ui_awf_testing_utils.md#getconfig)
- [getDefaultNormalizer](akashaproject_ui_awf_testing_utils.md#getdefaultnormalizer)
- [getElementError](akashaproject_ui_awf_testing_utils.md#getelementerror)
- [getNodeText](akashaproject_ui_awf_testing_utils.md#getnodetext)
- [getQueriesForElement](akashaproject_ui_awf_testing_utils.md#getqueriesforelement)
- [getRoles](akashaproject_ui_awf_testing_utils.md#getroles)
- [getSDKMocks](akashaproject_ui_awf_testing_utils.md#getsdkmocks)
- [getSuggestedQuery](akashaproject_ui_awf_testing_utils.md#getsuggestedquery)
- [isInaccessible](akashaproject_ui_awf_testing_utils.md#isinaccessible)
- [logDOM](akashaproject_ui_awf_testing_utils.md#logdom)
- [logRoles](akashaproject_ui_awf_testing_utils.md#logroles)
- [prettyDOM](akashaproject_ui_awf_testing_utils.md#prettydom)
- [queryAllByAltText](akashaproject_ui_awf_testing_utils.md#queryallbyalttext)
- [queryAllByAttribute](akashaproject_ui_awf_testing_utils.md#queryallbyattribute)
- [queryAllByDisplayValue](akashaproject_ui_awf_testing_utils.md#queryallbydisplayvalue)
- [queryAllByLabelText](akashaproject_ui_awf_testing_utils.md#queryallbylabeltext)
- [queryAllByPlaceholderText](akashaproject_ui_awf_testing_utils.md#queryallbyplaceholdertext)
- [queryAllByRole](akashaproject_ui_awf_testing_utils.md#queryallbyrole)
- [queryAllByTestId](akashaproject_ui_awf_testing_utils.md#queryallbytestid)
- [queryAllByText](akashaproject_ui_awf_testing_utils.md#queryallbytext)
- [queryAllByTitle](akashaproject_ui_awf_testing_utils.md#queryallbytitle)
- [queryByAltText](akashaproject_ui_awf_testing_utils.md#querybyalttext)
- [queryByAttribute](akashaproject_ui_awf_testing_utils.md#querybyattribute)
- [queryByDisplayValue](akashaproject_ui_awf_testing_utils.md#querybydisplayvalue)
- [queryByLabelText](akashaproject_ui_awf_testing_utils.md#querybylabeltext)
- [queryByPlaceholderText](akashaproject_ui_awf_testing_utils.md#querybyplaceholdertext)
- [queryByRole](akashaproject_ui_awf_testing_utils.md#querybyrole)
- [queryByTestId](akashaproject_ui_awf_testing_utils.md#querybytestid)
- [queryByText](akashaproject_ui_awf_testing_utils.md#querybytext)
- [queryByTitle](akashaproject_ui_awf_testing_utils.md#querybytitle)
- [render](akashaproject_ui_awf_testing_utils.md#render)
- [renderWithAllProviders](akashaproject_ui_awf_testing_utils.md#renderwithallproviders)
- [renderWithWrapper](akashaproject_ui_awf_testing_utils.md#renderwithwrapper)
- [waitFor](akashaproject_ui_awf_testing_utils.md#waitfor)
- [waitForElementToBeRemoved](akashaproject_ui_awf_testing_utils.md#waitforelementtoberemoved)
- [within](akashaproject_ui_awf_testing_utils.md#within)

## Type aliases

### AllByAttribute

Ƭ **AllByAttribute**: (`attribute`: `string`, `container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `HTMLElement`[]

#### Type declaration

▸ (`attribute`, `container`, `id`, `options?`): `HTMLElement`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`HTMLElement`[]

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:23

___

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

### BoundFunction

Ƭ **BoundFunction**<`T`\>: `T` extends (`container`: `HTMLElement`, ...`args`: infer P) => infer R ? (...`args`: `P`) => `R` : `never`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:3

___

### BoundFunctions

Ƭ **BoundFunctions**<`Q`\>: `Q` extends typeof [`queries`](akashaproject_ui_awf_testing_utils.queries.md) ? { `findAllByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findAllByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`[]\> ; `findByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `findByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions, waitForElementOptions?: waitForOptions]) => `Promise`<`T`\> ; `getAllByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `getAllByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `getAllByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T`[] ; `getAllByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `getAllByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions]) => `T`[] ; `getAllByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `getAllByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T`[] ; `getAllByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `getByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `getByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `getByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T` ; `getByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `getByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions]) => `T` ; `getByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `getByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T` ; `getByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `queryAllByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `queryAllByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `queryAllByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T`[] ; `queryAllByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `queryAllByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions]) => `T`[] ; `queryAllByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `queryAllByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T`[] ; `queryAllByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`[] ; `queryByAltText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `queryByDisplayValue`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `queryByLabelText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T` ; `queryByPlaceholderText`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `queryByRole`: <T\>(...`args`: [role: ByRoleMatcher, options?: ByRoleOptions]) => `T` ; `queryByTestId`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T` ; `queryByText`: <T\>(...`args`: [id: Matcher, options?: SelectorMatcherOptions]) => `T` ; `queryByTitle`: <T\>(...`args`: [id: Matcher, options?: MatcherOptions]) => `T`  } & { [P in keyof Q]: BoundFunction<Q[P]\> } : { [P in keyof Q]: BoundFunction<Q[P]\> }

#### Type parameters

| Name |
| :------ |
| `Q` |

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:10

___

### BuiltQueryMethods

Ƭ **BuiltQueryMethods**<`Arguments`\>: [[`QueryBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#queryby)<`Arguments`\>, [`GetAllBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#getallby)<`Arguments`\>, [`GetBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#getby)<`Arguments`\>, [`FindAllBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#findallby)<`Arguments`\>, [`FindBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#findby)<`Arguments`\>]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:62

___

### ByRoleMatcher

Ƭ **ByRoleMatcher**: [`ARIARole`](akashaproject_ui_awf_testing_utils._internal_.md#ariarole) \| [`MatcherFunction`](akashaproject_ui_awf_testing_utils.md#matcherfunction) \| {}

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:11

___

### CreateFunction

Ƭ **CreateFunction**: (`eventName`: `string`, `node`: `Document` \| `Element` \| [`Window`](akashaproject_ui_awf_testing_utils._internal_.md#window) \| [`Node`](akashaproject_ui_awf_testing_utils._internal_.md#node), `init?`: {}, `options?`: { `EventType?`: `string` ; `defaultInit?`: {}  }) => `Event`

#### Type declaration

▸ (`eventName`, `node`, `init?`, `options?`): `Event`

##### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` |
| `node` | `Document` \| `Element` \| [`Window`](akashaproject_ui_awf_testing_utils._internal_.md#window) \| [`Node`](akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `init?` | `Object` |
| `options?` | `Object` |
| `options.EventType?` | `string` |
| `options.defaultInit?` | `Object` |

##### Returns

`Event`

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:100

___

### CreateObject

Ƭ **CreateObject**: { [K in EventType]: Function }

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:106

___

### EventType

Ƭ **EventType**: ``"copy"`` \| ``"cut"`` \| ``"paste"`` \| ``"compositionEnd"`` \| ``"compositionStart"`` \| ``"compositionUpdate"`` \| ``"keyDown"`` \| ``"keyPress"`` \| ``"keyUp"`` \| ``"focus"`` \| ``"blur"`` \| ``"focusIn"`` \| ``"focusOut"`` \| ``"change"`` \| ``"input"`` \| ``"invalid"`` \| ``"submit"`` \| ``"reset"`` \| ``"click"`` \| ``"contextMenu"`` \| ``"dblClick"`` \| ``"drag"`` \| ``"dragEnd"`` \| ``"dragEnter"`` \| ``"dragExit"`` \| ``"dragLeave"`` \| ``"dragOver"`` \| ``"dragStart"`` \| ``"drop"`` \| ``"mouseDown"`` \| ``"mouseEnter"`` \| ``"mouseLeave"`` \| ``"mouseMove"`` \| ``"mouseOut"`` \| ``"mouseOver"`` \| ``"mouseUp"`` \| ``"popState"`` \| ``"select"`` \| ``"touchCancel"`` \| ``"touchEnd"`` \| ``"touchMove"`` \| ``"touchStart"`` \| ``"resize"`` \| ``"scroll"`` \| ``"wheel"`` \| ``"abort"`` \| ``"canPlay"`` \| ``"canPlayThrough"`` \| ``"durationChange"`` \| ``"emptied"`` \| ``"encrypted"`` \| ``"ended"`` \| ``"loadedData"`` \| ``"loadedMetadata"`` \| ``"loadStart"`` \| ``"pause"`` \| ``"play"`` \| ``"playing"`` \| ``"progress"`` \| ``"rateChange"`` \| ``"seeked"`` \| ``"seeking"`` \| ``"stalled"`` \| ``"suspend"`` \| ``"timeUpdate"`` \| ``"volumeChange"`` \| ``"waiting"`` \| ``"load"`` \| ``"error"`` \| ``"animationStart"`` \| ``"animationEnd"`` \| ``"animationIteration"`` \| ``"transitionCancel"`` \| ``"transitionEnd"`` \| ``"transitionRun"`` \| ``"transitionStart"`` \| ``"doubleClick"`` \| ``"pointerOver"`` \| ``"pointerEnter"`` \| ``"pointerDown"`` \| ``"pointerMove"`` \| ``"pointerUp"`` \| ``"pointerCancel"`` \| ``"pointerOut"`` \| ``"pointerLeave"`` \| ``"gotPointerCapture"`` \| ``"lostPointerCapture"``

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:1

___

### FindAllBy

Ƭ **FindAllBy**<`Arguments`\>: [`QueryMethod`](akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<[`Arguments`[``0``], Arguments[1]?, waitForOptions?], `Promise`<`HTMLElement`[]\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:52

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

### FindBy

Ƭ **FindBy**<`Arguments`\>: [`QueryMethod`](akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<[`Arguments`[``0``], Arguments[1]?, waitForOptions?], `Promise`<`HTMLElement`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:57

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

### FireFunction

Ƭ **FireFunction**: (`element`: `Document` \| `Element` \| [`Window`](akashaproject_ui_awf_testing_utils._internal_.md#window) \| [`Node`](akashaproject_ui_awf_testing_utils._internal_.md#node), `event`: `Event`) => `boolean`

#### Type declaration

▸ (`element`, `event`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `Document` \| `Element` \| [`Window`](akashaproject_ui_awf_testing_utils._internal_.md#window) \| [`Node`](akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `event` | `Event` |

##### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:90

___

### FireObject

Ƭ **FireObject**: { [K in EventType]: Function }

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:94

___

### GetAllBy

Ƭ **GetAllBy**<`Arguments`\>: [`QueryMethod`](akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:48

___

### GetBy

Ƭ **GetBy**<`Arguments`\>: [`QueryMethod`](akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:56

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

### GetErrorFunction

Ƭ **GetErrorFunction**<`Arguments`\>: (`c`: `Element` \| ``null``, ...`args`: `Arguments`) => `string`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] = [`string`] |

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

### Match

Ƭ **Match**: (`textToMatch`: `string`, `node`: `HTMLElement` \| ``null``, `matcher`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `boolean`

#### Type declaration

▸ (`textToMatch`, `node`, `matcher`, `options?`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `textToMatch` | `string` |
| `node` | `HTMLElement` \| ``null`` |
| `matcher` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:30

___

### Matcher

Ƭ **Matcher**: [`MatcherFunction`](akashaproject_ui_awf_testing_utils.md#matcherfunction) \| `RegExp` \| `number` \| `string`

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:7

___

### MatcherFunction

Ƭ **MatcherFunction**: (`content`: `string`, `element`: `Element` \| ``null``) => `boolean`

#### Type declaration

▸ (`content`, `element`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `content` | `string` |
| `element` | `Element` \| ``null`` |

##### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:3

___

### Method

Ƭ **Method**: ``"AltText"`` \| ``"alttext"`` \| ``"DisplayValue"`` \| ``"displayvalue"`` \| ``"LabelText"`` \| ``"labeltext"`` \| ``"PlaceholderText"`` \| ``"placeholdertext"`` \| ``"Role"`` \| ``"role"`` \| ``"TestId"`` \| ``"testid"`` \| ``"Text"`` \| ``"text"`` \| ``"Title"`` \| ``"title"``

#### Defined in

node_modules/@testing-library/dom/types/suggestions.d.ts:24

___

### NormalizerFn

Ƭ **NormalizerFn**: (`text`: `string`) => `string`

#### Type declaration

▸ (`text`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `text` | `string` |

##### Returns

`string`

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:13

___

### Query

Ƭ **Query**: (`container`: `HTMLElement`, ...`args`: `any`[]) => [`Error`](akashaproject_ui_awf_testing_utils._internal_.md#error) \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

#### Type declaration

▸ (`container`, ...`args`): [`Error`](akashaproject_ui_awf_testing_utils._internal_.md#error) \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `...args` | `any`[] |

##### Returns

[`Error`](akashaproject_ui_awf_testing_utils._internal_.md#error) \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:163

___

### QueryArgs

Ƭ **QueryArgs**: [`string`, QueryOptions?]

#### Defined in

node_modules/@testing-library/dom/types/suggestions.d.ts:5

___

### QueryBy

Ƭ **QueryBy**<`Arguments`\>: [`QueryMethod`](akashaproject_ui_awf_testing_utils.queryHelpers.md#querymethod)<`Arguments`, `HTMLElement` \| ``null``\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:44

___

### QueryByAttribute

Ƭ **QueryByAttribute**: (`attribute`: `string`, `container`: `HTMLElement`, `id`: [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `HTMLElement` \| ``null``

#### Type declaration

▸ (`attribute`, `container`, `id`, `options?`): `HTMLElement` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`HTMLElement` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:16

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

### RenderResult

Ƭ **RenderResult**<`Q`, `Container`\>: { `baseElement`: `Element` ; `container`: `Container` ; `asFragment`: () => `DocumentFragment` ; `debug`: (`baseElement?`: `Element` \| `DocumentFragment` \| (`Element` \| `DocumentFragment`)[], `maxLength?`: `number`, `options?`: [`PrettyFormatOptions`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.PrettyFormatOptions.md)) => `void` ; `rerender`: (`ui`: [`ReactElement`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.md#jsxelementconstructor)<`any`\>\>) => `void` ; `unmount`: () => `void`  } & { [P in keyof Q]: BoundFunction<Q[P]\> }

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md) = typeof [`queries`](akashaproject_ui_awf_testing_utils.queries.md) |
| `Container` | extends `Element` \| `DocumentFragment` = `HTMLElement` |

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:14

___

### Screen

Ƭ **Screen**<`Q`\>: [`BoundFunctions`](akashaproject_ui_awf_testing_utils.md#boundfunctions)<`Q`\> & { `debug`: (`element?`: `Element` \| [`HTMLDocument`](akashaproject_ui_awf_testing_utils._internal_.md#htmldocument) \| (`Element` \| [`HTMLDocument`](akashaproject_ui_awf_testing_utils._internal_.md#htmldocument))[], `maxLength?`: `number`, `options?`: [`PrettyFormatOptions`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.PrettyFormatOptions.md)) => `void` ; `logTestingPlaygroundURL`: (`element?`: `Element` \| [`HTMLDocument`](akashaproject_ui_awf_testing_utils._internal_.md#htmldocument)) => `void`  }

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md) = typeof [`queries`](akashaproject_ui_awf_testing_utils.queries.md) |

#### Defined in

node_modules/@testing-library/dom/types/screen.d.ts:5

___

### Variant

Ƭ **Variant**: ``"find"`` \| ``"findAll"`` \| ``"get"`` \| ``"getAll"`` \| ``"query"`` \| ``"queryAll"``

#### Defined in

node_modules/@testing-library/dom/types/suggestions.d.ts:16

___

### WithSuggest

Ƭ **WithSuggest**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `suggest?` | `boolean` |

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:4

## Variables

### createEvent

• **createEvent**: [`CreateObject`](akashaproject_ui_awf_testing_utils.md#createobject) & [`CreateFunction`](akashaproject_ui_awf_testing_utils.md#createfunction)

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:113

___

### fireEvent

• **fireEvent**: [`FireFunction`](akashaproject_ui_awf_testing_utils.md#firefunction) & [`FireObject`](akashaproject_ui_awf_testing_utils.md#fireobject)

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:114

___

### globalChannelMock

• **globalChannelMock**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `pipe` | () => { `subscribe`: () => `void` ; `unsubscribe`: () => `void`  } |

#### Defined in

[ui/testing-utils/src/mocks/channels.ts:2](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/mocks/channels.ts#L2)

___

### screen

• **screen**: [`Screen`](akashaproject_ui_awf_testing_utils.md#screen)

#### Defined in

node_modules/@testing-library/dom/types/screen.d.ts:22

## Functions

### act

▸ `Const` **act**(`callback`): `Promise`<`undefined`\>

Simply calls ReactDOMTestUtils.act(cb)
If that's not available (older version of react) then it
simply calls the given callback immediately

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | () => `Promise`<`void`\> |

#### Returns

`Promise`<`undefined`\>

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:103

▸ `Const` **act**(`callback`): `void`

Simply calls ReactDOMTestUtils.act(cb)
If that's not available (older version of react) then it
simply calls the given callback immediately

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | () => [`VoidOrUndefinedOnly`](akashaproject_ui_awf_testing_utils._internal_.md#voidorundefinedonly) |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:103

___

### buildQueries

▸ **buildQueries**<`Arguments`\>(`queryAllBy`, `getMultipleError`, `getMissingError`): [`BuiltQueryMethods`](akashaproject_ui_awf_testing_utils.queryHelpers.md#builtquerymethods)<`Arguments`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Arguments` | extends `any`[] |

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryAllBy` | [`GetAllBy`](akashaproject_ui_awf_testing_utils.queryHelpers.md#getallby)<`Arguments`\> |
| `getMultipleError` | [`GetErrorFunction`](akashaproject_ui_awf_testing_utils.queryHelpers.md#geterrorfunction)<`Arguments`\> |
| `getMissingError` | [`GetErrorFunction`](akashaproject_ui_awf_testing_utils.queryHelpers.md#geterrorfunction)<`Arguments`\> |

#### Returns

[`BuiltQueryMethods`](akashaproject_ui_awf_testing_utils.queryHelpers.md#builtquerymethods)<`Arguments`\>

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:70

___

### cleanup

▸ **cleanup**(): `void`

Unmounts React trees that were mounted with render.

#### Returns

`void`

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:96

___

### computeHeadingLevel

▸ **computeHeadingLevel**(`element`): `number` \| `undefined`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `Element` |

#### Returns

`number` \| `undefined`

#### Defined in

node_modules/@testing-library/dom/types/role-helpers.d.ts:9

___

### configure

▸ **configure**(`configDelta`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `configDelta` | [`ConfigFn`](../interfaces/akashaproject_ui_awf_testing_utils.ConfigFn.md) \| [`Partial`](akashaproject_ui_awf_testing_utils._internal_.md#partial)<[`Config`](../interfaces/akashaproject_ui_awf_testing_utils.Config.md)\> |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:24

___

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

### genEthAddress

▸ `Const` **genEthAddress**(): `string`

#### Returns

`string`

#### Defined in

[ui/testing-utils/src/data-generator/user.ts:45](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/data-generator/user.ts#L45)

___

### genLoggedUser

▸ `Const` **genLoggedUser**(`ethAddress?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress?` | `string` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `avatar` | `string` |
| `coverImage` | `string` |
| `default` | { `property`: `string` = 'userName'; `provider`: `string` = 'ewa.providers.basic'; `value`: `string` = userName }[] |
| `description` | `string` |
| `ethAddress` | `string` |
| `name` | `string` |
| `providers` | { `property`: `string` = 'userName'; `provider`: `string` = 'ewa.providers.basic'; `value`: `string` = userName }[] |
| `pubKey` | `string` |
| `userName` | `string` |

#### Defined in

[ui/testing-utils/src/data-generator/user.ts:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/data-generator/user.ts#L17)

___

### genMockOp

▸ `Const` **genMockOp**(`payload?`): [`Mock`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `payload?` | [`Record`](akashaproject_ui_awf_testing_utils._internal_.md#record)<`string`, `unknown`\> |

#### Returns

[`Mock`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.Mock.md)<`any`, `any`\>

#### Defined in

[ui/testing-utils/src/mocks/operator.ts:1](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/mocks/operator.ts#L1)

___

### genPostData

▸ `Const` **genPostData**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `_id` | `string` |
| `author` | `Object` |
| `author.avatar` | `string` |
| `author.coverImage` | `string` |
| `author.default` | `any`[] |
| `author.description` | `string` |
| `author.ethAddress` | `string` |
| `author.name` | `string` |
| `author.providers` | `any`[] |
| `author.pubKey` | `string` |
| `author.totalFollowers` | `number` |
| `author.totalFollowing` | `number` |
| `author.totalPosts` | `string` |
| `author.userName` | `string` |
| `content` | ({ `children`: ({ `children`: `undefined` ; `text`: `string` = ''; `type`: `undefined` = 'text'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `text`: `undefined` = ' -\> test'; `type`: `string` = 'link'; `url`: `string` = 'https://google.com' } \| { `children`: `undefined` ; `text`: `string` = ' -\> test'; `type`: `string` = 'text'; `url`: `undefined` = 'https://google.com' })[] ; `size`: `undefined` ; `type`: `string` = 'paragraph'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `size`: { `height`: `number` = 426; `naturalHeight`: `number` = 426; `naturalWidth`: `number` = 640; `width`: `number` = 640 } ; `type`: `string` = 'image'; `url`: `string` = 'https://hub.textile.io/ipfs/bafkreidketqm2q5xuxvtezegtu7hchc2a6bdlazpxftdudczngkrht674i' })[] |
| `entryId` | `string` |
| `ipfsLink` | `string` |
| `quotedBy` | `any`[] |
| `quotedByAthors` | `any` |
| `quotes` | `any`[] |
| `tags` | `any`[] |
| `totalComments` | `number` |

#### Defined in

[ui/testing-utils/src/data-generator/post.ts:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/data-generator/post.ts#L13)

___

### genSlatePost

▸ `Const` **genSlatePost**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `content` | ({ `children`: ({ `children`: `undefined` ; `text`: `string` = ''; `type`: `undefined` = 'text'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `text`: `undefined` = ' -\> test'; `type`: `string` = 'link'; `url`: `string` = 'https://google.com' } \| { `children`: `undefined` ; `text`: `string` = ' -\> test'; `type`: `string` = 'text'; `url`: `undefined` = 'https://google.com' })[] ; `size`: `undefined` ; `type`: `string` = 'paragraph'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `size`: { `height`: `number` = 426; `naturalHeight`: `number` = 426; `naturalWidth`: `number` = 640; `width`: `number` = 640 } ; `type`: `string` = 'image'; `url`: `string` = 'https://hub.textile.io/ipfs/bafkreidketqm2q5xuxvtezegtu7hchc2a6bdlazpxftdudczngkrht674i' })[] |

#### Defined in

[ui/testing-utils/src/data-generator/post.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/data-generator/post.ts#L28)

___

### genUser

▸ `Const` **genUser**(`ethAddress?`, `userName?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ethAddress?` | `string` |
| `userName?` | `string` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `avatar` | `string` |
| `coverImage` | `string` |
| `default` | `any`[] |
| `description` | `string` |
| `ethAddress` | `string` |
| `name` | `string` |
| `providers` | `any`[] |
| `pubKey` | `string` |
| `userName` | `string` |

#### Defined in

[ui/testing-utils/src/data-generator/user.ts:3](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/data-generator/user.ts#L3)

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

### getConfig

▸ **getConfig**(): [`Config`](../interfaces/akashaproject_ui_awf_testing_utils.Config.md)

#### Returns

[`Config`](../interfaces/akashaproject_ui_awf_testing_utils.Config.md)

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:25

___

### getDefaultNormalizer

▸ **getDefaultNormalizer**(`options?`): [`NormalizerFn`](akashaproject_ui_awf_testing_utils.md#normalizerfn)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`DefaultNormalizerOptions`](../interfaces/akashaproject_ui_awf_testing_utils.DefaultNormalizerOptions.md) |

#### Returns

[`NormalizerFn`](akashaproject_ui_awf_testing_utils.md#normalizerfn)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:42

___

### getElementError

▸ **getElementError**(`message`, `container`): [`Error`](akashaproject_ui_awf_testing_utils._internal_.md#error)

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `container` | `HTMLElement` |

#### Returns

[`Error`](akashaproject_ui_awf_testing_utils._internal_.md#error)

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:32

___

### getNodeText

▸ **getNodeText**(`node`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `HTMLElement` |

#### Returns

`string`

#### Defined in

node_modules/@testing-library/dom/types/get-node-text.d.ts:1

___

### getQueriesForElement

▸ **getQueriesForElement**<`T`\>(`element`, `queriesToBind?`): [`BoundFunctions`](akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Queries`](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md) = [`queries`](akashaproject_ui_awf_testing_utils.queries.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `queriesToBind?` | `T` |

#### Returns

[`BoundFunctions`](akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:178

___

### getRoles

▸ **getRoles**(`container`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |

#### Returns

`Object`

#### Defined in

node_modules/@testing-library/dom/types/role-helpers.d.ts:2

___

### getSDKMocks

▸ `Const` **getSDKMocks**(`overrides`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `overrides` | [`ChannelOverrides`](../interfaces/akashaproject_ui_awf_testing_utils.ChannelOverrides.md) |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `auth` | `Object` |
| `auth.authService` | `Object` |
| `auth.authService.getCurrentUser` | () => `Observable`<`string`\> |
| `commons` | `Object` |
| `commons.ipfsService` | `Object` |
| `commons.ipfsService.getSettings` | () => `Observable`<`string`\> |
| `commons.web3Service` | `Object` |
| `commons.web3Service.checkCurrentNetwork` | () => `Observable`<`string`\> |
| `posts` | `Object` |
| `posts.tags` | `Object` |
| `posts.tags.getTrending` | () => `Observable`<`string`\> |
| `profiles` | `Object` |
| `profiles.profileService` | `Object` |
| `profiles.profileService.getTrending` | () => `Observable`<`string`\> |
| `profiles.profileService.isFollowing` | () => `Observable`<`string`\> |
| `registry` | `Object` |
| `registry.ens` | `Object` |
| `registry.ens.resolveAddress` | () => `Observable`<`string`\> |

#### Defined in

[ui/testing-utils/src/mocks/channels.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/mocks/channels.ts#L23)

___

### getSuggestedQuery

▸ **getSuggestedQuery**(`element`, `variant?`, `method?`): [`Suggestion`](../interfaces/akashaproject_ui_awf_testing_utils.Suggestion.md) \| `undefined`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `variant?` | [`Variant`](akashaproject_ui_awf_testing_utils.md#variant) |
| `method?` | [`Method`](akashaproject_ui_awf_testing_utils.md#method) |

#### Returns

[`Suggestion`](../interfaces/akashaproject_ui_awf_testing_utils.Suggestion.md) \| `undefined`

#### Defined in

node_modules/@testing-library/dom/types/suggestions.d.ts:42

___

### isInaccessible

▸ **isInaccessible**(`element`): `boolean`

https://testing-library.com/docs/dom-testing-library/api-helpers#isinaccessible

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `Element` |

#### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/role-helpers.d.ts:8

___

### logDOM

▸ **logDOM**(`dom?`, `maxLength?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dom?` | `Element` \| [`HTMLDocument`](akashaproject_ui_awf_testing_utils._internal_.md#htmldocument) |
| `maxLength?` | `number` |
| `options?` | [`PrettyDOMOptions`](../interfaces/akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/dom/types/pretty-dom.d.ts:16

___

### logRoles

▸ **logRoles**(`container`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |

#### Returns

`string`

#### Defined in

node_modules/@testing-library/dom/types/role-helpers.d.ts:1

___

### prettyDOM

▸ **prettyDOM**(`dom?`, `maxLength?`, `options?`): `string` \| ``false``

#### Parameters

| Name | Type |
| :------ | :------ |
| `dom?` | `Element` \| [`HTMLDocument`](akashaproject_ui_awf_testing_utils._internal_.md#htmldocument) |
| `maxLength?` | `number` |
| `options?` | [`PrettyDOMOptions`](../interfaces/akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md) |

#### Returns

`string` \| ``false``

#### Defined in

node_modules/@testing-library/dom/types/pretty-dom.d.ts:11

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

### queryAllByAttribute

▸ `Const` **queryAllByAttribute**(`attribute`, `container`, `id`, `options?`): `HTMLElement`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`[]

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:31

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

### queryByAttribute

▸ `Const` **queryByAttribute**(`attribute`, `container`, `id`, `options?`): `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `attribute` | `string` |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:30

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

___

### render

▸ **render**<`Q`, `Container`\>(`ui`, `options`): [`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<`Q`, `Container`\>

Render into a container which is appended to document.body. It should be used with cleanup.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md) = [`queries`](akashaproject_ui_awf_testing_utils.queries.md) |
| `Container` | extends `Element` \| `DocumentFragment` = `HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `ui` | [`ReactElement`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.md#jsxelementconstructor)<`any`\>\> |
| `options` | [`RenderOptions`](../interfaces/akashaproject_ui_awf_testing_utils.RenderOptions.md)<`Q`, `Container`\> |

#### Returns

[`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<`Q`, `Container`\>

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:81

▸ **render**(`ui`, `options?`): [`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ui` | [`ReactElement`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.md#jsxelementconstructor)<`any`\>\> |
| `options?` | [`Omit`](akashaproject_ui_awf_testing_utils._internal_.md#omit)<[`RenderOptions`](../interfaces/akashaproject_ui_awf_testing_utils.RenderOptions.md)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>, ``"queries"``\> |

#### Returns

[`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:88

___

### renderWithAllProviders

▸ `Const` **renderWithAllProviders**(`component`, `options`): [`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | [`ReactElement`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.md#jsxelementconstructor)<`any`\>\> |
| `options` | [`RenderOptions`](../interfaces/akashaproject_ui_awf_testing_utils.RenderOptions.md)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\> |

#### Returns

[`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Defined in

[ui/testing-utils/src/index.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/index.ts#L31)

___

### renderWithWrapper

▸ `Const` **renderWithWrapper**(`component`, `wrapper`, `options`): [`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | [`ReactElement`](../interfaces/akashaproject_ui_awf_testing_utils._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.md#jsxelementconstructor)<`any`\>\> |
| `wrapper` | [`ComponentType`](akashaproject_ui_awf_testing_utils._internal_.md#componenttype)<{}\> |
| `options` | [`RenderOptions`](../interfaces/akashaproject_ui_awf_testing_utils.RenderOptions.md)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\> |

#### Returns

[`RenderResult`](akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Defined in

[ui/testing-utils/src/index.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/testing-utils/src/index.ts#L22)

___

### waitFor

▸ **waitFor**<`T`\>(`callback`, `options?`): `Promise`<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | () => `T` \| `Promise`<`T`\> |
| `options?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

#### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/wait-for.d.ts:9

___

### waitForElementToBeRemoved

▸ **waitForElementToBeRemoved**<`T`\>(`callback`, `options?`): `Promise`<`void`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | `T` \| () => `T` |
| `options?` | [`waitForOptions`](../interfaces/akashaproject_ui_awf_testing_utils.waitForOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/@testing-library/dom/types/wait-for-element-to-be-removed.d.ts:3

___

### within

▸ `Const` **within**<`T`\>(`element`, `queriesToBind?`): [`BoundFunctions`](akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Queries`](../interfaces/akashaproject_ui_awf_testing_utils.Queries.md) = [`queries`](akashaproject_ui_awf_testing_utils.queries.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `queriesToBind?` | `T` |

#### Returns

[`BoundFunctions`](akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/index.d.ts:7
