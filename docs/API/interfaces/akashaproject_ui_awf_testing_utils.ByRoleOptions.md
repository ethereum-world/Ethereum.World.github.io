[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / ByRoleOptions

# Interface: ByRoleOptions

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).ByRoleOptions

## Hierarchy

- [`MatcherOptions`](akashaproject_ui_awf_testing_utils.MatcherOptions.md)

  ↳ **`ByRoleOptions`**

## Table of contents

### Properties

- [checked](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#checked)
- [collapseWhitespace](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#collapsewhitespace)
- [current](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#current)
- [exact](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#exact)
- [expanded](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#expanded)
- [hidden](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#hidden)
- [level](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#level)
- [name](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#name)
- [normalizer](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#normalizer)
- [pressed](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#pressed)
- [queryFallbacks](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#queryfallbacks)
- [selected](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#selected)
- [suggest](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#suggest)
- [trim](akashaproject_ui_awf_testing_utils.ByRoleOptions.md#trim)

## Properties

### checked

• `Optional` **checked**: `boolean`

If true only includes elements in the query set that are marked as
checked in the accessibility tree, i.e., `aria-checked="true"`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:85

___

### collapseWhitespace

• `Optional` **collapseWhitespace**: `boolean`

Use normalizer with getDefaultNormalizer instead

#### Inherited from

[MatcherOptions](akashaproject_ui_awf_testing_utils.MatcherOptions.md).[collapseWhitespace](akashaproject_ui_awf_testing_utils.MatcherOptions.md#collapsewhitespace)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:24

___

### current

• `Optional` **current**: `string` \| `boolean`

Filters elements by their `aria-current` state. `true` and `false` match `aria-current="true"` and `aria-current="false"` (as well as a missing `aria-current` attribute) respectively.

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:94

___

### exact

• `Optional` **exact**: `boolean`

#### Inherited from

[MatcherOptions](akashaproject_ui_awf_testing_utils.MatcherOptions.md).[exact](akashaproject_ui_awf_testing_utils.MatcherOptions.md#exact)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:20

___

### expanded

• `Optional` **expanded**: `boolean`

If true only includes elements in the query set that are marked as
expanded in the accessibility tree, i.e., `aria-expanded="true"`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:99

___

### hidden

• `Optional` **hidden**: `boolean`

If true includes elements in the query set that are usually excluded from
the accessibility tree. `role="none"` or `role="presentation"` are included
in either case.

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:75

___

### level

• `Optional` **level**: `number`

Includes elements with the `"heading"` role matching the indicated level,
either by the semantic HTML heading elements `<h1>-<h6>` or matching
the `aria-level` attribute.

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:105

___

### name

• `Optional` **name**: `string` \| `RegExp` \| (`accessibleName`: `string`, `element`: `Element`) => `boolean`

Only considers elements with the specified accessible name.

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:114

___

### normalizer

• `Optional` **normalizer**: [`NormalizerFn`](../modules/akashaproject_ui_awf_testing_utils.md#normalizerfn)

#### Inherited from

[MatcherOptions](akashaproject_ui_awf_testing_utils.MatcherOptions.md).[normalizer](akashaproject_ui_awf_testing_utils.MatcherOptions.md#normalizer)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:25

___

### pressed

• `Optional` **pressed**: `boolean`

If true only includes elements in the query set that are marked as
pressed in the accessibility tree, i.e., `aria-pressed="true"`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:90

___

### queryFallbacks

• `Optional` **queryFallbacks**: `boolean`

Includes every role used in the `role` attribute
For example *ByRole('progressbar', {queryFallbacks: true})` will find <div role="meter progressbar">`.

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:110

___

### selected

• `Optional` **selected**: `boolean`

If true only includes elements in the query set that are marked as
selected in the accessibility tree, i.e., `aria-selected="true"`

#### Defined in

node_modules/@testing-library/dom/types/queries.d.ts:80

___

### suggest

• `Optional` **suggest**: `boolean`

suppress suggestions for a specific query

#### Inherited from

[MatcherOptions](akashaproject_ui_awf_testing_utils.MatcherOptions.md).[suggest](akashaproject_ui_awf_testing_utils.MatcherOptions.md#suggest)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:27

___

### trim

• `Optional` **trim**: `boolean`

Use normalizer with getDefaultNormalizer instead

#### Inherited from

[MatcherOptions](akashaproject_ui_awf_testing_utils.MatcherOptions.md).[trim](akashaproject_ui_awf_testing_utils.MatcherOptions.md#trim)

#### Defined in

node_modules/@testing-library/dom/types/matches.d.ts:22
