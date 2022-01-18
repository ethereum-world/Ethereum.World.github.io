[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / SvgPropertiesFallback

# Interface: SvgPropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).SvgPropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- **`SvgPropertiesFallback`**

  ↳ [`PropertiesFallback`](akashaproject_design_system._internal_.PropertiesFallback.md)

## Table of contents

### Properties

- [alignmentBaseline](akashaproject_design_system._internal_.SvgPropertiesFallback.md#alignmentbaseline)
- [baselineShift](akashaproject_design_system._internal_.SvgPropertiesFallback.md#baselineshift)
- [clip](akashaproject_design_system._internal_.SvgPropertiesFallback.md#clip)
- [clipPath](akashaproject_design_system._internal_.SvgPropertiesFallback.md#clippath)
- [clipRule](akashaproject_design_system._internal_.SvgPropertiesFallback.md#cliprule)
- [color](akashaproject_design_system._internal_.SvgPropertiesFallback.md#color)
- [colorInterpolation](akashaproject_design_system._internal_.SvgPropertiesFallback.md#colorinterpolation)
- [colorRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#colorrendering)
- [cursor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#cursor)
- [direction](akashaproject_design_system._internal_.SvgPropertiesFallback.md#direction)
- [display](akashaproject_design_system._internal_.SvgPropertiesFallback.md#display)
- [dominantBaseline](akashaproject_design_system._internal_.SvgPropertiesFallback.md#dominantbaseline)
- [fill](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fill)
- [fillOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fillopacity)
- [fillRule](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fillrule)
- [filter](akashaproject_design_system._internal_.SvgPropertiesFallback.md#filter)
- [floodColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#floodcolor)
- [floodOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#floodopacity)
- [font](akashaproject_design_system._internal_.SvgPropertiesFallback.md#font)
- [fontFamily](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontfamily)
- [fontSize](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontsize)
- [fontSizeAdjust](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontsizeadjust)
- [fontStretch](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontstretch)
- [fontStyle](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontstyle)
- [fontVariant](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontvariant)
- [fontWeight](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontweight)
- [glyphOrientationVertical](akashaproject_design_system._internal_.SvgPropertiesFallback.md#glyphorientationvertical)
- [imageRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#imagerendering)
- [letterSpacing](akashaproject_design_system._internal_.SvgPropertiesFallback.md#letterspacing)
- [lightingColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#lightingcolor)
- [lineHeight](akashaproject_design_system._internal_.SvgPropertiesFallback.md#lineheight)
- [marker](akashaproject_design_system._internal_.SvgPropertiesFallback.md#marker)
- [markerEnd](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markerend)
- [markerMid](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markermid)
- [markerStart](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markerstart)
- [mask](akashaproject_design_system._internal_.SvgPropertiesFallback.md#mask)
- [opacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#opacity)
- [overflow](akashaproject_design_system._internal_.SvgPropertiesFallback.md#overflow)
- [paintOrder](akashaproject_design_system._internal_.SvgPropertiesFallback.md#paintorder)
- [pointerEvents](akashaproject_design_system._internal_.SvgPropertiesFallback.md#pointerevents)
- [shapeRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#shaperendering)
- [stopColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stopcolor)
- [stopOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stopopacity)
- [stroke](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stroke)
- [strokeDasharray](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokedasharray)
- [strokeDashoffset](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokedashoffset)
- [strokeLinecap](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokelinecap)
- [strokeLinejoin](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokelinejoin)
- [strokeMiterlimit](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokemiterlimit)
- [strokeOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokeopacity)
- [strokeWidth](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokewidth)
- [textAnchor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textanchor)
- [textDecoration](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textdecoration)
- [textRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textrendering)
- [unicodeBidi](akashaproject_design_system._internal_.SvgPropertiesFallback.md#unicodebidi)
- [vectorEffect](akashaproject_design_system._internal_.SvgPropertiesFallback.md#vectoreffect)
- [visibility](akashaproject_design_system._internal_.SvgPropertiesFallback.md#visibility)
- [whiteSpace](akashaproject_design_system._internal_.SvgPropertiesFallback.md#whitespace)
- [wordSpacing](akashaproject_design_system._internal_.SvgPropertiesFallback.md#wordspacing)
- [writingMode](akashaproject_design_system._internal_.SvgPropertiesFallback.md#writingmode)

## Properties

### alignmentBaseline

• `Optional` **alignmentBaseline**: [`AlignmentBaselineProperty`](../modules/akashaproject_design_system._internal_.md#alignmentbaselineproperty) \| [`AlignmentBaselineProperty`](../modules/akashaproject_design_system._internal_.md#alignmentbaselineproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26356

___

### baselineShift

• `Optional` **baselineShift**: [`BaselineShiftProperty`](../modules/akashaproject_design_system._internal_.md#baselineshiftproperty)<`TLength`\> \| [`BaselineShiftProperty`](../modules/akashaproject_design_system._internal_.md#baselineshiftproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26357

___

### clip

• `Optional` **clip**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26358

___

### clipPath

• `Optional` **clipPath**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26359

___

### clipRule

• `Optional` **clipRule**: [`ClipRuleProperty`](../modules/akashaproject_design_system._internal_.md#clipruleproperty) \| [`ClipRuleProperty`](../modules/akashaproject_design_system._internal_.md#clipruleproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26360

___

### color

• `Optional` **color**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26361

___

### colorInterpolation

• `Optional` **colorInterpolation**: [`ColorInterpolationProperty`](../modules/akashaproject_design_system._internal_.md#colorinterpolationproperty) \| [`ColorInterpolationProperty`](../modules/akashaproject_design_system._internal_.md#colorinterpolationproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26362

___

### colorRendering

• `Optional` **colorRendering**: [`ColorRenderingProperty`](../modules/akashaproject_design_system._internal_.md#colorrenderingproperty) \| [`ColorRenderingProperty`](../modules/akashaproject_design_system._internal_.md#colorrenderingproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26363

___

### cursor

• `Optional` **cursor**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26364

___

### direction

• `Optional` **direction**: [`DirectionProperty`](../modules/akashaproject_design_system._internal_.md#directionproperty) \| [`DirectionProperty`](../modules/akashaproject_design_system._internal_.md#directionproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26365

___

### display

• `Optional` **display**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26366

___

### dominantBaseline

• `Optional` **dominantBaseline**: [`DominantBaselineProperty`](../modules/akashaproject_design_system._internal_.md#dominantbaselineproperty) \| [`DominantBaselineProperty`](../modules/akashaproject_design_system._internal_.md#dominantbaselineproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26367

___

### fill

• `Optional` **fill**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26368

___

### fillOpacity

• `Optional` **fillOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26369

___

### fillRule

• `Optional` **fillRule**: [`FillRuleProperty`](../modules/akashaproject_design_system._internal_.md#fillruleproperty) \| [`FillRuleProperty`](../modules/akashaproject_design_system._internal_.md#fillruleproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26370

___

### filter

• `Optional` **filter**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26371

___

### floodColor

• `Optional` **floodColor**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26372

___

### floodOpacity

• `Optional` **floodOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26373

___

### font

• `Optional` **font**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26374

___

### fontFamily

• `Optional` **fontFamily**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26375

___

### fontSize

• `Optional` **fontSize**: [`FontSizeProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeproperty)<`TLength`\> \| [`FontSizeProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26376

___

### fontSizeAdjust

• `Optional` **fontSizeAdjust**: [`FontSizeAdjustProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeadjustproperty) \| [`FontSizeAdjustProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeadjustproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26377

___

### fontStretch

• `Optional` **fontStretch**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26378

___

### fontStyle

• `Optional` **fontStyle**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26379

___

### fontVariant

• `Optional` **fontVariant**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26380

___

### fontWeight

• `Optional` **fontWeight**: [`FontWeightProperty`](../modules/akashaproject_design_system._internal_.md#fontweightproperty) \| [`FontWeightProperty`](../modules/akashaproject_design_system._internal_.md#fontweightproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26381

___

### glyphOrientationVertical

• `Optional` **glyphOrientationVertical**: [`GlyphOrientationVerticalProperty`](../modules/akashaproject_design_system._internal_.md#glyphorientationverticalproperty) \| [`GlyphOrientationVerticalProperty`](../modules/akashaproject_design_system._internal_.md#glyphorientationverticalproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26382

___

### imageRendering

• `Optional` **imageRendering**: [`ImageRenderingProperty`](../modules/akashaproject_design_system._internal_.md#imagerenderingproperty) \| [`ImageRenderingProperty`](../modules/akashaproject_design_system._internal_.md#imagerenderingproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26383

___

### letterSpacing

• `Optional` **letterSpacing**: [`LetterSpacingProperty`](../modules/akashaproject_design_system._internal_.md#letterspacingproperty)<`TLength`\> \| [`LetterSpacingProperty`](../modules/akashaproject_design_system._internal_.md#letterspacingproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26384

___

### lightingColor

• `Optional` **lightingColor**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26385

___

### lineHeight

• `Optional` **lineHeight**: [`LineHeightProperty`](../modules/akashaproject_design_system._internal_.md#lineheightproperty)<`TLength`\> \| [`LineHeightProperty`](../modules/akashaproject_design_system._internal_.md#lineheightproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26386

___

### marker

• `Optional` **marker**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26387

___

### markerEnd

• `Optional` **markerEnd**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26388

___

### markerMid

• `Optional` **markerMid**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26389

___

### markerStart

• `Optional` **markerStart**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26390

___

### mask

• `Optional` **mask**: [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\> \| [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26391

___

### opacity

• `Optional` **opacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26392

___

### overflow

• `Optional` **overflow**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26393

___

### paintOrder

• `Optional` **paintOrder**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26394

___

### pointerEvents

• `Optional` **pointerEvents**: [`PointerEventsProperty`](../modules/akashaproject_design_system._internal_.md#pointereventsproperty) \| [`PointerEventsProperty`](../modules/akashaproject_design_system._internal_.md#pointereventsproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26395

___

### shapeRendering

• `Optional` **shapeRendering**: [`ShapeRenderingProperty`](../modules/akashaproject_design_system._internal_.md#shaperenderingproperty) \| [`ShapeRenderingProperty`](../modules/akashaproject_design_system._internal_.md#shaperenderingproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26396

___

### stopColor

• `Optional` **stopColor**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26397

___

### stopOpacity

• `Optional` **stopOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26398

___

### stroke

• `Optional` **stroke**: `string` \| `string`[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26399

___

### strokeDasharray

• `Optional` **strokeDasharray**: [`StrokeDasharrayProperty`](../modules/akashaproject_design_system._internal_.md#strokedasharrayproperty)<`TLength`\> \| [`StrokeDasharrayProperty`](../modules/akashaproject_design_system._internal_.md#strokedasharrayproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26400

___

### strokeDashoffset

• `Optional` **strokeDashoffset**: [`StrokeDashoffsetProperty`](../modules/akashaproject_design_system._internal_.md#strokedashoffsetproperty)<`TLength`\> \| [`StrokeDashoffsetProperty`](../modules/akashaproject_design_system._internal_.md#strokedashoffsetproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26401

___

### strokeLinecap

• `Optional` **strokeLinecap**: [`StrokeLinecapProperty`](../modules/akashaproject_design_system._internal_.md#strokelinecapproperty) \| [`StrokeLinecapProperty`](../modules/akashaproject_design_system._internal_.md#strokelinecapproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26402

___

### strokeLinejoin

• `Optional` **strokeLinejoin**: [`StrokeLinejoinProperty`](../modules/akashaproject_design_system._internal_.md#strokelinejoinproperty) \| [`StrokeLinejoinProperty`](../modules/akashaproject_design_system._internal_.md#strokelinejoinproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26403

___

### strokeMiterlimit

• `Optional` **strokeMiterlimit**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26404

___

### strokeOpacity

• `Optional` **strokeOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26405

___

### strokeWidth

• `Optional` **strokeWidth**: [`StrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#strokewidthproperty)<`TLength`\> \| [`StrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#strokewidthproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26406

___

### textAnchor

• `Optional` **textAnchor**: [`TextAnchorProperty`](../modules/akashaproject_design_system._internal_.md#textanchorproperty) \| [`TextAnchorProperty`](../modules/akashaproject_design_system._internal_.md#textanchorproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26407

___

### textDecoration

• `Optional` **textDecoration**: [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\> \| [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26408

___

### textRendering

• `Optional` **textRendering**: [`TextRenderingProperty`](../modules/akashaproject_design_system._internal_.md#textrenderingproperty) \| [`TextRenderingProperty`](../modules/akashaproject_design_system._internal_.md#textrenderingproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26409

___

### unicodeBidi

• `Optional` **unicodeBidi**: [`UnicodeBidiProperty`](../modules/akashaproject_design_system._internal_.md#unicodebidiproperty) \| [`UnicodeBidiProperty`](../modules/akashaproject_design_system._internal_.md#unicodebidiproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26410

___

### vectorEffect

• `Optional` **vectorEffect**: [`VectorEffectProperty`](../modules/akashaproject_design_system._internal_.md#vectoreffectproperty) \| [`VectorEffectProperty`](../modules/akashaproject_design_system._internal_.md#vectoreffectproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26411

___

### visibility

• `Optional` **visibility**: [`VisibilityProperty`](../modules/akashaproject_design_system._internal_.md#visibilityproperty) \| [`VisibilityProperty`](../modules/akashaproject_design_system._internal_.md#visibilityproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26412

___

### whiteSpace

• `Optional` **whiteSpace**: [`WhiteSpaceProperty`](../modules/akashaproject_design_system._internal_.md#whitespaceproperty) \| [`WhiteSpaceProperty`](../modules/akashaproject_design_system._internal_.md#whitespaceproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26413

___

### wordSpacing

• `Optional` **wordSpacing**: [`WordSpacingProperty`](../modules/akashaproject_design_system._internal_.md#wordspacingproperty)<`TLength`\> \| [`WordSpacingProperty`](../modules/akashaproject_design_system._internal_.md#wordspacingproperty)<`TLength`\>[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26414

___

### writingMode

• `Optional` **writingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26415
