[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / StandardProperties

# Interface: StandardProperties<TLength, TTime\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).StandardProperties

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` & {} \| ``0`` |
| `TTime` | `string` & {} |

## Hierarchy

- [`StandardLonghandProperties`](akashaproject_design_system._internal_.StandardLonghandProperties.md)<`TLength`, `TTime`\>

- [`StandardShorthandProperties`](akashaproject_design_system._internal_.StandardShorthandProperties.md)<`TLength`, `TTime`\>

  ↳ **`StandardProperties`**

  ↳↳ [`Properties`](akashaproject_design_system._internal_.Properties.md)

## Table of contents

### Properties

- [accentColor](akashaproject_design_system._internal_.StandardProperties.md#accentcolor)
- [alignContent](akashaproject_design_system._internal_.StandardProperties.md#aligncontent)
- [alignItems](akashaproject_design_system._internal_.StandardProperties.md#alignitems)
- [alignSelf](akashaproject_design_system._internal_.StandardProperties.md#alignself)
- [alignTracks](akashaproject_design_system._internal_.StandardProperties.md#aligntracks)
- [all](akashaproject_design_system._internal_.StandardProperties.md#all)
- [animation](akashaproject_design_system._internal_.StandardProperties.md#animation)
- [animationDelay](akashaproject_design_system._internal_.StandardProperties.md#animationdelay)
- [animationDirection](akashaproject_design_system._internal_.StandardProperties.md#animationdirection)
- [animationDuration](akashaproject_design_system._internal_.StandardProperties.md#animationduration)
- [animationFillMode](akashaproject_design_system._internal_.StandardProperties.md#animationfillmode)
- [animationIterationCount](akashaproject_design_system._internal_.StandardProperties.md#animationiterationcount)
- [animationName](akashaproject_design_system._internal_.StandardProperties.md#animationname)
- [animationPlayState](akashaproject_design_system._internal_.StandardProperties.md#animationplaystate)
- [animationTimingFunction](akashaproject_design_system._internal_.StandardProperties.md#animationtimingfunction)
- [appearance](akashaproject_design_system._internal_.StandardProperties.md#appearance)
- [aspectRatio](akashaproject_design_system._internal_.StandardProperties.md#aspectratio)
- [backdropFilter](akashaproject_design_system._internal_.StandardProperties.md#backdropfilter)
- [backfaceVisibility](akashaproject_design_system._internal_.StandardProperties.md#backfacevisibility)
- [background](akashaproject_design_system._internal_.StandardProperties.md#background)
- [backgroundAttachment](akashaproject_design_system._internal_.StandardProperties.md#backgroundattachment)
- [backgroundBlendMode](akashaproject_design_system._internal_.StandardProperties.md#backgroundblendmode)
- [backgroundClip](akashaproject_design_system._internal_.StandardProperties.md#backgroundclip)
- [backgroundColor](akashaproject_design_system._internal_.StandardProperties.md#backgroundcolor)
- [backgroundImage](akashaproject_design_system._internal_.StandardProperties.md#backgroundimage)
- [backgroundOrigin](akashaproject_design_system._internal_.StandardProperties.md#backgroundorigin)
- [backgroundPosition](akashaproject_design_system._internal_.StandardProperties.md#backgroundposition)
- [backgroundPositionX](akashaproject_design_system._internal_.StandardProperties.md#backgroundpositionx)
- [backgroundPositionY](akashaproject_design_system._internal_.StandardProperties.md#backgroundpositiony)
- [backgroundRepeat](akashaproject_design_system._internal_.StandardProperties.md#backgroundrepeat)
- [backgroundSize](akashaproject_design_system._internal_.StandardProperties.md#backgroundsize)
- [blockOverflow](akashaproject_design_system._internal_.StandardProperties.md#blockoverflow)
- [blockSize](akashaproject_design_system._internal_.StandardProperties.md#blocksize)
- [border](akashaproject_design_system._internal_.StandardProperties.md#border)
- [borderBlock](akashaproject_design_system._internal_.StandardProperties.md#borderblock)
- [borderBlockColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockcolor)
- [borderBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#borderblockend)
- [borderBlockEndColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockendcolor)
- [borderBlockEndStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockendstyle)
- [borderBlockEndWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockendwidth)
- [borderBlockStart](akashaproject_design_system._internal_.StandardProperties.md#borderblockstart)
- [borderBlockStartColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartcolor)
- [borderBlockStartStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartstyle)
- [borderBlockStartWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartwidth)
- [borderBlockStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockstyle)
- [borderBlockWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockwidth)
- [borderBottom](akashaproject_design_system._internal_.StandardProperties.md#borderbottom)
- [borderBottomColor](akashaproject_design_system._internal_.StandardProperties.md#borderbottomcolor)
- [borderBottomLeftRadius](akashaproject_design_system._internal_.StandardProperties.md#borderbottomleftradius)
- [borderBottomRightRadius](akashaproject_design_system._internal_.StandardProperties.md#borderbottomrightradius)
- [borderBottomStyle](akashaproject_design_system._internal_.StandardProperties.md#borderbottomstyle)
- [borderBottomWidth](akashaproject_design_system._internal_.StandardProperties.md#borderbottomwidth)
- [borderCollapse](akashaproject_design_system._internal_.StandardProperties.md#bordercollapse)
- [borderColor](akashaproject_design_system._internal_.StandardProperties.md#bordercolor)
- [borderEndEndRadius](akashaproject_design_system._internal_.StandardProperties.md#borderendendradius)
- [borderEndStartRadius](akashaproject_design_system._internal_.StandardProperties.md#borderendstartradius)
- [borderImage](akashaproject_design_system._internal_.StandardProperties.md#borderimage)
- [borderImageOutset](akashaproject_design_system._internal_.StandardProperties.md#borderimageoutset)
- [borderImageRepeat](akashaproject_design_system._internal_.StandardProperties.md#borderimagerepeat)
- [borderImageSlice](akashaproject_design_system._internal_.StandardProperties.md#borderimageslice)
- [borderImageSource](akashaproject_design_system._internal_.StandardProperties.md#borderimagesource)
- [borderImageWidth](akashaproject_design_system._internal_.StandardProperties.md#borderimagewidth)
- [borderInline](akashaproject_design_system._internal_.StandardProperties.md#borderinline)
- [borderInlineColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlinecolor)
- [borderInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#borderinlineend)
- [borderInlineEndColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendcolor)
- [borderInlineEndStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendstyle)
- [borderInlineEndWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendwidth)
- [borderInlineStart](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestart)
- [borderInlineStartColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartcolor)
- [borderInlineStartStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartstyle)
- [borderInlineStartWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartwidth)
- [borderInlineStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestyle)
- [borderInlineWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlinewidth)
- [borderLeft](akashaproject_design_system._internal_.StandardProperties.md#borderleft)
- [borderLeftColor](akashaproject_design_system._internal_.StandardProperties.md#borderleftcolor)
- [borderLeftStyle](akashaproject_design_system._internal_.StandardProperties.md#borderleftstyle)
- [borderLeftWidth](akashaproject_design_system._internal_.StandardProperties.md#borderleftwidth)
- [borderRadius](akashaproject_design_system._internal_.StandardProperties.md#borderradius)
- [borderRight](akashaproject_design_system._internal_.StandardProperties.md#borderright)
- [borderRightColor](akashaproject_design_system._internal_.StandardProperties.md#borderrightcolor)
- [borderRightStyle](akashaproject_design_system._internal_.StandardProperties.md#borderrightstyle)
- [borderRightWidth](akashaproject_design_system._internal_.StandardProperties.md#borderrightwidth)
- [borderSpacing](akashaproject_design_system._internal_.StandardProperties.md#borderspacing)
- [borderStartEndRadius](akashaproject_design_system._internal_.StandardProperties.md#borderstartendradius)
- [borderStartStartRadius](akashaproject_design_system._internal_.StandardProperties.md#borderstartstartradius)
- [borderStyle](akashaproject_design_system._internal_.StandardProperties.md#borderstyle)
- [borderTop](akashaproject_design_system._internal_.StandardProperties.md#bordertop)
- [borderTopColor](akashaproject_design_system._internal_.StandardProperties.md#bordertopcolor)
- [borderTopLeftRadius](akashaproject_design_system._internal_.StandardProperties.md#bordertopleftradius)
- [borderTopRightRadius](akashaproject_design_system._internal_.StandardProperties.md#bordertoprightradius)
- [borderTopStyle](akashaproject_design_system._internal_.StandardProperties.md#bordertopstyle)
- [borderTopWidth](akashaproject_design_system._internal_.StandardProperties.md#bordertopwidth)
- [borderWidth](akashaproject_design_system._internal_.StandardProperties.md#borderwidth)
- [bottom](akashaproject_design_system._internal_.StandardProperties.md#bottom)
- [boxDecorationBreak](akashaproject_design_system._internal_.StandardProperties.md#boxdecorationbreak)
- [boxShadow](akashaproject_design_system._internal_.StandardProperties.md#boxshadow)
- [boxSizing](akashaproject_design_system._internal_.StandardProperties.md#boxsizing)
- [breakAfter](akashaproject_design_system._internal_.StandardProperties.md#breakafter)
- [breakBefore](akashaproject_design_system._internal_.StandardProperties.md#breakbefore)
- [breakInside](akashaproject_design_system._internal_.StandardProperties.md#breakinside)
- [captionSide](akashaproject_design_system._internal_.StandardProperties.md#captionside)
- [caretColor](akashaproject_design_system._internal_.StandardProperties.md#caretcolor)
- [clear](akashaproject_design_system._internal_.StandardProperties.md#clear)
- [clipPath](akashaproject_design_system._internal_.StandardProperties.md#clippath)
- [color](akashaproject_design_system._internal_.StandardProperties.md#color)
- [colorAdjust](akashaproject_design_system._internal_.StandardProperties.md#coloradjust)
- [colorScheme](akashaproject_design_system._internal_.StandardProperties.md#colorscheme)
- [columnCount](akashaproject_design_system._internal_.StandardProperties.md#columncount)
- [columnFill](akashaproject_design_system._internal_.StandardProperties.md#columnfill)
- [columnGap](akashaproject_design_system._internal_.StandardProperties.md#columngap)
- [columnRule](akashaproject_design_system._internal_.StandardProperties.md#columnrule)
- [columnRuleColor](akashaproject_design_system._internal_.StandardProperties.md#columnrulecolor)
- [columnRuleStyle](akashaproject_design_system._internal_.StandardProperties.md#columnrulestyle)
- [columnRuleWidth](akashaproject_design_system._internal_.StandardProperties.md#columnrulewidth)
- [columnSpan](akashaproject_design_system._internal_.StandardProperties.md#columnspan)
- [columnWidth](akashaproject_design_system._internal_.StandardProperties.md#columnwidth)
- [columns](akashaproject_design_system._internal_.StandardProperties.md#columns)
- [contain](akashaproject_design_system._internal_.StandardProperties.md#contain)
- [content](akashaproject_design_system._internal_.StandardProperties.md#content)
- [contentVisibility](akashaproject_design_system._internal_.StandardProperties.md#contentvisibility)
- [counterIncrement](akashaproject_design_system._internal_.StandardProperties.md#counterincrement)
- [counterReset](akashaproject_design_system._internal_.StandardProperties.md#counterreset)
- [counterSet](akashaproject_design_system._internal_.StandardProperties.md#counterset)
- [cursor](akashaproject_design_system._internal_.StandardProperties.md#cursor)
- [direction](akashaproject_design_system._internal_.StandardProperties.md#direction)
- [display](akashaproject_design_system._internal_.StandardProperties.md#display)
- [emptyCells](akashaproject_design_system._internal_.StandardProperties.md#emptycells)
- [filter](akashaproject_design_system._internal_.StandardProperties.md#filter)
- [flex](akashaproject_design_system._internal_.StandardProperties.md#flex)
- [flexBasis](akashaproject_design_system._internal_.StandardProperties.md#flexbasis)
- [flexDirection](akashaproject_design_system._internal_.StandardProperties.md#flexdirection)
- [flexFlow](akashaproject_design_system._internal_.StandardProperties.md#flexflow)
- [flexGrow](akashaproject_design_system._internal_.StandardProperties.md#flexgrow)
- [flexShrink](akashaproject_design_system._internal_.StandardProperties.md#flexshrink)
- [flexWrap](akashaproject_design_system._internal_.StandardProperties.md#flexwrap)
- [float](akashaproject_design_system._internal_.StandardProperties.md#float)
- [font](akashaproject_design_system._internal_.StandardProperties.md#font)
- [fontFamily](akashaproject_design_system._internal_.StandardProperties.md#fontfamily)
- [fontFeatureSettings](akashaproject_design_system._internal_.StandardProperties.md#fontfeaturesettings)
- [fontKerning](akashaproject_design_system._internal_.StandardProperties.md#fontkerning)
- [fontLanguageOverride](akashaproject_design_system._internal_.StandardProperties.md#fontlanguageoverride)
- [fontOpticalSizing](akashaproject_design_system._internal_.StandardProperties.md#fontopticalsizing)
- [fontSize](akashaproject_design_system._internal_.StandardProperties.md#fontsize)
- [fontSizeAdjust](akashaproject_design_system._internal_.StandardProperties.md#fontsizeadjust)
- [fontSmooth](akashaproject_design_system._internal_.StandardProperties.md#fontsmooth)
- [fontStretch](akashaproject_design_system._internal_.StandardProperties.md#fontstretch)
- [fontStyle](akashaproject_design_system._internal_.StandardProperties.md#fontstyle)
- [fontSynthesis](akashaproject_design_system._internal_.StandardProperties.md#fontsynthesis)
- [fontVariant](akashaproject_design_system._internal_.StandardProperties.md#fontvariant)
- [fontVariantCaps](akashaproject_design_system._internal_.StandardProperties.md#fontvariantcaps)
- [fontVariantEastAsian](akashaproject_design_system._internal_.StandardProperties.md#fontvarianteastasian)
- [fontVariantLigatures](akashaproject_design_system._internal_.StandardProperties.md#fontvariantligatures)
- [fontVariantNumeric](akashaproject_design_system._internal_.StandardProperties.md#fontvariantnumeric)
- [fontVariantPosition](akashaproject_design_system._internal_.StandardProperties.md#fontvariantposition)
- [fontVariationSettings](akashaproject_design_system._internal_.StandardProperties.md#fontvariationsettings)
- [fontWeight](akashaproject_design_system._internal_.StandardProperties.md#fontweight)
- [forcedColorAdjust](akashaproject_design_system._internal_.StandardProperties.md#forcedcoloradjust)
- [gap](akashaproject_design_system._internal_.StandardProperties.md#gap)
- [grid](akashaproject_design_system._internal_.StandardProperties.md#grid)
- [gridArea](akashaproject_design_system._internal_.StandardProperties.md#gridarea)
- [gridAutoColumns](akashaproject_design_system._internal_.StandardProperties.md#gridautocolumns)
- [gridAutoFlow](akashaproject_design_system._internal_.StandardProperties.md#gridautoflow)
- [gridAutoRows](akashaproject_design_system._internal_.StandardProperties.md#gridautorows)
- [gridColumn](akashaproject_design_system._internal_.StandardProperties.md#gridcolumn)
- [gridColumnEnd](akashaproject_design_system._internal_.StandardProperties.md#gridcolumnend)
- [gridColumnStart](akashaproject_design_system._internal_.StandardProperties.md#gridcolumnstart)
- [gridRow](akashaproject_design_system._internal_.StandardProperties.md#gridrow)
- [gridRowEnd](akashaproject_design_system._internal_.StandardProperties.md#gridrowend)
- [gridRowStart](akashaproject_design_system._internal_.StandardProperties.md#gridrowstart)
- [gridTemplate](akashaproject_design_system._internal_.StandardProperties.md#gridtemplate)
- [gridTemplateAreas](akashaproject_design_system._internal_.StandardProperties.md#gridtemplateareas)
- [gridTemplateColumns](akashaproject_design_system._internal_.StandardProperties.md#gridtemplatecolumns)
- [gridTemplateRows](akashaproject_design_system._internal_.StandardProperties.md#gridtemplaterows)
- [hangingPunctuation](akashaproject_design_system._internal_.StandardProperties.md#hangingpunctuation)
- [height](akashaproject_design_system._internal_.StandardProperties.md#height)
- [hyphens](akashaproject_design_system._internal_.StandardProperties.md#hyphens)
- [imageOrientation](akashaproject_design_system._internal_.StandardProperties.md#imageorientation)
- [imageRendering](akashaproject_design_system._internal_.StandardProperties.md#imagerendering)
- [imageResolution](akashaproject_design_system._internal_.StandardProperties.md#imageresolution)
- [initialLetter](akashaproject_design_system._internal_.StandardProperties.md#initialletter)
- [inlineSize](akashaproject_design_system._internal_.StandardProperties.md#inlinesize)
- [inset](akashaproject_design_system._internal_.StandardProperties.md#inset)
- [insetBlock](akashaproject_design_system._internal_.StandardProperties.md#insetblock)
- [insetBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#insetblockend)
- [insetBlockStart](akashaproject_design_system._internal_.StandardProperties.md#insetblockstart)
- [insetInline](akashaproject_design_system._internal_.StandardProperties.md#insetinline)
- [insetInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#insetinlineend)
- [insetInlineStart](akashaproject_design_system._internal_.StandardProperties.md#insetinlinestart)
- [isolation](akashaproject_design_system._internal_.StandardProperties.md#isolation)
- [justifyContent](akashaproject_design_system._internal_.StandardProperties.md#justifycontent)
- [justifyItems](akashaproject_design_system._internal_.StandardProperties.md#justifyitems)
- [justifySelf](akashaproject_design_system._internal_.StandardProperties.md#justifyself)
- [justifyTracks](akashaproject_design_system._internal_.StandardProperties.md#justifytracks)
- [left](akashaproject_design_system._internal_.StandardProperties.md#left)
- [letterSpacing](akashaproject_design_system._internal_.StandardProperties.md#letterspacing)
- [lineBreak](akashaproject_design_system._internal_.StandardProperties.md#linebreak)
- [lineClamp](akashaproject_design_system._internal_.StandardProperties.md#lineclamp)
- [lineHeight](akashaproject_design_system._internal_.StandardProperties.md#lineheight)
- [lineHeightStep](akashaproject_design_system._internal_.StandardProperties.md#lineheightstep)
- [listStyle](akashaproject_design_system._internal_.StandardProperties.md#liststyle)
- [listStyleImage](akashaproject_design_system._internal_.StandardProperties.md#liststyleimage)
- [listStylePosition](akashaproject_design_system._internal_.StandardProperties.md#liststyleposition)
- [listStyleType](akashaproject_design_system._internal_.StandardProperties.md#liststyletype)
- [margin](akashaproject_design_system._internal_.StandardProperties.md#margin)
- [marginBlock](akashaproject_design_system._internal_.StandardProperties.md#marginblock)
- [marginBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#marginblockend)
- [marginBlockStart](akashaproject_design_system._internal_.StandardProperties.md#marginblockstart)
- [marginBottom](akashaproject_design_system._internal_.StandardProperties.md#marginbottom)
- [marginInline](akashaproject_design_system._internal_.StandardProperties.md#margininline)
- [marginInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#margininlineend)
- [marginInlineStart](akashaproject_design_system._internal_.StandardProperties.md#margininlinestart)
- [marginLeft](akashaproject_design_system._internal_.StandardProperties.md#marginleft)
- [marginRight](akashaproject_design_system._internal_.StandardProperties.md#marginright)
- [marginTop](akashaproject_design_system._internal_.StandardProperties.md#margintop)
- [mask](akashaproject_design_system._internal_.StandardProperties.md#mask)
- [maskBorder](akashaproject_design_system._internal_.StandardProperties.md#maskborder)
- [maskBorderMode](akashaproject_design_system._internal_.StandardProperties.md#maskbordermode)
- [maskBorderOutset](akashaproject_design_system._internal_.StandardProperties.md#maskborderoutset)
- [maskBorderRepeat](akashaproject_design_system._internal_.StandardProperties.md#maskborderrepeat)
- [maskBorderSlice](akashaproject_design_system._internal_.StandardProperties.md#maskborderslice)
- [maskBorderSource](akashaproject_design_system._internal_.StandardProperties.md#maskbordersource)
- [maskBorderWidth](akashaproject_design_system._internal_.StandardProperties.md#maskborderwidth)
- [maskClip](akashaproject_design_system._internal_.StandardProperties.md#maskclip)
- [maskComposite](akashaproject_design_system._internal_.StandardProperties.md#maskcomposite)
- [maskImage](akashaproject_design_system._internal_.StandardProperties.md#maskimage)
- [maskMode](akashaproject_design_system._internal_.StandardProperties.md#maskmode)
- [maskOrigin](akashaproject_design_system._internal_.StandardProperties.md#maskorigin)
- [maskPosition](akashaproject_design_system._internal_.StandardProperties.md#maskposition)
- [maskRepeat](akashaproject_design_system._internal_.StandardProperties.md#maskrepeat)
- [maskSize](akashaproject_design_system._internal_.StandardProperties.md#masksize)
- [maskType](akashaproject_design_system._internal_.StandardProperties.md#masktype)
- [mathStyle](akashaproject_design_system._internal_.StandardProperties.md#mathstyle)
- [maxBlockSize](akashaproject_design_system._internal_.StandardProperties.md#maxblocksize)
- [maxHeight](akashaproject_design_system._internal_.StandardProperties.md#maxheight)
- [maxInlineSize](akashaproject_design_system._internal_.StandardProperties.md#maxinlinesize)
- [maxLines](akashaproject_design_system._internal_.StandardProperties.md#maxlines)
- [maxWidth](akashaproject_design_system._internal_.StandardProperties.md#maxwidth)
- [minBlockSize](akashaproject_design_system._internal_.StandardProperties.md#minblocksize)
- [minHeight](akashaproject_design_system._internal_.StandardProperties.md#minheight)
- [minInlineSize](akashaproject_design_system._internal_.StandardProperties.md#mininlinesize)
- [minWidth](akashaproject_design_system._internal_.StandardProperties.md#minwidth)
- [mixBlendMode](akashaproject_design_system._internal_.StandardProperties.md#mixblendmode)
- [motion](akashaproject_design_system._internal_.StandardProperties.md#motion)
- [motionDistance](akashaproject_design_system._internal_.StandardProperties.md#motiondistance)
- [motionPath](akashaproject_design_system._internal_.StandardProperties.md#motionpath)
- [motionRotation](akashaproject_design_system._internal_.StandardProperties.md#motionrotation)
- [objectFit](akashaproject_design_system._internal_.StandardProperties.md#objectfit)
- [objectPosition](akashaproject_design_system._internal_.StandardProperties.md#objectposition)
- [offset](akashaproject_design_system._internal_.StandardProperties.md#offset)
- [offsetAnchor](akashaproject_design_system._internal_.StandardProperties.md#offsetanchor)
- [offsetDistance](akashaproject_design_system._internal_.StandardProperties.md#offsetdistance)
- [offsetPath](akashaproject_design_system._internal_.StandardProperties.md#offsetpath)
- [offsetRotate](akashaproject_design_system._internal_.StandardProperties.md#offsetrotate)
- [offsetRotation](akashaproject_design_system._internal_.StandardProperties.md#offsetrotation)
- [opacity](akashaproject_design_system._internal_.StandardProperties.md#opacity)
- [order](akashaproject_design_system._internal_.StandardProperties.md#order)
- [orphans](akashaproject_design_system._internal_.StandardProperties.md#orphans)
- [outline](akashaproject_design_system._internal_.StandardProperties.md#outline)
- [outlineColor](akashaproject_design_system._internal_.StandardProperties.md#outlinecolor)
- [outlineOffset](akashaproject_design_system._internal_.StandardProperties.md#outlineoffset)
- [outlineStyle](akashaproject_design_system._internal_.StandardProperties.md#outlinestyle)
- [outlineWidth](akashaproject_design_system._internal_.StandardProperties.md#outlinewidth)
- [overflow](akashaproject_design_system._internal_.StandardProperties.md#overflow)
- [overflowAnchor](akashaproject_design_system._internal_.StandardProperties.md#overflowanchor)
- [overflowBlock](akashaproject_design_system._internal_.StandardProperties.md#overflowblock)
- [overflowClipBox](akashaproject_design_system._internal_.StandardProperties.md#overflowclipbox)
- [overflowClipMargin](akashaproject_design_system._internal_.StandardProperties.md#overflowclipmargin)
- [overflowInline](akashaproject_design_system._internal_.StandardProperties.md#overflowinline)
- [overflowWrap](akashaproject_design_system._internal_.StandardProperties.md#overflowwrap)
- [overflowX](akashaproject_design_system._internal_.StandardProperties.md#overflowx)
- [overflowY](akashaproject_design_system._internal_.StandardProperties.md#overflowy)
- [overscrollBehavior](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehavior)
- [overscrollBehaviorBlock](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorblock)
- [overscrollBehaviorInline](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorinline)
- [overscrollBehaviorX](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorx)
- [overscrollBehaviorY](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviory)
- [padding](akashaproject_design_system._internal_.StandardProperties.md#padding)
- [paddingBlock](akashaproject_design_system._internal_.StandardProperties.md#paddingblock)
- [paddingBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#paddingblockend)
- [paddingBlockStart](akashaproject_design_system._internal_.StandardProperties.md#paddingblockstart)
- [paddingBottom](akashaproject_design_system._internal_.StandardProperties.md#paddingbottom)
- [paddingInline](akashaproject_design_system._internal_.StandardProperties.md#paddinginline)
- [paddingInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#paddinginlineend)
- [paddingInlineStart](akashaproject_design_system._internal_.StandardProperties.md#paddinginlinestart)
- [paddingLeft](akashaproject_design_system._internal_.StandardProperties.md#paddingleft)
- [paddingRight](akashaproject_design_system._internal_.StandardProperties.md#paddingright)
- [paddingTop](akashaproject_design_system._internal_.StandardProperties.md#paddingtop)
- [pageBreakAfter](akashaproject_design_system._internal_.StandardProperties.md#pagebreakafter)
- [pageBreakBefore](akashaproject_design_system._internal_.StandardProperties.md#pagebreakbefore)
- [pageBreakInside](akashaproject_design_system._internal_.StandardProperties.md#pagebreakinside)
- [paintOrder](akashaproject_design_system._internal_.StandardProperties.md#paintorder)
- [perspective](akashaproject_design_system._internal_.StandardProperties.md#perspective)
- [perspectiveOrigin](akashaproject_design_system._internal_.StandardProperties.md#perspectiveorigin)
- [placeContent](akashaproject_design_system._internal_.StandardProperties.md#placecontent)
- [placeItems](akashaproject_design_system._internal_.StandardProperties.md#placeitems)
- [placeSelf](akashaproject_design_system._internal_.StandardProperties.md#placeself)
- [pointerEvents](akashaproject_design_system._internal_.StandardProperties.md#pointerevents)
- [position](akashaproject_design_system._internal_.StandardProperties.md#position)
- [quotes](akashaproject_design_system._internal_.StandardProperties.md#quotes)
- [resize](akashaproject_design_system._internal_.StandardProperties.md#resize)
- [right](akashaproject_design_system._internal_.StandardProperties.md#right)
- [rotate](akashaproject_design_system._internal_.StandardProperties.md#rotate)
- [rowGap](akashaproject_design_system._internal_.StandardProperties.md#rowgap)
- [rubyAlign](akashaproject_design_system._internal_.StandardProperties.md#rubyalign)
- [rubyMerge](akashaproject_design_system._internal_.StandardProperties.md#rubymerge)
- [rubyPosition](akashaproject_design_system._internal_.StandardProperties.md#rubyposition)
- [scale](akashaproject_design_system._internal_.StandardProperties.md#scale)
- [scrollBehavior](akashaproject_design_system._internal_.StandardProperties.md#scrollbehavior)
- [scrollMargin](akashaproject_design_system._internal_.StandardProperties.md#scrollmargin)
- [scrollMarginBlock](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblock)
- [scrollMarginBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblockend)
- [scrollMarginBlockStart](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblockstart)
- [scrollMarginBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginbottom)
- [scrollMarginInline](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininline)
- [scrollMarginInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininlineend)
- [scrollMarginInlineStart](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininlinestart)
- [scrollMarginLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginleft)
- [scrollMarginRight](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginright)
- [scrollMarginTop](akashaproject_design_system._internal_.StandardProperties.md#scrollmargintop)
- [scrollPadding](akashaproject_design_system._internal_.StandardProperties.md#scrollpadding)
- [scrollPaddingBlock](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblock)
- [scrollPaddingBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblockend)
- [scrollPaddingBlockStart](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblockstart)
- [scrollPaddingBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingbottom)
- [scrollPaddingInline](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginline)
- [scrollPaddingInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginlineend)
- [scrollPaddingInlineStart](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginlinestart)
- [scrollPaddingLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingleft)
- [scrollPaddingRight](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingright)
- [scrollPaddingTop](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingtop)
- [scrollSnapAlign](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapalign)
- [scrollSnapMargin](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmargin)
- [scrollSnapMarginBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginbottom)
- [scrollSnapMarginLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginleft)
- [scrollSnapMarginRight](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginright)
- [scrollSnapMarginTop](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmargintop)
- [scrollSnapStop](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapstop)
- [scrollSnapType](akashaproject_design_system._internal_.StandardProperties.md#scrollsnaptype)
- [scrollbarColor](akashaproject_design_system._internal_.StandardProperties.md#scrollbarcolor)
- [scrollbarGutter](akashaproject_design_system._internal_.StandardProperties.md#scrollbargutter)
- [scrollbarWidth](akashaproject_design_system._internal_.StandardProperties.md#scrollbarwidth)
- [shapeImageThreshold](akashaproject_design_system._internal_.StandardProperties.md#shapeimagethreshold)
- [shapeMargin](akashaproject_design_system._internal_.StandardProperties.md#shapemargin)
- [shapeOutside](akashaproject_design_system._internal_.StandardProperties.md#shapeoutside)
- [tabSize](akashaproject_design_system._internal_.StandardProperties.md#tabsize)
- [tableLayout](akashaproject_design_system._internal_.StandardProperties.md#tablelayout)
- [textAlign](akashaproject_design_system._internal_.StandardProperties.md#textalign)
- [textAlignLast](akashaproject_design_system._internal_.StandardProperties.md#textalignlast)
- [textCombineUpright](akashaproject_design_system._internal_.StandardProperties.md#textcombineupright)
- [textDecoration](akashaproject_design_system._internal_.StandardProperties.md#textdecoration)
- [textDecorationColor](akashaproject_design_system._internal_.StandardProperties.md#textdecorationcolor)
- [textDecorationLine](akashaproject_design_system._internal_.StandardProperties.md#textdecorationline)
- [textDecorationSkip](akashaproject_design_system._internal_.StandardProperties.md#textdecorationskip)
- [textDecorationSkipInk](akashaproject_design_system._internal_.StandardProperties.md#textdecorationskipink)
- [textDecorationStyle](akashaproject_design_system._internal_.StandardProperties.md#textdecorationstyle)
- [textDecorationThickness](akashaproject_design_system._internal_.StandardProperties.md#textdecorationthickness)
- [textDecorationWidth](akashaproject_design_system._internal_.StandardProperties.md#textdecorationwidth)
- [textEmphasis](akashaproject_design_system._internal_.StandardProperties.md#textemphasis)
- [textEmphasisColor](akashaproject_design_system._internal_.StandardProperties.md#textemphasiscolor)
- [textEmphasisPosition](akashaproject_design_system._internal_.StandardProperties.md#textemphasisposition)
- [textEmphasisStyle](akashaproject_design_system._internal_.StandardProperties.md#textemphasisstyle)
- [textIndent](akashaproject_design_system._internal_.StandardProperties.md#textindent)
- [textJustify](akashaproject_design_system._internal_.StandardProperties.md#textjustify)
- [textOrientation](akashaproject_design_system._internal_.StandardProperties.md#textorientation)
- [textOverflow](akashaproject_design_system._internal_.StandardProperties.md#textoverflow)
- [textRendering](akashaproject_design_system._internal_.StandardProperties.md#textrendering)
- [textShadow](akashaproject_design_system._internal_.StandardProperties.md#textshadow)
- [textSizeAdjust](akashaproject_design_system._internal_.StandardProperties.md#textsizeadjust)
- [textTransform](akashaproject_design_system._internal_.StandardProperties.md#texttransform)
- [textUnderlineOffset](akashaproject_design_system._internal_.StandardProperties.md#textunderlineoffset)
- [textUnderlinePosition](akashaproject_design_system._internal_.StandardProperties.md#textunderlineposition)
- [top](akashaproject_design_system._internal_.StandardProperties.md#top)
- [touchAction](akashaproject_design_system._internal_.StandardProperties.md#touchaction)
- [transform](akashaproject_design_system._internal_.StandardProperties.md#transform)
- [transformBox](akashaproject_design_system._internal_.StandardProperties.md#transformbox)
- [transformOrigin](akashaproject_design_system._internal_.StandardProperties.md#transformorigin)
- [transformStyle](akashaproject_design_system._internal_.StandardProperties.md#transformstyle)
- [transition](akashaproject_design_system._internal_.StandardProperties.md#transition)
- [transitionDelay](akashaproject_design_system._internal_.StandardProperties.md#transitiondelay)
- [transitionDuration](akashaproject_design_system._internal_.StandardProperties.md#transitionduration)
- [transitionProperty](akashaproject_design_system._internal_.StandardProperties.md#transitionproperty)
- [transitionTimingFunction](akashaproject_design_system._internal_.StandardProperties.md#transitiontimingfunction)
- [translate](akashaproject_design_system._internal_.StandardProperties.md#translate)
- [unicodeBidi](akashaproject_design_system._internal_.StandardProperties.md#unicodebidi)
- [userSelect](akashaproject_design_system._internal_.StandardProperties.md#userselect)
- [verticalAlign](akashaproject_design_system._internal_.StandardProperties.md#verticalalign)
- [visibility](akashaproject_design_system._internal_.StandardProperties.md#visibility)
- [whiteSpace](akashaproject_design_system._internal_.StandardProperties.md#whitespace)
- [widows](akashaproject_design_system._internal_.StandardProperties.md#widows)
- [width](akashaproject_design_system._internal_.StandardProperties.md#width)
- [willChange](akashaproject_design_system._internal_.StandardProperties.md#willchange)
- [wordBreak](akashaproject_design_system._internal_.StandardProperties.md#wordbreak)
- [wordSpacing](akashaproject_design_system._internal_.StandardProperties.md#wordspacing)
- [wordWrap](akashaproject_design_system._internal_.StandardProperties.md#wordwrap)
- [writingMode](akashaproject_design_system._internal_.StandardProperties.md#writingmode)
- [zIndex](akashaproject_design_system._internal_.StandardProperties.md#zindex)
- [zoom](akashaproject_design_system._internal_.StandardProperties.md#zoom)

## Properties

### accentColor

• `Optional` **accentColor**: [`AccentColor`](../modules/akashaproject_design_system._internal_.md#accentcolor)

The **`accent-color`** CSS property sets the color of the elements accent. An accent appears in elements such as `<input>` of `type="checkbox"`, or `type="radio"`.

**Syntax**: `auto | <color>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **93** | **92**  |   No   | **93** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/accent-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[accentColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#accentcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:25

___

### alignContent

• `Optional` **alignContent**: [`AlignContent`](../modules/akashaproject_design_system._internal_.md#aligncontent)

The CSS **`align-content`** property sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

**Syntax**: `normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position>`

**Initial value**: `normal`

---

_Supported in Flex Layout_

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **28**  |  **9**  | **12** | **11** |
| 21 _-x-_ |         | 7 _-x-_ |        |        |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/align-content

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[alignContent](akashaproject_design_system._internal_.StandardLonghandProperties.md#aligncontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:54

___

### alignItems

• `Optional` **alignItems**: [`AlignItems`](../modules/akashaproject_design_system._internal_.md#alignitems)

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

**Syntax**: `normal | stretch | <baseline-position> | [ <overflow-position>? <self-position> ]`

**Initial value**: `normal`

---

_Supported in Flex Layout_

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **52**  | **20**  |  **9**  | **12** | **11** |
| 21 _-x-_ |         | 7 _-x-_ |        |        |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/align-items

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[alignItems](akashaproject_design_system._internal_.StandardLonghandProperties.md#alignitems)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:83

___

### alignSelf

• `Optional` **alignSelf**: [`AlignSelf`](../modules/akashaproject_design_system._internal_.md#alignself)

The **`align-self`** CSS property overrides a grid or flex item's `align-items` value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

---

_Supported in Flex Layout_

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **36**  | **20**  |   **9**   | **12** | **11** |
| 21 _-x-_ |         | 6.1 _-x-_ |        |        |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  |      IE      |
| :----: | :-----: | :------: | :----: | :----------: |
| **57** | **52**  | **10.1** | **16** | **10** _-x-_ |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/align-self

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[alignSelf](akashaproject_design_system._internal_.StandardLonghandProperties.md#alignself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:112

___

### alignTracks

• `Optional` **alignTracks**: [`AlignTracks`](../modules/akashaproject_design_system._internal_.md#aligntracks)

The **`align-tracks`** CSS property sets the alignment in the masonry axis for grid containers that have masonry in their block axis.

**Syntax**: `[ normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position> ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   n/a   |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/align-tracks

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[alignTracks](akashaproject_design_system._internal_.StandardLonghandProperties.md#aligntracks)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:126

___

### all

• `Optional` **all**: [`Globals`](../modules/akashaproject_design_system._internal_.md#globals)

The `**all**` shorthand CSS property resets all of an element's properties except `unicode-bidi`, `direction`, and CSS Custom Properties. It can set properties to their initial or inherited values, or to the values specified in another stylesheet origin.

**Syntax**: `initial | inherit | unset | revert`

**Initial value**: There is no practical initial value for it.

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **37** | **27**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/all

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[all](akashaproject_design_system._internal_.StandardShorthandProperties.md#all)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5146

___

### animation

• `Optional` **animation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`TTime`\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[animation](akashaproject_design_system._internal_.StandardShorthandProperties.md#animation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5159

___

### animationDelay

• `Optional` **animationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`TTime`\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-delay

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationDelay](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:141

___

### animationDirection

• `Optional` **animationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-direction

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationDirection](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:156

___

### animationDuration

• `Optional` **animationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`TTime`\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-duration

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationDuration](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:171

___

### animationFillMode

• `Optional` **animationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 5 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-fill-mode

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationFillMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:186

___

### animationIterationCount

• `Optional` **animationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-iteration-count

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationIterationCount](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:201

___

### animationName

• `Optional` **animationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-name

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationName](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:216

___

### animationPlayState

• `Optional` **animationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-play-state

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationPlayState](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:231

___

### animationTimingFunction

• `Optional` **animationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-timing-function

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[animationTimingFunction](akashaproject_design_system._internal_.StandardLonghandProperties.md#animationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:246

___

### appearance

• `Optional` **appearance**: [`Appearance`](../modules/akashaproject_design_system._internal_.md#appearance)

The `**appearance**` CSS property is used to display an element using platform-native styling, based on the operating system's theme. The **`-moz-appearance`** and **`-webkit-appearance`** properties are non-standard versions of this property, used (respectively) by Gecko (Firefox) and by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support **`-webkit-appearance`**, for compatibility reasons.

**Syntax**: `none | auto | textfield | menulist-button | <compat-auto>`

**Initial value**: `auto`

| Chrome  | Firefox |   Safari    |   Edge   | IE  |
| :-----: | :-----: | :---------: | :------: | :-: |
| **84**  | **80**  | **3** _-x-_ |  **84**  | No  |
| 1 _-x-_ | 1 _-x-_ |             | 12 _-x-_ |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/appearance

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[appearance](akashaproject_design_system._internal_.StandardLonghandProperties.md#appearance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:261

___

### aspectRatio

• `Optional` **aspectRatio**: [`AspectRatio`](../modules/akashaproject_design_system._internal_.md#aspectratio)

The **`aspect-ratio`**  CSS property sets a **preferred aspect ratio** for the box, which will be used in the calculation of auto sizes and some other layout functions.

**Syntax**: `auto | <ratio>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **88** | **89**  | **15** | **88** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/aspect-ratio

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[aspectRatio](akashaproject_design_system._internal_.StandardLonghandProperties.md#aspectratio)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:275

___

### backdropFilter

• `Optional` **backdropFilter**: [`BackdropFilter`](../modules/akashaproject_design_system._internal_.md#backdropfilter)

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

| Chrome | Firefox |   Safari    |  Edge  | IE  |
| :----: | :-----: | :---------: | :----: | :-: |
| **76** |   n/a   | **9** _-x-_ | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/backdrop-filter

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backdropFilter](akashaproject_design_system._internal_.StandardLonghandProperties.md#backdropfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:289

___

### backfaceVisibility

• `Optional` **backfaceVisibility**: [`BackfaceVisibility`](../modules/akashaproject_design_system._internal_.md#backfacevisibility)

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

|  Chrome  | Firefox  |    Safari     |  Edge  |   IE   |
| :------: | :------: | :-----------: | :----: | :----: |
|  **36**  |  **16**  | **5.1** _-x-_ | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ |               |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/backface-visibility

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backfaceVisibility](akashaproject_design_system._internal_.StandardLonghandProperties.md#backfacevisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:304

___

### background

• `Optional` **background**: [`Background`](../modules/akashaproject_design_system._internal_.md#background)<`TLength`\>

The **`background`** shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.

**Syntax**: `[ <bg-layer> , ]* <final-bg-layer>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[background](akashaproject_design_system._internal_.StandardShorthandProperties.md#background)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5171

___

### backgroundAttachment

• `Optional` **backgroundAttachment**: [`BackgroundAttachment`](../modules/akashaproject_design_system._internal_.md#backgroundattachment)

The **`background-attachment`** CSS property sets whether a background image's position is fixed within the viewport, or scrolls with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-attachment

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundAttachment](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundattachment)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:318

___

### backgroundBlendMode

• `Optional` **backgroundBlendMode**: [`BackgroundBlendMode`](../modules/akashaproject_design_system._internal_.md#backgroundblendmode)

The **`background-blend-mode`** CSS property sets how an element's background images should blend with each other and with the element's background color.

**Syntax**: `<blend-mode>#`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **35** | **30**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-blend-mode

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundBlendMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundblendmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:332

___

### backgroundClip

• `Optional` **backgroundClip**: [`BackgroundClip`](../modules/akashaproject_design_system._internal_.md#backgroundclip)

The **`background-clip`** CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

**Syntax**: `<box>#`

**Initial value**: `border-box`

| Chrome | Firefox |   Safari    |  Edge  |  IE   |
| :----: | :-----: | :---------: | :----: | :---: |
| **1**  |  **4**  | **3** _-x-_ | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-clip

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundClip](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:346

___

### backgroundColor

• `Optional` **backgroundColor**: [`BackgroundColor`](../modules/akashaproject_design_system._internal_.md#backgroundcolor)

The **`background-color`** CSS property sets the background color of an element.

**Syntax**: `<color>`

**Initial value**: `transparent`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:360

___

### backgroundImage

• `Optional` **backgroundImage**: [`BackgroundImage`](../modules/akashaproject_design_system._internal_.md#backgroundimage)

The **`background-image`** CSS property sets one or more background images on an element.

**Syntax**: `<bg-image>#`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-image

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundImage](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:374

___

### backgroundOrigin

• `Optional` **backgroundOrigin**: [`BackgroundOrigin`](../modules/akashaproject_design_system._internal_.md#backgroundorigin)

The **`background-origin`** CSS property sets the background's origin: from the border start, inside the border, or inside the padding.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **4**  | **3**  | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-origin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundOrigin](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:388

___

### backgroundPosition

• `Optional` **backgroundPosition**: [`BackgroundPosition`](../modules/akashaproject_design_system._internal_.md#backgroundposition)<`TLength`\>

The **`background-position`** CSS property sets the initial position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `<bg-position>#`

**Initial value**: `0% 0%`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[backgroundPosition](akashaproject_design_system._internal_.StandardShorthandProperties.md#backgroundposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5185

___

### backgroundPositionX

• `Optional` **backgroundPositionX**: [`BackgroundPositionX`](../modules/akashaproject_design_system._internal_.md#backgroundpositionx)<`TLength`\>

The **`background-position-x`** CSS property sets the initial horizontal position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `[ center | [ [ left | right | x-start | x-end ]? <length-percentage>? ]! ]#`

**Initial value**: `left`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-x

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundPositionX](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundpositionx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:402

___

### backgroundPositionY

• `Optional` **backgroundPositionY**: [`BackgroundPositionY`](../modules/akashaproject_design_system._internal_.md#backgroundpositiony)<`TLength`\>

The **`background-position-y`** CSS property sets the initial vertical position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `[ center | [ [ top | bottom | y-start | y-end ]? <length-percentage>? ]! ]#`

**Initial value**: `top`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-y

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundPositionY](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundpositiony)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:416

___

### backgroundRepeat

• `Optional` **backgroundRepeat**: [`BackgroundRepeat`](../modules/akashaproject_design_system._internal_.md#backgroundrepeat)

The **`background-repeat`** CSS property sets how background images are repeated. A background image can be repeated along the horizontal and vertical axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-repeat

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundRepeat](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:430

___

### backgroundSize

• `Optional` **backgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`TLength`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **3**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[backgroundSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#backgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:445

___

### blockOverflow

• `Optional` **blockOverflow**: [`BlockOverflow`](../modules/akashaproject_design_system._internal_.md#blockoverflow)

**Syntax**: `clip | ellipsis | <string>`

**Initial value**: `clip`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[blockOverflow](akashaproject_design_system._internal_.StandardLonghandProperties.md#blockoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:451

___

### blockSize

• `Optional` **blockSize**: [`BlockSize`](../modules/akashaproject_design_system._internal_.md#blocksize)<`TLength`\>

The **`block-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/block-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[blockSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#blocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:465

___

### border

• `Optional` **border**: [`Border`](../modules/akashaproject_design_system._internal_.md#border)<`TLength`\>

The **`border`** shorthand CSS property sets an element's border. It sets the values of `border-width`, `border-style`, and `border-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[border](akashaproject_design_system._internal_.StandardShorthandProperties.md#border)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5197

___

### borderBlock

• `Optional` **borderBlock**: [`BorderBlock`](../modules/akashaproject_design_system._internal_.md#borderblock)<`TLength`\>

The **`border-block`** CSS property is a shorthand property for setting the individual logical block border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderBlock](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5209

___

### borderBlockColor

• `Optional` **borderBlockColor**: [`BorderBlockColor`](../modules/akashaproject_design_system._internal_.md#borderblockcolor)

The **`border-block-color`** CSS property defines the color of the logical block borders of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color` and `border-bottom-color`, or `border-right-color` and `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>{1,2}`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:479

___

### borderBlockEnd

• `Optional` **borderBlockEnd**: [`BorderBlockEnd`](../modules/akashaproject_design_system._internal_.md#borderblockend)<`TLength`\>

The **`border-block-end`** CSS property is a shorthand property for setting the individual logical block-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderBlockEnd](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5221

___

### borderBlockEndColor

• `Optional` **borderBlockEndColor**: [`BorderBlockEndColor`](../modules/akashaproject_design_system._internal_.md#borderblockendcolor)

The **`border-block-end-color`** CSS property defines the color of the logical block-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockEndColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockendcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:493

___

### borderBlockEndStyle

• `Optional` **borderBlockEndStyle**: [`BorderBlockEndStyle`](../modules/akashaproject_design_system._internal_.md#borderblockendstyle)

The **`border-block-end-style`** CSS property defines the style of the logical block-end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockEndStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:507

___

### borderBlockEndWidth

• `Optional` **borderBlockEndWidth**: [`BorderBlockEndWidth`](../modules/akashaproject_design_system._internal_.md#borderblockendwidth)<`TLength`\>

The **`border-block-end-width`** CSS property defines the width of the logical block-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockEndWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:521

___

### borderBlockStart

• `Optional` **borderBlockStart**: [`BorderBlockStart`](../modules/akashaproject_design_system._internal_.md#borderblockstart)<`TLength`\>

The **`border-block-start`** CSS property is a shorthand property for setting the individual logical block-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderBlockStart](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5233

___

### borderBlockStartColor

• `Optional` **borderBlockStartColor**: [`BorderBlockStartColor`](../modules/akashaproject_design_system._internal_.md#borderblockstartcolor)

The **`border-block-start-color`** CSS property defines the color of the logical block-start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockStartColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockstartcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:535

___

### borderBlockStartStyle

• `Optional` **borderBlockStartStyle**: [`BorderBlockStartStyle`](../modules/akashaproject_design_system._internal_.md#borderblockstartstyle)

The **`border-block-start-style`** CSS property defines the style of the logical block start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockStartStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockstartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:549

___

### borderBlockStartWidth

• `Optional` **borderBlockStartWidth**: [`BorderBlockStartWidth`](../modules/akashaproject_design_system._internal_.md#borderblockstartwidth)<`TLength`\>

The **`border-block-start-width`** CSS property defines the width of the logical block-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockStartWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockstartwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:563

___

### borderBlockStyle

• `Optional` **borderBlockStyle**: [`BorderBlockStyle`](../modules/akashaproject_design_system._internal_.md#borderblockstyle)

The **`border-block-style`** CSS property defines the style of the logical block borders of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style` and `border-bottom-style`, or `border-left-style` and `border-right-style` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:577

___

### borderBlockWidth

• `Optional` **borderBlockWidth**: [`BorderBlockWidth`](../modules/akashaproject_design_system._internal_.md#borderblockwidth)<`TLength`\>

The **`border-block-width`** CSS property defines the width of the logical block borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBlockWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderblockwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:591

___

### borderBottom

• `Optional` **borderBottom**: [`BorderBottom`](../modules/akashaproject_design_system._internal_.md#borderbottom)<`TLength`\>

The **`border-bottom`** shorthand CSS property sets an element's bottom border. It sets the values of `border-bottom-width`, `border-bottom-style` and `border-bottom-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderBottom](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5245

___

### borderBottomColor

• `Optional` **borderBottomColor**: [`BorderBottomColor`](../modules/akashaproject_design_system._internal_.md#borderbottomcolor)

The **`border-bottom-color`** CSS property sets the color of an element's bottom border. It can also be set with the shorthand CSS properties `border-color` or `border-bottom`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBottomColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderbottomcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:605

___

### borderBottomLeftRadius

• `Optional` **borderBottomLeftRadius**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`TLength`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-left-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBottomLeftRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderbottomleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:620

___

### borderBottomRightRadius

• `Optional` **borderBottomRightRadius**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`TLength`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-right-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBottomRightRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderbottomrightradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:635

___

### borderBottomStyle

• `Optional` **borderBottomStyle**: [`BorderBottomStyle`](../modules/akashaproject_design_system._internal_.md#borderbottomstyle)

The **`border-bottom-style`** CSS property sets the line style of an element's bottom `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBottomStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderbottomstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:649

___

### borderBottomWidth

• `Optional` **borderBottomWidth**: [`BorderBottomWidth`](../modules/akashaproject_design_system._internal_.md#borderbottomwidth)<`TLength`\>

The **`border-bottom-width`** CSS property sets the width of the bottom border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderBottomWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderbottomwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:663

___

### borderCollapse

• `Optional` **borderCollapse**: [`BorderCollapse`](../modules/akashaproject_design_system._internal_.md#bordercollapse)

The **`border-collapse`** CSS property sets whether cells inside a `<table>` have shared or separate borders.

**Syntax**: `collapse | separate`

**Initial value**: `separate`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-collapse

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderCollapse](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordercollapse)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:677

___

### borderColor

• `Optional` **borderColor**: [`BorderColor`](../modules/akashaproject_design_system._internal_.md#bordercolor)

The **`border-color`** shorthand CSS property sets the color of an element's border.

**Syntax**: `<color>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-color

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderColor](akashaproject_design_system._internal_.StandardShorthandProperties.md#bordercolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5257

___

### borderEndEndRadius

• `Optional` **borderEndEndRadius**: [`BorderEndEndRadius`](../modules/akashaproject_design_system._internal_.md#borderendendradius)<`TLength`\>

The **`border-end-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-end-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderEndEndRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderendendradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:691

___

### borderEndStartRadius

• `Optional` **borderEndStartRadius**: [`BorderEndStartRadius`](../modules/akashaproject_design_system._internal_.md#borderendstartradius)<`TLength`\>

The **`border-end-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-start-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderEndStartRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderendstartradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:705

___

### borderImage

• `Optional` **borderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

| Chrome  |  Firefox  | Safari  |  Edge  |   IE   |
| :-----: | :-------: | :-----: | :----: | :----: |
| **16**  |  **15**   |  **6**  | **12** | **11** |
| 7 _-x-_ | 3.5 _-x-_ | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderImage](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5270

___

### borderImageOutset

• `Optional` **borderImageOutset**: [`BorderImageOutset`](../modules/akashaproject_design_system._internal_.md#borderimageoutset)<`TLength`\>

The **`border-image-outset`** CSS property sets the distance by which an element's border image is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-outset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderImageOutset](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderimageoutset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:719

___

### borderImageRepeat

• `Optional` **borderImageRepeat**: [`BorderImageRepeat`](../modules/akashaproject_design_system._internal_.md#borderimagerepeat)

The **`border-image-repeat`** CSS property defines how the edge regions of a source image are adjusted to fit the dimensions of an element's border image.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-repeat

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderImageRepeat](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderimagerepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:733

___

### borderImageSlice

• `Optional` **borderImageSlice**: [`BorderImageSlice`](../modules/akashaproject_design_system._internal_.md#borderimageslice)

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-slice

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderImageSlice](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderimageslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:747

___

### borderImageSource

• `Optional` **borderImageSource**: [`BorderImageSource`](../modules/akashaproject_design_system._internal_.md#borderimagesource)

The **`border-image-source`** CSS property sets the source image used to create an element's border image.

**Syntax**: `none | <image>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-source

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderImageSource](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderimagesource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:761

___

### borderImageWidth

• `Optional` **borderImageWidth**: [`BorderImageWidth`](../modules/akashaproject_design_system._internal_.md#borderimagewidth)<`TLength`\>

The **`border-image-width`** CSS property sets the width of an element's border image.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `1`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **13**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderImageWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderimagewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:775

___

### borderInline

• `Optional` **borderInline**: [`BorderInline`](../modules/akashaproject_design_system._internal_.md#borderinline)<`TLength`\>

The **`border-inline`** CSS property is a shorthand property for setting the individual logical inline border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderInline](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5282

___

### borderInlineColor

• `Optional` **borderInlineColor**: [`BorderInlineColor`](../modules/akashaproject_design_system._internal_.md#borderinlinecolor)

The **`border-inline-color`** CSS property defines the color of the logical inline borders of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color` and `border-bottom-color`, or `border-right-color` and `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>{1,2}`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:789

___

### borderInlineEnd

• `Optional` **borderInlineEnd**: [`BorderInlineEnd`](../modules/akashaproject_design_system._internal_.md#borderinlineend)<`TLength`\>

The **`border-inline-end`** CSS property is a shorthand property for setting the individual logical inline-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderInlineEnd](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderinlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5294

___

### borderInlineEndColor

• `Optional` **borderInlineEndColor**: [`BorderInlineEndColor`](../modules/akashaproject_design_system._internal_.md#borderinlineendcolor)

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-color)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineEndColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlineendcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:804

___

### borderInlineEndStyle

• `Optional` **borderInlineEndStyle**: [`BorderInlineEndStyle`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyle)

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-style)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineEndStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlineendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:819

___

### borderInlineEndWidth

• `Optional` **borderInlineEndWidth**: [`BorderInlineEndWidth`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidth)<`TLength`\>

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-width)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineEndWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlineendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:834

___

### borderInlineStart

• `Optional` **borderInlineStart**: [`BorderInlineStart`](../modules/akashaproject_design_system._internal_.md#borderinlinestart)<`TLength`\>

The **`border-inline-start`** CSS property is a shorthand property for setting the individual logical inline-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderInlineStart](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderinlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5306

___

### borderInlineStartColor

• `Optional` **borderInlineStartColor**: [`BorderInlineStartColor`](../modules/akashaproject_design_system._internal_.md#borderinlinestartcolor)

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome |            Firefox            |  Safari  |  Edge  | IE  |
| :----: | :---------------------------: | :------: | :----: | :-: |
| **69** |            **41**             | **12.1** | **79** | No  |
|        | 3 _(-moz-border-start-color)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineStartColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinestartcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:849

___

### borderInlineStartStyle

• `Optional` **borderInlineStartStyle**: [`BorderInlineStartStyle`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyle)

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome |            Firefox            |  Safari  |  Edge  | IE  |
| :----: | :---------------------------: | :------: | :----: | :-: |
| **69** |            **41**             | **12.1** | **79** | No  |
|        | 3 _(-moz-border-start-style)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineStartStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinestartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:864

___

### borderInlineStartWidth

• `Optional` **borderInlineStartWidth**: [`BorderInlineStartWidth`](../modules/akashaproject_design_system._internal_.md#borderinlinestartwidth)<`TLength`\>

The **`border-inline-start-width`** CSS property defines the width of the logical inline-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineStartWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinestartwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:878

___

### borderInlineStyle

• `Optional` **borderInlineStyle**: [`BorderInlineStyle`](../modules/akashaproject_design_system._internal_.md#borderinlinestyle)

The **`border-inline-style`** CSS property defines the style of the logical inline borders of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style` and `border-bottom-style`, or `border-left-style` and `border-right-style` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:892

___

### borderInlineWidth

• `Optional` **borderInlineWidth**: [`BorderInlineWidth`](../modules/akashaproject_design_system._internal_.md#borderinlinewidth)<`TLength`\>

The **`border-inline-width`** CSS property defines the width of the logical inline borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderInlineWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderinlinewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:906

___

### borderLeft

• `Optional` **borderLeft**: [`BorderLeft`](../modules/akashaproject_design_system._internal_.md#borderleft)<`TLength`\>

The **`border-left`** shorthand CSS property sets all the properties of an element's left border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderLeft](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5318

___

### borderLeftColor

• `Optional` **borderLeftColor**: [`BorderLeftColor`](../modules/akashaproject_design_system._internal_.md#borderleftcolor)

The **`border-left-color`** CSS property sets the color of an element's left border. It can also be set with the shorthand CSS properties `border-color` or `border-left`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderLeftColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderleftcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:920

___

### borderLeftStyle

• `Optional` **borderLeftStyle**: [`BorderLeftStyle`](../modules/akashaproject_design_system._internal_.md#borderleftstyle)

The **`border-left-style`** CSS property sets the line style of an element's left `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderLeftStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderleftstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:934

___

### borderLeftWidth

• `Optional` **borderLeftWidth**: [`BorderLeftWidth`](../modules/akashaproject_design_system._internal_.md#borderleftwidth)<`TLength`\>

The **`border-left-width`** CSS property sets the width of the left border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderLeftWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderleftwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:948

___

### borderRadius

• `Optional` **borderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`TLength`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-radius

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderRadius](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5331

___

### borderRight

• `Optional` **borderRight**: [`BorderRight`](../modules/akashaproject_design_system._internal_.md#borderright)<`TLength`\>

The **`border-right`** shorthand CSS property sets all the properties of an element's right border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderRight](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5343

___

### borderRightColor

• `Optional` **borderRightColor**: [`BorderRightColor`](../modules/akashaproject_design_system._internal_.md#borderrightcolor)

The **`border-right-color`** CSS property sets the color of an element's right border. It can also be set with the shorthand CSS properties `border-color` or `border-right`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderRightColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderrightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:962

___

### borderRightStyle

• `Optional` **borderRightStyle**: [`BorderRightStyle`](../modules/akashaproject_design_system._internal_.md#borderrightstyle)

The **`border-right-style`** CSS property sets the line style of an element's right `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderRightStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderrightstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:976

___

### borderRightWidth

• `Optional` **borderRightWidth**: [`BorderRightWidth`](../modules/akashaproject_design_system._internal_.md#borderrightwidth)<`TLength`\>

The **`border-right-width`** CSS property sets the width of the right border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderRightWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderrightwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:990

___

### borderSpacing

• `Optional` **borderSpacing**: [`BorderSpacing`](../modules/akashaproject_design_system._internal_.md#borderspacing)<`TLength`\>

The **`border-spacing`** CSS property sets the distance between the borders of adjacent `<table>` cells. This property applies only when `border-collapse` is `separate`.

**Syntax**: `<length> <length>?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-spacing

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderSpacing](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1004

___

### borderStartEndRadius

• `Optional` **borderStartEndRadius**: [`BorderStartEndRadius`](../modules/akashaproject_design_system._internal_.md#borderstartendradius)<`TLength`\>

The **`border-start-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-end-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderStartEndRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderstartendradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1018

___

### borderStartStartRadius

• `Optional` **borderStartStartRadius**: [`BorderStartStartRadius`](../modules/akashaproject_design_system._internal_.md#borderstartstartradius)<`TLength`\>

The **`border-start-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-start-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderStartStartRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#borderstartstartradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1032

___

### borderStyle

• `Optional` **borderStyle**: [`BorderStyle`](../modules/akashaproject_design_system._internal_.md#borderstyle)

The **`border-style`** shorthand CSS property sets the line style for all four sides of an element's border.

**Syntax**: `<line-style>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-style

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderStyle](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5355

___

### borderTop

• `Optional` **borderTop**: [`BorderTop`](../modules/akashaproject_design_system._internal_.md#bordertop)<`TLength`\>

The **`border-top`** shorthand CSS property sets all the properties of an element's top border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderTop](akashaproject_design_system._internal_.StandardShorthandProperties.md#bordertop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5367

___

### borderTopColor

• `Optional` **borderTopColor**: [`BorderTopColor`](../modules/akashaproject_design_system._internal_.md#bordertopcolor)

The **`border-top-color`** CSS property sets the color of an element's top border. It can also be set with the shorthand CSS properties `border-color` or `border-top`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderTopColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordertopcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1046

___

### borderTopLeftRadius

• `Optional` **borderTopLeftRadius**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`TLength`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-left-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderTopLeftRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordertopleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1061

___

### borderTopRightRadius

• `Optional` **borderTopRightRadius**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`TLength`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-right-radius

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderTopRightRadius](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordertoprightradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1076

___

### borderTopStyle

• `Optional` **borderTopStyle**: [`BorderTopStyle`](../modules/akashaproject_design_system._internal_.md#bordertopstyle)

The **`border-top-style`** CSS property sets the line style of an element's top `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderTopStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordertopstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1090

___

### borderTopWidth

• `Optional` **borderTopWidth**: [`BorderTopWidth`](../modules/akashaproject_design_system._internal_.md#bordertopwidth)<`TLength`\>

The **`border-top-width`** CSS property sets the width of the top border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[borderTopWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#bordertopwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1104

___

### borderWidth

• `Optional` **borderWidth**: [`BorderWidth`](../modules/akashaproject_design_system._internal_.md#borderwidth)<`TLength`\>

The **`border-width`** shorthand CSS property sets the width of an element's border.

**Syntax**: `<line-width>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-width

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[borderWidth](akashaproject_design_system._internal_.StandardShorthandProperties.md#borderwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5379

___

### bottom

• `Optional` **bottom**: [`Bottom`](../modules/akashaproject_design_system._internal_.md#bottom)<`TLength`\>

The **`bottom`** CSS property participates in setting the vertical position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[bottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#bottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1118

___

### boxDecorationBreak

• `Optional` **boxDecorationBreak**: [`BoxDecorationBreak`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreak)

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

|    Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :----------: | :-----: | :---------: | :----------: | :-: |
| **22** _-x-_ | **32**  | **7** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-decoration-break

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[boxDecorationBreak](akashaproject_design_system._internal_.StandardLonghandProperties.md#boxdecorationbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1132

___

### boxShadow

• `Optional` **boxShadow**: [`BoxShadow`](../modules/akashaproject_design_system._internal_.md#boxshadow)

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
| **10**  |  **4**  | **5.1** | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-shadow

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[boxShadow](akashaproject_design_system._internal_.StandardLonghandProperties.md#boxshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1147

___

### boxSizing

• `Optional` **boxSizing**: [`BoxSizing`](../modules/akashaproject_design_system._internal_.md#boxsizing)

The **`box-sizing`** CSS property sets how the total width and height of an element is calculated.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
| **10**  | **29**  | **5.1** | **12** | **8** |
| 1 _-x-_ | 1 _-x-_ | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-sizing

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[boxSizing](akashaproject_design_system._internal_.StandardLonghandProperties.md#boxsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1162

___

### breakAfter

• `Optional` **breakAfter**: [`BreakAfter`](../modules/akashaproject_design_system._internal_.md#breakafter)

The **`break-after`** CSS property sets how page, column, or region breaks should behave after a generated box. If there is no generated box, the property is ignored.

**Syntax**: `auto | avoid | always | all | avoid-page | page | left | right | recto | verso | avoid-column | column | avoid-region | region`

**Initial value**: `auto`

---

_Supported in Multi-column Layout_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  |   No   | **12** | **10** |

---

_Supported in Paged Media_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  | **10** | **12** | **10** |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/break-after

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[breakAfter](akashaproject_design_system._internal_.StandardLonghandProperties.md#breakafter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1190

___

### breakBefore

• `Optional` **breakBefore**: [`BreakBefore`](../modules/akashaproject_design_system._internal_.md#breakbefore)

The **`break-before`** CSS property sets how page, column, or region breaks should behave before a generated box. If there is no generated box, the property is ignored.

**Syntax**: `auto | avoid | always | all | avoid-page | page | left | right | recto | verso | avoid-column | column | avoid-region | region`

**Initial value**: `auto`

---

_Supported in Multi-column Layout_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  |   No   | **12** | **10** |

---

_Supported in Paged Media_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  | **10** | **12** | **10** |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/break-before

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[breakBefore](akashaproject_design_system._internal_.StandardLonghandProperties.md#breakbefore)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1218

___

### breakInside

• `Optional` **breakInside**: [`BreakInside`](../modules/akashaproject_design_system._internal_.md#breakinside)

The **`break-inside`** CSS property sets how page, column, or region breaks should behave inside a generated box. If there is no generated box, the property is ignored.

**Syntax**: `auto | avoid | avoid-page | avoid-column | avoid-region`

**Initial value**: `auto`

---

_Supported in Multi-column Layout_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  | **10** | **12** | **10** |

---

_Supported in Paged Media_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **50** | **65**  | **10** | **12** | **10** |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/break-inside

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[breakInside](akashaproject_design_system._internal_.StandardLonghandProperties.md#breakinside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1246

___

### captionSide

• `Optional` **captionSide**: [`CaptionSide`](../modules/akashaproject_design_system._internal_.md#captionside)

The **`caption-side`** CSS property puts the content of a table's `<caption>` on the specified side. The values are relative to the `writing-mode` of the table.

**Syntax**: `top | bottom | block-start | block-end | inline-start | inline-end`

**Initial value**: `top`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/caption-side

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[captionSide](akashaproject_design_system._internal_.StandardLonghandProperties.md#captionside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1260

___

### caretColor

• `Optional` **caretColor**: [`CaretColor`](../modules/akashaproject_design_system._internal_.md#caretcolor)

The **`caret-color`** CSS property sets the color of the **insertion caret**, the visible marker where the next character typed will be inserted. This is sometimes referred to as the **text input cursor**. The caret appears in elements such as `<input>` or those with the `contenteditable` attribute. The caret is typically a thin vertical line that flashes to help make it more noticeable. By default, it is black, but its color can be altered with this property.

**Syntax**: `auto | <color>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **53**  | **11.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/caret-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[caretColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#caretcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1274

___

### clear

• `Optional` **clear**: [`Clear`](../modules/akashaproject_design_system._internal_.md#clear)

The **`clear`** CSS property sets whether an element must be moved below (cleared) floating elements that precede it. The `clear` property applies to floating and non-floating elements.

**Syntax**: `none | left | right | both | inline-start | inline-end`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/clear

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[clear](akashaproject_design_system._internal_.StandardLonghandProperties.md#clear)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1288

___

### clipPath

• `Optional` **clipPath**: [`ClipPath`](../modules/akashaproject_design_system._internal_.md#clippath)

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **55**  | **3.5** |  **9.1**  | **12** | **10** |
| 23 _-x-_ |         | 6.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/clip-path

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[clipPath](akashaproject_design_system._internal_.StandardLonghandProperties.md#clippath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1303

___

### color

• `Optional` **color**: [`Color`](../modules/akashaproject_design_system._internal_.md#color)

The **`color`** CSS property sets the foreground color value of an element's text and text decorations, and sets the `<currentcolor>` value. `currentcolor` may be used as an indirect value on _other_ properties and is the default for other color properties, such as `border-color`.

**Syntax**: `<color>`

**Initial value**: Varies from one browser to another

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[color](akashaproject_design_system._internal_.StandardLonghandProperties.md#color)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1317

___

### colorAdjust

• `Optional` **colorAdjust**: [`ColorAdjust`](../modules/akashaproject_design_system._internal_.md#coloradjust)

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

|                Chrome                 | Firefox |                Safari                |                 Edge                  | IE  |
| :-----------------------------------: | :-----: | :----------------------------------: | :-----------------------------------: | :-: |
| **49** _(-webkit-print-color-adjust)_ | **48**  | **6** _(-webkit-print-color-adjust)_ | **79** _(-webkit-print-color-adjust)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color-adjust

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[colorAdjust](akashaproject_design_system._internal_.StandardLonghandProperties.md#coloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1331

___

### colorScheme

• `Optional` **colorScheme**: [`ColorScheme`](../modules/akashaproject_design_system._internal_.md#colorscheme)

The **`color-scheme`** CSS property allows an element to indicate which color schemes it can comfortably be rendered in.

**Syntax**: `normal | [ light | dark | <custom-ident> ]+`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **81** |   No    | **13** | **81** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color-scheme

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[colorScheme](akashaproject_design_system._internal_.StandardLonghandProperties.md#colorscheme)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1345

___

### columnCount

• `Optional` **columnCount**: [`ColumnCount`](../modules/akashaproject_design_system._internal_.md#columncount)

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-count

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnCount](akashaproject_design_system._internal_.StandardLonghandProperties.md#columncount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1360

___

### columnFill

• `Optional` **columnFill**: [`ColumnFill`](../modules/akashaproject_design_system._internal_.md#columnfill)

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **50** | **52**  |  **9**  | **12** | **10** |
|        |         | 8 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-fill

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnFill](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1375

___

### columnGap

• `Optional` **columnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`TLength`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

---

_Supported in Flex Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **84** | **63**  | **14.1** | **84** | No  |

---

_Supported in Grid Layout_

|         Chrome         |        Firefox         |          Safari          |  Edge  | IE  |
| :--------------------: | :--------------------: | :----------------------: | :----: | :-: |
|         **66**         |         **61**         |          **12**          | **16** | No  |
| 57 _(grid-column-gap)_ | 52 _(grid-column-gap)_ | 10.1 _(grid-column-gap)_ |        |     |

---

_Supported in Multi-column Layout_

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  | **10**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-gap

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnGap](akashaproject_design_system._internal_.StandardLonghandProperties.md#columngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1413

___

### columnRule

• `Optional` **columnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`TLength`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[columnRule](akashaproject_design_system._internal_.StandardShorthandProperties.md#columnrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5392

___

### columnRuleColor

• `Optional` **columnRuleColor**: [`ColumnRuleColor`](../modules/akashaproject_design_system._internal_.md#columnrulecolor)

The **`column-rule-color`** CSS property sets the color of the line drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnRuleColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnrulecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1428

___

### columnRuleStyle

• `Optional` **columnRuleStyle**: [`ColumnRuleStyle`](../modules/akashaproject_design_system._internal_.md#columnrulestyle)

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnRuleStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1443

___

### columnRuleWidth

• `Optional` **columnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`TLength`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnRuleWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnrulewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1458

___

### columnSpan

• `Optional` **columnSpan**: [`ColumnSpan`](../modules/akashaproject_design_system._internal_.md#columnspan)

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **50**  | **71**  |   **9**   | **12** | **10** |
| 6 _-x-_ |         | 5.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-span

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnSpan](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnspan)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1473

___

### columnWidth

• `Optional` **columnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`TLength`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **50**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[columnWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#columnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1488

___

### columns

• `Optional` **columns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`TLength`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **50** | **52**  |  **9**  | **12** | **10** |
|        |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/columns

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[columns](akashaproject_design_system._internal_.StandardShorthandProperties.md#columns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5405

___

### contain

• `Optional` **contain**: [`Contain`](../modules/akashaproject_design_system._internal_.md#contain)

The **`contain`** CSS property allows an author to indicate that an element and its contents are, as much as possible, _independent_ of the rest of the document tree. This allows the browser to recalculate layout, style, paint, size, or any combination of them for a limited area of the DOM and not the entire page, leading to obvious performance benefits.

**Syntax**: `none | strict | content | [ size || layout || style || paint ]`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **52** | **69**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/contain

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[contain](akashaproject_design_system._internal_.StandardLonghandProperties.md#contain)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1502

___

### content

• `Optional` **content**: [`Content`](../modules/akashaproject_design_system._internal_.md#content)

The **`content`** CSS property replaces an element with a generated value. Objects inserted using the `content` property are **anonymous replaced elements**_._

**Syntax**: `normal | none | [ <content-replacement> | <content-list> ] [/ <string> ]?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/content

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[content](akashaproject_design_system._internal_.StandardLonghandProperties.md#content)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1516

___

### contentVisibility

• `Optional` **contentVisibility**: [`ContentVisibility`](../modules/akashaproject_design_system._internal_.md#contentvisibility)

The **`content-visibility`** CSS property controls whether or not an element renders its contents at all, along with forcing a strong set of containments, allowing user agents to potentially omit large swathes of layout and rendering work until it becomes needed. Basically it enables the user agent to skip an element's rendering work, including layout and painting, until it is needed, makes the initial page load much faster.

**Syntax**: `visible | auto | hidden`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **85** |   No    |   No   | **85** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/content-visibility

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[contentVisibility](akashaproject_design_system._internal_.StandardLonghandProperties.md#contentvisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1530

___

### counterIncrement

• `Optional` **counterIncrement**: [`CounterIncrement`](../modules/akashaproject_design_system._internal_.md#counterincrement)

The **`counter-increment`** CSS property increases or decreases the value of a CSS counter by a given value.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **3**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-increment

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[counterIncrement](akashaproject_design_system._internal_.StandardLonghandProperties.md#counterincrement)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1544

___

### counterReset

• `Optional` **counterReset**: [`CounterReset`](../modules/akashaproject_design_system._internal_.md#counterreset)

The **`counter-reset`** CSS property resets a CSS counter to a given value.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **3**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-reset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[counterReset](akashaproject_design_system._internal_.StandardLonghandProperties.md#counterreset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1558

___

### counterSet

• `Optional` **counterSet**: [`CounterSet`](../modules/akashaproject_design_system._internal_.md#counterset)

The **`counter-set`** CSS property sets a CSS counter to a given value. It manipulates the value of existing counters, and will only create new counters if there isn't already a counter of the given name on the element.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **85** | **68**  |   No   | **85** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-set

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[counterSet](akashaproject_design_system._internal_.StandardLonghandProperties.md#counterset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1572

___

### cursor

• `Optional` **cursor**: [`Cursor`](../modules/akashaproject_design_system._internal_.md#cursor)

The **`cursor`** CSS property sets the type of mouse cursor, if any, to show when the mouse pointer is over an element.

**Syntax**: `[ [ <url> [ <x> <y> ]? , ]* [ auto | default | none | context-menu | help | pointer | progress | wait | cell | crosshair | text | vertical-text | alias | copy | move | no-drop | not-allowed | e-resize | n-resize | ne-resize | nw-resize | s-resize | se-resize | sw-resize | w-resize | ew-resize | ns-resize | nesw-resize | nwse-resize | col-resize | row-resize | all-scroll | zoom-in | zoom-out | grab | grabbing ] ]`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/cursor

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[cursor](akashaproject_design_system._internal_.StandardLonghandProperties.md#cursor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1586

___

### direction

• `Optional` **direction**: [`Direction`](../modules/akashaproject_design_system._internal_.md#direction)

The **`direction`** CSS property sets the direction of text, table columns, and horizontal overflow. Use `rtl` for languages written from right to left (like Hebrew or Arabic), and `ltr` for those written from left to right (like English and most other languages).

**Syntax**: `ltr | rtl`

**Initial value**: `ltr`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **2**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/direction

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[direction](akashaproject_design_system._internal_.StandardLonghandProperties.md#direction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1600

___

### display

• `Optional` **display**: [`Display`](../modules/akashaproject_design_system._internal_.md#display)

The **`display`** CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.

**Syntax**: `[ <display-outside> || <display-inside> ] | <display-listitem> | <display-internal> | <display-box> | <display-legacy>`

**Initial value**: `inline`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/display

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[display](akashaproject_design_system._internal_.StandardLonghandProperties.md#display)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1614

___

### emptyCells

• `Optional` **emptyCells**: [`EmptyCells`](../modules/akashaproject_design_system._internal_.md#emptycells)

The **`empty-cells`** CSS property sets whether borders and backgrounds appear around `<table>` cells that have no visible content.

**Syntax**: `show | hide`

**Initial value**: `show`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/empty-cells

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[emptyCells](akashaproject_design_system._internal_.StandardLonghandProperties.md#emptycells)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1628

___

### filter

• `Optional` **filter**: [`Filter`](../modules/akashaproject_design_system._internal_.md#filter)

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

|  Chrome  | Firefox | Safari  |  Edge  | IE  |
| :------: | :-----: | :-----: | :----: | :-: |
|  **53**  | **35**  | **9.1** | **12** | No  |
| 18 _-x-_ |         | 6 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/filter

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[filter](akashaproject_design_system._internal_.StandardLonghandProperties.md#filter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1643

___

### flex

• `Optional` **flex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`TLength`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[flex](akashaproject_design_system._internal_.StandardShorthandProperties.md#flex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5418

___

### flexBasis

• `Optional` **flexBasis**: [`FlexBasis`](../modules/akashaproject_design_system._internal_.md#flexbasis)<`TLength`\>

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **22**  |  **9**  | **12** | **11** |
| 22 _-x-_ |         | 7 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-basis

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[flexBasis](akashaproject_design_system._internal_.StandardLonghandProperties.md#flexbasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1658

___

### flexDirection

• `Optional` **flexDirection**: [`FlexDirection`](../modules/akashaproject_design_system._internal_.md#flexdirection)

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-direction

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[flexDirection](akashaproject_design_system._internal_.StandardLonghandProperties.md#flexdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1673

___

### flexFlow

• `Optional` **flexFlow**: [`FlexFlow`](../modules/akashaproject_design_system._internal_.md#flexflow)

The **`flex-flow`** CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **28**  |  **9**  | **12** | **11** |
| 21 _-x-_ |         | 7 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-flow

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[flexFlow](akashaproject_design_system._internal_.StandardShorthandProperties.md#flexflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5431

___

### flexGrow

• `Optional` **flexGrow**: [`FlexGrow`](../modules/akashaproject_design_system._internal_.md#flexgrow)

The **`flex-grow`** CSS property sets the flex grow factor of a flex item main size.

**Syntax**: `<number>`

**Initial value**: `0`

|  Chrome  | Firefox | Safari  |  Edge  |            IE            |
| :------: | :-----: | :-----: | :----: | :----------------------: |
|  **29**  | **20**  |  **9**  | **12** |          **11**          |
| 22 _-x-_ |         | 7 _-x-_ |        | 10 _(-ms-flex-positive)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-grow

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[flexGrow](akashaproject_design_system._internal_.StandardLonghandProperties.md#flexgrow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1688

___

### flexShrink

• `Optional` **flexShrink**: [`FlexShrink`](../modules/akashaproject_design_system._internal_.md#flexshrink)

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **20**  |  **9**  | **12** | **10** |
| 22 _-x-_ |         | 8 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-shrink

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[flexShrink](akashaproject_design_system._internal_.StandardLonghandProperties.md#flexshrink)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1703

___

### flexWrap

• `Optional` **flexWrap**: [`FlexWrap`](../modules/akashaproject_design_system._internal_.md#flexwrap)

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **29**  | **28**  |   **9**   | **12** | **11** |
| 21 _-x-_ |         | 6.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-wrap

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[flexWrap](akashaproject_design_system._internal_.StandardLonghandProperties.md#flexwrap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1718

___

### float

• `Optional` **float**: [`Float`](../modules/akashaproject_design_system._internal_.md#float)

The **`float`** CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

**Syntax**: `left | right | none | inline-start | inline-end`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/float

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[float](akashaproject_design_system._internal_.StandardLonghandProperties.md#float)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1732

___

### font

• `Optional` **font**: [`Font`](../modules/akashaproject_design_system._internal_.md#font)

The **`font`** CSS shorthand property sets all the different properties of an element's font. Alternatively, it sets an element's font to a system font.

**Syntax**: `[ [ <'font-style'> || <font-variant-css21> || <'font-weight'> || <'font-stretch'> ]? <'font-size'> [ / <'line-height'> ]? <'font-family'> ] | caption | icon | menu | message-box | small-caption | status-bar`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[font](akashaproject_design_system._internal_.StandardShorthandProperties.md#font)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5443

___

### fontFamily

• `Optional` **fontFamily**: [`FontFamily`](../modules/akashaproject_design_system._internal_.md#fontfamily)

The **`font-family`** CSS property specifies a prioritized list of one or more font family names and/or generic family names for the selected element.

**Syntax**: `[ <family-name> | <generic-family> ]#`

**Initial value**: depends on user agent

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-family

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontFamily](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontfamily)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1746

___

### fontFeatureSettings

• `Optional` **fontFeatureSettings**: [`FontFeatureSettings`](../modules/akashaproject_design_system._internal_.md#fontfeaturesettings)

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **48**  |  **34**  | **9.1** | **15** | **10** |
| 16 _-x-_ | 15 _-x-_ |         |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-feature-settings

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontFeatureSettings](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontfeaturesettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1761

___

### fontKerning

• `Optional` **fontKerning**: [`FontKerning`](../modules/akashaproject_design_system._internal_.md#fontkerning)

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **33** | **32**  |  **9**  | **79** | No  |
|        |         | 6 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-kerning

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontKerning](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontkerning)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1776

___

### fontLanguageOverride

• `Optional` **fontLanguageOverride**: [`FontLanguageOverride`](../modules/akashaproject_design_system._internal_.md#fontlanguageoverride)

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **34**  |   No   |  No  | No  |
|        | 4 _-x-_ |        |      |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-language-override

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontLanguageOverride](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontlanguageoverride)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1791

___

### fontOpticalSizing

• `Optional` **fontOpticalSizing**: [`FontOpticalSizing`](../modules/akashaproject_design_system._internal_.md#fontopticalsizing)

The **`font-optical-sizing`** CSS property sets whether text rendering is optimized for viewing at different sizes.

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **79** | **62**  | **11** | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-optical-sizing

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontOpticalSizing](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontopticalsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1805

___

### fontSize

• `Optional` **fontSize**: [`FontSize`](../modules/akashaproject_design_system._internal_.md#fontsize)<`TLength`\>

The **`font-size`** CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative `<length>` units, such as `em`, `ex`, and so forth.

**Syntax**: `<absolute-size> | <relative-size> | <length-percentage>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1819

___

### fontSizeAdjust

• `Optional` **fontSizeAdjust**: [`FontSizeAdjust`](../modules/akashaproject_design_system._internal_.md#fontsizeadjust)

The **`font-size-adjust`** CSS property sets the size of lower-case letters relative to the current font size (which defines the size of upper-case letters).

**Syntax**: `none | [ ex-height | cap-height | ch-width | ic-width | ic-height ]? [ from-font | <number> ]`

**Initial value**: `none`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |  **1**  |   No   | n/a  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-size-adjust

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontSizeAdjust](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1833

___

### fontSmooth

• `Optional` **fontSmooth**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`TLength`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

|              Chrome              |              Firefox               |              Safari              |               Edge                | IE  |
| :------------------------------: | :--------------------------------: | :------------------------------: | :-------------------------------: | :-: |
| **5** _(-webkit-font-smoothing)_ | **25** _(-moz-osx-font-smoothing)_ | **4** _(-webkit-font-smoothing)_ | **79** _(-webkit-font-smoothing)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-smooth

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontSmooth](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontsmooth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1847

___

### fontStretch

• `Optional` **fontStretch**: [`FontStretch`](../modules/akashaproject_design_system._internal_.md#fontstretch)

The **`font-stretch`** CSS property selects a normal, condensed, or expanded face from a font.

**Syntax**: `<font-stretch-absolute>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **60** |  **9**  | **11** | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-stretch

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontStretch](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontstretch)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1861

___

### fontStyle

• `Optional` **fontStyle**: [`FontStyle`](../modules/akashaproject_design_system._internal_.md#fontstyle)

The **`font-style`** CSS property sets whether a font should be styled with a normal, italic, or oblique face from its `font-family`.

**Syntax**: `normal | italic | oblique <angle>?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1875

___

### fontSynthesis

• `Optional` **fontSynthesis**: [`FontSynthesis`](../modules/akashaproject_design_system._internal_.md#fontsynthesis)

The **`font-synthesis`** CSS property controls which missing typefaces, bold or italic, may be synthesized by the browser.

**Syntax**: `none | [ weight || style || small-caps ]`

**Initial value**: `weight style`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **34**  | **9**  |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-synthesis

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontSynthesis](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontsynthesis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1889

___

### fontVariant

• `Optional` **fontVariant**: [`FontVariant`](../modules/akashaproject_design_system._internal_.md#fontvariant)

The **`font-variant`** CSS shorthand property allows you to set all the font variants for a font.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> || stylistic( <feature-value-name> ) || historical-forms || styleset( <feature-value-name># ) || character-variant( <feature-value-name># ) || swash( <feature-value-name> ) || ornaments( <feature-value-name> ) || annotation( <feature-value-name> ) || [ small-caps | all-small-caps | petite-caps | all-petite-caps | unicase | titling-caps ] || <numeric-figure-values> || <numeric-spacing-values> || <numeric-fraction-values> || ordinal || slashed-zero || <east-asian-variant-values> || <east-asian-width-values> || ruby ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariant](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariant)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1903

___

### fontVariantCaps

• `Optional` **fontVariantCaps**: [`FontVariantCaps`](../modules/akashaproject_design_system._internal_.md#fontvariantcaps)

The **`font-variant-caps`** CSS property controls the use of alternate glyphs for capital letters.

**Syntax**: `normal | small-caps | all-small-caps | petite-caps | all-petite-caps | unicase | titling-caps`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **52** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-caps

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariantCaps](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariantcaps)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1917

___

### fontVariantEastAsian

• `Optional` **fontVariantEastAsian**: [`FontVariantEastAsian`](../modules/akashaproject_design_system._internal_.md#fontvarianteastasian)

The **`font-variant-east-asian`** CSS property controls the use of alternate glyphs for East Asian scripts, like Japanese and Chinese.

**Syntax**: `normal | [ <east-asian-variant-values> || <east-asian-width-values> || ruby ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **63** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-east-asian

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariantEastAsian](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvarianteastasian)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1931

___

### fontVariantLigatures

• `Optional` **fontVariantLigatures**: [`FontVariantLigatures`](../modules/akashaproject_design_system._internal_.md#fontvariantligatures)

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

|  Chrome  | Firefox | Safari  |  Edge  | IE  |
| :------: | :-----: | :-----: | :----: | :-: |
|  **34**  | **34**  | **9.1** | **79** | No  |
| 31 _-x-_ |         | 7 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-ligatures

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariantLigatures](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariantligatures)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1946

___

### fontVariantNumeric

• `Optional` **fontVariantNumeric**: [`FontVariantNumeric`](../modules/akashaproject_design_system._internal_.md#fontvariantnumeric)

The **`font-variant-numeric`** CSS property controls the usage of alternate glyphs for numbers, fractions, and ordinal markers.

**Syntax**: `normal | [ <numeric-figure-values> || <numeric-spacing-values> || <numeric-fraction-values> || ordinal || slashed-zero ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **52** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-numeric

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariantNumeric](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariantnumeric)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1960

___

### fontVariantPosition

• `Optional` **fontVariantPosition**: [`FontVariantPosition`](../modules/akashaproject_design_system._internal_.md#fontvariantposition)

The **`font-variant-position`** CSS property controls the use of alternate, smaller glyphs that are positioned as superscript or subscript.

**Syntax**: `normal | sub | super`

**Initial value**: `normal`

| Chrome | Firefox | Safari  | Edge | IE  |
| :----: | :-----: | :-----: | :--: | :-: |
|   No   | **34**  | **9.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariantPosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariantposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1974

___

### fontVariationSettings

• `Optional` **fontVariationSettings**: [`FontVariationSettings`](../modules/akashaproject_design_system._internal_.md#fontvariationsettings)

The **`font-variation-settings`** CSS property provides low-level control over variable font characteristics, by specifying the four letter axis names of the characteristics you want to vary, along with their values.

**Syntax**: `normal | [ <string> <number> ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **62** | **62**  | **11** | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variation-settings

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontVariationSettings](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontvariationsettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1988

___

### fontWeight

• `Optional` **fontWeight**: [`FontWeight`](../modules/akashaproject_design_system._internal_.md#fontweight)

The **`font-weight`** CSS property sets the weight (or boldness) of the font. The weights available depend on the `font-family` that is currently set.

**Syntax**: `<font-weight-absolute> | bolder | lighter`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-weight

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[fontWeight](akashaproject_design_system._internal_.StandardLonghandProperties.md#fontweight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2002

___

### forcedColorAdjust

• `Optional` **forcedColorAdjust**: [`ForcedColorAdjust`](../modules/akashaproject_design_system._internal_.md#forcedcoloradjust)

The **`forced-color-adjust`** CSS property allows authors to opt certain elements out of forced colors mode. This then restores the control of those values to CSS.

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |              Edge               |                 IE                  |
| :----: | :-----: | :----: | :-----------------------------: | :---------------------------------: |
| **89** |   No    |   No   |             **79**              | **10** _(-ms-high-contrast-adjust)_ |
|        |         |        | 12 _(-ms-high-contrast-adjust)_ |                                     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/forced-color-adjust

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[forcedColorAdjust](akashaproject_design_system._internal_.StandardLonghandProperties.md#forcedcoloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2017

___

### gap

• `Optional` **gap**: [`Gap`](../modules/akashaproject_design_system._internal_.md#gap)<`TLength`\>

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

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[gap](akashaproject_design_system._internal_.StandardShorthandProperties.md#gap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5478

___

### grid

• `Optional` **grid**: [`Grid`](../modules/akashaproject_design_system._internal_.md#grid)

The **`grid`** CSS property is a shorthand property that sets all of the explicit and implicit grid properties in a single declaration.

**Syntax**: `<'grid-template'> | <'grid-template-rows'> / [ auto-flow && dense? ] <'grid-auto-columns'>? | [ auto-flow && dense? ] <'grid-auto-rows'>? / <'grid-template-columns'>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[grid](akashaproject_design_system._internal_.StandardShorthandProperties.md#grid)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5490

___

### gridArea

• `Optional` **gridArea**: [`GridArea`](../modules/akashaproject_design_system._internal_.md#gridarea)

The **`grid-area`** CSS shorthand property specifies a grid item’s size and location within a grid by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the edges of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]{0,3}`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-area

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[gridArea](akashaproject_design_system._internal_.StandardShorthandProperties.md#gridarea)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5502

___

### gridAutoColumns

• `Optional` **gridAutoColumns**: [`GridAutoColumns`](../modules/akashaproject_design_system._internal_.md#gridautocolumns)<`TLength`\>

The **`grid-auto-columns`** CSS property specifies the size of an implicitly-created grid column track or pattern of tracks.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-columns

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridAutoColumns](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridautocolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2031

___

### gridAutoFlow

• `Optional` **gridAutoFlow**: [`GridAutoFlow`](../modules/akashaproject_design_system._internal_.md#gridautoflow)

The **`grid-auto-flow`** CSS property controls how the auto-placement algorithm works, specifying exactly how auto-placed items get flowed into the grid.

**Syntax**: `[ row | column ] || dense`

**Initial value**: `row`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-flow

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridAutoFlow](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridautoflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2045

___

### gridAutoRows

• `Optional` **gridAutoRows**: [`GridAutoRows`](../modules/akashaproject_design_system._internal_.md#gridautorows)<`TLength`\>

The **`grid-auto-rows`** CSS property specifies the size of an implicitly-created grid row track or pattern of tracks.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-rows

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridAutoRows](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridautorows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2059

___

### gridColumn

• `Optional` **gridColumn**: [`GridColumn`](../modules/akashaproject_design_system._internal_.md#gridcolumn)

The **`grid-column`** CSS shorthand property specifies a grid item's size and location within a grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[gridColumn](akashaproject_design_system._internal_.StandardShorthandProperties.md#gridcolumn)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5514

___

### gridColumnEnd

• `Optional` **gridColumnEnd**: [`GridColumnEnd`](../modules/akashaproject_design_system._internal_.md#gridcolumnend)

The **`grid-column-end`** CSS property specifies a grid item’s end position within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the block-end edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridColumnEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridcolumnend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2073

___

### gridColumnStart

• `Optional` **gridColumnStart**: [`GridColumnStart`](../modules/akashaproject_design_system._internal_.md#gridcolumnstart)

The **`grid-column-start`** CSS property specifies a grid item’s start position within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement. This start position defines the block-start edge of the grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridColumnStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridcolumnstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2087

___

### gridRow

• `Optional` **gridRow**: [`GridRow`](../modules/akashaproject_design_system._internal_.md#gridrow)

The **`grid-row`** CSS shorthand property specifies a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[gridRow](akashaproject_design_system._internal_.StandardShorthandProperties.md#gridrow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5526

___

### gridRowEnd

• `Optional` **gridRowEnd**: [`GridRowEnd`](../modules/akashaproject_design_system._internal_.md#gridrowend)

The **`grid-row-end`** CSS property specifies a grid item’s end position within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-end edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridRowEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridrowend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2101

___

### gridRowStart

• `Optional` **gridRowStart**: [`GridRowStart`](../modules/akashaproject_design_system._internal_.md#gridrowstart)

The **`grid-row-start`** CSS property specifies a grid item’s start position within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridRowStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridrowstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2115

___

### gridTemplate

• `Optional` **gridTemplate**: [`GridTemplate`](../modules/akashaproject_design_system._internal_.md#gridtemplate)

The **`grid-template`** CSS property is a shorthand property for defining grid columns, rows, and areas.

**Syntax**: `none | [ <'grid-template-rows'> / <'grid-template-columns'> ] | [ <line-names>? <string> <track-size>? <line-names>? ]+ [ / <explicit-track-list> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[gridTemplate](akashaproject_design_system._internal_.StandardShorthandProperties.md#gridtemplate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5538

___

### gridTemplateAreas

• `Optional` **gridTemplateAreas**: [`GridTemplateAreas`](../modules/akashaproject_design_system._internal_.md#gridtemplateareas)

The **`grid-template-areas`** CSS property specifies named grid areas, establishing the cells in the grid and assigning them names.

**Syntax**: `none | <string>+`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-areas

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridTemplateAreas](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridtemplateareas)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2129

___

### gridTemplateColumns

• `Optional` **gridTemplateColumns**: [`GridTemplateColumns`](../modules/akashaproject_design_system._internal_.md#gridtemplatecolumns)<`TLength`\>

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-columns

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridTemplateColumns](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridtemplatecolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2143

___

### gridTemplateRows

• `Optional` **gridTemplateRows**: [`GridTemplateRows`](../modules/akashaproject_design_system._internal_.md#gridtemplaterows)<`TLength`\>

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-rows

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[gridTemplateRows](akashaproject_design_system._internal_.StandardLonghandProperties.md#gridtemplaterows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2157

___

### hangingPunctuation

• `Optional` **hangingPunctuation**: [`HangingPunctuation`](../modules/akashaproject_design_system._internal_.md#hangingpunctuation)

The **`hanging-punctuation`** CSS property specifies whether a punctuation mark should hang at the start or end of a line of text. Hanging punctuation may be placed outside the line box.

**Syntax**: `none | [ first || [ force-end | allow-end ] || last ]`

**Initial value**: `none`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   No    | **10** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/hanging-punctuation

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[hangingPunctuation](akashaproject_design_system._internal_.StandardLonghandProperties.md#hangingpunctuation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2171

___

### height

• `Optional` **height**: [`Height`](../modules/akashaproject_design_system._internal_.md#height)<`TLength`\>

The **`height`** CSS property specifies the height of an element. By default, the property defines the height of the content area. If `box-sizing` is set to `border-box`, however, it instead determines the height of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/height

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[height](akashaproject_design_system._internal_.StandardLonghandProperties.md#height)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2185

___

### hyphens

• `Optional` **hyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

|  Chrome  | Firefox |    Safari     |  Edge  |      IE      |
| :------: | :-----: | :-----------: | :----: | :----------: |
|  **55**  | **43**  | **5.1** _-x-_ | **79** | **10** _-x-_ |
| 13 _-x-_ | 6 _-x-_ |               |        |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/hyphens

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[hyphens](akashaproject_design_system._internal_.StandardLonghandProperties.md#hyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2200

___

### imageOrientation

• `Optional` **imageOrientation**: [`ImageOrientation`](../modules/akashaproject_design_system._internal_.md#imageorientation)

The **`image-orientation`** CSS property specifies a layout-independent correction to the orientation of an image. It should _not_ be used for any other orientation adjustments; instead, the `transform` property should be used with the `rotate` `<transform-function>`.

**Syntax**: `from-image | <angle> | [ <angle>? flip ]`

**Initial value**: `from-image`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **81** | **26**  | **13.1** | **81** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/image-orientation

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[imageOrientation](akashaproject_design_system._internal_.StandardLonghandProperties.md#imageorientation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2214

___

### imageRendering

• `Optional` **imageRendering**: [`ImageRendering`](../modules/akashaproject_design_system._internal_.md#imagerendering)

The **`image-rendering`** CSS property sets an image scaling algorithm. The property applies to an element itself, to any images set in its other properties, and to its descendants.

**Syntax**: `auto | crisp-edges | pixelated`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **13** | **3.6** | **6**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/image-rendering

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[imageRendering](akashaproject_design_system._internal_.StandardLonghandProperties.md#imagerendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2228

___

### imageResolution

• `Optional` **imageResolution**: [`ImageResolution`](../modules/akashaproject_design_system._internal_.md#imageresolution)

**Syntax**: `[ from-image || <resolution> ] && snap?`

**Initial value**: `1dppx`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[imageResolution](akashaproject_design_system._internal_.StandardLonghandProperties.md#imageresolution)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2234

___

### initialLetter

• `Optional` **initialLetter**: [`InitialLetter`](../modules/akashaproject_design_system._internal_.md#initialletter)

The `initial-letter` CSS property sets styling for dropped, raised, and sunken initial letters.

**Syntax**: `normal | [ <number> <integer>? ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   No    | **9**  |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/initial-letter

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[initialLetter](akashaproject_design_system._internal_.StandardLonghandProperties.md#initialletter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2248

___

### inlineSize

• `Optional` **inlineSize**: [`InlineSize`](../modules/akashaproject_design_system._internal_.md#inlinesize)<`TLength`\>

The **`inline-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inline-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[inlineSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#inlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2262

___

### inset

• `Optional` **inset**: [`Inset`](../modules/akashaproject_design_system._internal_.md#inset)<`TLength`\>

The **`inset`** CSS property is a shorthand that corresponds to the `top`, `right`, `bottom`, and/or `left` properties. It has the same multi-value syntax of the `margin` shorthand.

**Syntax**: `<'top'>{1,4}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[inset](akashaproject_design_system._internal_.StandardLonghandProperties.md#inset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2276

___

### insetBlock

• `Optional` **insetBlock**: [`InsetBlock`](../modules/akashaproject_design_system._internal_.md#insetblock)<`TLength`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2290

___

### insetBlockEnd

• `Optional` **insetBlockEnd**: [`InsetBlockEnd`](../modules/akashaproject_design_system._internal_.md#insetblockend)<`TLength`\>

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetBlockEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2304

___

### insetBlockStart

• `Optional` **insetBlockStart**: [`InsetBlockStart`](../modules/akashaproject_design_system._internal_.md#insetblockstart)<`TLength`\>

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetBlockStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2318

___

### insetInline

• `Optional` **insetInline**: [`InsetInline`](../modules/akashaproject_design_system._internal_.md#insetinline)<`TLength`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2332

___

### insetInlineEnd

• `Optional` **insetInlineEnd**: [`InsetInlineEnd`](../modules/akashaproject_design_system._internal_.md#insetinlineend)<`TLength`\>

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetInlineEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetinlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2346

___

### insetInlineStart

• `Optional` **insetInlineStart**: [`InsetInlineStart`](../modules/akashaproject_design_system._internal_.md#insetinlinestart)<`TLength`\>

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[insetInlineStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#insetinlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2360

___

### isolation

• `Optional` **isolation**: [`Isolation`](../modules/akashaproject_design_system._internal_.md#isolation)

The **`isolation`** CSS property determines whether an element must create a new stacking context.

**Syntax**: `auto | isolate`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **41** | **36**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/isolation

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[isolation](akashaproject_design_system._internal_.StandardLonghandProperties.md#isolation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2374

___

### justifyContent

• `Optional` **justifyContent**: [`JustifyContent`](../modules/akashaproject_design_system._internal_.md#justifycontent)

The CSS **`justify-content`** property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

**Syntax**: `normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ]`

**Initial value**: `normal`

---

_Supported in Flex Layout_

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **52**  | **20**  |   **9**   | **12** | **11** |
| 21 _-x-_ |         | 6.1 _-x-_ |        |        |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/justify-content

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[justifyContent](akashaproject_design_system._internal_.StandardLonghandProperties.md#justifycontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2403

___

### justifyItems

• `Optional` **justifyItems**: [`JustifyItems`](../modules/akashaproject_design_system._internal_.md#justifyitems)

The CSS **`justify-items`** property defines the default `justify-self` for all items of the box, giving them all a default way of justifying each box along the appropriate axis.

**Syntax**: `normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ] | legacy | legacy && [ left | right | center ]`

**Initial value**: `legacy`

---

_Supported in Flex Layout_

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **52** | **20**  | **9**  | **12** | **11** |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **45**  | **10.1** | **16** | No  |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/justify-items

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[justifyItems](akashaproject_design_system._internal_.StandardLonghandProperties.md#justifyitems)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2431

___

### justifySelf

• `Optional` **justifySelf**: [`JustifySelf`](../modules/akashaproject_design_system._internal_.md#justifyself)

The CSS **`justify-self`** property sets the way a box is justified inside its alignment container along the appropriate axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ]`

**Initial value**: `auto`

---

_Supported in Flex Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **45**  | **10.1** | **16** | No  |

---

_Supported in Grid Layout_

| Chrome | Firefox |  Safari  |  Edge  |      IE      |
| :----: | :-----: | :------: | :----: | :----------: |
| **57** | **45**  | **10.1** | **16** | **10** _-x-_ |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/justify-self

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[justifySelf](akashaproject_design_system._internal_.StandardLonghandProperties.md#justifyself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2459

___

### justifyTracks

• `Optional` **justifyTracks**: [`JustifyTracks`](../modules/akashaproject_design_system._internal_.md#justifytracks)

The **`justify-tracks`** CSS property sets the alignment in the masonry axis for grid containers that have masonry in their inline axis.

**Syntax**: `[ normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ] ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   n/a   |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/justify-tracks

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[justifyTracks](akashaproject_design_system._internal_.StandardLonghandProperties.md#justifytracks)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2473

___

### left

• `Optional` **left**: [`Left`](../modules/akashaproject_design_system._internal_.md#left)<`TLength`\>

The **`left`** CSS property participates in specifying the horizontal position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[left](akashaproject_design_system._internal_.StandardLonghandProperties.md#left)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2487

___

### letterSpacing

• `Optional` **letterSpacing**: [`LetterSpacing`](../modules/akashaproject_design_system._internal_.md#letterspacing)<`TLength`\>

The **`letter-spacing`** CSS property sets the horizontal spacing behavior between text characters. This value is added to the natural spacing between characters while rendering the text. Positive values of `letter-spacing` causes characters to spread farther apart, while negative values of `letter-spacing` bring characters closer together.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/letter-spacing

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[letterSpacing](akashaproject_design_system._internal_.StandardLonghandProperties.md#letterspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2501

___

### lineBreak

• `Optional` **lineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE    |
| :-----: | :-----: | :-----: | :----: | :-----: |
| **58**  | **69**  | **11**  | **14** | **5.5** |
| 1 _-x-_ |         | 3 _-x-_ |        |         |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-break

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[lineBreak](akashaproject_design_system._internal_.StandardLonghandProperties.md#linebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2516

___

### lineClamp

• `Optional` **lineClamp**: [`LineClamp`](../modules/akashaproject_design_system._internal_.md#lineclamp)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[lineClamp](akashaproject_design_system._internal_.StandardShorthandProperties.md#lineclamp)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5544

___

### lineHeight

• `Optional` **lineHeight**: [`LineHeight`](../modules/akashaproject_design_system._internal_.md#lineheight)<`TLength`\>

The **`line-height`** CSS property sets the height of a line box. It's commonly used to set the distance between lines of text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.

**Syntax**: `normal | <number> | <length> | <percentage>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[lineHeight](akashaproject_design_system._internal_.StandardLonghandProperties.md#lineheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2530

___

### lineHeightStep

• `Optional` **lineHeightStep**: [`LineHeightStep`](../modules/akashaproject_design_system._internal_.md#lineheightstep)<`TLength`\>

The **`line-height-step`** CSS property sets the step unit for line box heights. When the property is set, line box heights are rounded up to the closest multiple of the unit.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |   No    |   No   | n/a  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height-step

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[lineHeightStep](akashaproject_design_system._internal_.StandardLonghandProperties.md#lineheightstep)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2544

___

### listStyle

• `Optional` **listStyle**: [`ListStyle`](../modules/akashaproject_design_system._internal_.md#liststyle)

The **`list-style`** CSS shorthand property allows you set all the list style properties at once.

**Syntax**: `<'list-style-type'> || <'list-style-position'> || <'list-style-image'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[listStyle](akashaproject_design_system._internal_.StandardShorthandProperties.md#liststyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5556

___

### listStyleImage

• `Optional` **listStyleImage**: [`ListStyleImage`](../modules/akashaproject_design_system._internal_.md#liststyleimage)

The **`list-style-image`** CSS property sets an image to be used as the list item marker.

**Syntax**: `<image> | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-image

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[listStyleImage](akashaproject_design_system._internal_.StandardLonghandProperties.md#liststyleimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2558

___

### listStylePosition

• `Optional` **listStylePosition**: [`ListStylePosition`](../modules/akashaproject_design_system._internal_.md#liststyleposition)

The **`list-style-position`** CSS property sets the position of the `::marker` relative to a list item.

**Syntax**: `inside | outside`

**Initial value**: `outside`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[listStylePosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#liststyleposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2572

___

### listStyleType

• `Optional` **listStyleType**: [`ListStyleType`](../modules/akashaproject_design_system._internal_.md#liststyletype)

The **`list-style-type`** CSS property sets the marker (such as a disc, character, or custom counter style) of a list item element.

**Syntax**: `<counter-style> | <string> | none`

**Initial value**: `disc`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-type

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[listStyleType](akashaproject_design_system._internal_.StandardLonghandProperties.md#liststyletype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2586

___

### margin

• `Optional` **margin**: [`Margin`](../modules/akashaproject_design_system._internal_.md#margin)<`TLength`\>

The **`margin`** CSS property sets the margin area on all four sides of an element. It is a shorthand for `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`.

**Syntax**: `[ <length> | <percentage> | auto ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[margin](akashaproject_design_system._internal_.StandardShorthandProperties.md#margin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5568

___

### marginBlock

• `Optional` **marginBlock**: [`MarginBlock`](../modules/akashaproject_design_system._internal_.md#marginblock)<`TLength`\>

The **`margin-block`** CSS shorthand property defines the logical block start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2600

___

### marginBlockEnd

• `Optional` **marginBlockEnd**: [`MarginBlockEnd`](../modules/akashaproject_design_system._internal_.md#marginblockend)<`TLength`\>

The **`margin-block-end`** CSS property defines the logical block end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginBlockEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2614

___

### marginBlockStart

• `Optional` **marginBlockStart**: [`MarginBlockStart`](../modules/akashaproject_design_system._internal_.md#marginblockstart)<`TLength`\>

The **`margin-block-start`** CSS property defines the logical block start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginBlockStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2628

___

### marginBottom

• `Optional` **marginBottom**: [`MarginBottom`](../modules/akashaproject_design_system._internal_.md#marginbottom)<`TLength`\>

The **`margin-bottom`** CSS property sets the margin area on the bottom of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginBottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2642

___

### marginInline

• `Optional` **marginInline**: [`MarginInline`](../modules/akashaproject_design_system._internal_.md#margininline)<`TLength`\>

The **`margin-inline`** CSS shorthand property is a shorthand property that defines both the logical inline start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#margininline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2656

___

### marginInlineEnd

• `Optional` **marginInlineEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`TLength`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|          Chrome          |        Firefox        |          Safari          |  Edge  | IE  |
| :----------------------: | :-------------------: | :----------------------: | :----: | :-: |
|          **69**          |        **41**         |         **12.1**         | **79** | No  |
| 2 _(-webkit-margin-end)_ | 3 _(-moz-margin-end)_ | 3 _(-webkit-margin-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginInlineEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#margininlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2671

___

### marginInlineStart

• `Optional` **marginInlineStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`TLength`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|           Chrome           |         Firefox         |           Safari           |  Edge  | IE  |
| :------------------------: | :---------------------: | :------------------------: | :----: | :-: |
|           **69**           |         **41**          |          **12.1**          | **79** | No  |
| 2 _(-webkit-margin-start)_ | 3 _(-moz-margin-start)_ | 3 _(-webkit-margin-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginInlineStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#margininlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2686

___

### marginLeft

• `Optional` **marginLeft**: [`MarginLeft`](../modules/akashaproject_design_system._internal_.md#marginleft)<`TLength`\>

The **`margin-left`** CSS property sets the margin area on the left side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginLeft](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2700

___

### marginRight

• `Optional` **marginRight**: [`MarginRight`](../modules/akashaproject_design_system._internal_.md#marginright)<`TLength`\>

The **`margin-right`** CSS property sets the margin area on the right side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginRight](akashaproject_design_system._internal_.StandardLonghandProperties.md#marginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2714

___

### marginTop

• `Optional` **marginTop**: [`MarginTop`](../modules/akashaproject_design_system._internal_.md#margintop)<`TLength`\>

The **`margin-top`** CSS property sets the margin area on the top of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[marginTop](akashaproject_design_system._internal_.StandardLonghandProperties.md#margintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2728

___

### mask

• `Optional` **mask**: [`Mask`](../modules/akashaproject_design_system._internal_.md#mask)<`TLength`\>

The **`mask`** CSS shorthand property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `<mask-layer>#`

| Chrome | Firefox | Safari  | Edge  | IE  |
| :----: | :-----: | :-----: | :---: | :-: |
| **1**  |  **2**  | **3.1** | 12-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[mask](akashaproject_design_system._internal_.StandardShorthandProperties.md#mask)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5580

___

### maskBorder

• `Optional` **maskBorder**: [`MaskBorder`](../modules/akashaproject_design_system._internal_.md#maskborder)

The **`mask-border`** CSS shorthand property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

|              Chrome              | Firefox |               Safari               |               Edge                | IE  |
| :------------------------------: | :-----: | :--------------------------------: | :-------------------------------: | :-: |
| **1** _(-webkit-mask-box-image)_ |   No    | **3.1** _(-webkit-mask-box-image)_ | **79** _(-webkit-mask-box-image)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[maskBorder](akashaproject_design_system._internal_.StandardShorthandProperties.md#maskborder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5592

___

### maskBorderMode

• `Optional` **maskBorderMode**: [`MaskBorderMode`](../modules/akashaproject_design_system._internal_.md#maskbordermode)

The **`mask-border-mode`** CSS property specifies the blending mode used in a mask border.

**Syntax**: `luminance | alpha`

**Initial value**: `alpha`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskbordermode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2736

___

### maskBorderOutset

• `Optional` **maskBorderOutset**: [`MaskBorderOutset`](../modules/akashaproject_design_system._internal_.md#maskborderoutset)<`TLength`\>

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-outset)_ |   No    | **3.1** _(-webkit-mask-box-image-outset)_ | **79** _(-webkit-mask-box-image-outset)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-outset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderOutset](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskborderoutset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2750

___

### maskBorderRepeat

• `Optional` **maskBorderRepeat**: [`MaskBorderRepeat`](../modules/akashaproject_design_system._internal_.md#maskborderrepeat)

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-repeat)_ |   No    | **3.1** _(-webkit-mask-box-image-repeat)_ | **79** _(-webkit-mask-box-image-repeat)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-repeat

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderRepeat](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskborderrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2764

___

### maskBorderSlice

• `Optional` **maskBorderSlice**: [`MaskBorderSlice`](../modules/akashaproject_design_system._internal_.md#maskborderslice)

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

|                 Chrome                 | Firefox |                  Safari                  |                  Edge                   | IE  |
| :------------------------------------: | :-----: | :--------------------------------------: | :-------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-slice)_ |   No    | **3.1** _(-webkit-mask-box-image-slice)_ | **79** _(-webkit-mask-box-image-slice)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-slice

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderSlice](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskborderslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2778

___

### maskBorderSource

• `Optional` **maskBorderSource**: [`MaskBorderSource`](../modules/akashaproject_design_system._internal_.md#maskbordersource)

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-source)_ |   No    | **3.1** _(-webkit-mask-box-image-source)_ | **79** _(-webkit-mask-box-image-source)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-source

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderSource](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskbordersource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2792

___

### maskBorderWidth

• `Optional` **maskBorderWidth**: [`MaskBorderWidth`](../modules/akashaproject_design_system._internal_.md#maskborderwidth)<`TLength`\>

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

|                 Chrome                 | Firefox |                  Safari                  |                  Edge                   | IE  |
| :------------------------------------: | :-----: | :--------------------------------------: | :-------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-width)_ |   No    | **3.1** _(-webkit-mask-box-image-width)_ | **79** _(-webkit-mask-box-image-width)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskBorderWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskborderwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2806

___

### maskClip

• `Optional` **maskClip**: [`MaskClip`](../modules/akashaproject_design_system._internal_.md#maskclip)

The **`mask-clip`** CSS property determines the area which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <geometry-box> | no-clip ]#`

**Initial value**: `border-box`

|   Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :---------: | :-----: | :---------: | :----------: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-clip

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskClip](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2820

___

### maskComposite

• `Optional` **maskComposite**: [`MaskComposite`](../modules/akashaproject_design_system._internal_.md#maskcomposite)

The **`mask-composite`** CSS property represents a compositing operation used on the current mask layer with the mask layers below it.

**Syntax**: `<compositing-operator>#`

**Initial value**: `add`

| Chrome | Firefox | Safari | Edge  | IE  |
| :----: | :-----: | :----: | :---: | :-: |
|   No   | **53**  |   No   | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-composite

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskComposite](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskcomposite)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2834

___

### maskImage

• `Optional` **maskImage**: [`MaskImage`](../modules/akashaproject_design_system._internal_.md#maskimage)

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

|   Chrome    | Firefox |   Safari    | Edge  | IE  |
| :---------: | :-----: | :---------: | :---: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | 16-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-image

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskImage](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2848

___

### maskMode

• `Optional` **maskMode**: [`MaskMode`](../modules/akashaproject_design_system._internal_.md#maskmode)

The **`mask-mode`** CSS property sets whether the mask reference defined by `mask-image` is treated as a luminance or alpha mask.

**Syntax**: `<masking-mode>#`

**Initial value**: `match-source`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **53**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-mode

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2862

___

### maskOrigin

• `Optional` **maskOrigin**: [`MaskOrigin`](../modules/akashaproject_design_system._internal_.md#maskorigin)

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `<geometry-box>#`

**Initial value**: `border-box`

|   Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :---------: | :-----: | :---------: | :----------: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-origin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskOrigin](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2876

___

### maskPosition

• `Optional` **maskPosition**: [`MaskPosition`](../modules/akashaproject_design_system._internal_.md#maskposition)<`TLength`\>

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `center`

|   Chrome    | Firefox |    Safari     | Edge  | IE  |
| :---------: | :-----: | :-----------: | :---: | :-: |
| **1** _-x-_ | **53**  | **3.1** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskPosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2890

___

### maskRepeat

• `Optional` **maskRepeat**: [`MaskRepeat`](../modules/akashaproject_design_system._internal_.md#maskrepeat)

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `no-repeat`

|   Chrome    | Firefox |    Safari     | Edge  | IE  |
| :---------: | :-----: | :-----------: | :---: | :-: |
| **1** _-x-_ | **53**  | **3.1** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-repeat

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskRepeat](akashaproject_design_system._internal_.StandardLonghandProperties.md#maskrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2904

___

### maskSize

• `Optional` **maskSize**: [`MaskSize`](../modules/akashaproject_design_system._internal_.md#masksize)<`TLength`\>

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto`

|   Chrome    | Firefox |   Safari    | Edge  | IE  |
| :---------: | :-----: | :---------: | :---: | :-: |
| **4** _-x-_ | **53**  | **4** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#masksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2918

___

### maskType

• `Optional` **maskType**: [`MaskType`](../modules/akashaproject_design_system._internal_.md#masktype)

The **`mask-type`** CSS property sets whether an SVG `<mask>` element is used as a _luminance_ or an _alpha_ mask. It applies to the `<mask>` element itself.

**Syntax**: `luminance | alpha`

**Initial value**: `luminance`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **24** | **35**  | **7**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-type

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maskType](akashaproject_design_system._internal_.StandardLonghandProperties.md#masktype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2932

___

### mathStyle

• `Optional` **mathStyle**: [`MathStyle`](../modules/akashaproject_design_system._internal_.md#mathstyle)

The `math-style` property indicates whether MathML equations should render with normal or compact height.

**Syntax**: `normal | compact`

**Initial value**: `normal`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|  n/a   |   n/a   | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/math-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[mathStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#mathstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2946

___

### maxBlockSize

• `Optional` **maxBlockSize**: [`MaxBlockSize`](../modules/akashaproject_design_system._internal_.md#maxblocksize)<`TLength`\>

The `**max-block-size**` CSS property specifies the maximum size of an element in the direction opposite that of the writing direction as specified by `writing-mode`. That is, if the writing direction is horizontal, then `max-block-size` is equivalent to `max-height`; if the writing direction is vertical, `max-block-size` is the same as `max-width`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-block-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maxBlockSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#maxblocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2960

___

### maxHeight

• `Optional` **maxHeight**: [`MaxHeight`](../modules/akashaproject_design_system._internal_.md#maxheight)<`TLength`\>

The **`max-height`** CSS property sets the maximum height of an element. It prevents the used value of the `height` property from becoming larger than the value specified for `max-height`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **18** |  **1**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-height

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maxHeight](akashaproject_design_system._internal_.StandardLonghandProperties.md#maxheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2974

___

### maxInlineSize

• `Optional` **maxInlineSize**: [`MaxInlineSize`](../modules/akashaproject_design_system._internal_.md#maxinlinesize)<`TLength`\>

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block, depending on its writing mode. It corresponds to either the `max-width` or the `max-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |   Safari   |  Edge  | IE  |
| :----: | :-----: | :--------: | :----: | :-: |
| **57** | **41**  |  **12.1**  | **79** | No  |
|        |         | 10.1 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-inline-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maxInlineSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#maxinlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2989

___

### maxLines

• `Optional` **maxLines**: [`MaxLines`](../modules/akashaproject_design_system._internal_.md#maxlines)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maxLines](akashaproject_design_system._internal_.StandardLonghandProperties.md#maxlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2995

___

### maxWidth

• `Optional` **maxWidth**: [`MaxWidth`](../modules/akashaproject_design_system._internal_.md#maxwidth)<`TLength`\>

The **`max-width`** CSS property sets the maximum width of an element. It prevents the used value of the `width` property from becoming larger than the value specified by `max-width`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[maxWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#maxwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3009

___

### minBlockSize

• `Optional` **minBlockSize**: [`MinBlockSize`](../modules/akashaproject_design_system._internal_.md#minblocksize)<`TLength`\>

The **`min-block-size`** CSS property defines the minimum horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-block-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[minBlockSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#minblocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3023

___

### minHeight

• `Optional` **minHeight**: [`MinHeight`](../modules/akashaproject_design_system._internal_.md#minheight)<`TLength`\>

The **`min-height`** CSS property sets the minimum height of an element. It prevents the used value of the `height` property from becoming smaller than the value specified for `min-height`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **3**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-height

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[minHeight](akashaproject_design_system._internal_.StandardLonghandProperties.md#minheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3037

___

### minInlineSize

• `Optional` **minInlineSize**: [`MinInlineSize`](../modules/akashaproject_design_system._internal_.md#mininlinesize)<`TLength`\>

The **`min-inline-size`** CSS property defines the horizontal or vertical minimal size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-inline-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[minInlineSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#mininlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3051

___

### minWidth

• `Optional` **minWidth**: [`MinWidth`](../modules/akashaproject_design_system._internal_.md#minwidth)<`TLength`\>

The **`min-width`** CSS property sets the minimum width of an element. It prevents the used value of the `width` property from becoming smaller than the value specified for `min-width`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[minWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#minwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3065

___

### mixBlendMode

• `Optional` **mixBlendMode**: [`MixBlendMode`](../modules/akashaproject_design_system._internal_.md#mixblendmode)

The **`mix-blend-mode`** CSS property sets how an element's content should blend with the content of the element's parent and the element's background.

**Syntax**: `<blend-mode>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **41** | **32**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mix-blend-mode

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[mixBlendMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#mixblendmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3079

___

### motion

• `Optional` **motion**: [`Offset`](../modules/akashaproject_design_system._internal_.md#offset)<`TLength`\>

The **`offset`** CSS shorthand property sets all the properties required for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[motion](akashaproject_design_system._internal_.StandardShorthandProperties.md#motion)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5605

___

### motionDistance

• `Optional` **motionDistance**: [`OffsetDistance`](../modules/akashaproject_design_system._internal_.md#offsetdistance)<`TLength`\>

The **`offset-distance`** CSS property specifies a position along an `offset-path` for an element to be placed.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[motionDistance](akashaproject_design_system._internal_.StandardLonghandProperties.md#motiondistance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3094

___

### motionPath

• `Optional` **motionPath**: [`OffsetPath`](../modules/akashaproject_design_system._internal_.md#offsetpath)

The **`offset-path`** CSS property specifies a motion path for an element to follow and defines the element's positioning within the parent container or SVG coordinate system.

**Syntax**: `none | ray( [ <angle> && <size> && contain? ] ) | <path()> | <url> | [ <basic-shape> || <geometry-box> ]`

**Initial value**: `none`

|       Chrome       | Firefox | Safari |  Edge  | IE  |
| :----------------: | :-----: | :----: | :----: | :-: |
|       **55**       | **72**  |   No   | **79** | No  |
| 46 _(motion-path)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-path

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[motionPath](akashaproject_design_system._internal_.StandardLonghandProperties.md#motionpath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3109

___

### motionRotation

• `Optional` **motionRotation**: [`OffsetRotate`](../modules/akashaproject_design_system._internal_.md#offsetrotate)

The **`offset-rotate`** CSS property defines the orientation/direction of the element as it is positioned along the `offset-path`.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[motionRotation](akashaproject_design_system._internal_.StandardLonghandProperties.md#motionrotation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3124

___

### objectFit

• `Optional` **objectFit**: [`ObjectFit`](../modules/akashaproject_design_system._internal_.md#objectfit)

The **`object-fit`** CSS property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container.

**Syntax**: `fill | contain | cover | none | scale-down`

**Initial value**: `fill`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **32** | **36**  | **10** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/object-fit

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[objectFit](akashaproject_design_system._internal_.StandardLonghandProperties.md#objectfit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3138

___

### objectPosition

• `Optional` **objectPosition**: [`ObjectPosition`](../modules/akashaproject_design_system._internal_.md#objectposition)<`TLength`\>

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **32** | **36**  | **10** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/object-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[objectPosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#objectposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3152

___

### offset

• `Optional` **offset**: [`Offset`](../modules/akashaproject_design_system._internal_.md#offset)<`TLength`\>

The **`offset`** CSS shorthand property sets all the properties required for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[offset](akashaproject_design_system._internal_.StandardShorthandProperties.md#offset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5618

___

### offsetAnchor

• `Optional` **offsetAnchor**: [`OffsetAnchor`](../modules/akashaproject_design_system._internal_.md#offsetanchor)<`TLength`\>

**Syntax**: `auto | <position>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **79** | **72**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-anchor

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[offsetAnchor](akashaproject_design_system._internal_.StandardLonghandProperties.md#offsetanchor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3164

___

### offsetDistance

• `Optional` **offsetDistance**: [`OffsetDistance`](../modules/akashaproject_design_system._internal_.md#offsetdistance)<`TLength`\>

The **`offset-distance`** CSS property specifies a position along an `offset-path` for an element to be placed.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[offsetDistance](akashaproject_design_system._internal_.StandardLonghandProperties.md#offsetdistance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3179

___

### offsetPath

• `Optional` **offsetPath**: [`OffsetPath`](../modules/akashaproject_design_system._internal_.md#offsetpath)

The **`offset-path`** CSS property specifies a motion path for an element to follow and defines the element's positioning within the parent container or SVG coordinate system.

**Syntax**: `none | ray( [ <angle> && <size> && contain? ] ) | <path()> | <url> | [ <basic-shape> || <geometry-box> ]`

**Initial value**: `none`

|       Chrome       | Firefox | Safari |  Edge  | IE  |
| :----------------: | :-----: | :----: | :----: | :-: |
|       **55**       | **72**  |   No   | **79** | No  |
| 46 _(motion-path)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-path

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[offsetPath](akashaproject_design_system._internal_.StandardLonghandProperties.md#offsetpath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3194

___

### offsetRotate

• `Optional` **offsetRotate**: [`OffsetRotate`](../modules/akashaproject_design_system._internal_.md#offsetrotate)

The **`offset-rotate`** CSS property defines the orientation/direction of the element as it is positioned along the `offset-path`.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[offsetRotate](akashaproject_design_system._internal_.StandardLonghandProperties.md#offsetrotate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3209

___

### offsetRotation

• `Optional` **offsetRotation**: [`OffsetRotate`](../modules/akashaproject_design_system._internal_.md#offsetrotate)

The **`offset-rotate`** CSS property defines the orientation/direction of the element as it is positioned along the `offset-path`.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[offsetRotation](akashaproject_design_system._internal_.StandardLonghandProperties.md#offsetrotation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3224

___

### opacity

• `Optional` **opacity**: [`Opacity`](../modules/akashaproject_design_system._internal_.md#opacity)

The **`opacity`** CSS property sets the opacity of an element. Opacity is the degree to which content behind an element is hidden, and is the opposite of transparency.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **2**  | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/opacity

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[opacity](akashaproject_design_system._internal_.StandardLonghandProperties.md#opacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3238

___

### order

• `Optional` **order**: [`Order`](../modules/akashaproject_design_system._internal_.md#order)

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/order

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[order](akashaproject_design_system._internal_.StandardLonghandProperties.md#order)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3253

___

### orphans

• `Optional` **orphans**: [`Orphans`](../modules/akashaproject_design_system._internal_.md#orphans)

The **`orphans`** CSS property sets the minimum number of lines in a block container that must be shown at the _bottom_ of a page, region, or column.

**Syntax**: `<integer>`

**Initial value**: `2`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **25** |   No    | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/orphans

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[orphans](akashaproject_design_system._internal_.StandardLonghandProperties.md#orphans)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3267

___

### outline

• `Optional` **outline**: [`Outline`](../modules/akashaproject_design_system._internal_.md#outline)<`TLength`\>

The **`outline`** CSS shorthand property set all the outline properties in a single declaration.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[outline](akashaproject_design_system._internal_.StandardShorthandProperties.md#outline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5630

___

### outlineColor

• `Optional` **outlineColor**: [`OutlineColor`](../modules/akashaproject_design_system._internal_.md#outlinecolor)

The **`outline-color`** CSS property sets the color of an element's outline.

**Syntax**: `<color> | invert`

**Initial value**: `invert`, for browsers supporting it, `currentColor` for the other

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[outlineColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#outlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3281

___

### outlineOffset

• `Optional` **outlineOffset**: [`OutlineOffset`](../modules/akashaproject_design_system._internal_.md#outlineoffset)<`TLength`\>

The **`outline-offset`** CSS property sets the amount of space between an outline and the edge or border of an element.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **1**  | **1.5** | **1.2** | **15** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-offset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[outlineOffset](akashaproject_design_system._internal_.StandardLonghandProperties.md#outlineoffset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3295

___

### outlineStyle

• `Optional` **outlineStyle**: [`OutlineStyle`](../modules/akashaproject_design_system._internal_.md#outlinestyle)

The **`outline-style`** CSS property sets the style of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `auto | <'border-style'>`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[outlineStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#outlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3309

___

### outlineWidth

• `Optional` **outlineWidth**: [`OutlineWidth`](../modules/akashaproject_design_system._internal_.md#outlinewidth)<`TLength`\>

The CSS **`outline-width`** property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[outlineWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#outlinewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3323

___

### overflow

• `Optional` **overflow**: [`Overflow`](../modules/akashaproject_design_system._internal_.md#overflow)

The **`overflow`** CSS shorthand property sets the desired behavior for an element's overflow — i.e. when an element's content is too big to fit in its block formatting context — in both directions.

**Syntax**: `[ visible | hidden | clip | scroll | auto ]{1,2}`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[overflow](akashaproject_design_system._internal_.StandardShorthandProperties.md#overflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5644

___

### overflowAnchor

• `Optional` **overflowAnchor**: [`OverflowAnchor`](../modules/akashaproject_design_system._internal_.md#overflowanchor)

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **56** | **66**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-anchor

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowAnchor](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowanchor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3335

___

### overflowBlock

• `Optional` **overflowBlock**: [`OverflowBlock`](../modules/akashaproject_design_system._internal_.md#overflowblock)

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **69**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3347

___

### overflowClipBox

• `Optional` **overflowClipBox**: [`OverflowClipBox`](../modules/akashaproject_design_system._internal_.md#overflowclipbox)

The **`overflow-clip-box`** CSS property specifies relative to which box the clipping happens when there is an overflow. It is short hand for the `overflow-clip-box-inline` and `overflow-clip-box-block` properties.

**Syntax**: `padding-box | content-box`

**Initial value**: `padding-box`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **29**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Mozilla/Gecko/Chrome/CSS/overflow-clip-box

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowClipBox](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowclipbox)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3361

___

### overflowClipMargin

• `Optional` **overflowClipMargin**: [`OverflowClipMargin`](../modules/akashaproject_design_system._internal_.md#overflowclipmargin)<`TLength`\>

**Syntax**: `<visual-box> || <length [0,∞]>`

**Initial value**: `0px`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **90** |   No    |   No   | **90** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-clip-margin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowClipMargin](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowclipmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3373

___

### overflowInline

• `Optional` **overflowInline**: [`OverflowInline`](../modules/akashaproject_design_system._internal_.md#overflowinline)

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **69**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3385

___

### overflowWrap

• `Optional` **overflowWrap**: [`OverflowWrap`](../modules/akashaproject_design_system._internal_.md#overflowwrap)

The `**overflow-wrap**` CSS property applies to inline elements, setting whether the browser should insert line breaks within an otherwise unbreakable string to prevent text from overflowing its line box.

**Syntax**: `normal | break-word | anywhere`

**Initial value**: `normal`

|     Chrome      |      Firefox      |     Safari      |       Edge       |          IE           |
| :-------------: | :---------------: | :-------------: | :--------------: | :-------------------: |
|     **23**      |      **49**       |      **7**      |      **18**      | **5.5** _(word-wrap)_ |
| 1 _(word-wrap)_ | 3.5 _(word-wrap)_ | 1 _(word-wrap)_ | 12 _(word-wrap)_ |                       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-wrap

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowWrap](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowwrap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3400

___

### overflowX

• `Optional` **overflowX**: [`OverflowX`](../modules/akashaproject_design_system._internal_.md#overflowx)

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **3.5** | **3**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-x

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowX](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3414

___

### overflowY

• `Optional` **overflowY**: [`OverflowY`](../modules/akashaproject_design_system._internal_.md#overflowy)

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **3.5** | **3**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-y

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overflowY](akashaproject_design_system._internal_.StandardLonghandProperties.md#overflowy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3428

___

### overscrollBehavior

• `Optional` **overscrollBehavior**: [`OverscrollBehavior`](../modules/akashaproject_design_system._internal_.md#overscrollbehavior)

The **`overscroll-behavior`** CSS property sets what a browser does when reaching the boundary of a scrolling area. It's a shorthand for `overscroll-behavior-x` and `overscroll-behavior-y`.

**Syntax**: `[ contain | none | auto ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[overscrollBehavior](akashaproject_design_system._internal_.StandardShorthandProperties.md#overscrollbehavior)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5658

___

### overscrollBehaviorBlock

• `Optional` **overscrollBehaviorBlock**: [`OverscrollBehaviorBlock`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorblock)

The **`overscroll-behavior-block`** CSS property sets the browser's behavior when the block direction boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **77** | **73**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overscrollBehaviorBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#overscrollbehaviorblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3442

___

### overscrollBehaviorInline

• `Optional` **overscrollBehaviorInline**: [`OverscrollBehaviorInline`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorinline)

The **`overscroll-behavior-inline`** CSS property sets the browser's behavior when the inline direction boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **77** | **73**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overscrollBehaviorInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#overscrollbehaviorinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3456

___

### overscrollBehaviorX

• `Optional` **overscrollBehaviorX**: [`OverscrollBehaviorX`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorx)

The **`overscroll-behavior-x`** CSS property sets the browser's behavior when the horizontal boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-x

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overscrollBehaviorX](akashaproject_design_system._internal_.StandardLonghandProperties.md#overscrollbehaviorx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3470

___

### overscrollBehaviorY

• `Optional` **overscrollBehaviorY**: [`OverscrollBehaviorY`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviory)

The **`overscroll-behavior-y`** CSS property sets the browser's behavior when the vertical boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-y

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[overscrollBehaviorY](akashaproject_design_system._internal_.StandardLonghandProperties.md#overscrollbehaviory)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3484

___

### padding

• `Optional` **padding**: [`Padding`](../modules/akashaproject_design_system._internal_.md#padding)<`TLength`\>

The **`padding`** CSS shorthand property sets the padding area on all four sides of an element at once.

**Syntax**: `[ <length> | <percentage> ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[padding](akashaproject_design_system._internal_.StandardShorthandProperties.md#padding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5670

___

### paddingBlock

• `Optional` **paddingBlock**: [`PaddingBlock`](../modules/akashaproject_design_system._internal_.md#paddingblock)<`TLength`\>

The **`padding-block`** CSS shorthand property defines the logical block start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3498

___

### paddingBlockEnd

• `Optional` **paddingBlockEnd**: [`PaddingBlockEnd`](../modules/akashaproject_design_system._internal_.md#paddingblockend)<`TLength`\>

The **`padding-block-end`** CSS property defines the logical block end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingBlockEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3512

___

### paddingBlockStart

• `Optional` **paddingBlockStart**: [`PaddingBlockStart`](../modules/akashaproject_design_system._internal_.md#paddingblockstart)<`TLength`\>

The **`padding-block-start`** CSS property defines the logical block start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingBlockStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3526

___

### paddingBottom

• `Optional` **paddingBottom**: [`PaddingBottom`](../modules/akashaproject_design_system._internal_.md#paddingbottom)<`TLength`\>

The **`padding-bottom`** CSS property sets the height of the padding area on the bottom of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingBottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3540

___

### paddingInline

• `Optional` **paddingInline**: [`PaddingInline`](../modules/akashaproject_design_system._internal_.md#paddinginline)<`TLength`\>

The **`padding-inline`** CSS shorthand property defines the logical inline start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddinginline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3554

___

### paddingInlineEnd

• `Optional` **paddingInlineEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`TLength`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|          Chrome           |        Firefox         |          Safari           |  Edge  | IE  |
| :-----------------------: | :--------------------: | :-----------------------: | :----: | :-: |
|          **69**           |         **41**         |         **12.1**          | **79** | No  |
| 2 _(-webkit-padding-end)_ | 3 _(-moz-padding-end)_ | 3 _(-webkit-padding-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingInlineEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddinginlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3569

___

### paddingInlineStart

• `Optional` **paddingInlineStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`TLength`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|           Chrome            |         Firefox          |           Safari            |  Edge  | IE  |
| :-------------------------: | :----------------------: | :-------------------------: | :----: | :-: |
|           **69**            |          **41**          |          **12.1**           | **79** | No  |
| 2 _(-webkit-padding-start)_ | 3 _(-moz-padding-start)_ | 3 _(-webkit-padding-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingInlineStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddinginlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3584

___

### paddingLeft

• `Optional` **paddingLeft**: [`PaddingLeft`](../modules/akashaproject_design_system._internal_.md#paddingleft)<`TLength`\>

The **`padding-left`** CSS property sets the width of the padding area to the left of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingLeft](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3598

___

### paddingRight

• `Optional` **paddingRight**: [`PaddingRight`](../modules/akashaproject_design_system._internal_.md#paddingright)<`TLength`\>

The **`padding-right`** CSS property sets the width of the padding area on the right of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingRight](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3612

___

### paddingTop

• `Optional` **paddingTop**: [`PaddingTop`](../modules/akashaproject_design_system._internal_.md#paddingtop)<`TLength`\>

The **`padding-top`** CSS property sets the height of the padding area on the top of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paddingTop](akashaproject_design_system._internal_.StandardLonghandProperties.md#paddingtop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3626

___

### pageBreakAfter

• `Optional` **pageBreakAfter**: [`PageBreakAfter`](../modules/akashaproject_design_system._internal_.md#pagebreakafter)

The **`page-break-after`** CSS property adjusts page breaks _after_ the current element.

**Syntax**: `auto | always | avoid | left | right | recto | verso`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-after

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[pageBreakAfter](akashaproject_design_system._internal_.StandardLonghandProperties.md#pagebreakafter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3640

___

### pageBreakBefore

• `Optional` **pageBreakBefore**: [`PageBreakBefore`](../modules/akashaproject_design_system._internal_.md#pagebreakbefore)

The **`page-break-before`** CSS property adjusts page breaks _before_ the current element.

**Syntax**: `auto | always | avoid | left | right | recto | verso`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-before

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[pageBreakBefore](akashaproject_design_system._internal_.StandardLonghandProperties.md#pagebreakbefore)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3654

___

### pageBreakInside

• `Optional` **pageBreakInside**: [`PageBreakInside`](../modules/akashaproject_design_system._internal_.md#pagebreakinside)

The **`page-break-inside`** CSS property adjusts page breaks _inside_ the current element.

**Syntax**: `auto | avoid`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **19**  | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-inside

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[pageBreakInside](akashaproject_design_system._internal_.StandardLonghandProperties.md#pagebreakinside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3668

___

### paintOrder

• `Optional` **paintOrder**: [`PaintOrder`](../modules/akashaproject_design_system._internal_.md#paintorder)

The **`paint-order`** CSS property lets you control the order in which the fill and stroke (and painting markers) of text content and shapes are drawn.

**Syntax**: `normal | [ fill || stroke || markers ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **35** | **60**  | **8**  | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/paint-order

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[paintOrder](akashaproject_design_system._internal_.StandardLonghandProperties.md#paintorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3682

___

### perspective

• `Optional` **perspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`TLength`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[perspective](akashaproject_design_system._internal_.StandardLonghandProperties.md#perspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3697

___

### perspectiveOrigin

• `Optional` **perspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`TLength`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective-origin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[perspectiveOrigin](akashaproject_design_system._internal_.StandardLonghandProperties.md#perspectiveorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3712

___

### placeContent

• `Optional` **placeContent**: [`PlaceContent`](../modules/akashaproject_design_system._internal_.md#placecontent)

The `**place-content**` CSS shorthand property allows you to align content along both the block and inline directions at once (i.e. the `align-content` and `justify-content` properties) in a relevant layout system such as Grid or Flexbox.

**Syntax**: `<'align-content'> <'justify-content'>?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **9**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-content

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[placeContent](akashaproject_design_system._internal_.StandardLonghandProperties.md#placecontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3726

___

### placeItems

• `Optional` **placeItems**: [`PlaceItems`](../modules/akashaproject_design_system._internal_.md#placeitems)

The CSS **`place-items`** shorthand property allows you to align items along both the block and inline directions at once (i.e. the `align-items` and `justify-items` properties) in a relevant layout system such as Grid or Flexbox. If the second value is not set, the first value is also used for it.

**Syntax**: `<'align-items'> <'justify-items'>?`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-items

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[placeItems](akashaproject_design_system._internal_.StandardShorthandProperties.md#placeitems)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5682

___

### placeSelf

• `Optional` **placeSelf**: [`PlaceSelf`](../modules/akashaproject_design_system._internal_.md#placeself)

The **`place-self`** CSS shorthand property allows you to align an individual item in both the block and inline directions at once (i.e. the `align-self` and `justify-self` properties) in a relevant layout system such as Grid or Flexbox. If the second value is not present, the first value is also used for it.

**Syntax**: `<'align-self'> <'justify-self'>?`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-self

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[placeSelf](akashaproject_design_system._internal_.StandardShorthandProperties.md#placeself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5694

___

### pointerEvents

• `Optional` **pointerEvents**: [`PointerEvents`](../modules/akashaproject_design_system._internal_.md#pointerevents)

The **`pointer-events`** CSS property sets under what circumstances (if any) a particular graphic element can become the target of pointer events.

**Syntax**: `auto | none | visiblePainted | visibleFill | visibleStroke | visible | painted | fill | stroke | all | inherit`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **1**  | **1.5** | **4**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/pointer-events

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[pointerEvents](akashaproject_design_system._internal_.StandardLonghandProperties.md#pointerevents)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3740

___

### position

• `Optional` **position**: [`Position`](../modules/akashaproject_design_system._internal_.md#position)

The **`position`** CSS property sets how an element is positioned in a document. The `top`, `right`, `bottom`, and `left` properties determine the final location of positioned elements.

**Syntax**: `static | relative | absolute | sticky | fixed`

**Initial value**: `static`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[position](akashaproject_design_system._internal_.StandardLonghandProperties.md#position)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3754

___

### quotes

• `Optional` **quotes**: [`Quotes`](../modules/akashaproject_design_system._internal_.md#quotes)

The **`quotes`** CSS property sets how the browser should render quotation marks that are added using the `open-quotes` or `close-quotes` values of the CSS `content` property.

**Syntax**: `none | auto | [ <string> <string> ]+`

**Initial value**: depends on user agent

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **11** | **1.5** | **9**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/quotes

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[quotes](akashaproject_design_system._internal_.StandardLonghandProperties.md#quotes)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3768

___

### resize

• `Optional` **resize**: [`Resize`](../modules/akashaproject_design_system._internal_.md#resize)

The **`resize`** CSS property sets whether an element is resizable, and if so, in which directions.

**Syntax**: `none | both | horizontal | vertical | block | inline`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **1**  |  **4**  | **3**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/resize

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[resize](akashaproject_design_system._internal_.StandardLonghandProperties.md#resize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3782

___

### right

• `Optional` **right**: [`Right`](../modules/akashaproject_design_system._internal_.md#right)<`TLength`\>

The **`right`** CSS property participates in specifying the horizontal position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[right](akashaproject_design_system._internal_.StandardLonghandProperties.md#right)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3796

___

### rotate

• `Optional` **rotate**: [`Rotate`](../modules/akashaproject_design_system._internal_.md#rotate)

The **`rotate`** CSS property allows you to specify rotation transforms individually and independently of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` property.

**Syntax**: `none | <angle> | [ x | y | z | <number>{3} ] && <angle>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/rotate

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[rotate](akashaproject_design_system._internal_.StandardLonghandProperties.md#rotate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3810

___

### rowGap

• `Optional` **rowGap**: [`RowGap`](../modules/akashaproject_design_system._internal_.md#rowgap)<`TLength`\>

The **`row-gap`** CSS property sets the size of the gap (gutter) between an element's grid rows.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

---

_Supported in Flex Layout_

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **84** | **63**  | **14.1** | **84** | No  |

---

_Supported in Grid Layout_

|       Chrome        |       Firefox       |        Safari         |  Edge  | IE  |
| :-----------------: | :-----------------: | :-------------------: | :----: | :-: |
|       **66**        |       **61**        |        **12**         | **16** | No  |
| 57 _(grid-row-gap)_ | 52 _(grid-row-gap)_ | 10.1 _(grid-row-gap)_ |        |     |

---

**`see`** https://developer.mozilla.org/docs/Web/CSS/row-gap

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[rowGap](akashaproject_design_system._internal_.StandardLonghandProperties.md#rowgap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3839

___

### rubyAlign

• `Optional` **rubyAlign**: [`RubyAlign`](../modules/akashaproject_design_system._internal_.md#rubyalign)

The `**ruby-align**` CSS property defines the distribution of the different ruby elements over the base.

**Syntax**: `start | center | space-between | space-around`

**Initial value**: `space-around`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **38**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/ruby-align

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[rubyAlign](akashaproject_design_system._internal_.StandardLonghandProperties.md#rubyalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3853

___

### rubyMerge

• `Optional` **rubyMerge**: [`RubyMerge`](../modules/akashaproject_design_system._internal_.md#rubymerge)

**Syntax**: `separate | collapse | auto`

**Initial value**: `separate`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[rubyMerge](akashaproject_design_system._internal_.StandardLonghandProperties.md#rubymerge)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3859

___

### rubyPosition

• `Optional` **rubyPosition**: [`RubyPosition`](../modules/akashaproject_design_system._internal_.md#rubyposition)

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

| Chrome  | Firefox |    Safari     | Edge  | IE  |
| :-----: | :-----: | :-----------: | :---: | :-: |
| **84**  | **38**  | **6.1** _-x-_ | 12-79 | No  |
| 1 _-x-_ |         |               |       |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/ruby-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[rubyPosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#rubyposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3874

___

### scale

• `Optional` **scale**: [`Scale`](../modules/akashaproject_design_system._internal_.md#scale)

The **`scale`** CSS property allows you to specify scale transforms individually and independently of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <number>{1,3}`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scale

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scale](akashaproject_design_system._internal_.StandardLonghandProperties.md#scale)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3888

___

### scrollBehavior

• `Optional` **scrollBehavior**: [`ScrollBehavior`](../modules/akashaproject_design_system._internal_.md#scrollbehavior)

The **`scroll-behavior`** CSS property sets the behavior for a scrolling box when scrolling is triggered by the navigation or CSSOM scrolling APIs.

**Syntax**: `auto | smooth`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **61** | **36**  |  n/a   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-behavior

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollBehavior](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollbehavior)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3902

___

### scrollMargin

• `Optional` **scrollMargin**: [`ScrollMargin`](../modules/akashaproject_design_system._internal_.md#scrollmargin)<`TLength`\>

The **`scroll-margin`** shorthand property sets all of the scroll margins of an element at once, assigning values much like the `margin` property does for margins of an element.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** | **90**  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMargin](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3917

___

### scrollMarginBlock

• `Optional` **scrollMarginBlock**: [`ScrollMarginBlock`](../modules/akashaproject_design_system._internal_.md#scrollmarginblock)<`TLength`\>

The `scroll-margin-block` shorthand property sets the scroll margins of an element in the block dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3931

___

### scrollMarginBlockEnd

• `Optional` **scrollMarginBlockEnd**: [`ScrollMarginBlockEnd`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockend)<`TLength`\>

The `scroll-margin-block-end` property defines the margin of the scroll snap area at the end of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginBlockEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3945

___

### scrollMarginBlockStart

• `Optional` **scrollMarginBlockStart**: [`ScrollMarginBlockStart`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockstart)<`TLength`\>

The `scroll-margin-block-start` property defines the margin of the scroll snap area at the start of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginBlockStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3959

___

### scrollMarginBottom

• `Optional` **scrollMarginBottom**: [`ScrollMarginBottom`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottom)<`TLength`\>

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginBottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3974

___

### scrollMarginInline

• `Optional` **scrollMarginInline**: [`ScrollMarginInline`](../modules/akashaproject_design_system._internal_.md#scrollmargininline)<`TLength`\>

The `scroll-margin-inline` shorthand property sets the scroll margins of an element in the inline dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **68**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmargininline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3988

___

### scrollMarginInlineEnd

• `Optional` **scrollMarginInlineEnd**: [`ScrollMarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineend)<`TLength`\>

The `scroll-margin-inline-end` property defines the margin of the scroll snap area at the end of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginInlineEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmargininlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4002

___

### scrollMarginInlineStart

• `Optional` **scrollMarginInlineStart**: [`ScrollMarginInlineStart`](../modules/akashaproject_design_system._internal_.md#scrollmargininlinestart)<`TLength`\>

The `scroll-margin-inline-start` property defines the margin of the scroll snap area at the start of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginInlineStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmargininlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4016

___

### scrollMarginLeft

• `Optional` **scrollMarginLeft**: [`ScrollMarginLeft`](../modules/akashaproject_design_system._internal_.md#scrollmarginleft)<`TLength`\>

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginLeft](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4031

___

### scrollMarginRight

• `Optional` **scrollMarginRight**: [`ScrollMarginRight`](../modules/akashaproject_design_system._internal_.md#scrollmarginright)<`TLength`\>

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginRight](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmarginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4046

___

### scrollMarginTop

• `Optional` **scrollMarginTop**: [`ScrollMarginTop`](../modules/akashaproject_design_system._internal_.md#scrollmargintop)<`TLength`\>

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollMarginTop](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollmargintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4061

___

### scrollPadding

• `Optional` **scrollPadding**: [`ScrollPadding`](../modules/akashaproject_design_system._internal_.md#scrollpadding)<`TLength`\>

The **`scroll-padding`** shorthand property sets scroll padding on all sides of an element at once, much like the `padding` property does for padding on an element.

**Syntax**: `[ auto | <length-percentage> ]{1,4}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPadding](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpadding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4075

___

### scrollPaddingBlock

• `Optional` **scrollPaddingBlock**: [`ScrollPaddingBlock`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblock)<`TLength`\>

The `scroll-padding-block` shorthand property sets the scroll padding of an element in the block dimension.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingBlock](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4089

___

### scrollPaddingBlockEnd

• `Optional` **scrollPaddingBlockEnd**: [`ScrollPaddingBlockEnd`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockend)<`TLength`\>

The `scroll-padding-block-end` property defines offsets for the end edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingBlockEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4103

___

### scrollPaddingBlockStart

• `Optional` **scrollPaddingBlockStart**: [`ScrollPaddingBlockStart`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockstart)<`TLength`\>

The `scroll-padding-block-start` property defines offsets for the start edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingBlockStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4117

___

### scrollPaddingBottom

• `Optional` **scrollPaddingBottom**: [`ScrollPaddingBottom`](../modules/akashaproject_design_system._internal_.md#scrollpaddingbottom)<`TLength`\>

The `scroll-padding-bottom` property defines offsets for the bottom of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingBottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4131

___

### scrollPaddingInline

• `Optional` **scrollPaddingInline**: [`ScrollPaddingInline`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginline)<`TLength`\>

The `scroll-padding-inline` shorthand property sets the scroll padding of an element in the inline dimension.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingInline](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddinginline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4145

___

### scrollPaddingInlineEnd

• `Optional` **scrollPaddingInlineEnd**: [`ScrollPaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineend)<`TLength`\>

The `scroll-padding-inline-end` property defines offsets for the end edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-end

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingInlineEnd](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddinginlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4159

___

### scrollPaddingInlineStart

• `Optional` **scrollPaddingInlineStart**: [`ScrollPaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlinestart)<`TLength`\>

The `scroll-padding-inline-start` property defines offsets for the start edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-start

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingInlineStart](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddinginlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4173

___

### scrollPaddingLeft

• `Optional` **scrollPaddingLeft**: [`ScrollPaddingLeft`](../modules/akashaproject_design_system._internal_.md#scrollpaddingleft)<`TLength`\>

The `scroll-padding-left` property defines offsets for the left of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingLeft](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4187

___

### scrollPaddingRight

• `Optional` **scrollPaddingRight**: [`ScrollPaddingRight`](../modules/akashaproject_design_system._internal_.md#scrollpaddingright)<`TLength`\>

The `scroll-padding-right` property defines offsets for the right of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingRight](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4201

___

### scrollPaddingTop

• `Optional` **scrollPaddingTop**: [`ScrollPaddingTop`](../modules/akashaproject_design_system._internal_.md#scrollpaddingtop)<`TLength`\>

The **`scroll-padding-top`** property defines offsets for the top of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollPaddingTop](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollpaddingtop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4215

___

### scrollSnapAlign

• `Optional` **scrollSnapAlign**: [`ScrollSnapAlign`](../modules/akashaproject_design_system._internal_.md#scrollsnapalign)

The `scroll-snap-align` property specifies the box’s snap position as an alignment of its snap area (as the alignment subject) within its snap container’s snapport (as the alignment container). The two values specify the snapping alignment in the block axis and inline axis, respectively. If only one value is specified, the second value defaults to the same value.

**Syntax**: `[ none | start | end | center ]{1,2}`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-align

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapAlign](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4229

___

### scrollSnapMargin

• `Optional` **scrollSnapMargin**: [`ScrollMargin`](../modules/akashaproject_design_system._internal_.md#scrollmargin)<`TLength`\>

The **`scroll-margin`** shorthand property sets all of the scroll margins of an element at once, assigning values much like the `margin` property does for margins of an element.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** |  68-90  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapMargin](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4244

___

### scrollSnapMarginBottom

• `Optional` **scrollSnapMarginBottom**: [`ScrollMarginBottom`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottom)<`TLength`\>

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapMarginBottom](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapmarginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4259

___

### scrollSnapMarginLeft

• `Optional` **scrollSnapMarginLeft**: [`ScrollMarginLeft`](../modules/akashaproject_design_system._internal_.md#scrollmarginleft)<`TLength`\>

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapMarginLeft](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapmarginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4274

___

### scrollSnapMarginRight

• `Optional` **scrollSnapMarginRight**: [`ScrollMarginRight`](../modules/akashaproject_design_system._internal_.md#scrollmarginright)<`TLength`\>

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapMarginRight](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapmarginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4289

___

### scrollSnapMarginTop

• `Optional` **scrollSnapMarginTop**: [`ScrollMarginTop`](../modules/akashaproject_design_system._internal_.md#scrollmargintop)<`TLength`\>

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapMarginTop](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapmargintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4304

___

### scrollSnapStop

• `Optional` **scrollSnapStop**: [`ScrollSnapStop`](../modules/akashaproject_design_system._internal_.md#scrollsnapstop)

The **`scroll-snap-stop`** CSS property defines whether the scroll container is allowed to "pass over" possible snap positions.

**Syntax**: `normal | always`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **75** |   No    | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-stop

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapStop](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnapstop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4318

___

### scrollSnapType

• `Optional` **scrollSnapType**: [`ScrollSnapType`](../modules/akashaproject_design_system._internal_.md#scrollsnaptype)

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |      IE      |
| :----: | :-----: | :-----: | :----: | :----------: |
| **69** |  39-68  | **11**  | **79** | **10** _-x-_ |
|        |         | 9 _-x-_ |        |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-type

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollSnapType](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4333

___

### scrollbarColor

• `Optional` **scrollbarColor**: [`ScrollbarColor`](../modules/akashaproject_design_system._internal_.md#scrollbarcolor)

The **`scrollbar-color`** CSS property sets the color of the scrollbar track and thumb.

**Syntax**: `auto | <color>{2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **64**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollbarColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollbarcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4347

___

### scrollbarGutter

• `Optional` **scrollbarGutter**: [`ScrollbarGutter`](../modules/akashaproject_design_system._internal_.md#scrollbargutter)

The **`scrollbar-gutter`** CSS property allows authors to reserve space for the scrollbar, preventing unwanted layout changes as the content grows while also avoiding unnecessary visuals when scrolling isn't needed.

**Syntax**: `auto | stable && both-edges?`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |   No    |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-gutter

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollbarGutter](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollbargutter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4361

___

### scrollbarWidth

• `Optional` **scrollbarWidth**: [`ScrollbarWidth`](../modules/akashaproject_design_system._internal_.md#scrollbarwidth)

The **`scrollbar-width`** property allows the author to set the maximum thickness of an element’s scrollbars when they are shown.

**Syntax**: `auto | thin | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **64**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[scrollbarWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#scrollbarwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4375

___

### shapeImageThreshold

• `Optional` **shapeImageThreshold**: [`ShapeImageThreshold`](../modules/akashaproject_design_system._internal_.md#shapeimagethreshold)

The **`shape-image-threshold`** CSS property sets the alpha channel threshold used to extract the shape using an image as the value for `shape-outside`.

**Syntax**: `<alpha-value>`

**Initial value**: `0.0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-image-threshold

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[shapeImageThreshold](akashaproject_design_system._internal_.StandardLonghandProperties.md#shapeimagethreshold)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4389

___

### shapeMargin

• `Optional` **shapeMargin**: [`ShapeMargin`](../modules/akashaproject_design_system._internal_.md#shapemargin)<`TLength`\>

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-margin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[shapeMargin](akashaproject_design_system._internal_.StandardLonghandProperties.md#shapemargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4403

___

### shapeOutside

• `Optional` **shapeOutside**: [`ShapeOutside`](../modules/akashaproject_design_system._internal_.md#shapeoutside)

The **`shape-outside`** CSS property defines a shape—which may be non-rectangular—around which adjacent inline content should wrap. By default, inline content wraps around its margin box; `shape-outside` provides a way to customize this wrapping, making it possible to wrap text around complex objects rather than simple boxes.

**Syntax**: `none | [ <shape-box> || <basic-shape> ] | <image>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-outside

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[shapeOutside](akashaproject_design_system._internal_.StandardLonghandProperties.md#shapeoutside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4417

___

### tabSize

• `Optional` **tabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`TLength`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **21** | **91**  | **7**  | **79** | No  |
|        | 4 _-x-_ |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/tab-size

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[tabSize](akashaproject_design_system._internal_.StandardLonghandProperties.md#tabsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4432

___

### tableLayout

• `Optional` **tableLayout**: [`TableLayout`](../modules/akashaproject_design_system._internal_.md#tablelayout)

The **`table-layout`** CSS property sets the algorithm used to lay out `<table>` cells, rows, and columns.

**Syntax**: `auto | fixed`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **14** |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/table-layout

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[tableLayout](akashaproject_design_system._internal_.StandardLonghandProperties.md#tablelayout)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4446

___

### textAlign

• `Optional` **textAlign**: [`TextAlign`](../modules/akashaproject_design_system._internal_.md#textalign)

The **`text-align`** CSS property sets the horizontal alignment of a block element or table-cell box. This means it works like `vertical-align` but in the horizontal direction.

**Syntax**: `start | end | left | right | center | justify | match-parent`

**Initial value**: `start`, or a nameless value that acts as `left` if _direction_ is `ltr`, `right` if _direction_ is `rtl` if `start` is not supported by the browser.

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-align

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textAlign](akashaproject_design_system._internal_.StandardLonghandProperties.md#textalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4460

___

### textAlignLast

• `Optional` **textAlignLast**: [`TextAlignLast`](../modules/akashaproject_design_system._internal_.md#textalignlast)

The **`text-align-last`** CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

**Syntax**: `auto | start | end | left | right | center | justify`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **47** | **49**  |   No   | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-align-last

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textAlignLast](akashaproject_design_system._internal_.StandardLonghandProperties.md#textalignlast)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4474

___

### textCombineUpright

• `Optional` **textCombineUpright**: [`TextCombineUpright`](../modules/akashaproject_design_system._internal_.md#textcombineupright)

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

|           Chrome           | Firefox |              Safari              | Edge  |                   IE                   |
| :------------------------: | :-----: | :------------------------------: | :---: | :------------------------------------: |
|           **48**           | **48**  | **5.1** _(-webkit-text-combine)_ | 15-79 | **11** _(-ms-text-combine-horizontal)_ |
| 9 _(-webkit-text-combine)_ |         |                                  |       |                                        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-combine-upright

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textCombineUpright](akashaproject_design_system._internal_.StandardLonghandProperties.md#textcombineupright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4489

___

### textDecoration

• `Optional` **textDecoration**: [`TextDecoration`](../modules/akashaproject_design_system._internal_.md#textdecoration)<`TLength`\>

The **`text-decoration`** shorthand CSS property sets the appearance of decorative lines on text. It is a shorthand for `text-decoration-line`, `text-decoration-color`, `text-decoration-style`, and the newer `text-decoration-thickness` property.

**Syntax**: `<'text-decoration-line'> || <'text-decoration-style'> || <'text-decoration-color'> || <'text-decoration-thickness'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[textDecoration](akashaproject_design_system._internal_.StandardShorthandProperties.md#textdecoration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5706

___

### textDecorationColor

• `Optional` **textDecorationColor**: [`TextDecorationColor`](../modules/akashaproject_design_system._internal_.md#textdecorationcolor)

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4504

___

### textDecorationLine

• `Optional` **textDecorationLine**: [`TextDecorationLine`](../modules/akashaproject_design_system._internal_.md#textdecorationline)

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-line

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationLine](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4519

___

### textDecorationSkip

• `Optional` **textDecorationSkip**: [`TextDecorationSkip`](../modules/akashaproject_design_system._internal_.md#textdecorationskip)

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
| 57-64  |   No    | **12.1** |  No  | No  |
|        |         | 7 _-x-_  |      |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-skip

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationSkip](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationskip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4534

___

### textDecorationSkipInk

• `Optional` **textDecorationSkipInk**: [`TextDecorationSkipInk`](../modules/akashaproject_design_system._internal_.md#textdecorationskipink)

The **`text-decoration-skip-ink`** CSS property specifies how overlines and underlines are drawn when they pass over glyph ascenders and descenders.

**Syntax**: `auto | all | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **64** | **70**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-skip-ink

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationSkipInk](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationskipink)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4548

___

### textDecorationStyle

• `Optional` **textDecorationStyle**: [`TextDecorationStyle`](../modules/akashaproject_design_system._internal_.md#textdecorationstyle)

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4563

___

### textDecorationThickness

• `Optional` **textDecorationThickness**: [`TextDecorationThickness`](../modules/akashaproject_design_system._internal_.md#textdecorationthickness)<`TLength`\>

The **`text-decoration-thickness`** CSS property sets the stroke thickness of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **89** | **70**  | **12.1** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationThickness](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationthickness)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4577

___

### textDecorationWidth

• `Optional` **textDecorationWidth**: [`TextDecorationThickness`](../modules/akashaproject_design_system._internal_.md#textdecorationthickness)<`TLength`\>

The **`text-decoration-thickness`** CSS property sets the stroke thickness of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  | Edge  | IE  |
| :----: | :-----: | :------: | :---: | :-: |
| 87-89  | **70**  | **12.1** | 87-89 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textDecorationWidth](akashaproject_design_system._internal_.StandardLonghandProperties.md#textdecorationwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4591

___

### textEmphasis

• `Optional` **textEmphasis**: [`TextEmphasis`](../modules/akashaproject_design_system._internal_.md#textemphasis)

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[textEmphasis](akashaproject_design_system._internal_.StandardShorthandProperties.md#textemphasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5718

___

### textEmphasisColor

• `Optional` **textEmphasisColor**: [`TextEmphasisColor`](../modules/akashaproject_design_system._internal_.md#textemphasiscolor)

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-color

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textEmphasisColor](akashaproject_design_system._internal_.StandardLonghandProperties.md#textemphasiscolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4605

___

### textEmphasisPosition

• `Optional` **textEmphasisPosition**: [`TextEmphasisPosition`](../modules/akashaproject_design_system._internal_.md#textemphasisposition)

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textEmphasisPosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#textemphasisposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4619

___

### textEmphasisStyle

• `Optional` **textEmphasisStyle**: [`TextEmphasisStyle`](../modules/akashaproject_design_system._internal_.md#textemphasisstyle)

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textEmphasisStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#textemphasisstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4633

___

### textIndent

• `Optional` **textIndent**: [`TextIndent`](../modules/akashaproject_design_system._internal_.md#textindent)<`TLength`\>

The **`text-indent`** CSS property sets the length of empty space (indentation) that is put before lines of text in a block.

**Syntax**: `<length-percentage> && hanging? && each-line?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-indent

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textIndent](akashaproject_design_system._internal_.StandardLonghandProperties.md#textindent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4647

___

### textJustify

• `Optional` **textJustify**: [`TextJustify`](../modules/akashaproject_design_system._internal_.md#textjustify)

The **`text-justify`** CSS property sets what type of justification should be applied to text when `text-align``: justify;` is set on an element.

**Syntax**: `auto | inter-character | inter-word | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
|  n/a   | **55**  |   No   | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-justify

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textJustify](akashaproject_design_system._internal_.StandardLonghandProperties.md#textjustify)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4661

___

### textOrientation

• `Optional` **textOrientation**: [`TextOrientation`](../modules/akashaproject_design_system._internal_.md#textorientation)

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

|  Chrome  | Firefox |  Safari   |  Edge  | IE  |
| :------: | :-----: | :-------: | :----: | :-: |
|  **48**  | **41**  |  **14**   | **79** | No  |
| 11 _-x-_ |         | 5.1 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-orientation

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textOrientation](akashaproject_design_system._internal_.StandardLonghandProperties.md#textorientation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4676

___

### textOverflow

• `Optional` **textOverflow**: [`TextOverflow`](../modules/akashaproject_design_system._internal_.md#textoverflow)

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **7**  | **1.3** | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-overflow

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textOverflow](akashaproject_design_system._internal_.StandardLonghandProperties.md#textoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4690

___

### textRendering

• `Optional` **textRendering**: [`TextRendering`](../modules/akashaproject_design_system._internal_.md#textrendering)

The **`text-rendering`** CSS property provides information to the rendering engine about what to optimize for when rendering text.

**Syntax**: `auto | optimizeSpeed | optimizeLegibility | geometricPrecision`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **4**  |  **1**  | **5**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-rendering

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textRendering](akashaproject_design_system._internal_.StandardLonghandProperties.md#textrendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4704

___

### textShadow

• `Optional` **textShadow**: [`TextShadow`](../modules/akashaproject_design_system._internal_.md#textshadow)

The **`text-shadow`** CSS property adds shadows to text. It accepts a comma-separated list of shadows to be applied to the text and any of its `decorations`. Each shadow is described by some combination of X and Y offsets from the element, blur radius, and color.

**Syntax**: `none | <shadow-t>#`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **2**  | **3.5** | **1.1** | **12** | **10** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-shadow

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textShadow](akashaproject_design_system._internal_.StandardLonghandProperties.md#textshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4718

___

### textSizeAdjust

• `Optional` **textSizeAdjust**: [`TextSizeAdjust`](../modules/akashaproject_design_system._internal_.md#textsizeadjust)

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **54** |   No    |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-size-adjust

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textSizeAdjust](akashaproject_design_system._internal_.StandardLonghandProperties.md#textsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4732

___

### textTransform

• `Optional` **textTransform**: [`TextTransform`](../modules/akashaproject_design_system._internal_.md#texttransform)

The **`text-transform`** CSS property specifies how to capitalize an element's text. It can be used to make text appear in all-uppercase or all-lowercase, or with each word capitalized. It also can help improve legibility for ruby.

**Syntax**: `none | capitalize | uppercase | lowercase | full-width | full-size-kana`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-transform

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textTransform](akashaproject_design_system._internal_.StandardLonghandProperties.md#texttransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4746

___

### textUnderlineOffset

• `Optional` **textUnderlineOffset**: [`TextUnderlineOffset`](../modules/akashaproject_design_system._internal_.md#textunderlineoffset)<`TLength`\>

The **`text-underline-offset`** CSS property sets the offset distance of an underline text decoration line (applied using `text-decoration`) from its original position.

**Syntax**: `auto | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **70**  | **12.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-underline-offset

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textUnderlineOffset](akashaproject_design_system._internal_.StandardLonghandProperties.md#textunderlineoffset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4760

___

### textUnderlinePosition

• `Optional` **textUnderlinePosition**: [`TextUnderlinePosition`](../modules/akashaproject_design_system._internal_.md#textunderlineposition)

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |  IE   |
| :----: | :-----: | :------: | :----: | :---: |
| **33** | **74**  | **12.1** | **12** | **6** |
|        |         | 9 _-x-_  |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-underline-position

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[textUnderlinePosition](akashaproject_design_system._internal_.StandardLonghandProperties.md#textunderlineposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4775

___

### top

• `Optional` **top**: [`Top`](../modules/akashaproject_design_system._internal_.md#top)<`TLength`\>

The **`top`** CSS property participates in specifying the vertical position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/top

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[top](akashaproject_design_system._internal_.StandardLonghandProperties.md#top)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4789

___

### touchAction

• `Optional` **touchAction**: [`TouchAction`](../modules/akashaproject_design_system._internal_.md#touchaction)

The **`touch-action`** CSS property sets how an element's region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |    IE    |
| :----: | :-----: | :----: | :----: | :------: |
| **36** | **52**  | **13** | **12** |  **11**  |
|        |         |        |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/touch-action

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[touchAction](akashaproject_design_system._internal_.StandardLonghandProperties.md#touchaction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4804

___

### transform

• `Optional` **transform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

| Chrome  | Firefox |  Safari   |  Edge  |   IE    |
| :-----: | :-----: | :-------: | :----: | :-----: |
| **36**  | **16**  |   **9**   | **12** | **10**  |
| 1 _-x-_ |         | 3.1 _-x-_ |        | 9 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transform](akashaproject_design_system._internal_.StandardLonghandProperties.md#transform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4819

___

### transformBox

• `Optional` **transformBox**: [`TransformBox`](../modules/akashaproject_design_system._internal_.md#transformbox)

The **`transform-box`** CSS property defines the layout box to which the `transform` and `transform-origin` properties relate.

**Syntax**: `content-box | border-box | fill-box | stroke-box | view-box`

**Initial value**: `view-box`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **64** | **55**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-box

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transformBox](akashaproject_design_system._internal_.StandardLonghandProperties.md#transformbox)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4833

___

### transformOrigin

• `Optional` **transformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`TLength`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

| Chrome  |  Firefox  | Safari  |  Edge  |   IE    |
| :-----: | :-------: | :-----: | :----: | :-----: |
| **36**  |  **16**   |  **9**  | **12** | **10**  |
| 1 _-x-_ | 3.5 _-x-_ | 2 _-x-_ |        | 9 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-origin

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transformOrigin](akashaproject_design_system._internal_.StandardLonghandProperties.md#transformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4848

___

### transformStyle

• `Optional` **transformStyle**: [`TransformStyle`](../modules/akashaproject_design_system._internal_.md#transformstyle)

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

|  Chrome  | Firefox  | Safari  |  Edge  | IE  |
| :------: | :------: | :-----: | :----: | :-: |
|  **36**  |  **16**  |  **9**  | **12** | No  |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-style

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transformStyle](akashaproject_design_system._internal_.StandardLonghandProperties.md#transformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4863

___

### transition

• `Optional` **transition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`TTime`\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition

#### Inherited from

[StandardShorthandProperties](akashaproject_design_system._internal_.StandardShorthandProperties.md).[transition](akashaproject_design_system._internal_.StandardShorthandProperties.md#transition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5731

___

### transitionDelay

• `Optional` **transitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`TTime`\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **26**  | **16**  |  **9**  | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-delay

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transitionDelay](akashaproject_design_system._internal_.StandardLonghandProperties.md#transitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4878

___

### transitionDuration

• `Optional` **transitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`TTime`\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-duration

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transitionDuration](akashaproject_design_system._internal_.StandardLonghandProperties.md#transitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4893

___

### transitionProperty

• `Optional` **transitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-property

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transitionProperty](akashaproject_design_system._internal_.StandardLonghandProperties.md#transitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4908

___

### transitionTimingFunction

• `Optional` **transitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-timing-function

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[transitionTimingFunction](akashaproject_design_system._internal_.StandardLonghandProperties.md#transitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4923

___

### translate

• `Optional` **translate**: [`Translate`](../modules/akashaproject_design_system._internal_.md#translate)<`TLength`\>

The **`translate`** CSS property allows you to specify translation transforms individually and independently of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <length-percentage> [ <length-percentage> <length>? ]?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/translate

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[translate](akashaproject_design_system._internal_.StandardLonghandProperties.md#translate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4937

___

### unicodeBidi

• `Optional` **unicodeBidi**: [`UnicodeBidi`](../modules/akashaproject_design_system._internal_.md#unicodebidi)

The **`unicode-bidi`** CSS property, together with the `direction` property, determines how bidirectional text in a document is handled. For example, if a block of content contains both left-to-right and right-to-left text, the user-agent uses a complex Unicode algorithm to decide how to display the text. The `unicode-bidi` property overrides this algorithm and allows the developer to control the text embedding.

**Syntax**: `normal | embed | isolate | bidi-override | isolate-override | plaintext`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  |   IE    |
| :----: | :-----: | :-----: | :----: | :-----: |
| **2**  |  **1**  | **1.3** | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/unicode-bidi

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[unicodeBidi](akashaproject_design_system._internal_.StandardLonghandProperties.md#unicodebidi)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4951

___

### userSelect

• `Optional` **userSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

| Chrome  | Firefox |   Safari    |   Edge   |      IE      |
| :-----: | :-----: | :---------: | :------: | :----------: |
| **54**  | **69**  | **3** _-x-_ |  **79**  | **10** _-x-_ |
| 1 _-x-_ | 1 _-x-_ |             | 12 _-x-_ |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/user-select

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[userSelect](akashaproject_design_system._internal_.StandardLonghandProperties.md#userselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4966

___

### verticalAlign

• `Optional` **verticalAlign**: [`VerticalAlign`](../modules/akashaproject_design_system._internal_.md#verticalalign)<`TLength`\>

The **`vertical-align`** CSS property sets vertical alignment of an inline, inline-block or table-cell box.

**Syntax**: `baseline | sub | super | text-top | text-bottom | middle | top | bottom | <percentage> | <length>`

**Initial value**: `baseline`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/vertical-align

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[verticalAlign](akashaproject_design_system._internal_.StandardLonghandProperties.md#verticalalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4980

___

### visibility

• `Optional` **visibility**: [`Visibility`](../modules/akashaproject_design_system._internal_.md#visibility)

The **`visibility`** CSS property shows or hides an element without changing the layout of a document. The property can also hide rows or columns in a `<table>`.

**Syntax**: `visible | hidden | collapse`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/visibility

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[visibility](akashaproject_design_system._internal_.StandardLonghandProperties.md#visibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4994

___

### whiteSpace

• `Optional` **whiteSpace**: [`WhiteSpace`](../modules/akashaproject_design_system._internal_.md#whitespace)

The **`white-space`** CSS property sets how white space inside an element is handled.

**Syntax**: `normal | pre | nowrap | pre-wrap | pre-line | break-spaces`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/white-space

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[whiteSpace](akashaproject_design_system._internal_.StandardLonghandProperties.md#whitespace)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5008

___

### widows

• `Optional` **widows**: [`Widows`](../modules/akashaproject_design_system._internal_.md#widows)

The **`widows`** CSS property sets the minimum number of lines in a block container that must be shown at the _top_ of a page, region, or column.

**Syntax**: `<integer>`

**Initial value**: `2`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **25** |   No    | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/widows

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[widows](akashaproject_design_system._internal_.StandardLonghandProperties.md#widows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5022

___

### width

• `Optional` **width**: [`Width`](../modules/akashaproject_design_system._internal_.md#width)<`TLength`\>

The **`width`** CSS property sets an element's width. By default, it sets the width of the content area, but if `box-sizing` is set to `border-box`, it sets the width of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/width

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[width](akashaproject_design_system._internal_.StandardLonghandProperties.md#width)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5036

___

### willChange

• `Optional` **willChange**: [`WillChange`](../modules/akashaproject_design_system._internal_.md#willchange)

The **`will-change`** CSS property hints to browsers how an element is expected to change. Browsers may set up optimizations before an element is actually changed. These kinds of optimizations can increase the responsiveness of a page by doing potentially expensive work before they are actually required.

**Syntax**: `auto | <animateable-feature>#`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **36** | **36**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/will-change

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[willChange](akashaproject_design_system._internal_.StandardLonghandProperties.md#willchange)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5050

___

### wordBreak

• `Optional` **wordBreak**: [`WordBreak`](../modules/akashaproject_design_system._internal_.md#wordbreak)

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  | **15**  | **3**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/word-break

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[wordBreak](akashaproject_design_system._internal_.StandardLonghandProperties.md#wordbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5064

___

### wordSpacing

• `Optional` **wordSpacing**: [`WordSpacing`](../modules/akashaproject_design_system._internal_.md#wordspacing)<`TLength`\>

The **`word-spacing`** CSS property sets the length of space between words and between tags.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/word-spacing

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[wordSpacing](akashaproject_design_system._internal_.StandardLonghandProperties.md#wordspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5078

___

### wordWrap

• `Optional` **wordWrap**: [`WordWrap`](../modules/akashaproject_design_system._internal_.md#wordwrap)

The `**overflow-wrap**` CSS property applies to inline elements, setting whether the browser should insert line breaks within an otherwise unbreakable string to prevent text from overflowing its line box.

**Syntax**: `normal | break-word`

**Initial value**: `normal`

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[wordWrap](akashaproject_design_system._internal_.StandardLonghandProperties.md#wordwrap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5086

___

### writingMode

• `Optional` **writingMode**: [`WritingMode`](../modules/akashaproject_design_system._internal_.md#writingmode)

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (`html` element for HTML documents).

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

| Chrome  | Firefox |  Safari   |  Edge  |  IE   |
| :-----: | :-----: | :-------: | :----: | :---: |
| **48**  | **41**  | **10.1**  | **12** | **9** |
| 8 _-x-_ |         | 5.1 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/writing-mode

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[writingMode](akashaproject_design_system._internal_.StandardLonghandProperties.md#writingmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5101

___

### zIndex

• `Optional` **zIndex**: [`ZIndex`](../modules/akashaproject_design_system._internal_.md#zindex)

The **`z-index`** CSS property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.

**Syntax**: `auto | <integer>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/z-index

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[zIndex](akashaproject_design_system._internal_.StandardLonghandProperties.md#zindex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5115

___

### zoom

• `Optional` **zoom**: [`Zoom`](../modules/akashaproject_design_system._internal_.md#zoom)

The non-standard **`zoom`** CSS property can be used to control the magnification level of an element. `transform: scale()` should be used instead of this property, if possible. However, unlike CSS Transforms, `zoom` affects the layout size of the element.

**Syntax**: `normal | reset | <number> | <percentage>`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  |   IE    |
| :----: | :-----: | :-----: | :----: | :-----: |
| **1**  |   No    | **3.1** | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/zoom

#### Inherited from

[StandardLonghandProperties](akashaproject_design_system._internal_.StandardLonghandProperties.md).[zoom](akashaproject_design_system._internal_.StandardLonghandProperties.md#zoom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5129
