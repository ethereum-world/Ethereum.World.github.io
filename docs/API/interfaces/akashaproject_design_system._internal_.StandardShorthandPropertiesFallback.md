[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / StandardShorthandPropertiesFallback

# Interface: StandardShorthandPropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).StandardShorthandPropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- **`StandardShorthandPropertiesFallback`**

  ↳ [`StandardPropertiesFallback`](akashaproject_design_system._internal_.StandardPropertiesFallback.md)

## Table of contents

### Properties

- [all](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#all)
- [animation](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#animation)
- [background](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#background)
- [backgroundPosition](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#backgroundposition)
- [border](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#border)
- [borderBlock](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderblock)
- [borderBlockEnd](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderblockend)
- [borderBlockStart](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderblockstart)
- [borderBottom](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderbottom)
- [borderColor](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#bordercolor)
- [borderImage](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderimage)
- [borderInline](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderinline)
- [borderInlineEnd](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderinlineend)
- [borderInlineStart](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderinlinestart)
- [borderLeft](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderleft)
- [borderRadius](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderradius)
- [borderRight](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderright)
- [borderStyle](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderstyle)
- [borderTop](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#bordertop)
- [borderWidth](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#borderwidth)
- [columnRule](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#columnrule)
- [columns](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#columns)
- [flex](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#flex)
- [flexFlow](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#flexflow)
- [font](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#font)
- [gap](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#gap)
- [grid](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#grid)
- [gridArea](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#gridarea)
- [gridColumn](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#gridcolumn)
- [gridRow](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#gridrow)
- [gridTemplate](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#gridtemplate)
- [lineClamp](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#lineclamp)
- [listStyle](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#liststyle)
- [margin](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#margin)
- [mask](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#mask)
- [maskBorder](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#maskborder)
- [motion](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#motion)
- [offset](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#offset)
- [outline](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#outline)
- [overflow](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#overflow)
- [overscrollBehavior](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#overscrollbehavior)
- [padding](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#padding)
- [placeItems](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#placeitems)
- [placeSelf](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#placeself)
- [textDecoration](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#textdecoration)
- [textEmphasis](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#textemphasis)
- [transition](akashaproject_design_system._internal_.StandardShorthandPropertiesFallback.md#transition)

## Properties

### all

• `Optional` **all**: [`Globals`](../modules/akashaproject_design_system._internal_.md#globals) \| [`Globals`](../modules/akashaproject_design_system._internal_.md#globals)[]

The `**all**` CSS shorthand property sets all of an element's properties (other than `unicode-bidi` and `direction`) to their initial or inherited values, or to the values specified in another stylesheet origin.

**Syntax**: `initial | inherit | unset | revert`

**Initial value**: There is no practical initial value for it.

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **37** | **27**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/all

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22756

___

### animation

• `Optional` **animation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22769

___

### background

• `Optional` **background**: [`BackgroundProperty`](../modules/akashaproject_design_system._internal_.md#backgroundproperty)<`TLength`\> \| [`BackgroundProperty`](../modules/akashaproject_design_system._internal_.md#backgroundproperty)<`TLength`\>[]

The **`background`** shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.

**Syntax**: `[ <bg-layer> , ]* <final-bg-layer>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22781

___

### backgroundPosition

• `Optional` **backgroundPosition**: [`BackgroundPositionProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionproperty)<`TLength`\> \| [`BackgroundPositionProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionproperty)<`TLength`\>[]

The **`background-position`** CSS property sets the initial position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `<bg-position>#`

**Initial value**: `0% 0%`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22795

___

### border

• `Optional` **border**: [`BorderProperty`](../modules/akashaproject_design_system._internal_.md#borderproperty)<`TLength`\> \| [`BorderProperty`](../modules/akashaproject_design_system._internal_.md#borderproperty)<`TLength`\>[]

The **`border`** CSS property sets an element's border. It's a shorthand for `border-width`, `border-style`, and `border-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22807

___

### borderBlock

• `Optional` **borderBlock**: [`BorderBlockProperty`](../modules/akashaproject_design_system._internal_.md#borderblockproperty)<`TLength`\> \| [`BorderBlockProperty`](../modules/akashaproject_design_system._internal_.md#borderblockproperty)<`TLength`\>[]

The **`border-block`** CSS property is a shorthand property for setting the individual logical block border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22819

___

### borderBlockEnd

• `Optional` **borderBlockEnd**: [`BorderBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendproperty)<`TLength`\> \| [`BorderBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendproperty)<`TLength`\>[]

The **`border-block-end`** CSS property is a shorthand property for setting the individual logical block-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22831

___

### borderBlockStart

• `Optional` **borderBlockStart**: [`BorderBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartproperty)<`TLength`\> \| [`BorderBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartproperty)<`TLength`\>[]

The **`border-block-start`** CSS property is a shorthand property for setting the individual logical block-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22843

___

### borderBottom

• `Optional` **borderBottom**: [`BorderBottomProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomproperty)<`TLength`\> \| [`BorderBottomProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomproperty)<`TLength`\>[]

The **`border-bottom`** CSS property is a shorthand that sets the values of `border-bottom-width`, `border-bottom-style` and `border-bottom-color`. These properties set an element's bottom border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22855

___

### borderColor

• `Optional` **borderColor**: `string` \| `string`[]

The **`border-color`** shorthand CSS property sets the color of all sides of an element's border.

**Syntax**: `<color>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-color

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22867

___

### borderImage

• `Optional` **borderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

| Chrome  |  Firefox  | Safari  |  Edge  |   IE   |
| :-----: | :-------: | :-----: | :----: | :----: |
| **16**  |  **15**   |  **6**  | **12** | **11** |
| 7 _-x-_ | 3.5 _-x-_ | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22880

___

### borderInline

• `Optional` **borderInline**: [`BorderInlineProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineproperty)<`TLength`\> \| [`BorderInlineProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineproperty)<`TLength`\>[]

The **`border-inline`** CSS property is a shorthand property for setting the individual logical inline border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22892

___

### borderInlineEnd

• `Optional` **borderInlineEnd**: [`BorderInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendproperty)<`TLength`\> \| [`BorderInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendproperty)<`TLength`\>[]

The **`border-inline-end`** CSS property is a shorthand property for setting the individual logical inline-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22904

___

### borderInlineStart

• `Optional` **borderInlineStart**: [`BorderInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartproperty)<`TLength`\> \| [`BorderInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartproperty)<`TLength`\>[]

The **`border-inline-start`** CSS property is a shorthand property for setting the individual logical inline-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22916

___

### borderLeft

• `Optional` **borderLeft**: [`BorderLeftProperty`](../modules/akashaproject_design_system._internal_.md#borderleftproperty)<`TLength`\> \| [`BorderLeftProperty`](../modules/akashaproject_design_system._internal_.md#borderleftproperty)<`TLength`\>[]

The **`border-left`** CSS property is a shorthand that sets the values of `border-left-width`, `border-left-style` and `border-left-color`. These properties set an element's left border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22928

___

### borderRadius

• `Optional` **borderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-radius

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22941

___

### borderRight

• `Optional` **borderRight**: [`BorderRightProperty`](../modules/akashaproject_design_system._internal_.md#borderrightproperty)<`TLength`\> \| [`BorderRightProperty`](../modules/akashaproject_design_system._internal_.md#borderrightproperty)<`TLength`\>[]

The **`border-right`** CSS property is a shorthand that sets the values of `border-right-width`, `border-right-style` and `border-right-color`. These properties set an element's right border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22953

___

### borderStyle

• `Optional` **borderStyle**: `string` \| `string`[]

The **`border-style`** CSS property is a shorthand property that sets the line style for all four sides of an element's border.

**Syntax**: `<line-style>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-style

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22965

___

### borderTop

• `Optional` **borderTop**: [`BorderTopProperty`](../modules/akashaproject_design_system._internal_.md#bordertopproperty)<`TLength`\> \| [`BorderTopProperty`](../modules/akashaproject_design_system._internal_.md#bordertopproperty)<`TLength`\>[]

The **`border-top`** CSS property is a shorthand that sets the values of `border-top-width`, `border-top-style` and `border-top-color`. These properties set an element's top border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22977

___

### borderWidth

• `Optional` **borderWidth**: [`BorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderwidthproperty)<`TLength`\> \| [`BorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderwidthproperty)<`TLength`\>[]

The **`border-width`** shorthand CSS property sets the widths of all four sides of an element's border.

**Syntax**: `<line-width>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-width

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22989

___

### columnRule

• `Optional` **columnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23002

___

### columns

• `Optional` **columns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **50** | **52**  |  **9**  | **12** | **10** |
|        |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/columns

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23015

___

### flex

• `Optional` **flex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23028

___

### flexFlow

• `Optional` **flexFlow**: `string` \| `string`[]

The **`flex-flow`** CSS property is a shorthand property for `flex-direction` and `flex-wrap` properties.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **28**  |  **9**  | **12** | **11** |
| 21 _-x-_ |         | 7 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-flow

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23041

___

### font

• `Optional` **font**: `string` \| `string`[]

The **`font`** CSS property is a shorthand for `font-style`, `font-variant`, `font-weight`, `font-size`, `line-height`, and `font-family`. Alternatively, it sets an element's font to a system font.

**Syntax**: `[ [ <'font-style'> || <font-variant-css21> || <'font-weight'> || <'font-stretch'> ]? <'font-size'> [ / <'line-height'> ]? <'font-family'> ] | caption | icon | menu | message-box | small-caption | status-bar`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23053

___

### gap

• `Optional` **gap**: [`GapProperty`](../modules/akashaproject_design_system._internal_.md#gapproperty)<`TLength`\> \| [`GapProperty`](../modules/akashaproject_design_system._internal_.md#gapproperty)<`TLength`\>[]

The **`gap`** CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for `row-gap` and `column-gap`.

**Syntax**: `<'row-gap'> <'column-gap'>?`

---

_Supported in Flex Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **84** | **63**  | **14.1** | **84** | No  |

---

_Supported in Grid Layout_

|     Chrome      |     Firefox     |      Safari       |  Edge  | IE  |
| :-------------: | :-------------: | :---------------: | :----: | :-: |
|     **66**      |     **61**      |      **12**       | **16** | No  |
| 57 _(grid-gap)_ | 52 _(grid-gap)_ | 10.1 _(grid-gap)_ |        |     |

---

_Supported in Multi-column Layout_

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **66** | **61**  |   No   | **16** | No  |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/gap

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23088

___

### grid

• `Optional` **grid**: `string` \| `string`[]

The **`grid`** CSS property is a shorthand property that sets all of the explicit grid properties (`grid-template-rows`, `grid-template-columns`, and `grid-template-areas`), and all the implicit grid properties (`grid-auto-rows`, `grid-auto-columns`, and `grid-auto-flow`), in a single declaration.

**Syntax**: `<'grid-template'> | <'grid-template-rows'> / [ auto-flow && dense? ] <'grid-auto-columns'>? | [ auto-flow && dense? ] <'grid-auto-rows'>? / <'grid-template-columns'>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23100

___

### gridArea

• `Optional` **gridArea**: [`GridAreaProperty`](../modules/akashaproject_design_system._internal_.md#gridareaproperty) \| [`GridAreaProperty`](../modules/akashaproject_design_system._internal_.md#gridareaproperty)[]

The **`grid-area`** CSS property is a shorthand property for `grid-row-start`, `grid-column-start`, `grid-row-end` and `grid-column-end`, specifying a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the edges of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]{0,3}`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-area

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23112

___

### gridColumn

• `Optional` **gridColumn**: [`GridColumnProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnproperty) \| [`GridColumnProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnproperty)[]

The **`grid-column`** CSS property is a shorthand property for `grid-column-start` and `grid-column-end` specifying a grid item's size and location within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23124

___

### gridRow

• `Optional` **gridRow**: [`GridRowProperty`](../modules/akashaproject_design_system._internal_.md#gridrowproperty) \| [`GridRowProperty`](../modules/akashaproject_design_system._internal_.md#gridrowproperty)[]

The **`grid-row`** CSS property is a shorthand property for `grid-row-start` and `grid-row-end` specifying a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23136

___

### gridTemplate

• `Optional` **gridTemplate**: `string` \| `string`[]

The **`grid-template`** CSS property is a shorthand property for defining grid columns, rows, and areas.

**Syntax**: `none | [ <'grid-template-rows'> / <'grid-template-columns'> ] | [ <line-names>? <string> <track-size>? <line-names>? ]+ [ / <explicit-track-list> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23148

___

### lineClamp

• `Optional` **lineClamp**: [`LineClampProperty`](../modules/akashaproject_design_system._internal_.md#lineclampproperty) \| [`LineClampProperty`](../modules/akashaproject_design_system._internal_.md#lineclampproperty)[]

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23154

___

### listStyle

• `Optional` **listStyle**: `string` \| `string`[]

The **`list-style`** CSS property is a shorthand to set list style properties `list-style-type`, `list-style-image`, and `list-style-position`.

**Syntax**: `<'list-style-type'> || <'list-style-position'> || <'list-style-image'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23166

___

### margin

• `Optional` **margin**: [`MarginProperty`](../modules/akashaproject_design_system._internal_.md#marginproperty)<`TLength`\> \| [`MarginProperty`](../modules/akashaproject_design_system._internal_.md#marginproperty)<`TLength`\>[]

The **`margin`** CSS property sets the margin area on all four sides of an element. It is a shorthand for `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`.

**Syntax**: `[ <length> | <percentage> | auto ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23178

___

### mask

• `Optional` **mask**: [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\> \| [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\>[]

The **`mask`** CSS property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `<mask-layer>#`

| Chrome | Firefox | Safari  | Edge  | IE  |
| :----: | :-----: | :-----: | :---: | :-: |
| **1**  |  **2**  | **3.1** | 12-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23190

___

### maskBorder

• `Optional` **maskBorder**: [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty) \| [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty)[]

The **`mask-border`** CSS property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

|              Chrome              | Firefox |               Safari               |               Edge                | IE  |
| :------------------------------: | :-----: | :--------------------------------: | :-------------------------------: | :-: |
| **1** _(-webkit-mask-box-image)_ |   No    | **3.1** _(-webkit-mask-box-image)_ | **79** _(-webkit-mask-box-image)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23202

___

### motion

• `Optional` **motion**: [`OffsetProperty`](../modules/akashaproject_design_system._internal_.md#offsetproperty)<`TLength`\> \| [`OffsetProperty`](../modules/akashaproject_design_system._internal_.md#offsetproperty)<`TLength`\>[]

The **`offset`** CSS property is a shorthand property for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23215

___

### offset

• `Optional` **offset**: [`OffsetProperty`](../modules/akashaproject_design_system._internal_.md#offsetproperty)<`TLength`\> \| [`OffsetProperty`](../modules/akashaproject_design_system._internal_.md#offsetproperty)<`TLength`\>[]

The **`offset`** CSS property is a shorthand property for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23228

___

### outline

• `Optional` **outline**: [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\> \| [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\>[]

The **`outline`** CSS property is a shorthand to set various outline properties in a single declaration: `outline-style`, `outline-width`, and `outline-color`.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23240

___

### overflow

• `Optional` **overflow**: `string` \| `string`[]

The **`overflow`** CSS property sets what to do when an element's content is too big to fit in its block formatting context. It is a shorthand for `overflow-x` and `overflow-y`.

**Syntax**: `[ visible | hidden | clip | scroll | auto ]{1,2}`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23254

___

### overscrollBehavior

• `Optional` **overscrollBehavior**: `string` \| `string`[]

The **`overscroll-behavior`** CSS property sets what a browser does when reaching the boundary of a scrolling area. It's a shorthand for `overscroll-behavior-x` and `overscroll-behavior-y`.

**Syntax**: `[ contain | none | auto ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23268

___

### padding

• `Optional` **padding**: [`PaddingProperty`](../modules/akashaproject_design_system._internal_.md#paddingproperty)<`TLength`\> \| [`PaddingProperty`](../modules/akashaproject_design_system._internal_.md#paddingproperty)<`TLength`\>[]

The **`padding`** CSS property sets the padding area on all four sides of an element. It is a shorthand for `padding-top`, `padding-right`, `padding-bottom`, and `padding-left`.

**Syntax**: `[ <length> | <percentage> ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23280

___

### placeItems

• `Optional` **placeItems**: `string` \| `string`[]

The CSS **`place-items`** shorthand property sets the `align-items` and `justify-items` properties, respectively. If the second value is not set, the first value is also used for it.

**Syntax**: `<'align-items'> <'justify-items'>?`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-items

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23292

___

### placeSelf

• `Optional` **placeSelf**: `string` \| `string`[]

The **`place-self`** CSS property is a shorthand property sets both the `align-self` and `justify-self` properties. The first value is the `align-self` property value, the second the `justify-self` one. If the second value is not present, the first value is also used for it.

**Syntax**: `<'align-self'> <'justify-self'>?`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-self

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23304

___

### textDecoration

• `Optional` **textDecoration**: [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\> \| [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\>[]

The **`text-decoration`** CSS property sets the appearance of decorative lines on text. It is a shorthand for `text-decoration-line`, `text-decoration-color`, and `text-decoration-style`.

**Syntax**: `<'text-decoration-line'> || <'text-decoration-style'> || <'text-decoration-color'> || <'text-decoration-thickness'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23316

___

### textEmphasis

• `Optional` **textEmphasis**: `string` \| `string`[]

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23328

___

### transition

• `Optional` **transition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23341
