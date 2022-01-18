[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / Properties

# Interface: Properties<TLength, TTime\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).Properties

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` & {} \| ``0`` |
| `TTime` | `string` & {} |

## Hierarchy

- [`StandardProperties`](akashaproject_design_system._internal_.StandardProperties.md)<`TLength`, `TTime`\>

- [`VendorProperties`](akashaproject_design_system._internal_.VendorProperties.md)<`TLength`, `TTime`\>

- [`ObsoleteProperties`](akashaproject_design_system._internal_.ObsoleteProperties.md)<`TLength`, `TTime`\>

- [`SvgProperties`](akashaproject_design_system._internal_.SvgProperties.md)<`TLength`, `TTime`\>

  ↳ **`Properties`**

  ↳↳ [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

## Table of contents

### Properties

- [KhtmlBoxAlign](akashaproject_design_system._internal_.Properties.md#khtmlboxalign)
- [KhtmlBoxDirection](akashaproject_design_system._internal_.Properties.md#khtmlboxdirection)
- [KhtmlBoxFlex](akashaproject_design_system._internal_.Properties.md#khtmlboxflex)
- [KhtmlBoxFlexGroup](akashaproject_design_system._internal_.Properties.md#khtmlboxflexgroup)
- [KhtmlBoxLines](akashaproject_design_system._internal_.Properties.md#khtmlboxlines)
- [KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#khtmlboxordinalgroup)
- [KhtmlBoxOrient](akashaproject_design_system._internal_.Properties.md#khtmlboxorient)
- [KhtmlBoxPack](akashaproject_design_system._internal_.Properties.md#khtmlboxpack)
- [KhtmlLineBreak](akashaproject_design_system._internal_.Properties.md#khtmllinebreak)
- [KhtmlOpacity](akashaproject_design_system._internal_.Properties.md#khtmlopacity)
- [KhtmlUserSelect](akashaproject_design_system._internal_.Properties.md#khtmluserselect)
- [MozAnimation](akashaproject_design_system._internal_.Properties.md#mozanimation)
- [MozAnimationDelay](akashaproject_design_system._internal_.Properties.md#mozanimationdelay)
- [MozAnimationDirection](akashaproject_design_system._internal_.Properties.md#mozanimationdirection)
- [MozAnimationDuration](akashaproject_design_system._internal_.Properties.md#mozanimationduration)
- [MozAnimationFillMode](akashaproject_design_system._internal_.Properties.md#mozanimationfillmode)
- [MozAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#mozanimationiterationcount)
- [MozAnimationName](akashaproject_design_system._internal_.Properties.md#mozanimationname)
- [MozAnimationPlayState](akashaproject_design_system._internal_.Properties.md#mozanimationplaystate)
- [MozAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#mozanimationtimingfunction)
- [MozAppearance](akashaproject_design_system._internal_.Properties.md#mozappearance)
- [MozBackfaceVisibility](akashaproject_design_system._internal_.Properties.md#mozbackfacevisibility)
- [MozBackgroundClip](akashaproject_design_system._internal_.Properties.md#mozbackgroundclip)
- [MozBackgroundInlinePolicy](akashaproject_design_system._internal_.Properties.md#mozbackgroundinlinepolicy)
- [MozBackgroundOrigin](akashaproject_design_system._internal_.Properties.md#mozbackgroundorigin)
- [MozBackgroundSize](akashaproject_design_system._internal_.Properties.md#mozbackgroundsize)
- [MozBinding](akashaproject_design_system._internal_.Properties.md#mozbinding)
- [MozBorderBottomColors](akashaproject_design_system._internal_.Properties.md#mozborderbottomcolors)
- [MozBorderEndColor](akashaproject_design_system._internal_.Properties.md#mozborderendcolor)
- [MozBorderEndStyle](akashaproject_design_system._internal_.Properties.md#mozborderendstyle)
- [MozBorderEndWidth](akashaproject_design_system._internal_.Properties.md#mozborderendwidth)
- [MozBorderImage](akashaproject_design_system._internal_.Properties.md#mozborderimage)
- [MozBorderLeftColors](akashaproject_design_system._internal_.Properties.md#mozborderleftcolors)
- [MozBorderRadius](akashaproject_design_system._internal_.Properties.md#mozborderradius)
- [MozBorderRadiusBottomleft](akashaproject_design_system._internal_.Properties.md#mozborderradiusbottomleft)
- [MozBorderRadiusBottomright](akashaproject_design_system._internal_.Properties.md#mozborderradiusbottomright)
- [MozBorderRadiusTopleft](akashaproject_design_system._internal_.Properties.md#mozborderradiustopleft)
- [MozBorderRadiusTopright](akashaproject_design_system._internal_.Properties.md#mozborderradiustopright)
- [MozBorderRightColors](akashaproject_design_system._internal_.Properties.md#mozborderrightcolors)
- [MozBorderStartColor](akashaproject_design_system._internal_.Properties.md#mozborderstartcolor)
- [MozBorderStartStyle](akashaproject_design_system._internal_.Properties.md#mozborderstartstyle)
- [MozBorderTopColors](akashaproject_design_system._internal_.Properties.md#mozbordertopcolors)
- [MozBoxAlign](akashaproject_design_system._internal_.Properties.md#mozboxalign)
- [MozBoxDirection](akashaproject_design_system._internal_.Properties.md#mozboxdirection)
- [MozBoxFlex](akashaproject_design_system._internal_.Properties.md#mozboxflex)
- [MozBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#mozboxordinalgroup)
- [MozBoxOrient](akashaproject_design_system._internal_.Properties.md#mozboxorient)
- [MozBoxPack](akashaproject_design_system._internal_.Properties.md#mozboxpack)
- [MozBoxShadow](akashaproject_design_system._internal_.Properties.md#mozboxshadow)
- [MozBoxSizing](akashaproject_design_system._internal_.Properties.md#mozboxsizing)
- [MozColumnCount](akashaproject_design_system._internal_.Properties.md#mozcolumncount)
- [MozColumnFill](akashaproject_design_system._internal_.Properties.md#mozcolumnfill)
- [MozColumnGap](akashaproject_design_system._internal_.Properties.md#mozcolumngap)
- [MozColumnRule](akashaproject_design_system._internal_.Properties.md#mozcolumnrule)
- [MozColumnRuleColor](akashaproject_design_system._internal_.Properties.md#mozcolumnrulecolor)
- [MozColumnRuleStyle](akashaproject_design_system._internal_.Properties.md#mozcolumnrulestyle)
- [MozColumnRuleWidth](akashaproject_design_system._internal_.Properties.md#mozcolumnrulewidth)
- [MozColumnWidth](akashaproject_design_system._internal_.Properties.md#mozcolumnwidth)
- [MozColumns](akashaproject_design_system._internal_.Properties.md#mozcolumns)
- [MozContextProperties](akashaproject_design_system._internal_.Properties.md#mozcontextproperties)
- [MozFloatEdge](akashaproject_design_system._internal_.Properties.md#mozfloatedge)
- [MozFontFeatureSettings](akashaproject_design_system._internal_.Properties.md#mozfontfeaturesettings)
- [MozFontLanguageOverride](akashaproject_design_system._internal_.Properties.md#mozfontlanguageoverride)
- [MozForceBrokenImageIcon](akashaproject_design_system._internal_.Properties.md#mozforcebrokenimageicon)
- [MozHyphens](akashaproject_design_system._internal_.Properties.md#mozhyphens)
- [MozImageRegion](akashaproject_design_system._internal_.Properties.md#mozimageregion)
- [MozMarginEnd](akashaproject_design_system._internal_.Properties.md#mozmarginend)
- [MozMarginStart](akashaproject_design_system._internal_.Properties.md#mozmarginstart)
- [MozOpacity](akashaproject_design_system._internal_.Properties.md#mozopacity)
- [MozOrient](akashaproject_design_system._internal_.Properties.md#mozorient)
- [MozOsxFontSmoothing](akashaproject_design_system._internal_.Properties.md#mozosxfontsmoothing)
- [MozOutline](akashaproject_design_system._internal_.Properties.md#mozoutline)
- [MozOutlineColor](akashaproject_design_system._internal_.Properties.md#mozoutlinecolor)
- [MozOutlineRadius](akashaproject_design_system._internal_.Properties.md#mozoutlineradius)
- [MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.Properties.md#mozoutlineradiusbottomleft)
- [MozOutlineRadiusBottomright](akashaproject_design_system._internal_.Properties.md#mozoutlineradiusbottomright)
- [MozOutlineRadiusTopleft](akashaproject_design_system._internal_.Properties.md#mozoutlineradiustopleft)
- [MozOutlineRadiusTopright](akashaproject_design_system._internal_.Properties.md#mozoutlineradiustopright)
- [MozOutlineStyle](akashaproject_design_system._internal_.Properties.md#mozoutlinestyle)
- [MozOutlineWidth](akashaproject_design_system._internal_.Properties.md#mozoutlinewidth)
- [MozPaddingEnd](akashaproject_design_system._internal_.Properties.md#mozpaddingend)
- [MozPaddingStart](akashaproject_design_system._internal_.Properties.md#mozpaddingstart)
- [MozPerspective](akashaproject_design_system._internal_.Properties.md#mozperspective)
- [MozPerspectiveOrigin](akashaproject_design_system._internal_.Properties.md#mozperspectiveorigin)
- [MozStackSizing](akashaproject_design_system._internal_.Properties.md#mozstacksizing)
- [MozTabSize](akashaproject_design_system._internal_.Properties.md#moztabsize)
- [MozTextAlignLast](akashaproject_design_system._internal_.Properties.md#moztextalignlast)
- [MozTextBlink](akashaproject_design_system._internal_.Properties.md#moztextblink)
- [MozTextDecorationColor](akashaproject_design_system._internal_.Properties.md#moztextdecorationcolor)
- [MozTextDecorationLine](akashaproject_design_system._internal_.Properties.md#moztextdecorationline)
- [MozTextDecorationStyle](akashaproject_design_system._internal_.Properties.md#moztextdecorationstyle)
- [MozTextSizeAdjust](akashaproject_design_system._internal_.Properties.md#moztextsizeadjust)
- [MozTransformOrigin](akashaproject_design_system._internal_.Properties.md#moztransformorigin)
- [MozTransformStyle](akashaproject_design_system._internal_.Properties.md#moztransformstyle)
- [MozTransition](akashaproject_design_system._internal_.Properties.md#moztransition)
- [MozTransitionDelay](akashaproject_design_system._internal_.Properties.md#moztransitiondelay)
- [MozTransitionDuration](akashaproject_design_system._internal_.Properties.md#moztransitionduration)
- [MozTransitionProperty](akashaproject_design_system._internal_.Properties.md#moztransitionproperty)
- [MozTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#moztransitiontimingfunction)
- [MozUserFocus](akashaproject_design_system._internal_.Properties.md#mozuserfocus)
- [MozUserInput](akashaproject_design_system._internal_.Properties.md#mozuserinput)
- [MozUserModify](akashaproject_design_system._internal_.Properties.md#mozusermodify)
- [MozUserSelect](akashaproject_design_system._internal_.Properties.md#mozuserselect)
- [MozWindowDragging](akashaproject_design_system._internal_.Properties.md#mozwindowdragging)
- [MozWindowShadow](akashaproject_design_system._internal_.Properties.md#mozwindowshadow)
- [OAnimation](akashaproject_design_system._internal_.Properties.md#oanimation)
- [OAnimationDelay](akashaproject_design_system._internal_.Properties.md#oanimationdelay)
- [OAnimationDirection](akashaproject_design_system._internal_.Properties.md#oanimationdirection)
- [OAnimationDuration](akashaproject_design_system._internal_.Properties.md#oanimationduration)
- [OAnimationFillMode](akashaproject_design_system._internal_.Properties.md#oanimationfillmode)
- [OAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#oanimationiterationcount)
- [OAnimationName](akashaproject_design_system._internal_.Properties.md#oanimationname)
- [OAnimationPlayState](akashaproject_design_system._internal_.Properties.md#oanimationplaystate)
- [OAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#oanimationtimingfunction)
- [OBackgroundSize](akashaproject_design_system._internal_.Properties.md#obackgroundsize)
- [OBorderImage](akashaproject_design_system._internal_.Properties.md#oborderimage)
- [OObjectFit](akashaproject_design_system._internal_.Properties.md#oobjectfit)
- [OObjectPosition](akashaproject_design_system._internal_.Properties.md#oobjectposition)
- [OTabSize](akashaproject_design_system._internal_.Properties.md#otabsize)
- [OTextOverflow](akashaproject_design_system._internal_.Properties.md#otextoverflow)
- [OTransform](akashaproject_design_system._internal_.Properties.md#otransform)
- [OTransformOrigin](akashaproject_design_system._internal_.Properties.md#otransformorigin)
- [OTransition](akashaproject_design_system._internal_.Properties.md#otransition)
- [OTransitionDelay](akashaproject_design_system._internal_.Properties.md#otransitiondelay)
- [OTransitionDuration](akashaproject_design_system._internal_.Properties.md#otransitionduration)
- [OTransitionProperty](akashaproject_design_system._internal_.Properties.md#otransitionproperty)
- [OTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#otransitiontimingfunction)
- [WebkitAlignContent](akashaproject_design_system._internal_.Properties.md#webkitaligncontent)
- [WebkitAlignItems](akashaproject_design_system._internal_.Properties.md#webkitalignitems)
- [WebkitAlignSelf](akashaproject_design_system._internal_.Properties.md#webkitalignself)
- [WebkitAnimation](akashaproject_design_system._internal_.Properties.md#webkitanimation)
- [WebkitAnimationDelay](akashaproject_design_system._internal_.Properties.md#webkitanimationdelay)
- [WebkitAnimationDirection](akashaproject_design_system._internal_.Properties.md#webkitanimationdirection)
- [WebkitAnimationDuration](akashaproject_design_system._internal_.Properties.md#webkitanimationduration)
- [WebkitAnimationFillMode](akashaproject_design_system._internal_.Properties.md#webkitanimationfillmode)
- [WebkitAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#webkitanimationiterationcount)
- [WebkitAnimationName](akashaproject_design_system._internal_.Properties.md#webkitanimationname)
- [WebkitAnimationPlayState](akashaproject_design_system._internal_.Properties.md#webkitanimationplaystate)
- [WebkitAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#webkitanimationtimingfunction)
- [WebkitAppearance](akashaproject_design_system._internal_.Properties.md#webkitappearance)
- [WebkitBackdropFilter](akashaproject_design_system._internal_.Properties.md#webkitbackdropfilter)
- [WebkitBackfaceVisibility](akashaproject_design_system._internal_.Properties.md#webkitbackfacevisibility)
- [WebkitBackgroundClip](akashaproject_design_system._internal_.Properties.md#webkitbackgroundclip)
- [WebkitBackgroundOrigin](akashaproject_design_system._internal_.Properties.md#webkitbackgroundorigin)
- [WebkitBackgroundSize](akashaproject_design_system._internal_.Properties.md#webkitbackgroundsize)
- [WebkitBorderBefore](akashaproject_design_system._internal_.Properties.md#webkitborderbefore)
- [WebkitBorderBeforeColor](akashaproject_design_system._internal_.Properties.md#webkitborderbeforecolor)
- [WebkitBorderBeforeStyle](akashaproject_design_system._internal_.Properties.md#webkitborderbeforestyle)
- [WebkitBorderBeforeWidth](akashaproject_design_system._internal_.Properties.md#webkitborderbeforewidth)
- [WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.Properties.md#webkitborderbottomleftradius)
- [WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.Properties.md#webkitborderbottomrightradius)
- [WebkitBorderImage](akashaproject_design_system._internal_.Properties.md#webkitborderimage)
- [WebkitBorderImageSlice](akashaproject_design_system._internal_.Properties.md#webkitborderimageslice)
- [WebkitBorderRadius](akashaproject_design_system._internal_.Properties.md#webkitborderradius)
- [WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.Properties.md#webkitbordertopleftradius)
- [WebkitBorderTopRightRadius](akashaproject_design_system._internal_.Properties.md#webkitbordertoprightradius)
- [WebkitBoxAlign](akashaproject_design_system._internal_.Properties.md#webkitboxalign)
- [WebkitBoxDecorationBreak](akashaproject_design_system._internal_.Properties.md#webkitboxdecorationbreak)
- [WebkitBoxDirection](akashaproject_design_system._internal_.Properties.md#webkitboxdirection)
- [WebkitBoxFlex](akashaproject_design_system._internal_.Properties.md#webkitboxflex)
- [WebkitBoxFlexGroup](akashaproject_design_system._internal_.Properties.md#webkitboxflexgroup)
- [WebkitBoxLines](akashaproject_design_system._internal_.Properties.md#webkitboxlines)
- [WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#webkitboxordinalgroup)
- [WebkitBoxOrient](akashaproject_design_system._internal_.Properties.md#webkitboxorient)
- [WebkitBoxPack](akashaproject_design_system._internal_.Properties.md#webkitboxpack)
- [WebkitBoxReflect](akashaproject_design_system._internal_.Properties.md#webkitboxreflect)
- [WebkitBoxShadow](akashaproject_design_system._internal_.Properties.md#webkitboxshadow)
- [WebkitBoxSizing](akashaproject_design_system._internal_.Properties.md#webkitboxsizing)
- [WebkitClipPath](akashaproject_design_system._internal_.Properties.md#webkitclippath)
- [WebkitColumnCount](akashaproject_design_system._internal_.Properties.md#webkitcolumncount)
- [WebkitColumnFill](akashaproject_design_system._internal_.Properties.md#webkitcolumnfill)
- [WebkitColumnGap](akashaproject_design_system._internal_.Properties.md#webkitcolumngap)
- [WebkitColumnRule](akashaproject_design_system._internal_.Properties.md#webkitcolumnrule)
- [WebkitColumnRuleColor](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulecolor)
- [WebkitColumnRuleStyle](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulestyle)
- [WebkitColumnRuleWidth](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulewidth)
- [WebkitColumnSpan](akashaproject_design_system._internal_.Properties.md#webkitcolumnspan)
- [WebkitColumnWidth](akashaproject_design_system._internal_.Properties.md#webkitcolumnwidth)
- [WebkitColumns](akashaproject_design_system._internal_.Properties.md#webkitcolumns)
- [WebkitFilter](akashaproject_design_system._internal_.Properties.md#webkitfilter)
- [WebkitFlex](akashaproject_design_system._internal_.Properties.md#webkitflex)
- [WebkitFlexBasis](akashaproject_design_system._internal_.Properties.md#webkitflexbasis)
- [WebkitFlexDirection](akashaproject_design_system._internal_.Properties.md#webkitflexdirection)
- [WebkitFlexFlow](akashaproject_design_system._internal_.Properties.md#webkitflexflow)
- [WebkitFlexGrow](akashaproject_design_system._internal_.Properties.md#webkitflexgrow)
- [WebkitFlexShrink](akashaproject_design_system._internal_.Properties.md#webkitflexshrink)
- [WebkitFlexWrap](akashaproject_design_system._internal_.Properties.md#webkitflexwrap)
- [WebkitFontFeatureSettings](akashaproject_design_system._internal_.Properties.md#webkitfontfeaturesettings)
- [WebkitFontKerning](akashaproject_design_system._internal_.Properties.md#webkitfontkerning)
- [WebkitFontSmoothing](akashaproject_design_system._internal_.Properties.md#webkitfontsmoothing)
- [WebkitFontVariantLigatures](akashaproject_design_system._internal_.Properties.md#webkitfontvariantligatures)
- [WebkitHyphens](akashaproject_design_system._internal_.Properties.md#webkithyphens)
- [WebkitJustifyContent](akashaproject_design_system._internal_.Properties.md#webkitjustifycontent)
- [WebkitLineBreak](akashaproject_design_system._internal_.Properties.md#webkitlinebreak)
- [WebkitLineClamp](akashaproject_design_system._internal_.Properties.md#webkitlineclamp)
- [WebkitMarginEnd](akashaproject_design_system._internal_.Properties.md#webkitmarginend)
- [WebkitMarginStart](akashaproject_design_system._internal_.Properties.md#webkitmarginstart)
- [WebkitMask](akashaproject_design_system._internal_.Properties.md#webkitmask)
- [WebkitMaskAttachment](akashaproject_design_system._internal_.Properties.md#webkitmaskattachment)
- [WebkitMaskBoxImage](akashaproject_design_system._internal_.Properties.md#webkitmaskboximage)
- [WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.Properties.md#webkitmaskboximageoutset)
- [WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagerepeat)
- [WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.Properties.md#webkitmaskboximageslice)
- [WebkitMaskBoxImageSource](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagesource)
- [WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagewidth)
- [WebkitMaskClip](akashaproject_design_system._internal_.Properties.md#webkitmaskclip)
- [WebkitMaskComposite](akashaproject_design_system._internal_.Properties.md#webkitmaskcomposite)
- [WebkitMaskImage](akashaproject_design_system._internal_.Properties.md#webkitmaskimage)
- [WebkitMaskOrigin](akashaproject_design_system._internal_.Properties.md#webkitmaskorigin)
- [WebkitMaskPosition](akashaproject_design_system._internal_.Properties.md#webkitmaskposition)
- [WebkitMaskPositionX](akashaproject_design_system._internal_.Properties.md#webkitmaskpositionx)
- [WebkitMaskPositionY](akashaproject_design_system._internal_.Properties.md#webkitmaskpositiony)
- [WebkitMaskRepeat](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeat)
- [WebkitMaskRepeatX](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeatx)
- [WebkitMaskRepeatY](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeaty)
- [WebkitMaskSize](akashaproject_design_system._internal_.Properties.md#webkitmasksize)
- [WebkitMaxInlineSize](akashaproject_design_system._internal_.Properties.md#webkitmaxinlinesize)
- [WebkitOrder](akashaproject_design_system._internal_.Properties.md#webkitorder)
- [WebkitOverflowScrolling](akashaproject_design_system._internal_.Properties.md#webkitoverflowscrolling)
- [WebkitPaddingEnd](akashaproject_design_system._internal_.Properties.md#webkitpaddingend)
- [WebkitPaddingStart](akashaproject_design_system._internal_.Properties.md#webkitpaddingstart)
- [WebkitPerspective](akashaproject_design_system._internal_.Properties.md#webkitperspective)
- [WebkitPerspectiveOrigin](akashaproject_design_system._internal_.Properties.md#webkitperspectiveorigin)
- [WebkitPrintColorAdjust](akashaproject_design_system._internal_.Properties.md#webkitprintcoloradjust)
- [WebkitRubyPosition](akashaproject_design_system._internal_.Properties.md#webkitrubyposition)
- [WebkitScrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#webkitscrollsnappointsx)
- [WebkitScrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#webkitscrollsnappointsy)
- [WebkitScrollSnapType](akashaproject_design_system._internal_.Properties.md#webkitscrollsnaptype)
- [WebkitShapeMargin](akashaproject_design_system._internal_.Properties.md#webkitshapemargin)
- [WebkitTapHighlightColor](akashaproject_design_system._internal_.Properties.md#webkittaphighlightcolor)
- [WebkitTextCombine](akashaproject_design_system._internal_.Properties.md#webkittextcombine)
- [WebkitTextDecorationColor](akashaproject_design_system._internal_.Properties.md#webkittextdecorationcolor)
- [WebkitTextDecorationLine](akashaproject_design_system._internal_.Properties.md#webkittextdecorationline)
- [WebkitTextDecorationSkip](akashaproject_design_system._internal_.Properties.md#webkittextdecorationskip)
- [WebkitTextDecorationStyle](akashaproject_design_system._internal_.Properties.md#webkittextdecorationstyle)
- [WebkitTextEmphasis](akashaproject_design_system._internal_.Properties.md#webkittextemphasis)
- [WebkitTextEmphasisColor](akashaproject_design_system._internal_.Properties.md#webkittextemphasiscolor)
- [WebkitTextEmphasisPosition](akashaproject_design_system._internal_.Properties.md#webkittextemphasisposition)
- [WebkitTextEmphasisStyle](akashaproject_design_system._internal_.Properties.md#webkittextemphasisstyle)
- [WebkitTextFillColor](akashaproject_design_system._internal_.Properties.md#webkittextfillcolor)
- [WebkitTextOrientation](akashaproject_design_system._internal_.Properties.md#webkittextorientation)
- [WebkitTextSizeAdjust](akashaproject_design_system._internal_.Properties.md#webkittextsizeadjust)
- [WebkitTextStroke](akashaproject_design_system._internal_.Properties.md#webkittextstroke)
- [WebkitTextStrokeColor](akashaproject_design_system._internal_.Properties.md#webkittextstrokecolor)
- [WebkitTextStrokeWidth](akashaproject_design_system._internal_.Properties.md#webkittextstrokewidth)
- [WebkitTextUnderlinePosition](akashaproject_design_system._internal_.Properties.md#webkittextunderlineposition)
- [WebkitTouchCallout](akashaproject_design_system._internal_.Properties.md#webkittouchcallout)
- [WebkitTransform](akashaproject_design_system._internal_.Properties.md#webkittransform)
- [WebkitTransformOrigin](akashaproject_design_system._internal_.Properties.md#webkittransformorigin)
- [WebkitTransformStyle](akashaproject_design_system._internal_.Properties.md#webkittransformstyle)
- [WebkitTransition](akashaproject_design_system._internal_.Properties.md#webkittransition)
- [WebkitTransitionDelay](akashaproject_design_system._internal_.Properties.md#webkittransitiondelay)
- [WebkitTransitionDuration](akashaproject_design_system._internal_.Properties.md#webkittransitionduration)
- [WebkitTransitionProperty](akashaproject_design_system._internal_.Properties.md#webkittransitionproperty)
- [WebkitTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#webkittransitiontimingfunction)
- [WebkitUserModify](akashaproject_design_system._internal_.Properties.md#webkitusermodify)
- [WebkitUserSelect](akashaproject_design_system._internal_.Properties.md#webkituserselect)
- [WebkitWritingMode](akashaproject_design_system._internal_.Properties.md#webkitwritingmode)
- [accentColor](akashaproject_design_system._internal_.Properties.md#accentcolor)
- [alignContent](akashaproject_design_system._internal_.Properties.md#aligncontent)
- [alignItems](akashaproject_design_system._internal_.Properties.md#alignitems)
- [alignSelf](akashaproject_design_system._internal_.Properties.md#alignself)
- [alignTracks](akashaproject_design_system._internal_.Properties.md#aligntracks)
- [alignmentBaseline](akashaproject_design_system._internal_.Properties.md#alignmentbaseline)
- [all](akashaproject_design_system._internal_.Properties.md#all)
- [animation](akashaproject_design_system._internal_.Properties.md#animation)
- [animationDelay](akashaproject_design_system._internal_.Properties.md#animationdelay)
- [animationDirection](akashaproject_design_system._internal_.Properties.md#animationdirection)
- [animationDuration](akashaproject_design_system._internal_.Properties.md#animationduration)
- [animationFillMode](akashaproject_design_system._internal_.Properties.md#animationfillmode)
- [animationIterationCount](akashaproject_design_system._internal_.Properties.md#animationiterationcount)
- [animationName](akashaproject_design_system._internal_.Properties.md#animationname)
- [animationPlayState](akashaproject_design_system._internal_.Properties.md#animationplaystate)
- [animationTimingFunction](akashaproject_design_system._internal_.Properties.md#animationtimingfunction)
- [appearance](akashaproject_design_system._internal_.Properties.md#appearance)
- [aspectRatio](akashaproject_design_system._internal_.Properties.md#aspectratio)
- [azimuth](akashaproject_design_system._internal_.Properties.md#azimuth)
- [backdropFilter](akashaproject_design_system._internal_.Properties.md#backdropfilter)
- [backfaceVisibility](akashaproject_design_system._internal_.Properties.md#backfacevisibility)
- [background](akashaproject_design_system._internal_.Properties.md#background)
- [backgroundAttachment](akashaproject_design_system._internal_.Properties.md#backgroundattachment)
- [backgroundBlendMode](akashaproject_design_system._internal_.Properties.md#backgroundblendmode)
- [backgroundClip](akashaproject_design_system._internal_.Properties.md#backgroundclip)
- [backgroundColor](akashaproject_design_system._internal_.Properties.md#backgroundcolor)
- [backgroundImage](akashaproject_design_system._internal_.Properties.md#backgroundimage)
- [backgroundOrigin](akashaproject_design_system._internal_.Properties.md#backgroundorigin)
- [backgroundPosition](akashaproject_design_system._internal_.Properties.md#backgroundposition)
- [backgroundPositionX](akashaproject_design_system._internal_.Properties.md#backgroundpositionx)
- [backgroundPositionY](akashaproject_design_system._internal_.Properties.md#backgroundpositiony)
- [backgroundRepeat](akashaproject_design_system._internal_.Properties.md#backgroundrepeat)
- [backgroundSize](akashaproject_design_system._internal_.Properties.md#backgroundsize)
- [baselineShift](akashaproject_design_system._internal_.Properties.md#baselineshift)
- [blockOverflow](akashaproject_design_system._internal_.Properties.md#blockoverflow)
- [blockSize](akashaproject_design_system._internal_.Properties.md#blocksize)
- [border](akashaproject_design_system._internal_.Properties.md#border)
- [borderBlock](akashaproject_design_system._internal_.Properties.md#borderblock)
- [borderBlockColor](akashaproject_design_system._internal_.Properties.md#borderblockcolor)
- [borderBlockEnd](akashaproject_design_system._internal_.Properties.md#borderblockend)
- [borderBlockEndColor](akashaproject_design_system._internal_.Properties.md#borderblockendcolor)
- [borderBlockEndStyle](akashaproject_design_system._internal_.Properties.md#borderblockendstyle)
- [borderBlockEndWidth](akashaproject_design_system._internal_.Properties.md#borderblockendwidth)
- [borderBlockStart](akashaproject_design_system._internal_.Properties.md#borderblockstart)
- [borderBlockStartColor](akashaproject_design_system._internal_.Properties.md#borderblockstartcolor)
- [borderBlockStartStyle](akashaproject_design_system._internal_.Properties.md#borderblockstartstyle)
- [borderBlockStartWidth](akashaproject_design_system._internal_.Properties.md#borderblockstartwidth)
- [borderBlockStyle](akashaproject_design_system._internal_.Properties.md#borderblockstyle)
- [borderBlockWidth](akashaproject_design_system._internal_.Properties.md#borderblockwidth)
- [borderBottom](akashaproject_design_system._internal_.Properties.md#borderbottom)
- [borderBottomColor](akashaproject_design_system._internal_.Properties.md#borderbottomcolor)
- [borderBottomLeftRadius](akashaproject_design_system._internal_.Properties.md#borderbottomleftradius)
- [borderBottomRightRadius](akashaproject_design_system._internal_.Properties.md#borderbottomrightradius)
- [borderBottomStyle](akashaproject_design_system._internal_.Properties.md#borderbottomstyle)
- [borderBottomWidth](akashaproject_design_system._internal_.Properties.md#borderbottomwidth)
- [borderCollapse](akashaproject_design_system._internal_.Properties.md#bordercollapse)
- [borderColor](akashaproject_design_system._internal_.Properties.md#bordercolor)
- [borderEndEndRadius](akashaproject_design_system._internal_.Properties.md#borderendendradius)
- [borderEndStartRadius](akashaproject_design_system._internal_.Properties.md#borderendstartradius)
- [borderImage](akashaproject_design_system._internal_.Properties.md#borderimage)
- [borderImageOutset](akashaproject_design_system._internal_.Properties.md#borderimageoutset)
- [borderImageRepeat](akashaproject_design_system._internal_.Properties.md#borderimagerepeat)
- [borderImageSlice](akashaproject_design_system._internal_.Properties.md#borderimageslice)
- [borderImageSource](akashaproject_design_system._internal_.Properties.md#borderimagesource)
- [borderImageWidth](akashaproject_design_system._internal_.Properties.md#borderimagewidth)
- [borderInline](akashaproject_design_system._internal_.Properties.md#borderinline)
- [borderInlineColor](akashaproject_design_system._internal_.Properties.md#borderinlinecolor)
- [borderInlineEnd](akashaproject_design_system._internal_.Properties.md#borderinlineend)
- [borderInlineEndColor](akashaproject_design_system._internal_.Properties.md#borderinlineendcolor)
- [borderInlineEndStyle](akashaproject_design_system._internal_.Properties.md#borderinlineendstyle)
- [borderInlineEndWidth](akashaproject_design_system._internal_.Properties.md#borderinlineendwidth)
- [borderInlineStart](akashaproject_design_system._internal_.Properties.md#borderinlinestart)
- [borderInlineStartColor](akashaproject_design_system._internal_.Properties.md#borderinlinestartcolor)
- [borderInlineStartStyle](akashaproject_design_system._internal_.Properties.md#borderinlinestartstyle)
- [borderInlineStartWidth](akashaproject_design_system._internal_.Properties.md#borderinlinestartwidth)
- [borderInlineStyle](akashaproject_design_system._internal_.Properties.md#borderinlinestyle)
- [borderInlineWidth](akashaproject_design_system._internal_.Properties.md#borderinlinewidth)
- [borderLeft](akashaproject_design_system._internal_.Properties.md#borderleft)
- [borderLeftColor](akashaproject_design_system._internal_.Properties.md#borderleftcolor)
- [borderLeftStyle](akashaproject_design_system._internal_.Properties.md#borderleftstyle)
- [borderLeftWidth](akashaproject_design_system._internal_.Properties.md#borderleftwidth)
- [borderRadius](akashaproject_design_system._internal_.Properties.md#borderradius)
- [borderRight](akashaproject_design_system._internal_.Properties.md#borderright)
- [borderRightColor](akashaproject_design_system._internal_.Properties.md#borderrightcolor)
- [borderRightStyle](akashaproject_design_system._internal_.Properties.md#borderrightstyle)
- [borderRightWidth](akashaproject_design_system._internal_.Properties.md#borderrightwidth)
- [borderSpacing](akashaproject_design_system._internal_.Properties.md#borderspacing)
- [borderStartEndRadius](akashaproject_design_system._internal_.Properties.md#borderstartendradius)
- [borderStartStartRadius](akashaproject_design_system._internal_.Properties.md#borderstartstartradius)
- [borderStyle](akashaproject_design_system._internal_.Properties.md#borderstyle)
- [borderTop](akashaproject_design_system._internal_.Properties.md#bordertop)
- [borderTopColor](akashaproject_design_system._internal_.Properties.md#bordertopcolor)
- [borderTopLeftRadius](akashaproject_design_system._internal_.Properties.md#bordertopleftradius)
- [borderTopRightRadius](akashaproject_design_system._internal_.Properties.md#bordertoprightradius)
- [borderTopStyle](akashaproject_design_system._internal_.Properties.md#bordertopstyle)
- [borderTopWidth](akashaproject_design_system._internal_.Properties.md#bordertopwidth)
- [borderWidth](akashaproject_design_system._internal_.Properties.md#borderwidth)
- [bottom](akashaproject_design_system._internal_.Properties.md#bottom)
- [boxAlign](akashaproject_design_system._internal_.Properties.md#boxalign)
- [boxDecorationBreak](akashaproject_design_system._internal_.Properties.md#boxdecorationbreak)
- [boxDirection](akashaproject_design_system._internal_.Properties.md#boxdirection)
- [boxFlex](akashaproject_design_system._internal_.Properties.md#boxflex)
- [boxFlexGroup](akashaproject_design_system._internal_.Properties.md#boxflexgroup)
- [boxLines](akashaproject_design_system._internal_.Properties.md#boxlines)
- [boxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#boxordinalgroup)
- [boxOrient](akashaproject_design_system._internal_.Properties.md#boxorient)
- [boxPack](akashaproject_design_system._internal_.Properties.md#boxpack)
- [boxShadow](akashaproject_design_system._internal_.Properties.md#boxshadow)
- [boxSizing](akashaproject_design_system._internal_.Properties.md#boxsizing)
- [breakAfter](akashaproject_design_system._internal_.Properties.md#breakafter)
- [breakBefore](akashaproject_design_system._internal_.Properties.md#breakbefore)
- [breakInside](akashaproject_design_system._internal_.Properties.md#breakinside)
- [captionSide](akashaproject_design_system._internal_.Properties.md#captionside)
- [caretColor](akashaproject_design_system._internal_.Properties.md#caretcolor)
- [clear](akashaproject_design_system._internal_.Properties.md#clear)
- [clip](akashaproject_design_system._internal_.Properties.md#clip)
- [clipPath](akashaproject_design_system._internal_.Properties.md#clippath)
- [clipRule](akashaproject_design_system._internal_.Properties.md#cliprule)
- [color](akashaproject_design_system._internal_.Properties.md#color)
- [colorAdjust](akashaproject_design_system._internal_.Properties.md#coloradjust)
- [colorInterpolation](akashaproject_design_system._internal_.Properties.md#colorinterpolation)
- [colorRendering](akashaproject_design_system._internal_.Properties.md#colorrendering)
- [colorScheme](akashaproject_design_system._internal_.Properties.md#colorscheme)
- [columnCount](akashaproject_design_system._internal_.Properties.md#columncount)
- [columnFill](akashaproject_design_system._internal_.Properties.md#columnfill)
- [columnGap](akashaproject_design_system._internal_.Properties.md#columngap)
- [columnRule](akashaproject_design_system._internal_.Properties.md#columnrule)
- [columnRuleColor](akashaproject_design_system._internal_.Properties.md#columnrulecolor)
- [columnRuleStyle](akashaproject_design_system._internal_.Properties.md#columnrulestyle)
- [columnRuleWidth](akashaproject_design_system._internal_.Properties.md#columnrulewidth)
- [columnSpan](akashaproject_design_system._internal_.Properties.md#columnspan)
- [columnWidth](akashaproject_design_system._internal_.Properties.md#columnwidth)
- [columns](akashaproject_design_system._internal_.Properties.md#columns)
- [contain](akashaproject_design_system._internal_.Properties.md#contain)
- [content](akashaproject_design_system._internal_.Properties.md#content)
- [contentVisibility](akashaproject_design_system._internal_.Properties.md#contentvisibility)
- [counterIncrement](akashaproject_design_system._internal_.Properties.md#counterincrement)
- [counterReset](akashaproject_design_system._internal_.Properties.md#counterreset)
- [counterSet](akashaproject_design_system._internal_.Properties.md#counterset)
- [cursor](akashaproject_design_system._internal_.Properties.md#cursor)
- [direction](akashaproject_design_system._internal_.Properties.md#direction)
- [display](akashaproject_design_system._internal_.Properties.md#display)
- [dominantBaseline](akashaproject_design_system._internal_.Properties.md#dominantbaseline)
- [emptyCells](akashaproject_design_system._internal_.Properties.md#emptycells)
- [fill](akashaproject_design_system._internal_.Properties.md#fill)
- [fillOpacity](akashaproject_design_system._internal_.Properties.md#fillopacity)
- [fillRule](akashaproject_design_system._internal_.Properties.md#fillrule)
- [filter](akashaproject_design_system._internal_.Properties.md#filter)
- [flex](akashaproject_design_system._internal_.Properties.md#flex)
- [flexBasis](akashaproject_design_system._internal_.Properties.md#flexbasis)
- [flexDirection](akashaproject_design_system._internal_.Properties.md#flexdirection)
- [flexFlow](akashaproject_design_system._internal_.Properties.md#flexflow)
- [flexGrow](akashaproject_design_system._internal_.Properties.md#flexgrow)
- [flexShrink](akashaproject_design_system._internal_.Properties.md#flexshrink)
- [flexWrap](akashaproject_design_system._internal_.Properties.md#flexwrap)
- [float](akashaproject_design_system._internal_.Properties.md#float)
- [floodColor](akashaproject_design_system._internal_.Properties.md#floodcolor)
- [floodOpacity](akashaproject_design_system._internal_.Properties.md#floodopacity)
- [font](akashaproject_design_system._internal_.Properties.md#font)
- [fontFamily](akashaproject_design_system._internal_.Properties.md#fontfamily)
- [fontFeatureSettings](akashaproject_design_system._internal_.Properties.md#fontfeaturesettings)
- [fontKerning](akashaproject_design_system._internal_.Properties.md#fontkerning)
- [fontLanguageOverride](akashaproject_design_system._internal_.Properties.md#fontlanguageoverride)
- [fontOpticalSizing](akashaproject_design_system._internal_.Properties.md#fontopticalsizing)
- [fontSize](akashaproject_design_system._internal_.Properties.md#fontsize)
- [fontSizeAdjust](akashaproject_design_system._internal_.Properties.md#fontsizeadjust)
- [fontSmooth](akashaproject_design_system._internal_.Properties.md#fontsmooth)
- [fontStretch](akashaproject_design_system._internal_.Properties.md#fontstretch)
- [fontStyle](akashaproject_design_system._internal_.Properties.md#fontstyle)
- [fontSynthesis](akashaproject_design_system._internal_.Properties.md#fontsynthesis)
- [fontVariant](akashaproject_design_system._internal_.Properties.md#fontvariant)
- [fontVariantAlternates](akashaproject_design_system._internal_.Properties.md#fontvariantalternates)
- [fontVariantCaps](akashaproject_design_system._internal_.Properties.md#fontvariantcaps)
- [fontVariantEastAsian](akashaproject_design_system._internal_.Properties.md#fontvarianteastasian)
- [fontVariantLigatures](akashaproject_design_system._internal_.Properties.md#fontvariantligatures)
- [fontVariantNumeric](akashaproject_design_system._internal_.Properties.md#fontvariantnumeric)
- [fontVariantPosition](akashaproject_design_system._internal_.Properties.md#fontvariantposition)
- [fontVariationSettings](akashaproject_design_system._internal_.Properties.md#fontvariationsettings)
- [fontWeight](akashaproject_design_system._internal_.Properties.md#fontweight)
- [forcedColorAdjust](akashaproject_design_system._internal_.Properties.md#forcedcoloradjust)
- [gap](akashaproject_design_system._internal_.Properties.md#gap)
- [glyphOrientationVertical](akashaproject_design_system._internal_.Properties.md#glyphorientationvertical)
- [grid](akashaproject_design_system._internal_.Properties.md#grid)
- [gridArea](akashaproject_design_system._internal_.Properties.md#gridarea)
- [gridAutoColumns](akashaproject_design_system._internal_.Properties.md#gridautocolumns)
- [gridAutoFlow](akashaproject_design_system._internal_.Properties.md#gridautoflow)
- [gridAutoRows](akashaproject_design_system._internal_.Properties.md#gridautorows)
- [gridColumn](akashaproject_design_system._internal_.Properties.md#gridcolumn)
- [gridColumnEnd](akashaproject_design_system._internal_.Properties.md#gridcolumnend)
- [gridColumnGap](akashaproject_design_system._internal_.Properties.md#gridcolumngap)
- [gridColumnStart](akashaproject_design_system._internal_.Properties.md#gridcolumnstart)
- [gridGap](akashaproject_design_system._internal_.Properties.md#gridgap)
- [gridRow](akashaproject_design_system._internal_.Properties.md#gridrow)
- [gridRowEnd](akashaproject_design_system._internal_.Properties.md#gridrowend)
- [gridRowGap](akashaproject_design_system._internal_.Properties.md#gridrowgap)
- [gridRowStart](akashaproject_design_system._internal_.Properties.md#gridrowstart)
- [gridTemplate](akashaproject_design_system._internal_.Properties.md#gridtemplate)
- [gridTemplateAreas](akashaproject_design_system._internal_.Properties.md#gridtemplateareas)
- [gridTemplateColumns](akashaproject_design_system._internal_.Properties.md#gridtemplatecolumns)
- [gridTemplateRows](akashaproject_design_system._internal_.Properties.md#gridtemplaterows)
- [hangingPunctuation](akashaproject_design_system._internal_.Properties.md#hangingpunctuation)
- [height](akashaproject_design_system._internal_.Properties.md#height)
- [hyphens](akashaproject_design_system._internal_.Properties.md#hyphens)
- [imageOrientation](akashaproject_design_system._internal_.Properties.md#imageorientation)
- [imageRendering](akashaproject_design_system._internal_.Properties.md#imagerendering)
- [imageResolution](akashaproject_design_system._internal_.Properties.md#imageresolution)
- [imeMode](akashaproject_design_system._internal_.Properties.md#imemode)
- [initialLetter](akashaproject_design_system._internal_.Properties.md#initialletter)
- [inlineSize](akashaproject_design_system._internal_.Properties.md#inlinesize)
- [inset](akashaproject_design_system._internal_.Properties.md#inset)
- [insetBlock](akashaproject_design_system._internal_.Properties.md#insetblock)
- [insetBlockEnd](akashaproject_design_system._internal_.Properties.md#insetblockend)
- [insetBlockStart](akashaproject_design_system._internal_.Properties.md#insetblockstart)
- [insetInline](akashaproject_design_system._internal_.Properties.md#insetinline)
- [insetInlineEnd](akashaproject_design_system._internal_.Properties.md#insetinlineend)
- [insetInlineStart](akashaproject_design_system._internal_.Properties.md#insetinlinestart)
- [isolation](akashaproject_design_system._internal_.Properties.md#isolation)
- [justifyContent](akashaproject_design_system._internal_.Properties.md#justifycontent)
- [justifyItems](akashaproject_design_system._internal_.Properties.md#justifyitems)
- [justifySelf](akashaproject_design_system._internal_.Properties.md#justifyself)
- [justifyTracks](akashaproject_design_system._internal_.Properties.md#justifytracks)
- [left](akashaproject_design_system._internal_.Properties.md#left)
- [letterSpacing](akashaproject_design_system._internal_.Properties.md#letterspacing)
- [lightingColor](akashaproject_design_system._internal_.Properties.md#lightingcolor)
- [lineBreak](akashaproject_design_system._internal_.Properties.md#linebreak)
- [lineClamp](akashaproject_design_system._internal_.Properties.md#lineclamp)
- [lineHeight](akashaproject_design_system._internal_.Properties.md#lineheight)
- [lineHeightStep](akashaproject_design_system._internal_.Properties.md#lineheightstep)
- [listStyle](akashaproject_design_system._internal_.Properties.md#liststyle)
- [listStyleImage](akashaproject_design_system._internal_.Properties.md#liststyleimage)
- [listStylePosition](akashaproject_design_system._internal_.Properties.md#liststyleposition)
- [listStyleType](akashaproject_design_system._internal_.Properties.md#liststyletype)
- [margin](akashaproject_design_system._internal_.Properties.md#margin)
- [marginBlock](akashaproject_design_system._internal_.Properties.md#marginblock)
- [marginBlockEnd](akashaproject_design_system._internal_.Properties.md#marginblockend)
- [marginBlockStart](akashaproject_design_system._internal_.Properties.md#marginblockstart)
- [marginBottom](akashaproject_design_system._internal_.Properties.md#marginbottom)
- [marginInline](akashaproject_design_system._internal_.Properties.md#margininline)
- [marginInlineEnd](akashaproject_design_system._internal_.Properties.md#margininlineend)
- [marginInlineStart](akashaproject_design_system._internal_.Properties.md#margininlinestart)
- [marginLeft](akashaproject_design_system._internal_.Properties.md#marginleft)
- [marginRight](akashaproject_design_system._internal_.Properties.md#marginright)
- [marginTop](akashaproject_design_system._internal_.Properties.md#margintop)
- [marker](akashaproject_design_system._internal_.Properties.md#marker)
- [markerEnd](akashaproject_design_system._internal_.Properties.md#markerend)
- [markerMid](akashaproject_design_system._internal_.Properties.md#markermid)
- [markerStart](akashaproject_design_system._internal_.Properties.md#markerstart)
- [mask](akashaproject_design_system._internal_.Properties.md#mask)
- [maskBorder](akashaproject_design_system._internal_.Properties.md#maskborder)
- [maskBorderMode](akashaproject_design_system._internal_.Properties.md#maskbordermode)
- [maskBorderOutset](akashaproject_design_system._internal_.Properties.md#maskborderoutset)
- [maskBorderRepeat](akashaproject_design_system._internal_.Properties.md#maskborderrepeat)
- [maskBorderSlice](akashaproject_design_system._internal_.Properties.md#maskborderslice)
- [maskBorderSource](akashaproject_design_system._internal_.Properties.md#maskbordersource)
- [maskBorderWidth](akashaproject_design_system._internal_.Properties.md#maskborderwidth)
- [maskClip](akashaproject_design_system._internal_.Properties.md#maskclip)
- [maskComposite](akashaproject_design_system._internal_.Properties.md#maskcomposite)
- [maskImage](akashaproject_design_system._internal_.Properties.md#maskimage)
- [maskMode](akashaproject_design_system._internal_.Properties.md#maskmode)
- [maskOrigin](akashaproject_design_system._internal_.Properties.md#maskorigin)
- [maskPosition](akashaproject_design_system._internal_.Properties.md#maskposition)
- [maskRepeat](akashaproject_design_system._internal_.Properties.md#maskrepeat)
- [maskSize](akashaproject_design_system._internal_.Properties.md#masksize)
- [maskType](akashaproject_design_system._internal_.Properties.md#masktype)
- [mathStyle](akashaproject_design_system._internal_.Properties.md#mathstyle)
- [maxBlockSize](akashaproject_design_system._internal_.Properties.md#maxblocksize)
- [maxHeight](akashaproject_design_system._internal_.Properties.md#maxheight)
- [maxInlineSize](akashaproject_design_system._internal_.Properties.md#maxinlinesize)
- [maxLines](akashaproject_design_system._internal_.Properties.md#maxlines)
- [maxWidth](akashaproject_design_system._internal_.Properties.md#maxwidth)
- [minBlockSize](akashaproject_design_system._internal_.Properties.md#minblocksize)
- [minHeight](akashaproject_design_system._internal_.Properties.md#minheight)
- [minInlineSize](akashaproject_design_system._internal_.Properties.md#mininlinesize)
- [minWidth](akashaproject_design_system._internal_.Properties.md#minwidth)
- [mixBlendMode](akashaproject_design_system._internal_.Properties.md#mixblendmode)
- [motion](akashaproject_design_system._internal_.Properties.md#motion)
- [motionDistance](akashaproject_design_system._internal_.Properties.md#motiondistance)
- [motionPath](akashaproject_design_system._internal_.Properties.md#motionpath)
- [motionRotation](akashaproject_design_system._internal_.Properties.md#motionrotation)
- [msAccelerator](akashaproject_design_system._internal_.Properties.md#msaccelerator)
- [msAlignSelf](akashaproject_design_system._internal_.Properties.md#msalignself)
- [msBlockProgression](akashaproject_design_system._internal_.Properties.md#msblockprogression)
- [msContentZoomChaining](akashaproject_design_system._internal_.Properties.md#mscontentzoomchaining)
- [msContentZoomLimit](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimit)
- [msContentZoomLimitMax](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimitmax)
- [msContentZoomLimitMin](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimitmin)
- [msContentZoomSnap](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnap)
- [msContentZoomSnapPoints](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnappoints)
- [msContentZoomSnapType](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnaptype)
- [msContentZooming](akashaproject_design_system._internal_.Properties.md#mscontentzooming)
- [msFilter](akashaproject_design_system._internal_.Properties.md#msfilter)
- [msFlex](akashaproject_design_system._internal_.Properties.md#msflex)
- [msFlexDirection](akashaproject_design_system._internal_.Properties.md#msflexdirection)
- [msFlexPositive](akashaproject_design_system._internal_.Properties.md#msflexpositive)
- [msFlowFrom](akashaproject_design_system._internal_.Properties.md#msflowfrom)
- [msFlowInto](akashaproject_design_system._internal_.Properties.md#msflowinto)
- [msGridColumns](akashaproject_design_system._internal_.Properties.md#msgridcolumns)
- [msGridRows](akashaproject_design_system._internal_.Properties.md#msgridrows)
- [msHighContrastAdjust](akashaproject_design_system._internal_.Properties.md#mshighcontrastadjust)
- [msHyphenateLimitChars](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitchars)
- [msHyphenateLimitLines](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitlines)
- [msHyphenateLimitZone](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitzone)
- [msHyphens](akashaproject_design_system._internal_.Properties.md#mshyphens)
- [msImeAlign](akashaproject_design_system._internal_.Properties.md#msimealign)
- [msImeMode](akashaproject_design_system._internal_.Properties.md#msimemode)
- [msJustifySelf](akashaproject_design_system._internal_.Properties.md#msjustifyself)
- [msLineBreak](akashaproject_design_system._internal_.Properties.md#mslinebreak)
- [msOrder](akashaproject_design_system._internal_.Properties.md#msorder)
- [msOverflowStyle](akashaproject_design_system._internal_.Properties.md#msoverflowstyle)
- [msOverflowX](akashaproject_design_system._internal_.Properties.md#msoverflowx)
- [msOverflowY](akashaproject_design_system._internal_.Properties.md#msoverflowy)
- [msScrollChaining](akashaproject_design_system._internal_.Properties.md#msscrollchaining)
- [msScrollLimit](akashaproject_design_system._internal_.Properties.md#msscrolllimit)
- [msScrollLimitXMax](akashaproject_design_system._internal_.Properties.md#msscrolllimitxmax)
- [msScrollLimitXMin](akashaproject_design_system._internal_.Properties.md#msscrolllimitxmin)
- [msScrollLimitYMax](akashaproject_design_system._internal_.Properties.md#msscrolllimitymax)
- [msScrollLimitYMin](akashaproject_design_system._internal_.Properties.md#msscrolllimitymin)
- [msScrollRails](akashaproject_design_system._internal_.Properties.md#msscrollrails)
- [msScrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#msscrollsnappointsx)
- [msScrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#msscrollsnappointsy)
- [msScrollSnapType](akashaproject_design_system._internal_.Properties.md#msscrollsnaptype)
- [msScrollSnapX](akashaproject_design_system._internal_.Properties.md#msscrollsnapx)
- [msScrollSnapY](akashaproject_design_system._internal_.Properties.md#msscrollsnapy)
- [msScrollTranslation](akashaproject_design_system._internal_.Properties.md#msscrolltranslation)
- [msScrollbar3dlightColor](akashaproject_design_system._internal_.Properties.md#msscrollbar3dlightcolor)
- [msScrollbarArrowColor](akashaproject_design_system._internal_.Properties.md#msscrollbararrowcolor)
- [msScrollbarBaseColor](akashaproject_design_system._internal_.Properties.md#msscrollbarbasecolor)
- [msScrollbarDarkshadowColor](akashaproject_design_system._internal_.Properties.md#msscrollbardarkshadowcolor)
- [msScrollbarFaceColor](akashaproject_design_system._internal_.Properties.md#msscrollbarfacecolor)
- [msScrollbarHighlightColor](akashaproject_design_system._internal_.Properties.md#msscrollbarhighlightcolor)
- [msScrollbarShadowColor](akashaproject_design_system._internal_.Properties.md#msscrollbarshadowcolor)
- [msScrollbarTrackColor](akashaproject_design_system._internal_.Properties.md#msscrollbartrackcolor)
- [msTextAutospace](akashaproject_design_system._internal_.Properties.md#mstextautospace)
- [msTextCombineHorizontal](akashaproject_design_system._internal_.Properties.md#mstextcombinehorizontal)
- [msTextOverflow](akashaproject_design_system._internal_.Properties.md#mstextoverflow)
- [msTouchAction](akashaproject_design_system._internal_.Properties.md#mstouchaction)
- [msTouchSelect](akashaproject_design_system._internal_.Properties.md#mstouchselect)
- [msTransform](akashaproject_design_system._internal_.Properties.md#mstransform)
- [msTransformOrigin](akashaproject_design_system._internal_.Properties.md#mstransformorigin)
- [msTransition](akashaproject_design_system._internal_.Properties.md#mstransition)
- [msTransitionDelay](akashaproject_design_system._internal_.Properties.md#mstransitiondelay)
- [msTransitionDuration](akashaproject_design_system._internal_.Properties.md#mstransitionduration)
- [msTransitionProperty](akashaproject_design_system._internal_.Properties.md#mstransitionproperty)
- [msTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#mstransitiontimingfunction)
- [msUserSelect](akashaproject_design_system._internal_.Properties.md#msuserselect)
- [msWordBreak](akashaproject_design_system._internal_.Properties.md#mswordbreak)
- [msWrapFlow](akashaproject_design_system._internal_.Properties.md#mswrapflow)
- [msWrapMargin](akashaproject_design_system._internal_.Properties.md#mswrapmargin)
- [msWrapThrough](akashaproject_design_system._internal_.Properties.md#mswrapthrough)
- [msWritingMode](akashaproject_design_system._internal_.Properties.md#mswritingmode)
- [objectFit](akashaproject_design_system._internal_.Properties.md#objectfit)
- [objectPosition](akashaproject_design_system._internal_.Properties.md#objectposition)
- [offset](akashaproject_design_system._internal_.Properties.md#offset)
- [offsetAnchor](akashaproject_design_system._internal_.Properties.md#offsetanchor)
- [offsetBlock](akashaproject_design_system._internal_.Properties.md#offsetblock)
- [offsetBlockEnd](akashaproject_design_system._internal_.Properties.md#offsetblockend)
- [offsetBlockStart](akashaproject_design_system._internal_.Properties.md#offsetblockstart)
- [offsetDistance](akashaproject_design_system._internal_.Properties.md#offsetdistance)
- [offsetInline](akashaproject_design_system._internal_.Properties.md#offsetinline)
- [offsetInlineEnd](akashaproject_design_system._internal_.Properties.md#offsetinlineend)
- [offsetInlineStart](akashaproject_design_system._internal_.Properties.md#offsetinlinestart)
- [offsetPath](akashaproject_design_system._internal_.Properties.md#offsetpath)
- [offsetRotate](akashaproject_design_system._internal_.Properties.md#offsetrotate)
- [offsetRotation](akashaproject_design_system._internal_.Properties.md#offsetrotation)
- [opacity](akashaproject_design_system._internal_.Properties.md#opacity)
- [order](akashaproject_design_system._internal_.Properties.md#order)
- [orphans](akashaproject_design_system._internal_.Properties.md#orphans)
- [outline](akashaproject_design_system._internal_.Properties.md#outline)
- [outlineColor](akashaproject_design_system._internal_.Properties.md#outlinecolor)
- [outlineOffset](akashaproject_design_system._internal_.Properties.md#outlineoffset)
- [outlineStyle](akashaproject_design_system._internal_.Properties.md#outlinestyle)
- [outlineWidth](akashaproject_design_system._internal_.Properties.md#outlinewidth)
- [overflow](akashaproject_design_system._internal_.Properties.md#overflow)
- [overflowAnchor](akashaproject_design_system._internal_.Properties.md#overflowanchor)
- [overflowBlock](akashaproject_design_system._internal_.Properties.md#overflowblock)
- [overflowClipBox](akashaproject_design_system._internal_.Properties.md#overflowclipbox)
- [overflowClipMargin](akashaproject_design_system._internal_.Properties.md#overflowclipmargin)
- [overflowInline](akashaproject_design_system._internal_.Properties.md#overflowinline)
- [overflowWrap](akashaproject_design_system._internal_.Properties.md#overflowwrap)
- [overflowX](akashaproject_design_system._internal_.Properties.md#overflowx)
- [overflowY](akashaproject_design_system._internal_.Properties.md#overflowy)
- [overscrollBehavior](akashaproject_design_system._internal_.Properties.md#overscrollbehavior)
- [overscrollBehaviorBlock](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorblock)
- [overscrollBehaviorInline](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorinline)
- [overscrollBehaviorX](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorx)
- [overscrollBehaviorY](akashaproject_design_system._internal_.Properties.md#overscrollbehaviory)
- [padding](akashaproject_design_system._internal_.Properties.md#padding)
- [paddingBlock](akashaproject_design_system._internal_.Properties.md#paddingblock)
- [paddingBlockEnd](akashaproject_design_system._internal_.Properties.md#paddingblockend)
- [paddingBlockStart](akashaproject_design_system._internal_.Properties.md#paddingblockstart)
- [paddingBottom](akashaproject_design_system._internal_.Properties.md#paddingbottom)
- [paddingInline](akashaproject_design_system._internal_.Properties.md#paddinginline)
- [paddingInlineEnd](akashaproject_design_system._internal_.Properties.md#paddinginlineend)
- [paddingInlineStart](akashaproject_design_system._internal_.Properties.md#paddinginlinestart)
- [paddingLeft](akashaproject_design_system._internal_.Properties.md#paddingleft)
- [paddingRight](akashaproject_design_system._internal_.Properties.md#paddingright)
- [paddingTop](akashaproject_design_system._internal_.Properties.md#paddingtop)
- [pageBreakAfter](akashaproject_design_system._internal_.Properties.md#pagebreakafter)
- [pageBreakBefore](akashaproject_design_system._internal_.Properties.md#pagebreakbefore)
- [pageBreakInside](akashaproject_design_system._internal_.Properties.md#pagebreakinside)
- [paintOrder](akashaproject_design_system._internal_.Properties.md#paintorder)
- [perspective](akashaproject_design_system._internal_.Properties.md#perspective)
- [perspectiveOrigin](akashaproject_design_system._internal_.Properties.md#perspectiveorigin)
- [placeContent](akashaproject_design_system._internal_.Properties.md#placecontent)
- [placeItems](akashaproject_design_system._internal_.Properties.md#placeitems)
- [placeSelf](akashaproject_design_system._internal_.Properties.md#placeself)
- [pointerEvents](akashaproject_design_system._internal_.Properties.md#pointerevents)
- [position](akashaproject_design_system._internal_.Properties.md#position)
- [quotes](akashaproject_design_system._internal_.Properties.md#quotes)
- [resize](akashaproject_design_system._internal_.Properties.md#resize)
- [right](akashaproject_design_system._internal_.Properties.md#right)
- [rotate](akashaproject_design_system._internal_.Properties.md#rotate)
- [rowGap](akashaproject_design_system._internal_.Properties.md#rowgap)
- [rubyAlign](akashaproject_design_system._internal_.Properties.md#rubyalign)
- [rubyMerge](akashaproject_design_system._internal_.Properties.md#rubymerge)
- [rubyPosition](akashaproject_design_system._internal_.Properties.md#rubyposition)
- [scale](akashaproject_design_system._internal_.Properties.md#scale)
- [scrollBehavior](akashaproject_design_system._internal_.Properties.md#scrollbehavior)
- [scrollMargin](akashaproject_design_system._internal_.Properties.md#scrollmargin)
- [scrollMarginBlock](akashaproject_design_system._internal_.Properties.md#scrollmarginblock)
- [scrollMarginBlockEnd](akashaproject_design_system._internal_.Properties.md#scrollmarginblockend)
- [scrollMarginBlockStart](akashaproject_design_system._internal_.Properties.md#scrollmarginblockstart)
- [scrollMarginBottom](akashaproject_design_system._internal_.Properties.md#scrollmarginbottom)
- [scrollMarginInline](akashaproject_design_system._internal_.Properties.md#scrollmargininline)
- [scrollMarginInlineEnd](akashaproject_design_system._internal_.Properties.md#scrollmargininlineend)
- [scrollMarginInlineStart](akashaproject_design_system._internal_.Properties.md#scrollmargininlinestart)
- [scrollMarginLeft](akashaproject_design_system._internal_.Properties.md#scrollmarginleft)
- [scrollMarginRight](akashaproject_design_system._internal_.Properties.md#scrollmarginright)
- [scrollMarginTop](akashaproject_design_system._internal_.Properties.md#scrollmargintop)
- [scrollPadding](akashaproject_design_system._internal_.Properties.md#scrollpadding)
- [scrollPaddingBlock](akashaproject_design_system._internal_.Properties.md#scrollpaddingblock)
- [scrollPaddingBlockEnd](akashaproject_design_system._internal_.Properties.md#scrollpaddingblockend)
- [scrollPaddingBlockStart](akashaproject_design_system._internal_.Properties.md#scrollpaddingblockstart)
- [scrollPaddingBottom](akashaproject_design_system._internal_.Properties.md#scrollpaddingbottom)
- [scrollPaddingInline](akashaproject_design_system._internal_.Properties.md#scrollpaddinginline)
- [scrollPaddingInlineEnd](akashaproject_design_system._internal_.Properties.md#scrollpaddinginlineend)
- [scrollPaddingInlineStart](akashaproject_design_system._internal_.Properties.md#scrollpaddinginlinestart)
- [scrollPaddingLeft](akashaproject_design_system._internal_.Properties.md#scrollpaddingleft)
- [scrollPaddingRight](akashaproject_design_system._internal_.Properties.md#scrollpaddingright)
- [scrollPaddingTop](akashaproject_design_system._internal_.Properties.md#scrollpaddingtop)
- [scrollSnapAlign](akashaproject_design_system._internal_.Properties.md#scrollsnapalign)
- [scrollSnapCoordinate](akashaproject_design_system._internal_.Properties.md#scrollsnapcoordinate)
- [scrollSnapDestination](akashaproject_design_system._internal_.Properties.md#scrollsnapdestination)
- [scrollSnapMargin](akashaproject_design_system._internal_.Properties.md#scrollsnapmargin)
- [scrollSnapMarginBottom](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginbottom)
- [scrollSnapMarginLeft](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginleft)
- [scrollSnapMarginRight](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginright)
- [scrollSnapMarginTop](akashaproject_design_system._internal_.Properties.md#scrollsnapmargintop)
- [scrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#scrollsnappointsx)
- [scrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#scrollsnappointsy)
- [scrollSnapStop](akashaproject_design_system._internal_.Properties.md#scrollsnapstop)
- [scrollSnapType](akashaproject_design_system._internal_.Properties.md#scrollsnaptype)
- [scrollSnapTypeX](akashaproject_design_system._internal_.Properties.md#scrollsnaptypex)
- [scrollSnapTypeY](akashaproject_design_system._internal_.Properties.md#scrollsnaptypey)
- [scrollbarColor](akashaproject_design_system._internal_.Properties.md#scrollbarcolor)
- [scrollbarGutter](akashaproject_design_system._internal_.Properties.md#scrollbargutter)
- [scrollbarTrackColor](akashaproject_design_system._internal_.Properties.md#scrollbartrackcolor)
- [scrollbarWidth](akashaproject_design_system._internal_.Properties.md#scrollbarwidth)
- [shapeImageThreshold](akashaproject_design_system._internal_.Properties.md#shapeimagethreshold)
- [shapeMargin](akashaproject_design_system._internal_.Properties.md#shapemargin)
- [shapeOutside](akashaproject_design_system._internal_.Properties.md#shapeoutside)
- [shapeRendering](akashaproject_design_system._internal_.Properties.md#shaperendering)
- [stopColor](akashaproject_design_system._internal_.Properties.md#stopcolor)
- [stopOpacity](akashaproject_design_system._internal_.Properties.md#stopopacity)
- [stroke](akashaproject_design_system._internal_.Properties.md#stroke)
- [strokeDasharray](akashaproject_design_system._internal_.Properties.md#strokedasharray)
- [strokeDashoffset](akashaproject_design_system._internal_.Properties.md#strokedashoffset)
- [strokeLinecap](akashaproject_design_system._internal_.Properties.md#strokelinecap)
- [strokeLinejoin](akashaproject_design_system._internal_.Properties.md#strokelinejoin)
- [strokeMiterlimit](akashaproject_design_system._internal_.Properties.md#strokemiterlimit)
- [strokeOpacity](akashaproject_design_system._internal_.Properties.md#strokeopacity)
- [strokeWidth](akashaproject_design_system._internal_.Properties.md#strokewidth)
- [tabSize](akashaproject_design_system._internal_.Properties.md#tabsize)
- [tableLayout](akashaproject_design_system._internal_.Properties.md#tablelayout)
- [textAlign](akashaproject_design_system._internal_.Properties.md#textalign)
- [textAlignLast](akashaproject_design_system._internal_.Properties.md#textalignlast)
- [textAnchor](akashaproject_design_system._internal_.Properties.md#textanchor)
- [textCombineUpright](akashaproject_design_system._internal_.Properties.md#textcombineupright)
- [textDecoration](akashaproject_design_system._internal_.Properties.md#textdecoration)
- [textDecorationColor](akashaproject_design_system._internal_.Properties.md#textdecorationcolor)
- [textDecorationLine](akashaproject_design_system._internal_.Properties.md#textdecorationline)
- [textDecorationSkip](akashaproject_design_system._internal_.Properties.md#textdecorationskip)
- [textDecorationSkipInk](akashaproject_design_system._internal_.Properties.md#textdecorationskipink)
- [textDecorationStyle](akashaproject_design_system._internal_.Properties.md#textdecorationstyle)
- [textDecorationThickness](akashaproject_design_system._internal_.Properties.md#textdecorationthickness)
- [textDecorationWidth](akashaproject_design_system._internal_.Properties.md#textdecorationwidth)
- [textEmphasis](akashaproject_design_system._internal_.Properties.md#textemphasis)
- [textEmphasisColor](akashaproject_design_system._internal_.Properties.md#textemphasiscolor)
- [textEmphasisPosition](akashaproject_design_system._internal_.Properties.md#textemphasisposition)
- [textEmphasisStyle](akashaproject_design_system._internal_.Properties.md#textemphasisstyle)
- [textIndent](akashaproject_design_system._internal_.Properties.md#textindent)
- [textJustify](akashaproject_design_system._internal_.Properties.md#textjustify)
- [textOrientation](akashaproject_design_system._internal_.Properties.md#textorientation)
- [textOverflow](akashaproject_design_system._internal_.Properties.md#textoverflow)
- [textRendering](akashaproject_design_system._internal_.Properties.md#textrendering)
- [textShadow](akashaproject_design_system._internal_.Properties.md#textshadow)
- [textSizeAdjust](akashaproject_design_system._internal_.Properties.md#textsizeadjust)
- [textTransform](akashaproject_design_system._internal_.Properties.md#texttransform)
- [textUnderlineOffset](akashaproject_design_system._internal_.Properties.md#textunderlineoffset)
- [textUnderlinePosition](akashaproject_design_system._internal_.Properties.md#textunderlineposition)
- [top](akashaproject_design_system._internal_.Properties.md#top)
- [touchAction](akashaproject_design_system._internal_.Properties.md#touchaction)
- [transform](akashaproject_design_system._internal_.Properties.md#transform)
- [transformBox](akashaproject_design_system._internal_.Properties.md#transformbox)
- [transformOrigin](akashaproject_design_system._internal_.Properties.md#transformorigin)
- [transformStyle](akashaproject_design_system._internal_.Properties.md#transformstyle)
- [transition](akashaproject_design_system._internal_.Properties.md#transition)
- [transitionDelay](akashaproject_design_system._internal_.Properties.md#transitiondelay)
- [transitionDuration](akashaproject_design_system._internal_.Properties.md#transitionduration)
- [transitionProperty](akashaproject_design_system._internal_.Properties.md#transitionproperty)
- [transitionTimingFunction](akashaproject_design_system._internal_.Properties.md#transitiontimingfunction)
- [translate](akashaproject_design_system._internal_.Properties.md#translate)
- [unicodeBidi](akashaproject_design_system._internal_.Properties.md#unicodebidi)
- [userSelect](akashaproject_design_system._internal_.Properties.md#userselect)
- [vectorEffect](akashaproject_design_system._internal_.Properties.md#vectoreffect)
- [verticalAlign](akashaproject_design_system._internal_.Properties.md#verticalalign)
- [visibility](akashaproject_design_system._internal_.Properties.md#visibility)
- [whiteSpace](akashaproject_design_system._internal_.Properties.md#whitespace)
- [widows](akashaproject_design_system._internal_.Properties.md#widows)
- [width](akashaproject_design_system._internal_.Properties.md#width)
- [willChange](akashaproject_design_system._internal_.Properties.md#willchange)
- [wordBreak](akashaproject_design_system._internal_.Properties.md#wordbreak)
- [wordSpacing](akashaproject_design_system._internal_.Properties.md#wordspacing)
- [wordWrap](akashaproject_design_system._internal_.Properties.md#wordwrap)
- [writingMode](akashaproject_design_system._internal_.Properties.md#writingmode)
- [zIndex](akashaproject_design_system._internal_.Properties.md#zindex)
- [zoom](akashaproject_design_system._internal_.Properties.md#zoom)

## Properties

### KhtmlBoxAlign

• `Optional` **KhtmlBoxAlign**: [`BoxAlign`](../modules/akashaproject_design_system._internal_.md#boxalign)

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxAlign](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7976

___

### KhtmlBoxDirection

• `Optional` **KhtmlBoxDirection**: [`BoxDirection`](../modules/akashaproject_design_system._internal_.md#boxdirection)

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxDirection](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7986

___

### KhtmlBoxFlex

• `Optional` **KhtmlBoxFlex**: [`BoxFlex`](../modules/akashaproject_design_system._internal_.md#boxflex)

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxFlex](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7996

___

### KhtmlBoxFlexGroup

• `Optional` **KhtmlBoxFlexGroup**: [`BoxFlexGroup`](../modules/akashaproject_design_system._internal_.md#boxflexgroup)

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxFlexGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxflexgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8006

___

### KhtmlBoxLines

• `Optional` **KhtmlBoxLines**: [`BoxLines`](../modules/akashaproject_design_system._internal_.md#boxlines)

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxLines](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8016

___

### KhtmlBoxOrdinalGroup

• `Optional` **KhtmlBoxOrdinalGroup**: [`BoxOrdinalGroup`](../modules/akashaproject_design_system._internal_.md#boxordinalgroup)

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxordinalgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8026

___

### KhtmlBoxOrient

• `Optional` **KhtmlBoxOrient**: [`BoxOrient`](../modules/akashaproject_design_system._internal_.md#boxorient)

This is a property of the original CSS Flexible Box Layout Module draft, and has been replaced by a newer standard. See flexbox for information about the current standard.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxOrient](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8036

___

### KhtmlBoxPack

• `Optional` **KhtmlBoxPack**: [`BoxPack`](../modules/akashaproject_design_system._internal_.md#boxpack)

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlBoxPack](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlboxpack)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8046

___

### KhtmlLineBreak

• `Optional` **KhtmlLineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlLineBreak](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmllinebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8056

___

### KhtmlOpacity

• `Optional` **KhtmlOpacity**: [`Opacity`](../modules/akashaproject_design_system._internal_.md#opacity)

The **`opacity`** CSS property sets the opacity of an element. Opacity is the degree to which content behind an element is hidden, and is the opposite of transparency.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlOpacity](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmlopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8066

___

### KhtmlUserSelect

• `Optional` **KhtmlUserSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[KhtmlUserSelect](akashaproject_design_system._internal_.ObsoleteProperties.md#khtmluserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8076

___

### MozAnimation

• `Optional` **MozAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`TTime`\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimation](akashaproject_design_system._internal_.VendorProperties.md#mozanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7539

___

### MozAnimationDelay

• `Optional` **MozAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`TTime`\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationDelay](akashaproject_design_system._internal_.VendorProperties.md#mozanimationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5746

___

### MozAnimationDirection

• `Optional` **MozAnimationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationDirection](akashaproject_design_system._internal_.VendorProperties.md#mozanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5754

___

### MozAnimationDuration

• `Optional` **MozAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`TTime`\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationDuration](akashaproject_design_system._internal_.VendorProperties.md#mozanimationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5762

___

### MozAnimationFillMode

• `Optional` **MozAnimationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationFillMode](akashaproject_design_system._internal_.VendorProperties.md#mozanimationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5770

___

### MozAnimationIterationCount

• `Optional` **MozAnimationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationIterationCount](akashaproject_design_system._internal_.VendorProperties.md#mozanimationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5778

___

### MozAnimationName

• `Optional` **MozAnimationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationName](akashaproject_design_system._internal_.VendorProperties.md#mozanimationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5786

___

### MozAnimationPlayState

• `Optional` **MozAnimationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationPlayState](akashaproject_design_system._internal_.VendorProperties.md#mozanimationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5794

___

### MozAnimationTimingFunction

• `Optional` **MozAnimationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAnimationTimingFunction](akashaproject_design_system._internal_.VendorProperties.md#mozanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5802

___

### MozAppearance

• `Optional` **MozAppearance**: [`MozAppearance`](../modules/akashaproject_design_system._internal_.md#mozappearance)

The `**appearance**` CSS property is used to display an element using platform-native styling, based on the operating system's theme. The **`-moz-appearance`** and **`-webkit-appearance`** properties are non-standard versions of this property, used (respectively) by Gecko (Firefox) and by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support **`-webkit-appearance`**, for compatibility reasons.

**Syntax**: `none | button | button-arrow-down | button-arrow-next | button-arrow-previous | button-arrow-up | button-bevel | button-focus | caret | checkbox | checkbox-container | checkbox-label | checkmenuitem | dualbutton | groupbox | listbox | listitem | menuarrow | menubar | menucheckbox | menuimage | menuitem | menuitemtext | menulist | menulist-button | menulist-text | menulist-textfield | menupopup | menuradio | menuseparator | meterbar | meterchunk | progressbar | progressbar-vertical | progresschunk | progresschunk-vertical | radio | radio-container | radio-label | radiomenuitem | range | range-thumb | resizer | resizerpanel | scale-horizontal | scalethumbend | scalethumb-horizontal | scalethumbstart | scalethumbtick | scalethumb-vertical | scale-vertical | scrollbarbutton-down | scrollbarbutton-left | scrollbarbutton-right | scrollbarbutton-up | scrollbarthumb-horizontal | scrollbarthumb-vertical | scrollbartrack-horizontal | scrollbartrack-vertical | searchfield | separator | sheet | spinner | spinner-downbutton | spinner-textfield | spinner-upbutton | splitter | statusbar | statusbarpanel | tab | tabpanel | tabpanels | tab-scroll-arrow-back | tab-scroll-arrow-forward | textfield | textfield-multiline | toolbar | toolbarbutton | toolbarbutton-dropdown | toolbargripper | toolbox | tooltip | treeheader | treeheadercell | treeheadersortarrow | treeitem | treeline | treetwisty | treetwistyopen | treeview | -moz-mac-unified-toolbar | -moz-win-borderless-glass | -moz-win-browsertabbar-toolbox | -moz-win-communicationstext | -moz-win-communications-toolbox | -moz-win-exclude-glass | -moz-win-glass | -moz-win-mediatext | -moz-win-media-toolbox | -moz-window-button-box | -moz-window-button-box-maximized | -moz-window-button-close | -moz-window-button-maximize | -moz-window-button-minimize | -moz-window-button-restore | -moz-window-frame-bottom | -moz-window-frame-left | -moz-window-frame-right | -moz-window-titlebar | -moz-window-titlebar-maximized`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozAppearance](akashaproject_design_system._internal_.VendorProperties.md#mozappearance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5810

___

### MozBackfaceVisibility

• `Optional` **MozBackfaceVisibility**: [`BackfaceVisibility`](../modules/akashaproject_design_system._internal_.md#backfacevisibility)

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBackfaceVisibility](akashaproject_design_system._internal_.VendorProperties.md#mozbackfacevisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5818

___

### MozBackgroundClip

• `Optional` **MozBackgroundClip**: [`BackgroundClip`](../modules/akashaproject_design_system._internal_.md#backgroundclip)

The **`background-clip`** CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

**Syntax**: `<box>#`

**Initial value**: `border-box`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBackgroundClip](akashaproject_design_system._internal_.ObsoleteProperties.md#mozbackgroundclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8086

___

### MozBackgroundInlinePolicy

• `Optional` **MozBackgroundInlinePolicy**: [`BoxDecorationBreak`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreak)

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBackgroundInlinePolicy](akashaproject_design_system._internal_.ObsoleteProperties.md#mozbackgroundinlinepolicy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8096

___

### MozBackgroundOrigin

• `Optional` **MozBackgroundOrigin**: [`BackgroundOrigin`](../modules/akashaproject_design_system._internal_.md#backgroundorigin)

The **`background-origin`** CSS property sets the background's origin: from the border start, inside the border, or inside the padding.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBackgroundOrigin](akashaproject_design_system._internal_.ObsoleteProperties.md#mozbackgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8106

___

### MozBackgroundSize

• `Optional` **MozBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`TLength`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBackgroundSize](akashaproject_design_system._internal_.ObsoleteProperties.md#mozbackgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8116

___

### MozBinding

• `Optional` **MozBinding**: [`MozBinding`](../modules/akashaproject_design_system._internal_.md#mozbinding)

The **`-moz-binding`** CSS property is used by Mozilla-based applications to attach an XBL binding to a DOM element.

**Syntax**: `<url> | none`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBinding](akashaproject_design_system._internal_.ObsoleteProperties.md#mozbinding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8126

___

### MozBorderBottomColors

• `Optional` **MozBorderBottomColors**: [`MozBorderBottomColors`](../modules/akashaproject_design_system._internal_.md#mozborderbottomcolors)

In Mozilla applications like Firefox, the **`-moz-border-bottom-colors`** CSS property sets a list of colors for the bottom border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderBottomColors](akashaproject_design_system._internal_.VendorProperties.md#mozborderbottomcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5826

___

### MozBorderEndColor

• `Optional` **MozBorderEndColor**: [`BorderInlineEndColor`](../modules/akashaproject_design_system._internal_.md#borderinlineendcolor)

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderEndColor](akashaproject_design_system._internal_.VendorProperties.md#mozborderendcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5834

___

### MozBorderEndStyle

• `Optional` **MozBorderEndStyle**: [`BorderInlineEndStyle`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyle)

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderEndStyle](akashaproject_design_system._internal_.VendorProperties.md#mozborderendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5842

___

### MozBorderEndWidth

• `Optional` **MozBorderEndWidth**: [`BorderInlineEndWidth`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidth)<`TLength`\>

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderEndWidth](akashaproject_design_system._internal_.VendorProperties.md#mozborderendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5850

___

### MozBorderImage

• `Optional` **MozBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderImage](akashaproject_design_system._internal_.VendorProperties.md#mozborderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7545

___

### MozBorderLeftColors

• `Optional` **MozBorderLeftColors**: [`MozBorderLeftColors`](../modules/akashaproject_design_system._internal_.md#mozborderleftcolors)

In Mozilla applications like Firefox, the **`-moz-border-left-colors`** CSS property sets a list of colors for the left border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderLeftColors](akashaproject_design_system._internal_.VendorProperties.md#mozborderleftcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5858

___

### MozBorderRadius

• `Optional` **MozBorderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`TLength`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBorderRadius](akashaproject_design_system._internal_.ObsoleteProperties.md#mozborderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8134

___

### MozBorderRadiusBottomleft

• `Optional` **MozBorderRadiusBottomleft**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`TLength`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBorderRadiusBottomleft](akashaproject_design_system._internal_.ObsoleteProperties.md#mozborderradiusbottomleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8144

___

### MozBorderRadiusBottomright

• `Optional` **MozBorderRadiusBottomright**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`TLength`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBorderRadiusBottomright](akashaproject_design_system._internal_.ObsoleteProperties.md#mozborderradiusbottomright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8154

___

### MozBorderRadiusTopleft

• `Optional` **MozBorderRadiusTopleft**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`TLength`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBorderRadiusTopleft](akashaproject_design_system._internal_.ObsoleteProperties.md#mozborderradiustopleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8164

___

### MozBorderRadiusTopright

• `Optional` **MozBorderRadiusTopright**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`TLength`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBorderRadiusTopright](akashaproject_design_system._internal_.ObsoleteProperties.md#mozborderradiustopright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8174

___

### MozBorderRightColors

• `Optional` **MozBorderRightColors**: [`MozBorderRightColors`](../modules/akashaproject_design_system._internal_.md#mozborderrightcolors)

In Mozilla applications like Firefox, the **`-moz-border-right-colors`** CSS property sets a list of colors for the right border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderRightColors](akashaproject_design_system._internal_.VendorProperties.md#mozborderrightcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5866

___

### MozBorderStartColor

• `Optional` **MozBorderStartColor**: [`BorderInlineStartColor`](../modules/akashaproject_design_system._internal_.md#borderinlinestartcolor)

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderStartColor](akashaproject_design_system._internal_.VendorProperties.md#mozborderstartcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5874

___

### MozBorderStartStyle

• `Optional` **MozBorderStartStyle**: [`BorderInlineStartStyle`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyle)

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderStartStyle](akashaproject_design_system._internal_.VendorProperties.md#mozborderstartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5882

___

### MozBorderTopColors

• `Optional` **MozBorderTopColors**: [`MozBorderTopColors`](../modules/akashaproject_design_system._internal_.md#mozbordertopcolors)

In Mozilla applications like Firefox, the **`-moz-border-top-colors`** CSS property sets a list of colors for the top border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBorderTopColors](akashaproject_design_system._internal_.VendorProperties.md#mozbordertopcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5890

___

### MozBoxAlign

• `Optional` **MozBoxAlign**: [`BoxAlign`](../modules/akashaproject_design_system._internal_.md#boxalign)

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxAlign](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8184

___

### MozBoxDirection

• `Optional` **MozBoxDirection**: [`BoxDirection`](../modules/akashaproject_design_system._internal_.md#boxdirection)

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxDirection](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8194

___

### MozBoxFlex

• `Optional` **MozBoxFlex**: [`BoxFlex`](../modules/akashaproject_design_system._internal_.md#boxflex)

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxFlex](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8204

___

### MozBoxOrdinalGroup

• `Optional` **MozBoxOrdinalGroup**: [`BoxOrdinalGroup`](../modules/akashaproject_design_system._internal_.md#boxordinalgroup)

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxordinalgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8214

___

### MozBoxOrient

• `Optional` **MozBoxOrient**: [`BoxOrient`](../modules/akashaproject_design_system._internal_.md#boxorient)

This is a property of the original CSS Flexible Box Layout Module draft, and has been replaced by a newer standard. See flexbox for information about the current standard.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxOrient](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8224

___

### MozBoxPack

• `Optional` **MozBoxPack**: [`BoxPack`](../modules/akashaproject_design_system._internal_.md#boxpack)

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxPack](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxpack)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8234

___

### MozBoxShadow

• `Optional` **MozBoxShadow**: [`BoxShadow`](../modules/akashaproject_design_system._internal_.md#boxshadow)

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozBoxShadow](akashaproject_design_system._internal_.ObsoleteProperties.md#mozboxshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8244

___

### MozBoxSizing

• `Optional` **MozBoxSizing**: [`BoxSizing`](../modules/akashaproject_design_system._internal_.md#boxsizing)

The **`box-sizing`** CSS property sets how the total width and height of an element is calculated.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozBoxSizing](akashaproject_design_system._internal_.VendorProperties.md#mozboxsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5898

___

### MozColumnCount

• `Optional` **MozColumnCount**: [`ColumnCount`](../modules/akashaproject_design_system._internal_.md#columncount)

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnCount](akashaproject_design_system._internal_.VendorProperties.md#mozcolumncount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5906

___

### MozColumnFill

• `Optional` **MozColumnFill**: [`ColumnFill`](../modules/akashaproject_design_system._internal_.md#columnfill)

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnFill](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5914

___

### MozColumnGap

• `Optional` **MozColumnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`TLength`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnGap](akashaproject_design_system._internal_.VendorProperties.md#mozcolumngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5922

___

### MozColumnRule

• `Optional` **MozColumnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`TLength`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnRule](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7551

___

### MozColumnRuleColor

• `Optional` **MozColumnRuleColor**: [`ColumnRuleColor`](../modules/akashaproject_design_system._internal_.md#columnrulecolor)

The **`column-rule-color`** CSS property sets the color of the line drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnRuleColor](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnrulecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5930

___

### MozColumnRuleStyle

• `Optional` **MozColumnRuleStyle**: [`ColumnRuleStyle`](../modules/akashaproject_design_system._internal_.md#columnrulestyle)

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnRuleStyle](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5938

___

### MozColumnRuleWidth

• `Optional` **MozColumnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`TLength`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnRuleWidth](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnrulewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5946

___

### MozColumnWidth

• `Optional` **MozColumnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`TLength`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumnWidth](akashaproject_design_system._internal_.VendorProperties.md#mozcolumnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5954

___

### MozColumns

• `Optional` **MozColumns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`TLength`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozColumns](akashaproject_design_system._internal_.VendorProperties.md#mozcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7557

___

### MozContextProperties

• `Optional` **MozContextProperties**: [`MozContextProperties`](../modules/akashaproject_design_system._internal_.md#mozcontextproperties)

The `**-moz-context-properties**` property can be used within privileged contexts in Firefox to share the values of specified properties of the element with a child SVG image.

**Syntax**: `none | [ fill | fill-opacity | stroke | stroke-opacity ]#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozContextProperties](akashaproject_design_system._internal_.VendorProperties.md#mozcontextproperties)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5962

___

### MozFloatEdge

• `Optional` **MozFloatEdge**: [`MozFloatEdge`](../modules/akashaproject_design_system._internal_.md#mozfloatedge)

The non-standard **`-moz-float-edge`** CSS property specifies whether the height and width properties of the element include the margin, border, or padding thickness.

**Syntax**: `border-box | content-box | margin-box | padding-box`

**Initial value**: `content-box`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozFloatEdge](akashaproject_design_system._internal_.ObsoleteProperties.md#mozfloatedge)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8254

___

### MozFontFeatureSettings

• `Optional` **MozFontFeatureSettings**: [`FontFeatureSettings`](../modules/akashaproject_design_system._internal_.md#fontfeaturesettings)

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozFontFeatureSettings](akashaproject_design_system._internal_.VendorProperties.md#mozfontfeaturesettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5970

___

### MozFontLanguageOverride

• `Optional` **MozFontLanguageOverride**: [`FontLanguageOverride`](../modules/akashaproject_design_system._internal_.md#fontlanguageoverride)

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozFontLanguageOverride](akashaproject_design_system._internal_.VendorProperties.md#mozfontlanguageoverride)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5978

___

### MozForceBrokenImageIcon

• `Optional` **MozForceBrokenImageIcon**: [`MozForceBrokenImageIcon`](../modules/akashaproject_design_system._internal_.md#mozforcebrokenimageicon)

The **`-moz-force-broken-image-icon`** extended CSS property can be used to force the broken image icon to be shown even when a broken image has an `alt` attribute.

**Syntax**: `0 | 1`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozForceBrokenImageIcon](akashaproject_design_system._internal_.ObsoleteProperties.md#mozforcebrokenimageicon)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8264

___

### MozHyphens

• `Optional` **MozHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozHyphens](akashaproject_design_system._internal_.VendorProperties.md#mozhyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5986

___

### MozImageRegion

• `Optional` **MozImageRegion**: [`MozImageRegion`](../modules/akashaproject_design_system._internal_.md#mozimageregion)

For certain XUL elements and pseudo-elements that use an image from the `list-style-image` property, this property specifies a region of the image that is used in place of the whole image. This allows elements to use different pieces of the same image to improve performance.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozImageRegion](akashaproject_design_system._internal_.VendorProperties.md#mozimageregion)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5994

___

### MozMarginEnd

• `Optional` **MozMarginEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`TLength`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozMarginEnd](akashaproject_design_system._internal_.VendorProperties.md#mozmarginend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6002

___

### MozMarginStart

• `Optional` **MozMarginStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`TLength`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozMarginStart](akashaproject_design_system._internal_.VendorProperties.md#mozmarginstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6010

___

### MozOpacity

• `Optional` **MozOpacity**: [`Opacity`](../modules/akashaproject_design_system._internal_.md#opacity)

The **`opacity`** CSS property sets the opacity of an element. Opacity is the degree to which content behind an element is hidden, and is the opposite of transparency.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOpacity](akashaproject_design_system._internal_.ObsoleteProperties.md#mozopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8274

___

### MozOrient

• `Optional` **MozOrient**: [`MozOrient`](../modules/akashaproject_design_system._internal_.md#mozorient)

The **`-moz-orient`** CSS property specifies the orientation of the element to which it's applied.

**Syntax**: `inline | block | horizontal | vertical`

**Initial value**: `inline`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozOrient](akashaproject_design_system._internal_.VendorProperties.md#mozorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6018

___

### MozOsxFontSmoothing

• `Optional` **MozOsxFontSmoothing**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`TLength`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozOsxFontSmoothing](akashaproject_design_system._internal_.VendorProperties.md#mozosxfontsmoothing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6026

___

### MozOutline

• `Optional` **MozOutline**: [`Outline`](../modules/akashaproject_design_system._internal_.md#outline)<`TLength`\>

The **`outline`** CSS shorthand property set all the outline properties in a single declaration.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutline](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8282

___

### MozOutlineColor

• `Optional` **MozOutlineColor**: [`OutlineColor`](../modules/akashaproject_design_system._internal_.md#outlinecolor)

The **`outline-color`** CSS property sets the color of an element's outline.

**Syntax**: `<color> | invert`

**Initial value**: `invert`, for browsers supporting it, `currentColor` for the other

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineColor](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8292

___

### MozOutlineRadius

• `Optional` **MozOutlineRadius**: [`MozOutlineRadius`](../modules/akashaproject_design_system._internal_.md#mozoutlineradius)<`TLength`\>

In Mozilla applications like Firefox, the **`-moz-outline-radius`** CSS shorthand property can be used to give an element's `outline` rounded corners.

**Syntax**: `<outline-radius>{1,4} [ / <outline-radius>{1,4} ]?`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineRadius](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlineradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8300

___

### MozOutlineRadiusBottomleft

• `Optional` **MozOutlineRadiusBottomleft**: [`MozOutlineRadiusBottomleft`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleft)<`TLength`\>

In Mozilla applications, the **`-moz-outline-radius-bottomleft`** CSS property can be used to round the bottom-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlineradiusbottomleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8310

___

### MozOutlineRadiusBottomright

• `Optional` **MozOutlineRadiusBottomright**: [`MozOutlineRadiusBottomright`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomright)<`TLength`\>

In Mozilla applications, the **`-moz-outline-radius-bottomright`** CSS property can be used to round the bottom-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineRadiusBottomright](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlineradiusbottomright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8320

___

### MozOutlineRadiusTopleft

• `Optional` **MozOutlineRadiusTopleft**: [`MozOutlineRadiusTopleft`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleft)<`TLength`\>

In Mozilla applications, the **`-moz-outline-radius-topleft`** CSS property can be used to round the top-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineRadiusTopleft](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlineradiustopleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8330

___

### MozOutlineRadiusTopright

• `Optional` **MozOutlineRadiusTopright**: [`MozOutlineRadiusTopright`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopright)<`TLength`\>

In Mozilla applications, the **`-moz-outline-radius-topright`** CSS property can be used to round the top-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineRadiusTopright](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlineradiustopright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8340

___

### MozOutlineStyle

• `Optional` **MozOutlineStyle**: [`OutlineStyle`](../modules/akashaproject_design_system._internal_.md#outlinestyle)

The **`outline-style`** CSS property sets the style of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `auto | <'border-style'>`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineStyle](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8350

___

### MozOutlineWidth

• `Optional` **MozOutlineWidth**: [`OutlineWidth`](../modules/akashaproject_design_system._internal_.md#outlinewidth)<`TLength`\>

The CSS **`outline-width`** property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozOutlineWidth](akashaproject_design_system._internal_.ObsoleteProperties.md#mozoutlinewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8360

___

### MozPaddingEnd

• `Optional` **MozPaddingEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`TLength`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozPaddingEnd](akashaproject_design_system._internal_.VendorProperties.md#mozpaddingend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6034

___

### MozPaddingStart

• `Optional` **MozPaddingStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`TLength`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozPaddingStart](akashaproject_design_system._internal_.VendorProperties.md#mozpaddingstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6042

___

### MozPerspective

• `Optional` **MozPerspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`TLength`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozPerspective](akashaproject_design_system._internal_.VendorProperties.md#mozperspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6050

___

### MozPerspectiveOrigin

• `Optional` **MozPerspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`TLength`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozPerspectiveOrigin](akashaproject_design_system._internal_.VendorProperties.md#mozperspectiveorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6058

___

### MozStackSizing

• `Optional` **MozStackSizing**: [`MozStackSizing`](../modules/akashaproject_design_system._internal_.md#mozstacksizing)

**`-moz-stack-sizing`** is an extended CSS property. Normally, a `<xul:stack>` will change its size so that all of its child elements are completely visible. For example, moving a child of the stack far to the right will widen the stack so the child remains visible.

**Syntax**: `ignore | stretch-to-fit`

**Initial value**: `stretch-to-fit`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozStackSizing](akashaproject_design_system._internal_.VendorProperties.md#mozstacksizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6066

___

### MozTabSize

• `Optional` **MozTabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`TLength`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTabSize](akashaproject_design_system._internal_.VendorProperties.md#moztabsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6074

___

### MozTextAlignLast

• `Optional` **MozTextAlignLast**: [`TextAlignLast`](../modules/akashaproject_design_system._internal_.md#textalignlast)

The **`text-align-last`** CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

**Syntax**: `auto | start | end | left | right | center | justify`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozTextAlignLast](akashaproject_design_system._internal_.ObsoleteProperties.md#moztextalignlast)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8370

___

### MozTextBlink

• `Optional` **MozTextBlink**: [`MozTextBlink`](../modules/akashaproject_design_system._internal_.md#moztextblink)

The **`-moz-text-blink`** non-standard Mozilla CSS extension specifies the blink mode.

**Syntax**: `none | blink`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTextBlink](akashaproject_design_system._internal_.VendorProperties.md#moztextblink)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6082

___

### MozTextDecorationColor

• `Optional` **MozTextDecorationColor**: [`TextDecorationColor`](../modules/akashaproject_design_system._internal_.md#textdecorationcolor)

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozTextDecorationColor](akashaproject_design_system._internal_.ObsoleteProperties.md#moztextdecorationcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8380

___

### MozTextDecorationLine

• `Optional` **MozTextDecorationLine**: [`TextDecorationLine`](../modules/akashaproject_design_system._internal_.md#textdecorationline)

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozTextDecorationLine](akashaproject_design_system._internal_.ObsoleteProperties.md#moztextdecorationline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8390

___

### MozTextDecorationStyle

• `Optional` **MozTextDecorationStyle**: [`TextDecorationStyle`](../modules/akashaproject_design_system._internal_.md#textdecorationstyle)

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozTextDecorationStyle](akashaproject_design_system._internal_.ObsoleteProperties.md#moztextdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8400

___

### MozTextSizeAdjust

• `Optional` **MozTextSizeAdjust**: [`TextSizeAdjust`](../modules/akashaproject_design_system._internal_.md#textsizeadjust)

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTextSizeAdjust](akashaproject_design_system._internal_.VendorProperties.md#moztextsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6090

___

### MozTransformOrigin

• `Optional` **MozTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`TLength`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransformOrigin](akashaproject_design_system._internal_.VendorProperties.md#moztransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6098

___

### MozTransformStyle

• `Optional` **MozTransformStyle**: [`TransformStyle`](../modules/akashaproject_design_system._internal_.md#transformstyle)

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransformStyle](akashaproject_design_system._internal_.VendorProperties.md#moztransformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6106

___

### MozTransition

• `Optional` **MozTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`TTime`\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransition](akashaproject_design_system._internal_.VendorProperties.md#moztransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7563

___

### MozTransitionDelay

• `Optional` **MozTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`TTime`\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransitionDelay](akashaproject_design_system._internal_.VendorProperties.md#moztransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6114

___

### MozTransitionDuration

• `Optional` **MozTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`TTime`\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransitionDuration](akashaproject_design_system._internal_.VendorProperties.md#moztransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6122

___

### MozTransitionProperty

• `Optional` **MozTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransitionProperty](akashaproject_design_system._internal_.VendorProperties.md#moztransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6130

___

### MozTransitionTimingFunction

• `Optional` **MozTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozTransitionTimingFunction](akashaproject_design_system._internal_.VendorProperties.md#moztransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6138

___

### MozUserFocus

• `Optional` **MozUserFocus**: [`MozUserFocus`](../modules/akashaproject_design_system._internal_.md#mozuserfocus)

The **`-moz-user-focus`** CSS property is used to indicate whether an element can have the focus.

**Syntax**: `ignore | normal | select-after | select-before | select-menu | select-same | select-all | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozUserFocus](akashaproject_design_system._internal_.VendorProperties.md#mozuserfocus)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6146

___

### MozUserInput

• `Optional` **MozUserInput**: [`MozUserInput`](../modules/akashaproject_design_system._internal_.md#mozuserinput)

In Mozilla applications, **`-moz-user-input`** determines if an element will accept user input.

**Syntax**: `auto | none | enabled | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[MozUserInput](akashaproject_design_system._internal_.ObsoleteProperties.md#mozuserinput)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8410

___

### MozUserModify

• `Optional` **MozUserModify**: [`MozUserModify`](../modules/akashaproject_design_system._internal_.md#mozusermodify)

The **`user-modify`** property has no effect in Firefox. It was originally planned to determine whether or not the content of an element can be edited by a user.

**Syntax**: `read-only | read-write | write-only`

**Initial value**: `read-only`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozUserModify](akashaproject_design_system._internal_.VendorProperties.md#mozusermodify)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6154

___

### MozUserSelect

• `Optional` **MozUserSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozUserSelect](akashaproject_design_system._internal_.VendorProperties.md#mozuserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6162

___

### MozWindowDragging

• `Optional` **MozWindowDragging**: [`MozWindowDragging`](../modules/akashaproject_design_system._internal_.md#mozwindowdragging)

The **`-moz-window-dragging`** CSS property specifies whether a window is draggable or not. It only works in Chrome code, and only on Mac OS X.

**Syntax**: `drag | no-drag`

**Initial value**: `drag`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozWindowDragging](akashaproject_design_system._internal_.VendorProperties.md#mozwindowdragging)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6170

___

### MozWindowShadow

• `Optional` **MozWindowShadow**: [`MozWindowShadow`](../modules/akashaproject_design_system._internal_.md#mozwindowshadow)

The **`-moz-window-shadow`** CSS property specifies whether a window will have a shadow. It only works on Mac OS X.

**Syntax**: `default | menu | tooltip | sheet | none`

**Initial value**: `default`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[MozWindowShadow](akashaproject_design_system._internal_.VendorProperties.md#mozwindowshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6178

___

### OAnimation

• `Optional` **OAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`TTime`\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimation](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8438

___

### OAnimationDelay

• `Optional` **OAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`TTime`\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationDelay](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8448

___

### OAnimationDirection

• `Optional` **OAnimationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationDirection](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8458

___

### OAnimationDuration

• `Optional` **OAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`TTime`\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationDuration](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8468

___

### OAnimationFillMode

• `Optional` **OAnimationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationFillMode](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8478

___

### OAnimationIterationCount

• `Optional` **OAnimationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationIterationCount](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8488

___

### OAnimationName

• `Optional` **OAnimationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationName](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8498

___

### OAnimationPlayState

• `Optional` **OAnimationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationPlayState](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8508

___

### OAnimationTimingFunction

• `Optional` **OAnimationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OAnimationTimingFunction](akashaproject_design_system._internal_.ObsoleteProperties.md#oanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8518

___

### OBackgroundSize

• `Optional` **OBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`TLength`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OBackgroundSize](akashaproject_design_system._internal_.ObsoleteProperties.md#obackgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8528

___

### OBorderImage

• `Optional` **OBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OBorderImage](akashaproject_design_system._internal_.ObsoleteProperties.md#oborderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8536

___

### OObjectFit

• `Optional` **OObjectFit**: [`ObjectFit`](../modules/akashaproject_design_system._internal_.md#objectfit)

The **`object-fit`** CSS property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container.

**Syntax**: `fill | contain | cover | none | scale-down`

**Initial value**: `fill`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OObjectFit](akashaproject_design_system._internal_.ObsoleteProperties.md#oobjectfit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8546

___

### OObjectPosition

• `Optional` **OObjectPosition**: [`ObjectPosition`](../modules/akashaproject_design_system._internal_.md#objectposition)<`TLength`\>

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OObjectPosition](akashaproject_design_system._internal_.ObsoleteProperties.md#oobjectposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8556

___

### OTabSize

• `Optional` **OTabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`TLength`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTabSize](akashaproject_design_system._internal_.ObsoleteProperties.md#otabsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8566

___

### OTextOverflow

• `Optional` **OTextOverflow**: [`TextOverflow`](../modules/akashaproject_design_system._internal_.md#textoverflow)

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTextOverflow](akashaproject_design_system._internal_.ObsoleteProperties.md#otextoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8576

___

### OTransform

• `Optional` **OTransform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransform](akashaproject_design_system._internal_.ObsoleteProperties.md#otransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8586

___

### OTransformOrigin

• `Optional` **OTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`TLength`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransformOrigin](akashaproject_design_system._internal_.ObsoleteProperties.md#otransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8596

___

### OTransition

• `Optional` **OTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`TTime`\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransition](akashaproject_design_system._internal_.ObsoleteProperties.md#otransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8604

___

### OTransitionDelay

• `Optional` **OTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`TTime`\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransitionDelay](akashaproject_design_system._internal_.ObsoleteProperties.md#otransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8614

___

### OTransitionDuration

• `Optional` **OTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`TTime`\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransitionDuration](akashaproject_design_system._internal_.ObsoleteProperties.md#otransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8624

___

### OTransitionProperty

• `Optional` **OTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransitionProperty](akashaproject_design_system._internal_.ObsoleteProperties.md#otransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8634

___

### OTransitionTimingFunction

• `Optional` **OTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[OTransitionTimingFunction](akashaproject_design_system._internal_.ObsoleteProperties.md#otransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8644

___

### WebkitAlignContent

• `Optional` **WebkitAlignContent**: [`AlignContent`](../modules/akashaproject_design_system._internal_.md#aligncontent)

The CSS **`align-content`** property sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

**Syntax**: `normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position>`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAlignContent](akashaproject_design_system._internal_.VendorProperties.md#webkitaligncontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6682

___

### WebkitAlignItems

• `Optional` **WebkitAlignItems**: [`AlignItems`](../modules/akashaproject_design_system._internal_.md#alignitems)

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

**Syntax**: `normal | stretch | <baseline-position> | [ <overflow-position>? <self-position> ]`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAlignItems](akashaproject_design_system._internal_.VendorProperties.md#webkitalignitems)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6690

___

### WebkitAlignSelf

• `Optional` **WebkitAlignSelf**: [`AlignSelf`](../modules/akashaproject_design_system._internal_.md#alignself)

The **`align-self`** CSS property overrides a grid or flex item's `align-items` value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAlignSelf](akashaproject_design_system._internal_.VendorProperties.md#webkitalignself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6698

___

### WebkitAnimation

• `Optional` **WebkitAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`TTime`\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimation](akashaproject_design_system._internal_.VendorProperties.md#webkitanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7611

___

### WebkitAnimationDelay

• `Optional` **WebkitAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`TTime`\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationDelay](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6706

___

### WebkitAnimationDirection

• `Optional` **WebkitAnimationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationDirection](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6714

___

### WebkitAnimationDuration

• `Optional` **WebkitAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`TTime`\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationDuration](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6722

___

### WebkitAnimationFillMode

• `Optional` **WebkitAnimationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationFillMode](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6730

___

### WebkitAnimationIterationCount

• `Optional` **WebkitAnimationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationIterationCount](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6738

___

### WebkitAnimationName

• `Optional` **WebkitAnimationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationName](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6746

___

### WebkitAnimationPlayState

• `Optional` **WebkitAnimationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationPlayState](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6754

___

### WebkitAnimationTimingFunction

• `Optional` **WebkitAnimationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAnimationTimingFunction](akashaproject_design_system._internal_.VendorProperties.md#webkitanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6762

___

### WebkitAppearance

• `Optional` **WebkitAppearance**: [`WebkitAppearance`](../modules/akashaproject_design_system._internal_.md#webkitappearance)

The `**appearance**` CSS property is used to display an element using platform-native styling, based on the operating system's theme. The **`-moz-appearance`** and **`-webkit-appearance`** properties are non-standard versions of this property, used (respectively) by Gecko (Firefox) and by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support **`-webkit-appearance`**, for compatibility reasons.

**Syntax**: `none | button | button-bevel | caret | checkbox | default-button | inner-spin-button | listbox | listitem | media-controls-background | media-controls-fullscreen-background | media-current-time-display | media-enter-fullscreen-button | media-exit-fullscreen-button | media-fullscreen-button | media-mute-button | media-overlay-play-button | media-play-button | media-seek-back-button | media-seek-forward-button | media-slider | media-sliderthumb | media-time-remaining-display | media-toggle-closed-captions-button | media-volume-slider | media-volume-slider-container | media-volume-sliderthumb | menulist | menulist-button | menulist-text | menulist-textfield | meter | progress-bar | progress-bar-value | push-button | radio | searchfield | searchfield-cancel-button | searchfield-decoration | searchfield-results-button | searchfield-results-decoration | slider-horizontal | slider-vertical | sliderthumb-horizontal | sliderthumb-vertical | square-button | textarea | textfield | -apple-pay-button`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitAppearance](akashaproject_design_system._internal_.VendorProperties.md#webkitappearance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6770

___

### WebkitBackdropFilter

• `Optional` **WebkitBackdropFilter**: [`BackdropFilter`](../modules/akashaproject_design_system._internal_.md#backdropfilter)

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBackdropFilter](akashaproject_design_system._internal_.VendorProperties.md#webkitbackdropfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6778

___

### WebkitBackfaceVisibility

• `Optional` **WebkitBackfaceVisibility**: [`BackfaceVisibility`](../modules/akashaproject_design_system._internal_.md#backfacevisibility)

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBackfaceVisibility](akashaproject_design_system._internal_.VendorProperties.md#webkitbackfacevisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6786

___

### WebkitBackgroundClip

• `Optional` **WebkitBackgroundClip**: [`BackgroundClip`](../modules/akashaproject_design_system._internal_.md#backgroundclip)

The **`background-clip`** CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

**Syntax**: `<box>#`

**Initial value**: `border-box`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBackgroundClip](akashaproject_design_system._internal_.VendorProperties.md#webkitbackgroundclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6794

___

### WebkitBackgroundOrigin

• `Optional` **WebkitBackgroundOrigin**: [`BackgroundOrigin`](../modules/akashaproject_design_system._internal_.md#backgroundorigin)

The **`background-origin`** CSS property sets the background's origin: from the border start, inside the border, or inside the padding.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBackgroundOrigin](akashaproject_design_system._internal_.VendorProperties.md#webkitbackgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6802

___

### WebkitBackgroundSize

• `Optional` **WebkitBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`TLength`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBackgroundSize](akashaproject_design_system._internal_.VendorProperties.md#webkitbackgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6810

___

### WebkitBorderBefore

• `Optional` **WebkitBorderBefore**: [`WebkitBorderBefore`](../modules/akashaproject_design_system._internal_.md#webkitborderbefore)<`TLength`\>

The **`-webkit-border-before`** CSS property is a shorthand property for setting the individual logical block start border property values in a single place in the style sheet.

**Syntax**: `<'border-width'> || <'border-style'> || <color>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBefore](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbefore)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7617

___

### WebkitBorderBeforeColor

• `Optional` **WebkitBorderBeforeColor**: [`WebkitBorderBeforeColor`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforecolor)

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBeforeColor](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbeforecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6816

___

### WebkitBorderBeforeStyle

• `Optional` **WebkitBorderBeforeStyle**: [`WebkitBorderBeforeStyle`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforestyle)

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBeforeStyle](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbeforestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6822

___

### WebkitBorderBeforeWidth

• `Optional` **WebkitBorderBeforeWidth**: [`WebkitBorderBeforeWidth`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidth)<`TLength`\>

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBeforeWidth](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbeforewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6828

___

### WebkitBorderBottomLeftRadius

• `Optional` **WebkitBorderBottomLeftRadius**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`TLength`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbottomleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6836

___

### WebkitBorderBottomRightRadius

• `Optional` **WebkitBorderBottomRightRadius**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`TLength`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.VendorProperties.md#webkitborderbottomrightradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6844

___

### WebkitBorderImage

• `Optional` **WebkitBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderImage](akashaproject_design_system._internal_.VendorProperties.md#webkitborderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7623

___

### WebkitBorderImageSlice

• `Optional` **WebkitBorderImageSlice**: [`BorderImageSlice`](../modules/akashaproject_design_system._internal_.md#borderimageslice)

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderImageSlice](akashaproject_design_system._internal_.VendorProperties.md#webkitborderimageslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6852

___

### WebkitBorderRadius

• `Optional` **WebkitBorderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`TLength`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderRadius](akashaproject_design_system._internal_.VendorProperties.md#webkitborderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7629

___

### WebkitBorderTopLeftRadius

• `Optional` **WebkitBorderTopLeftRadius**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`TLength`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.VendorProperties.md#webkitbordertopleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6860

___

### WebkitBorderTopRightRadius

• `Optional` **WebkitBorderTopRightRadius**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`TLength`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBorderTopRightRadius](akashaproject_design_system._internal_.VendorProperties.md#webkitbordertoprightradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6868

___

### WebkitBoxAlign

• `Optional` **WebkitBoxAlign**: [`BoxAlign`](../modules/akashaproject_design_system._internal_.md#boxalign)

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxAlign](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8654

___

### WebkitBoxDecorationBreak

• `Optional` **WebkitBoxDecorationBreak**: [`BoxDecorationBreak`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreak)

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBoxDecorationBreak](akashaproject_design_system._internal_.VendorProperties.md#webkitboxdecorationbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6876

___

### WebkitBoxDirection

• `Optional` **WebkitBoxDirection**: [`BoxDirection`](../modules/akashaproject_design_system._internal_.md#boxdirection)

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxDirection](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8664

___

### WebkitBoxFlex

• `Optional` **WebkitBoxFlex**: [`BoxFlex`](../modules/akashaproject_design_system._internal_.md#boxflex)

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxFlex](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8674

___

### WebkitBoxFlexGroup

• `Optional` **WebkitBoxFlexGroup**: [`BoxFlexGroup`](../modules/akashaproject_design_system._internal_.md#boxflexgroup)

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxFlexGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxflexgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8684

___

### WebkitBoxLines

• `Optional` **WebkitBoxLines**: [`BoxLines`](../modules/akashaproject_design_system._internal_.md#boxlines)

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxLines](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8694

___

### WebkitBoxOrdinalGroup

• `Optional` **WebkitBoxOrdinalGroup**: [`BoxOrdinalGroup`](../modules/akashaproject_design_system._internal_.md#boxordinalgroup)

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxordinalgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8704

___

### WebkitBoxOrient

• `Optional` **WebkitBoxOrient**: [`BoxOrient`](../modules/akashaproject_design_system._internal_.md#boxorient)

This is a property of the original CSS Flexible Box Layout Module draft, and has been replaced by a newer standard. See flexbox for information about the current standard.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxOrient](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8714

___

### WebkitBoxPack

• `Optional` **WebkitBoxPack**: [`BoxPack`](../modules/akashaproject_design_system._internal_.md#boxpack)

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitBoxPack](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitboxpack)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8724

___

### WebkitBoxReflect

• `Optional` **WebkitBoxReflect**: [`WebkitBoxReflect`](../modules/akashaproject_design_system._internal_.md#webkitboxreflect)<`TLength`\>

The **`-webkit-box-reflect`** CSS property lets you reflect the content of an element in one specific direction.

**Syntax**: `[ above | below | right | left ]? <length>? <image>?`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBoxReflect](akashaproject_design_system._internal_.VendorProperties.md#webkitboxreflect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6884

___

### WebkitBoxShadow

• `Optional` **WebkitBoxShadow**: [`BoxShadow`](../modules/akashaproject_design_system._internal_.md#boxshadow)

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBoxShadow](akashaproject_design_system._internal_.VendorProperties.md#webkitboxshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6892

___

### WebkitBoxSizing

• `Optional` **WebkitBoxSizing**: [`BoxSizing`](../modules/akashaproject_design_system._internal_.md#boxsizing)

The **`box-sizing`** CSS property sets how the total width and height of an element is calculated.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitBoxSizing](akashaproject_design_system._internal_.VendorProperties.md#webkitboxsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6900

___

### WebkitClipPath

• `Optional` **WebkitClipPath**: [`ClipPath`](../modules/akashaproject_design_system._internal_.md#clippath)

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitClipPath](akashaproject_design_system._internal_.VendorProperties.md#webkitclippath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6908

___

### WebkitColumnCount

• `Optional` **WebkitColumnCount**: [`ColumnCount`](../modules/akashaproject_design_system._internal_.md#columncount)

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnCount](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumncount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6916

___

### WebkitColumnFill

• `Optional` **WebkitColumnFill**: [`ColumnFill`](../modules/akashaproject_design_system._internal_.md#columnfill)

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnFill](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6924

___

### WebkitColumnGap

• `Optional` **WebkitColumnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`TLength`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnGap](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6932

___

### WebkitColumnRule

• `Optional` **WebkitColumnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`TLength`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnRule](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7635

___

### WebkitColumnRuleColor

• `Optional` **WebkitColumnRuleColor**: [`ColumnRuleColor`](../modules/akashaproject_design_system._internal_.md#columnrulecolor)

The **`column-rule-color`** CSS property sets the color of the line drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnRuleColor](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnrulecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6940

___

### WebkitColumnRuleStyle

• `Optional` **WebkitColumnRuleStyle**: [`ColumnRuleStyle`](../modules/akashaproject_design_system._internal_.md#columnrulestyle)

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnRuleStyle](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6948

___

### WebkitColumnRuleWidth

• `Optional` **WebkitColumnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`TLength`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnRuleWidth](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnrulewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6956

___

### WebkitColumnSpan

• `Optional` **WebkitColumnSpan**: [`ColumnSpan`](../modules/akashaproject_design_system._internal_.md#columnspan)

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnSpan](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnspan)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6964

___

### WebkitColumnWidth

• `Optional` **WebkitColumnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`TLength`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumnWidth](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6972

___

### WebkitColumns

• `Optional` **WebkitColumns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`TLength`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitColumns](akashaproject_design_system._internal_.VendorProperties.md#webkitcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7641

___

### WebkitFilter

• `Optional` **WebkitFilter**: [`Filter`](../modules/akashaproject_design_system._internal_.md#filter)

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFilter](akashaproject_design_system._internal_.VendorProperties.md#webkitfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6980

___

### WebkitFlex

• `Optional` **WebkitFlex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`TLength`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlex](akashaproject_design_system._internal_.VendorProperties.md#webkitflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7647

___

### WebkitFlexBasis

• `Optional` **WebkitFlexBasis**: [`FlexBasis`](../modules/akashaproject_design_system._internal_.md#flexbasis)<`TLength`\>

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexBasis](akashaproject_design_system._internal_.VendorProperties.md#webkitflexbasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6988

___

### WebkitFlexDirection

• `Optional` **WebkitFlexDirection**: [`FlexDirection`](../modules/akashaproject_design_system._internal_.md#flexdirection)

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexDirection](akashaproject_design_system._internal_.VendorProperties.md#webkitflexdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6996

___

### WebkitFlexFlow

• `Optional` **WebkitFlexFlow**: [`FlexFlow`](../modules/akashaproject_design_system._internal_.md#flexflow)

The **`flex-flow`** CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexFlow](akashaproject_design_system._internal_.VendorProperties.md#webkitflexflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7653

___

### WebkitFlexGrow

• `Optional` **WebkitFlexGrow**: [`FlexGrow`](../modules/akashaproject_design_system._internal_.md#flexgrow)

The **`flex-grow`** CSS property sets the flex grow factor of a flex item main size.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexGrow](akashaproject_design_system._internal_.VendorProperties.md#webkitflexgrow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7004

___

### WebkitFlexShrink

• `Optional` **WebkitFlexShrink**: [`FlexShrink`](../modules/akashaproject_design_system._internal_.md#flexshrink)

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexShrink](akashaproject_design_system._internal_.VendorProperties.md#webkitflexshrink)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7012

___

### WebkitFlexWrap

• `Optional` **WebkitFlexWrap**: [`FlexWrap`](../modules/akashaproject_design_system._internal_.md#flexwrap)

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFlexWrap](akashaproject_design_system._internal_.VendorProperties.md#webkitflexwrap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7020

___

### WebkitFontFeatureSettings

• `Optional` **WebkitFontFeatureSettings**: [`FontFeatureSettings`](../modules/akashaproject_design_system._internal_.md#fontfeaturesettings)

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFontFeatureSettings](akashaproject_design_system._internal_.VendorProperties.md#webkitfontfeaturesettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7028

___

### WebkitFontKerning

• `Optional` **WebkitFontKerning**: [`FontKerning`](../modules/akashaproject_design_system._internal_.md#fontkerning)

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFontKerning](akashaproject_design_system._internal_.VendorProperties.md#webkitfontkerning)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7036

___

### WebkitFontSmoothing

• `Optional` **WebkitFontSmoothing**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`TLength`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFontSmoothing](akashaproject_design_system._internal_.VendorProperties.md#webkitfontsmoothing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7044

___

### WebkitFontVariantLigatures

• `Optional` **WebkitFontVariantLigatures**: [`FontVariantLigatures`](../modules/akashaproject_design_system._internal_.md#fontvariantligatures)

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitFontVariantLigatures](akashaproject_design_system._internal_.VendorProperties.md#webkitfontvariantligatures)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7052

___

### WebkitHyphens

• `Optional` **WebkitHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitHyphens](akashaproject_design_system._internal_.VendorProperties.md#webkithyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7060

___

### WebkitJustifyContent

• `Optional` **WebkitJustifyContent**: [`JustifyContent`](../modules/akashaproject_design_system._internal_.md#justifycontent)

The CSS **`justify-content`** property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

**Syntax**: `normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ]`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitJustifyContent](akashaproject_design_system._internal_.VendorProperties.md#webkitjustifycontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7068

___

### WebkitLineBreak

• `Optional` **WebkitLineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitLineBreak](akashaproject_design_system._internal_.VendorProperties.md#webkitlinebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7076

___

### WebkitLineClamp

• `Optional` **WebkitLineClamp**: [`WebkitLineClamp`](../modules/akashaproject_design_system._internal_.md#webkitlineclamp)

The **`-webkit-line-clamp`** CSS property allows limiting of the contents of a block container to the specified number of lines.

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitLineClamp](akashaproject_design_system._internal_.VendorProperties.md#webkitlineclamp)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7084

___

### WebkitMarginEnd

• `Optional` **WebkitMarginEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`TLength`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMarginEnd](akashaproject_design_system._internal_.VendorProperties.md#webkitmarginend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7092

___

### WebkitMarginStart

• `Optional` **WebkitMarginStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`TLength`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMarginStart](akashaproject_design_system._internal_.VendorProperties.md#webkitmarginstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7100

___

### WebkitMask

• `Optional` **WebkitMask**: [`WebkitMask`](../modules/akashaproject_design_system._internal_.md#webkitmask)<`TLength`\>

The **`mask`** CSS shorthand property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `[ <mask-reference> || <position> [ / <bg-size> ]? || <repeat-style> || [ <box> | border | padding | content | text ] || [ <box> | border | padding | content ] ]#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMask](akashaproject_design_system._internal_.VendorProperties.md#webkitmask)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7659

___

### WebkitMaskAttachment

• `Optional` **WebkitMaskAttachment**: [`WebkitMaskAttachment`](../modules/akashaproject_design_system._internal_.md#webkitmaskattachment)

If a `-webkit-mask-image` is specified, `-webkit-mask-attachment` determines whether the mask image's position is fixed within the viewport, or scrolls along with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskAttachment](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskattachment)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7108

___

### WebkitMaskBoxImage

• `Optional` **WebkitMaskBoxImage**: [`MaskBorder`](../modules/akashaproject_design_system._internal_.md#maskborder)

The **`mask-border`** CSS shorthand property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImage](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7665

___

### WebkitMaskBoxImageOutset

• `Optional` **WebkitMaskBoxImageOutset**: [`MaskBorderOutset`](../modules/akashaproject_design_system._internal_.md#maskborderoutset)<`TLength`\>

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximageoutset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7116

___

### WebkitMaskBoxImageRepeat

• `Optional` **WebkitMaskBoxImageRepeat**: [`MaskBorderRepeat`](../modules/akashaproject_design_system._internal_.md#maskborderrepeat)

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximagerepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7124

___

### WebkitMaskBoxImageSlice

• `Optional` **WebkitMaskBoxImageSlice**: [`MaskBorderSlice`](../modules/akashaproject_design_system._internal_.md#maskborderslice)

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximageslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7132

___

### WebkitMaskBoxImageSource

• `Optional` **WebkitMaskBoxImageSource**: [`MaskBorderSource`](../modules/akashaproject_design_system._internal_.md#maskbordersource)

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImageSource](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximagesource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7140

___

### WebkitMaskBoxImageWidth

• `Optional` **WebkitMaskBoxImageWidth**: [`MaskBorderWidth`](../modules/akashaproject_design_system._internal_.md#maskborderwidth)<`TLength`\>

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskboximagewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7148

___

### WebkitMaskClip

• `Optional` **WebkitMaskClip**: [`WebkitMaskClip`](../modules/akashaproject_design_system._internal_.md#webkitmaskclip)

The **`mask-clip`** CSS property determines the area which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <box> | border | padding | content | text ]#`

**Initial value**: `border`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskClip](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7156

___

### WebkitMaskComposite

• `Optional` **WebkitMaskComposite**: [`WebkitMaskComposite`](../modules/akashaproject_design_system._internal_.md#webkitmaskcomposite)

The **`-webkit-mask-composite`** property specifies the manner in which multiple mask images applied to the same element are composited with one another. Mask images are composited in the opposite order that they are declared with the `-webkit-mask-image` property.

**Syntax**: `<composite-style>#`

**Initial value**: `source-over`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskComposite](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskcomposite)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7164

___

### WebkitMaskImage

• `Optional` **WebkitMaskImage**: [`WebkitMaskImage`](../modules/akashaproject_design_system._internal_.md#webkitmaskimage)

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskImage](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7172

___

### WebkitMaskOrigin

• `Optional` **WebkitMaskOrigin**: [`WebkitMaskOrigin`](../modules/akashaproject_design_system._internal_.md#webkitmaskorigin)

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `[ <box> | border | padding | content ]#`

**Initial value**: `padding`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskOrigin](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7180

___

### WebkitMaskPosition

• `Optional` **WebkitMaskPosition**: [`WebkitMaskPosition`](../modules/akashaproject_design_system._internal_.md#webkitmaskposition)<`TLength`\>

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `0% 0%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskPosition](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7188

___

### WebkitMaskPositionX

• `Optional` **WebkitMaskPositionX**: [`WebkitMaskPositionX`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionx)<`TLength`\>

The `-webkit-mask-position-x` CSS property sets the initial horizontal position of a mask image.

**Syntax**: `[ <length-percentage> | left | center | right ]#`

**Initial value**: `0%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskPositionX](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskpositionx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7196

___

### WebkitMaskPositionY

• `Optional` **WebkitMaskPositionY**: [`WebkitMaskPositionY`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositiony)<`TLength`\>

The `-webkit-mask-position-y` CSS property sets the initial vertical position of a mask image.

**Syntax**: `[ <length-percentage> | top | center | bottom ]#`

**Initial value**: `0%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskPositionY](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskpositiony)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7204

___

### WebkitMaskRepeat

• `Optional` **WebkitMaskRepeat**: [`WebkitMaskRepeat`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeat)

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskRepeat](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7212

___

### WebkitMaskRepeatX

• `Optional` **WebkitMaskRepeatX**: [`WebkitMaskRepeatX`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatx)

The `-webkit-mask-repeat-x` property specifies whether and how a mask image is repeated (tiled) horizontally.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskRepeatX](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskrepeatx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7220

___

### WebkitMaskRepeatY

• `Optional` **WebkitMaskRepeatY**: [`WebkitMaskRepeatY`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeaty)

The `-webkit-mask-repeat-y` property sets whether and how a mask image is repeated (tiled) vertically.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskRepeatY](akashaproject_design_system._internal_.VendorProperties.md#webkitmaskrepeaty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7228

___

### WebkitMaskSize

• `Optional` **WebkitMaskSize**: [`WebkitMaskSize`](../modules/akashaproject_design_system._internal_.md#webkitmasksize)<`TLength`\>

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaskSize](akashaproject_design_system._internal_.VendorProperties.md#webkitmasksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7236

___

### WebkitMaxInlineSize

• `Optional` **WebkitMaxInlineSize**: [`MaxInlineSize`](../modules/akashaproject_design_system._internal_.md#maxinlinesize)<`TLength`\>

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block, depending on its writing mode. It corresponds to either the `max-width` or the `max-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitMaxInlineSize](akashaproject_design_system._internal_.VendorProperties.md#webkitmaxinlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7244

___

### WebkitOrder

• `Optional` **WebkitOrder**: [`Order`](../modules/akashaproject_design_system._internal_.md#order)

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitOrder](akashaproject_design_system._internal_.VendorProperties.md#webkitorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7252

___

### WebkitOverflowScrolling

• `Optional` **WebkitOverflowScrolling**: [`WebkitOverflowScrolling`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrolling)

The `-webkit-overflow-scrolling` CSS property controls whether or not touch devices use momentum-based scrolling for a given element.

**Syntax**: `auto | touch`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitOverflowScrolling](akashaproject_design_system._internal_.VendorProperties.md#webkitoverflowscrolling)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7260

___

### WebkitPaddingEnd

• `Optional` **WebkitPaddingEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`TLength`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitPaddingEnd](akashaproject_design_system._internal_.VendorProperties.md#webkitpaddingend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7268

___

### WebkitPaddingStart

• `Optional` **WebkitPaddingStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`TLength`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitPaddingStart](akashaproject_design_system._internal_.VendorProperties.md#webkitpaddingstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7276

___

### WebkitPerspective

• `Optional` **WebkitPerspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`TLength`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitPerspective](akashaproject_design_system._internal_.VendorProperties.md#webkitperspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7284

___

### WebkitPerspectiveOrigin

• `Optional` **WebkitPerspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`TLength`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitPerspectiveOrigin](akashaproject_design_system._internal_.VendorProperties.md#webkitperspectiveorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7292

___

### WebkitPrintColorAdjust

• `Optional` **WebkitPrintColorAdjust**: [`ColorAdjust`](../modules/akashaproject_design_system._internal_.md#coloradjust)

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitPrintColorAdjust](akashaproject_design_system._internal_.VendorProperties.md#webkitprintcoloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7300

___

### WebkitRubyPosition

• `Optional` **WebkitRubyPosition**: [`RubyPosition`](../modules/akashaproject_design_system._internal_.md#rubyposition)

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitRubyPosition](akashaproject_design_system._internal_.VendorProperties.md#webkitrubyposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7308

___

### WebkitScrollSnapPointsX

• `Optional` **WebkitScrollSnapPointsX**: [`ScrollSnapPointsX`](../modules/akashaproject_design_system._internal_.md#scrollsnappointsx)

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitScrollSnapPointsX](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitscrollsnappointsx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8734

___

### WebkitScrollSnapPointsY

• `Optional` **WebkitScrollSnapPointsY**: [`ScrollSnapPointsY`](../modules/akashaproject_design_system._internal_.md#scrollsnappointsy)

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[WebkitScrollSnapPointsY](akashaproject_design_system._internal_.ObsoleteProperties.md#webkitscrollsnappointsy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8744

___

### WebkitScrollSnapType

• `Optional` **WebkitScrollSnapType**: [`ScrollSnapType`](../modules/akashaproject_design_system._internal_.md#scrollsnaptype)

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitScrollSnapType](akashaproject_design_system._internal_.VendorProperties.md#webkitscrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7316

___

### WebkitShapeMargin

• `Optional` **WebkitShapeMargin**: [`ShapeMargin`](../modules/akashaproject_design_system._internal_.md#shapemargin)<`TLength`\>

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitShapeMargin](akashaproject_design_system._internal_.VendorProperties.md#webkitshapemargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7324

___

### WebkitTapHighlightColor

• `Optional` **WebkitTapHighlightColor**: [`WebkitTapHighlightColor`](../modules/akashaproject_design_system._internal_.md#webkittaphighlightcolor)

**`-webkit-tap-highlight-color`** is a non-standard CSS property that sets the color of the highlight that appears over a link while it's being tapped. The highlighting indicates to the user that their tap is being successfully recognized, and indicates which element they're tapping on.

**Syntax**: `<color>`

**Initial value**: `black`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTapHighlightColor](akashaproject_design_system._internal_.VendorProperties.md#webkittaphighlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7332

___

### WebkitTextCombine

• `Optional` **WebkitTextCombine**: [`TextCombineUpright`](../modules/akashaproject_design_system._internal_.md#textcombineupright)

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextCombine](akashaproject_design_system._internal_.VendorProperties.md#webkittextcombine)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7340

___

### WebkitTextDecorationColor

• `Optional` **WebkitTextDecorationColor**: [`TextDecorationColor`](../modules/akashaproject_design_system._internal_.md#textdecorationcolor)

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextDecorationColor](akashaproject_design_system._internal_.VendorProperties.md#webkittextdecorationcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7348

___

### WebkitTextDecorationLine

• `Optional` **WebkitTextDecorationLine**: [`TextDecorationLine`](../modules/akashaproject_design_system._internal_.md#textdecorationline)

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextDecorationLine](akashaproject_design_system._internal_.VendorProperties.md#webkittextdecorationline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7356

___

### WebkitTextDecorationSkip

• `Optional` **WebkitTextDecorationSkip**: [`TextDecorationSkip`](../modules/akashaproject_design_system._internal_.md#textdecorationskip)

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextDecorationSkip](akashaproject_design_system._internal_.VendorProperties.md#webkittextdecorationskip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7364

___

### WebkitTextDecorationStyle

• `Optional` **WebkitTextDecorationStyle**: [`TextDecorationStyle`](../modules/akashaproject_design_system._internal_.md#textdecorationstyle)

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextDecorationStyle](akashaproject_design_system._internal_.VendorProperties.md#webkittextdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7372

___

### WebkitTextEmphasis

• `Optional` **WebkitTextEmphasis**: [`TextEmphasis`](../modules/akashaproject_design_system._internal_.md#textemphasis)

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextEmphasis](akashaproject_design_system._internal_.VendorProperties.md#webkittextemphasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7671

___

### WebkitTextEmphasisColor

• `Optional` **WebkitTextEmphasisColor**: [`TextEmphasisColor`](../modules/akashaproject_design_system._internal_.md#textemphasiscolor)

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextEmphasisColor](akashaproject_design_system._internal_.VendorProperties.md#webkittextemphasiscolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7380

___

### WebkitTextEmphasisPosition

• `Optional` **WebkitTextEmphasisPosition**: [`TextEmphasisPosition`](../modules/akashaproject_design_system._internal_.md#textemphasisposition)

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextEmphasisPosition](akashaproject_design_system._internal_.VendorProperties.md#webkittextemphasisposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7388

___

### WebkitTextEmphasisStyle

• `Optional` **WebkitTextEmphasisStyle**: [`TextEmphasisStyle`](../modules/akashaproject_design_system._internal_.md#textemphasisstyle)

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextEmphasisStyle](akashaproject_design_system._internal_.VendorProperties.md#webkittextemphasisstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7396

___

### WebkitTextFillColor

• `Optional` **WebkitTextFillColor**: [`WebkitTextFillColor`](../modules/akashaproject_design_system._internal_.md#webkittextfillcolor)

The **`-webkit-text-fill-color`** CSS property specifies the fill color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextFillColor](akashaproject_design_system._internal_.VendorProperties.md#webkittextfillcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7404

___

### WebkitTextOrientation

• `Optional` **WebkitTextOrientation**: [`TextOrientation`](../modules/akashaproject_design_system._internal_.md#textorientation)

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextOrientation](akashaproject_design_system._internal_.VendorProperties.md#webkittextorientation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7412

___

### WebkitTextSizeAdjust

• `Optional` **WebkitTextSizeAdjust**: [`TextSizeAdjust`](../modules/akashaproject_design_system._internal_.md#textsizeadjust)

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextSizeAdjust](akashaproject_design_system._internal_.VendorProperties.md#webkittextsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7420

___

### WebkitTextStroke

• `Optional` **WebkitTextStroke**: [`WebkitTextStroke`](../modules/akashaproject_design_system._internal_.md#webkittextstroke)<`TLength`\>

The **`-webkit-text-stroke`** CSS property specifies the width and color of strokes for text characters. This is a shorthand property for the longhand properties `-webkit-text-stroke-width` and `-webkit-text-stroke-color`.

**Syntax**: `<length> || <color>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextStroke](akashaproject_design_system._internal_.VendorProperties.md#webkittextstroke)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7677

___

### WebkitTextStrokeColor

• `Optional` **WebkitTextStrokeColor**: [`WebkitTextStrokeColor`](../modules/akashaproject_design_system._internal_.md#webkittextstrokecolor)

The **`-webkit-text-stroke-color`** CSS property specifies the stroke color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextStrokeColor](akashaproject_design_system._internal_.VendorProperties.md#webkittextstrokecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7428

___

### WebkitTextStrokeWidth

• `Optional` **WebkitTextStrokeWidth**: [`WebkitTextStrokeWidth`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidth)<`TLength`\>

The **`-webkit-text-stroke-width`** CSS property specifies the width of the stroke for text.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextStrokeWidth](akashaproject_design_system._internal_.VendorProperties.md#webkittextstrokewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7436

___

### WebkitTextUnderlinePosition

• `Optional` **WebkitTextUnderlinePosition**: [`TextUnderlinePosition`](../modules/akashaproject_design_system._internal_.md#textunderlineposition)

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTextUnderlinePosition](akashaproject_design_system._internal_.VendorProperties.md#webkittextunderlineposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7444

___

### WebkitTouchCallout

• `Optional` **WebkitTouchCallout**: [`WebkitTouchCallout`](../modules/akashaproject_design_system._internal_.md#webkittouchcallout)

The `-webkit-touch-callout` CSS property controls the display of the default callout shown when you touch and hold a touch target.

**Syntax**: `default | none`

**Initial value**: `default`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTouchCallout](akashaproject_design_system._internal_.VendorProperties.md#webkittouchcallout)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7452

___

### WebkitTransform

• `Optional` **WebkitTransform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransform](akashaproject_design_system._internal_.VendorProperties.md#webkittransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7460

___

### WebkitTransformOrigin

• `Optional` **WebkitTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`TLength`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransformOrigin](akashaproject_design_system._internal_.VendorProperties.md#webkittransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7468

___

### WebkitTransformStyle

• `Optional` **WebkitTransformStyle**: [`TransformStyle`](../modules/akashaproject_design_system._internal_.md#transformstyle)

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransformStyle](akashaproject_design_system._internal_.VendorProperties.md#webkittransformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7476

___

### WebkitTransition

• `Optional` **WebkitTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`TTime`\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransition](akashaproject_design_system._internal_.VendorProperties.md#webkittransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7683

___

### WebkitTransitionDelay

• `Optional` **WebkitTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`TTime`\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransitionDelay](akashaproject_design_system._internal_.VendorProperties.md#webkittransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7484

___

### WebkitTransitionDuration

• `Optional` **WebkitTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`TTime`\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransitionDuration](akashaproject_design_system._internal_.VendorProperties.md#webkittransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7492

___

### WebkitTransitionProperty

• `Optional` **WebkitTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransitionProperty](akashaproject_design_system._internal_.VendorProperties.md#webkittransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7500

___

### WebkitTransitionTimingFunction

• `Optional` **WebkitTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitTransitionTimingFunction](akashaproject_design_system._internal_.VendorProperties.md#webkittransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7508

___

### WebkitUserModify

• `Optional` **WebkitUserModify**: [`WebkitUserModify`](../modules/akashaproject_design_system._internal_.md#webkitusermodify)

**Syntax**: `read-only | read-write | read-write-plaintext-only`

**Initial value**: `read-only`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitUserModify](akashaproject_design_system._internal_.VendorProperties.md#webkitusermodify)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7514

___

### WebkitUserSelect

• `Optional` **WebkitUserSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitUserSelect](akashaproject_design_system._internal_.VendorProperties.md#webkituserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7522

___

### WebkitWritingMode

• `Optional` **WebkitWritingMode**: [`WritingMode`](../modules/akashaproject_design_system._internal_.md#writingmode)

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (`html` element for HTML documents).

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[WebkitWritingMode](akashaproject_design_system._internal_.VendorProperties.md#webkitwritingmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7530

___

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[accentColor](akashaproject_design_system._internal_.StandardProperties.md#accentcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[alignContent](akashaproject_design_system._internal_.StandardProperties.md#aligncontent)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[alignItems](akashaproject_design_system._internal_.StandardProperties.md#alignitems)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[alignSelf](akashaproject_design_system._internal_.StandardProperties.md#alignself)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[alignTracks](akashaproject_design_system._internal_.StandardProperties.md#aligntracks)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:126

___

### alignmentBaseline

• `Optional` **alignmentBaseline**: [`AlignmentBaseline`](../modules/akashaproject_design_system._internal_.md#alignmentbaseline)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[alignmentBaseline](akashaproject_design_system._internal_.SvgProperties.md#alignmentbaseline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8748

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[all](akashaproject_design_system._internal_.StandardProperties.md#all)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animation](akashaproject_design_system._internal_.StandardProperties.md#animation)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationDelay](akashaproject_design_system._internal_.StandardProperties.md#animationdelay)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationDirection](akashaproject_design_system._internal_.StandardProperties.md#animationdirection)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationDuration](akashaproject_design_system._internal_.StandardProperties.md#animationduration)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationFillMode](akashaproject_design_system._internal_.StandardProperties.md#animationfillmode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationIterationCount](akashaproject_design_system._internal_.StandardProperties.md#animationiterationcount)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationName](akashaproject_design_system._internal_.StandardProperties.md#animationname)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationPlayState](akashaproject_design_system._internal_.StandardProperties.md#animationplaystate)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[animationTimingFunction](akashaproject_design_system._internal_.StandardProperties.md#animationtimingfunction)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[appearance](akashaproject_design_system._internal_.StandardProperties.md#appearance)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[aspectRatio](akashaproject_design_system._internal_.StandardProperties.md#aspectratio)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:275

___

### azimuth

• `Optional` **azimuth**: [`Azimuth`](../modules/akashaproject_design_system._internal_.md#azimuth)

In combination with `elevation`, the **`azimuth`** CSS property enables different audio sources to be positioned spatially for aural presentation. This is important in that it provides a natural way to tell several voices apart, as each can be positioned to originate at a different location on the sound stage. Stereo output produce a lateral sound stage, while binaural headphones and multi-speaker setups allow for a fully three-dimensional stage.

**Syntax**: `<angle> | [ [ left-side | far-left | left | center-left | center | center-right | right | far-right | right-side ] || behind ] | leftwards | rightwards`

**Initial value**: `center`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[azimuth](akashaproject_design_system._internal_.ObsoleteProperties.md#azimuth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7698

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backdropFilter](akashaproject_design_system._internal_.StandardProperties.md#backdropfilter)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backfaceVisibility](akashaproject_design_system._internal_.StandardProperties.md#backfacevisibility)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[background](akashaproject_design_system._internal_.StandardProperties.md#background)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundAttachment](akashaproject_design_system._internal_.StandardProperties.md#backgroundattachment)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundBlendMode](akashaproject_design_system._internal_.StandardProperties.md#backgroundblendmode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundClip](akashaproject_design_system._internal_.StandardProperties.md#backgroundclip)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundColor](akashaproject_design_system._internal_.StandardProperties.md#backgroundcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundImage](akashaproject_design_system._internal_.StandardProperties.md#backgroundimage)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundOrigin](akashaproject_design_system._internal_.StandardProperties.md#backgroundorigin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundPosition](akashaproject_design_system._internal_.StandardProperties.md#backgroundposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundPositionX](akashaproject_design_system._internal_.StandardProperties.md#backgroundpositionx)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundPositionY](akashaproject_design_system._internal_.StandardProperties.md#backgroundpositiony)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundRepeat](akashaproject_design_system._internal_.StandardProperties.md#backgroundrepeat)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[backgroundSize](akashaproject_design_system._internal_.StandardProperties.md#backgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:445

___

### baselineShift

• `Optional` **baselineShift**: [`BaselineShift`](../modules/akashaproject_design_system._internal_.md#baselineshift)<`TLength`\>

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[baselineShift](akashaproject_design_system._internal_.SvgProperties.md#baselineshift)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8749

___

### blockOverflow

• `Optional` **blockOverflow**: [`BlockOverflow`](../modules/akashaproject_design_system._internal_.md#blockoverflow)

**Syntax**: `clip | ellipsis | <string>`

**Initial value**: `clip`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[blockOverflow](akashaproject_design_system._internal_.StandardProperties.md#blockoverflow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[blockSize](akashaproject_design_system._internal_.StandardProperties.md#blocksize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[border](akashaproject_design_system._internal_.StandardProperties.md#border)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlock](akashaproject_design_system._internal_.StandardProperties.md#borderblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#borderblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockEndColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockendcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockEndStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockendstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockEndWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockendwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockStart](akashaproject_design_system._internal_.StandardProperties.md#borderblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockStartColor](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockStartStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockStartWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockstartwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockStyle](akashaproject_design_system._internal_.StandardProperties.md#borderblockstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBlockWidth](akashaproject_design_system._internal_.StandardProperties.md#borderblockwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottom](akashaproject_design_system._internal_.StandardProperties.md#borderbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottomColor](akashaproject_design_system._internal_.StandardProperties.md#borderbottomcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottomLeftRadius](akashaproject_design_system._internal_.StandardProperties.md#borderbottomleftradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottomRightRadius](akashaproject_design_system._internal_.StandardProperties.md#borderbottomrightradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottomStyle](akashaproject_design_system._internal_.StandardProperties.md#borderbottomstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderBottomWidth](akashaproject_design_system._internal_.StandardProperties.md#borderbottomwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderCollapse](akashaproject_design_system._internal_.StandardProperties.md#bordercollapse)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderColor](akashaproject_design_system._internal_.StandardProperties.md#bordercolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderEndEndRadius](akashaproject_design_system._internal_.StandardProperties.md#borderendendradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderEndStartRadius](akashaproject_design_system._internal_.StandardProperties.md#borderendstartradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImage](akashaproject_design_system._internal_.StandardProperties.md#borderimage)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImageOutset](akashaproject_design_system._internal_.StandardProperties.md#borderimageoutset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImageRepeat](akashaproject_design_system._internal_.StandardProperties.md#borderimagerepeat)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImageSlice](akashaproject_design_system._internal_.StandardProperties.md#borderimageslice)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImageSource](akashaproject_design_system._internal_.StandardProperties.md#borderimagesource)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderImageWidth](akashaproject_design_system._internal_.StandardProperties.md#borderimagewidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInline](akashaproject_design_system._internal_.StandardProperties.md#borderinline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlinecolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#borderinlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineEndColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineEndStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineEndWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlineendwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineStart](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineStartColor](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineStartStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineStartWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestartwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineStyle](akashaproject_design_system._internal_.StandardProperties.md#borderinlinestyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderInlineWidth](akashaproject_design_system._internal_.StandardProperties.md#borderinlinewidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderLeft](akashaproject_design_system._internal_.StandardProperties.md#borderleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderLeftColor](akashaproject_design_system._internal_.StandardProperties.md#borderleftcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderLeftStyle](akashaproject_design_system._internal_.StandardProperties.md#borderleftstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderLeftWidth](akashaproject_design_system._internal_.StandardProperties.md#borderleftwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderRadius](akashaproject_design_system._internal_.StandardProperties.md#borderradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderRight](akashaproject_design_system._internal_.StandardProperties.md#borderright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderRightColor](akashaproject_design_system._internal_.StandardProperties.md#borderrightcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderRightStyle](akashaproject_design_system._internal_.StandardProperties.md#borderrightstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderRightWidth](akashaproject_design_system._internal_.StandardProperties.md#borderrightwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderSpacing](akashaproject_design_system._internal_.StandardProperties.md#borderspacing)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderStartEndRadius](akashaproject_design_system._internal_.StandardProperties.md#borderstartendradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderStartStartRadius](akashaproject_design_system._internal_.StandardProperties.md#borderstartstartradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderStyle](akashaproject_design_system._internal_.StandardProperties.md#borderstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTop](akashaproject_design_system._internal_.StandardProperties.md#bordertop)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTopColor](akashaproject_design_system._internal_.StandardProperties.md#bordertopcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTopLeftRadius](akashaproject_design_system._internal_.StandardProperties.md#bordertopleftradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTopRightRadius](akashaproject_design_system._internal_.StandardProperties.md#bordertoprightradius)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTopStyle](akashaproject_design_system._internal_.StandardProperties.md#bordertopstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderTopWidth](akashaproject_design_system._internal_.StandardProperties.md#bordertopwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[borderWidth](akashaproject_design_system._internal_.StandardProperties.md#borderwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[bottom](akashaproject_design_system._internal_.StandardProperties.md#bottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1118

___

### boxAlign

• `Optional` **boxAlign**: [`BoxAlign`](../modules/akashaproject_design_system._internal_.md#boxalign)

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxAlign](akashaproject_design_system._internal_.ObsoleteProperties.md#boxalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7708

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[boxDecorationBreak](akashaproject_design_system._internal_.StandardProperties.md#boxdecorationbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1132

___

### boxDirection

• `Optional` **boxDirection**: [`BoxDirection`](../modules/akashaproject_design_system._internal_.md#boxdirection)

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxDirection](akashaproject_design_system._internal_.ObsoleteProperties.md#boxdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7718

___

### boxFlex

• `Optional` **boxFlex**: [`BoxFlex`](../modules/akashaproject_design_system._internal_.md#boxflex)

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxFlex](akashaproject_design_system._internal_.ObsoleteProperties.md#boxflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7728

___

### boxFlexGroup

• `Optional` **boxFlexGroup**: [`BoxFlexGroup`](../modules/akashaproject_design_system._internal_.md#boxflexgroup)

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxFlexGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#boxflexgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7738

___

### boxLines

• `Optional` **boxLines**: [`BoxLines`](../modules/akashaproject_design_system._internal_.md#boxlines)

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxLines](akashaproject_design_system._internal_.ObsoleteProperties.md#boxlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7748

___

### boxOrdinalGroup

• `Optional` **boxOrdinalGroup**: [`BoxOrdinalGroup`](../modules/akashaproject_design_system._internal_.md#boxordinalgroup)

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxOrdinalGroup](akashaproject_design_system._internal_.ObsoleteProperties.md#boxordinalgroup)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7758

___

### boxOrient

• `Optional` **boxOrient**: [`BoxOrient`](../modules/akashaproject_design_system._internal_.md#boxorient)

This is a property of the original CSS Flexible Box Layout Module draft, and has been replaced by a newer standard. See flexbox for information about the current standard.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxOrient](akashaproject_design_system._internal_.ObsoleteProperties.md#boxorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7768

___

### boxPack

• `Optional` **boxPack**: [`BoxPack`](../modules/akashaproject_design_system._internal_.md#boxpack)

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[boxPack](akashaproject_design_system._internal_.ObsoleteProperties.md#boxpack)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7778

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[boxShadow](akashaproject_design_system._internal_.StandardProperties.md#boxshadow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[boxSizing](akashaproject_design_system._internal_.StandardProperties.md#boxsizing)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[breakAfter](akashaproject_design_system._internal_.StandardProperties.md#breakafter)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[breakBefore](akashaproject_design_system._internal_.StandardProperties.md#breakbefore)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[breakInside](akashaproject_design_system._internal_.StandardProperties.md#breakinside)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[captionSide](akashaproject_design_system._internal_.StandardProperties.md#captionside)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[caretColor](akashaproject_design_system._internal_.StandardProperties.md#caretcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[clear](akashaproject_design_system._internal_.StandardProperties.md#clear)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1288

___

### clip

• `Optional` **clip**: [`Clip`](../modules/akashaproject_design_system._internal_.md#clip)

The **`clip`** CSS property defines a visible portion of an element. The `clip` property applies only to absolutely positioned elements — that is, elements with `position:absolute` or `position:fixed`.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[clip](akashaproject_design_system._internal_.SvgProperties.md#clip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7788

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[clipPath](akashaproject_design_system._internal_.SvgProperties.md#clippath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1303

___

### clipRule

• `Optional` **clipRule**: [`ClipRule`](../modules/akashaproject_design_system._internal_.md#cliprule)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[clipRule](akashaproject_design_system._internal_.SvgProperties.md#cliprule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8752

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[color](akashaproject_design_system._internal_.SvgProperties.md#color)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[colorAdjust](akashaproject_design_system._internal_.StandardProperties.md#coloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1331

___

### colorInterpolation

• `Optional` **colorInterpolation**: [`ColorInterpolation`](../modules/akashaproject_design_system._internal_.md#colorinterpolation)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[colorInterpolation](akashaproject_design_system._internal_.SvgProperties.md#colorinterpolation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8754

___

### colorRendering

• `Optional` **colorRendering**: [`ColorRendering`](../modules/akashaproject_design_system._internal_.md#colorrendering)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[colorRendering](akashaproject_design_system._internal_.SvgProperties.md#colorrendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8755

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[colorScheme](akashaproject_design_system._internal_.StandardProperties.md#colorscheme)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnCount](akashaproject_design_system._internal_.StandardProperties.md#columncount)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnFill](akashaproject_design_system._internal_.StandardProperties.md#columnfill)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnGap](akashaproject_design_system._internal_.StandardProperties.md#columngap)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnRule](akashaproject_design_system._internal_.StandardProperties.md#columnrule)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnRuleColor](akashaproject_design_system._internal_.StandardProperties.md#columnrulecolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnRuleStyle](akashaproject_design_system._internal_.StandardProperties.md#columnrulestyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnRuleWidth](akashaproject_design_system._internal_.StandardProperties.md#columnrulewidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnSpan](akashaproject_design_system._internal_.StandardProperties.md#columnspan)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columnWidth](akashaproject_design_system._internal_.StandardProperties.md#columnwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[columns](akashaproject_design_system._internal_.StandardProperties.md#columns)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[contain](akashaproject_design_system._internal_.StandardProperties.md#contain)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[content](akashaproject_design_system._internal_.StandardProperties.md#content)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[contentVisibility](akashaproject_design_system._internal_.StandardProperties.md#contentvisibility)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[counterIncrement](akashaproject_design_system._internal_.StandardProperties.md#counterincrement)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[counterReset](akashaproject_design_system._internal_.StandardProperties.md#counterreset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[counterSet](akashaproject_design_system._internal_.StandardProperties.md#counterset)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[cursor](akashaproject_design_system._internal_.SvgProperties.md#cursor)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[direction](akashaproject_design_system._internal_.SvgProperties.md#direction)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[display](akashaproject_design_system._internal_.SvgProperties.md#display)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1614

___

### dominantBaseline

• `Optional` **dominantBaseline**: [`DominantBaseline`](../modules/akashaproject_design_system._internal_.md#dominantbaseline)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[dominantBaseline](akashaproject_design_system._internal_.SvgProperties.md#dominantbaseline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8759

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[emptyCells](akashaproject_design_system._internal_.StandardProperties.md#emptycells)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1628

___

### fill

• `Optional` **fill**: [`Fill`](../modules/akashaproject_design_system._internal_.md#fill)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fill](akashaproject_design_system._internal_.SvgProperties.md#fill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8760

___

### fillOpacity

• `Optional` **fillOpacity**: [`FillOpacity`](../modules/akashaproject_design_system._internal_.md#fillopacity)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fillOpacity](akashaproject_design_system._internal_.SvgProperties.md#fillopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8761

___

### fillRule

• `Optional` **fillRule**: [`FillRule`](../modules/akashaproject_design_system._internal_.md#fillrule)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fillRule](akashaproject_design_system._internal_.SvgProperties.md#fillrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8762

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[filter](akashaproject_design_system._internal_.SvgProperties.md#filter)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flex](akashaproject_design_system._internal_.StandardProperties.md#flex)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexBasis](akashaproject_design_system._internal_.StandardProperties.md#flexbasis)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexDirection](akashaproject_design_system._internal_.StandardProperties.md#flexdirection)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexFlow](akashaproject_design_system._internal_.StandardProperties.md#flexflow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexGrow](akashaproject_design_system._internal_.StandardProperties.md#flexgrow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexShrink](akashaproject_design_system._internal_.StandardProperties.md#flexshrink)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[flexWrap](akashaproject_design_system._internal_.StandardProperties.md#flexwrap)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[float](akashaproject_design_system._internal_.StandardProperties.md#float)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1732

___

### floodColor

• `Optional` **floodColor**: [`FloodColor`](../modules/akashaproject_design_system._internal_.md#floodcolor)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[floodColor](akashaproject_design_system._internal_.SvgProperties.md#floodcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8764

___

### floodOpacity

• `Optional` **floodOpacity**: [`FloodOpacity`](../modules/akashaproject_design_system._internal_.md#floodopacity)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[floodOpacity](akashaproject_design_system._internal_.SvgProperties.md#floodopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8765

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[font](akashaproject_design_system._internal_.SvgProperties.md#font)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontFamily](akashaproject_design_system._internal_.SvgProperties.md#fontfamily)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontFeatureSettings](akashaproject_design_system._internal_.StandardProperties.md#fontfeaturesettings)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontKerning](akashaproject_design_system._internal_.StandardProperties.md#fontkerning)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontLanguageOverride](akashaproject_design_system._internal_.StandardProperties.md#fontlanguageoverride)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontOpticalSizing](akashaproject_design_system._internal_.StandardProperties.md#fontopticalsizing)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontSize](akashaproject_design_system._internal_.SvgProperties.md#fontsize)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontSizeAdjust](akashaproject_design_system._internal_.SvgProperties.md#fontsizeadjust)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontSmooth](akashaproject_design_system._internal_.StandardProperties.md#fontsmooth)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontStretch](akashaproject_design_system._internal_.SvgProperties.md#fontstretch)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontStyle](akashaproject_design_system._internal_.SvgProperties.md#fontstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontSynthesis](akashaproject_design_system._internal_.StandardProperties.md#fontsynthesis)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontVariant](akashaproject_design_system._internal_.SvgProperties.md#fontvariant)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1903

___

### fontVariantAlternates

• `Optional` **fontVariantAlternates**: [`FontVariantAlternates`](../modules/akashaproject_design_system._internal_.md#fontvariantalternates)

The **`font-variant-alternates`** CSS property controls the usage of alternate glyphs. These alternate glyphs may be referenced by alternative names defined in `@font-feature-values`.

**Syntax**: `normal | [ stylistic( <feature-value-name> ) || historical-forms || styleset( <feature-value-name># ) || character-variant( <feature-value-name># ) || swash( <feature-value-name> ) || ornaments( <feature-value-name> ) || annotation( <feature-value-name> ) ]`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[fontVariantAlternates](akashaproject_design_system._internal_.ObsoleteProperties.md#fontvariantalternates)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7798

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariantCaps](akashaproject_design_system._internal_.StandardProperties.md#fontvariantcaps)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariantEastAsian](akashaproject_design_system._internal_.StandardProperties.md#fontvarianteastasian)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariantLigatures](akashaproject_design_system._internal_.StandardProperties.md#fontvariantligatures)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariantNumeric](akashaproject_design_system._internal_.StandardProperties.md#fontvariantnumeric)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariantPosition](akashaproject_design_system._internal_.StandardProperties.md#fontvariantposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[fontVariationSettings](akashaproject_design_system._internal_.StandardProperties.md#fontvariationsettings)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[fontWeight](akashaproject_design_system._internal_.SvgProperties.md#fontweight)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[forcedColorAdjust](akashaproject_design_system._internal_.StandardProperties.md#forcedcoloradjust)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gap](akashaproject_design_system._internal_.StandardProperties.md#gap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5478

___

### glyphOrientationVertical

• `Optional` **glyphOrientationVertical**: [`GlyphOrientationVertical`](../modules/akashaproject_design_system._internal_.md#glyphorientationvertical)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[glyphOrientationVertical](akashaproject_design_system._internal_.SvgProperties.md#glyphorientationvertical)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8774

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[grid](akashaproject_design_system._internal_.StandardProperties.md#grid)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridArea](akashaproject_design_system._internal_.StandardProperties.md#gridarea)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridAutoColumns](akashaproject_design_system._internal_.StandardProperties.md#gridautocolumns)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridAutoFlow](akashaproject_design_system._internal_.StandardProperties.md#gridautoflow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridAutoRows](akashaproject_design_system._internal_.StandardProperties.md#gridautorows)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridColumn](akashaproject_design_system._internal_.StandardProperties.md#gridcolumn)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridColumnEnd](akashaproject_design_system._internal_.StandardProperties.md#gridcolumnend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2073

___

### gridColumnGap

• `Optional` **gridColumnGap**: [`GridColumnGap`](../modules/akashaproject_design_system._internal_.md#gridcolumngap)<`TLength`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[gridColumnGap](akashaproject_design_system._internal_.ObsoleteProperties.md#gridcolumngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7808

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridColumnStart](akashaproject_design_system._internal_.StandardProperties.md#gridcolumnstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2087

___

### gridGap

• `Optional` **gridGap**: [`GridGap`](../modules/akashaproject_design_system._internal_.md#gridgap)<`TLength`\>

The **`gap`** CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for `row-gap` and `column-gap`.

**Syntax**: `<'grid-row-gap'> <'grid-column-gap'>?`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[gridGap](akashaproject_design_system._internal_.ObsoleteProperties.md#gridgap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7816

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridRow](akashaproject_design_system._internal_.StandardProperties.md#gridrow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridRowEnd](akashaproject_design_system._internal_.StandardProperties.md#gridrowend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2101

___

### gridRowGap

• `Optional` **gridRowGap**: [`GridRowGap`](../modules/akashaproject_design_system._internal_.md#gridrowgap)<`TLength`\>

The **`row-gap`** CSS property sets the size of the gap (gutter) between an element's grid rows.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[gridRowGap](akashaproject_design_system._internal_.ObsoleteProperties.md#gridrowgap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7826

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridRowStart](akashaproject_design_system._internal_.StandardProperties.md#gridrowstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridTemplate](akashaproject_design_system._internal_.StandardProperties.md#gridtemplate)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridTemplateAreas](akashaproject_design_system._internal_.StandardProperties.md#gridtemplateareas)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridTemplateColumns](akashaproject_design_system._internal_.StandardProperties.md#gridtemplatecolumns)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[gridTemplateRows](akashaproject_design_system._internal_.StandardProperties.md#gridtemplaterows)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[hangingPunctuation](akashaproject_design_system._internal_.StandardProperties.md#hangingpunctuation)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[height](akashaproject_design_system._internal_.StandardProperties.md#height)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[hyphens](akashaproject_design_system._internal_.StandardProperties.md#hyphens)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[imageOrientation](akashaproject_design_system._internal_.StandardProperties.md#imageorientation)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[imageRendering](akashaproject_design_system._internal_.SvgProperties.md#imagerendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2228

___

### imageResolution

• `Optional` **imageResolution**: [`ImageResolution`](../modules/akashaproject_design_system._internal_.md#imageresolution)

**Syntax**: `[ from-image || <resolution> ] && snap?`

**Initial value**: `1dppx`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[imageResolution](akashaproject_design_system._internal_.StandardProperties.md#imageresolution)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2234

___

### imeMode

• `Optional` **imeMode**: [`ImeMode`](../modules/akashaproject_design_system._internal_.md#imemode)

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[imeMode](akashaproject_design_system._internal_.ObsoleteProperties.md#imemode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7836

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[initialLetter](akashaproject_design_system._internal_.StandardProperties.md#initialletter)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[inlineSize](akashaproject_design_system._internal_.StandardProperties.md#inlinesize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[inset](akashaproject_design_system._internal_.StandardProperties.md#inset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetBlock](akashaproject_design_system._internal_.StandardProperties.md#insetblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#insetblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetBlockStart](akashaproject_design_system._internal_.StandardProperties.md#insetblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetInline](akashaproject_design_system._internal_.StandardProperties.md#insetinline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#insetinlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[insetInlineStart](akashaproject_design_system._internal_.StandardProperties.md#insetinlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[isolation](akashaproject_design_system._internal_.StandardProperties.md#isolation)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[justifyContent](akashaproject_design_system._internal_.StandardProperties.md#justifycontent)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[justifyItems](akashaproject_design_system._internal_.StandardProperties.md#justifyitems)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[justifySelf](akashaproject_design_system._internal_.StandardProperties.md#justifyself)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[justifyTracks](akashaproject_design_system._internal_.StandardProperties.md#justifytracks)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[left](akashaproject_design_system._internal_.StandardProperties.md#left)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[letterSpacing](akashaproject_design_system._internal_.SvgProperties.md#letterspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2501

___

### lightingColor

• `Optional` **lightingColor**: [`LightingColor`](../modules/akashaproject_design_system._internal_.md#lightingcolor)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[lightingColor](akashaproject_design_system._internal_.SvgProperties.md#lightingcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8777

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[lineBreak](akashaproject_design_system._internal_.StandardProperties.md#linebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2516

___

### lineClamp

• `Optional` **lineClamp**: [`LineClamp`](../modules/akashaproject_design_system._internal_.md#lineclamp)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[lineClamp](akashaproject_design_system._internal_.StandardProperties.md#lineclamp)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[lineHeight](akashaproject_design_system._internal_.SvgProperties.md#lineheight)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[lineHeightStep](akashaproject_design_system._internal_.StandardProperties.md#lineheightstep)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[listStyle](akashaproject_design_system._internal_.StandardProperties.md#liststyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[listStyleImage](akashaproject_design_system._internal_.StandardProperties.md#liststyleimage)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[listStylePosition](akashaproject_design_system._internal_.StandardProperties.md#liststyleposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[listStyleType](akashaproject_design_system._internal_.StandardProperties.md#liststyletype)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[margin](akashaproject_design_system._internal_.StandardProperties.md#margin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginBlock](akashaproject_design_system._internal_.StandardProperties.md#marginblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#marginblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginBlockStart](akashaproject_design_system._internal_.StandardProperties.md#marginblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginBottom](akashaproject_design_system._internal_.StandardProperties.md#marginbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginInline](akashaproject_design_system._internal_.StandardProperties.md#margininline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#margininlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginInlineStart](akashaproject_design_system._internal_.StandardProperties.md#margininlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginLeft](akashaproject_design_system._internal_.StandardProperties.md#marginleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginRight](akashaproject_design_system._internal_.StandardProperties.md#marginright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[marginTop](akashaproject_design_system._internal_.StandardProperties.md#margintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2728

___

### marker

• `Optional` **marker**: [`Marker`](../modules/akashaproject_design_system._internal_.md#marker)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[marker](akashaproject_design_system._internal_.SvgProperties.md#marker)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8779

___

### markerEnd

• `Optional` **markerEnd**: [`MarkerEnd`](../modules/akashaproject_design_system._internal_.md#markerend)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[markerEnd](akashaproject_design_system._internal_.SvgProperties.md#markerend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8780

___

### markerMid

• `Optional` **markerMid**: [`MarkerMid`](../modules/akashaproject_design_system._internal_.md#markermid)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[markerMid](akashaproject_design_system._internal_.SvgProperties.md#markermid)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8781

___

### markerStart

• `Optional` **markerStart**: [`MarkerStart`](../modules/akashaproject_design_system._internal_.md#markerstart)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[markerStart](akashaproject_design_system._internal_.SvgProperties.md#markerstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8782

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[mask](akashaproject_design_system._internal_.SvgProperties.md#mask)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorder](akashaproject_design_system._internal_.StandardProperties.md#maskborder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5592

___

### maskBorderMode

• `Optional` **maskBorderMode**: [`MaskBorderMode`](../modules/akashaproject_design_system._internal_.md#maskbordermode)

The **`mask-border-mode`** CSS property specifies the blending mode used in a mask border.

**Syntax**: `luminance | alpha`

**Initial value**: `alpha`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderMode](akashaproject_design_system._internal_.StandardProperties.md#maskbordermode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderOutset](akashaproject_design_system._internal_.StandardProperties.md#maskborderoutset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderRepeat](akashaproject_design_system._internal_.StandardProperties.md#maskborderrepeat)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderSlice](akashaproject_design_system._internal_.StandardProperties.md#maskborderslice)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderSource](akashaproject_design_system._internal_.StandardProperties.md#maskbordersource)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskBorderWidth](akashaproject_design_system._internal_.StandardProperties.md#maskborderwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskClip](akashaproject_design_system._internal_.StandardProperties.md#maskclip)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskComposite](akashaproject_design_system._internal_.StandardProperties.md#maskcomposite)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskImage](akashaproject_design_system._internal_.StandardProperties.md#maskimage)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskMode](akashaproject_design_system._internal_.StandardProperties.md#maskmode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskOrigin](akashaproject_design_system._internal_.StandardProperties.md#maskorigin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskPosition](akashaproject_design_system._internal_.StandardProperties.md#maskposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskRepeat](akashaproject_design_system._internal_.StandardProperties.md#maskrepeat)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskSize](akashaproject_design_system._internal_.StandardProperties.md#masksize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maskType](akashaproject_design_system._internal_.StandardProperties.md#masktype)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[mathStyle](akashaproject_design_system._internal_.StandardProperties.md#mathstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maxBlockSize](akashaproject_design_system._internal_.StandardProperties.md#maxblocksize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maxHeight](akashaproject_design_system._internal_.StandardProperties.md#maxheight)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maxInlineSize](akashaproject_design_system._internal_.StandardProperties.md#maxinlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2989

___

### maxLines

• `Optional` **maxLines**: [`MaxLines`](../modules/akashaproject_design_system._internal_.md#maxlines)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maxLines](akashaproject_design_system._internal_.StandardProperties.md#maxlines)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[maxWidth](akashaproject_design_system._internal_.StandardProperties.md#maxwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[minBlockSize](akashaproject_design_system._internal_.StandardProperties.md#minblocksize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[minHeight](akashaproject_design_system._internal_.StandardProperties.md#minheight)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[minInlineSize](akashaproject_design_system._internal_.StandardProperties.md#mininlinesize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[minWidth](akashaproject_design_system._internal_.StandardProperties.md#minwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[mixBlendMode](akashaproject_design_system._internal_.StandardProperties.md#mixblendmode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[motion](akashaproject_design_system._internal_.StandardProperties.md#motion)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[motionDistance](akashaproject_design_system._internal_.StandardProperties.md#motiondistance)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[motionPath](akashaproject_design_system._internal_.StandardProperties.md#motionpath)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[motionRotation](akashaproject_design_system._internal_.StandardProperties.md#motionrotation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3124

___

### msAccelerator

• `Optional` **msAccelerator**: [`MsAccelerator`](../modules/akashaproject_design_system._internal_.md#msaccelerator)

The **`-ms-accelerator`** CSS property is a Microsoft extension that sets or retrieves a string indicating whether the object represents a keyboard shortcut.

**Syntax**: `false | true`

**Initial value**: `false`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msAccelerator](akashaproject_design_system._internal_.VendorProperties.md#msaccelerator)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6186

___

### msAlignSelf

• `Optional` **msAlignSelf**: [`AlignSelf`](../modules/akashaproject_design_system._internal_.md#alignself)

The **`align-self`** CSS property overrides a grid or flex item's `align-items` value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msAlignSelf](akashaproject_design_system._internal_.VendorProperties.md#msalignself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6194

___

### msBlockProgression

• `Optional` **msBlockProgression**: [`MsBlockProgression`](../modules/akashaproject_design_system._internal_.md#msblockprogression)

The **`-ms-block-progression`** CSS property is a Microsoft extension that specifies the block progression and layout orientation.

**Syntax**: `tb | rl | bt | lr`

**Initial value**: `tb`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msBlockProgression](akashaproject_design_system._internal_.VendorProperties.md#msblockprogression)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6202

___

### msContentZoomChaining

• `Optional` **msContentZoomChaining**: [`MsContentZoomChaining`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchaining)

The **`-ms-content-zoom-chaining`** CSS property is a Microsoft extension specifying the zoom behavior that occurs when a user hits the zoom limit during page manipulation.

**Syntax**: `none | chained`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomChaining](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomchaining)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6210

___

### msContentZoomLimit

• `Optional` **msContentZoomLimit**: [`MsContentZoomLimit`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimit)

The **`-ms-content-zoom-limit`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-limit-min` and `-ms-content-zoom-limit-max` properties.

**Syntax**: `<'-ms-content-zoom-limit-min'> <'-ms-content-zoom-limit-max'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomLimit](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomlimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7569

___

### msContentZoomLimitMax

• `Optional` **msContentZoomLimitMax**: [`MsContentZoomLimitMax`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimitmax)

The **`-ms-content-zoom-limit-max`** CSS property is a Microsoft extension that specifies the selected elements' maximum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `400%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomLimitMax](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomlimitmax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6218

___

### msContentZoomLimitMin

• `Optional` **msContentZoomLimitMin**: [`MsContentZoomLimitMin`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimitmin)

The **`-ms-content-zoom-limit-min`** CSS property is a Microsoft extension that specifies the minimum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `100%`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomLimitMin](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomlimitmin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6226

___

### msContentZoomSnap

• `Optional` **msContentZoomSnap**: [`MsContentZoomSnap`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnap)

The **`-ms-content-zoom-snap`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-snap-type` and `-ms-content-zoom-snap-points` properties.

**Syntax**: `<'-ms-content-zoom-snap-type'> || <'-ms-content-zoom-snap-points'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomSnap](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomsnap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7575

___

### msContentZoomSnapPoints

• `Optional` **msContentZoomSnapPoints**: [`MsContentZoomSnapPoints`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnappoints)

The **`-ms-content-zoom-snap-points`** CSS property is a Microsoft extension that specifies where zoom snap-points are located.

**Syntax**: `snapInterval( <percentage>, <percentage> ) | snapList( <percentage># )`

**Initial value**: `snapInterval(0%, 100%)`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomSnapPoints](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomsnappoints)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6234

___

### msContentZoomSnapType

• `Optional` **msContentZoomSnapType**: [`MsContentZoomSnapType`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptype)

The **`-ms-content-zoom-snap-type`** CSS property is a Microsoft extension that specifies how zooming is affected by defined snap-points.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZoomSnapType](akashaproject_design_system._internal_.VendorProperties.md#mscontentzoomsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6242

___

### msContentZooming

• `Optional` **msContentZooming**: [`MsContentZooming`](../modules/akashaproject_design_system._internal_.md#mscontentzooming)

The **`-ms-content-zooming`** CSS property is a Microsoft extension that specifies whether zooming is enabled.

**Syntax**: `none | zoom`

**Initial value**: zoom for the top level element, none for all other elements

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msContentZooming](akashaproject_design_system._internal_.VendorProperties.md#mscontentzooming)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6250

___

### msFilter

• `Optional` **msFilter**: [`MsFilter`](../modules/akashaproject_design_system._internal_.md#msfilter)

The `-ms-filter` CSS property is a Microsoft extension that sets or retrieves the filter or collection of filters applied to an object.

**Syntax**: `<string>`

**Initial value**: "" (the empty string)

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFilter](akashaproject_design_system._internal_.VendorProperties.md#msfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6258

___

### msFlex

• `Optional` **msFlex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`TLength`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFlex](akashaproject_design_system._internal_.VendorProperties.md#msflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7581

___

### msFlexDirection

• `Optional` **msFlexDirection**: [`FlexDirection`](../modules/akashaproject_design_system._internal_.md#flexdirection)

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFlexDirection](akashaproject_design_system._internal_.VendorProperties.md#msflexdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6266

___

### msFlexPositive

• `Optional` **msFlexPositive**: [`FlexGrow`](../modules/akashaproject_design_system._internal_.md#flexgrow)

The **`flex-grow`** CSS property sets the flex grow factor of a flex item main size.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFlexPositive](akashaproject_design_system._internal_.VendorProperties.md#msflexpositive)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6274

___

### msFlowFrom

• `Optional` **msFlowFrom**: [`MsFlowFrom`](../modules/akashaproject_design_system._internal_.md#msflowfrom)

The **`-ms-flow-from`** CSS property is a Microsoft extension that gets or sets a value identifying a region container in the document that accepts the content flow from the data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFlowFrom](akashaproject_design_system._internal_.VendorProperties.md#msflowfrom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6282

___

### msFlowInto

• `Optional` **msFlowInto**: [`MsFlowInto`](../modules/akashaproject_design_system._internal_.md#msflowinto)

The **`-ms-flow-into`** CSS property is a Microsoft extension that gets or sets a value identifying an iframe container in the document that serves as the region's data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msFlowInto](akashaproject_design_system._internal_.VendorProperties.md#msflowinto)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6290

___

### msGridColumns

• `Optional` **msGridColumns**: [`MsGridColumns`](../modules/akashaproject_design_system._internal_.md#msgridcolumns)<`TLength`\>

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msGridColumns](akashaproject_design_system._internal_.VendorProperties.md#msgridcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6298

___

### msGridRows

• `Optional` **msGridRows**: [`MsGridRows`](../modules/akashaproject_design_system._internal_.md#msgridrows)<`TLength`\>

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msGridRows](akashaproject_design_system._internal_.VendorProperties.md#msgridrows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6306

___

### msHighContrastAdjust

• `Optional` **msHighContrastAdjust**: [`MsHighContrastAdjust`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjust)

The **`-ms-high-contrast-adjust`** CSS property is a Microsoft extension that gets or sets a value indicating whether to override any CSS properties that would have been set in high contrast mode.

**Syntax**: `auto | none`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msHighContrastAdjust](akashaproject_design_system._internal_.VendorProperties.md#mshighcontrastadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6314

___

### msHyphenateLimitChars

• `Optional` **msHyphenateLimitChars**: [`MsHyphenateLimitChars`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitchars)

The **`-ms-hyphenate-limit-chars`** CSS property is a Microsoft extension that specifies one to three values indicating the minimum number of characters in a hyphenated word. If the word does not meet the required minimum number of characters in the word, before the hyphen, or after the hyphen, then the word is not hyphenated.

**Syntax**: `auto | <integer>{1,3}`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msHyphenateLimitChars](akashaproject_design_system._internal_.VendorProperties.md#mshyphenatelimitchars)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6322

___

### msHyphenateLimitLines

• `Optional` **msHyphenateLimitLines**: [`MsHyphenateLimitLines`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlines)

The **`-ms-hyphenate-limit-lines`** CSS property is a Microsoft extension specifying the maximum number of consecutive lines in an element that may be ended with a hyphenated word.

**Syntax**: `no-limit | <integer>`

**Initial value**: `no-limit`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msHyphenateLimitLines](akashaproject_design_system._internal_.VendorProperties.md#mshyphenatelimitlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6330

___

### msHyphenateLimitZone

• `Optional` **msHyphenateLimitZone**: [`MsHyphenateLimitZone`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzone)<`TLength`\>

The `**-ms-hyphenate-limit-zone**` CSS property is a Microsoft extension specifying the width of the hyphenation zone.

**Syntax**: `<percentage> | <length>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msHyphenateLimitZone](akashaproject_design_system._internal_.VendorProperties.md#mshyphenatelimitzone)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6338

___

### msHyphens

• `Optional` **msHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msHyphens](akashaproject_design_system._internal_.VendorProperties.md#mshyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6346

___

### msImeAlign

• `Optional` **msImeAlign**: [`MsImeAlign`](../modules/akashaproject_design_system._internal_.md#msimealign)

The **`-ms-ime-align`** CSS property is a Microsoft extension aligning the Input Method Editor (IME) candidate window box relative to the element on which the IME composition is active. The extension is implemented in Microsoft Edge and Internet Explorer 11.

**Syntax**: `auto | after`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msImeAlign](akashaproject_design_system._internal_.VendorProperties.md#msimealign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6354

___

### msImeMode

• `Optional` **msImeMode**: [`ImeMode`](../modules/akashaproject_design_system._internal_.md#imemode)

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[msImeMode](akashaproject_design_system._internal_.ObsoleteProperties.md#msimemode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8420

___

### msJustifySelf

• `Optional` **msJustifySelf**: [`JustifySelf`](../modules/akashaproject_design_system._internal_.md#justifyself)

The CSS **`justify-self`** property sets the way a box is justified inside its alignment container along the appropriate axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ]`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msJustifySelf](akashaproject_design_system._internal_.VendorProperties.md#msjustifyself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6362

___

### msLineBreak

• `Optional` **msLineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msLineBreak](akashaproject_design_system._internal_.VendorProperties.md#mslinebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6370

___

### msOrder

• `Optional` **msOrder**: [`Order`](../modules/akashaproject_design_system._internal_.md#order)

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msOrder](akashaproject_design_system._internal_.VendorProperties.md#msorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6378

___

### msOverflowStyle

• `Optional` **msOverflowStyle**: [`MsOverflowStyle`](../modules/akashaproject_design_system._internal_.md#msoverflowstyle)

The **`-ms-overflow-style`** CSS property is a Microsoft extension controlling the behavior of scrollbars when the content of an element overflows.

**Syntax**: `auto | none | scrollbar | -ms-autohiding-scrollbar`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msOverflowStyle](akashaproject_design_system._internal_.VendorProperties.md#msoverflowstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6386

___

### msOverflowX

• `Optional` **msOverflowX**: [`OverflowX`](../modules/akashaproject_design_system._internal_.md#overflowx)

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msOverflowX](akashaproject_design_system._internal_.VendorProperties.md#msoverflowx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6394

___

### msOverflowY

• `Optional` **msOverflowY**: [`OverflowY`](../modules/akashaproject_design_system._internal_.md#overflowy)

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msOverflowY](akashaproject_design_system._internal_.VendorProperties.md#msoverflowy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6402

___

### msScrollChaining

• `Optional` **msScrollChaining**: [`MsScrollChaining`](../modules/akashaproject_design_system._internal_.md#msscrollchaining)

The `**-ms-scroll-chaining**` CSS property is a Microsoft extension that specifies the scrolling behavior that occurs when a user hits the scroll limit during a manipulation.

**Syntax**: `chained | none`

**Initial value**: `chained`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollChaining](akashaproject_design_system._internal_.VendorProperties.md#msscrollchaining)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6410

___

### msScrollLimit

• `Optional` **msScrollLimit**: [`MsScrollLimit`](../modules/akashaproject_design_system._internal_.md#msscrolllimit)

The **\-ms-scroll-limit** CSS property is a Microsoft extension that specifies values for the `-ms-scroll-limit-x-min`, `-ms-scroll-limit-y-min`, `-ms-scroll-limit-x-max`, and `-ms-scroll-limit-y-max` properties.

**Syntax**: `<'-ms-scroll-limit-x-min'> <'-ms-scroll-limit-y-min'> <'-ms-scroll-limit-x-max'> <'-ms-scroll-limit-y-max'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollLimit](akashaproject_design_system._internal_.VendorProperties.md#msscrolllimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7587

___

### msScrollLimitXMax

• `Optional` **msScrollLimitXMax**: [`MsScrollLimitXMax`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmax)<`TLength`\>

The `**-ms-scroll-limit-x-max**` CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollLeft` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollLimitXMax](akashaproject_design_system._internal_.VendorProperties.md#msscrolllimitxmax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6418

___

### msScrollLimitXMin

• `Optional` **msScrollLimitXMin**: [`MsScrollLimitXMin`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmin)<`TLength`\>

The **`-ms-scroll-limit-x-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollLeft` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollLimitXMin](akashaproject_design_system._internal_.VendorProperties.md#msscrolllimitxmin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6426

___

### msScrollLimitYMax

• `Optional` **msScrollLimitYMax**: [`MsScrollLimitYMax`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymax)<`TLength`\>

The **`-ms-scroll-limit-y-max`** CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollTop` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollLimitYMax](akashaproject_design_system._internal_.VendorProperties.md#msscrolllimitymax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6434

___

### msScrollLimitYMin

• `Optional` **msScrollLimitYMin**: [`MsScrollLimitYMin`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymin)<`TLength`\>

The **`-ms-scroll-limit-y-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollTop` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollLimitYMin](akashaproject_design_system._internal_.VendorProperties.md#msscrolllimitymin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6442

___

### msScrollRails

• `Optional` **msScrollRails**: [`MsScrollRails`](../modules/akashaproject_design_system._internal_.md#msscrollrails)

The **`-ms-scroll-rails`** CSS property is a Microsoft extension that specifies whether scrolling locks to the primary axis of motion.

**Syntax**: `none | railed`

**Initial value**: `railed`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollRails](akashaproject_design_system._internal_.VendorProperties.md#msscrollrails)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6450

___

### msScrollSnapPointsX

• `Optional` **msScrollSnapPointsX**: [`MsScrollSnapPointsX`](../modules/akashaproject_design_system._internal_.md#msscrollsnappointsx)

The **`-ms-scroll-snap-points-x`** CSS property is a Microsoft extension that specifies where snap-points will be located along the x-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollSnapPointsX](akashaproject_design_system._internal_.VendorProperties.md#msscrollsnappointsx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6458

___

### msScrollSnapPointsY

• `Optional` **msScrollSnapPointsY**: [`MsScrollSnapPointsY`](../modules/akashaproject_design_system._internal_.md#msscrollsnappointsy)

The **`-ms-scroll-snap-points-y`** CSS property is a Microsoft extension that specifies where snap-points will be located along the y-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollSnapPointsY](akashaproject_design_system._internal_.VendorProperties.md#msscrollsnappointsy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6466

___

### msScrollSnapType

• `Optional` **msScrollSnapType**: [`MsScrollSnapType`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptype)

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollSnapType](akashaproject_design_system._internal_.VendorProperties.md#msscrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6474

___

### msScrollSnapX

• `Optional` **msScrollSnapX**: [`MsScrollSnapX`](../modules/akashaproject_design_system._internal_.md#msscrollsnapx)

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-x` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-x'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollSnapX](akashaproject_design_system._internal_.VendorProperties.md#msscrollsnapx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7593

___

### msScrollSnapY

• `Optional` **msScrollSnapY**: [`MsScrollSnapY`](../modules/akashaproject_design_system._internal_.md#msscrollsnapy)

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-y` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-y'>`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollSnapY](akashaproject_design_system._internal_.VendorProperties.md#msscrollsnapy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7599

___

### msScrollTranslation

• `Optional` **msScrollTranslation**: [`MsScrollTranslation`](../modules/akashaproject_design_system._internal_.md#msscrolltranslation)

The **`-ms-scroll-translation`** CSS property is a Microsoft extension that specifies whether vertical-to-horizontal scroll wheel translation occurs on the specified element.

**Syntax**: `none | vertical-to-horizontal`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollTranslation](akashaproject_design_system._internal_.VendorProperties.md#msscrolltranslation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6482

___

### msScrollbar3dlightColor

• `Optional` **msScrollbar3dlightColor**: [`MsScrollbar3dlightColor`](../modules/akashaproject_design_system._internal_.md#msscrollbar3dlightcolor)

The **`-ms-scrollbar-3dlight-color`** CSS property is a Microsoft extension specifying the color of the top and left edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbar3dlightColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbar3dlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6490

___

### msScrollbarArrowColor

• `Optional` **msScrollbarArrowColor**: [`MsScrollbarArrowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbararrowcolor)

The **`-ms-scrollbar-arrow-color`** CSS property is a Microsoft extension that specifies the color of the arrow elements of a scroll arrow.

**Syntax**: `<color>`

**Initial value**: `ButtonText`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarArrowColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbararrowcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6498

___

### msScrollbarBaseColor

• `Optional` **msScrollbarBaseColor**: [`MsScrollbarBaseColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarbasecolor)

The `**-ms-scrollbar-base-color**` CSS property is a Microsoft extension that specifies the base color of the main elements of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarBaseColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbarbasecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6506

___

### msScrollbarDarkshadowColor

• `Optional` **msScrollbarDarkshadowColor**: [`MsScrollbarDarkshadowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbardarkshadowcolor)

The **`-ms-scrollbar-darkshadow-color`** CSS property is a Microsoft extension that specifies the color of a scroll bar's gutter.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarDarkshadowColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbardarkshadowcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6514

___

### msScrollbarFaceColor

• `Optional` **msScrollbarFaceColor**: [`MsScrollbarFaceColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarfacecolor)

The `**-ms-scrollbar-face-color**` CSS property is a Microsoft extension that specifies the color of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDFace`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarFaceColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbarfacecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6522

___

### msScrollbarHighlightColor

• `Optional` **msScrollbarHighlightColor**: [`MsScrollbarHighlightColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarhighlightcolor)

The `**-ms-scrollbar-highlight-color**` CSS property is a Microsoft extension that specifies the color of the slider tray, the top and left edges of the scroll box, and the scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDHighlight`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarHighlightColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbarhighlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6530

___

### msScrollbarShadowColor

• `Optional` **msScrollbarShadowColor**: [`MsScrollbarShadowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarshadowcolor)

The **`-ms-scrollbar-shadow-color`** CSS property is a Microsoft extension that specifies the color of the bottom and right edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msScrollbarShadowColor](akashaproject_design_system._internal_.VendorProperties.md#msscrollbarshadowcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6538

___

### msScrollbarTrackColor

• `Optional` **msScrollbarTrackColor**: [`MsScrollbarTrackColor`](../modules/akashaproject_design_system._internal_.md#msscrollbartrackcolor)

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[msScrollbarTrackColor](akashaproject_design_system._internal_.ObsoleteProperties.md#msscrollbartrackcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8430

___

### msTextAutospace

• `Optional` **msTextAutospace**: [`MsTextAutospace`](../modules/akashaproject_design_system._internal_.md#mstextautospace)

The **`-ms-text-autospace`** CSS property is a Microsoft extension that specifies the autospacing and narrow space width adjustment of text.

**Syntax**: `none | ideograph-alpha | ideograph-numeric | ideograph-parenthesis | ideograph-space`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTextAutospace](akashaproject_design_system._internal_.VendorProperties.md#mstextautospace)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6546

___

### msTextCombineHorizontal

• `Optional` **msTextCombineHorizontal**: [`TextCombineUpright`](../modules/akashaproject_design_system._internal_.md#textcombineupright)

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTextCombineHorizontal](akashaproject_design_system._internal_.VendorProperties.md#mstextcombinehorizontal)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6554

___

### msTextOverflow

• `Optional` **msTextOverflow**: [`TextOverflow`](../modules/akashaproject_design_system._internal_.md#textoverflow)

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTextOverflow](akashaproject_design_system._internal_.VendorProperties.md#mstextoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6562

___

### msTouchAction

• `Optional` **msTouchAction**: [`TouchAction`](../modules/akashaproject_design_system._internal_.md#touchaction)

The **`touch-action`** CSS property sets how an element's region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTouchAction](akashaproject_design_system._internal_.VendorProperties.md#mstouchaction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6570

___

### msTouchSelect

• `Optional` **msTouchSelect**: [`MsTouchSelect`](../modules/akashaproject_design_system._internal_.md#mstouchselect)

The **`-ms-touch-select`** CSS property is a Microsoft extension that toggles the gripper visual elements that enable touch text selection.

**Syntax**: `grippers | none`

**Initial value**: `grippers`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTouchSelect](akashaproject_design_system._internal_.VendorProperties.md#mstouchselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6578

___

### msTransform

• `Optional` **msTransform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransform](akashaproject_design_system._internal_.VendorProperties.md#mstransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6586

___

### msTransformOrigin

• `Optional` **msTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`TLength`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransformOrigin](akashaproject_design_system._internal_.VendorProperties.md#mstransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6594

___

### msTransition

• `Optional` **msTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`TTime`\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransition](akashaproject_design_system._internal_.VendorProperties.md#mstransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7605

___

### msTransitionDelay

• `Optional` **msTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`TTime`\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransitionDelay](akashaproject_design_system._internal_.VendorProperties.md#mstransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6602

___

### msTransitionDuration

• `Optional` **msTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`TTime`\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransitionDuration](akashaproject_design_system._internal_.VendorProperties.md#mstransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6610

___

### msTransitionProperty

• `Optional` **msTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransitionProperty](akashaproject_design_system._internal_.VendorProperties.md#mstransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6618

___

### msTransitionTimingFunction

• `Optional` **msTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msTransitionTimingFunction](akashaproject_design_system._internal_.VendorProperties.md#mstransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6626

___

### msUserSelect

• `Optional` **msUserSelect**: [`MsUserSelect`](../modules/akashaproject_design_system._internal_.md#msuserselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `none | element | text`

**Initial value**: `text`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msUserSelect](akashaproject_design_system._internal_.VendorProperties.md#msuserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6634

___

### msWordBreak

• `Optional` **msWordBreak**: [`WordBreak`](../modules/akashaproject_design_system._internal_.md#wordbreak)

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msWordBreak](akashaproject_design_system._internal_.VendorProperties.md#mswordbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6642

___

### msWrapFlow

• `Optional` **msWrapFlow**: [`MsWrapFlow`](../modules/akashaproject_design_system._internal_.md#mswrapflow)

The **`-ms-wrap-flow`** CSS property is a Microsoft extension that specifies how exclusions impact inline content within block-level elements.

**Syntax**: `auto | both | start | end | maximum | clear`

**Initial value**: `auto`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msWrapFlow](akashaproject_design_system._internal_.VendorProperties.md#mswrapflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6650

___

### msWrapMargin

• `Optional` **msWrapMargin**: [`MsWrapMargin`](../modules/akashaproject_design_system._internal_.md#mswrapmargin)<`TLength`\>

The **`-ms-wrap-margin`** CSS property is a Microsoft extension that specifies a margin that offsets the inner wrap shape from other shapes.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msWrapMargin](akashaproject_design_system._internal_.VendorProperties.md#mswrapmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6658

___

### msWrapThrough

• `Optional` **msWrapThrough**: [`MsWrapThrough`](../modules/akashaproject_design_system._internal_.md#mswrapthrough)

The **`-ms-wrap-through`** CSS property is a Microsoft extension that specifies how content should wrap around an exclusion element.

**Syntax**: `wrap | none`

**Initial value**: `wrap`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msWrapThrough](akashaproject_design_system._internal_.VendorProperties.md#mswrapthrough)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6666

___

### msWritingMode

• `Optional` **msWritingMode**: [`WritingMode`](../modules/akashaproject_design_system._internal_.md#writingmode)

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (`html` element for HTML documents).

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorProperties](akashaproject_design_system._internal_.VendorProperties.md).[msWritingMode](akashaproject_design_system._internal_.VendorProperties.md#mswritingmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6674

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[objectFit](akashaproject_design_system._internal_.StandardProperties.md#objectfit)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[objectPosition](akashaproject_design_system._internal_.StandardProperties.md#objectposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offset](akashaproject_design_system._internal_.StandardProperties.md#offset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offsetAnchor](akashaproject_design_system._internal_.StandardProperties.md#offsetanchor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3164

___

### offsetBlock

• `Optional` **offsetBlock**: [`InsetBlock`](../modules/akashaproject_design_system._internal_.md#insetblock)<`TLength`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetBlock](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7846

___

### offsetBlockEnd

• `Optional` **offsetBlockEnd**: [`InsetBlockEnd`](../modules/akashaproject_design_system._internal_.md#insetblockend)<`TLength`\>

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetBlockEnd](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7856

___

### offsetBlockStart

• `Optional` **offsetBlockStart**: [`InsetBlockStart`](../modules/akashaproject_design_system._internal_.md#insetblockstart)<`TLength`\>

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetBlockStart](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7866

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offsetDistance](akashaproject_design_system._internal_.StandardProperties.md#offsetdistance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3179

___

### offsetInline

• `Optional` **offsetInline**: [`InsetInline`](../modules/akashaproject_design_system._internal_.md#insetinline)<`TLength`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetInline](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7876

___

### offsetInlineEnd

• `Optional` **offsetInlineEnd**: [`InsetInlineEnd`](../modules/akashaproject_design_system._internal_.md#insetinlineend)<`TLength`\>

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetInlineEnd](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetinlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7886

___

### offsetInlineStart

• `Optional` **offsetInlineStart**: [`InsetInlineStart`](../modules/akashaproject_design_system._internal_.md#insetinlinestart)<`TLength`\>

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[offsetInlineStart](akashaproject_design_system._internal_.ObsoleteProperties.md#offsetinlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7896

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offsetPath](akashaproject_design_system._internal_.StandardProperties.md#offsetpath)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offsetRotate](akashaproject_design_system._internal_.StandardProperties.md#offsetrotate)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[offsetRotation](akashaproject_design_system._internal_.StandardProperties.md#offsetrotation)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[opacity](akashaproject_design_system._internal_.SvgProperties.md#opacity)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[order](akashaproject_design_system._internal_.StandardProperties.md#order)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[orphans](akashaproject_design_system._internal_.StandardProperties.md#orphans)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[outline](akashaproject_design_system._internal_.StandardProperties.md#outline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[outlineColor](akashaproject_design_system._internal_.StandardProperties.md#outlinecolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[outlineOffset](akashaproject_design_system._internal_.StandardProperties.md#outlineoffset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[outlineStyle](akashaproject_design_system._internal_.StandardProperties.md#outlinestyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[outlineWidth](akashaproject_design_system._internal_.StandardProperties.md#outlinewidth)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[overflow](akashaproject_design_system._internal_.SvgProperties.md#overflow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowAnchor](akashaproject_design_system._internal_.StandardProperties.md#overflowanchor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowBlock](akashaproject_design_system._internal_.StandardProperties.md#overflowblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowClipBox](akashaproject_design_system._internal_.StandardProperties.md#overflowclipbox)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowClipMargin](akashaproject_design_system._internal_.StandardProperties.md#overflowclipmargin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowInline](akashaproject_design_system._internal_.StandardProperties.md#overflowinline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowWrap](akashaproject_design_system._internal_.StandardProperties.md#overflowwrap)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowX](akashaproject_design_system._internal_.StandardProperties.md#overflowx)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overflowY](akashaproject_design_system._internal_.StandardProperties.md#overflowy)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overscrollBehavior](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehavior)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overscrollBehaviorBlock](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overscrollBehaviorInline](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorinline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overscrollBehaviorX](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviorx)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[overscrollBehaviorY](akashaproject_design_system._internal_.StandardProperties.md#overscrollbehaviory)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[padding](akashaproject_design_system._internal_.StandardProperties.md#padding)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingBlock](akashaproject_design_system._internal_.StandardProperties.md#paddingblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#paddingblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingBlockStart](akashaproject_design_system._internal_.StandardProperties.md#paddingblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingBottom](akashaproject_design_system._internal_.StandardProperties.md#paddingbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingInline](akashaproject_design_system._internal_.StandardProperties.md#paddinginline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#paddinginlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingInlineStart](akashaproject_design_system._internal_.StandardProperties.md#paddinginlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingLeft](akashaproject_design_system._internal_.StandardProperties.md#paddingleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingRight](akashaproject_design_system._internal_.StandardProperties.md#paddingright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[paddingTop](akashaproject_design_system._internal_.StandardProperties.md#paddingtop)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[pageBreakAfter](akashaproject_design_system._internal_.StandardProperties.md#pagebreakafter)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[pageBreakBefore](akashaproject_design_system._internal_.StandardProperties.md#pagebreakbefore)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[pageBreakInside](akashaproject_design_system._internal_.StandardProperties.md#pagebreakinside)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[paintOrder](akashaproject_design_system._internal_.SvgProperties.md#paintorder)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[perspective](akashaproject_design_system._internal_.StandardProperties.md#perspective)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[perspectiveOrigin](akashaproject_design_system._internal_.StandardProperties.md#perspectiveorigin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[placeContent](akashaproject_design_system._internal_.StandardProperties.md#placecontent)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[placeItems](akashaproject_design_system._internal_.StandardProperties.md#placeitems)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[placeSelf](akashaproject_design_system._internal_.StandardProperties.md#placeself)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[pointerEvents](akashaproject_design_system._internal_.SvgProperties.md#pointerevents)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[position](akashaproject_design_system._internal_.StandardProperties.md#position)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[quotes](akashaproject_design_system._internal_.StandardProperties.md#quotes)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[resize](akashaproject_design_system._internal_.StandardProperties.md#resize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[right](akashaproject_design_system._internal_.StandardProperties.md#right)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[rotate](akashaproject_design_system._internal_.StandardProperties.md#rotate)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[rowGap](akashaproject_design_system._internal_.StandardProperties.md#rowgap)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[rubyAlign](akashaproject_design_system._internal_.StandardProperties.md#rubyalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3853

___

### rubyMerge

• `Optional` **rubyMerge**: [`RubyMerge`](../modules/akashaproject_design_system._internal_.md#rubymerge)

**Syntax**: `separate | collapse | auto`

**Initial value**: `separate`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[rubyMerge](akashaproject_design_system._internal_.StandardProperties.md#rubymerge)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[rubyPosition](akashaproject_design_system._internal_.StandardProperties.md#rubyposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scale](akashaproject_design_system._internal_.StandardProperties.md#scale)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollBehavior](akashaproject_design_system._internal_.StandardProperties.md#scrollbehavior)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMargin](akashaproject_design_system._internal_.StandardProperties.md#scrollmargin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginBlock](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginBlockStart](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginInline](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginInlineStart](akashaproject_design_system._internal_.StandardProperties.md#scrollmargininlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginRight](akashaproject_design_system._internal_.StandardProperties.md#scrollmarginright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollMarginTop](akashaproject_design_system._internal_.StandardProperties.md#scrollmargintop)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPadding](akashaproject_design_system._internal_.StandardProperties.md#scrollpadding)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingBlock](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblock)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingBlockEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblockend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingBlockStart](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingblockstart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingInline](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingInlineEnd](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginlineend)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingInlineStart](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddinginlinestart)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingRight](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollPaddingTop](akashaproject_design_system._internal_.StandardProperties.md#scrollpaddingtop)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapAlign](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4229

___

### scrollSnapCoordinate

• `Optional` **scrollSnapCoordinate**: [`ScrollSnapCoordinate`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinate)<`TLength`\>

The **`scroll-snap-coordinate`** CSS property defines the x and y coordinate positions within an element that will align with its nearest ancestor scroll container's `scroll-snap-destination` for each respective axis.

**Syntax**: `none | <position>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapCoordinate](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnapcoordinate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7906

___

### scrollSnapDestination

• `Optional` **scrollSnapDestination**: [`ScrollSnapDestination`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestination)<`TLength`\>

The **`scroll-snap-destination`** CSS property defines the position in x and y coordinates within the scroll container's visual viewport which element snap points align with.

**Syntax**: `<position>`

**Initial value**: `0px 0px`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapDestination](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnapdestination)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7916

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapMargin](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmargin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapMarginBottom](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginbottom)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapMarginLeft](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginleft)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapMarginRight](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmarginright)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapMarginTop](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapmargintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4304

___

### scrollSnapPointsX

• `Optional` **scrollSnapPointsX**: [`ScrollSnapPointsX`](../modules/akashaproject_design_system._internal_.md#scrollsnappointsx)

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapPointsX](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnappointsx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7926

___

### scrollSnapPointsY

• `Optional` **scrollSnapPointsY**: [`ScrollSnapPointsY`](../modules/akashaproject_design_system._internal_.md#scrollsnappointsy)

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapPointsY](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnappointsy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7936

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapStop](akashaproject_design_system._internal_.StandardProperties.md#scrollsnapstop)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollSnapType](akashaproject_design_system._internal_.StandardProperties.md#scrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4333

___

### scrollSnapTypeX

• `Optional` **scrollSnapTypeX**: [`ScrollSnapTypeX`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypex)

The **`scroll-snap-type-x`** CSS property defines how strictly snap points are enforced on the horizontal axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapTypeX](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnaptypex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7946

___

### scrollSnapTypeY

• `Optional` **scrollSnapTypeY**: [`ScrollSnapTypeY`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypey)

The **`scroll-snap-type-y`** CSS property defines how strictly snap points are enforced on the vertical axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollSnapTypeY](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollsnaptypey)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7956

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollbarColor](akashaproject_design_system._internal_.StandardProperties.md#scrollbarcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollbarGutter](akashaproject_design_system._internal_.StandardProperties.md#scrollbargutter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4361

___

### scrollbarTrackColor

• `Optional` **scrollbarTrackColor**: [`MsScrollbarTrackColor`](../modules/akashaproject_design_system._internal_.md#msscrollbartrackcolor)

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Inherited from

[ObsoleteProperties](akashaproject_design_system._internal_.ObsoleteProperties.md).[scrollbarTrackColor](akashaproject_design_system._internal_.ObsoleteProperties.md#scrollbartrackcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7966

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[scrollbarWidth](akashaproject_design_system._internal_.StandardProperties.md#scrollbarwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[shapeImageThreshold](akashaproject_design_system._internal_.StandardProperties.md#shapeimagethreshold)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[shapeMargin](akashaproject_design_system._internal_.StandardProperties.md#shapemargin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[shapeOutside](akashaproject_design_system._internal_.StandardProperties.md#shapeoutside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4417

___

### shapeRendering

• `Optional` **shapeRendering**: [`ShapeRendering`](../modules/akashaproject_design_system._internal_.md#shaperendering)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[shapeRendering](akashaproject_design_system._internal_.SvgProperties.md#shaperendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8788

___

### stopColor

• `Optional` **stopColor**: [`StopColor`](../modules/akashaproject_design_system._internal_.md#stopcolor)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[stopColor](akashaproject_design_system._internal_.SvgProperties.md#stopcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8789

___

### stopOpacity

• `Optional` **stopOpacity**: [`StopOpacity`](../modules/akashaproject_design_system._internal_.md#stopopacity)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[stopOpacity](akashaproject_design_system._internal_.SvgProperties.md#stopopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8790

___

### stroke

• `Optional` **stroke**: [`Stroke`](../modules/akashaproject_design_system._internal_.md#stroke)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[stroke](akashaproject_design_system._internal_.SvgProperties.md#stroke)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8791

___

### strokeDasharray

• `Optional` **strokeDasharray**: [`StrokeDasharray`](../modules/akashaproject_design_system._internal_.md#strokedasharray)<`TLength`\>

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeDasharray](akashaproject_design_system._internal_.SvgProperties.md#strokedasharray)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8792

___

### strokeDashoffset

• `Optional` **strokeDashoffset**: [`StrokeDashoffset`](../modules/akashaproject_design_system._internal_.md#strokedashoffset)<`TLength`\>

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeDashoffset](akashaproject_design_system._internal_.SvgProperties.md#strokedashoffset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8793

___

### strokeLinecap

• `Optional` **strokeLinecap**: [`StrokeLinecap`](../modules/akashaproject_design_system._internal_.md#strokelinecap)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeLinecap](akashaproject_design_system._internal_.SvgProperties.md#strokelinecap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8794

___

### strokeLinejoin

• `Optional` **strokeLinejoin**: [`StrokeLinejoin`](../modules/akashaproject_design_system._internal_.md#strokelinejoin)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeLinejoin](akashaproject_design_system._internal_.SvgProperties.md#strokelinejoin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8795

___

### strokeMiterlimit

• `Optional` **strokeMiterlimit**: [`StrokeMiterlimit`](../modules/akashaproject_design_system._internal_.md#strokemiterlimit)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeMiterlimit](akashaproject_design_system._internal_.SvgProperties.md#strokemiterlimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8796

___

### strokeOpacity

• `Optional` **strokeOpacity**: [`StrokeOpacity`](../modules/akashaproject_design_system._internal_.md#strokeopacity)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeOpacity](akashaproject_design_system._internal_.SvgProperties.md#strokeopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8797

___

### strokeWidth

• `Optional` **strokeWidth**: [`StrokeWidth`](../modules/akashaproject_design_system._internal_.md#strokewidth)<`TLength`\>

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[strokeWidth](akashaproject_design_system._internal_.SvgProperties.md#strokewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8798

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[tabSize](akashaproject_design_system._internal_.StandardProperties.md#tabsize)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[tableLayout](akashaproject_design_system._internal_.StandardProperties.md#tablelayout)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textAlign](akashaproject_design_system._internal_.StandardProperties.md#textalign)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textAlignLast](akashaproject_design_system._internal_.StandardProperties.md#textalignlast)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4474

___

### textAnchor

• `Optional` **textAnchor**: [`TextAnchor`](../modules/akashaproject_design_system._internal_.md#textanchor)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[textAnchor](akashaproject_design_system._internal_.SvgProperties.md#textanchor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8799

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textCombineUpright](akashaproject_design_system._internal_.StandardProperties.md#textcombineupright)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[textDecoration](akashaproject_design_system._internal_.SvgProperties.md#textdecoration)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationColor](akashaproject_design_system._internal_.StandardProperties.md#textdecorationcolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationLine](akashaproject_design_system._internal_.StandardProperties.md#textdecorationline)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationSkip](akashaproject_design_system._internal_.StandardProperties.md#textdecorationskip)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationSkipInk](akashaproject_design_system._internal_.StandardProperties.md#textdecorationskipink)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationStyle](akashaproject_design_system._internal_.StandardProperties.md#textdecorationstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationThickness](akashaproject_design_system._internal_.StandardProperties.md#textdecorationthickness)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textDecorationWidth](akashaproject_design_system._internal_.StandardProperties.md#textdecorationwidth)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textEmphasis](akashaproject_design_system._internal_.StandardProperties.md#textemphasis)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textEmphasisColor](akashaproject_design_system._internal_.StandardProperties.md#textemphasiscolor)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textEmphasisPosition](akashaproject_design_system._internal_.StandardProperties.md#textemphasisposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textEmphasisStyle](akashaproject_design_system._internal_.StandardProperties.md#textemphasisstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textIndent](akashaproject_design_system._internal_.StandardProperties.md#textindent)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textJustify](akashaproject_design_system._internal_.StandardProperties.md#textjustify)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textOrientation](akashaproject_design_system._internal_.StandardProperties.md#textorientation)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textOverflow](akashaproject_design_system._internal_.StandardProperties.md#textoverflow)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[textRendering](akashaproject_design_system._internal_.SvgProperties.md#textrendering)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textShadow](akashaproject_design_system._internal_.StandardProperties.md#textshadow)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textSizeAdjust](akashaproject_design_system._internal_.StandardProperties.md#textsizeadjust)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textTransform](akashaproject_design_system._internal_.StandardProperties.md#texttransform)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textUnderlineOffset](akashaproject_design_system._internal_.StandardProperties.md#textunderlineoffset)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[textUnderlinePosition](akashaproject_design_system._internal_.StandardProperties.md#textunderlineposition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[top](akashaproject_design_system._internal_.StandardProperties.md#top)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[touchAction](akashaproject_design_system._internal_.StandardProperties.md#touchaction)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transform](akashaproject_design_system._internal_.StandardProperties.md#transform)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transformBox](akashaproject_design_system._internal_.StandardProperties.md#transformbox)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transformOrigin](akashaproject_design_system._internal_.StandardProperties.md#transformorigin)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transformStyle](akashaproject_design_system._internal_.StandardProperties.md#transformstyle)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transition](akashaproject_design_system._internal_.StandardProperties.md#transition)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transitionDelay](akashaproject_design_system._internal_.StandardProperties.md#transitiondelay)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transitionDuration](akashaproject_design_system._internal_.StandardProperties.md#transitionduration)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transitionProperty](akashaproject_design_system._internal_.StandardProperties.md#transitionproperty)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[transitionTimingFunction](akashaproject_design_system._internal_.StandardProperties.md#transitiontimingfunction)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[translate](akashaproject_design_system._internal_.StandardProperties.md#translate)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[unicodeBidi](akashaproject_design_system._internal_.SvgProperties.md#unicodebidi)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[userSelect](akashaproject_design_system._internal_.StandardProperties.md#userselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4966

___

### vectorEffect

• `Optional` **vectorEffect**: [`VectorEffect`](../modules/akashaproject_design_system._internal_.md#vectoreffect)

#### Inherited from

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[vectorEffect](akashaproject_design_system._internal_.SvgProperties.md#vectoreffect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8803

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[verticalAlign](akashaproject_design_system._internal_.StandardProperties.md#verticalalign)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[visibility](akashaproject_design_system._internal_.SvgProperties.md#visibility)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[whiteSpace](akashaproject_design_system._internal_.SvgProperties.md#whitespace)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[widows](akashaproject_design_system._internal_.StandardProperties.md#widows)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[width](akashaproject_design_system._internal_.StandardProperties.md#width)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[willChange](akashaproject_design_system._internal_.StandardProperties.md#willchange)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[wordBreak](akashaproject_design_system._internal_.StandardProperties.md#wordbreak)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[wordSpacing](akashaproject_design_system._internal_.SvgProperties.md#wordspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5078

___

### wordWrap

• `Optional` **wordWrap**: [`WordWrap`](../modules/akashaproject_design_system._internal_.md#wordwrap)

The `**overflow-wrap**` CSS property applies to inline elements, setting whether the browser should insert line breaks within an otherwise unbreakable string to prevent text from overflowing its line box.

**Syntax**: `normal | break-word`

**Initial value**: `normal`

#### Inherited from

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[wordWrap](akashaproject_design_system._internal_.StandardProperties.md#wordwrap)

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

[SvgProperties](akashaproject_design_system._internal_.SvgProperties.md).[writingMode](akashaproject_design_system._internal_.SvgProperties.md#writingmode)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[zIndex](akashaproject_design_system._internal_.StandardProperties.md#zindex)

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

[StandardProperties](akashaproject_design_system._internal_.StandardProperties.md).[zoom](akashaproject_design_system._internal_.StandardProperties.md#zoom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5129
