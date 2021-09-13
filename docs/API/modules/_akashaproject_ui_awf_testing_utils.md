[AWF](../README.md) / [Exports](../modules.md) / @akashaproject/ui-awf-testing-utils

# Module: @akashaproject/ui-awf-testing-utils

## Table of contents

### Namespaces

- [prettyFormat](_akashaproject_ui_awf_testing_utils.prettyFormat.md)
- [queries](_akashaproject_ui_awf_testing_utils.queries.md)
- [queryHelpers](_akashaproject_ui_awf_testing_utils.queryHelpers.md)

### Interfaces

- [ByRoleOptions](../interfaces/_akashaproject_ui_awf_testing_utils.ByRoleOptions.md)
- [ChannelOverrides](../interfaces/_akashaproject_ui_awf_testing_utils.ChannelOverrides.md)
- [Config](../interfaces/_akashaproject_ui_awf_testing_utils.Config.md)
- [ConfigFn](../interfaces/_akashaproject_ui_awf_testing_utils.ConfigFn.md)
- [DefaultNormalizerOptions](../interfaces/_akashaproject_ui_awf_testing_utils.DefaultNormalizerOptions.md)
- [MatcherOptions](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)
- [NormalizerOptions](../interfaces/_akashaproject_ui_awf_testing_utils.NormalizerOptions.md)
- [PrettyDOMOptions](../interfaces/_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md)
- [Queries](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)
- [QueryOptions](../interfaces/_akashaproject_ui_awf_testing_utils.QueryOptions.md)
- [RenderOptions](../interfaces/_akashaproject_ui_awf_testing_utils.RenderOptions.md)
- [SelectorMatcherOptions](../interfaces/_akashaproject_ui_awf_testing_utils.SelectorMatcherOptions.md)
- [Suggestion](../interfaces/_akashaproject_ui_awf_testing_utils.Suggestion.md)
- [waitForOptions](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)

### Type aliases

