[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ObsoletePropertiesFallback

# Interface: ObsoletePropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ObsoletePropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- **`ObsoletePropertiesFallback`**

  ↳ [`PropertiesFallback`](akashaproject_design_system._internal_.PropertiesFallback.md)

## Table of contents

### Properties

- [KhtmlBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxalign)
- [KhtmlBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxdirection)
- [KhtmlBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxflex)
- [KhtmlBoxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxflexgroup)
- [KhtmlBoxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxlines)
- [KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxordinalgroup)
- [KhtmlBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxorient)
- [KhtmlBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxpack)
- [KhtmlLineBreak](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmllinebreak)
- [KhtmlOpacity](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlopacity)
- [KhtmlUserSelect](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmluserselect)
- [MozBackgroundClip](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundclip)
- [MozBackgroundInlinePolicy](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundinlinepolicy)
- [MozBackgroundOrigin](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundorigin)
- [MozBackgroundSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundsize)
- [MozBinding](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbinding)
- [MozBorderRadius](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradius)
- [MozBorderRadiusBottomleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiusbottomleft)
- [MozBorderRadiusBottomright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiusbottomright)
- [MozBorderRadiusTopleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiustopleft)
- [MozBorderRadiusTopright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiustopright)
- [MozBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxalign)
- [MozBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxdirection)
- [MozBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxflex)
- [MozBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxordinalgroup)
- [MozBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxorient)
- [MozBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxpack)
- [MozBoxShadow](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxshadow)
- [MozFloatEdge](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozfloatedge)
- [MozForceBrokenImageIcon](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozforcebrokenimageicon)
- [MozOpacity](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozopacity)
- [MozOutline](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutline)
- [MozOutlineColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinecolor)
- [MozOutlineRadius](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradius)
- [MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiusbottomleft)
- [MozOutlineRadiusBottomright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiusbottomright)
- [MozOutlineRadiusTopleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiustopleft)
- [MozOutlineRadiusTopright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiustopright)
- [MozOutlineStyle](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinestyle)
- [MozOutlineWidth](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinewidth)
- [MozTextAlignLast](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextalignlast)
- [MozTextDecorationColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationcolor)
- [MozTextDecorationLine](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationline)
- [MozTextDecorationStyle](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationstyle)
- [MozUserInput](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozuserinput)
- [OAnimation](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimation)
- [OAnimationDelay](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationdelay)
- [OAnimationDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationdirection)
- [OAnimationDuration](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationduration)
- [OAnimationFillMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationfillmode)
- [OAnimationIterationCount](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationiterationcount)
- [OAnimationName](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationname)
- [OAnimationPlayState](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationplaystate)
- [OAnimationTimingFunction](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationtimingfunction)
- [OBackgroundSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#obackgroundsize)
- [OBorderImage](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oborderimage)
- [OObjectFit](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oobjectfit)
- [OObjectPosition](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oobjectposition)
- [OTabSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otabsize)
- [OTextOverflow](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otextoverflow)
- [OTransform](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransform)
- [OTransformOrigin](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransformorigin)
- [OTransition](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransition)
- [OTransitionDelay](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitiondelay)
- [OTransitionDuration](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitionduration)
- [OTransitionProperty](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitionproperty)
- [OTransitionTimingFunction](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitiontimingfunction)
- [WebkitBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxalign)
- [WebkitBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxdirection)
- [WebkitBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxflex)
- [WebkitBoxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxflexgroup)
- [WebkitBoxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxlines)
- [WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxordinalgroup)
- [WebkitBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxorient)
- [WebkitBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxpack)
- [WebkitScrollSnapPointsX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitscrollsnappointsx)
- [WebkitScrollSnapPointsY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitscrollsnappointsy)
- [azimuth](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#azimuth)
- [boxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxalign)
- [boxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxdirection)
- [boxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxflex)
- [boxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxflexgroup)
- [boxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxlines)
- [boxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxordinalgroup)
- [boxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxorient)
- [boxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxpack)
- [clip](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#clip)
- [fontVariantAlternates](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#fontvariantalternates)
- [gridColumnGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridcolumngap)
- [gridGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridgap)
- [gridRowGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridrowgap)
- [imeMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#imemode)
- [msImeMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#msimemode)
- [msScrollbarTrackColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#msscrollbartrackcolor)
- [offsetBlock](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblock)
- [offsetBlockEnd](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblockend)
- [offsetBlockStart](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblockstart)
- [offsetInline](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinline)
- [offsetInlineEnd](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinlineend)
- [offsetInlineStart](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinlinestart)
- [scrollSnapCoordinate](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnapcoordinate)
- [scrollSnapDestination](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnapdestination)
- [scrollSnapPointsX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnappointsx)
- [scrollSnapPointsY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnappointsy)
- [scrollSnapTypeX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnaptypex)
- [scrollSnapTypeY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnaptypey)
- [scrollbarTrackColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollbartrackcolor)

## Properties

### KhtmlBoxAlign

• `Optional` **KhtmlBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25584

___

### KhtmlBoxDirection

• `Optional` **KhtmlBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25594

___

### KhtmlBoxFlex

• `Optional` **KhtmlBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25604

___

### KhtmlBoxFlexGroup

• `Optional` **KhtmlBoxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25614

___

### KhtmlBoxLines

• `Optional` **KhtmlBoxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25624

___

### KhtmlBoxOrdinalGroup

• `Optional` **KhtmlBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25634

___

### KhtmlBoxOrient

• `Optional` **KhtmlBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25644

___

### KhtmlBoxPack

• `Optional` **KhtmlBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25654

___

### KhtmlLineBreak

• `Optional` **KhtmlLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25664

___

### KhtmlOpacity

• `Optional` **KhtmlOpacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

The **`opacity`** CSS property sets the transparency of an element or the degree to which content behind an element is visible.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25674

___

### KhtmlUserSelect

• `Optional` **KhtmlUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25684

___

### MozBackgroundClip

• `Optional` **MozBackgroundClip**: `string` \| `string`[]

The **`background-clip`** CSS property sets whether an element's background `<color>` or `<image>` extends underneath its border.

**Syntax**: `<box>#`

**Initial value**: `border-box`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25694

___

### MozBackgroundInlinePolicy

• `Optional` **MozBackgroundInlinePolicy**: [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty) \| [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty)[]

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25704

___

### MozBackgroundOrigin

• `Optional` **MozBackgroundOrigin**: `string` \| `string`[]

The **`background-origin`** CSS property sets the _background positioning area_. In other words, it sets the origin position of an image set with the `background-image` property.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25714

___

### MozBackgroundSize

• `Optional` **MozBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25724

___

### MozBinding

• `Optional` **MozBinding**: `string` \| `string`[]

The **`-moz-binding`** CSS property is used by Mozilla-based applications to attach an XBL binding to a DOM element.

**Syntax**: `<url> | none`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25734

___

### MozBorderRadius

• `Optional` **MozBorderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25742

___

### MozBorderRadiusBottomleft

• `Optional` **MozBorderRadiusBottomleft**: [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\> \| [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\>[]

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25752

___

### MozBorderRadiusBottomright

• `Optional` **MozBorderRadiusBottomright**: [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\> \| [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\>[]

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25762

___

### MozBorderRadiusTopleft

• `Optional` **MozBorderRadiusTopleft**: [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\> \| [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\>[]

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25772

___

### MozBorderRadiusTopright

• `Optional` **MozBorderRadiusTopright**: [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\> \| [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\>[]

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25782

___

### MozBoxAlign

• `Optional` **MozBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25792

___

### MozBoxDirection

• `Optional` **MozBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25802

___

### MozBoxFlex

• `Optional` **MozBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25812

___

### MozBoxOrdinalGroup

• `Optional` **MozBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25822

___

### MozBoxOrient

• `Optional` **MozBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25832

___

### MozBoxPack

• `Optional` **MozBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25842

___

### MozBoxShadow

• `Optional` **MozBoxShadow**: `string` \| `string`[]

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25852

___

### MozFloatEdge

• `Optional` **MozFloatEdge**: [`MozFloatEdgeProperty`](../modules/akashaproject_design_system._internal_.md#mozfloatedgeproperty) \| [`MozFloatEdgeProperty`](../modules/akashaproject_design_system._internal_.md#mozfloatedgeproperty)[]

The non-standard **`-moz-float-edge`** CSS property specifies whether the height and width properties of the element include the margin, border, or padding thickness.

**Syntax**: `border-box | content-box | margin-box | padding-box`

**Initial value**: `content-box`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25862

___

### MozForceBrokenImageIcon

• `Optional` **MozForceBrokenImageIcon**: [`MozForceBrokenImageIconProperty`](../modules/akashaproject_design_system._internal_.md#mozforcebrokenimageiconproperty) \| [`MozForceBrokenImageIconProperty`](../modules/akashaproject_design_system._internal_.md#mozforcebrokenimageiconproperty)[]

The **`-moz-force-broken-image-icon`** extended CSS property can be used to force the broken image icon to be shown even when a broken image has an `alt` attribute.

**Syntax**: `0 | 1`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25872

___

### MozOpacity

• `Optional` **MozOpacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

The **`opacity`** CSS property sets the transparency of an element or the degree to which content behind an element is visible.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25882

___

### MozOutline

• `Optional` **MozOutline**: [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\> \| [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\>[]

The **`outline`** CSS property is a shorthand to set various outline properties in a single declaration: `outline-style`, `outline-width`, and `outline-color`.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25890

___

### MozOutlineColor

• `Optional` **MozOutlineColor**: `string` \| `string`[]

The **`outline-color`** CSS property sets the color of an element's outline.

**Syntax**: `<color> | invert`

**Initial value**: `invert`, for browsers supporting it, `currentColor` for the other

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25900

___

### MozOutlineRadius

• `Optional` **MozOutlineRadius**: [`MozOutlineRadiusProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusproperty)<`TLength`\> \| [`MozOutlineRadiusProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusproperty)<`TLength`\>[]

In Mozilla applications like Firefox, the **`-moz-outline-radius`** CSS property can be used to give an element's `outline` rounded corners.

**Syntax**: `<outline-radius>{1,4} [ / <outline-radius>{1,4} ]?`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25908

___

### MozOutlineRadiusBottomleft

• `Optional` **MozOutlineRadiusBottomleft**: [`MozOutlineRadiusBottomleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleftproperty)<`TLength`\> \| [`MozOutlineRadiusBottomleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleftproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-bottomleft`** CSS property can be used to round the bottom-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25918

___

### MozOutlineRadiusBottomright

• `Optional` **MozOutlineRadiusBottomright**: [`MozOutlineRadiusBottomrightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomrightproperty)<`TLength`\> \| [`MozOutlineRadiusBottomrightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomrightproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-bottomright`** CSS property can be used to round the bottom-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25928

___

### MozOutlineRadiusTopleft

• `Optional` **MozOutlineRadiusTopleft**: [`MozOutlineRadiusTopleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleftproperty)<`TLength`\> \| [`MozOutlineRadiusTopleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleftproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-topleft`** CSS property can be used to round the top-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25938

___

### MozOutlineRadiusTopright

• `Optional` **MozOutlineRadiusTopright**: [`MozOutlineRadiusToprightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustoprightproperty)<`TLength`\> \| [`MozOutlineRadiusToprightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustoprightproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-topright`** CSS property can be used to round the top-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25948

___

### MozOutlineStyle

• `Optional` **MozOutlineStyle**: `string` \| `string`[]

The **`outline-style`** CSS property sets the style of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `auto | <'border-style'>`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25958

___

### MozOutlineWidth

• `Optional` **MozOutlineWidth**: [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\> \| [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\>[]

The **`outline-width`** CSS property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25968

___

### MozTextAlignLast

• `Optional` **MozTextAlignLast**: [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty) \| [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty)[]

The **`text-align-last`** CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

**Syntax**: `auto | start | end | left | right | center | justify`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25978

___

### MozTextDecorationColor

• `Optional` **MozTextDecorationColor**: `string` \| `string`[]

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25988

___

### MozTextDecorationLine

• `Optional` **MozTextDecorationLine**: `string` \| `string`[]

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25998

___

### MozTextDecorationStyle

• `Optional` **MozTextDecorationStyle**: [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty) \| [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty)[]

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26008

___

### MozUserInput

• `Optional` **MozUserInput**: [`MozUserInputProperty`](../modules/akashaproject_design_system._internal_.md#mozuserinputproperty) \| [`MozUserInputProperty`](../modules/akashaproject_design_system._internal_.md#mozuserinputproperty)[]

In Mozilla applications, **`-moz-user-input`** determines if an element will accept user input.

**Syntax**: `auto | none | enabled | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26018

___

### OAnimation

• `Optional` **OAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26046

___

### OAnimationDelay

• `Optional` **OAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26056

___

### OAnimationDirection

• `Optional` **OAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26066

___

### OAnimationDuration

• `Optional` **OAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26076

___

### OAnimationFillMode

• `Optional` **OAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26086

___

### OAnimationIterationCount

• `Optional` **OAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26096

___

### OAnimationName

• `Optional` **OAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26106

___

### OAnimationPlayState

• `Optional` **OAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26116

___

### OAnimationTimingFunction

• `Optional` **OAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26126

___

### OBackgroundSize

• `Optional` **OBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26136

___

### OBorderImage

• `Optional` **OBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26144

___

### OObjectFit

• `Optional` **OObjectFit**: [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty) \| [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty)[]

The **`object-fit`** CSS property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container.

**Syntax**: `fill | contain | cover | none | scale-down`

**Initial value**: `fill`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26154

___

### OObjectPosition

• `Optional` **OObjectPosition**: [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\> \| [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\>[]

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26164

___

### OTabSize

• `Optional` **OTabSize**: [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\> \| [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\>[]

The **`tab-size`** CSS property is used to customize the width of a tab (`U+0009`) character.

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26174

___

### OTextOverflow

• `Optional` **OTextOverflow**: `string` \| `string`[]

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26184

___

### OTransform

• `Optional` **OTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26194

___

### OTransformOrigin

• `Optional` **OTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26204

___

### OTransition

• `Optional` **OTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26212

___

### OTransitionDelay

• `Optional` **OTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26222

___

### OTransitionDuration

• `Optional` **OTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26232

___

### OTransitionProperty

• `Optional` **OTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26242

___

### OTransitionTimingFunction

• `Optional` **OTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26252

___

### WebkitBoxAlign

• `Optional` **WebkitBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26262

___

### WebkitBoxDirection

• `Optional` **WebkitBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26272

___

### WebkitBoxFlex

• `Optional` **WebkitBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26282

___

### WebkitBoxFlexGroup

• `Optional` **WebkitBoxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26292

___

### WebkitBoxLines

• `Optional` **WebkitBoxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26302

___

### WebkitBoxOrdinalGroup

• `Optional` **WebkitBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26312

___

### WebkitBoxOrient

• `Optional` **WebkitBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26322

___

### WebkitBoxPack

• `Optional` **WebkitBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26332

___

### WebkitScrollSnapPointsX

• `Optional` **WebkitScrollSnapPointsX**: `string` \| `string`[]

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26342

___

### WebkitScrollSnapPointsY

• `Optional` **WebkitScrollSnapPointsY**: `string` \| `string`[]

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26352

___

### azimuth

• `Optional` **azimuth**: `string` \| `string`[]

In combination with `elevation`, the **`azimuth`** CSS property enables different audio sources to be positioned spatially for aural presentation. This is important in that it provides a natural way to tell several voices apart, as each can be positioned to originate at a different location on the sound stage. Stereo output produce a lateral sound stage, while binaural headphones and multi-speaker setups allow for a fully three-dimensional stage.

**Syntax**: `<angle> | [ [ left-side | far-left | left | center-left | center | center-right | right | far-right | right-side ] || behind ] | leftwards | rightwards`

**Initial value**: `center`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25306

___

### boxAlign

• `Optional` **boxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25316

___

### boxDirection

• `Optional` **boxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25326

___

### boxFlex

• `Optional` **boxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25336

___

### boxFlexGroup

• `Optional` **boxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25346

___

### boxLines

• `Optional` **boxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25356

___

### boxOrdinalGroup

• `Optional` **boxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25366

___

### boxOrient

• `Optional` **boxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25376

___

### boxPack

• `Optional` **boxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25386

___

### clip

• `Optional` **clip**: `string` \| `string`[]

The **`clip`** CSS property defines what portion of an element is visible. The `clip` property applies only to absolutely positioned elements, that is elements with `position:absolute` or `position:fixed`.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25396

___

### fontVariantAlternates

• `Optional` **fontVariantAlternates**: `string` \| `string`[]

The **`font-variant-alternates`** CSS property controls the usage of alternate glyphs. These alternate glyphs may be referenced by alternative names defined in `@font-feature-values`.

**Syntax**: `normal | [ stylistic( <feature-value-name> ) || historical-forms || styleset( <feature-value-name># ) || character-variant( <feature-value-name># ) || swash( <feature-value-name> ) || ornaments( <feature-value-name> ) || annotation( <feature-value-name> ) ]`

**Initial value**: `normal`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25406

___

### gridColumnGap

• `Optional` **gridColumnGap**: [`GridColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumngapproperty)<`TLength`\> \| [`GridColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25416

___

### gridGap

• `Optional` **gridGap**: [`GridGapProperty`](../modules/akashaproject_design_system._internal_.md#gridgapproperty)<`TLength`\> \| [`GridGapProperty`](../modules/akashaproject_design_system._internal_.md#gridgapproperty)<`TLength`\>[]

The **`gap`** CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for `row-gap` and `column-gap`.

**Syntax**: `<'grid-row-gap'> <'grid-column-gap'>?`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25424

___

### gridRowGap

• `Optional` **gridRowGap**: [`GridRowGapProperty`](../modules/akashaproject_design_system._internal_.md#gridrowgapproperty)<`TLength`\> \| [`GridRowGapProperty`](../modules/akashaproject_design_system._internal_.md#gridrowgapproperty)<`TLength`\>[]

The **`row-gap`** CSS property sets the size of the gap (gutter) between an element's grid rows.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25434

___

### imeMode

• `Optional` **imeMode**: [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty) \| [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty)[]

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25444

___

### msImeMode

• `Optional` **msImeMode**: [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty) \| [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty)[]

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26028

___

### msScrollbarTrackColor

• `Optional` **msScrollbarTrackColor**: `string` \| `string`[]

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26038

___

### offsetBlock

• `Optional` **offsetBlock**: [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\> \| [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\>[]

The **`inset-block`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25454

___

### offsetBlockEnd

• `Optional` **offsetBlockEnd**: [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\> \| [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\>[]

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25464

___

### offsetBlockStart

• `Optional` **offsetBlockStart**: [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\> \| [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\>[]

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25474

___

### offsetInline

• `Optional` **offsetInline**: [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\> \| [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\>[]

The **`inset-inline`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25484

___

### offsetInlineEnd

• `Optional` **offsetInlineEnd**: [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\> \| [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\>[]

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25494

___

### offsetInlineStart

• `Optional` **offsetInlineStart**: [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\> \| [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\>[]

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25504

___

### scrollSnapCoordinate

• `Optional` **scrollSnapCoordinate**: [`ScrollSnapCoordinateProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinateproperty)<`TLength`\> \| [`ScrollSnapCoordinateProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinateproperty)<`TLength`\>[]

The **`scroll-snap-coordinate`** CSS property defines the x and y coordinate positions within an element that will align with its nearest ancestor scroll container's `scroll-snap-destination` for each respective axis.

**Syntax**: `none | <position>#`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25514

___

### scrollSnapDestination

• `Optional` **scrollSnapDestination**: [`ScrollSnapDestinationProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestinationproperty)<`TLength`\> \| [`ScrollSnapDestinationProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestinationproperty)<`TLength`\>[]

The **`scroll-snap-destination`** CSS property defines the position in x and y coordinates within the scroll container's visual viewport which element snap points align with.

**Syntax**: `<position>`

**Initial value**: `0px 0px`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25524

___

### scrollSnapPointsX

• `Optional` **scrollSnapPointsX**: `string` \| `string`[]

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25534

___

### scrollSnapPointsY

• `Optional` **scrollSnapPointsY**: `string` \| `string`[]

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25544

___

### scrollSnapTypeX

• `Optional` **scrollSnapTypeX**: [`ScrollSnapTypeXProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypexproperty) \| [`ScrollSnapTypeXProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypexproperty)[]

The **`scroll-snap-type-x`** CSS property defines how strictly snap points are enforced on the horizontal axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25554

___

### scrollSnapTypeY

• `Optional` **scrollSnapTypeY**: [`ScrollSnapTypeYProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypeyproperty) \| [`ScrollSnapTypeYProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypeyproperty)[]

The **`scroll-snap-type-y`** CSS property defines how strictly snap points are enforced on the vertical axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25564

___

### scrollbarTrackColor

• `Optional` **scrollbarTrackColor**: `string` \| `string`[]

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25574
