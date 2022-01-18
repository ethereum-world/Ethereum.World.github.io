[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / VendorShorthandPropertiesFallback

# Interface: VendorShorthandPropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).VendorShorthandPropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- **`VendorShorthandPropertiesFallback`**

  ↳ [`VendorPropertiesFallback`](akashaproject_design_system._internal_.VendorPropertiesFallback.md)

## Table of contents

### Properties

- [MozAnimation](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozanimation)
- [MozBorderImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozborderimage)
- [MozColumnRule](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozcolumnrule)
- [MozColumns](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozcolumns)
- [MozTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#moztransition)
- [WebkitAnimation](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitanimation)
- [WebkitBorderBefore](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderbefore)
- [WebkitBorderImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderimage)
- [WebkitBorderRadius](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderradius)
- [WebkitColumnRule](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitcolumnrule)
- [WebkitColumns](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitcolumns)
- [WebkitFlex](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitflex)
- [WebkitFlexFlow](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitflexflow)
- [WebkitMask](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitmask)
- [WebkitMaskBoxImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitmaskboximage)
- [WebkitTextEmphasis](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittextemphasis)
- [WebkitTextStroke](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittextstroke)
- [WebkitTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittransition)
- [msContentZoomLimit](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mscontentzoomlimit)
- [msContentZoomSnap](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mscontentzoomsnap)
- [msFlex](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msflex)
- [msScrollLimit](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrolllimit)
- [msScrollSnapX](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrollsnapx)
- [msScrollSnapY](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrollsnapy)
- [msTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mstransition)

## Properties

### MozAnimation

• `Optional` **MozAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25147

___

### MozBorderImage

• `Optional` **MozBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25153

___

### MozColumnRule

• `Optional` **MozColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25159

___

### MozColumns

• `Optional` **MozColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25165

___

### MozTransition

• `Optional` **MozTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25171

___

### WebkitAnimation

• `Optional` **WebkitAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25219

___

### WebkitBorderBefore

• `Optional` **WebkitBorderBefore**: [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\> \| [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\>[]

The **`-webkit-border-before`** CSS property is a shorthand property for setting the individual logical block start border property values in a single place in the style sheet.

**Syntax**: `<'border-width'> || <'border-style'> || <color>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25225

___

### WebkitBorderImage

• `Optional` **WebkitBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25231

___

### WebkitBorderRadius

• `Optional` **WebkitBorderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25237

___

### WebkitColumnRule

• `Optional` **WebkitColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25243

___

### WebkitColumns

• `Optional` **WebkitColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25249

___

### WebkitFlex

• `Optional` **WebkitFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25255

___

### WebkitFlexFlow

• `Optional` **WebkitFlexFlow**: `string` \| `string`[]

The **`flex-flow`** CSS property is a shorthand property for `flex-direction` and `flex-wrap` properties.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25261

___

### WebkitMask

• `Optional` **WebkitMask**: [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\> \| [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\>[]

The **`mask`** CSS property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `[ <mask-reference> || <position> [ / <bg-size> ]? || <repeat-style> || [ <box> | border | padding | content | text ] || [ <box> | border | padding | content ] ]#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25267

___

### WebkitMaskBoxImage

• `Optional` **WebkitMaskBoxImage**: [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty) \| [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty)[]

The **`mask-border`** CSS property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25273

___

### WebkitTextEmphasis

• `Optional` **WebkitTextEmphasis**: `string` \| `string`[]

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25279

___

### WebkitTextStroke

• `Optional` **WebkitTextStroke**: [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\> \| [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\>[]

The **`-webkit-text-stroke`** CSS property specifies the width and color of strokes for text characters. This is a shorthand property for the longhand properties `-webkit-text-stroke-width` and `-webkit-text-stroke-color`.

**Syntax**: `<length> || <color>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25285

___

### WebkitTransition

• `Optional` **WebkitTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25291

___

### msContentZoomLimit

• `Optional` **msContentZoomLimit**: `string` \| `string`[]

The **`-ms-content-zoom-limit`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-limit-min` and `-ms-content-zoom-limit-max` properties.

**Syntax**: `<'-ms-content-zoom-limit-min'> <'-ms-content-zoom-limit-max'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25177

___

### msContentZoomSnap

• `Optional` **msContentZoomSnap**: `string` \| `string`[]

The **`-ms-content-zoom-snap`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-snap-type` and `-ms-content-zoom-snap-points` properties.

**Syntax**: `<'-ms-content-zoom-snap-type'> || <'-ms-content-zoom-snap-points'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25183

___

### msFlex

• `Optional` **msFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25189

___

### msScrollLimit

• `Optional` **msScrollLimit**: `string` \| `string`[]

The **\-ms-scroll-limit** CSS property is a Microsoft extension that specifies values for the `-ms-scroll-limit-x-min`, `-ms-scroll-limit-y-min`, `-ms-scroll-limit-x-max`, and `-ms-scroll-limit-y-max` properties.

**Syntax**: `<'-ms-scroll-limit-x-min'> <'-ms-scroll-limit-y-min'> <'-ms-scroll-limit-x-max'> <'-ms-scroll-limit-y-max'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25195

___

### msScrollSnapX

• `Optional` **msScrollSnapX**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-x` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-x'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25201

___

### msScrollSnapY

• `Optional` **msScrollSnapY**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-y` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-y'>`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25207

___

### msTransition

• `Optional` **msTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25213