- [AllByAttribute](_akashaproject_ui_awf_testing_utils.md#allbyattribute)
- [AllByBoundAttribute](_akashaproject_ui_awf_testing_utils.md#allbyboundattribute)
- [AllByRole](_akashaproject_ui_awf_testing_utils.md#allbyrole)
- [AllByText](_akashaproject_ui_awf_testing_utils.md#allbytext)
- [BoundFunction](_akashaproject_ui_awf_testing_utils.md#boundfunction)
- [BoundFunctions](_akashaproject_ui_awf_testing_utils.md#boundfunctions)
- [BuiltQueryMethods](_akashaproject_ui_awf_testing_utils.md#builtquerymethods)
- [ByRoleMatcher](_akashaproject_ui_awf_testing_utils.md#byrolematcher)
- [CreateFunction](_akashaproject_ui_awf_testing_utils.md#createfunction)
- [CreateObject](_akashaproject_ui_awf_testing_utils.md#createobject)
- [EventType](_akashaproject_ui_awf_testing_utils.md#eventtype)
- [FindAllBy](_akashaproject_ui_awf_testing_utils.md#findallby)
- [FindAllByBoundAttribute](_akashaproject_ui_awf_testing_utils.md#findallbyboundattribute)
- [FindAllByRole](_akashaproject_ui_awf_testing_utils.md#findallbyrole)
- [FindAllByText](_akashaproject_ui_awf_testing_utils.md#findallbytext)
- [FindBy](_akashaproject_ui_awf_testing_utils.md#findby)
- [FindByBoundAttribute](_akashaproject_ui_awf_testing_utils.md#findbyboundattribute)
- [FindByRole](_akashaproject_ui_awf_testing_utils.md#findbyrole)
- [FindByText](_akashaproject_ui_awf_testing_utils.md#findbytext)
- [FireFunction](_akashaproject_ui_awf_testing_utils.md#firefunction)
- [FireObject](_akashaproject_ui_awf_testing_utils.md#fireobject)
- [GetAllBy](_akashaproject_ui_awf_testing_utils.md#getallby)
- [GetBy](_akashaproject_ui_awf_testing_utils.md#getby)
- [GetByBoundAttribute](_akashaproject_ui_awf_testing_utils.md#getbyboundattribute)
- [GetByRole](_akashaproject_ui_awf_testing_utils.md#getbyrole)
- [GetByText](_akashaproject_ui_awf_testing_utils.md#getbytext)
- [GetErrorFunction](_akashaproject_ui_awf_testing_utils.md#geterrorfunction)
- [Match](_akashaproject_ui_awf_testing_utils.md#match)
- [Matcher](_akashaproject_ui_awf_testing_utils.md#matcher)
- [MatcherFunction](_akashaproject_ui_awf_testing_utils.md#matcherfunction)
- [Method](_akashaproject_ui_awf_testing_utils.md#method)
- [NormalizerFn](_akashaproject_ui_awf_testing_utils.md#normalizerfn)
- [Query](_akashaproject_ui_awf_testing_utils.md#query)
- [QueryArgs](_akashaproject_ui_awf_testing_utils.md#queryargs)
- [QueryBy](_akashaproject_ui_awf_testing_utils.md#queryby)
- [QueryByAttribute](_akashaproject_ui_awf_testing_utils.md#querybyattribute)
- [QueryByBoundAttribute](_akashaproject_ui_awf_testing_utils.md#querybyboundattribute)
- [QueryByRole](_akashaproject_ui_awf_testing_utils.md#querybyrole)
- [QueryByText](_akashaproject_ui_awf_testing_utils.md#querybytext)
- [QueryMethod](_akashaproject_ui_awf_testing_utils.md#querymethod)
- [RenderResult](_akashaproject_ui_awf_testing_utils.md#renderresult)
- [Screen](_akashaproject_ui_awf_testing_utils.md#screen)
- [Variant](_akashaproject_ui_awf_testing_utils.md#variant)
- [WithSuggest](_akashaproject_ui_awf_testing_utils.md#withsuggest)

### Variables

- [createEvent](_akashaproject_ui_awf_testing_utils.md#createevent)
- [fireEvent](_akashaproject_ui_awf_testing_utils.md#fireevent)
- [globalChannelMock](_akashaproject_ui_awf_testing_utils.md#globalchannelmock)
- [screen](_akashaproject_ui_awf_testing_utils.md#screen)

### Functions

- [act](_akashaproject_ui_awf_testing_utils.md#act)
- [buildQueries](_akashaproject_ui_awf_testing_utils.md#buildqueries)
- [cleanup](_akashaproject_ui_awf_testing_utils.md#cleanup)
- [computeHeadingLevel](_akashaproject_ui_awf_testing_utils.md#computeheadinglevel)
- [configure](_akashaproject_ui_awf_testing_utils.md#configure)
- [findAllByAltText](_akashaproject_ui_awf_testing_utils.md#findallbyalttext)
- [findAllByDisplayValue](_akashaproject_ui_awf_testing_utils.md#findallbydisplayvalue)
- [findAllByLabelText](_akashaproject_ui_awf_testing_utils.md#findallbylabeltext)
- [findAllByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#findallbyplaceholdertext)
- [findAllByRole](_akashaproject_ui_awf_testing_utils.md#findallbyrole)
- [findAllByTestId](_akashaproject_ui_awf_testing_utils.md#findallbytestid)
- [findAllByText](_akashaproject_ui_awf_testing_utils.md#findallbytext)
- [findAllByTitle](_akashaproject_ui_awf_testing_utils.md#findallbytitle)
- [findByAltText](_akashaproject_ui_awf_testing_utils.md#findbyalttext)
- [findByDisplayValue](_akashaproject_ui_awf_testing_utils.md#findbydisplayvalue)
- [findByLabelText](_akashaproject_ui_awf_testing_utils.md#findbylabeltext)
- [findByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#findbyplaceholdertext)
- [findByRole](_akashaproject_ui_awf_testing_utils.md#findbyrole)
- [findByTestId](_akashaproject_ui_awf_testing_utils.md#findbytestid)
- [findByText](_akashaproject_ui_awf_testing_utils.md#findbytext)
- [findByTitle](_akashaproject_ui_awf_testing_utils.md#findbytitle)
- [genEthAddress](_akashaproject_ui_awf_testing_utils.md#genethaddress)
- [genLoggedUser](_akashaproject_ui_awf_testing_utils.md#genloggeduser)
- [genMockOp](_akashaproject_ui_awf_testing_utils.md#genmockop)
- [genPostData](_akashaproject_ui_awf_testing_utils.md#genpostdata)
- [genSlatePost](_akashaproject_ui_awf_testing_utils.md#genslatepost)
- [genUser](_akashaproject_ui_awf_testing_utils.md#genuser)
- [getAllByAltText](_akashaproject_ui_awf_testing_utils.md#getallbyalttext)
- [getAllByDisplayValue](_akashaproject_ui_awf_testing_utils.md#getallbydisplayvalue)
- [getAllByLabelText](_akashaproject_ui_awf_testing_utils.md#getallbylabeltext)
- [getAllByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#getallbyplaceholdertext)
- [getAllByRole](_akashaproject_ui_awf_testing_utils.md#getallbyrole)
- [getAllByTestId](_akashaproject_ui_awf_testing_utils.md#getallbytestid)
- [getAllByText](_akashaproject_ui_awf_testing_utils.md#getallbytext)
- [getAllByTitle](_akashaproject_ui_awf_testing_utils.md#getallbytitle)
- [getByAltText](_akashaproject_ui_awf_testing_utils.md#getbyalttext)
- [getByDisplayValue](_akashaproject_ui_awf_testing_utils.md#getbydisplayvalue)
- [getByLabelText](_akashaproject_ui_awf_testing_utils.md#getbylabeltext)
- [getByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#getbyplaceholdertext)
- [getByRole](_akashaproject_ui_awf_testing_utils.md#getbyrole)
- [getByTestId](_akashaproject_ui_awf_testing_utils.md#getbytestid)
- [getByText](_akashaproject_ui_awf_testing_utils.md#getbytext)
- [getByTitle](_akashaproject_ui_awf_testing_utils.md#getbytitle)
- [getConfig](_akashaproject_ui_awf_testing_utils.md#getconfig)
- [getDefaultNormalizer](_akashaproject_ui_awf_testing_utils.md#getdefaultnormalizer)
- [getElementError](_akashaproject_ui_awf_testing_utils.md#getelementerror)
- [getNodeText](_akashaproject_ui_awf_testing_utils.md#getnodetext)
- [getQueriesForElement](_akashaproject_ui_awf_testing_utils.md#getqueriesforelement)
- [getRoles](_akashaproject_ui_awf_testing_utils.md#getroles)
- [getSDKMocks](_akashaproject_ui_awf_testing_utils.md#getsdkmocks)
- [getSuggestedQuery](_akashaproject_ui_awf_testing_utils.md#getsuggestedquery)
- [isInaccessible](_akashaproject_ui_awf_testing_utils.md#isinaccessible)
- [logDOM](_akashaproject_ui_awf_testing_utils.md#logdom)
- [logRoles](_akashaproject_ui_awf_testing_utils.md#logroles)
- [prettyDOM](_akashaproject_ui_awf_testing_utils.md#prettydom)
- [queryAllByAltText](_akashaproject_ui_awf_testing_utils.md#queryallbyalttext)
- [queryAllByAttribute](_akashaproject_ui_awf_testing_utils.md#queryallbyattribute)
- [queryAllByDisplayValue](_akashaproject_ui_awf_testing_utils.md#queryallbydisplayvalue)
- [queryAllByLabelText](_akashaproject_ui_awf_testing_utils.md#queryallbylabeltext)
- [queryAllByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#queryallbyplaceholdertext)
- [queryAllByRole](_akashaproject_ui_awf_testing_utils.md#queryallbyrole)
- [queryAllByTestId](_akashaproject_ui_awf_testing_utils.md#queryallbytestid)
- [queryAllByText](_akashaproject_ui_awf_testing_utils.md#queryallbytext)
- [queryAllByTitle](_akashaproject_ui_awf_testing_utils.md#queryallbytitle)
- [queryByAltText](_akashaproject_ui_awf_testing_utils.md#querybyalttext)
- [queryByAttribute](_akashaproject_ui_awf_testing_utils.md#querybyattribute)
- [queryByDisplayValue](_akashaproject_ui_awf_testing_utils.md#querybydisplayvalue)
- [queryByLabelText](_akashaproject_ui_awf_testing_utils.md#querybylabeltext)
- [queryByPlaceholderText](_akashaproject_ui_awf_testing_utils.md#querybyplaceholdertext)
- [queryByRole](_akashaproject_ui_awf_testing_utils.md#querybyrole)
- [queryByTestId](_akashaproject_ui_awf_testing_utils.md#querybytestid)
- [queryByText](_akashaproject_ui_awf_testing_utils.md#querybytext)
- [queryByTitle](_akashaproject_ui_awf_testing_utils.md#querybytitle)
- [render](_akashaproject_ui_awf_testing_utils.md#render)
- [renderWithAllProviders](_akashaproject_ui_awf_testing_utils.md#renderwithallproviders)
- [renderWithWrapper](_akashaproject_ui_awf_testing_utils.md#renderwithwrapper)
- [waitFor](_akashaproject_ui_awf_testing_utils.md#waitfor)
- [waitForElementToBeRemoved](_akashaproject_ui_awf_testing_utils.md#waitforelementtoberemoved)
- [within](_akashaproject_ui_awf_testing_utils.md#within)

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

### AllByBoundAttribute

Ƭ **AllByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:11

___

### AllByRole

Ƭ **AllByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:120

___

### AllByText

Ƭ **AllByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T`[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

##### Returns

`T`[]

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:43

___

### BoundFunction

Ƭ **BoundFunction**<`T`\>: `T` extends (`attribute`: `string`, `element`: `HTMLElement`, `text`: infer P, `options`: infer Q) => infer R ? (`text`: `P`, `options?`: `Q`) => `R` : `T` extends (`a1`: `any`, `text`: infer P, `options`: infer Q, `waitForElementOptions`: infer W) => infer R ? (`text`: `P`, `options?`: `Q`, `waitForElementOptions?`: `W`) => `R` : `T` extends (`a1`: `any`, `text`: infer P, `options`: infer Q) => infer R ? (`text`: `P`, `options?`: `Q`) => `R` : `never`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:3

___

### BoundFunctions

Ƭ **BoundFunctions**<`T`\>: { [P in keyof T]: BoundFunction<T[P]\>}

#### Type parameters

| Name |
| :------ |
| `T` |

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:20

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

### ByRoleMatcher

Ƭ **ByRoleMatcher**: `ARIARole` \| [`MatcherFunction`](_akashaproject_ui_awf_testing_utils.md#matcherfunction) \| {}

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:11

___

### CreateFunction

Ƭ **CreateFunction**: (`eventName`: `string`, `node`: `Document` \| `Element` \| `Window` \| `Node`, `init?`: {}, `options?`: { `EventType?`: `string` ; `defaultInit?`: {}  }) => `Event`

#### Type declaration

▸ (`eventName`, `node`, `init?`, `options?`): `Event`

##### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` |
| `node` | `Document` \| `Element` \| `Window` \| `Node` |
| `init?` | `Object` |
| `options?` | `Object` |
| `options.EventType?` | `string` |
| `options.defaultInit?` | `Object` |

##### Returns

`Event`

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:97

___

### CreateObject

Ƭ **CreateObject**: { [K in EventType]: function}

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:103

___

### EventType

Ƭ **EventType**: ``"copy"`` \| ``"cut"`` \| ``"paste"`` \| ``"compositionEnd"`` \| ``"compositionStart"`` \| ``"compositionUpdate"`` \| ``"keyDown"`` \| ``"keyPress"`` \| ``"keyUp"`` \| ``"focus"`` \| ``"blur"`` \| ``"focusIn"`` \| ``"focusOut"`` \| ``"change"`` \| ``"input"`` \| ``"invalid"`` \| ``"submit"`` \| ``"reset"`` \| ``"click"`` \| ``"contextMenu"`` \| ``"dblClick"`` \| ``"drag"`` \| ``"dragEnd"`` \| ``"dragEnter"`` \| ``"dragExit"`` \| ``"dragLeave"`` \| ``"dragOver"`` \| ``"dragStart"`` \| ``"drop"`` \| ``"mouseDown"`` \| ``"mouseEnter"`` \| ``"mouseLeave"`` \| ``"mouseMove"`` \| ``"mouseOut"`` \| ``"mouseOver"`` \| ``"mouseUp"`` \| ``"popState"`` \| ``"select"`` \| ``"touchCancel"`` \| ``"touchEnd"`` \| ``"touchMove"`` \| ``"touchStart"`` \| ``"resize"`` \| ``"scroll"`` \| ``"wheel"`` \| ``"abort"`` \| ``"canPlay"`` \| ``"canPlayThrough"`` \| ``"durationChange"`` \| ``"emptied"`` \| ``"encrypted"`` \| ``"ended"`` \| ``"loadedData"`` \| ``"loadedMetadata"`` \| ``"loadStart"`` \| ``"pause"`` \| ``"play"`` \| ``"playing"`` \| ``"progress"`` \| ``"rateChange"`` \| ``"seeked"`` \| ``"seeking"`` \| ``"stalled"`` \| ``"suspend"`` \| ``"timeUpdate"`` \| ``"volumeChange"`` \| ``"waiting"`` \| ``"load"`` \| ``"error"`` \| ``"animationStart"`` \| ``"animationEnd"`` \| ``"animationIteration"`` \| ``"transitionEnd"`` \| ``"doubleClick"`` \| ``"pointerOver"`` \| ``"pointerEnter"`` \| ``"pointerDown"`` \| ``"pointerMove"`` \| ``"pointerUp"`` \| ``"pointerCancel"`` \| ``"pointerOut"`` \| ``"pointerLeave"`` \| ``"gotPointerCapture"`` \| ``"lostPointerCapture"``

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:1

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

### FindAllByBoundAttribute

Ƭ **FindAllByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:17

___

### FindAllByRole

Ƭ **FindAllByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:145

___

### FindAllByText

Ƭ **FindAllByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`[]\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`[]\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`[]\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:49

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

### FindByBoundAttribute

Ƭ **FindByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:30

___

### FindByRole

Ƭ **FindByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:138

___

### FindByText

Ƭ **FindByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md), `waitForElementOptions?`: [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md)) => `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`, `waitForElementOptions?`): `Promise`<`T`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |
| `waitForElementOptions?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

##### Returns

`Promise`<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:62

___

### FireFunction

Ƭ **FireFunction**: (`element`: `Document` \| `Element` \| `Window` \| `Node`, `event`: `Event`) => `boolean`

#### Type declaration

▸ (`element`, `event`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `Document` \| `Element` \| `Window` \| `Node` |
| `event` | `Event` |

##### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:87

___

### FireObject

Ƭ **FireObject**: { [K in EventType]: function}

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:91

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

### GetByBoundAttribute

Ƭ **GetByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:24

___

### GetByRole

Ƭ **GetByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:126

___

### GetByText

Ƭ **GetByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

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

### Match

Ƭ **Match**: (`textToMatch`: `string`, `node`: `HTMLElement` \| ``null``, `matcher`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `boolean`

#### Type declaration

▸ (`textToMatch`, `node`, `matcher`, `options?`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `textToMatch` | `string` |
| `node` | `HTMLElement` \| ``null`` |
| `matcher` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`boolean`

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:30

___

### Matcher

Ƭ **Matcher**: [`MatcherFunction`](_akashaproject_ui_awf_testing_utils.md#matcherfunction) \| `RegExp` \| `number` \| `string`

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

Ƭ **Query**: (`container`: `HTMLElement`, ...`args`: `any`[]) => `Error` \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

#### Type declaration

▸ (`container`, ...`args`): `Error` \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `...args` | `any`[] |

##### Returns

`Error` \| `HTMLElement` \| `HTMLElement`[] \| `Promise`<`HTMLElement`[]\> \| `Promise`<`HTMLElement`\> \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:22

___

### QueryArgs

Ƭ **QueryArgs**: [`string`, QueryOptions?]

#### Defined in

node_modules/@testing-library/dom/types/suggestions.d.ts:5

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

### QueryByBoundAttribute

Ƭ **QueryByBoundAttribute**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

##### Returns

`T` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:5

___

### QueryByRole

Ƭ **QueryByRole**<`T`\>: (`container`: `HTMLElement`, `role`: [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher), `options?`: [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `role`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `role` | [`ByRoleMatcher`](_akashaproject_ui_awf_testing_utils.md#byrolematcher) |
| `options?` | [`ByRoleOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queries.ByRoleOptions.md) |

##### Returns

`T` \| ``null``

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:132

___

### QueryByText

Ƭ **QueryByText**<`T`\>: (`container`: `HTMLElement`, `id`: [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher), `options?`: [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md)) => `T` \| ``null``

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Type declaration

▸ (`container`, `id`, `options?`): `T` \| ``null``

##### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `HTMLElement` |
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`SelectorMatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.queryHelpers.SelectorMatcherOptions.md) |

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

Ƭ **RenderResult**<`Q`, `Container`\>: { `baseElement`: `Element` ; `container`: `Container` ; `asFragment`: () => `DocumentFragment` ; `debug`: (`baseElement?`: `Element` \| `DocumentFragment` \| (`Element` \| `DocumentFragment`)[], `maxLength?`: `number`, `options?`: `PrettyFormatOptions`) => `void` ; `rerender`: (`ui`: `ReactElement`<`any`, `string` \| `JSXElementConstructor`<`any`\>\>) => `void` ; `unmount`: () => `void`  } & { [P in keyof Q]: BoundFunction<Q[P]\>}

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)typeof [`queries`](_akashaproject_ui_awf_testing_utils.queries.md) |
| `Container` | extends `Element` \| `DocumentFragment``HTMLElement` |

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:14

___

### Screen

Ƭ **Screen**<`Q`\>: [`BoundFunctions`](_akashaproject_ui_awf_testing_utils.md#boundfunctions)<`Q`\> & { `debug`: (`element?`: `Element` \| `HTMLDocument` \| (`Element` \| `HTMLDocument`)[], `maxLength?`: `number`, `options?`: `PrettyFormatOptions`) => `void` ; `logTestingPlaygroundURL`: (`element?`: `Element` \| `HTMLDocument`) => `void`  }

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)typeof [`queries`](_akashaproject_ui_awf_testing_utils.queries.md) |

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

• `Const` **createEvent**: [`CreateObject`](_akashaproject_ui_awf_testing_utils.md#createobject) & [`CreateFunction`](_akashaproject_ui_awf_testing_utils.md#createfunction)

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:110

___

### fireEvent

• `Const` **fireEvent**: [`FireFunction`](_akashaproject_ui_awf_testing_utils.md#firefunction) & [`FireObject`](_akashaproject_ui_awf_testing_utils.md#fireobject)

#### Defined in

node_modules/@testing-library/dom/types/events.d.ts:111

___

### globalChannelMock

• `Const` **globalChannelMock**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `pipe` | () => { `subscribe`: () => `void` ; `unsubscribe`: () => `void`  } |

#### Defined in

[ui/testing-utils/src/mocks/channels.ts:2](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/mocks/channels.ts#L2)

___

### screen

• `Const` **screen**: [`Screen`](_akashaproject_ui_awf_testing_utils.md#screen)

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

node_modules/@testing-library/react/types/index.d.ts:71

▸ `Const` **act**(`callback`): `void`

Simply calls ReactDOMTestUtils.act(cb)
If that's not available (older version of react) then it
simply calls the given callback immediately

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | () => `VoidOrUndefinedOnly` |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:71

___

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

### cleanup

▸ **cleanup**(): `void`

Unmounts React trees that were mounted with render.

#### Returns

`void`

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:64

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
| `configDelta` | [`ConfigFn`](../interfaces/_akashaproject_ui_awf_testing_utils.ConfigFn.md) \| `Partial`<[`Config`](../interfaces/_akashaproject_ui_awf_testing_utils.Config.md)\> |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:24

___

### findAllByAltText

▸ **findAllByAltText**<`T`\>(...`args`): `ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:221

___

### findAllByDisplayValue

▸ **findAllByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:257

___

### findAllByLabelText

▸ **findAllByLabelText**<`T`\>(...`args`): `ReturnType`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:167

___

### findAllByPlaceholderText

▸ **findAllByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:185

___

### findAllByRole

▸ **findAllByRole**<`T`\>(...`args`): `ReturnType`<[`FindAllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:275

___

### findAllByTestId

▸ **findAllByTestId**<`T`\>(...`args`): `ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:293

___

### findAllByText

▸ **findAllByText**<`T`\>(...`args`): `ReturnType`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByText`](_akashaproject_ui_awf_testing_utils.queries.md#findallbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:203

___

### findAllByTitle

▸ **findAllByTitle**<`T`\>(...`args`): `ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindAllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findallbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:239

___

### findByAltText

▸ **findByAltText**<`T`\>(...`args`): `ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:218

___

### findByDisplayValue

▸ **findByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:254

___

### findByLabelText

▸ **findByLabelText**<`T`\>(...`args`): `ReturnType`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:164

___

### findByPlaceholderText

▸ **findByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:182

___

### findByRole

▸ **findByRole**<`T`\>(...`args`): `ReturnType`<[`FindByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findbyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByRole`](_akashaproject_ui_awf_testing_utils.queries.md#findbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:272

___

### findByTestId

▸ **findByTestId**<`T`\>(...`args`): `ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:290

___

### findByText

▸ **findByText**<`T`\>(...`args`): `ReturnType`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByText`](_akashaproject_ui_awf_testing_utils.queries.md#findbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:200

___

### findByTitle

▸ **findByTitle**<`T`\>(...`args`): `ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`FindByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#findbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:236

___

### genEthAddress

▸ `Const` **genEthAddress**(): `string`

#### Returns

`string`

#### Defined in

[ui/testing-utils/src/data-generator/user.ts:45](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/data-generator/user.ts#L45)

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
| `default` | { `property`: `string` = 'userName'; `provider`: `string` = 'ewa.providers.basic'; `value`: `string`  }[] |
| `description` | `string` |
| `ethAddress` | `string` |
| `name` | `string` |
| `providers` | { `property`: `string` = 'userName'; `provider`: `string` = 'ewa.providers.basic'; `value`: `string`  }[] |
| `pubKey` | `string` |
| `userName` | `string` |

#### Defined in

[ui/testing-utils/src/data-generator/user.ts:17](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/data-generator/user.ts#L17)

___

### genMockOp

▸ `Const` **genMockOp**(`payload?`): `Mock`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `payload?` | `Record`<`string`, `unknown`\> |

#### Returns

`Mock`<`any`, `any`\>

#### Defined in

[ui/testing-utils/src/mocks/operator.ts:1](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/mocks/operator.ts#L1)

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

[ui/testing-utils/src/data-generator/post.ts:13](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/data-generator/post.ts#L13)

___

### genSlatePost

▸ `Const` **genSlatePost**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `content` | ({ `children`: ({ `children`: `undefined` ; `text`: `string` = ''; `type`: `undefined` = 'text'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `text`: `undefined` = ' -\> test'; `type`: `string` = 'link'; `url`: `string` = 'https://google.com' } \| { `children`: `undefined` ; `text`: `string` = ' -\> test'; `type`: `string` = 'text'; `url`: `undefined` = 'https://google.com' })[] ; `size`: `undefined` ; `type`: `string` = 'paragraph'; `url`: `undefined` = 'https://google.com' } \| { `children`: { `text`: `string` = '' }[] ; `size`: { `height`: `number` = 426; `naturalHeight`: `number` = 426; `naturalWidth`: `number` = 640; `width`: `number` = 640 } ; `type`: `string` = 'image'; `url`: `string` = 'https://hub.textile.io/ipfs/bafkreidketqm2q5xuxvtezegtu7hchc2a6bdlazpxftdudczngkrht674i' })[] |

#### Defined in

[ui/testing-utils/src/data-generator/post.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/data-generator/post.ts#L28)

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

[ui/testing-utils/src/data-generator/user.ts:3](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/data-generator/user.ts#L3)

___

### getAllByAltText

▸ **getAllByAltText**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:209

___

### getAllByDisplayValue

▸ **getAllByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:245

___

### getAllByLabelText

▸ **getAllByLabelText**<`T`\>(...`args`): `ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:155

___

### getAllByPlaceholderText

▸ **getAllByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:173

___

### getAllByRole

▸ **getAllByRole**<`T`\>(...`args`): `ReturnType`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:263

___

### getAllByTestId

▸ **getAllByTestId**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:281

___

### getAllByText

▸ **getAllByText**<`T`\>(...`args`): `ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:191

___

### getAllByTitle

▸ **getAllByTitle**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:227

___

### getByAltText

▸ **getByAltText**<`T`\>(...`args`): `ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:206

___

### getByDisplayValue

▸ **getByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:242

___

### getByLabelText

▸ **getByLabelText**<`T`\>(...`args`): `ReturnType`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:152

___

### getByPlaceholderText

▸ **getByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:170

___

### getByRole

▸ **getByRole**<`T`\>(...`args`): `ReturnType`<[`GetByRole`](_akashaproject_ui_awf_testing_utils.queries.md#getbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByRole`](_akashaproject_ui_awf_testing_utils.queries.md#getbyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByRole`](_akashaproject_ui_awf_testing_utils.queries.md#getbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:260

___

### getByTestId

▸ **getByTestId**<`T`\>(...`args`): `ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:278

___

### getByText

▸ **getByText**<`T`\>(...`args`): `ReturnType`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByText`](_akashaproject_ui_awf_testing_utils.queries.md#getbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:188

___

### getByTitle

▸ **getByTitle**<`T`\>(...`args`): `ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`GetByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#getbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:224

___

### getConfig

▸ **getConfig**(): [`Config`](../interfaces/_akashaproject_ui_awf_testing_utils.Config.md)

#### Returns

[`Config`](../interfaces/_akashaproject_ui_awf_testing_utils.Config.md)

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:25

___

### getDefaultNormalizer

▸ **getDefaultNormalizer**(`options?`): [`NormalizerFn`](_akashaproject_ui_awf_testing_utils.md#normalizerfn)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`DefaultNormalizerOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.DefaultNormalizerOptions.md) |

#### Returns

[`NormalizerFn`](_akashaproject_ui_awf_testing_utils.md#normalizerfn)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:42

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

▸ **getQueriesForElement**<`T`\>(`element`, `queriesToBind?`): [`BoundFunctions`](_akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Queries`](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)[`queries`](_akashaproject_ui_awf_testing_utils.queries.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `queriesToBind?` | `T` |

#### Returns

[`BoundFunctions`](_akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/get-queries-for-element.d.ts:37

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
| `overrides` | [`ChannelOverrides`](../interfaces/_akashaproject_ui_awf_testing_utils.ChannelOverrides.md) |

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

[ui/testing-utils/src/mocks/channels.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/mocks/channels.ts#L23)

___

### getSuggestedQuery

▸ **getSuggestedQuery**(`element`, `variant?`, `method?`): [`Suggestion`](../interfaces/_akashaproject_ui_awf_testing_utils.Suggestion.md) \| `undefined`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `variant?` | [`Variant`](_akashaproject_ui_awf_testing_utils.md#variant) |
| `method?` | [`Method`](_akashaproject_ui_awf_testing_utils.md#method) |

#### Returns

[`Suggestion`](../interfaces/_akashaproject_ui_awf_testing_utils.Suggestion.md) \| `undefined`

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
| `dom?` | `Element` \| `HTMLDocument` |
| `maxLength?` | `number` |
| `options?` | [`PrettyDOMOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md) |

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
| `dom?` | `Element` \| `HTMLDocument` |
| `maxLength?` | `number` |
| `options?` | [`PrettyDOMOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.PrettyDOMOptions.md) |

#### Returns

`string` \| ``false``

#### Defined in

node_modules/@testing-library/dom/types/pretty-dom.d.ts:11

___

### queryAllByAltText

▸ **queryAllByAltText**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

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
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`[]

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:31

___

### queryAllByDisplayValue

▸ **queryAllByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:251

___

### queryAllByLabelText

▸ **queryAllByLabelText**<`T`\>(...`args`): `ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:161

___

### queryAllByPlaceholderText

▸ **queryAllByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:179

___

### queryAllByRole

▸ **queryAllByRole**<`T`\>(...`args`): `ReturnType`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByRole`](_akashaproject_ui_awf_testing_utils.queries.md#allbyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:269

___

### queryAllByTestId

▸ **queryAllByTestId**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:287

___

### queryAllByText

▸ **queryAllByText**<`T`\>(...`args`): `ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByText`](_akashaproject_ui_awf_testing_utils.queries.md#allbytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:197

___

### queryAllByTitle

▸ **queryAllByTitle**<`T`\>(...`args`): `ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`AllByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#allbyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:233

___

### queryByAltText

▸ **queryByAltText**<`T`\>(...`args`): `ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

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
| `id` | [`Matcher`](_akashaproject_ui_awf_testing_utils.md#matcher) |
| `options?` | [`MatcherOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.MatcherOptions.md) |

#### Returns

`HTMLElement`

#### Defined in

node_modules/@testing-library/dom/types/query-helpers.d.ts:30

___

### queryByDisplayValue

▸ **queryByDisplayValue**<`T`\>(...`args`): `ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:248

___

### queryByLabelText

▸ **queryByLabelText**<`T`\>(...`args`): `ReturnType`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:158

___

### queryByPlaceholderText

▸ **queryByPlaceholderText**<`T`\>(...`args`): `ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:176

___

### queryByRole

▸ **queryByRole**<`T`\>(...`args`): `ReturnType`<[`QueryByRole`](_akashaproject_ui_awf_testing_utils.queries.md#querybyrole)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByRole`](_akashaproject_ui_awf_testing_utils.queries.md#querybyrole)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByRole`](_akashaproject_ui_awf_testing_utils.queries.md#querybyrole)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:266

___

### queryByTestId

▸ **queryByTestId**<`T`\>(...`args`): `ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:284

___

### queryByText

▸ **queryByText**<`T`\>(...`args`): `ReturnType`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByText`](_akashaproject_ui_awf_testing_utils.queries.md#querybytext)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:194

___

### queryByTitle

▸ **queryByTitle**<`T`\>(...`args`): `ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `HTMLElement``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `Parameters`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\> |

#### Returns

`ReturnType`<[`QueryByBoundAttribute`](_akashaproject_ui_awf_testing_utils.queries.md#querybyboundattribute)<`T`\>\>

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:230

___

### render

▸ **render**<`Q`, `Container`\>(`ui`, `options`): [`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<`Q`, `Container`\>

Render into a container which is appended to document.body. It should be used with cleanup.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)[`queries`](_akashaproject_ui_awf_testing_utils.queries.md) |
| `Container` | extends `Element` \| `DocumentFragment``HTMLElement` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `ui` | `React.ReactElement` |
| `options` | [`RenderOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.RenderOptions.md)<`Q`, `Container`\> |

#### Returns

[`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<`Q`, `Container`\>

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:49

▸ **render**(`ui`, `options?`): [`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ui` | `React.ReactElement` |
| `options?` | `Omit`<[`RenderOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.RenderOptions.md), ``"queries"``\> |

#### Returns

[`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:56

___

### renderWithAllProviders

▸ `Const` **renderWithAllProviders**(`component`, `options`): [`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | `ReactElement`<`any`, `string` \| `JSXElementConstructor`<`any`\>\> |
| `options` | [`RenderOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.RenderOptions.md)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\> |

#### Returns

[`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Defined in

[ui/testing-utils/src/index.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/index.ts#L31)

___

### renderWithWrapper

▸ `Const` **renderWithWrapper**(`component`, `wrapper`, `options`): [`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | `ReactElement`<`any`, `string` \| `JSXElementConstructor`<`any`\>\> |
| `wrapper` | `ComponentType`<`Object`\> |
| `options` | [`RenderOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.RenderOptions.md)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\> |

#### Returns

[`RenderResult`](_akashaproject_ui_awf_testing_utils.md#renderresult)<[`queries`](_akashaproject_ui_awf_testing_utils.queries.md), `HTMLElement`\>

#### Defined in

[ui/testing-utils/src/index.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/testing-utils/src/index.ts#L22)

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
| `callback` | () => `Promise`<`T`\> \| `T` |
| `options?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

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
| `options?` | [`waitForOptions`](../interfaces/_akashaproject_ui_awf_testing_utils.waitForOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/@testing-library/dom/types/wait-for-element-to-be-removed.d.ts:3

___

### within

▸ `Const` **within**<`T`\>(`element`, `queriesToBind?`): [`BoundFunctions`](_akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Queries`](../interfaces/_akashaproject_ui_awf_testing_utils.Queries.md)[`queries`](_akashaproject_ui_awf_testing_utils.queries.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `HTMLElement` |
| `queriesToBind?` | `T` |

#### Returns

[`BoundFunctions`](_akashaproject_ui_awf_testing_utils.md#boundfunctions)<`T`\>

#### Defined in

node_modules/@testing-library/dom/types/index.d.ts:7
