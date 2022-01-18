[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / VendorPropertiesFallback

# Interface: VendorPropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).VendorPropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- [`VendorLonghandPropertiesFallback`](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md)<`TLength`\>

- [`VendorShorthandPropertiesFallback`](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md)<`TLength`\>

  ↳ **`VendorPropertiesFallback`**

  ↳↳ [`PropertiesFallback`](akashaproject_design_system._internal_.PropertiesFallback.md)

## Table of contents

### Properties

- [MozAnimation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimation)
- [MozAnimationDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationdelay)
- [MozAnimationDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationdirection)
- [MozAnimationDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationduration)
- [MozAnimationFillMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationfillmode)
- [MozAnimationIterationCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationiterationcount)
- [MozAnimationName](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationname)
- [MozAnimationPlayState](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationplaystate)
- [MozAnimationTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationtimingfunction)
- [MozAppearance](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozappearance)
- [MozBackfaceVisibility](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozbackfacevisibility)
- [MozBorderBottomColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderbottomcolors)
- [MozBorderEndColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendcolor)
- [MozBorderEndStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendstyle)
- [MozBorderEndWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendwidth)
- [MozBorderImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderimage)
- [MozBorderLeftColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderleftcolors)
- [MozBorderRightColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderrightcolors)
- [MozBorderStartColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderstartcolor)
- [MozBorderStartStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderstartstyle)
- [MozBorderTopColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozbordertopcolors)
- [MozBoxSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozboxsizing)
- [MozColumnCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumncount)
- [MozColumnFill](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnfill)
- [MozColumnGap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumngap)
- [MozColumnRule](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrule)
- [MozColumnRuleColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulecolor)
- [MozColumnRuleStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulestyle)
- [MozColumnRuleWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulewidth)
- [MozColumnWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnwidth)
- [MozColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumns)
- [MozContextProperties](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcontextproperties)
- [MozFontFeatureSettings](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozfontfeaturesettings)
- [MozFontLanguageOverride](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozfontlanguageoverride)
- [MozHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozhyphens)
- [MozImageRegion](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozimageregion)
- [MozMarginEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozmarginend)
- [MozMarginStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozmarginstart)
- [MozOrient](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozorient)
- [MozOsxFontSmoothing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozosxfontsmoothing)
- [MozPaddingEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozpaddingend)
- [MozPaddingStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozpaddingstart)
- [MozPerspective](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozperspective)
- [MozPerspectiveOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozperspectiveorigin)
- [MozStackSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozstacksizing)
- [MozTabSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztabsize)
- [MozTextBlink](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztextblink)
- [MozTextSizeAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztextsizeadjust)
- [MozTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransformorigin)
- [MozTransformStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransformstyle)
- [MozTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransition)
- [MozTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitiondelay)
- [MozTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitionduration)
- [MozTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitionproperty)
- [MozTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitiontimingfunction)
- [MozUserFocus](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozuserfocus)
- [MozUserModify](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozusermodify)
- [MozUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozuserselect)
- [MozWindowDragging](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozwindowdragging)
- [MozWindowShadow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozwindowshadow)
- [WebkitAlignContent](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitaligncontent)
- [WebkitAlignItems](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitalignitems)
- [WebkitAlignSelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitalignself)
- [WebkitAnimation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimation)
- [WebkitAnimationDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationdelay)
- [WebkitAnimationDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationdirection)
- [WebkitAnimationDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationduration)
- [WebkitAnimationFillMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationfillmode)
- [WebkitAnimationIterationCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationiterationcount)
- [WebkitAnimationName](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationname)
- [WebkitAnimationPlayState](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationplaystate)
- [WebkitAnimationTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationtimingfunction)
- [WebkitAppearance](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitappearance)
- [WebkitBackdropFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackdropfilter)
- [WebkitBackfaceVisibility](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackfacevisibility)
- [WebkitBackgroundClip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundclip)
- [WebkitBackgroundOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundorigin)
- [WebkitBackgroundSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundsize)
- [WebkitBorderBefore](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbefore)
- [WebkitBorderBeforeColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforecolor)
- [WebkitBorderBeforeStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforestyle)
- [WebkitBorderBeforeWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforewidth)
- [WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbottomleftradius)
- [WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbottomrightradius)
- [WebkitBorderImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderimage)
- [WebkitBorderImageSlice](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderimageslice)
- [WebkitBorderRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderradius)
- [WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbordertopleftradius)
- [WebkitBorderTopRightRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbordertoprightradius)
- [WebkitBoxDecorationBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxdecorationbreak)
- [WebkitBoxReflect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxreflect)
- [WebkitBoxShadow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxshadow)
- [WebkitBoxSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxsizing)
- [WebkitClipPath](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitclippath)
- [WebkitColumnCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumncount)
- [WebkitColumnFill](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnfill)
- [WebkitColumnGap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumngap)
- [WebkitColumnRule](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrule)
- [WebkitColumnRuleColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulecolor)
- [WebkitColumnRuleStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulestyle)
- [WebkitColumnRuleWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulewidth)
- [WebkitColumnSpan](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnspan)
- [WebkitColumnWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnwidth)
- [WebkitColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumns)
- [WebkitFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfilter)
- [WebkitFlex](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflex)
- [WebkitFlexBasis](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexbasis)
- [WebkitFlexDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexdirection)
- [WebkitFlexFlow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexflow)
- [WebkitFlexGrow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexgrow)
- [WebkitFlexShrink](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexshrink)
- [WebkitFlexWrap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexwrap)
- [WebkitFontFeatureSettings](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontfeaturesettings)
- [WebkitFontKerning](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontkerning)
- [WebkitFontSmoothing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontsmoothing)
- [WebkitFontVariantLigatures](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontvariantligatures)
- [WebkitHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkithyphens)
- [WebkitJustifyContent](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitjustifycontent)
- [WebkitLineBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitlinebreak)
- [WebkitLineClamp](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitlineclamp)
- [WebkitMarginEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmarginend)
- [WebkitMarginStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmarginstart)
- [WebkitMask](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmask)
- [WebkitMaskAttachment](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskattachment)
- [WebkitMaskBoxImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximage)
- [WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximageoutset)
- [WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagerepeat)
- [WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximageslice)
- [WebkitMaskBoxImageSource](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagesource)
- [WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagewidth)
- [WebkitMaskClip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskclip)
- [WebkitMaskComposite](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskcomposite)
- [WebkitMaskImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskimage)
- [WebkitMaskOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskorigin)
- [WebkitMaskPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskposition)
- [WebkitMaskPositionX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskpositionx)
- [WebkitMaskPositionY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskpositiony)
- [WebkitMaskRepeat](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeat)
- [WebkitMaskRepeatX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeatx)
- [WebkitMaskRepeatY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeaty)
- [WebkitMaskSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmasksize)
- [WebkitMaxInlineSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaxinlinesize)
- [WebkitOrder](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitorder)
- [WebkitOverflowScrolling](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitoverflowscrolling)
- [WebkitPaddingEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitpaddingend)
- [WebkitPaddingStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitpaddingstart)
- [WebkitPerspective](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitperspective)
- [WebkitPerspectiveOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitperspectiveorigin)
- [WebkitPrintColorAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitprintcoloradjust)
- [WebkitRubyPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitrubyposition)
- [WebkitScrollSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitscrollsnaptype)
- [WebkitShapeMargin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitshapemargin)
- [WebkitTapHighlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittaphighlightcolor)
- [WebkitTextCombine](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextcombine)
- [WebkitTextDecorationColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationcolor)
- [WebkitTextDecorationLine](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationline)
- [WebkitTextDecorationSkip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationskip)
- [WebkitTextDecorationStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationstyle)
- [WebkitTextEmphasis](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasis)
- [WebkitTextEmphasisColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasiscolor)
- [WebkitTextEmphasisPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasisposition)
- [WebkitTextEmphasisStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasisstyle)
- [WebkitTextFillColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextfillcolor)
- [WebkitTextOrientation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextorientation)
- [WebkitTextSizeAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextsizeadjust)
- [WebkitTextStroke](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstroke)
- [WebkitTextStrokeColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstrokecolor)
- [WebkitTextStrokeWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstrokewidth)
- [WebkitTextUnderlinePosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextunderlineposition)
- [WebkitTouchCallout](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittouchcallout)
- [WebkitTransform](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransform)
- [WebkitTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransformorigin)
- [WebkitTransformStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransformstyle)
- [WebkitTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransition)
- [WebkitTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitiondelay)
- [WebkitTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitionduration)
- [WebkitTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitionproperty)
- [WebkitTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitiontimingfunction)
- [WebkitUserModify](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitusermodify)
- [WebkitUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkituserselect)
- [WebkitWritingMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitwritingmode)
- [msAccelerator](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msaccelerator)
- [msAlignSelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msalignself)
- [msBlockProgression](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msblockprogression)
- [msContentZoomChaining](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomchaining)
- [msContentZoomLimit](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimit)
- [msContentZoomLimitMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimitmax)
- [msContentZoomLimitMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimitmin)
- [msContentZoomSnap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnap)
- [msContentZoomSnapPoints](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnappoints)
- [msContentZoomSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnaptype)
- [msContentZooming](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzooming)
- [msFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msfilter)
- [msFlex](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflex)
- [msFlexDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflexdirection)
- [msFlexPositive](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflexpositive)
- [msFlowFrom](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflowfrom)
- [msFlowInto](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflowinto)
- [msGridColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msgridcolumns)
- [msGridRows](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msgridrows)
- [msHighContrastAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshighcontrastadjust)
- [msHyphenateLimitChars](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitchars)
- [msHyphenateLimitLines](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitlines)
- [msHyphenateLimitZone](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitzone)
- [msHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphens)
- [msImeAlign](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msimealign)
- [msJustifySelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msjustifyself)
- [msLineBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mslinebreak)
- [msOrder](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msorder)
- [msOverflowStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowstyle)
- [msOverflowX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowx)
- [msOverflowY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowy)
- [msScrollChaining](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollchaining)
- [msScrollLimit](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimit)
- [msScrollLimitXMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitxmax)
- [msScrollLimitXMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitxmin)
- [msScrollLimitYMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitymax)
- [msScrollLimitYMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitymin)
- [msScrollRails](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollrails)
- [msScrollSnapPointsX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnappointsx)
- [msScrollSnapPointsY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnappointsy)
- [msScrollSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnaptype)
- [msScrollSnapX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnapx)
- [msScrollSnapY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnapy)
- [msScrollTranslation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolltranslation)
- [msScrollbar3dlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbar3dlightcolor)
- [msScrollbarArrowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbararrowcolor)
- [msScrollbarBaseColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarbasecolor)
- [msScrollbarDarkshadowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbardarkshadowcolor)
- [msScrollbarFaceColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarfacecolor)
- [msScrollbarHighlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarhighlightcolor)
- [msScrollbarShadowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarshadowcolor)
- [msTextAutospace](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextautospace)
- [msTextCombineHorizontal](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextcombinehorizontal)
- [msTextOverflow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextoverflow)
- [msTouchAction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstouchaction)
- [msTouchSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstouchselect)
- [msTransform](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransform)
- [msTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransformorigin)
- [msTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransition)
- [msTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitiondelay)
- [msTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitionduration)
- [msTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitionproperty)
- [msTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitiontimingfunction)
- [msUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msuserselect)
- [msWordBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswordbreak)
- [msWrapFlow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapflow)
- [msWrapMargin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapmargin)
- [msWrapThrough](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapthrough)
- [msWritingMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswritingmode)

## Properties

### MozAnimation

• `Optional` **MozAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[MozAnimation](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozanimation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25147

___

### MozAnimationDelay

• `Optional` **MozAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationDelay](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23354

___

### MozAnimationDirection

• `Optional` **MozAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationDirection](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23362

___

### MozAnimationDuration

• `Optional` **MozAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationDuration](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23370

___

### MozAnimationFillMode

• `Optional` **MozAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationFillMode](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23378

___

### MozAnimationIterationCount

• `Optional` **MozAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationIterationCount](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23386

___

### MozAnimationName

• `Optional` **MozAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationName](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23394

___

### MozAnimationPlayState

• `Optional` **MozAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationPlayState](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23402

___

### MozAnimationTimingFunction

• `Optional` **MozAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAnimationTimingFunction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozanimationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23410

___

### MozAppearance

• `Optional` **MozAppearance**: [`MozAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#mozappearanceproperty) \| [`MozAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#mozappearanceproperty)[]

The **`-moz-appearance`** CSS property is used in Gecko (Firefox) to display an element using platform-native styling based on the operating system's theme.

**Syntax**: `none | button | button-arrow-down | button-arrow-next | button-arrow-previous | button-arrow-up | button-bevel | button-focus | caret | checkbox | checkbox-container | checkbox-label | checkmenuitem | dualbutton | groupbox | listbox | listitem | menuarrow | menubar | menucheckbox | menuimage | menuitem | menuitemtext | menulist | menulist-button | menulist-text | menulist-textfield | menupopup | menuradio | menuseparator | meterbar | meterchunk | progressbar | progressbar-vertical | progresschunk | progresschunk-vertical | radio | radio-container | radio-label | radiomenuitem | range | range-thumb | resizer | resizerpanel | scale-horizontal | scalethumbend | scalethumb-horizontal | scalethumbstart | scalethumbtick | scalethumb-vertical | scale-vertical | scrollbarbutton-down | scrollbarbutton-left | scrollbarbutton-right | scrollbarbutton-up | scrollbarthumb-horizontal | scrollbarthumb-vertical | scrollbartrack-horizontal | scrollbartrack-vertical | searchfield | separator | sheet | spinner | spinner-downbutton | spinner-textfield | spinner-upbutton | splitter | statusbar | statusbarpanel | tab | tabpanel | tabpanels | tab-scroll-arrow-back | tab-scroll-arrow-forward | textfield | textfield-multiline | toolbar | toolbarbutton | toolbarbutton-dropdown | toolbargripper | toolbox | tooltip | treeheader | treeheadercell | treeheadersortarrow | treeitem | treeline | treetwisty | treetwistyopen | treeview | -moz-mac-unified-toolbar | -moz-win-borderless-glass | -moz-win-browsertabbar-toolbox | -moz-win-communicationstext | -moz-win-communications-toolbox | -moz-win-exclude-glass | -moz-win-glass | -moz-win-mediatext | -moz-win-media-toolbox | -moz-window-button-box | -moz-window-button-box-maximized | -moz-window-button-close | -moz-window-button-maximize | -moz-window-button-minimize | -moz-window-button-restore | -moz-window-frame-bottom | -moz-window-frame-left | -moz-window-frame-right | -moz-window-titlebar | -moz-window-titlebar-maximized`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozAppearance](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozappearance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23418

___

### MozBackfaceVisibility

• `Optional` **MozBackfaceVisibility**: [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty) \| [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty)[]

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBackfaceVisibility](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozbackfacevisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23426

___

### MozBorderBottomColors

• `Optional` **MozBorderBottomColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-bottom-colors`** CSS property sets a list of colors for the bottom border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderBottomColors](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderbottomcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23434

___

### MozBorderEndColor

• `Optional` **MozBorderEndColor**: `string` \| `string`[]

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderEndColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderendcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23442

___

### MozBorderEndStyle

• `Optional` **MozBorderEndStyle**: [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty) \| [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty)[]

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderEndStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderendstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23450

___

### MozBorderEndWidth

• `Optional` **MozBorderEndWidth**: [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\> \| [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\>[]

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderEndWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderendwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23458

___

### MozBorderImage

• `Optional` **MozBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[MozBorderImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozborderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25153

___

### MozBorderLeftColors

• `Optional` **MozBorderLeftColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-left-colors`** CSS property sets a list of colors for the left border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderLeftColors](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderleftcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23466

___

### MozBorderRightColors

• `Optional` **MozBorderRightColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-right-colors`** CSS property sets a list of colors for the right border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderRightColors](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderrightcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23474

___

### MozBorderStartColor

• `Optional` **MozBorderStartColor**: `string` \| `string`[]

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderStartColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderstartcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23482

___

### MozBorderStartStyle

• `Optional` **MozBorderStartStyle**: [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty) \| [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty)[]

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderStartStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozborderstartstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23490

___

### MozBorderTopColors

• `Optional` **MozBorderTopColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-top-colors`** CSS property sets a list of colors for the top border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBorderTopColors](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozbordertopcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23498

___

### MozBoxSizing

• `Optional` **MozBoxSizing**: [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty) \| [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty)[]

The **`box-sizing`** CSS property defines how the user agent should calculate the total width and height of an element.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozBoxSizing](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozboxsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23506

___

### MozColumnCount

• `Optional` **MozColumnCount**: [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty) \| [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty)[]

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnCount](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumncount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23514

___

### MozColumnFill

• `Optional` **MozColumnFill**: [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty) \| [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty)[]

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnFill](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumnfill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23522

___

### MozColumnGap

• `Optional` **MozColumnGap**: [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\> \| [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnGap](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23530

___

### MozColumnRule

• `Optional` **MozColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[MozColumnRule](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozcolumnrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25159

___

### MozColumnRuleColor

• `Optional` **MozColumnRuleColor**: `string` \| `string`[]

The **`column-rule-color`** CSS property sets the color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnRuleColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumnrulecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23538

___

### MozColumnRuleStyle

• `Optional` **MozColumnRuleStyle**: `string` \| `string`[]

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnRuleStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumnrulestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23546

___

### MozColumnRuleWidth

• `Optional` **MozColumnRuleWidth**: [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\> \| [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\>[]

The **`column-rule-width`** CSS property sets the width of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnRuleWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumnrulewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23554

___

### MozColumnWidth

• `Optional` **MozColumnWidth**: [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\> \| [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\>[]

The **`column-width`** CSS property specifies the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozColumnWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcolumnwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23562

___

### MozColumns

• `Optional` **MozColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[MozColumns](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mozcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25165

___

### MozContextProperties

• `Optional` **MozContextProperties**: `string` \| `string`[]

If you reference an SVG image in a webpage (such as with the `<img>` element or as a background image), the SVG image can coordinate with the embedding element (its context) to have the image adopt property values set on the embedding element. To do this the embedding element needs to list the properties that are to be made available to the image by listing them as values of the **`-moz-context-properties`** property, and the image needs to opt in to using those properties by using values such as the `context-fill` value.

**Syntax**: `none | [ fill | fill-opacity | stroke | stroke-opacity ]#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozContextProperties](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozcontextproperties)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23570

___

### MozFontFeatureSettings

• `Optional` **MozFontFeatureSettings**: `string` \| `string`[]

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozFontFeatureSettings](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozfontfeaturesettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23578

___

### MozFontLanguageOverride

• `Optional` **MozFontLanguageOverride**: `string` \| `string`[]

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozFontLanguageOverride](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozfontlanguageoverride)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23586

___

### MozHyphens

• `Optional` **MozHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozHyphens](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozhyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23594

___

### MozImageRegion

• `Optional` **MozImageRegion**: `string` \| `string`[]

For certain XUL elements and pseudo-elements that use an image from the `list-style-image` property, this property specifies a region of the image that is used in place of the whole image. This allows elements to use different pieces of the same image to improve performance.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozImageRegion](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozimageregion)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23602

___

### MozMarginEnd

• `Optional` **MozMarginEnd**: [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\> \| [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\>[]

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozMarginEnd](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozmarginend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23610

___

### MozMarginStart

• `Optional` **MozMarginStart**: [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\> \| [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\>[]

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozMarginStart](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozmarginstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23618

___

### MozOrient

• `Optional` **MozOrient**: [`MozOrientProperty`](../modules/akashaproject_design_system._internal_.md#mozorientproperty) \| [`MozOrientProperty`](../modules/akashaproject_design_system._internal_.md#mozorientproperty)[]

The **`-moz-orient`** CSS property specifies the orientation of the element to which it's applied.

**Syntax**: `inline | block | horizontal | vertical`

**Initial value**: `inline`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozOrient](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23626

___

### MozOsxFontSmoothing

• `Optional` **MozOsxFontSmoothing**: [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\> \| [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\>[]

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozOsxFontSmoothing](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozosxfontsmoothing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23634

___

### MozPaddingEnd

• `Optional` **MozPaddingEnd**: [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\> \| [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\>[]

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozPaddingEnd](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozpaddingend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23642

___

### MozPaddingStart

• `Optional` **MozPaddingStart**: [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\> \| [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\>[]

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozPaddingStart](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozpaddingstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23650

___

### MozPerspective

• `Optional` **MozPerspective**: [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\> \| [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\>[]

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective. Each 3D element with z>0 becomes larger; each 3D-element with z<0 becomes smaller. The strength of the effect is determined by the value of this property.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozPerspective](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozperspective)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23658

___

### MozPerspectiveOrigin

• `Optional` **MozPerspectiveOrigin**: [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\> \| [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\>[]

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozPerspectiveOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozperspectiveorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23666

___

### MozStackSizing

• `Optional` **MozStackSizing**: [`MozStackSizingProperty`](../modules/akashaproject_design_system._internal_.md#mozstacksizingproperty) \| [`MozStackSizingProperty`](../modules/akashaproject_design_system._internal_.md#mozstacksizingproperty)[]

**`-moz-stack-sizing`** is an extended CSS property. Normally, a `stack` will change its size so that all of its child elements are completely visible. For example, moving a child of the stack far to the right will widen the stack so the child remains visible.

**Syntax**: `ignore | stretch-to-fit`

**Initial value**: `stretch-to-fit`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozStackSizing](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozstacksizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23674

___

### MozTabSize

• `Optional` **MozTabSize**: [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\> \| [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\>[]

The **`tab-size`** CSS property is used to customize the width of a tab (`U+0009`) character.

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTabSize](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztabsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23682

___

### MozTextBlink

• `Optional` **MozTextBlink**: [`MozTextBlinkProperty`](../modules/akashaproject_design_system._internal_.md#moztextblinkproperty) \| [`MozTextBlinkProperty`](../modules/akashaproject_design_system._internal_.md#moztextblinkproperty)[]

The **`-moz-text-blink`** non-standard Mozilla CSS extension specifies the blink mode.

**Syntax**: `none | blink`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTextBlink](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztextblink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23690

___

### MozTextSizeAdjust

• `Optional` **MozTextSizeAdjust**: `string` \| `string`[]

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTextSizeAdjust](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztextsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23698

___

### MozTransformOrigin

• `Optional` **MozTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransformOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23706

___

### MozTransformStyle

• `Optional` **MozTransformStyle**: [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty) \| [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty)[]

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransformStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransformstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23714

___

### MozTransition

• `Optional` **MozTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[MozTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#moztransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25171

___

### MozTransitionDelay

• `Optional` **MozTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransitionDelay](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23722

___

### MozTransitionDuration

• `Optional` **MozTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransitionDuration](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23730

___

### MozTransitionProperty

• `Optional` **MozTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransitionProperty](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23738

___

### MozTransitionTimingFunction

• `Optional` **MozTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozTransitionTimingFunction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#moztransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23746

___

### MozUserFocus

• `Optional` **MozUserFocus**: [`MozUserFocusProperty`](../modules/akashaproject_design_system._internal_.md#mozuserfocusproperty) \| [`MozUserFocusProperty`](../modules/akashaproject_design_system._internal_.md#mozuserfocusproperty)[]

The **`-moz-user-focus`** CSS property is used to indicate whether an element can have the focus.

**Syntax**: `ignore | normal | select-after | select-before | select-menu | select-same | select-all | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozUserFocus](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozuserfocus)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23754

___

### MozUserModify

• `Optional` **MozUserModify**: [`MozUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#mozusermodifyproperty) \| [`MozUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#mozusermodifyproperty)[]

The **`user-modify`** property has no effect in Firefox. It was originally planned to determine whether or not the content of an element can be edited by a user.

**Syntax**: `read-only | read-write | write-only`

**Initial value**: `read-only`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozUserModify](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozusermodify)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23762

___

### MozUserSelect

• `Optional` **MozUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozUserSelect](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozuserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23770

___

### MozWindowDragging

• `Optional` **MozWindowDragging**: [`MozWindowDraggingProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowdraggingproperty) \| [`MozWindowDraggingProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowdraggingproperty)[]

The **`-moz-window-dragging`** CSS property specifies whether a window is draggable or not. It only works in Chrome code, and only on Mac OS X.

**Syntax**: `drag | no-drag`

**Initial value**: `drag`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozWindowDragging](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozwindowdragging)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23778

___

### MozWindowShadow

• `Optional` **MozWindowShadow**: [`MozWindowShadowProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowshadowproperty) \| [`MozWindowShadowProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowshadowproperty)[]

The **`-moz-window-shadow`** CSS property specifies whether a window will have a shadow. It only works on Mac OS X.

**Syntax**: `default | menu | tooltip | sheet | none`

**Initial value**: `default`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[MozWindowShadow](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mozwindowshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23786

___

### WebkitAlignContent

• `Optional` **WebkitAlignContent**: `string` \| `string`[]

The CSS **`align-content`** property sets how the browser distributes space between and around content items along the cross-axis of a flexbox container, and the main-axis of a grid container.

**Syntax**: `normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position>`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAlignContent](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitaligncontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24290

___

### WebkitAlignItems

• `Optional` **WebkitAlignItems**: `string` \| `string`[]

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. The align-self property sets the alignment of an item within its containing block. In Flexbox it controls the alignment of items on the Cross Axis, in Grid Layout it controls the alignment of items on the Block Axis within their grid area.

**Syntax**: `normal | stretch | <baseline-position> | [ <overflow-position>? <self-position> ]`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAlignItems](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitalignitems)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24298

___

### WebkitAlignSelf

• `Optional` **WebkitAlignSelf**: `string` \| `string`[]

The **`align-self`** CSS property aligns flex items of the current flex line overriding the `align-items` value. If any of the item's cross-axis margin is set to `auto`, then `align-self` is ignored. In Grid layout `align-self` aligns the item inside the grid area.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAlignSelf](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitalignself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24306

___

### WebkitAnimation

• `Optional` **WebkitAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitAnimation](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitanimation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25219

___

### WebkitAnimationDelay

• `Optional` **WebkitAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationDelay](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24314

___

### WebkitAnimationDirection

• `Optional` **WebkitAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationDirection](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24322

___

### WebkitAnimationDuration

• `Optional` **WebkitAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationDuration](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24330

___

### WebkitAnimationFillMode

• `Optional` **WebkitAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationFillMode](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24338

___

### WebkitAnimationIterationCount

• `Optional` **WebkitAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationIterationCount](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24346

___

### WebkitAnimationName

• `Optional` **WebkitAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationName](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24354

___

### WebkitAnimationPlayState

• `Optional` **WebkitAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationPlayState](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24362

___

### WebkitAnimationTimingFunction

• `Optional` **WebkitAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAnimationTimingFunction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitanimationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24370

___

### WebkitAppearance

• `Optional` **WebkitAppearance**: [`WebkitAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#webkitappearanceproperty) \| [`WebkitAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#webkitappearanceproperty)[]

The **`-moz-appearance`** CSS property is used in Gecko (Firefox) to display an element using platform-native styling based on the operating system's theme.

**Syntax**: `none | button | button-bevel | caret | checkbox | default-button | inner-spin-button | listbox | listitem | media-controls-background | media-controls-fullscreen-background | media-current-time-display | media-enter-fullscreen-button | media-exit-fullscreen-button | media-fullscreen-button | media-mute-button | media-overlay-play-button | media-play-button | media-seek-back-button | media-seek-forward-button | media-slider | media-sliderthumb | media-time-remaining-display | media-toggle-closed-captions-button | media-volume-slider | media-volume-slider-container | media-volume-sliderthumb | menulist | menulist-button | menulist-text | menulist-textfield | meter | progress-bar | progress-bar-value | push-button | radio | searchfield | searchfield-cancel-button | searchfield-decoration | searchfield-results-button | searchfield-results-decoration | slider-horizontal | slider-vertical | sliderthumb-horizontal | sliderthumb-vertical | square-button | textarea | textfield | -apple-pay-button`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitAppearance](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitappearance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24378

___

### WebkitBackdropFilter

• `Optional` **WebkitBackdropFilter**: `string` \| `string`[]

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBackdropFilter](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbackdropfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24386

___

### WebkitBackfaceVisibility

• `Optional` **WebkitBackfaceVisibility**: [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty) \| [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty)[]

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBackfaceVisibility](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbackfacevisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24394

___

### WebkitBackgroundClip

• `Optional` **WebkitBackgroundClip**: `string` \| `string`[]

The **`background-clip`** CSS property sets whether an element's background `<color>` or `<image>` extends underneath its border.

**Syntax**: `<box>#`

**Initial value**: `border-box`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBackgroundClip](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbackgroundclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24402

___

### WebkitBackgroundOrigin

• `Optional` **WebkitBackgroundOrigin**: `string` \| `string`[]

The **`background-origin`** CSS property sets the _background positioning area_. In other words, it sets the origin position of an image set with the `background-image` property.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBackgroundOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbackgroundorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24410

___

### WebkitBackgroundSize

• `Optional` **WebkitBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBackgroundSize](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbackgroundsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24418

___

### WebkitBorderBefore

• `Optional` **WebkitBorderBefore**: [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\> \| [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\>[]

The **`-webkit-border-before`** CSS property is a shorthand property for setting the individual logical block start border property values in a single place in the style sheet.

**Syntax**: `<'border-width'> || <'border-style'> || <color>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitBorderBefore](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderbefore)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25225

___

### WebkitBorderBeforeColor

• `Optional` **WebkitBorderBeforeColor**: `string` \| `string`[]

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderBeforeColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderbeforecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24424

___

### WebkitBorderBeforeStyle

• `Optional` **WebkitBorderBeforeStyle**: `string` \| `string`[]

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderBeforeStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderbeforestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24430

___

### WebkitBorderBeforeWidth

• `Optional` **WebkitBorderBeforeWidth**: [`WebkitBorderBeforeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidthproperty)<`TLength`\> \| [`WebkitBorderBeforeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidthproperty)<`TLength`\>[]

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderBeforeWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderbeforewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24436

___

### WebkitBorderBottomLeftRadius

• `Optional` **WebkitBorderBottomLeftRadius**: [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\> \| [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\>[]

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderbottomleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24444

___

### WebkitBorderBottomRightRadius

• `Optional` **WebkitBorderBottomRightRadius**: [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\> \| [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\>[]

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderbottomrightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24452

___

### WebkitBorderImage

• `Optional` **WebkitBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitBorderImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25231

___

### WebkitBorderImageSlice

• `Optional` **WebkitBorderImageSlice**: [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty) \| [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty)[]

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderImageSlice](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitborderimageslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24460

___

### WebkitBorderRadius

• `Optional` **WebkitBorderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitBorderRadius](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitborderradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25237

___

### WebkitBorderTopLeftRadius

• `Optional` **WebkitBorderTopLeftRadius**: [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\> \| [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\>[]

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbordertopleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24468

___

### WebkitBorderTopRightRadius

• `Optional` **WebkitBorderTopRightRadius**: [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\> \| [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\>[]

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBorderTopRightRadius](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitbordertoprightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24476

___

### WebkitBoxDecorationBreak

• `Optional` **WebkitBoxDecorationBreak**: [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty) \| [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty)[]

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBoxDecorationBreak](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitboxdecorationbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24484

___

### WebkitBoxReflect

• `Optional` **WebkitBoxReflect**: [`WebkitBoxReflectProperty`](../modules/akashaproject_design_system._internal_.md#webkitboxreflectproperty)<`TLength`\> \| [`WebkitBoxReflectProperty`](../modules/akashaproject_design_system._internal_.md#webkitboxreflectproperty)<`TLength`\>[]

The **`-webkit-box-reflect`** CSS property lets you reflect the content of an element in one specific direction.

**Syntax**: `[ above | below | right | left ]? <length>? <image>?`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBoxReflect](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitboxreflect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24492

___

### WebkitBoxShadow

• `Optional` **WebkitBoxShadow**: `string` \| `string`[]

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBoxShadow](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitboxshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24500

___

### WebkitBoxSizing

• `Optional` **WebkitBoxSizing**: [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty) \| [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty)[]

The **`box-sizing`** CSS property defines how the user agent should calculate the total width and height of an element.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitBoxSizing](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitboxsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24508

___

### WebkitClipPath

• `Optional` **WebkitClipPath**: `string` \| `string`[]

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitClipPath](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitclippath)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24516

___

### WebkitColumnCount

• `Optional` **WebkitColumnCount**: [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty) \| [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty)[]

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnCount](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumncount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24524

___

### WebkitColumnFill

• `Optional` **WebkitColumnFill**: [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty) \| [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty)[]

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnFill](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnfill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24532

___

### WebkitColumnGap

• `Optional` **WebkitColumnGap**: [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\> \| [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnGap](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24540

___

### WebkitColumnRule

• `Optional` **WebkitColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitColumnRule](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitcolumnrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25243

___

### WebkitColumnRuleColor

• `Optional` **WebkitColumnRuleColor**: `string` \| `string`[]

The **`column-rule-color`** CSS property sets the color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnRuleColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnrulecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24548

___

### WebkitColumnRuleStyle

• `Optional` **WebkitColumnRuleStyle**: `string` \| `string`[]

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnRuleStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnrulestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24556

___

### WebkitColumnRuleWidth

• `Optional` **WebkitColumnRuleWidth**: [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\> \| [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\>[]

The **`column-rule-width`** CSS property sets the width of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnRuleWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnrulewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24564

___

### WebkitColumnSpan

• `Optional` **WebkitColumnSpan**: [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty) \| [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty)[]

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnSpan](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnspan)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24572

___

### WebkitColumnWidth

• `Optional` **WebkitColumnWidth**: [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\> \| [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\>[]

The **`column-width`** CSS property specifies the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitColumnWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitcolumnwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24580

___

### WebkitColumns

• `Optional` **WebkitColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitColumns](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25249

___

### WebkitFilter

• `Optional` **WebkitFilter**: `string` \| `string`[]

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFilter](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24588

___

### WebkitFlex

• `Optional` **WebkitFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitFlex](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25255

___

### WebkitFlexBasis

• `Optional` **WebkitFlexBasis**: [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\> \| [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\>[]

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFlexBasis](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitflexbasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24596

___

### WebkitFlexDirection

• `Optional` **WebkitFlexDirection**: [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty) \| [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty)[]

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFlexDirection](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitflexdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24604

___

### WebkitFlexFlow

• `Optional` **WebkitFlexFlow**: `string` \| `string`[]

The **`flex-flow`** CSS property is a shorthand property for `flex-direction` and `flex-wrap` properties.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitFlexFlow](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitflexflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25261

___

### WebkitFlexGrow

• `Optional` **WebkitFlexGrow**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-grow`** CSS property sets how much of the available space in the flex container should be assigned to that item (the flex grow factor). If all sibling items have the same flex grow factor, then all items will receive the same share of available space, otherwise it is distributed according to the ratio defined by the different flex grow factors.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFlexGrow](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitflexgrow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24612

___

### WebkitFlexShrink

• `Optional` **WebkitFlexShrink**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFlexShrink](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitflexshrink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24620

___

### WebkitFlexWrap

• `Optional` **WebkitFlexWrap**: [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty) \| [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty)[]

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFlexWrap](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitflexwrap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24628

___

### WebkitFontFeatureSettings

• `Optional` **WebkitFontFeatureSettings**: `string` \| `string`[]

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFontFeatureSettings](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitfontfeaturesettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24636

___

### WebkitFontKerning

• `Optional` **WebkitFontKerning**: [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty) \| [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty)[]

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFontKerning](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitfontkerning)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24644

___

### WebkitFontSmoothing

• `Optional` **WebkitFontSmoothing**: [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\> \| [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\>[]

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFontSmoothing](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitfontsmoothing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24652

___

### WebkitFontVariantLigatures

• `Optional` **WebkitFontVariantLigatures**: `string` \| `string`[]

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitFontVariantLigatures](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitfontvariantligatures)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24660

___

### WebkitHyphens

• `Optional` **WebkitHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitHyphens](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkithyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24668

___

### WebkitJustifyContent

• `Optional` **WebkitJustifyContent**: `string` \| `string`[]

The CSS **`justify-content`** property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

**Syntax**: `normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ]`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitJustifyContent](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitjustifycontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24676

___

### WebkitLineBreak

• `Optional` **WebkitLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitLineBreak](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitlinebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24684

___

### WebkitLineClamp

• `Optional` **WebkitLineClamp**: [`WebkitLineClampProperty`](../modules/akashaproject_design_system._internal_.md#webkitlineclampproperty) \| [`WebkitLineClampProperty`](../modules/akashaproject_design_system._internal_.md#webkitlineclampproperty)[]

The **`-webkit-line-clamp`** CSS property allows limiting of the contents of a block container to the specified number of lines.

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitLineClamp](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitlineclamp)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24692

___

### WebkitMarginEnd

• `Optional` **WebkitMarginEnd**: [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\> \| [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\>[]

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMarginEnd](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmarginend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24700

___

### WebkitMarginStart

• `Optional` **WebkitMarginStart**: [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\> \| [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\>[]

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMarginStart](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmarginstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24708

___

### WebkitMask

• `Optional` **WebkitMask**: [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\> \| [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\>[]

The **`mask`** CSS property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `[ <mask-reference> || <position> [ / <bg-size> ]? || <repeat-style> || [ <box> | border | padding | content | text ] || [ <box> | border | padding | content ] ]#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitMask](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitmask)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25267

___

### WebkitMaskAttachment

• `Optional` **WebkitMaskAttachment**: `string` \| `string`[]

If a `-webkit-mask-image` is specified, `-webkit-mask-attachment` determines whether the mask image's position is fixed within the viewport, or scrolls along with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskAttachment](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskattachment)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24716

___

### WebkitMaskBoxImage

• `Optional` **WebkitMaskBoxImage**: [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty) \| [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty)[]

The **`mask-border`** CSS property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitMaskBoxImage](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkitmaskboximage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25273

___

### WebkitMaskBoxImageOutset

• `Optional` **WebkitMaskBoxImageOutset**: [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\> \| [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\>[]

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskboximageoutset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24724

___

### WebkitMaskBoxImageRepeat

• `Optional` **WebkitMaskBoxImageRepeat**: `string` \| `string`[]

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskboximagerepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24732

___

### WebkitMaskBoxImageSlice

• `Optional` **WebkitMaskBoxImageSlice**: [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty) \| [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty)[]

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskboximageslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24740

___

### WebkitMaskBoxImageSource

• `Optional` **WebkitMaskBoxImageSource**: `string` \| `string`[]

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskBoxImageSource](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskboximagesource)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24748

___

### WebkitMaskBoxImageWidth

• `Optional` **WebkitMaskBoxImageWidth**: [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\> \| [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\>[]

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskboximagewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24756

___

### WebkitMaskClip

• `Optional` **WebkitMaskClip**: `string` \| `string`[]

The **`mask-clip`** CSS property determines the area, which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <box> | border | padding | content | text ]#`

**Initial value**: `border`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskClip](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24764

___

### WebkitMaskComposite

• `Optional` **WebkitMaskComposite**: `string` \| `string`[]

The **`-webkit-mask-composite`** property specifies the manner in which multiple mask images applied to the same element are composited with one another. Mask images are composited in the opposite order that they are declared with the `-webkit-mask-image` property.

**Syntax**: `<composite-style>#`

**Initial value**: `source-over`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskComposite](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskcomposite)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24772

___

### WebkitMaskImage

• `Optional` **WebkitMaskImage**: `string` \| `string`[]

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskImage](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24780

___

### WebkitMaskOrigin

• `Optional` **WebkitMaskOrigin**: `string` \| `string`[]

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `[ <box> | border | padding | content ]#`

**Initial value**: `padding`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24788

___

### WebkitMaskPosition

• `Optional` **WebkitMaskPosition**: [`WebkitMaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionproperty)<`TLength`\> \| [`WebkitMaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionproperty)<`TLength`\>[]

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `0% 0%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskPosition](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24796

___

### WebkitMaskPositionX

• `Optional` **WebkitMaskPositionX**: [`WebkitMaskPositionXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionxproperty)<`TLength`\> \| [`WebkitMaskPositionXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionxproperty)<`TLength`\>[]

The `-webkit-mask-position-x` CSS property sets the initial horizontal position of a mask image.

**Syntax**: `[ <length-percentage> | left | center | right ]#`

**Initial value**: `0%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskPositionX](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskpositionx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24804

___

### WebkitMaskPositionY

• `Optional` **WebkitMaskPositionY**: [`WebkitMaskPositionYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionyproperty)<`TLength`\> \| [`WebkitMaskPositionYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionyproperty)<`TLength`\>[]

The `-webkit-mask-position-y` CSS property sets the initial vertical position of a mask image.

**Syntax**: `[ <length-percentage> | top | center | bottom ]#`

**Initial value**: `0%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskPositionY](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskpositiony)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24812

___

### WebkitMaskRepeat

• `Optional` **WebkitMaskRepeat**: `string` \| `string`[]

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskRepeat](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskrepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24820

___

### WebkitMaskRepeatX

• `Optional` **WebkitMaskRepeatX**: [`WebkitMaskRepeatXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatxproperty) \| [`WebkitMaskRepeatXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatxproperty)[]

The `-webkit-mask-repeat-x` property specifies whether and how a mask image is repeated (tiled) horizontally.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskRepeatX](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskrepeatx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24828

___

### WebkitMaskRepeatY

• `Optional` **WebkitMaskRepeatY**: [`WebkitMaskRepeatYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatyproperty) \| [`WebkitMaskRepeatYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatyproperty)[]

The `-webkit-mask-repeat-y` property sets whether and how a mask image is repeated (tiled) vertically.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskRepeatY](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaskrepeaty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24836

___

### WebkitMaskSize

• `Optional` **WebkitMaskSize**: [`WebkitMaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#webkitmasksizeproperty)<`TLength`\> \| [`WebkitMaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#webkitmasksizeproperty)<`TLength`\>[]

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaskSize](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmasksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24844

___

### WebkitMaxInlineSize

• `Optional` **WebkitMaxInlineSize**: [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\> \| [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\>[]

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block depending on its writing mode. It corresponds to the `max-width` or the `max-height` property depending on the value defined for `writing-mode`. If the writing mode is vertically oriented, the value of `max-inline-size` relates to the maximal height of the element, otherwise it relates to the maximal width of the element. It relates to `max-block-size`, which defines the other dimension of the element.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitMaxInlineSize](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitmaxinlinesize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24852

___

### WebkitOrder

• `Optional` **WebkitOrder**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitOrder](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitorder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24860

___

### WebkitOverflowScrolling

• `Optional` **WebkitOverflowScrolling**: [`WebkitOverflowScrollingProperty`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrollingproperty) \| [`WebkitOverflowScrollingProperty`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrollingproperty)[]

The `-webkit-overflow-scrolling` CSS property controls whether or not touch devices use momentum-based scrolling for a given element.

**Syntax**: `auto | touch`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitOverflowScrolling](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitoverflowscrolling)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24868

___

### WebkitPaddingEnd

• `Optional` **WebkitPaddingEnd**: [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\> \| [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\>[]

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitPaddingEnd](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitpaddingend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24876

___

### WebkitPaddingStart

• `Optional` **WebkitPaddingStart**: [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\> \| [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\>[]

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitPaddingStart](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitpaddingstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24884

___

### WebkitPerspective

• `Optional` **WebkitPerspective**: [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\> \| [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\>[]

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective. Each 3D element with z>0 becomes larger; each 3D-element with z<0 becomes smaller. The strength of the effect is determined by the value of this property.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitPerspective](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitperspective)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24892

___

### WebkitPerspectiveOrigin

• `Optional` **WebkitPerspectiveOrigin**: [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\> \| [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\>[]

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitPerspectiveOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitperspectiveorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24900

___

### WebkitPrintColorAdjust

• `Optional` **WebkitPrintColorAdjust**: [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty) \| [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty)[]

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitPrintColorAdjust](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitprintcoloradjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24908

___

### WebkitRubyPosition

• `Optional` **WebkitRubyPosition**: `string` \| `string`[]

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitRubyPosition](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitrubyposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24916

___

### WebkitScrollSnapType

• `Optional` **WebkitScrollSnapType**: `string` \| `string`[]

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitScrollSnapType](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitscrollsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24924

___

### WebkitShapeMargin

• `Optional` **WebkitShapeMargin**: [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\> \| [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\>[]

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitShapeMargin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitshapemargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24932

___

### WebkitTapHighlightColor

• `Optional` **WebkitTapHighlightColor**: `string` \| `string`[]

**`-webkit-tap-highlight-color`** is a non-standard CSS property that sets the color of the highlight that appears over a link while it's being tapped. The highlighting indicates to the user that their tap is being successfully recognized, and indicates which element they're tapping on.

**Syntax**: `<color>`

**Initial value**: `black`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTapHighlightColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittaphighlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24940

___

### WebkitTextCombine

• `Optional` **WebkitTextCombine**: `string` \| `string`[]

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextCombine](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextcombine)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24948

___

### WebkitTextDecorationColor

• `Optional` **WebkitTextDecorationColor**: `string` \| `string`[]

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextDecorationColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextdecorationcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24956

___

### WebkitTextDecorationLine

• `Optional` **WebkitTextDecorationLine**: `string` \| `string`[]

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextDecorationLine](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextdecorationline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24964

___

### WebkitTextDecorationSkip

• `Optional` **WebkitTextDecorationSkip**: `string` \| `string`[]

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextDecorationSkip](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextdecorationskip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24972

___

### WebkitTextDecorationStyle

• `Optional` **WebkitTextDecorationStyle**: [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty) \| [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty)[]

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextDecorationStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextdecorationstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24980

___

### WebkitTextEmphasis

• `Optional` **WebkitTextEmphasis**: `string` \| `string`[]

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitTextEmphasis](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittextemphasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25279

___

### WebkitTextEmphasisColor

• `Optional` **WebkitTextEmphasisColor**: `string` \| `string`[]

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextEmphasisColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextemphasiscolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24988

___

### WebkitTextEmphasisPosition

• `Optional` **WebkitTextEmphasisPosition**: `string` \| `string`[]

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextEmphasisPosition](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextemphasisposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24996

___

### WebkitTextEmphasisStyle

• `Optional` **WebkitTextEmphasisStyle**: `string` \| `string`[]

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextEmphasisStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextemphasisstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25004

___

### WebkitTextFillColor

• `Optional` **WebkitTextFillColor**: `string` \| `string`[]

The **`-webkit-text-fill-color`** CSS property specifies the fill color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextFillColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextfillcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25012

___

### WebkitTextOrientation

• `Optional` **WebkitTextOrientation**: [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty) \| [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty)[]

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextOrientation](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextorientation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25020

___

### WebkitTextSizeAdjust

• `Optional` **WebkitTextSizeAdjust**: `string` \| `string`[]

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextSizeAdjust](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25028

___

### WebkitTextStroke

• `Optional` **WebkitTextStroke**: [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\> \| [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\>[]

The **`-webkit-text-stroke`** CSS property specifies the width and color of strokes for text characters. This is a shorthand property for the longhand properties `-webkit-text-stroke-width` and `-webkit-text-stroke-color`.

**Syntax**: `<length> || <color>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitTextStroke](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittextstroke)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25285

___

### WebkitTextStrokeColor

• `Optional` **WebkitTextStrokeColor**: `string` \| `string`[]

The **`-webkit-text-stroke-color`** CSS property specifies the stroke color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextStrokeColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextstrokecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25036

___

### WebkitTextStrokeWidth

• `Optional` **WebkitTextStrokeWidth**: [`WebkitTextStrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidthproperty)<`TLength`\> \| [`WebkitTextStrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidthproperty)<`TLength`\>[]

The **`-webkit-text-stroke-width`** CSS property specifies the width of the stroke for text.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextStrokeWidth](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextstrokewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25044

___

### WebkitTextUnderlinePosition

• `Optional` **WebkitTextUnderlinePosition**: `string` \| `string`[]

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTextUnderlinePosition](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittextunderlineposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25052

___

### WebkitTouchCallout

• `Optional` **WebkitTouchCallout**: [`WebkitTouchCalloutProperty`](../modules/akashaproject_design_system._internal_.md#webkittouchcalloutproperty) \| [`WebkitTouchCalloutProperty`](../modules/akashaproject_design_system._internal_.md#webkittouchcalloutproperty)[]

The `-webkit-touch-callout` CSS property controls the display of the default callout shown when you touch and hold a touch target.

**Syntax**: `default | none`

**Initial value**: `default`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTouchCallout](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittouchcallout)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25060

___

### WebkitTransform

• `Optional` **WebkitTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransform](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25068

___

### WebkitTransformOrigin

• `Optional` **WebkitTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransformOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25076

___

### WebkitTransformStyle

• `Optional` **WebkitTransformStyle**: [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty) \| [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty)[]

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransformStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransformstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25084

___

### WebkitTransition

• `Optional` **WebkitTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[WebkitTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#webkittransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25291

___

### WebkitTransitionDelay

• `Optional` **WebkitTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransitionDelay](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25092

___

### WebkitTransitionDuration

• `Optional` **WebkitTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransitionDuration](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25100

___

### WebkitTransitionProperty

• `Optional` **WebkitTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransitionProperty](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25108

___

### WebkitTransitionTimingFunction

• `Optional` **WebkitTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitTransitionTimingFunction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkittransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25116

___

### WebkitUserModify

• `Optional` **WebkitUserModify**: [`WebkitUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#webkitusermodifyproperty) \| [`WebkitUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#webkitusermodifyproperty)[]

**Syntax**: `read-only | read-write | read-write-plaintext-only`

**Initial value**: `read-only`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitUserModify](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitusermodify)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25122

___

### WebkitUserSelect

• `Optional` **WebkitUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitUserSelect](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkituserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25130

___

### WebkitWritingMode

• `Optional` **WebkitWritingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress.

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[WebkitWritingMode](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#webkitwritingmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25138

___

### msAccelerator

• `Optional` **msAccelerator**: [`MsAcceleratorProperty`](../modules/akashaproject_design_system._internal_.md#msacceleratorproperty) \| [`MsAcceleratorProperty`](../modules/akashaproject_design_system._internal_.md#msacceleratorproperty)[]

The **`-ms-accelerator`** CSS property is a Microsoft extension that sets or retrieves a string indicating whether the object represents a keyboard shortcut.

**Syntax**: `false | true`

**Initial value**: `false`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msAccelerator](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msaccelerator)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23794

___

### msAlignSelf

• `Optional` **msAlignSelf**: `string` \| `string`[]

The **`align-self`** CSS property aligns flex items of the current flex line overriding the `align-items` value. If any of the item's cross-axis margin is set to `auto`, then `align-self` is ignored. In Grid layout `align-self` aligns the item inside the grid area.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msAlignSelf](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msalignself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23802

___

### msBlockProgression

• `Optional` **msBlockProgression**: [`MsBlockProgressionProperty`](../modules/akashaproject_design_system._internal_.md#msblockprogressionproperty) \| [`MsBlockProgressionProperty`](../modules/akashaproject_design_system._internal_.md#msblockprogressionproperty)[]

The **`-ms-block-progression`** CSS property is a Microsoft extension that specifies the block progression and layout orientation.

**Syntax**: `tb | rl | bt | lr`

**Initial value**: `tb`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msBlockProgression](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msblockprogression)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23810

___

### msContentZoomChaining

• `Optional` **msContentZoomChaining**: [`MsContentZoomChainingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchainingproperty) \| [`MsContentZoomChainingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchainingproperty)[]

The **`-ms-content-zoom-chaining`** CSS property is a Microsoft extension specifying the zoom behavior that occurs when a user hits the zoom limit during page manipulation.

**Syntax**: `none | chained`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZoomChaining](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzoomchaining)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23818

___

### msContentZoomLimit

• `Optional` **msContentZoomLimit**: `string` \| `string`[]

The **`-ms-content-zoom-limit`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-limit-min` and `-ms-content-zoom-limit-max` properties.

**Syntax**: `<'-ms-content-zoom-limit-min'> <'-ms-content-zoom-limit-max'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msContentZoomLimit](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mscontentzoomlimit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25177

___

### msContentZoomLimitMax

• `Optional` **msContentZoomLimitMax**: `string` \| `string`[]

The **`-ms-content-zoom-limit-max`** CSS property is a Microsoft extension that specifies the selected elements' maximum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `400%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZoomLimitMax](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzoomlimitmax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23826

___

### msContentZoomLimitMin

• `Optional` **msContentZoomLimitMin**: `string` \| `string`[]

The **`-ms-content-zoom-limit-min`** CSS property is a Microsoft extension that specifies the minimum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `100%`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZoomLimitMin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzoomlimitmin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23834

___

### msContentZoomSnap

• `Optional` **msContentZoomSnap**: `string` \| `string`[]

The **`-ms-content-zoom-snap`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-snap-type` and `-ms-content-zoom-snap-points` properties.

**Syntax**: `<'-ms-content-zoom-snap-type'> || <'-ms-content-zoom-snap-points'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msContentZoomSnap](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mscontentzoomsnap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25183

___

### msContentZoomSnapPoints

• `Optional` **msContentZoomSnapPoints**: `string` \| `string`[]

The **`-ms-content-zoom-snap-points`** CSS property is a Microsoft extension that specifies where zoom snap-points are located.

**Syntax**: `snapInterval( <percentage>, <percentage> ) | snapList( <percentage># )`

**Initial value**: `snapInterval(0%, 100%)`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZoomSnapPoints](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzoomsnappoints)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23842

___

### msContentZoomSnapType

• `Optional` **msContentZoomSnapType**: [`MsContentZoomSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptypeproperty) \| [`MsContentZoomSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptypeproperty)[]

The **`-ms-content-zoom-snap-type`** CSS property is a Microsoft extension that specifies how zooming is affected by defined snap-points.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZoomSnapType](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzoomsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23850

___

### msContentZooming

• `Optional` **msContentZooming**: [`MsContentZoomingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomingproperty) \| [`MsContentZoomingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomingproperty)[]

The **`-ms-content-zooming`** CSS property is a Microsoft extension that specifies whether zooming is enabled.

**Syntax**: `none | zoom`

**Initial value**: zoom for the top level element, none for all other elements

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msContentZooming](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mscontentzooming)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23858

___

### msFilter

• `Optional` **msFilter**: `string` \| `string`[]

The `-ms-filter` CSS property is a Microsoft extension that sets or retrieves the filter or collection of filters applied to an object.

**Syntax**: `<string>`

**Initial value**: "" (the empty string)

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msFilter](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23866

___

### msFlex

• `Optional` **msFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msFlex](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25189

___

### msFlexDirection

• `Optional` **msFlexDirection**: [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty) \| [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty)[]

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msFlexDirection](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msflexdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23874

___

### msFlexPositive

• `Optional` **msFlexPositive**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-grow`** CSS property sets how much of the available space in the flex container should be assigned to that item (the flex grow factor). If all sibling items have the same flex grow factor, then all items will receive the same share of available space, otherwise it is distributed according to the ratio defined by the different flex grow factors.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msFlexPositive](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msflexpositive)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23882

___

### msFlowFrom

• `Optional` **msFlowFrom**: `string` \| `string`[]

The **`-ms-flow-from`** CSS property is a Microsoft extension that gets or sets a value identifying a region container in the document that accepts the content flow from the data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msFlowFrom](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msflowfrom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23890

___

### msFlowInto

• `Optional` **msFlowInto**: `string` \| `string`[]

The **`-ms-flow-into`** CSS property is a Microsoft extension that gets or sets a value identifying an iframe container in the document that serves as the region's data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msFlowInto](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msflowinto)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23898

___

### msGridColumns

• `Optional` **msGridColumns**: [`MsGridColumnsProperty`](../modules/akashaproject_design_system._internal_.md#msgridcolumnsproperty)<`TLength`\> \| [`MsGridColumnsProperty`](../modules/akashaproject_design_system._internal_.md#msgridcolumnsproperty)<`TLength`\>[]

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msGridColumns](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msgridcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23906

___

### msGridRows

• `Optional` **msGridRows**: [`MsGridRowsProperty`](../modules/akashaproject_design_system._internal_.md#msgridrowsproperty)<`TLength`\> \| [`MsGridRowsProperty`](../modules/akashaproject_design_system._internal_.md#msgridrowsproperty)<`TLength`\>[]

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msGridRows](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msgridrows)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23914

___

### msHighContrastAdjust

• `Optional` **msHighContrastAdjust**: [`MsHighContrastAdjustProperty`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjustproperty) \| [`MsHighContrastAdjustProperty`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjustproperty)[]

The **`-ms-high-contrast-adjust`** CSS property is a Microsoft extension that gets or sets a value indicating whether to override any CSS properties that would have been set in high contrast mode.

**Syntax**: `auto | none`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msHighContrastAdjust](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mshighcontrastadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23922

___

### msHyphenateLimitChars

• `Optional` **msHyphenateLimitChars**: [`MsHyphenateLimitCharsProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitcharsproperty) \| [`MsHyphenateLimitCharsProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitcharsproperty)[]

The **`-ms-hyphenate-limit-chars`** CSS property is a Microsoft extension that specifies one to three values indicating the minimum number of characters in a hyphenated word. If the word does not meet the required minimum number of characters in the word, before the hyphen, or after the hyphen, then the word is not hyphenated.

**Syntax**: `auto | <integer>{1,3}`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msHyphenateLimitChars](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mshyphenatelimitchars)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23930

___

### msHyphenateLimitLines

• `Optional` **msHyphenateLimitLines**: [`MsHyphenateLimitLinesProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlinesproperty) \| [`MsHyphenateLimitLinesProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlinesproperty)[]

The **`-ms-hyphenate-limit-lines`** CSS property is a Microsoft extension specifying the maximum number of consecutive lines in an element that may be ended with a hyphenated word.

**Syntax**: `no-limit | <integer>`

**Initial value**: `no-limit`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msHyphenateLimitLines](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mshyphenatelimitlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23938

___

### msHyphenateLimitZone

• `Optional` **msHyphenateLimitZone**: [`MsHyphenateLimitZoneProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzoneproperty)<`TLength`\> \| [`MsHyphenateLimitZoneProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzoneproperty)<`TLength`\>[]

The `**-ms-hyphenate-limit-zone**` CSS property is a Microsoft extension specifying the width of the hyphenation zone.

**Syntax**: `<percentage> | <length>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msHyphenateLimitZone](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mshyphenatelimitzone)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23946

___

### msHyphens

• `Optional` **msHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msHyphens](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mshyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23954

___

### msImeAlign

• `Optional` **msImeAlign**: [`MsImeAlignProperty`](../modules/akashaproject_design_system._internal_.md#msimealignproperty) \| [`MsImeAlignProperty`](../modules/akashaproject_design_system._internal_.md#msimealignproperty)[]

The **`-ms-ime-align`** CSS property is a Microsoft extension aligning the Input Method Editor (IME) candidate window box relative to the element on which the IME composition is active. The extension is implemented in Microsoft Edge and Internet Explorer 11.

**Syntax**: `auto | after`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msImeAlign](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msimealign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23962

___

### msJustifySelf

• `Optional` **msJustifySelf**: `string` \| `string`[]

The CSS **`justify-self`** property set the way a box is justified inside its alignment container along the appropriate axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ]`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msJustifySelf](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msjustifyself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23970

___

### msLineBreak

• `Optional` **msLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msLineBreak](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mslinebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23978

___

### msOrder

• `Optional` **msOrder**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msOrder](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msorder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23986

___

### msOverflowStyle

• `Optional` **msOverflowStyle**: [`MsOverflowStyleProperty`](../modules/akashaproject_design_system._internal_.md#msoverflowstyleproperty) \| [`MsOverflowStyleProperty`](../modules/akashaproject_design_system._internal_.md#msoverflowstyleproperty)[]

The **`-ms-overflow-style`** CSS property is a Microsoft extension controlling the behavior of scrollbars when the content of an element overflows.

**Syntax**: `auto | none | scrollbar | -ms-autohiding-scrollbar`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msOverflowStyle](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msoverflowstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23994

___

### msOverflowX

• `Optional` **msOverflowX**: [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty) \| [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty)[]

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msOverflowX](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msoverflowx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24002

___

### msOverflowY

• `Optional` **msOverflowY**: [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty) \| [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty)[]

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msOverflowY](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msoverflowy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24010

___

### msScrollChaining

• `Optional` **msScrollChaining**: [`MsScrollChainingProperty`](../modules/akashaproject_design_system._internal_.md#msscrollchainingproperty) \| [`MsScrollChainingProperty`](../modules/akashaproject_design_system._internal_.md#msscrollchainingproperty)[]

The `**-ms-scroll-chaining**` CSS property is a Microsoft extension that specifies the scrolling behavior that occurs when a user hits the scroll limit during a manipulation.

**Syntax**: `chained | none`

**Initial value**: `chained`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollChaining](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollchaining)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24018

___

### msScrollLimit

• `Optional` **msScrollLimit**: `string` \| `string`[]

The **\-ms-scroll-limit** CSS property is a Microsoft extension that specifies values for the `-ms-scroll-limit-x-min`, `-ms-scroll-limit-y-min`, `-ms-scroll-limit-x-max`, and `-ms-scroll-limit-y-max` properties.

**Syntax**: `<'-ms-scroll-limit-x-min'> <'-ms-scroll-limit-y-min'> <'-ms-scroll-limit-x-max'> <'-ms-scroll-limit-y-max'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msScrollLimit](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrolllimit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25195

___

### msScrollLimitXMax

• `Optional` **msScrollLimitXMax**: [`MsScrollLimitXMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmaxproperty)<`TLength`\> \| [`MsScrollLimitXMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmaxproperty)<`TLength`\>[]

The `**-ms-scroll-limit-x-max**` CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollLeft` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollLimitXMax](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrolllimitxmax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24026

___

### msScrollLimitXMin

• `Optional` **msScrollLimitXMin**: [`MsScrollLimitXMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxminproperty)<`TLength`\> \| [`MsScrollLimitXMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxminproperty)<`TLength`\>[]

The **`-ms-scroll-limit-x-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollLeft` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollLimitXMin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrolllimitxmin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24034

___

### msScrollLimitYMax

• `Optional` **msScrollLimitYMax**: [`MsScrollLimitYMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymaxproperty)<`TLength`\> \| [`MsScrollLimitYMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymaxproperty)<`TLength`\>[]

The **`-ms-scroll-limit-y-max`** CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollTop` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollLimitYMax](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrolllimitymax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24042

___

### msScrollLimitYMin

• `Optional` **msScrollLimitYMin**: [`MsScrollLimitYMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimityminproperty)<`TLength`\> \| [`MsScrollLimitYMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimityminproperty)<`TLength`\>[]

The **`-ms-scroll-limit-y-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollTop` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollLimitYMin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrolllimitymin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24050

___

### msScrollRails

• `Optional` **msScrollRails**: [`MsScrollRailsProperty`](../modules/akashaproject_design_system._internal_.md#msscrollrailsproperty) \| [`MsScrollRailsProperty`](../modules/akashaproject_design_system._internal_.md#msscrollrailsproperty)[]

The **`-ms-scroll-rails`** CSS property is a Microsoft extension that specifies whether scrolling locks to the primary axis of motion.

**Syntax**: `none | railed`

**Initial value**: `railed`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollRails](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollrails)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24058

___

### msScrollSnapPointsX

• `Optional` **msScrollSnapPointsX**: `string` \| `string`[]

The **`-ms-scroll-snap-points-x`** CSS property is a Microsoft extension that specifies where snap-points will be located along the x-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollSnapPointsX](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollsnappointsx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24066

___

### msScrollSnapPointsY

• `Optional` **msScrollSnapPointsY**: `string` \| `string`[]

The **`-ms-scroll-snap-points-y`** CSS property is a Microsoft extension that specifies where snap-points will be located along the y-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollSnapPointsY](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollsnappointsy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24074

___

### msScrollSnapType

• `Optional` **msScrollSnapType**: [`MsScrollSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptypeproperty) \| [`MsScrollSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptypeproperty)[]

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollSnapType](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24082

___

### msScrollSnapX

• `Optional` **msScrollSnapX**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-x` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-x'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msScrollSnapX](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrollsnapx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25201

___

### msScrollSnapY

• `Optional` **msScrollSnapY**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-y` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-y'>`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msScrollSnapY](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#msscrollsnapy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25207

___

### msScrollTranslation

• `Optional` **msScrollTranslation**: [`MsScrollTranslationProperty`](../modules/akashaproject_design_system._internal_.md#msscrolltranslationproperty) \| [`MsScrollTranslationProperty`](../modules/akashaproject_design_system._internal_.md#msscrolltranslationproperty)[]

The **`-ms-scroll-translation`** CSS property is a Microsoft extension that specifies whether vertical-to-horizontal scroll wheel translation occurs on the specified element.

**Syntax**: `none | vertical-to-horizontal`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollTranslation](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrolltranslation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24090

___

### msScrollbar3dlightColor

• `Optional` **msScrollbar3dlightColor**: `string` \| `string`[]

The **`-ms-scrollbar-3dlight-color`** CSS property is a Microsoft extension specifying the color of the top and left edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbar3dlightColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbar3dlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24098

___

### msScrollbarArrowColor

• `Optional` **msScrollbarArrowColor**: `string` \| `string`[]

The **`-ms-scrollbar-arrow-color`** CSS property is a Microsoft extension that specifies the color of the arrow elements of a scroll arrow.

**Syntax**: `<color>`

**Initial value**: `ButtonText`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarArrowColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbararrowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24106

___

### msScrollbarBaseColor

• `Optional` **msScrollbarBaseColor**: `string` \| `string`[]

The `**-ms-scrollbar-base-color**` CSS property is a Microsoft extension that specifies the base color of the main elements of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarBaseColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbarbasecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24114

___

### msScrollbarDarkshadowColor

• `Optional` **msScrollbarDarkshadowColor**: `string` \| `string`[]

The **`-ms-scrollbar-darkshadow-color`** CSS property is a Microsoft extension that specifies the color of a scroll bar's gutter.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarDarkshadowColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbardarkshadowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24122

___

### msScrollbarFaceColor

• `Optional` **msScrollbarFaceColor**: `string` \| `string`[]

The `**-ms-scrollbar-face-color**` CSS property is a Microsoft extension that specifies the color of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDFace`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarFaceColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbarfacecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24130

___

### msScrollbarHighlightColor

• `Optional` **msScrollbarHighlightColor**: `string` \| `string`[]

The `**-ms-scrollbar-highlight-color**` CSS property is a Microsoft extension that specifies the color of the slider tray, the top and left edges of the scroll box, and the scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDHighlight`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarHighlightColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbarhighlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24138

___

### msScrollbarShadowColor

• `Optional` **msScrollbarShadowColor**: `string` \| `string`[]

The **`-ms-scrollbar-shadow-color`** CSS property is a Microsoft extension that specifies the color of the bottom and right edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msScrollbarShadowColor](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msscrollbarshadowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24146

___

### msTextAutospace

• `Optional` **msTextAutospace**: [`MsTextAutospaceProperty`](../modules/akashaproject_design_system._internal_.md#mstextautospaceproperty) \| [`MsTextAutospaceProperty`](../modules/akashaproject_design_system._internal_.md#mstextautospaceproperty)[]

The **`-ms-text-autospace`** CSS property is a Microsoft extension that specifies the autospacing and narrow space width adjustment of text.

**Syntax**: `none | ideograph-alpha | ideograph-numeric | ideograph-parenthesis | ideograph-space`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTextAutospace](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstextautospace)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24154

___

### msTextCombineHorizontal

• `Optional` **msTextCombineHorizontal**: `string` \| `string`[]

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTextCombineHorizontal](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstextcombinehorizontal)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24162

___

### msTextOverflow

• `Optional` **msTextOverflow**: `string` \| `string`[]

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTextOverflow](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstextoverflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24170

___

### msTouchAction

• `Optional` **msTouchAction**: `string` \| `string`[]

The **`touch-action`** CSS property sets how a region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTouchAction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstouchaction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24178

___

### msTouchSelect

• `Optional` **msTouchSelect**: [`MsTouchSelectProperty`](../modules/akashaproject_design_system._internal_.md#mstouchselectproperty) \| [`MsTouchSelectProperty`](../modules/akashaproject_design_system._internal_.md#mstouchselectproperty)[]

The **`-ms-touch-select`** CSS property is a Microsoft extension that toggles the gripper visual elements that enable touch text selection.

**Syntax**: `grippers | none`

**Initial value**: `grippers`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTouchSelect](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstouchselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24186

___

### msTransform

• `Optional` **msTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransform](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24194

___

### msTransformOrigin

• `Optional` **msTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransformOrigin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24202

___

### msTransition

• `Optional` **msTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorShorthandPropertiesFallback](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md).[msTransition](akashaproject_design_system._internal_.VendorShorthandPropertiesFallback.md#mstransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25213

___

### msTransitionDelay

• `Optional` **msTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransitionDelay](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24210

___

### msTransitionDuration

• `Optional` **msTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransitionDuration](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24218

___

### msTransitionProperty

• `Optional` **msTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransitionProperty](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24226

___

### msTransitionTimingFunction

• `Optional` **msTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msTransitionTimingFunction](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mstransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24234

___

### msUserSelect

• `Optional` **msUserSelect**: [`MsUserSelectProperty`](../modules/akashaproject_design_system._internal_.md#msuserselectproperty) \| [`MsUserSelectProperty`](../modules/akashaproject_design_system._internal_.md#msuserselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `none | element | text`

**Initial value**: `text`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msUserSelect](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#msuserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24242

___

### msWordBreak

• `Optional` **msWordBreak**: [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty) \| [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty)[]

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msWordBreak](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mswordbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24250

___

### msWrapFlow

• `Optional` **msWrapFlow**: [`MsWrapFlowProperty`](../modules/akashaproject_design_system._internal_.md#mswrapflowproperty) \| [`MsWrapFlowProperty`](../modules/akashaproject_design_system._internal_.md#mswrapflowproperty)[]

The **`-ms-wrap-flow`** CSS property is a Microsoft extension that specifies how exclusions impact inline content within block-level elements.

**Syntax**: `auto | both | start | end | maximum | clear`

**Initial value**: `auto`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msWrapFlow](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mswrapflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24258

___

### msWrapMargin

• `Optional` **msWrapMargin**: [`MsWrapMarginProperty`](../modules/akashaproject_design_system._internal_.md#mswrapmarginproperty)<`TLength`\> \| [`MsWrapMarginProperty`](../modules/akashaproject_design_system._internal_.md#mswrapmarginproperty)<`TLength`\>[]

The **`-ms-wrap-margin`** CSS property is a Microsoft extension that specifies a margin that offsets the inner wrap shape from other shapes.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msWrapMargin](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mswrapmargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24266

___

### msWrapThrough

• `Optional` **msWrapThrough**: [`MsWrapThroughProperty`](../modules/akashaproject_design_system._internal_.md#mswrapthroughproperty) \| [`MsWrapThroughProperty`](../modules/akashaproject_design_system._internal_.md#mswrapthroughproperty)[]

The **`-ms-wrap-through`** CSS property is a Microsoft extension that specifies how content should wrap around an exclusion element.

**Syntax**: `wrap | none`

**Initial value**: `wrap`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msWrapThrough](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mswrapthrough)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24274

___

### msWritingMode

• `Optional` **msWritingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress.

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorLonghandPropertiesFallback](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md).[msWritingMode](akashaproject_design_system._internal_.VendorLonghandPropertiesFallback.md#mswritingmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24282
