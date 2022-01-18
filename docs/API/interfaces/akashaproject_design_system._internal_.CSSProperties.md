[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / CSSProperties

# Interface: CSSProperties

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).CSSProperties

## Hierarchy

- [`Properties`](akashaproject_design_system._internal_.Properties.md)<`string` \| `number`\>

  ↳ **`CSSProperties`**

## Table of contents

### Properties

- [KhtmlBoxAlign](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxalign)
- [KhtmlBoxDirection](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxdirection)
- [KhtmlBoxFlex](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxflex)
- [KhtmlBoxFlexGroup](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxflexgroup)
- [KhtmlBoxLines](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxlines)
- [KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxordinalgroup)
- [KhtmlBoxOrient](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxorient)
- [KhtmlBoxPack](akashaproject_design_system._internal_.CSSProperties.md#khtmlboxpack)
- [KhtmlLineBreak](akashaproject_design_system._internal_.CSSProperties.md#khtmllinebreak)
- [KhtmlOpacity](akashaproject_design_system._internal_.CSSProperties.md#khtmlopacity)
- [KhtmlUserSelect](akashaproject_design_system._internal_.CSSProperties.md#khtmluserselect)
- [MozAnimation](akashaproject_design_system._internal_.CSSProperties.md#mozanimation)
- [MozAnimationDelay](akashaproject_design_system._internal_.CSSProperties.md#mozanimationdelay)
- [MozAnimationDirection](akashaproject_design_system._internal_.CSSProperties.md#mozanimationdirection)
- [MozAnimationDuration](akashaproject_design_system._internal_.CSSProperties.md#mozanimationduration)
- [MozAnimationFillMode](akashaproject_design_system._internal_.CSSProperties.md#mozanimationfillmode)
- [MozAnimationIterationCount](akashaproject_design_system._internal_.CSSProperties.md#mozanimationiterationcount)
- [MozAnimationName](akashaproject_design_system._internal_.CSSProperties.md#mozanimationname)
- [MozAnimationPlayState](akashaproject_design_system._internal_.CSSProperties.md#mozanimationplaystate)
- [MozAnimationTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#mozanimationtimingfunction)
- [MozAppearance](akashaproject_design_system._internal_.CSSProperties.md#mozappearance)
- [MozBackfaceVisibility](akashaproject_design_system._internal_.CSSProperties.md#mozbackfacevisibility)
- [MozBackgroundClip](akashaproject_design_system._internal_.CSSProperties.md#mozbackgroundclip)
- [MozBackgroundInlinePolicy](akashaproject_design_system._internal_.CSSProperties.md#mozbackgroundinlinepolicy)
- [MozBackgroundOrigin](akashaproject_design_system._internal_.CSSProperties.md#mozbackgroundorigin)
- [MozBackgroundSize](akashaproject_design_system._internal_.CSSProperties.md#mozbackgroundsize)
- [MozBinding](akashaproject_design_system._internal_.CSSProperties.md#mozbinding)
- [MozBorderBottomColors](akashaproject_design_system._internal_.CSSProperties.md#mozborderbottomcolors)
- [MozBorderEndColor](akashaproject_design_system._internal_.CSSProperties.md#mozborderendcolor)
- [MozBorderEndStyle](akashaproject_design_system._internal_.CSSProperties.md#mozborderendstyle)
- [MozBorderEndWidth](akashaproject_design_system._internal_.CSSProperties.md#mozborderendwidth)
- [MozBorderImage](akashaproject_design_system._internal_.CSSProperties.md#mozborderimage)
- [MozBorderLeftColors](akashaproject_design_system._internal_.CSSProperties.md#mozborderleftcolors)
- [MozBorderRadius](akashaproject_design_system._internal_.CSSProperties.md#mozborderradius)
- [MozBorderRadiusBottomleft](akashaproject_design_system._internal_.CSSProperties.md#mozborderradiusbottomleft)
- [MozBorderRadiusBottomright](akashaproject_design_system._internal_.CSSProperties.md#mozborderradiusbottomright)
- [MozBorderRadiusTopleft](akashaproject_design_system._internal_.CSSProperties.md#mozborderradiustopleft)
- [MozBorderRadiusTopright](akashaproject_design_system._internal_.CSSProperties.md#mozborderradiustopright)
- [MozBorderRightColors](akashaproject_design_system._internal_.CSSProperties.md#mozborderrightcolors)
- [MozBorderStartColor](akashaproject_design_system._internal_.CSSProperties.md#mozborderstartcolor)
- [MozBorderStartStyle](akashaproject_design_system._internal_.CSSProperties.md#mozborderstartstyle)
- [MozBorderTopColors](akashaproject_design_system._internal_.CSSProperties.md#mozbordertopcolors)
- [MozBoxAlign](akashaproject_design_system._internal_.CSSProperties.md#mozboxalign)
- [MozBoxDirection](akashaproject_design_system._internal_.CSSProperties.md#mozboxdirection)
- [MozBoxFlex](akashaproject_design_system._internal_.CSSProperties.md#mozboxflex)
- [MozBoxOrdinalGroup](akashaproject_design_system._internal_.CSSProperties.md#mozboxordinalgroup)
- [MozBoxOrient](akashaproject_design_system._internal_.CSSProperties.md#mozboxorient)
- [MozBoxPack](akashaproject_design_system._internal_.CSSProperties.md#mozboxpack)
- [MozBoxShadow](akashaproject_design_system._internal_.CSSProperties.md#mozboxshadow)
- [MozBoxSizing](akashaproject_design_system._internal_.CSSProperties.md#mozboxsizing)
- [MozColumnCount](akashaproject_design_system._internal_.CSSProperties.md#mozcolumncount)
- [MozColumnFill](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnfill)
- [MozColumnGap](akashaproject_design_system._internal_.CSSProperties.md#mozcolumngap)
- [MozColumnRule](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnrule)
- [MozColumnRuleColor](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnrulecolor)
- [MozColumnRuleStyle](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnrulestyle)
- [MozColumnRuleWidth](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnrulewidth)
- [MozColumnWidth](akashaproject_design_system._internal_.CSSProperties.md#mozcolumnwidth)
- [MozColumns](akashaproject_design_system._internal_.CSSProperties.md#mozcolumns)
- [MozContextProperties](akashaproject_design_system._internal_.CSSProperties.md#mozcontextproperties)
- [MozFloatEdge](akashaproject_design_system._internal_.CSSProperties.md#mozfloatedge)
- [MozFontFeatureSettings](akashaproject_design_system._internal_.CSSProperties.md#mozfontfeaturesettings)
- [MozFontLanguageOverride](akashaproject_design_system._internal_.CSSProperties.md#mozfontlanguageoverride)
- [MozForceBrokenImageIcon](akashaproject_design_system._internal_.CSSProperties.md#mozforcebrokenimageicon)
- [MozHyphens](akashaproject_design_system._internal_.CSSProperties.md#mozhyphens)
- [MozImageRegion](akashaproject_design_system._internal_.CSSProperties.md#mozimageregion)
- [MozMarginEnd](akashaproject_design_system._internal_.CSSProperties.md#mozmarginend)
- [MozMarginStart](akashaproject_design_system._internal_.CSSProperties.md#mozmarginstart)
- [MozOpacity](akashaproject_design_system._internal_.CSSProperties.md#mozopacity)
- [MozOrient](akashaproject_design_system._internal_.CSSProperties.md#mozorient)
- [MozOsxFontSmoothing](akashaproject_design_system._internal_.CSSProperties.md#mozosxfontsmoothing)
- [MozOutline](akashaproject_design_system._internal_.CSSProperties.md#mozoutline)
- [MozOutlineColor](akashaproject_design_system._internal_.CSSProperties.md#mozoutlinecolor)
- [MozOutlineRadius](akashaproject_design_system._internal_.CSSProperties.md#mozoutlineradius)
- [MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.CSSProperties.md#mozoutlineradiusbottomleft)
- [MozOutlineRadiusBottomright](akashaproject_design_system._internal_.CSSProperties.md#mozoutlineradiusbottomright)
- [MozOutlineRadiusTopleft](akashaproject_design_system._internal_.CSSProperties.md#mozoutlineradiustopleft)
- [MozOutlineRadiusTopright](akashaproject_design_system._internal_.CSSProperties.md#mozoutlineradiustopright)
- [MozOutlineStyle](akashaproject_design_system._internal_.CSSProperties.md#mozoutlinestyle)
- [MozOutlineWidth](akashaproject_design_system._internal_.CSSProperties.md#mozoutlinewidth)
- [MozPaddingEnd](akashaproject_design_system._internal_.CSSProperties.md#mozpaddingend)
- [MozPaddingStart](akashaproject_design_system._internal_.CSSProperties.md#mozpaddingstart)
- [MozPerspective](akashaproject_design_system._internal_.CSSProperties.md#mozperspective)
- [MozPerspectiveOrigin](akashaproject_design_system._internal_.CSSProperties.md#mozperspectiveorigin)
- [MozStackSizing](akashaproject_design_system._internal_.CSSProperties.md#mozstacksizing)
- [MozTabSize](akashaproject_design_system._internal_.CSSProperties.md#moztabsize)
- [MozTextAlignLast](akashaproject_design_system._internal_.CSSProperties.md#moztextalignlast)
- [MozTextBlink](akashaproject_design_system._internal_.CSSProperties.md#moztextblink)
- [MozTextDecorationColor](akashaproject_design_system._internal_.CSSProperties.md#moztextdecorationcolor)
- [MozTextDecorationLine](akashaproject_design_system._internal_.CSSProperties.md#moztextdecorationline)
- [MozTextDecorationStyle](akashaproject_design_system._internal_.CSSProperties.md#moztextdecorationstyle)
- [MozTextSizeAdjust](akashaproject_design_system._internal_.CSSProperties.md#moztextsizeadjust)
- [MozTransformOrigin](akashaproject_design_system._internal_.CSSProperties.md#moztransformorigin)
- [MozTransformStyle](akashaproject_design_system._internal_.CSSProperties.md#moztransformstyle)
- [MozTransition](akashaproject_design_system._internal_.CSSProperties.md#moztransition)
- [MozTransitionDelay](akashaproject_design_system._internal_.CSSProperties.md#moztransitiondelay)
- [MozTransitionDuration](akashaproject_design_system._internal_.CSSProperties.md#moztransitionduration)
- [MozTransitionProperty](akashaproject_design_system._internal_.CSSProperties.md#moztransitionproperty)
- [MozTransitionTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#moztransitiontimingfunction)
- [MozUserFocus](akashaproject_design_system._internal_.CSSProperties.md#mozuserfocus)
- [MozUserInput](akashaproject_design_system._internal_.CSSProperties.md#mozuserinput)
- [MozUserModify](akashaproject_design_system._internal_.CSSProperties.md#mozusermodify)
- [MozUserSelect](akashaproject_design_system._internal_.CSSProperties.md#mozuserselect)
- [MozWindowDragging](akashaproject_design_system._internal_.CSSProperties.md#mozwindowdragging)
- [MozWindowShadow](akashaproject_design_system._internal_.CSSProperties.md#mozwindowshadow)
- [OAnimation](akashaproject_design_system._internal_.CSSProperties.md#oanimation)
- [OAnimationDelay](akashaproject_design_system._internal_.CSSProperties.md#oanimationdelay)
- [OAnimationDirection](akashaproject_design_system._internal_.CSSProperties.md#oanimationdirection)
- [OAnimationDuration](akashaproject_design_system._internal_.CSSProperties.md#oanimationduration)
- [OAnimationFillMode](akashaproject_design_system._internal_.CSSProperties.md#oanimationfillmode)
- [OAnimationIterationCount](akashaproject_design_system._internal_.CSSProperties.md#oanimationiterationcount)
- [OAnimationName](akashaproject_design_system._internal_.CSSProperties.md#oanimationname)
- [OAnimationPlayState](akashaproject_design_system._internal_.CSSProperties.md#oanimationplaystate)
- [OAnimationTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#oanimationtimingfunction)
- [OBackgroundSize](akashaproject_design_system._internal_.CSSProperties.md#obackgroundsize)
- [OBorderImage](akashaproject_design_system._internal_.CSSProperties.md#oborderimage)
- [OObjectFit](akashaproject_design_system._internal_.CSSProperties.md#oobjectfit)
- [OObjectPosition](akashaproject_design_system._internal_.CSSProperties.md#oobjectposition)
- [OTabSize](akashaproject_design_system._internal_.CSSProperties.md#otabsize)
- [OTextOverflow](akashaproject_design_system._internal_.CSSProperties.md#otextoverflow)
- [OTransform](akashaproject_design_system._internal_.CSSProperties.md#otransform)
- [OTransformOrigin](akashaproject_design_system._internal_.CSSProperties.md#otransformorigin)
- [OTransition](akashaproject_design_system._internal_.CSSProperties.md#otransition)
- [OTransitionDelay](akashaproject_design_system._internal_.CSSProperties.md#otransitiondelay)
- [OTransitionDuration](akashaproject_design_system._internal_.CSSProperties.md#otransitionduration)
- [OTransitionProperty](akashaproject_design_system._internal_.CSSProperties.md#otransitionproperty)
- [OTransitionTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#otransitiontimingfunction)
- [WebkitAlignContent](akashaproject_design_system._internal_.CSSProperties.md#webkitaligncontent)
- [WebkitAlignItems](akashaproject_design_system._internal_.CSSProperties.md#webkitalignitems)
- [WebkitAlignSelf](akashaproject_design_system._internal_.CSSProperties.md#webkitalignself)
- [WebkitAnimation](akashaproject_design_system._internal_.CSSProperties.md#webkitanimation)
- [WebkitAnimationDelay](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationdelay)
- [WebkitAnimationDirection](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationdirection)
- [WebkitAnimationDuration](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationduration)
- [WebkitAnimationFillMode](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationfillmode)
- [WebkitAnimationIterationCount](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationiterationcount)
- [WebkitAnimationName](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationname)
- [WebkitAnimationPlayState](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationplaystate)
- [WebkitAnimationTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#webkitanimationtimingfunction)
- [WebkitAppearance](akashaproject_design_system._internal_.CSSProperties.md#webkitappearance)
- [WebkitBackdropFilter](akashaproject_design_system._internal_.CSSProperties.md#webkitbackdropfilter)
- [WebkitBackfaceVisibility](akashaproject_design_system._internal_.CSSProperties.md#webkitbackfacevisibility)
- [WebkitBackgroundClip](akashaproject_design_system._internal_.CSSProperties.md#webkitbackgroundclip)
- [WebkitBackgroundOrigin](akashaproject_design_system._internal_.CSSProperties.md#webkitbackgroundorigin)
- [WebkitBackgroundSize](akashaproject_design_system._internal_.CSSProperties.md#webkitbackgroundsize)
- [WebkitBorderBefore](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbefore)
- [WebkitBorderBeforeColor](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbeforecolor)
- [WebkitBorderBeforeStyle](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbeforestyle)
- [WebkitBorderBeforeWidth](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbeforewidth)
- [WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbottomleftradius)
- [WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.CSSProperties.md#webkitborderbottomrightradius)
- [WebkitBorderImage](akashaproject_design_system._internal_.CSSProperties.md#webkitborderimage)
- [WebkitBorderImageSlice](akashaproject_design_system._internal_.CSSProperties.md#webkitborderimageslice)
- [WebkitBorderRadius](akashaproject_design_system._internal_.CSSProperties.md#webkitborderradius)
- [WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.CSSProperties.md#webkitbordertopleftradius)
- [WebkitBorderTopRightRadius](akashaproject_design_system._internal_.CSSProperties.md#webkitbordertoprightradius)
- [WebkitBoxAlign](akashaproject_design_system._internal_.CSSProperties.md#webkitboxalign)
- [WebkitBoxDecorationBreak](akashaproject_design_system._internal_.CSSProperties.md#webkitboxdecorationbreak)
- [WebkitBoxDirection](akashaproject_design_system._internal_.CSSProperties.md#webkitboxdirection)
- [WebkitBoxFlex](akashaproject_design_system._internal_.CSSProperties.md#webkitboxflex)
- [WebkitBoxFlexGroup](akashaproject_design_system._internal_.CSSProperties.md#webkitboxflexgroup)
- [WebkitBoxLines](akashaproject_design_system._internal_.CSSProperties.md#webkitboxlines)
- [WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.CSSProperties.md#webkitboxordinalgroup)
- [WebkitBoxOrient](akashaproject_design_system._internal_.CSSProperties.md#webkitboxorient)
- [WebkitBoxPack](akashaproject_design_system._internal_.CSSProperties.md#webkitboxpack)
- [WebkitBoxReflect](akashaproject_design_system._internal_.CSSProperties.md#webkitboxreflect)
- [WebkitBoxShadow](akashaproject_design_system._internal_.CSSProperties.md#webkitboxshadow)
- [WebkitBoxSizing](akashaproject_design_system._internal_.CSSProperties.md#webkitboxsizing)
- [WebkitClipPath](akashaproject_design_system._internal_.CSSProperties.md#webkitclippath)
- [WebkitColumnCount](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumncount)
- [WebkitColumnFill](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnfill)
- [WebkitColumnGap](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumngap)
- [WebkitColumnRule](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnrule)
- [WebkitColumnRuleColor](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnrulecolor)
- [WebkitColumnRuleStyle](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnrulestyle)
- [WebkitColumnRuleWidth](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnrulewidth)
- [WebkitColumnSpan](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnspan)
- [WebkitColumnWidth](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumnwidth)
- [WebkitColumns](akashaproject_design_system._internal_.CSSProperties.md#webkitcolumns)
- [WebkitFilter](akashaproject_design_system._internal_.CSSProperties.md#webkitfilter)
- [WebkitFlex](akashaproject_design_system._internal_.CSSProperties.md#webkitflex)
- [WebkitFlexBasis](akashaproject_design_system._internal_.CSSProperties.md#webkitflexbasis)
- [WebkitFlexDirection](akashaproject_design_system._internal_.CSSProperties.md#webkitflexdirection)
- [WebkitFlexFlow](akashaproject_design_system._internal_.CSSProperties.md#webkitflexflow)
- [WebkitFlexGrow](akashaproject_design_system._internal_.CSSProperties.md#webkitflexgrow)
- [WebkitFlexShrink](akashaproject_design_system._internal_.CSSProperties.md#webkitflexshrink)
- [WebkitFlexWrap](akashaproject_design_system._internal_.CSSProperties.md#webkitflexwrap)
- [WebkitFontFeatureSettings](akashaproject_design_system._internal_.CSSProperties.md#webkitfontfeaturesettings)
- [WebkitFontKerning](akashaproject_design_system._internal_.CSSProperties.md#webkitfontkerning)
- [WebkitFontSmoothing](akashaproject_design_system._internal_.CSSProperties.md#webkitfontsmoothing)
- [WebkitFontVariantLigatures](akashaproject_design_system._internal_.CSSProperties.md#webkitfontvariantligatures)
- [WebkitHyphens](akashaproject_design_system._internal_.CSSProperties.md#webkithyphens)
- [WebkitJustifyContent](akashaproject_design_system._internal_.CSSProperties.md#webkitjustifycontent)
- [WebkitLineBreak](akashaproject_design_system._internal_.CSSProperties.md#webkitlinebreak)
- [WebkitLineClamp](akashaproject_design_system._internal_.CSSProperties.md#webkitlineclamp)
- [WebkitMarginEnd](akashaproject_design_system._internal_.CSSProperties.md#webkitmarginend)
- [WebkitMarginStart](akashaproject_design_system._internal_.CSSProperties.md#webkitmarginstart)
- [WebkitMask](akashaproject_design_system._internal_.CSSProperties.md#webkitmask)
- [WebkitMaskAttachment](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskattachment)
- [WebkitMaskBoxImage](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximage)
- [WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximageoutset)
- [WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximagerepeat)
- [WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximageslice)
- [WebkitMaskBoxImageSource](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximagesource)
- [WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskboximagewidth)
- [WebkitMaskClip](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskclip)
- [WebkitMaskComposite](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskcomposite)
- [WebkitMaskImage](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskimage)
- [WebkitMaskOrigin](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskorigin)
- [WebkitMaskPosition](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskposition)
- [WebkitMaskPositionX](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskpositionx)
- [WebkitMaskPositionY](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskpositiony)
- [WebkitMaskRepeat](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskrepeat)
- [WebkitMaskRepeatX](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskrepeatx)
- [WebkitMaskRepeatY](akashaproject_design_system._internal_.CSSProperties.md#webkitmaskrepeaty)
- [WebkitMaskSize](akashaproject_design_system._internal_.CSSProperties.md#webkitmasksize)
- [WebkitMaxInlineSize](akashaproject_design_system._internal_.CSSProperties.md#webkitmaxinlinesize)
- [WebkitOrder](akashaproject_design_system._internal_.CSSProperties.md#webkitorder)
- [WebkitOverflowScrolling](akashaproject_design_system._internal_.CSSProperties.md#webkitoverflowscrolling)
- [WebkitPaddingEnd](akashaproject_design_system._internal_.CSSProperties.md#webkitpaddingend)
- [WebkitPaddingStart](akashaproject_design_system._internal_.CSSProperties.md#webkitpaddingstart)
- [WebkitPerspective](akashaproject_design_system._internal_.CSSProperties.md#webkitperspective)
- [WebkitPerspectiveOrigin](akashaproject_design_system._internal_.CSSProperties.md#webkitperspectiveorigin)
- [WebkitPrintColorAdjust](akashaproject_design_system._internal_.CSSProperties.md#webkitprintcoloradjust)
- [WebkitRubyPosition](akashaproject_design_system._internal_.CSSProperties.md#webkitrubyposition)
- [WebkitScrollSnapPointsX](akashaproject_design_system._internal_.CSSProperties.md#webkitscrollsnappointsx)
- [WebkitScrollSnapPointsY](akashaproject_design_system._internal_.CSSProperties.md#webkitscrollsnappointsy)
- [WebkitScrollSnapType](akashaproject_design_system._internal_.CSSProperties.md#webkitscrollsnaptype)
- [WebkitShapeMargin](akashaproject_design_system._internal_.CSSProperties.md#webkitshapemargin)
- [WebkitTapHighlightColor](akashaproject_design_system._internal_.CSSProperties.md#webkittaphighlightcolor)
- [WebkitTextCombine](akashaproject_design_system._internal_.CSSProperties.md#webkittextcombine)
- [WebkitTextDecorationColor](akashaproject_design_system._internal_.CSSProperties.md#webkittextdecorationcolor)
- [WebkitTextDecorationLine](akashaproject_design_system._internal_.CSSProperties.md#webkittextdecorationline)
- [WebkitTextDecorationSkip](akashaproject_design_system._internal_.CSSProperties.md#webkittextdecorationskip)
- [WebkitTextDecorationStyle](akashaproject_design_system._internal_.CSSProperties.md#webkittextdecorationstyle)
- [WebkitTextEmphasis](akashaproject_design_system._internal_.CSSProperties.md#webkittextemphasis)
- [WebkitTextEmphasisColor](akashaproject_design_system._internal_.CSSProperties.md#webkittextemphasiscolor)
- [WebkitTextEmphasisPosition](akashaproject_design_system._internal_.CSSProperties.md#webkittextemphasisposition)
- [WebkitTextEmphasisStyle](akashaproject_design_system._internal_.CSSProperties.md#webkittextemphasisstyle)
- [WebkitTextFillColor](akashaproject_design_system._internal_.CSSProperties.md#webkittextfillcolor)
- [WebkitTextOrientation](akashaproject_design_system._internal_.CSSProperties.md#webkittextorientation)
- [WebkitTextSizeAdjust](akashaproject_design_system._internal_.CSSProperties.md#webkittextsizeadjust)
- [WebkitTextStroke](akashaproject_design_system._internal_.CSSProperties.md#webkittextstroke)
- [WebkitTextStrokeColor](akashaproject_design_system._internal_.CSSProperties.md#webkittextstrokecolor)
- [WebkitTextStrokeWidth](akashaproject_design_system._internal_.CSSProperties.md#webkittextstrokewidth)
- [WebkitTextUnderlinePosition](akashaproject_design_system._internal_.CSSProperties.md#webkittextunderlineposition)
- [WebkitTouchCallout](akashaproject_design_system._internal_.CSSProperties.md#webkittouchcallout)
- [WebkitTransform](akashaproject_design_system._internal_.CSSProperties.md#webkittransform)
- [WebkitTransformOrigin](akashaproject_design_system._internal_.CSSProperties.md#webkittransformorigin)
- [WebkitTransformStyle](akashaproject_design_system._internal_.CSSProperties.md#webkittransformstyle)
- [WebkitTransition](akashaproject_design_system._internal_.CSSProperties.md#webkittransition)
- [WebkitTransitionDelay](akashaproject_design_system._internal_.CSSProperties.md#webkittransitiondelay)
- [WebkitTransitionDuration](akashaproject_design_system._internal_.CSSProperties.md#webkittransitionduration)
- [WebkitTransitionProperty](akashaproject_design_system._internal_.CSSProperties.md#webkittransitionproperty)
- [WebkitTransitionTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#webkittransitiontimingfunction)
- [WebkitUserModify](akashaproject_design_system._internal_.CSSProperties.md#webkitusermodify)
- [WebkitUserSelect](akashaproject_design_system._internal_.CSSProperties.md#webkituserselect)
- [WebkitWritingMode](akashaproject_design_system._internal_.CSSProperties.md#webkitwritingmode)
- [accentColor](akashaproject_design_system._internal_.CSSProperties.md#accentcolor)
- [alignContent](akashaproject_design_system._internal_.CSSProperties.md#aligncontent)
- [alignItems](akashaproject_design_system._internal_.CSSProperties.md#alignitems)
- [alignSelf](akashaproject_design_system._internal_.CSSProperties.md#alignself)
- [alignTracks](akashaproject_design_system._internal_.CSSProperties.md#aligntracks)
- [alignmentBaseline](akashaproject_design_system._internal_.CSSProperties.md#alignmentbaseline)
- [all](akashaproject_design_system._internal_.CSSProperties.md#all)
- [animation](akashaproject_design_system._internal_.CSSProperties.md#animation)
- [animationDelay](akashaproject_design_system._internal_.CSSProperties.md#animationdelay)
- [animationDirection](akashaproject_design_system._internal_.CSSProperties.md#animationdirection)
- [animationDuration](akashaproject_design_system._internal_.CSSProperties.md#animationduration)
- [animationFillMode](akashaproject_design_system._internal_.CSSProperties.md#animationfillmode)
- [animationIterationCount](akashaproject_design_system._internal_.CSSProperties.md#animationiterationcount)
- [animationName](akashaproject_design_system._internal_.CSSProperties.md#animationname)
- [animationPlayState](akashaproject_design_system._internal_.CSSProperties.md#animationplaystate)
- [animationTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#animationtimingfunction)
- [appearance](akashaproject_design_system._internal_.CSSProperties.md#appearance)
- [aspectRatio](akashaproject_design_system._internal_.CSSProperties.md#aspectratio)
- [azimuth](akashaproject_design_system._internal_.CSSProperties.md#azimuth)
- [backdropFilter](akashaproject_design_system._internal_.CSSProperties.md#backdropfilter)
- [backfaceVisibility](akashaproject_design_system._internal_.CSSProperties.md#backfacevisibility)
- [background](akashaproject_design_system._internal_.CSSProperties.md#background)
- [backgroundAttachment](akashaproject_design_system._internal_.CSSProperties.md#backgroundattachment)
- [backgroundBlendMode](akashaproject_design_system._internal_.CSSProperties.md#backgroundblendmode)
- [backgroundClip](akashaproject_design_system._internal_.CSSProperties.md#backgroundclip)
- [backgroundColor](akashaproject_design_system._internal_.CSSProperties.md#backgroundcolor)
- [backgroundImage](akashaproject_design_system._internal_.CSSProperties.md#backgroundimage)
- [backgroundOrigin](akashaproject_design_system._internal_.CSSProperties.md#backgroundorigin)
- [backgroundPosition](akashaproject_design_system._internal_.CSSProperties.md#backgroundposition)
- [backgroundPositionX](akashaproject_design_system._internal_.CSSProperties.md#backgroundpositionx)
- [backgroundPositionY](akashaproject_design_system._internal_.CSSProperties.md#backgroundpositiony)
- [backgroundRepeat](akashaproject_design_system._internal_.CSSProperties.md#backgroundrepeat)
- [backgroundSize](akashaproject_design_system._internal_.CSSProperties.md#backgroundsize)
- [baselineShift](akashaproject_design_system._internal_.CSSProperties.md#baselineshift)
- [blockOverflow](akashaproject_design_system._internal_.CSSProperties.md#blockoverflow)
- [blockSize](akashaproject_design_system._internal_.CSSProperties.md#blocksize)
- [border](akashaproject_design_system._internal_.CSSProperties.md#border)
- [borderBlock](akashaproject_design_system._internal_.CSSProperties.md#borderblock)
- [borderBlockColor](akashaproject_design_system._internal_.CSSProperties.md#borderblockcolor)
- [borderBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#borderblockend)
- [borderBlockEndColor](akashaproject_design_system._internal_.CSSProperties.md#borderblockendcolor)
- [borderBlockEndStyle](akashaproject_design_system._internal_.CSSProperties.md#borderblockendstyle)
- [borderBlockEndWidth](akashaproject_design_system._internal_.CSSProperties.md#borderblockendwidth)
- [borderBlockStart](akashaproject_design_system._internal_.CSSProperties.md#borderblockstart)
- [borderBlockStartColor](akashaproject_design_system._internal_.CSSProperties.md#borderblockstartcolor)
- [borderBlockStartStyle](akashaproject_design_system._internal_.CSSProperties.md#borderblockstartstyle)
- [borderBlockStartWidth](akashaproject_design_system._internal_.CSSProperties.md#borderblockstartwidth)
- [borderBlockStyle](akashaproject_design_system._internal_.CSSProperties.md#borderblockstyle)
- [borderBlockWidth](akashaproject_design_system._internal_.CSSProperties.md#borderblockwidth)
- [borderBottom](akashaproject_design_system._internal_.CSSProperties.md#borderbottom)
- [borderBottomColor](akashaproject_design_system._internal_.CSSProperties.md#borderbottomcolor)
- [borderBottomLeftRadius](akashaproject_design_system._internal_.CSSProperties.md#borderbottomleftradius)
- [borderBottomRightRadius](akashaproject_design_system._internal_.CSSProperties.md#borderbottomrightradius)
- [borderBottomStyle](akashaproject_design_system._internal_.CSSProperties.md#borderbottomstyle)
- [borderBottomWidth](akashaproject_design_system._internal_.CSSProperties.md#borderbottomwidth)
- [borderCollapse](akashaproject_design_system._internal_.CSSProperties.md#bordercollapse)
- [borderColor](akashaproject_design_system._internal_.CSSProperties.md#bordercolor)
- [borderEndEndRadius](akashaproject_design_system._internal_.CSSProperties.md#borderendendradius)
- [borderEndStartRadius](akashaproject_design_system._internal_.CSSProperties.md#borderendstartradius)
- [borderImage](akashaproject_design_system._internal_.CSSProperties.md#borderimage)
- [borderImageOutset](akashaproject_design_system._internal_.CSSProperties.md#borderimageoutset)
- [borderImageRepeat](akashaproject_design_system._internal_.CSSProperties.md#borderimagerepeat)
- [borderImageSlice](akashaproject_design_system._internal_.CSSProperties.md#borderimageslice)
- [borderImageSource](akashaproject_design_system._internal_.CSSProperties.md#borderimagesource)
- [borderImageWidth](akashaproject_design_system._internal_.CSSProperties.md#borderimagewidth)
- [borderInline](akashaproject_design_system._internal_.CSSProperties.md#borderinline)
- [borderInlineColor](akashaproject_design_system._internal_.CSSProperties.md#borderinlinecolor)
- [borderInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#borderinlineend)
- [borderInlineEndColor](akashaproject_design_system._internal_.CSSProperties.md#borderinlineendcolor)
- [borderInlineEndStyle](akashaproject_design_system._internal_.CSSProperties.md#borderinlineendstyle)
- [borderInlineEndWidth](akashaproject_design_system._internal_.CSSProperties.md#borderinlineendwidth)
- [borderInlineStart](akashaproject_design_system._internal_.CSSProperties.md#borderinlinestart)
- [borderInlineStartColor](akashaproject_design_system._internal_.CSSProperties.md#borderinlinestartcolor)
- [borderInlineStartStyle](akashaproject_design_system._internal_.CSSProperties.md#borderinlinestartstyle)
- [borderInlineStartWidth](akashaproject_design_system._internal_.CSSProperties.md#borderinlinestartwidth)
- [borderInlineStyle](akashaproject_design_system._internal_.CSSProperties.md#borderinlinestyle)
- [borderInlineWidth](akashaproject_design_system._internal_.CSSProperties.md#borderinlinewidth)
- [borderLeft](akashaproject_design_system._internal_.CSSProperties.md#borderleft)
- [borderLeftColor](akashaproject_design_system._internal_.CSSProperties.md#borderleftcolor)
- [borderLeftStyle](akashaproject_design_system._internal_.CSSProperties.md#borderleftstyle)
- [borderLeftWidth](akashaproject_design_system._internal_.CSSProperties.md#borderleftwidth)
- [borderRadius](akashaproject_design_system._internal_.CSSProperties.md#borderradius)
- [borderRight](akashaproject_design_system._internal_.CSSProperties.md#borderright)
- [borderRightColor](akashaproject_design_system._internal_.CSSProperties.md#borderrightcolor)
- [borderRightStyle](akashaproject_design_system._internal_.CSSProperties.md#borderrightstyle)
- [borderRightWidth](akashaproject_design_system._internal_.CSSProperties.md#borderrightwidth)
- [borderSpacing](akashaproject_design_system._internal_.CSSProperties.md#borderspacing)
- [borderStartEndRadius](akashaproject_design_system._internal_.CSSProperties.md#borderstartendradius)
- [borderStartStartRadius](akashaproject_design_system._internal_.CSSProperties.md#borderstartstartradius)
- [borderStyle](akashaproject_design_system._internal_.CSSProperties.md#borderstyle)
- [borderTop](akashaproject_design_system._internal_.CSSProperties.md#bordertop)
- [borderTopColor](akashaproject_design_system._internal_.CSSProperties.md#bordertopcolor)
- [borderTopLeftRadius](akashaproject_design_system._internal_.CSSProperties.md#bordertopleftradius)
- [borderTopRightRadius](akashaproject_design_system._internal_.CSSProperties.md#bordertoprightradius)
- [borderTopStyle](akashaproject_design_system._internal_.CSSProperties.md#bordertopstyle)
- [borderTopWidth](akashaproject_design_system._internal_.CSSProperties.md#bordertopwidth)
- [borderWidth](akashaproject_design_system._internal_.CSSProperties.md#borderwidth)
- [bottom](akashaproject_design_system._internal_.CSSProperties.md#bottom)
- [boxAlign](akashaproject_design_system._internal_.CSSProperties.md#boxalign)
- [boxDecorationBreak](akashaproject_design_system._internal_.CSSProperties.md#boxdecorationbreak)
- [boxDirection](akashaproject_design_system._internal_.CSSProperties.md#boxdirection)
- [boxFlex](akashaproject_design_system._internal_.CSSProperties.md#boxflex)
- [boxFlexGroup](akashaproject_design_system._internal_.CSSProperties.md#boxflexgroup)
- [boxLines](akashaproject_design_system._internal_.CSSProperties.md#boxlines)
- [boxOrdinalGroup](akashaproject_design_system._internal_.CSSProperties.md#boxordinalgroup)
- [boxOrient](akashaproject_design_system._internal_.CSSProperties.md#boxorient)
- [boxPack](akashaproject_design_system._internal_.CSSProperties.md#boxpack)
- [boxShadow](akashaproject_design_system._internal_.CSSProperties.md#boxshadow)
- [boxSizing](akashaproject_design_system._internal_.CSSProperties.md#boxsizing)
- [breakAfter](akashaproject_design_system._internal_.CSSProperties.md#breakafter)
- [breakBefore](akashaproject_design_system._internal_.CSSProperties.md#breakbefore)
- [breakInside](akashaproject_design_system._internal_.CSSProperties.md#breakinside)
- [captionSide](akashaproject_design_system._internal_.CSSProperties.md#captionside)
- [caretColor](akashaproject_design_system._internal_.CSSProperties.md#caretcolor)
- [clear](akashaproject_design_system._internal_.CSSProperties.md#clear)
- [clip](akashaproject_design_system._internal_.CSSProperties.md#clip)
- [clipPath](akashaproject_design_system._internal_.CSSProperties.md#clippath)
- [clipRule](akashaproject_design_system._internal_.CSSProperties.md#cliprule)
- [color](akashaproject_design_system._internal_.CSSProperties.md#color)
- [colorAdjust](akashaproject_design_system._internal_.CSSProperties.md#coloradjust)
- [colorInterpolation](akashaproject_design_system._internal_.CSSProperties.md#colorinterpolation)
- [colorRendering](akashaproject_design_system._internal_.CSSProperties.md#colorrendering)
- [colorScheme](akashaproject_design_system._internal_.CSSProperties.md#colorscheme)
- [columnCount](akashaproject_design_system._internal_.CSSProperties.md#columncount)
- [columnFill](akashaproject_design_system._internal_.CSSProperties.md#columnfill)
- [columnGap](akashaproject_design_system._internal_.CSSProperties.md#columngap)
- [columnRule](akashaproject_design_system._internal_.CSSProperties.md#columnrule)
- [columnRuleColor](akashaproject_design_system._internal_.CSSProperties.md#columnrulecolor)
- [columnRuleStyle](akashaproject_design_system._internal_.CSSProperties.md#columnrulestyle)
- [columnRuleWidth](akashaproject_design_system._internal_.CSSProperties.md#columnrulewidth)
- [columnSpan](akashaproject_design_system._internal_.CSSProperties.md#columnspan)
- [columnWidth](akashaproject_design_system._internal_.CSSProperties.md#columnwidth)
- [columns](akashaproject_design_system._internal_.CSSProperties.md#columns)
- [contain](akashaproject_design_system._internal_.CSSProperties.md#contain)
- [content](akashaproject_design_system._internal_.CSSProperties.md#content)
- [contentVisibility](akashaproject_design_system._internal_.CSSProperties.md#contentvisibility)
- [counterIncrement](akashaproject_design_system._internal_.CSSProperties.md#counterincrement)
- [counterReset](akashaproject_design_system._internal_.CSSProperties.md#counterreset)
- [counterSet](akashaproject_design_system._internal_.CSSProperties.md#counterset)
- [cursor](akashaproject_design_system._internal_.CSSProperties.md#cursor)
- [direction](akashaproject_design_system._internal_.CSSProperties.md#direction)
- [display](akashaproject_design_system._internal_.CSSProperties.md#display)
- [dominantBaseline](akashaproject_design_system._internal_.CSSProperties.md#dominantbaseline)
- [emptyCells](akashaproject_design_system._internal_.CSSProperties.md#emptycells)
- [fill](akashaproject_design_system._internal_.CSSProperties.md#fill)
- [fillOpacity](akashaproject_design_system._internal_.CSSProperties.md#fillopacity)
- [fillRule](akashaproject_design_system._internal_.CSSProperties.md#fillrule)
- [filter](akashaproject_design_system._internal_.CSSProperties.md#filter)
- [flex](akashaproject_design_system._internal_.CSSProperties.md#flex)
- [flexBasis](akashaproject_design_system._internal_.CSSProperties.md#flexbasis)
- [flexDirection](akashaproject_design_system._internal_.CSSProperties.md#flexdirection)
- [flexFlow](akashaproject_design_system._internal_.CSSProperties.md#flexflow)
- [flexGrow](akashaproject_design_system._internal_.CSSProperties.md#flexgrow)
- [flexShrink](akashaproject_design_system._internal_.CSSProperties.md#flexshrink)
- [flexWrap](akashaproject_design_system._internal_.CSSProperties.md#flexwrap)
- [float](akashaproject_design_system._internal_.CSSProperties.md#float)
- [floodColor](akashaproject_design_system._internal_.CSSProperties.md#floodcolor)
- [floodOpacity](akashaproject_design_system._internal_.CSSProperties.md#floodopacity)
- [font](akashaproject_design_system._internal_.CSSProperties.md#font)
- [fontFamily](akashaproject_design_system._internal_.CSSProperties.md#fontfamily)
- [fontFeatureSettings](akashaproject_design_system._internal_.CSSProperties.md#fontfeaturesettings)
- [fontKerning](akashaproject_design_system._internal_.CSSProperties.md#fontkerning)
- [fontLanguageOverride](akashaproject_design_system._internal_.CSSProperties.md#fontlanguageoverride)
- [fontOpticalSizing](akashaproject_design_system._internal_.CSSProperties.md#fontopticalsizing)
- [fontSize](akashaproject_design_system._internal_.CSSProperties.md#fontsize)
- [fontSizeAdjust](akashaproject_design_system._internal_.CSSProperties.md#fontsizeadjust)
- [fontSmooth](akashaproject_design_system._internal_.CSSProperties.md#fontsmooth)
- [fontStretch](akashaproject_design_system._internal_.CSSProperties.md#fontstretch)
- [fontStyle](akashaproject_design_system._internal_.CSSProperties.md#fontstyle)
- [fontSynthesis](akashaproject_design_system._internal_.CSSProperties.md#fontsynthesis)
- [fontVariant](akashaproject_design_system._internal_.CSSProperties.md#fontvariant)
- [fontVariantAlternates](akashaproject_design_system._internal_.CSSProperties.md#fontvariantalternates)
- [fontVariantCaps](akashaproject_design_system._internal_.CSSProperties.md#fontvariantcaps)
- [fontVariantEastAsian](akashaproject_design_system._internal_.CSSProperties.md#fontvarianteastasian)
- [fontVariantLigatures](akashaproject_design_system._internal_.CSSProperties.md#fontvariantligatures)
- [fontVariantNumeric](akashaproject_design_system._internal_.CSSProperties.md#fontvariantnumeric)
- [fontVariantPosition](akashaproject_design_system._internal_.CSSProperties.md#fontvariantposition)
- [fontVariationSettings](akashaproject_design_system._internal_.CSSProperties.md#fontvariationsettings)
- [fontWeight](akashaproject_design_system._internal_.CSSProperties.md#fontweight)
- [forcedColorAdjust](akashaproject_design_system._internal_.CSSProperties.md#forcedcoloradjust)
- [gap](akashaproject_design_system._internal_.CSSProperties.md#gap)
- [glyphOrientationVertical](akashaproject_design_system._internal_.CSSProperties.md#glyphorientationvertical)
- [grid](akashaproject_design_system._internal_.CSSProperties.md#grid)
- [gridArea](akashaproject_design_system._internal_.CSSProperties.md#gridarea)
- [gridAutoColumns](akashaproject_design_system._internal_.CSSProperties.md#gridautocolumns)
- [gridAutoFlow](akashaproject_design_system._internal_.CSSProperties.md#gridautoflow)
- [gridAutoRows](akashaproject_design_system._internal_.CSSProperties.md#gridautorows)
- [gridColumn](akashaproject_design_system._internal_.CSSProperties.md#gridcolumn)
- [gridColumnEnd](akashaproject_design_system._internal_.CSSProperties.md#gridcolumnend)
- [gridColumnGap](akashaproject_design_system._internal_.CSSProperties.md#gridcolumngap)
- [gridColumnStart](akashaproject_design_system._internal_.CSSProperties.md#gridcolumnstart)
- [gridGap](akashaproject_design_system._internal_.CSSProperties.md#gridgap)
- [gridRow](akashaproject_design_system._internal_.CSSProperties.md#gridrow)
- [gridRowEnd](akashaproject_design_system._internal_.CSSProperties.md#gridrowend)
- [gridRowGap](akashaproject_design_system._internal_.CSSProperties.md#gridrowgap)
- [gridRowStart](akashaproject_design_system._internal_.CSSProperties.md#gridrowstart)
- [gridTemplate](akashaproject_design_system._internal_.CSSProperties.md#gridtemplate)
- [gridTemplateAreas](akashaproject_design_system._internal_.CSSProperties.md#gridtemplateareas)
- [gridTemplateColumns](akashaproject_design_system._internal_.CSSProperties.md#gridtemplatecolumns)
- [gridTemplateRows](akashaproject_design_system._internal_.CSSProperties.md#gridtemplaterows)
- [hangingPunctuation](akashaproject_design_system._internal_.CSSProperties.md#hangingpunctuation)
- [height](akashaproject_design_system._internal_.CSSProperties.md#height)
- [hyphens](akashaproject_design_system._internal_.CSSProperties.md#hyphens)
- [imageOrientation](akashaproject_design_system._internal_.CSSProperties.md#imageorientation)
- [imageRendering](akashaproject_design_system._internal_.CSSProperties.md#imagerendering)
- [imageResolution](akashaproject_design_system._internal_.CSSProperties.md#imageresolution)
- [imeMode](akashaproject_design_system._internal_.CSSProperties.md#imemode)
- [initialLetter](akashaproject_design_system._internal_.CSSProperties.md#initialletter)
- [inlineSize](akashaproject_design_system._internal_.CSSProperties.md#inlinesize)
- [inset](akashaproject_design_system._internal_.CSSProperties.md#inset)
- [insetBlock](akashaproject_design_system._internal_.CSSProperties.md#insetblock)
- [insetBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#insetblockend)
- [insetBlockStart](akashaproject_design_system._internal_.CSSProperties.md#insetblockstart)
- [insetInline](akashaproject_design_system._internal_.CSSProperties.md#insetinline)
- [insetInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#insetinlineend)
- [insetInlineStart](akashaproject_design_system._internal_.CSSProperties.md#insetinlinestart)
- [isolation](akashaproject_design_system._internal_.CSSProperties.md#isolation)
- [justifyContent](akashaproject_design_system._internal_.CSSProperties.md#justifycontent)
- [justifyItems](akashaproject_design_system._internal_.CSSProperties.md#justifyitems)
- [justifySelf](akashaproject_design_system._internal_.CSSProperties.md#justifyself)
- [justifyTracks](akashaproject_design_system._internal_.CSSProperties.md#justifytracks)
- [left](akashaproject_design_system._internal_.CSSProperties.md#left)
- [letterSpacing](akashaproject_design_system._internal_.CSSProperties.md#letterspacing)
- [lightingColor](akashaproject_design_system._internal_.CSSProperties.md#lightingcolor)
- [lineBreak](akashaproject_design_system._internal_.CSSProperties.md#linebreak)
- [lineClamp](akashaproject_design_system._internal_.CSSProperties.md#lineclamp)
- [lineHeight](akashaproject_design_system._internal_.CSSProperties.md#lineheight)
- [lineHeightStep](akashaproject_design_system._internal_.CSSProperties.md#lineheightstep)
- [listStyle](akashaproject_design_system._internal_.CSSProperties.md#liststyle)
- [listStyleImage](akashaproject_design_system._internal_.CSSProperties.md#liststyleimage)
- [listStylePosition](akashaproject_design_system._internal_.CSSProperties.md#liststyleposition)
- [listStyleType](akashaproject_design_system._internal_.CSSProperties.md#liststyletype)
- [margin](akashaproject_design_system._internal_.CSSProperties.md#margin)
- [marginBlock](akashaproject_design_system._internal_.CSSProperties.md#marginblock)
- [marginBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#marginblockend)
- [marginBlockStart](akashaproject_design_system._internal_.CSSProperties.md#marginblockstart)
- [marginBottom](akashaproject_design_system._internal_.CSSProperties.md#marginbottom)
- [marginInline](akashaproject_design_system._internal_.CSSProperties.md#margininline)
- [marginInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#margininlineend)
- [marginInlineStart](akashaproject_design_system._internal_.CSSProperties.md#margininlinestart)
- [marginLeft](akashaproject_design_system._internal_.CSSProperties.md#marginleft)
- [marginRight](akashaproject_design_system._internal_.CSSProperties.md#marginright)
- [marginTop](akashaproject_design_system._internal_.CSSProperties.md#margintop)
- [marker](akashaproject_design_system._internal_.CSSProperties.md#marker)
- [markerEnd](akashaproject_design_system._internal_.CSSProperties.md#markerend)
- [markerMid](akashaproject_design_system._internal_.CSSProperties.md#markermid)
- [markerStart](akashaproject_design_system._internal_.CSSProperties.md#markerstart)
- [mask](akashaproject_design_system._internal_.CSSProperties.md#mask)
- [maskBorder](akashaproject_design_system._internal_.CSSProperties.md#maskborder)
- [maskBorderMode](akashaproject_design_system._internal_.CSSProperties.md#maskbordermode)
- [maskBorderOutset](akashaproject_design_system._internal_.CSSProperties.md#maskborderoutset)
- [maskBorderRepeat](akashaproject_design_system._internal_.CSSProperties.md#maskborderrepeat)
- [maskBorderSlice](akashaproject_design_system._internal_.CSSProperties.md#maskborderslice)
- [maskBorderSource](akashaproject_design_system._internal_.CSSProperties.md#maskbordersource)
- [maskBorderWidth](akashaproject_design_system._internal_.CSSProperties.md#maskborderwidth)
- [maskClip](akashaproject_design_system._internal_.CSSProperties.md#maskclip)
- [maskComposite](akashaproject_design_system._internal_.CSSProperties.md#maskcomposite)
- [maskImage](akashaproject_design_system._internal_.CSSProperties.md#maskimage)
- [maskMode](akashaproject_design_system._internal_.CSSProperties.md#maskmode)
- [maskOrigin](akashaproject_design_system._internal_.CSSProperties.md#maskorigin)
- [maskPosition](akashaproject_design_system._internal_.CSSProperties.md#maskposition)
- [maskRepeat](akashaproject_design_system._internal_.CSSProperties.md#maskrepeat)
- [maskSize](akashaproject_design_system._internal_.CSSProperties.md#masksize)
- [maskType](akashaproject_design_system._internal_.CSSProperties.md#masktype)
- [mathStyle](akashaproject_design_system._internal_.CSSProperties.md#mathstyle)
- [maxBlockSize](akashaproject_design_system._internal_.CSSProperties.md#maxblocksize)
- [maxHeight](akashaproject_design_system._internal_.CSSProperties.md#maxheight)
- [maxInlineSize](akashaproject_design_system._internal_.CSSProperties.md#maxinlinesize)
- [maxLines](akashaproject_design_system._internal_.CSSProperties.md#maxlines)
- [maxWidth](akashaproject_design_system._internal_.CSSProperties.md#maxwidth)
- [minBlockSize](akashaproject_design_system._internal_.CSSProperties.md#minblocksize)
- [minHeight](akashaproject_design_system._internal_.CSSProperties.md#minheight)
- [minInlineSize](akashaproject_design_system._internal_.CSSProperties.md#mininlinesize)
- [minWidth](akashaproject_design_system._internal_.CSSProperties.md#minwidth)
- [mixBlendMode](akashaproject_design_system._internal_.CSSProperties.md#mixblendmode)
- [motion](akashaproject_design_system._internal_.CSSProperties.md#motion)
- [motionDistance](akashaproject_design_system._internal_.CSSProperties.md#motiondistance)
- [motionPath](akashaproject_design_system._internal_.CSSProperties.md#motionpath)
- [motionRotation](akashaproject_design_system._internal_.CSSProperties.md#motionrotation)
- [msAccelerator](akashaproject_design_system._internal_.CSSProperties.md#msaccelerator)
- [msAlignSelf](akashaproject_design_system._internal_.CSSProperties.md#msalignself)
- [msBlockProgression](akashaproject_design_system._internal_.CSSProperties.md#msblockprogression)
- [msContentZoomChaining](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomchaining)
- [msContentZoomLimit](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomlimit)
- [msContentZoomLimitMax](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomlimitmax)
- [msContentZoomLimitMin](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomlimitmin)
- [msContentZoomSnap](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomsnap)
- [msContentZoomSnapPoints](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomsnappoints)
- [msContentZoomSnapType](akashaproject_design_system._internal_.CSSProperties.md#mscontentzoomsnaptype)
- [msContentZooming](akashaproject_design_system._internal_.CSSProperties.md#mscontentzooming)
- [msFilter](akashaproject_design_system._internal_.CSSProperties.md#msfilter)
- [msFlex](akashaproject_design_system._internal_.CSSProperties.md#msflex)
- [msFlexDirection](akashaproject_design_system._internal_.CSSProperties.md#msflexdirection)
- [msFlexPositive](akashaproject_design_system._internal_.CSSProperties.md#msflexpositive)
- [msFlowFrom](akashaproject_design_system._internal_.CSSProperties.md#msflowfrom)
- [msFlowInto](akashaproject_design_system._internal_.CSSProperties.md#msflowinto)
- [msGridColumns](akashaproject_design_system._internal_.CSSProperties.md#msgridcolumns)
- [msGridRows](akashaproject_design_system._internal_.CSSProperties.md#msgridrows)
- [msHighContrastAdjust](akashaproject_design_system._internal_.CSSProperties.md#mshighcontrastadjust)
- [msHyphenateLimitChars](akashaproject_design_system._internal_.CSSProperties.md#mshyphenatelimitchars)
- [msHyphenateLimitLines](akashaproject_design_system._internal_.CSSProperties.md#mshyphenatelimitlines)
- [msHyphenateLimitZone](akashaproject_design_system._internal_.CSSProperties.md#mshyphenatelimitzone)
- [msHyphens](akashaproject_design_system._internal_.CSSProperties.md#mshyphens)
- [msImeAlign](akashaproject_design_system._internal_.CSSProperties.md#msimealign)
- [msImeMode](akashaproject_design_system._internal_.CSSProperties.md#msimemode)
- [msJustifySelf](akashaproject_design_system._internal_.CSSProperties.md#msjustifyself)
- [msLineBreak](akashaproject_design_system._internal_.CSSProperties.md#mslinebreak)
- [msOrder](akashaproject_design_system._internal_.CSSProperties.md#msorder)
- [msOverflowStyle](akashaproject_design_system._internal_.CSSProperties.md#msoverflowstyle)
- [msOverflowX](akashaproject_design_system._internal_.CSSProperties.md#msoverflowx)
- [msOverflowY](akashaproject_design_system._internal_.CSSProperties.md#msoverflowy)
- [msScrollChaining](akashaproject_design_system._internal_.CSSProperties.md#msscrollchaining)
- [msScrollLimit](akashaproject_design_system._internal_.CSSProperties.md#msscrolllimit)
- [msScrollLimitXMax](akashaproject_design_system._internal_.CSSProperties.md#msscrolllimitxmax)
- [msScrollLimitXMin](akashaproject_design_system._internal_.CSSProperties.md#msscrolllimitxmin)
- [msScrollLimitYMax](akashaproject_design_system._internal_.CSSProperties.md#msscrolllimitymax)
- [msScrollLimitYMin](akashaproject_design_system._internal_.CSSProperties.md#msscrolllimitymin)
- [msScrollRails](akashaproject_design_system._internal_.CSSProperties.md#msscrollrails)
- [msScrollSnapPointsX](akashaproject_design_system._internal_.CSSProperties.md#msscrollsnappointsx)
- [msScrollSnapPointsY](akashaproject_design_system._internal_.CSSProperties.md#msscrollsnappointsy)
- [msScrollSnapType](akashaproject_design_system._internal_.CSSProperties.md#msscrollsnaptype)
- [msScrollSnapX](akashaproject_design_system._internal_.CSSProperties.md#msscrollsnapx)
- [msScrollSnapY](akashaproject_design_system._internal_.CSSProperties.md#msscrollsnapy)
- [msScrollTranslation](akashaproject_design_system._internal_.CSSProperties.md#msscrolltranslation)
- [msScrollbar3dlightColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbar3dlightcolor)
- [msScrollbarArrowColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbararrowcolor)
- [msScrollbarBaseColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbarbasecolor)
- [msScrollbarDarkshadowColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbardarkshadowcolor)
- [msScrollbarFaceColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbarfacecolor)
- [msScrollbarHighlightColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbarhighlightcolor)
- [msScrollbarShadowColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbarshadowcolor)
- [msScrollbarTrackColor](akashaproject_design_system._internal_.CSSProperties.md#msscrollbartrackcolor)
- [msTextAutospace](akashaproject_design_system._internal_.CSSProperties.md#mstextautospace)
- [msTextCombineHorizontal](akashaproject_design_system._internal_.CSSProperties.md#mstextcombinehorizontal)
- [msTextOverflow](akashaproject_design_system._internal_.CSSProperties.md#mstextoverflow)
- [msTouchAction](akashaproject_design_system._internal_.CSSProperties.md#mstouchaction)
- [msTouchSelect](akashaproject_design_system._internal_.CSSProperties.md#mstouchselect)
- [msTransform](akashaproject_design_system._internal_.CSSProperties.md#mstransform)
- [msTransformOrigin](akashaproject_design_system._internal_.CSSProperties.md#mstransformorigin)
- [msTransition](akashaproject_design_system._internal_.CSSProperties.md#mstransition)
- [msTransitionDelay](akashaproject_design_system._internal_.CSSProperties.md#mstransitiondelay)
- [msTransitionDuration](akashaproject_design_system._internal_.CSSProperties.md#mstransitionduration)
- [msTransitionProperty](akashaproject_design_system._internal_.CSSProperties.md#mstransitionproperty)
- [msTransitionTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#mstransitiontimingfunction)
- [msUserSelect](akashaproject_design_system._internal_.CSSProperties.md#msuserselect)
- [msWordBreak](akashaproject_design_system._internal_.CSSProperties.md#mswordbreak)
- [msWrapFlow](akashaproject_design_system._internal_.CSSProperties.md#mswrapflow)
- [msWrapMargin](akashaproject_design_system._internal_.CSSProperties.md#mswrapmargin)
- [msWrapThrough](akashaproject_design_system._internal_.CSSProperties.md#mswrapthrough)
- [msWritingMode](akashaproject_design_system._internal_.CSSProperties.md#mswritingmode)
- [objectFit](akashaproject_design_system._internal_.CSSProperties.md#objectfit)
- [objectPosition](akashaproject_design_system._internal_.CSSProperties.md#objectposition)
- [offset](akashaproject_design_system._internal_.CSSProperties.md#offset)
- [offsetAnchor](akashaproject_design_system._internal_.CSSProperties.md#offsetanchor)
- [offsetBlock](akashaproject_design_system._internal_.CSSProperties.md#offsetblock)
- [offsetBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#offsetblockend)
- [offsetBlockStart](akashaproject_design_system._internal_.CSSProperties.md#offsetblockstart)
- [offsetDistance](akashaproject_design_system._internal_.CSSProperties.md#offsetdistance)
- [offsetInline](akashaproject_design_system._internal_.CSSProperties.md#offsetinline)
- [offsetInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#offsetinlineend)
- [offsetInlineStart](akashaproject_design_system._internal_.CSSProperties.md#offsetinlinestart)
- [offsetPath](akashaproject_design_system._internal_.CSSProperties.md#offsetpath)
- [offsetRotate](akashaproject_design_system._internal_.CSSProperties.md#offsetrotate)
- [offsetRotation](akashaproject_design_system._internal_.CSSProperties.md#offsetrotation)
- [opacity](akashaproject_design_system._internal_.CSSProperties.md#opacity)
- [order](akashaproject_design_system._internal_.CSSProperties.md#order)
- [orphans](akashaproject_design_system._internal_.CSSProperties.md#orphans)
- [outline](akashaproject_design_system._internal_.CSSProperties.md#outline)
- [outlineColor](akashaproject_design_system._internal_.CSSProperties.md#outlinecolor)
- [outlineOffset](akashaproject_design_system._internal_.CSSProperties.md#outlineoffset)
- [outlineStyle](akashaproject_design_system._internal_.CSSProperties.md#outlinestyle)
- [outlineWidth](akashaproject_design_system._internal_.CSSProperties.md#outlinewidth)
- [overflow](akashaproject_design_system._internal_.CSSProperties.md#overflow)
- [overflowAnchor](akashaproject_design_system._internal_.CSSProperties.md#overflowanchor)
- [overflowBlock](akashaproject_design_system._internal_.CSSProperties.md#overflowblock)
- [overflowClipBox](akashaproject_design_system._internal_.CSSProperties.md#overflowclipbox)
- [overflowClipMargin](akashaproject_design_system._internal_.CSSProperties.md#overflowclipmargin)
- [overflowInline](akashaproject_design_system._internal_.CSSProperties.md#overflowinline)
- [overflowWrap](akashaproject_design_system._internal_.CSSProperties.md#overflowwrap)
- [overflowX](akashaproject_design_system._internal_.CSSProperties.md#overflowx)
- [overflowY](akashaproject_design_system._internal_.CSSProperties.md#overflowy)
- [overscrollBehavior](akashaproject_design_system._internal_.CSSProperties.md#overscrollbehavior)
- [overscrollBehaviorBlock](akashaproject_design_system._internal_.CSSProperties.md#overscrollbehaviorblock)
- [overscrollBehaviorInline](akashaproject_design_system._internal_.CSSProperties.md#overscrollbehaviorinline)
- [overscrollBehaviorX](akashaproject_design_system._internal_.CSSProperties.md#overscrollbehaviorx)
- [overscrollBehaviorY](akashaproject_design_system._internal_.CSSProperties.md#overscrollbehaviory)
- [padding](akashaproject_design_system._internal_.CSSProperties.md#padding)
- [paddingBlock](akashaproject_design_system._internal_.CSSProperties.md#paddingblock)
- [paddingBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#paddingblockend)
- [paddingBlockStart](akashaproject_design_system._internal_.CSSProperties.md#paddingblockstart)
- [paddingBottom](akashaproject_design_system._internal_.CSSProperties.md#paddingbottom)
- [paddingInline](akashaproject_design_system._internal_.CSSProperties.md#paddinginline)
- [paddingInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#paddinginlineend)
- [paddingInlineStart](akashaproject_design_system._internal_.CSSProperties.md#paddinginlinestart)
- [paddingLeft](akashaproject_design_system._internal_.CSSProperties.md#paddingleft)
- [paddingRight](akashaproject_design_system._internal_.CSSProperties.md#paddingright)
- [paddingTop](akashaproject_design_system._internal_.CSSProperties.md#paddingtop)
- [pageBreakAfter](akashaproject_design_system._internal_.CSSProperties.md#pagebreakafter)
- [pageBreakBefore](akashaproject_design_system._internal_.CSSProperties.md#pagebreakbefore)
- [pageBreakInside](akashaproject_design_system._internal_.CSSProperties.md#pagebreakinside)
- [paintOrder](akashaproject_design_system._internal_.CSSProperties.md#paintorder)
- [perspective](akashaproject_design_system._internal_.CSSProperties.md#perspective)
- [perspectiveOrigin](akashaproject_design_system._internal_.CSSProperties.md#perspectiveorigin)
- [placeContent](akashaproject_design_system._internal_.CSSProperties.md#placecontent)
- [placeItems](akashaproject_design_system._internal_.CSSProperties.md#placeitems)
- [placeSelf](akashaproject_design_system._internal_.CSSProperties.md#placeself)
- [pointerEvents](akashaproject_design_system._internal_.CSSProperties.md#pointerevents)
- [position](akashaproject_design_system._internal_.CSSProperties.md#position)
- [quotes](akashaproject_design_system._internal_.CSSProperties.md#quotes)
- [resize](akashaproject_design_system._internal_.CSSProperties.md#resize)
- [right](akashaproject_design_system._internal_.CSSProperties.md#right)
- [rotate](akashaproject_design_system._internal_.CSSProperties.md#rotate)
- [rowGap](akashaproject_design_system._internal_.CSSProperties.md#rowgap)
- [rubyAlign](akashaproject_design_system._internal_.CSSProperties.md#rubyalign)
- [rubyMerge](akashaproject_design_system._internal_.CSSProperties.md#rubymerge)
- [rubyPosition](akashaproject_design_system._internal_.CSSProperties.md#rubyposition)
- [scale](akashaproject_design_system._internal_.CSSProperties.md#scale)
- [scrollBehavior](akashaproject_design_system._internal_.CSSProperties.md#scrollbehavior)
- [scrollMargin](akashaproject_design_system._internal_.CSSProperties.md#scrollmargin)
- [scrollMarginBlock](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginblock)
- [scrollMarginBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginblockend)
- [scrollMarginBlockStart](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginblockstart)
- [scrollMarginBottom](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginbottom)
- [scrollMarginInline](akashaproject_design_system._internal_.CSSProperties.md#scrollmargininline)
- [scrollMarginInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#scrollmargininlineend)
- [scrollMarginInlineStart](akashaproject_design_system._internal_.CSSProperties.md#scrollmargininlinestart)
- [scrollMarginLeft](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginleft)
- [scrollMarginRight](akashaproject_design_system._internal_.CSSProperties.md#scrollmarginright)
- [scrollMarginTop](akashaproject_design_system._internal_.CSSProperties.md#scrollmargintop)
- [scrollPadding](akashaproject_design_system._internal_.CSSProperties.md#scrollpadding)
- [scrollPaddingBlock](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingblock)
- [scrollPaddingBlockEnd](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingblockend)
- [scrollPaddingBlockStart](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingblockstart)
- [scrollPaddingBottom](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingbottom)
- [scrollPaddingInline](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddinginline)
- [scrollPaddingInlineEnd](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddinginlineend)
- [scrollPaddingInlineStart](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddinginlinestart)
- [scrollPaddingLeft](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingleft)
- [scrollPaddingRight](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingright)
- [scrollPaddingTop](akashaproject_design_system._internal_.CSSProperties.md#scrollpaddingtop)
- [scrollSnapAlign](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapalign)
- [scrollSnapCoordinate](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapcoordinate)
- [scrollSnapDestination](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapdestination)
- [scrollSnapMargin](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapmargin)
- [scrollSnapMarginBottom](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapmarginbottom)
- [scrollSnapMarginLeft](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapmarginleft)
- [scrollSnapMarginRight](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapmarginright)
- [scrollSnapMarginTop](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapmargintop)
- [scrollSnapPointsX](akashaproject_design_system._internal_.CSSProperties.md#scrollsnappointsx)
- [scrollSnapPointsY](akashaproject_design_system._internal_.CSSProperties.md#scrollsnappointsy)
- [scrollSnapStop](akashaproject_design_system._internal_.CSSProperties.md#scrollsnapstop)
- [scrollSnapType](akashaproject_design_system._internal_.CSSProperties.md#scrollsnaptype)
- [scrollSnapTypeX](akashaproject_design_system._internal_.CSSProperties.md#scrollsnaptypex)
- [scrollSnapTypeY](akashaproject_design_system._internal_.CSSProperties.md#scrollsnaptypey)
- [scrollbarColor](akashaproject_design_system._internal_.CSSProperties.md#scrollbarcolor)
- [scrollbarGutter](akashaproject_design_system._internal_.CSSProperties.md#scrollbargutter)
- [scrollbarTrackColor](akashaproject_design_system._internal_.CSSProperties.md#scrollbartrackcolor)
- [scrollbarWidth](akashaproject_design_system._internal_.CSSProperties.md#scrollbarwidth)
- [shapeImageThreshold](akashaproject_design_system._internal_.CSSProperties.md#shapeimagethreshold)
- [shapeMargin](akashaproject_design_system._internal_.CSSProperties.md#shapemargin)
- [shapeOutside](akashaproject_design_system._internal_.CSSProperties.md#shapeoutside)
- [shapeRendering](akashaproject_design_system._internal_.CSSProperties.md#shaperendering)
- [stopColor](akashaproject_design_system._internal_.CSSProperties.md#stopcolor)
- [stopOpacity](akashaproject_design_system._internal_.CSSProperties.md#stopopacity)
- [stroke](akashaproject_design_system._internal_.CSSProperties.md#stroke)
- [strokeDasharray](akashaproject_design_system._internal_.CSSProperties.md#strokedasharray)
- [strokeDashoffset](akashaproject_design_system._internal_.CSSProperties.md#strokedashoffset)
- [strokeLinecap](akashaproject_design_system._internal_.CSSProperties.md#strokelinecap)
- [strokeLinejoin](akashaproject_design_system._internal_.CSSProperties.md#strokelinejoin)
- [strokeMiterlimit](akashaproject_design_system._internal_.CSSProperties.md#strokemiterlimit)
- [strokeOpacity](akashaproject_design_system._internal_.CSSProperties.md#strokeopacity)
- [strokeWidth](akashaproject_design_system._internal_.CSSProperties.md#strokewidth)
- [tabSize](akashaproject_design_system._internal_.CSSProperties.md#tabsize)
- [tableLayout](akashaproject_design_system._internal_.CSSProperties.md#tablelayout)
- [textAlign](akashaproject_design_system._internal_.CSSProperties.md#textalign)
- [textAlignLast](akashaproject_design_system._internal_.CSSProperties.md#textalignlast)
- [textAnchor](akashaproject_design_system._internal_.CSSProperties.md#textanchor)
- [textCombineUpright](akashaproject_design_system._internal_.CSSProperties.md#textcombineupright)
- [textDecoration](akashaproject_design_system._internal_.CSSProperties.md#textdecoration)
- [textDecorationColor](akashaproject_design_system._internal_.CSSProperties.md#textdecorationcolor)
- [textDecorationLine](akashaproject_design_system._internal_.CSSProperties.md#textdecorationline)
- [textDecorationSkip](akashaproject_design_system._internal_.CSSProperties.md#textdecorationskip)
- [textDecorationSkipInk](akashaproject_design_system._internal_.CSSProperties.md#textdecorationskipink)
- [textDecorationStyle](akashaproject_design_system._internal_.CSSProperties.md#textdecorationstyle)
- [textDecorationThickness](akashaproject_design_system._internal_.CSSProperties.md#textdecorationthickness)
- [textDecorationWidth](akashaproject_design_system._internal_.CSSProperties.md#textdecorationwidth)
- [textEmphasis](akashaproject_design_system._internal_.CSSProperties.md#textemphasis)
- [textEmphasisColor](akashaproject_design_system._internal_.CSSProperties.md#textemphasiscolor)
- [textEmphasisPosition](akashaproject_design_system._internal_.CSSProperties.md#textemphasisposition)
- [textEmphasisStyle](akashaproject_design_system._internal_.CSSProperties.md#textemphasisstyle)
- [textIndent](akashaproject_design_system._internal_.CSSProperties.md#textindent)
- [textJustify](akashaproject_design_system._internal_.CSSProperties.md#textjustify)
- [textOrientation](akashaproject_design_system._internal_.CSSProperties.md#textorientation)
- [textOverflow](akashaproject_design_system._internal_.CSSProperties.md#textoverflow)
- [textRendering](akashaproject_design_system._internal_.CSSProperties.md#textrendering)
- [textShadow](akashaproject_design_system._internal_.CSSProperties.md#textshadow)
- [textSizeAdjust](akashaproject_design_system._internal_.CSSProperties.md#textsizeadjust)
- [textTransform](akashaproject_design_system._internal_.CSSProperties.md#texttransform)
- [textUnderlineOffset](akashaproject_design_system._internal_.CSSProperties.md#textunderlineoffset)
- [textUnderlinePosition](akashaproject_design_system._internal_.CSSProperties.md#textunderlineposition)
- [top](akashaproject_design_system._internal_.CSSProperties.md#top)
- [touchAction](akashaproject_design_system._internal_.CSSProperties.md#touchaction)
- [transform](akashaproject_design_system._internal_.CSSProperties.md#transform)
- [transformBox](akashaproject_design_system._internal_.CSSProperties.md#transformbox)
- [transformOrigin](akashaproject_design_system._internal_.CSSProperties.md#transformorigin)
- [transformStyle](akashaproject_design_system._internal_.CSSProperties.md#transformstyle)
- [transition](akashaproject_design_system._internal_.CSSProperties.md#transition)
- [transitionDelay](akashaproject_design_system._internal_.CSSProperties.md#transitiondelay)
- [transitionDuration](akashaproject_design_system._internal_.CSSProperties.md#transitionduration)
- [transitionProperty](akashaproject_design_system._internal_.CSSProperties.md#transitionproperty)
- [transitionTimingFunction](akashaproject_design_system._internal_.CSSProperties.md#transitiontimingfunction)
- [translate](akashaproject_design_system._internal_.CSSProperties.md#translate)
- [unicodeBidi](akashaproject_design_system._internal_.CSSProperties.md#unicodebidi)
- [userSelect](akashaproject_design_system._internal_.CSSProperties.md#userselect)
- [vectorEffect](akashaproject_design_system._internal_.CSSProperties.md#vectoreffect)
- [verticalAlign](akashaproject_design_system._internal_.CSSProperties.md#verticalalign)
- [visibility](akashaproject_design_system._internal_.CSSProperties.md#visibility)
- [whiteSpace](akashaproject_design_system._internal_.CSSProperties.md#whitespace)
- [widows](akashaproject_design_system._internal_.CSSProperties.md#widows)
- [width](akashaproject_design_system._internal_.CSSProperties.md#width)
- [willChange](akashaproject_design_system._internal_.CSSProperties.md#willchange)
- [wordBreak](akashaproject_design_system._internal_.CSSProperties.md#wordbreak)
- [wordSpacing](akashaproject_design_system._internal_.CSSProperties.md#wordspacing)
- [wordWrap](akashaproject_design_system._internal_.CSSProperties.md#wordwrap)
- [writingMode](akashaproject_design_system._internal_.CSSProperties.md#writingmode)
- [zIndex](akashaproject_design_system._internal_.CSSProperties.md#zindex)
- [zoom](akashaproject_design_system._internal_.CSSProperties.md#zoom)

## Properties

### KhtmlBoxAlign

• `Optional` **KhtmlBoxAlign**: [`BoxAlign`](../modules/akashaproject_design_system._internal_.md#boxalign)

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxAlign](akashaproject_design_system._internal_.Properties.md#khtmlboxalign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxDirection](akashaproject_design_system._internal_.Properties.md#khtmlboxdirection)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxFlex](akashaproject_design_system._internal_.Properties.md#khtmlboxflex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxFlexGroup](akashaproject_design_system._internal_.Properties.md#khtmlboxflexgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxLines](akashaproject_design_system._internal_.Properties.md#khtmlboxlines)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#khtmlboxordinalgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxOrient](akashaproject_design_system._internal_.Properties.md#khtmlboxorient)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlBoxPack](akashaproject_design_system._internal_.Properties.md#khtmlboxpack)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlLineBreak](akashaproject_design_system._internal_.Properties.md#khtmllinebreak)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlOpacity](akashaproject_design_system._internal_.Properties.md#khtmlopacity)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[KhtmlUserSelect](akashaproject_design_system._internal_.Properties.md#khtmluserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8076

___

### MozAnimation

• `Optional` **MozAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`string` & {}\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimation](akashaproject_design_system._internal_.Properties.md#mozanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7539

___

### MozAnimationDelay

• `Optional` **MozAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`string` & {}\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationDelay](akashaproject_design_system._internal_.Properties.md#mozanimationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5746

___

### MozAnimationDirection

• `Optional` **MozAnimationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationDirection](akashaproject_design_system._internal_.Properties.md#mozanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5754

___

### MozAnimationDuration

• `Optional` **MozAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`string` & {}\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationDuration](akashaproject_design_system._internal_.Properties.md#mozanimationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5762

___

### MozAnimationFillMode

• `Optional` **MozAnimationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationFillMode](akashaproject_design_system._internal_.Properties.md#mozanimationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5770

___

### MozAnimationIterationCount

• `Optional` **MozAnimationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#mozanimationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5778

___

### MozAnimationName

• `Optional` **MozAnimationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationName](akashaproject_design_system._internal_.Properties.md#mozanimationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5786

___

### MozAnimationPlayState

• `Optional` **MozAnimationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationPlayState](akashaproject_design_system._internal_.Properties.md#mozanimationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5794

___

### MozAnimationTimingFunction

• `Optional` **MozAnimationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#mozanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5802

___

### MozAppearance

• `Optional` **MozAppearance**: [`MozAppearance`](../modules/akashaproject_design_system._internal_.md#mozappearance)

The `**appearance**` CSS property is used to display an element using platform-native styling, based on the operating system's theme. The **`-moz-appearance`** and **`-webkit-appearance`** properties are non-standard versions of this property, used (respectively) by Gecko (Firefox) and by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support **`-webkit-appearance`**, for compatibility reasons.

**Syntax**: `none | button | button-arrow-down | button-arrow-next | button-arrow-previous | button-arrow-up | button-bevel | button-focus | caret | checkbox | checkbox-container | checkbox-label | checkmenuitem | dualbutton | groupbox | listbox | listitem | menuarrow | menubar | menucheckbox | menuimage | menuitem | menuitemtext | menulist | menulist-button | menulist-text | menulist-textfield | menupopup | menuradio | menuseparator | meterbar | meterchunk | progressbar | progressbar-vertical | progresschunk | progresschunk-vertical | radio | radio-container | radio-label | radiomenuitem | range | range-thumb | resizer | resizerpanel | scale-horizontal | scalethumbend | scalethumb-horizontal | scalethumbstart | scalethumbtick | scalethumb-vertical | scale-vertical | scrollbarbutton-down | scrollbarbutton-left | scrollbarbutton-right | scrollbarbutton-up | scrollbarthumb-horizontal | scrollbarthumb-vertical | scrollbartrack-horizontal | scrollbartrack-vertical | searchfield | separator | sheet | spinner | spinner-downbutton | spinner-textfield | spinner-upbutton | splitter | statusbar | statusbarpanel | tab | tabpanel | tabpanels | tab-scroll-arrow-back | tab-scroll-arrow-forward | textfield | textfield-multiline | toolbar | toolbarbutton | toolbarbutton-dropdown | toolbargripper | toolbox | tooltip | treeheader | treeheadercell | treeheadersortarrow | treeitem | treeline | treetwisty | treetwistyopen | treeview | -moz-mac-unified-toolbar | -moz-win-borderless-glass | -moz-win-browsertabbar-toolbox | -moz-win-communicationstext | -moz-win-communications-toolbox | -moz-win-exclude-glass | -moz-win-glass | -moz-win-mediatext | -moz-win-media-toolbox | -moz-window-button-box | -moz-window-button-box-maximized | -moz-window-button-close | -moz-window-button-maximize | -moz-window-button-minimize | -moz-window-button-restore | -moz-window-frame-bottom | -moz-window-frame-left | -moz-window-frame-right | -moz-window-titlebar | -moz-window-titlebar-maximized`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozAppearance](akashaproject_design_system._internal_.Properties.md#mozappearance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5810

___

### MozBackfaceVisibility

• `Optional` **MozBackfaceVisibility**: [`BackfaceVisibility`](../modules/akashaproject_design_system._internal_.md#backfacevisibility)

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBackfaceVisibility](akashaproject_design_system._internal_.Properties.md#mozbackfacevisibility)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBackgroundClip](akashaproject_design_system._internal_.Properties.md#mozbackgroundclip)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBackgroundInlinePolicy](akashaproject_design_system._internal_.Properties.md#mozbackgroundinlinepolicy)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBackgroundOrigin](akashaproject_design_system._internal_.Properties.md#mozbackgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8106

___

### MozBackgroundSize

• `Optional` **MozBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`string` \| `number`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBackgroundSize](akashaproject_design_system._internal_.Properties.md#mozbackgroundsize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBinding](akashaproject_design_system._internal_.Properties.md#mozbinding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8126

___

### MozBorderBottomColors

• `Optional` **MozBorderBottomColors**: [`MozBorderBottomColors`](../modules/akashaproject_design_system._internal_.md#mozborderbottomcolors)

In Mozilla applications like Firefox, the **`-moz-border-bottom-colors`** CSS property sets a list of colors for the bottom border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderBottomColors](akashaproject_design_system._internal_.Properties.md#mozborderbottomcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5826

___

### MozBorderEndColor

• `Optional` **MozBorderEndColor**: [`BorderInlineEndColor`](../modules/akashaproject_design_system._internal_.md#borderinlineendcolor)

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderEndColor](akashaproject_design_system._internal_.Properties.md#mozborderendcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5834

___

### MozBorderEndStyle

• `Optional` **MozBorderEndStyle**: [`BorderInlineEndStyle`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyle)

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderEndStyle](akashaproject_design_system._internal_.Properties.md#mozborderendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5842

___

### MozBorderEndWidth

• `Optional` **MozBorderEndWidth**: [`BorderInlineEndWidth`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidth)<`string` \| `number`\>

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderEndWidth](akashaproject_design_system._internal_.Properties.md#mozborderendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5850

___

### MozBorderImage

• `Optional` **MozBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderImage](akashaproject_design_system._internal_.Properties.md#mozborderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7545

___

### MozBorderLeftColors

• `Optional` **MozBorderLeftColors**: [`MozBorderLeftColors`](../modules/akashaproject_design_system._internal_.md#mozborderleftcolors)

In Mozilla applications like Firefox, the **`-moz-border-left-colors`** CSS property sets a list of colors for the left border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderLeftColors](akashaproject_design_system._internal_.Properties.md#mozborderleftcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5858

___

### MozBorderRadius

• `Optional` **MozBorderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`string` \| `number`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRadius](akashaproject_design_system._internal_.Properties.md#mozborderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8134

___

### MozBorderRadiusBottomleft

• `Optional` **MozBorderRadiusBottomleft**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`string` \| `number`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRadiusBottomleft](akashaproject_design_system._internal_.Properties.md#mozborderradiusbottomleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8144

___

### MozBorderRadiusBottomright

• `Optional` **MozBorderRadiusBottomright**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`string` \| `number`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRadiusBottomright](akashaproject_design_system._internal_.Properties.md#mozborderradiusbottomright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8154

___

### MozBorderRadiusTopleft

• `Optional` **MozBorderRadiusTopleft**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`string` \| `number`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRadiusTopleft](akashaproject_design_system._internal_.Properties.md#mozborderradiustopleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8164

___

### MozBorderRadiusTopright

• `Optional` **MozBorderRadiusTopright**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`string` \| `number`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRadiusTopright](akashaproject_design_system._internal_.Properties.md#mozborderradiustopright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8174

___

### MozBorderRightColors

• `Optional` **MozBorderRightColors**: [`MozBorderRightColors`](../modules/akashaproject_design_system._internal_.md#mozborderrightcolors)

In Mozilla applications like Firefox, the **`-moz-border-right-colors`** CSS property sets a list of colors for the right border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderRightColors](akashaproject_design_system._internal_.Properties.md#mozborderrightcolors)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5866

___

### MozBorderStartColor

• `Optional` **MozBorderStartColor**: [`BorderInlineStartColor`](../modules/akashaproject_design_system._internal_.md#borderinlinestartcolor)

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderStartColor](akashaproject_design_system._internal_.Properties.md#mozborderstartcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5874

___

### MozBorderStartStyle

• `Optional` **MozBorderStartStyle**: [`BorderInlineStartStyle`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyle)

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderStartStyle](akashaproject_design_system._internal_.Properties.md#mozborderstartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5882

___

### MozBorderTopColors

• `Optional` **MozBorderTopColors**: [`MozBorderTopColors`](../modules/akashaproject_design_system._internal_.md#mozbordertopcolors)

In Mozilla applications like Firefox, the **`-moz-border-top-colors`** CSS property sets a list of colors for the top border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBorderTopColors](akashaproject_design_system._internal_.Properties.md#mozbordertopcolors)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxAlign](akashaproject_design_system._internal_.Properties.md#mozboxalign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxDirection](akashaproject_design_system._internal_.Properties.md#mozboxdirection)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxFlex](akashaproject_design_system._internal_.Properties.md#mozboxflex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#mozboxordinalgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxOrient](akashaproject_design_system._internal_.Properties.md#mozboxorient)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxPack](akashaproject_design_system._internal_.Properties.md#mozboxpack)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxShadow](akashaproject_design_system._internal_.Properties.md#mozboxshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8244

___

### MozBoxSizing

• `Optional` **MozBoxSizing**: [`BoxSizing`](../modules/akashaproject_design_system._internal_.md#boxsizing)

The **`box-sizing`** CSS property sets how the total width and height of an element is calculated.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozBoxSizing](akashaproject_design_system._internal_.Properties.md#mozboxsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5898

___

### MozColumnCount

• `Optional` **MozColumnCount**: [`ColumnCount`](../modules/akashaproject_design_system._internal_.md#columncount)

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnCount](akashaproject_design_system._internal_.Properties.md#mozcolumncount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5906

___

### MozColumnFill

• `Optional` **MozColumnFill**: [`ColumnFill`](../modules/akashaproject_design_system._internal_.md#columnfill)

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnFill](akashaproject_design_system._internal_.Properties.md#mozcolumnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5914

___

### MozColumnGap

• `Optional` **MozColumnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`string` \| `number`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnGap](akashaproject_design_system._internal_.Properties.md#mozcolumngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5922

___

### MozColumnRule

• `Optional` **MozColumnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`string` \| `number`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnRule](akashaproject_design_system._internal_.Properties.md#mozcolumnrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7551

___

### MozColumnRuleColor

• `Optional` **MozColumnRuleColor**: [`ColumnRuleColor`](../modules/akashaproject_design_system._internal_.md#columnrulecolor)

The **`column-rule-color`** CSS property sets the color of the line drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnRuleColor](akashaproject_design_system._internal_.Properties.md#mozcolumnrulecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5930

___

### MozColumnRuleStyle

• `Optional` **MozColumnRuleStyle**: [`ColumnRuleStyle`](../modules/akashaproject_design_system._internal_.md#columnrulestyle)

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnRuleStyle](akashaproject_design_system._internal_.Properties.md#mozcolumnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5938

___

### MozColumnRuleWidth

• `Optional` **MozColumnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`string` \| `number`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnRuleWidth](akashaproject_design_system._internal_.Properties.md#mozcolumnrulewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5946

___

### MozColumnWidth

• `Optional` **MozColumnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`string` \| `number`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumnWidth](akashaproject_design_system._internal_.Properties.md#mozcolumnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5954

___

### MozColumns

• `Optional` **MozColumns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`string` \| `number`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozColumns](akashaproject_design_system._internal_.Properties.md#mozcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7557

___

### MozContextProperties

• `Optional` **MozContextProperties**: [`MozContextProperties`](../modules/akashaproject_design_system._internal_.md#mozcontextproperties)

The `**-moz-context-properties**` property can be used within privileged contexts in Firefox to share the values of specified properties of the element with a child SVG image.

**Syntax**: `none | [ fill | fill-opacity | stroke | stroke-opacity ]#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozContextProperties](akashaproject_design_system._internal_.Properties.md#mozcontextproperties)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozFloatEdge](akashaproject_design_system._internal_.Properties.md#mozfloatedge)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8254

___

### MozFontFeatureSettings

• `Optional` **MozFontFeatureSettings**: [`FontFeatureSettings`](../modules/akashaproject_design_system._internal_.md#fontfeaturesettings)

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozFontFeatureSettings](akashaproject_design_system._internal_.Properties.md#mozfontfeaturesettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5970

___

### MozFontLanguageOverride

• `Optional` **MozFontLanguageOverride**: [`FontLanguageOverride`](../modules/akashaproject_design_system._internal_.md#fontlanguageoverride)

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozFontLanguageOverride](akashaproject_design_system._internal_.Properties.md#mozfontlanguageoverride)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozForceBrokenImageIcon](akashaproject_design_system._internal_.Properties.md#mozforcebrokenimageicon)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8264

___

### MozHyphens

• `Optional` **MozHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozHyphens](akashaproject_design_system._internal_.Properties.md#mozhyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5986

___

### MozImageRegion

• `Optional` **MozImageRegion**: [`MozImageRegion`](../modules/akashaproject_design_system._internal_.md#mozimageregion)

For certain XUL elements and pseudo-elements that use an image from the `list-style-image` property, this property specifies a region of the image that is used in place of the whole image. This allows elements to use different pieces of the same image to improve performance.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozImageRegion](akashaproject_design_system._internal_.Properties.md#mozimageregion)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5994

___

### MozMarginEnd

• `Optional` **MozMarginEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`string` \| `number`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozMarginEnd](akashaproject_design_system._internal_.Properties.md#mozmarginend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6002

___

### MozMarginStart

• `Optional` **MozMarginStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`string` \| `number`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozMarginStart](akashaproject_design_system._internal_.Properties.md#mozmarginstart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOpacity](akashaproject_design_system._internal_.Properties.md#mozopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8274

___

### MozOrient

• `Optional` **MozOrient**: [`MozOrient`](../modules/akashaproject_design_system._internal_.md#mozorient)

The **`-moz-orient`** CSS property specifies the orientation of the element to which it's applied.

**Syntax**: `inline | block | horizontal | vertical`

**Initial value**: `inline`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOrient](akashaproject_design_system._internal_.Properties.md#mozorient)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6018

___

### MozOsxFontSmoothing

• `Optional` **MozOsxFontSmoothing**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`string` \| `number`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOsxFontSmoothing](akashaproject_design_system._internal_.Properties.md#mozosxfontsmoothing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6026

___

### MozOutline

• `Optional` **MozOutline**: [`Outline`](../modules/akashaproject_design_system._internal_.md#outline)<`string` \| `number`\>

The **`outline`** CSS shorthand property set all the outline properties in a single declaration.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutline](akashaproject_design_system._internal_.Properties.md#mozoutline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineColor](akashaproject_design_system._internal_.Properties.md#mozoutlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8292

___

### MozOutlineRadius

• `Optional` **MozOutlineRadius**: [`MozOutlineRadius`](../modules/akashaproject_design_system._internal_.md#mozoutlineradius)<`string` \| `number`\>

In Mozilla applications like Firefox, the **`-moz-outline-radius`** CSS shorthand property can be used to give an element's `outline` rounded corners.

**Syntax**: `<outline-radius>{1,4} [ / <outline-radius>{1,4} ]?`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineRadius](akashaproject_design_system._internal_.Properties.md#mozoutlineradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8300

___

### MozOutlineRadiusBottomleft

• `Optional` **MozOutlineRadiusBottomleft**: [`MozOutlineRadiusBottomleft`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleft)<`string` \| `number`\>

In Mozilla applications, the **`-moz-outline-radius-bottomleft`** CSS property can be used to round the bottom-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.Properties.md#mozoutlineradiusbottomleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8310

___

### MozOutlineRadiusBottomright

• `Optional` **MozOutlineRadiusBottomright**: [`MozOutlineRadiusBottomright`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomright)<`string` \| `number`\>

In Mozilla applications, the **`-moz-outline-radius-bottomright`** CSS property can be used to round the bottom-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineRadiusBottomright](akashaproject_design_system._internal_.Properties.md#mozoutlineradiusbottomright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8320

___

### MozOutlineRadiusTopleft

• `Optional` **MozOutlineRadiusTopleft**: [`MozOutlineRadiusTopleft`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleft)<`string` \| `number`\>

In Mozilla applications, the **`-moz-outline-radius-topleft`** CSS property can be used to round the top-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineRadiusTopleft](akashaproject_design_system._internal_.Properties.md#mozoutlineradiustopleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8330

___

### MozOutlineRadiusTopright

• `Optional` **MozOutlineRadiusTopright**: [`MozOutlineRadiusTopright`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopright)<`string` \| `number`\>

In Mozilla applications, the **`-moz-outline-radius-topright`** CSS property can be used to round the top-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineRadiusTopright](akashaproject_design_system._internal_.Properties.md#mozoutlineradiustopright)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineStyle](akashaproject_design_system._internal_.Properties.md#mozoutlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8350

___

### MozOutlineWidth

• `Optional` **MozOutlineWidth**: [`OutlineWidth`](../modules/akashaproject_design_system._internal_.md#outlinewidth)<`string` \| `number`\>

The CSS **`outline-width`** property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozOutlineWidth](akashaproject_design_system._internal_.Properties.md#mozoutlinewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8360

___

### MozPaddingEnd

• `Optional` **MozPaddingEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`string` \| `number`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozPaddingEnd](akashaproject_design_system._internal_.Properties.md#mozpaddingend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6034

___

### MozPaddingStart

• `Optional` **MozPaddingStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`string` \| `number`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozPaddingStart](akashaproject_design_system._internal_.Properties.md#mozpaddingstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6042

___

### MozPerspective

• `Optional` **MozPerspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`string` \| `number`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozPerspective](akashaproject_design_system._internal_.Properties.md#mozperspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6050

___

### MozPerspectiveOrigin

• `Optional` **MozPerspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`string` \| `number`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozPerspectiveOrigin](akashaproject_design_system._internal_.Properties.md#mozperspectiveorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6058

___

### MozStackSizing

• `Optional` **MozStackSizing**: [`MozStackSizing`](../modules/akashaproject_design_system._internal_.md#mozstacksizing)

**`-moz-stack-sizing`** is an extended CSS property. Normally, a `<xul:stack>` will change its size so that all of its child elements are completely visible. For example, moving a child of the stack far to the right will widen the stack so the child remains visible.

**Syntax**: `ignore | stretch-to-fit`

**Initial value**: `stretch-to-fit`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozStackSizing](akashaproject_design_system._internal_.Properties.md#mozstacksizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6066

___

### MozTabSize

• `Optional` **MozTabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`string` \| `number`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTabSize](akashaproject_design_system._internal_.Properties.md#moztabsize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextAlignLast](akashaproject_design_system._internal_.Properties.md#moztextalignlast)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8370

___

### MozTextBlink

• `Optional` **MozTextBlink**: [`MozTextBlink`](../modules/akashaproject_design_system._internal_.md#moztextblink)

The **`-moz-text-blink`** non-standard Mozilla CSS extension specifies the blink mode.

**Syntax**: `none | blink`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextBlink](akashaproject_design_system._internal_.Properties.md#moztextblink)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextDecorationColor](akashaproject_design_system._internal_.Properties.md#moztextdecorationcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextDecorationLine](akashaproject_design_system._internal_.Properties.md#moztextdecorationline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextDecorationStyle](akashaproject_design_system._internal_.Properties.md#moztextdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8400

___

### MozTextSizeAdjust

• `Optional` **MozTextSizeAdjust**: [`TextSizeAdjust`](../modules/akashaproject_design_system._internal_.md#textsizeadjust)

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTextSizeAdjust](akashaproject_design_system._internal_.Properties.md#moztextsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6090

___

### MozTransformOrigin

• `Optional` **MozTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`string` \| `number`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransformOrigin](akashaproject_design_system._internal_.Properties.md#moztransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6098

___

### MozTransformStyle

• `Optional` **MozTransformStyle**: [`TransformStyle`](../modules/akashaproject_design_system._internal_.md#transformstyle)

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransformStyle](akashaproject_design_system._internal_.Properties.md#moztransformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6106

___

### MozTransition

• `Optional` **MozTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`string` & {}\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransition](akashaproject_design_system._internal_.Properties.md#moztransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7563

___

### MozTransitionDelay

• `Optional` **MozTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`string` & {}\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransitionDelay](akashaproject_design_system._internal_.Properties.md#moztransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6114

___

### MozTransitionDuration

• `Optional` **MozTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`string` & {}\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransitionDuration](akashaproject_design_system._internal_.Properties.md#moztransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6122

___

### MozTransitionProperty

• `Optional` **MozTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransitionProperty](akashaproject_design_system._internal_.Properties.md#moztransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6130

___

### MozTransitionTimingFunction

• `Optional` **MozTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#moztransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6138

___

### MozUserFocus

• `Optional` **MozUserFocus**: [`MozUserFocus`](../modules/akashaproject_design_system._internal_.md#mozuserfocus)

The **`-moz-user-focus`** CSS property is used to indicate whether an element can have the focus.

**Syntax**: `ignore | normal | select-after | select-before | select-menu | select-same | select-all | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozUserFocus](akashaproject_design_system._internal_.Properties.md#mozuserfocus)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[MozUserInput](akashaproject_design_system._internal_.Properties.md#mozuserinput)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8410

___

### MozUserModify

• `Optional` **MozUserModify**: [`MozUserModify`](../modules/akashaproject_design_system._internal_.md#mozusermodify)

The **`user-modify`** property has no effect in Firefox. It was originally planned to determine whether or not the content of an element can be edited by a user.

**Syntax**: `read-only | read-write | write-only`

**Initial value**: `read-only`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozUserModify](akashaproject_design_system._internal_.Properties.md#mozusermodify)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6154

___

### MozUserSelect

• `Optional` **MozUserSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozUserSelect](akashaproject_design_system._internal_.Properties.md#mozuserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6162

___

### MozWindowDragging

• `Optional` **MozWindowDragging**: [`MozWindowDragging`](../modules/akashaproject_design_system._internal_.md#mozwindowdragging)

The **`-moz-window-dragging`** CSS property specifies whether a window is draggable or not. It only works in Chrome code, and only on Mac OS X.

**Syntax**: `drag | no-drag`

**Initial value**: `drag`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozWindowDragging](akashaproject_design_system._internal_.Properties.md#mozwindowdragging)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6170

___

### MozWindowShadow

• `Optional` **MozWindowShadow**: [`MozWindowShadow`](../modules/akashaproject_design_system._internal_.md#mozwindowshadow)

The **`-moz-window-shadow`** CSS property specifies whether a window will have a shadow. It only works on Mac OS X.

**Syntax**: `default | menu | tooltip | sheet | none`

**Initial value**: `default`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[MozWindowShadow](akashaproject_design_system._internal_.Properties.md#mozwindowshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6178

___

### OAnimation

• `Optional` **OAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`string` & {}\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimation](akashaproject_design_system._internal_.Properties.md#oanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8438

___

### OAnimationDelay

• `Optional` **OAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`string` & {}\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationDelay](akashaproject_design_system._internal_.Properties.md#oanimationdelay)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationDirection](akashaproject_design_system._internal_.Properties.md#oanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8458

___

### OAnimationDuration

• `Optional` **OAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`string` & {}\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationDuration](akashaproject_design_system._internal_.Properties.md#oanimationduration)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationFillMode](akashaproject_design_system._internal_.Properties.md#oanimationfillmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#oanimationiterationcount)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationName](akashaproject_design_system._internal_.Properties.md#oanimationname)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationPlayState](akashaproject_design_system._internal_.Properties.md#oanimationplaystate)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#oanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8518

___

### OBackgroundSize

• `Optional` **OBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`string` \| `number`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OBackgroundSize](akashaproject_design_system._internal_.Properties.md#obackgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8528

___

### OBorderImage

• `Optional` **OBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OBorderImage](akashaproject_design_system._internal_.Properties.md#oborderimage)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OObjectFit](akashaproject_design_system._internal_.Properties.md#oobjectfit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8546

___

### OObjectPosition

• `Optional` **OObjectPosition**: [`ObjectPosition`](../modules/akashaproject_design_system._internal_.md#objectposition)<`string` \| `number`\>

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OObjectPosition](akashaproject_design_system._internal_.Properties.md#oobjectposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8556

___

### OTabSize

• `Optional` **OTabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`string` \| `number`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OTabSize](akashaproject_design_system._internal_.Properties.md#otabsize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OTextOverflow](akashaproject_design_system._internal_.Properties.md#otextoverflow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransform](akashaproject_design_system._internal_.Properties.md#otransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8586

___

### OTransformOrigin

• `Optional` **OTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`string` \| `number`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransformOrigin](akashaproject_design_system._internal_.Properties.md#otransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8596

___

### OTransition

• `Optional` **OTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`string` & {}\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransition](akashaproject_design_system._internal_.Properties.md#otransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8604

___

### OTransitionDelay

• `Optional` **OTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`string` & {}\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransitionDelay](akashaproject_design_system._internal_.Properties.md#otransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8614

___

### OTransitionDuration

• `Optional` **OTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`string` & {}\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransitionDuration](akashaproject_design_system._internal_.Properties.md#otransitionduration)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransitionProperty](akashaproject_design_system._internal_.Properties.md#otransitionproperty)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[OTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#otransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8644

___

### WebkitAlignContent

• `Optional` **WebkitAlignContent**: [`AlignContent`](../modules/akashaproject_design_system._internal_.md#aligncontent)

The CSS **`align-content`** property sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

**Syntax**: `normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position>`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAlignContent](akashaproject_design_system._internal_.Properties.md#webkitaligncontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6682

___

### WebkitAlignItems

• `Optional` **WebkitAlignItems**: [`AlignItems`](../modules/akashaproject_design_system._internal_.md#alignitems)

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

**Syntax**: `normal | stretch | <baseline-position> | [ <overflow-position>? <self-position> ]`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAlignItems](akashaproject_design_system._internal_.Properties.md#webkitalignitems)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6690

___

### WebkitAlignSelf

• `Optional` **WebkitAlignSelf**: [`AlignSelf`](../modules/akashaproject_design_system._internal_.md#alignself)

The **`align-self`** CSS property overrides a grid or flex item's `align-items` value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAlignSelf](akashaproject_design_system._internal_.Properties.md#webkitalignself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6698

___

### WebkitAnimation

• `Optional` **WebkitAnimation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`string` & {}\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimation](akashaproject_design_system._internal_.Properties.md#webkitanimation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7611

___

### WebkitAnimationDelay

• `Optional` **WebkitAnimationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`string` & {}\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationDelay](akashaproject_design_system._internal_.Properties.md#webkitanimationdelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6706

___

### WebkitAnimationDirection

• `Optional` **WebkitAnimationDirection**: [`AnimationDirection`](../modules/akashaproject_design_system._internal_.md#animationdirection)

The **`animation-direction`** CSS property sets whether an animation should play forward, backward, or alternate back and forth between playing the sequence forward and backward.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationDirection](akashaproject_design_system._internal_.Properties.md#webkitanimationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6714

___

### WebkitAnimationDuration

• `Optional` **WebkitAnimationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`string` & {}\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationDuration](akashaproject_design_system._internal_.Properties.md#webkitanimationduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6722

___

### WebkitAnimationFillMode

• `Optional` **WebkitAnimationFillMode**: [`AnimationFillMode`](../modules/akashaproject_design_system._internal_.md#animationfillmode)

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationFillMode](akashaproject_design_system._internal_.Properties.md#webkitanimationfillmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6730

___

### WebkitAnimationIterationCount

• `Optional` **WebkitAnimationIterationCount**: [`AnimationIterationCount`](../modules/akashaproject_design_system._internal_.md#animationiterationcount)

The **`animation-iteration-count`** CSS property sets the number of times an animation sequence should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationIterationCount](akashaproject_design_system._internal_.Properties.md#webkitanimationiterationcount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6738

___

### WebkitAnimationName

• `Optional` **WebkitAnimationName**: [`AnimationName`](../modules/akashaproject_design_system._internal_.md#animationname)

The **`animation-name`** CSS property specifies the names of one or more `@keyframes` at-rules describing the animation or animations to apply to the element.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationName](akashaproject_design_system._internal_.Properties.md#webkitanimationname)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6746

___

### WebkitAnimationPlayState

• `Optional` **WebkitAnimationPlayState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationPlayState](akashaproject_design_system._internal_.Properties.md#webkitanimationplaystate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6754

___

### WebkitAnimationTimingFunction

• `Optional` **WebkitAnimationTimingFunction**: [`AnimationTimingFunction`](../modules/akashaproject_design_system._internal_.md#animationtimingfunction)

The **`animation-timing-function`** CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAnimationTimingFunction](akashaproject_design_system._internal_.Properties.md#webkitanimationtimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6762

___

### WebkitAppearance

• `Optional` **WebkitAppearance**: [`WebkitAppearance`](../modules/akashaproject_design_system._internal_.md#webkitappearance)

The `**appearance**` CSS property is used to display an element using platform-native styling, based on the operating system's theme. The **`-moz-appearance`** and **`-webkit-appearance`** properties are non-standard versions of this property, used (respectively) by Gecko (Firefox) and by WebKit-based (e.g., Safari) and Blink-based (e.g., Chrome, Opera) browsers to achieve the same thing. Note that Firefox and Edge also support **`-webkit-appearance`**, for compatibility reasons.

**Syntax**: `none | button | button-bevel | caret | checkbox | default-button | inner-spin-button | listbox | listitem | media-controls-background | media-controls-fullscreen-background | media-current-time-display | media-enter-fullscreen-button | media-exit-fullscreen-button | media-fullscreen-button | media-mute-button | media-overlay-play-button | media-play-button | media-seek-back-button | media-seek-forward-button | media-slider | media-sliderthumb | media-time-remaining-display | media-toggle-closed-captions-button | media-volume-slider | media-volume-slider-container | media-volume-sliderthumb | menulist | menulist-button | menulist-text | menulist-textfield | meter | progress-bar | progress-bar-value | push-button | radio | searchfield | searchfield-cancel-button | searchfield-decoration | searchfield-results-button | searchfield-results-decoration | slider-horizontal | slider-vertical | sliderthumb-horizontal | sliderthumb-vertical | square-button | textarea | textfield | -apple-pay-button`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitAppearance](akashaproject_design_system._internal_.Properties.md#webkitappearance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6770

___

### WebkitBackdropFilter

• `Optional` **WebkitBackdropFilter**: [`BackdropFilter`](../modules/akashaproject_design_system._internal_.md#backdropfilter)

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBackdropFilter](akashaproject_design_system._internal_.Properties.md#webkitbackdropfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6778

___

### WebkitBackfaceVisibility

• `Optional` **WebkitBackfaceVisibility**: [`BackfaceVisibility`](../modules/akashaproject_design_system._internal_.md#backfacevisibility)

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBackfaceVisibility](akashaproject_design_system._internal_.Properties.md#webkitbackfacevisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6786

___

### WebkitBackgroundClip

• `Optional` **WebkitBackgroundClip**: [`BackgroundClip`](../modules/akashaproject_design_system._internal_.md#backgroundclip)

The **`background-clip`** CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

**Syntax**: `<box>#`

**Initial value**: `border-box`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBackgroundClip](akashaproject_design_system._internal_.Properties.md#webkitbackgroundclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6794

___

### WebkitBackgroundOrigin

• `Optional` **WebkitBackgroundOrigin**: [`BackgroundOrigin`](../modules/akashaproject_design_system._internal_.md#backgroundorigin)

The **`background-origin`** CSS property sets the background's origin: from the border start, inside the border, or inside the padding.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBackgroundOrigin](akashaproject_design_system._internal_.Properties.md#webkitbackgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6802

___

### WebkitBackgroundSize

• `Optional` **WebkitBackgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`string` \| `number`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBackgroundSize](akashaproject_design_system._internal_.Properties.md#webkitbackgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6810

___

### WebkitBorderBefore

• `Optional` **WebkitBorderBefore**: [`WebkitBorderBefore`](../modules/akashaproject_design_system._internal_.md#webkitborderbefore)<`string` \| `number`\>

The **`-webkit-border-before`** CSS property is a shorthand property for setting the individual logical block start border property values in a single place in the style sheet.

**Syntax**: `<'border-width'> || <'border-style'> || <color>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBefore](akashaproject_design_system._internal_.Properties.md#webkitborderbefore)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7617

___

### WebkitBorderBeforeColor

• `Optional` **WebkitBorderBeforeColor**: [`WebkitBorderBeforeColor`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforecolor)

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBeforeColor](akashaproject_design_system._internal_.Properties.md#webkitborderbeforecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6816

___

### WebkitBorderBeforeStyle

• `Optional` **WebkitBorderBeforeStyle**: [`WebkitBorderBeforeStyle`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforestyle)

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBeforeStyle](akashaproject_design_system._internal_.Properties.md#webkitborderbeforestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6822

___

### WebkitBorderBeforeWidth

• `Optional` **WebkitBorderBeforeWidth**: [`WebkitBorderBeforeWidth`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidth)<`string` \| `number`\>

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBeforeWidth](akashaproject_design_system._internal_.Properties.md#webkitborderbeforewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6828

___

### WebkitBorderBottomLeftRadius

• `Optional` **WebkitBorderBottomLeftRadius**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`string` \| `number`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.Properties.md#webkitborderbottomleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6836

___

### WebkitBorderBottomRightRadius

• `Optional` **WebkitBorderBottomRightRadius**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`string` \| `number`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.Properties.md#webkitborderbottomrightradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6844

___

### WebkitBorderImage

• `Optional` **WebkitBorderImage**: [`BorderImage`](../modules/akashaproject_design_system._internal_.md#borderimage)

The **`border-image`** CSS property draws an image around a given element. It replaces the element's regular border.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderImage](akashaproject_design_system._internal_.Properties.md#webkitborderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7623

___

### WebkitBorderImageSlice

• `Optional` **WebkitBorderImageSlice**: [`BorderImageSlice`](../modules/akashaproject_design_system._internal_.md#borderimageslice)

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderImageSlice](akashaproject_design_system._internal_.Properties.md#webkitborderimageslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6852

___

### WebkitBorderRadius

• `Optional` **WebkitBorderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`string` \| `number`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderRadius](akashaproject_design_system._internal_.Properties.md#webkitborderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7629

___

### WebkitBorderTopLeftRadius

• `Optional` **WebkitBorderTopLeftRadius**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`string` \| `number`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.Properties.md#webkitbordertopleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6860

___

### WebkitBorderTopRightRadius

• `Optional` **WebkitBorderTopRightRadius**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`string` \| `number`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBorderTopRightRadius](akashaproject_design_system._internal_.Properties.md#webkitbordertoprightradius)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxAlign](akashaproject_design_system._internal_.Properties.md#webkitboxalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8654

___

### WebkitBoxDecorationBreak

• `Optional` **WebkitBoxDecorationBreak**: [`BoxDecorationBreak`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreak)

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxDecorationBreak](akashaproject_design_system._internal_.Properties.md#webkitboxdecorationbreak)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxDirection](akashaproject_design_system._internal_.Properties.md#webkitboxdirection)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxFlex](akashaproject_design_system._internal_.Properties.md#webkitboxflex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxFlexGroup](akashaproject_design_system._internal_.Properties.md#webkitboxflexgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxLines](akashaproject_design_system._internal_.Properties.md#webkitboxlines)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#webkitboxordinalgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxOrient](akashaproject_design_system._internal_.Properties.md#webkitboxorient)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxPack](akashaproject_design_system._internal_.Properties.md#webkitboxpack)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8724

___

### WebkitBoxReflect

• `Optional` **WebkitBoxReflect**: [`WebkitBoxReflect`](../modules/akashaproject_design_system._internal_.md#webkitboxreflect)<`string` \| `number`\>

The **`-webkit-box-reflect`** CSS property lets you reflect the content of an element in one specific direction.

**Syntax**: `[ above | below | right | left ]? <length>? <image>?`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxReflect](akashaproject_design_system._internal_.Properties.md#webkitboxreflect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6884

___

### WebkitBoxShadow

• `Optional` **WebkitBoxShadow**: [`BoxShadow`](../modules/akashaproject_design_system._internal_.md#boxshadow)

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxShadow](akashaproject_design_system._internal_.Properties.md#webkitboxshadow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6892

___

### WebkitBoxSizing

• `Optional` **WebkitBoxSizing**: [`BoxSizing`](../modules/akashaproject_design_system._internal_.md#boxsizing)

The **`box-sizing`** CSS property sets how the total width and height of an element is calculated.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitBoxSizing](akashaproject_design_system._internal_.Properties.md#webkitboxsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6900

___

### WebkitClipPath

• `Optional` **WebkitClipPath**: [`ClipPath`](../modules/akashaproject_design_system._internal_.md#clippath)

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitClipPath](akashaproject_design_system._internal_.Properties.md#webkitclippath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6908

___

### WebkitColumnCount

• `Optional` **WebkitColumnCount**: [`ColumnCount`](../modules/akashaproject_design_system._internal_.md#columncount)

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnCount](akashaproject_design_system._internal_.Properties.md#webkitcolumncount)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6916

___

### WebkitColumnFill

• `Optional` **WebkitColumnFill**: [`ColumnFill`](../modules/akashaproject_design_system._internal_.md#columnfill)

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnFill](akashaproject_design_system._internal_.Properties.md#webkitcolumnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6924

___

### WebkitColumnGap

• `Optional` **WebkitColumnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`string` \| `number`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnGap](akashaproject_design_system._internal_.Properties.md#webkitcolumngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6932

___

### WebkitColumnRule

• `Optional` **WebkitColumnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`string` \| `number`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnRule](akashaproject_design_system._internal_.Properties.md#webkitcolumnrule)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7635

___

### WebkitColumnRuleColor

• `Optional` **WebkitColumnRuleColor**: [`ColumnRuleColor`](../modules/akashaproject_design_system._internal_.md#columnrulecolor)

The **`column-rule-color`** CSS property sets the color of the line drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnRuleColor](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6940

___

### WebkitColumnRuleStyle

• `Optional` **WebkitColumnRuleStyle**: [`ColumnRuleStyle`](../modules/akashaproject_design_system._internal_.md#columnrulestyle)

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnRuleStyle](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6948

___

### WebkitColumnRuleWidth

• `Optional` **WebkitColumnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`string` \| `number`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnRuleWidth](akashaproject_design_system._internal_.Properties.md#webkitcolumnrulewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6956

___

### WebkitColumnSpan

• `Optional` **WebkitColumnSpan**: [`ColumnSpan`](../modules/akashaproject_design_system._internal_.md#columnspan)

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnSpan](akashaproject_design_system._internal_.Properties.md#webkitcolumnspan)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6964

___

### WebkitColumnWidth

• `Optional` **WebkitColumnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`string` \| `number`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumnWidth](akashaproject_design_system._internal_.Properties.md#webkitcolumnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6972

___

### WebkitColumns

• `Optional` **WebkitColumns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`string` \| `number`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitColumns](akashaproject_design_system._internal_.Properties.md#webkitcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7641

___

### WebkitFilter

• `Optional` **WebkitFilter**: [`Filter`](../modules/akashaproject_design_system._internal_.md#filter)

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFilter](akashaproject_design_system._internal_.Properties.md#webkitfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6980

___

### WebkitFlex

• `Optional` **WebkitFlex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`string` \| `number`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlex](akashaproject_design_system._internal_.Properties.md#webkitflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7647

___

### WebkitFlexBasis

• `Optional` **WebkitFlexBasis**: [`FlexBasis`](../modules/akashaproject_design_system._internal_.md#flexbasis)<`string` \| `number`\>

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexBasis](akashaproject_design_system._internal_.Properties.md#webkitflexbasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6988

___

### WebkitFlexDirection

• `Optional` **WebkitFlexDirection**: [`FlexDirection`](../modules/akashaproject_design_system._internal_.md#flexdirection)

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexDirection](akashaproject_design_system._internal_.Properties.md#webkitflexdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6996

___

### WebkitFlexFlow

• `Optional` **WebkitFlexFlow**: [`FlexFlow`](../modules/akashaproject_design_system._internal_.md#flexflow)

The **`flex-flow`** CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexFlow](akashaproject_design_system._internal_.Properties.md#webkitflexflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7653

___

### WebkitFlexGrow

• `Optional` **WebkitFlexGrow**: [`FlexGrow`](../modules/akashaproject_design_system._internal_.md#flexgrow)

The **`flex-grow`** CSS property sets the flex grow factor of a flex item main size.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexGrow](akashaproject_design_system._internal_.Properties.md#webkitflexgrow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7004

___

### WebkitFlexShrink

• `Optional` **WebkitFlexShrink**: [`FlexShrink`](../modules/akashaproject_design_system._internal_.md#flexshrink)

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexShrink](akashaproject_design_system._internal_.Properties.md#webkitflexshrink)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7012

___

### WebkitFlexWrap

• `Optional` **WebkitFlexWrap**: [`FlexWrap`](../modules/akashaproject_design_system._internal_.md#flexwrap)

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFlexWrap](akashaproject_design_system._internal_.Properties.md#webkitflexwrap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7020

___

### WebkitFontFeatureSettings

• `Optional` **WebkitFontFeatureSettings**: [`FontFeatureSettings`](../modules/akashaproject_design_system._internal_.md#fontfeaturesettings)

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFontFeatureSettings](akashaproject_design_system._internal_.Properties.md#webkitfontfeaturesettings)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7028

___

### WebkitFontKerning

• `Optional` **WebkitFontKerning**: [`FontKerning`](../modules/akashaproject_design_system._internal_.md#fontkerning)

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFontKerning](akashaproject_design_system._internal_.Properties.md#webkitfontkerning)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7036

___

### WebkitFontSmoothing

• `Optional` **WebkitFontSmoothing**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`string` \| `number`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFontSmoothing](akashaproject_design_system._internal_.Properties.md#webkitfontsmoothing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7044

___

### WebkitFontVariantLigatures

• `Optional` **WebkitFontVariantLigatures**: [`FontVariantLigatures`](../modules/akashaproject_design_system._internal_.md#fontvariantligatures)

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitFontVariantLigatures](akashaproject_design_system._internal_.Properties.md#webkitfontvariantligatures)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7052

___

### WebkitHyphens

• `Optional` **WebkitHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitHyphens](akashaproject_design_system._internal_.Properties.md#webkithyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7060

___

### WebkitJustifyContent

• `Optional` **WebkitJustifyContent**: [`JustifyContent`](../modules/akashaproject_design_system._internal_.md#justifycontent)

The CSS **`justify-content`** property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

**Syntax**: `normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ]`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitJustifyContent](akashaproject_design_system._internal_.Properties.md#webkitjustifycontent)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7068

___

### WebkitLineBreak

• `Optional` **WebkitLineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitLineBreak](akashaproject_design_system._internal_.Properties.md#webkitlinebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7076

___

### WebkitLineClamp

• `Optional` **WebkitLineClamp**: [`WebkitLineClamp`](../modules/akashaproject_design_system._internal_.md#webkitlineclamp)

The **`-webkit-line-clamp`** CSS property allows limiting of the contents of a block container to the specified number of lines.

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitLineClamp](akashaproject_design_system._internal_.Properties.md#webkitlineclamp)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7084

___

### WebkitMarginEnd

• `Optional` **WebkitMarginEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`string` \| `number`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMarginEnd](akashaproject_design_system._internal_.Properties.md#webkitmarginend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7092

___

### WebkitMarginStart

• `Optional` **WebkitMarginStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`string` \| `number`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMarginStart](akashaproject_design_system._internal_.Properties.md#webkitmarginstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7100

___

### WebkitMask

• `Optional` **WebkitMask**: [`WebkitMask`](../modules/akashaproject_design_system._internal_.md#webkitmask)<`string` \| `number`\>

The **`mask`** CSS shorthand property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `[ <mask-reference> || <position> [ / <bg-size> ]? || <repeat-style> || [ <box> | border | padding | content | text ] || [ <box> | border | padding | content ] ]#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMask](akashaproject_design_system._internal_.Properties.md#webkitmask)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7659

___

### WebkitMaskAttachment

• `Optional` **WebkitMaskAttachment**: [`WebkitMaskAttachment`](../modules/akashaproject_design_system._internal_.md#webkitmaskattachment)

If a `-webkit-mask-image` is specified, `-webkit-mask-attachment` determines whether the mask image's position is fixed within the viewport, or scrolls along with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskAttachment](akashaproject_design_system._internal_.Properties.md#webkitmaskattachment)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7108

___

### WebkitMaskBoxImage

• `Optional` **WebkitMaskBoxImage**: [`MaskBorder`](../modules/akashaproject_design_system._internal_.md#maskborder)

The **`mask-border`** CSS shorthand property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImage](akashaproject_design_system._internal_.Properties.md#webkitmaskboximage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7665

___

### WebkitMaskBoxImageOutset

• `Optional` **WebkitMaskBoxImageOutset**: [`MaskBorderOutset`](../modules/akashaproject_design_system._internal_.md#maskborderoutset)<`string` \| `number`\>

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.Properties.md#webkitmaskboximageoutset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7116

___

### WebkitMaskBoxImageRepeat

• `Optional` **WebkitMaskBoxImageRepeat**: [`MaskBorderRepeat`](../modules/akashaproject_design_system._internal_.md#maskborderrepeat)

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagerepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7124

___

### WebkitMaskBoxImageSlice

• `Optional` **WebkitMaskBoxImageSlice**: [`MaskBorderSlice`](../modules/akashaproject_design_system._internal_.md#maskborderslice)

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.Properties.md#webkitmaskboximageslice)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7132

___

### WebkitMaskBoxImageSource

• `Optional` **WebkitMaskBoxImageSource**: [`MaskBorderSource`](../modules/akashaproject_design_system._internal_.md#maskbordersource)

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImageSource](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagesource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7140

___

### WebkitMaskBoxImageWidth

• `Optional` **WebkitMaskBoxImageWidth**: [`MaskBorderWidth`](../modules/akashaproject_design_system._internal_.md#maskborderwidth)<`string` \| `number`\>

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.Properties.md#webkitmaskboximagewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7148

___

### WebkitMaskClip

• `Optional` **WebkitMaskClip**: [`WebkitMaskClip`](../modules/akashaproject_design_system._internal_.md#webkitmaskclip)

The **`mask-clip`** CSS property determines the area which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <box> | border | padding | content | text ]#`

**Initial value**: `border`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskClip](akashaproject_design_system._internal_.Properties.md#webkitmaskclip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7156

___

### WebkitMaskComposite

• `Optional` **WebkitMaskComposite**: [`WebkitMaskComposite`](../modules/akashaproject_design_system._internal_.md#webkitmaskcomposite)

The **`-webkit-mask-composite`** property specifies the manner in which multiple mask images applied to the same element are composited with one another. Mask images are composited in the opposite order that they are declared with the `-webkit-mask-image` property.

**Syntax**: `<composite-style>#`

**Initial value**: `source-over`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskComposite](akashaproject_design_system._internal_.Properties.md#webkitmaskcomposite)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7164

___

### WebkitMaskImage

• `Optional` **WebkitMaskImage**: [`WebkitMaskImage`](../modules/akashaproject_design_system._internal_.md#webkitmaskimage)

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskImage](akashaproject_design_system._internal_.Properties.md#webkitmaskimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7172

___

### WebkitMaskOrigin

• `Optional` **WebkitMaskOrigin**: [`WebkitMaskOrigin`](../modules/akashaproject_design_system._internal_.md#webkitmaskorigin)

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `[ <box> | border | padding | content ]#`

**Initial value**: `padding`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskOrigin](akashaproject_design_system._internal_.Properties.md#webkitmaskorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7180

___

### WebkitMaskPosition

• `Optional` **WebkitMaskPosition**: [`WebkitMaskPosition`](../modules/akashaproject_design_system._internal_.md#webkitmaskposition)<`string` \| `number`\>

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `0% 0%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskPosition](akashaproject_design_system._internal_.Properties.md#webkitmaskposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7188

___

### WebkitMaskPositionX

• `Optional` **WebkitMaskPositionX**: [`WebkitMaskPositionX`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionx)<`string` \| `number`\>

The `-webkit-mask-position-x` CSS property sets the initial horizontal position of a mask image.

**Syntax**: `[ <length-percentage> | left | center | right ]#`

**Initial value**: `0%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskPositionX](akashaproject_design_system._internal_.Properties.md#webkitmaskpositionx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7196

___

### WebkitMaskPositionY

• `Optional` **WebkitMaskPositionY**: [`WebkitMaskPositionY`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositiony)<`string` \| `number`\>

The `-webkit-mask-position-y` CSS property sets the initial vertical position of a mask image.

**Syntax**: `[ <length-percentage> | top | center | bottom ]#`

**Initial value**: `0%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskPositionY](akashaproject_design_system._internal_.Properties.md#webkitmaskpositiony)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7204

___

### WebkitMaskRepeat

• `Optional` **WebkitMaskRepeat**: [`WebkitMaskRepeat`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeat)

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskRepeat](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7212

___

### WebkitMaskRepeatX

• `Optional` **WebkitMaskRepeatX**: [`WebkitMaskRepeatX`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatx)

The `-webkit-mask-repeat-x` property specifies whether and how a mask image is repeated (tiled) horizontally.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskRepeatX](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeatx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7220

___

### WebkitMaskRepeatY

• `Optional` **WebkitMaskRepeatY**: [`WebkitMaskRepeatY`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeaty)

The `-webkit-mask-repeat-y` property sets whether and how a mask image is repeated (tiled) vertically.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskRepeatY](akashaproject_design_system._internal_.Properties.md#webkitmaskrepeaty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7228

___

### WebkitMaskSize

• `Optional` **WebkitMaskSize**: [`WebkitMaskSize`](../modules/akashaproject_design_system._internal_.md#webkitmasksize)<`string` \| `number`\>

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaskSize](akashaproject_design_system._internal_.Properties.md#webkitmasksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7236

___

### WebkitMaxInlineSize

• `Optional` **WebkitMaxInlineSize**: [`MaxInlineSize`](../modules/akashaproject_design_system._internal_.md#maxinlinesize)<`string` \| `number`\>

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block, depending on its writing mode. It corresponds to either the `max-width` or the `max-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitMaxInlineSize](akashaproject_design_system._internal_.Properties.md#webkitmaxinlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7244

___

### WebkitOrder

• `Optional` **WebkitOrder**: [`Order`](../modules/akashaproject_design_system._internal_.md#order)

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitOrder](akashaproject_design_system._internal_.Properties.md#webkitorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7252

___

### WebkitOverflowScrolling

• `Optional` **WebkitOverflowScrolling**: [`WebkitOverflowScrolling`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrolling)

The `-webkit-overflow-scrolling` CSS property controls whether or not touch devices use momentum-based scrolling for a given element.

**Syntax**: `auto | touch`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitOverflowScrolling](akashaproject_design_system._internal_.Properties.md#webkitoverflowscrolling)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7260

___

### WebkitPaddingEnd

• `Optional` **WebkitPaddingEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`string` \| `number`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitPaddingEnd](akashaproject_design_system._internal_.Properties.md#webkitpaddingend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7268

___

### WebkitPaddingStart

• `Optional` **WebkitPaddingStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`string` \| `number`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitPaddingStart](akashaproject_design_system._internal_.Properties.md#webkitpaddingstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7276

___

### WebkitPerspective

• `Optional` **WebkitPerspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`string` \| `number`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitPerspective](akashaproject_design_system._internal_.Properties.md#webkitperspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7284

___

### WebkitPerspectiveOrigin

• `Optional` **WebkitPerspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`string` \| `number`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitPerspectiveOrigin](akashaproject_design_system._internal_.Properties.md#webkitperspectiveorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7292

___

### WebkitPrintColorAdjust

• `Optional` **WebkitPrintColorAdjust**: [`ColorAdjust`](../modules/akashaproject_design_system._internal_.md#coloradjust)

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitPrintColorAdjust](akashaproject_design_system._internal_.Properties.md#webkitprintcoloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7300

___

### WebkitRubyPosition

• `Optional` **WebkitRubyPosition**: [`RubyPosition`](../modules/akashaproject_design_system._internal_.md#rubyposition)

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitRubyPosition](akashaproject_design_system._internal_.Properties.md#webkitrubyposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitScrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#webkitscrollsnappointsx)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitScrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#webkitscrollsnappointsy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8744

___

### WebkitScrollSnapType

• `Optional` **WebkitScrollSnapType**: [`ScrollSnapType`](../modules/akashaproject_design_system._internal_.md#scrollsnaptype)

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitScrollSnapType](akashaproject_design_system._internal_.Properties.md#webkitscrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7316

___

### WebkitShapeMargin

• `Optional` **WebkitShapeMargin**: [`ShapeMargin`](../modules/akashaproject_design_system._internal_.md#shapemargin)<`string` \| `number`\>

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitShapeMargin](akashaproject_design_system._internal_.Properties.md#webkitshapemargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7324

___

### WebkitTapHighlightColor

• `Optional` **WebkitTapHighlightColor**: [`WebkitTapHighlightColor`](../modules/akashaproject_design_system._internal_.md#webkittaphighlightcolor)

**`-webkit-tap-highlight-color`** is a non-standard CSS property that sets the color of the highlight that appears over a link while it's being tapped. The highlighting indicates to the user that their tap is being successfully recognized, and indicates which element they're tapping on.

**Syntax**: `<color>`

**Initial value**: `black`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTapHighlightColor](akashaproject_design_system._internal_.Properties.md#webkittaphighlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7332

___

### WebkitTextCombine

• `Optional` **WebkitTextCombine**: [`TextCombineUpright`](../modules/akashaproject_design_system._internal_.md#textcombineupright)

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextCombine](akashaproject_design_system._internal_.Properties.md#webkittextcombine)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7340

___

### WebkitTextDecorationColor

• `Optional` **WebkitTextDecorationColor**: [`TextDecorationColor`](../modules/akashaproject_design_system._internal_.md#textdecorationcolor)

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextDecorationColor](akashaproject_design_system._internal_.Properties.md#webkittextdecorationcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7348

___

### WebkitTextDecorationLine

• `Optional` **WebkitTextDecorationLine**: [`TextDecorationLine`](../modules/akashaproject_design_system._internal_.md#textdecorationline)

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextDecorationLine](akashaproject_design_system._internal_.Properties.md#webkittextdecorationline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7356

___

### WebkitTextDecorationSkip

• `Optional` **WebkitTextDecorationSkip**: [`TextDecorationSkip`](../modules/akashaproject_design_system._internal_.md#textdecorationskip)

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextDecorationSkip](akashaproject_design_system._internal_.Properties.md#webkittextdecorationskip)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7364

___

### WebkitTextDecorationStyle

• `Optional` **WebkitTextDecorationStyle**: [`TextDecorationStyle`](../modules/akashaproject_design_system._internal_.md#textdecorationstyle)

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextDecorationStyle](akashaproject_design_system._internal_.Properties.md#webkittextdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7372

___

### WebkitTextEmphasis

• `Optional` **WebkitTextEmphasis**: [`TextEmphasis`](../modules/akashaproject_design_system._internal_.md#textemphasis)

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextEmphasis](akashaproject_design_system._internal_.Properties.md#webkittextemphasis)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7671

___

### WebkitTextEmphasisColor

• `Optional` **WebkitTextEmphasisColor**: [`TextEmphasisColor`](../modules/akashaproject_design_system._internal_.md#textemphasiscolor)

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextEmphasisColor](akashaproject_design_system._internal_.Properties.md#webkittextemphasiscolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7380

___

### WebkitTextEmphasisPosition

• `Optional` **WebkitTextEmphasisPosition**: [`TextEmphasisPosition`](../modules/akashaproject_design_system._internal_.md#textemphasisposition)

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextEmphasisPosition](akashaproject_design_system._internal_.Properties.md#webkittextemphasisposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7388

___

### WebkitTextEmphasisStyle

• `Optional` **WebkitTextEmphasisStyle**: [`TextEmphasisStyle`](../modules/akashaproject_design_system._internal_.md#textemphasisstyle)

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextEmphasisStyle](akashaproject_design_system._internal_.Properties.md#webkittextemphasisstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7396

___

### WebkitTextFillColor

• `Optional` **WebkitTextFillColor**: [`WebkitTextFillColor`](../modules/akashaproject_design_system._internal_.md#webkittextfillcolor)

The **`-webkit-text-fill-color`** CSS property specifies the fill color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextFillColor](akashaproject_design_system._internal_.Properties.md#webkittextfillcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7404

___

### WebkitTextOrientation

• `Optional` **WebkitTextOrientation**: [`TextOrientation`](../modules/akashaproject_design_system._internal_.md#textorientation)

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextOrientation](akashaproject_design_system._internal_.Properties.md#webkittextorientation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7412

___

### WebkitTextSizeAdjust

• `Optional` **WebkitTextSizeAdjust**: [`TextSizeAdjust`](../modules/akashaproject_design_system._internal_.md#textsizeadjust)

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextSizeAdjust](akashaproject_design_system._internal_.Properties.md#webkittextsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7420

___

### WebkitTextStroke

• `Optional` **WebkitTextStroke**: [`WebkitTextStroke`](../modules/akashaproject_design_system._internal_.md#webkittextstroke)<`string` \| `number`\>

The **`-webkit-text-stroke`** CSS property specifies the width and color of strokes for text characters. This is a shorthand property for the longhand properties `-webkit-text-stroke-width` and `-webkit-text-stroke-color`.

**Syntax**: `<length> || <color>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextStroke](akashaproject_design_system._internal_.Properties.md#webkittextstroke)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7677

___

### WebkitTextStrokeColor

• `Optional` **WebkitTextStrokeColor**: [`WebkitTextStrokeColor`](../modules/akashaproject_design_system._internal_.md#webkittextstrokecolor)

The **`-webkit-text-stroke-color`** CSS property specifies the stroke color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextStrokeColor](akashaproject_design_system._internal_.Properties.md#webkittextstrokecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7428

___

### WebkitTextStrokeWidth

• `Optional` **WebkitTextStrokeWidth**: [`WebkitTextStrokeWidth`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidth)<`string` \| `number`\>

The **`-webkit-text-stroke-width`** CSS property specifies the width of the stroke for text.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextStrokeWidth](akashaproject_design_system._internal_.Properties.md#webkittextstrokewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7436

___

### WebkitTextUnderlinePosition

• `Optional` **WebkitTextUnderlinePosition**: [`TextUnderlinePosition`](../modules/akashaproject_design_system._internal_.md#textunderlineposition)

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTextUnderlinePosition](akashaproject_design_system._internal_.Properties.md#webkittextunderlineposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7444

___

### WebkitTouchCallout

• `Optional` **WebkitTouchCallout**: [`WebkitTouchCallout`](../modules/akashaproject_design_system._internal_.md#webkittouchcallout)

The `-webkit-touch-callout` CSS property controls the display of the default callout shown when you touch and hold a touch target.

**Syntax**: `default | none`

**Initial value**: `default`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTouchCallout](akashaproject_design_system._internal_.Properties.md#webkittouchcallout)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7452

___

### WebkitTransform

• `Optional` **WebkitTransform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransform](akashaproject_design_system._internal_.Properties.md#webkittransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7460

___

### WebkitTransformOrigin

• `Optional` **WebkitTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`string` \| `number`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransformOrigin](akashaproject_design_system._internal_.Properties.md#webkittransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7468

___

### WebkitTransformStyle

• `Optional` **WebkitTransformStyle**: [`TransformStyle`](../modules/akashaproject_design_system._internal_.md#transformstyle)

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransformStyle](akashaproject_design_system._internal_.Properties.md#webkittransformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7476

___

### WebkitTransition

• `Optional` **WebkitTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`string` & {}\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransition](akashaproject_design_system._internal_.Properties.md#webkittransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7683

___

### WebkitTransitionDelay

• `Optional` **WebkitTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`string` & {}\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransitionDelay](akashaproject_design_system._internal_.Properties.md#webkittransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7484

___

### WebkitTransitionDuration

• `Optional` **WebkitTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`string` & {}\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransitionDuration](akashaproject_design_system._internal_.Properties.md#webkittransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7492

___

### WebkitTransitionProperty

• `Optional` **WebkitTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransitionProperty](akashaproject_design_system._internal_.Properties.md#webkittransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7500

___

### WebkitTransitionTimingFunction

• `Optional` **WebkitTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#webkittransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7508

___

### WebkitUserModify

• `Optional` **WebkitUserModify**: [`WebkitUserModify`](../modules/akashaproject_design_system._internal_.md#webkitusermodify)

**Syntax**: `read-only | read-write | read-write-plaintext-only`

**Initial value**: `read-only`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitUserModify](akashaproject_design_system._internal_.Properties.md#webkitusermodify)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7514

___

### WebkitUserSelect

• `Optional` **WebkitUserSelect**: [`UserSelect`](../modules/akashaproject_design_system._internal_.md#userselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitUserSelect](akashaproject_design_system._internal_.Properties.md#webkituserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7522

___

### WebkitWritingMode

• `Optional` **WebkitWritingMode**: [`WritingMode`](../modules/akashaproject_design_system._internal_.md#writingmode)

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (`html` element for HTML documents).

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[WebkitWritingMode](akashaproject_design_system._internal_.Properties.md#webkitwritingmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[accentColor](akashaproject_design_system._internal_.Properties.md#accentcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[alignContent](akashaproject_design_system._internal_.Properties.md#aligncontent)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[alignItems](akashaproject_design_system._internal_.Properties.md#alignitems)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[alignSelf](akashaproject_design_system._internal_.Properties.md#alignself)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[alignTracks](akashaproject_design_system._internal_.Properties.md#aligntracks)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:126

___

### alignmentBaseline

• `Optional` **alignmentBaseline**: [`AlignmentBaseline`](../modules/akashaproject_design_system._internal_.md#alignmentbaseline)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[alignmentBaseline](akashaproject_design_system._internal_.Properties.md#alignmentbaseline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[all](akashaproject_design_system._internal_.Properties.md#all)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5146

___

### animation

• `Optional` **animation**: [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)<`string` & {}\>

The **`animation`** shorthand CSS property applies an animation between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[animation](akashaproject_design_system._internal_.Properties.md#animation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5159

___

### animationDelay

• `Optional` **animationDelay**: [`AnimationDelay`](../modules/akashaproject_design_system._internal_.md#animationdelay)<`string` & {}\>

The **`animation-delay`** CSS property specifies the amount of time to wait from applying the animation to an element before beginning to perform the animation. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-delay

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[animationDelay](akashaproject_design_system._internal_.Properties.md#animationdelay)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationDirection](akashaproject_design_system._internal_.Properties.md#animationdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:156

___

### animationDuration

• `Optional` **animationDuration**: [`AnimationDuration`](../modules/akashaproject_design_system._internal_.md#animationduration)<`string` & {}\>

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-duration

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[animationDuration](akashaproject_design_system._internal_.Properties.md#animationduration)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationFillMode](akashaproject_design_system._internal_.Properties.md#animationfillmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationIterationCount](akashaproject_design_system._internal_.Properties.md#animationiterationcount)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationName](akashaproject_design_system._internal_.Properties.md#animationname)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationPlayState](akashaproject_design_system._internal_.Properties.md#animationplaystate)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[animationTimingFunction](akashaproject_design_system._internal_.Properties.md#animationtimingfunction)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[appearance](akashaproject_design_system._internal_.Properties.md#appearance)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[aspectRatio](akashaproject_design_system._internal_.Properties.md#aspectratio)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[azimuth](akashaproject_design_system._internal_.Properties.md#azimuth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backdropFilter](akashaproject_design_system._internal_.Properties.md#backdropfilter)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backfaceVisibility](akashaproject_design_system._internal_.Properties.md#backfacevisibility)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:304

___

### background

• `Optional` **background**: [`Background`](../modules/akashaproject_design_system._internal_.md#background)<`string` \| `number`\>

The **`background`** shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.

**Syntax**: `[ <bg-layer> , ]* <final-bg-layer>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[background](akashaproject_design_system._internal_.Properties.md#background)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundAttachment](akashaproject_design_system._internal_.Properties.md#backgroundattachment)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundBlendMode](akashaproject_design_system._internal_.Properties.md#backgroundblendmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundClip](akashaproject_design_system._internal_.Properties.md#backgroundclip)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundColor](akashaproject_design_system._internal_.Properties.md#backgroundcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundImage](akashaproject_design_system._internal_.Properties.md#backgroundimage)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundOrigin](akashaproject_design_system._internal_.Properties.md#backgroundorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:388

___

### backgroundPosition

• `Optional` **backgroundPosition**: [`BackgroundPosition`](../modules/akashaproject_design_system._internal_.md#backgroundposition)<`string` \| `number`\>

The **`background-position`** CSS property sets the initial position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `<bg-position>#`

**Initial value**: `0% 0%`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundPosition](akashaproject_design_system._internal_.Properties.md#backgroundposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5185

___

### backgroundPositionX

• `Optional` **backgroundPositionX**: [`BackgroundPositionX`](../modules/akashaproject_design_system._internal_.md#backgroundpositionx)<`string` \| `number`\>

The **`background-position-x`** CSS property sets the initial horizontal position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `[ center | [ [ left | right | x-start | x-end ]? <length-percentage>? ]! ]#`

**Initial value**: `left`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-x

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundPositionX](akashaproject_design_system._internal_.Properties.md#backgroundpositionx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:402

___

### backgroundPositionY

• `Optional` **backgroundPositionY**: [`BackgroundPositionY`](../modules/akashaproject_design_system._internal_.md#backgroundpositiony)<`string` \| `number`\>

The **`background-position-y`** CSS property sets the initial vertical position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `[ center | [ [ top | bottom | y-start | y-end ]? <length-percentage>? ]! ]#`

**Initial value**: `top`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-y

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundPositionY](akashaproject_design_system._internal_.Properties.md#backgroundpositiony)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundRepeat](akashaproject_design_system._internal_.Properties.md#backgroundrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:430

___

### backgroundSize

• `Optional` **backgroundSize**: [`BackgroundSize`](../modules/akashaproject_design_system._internal_.md#backgroundsize)<`string` \| `number`\>

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **3**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[backgroundSize](akashaproject_design_system._internal_.Properties.md#backgroundsize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:445

___

### baselineShift

• `Optional` **baselineShift**: [`BaselineShift`](../modules/akashaproject_design_system._internal_.md#baselineshift)<`string` \| `number`\>

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[baselineShift](akashaproject_design_system._internal_.Properties.md#baselineshift)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8749

___

### blockOverflow

• `Optional` **blockOverflow**: [`BlockOverflow`](../modules/akashaproject_design_system._internal_.md#blockoverflow)

**Syntax**: `clip | ellipsis | <string>`

**Initial value**: `clip`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[blockOverflow](akashaproject_design_system._internal_.Properties.md#blockoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:451

___

### blockSize

• `Optional` **blockSize**: [`BlockSize`](../modules/akashaproject_design_system._internal_.md#blocksize)<`string` \| `number`\>

The **`block-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/block-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[blockSize](akashaproject_design_system._internal_.Properties.md#blocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:465

___

### border

• `Optional` **border**: [`Border`](../modules/akashaproject_design_system._internal_.md#border)<`string` \| `number`\>

The **`border`** shorthand CSS property sets an element's border. It sets the values of `border-width`, `border-style`, and `border-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[border](akashaproject_design_system._internal_.Properties.md#border)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5197

___

### borderBlock

• `Optional` **borderBlock**: [`BorderBlock`](../modules/akashaproject_design_system._internal_.md#borderblock)<`string` \| `number`\>

The **`border-block`** CSS property is a shorthand property for setting the individual logical block border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlock](akashaproject_design_system._internal_.Properties.md#borderblock)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockColor](akashaproject_design_system._internal_.Properties.md#borderblockcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:479

___

### borderBlockEnd

• `Optional` **borderBlockEnd**: [`BorderBlockEnd`](../modules/akashaproject_design_system._internal_.md#borderblockend)<`string` \| `number`\>

The **`border-block-end`** CSS property is a shorthand property for setting the individual logical block-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockEnd](akashaproject_design_system._internal_.Properties.md#borderblockend)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockEndColor](akashaproject_design_system._internal_.Properties.md#borderblockendcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockEndStyle](akashaproject_design_system._internal_.Properties.md#borderblockendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:507

___

### borderBlockEndWidth

• `Optional` **borderBlockEndWidth**: [`BorderBlockEndWidth`](../modules/akashaproject_design_system._internal_.md#borderblockendwidth)<`string` \| `number`\>

The **`border-block-end-width`** CSS property defines the width of the logical block-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockEndWidth](akashaproject_design_system._internal_.Properties.md#borderblockendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:521

___

### borderBlockStart

• `Optional` **borderBlockStart**: [`BorderBlockStart`](../modules/akashaproject_design_system._internal_.md#borderblockstart)<`string` \| `number`\>

The **`border-block-start`** CSS property is a shorthand property for setting the individual logical block-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockStart](akashaproject_design_system._internal_.Properties.md#borderblockstart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockStartColor](akashaproject_design_system._internal_.Properties.md#borderblockstartcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockStartStyle](akashaproject_design_system._internal_.Properties.md#borderblockstartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:549

___

### borderBlockStartWidth

• `Optional` **borderBlockStartWidth**: [`BorderBlockStartWidth`](../modules/akashaproject_design_system._internal_.md#borderblockstartwidth)<`string` \| `number`\>

The **`border-block-start-width`** CSS property defines the width of the logical block-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockStartWidth](akashaproject_design_system._internal_.Properties.md#borderblockstartwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockStyle](akashaproject_design_system._internal_.Properties.md#borderblockstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:577

___

### borderBlockWidth

• `Optional` **borderBlockWidth**: [`BorderBlockWidth`](../modules/akashaproject_design_system._internal_.md#borderblockwidth)<`string` \| `number`\>

The **`border-block-width`** CSS property defines the width of the logical block borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBlockWidth](akashaproject_design_system._internal_.Properties.md#borderblockwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:591

___

### borderBottom

• `Optional` **borderBottom**: [`BorderBottom`](../modules/akashaproject_design_system._internal_.md#borderbottom)<`string` \| `number`\>

The **`border-bottom`** shorthand CSS property sets an element's bottom border. It sets the values of `border-bottom-width`, `border-bottom-style` and `border-bottom-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottom](akashaproject_design_system._internal_.Properties.md#borderbottom)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottomColor](akashaproject_design_system._internal_.Properties.md#borderbottomcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:605

___

### borderBottomLeftRadius

• `Optional` **borderBottomLeftRadius**: [`BorderBottomLeftRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradius)<`string` \| `number`\>

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-left-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottomLeftRadius](akashaproject_design_system._internal_.Properties.md#borderbottomleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:620

___

### borderBottomRightRadius

• `Optional` **borderBottomRightRadius**: [`BorderBottomRightRadius`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradius)<`string` \| `number`\>

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-right-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottomRightRadius](akashaproject_design_system._internal_.Properties.md#borderbottomrightradius)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottomStyle](akashaproject_design_system._internal_.Properties.md#borderbottomstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:649

___

### borderBottomWidth

• `Optional` **borderBottomWidth**: [`BorderBottomWidth`](../modules/akashaproject_design_system._internal_.md#borderbottomwidth)<`string` \| `number`\>

The **`border-bottom-width`** CSS property sets the width of the bottom border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderBottomWidth](akashaproject_design_system._internal_.Properties.md#borderbottomwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderCollapse](akashaproject_design_system._internal_.Properties.md#bordercollapse)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderColor](akashaproject_design_system._internal_.Properties.md#bordercolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5257

___

### borderEndEndRadius

• `Optional` **borderEndEndRadius**: [`BorderEndEndRadius`](../modules/akashaproject_design_system._internal_.md#borderendendradius)<`string` \| `number`\>

The **`border-end-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-end-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderEndEndRadius](akashaproject_design_system._internal_.Properties.md#borderendendradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:691

___

### borderEndStartRadius

• `Optional` **borderEndStartRadius**: [`BorderEndStartRadius`](../modules/akashaproject_design_system._internal_.md#borderendstartradius)<`string` \| `number`\>

The **`border-end-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-start-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderEndStartRadius](akashaproject_design_system._internal_.Properties.md#borderendstartradius)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImage](akashaproject_design_system._internal_.Properties.md#borderimage)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5270

___

### borderImageOutset

• `Optional` **borderImageOutset**: [`BorderImageOutset`](../modules/akashaproject_design_system._internal_.md#borderimageoutset)<`string` \| `number`\>

The **`border-image-outset`** CSS property sets the distance by which an element's border image is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-outset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImageOutset](akashaproject_design_system._internal_.Properties.md#borderimageoutset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImageRepeat](akashaproject_design_system._internal_.Properties.md#borderimagerepeat)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImageSlice](akashaproject_design_system._internal_.Properties.md#borderimageslice)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImageSource](akashaproject_design_system._internal_.Properties.md#borderimagesource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:761

___

### borderImageWidth

• `Optional` **borderImageWidth**: [`BorderImageWidth`](../modules/akashaproject_design_system._internal_.md#borderimagewidth)<`string` \| `number`\>

The **`border-image-width`** CSS property sets the width of an element's border image.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `1`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **13**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderImageWidth](akashaproject_design_system._internal_.Properties.md#borderimagewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:775

___

### borderInline

• `Optional` **borderInline**: [`BorderInline`](../modules/akashaproject_design_system._internal_.md#borderinline)<`string` \| `number`\>

The **`border-inline`** CSS property is a shorthand property for setting the individual logical inline border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInline](akashaproject_design_system._internal_.Properties.md#borderinline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineColor](akashaproject_design_system._internal_.Properties.md#borderinlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:789

___

### borderInlineEnd

• `Optional` **borderInlineEnd**: [`BorderInlineEnd`](../modules/akashaproject_design_system._internal_.md#borderinlineend)<`string` \| `number`\>

The **`border-inline-end`** CSS property is a shorthand property for setting the individual logical inline-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineEnd](akashaproject_design_system._internal_.Properties.md#borderinlineend)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineEndColor](akashaproject_design_system._internal_.Properties.md#borderinlineendcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineEndStyle](akashaproject_design_system._internal_.Properties.md#borderinlineendstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:819

___

### borderInlineEndWidth

• `Optional` **borderInlineEndWidth**: [`BorderInlineEndWidth`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidth)<`string` \| `number`\>

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-width)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineEndWidth](akashaproject_design_system._internal_.Properties.md#borderinlineendwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:834

___

### borderInlineStart

• `Optional` **borderInlineStart**: [`BorderInlineStart`](../modules/akashaproject_design_system._internal_.md#borderinlinestart)<`string` \| `number`\>

The **`border-inline-start`** CSS property is a shorthand property for setting the individual logical inline-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineStart](akashaproject_design_system._internal_.Properties.md#borderinlinestart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineStartColor](akashaproject_design_system._internal_.Properties.md#borderinlinestartcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineStartStyle](akashaproject_design_system._internal_.Properties.md#borderinlinestartstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:864

___

### borderInlineStartWidth

• `Optional` **borderInlineStartWidth**: [`BorderInlineStartWidth`](../modules/akashaproject_design_system._internal_.md#borderinlinestartwidth)<`string` \| `number`\>

The **`border-inline-start-width`** CSS property defines the width of the logical inline-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineStartWidth](akashaproject_design_system._internal_.Properties.md#borderinlinestartwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineStyle](akashaproject_design_system._internal_.Properties.md#borderinlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:892

___

### borderInlineWidth

• `Optional` **borderInlineWidth**: [`BorderInlineWidth`](../modules/akashaproject_design_system._internal_.md#borderinlinewidth)<`string` \| `number`\>

The **`border-inline-width`** CSS property defines the width of the logical inline borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderInlineWidth](akashaproject_design_system._internal_.Properties.md#borderinlinewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:906

___

### borderLeft

• `Optional` **borderLeft**: [`BorderLeft`](../modules/akashaproject_design_system._internal_.md#borderleft)<`string` \| `number`\>

The **`border-left`** shorthand CSS property sets all the properties of an element's left border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderLeft](akashaproject_design_system._internal_.Properties.md#borderleft)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderLeftColor](akashaproject_design_system._internal_.Properties.md#borderleftcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderLeftStyle](akashaproject_design_system._internal_.Properties.md#borderleftstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:934

___

### borderLeftWidth

• `Optional` **borderLeftWidth**: [`BorderLeftWidth`](../modules/akashaproject_design_system._internal_.md#borderleftwidth)<`string` \| `number`\>

The **`border-left-width`** CSS property sets the width of the left border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderLeftWidth](akashaproject_design_system._internal_.Properties.md#borderleftwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:948

___

### borderRadius

• `Optional` **borderRadius**: [`BorderRadius`](../modules/akashaproject_design_system._internal_.md#borderradius)<`string` \| `number`\>

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderRadius](akashaproject_design_system._internal_.Properties.md#borderradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5331

___

### borderRight

• `Optional` **borderRight**: [`BorderRight`](../modules/akashaproject_design_system._internal_.md#borderright)<`string` \| `number`\>

The **`border-right`** shorthand CSS property sets all the properties of an element's right border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderRight](akashaproject_design_system._internal_.Properties.md#borderright)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderRightColor](akashaproject_design_system._internal_.Properties.md#borderrightcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderRightStyle](akashaproject_design_system._internal_.Properties.md#borderrightstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:976

___

### borderRightWidth

• `Optional` **borderRightWidth**: [`BorderRightWidth`](../modules/akashaproject_design_system._internal_.md#borderrightwidth)<`string` \| `number`\>

The **`border-right-width`** CSS property sets the width of the right border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderRightWidth](akashaproject_design_system._internal_.Properties.md#borderrightwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:990

___

### borderSpacing

• `Optional` **borderSpacing**: [`BorderSpacing`](../modules/akashaproject_design_system._internal_.md#borderspacing)<`string` \| `number`\>

The **`border-spacing`** CSS property sets the distance between the borders of adjacent `<table>` cells. This property applies only when `border-collapse` is `separate`.

**Syntax**: `<length> <length>?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-spacing

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderSpacing](akashaproject_design_system._internal_.Properties.md#borderspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1004

___

### borderStartEndRadius

• `Optional` **borderStartEndRadius**: [`BorderStartEndRadius`](../modules/akashaproject_design_system._internal_.md#borderstartendradius)<`string` \| `number`\>

The **`border-start-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-end-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderStartEndRadius](akashaproject_design_system._internal_.Properties.md#borderstartendradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1018

___

### borderStartStartRadius

• `Optional` **borderStartStartRadius**: [`BorderStartStartRadius`](../modules/akashaproject_design_system._internal_.md#borderstartstartradius)<`string` \| `number`\>

The **`border-start-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on the element's `writing-mode`, `direction`, and `text-orientation`. This is useful when building styles to work regardless of the text orientation and writing mode.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-start-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderStartStartRadius](akashaproject_design_system._internal_.Properties.md#borderstartstartradius)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderStyle](akashaproject_design_system._internal_.Properties.md#borderstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5355

___

### borderTop

• `Optional` **borderTop**: [`BorderTop`](../modules/akashaproject_design_system._internal_.md#bordertop)<`string` \| `number`\>

The **`border-top`** shorthand CSS property sets all the properties of an element's top border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTop](akashaproject_design_system._internal_.Properties.md#bordertop)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTopColor](akashaproject_design_system._internal_.Properties.md#bordertopcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1046

___

### borderTopLeftRadius

• `Optional` **borderTopLeftRadius**: [`BorderTopLeftRadius`](../modules/akashaproject_design_system._internal_.md#bordertopleftradius)<`string` \| `number`\>

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-left-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTopLeftRadius](akashaproject_design_system._internal_.Properties.md#bordertopleftradius)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1061

___

### borderTopRightRadius

• `Optional` **borderTopRightRadius**: [`BorderTopRightRadius`](../modules/akashaproject_design_system._internal_.md#bordertoprightradius)<`string` \| `number`\>

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element by specifying the radius (or the radius of the semi-major and semi-minor axes) of the ellipse defining the curvature of the corner.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-right-radius

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTopRightRadius](akashaproject_design_system._internal_.Properties.md#bordertoprightradius)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTopStyle](akashaproject_design_system._internal_.Properties.md#bordertopstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1090

___

### borderTopWidth

• `Optional` **borderTopWidth**: [`BorderTopWidth`](../modules/akashaproject_design_system._internal_.md#bordertopwidth)<`string` \| `number`\>

The **`border-top-width`** CSS property sets the width of the top border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderTopWidth](akashaproject_design_system._internal_.Properties.md#bordertopwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1104

___

### borderWidth

• `Optional` **borderWidth**: [`BorderWidth`](../modules/akashaproject_design_system._internal_.md#borderwidth)<`string` \| `number`\>

The **`border-width`** shorthand CSS property sets the width of an element's border.

**Syntax**: `<line-width>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[borderWidth](akashaproject_design_system._internal_.Properties.md#borderwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5379

___

### bottom

• `Optional` **bottom**: [`Bottom`](../modules/akashaproject_design_system._internal_.md#bottom)<`string` \| `number`\>

The **`bottom`** CSS property participates in setting the vertical position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[bottom](akashaproject_design_system._internal_.Properties.md#bottom)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxAlign](akashaproject_design_system._internal_.Properties.md#boxalign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxDecorationBreak](akashaproject_design_system._internal_.Properties.md#boxdecorationbreak)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxDirection](akashaproject_design_system._internal_.Properties.md#boxdirection)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxFlex](akashaproject_design_system._internal_.Properties.md#boxflex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxFlexGroup](akashaproject_design_system._internal_.Properties.md#boxflexgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxLines](akashaproject_design_system._internal_.Properties.md#boxlines)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxOrdinalGroup](akashaproject_design_system._internal_.Properties.md#boxordinalgroup)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxOrient](akashaproject_design_system._internal_.Properties.md#boxorient)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxPack](akashaproject_design_system._internal_.Properties.md#boxpack)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxShadow](akashaproject_design_system._internal_.Properties.md#boxshadow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[boxSizing](akashaproject_design_system._internal_.Properties.md#boxsizing)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[breakAfter](akashaproject_design_system._internal_.Properties.md#breakafter)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[breakBefore](akashaproject_design_system._internal_.Properties.md#breakbefore)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[breakInside](akashaproject_design_system._internal_.Properties.md#breakinside)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[captionSide](akashaproject_design_system._internal_.Properties.md#captionside)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[caretColor](akashaproject_design_system._internal_.Properties.md#caretcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[clear](akashaproject_design_system._internal_.Properties.md#clear)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[clip](akashaproject_design_system._internal_.Properties.md#clip)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[clipPath](akashaproject_design_system._internal_.Properties.md#clippath)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1303

___

### clipRule

• `Optional` **clipRule**: [`ClipRule`](../modules/akashaproject_design_system._internal_.md#cliprule)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[clipRule](akashaproject_design_system._internal_.Properties.md#cliprule)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[color](akashaproject_design_system._internal_.Properties.md#color)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[colorAdjust](akashaproject_design_system._internal_.Properties.md#coloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1331

___

### colorInterpolation

• `Optional` **colorInterpolation**: [`ColorInterpolation`](../modules/akashaproject_design_system._internal_.md#colorinterpolation)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[colorInterpolation](akashaproject_design_system._internal_.Properties.md#colorinterpolation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8754

___

### colorRendering

• `Optional` **colorRendering**: [`ColorRendering`](../modules/akashaproject_design_system._internal_.md#colorrendering)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[colorRendering](akashaproject_design_system._internal_.Properties.md#colorrendering)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[colorScheme](akashaproject_design_system._internal_.Properties.md#colorscheme)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnCount](akashaproject_design_system._internal_.Properties.md#columncount)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnFill](akashaproject_design_system._internal_.Properties.md#columnfill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1375

___

### columnGap

• `Optional` **columnGap**: [`ColumnGap`](../modules/akashaproject_design_system._internal_.md#columngap)<`string` \| `number`\>

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnGap](akashaproject_design_system._internal_.Properties.md#columngap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1413

___

### columnRule

• `Optional` **columnRule**: [`ColumnRule`](../modules/akashaproject_design_system._internal_.md#columnrule)<`string` \| `number`\>

The **`column-rule`** shorthand CSS property sets the width, style, and color of the line drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[columnRule](akashaproject_design_system._internal_.Properties.md#columnrule)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnRuleColor](akashaproject_design_system._internal_.Properties.md#columnrulecolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnRuleStyle](akashaproject_design_system._internal_.Properties.md#columnrulestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1443

___

### columnRuleWidth

• `Optional` **columnRuleWidth**: [`ColumnRuleWidth`](../modules/akashaproject_design_system._internal_.md#columnrulewidth)<`string` \| `number`\>

The **`column-rule-width`** CSS property sets the width of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[columnRuleWidth](akashaproject_design_system._internal_.Properties.md#columnrulewidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[columnSpan](akashaproject_design_system._internal_.Properties.md#columnspan)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1473

___

### columnWidth

• `Optional` **columnWidth**: [`ColumnWidth`](../modules/akashaproject_design_system._internal_.md#columnwidth)<`string` \| `number`\>

The **`column-width`** CSS property sets the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **50**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[columnWidth](akashaproject_design_system._internal_.Properties.md#columnwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1488

___

### columns

• `Optional` **columns**: [`Columns`](../modules/akashaproject_design_system._internal_.md#columns)<`string` \| `number`\>

The **`columns`** CSS shorthand property sets the number of columns to use when drawing an element's contents, as well as those columns' widths.

**Syntax**: `<'column-width'> || <'column-count'>`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **50** | **52**  |  **9**  | **12** | **10** |
|        |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/columns

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[columns](akashaproject_design_system._internal_.Properties.md#columns)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[contain](akashaproject_design_system._internal_.Properties.md#contain)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[content](akashaproject_design_system._internal_.Properties.md#content)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[contentVisibility](akashaproject_design_system._internal_.Properties.md#contentvisibility)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[counterIncrement](akashaproject_design_system._internal_.Properties.md#counterincrement)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[counterReset](akashaproject_design_system._internal_.Properties.md#counterreset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[counterSet](akashaproject_design_system._internal_.Properties.md#counterset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[cursor](akashaproject_design_system._internal_.Properties.md#cursor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[direction](akashaproject_design_system._internal_.Properties.md#direction)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[display](akashaproject_design_system._internal_.Properties.md#display)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1614

___

### dominantBaseline

• `Optional` **dominantBaseline**: [`DominantBaseline`](../modules/akashaproject_design_system._internal_.md#dominantbaseline)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[dominantBaseline](akashaproject_design_system._internal_.Properties.md#dominantbaseline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[emptyCells](akashaproject_design_system._internal_.Properties.md#emptycells)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1628

___

### fill

• `Optional` **fill**: [`Fill`](../modules/akashaproject_design_system._internal_.md#fill)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[fill](akashaproject_design_system._internal_.Properties.md#fill)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8760

___

### fillOpacity

• `Optional` **fillOpacity**: [`FillOpacity`](../modules/akashaproject_design_system._internal_.md#fillopacity)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[fillOpacity](akashaproject_design_system._internal_.Properties.md#fillopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8761

___

### fillRule

• `Optional` **fillRule**: [`FillRule`](../modules/akashaproject_design_system._internal_.md#fillrule)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[fillRule](akashaproject_design_system._internal_.Properties.md#fillrule)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[filter](akashaproject_design_system._internal_.Properties.md#filter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1643

___

### flex

• `Optional` **flex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`string` \| `number`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[flex](akashaproject_design_system._internal_.Properties.md#flex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5418

___

### flexBasis

• `Optional` **flexBasis**: [`FlexBasis`](../modules/akashaproject_design_system._internal_.md#flexbasis)<`string` \| `number`\>

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **22**  |  **9**  | **12** | **11** |
| 22 _-x-_ |         | 7 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-basis

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[flexBasis](akashaproject_design_system._internal_.Properties.md#flexbasis)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[flexDirection](akashaproject_design_system._internal_.Properties.md#flexdirection)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[flexFlow](akashaproject_design_system._internal_.Properties.md#flexflow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[flexGrow](akashaproject_design_system._internal_.Properties.md#flexgrow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[flexShrink](akashaproject_design_system._internal_.Properties.md#flexshrink)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[flexWrap](akashaproject_design_system._internal_.Properties.md#flexwrap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[float](akashaproject_design_system._internal_.Properties.md#float)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1732

___

### floodColor

• `Optional` **floodColor**: [`FloodColor`](../modules/akashaproject_design_system._internal_.md#floodcolor)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[floodColor](akashaproject_design_system._internal_.Properties.md#floodcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8764

___

### floodOpacity

• `Optional` **floodOpacity**: [`FloodOpacity`](../modules/akashaproject_design_system._internal_.md#floodopacity)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[floodOpacity](akashaproject_design_system._internal_.Properties.md#floodopacity)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[font](akashaproject_design_system._internal_.Properties.md#font)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontFamily](akashaproject_design_system._internal_.Properties.md#fontfamily)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontFeatureSettings](akashaproject_design_system._internal_.Properties.md#fontfeaturesettings)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontKerning](akashaproject_design_system._internal_.Properties.md#fontkerning)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontLanguageOverride](akashaproject_design_system._internal_.Properties.md#fontlanguageoverride)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontOpticalSizing](akashaproject_design_system._internal_.Properties.md#fontopticalsizing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1805

___

### fontSize

• `Optional` **fontSize**: [`FontSize`](../modules/akashaproject_design_system._internal_.md#fontsize)<`string` \| `number`\>

The **`font-size`** CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative `<length>` units, such as `em`, `ex`, and so forth.

**Syntax**: `<absolute-size> | <relative-size> | <length-percentage>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[fontSize](akashaproject_design_system._internal_.Properties.md#fontsize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontSizeAdjust](akashaproject_design_system._internal_.Properties.md#fontsizeadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:1833

___

### fontSmooth

• `Optional` **fontSmooth**: [`FontSmooth`](../modules/akashaproject_design_system._internal_.md#fontsmooth)<`string` \| `number`\>

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

|              Chrome              |              Firefox               |              Safari              |               Edge                | IE  |
| :------------------------------: | :--------------------------------: | :------------------------------: | :-------------------------------: | :-: |
| **5** _(-webkit-font-smoothing)_ | **25** _(-moz-osx-font-smoothing)_ | **4** _(-webkit-font-smoothing)_ | **79** _(-webkit-font-smoothing)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-smooth

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[fontSmooth](akashaproject_design_system._internal_.Properties.md#fontsmooth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontStretch](akashaproject_design_system._internal_.Properties.md#fontstretch)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontStyle](akashaproject_design_system._internal_.Properties.md#fontstyle)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontSynthesis](akashaproject_design_system._internal_.Properties.md#fontsynthesis)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariant](akashaproject_design_system._internal_.Properties.md#fontvariant)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantAlternates](akashaproject_design_system._internal_.Properties.md#fontvariantalternates)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantCaps](akashaproject_design_system._internal_.Properties.md#fontvariantcaps)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantEastAsian](akashaproject_design_system._internal_.Properties.md#fontvarianteastasian)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantLigatures](akashaproject_design_system._internal_.Properties.md#fontvariantligatures)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantNumeric](akashaproject_design_system._internal_.Properties.md#fontvariantnumeric)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariantPosition](akashaproject_design_system._internal_.Properties.md#fontvariantposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontVariationSettings](akashaproject_design_system._internal_.Properties.md#fontvariationsettings)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[fontWeight](akashaproject_design_system._internal_.Properties.md#fontweight)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[forcedColorAdjust](akashaproject_design_system._internal_.Properties.md#forcedcoloradjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2017

___

### gap

• `Optional` **gap**: [`Gap`](../modules/akashaproject_design_system._internal_.md#gap)<`string` \| `number`\>

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gap](akashaproject_design_system._internal_.Properties.md#gap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5478

___

### glyphOrientationVertical

• `Optional` **glyphOrientationVertical**: [`GlyphOrientationVertical`](../modules/akashaproject_design_system._internal_.md#glyphorientationvertical)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[glyphOrientationVertical](akashaproject_design_system._internal_.Properties.md#glyphorientationvertical)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[grid](akashaproject_design_system._internal_.Properties.md#grid)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridArea](akashaproject_design_system._internal_.Properties.md#gridarea)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5502

___

### gridAutoColumns

• `Optional` **gridAutoColumns**: [`GridAutoColumns`](../modules/akashaproject_design_system._internal_.md#gridautocolumns)<`string` \| `number`\>

The **`grid-auto-columns`** CSS property specifies the size of an implicitly-created grid column track or pattern of tracks.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-columns

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridAutoColumns](akashaproject_design_system._internal_.Properties.md#gridautocolumns)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridAutoFlow](akashaproject_design_system._internal_.Properties.md#gridautoflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2045

___

### gridAutoRows

• `Optional` **gridAutoRows**: [`GridAutoRows`](../modules/akashaproject_design_system._internal_.md#gridautorows)<`string` \| `number`\>

The **`grid-auto-rows`** CSS property specifies the size of an implicitly-created grid row track or pattern of tracks.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-rows

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridAutoRows](akashaproject_design_system._internal_.Properties.md#gridautorows)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridColumn](akashaproject_design_system._internal_.Properties.md#gridcolumn)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridColumnEnd](akashaproject_design_system._internal_.Properties.md#gridcolumnend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2073

___

### gridColumnGap

• `Optional` **gridColumnGap**: [`GridColumnGap`](../modules/akashaproject_design_system._internal_.md#gridcolumngap)<`string` \| `number`\>

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridColumnGap](akashaproject_design_system._internal_.Properties.md#gridcolumngap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridColumnStart](akashaproject_design_system._internal_.Properties.md#gridcolumnstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2087

___

### gridGap

• `Optional` **gridGap**: [`GridGap`](../modules/akashaproject_design_system._internal_.md#gridgap)<`string` \| `number`\>

The **`gap`** CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for `row-gap` and `column-gap`.

**Syntax**: `<'grid-row-gap'> <'grid-column-gap'>?`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridGap](akashaproject_design_system._internal_.Properties.md#gridgap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridRow](akashaproject_design_system._internal_.Properties.md#gridrow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridRowEnd](akashaproject_design_system._internal_.Properties.md#gridrowend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2101

___

### gridRowGap

• `Optional` **gridRowGap**: [`GridRowGap`](../modules/akashaproject_design_system._internal_.md#gridrowgap)<`string` \| `number`\>

The **`row-gap`** CSS property sets the size of the gap (gutter) between an element's grid rows.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridRowGap](akashaproject_design_system._internal_.Properties.md#gridrowgap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridRowStart](akashaproject_design_system._internal_.Properties.md#gridrowstart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridTemplate](akashaproject_design_system._internal_.Properties.md#gridtemplate)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[gridTemplateAreas](akashaproject_design_system._internal_.Properties.md#gridtemplateareas)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2129

___

### gridTemplateColumns

• `Optional` **gridTemplateColumns**: [`GridTemplateColumns`](../modules/akashaproject_design_system._internal_.md#gridtemplatecolumns)<`string` \| `number`\>

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-columns

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridTemplateColumns](akashaproject_design_system._internal_.Properties.md#gridtemplatecolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2143

___

### gridTemplateRows

• `Optional` **gridTemplateRows**: [`GridTemplateRows`](../modules/akashaproject_design_system._internal_.md#gridtemplaterows)<`string` \| `number`\>

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-rows

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[gridTemplateRows](akashaproject_design_system._internal_.Properties.md#gridtemplaterows)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[hangingPunctuation](akashaproject_design_system._internal_.Properties.md#hangingpunctuation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2171

___

### height

• `Optional` **height**: [`Height`](../modules/akashaproject_design_system._internal_.md#height)<`string` \| `number`\>

The **`height`** CSS property specifies the height of an element. By default, the property defines the height of the content area. If `box-sizing` is set to `border-box`, however, it instead determines the height of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/height

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[height](akashaproject_design_system._internal_.Properties.md#height)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[hyphens](akashaproject_design_system._internal_.Properties.md#hyphens)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[imageOrientation](akashaproject_design_system._internal_.Properties.md#imageorientation)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[imageRendering](akashaproject_design_system._internal_.Properties.md#imagerendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2228

___

### imageResolution

• `Optional` **imageResolution**: [`ImageResolution`](../modules/akashaproject_design_system._internal_.md#imageresolution)

**Syntax**: `[ from-image || <resolution> ] && snap?`

**Initial value**: `1dppx`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[imageResolution](akashaproject_design_system._internal_.Properties.md#imageresolution)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[imeMode](akashaproject_design_system._internal_.Properties.md#imemode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[initialLetter](akashaproject_design_system._internal_.Properties.md#initialletter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2248

___

### inlineSize

• `Optional` **inlineSize**: [`InlineSize`](../modules/akashaproject_design_system._internal_.md#inlinesize)<`string` \| `number`\>

The **`inline-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inline-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[inlineSize](akashaproject_design_system._internal_.Properties.md#inlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2262

___

### inset

• `Optional` **inset**: [`Inset`](../modules/akashaproject_design_system._internal_.md#inset)<`string` \| `number`\>

The **`inset`** CSS property is a shorthand that corresponds to the `top`, `right`, `bottom`, and/or `left` properties. It has the same multi-value syntax of the `margin` shorthand.

**Syntax**: `<'top'>{1,4}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[inset](akashaproject_design_system._internal_.Properties.md#inset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2276

___

### insetBlock

• `Optional` **insetBlock**: [`InsetBlock`](../modules/akashaproject_design_system._internal_.md#insetblock)<`string` \| `number`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetBlock](akashaproject_design_system._internal_.Properties.md#insetblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2290

___

### insetBlockEnd

• `Optional` **insetBlockEnd**: [`InsetBlockEnd`](../modules/akashaproject_design_system._internal_.md#insetblockend)<`string` \| `number`\>

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetBlockEnd](akashaproject_design_system._internal_.Properties.md#insetblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2304

___

### insetBlockStart

• `Optional` **insetBlockStart**: [`InsetBlockStart`](../modules/akashaproject_design_system._internal_.md#insetblockstart)<`string` \| `number`\>

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetBlockStart](akashaproject_design_system._internal_.Properties.md#insetblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2318

___

### insetInline

• `Optional` **insetInline**: [`InsetInline`](../modules/akashaproject_design_system._internal_.md#insetinline)<`string` \| `number`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetInline](akashaproject_design_system._internal_.Properties.md#insetinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2332

___

### insetInlineEnd

• `Optional` **insetInlineEnd**: [`InsetInlineEnd`](../modules/akashaproject_design_system._internal_.md#insetinlineend)<`string` \| `number`\>

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetInlineEnd](akashaproject_design_system._internal_.Properties.md#insetinlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2346

___

### insetInlineStart

• `Optional` **insetInlineStart**: [`InsetInlineStart`](../modules/akashaproject_design_system._internal_.md#insetinlinestart)<`string` \| `number`\>

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[insetInlineStart](akashaproject_design_system._internal_.Properties.md#insetinlinestart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[isolation](akashaproject_design_system._internal_.Properties.md#isolation)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[justifyContent](akashaproject_design_system._internal_.Properties.md#justifycontent)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[justifyItems](akashaproject_design_system._internal_.Properties.md#justifyitems)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[justifySelf](akashaproject_design_system._internal_.Properties.md#justifyself)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[justifyTracks](akashaproject_design_system._internal_.Properties.md#justifytracks)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2473

___

### left

• `Optional` **left**: [`Left`](../modules/akashaproject_design_system._internal_.md#left)<`string` \| `number`\>

The **`left`** CSS property participates in specifying the horizontal position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[left](akashaproject_design_system._internal_.Properties.md#left)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2487

___

### letterSpacing

• `Optional` **letterSpacing**: [`LetterSpacing`](../modules/akashaproject_design_system._internal_.md#letterspacing)<`string` \| `number`\>

The **`letter-spacing`** CSS property sets the horizontal spacing behavior between text characters. This value is added to the natural spacing between characters while rendering the text. Positive values of `letter-spacing` causes characters to spread farther apart, while negative values of `letter-spacing` bring characters closer together.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/letter-spacing

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[letterSpacing](akashaproject_design_system._internal_.Properties.md#letterspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2501

___

### lightingColor

• `Optional` **lightingColor**: [`LightingColor`](../modules/akashaproject_design_system._internal_.md#lightingcolor)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[lightingColor](akashaproject_design_system._internal_.Properties.md#lightingcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[lineBreak](akashaproject_design_system._internal_.Properties.md#linebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2516

___

### lineClamp

• `Optional` **lineClamp**: [`LineClamp`](../modules/akashaproject_design_system._internal_.md#lineclamp)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[lineClamp](akashaproject_design_system._internal_.Properties.md#lineclamp)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5544

___

### lineHeight

• `Optional` **lineHeight**: [`LineHeight`](../modules/akashaproject_design_system._internal_.md#lineheight)<`string` \| `number`\>

The **`line-height`** CSS property sets the height of a line box. It's commonly used to set the distance between lines of text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.

**Syntax**: `normal | <number> | <length> | <percentage>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[lineHeight](akashaproject_design_system._internal_.Properties.md#lineheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2530

___

### lineHeightStep

• `Optional` **lineHeightStep**: [`LineHeightStep`](../modules/akashaproject_design_system._internal_.md#lineheightstep)<`string` \| `number`\>

The **`line-height-step`** CSS property sets the step unit for line box heights. When the property is set, line box heights are rounded up to the closest multiple of the unit.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |   No    |   No   | n/a  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height-step

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[lineHeightStep](akashaproject_design_system._internal_.Properties.md#lineheightstep)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[listStyle](akashaproject_design_system._internal_.Properties.md#liststyle)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[listStyleImage](akashaproject_design_system._internal_.Properties.md#liststyleimage)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[listStylePosition](akashaproject_design_system._internal_.Properties.md#liststyleposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[listStyleType](akashaproject_design_system._internal_.Properties.md#liststyletype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2586

___

### margin

• `Optional` **margin**: [`Margin`](../modules/akashaproject_design_system._internal_.md#margin)<`string` \| `number`\>

The **`margin`** CSS property sets the margin area on all four sides of an element. It is a shorthand for `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`.

**Syntax**: `[ <length> | <percentage> | auto ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[margin](akashaproject_design_system._internal_.Properties.md#margin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5568

___

### marginBlock

• `Optional` **marginBlock**: [`MarginBlock`](../modules/akashaproject_design_system._internal_.md#marginblock)<`string` \| `number`\>

The **`margin-block`** CSS shorthand property defines the logical block start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginBlock](akashaproject_design_system._internal_.Properties.md#marginblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2600

___

### marginBlockEnd

• `Optional` **marginBlockEnd**: [`MarginBlockEnd`](../modules/akashaproject_design_system._internal_.md#marginblockend)<`string` \| `number`\>

The **`margin-block-end`** CSS property defines the logical block end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginBlockEnd](akashaproject_design_system._internal_.Properties.md#marginblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2614

___

### marginBlockStart

• `Optional` **marginBlockStart**: [`MarginBlockStart`](../modules/akashaproject_design_system._internal_.md#marginblockstart)<`string` \| `number`\>

The **`margin-block-start`** CSS property defines the logical block start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginBlockStart](akashaproject_design_system._internal_.Properties.md#marginblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2628

___

### marginBottom

• `Optional` **marginBottom**: [`MarginBottom`](../modules/akashaproject_design_system._internal_.md#marginbottom)<`string` \| `number`\>

The **`margin-bottom`** CSS property sets the margin area on the bottom of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginBottom](akashaproject_design_system._internal_.Properties.md#marginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2642

___

### marginInline

• `Optional` **marginInline**: [`MarginInline`](../modules/akashaproject_design_system._internal_.md#margininline)<`string` \| `number`\>

The **`margin-inline`** CSS shorthand property is a shorthand property that defines both the logical inline start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginInline](akashaproject_design_system._internal_.Properties.md#margininline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2656

___

### marginInlineEnd

• `Optional` **marginInlineEnd**: [`MarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#margininlineend)<`string` \| `number`\>

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|          Chrome          |        Firefox        |          Safari          |  Edge  | IE  |
| :----------------------: | :-------------------: | :----------------------: | :----: | :-: |
|          **69**          |        **41**         |         **12.1**         | **79** | No  |
| 2 _(-webkit-margin-end)_ | 3 _(-moz-margin-end)_ | 3 _(-webkit-margin-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginInlineEnd](akashaproject_design_system._internal_.Properties.md#margininlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2671

___

### marginInlineStart

• `Optional` **marginInlineStart**: [`MarginInlineStart`](../modules/akashaproject_design_system._internal_.md#margininlinestart)<`string` \| `number`\>

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|           Chrome           |         Firefox         |           Safari           |  Edge  | IE  |
| :------------------------: | :---------------------: | :------------------------: | :----: | :-: |
|           **69**           |         **41**          |          **12.1**          | **79** | No  |
| 2 _(-webkit-margin-start)_ | 3 _(-moz-margin-start)_ | 3 _(-webkit-margin-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginInlineStart](akashaproject_design_system._internal_.Properties.md#margininlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2686

___

### marginLeft

• `Optional` **marginLeft**: [`MarginLeft`](../modules/akashaproject_design_system._internal_.md#marginleft)<`string` \| `number`\>

The **`margin-left`** CSS property sets the margin area on the left side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginLeft](akashaproject_design_system._internal_.Properties.md#marginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2700

___

### marginRight

• `Optional` **marginRight**: [`MarginRight`](../modules/akashaproject_design_system._internal_.md#marginright)<`string` \| `number`\>

The **`margin-right`** CSS property sets the margin area on the right side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginRight](akashaproject_design_system._internal_.Properties.md#marginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2714

___

### marginTop

• `Optional` **marginTop**: [`MarginTop`](../modules/akashaproject_design_system._internal_.md#margintop)<`string` \| `number`\>

The **`margin-top`** CSS property sets the margin area on the top of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marginTop](akashaproject_design_system._internal_.Properties.md#margintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2728

___

### marker

• `Optional` **marker**: [`Marker`](../modules/akashaproject_design_system._internal_.md#marker)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[marker](akashaproject_design_system._internal_.Properties.md#marker)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8779

___

### markerEnd

• `Optional` **markerEnd**: [`MarkerEnd`](../modules/akashaproject_design_system._internal_.md#markerend)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[markerEnd](akashaproject_design_system._internal_.Properties.md#markerend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8780

___

### markerMid

• `Optional` **markerMid**: [`MarkerMid`](../modules/akashaproject_design_system._internal_.md#markermid)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[markerMid](akashaproject_design_system._internal_.Properties.md#markermid)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8781

___

### markerStart

• `Optional` **markerStart**: [`MarkerStart`](../modules/akashaproject_design_system._internal_.md#markerstart)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[markerStart](akashaproject_design_system._internal_.Properties.md#markerstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8782

___

### mask

• `Optional` **mask**: [`Mask`](../modules/akashaproject_design_system._internal_.md#mask)<`string` \| `number`\>

The **`mask`** CSS shorthand property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `<mask-layer>#`

| Chrome | Firefox | Safari  | Edge  | IE  |
| :----: | :-----: | :-----: | :---: | :-: |
| **1**  |  **2**  | **3.1** | 12-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[mask](akashaproject_design_system._internal_.Properties.md#mask)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorder](akashaproject_design_system._internal_.Properties.md#maskborder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5592

___

### maskBorderMode

• `Optional` **maskBorderMode**: [`MaskBorderMode`](../modules/akashaproject_design_system._internal_.md#maskbordermode)

The **`mask-border-mode`** CSS property specifies the blending mode used in a mask border.

**Syntax**: `luminance | alpha`

**Initial value**: `alpha`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderMode](akashaproject_design_system._internal_.Properties.md#maskbordermode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2736

___

### maskBorderOutset

• `Optional` **maskBorderOutset**: [`MaskBorderOutset`](../modules/akashaproject_design_system._internal_.md#maskborderoutset)<`string` \| `number`\>

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-outset)_ |   No    | **3.1** _(-webkit-mask-box-image-outset)_ | **79** _(-webkit-mask-box-image-outset)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-outset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderOutset](akashaproject_design_system._internal_.Properties.md#maskborderoutset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderRepeat](akashaproject_design_system._internal_.Properties.md#maskborderrepeat)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderSlice](akashaproject_design_system._internal_.Properties.md#maskborderslice)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderSource](akashaproject_design_system._internal_.Properties.md#maskbordersource)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2792

___

### maskBorderWidth

• `Optional` **maskBorderWidth**: [`MaskBorderWidth`](../modules/akashaproject_design_system._internal_.md#maskborderwidth)<`string` \| `number`\>

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

|                 Chrome                 | Firefox |                  Safari                  |                  Edge                   | IE  |
| :------------------------------------: | :-----: | :--------------------------------------: | :-------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-width)_ |   No    | **3.1** _(-webkit-mask-box-image-width)_ | **79** _(-webkit-mask-box-image-width)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maskBorderWidth](akashaproject_design_system._internal_.Properties.md#maskborderwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskClip](akashaproject_design_system._internal_.Properties.md#maskclip)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskComposite](akashaproject_design_system._internal_.Properties.md#maskcomposite)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskImage](akashaproject_design_system._internal_.Properties.md#maskimage)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskMode](akashaproject_design_system._internal_.Properties.md#maskmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskOrigin](akashaproject_design_system._internal_.Properties.md#maskorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2876

___

### maskPosition

• `Optional` **maskPosition**: [`MaskPosition`](../modules/akashaproject_design_system._internal_.md#maskposition)<`string` \| `number`\>

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `center`

|   Chrome    | Firefox |    Safari     | Edge  | IE  |
| :---------: | :-----: | :-----------: | :---: | :-: |
| **1** _-x-_ | **53**  | **3.1** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-position

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maskPosition](akashaproject_design_system._internal_.Properties.md#maskposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskRepeat](akashaproject_design_system._internal_.Properties.md#maskrepeat)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2904

___

### maskSize

• `Optional` **maskSize**: [`MaskSize`](../modules/akashaproject_design_system._internal_.md#masksize)<`string` \| `number`\>

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto`

|   Chrome    | Firefox |   Safari    | Edge  | IE  |
| :---------: | :-----: | :---------: | :---: | :-: |
| **4** _-x-_ | **53**  | **4** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maskSize](akashaproject_design_system._internal_.Properties.md#masksize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[maskType](akashaproject_design_system._internal_.Properties.md#masktype)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[mathStyle](akashaproject_design_system._internal_.Properties.md#mathstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2946

___

### maxBlockSize

• `Optional` **maxBlockSize**: [`MaxBlockSize`](../modules/akashaproject_design_system._internal_.md#maxblocksize)<`string` \| `number`\>

The `**max-block-size**` CSS property specifies the maximum size of an element in the direction opposite that of the writing direction as specified by `writing-mode`. That is, if the writing direction is horizontal, then `max-block-size` is equivalent to `max-height`; if the writing direction is vertical, `max-block-size` is the same as `max-width`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-block-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maxBlockSize](akashaproject_design_system._internal_.Properties.md#maxblocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2960

___

### maxHeight

• `Optional` **maxHeight**: [`MaxHeight`](../modules/akashaproject_design_system._internal_.md#maxheight)<`string` \| `number`\>

The **`max-height`** CSS property sets the maximum height of an element. It prevents the used value of the `height` property from becoming larger than the value specified for `max-height`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **18** |  **1**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-height

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maxHeight](akashaproject_design_system._internal_.Properties.md#maxheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2974

___

### maxInlineSize

• `Optional` **maxInlineSize**: [`MaxInlineSize`](../modules/akashaproject_design_system._internal_.md#maxinlinesize)<`string` \| `number`\>

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block, depending on its writing mode. It corresponds to either the `max-width` or the `max-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |   Safari   |  Edge  | IE  |
| :----: | :-----: | :--------: | :----: | :-: |
| **57** | **41**  |  **12.1**  | **79** | No  |
|        |         | 10.1 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-inline-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maxInlineSize](akashaproject_design_system._internal_.Properties.md#maxinlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2989

___

### maxLines

• `Optional` **maxLines**: [`MaxLines`](../modules/akashaproject_design_system._internal_.md#maxlines)

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maxLines](akashaproject_design_system._internal_.Properties.md#maxlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:2995

___

### maxWidth

• `Optional` **maxWidth**: [`MaxWidth`](../modules/akashaproject_design_system._internal_.md#maxwidth)<`string` \| `number`\>

The **`max-width`** CSS property sets the maximum width of an element. It prevents the used value of the `width` property from becoming larger than the value specified by `max-width`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[maxWidth](akashaproject_design_system._internal_.Properties.md#maxwidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3009

___

### minBlockSize

• `Optional` **minBlockSize**: [`MinBlockSize`](../modules/akashaproject_design_system._internal_.md#minblocksize)<`string` \| `number`\>

The **`min-block-size`** CSS property defines the minimum horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-block-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[minBlockSize](akashaproject_design_system._internal_.Properties.md#minblocksize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3023

___

### minHeight

• `Optional` **minHeight**: [`MinHeight`](../modules/akashaproject_design_system._internal_.md#minheight)<`string` \| `number`\>

The **`min-height`** CSS property sets the minimum height of an element. It prevents the used value of the `height` property from becoming smaller than the value specified for `min-height`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **3**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-height

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[minHeight](akashaproject_design_system._internal_.Properties.md#minheight)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3037

___

### minInlineSize

• `Optional` **minInlineSize**: [`MinInlineSize`](../modules/akashaproject_design_system._internal_.md#mininlinesize)<`string` \| `number`\>

The **`min-inline-size`** CSS property defines the horizontal or vertical minimal size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-inline-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[minInlineSize](akashaproject_design_system._internal_.Properties.md#mininlinesize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3051

___

### minWidth

• `Optional` **minWidth**: [`MinWidth`](../modules/akashaproject_design_system._internal_.md#minwidth)<`string` \| `number`\>

The **`min-width`** CSS property sets the minimum width of an element. It prevents the used value of the `width` property from becoming smaller than the value specified for `min-width`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[minWidth](akashaproject_design_system._internal_.Properties.md#minwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[mixBlendMode](akashaproject_design_system._internal_.Properties.md#mixblendmode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3079

___

### motion

• `Optional` **motion**: [`Offset`](../modules/akashaproject_design_system._internal_.md#offset)<`string` \| `number`\>

The **`offset`** CSS shorthand property sets all the properties required for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[motion](akashaproject_design_system._internal_.Properties.md#motion)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5605

___

### motionDistance

• `Optional` **motionDistance**: [`OffsetDistance`](../modules/akashaproject_design_system._internal_.md#offsetdistance)<`string` \| `number`\>

The **`offset-distance`** CSS property specifies a position along an `offset-path` for an element to be placed.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[motionDistance](akashaproject_design_system._internal_.Properties.md#motiondistance)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[motionPath](akashaproject_design_system._internal_.Properties.md#motionpath)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[motionRotation](akashaproject_design_system._internal_.Properties.md#motionrotation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3124

___

### msAccelerator

• `Optional` **msAccelerator**: [`MsAccelerator`](../modules/akashaproject_design_system._internal_.md#msaccelerator)

The **`-ms-accelerator`** CSS property is a Microsoft extension that sets or retrieves a string indicating whether the object represents a keyboard shortcut.

**Syntax**: `false | true`

**Initial value**: `false`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msAccelerator](akashaproject_design_system._internal_.Properties.md#msaccelerator)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6186

___

### msAlignSelf

• `Optional` **msAlignSelf**: [`AlignSelf`](../modules/akashaproject_design_system._internal_.md#alignself)

The **`align-self`** CSS property overrides a grid or flex item's `align-items` value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msAlignSelf](akashaproject_design_system._internal_.Properties.md#msalignself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6194

___

### msBlockProgression

• `Optional` **msBlockProgression**: [`MsBlockProgression`](../modules/akashaproject_design_system._internal_.md#msblockprogression)

The **`-ms-block-progression`** CSS property is a Microsoft extension that specifies the block progression and layout orientation.

**Syntax**: `tb | rl | bt | lr`

**Initial value**: `tb`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msBlockProgression](akashaproject_design_system._internal_.Properties.md#msblockprogression)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6202

___

### msContentZoomChaining

• `Optional` **msContentZoomChaining**: [`MsContentZoomChaining`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchaining)

The **`-ms-content-zoom-chaining`** CSS property is a Microsoft extension specifying the zoom behavior that occurs when a user hits the zoom limit during page manipulation.

**Syntax**: `none | chained`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomChaining](akashaproject_design_system._internal_.Properties.md#mscontentzoomchaining)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6210

___

### msContentZoomLimit

• `Optional` **msContentZoomLimit**: [`MsContentZoomLimit`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimit)

The **`-ms-content-zoom-limit`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-limit-min` and `-ms-content-zoom-limit-max` properties.

**Syntax**: `<'-ms-content-zoom-limit-min'> <'-ms-content-zoom-limit-max'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomLimit](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7569

___

### msContentZoomLimitMax

• `Optional` **msContentZoomLimitMax**: [`MsContentZoomLimitMax`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimitmax)

The **`-ms-content-zoom-limit-max`** CSS property is a Microsoft extension that specifies the selected elements' maximum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `400%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomLimitMax](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimitmax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6218

___

### msContentZoomLimitMin

• `Optional` **msContentZoomLimitMin**: [`MsContentZoomLimitMin`](../modules/akashaproject_design_system._internal_.md#mscontentzoomlimitmin)

The **`-ms-content-zoom-limit-min`** CSS property is a Microsoft extension that specifies the minimum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `100%`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomLimitMin](akashaproject_design_system._internal_.Properties.md#mscontentzoomlimitmin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6226

___

### msContentZoomSnap

• `Optional` **msContentZoomSnap**: [`MsContentZoomSnap`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnap)

The **`-ms-content-zoom-snap`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-snap-type` and `-ms-content-zoom-snap-points` properties.

**Syntax**: `<'-ms-content-zoom-snap-type'> || <'-ms-content-zoom-snap-points'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomSnap](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7575

___

### msContentZoomSnapPoints

• `Optional` **msContentZoomSnapPoints**: [`MsContentZoomSnapPoints`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnappoints)

The **`-ms-content-zoom-snap-points`** CSS property is a Microsoft extension that specifies where zoom snap-points are located.

**Syntax**: `snapInterval( <percentage>, <percentage> ) | snapList( <percentage># )`

**Initial value**: `snapInterval(0%, 100%)`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomSnapPoints](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnappoints)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6234

___

### msContentZoomSnapType

• `Optional` **msContentZoomSnapType**: [`MsContentZoomSnapType`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptype)

The **`-ms-content-zoom-snap-type`** CSS property is a Microsoft extension that specifies how zooming is affected by defined snap-points.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZoomSnapType](akashaproject_design_system._internal_.Properties.md#mscontentzoomsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6242

___

### msContentZooming

• `Optional` **msContentZooming**: [`MsContentZooming`](../modules/akashaproject_design_system._internal_.md#mscontentzooming)

The **`-ms-content-zooming`** CSS property is a Microsoft extension that specifies whether zooming is enabled.

**Syntax**: `none | zoom`

**Initial value**: zoom for the top level element, none for all other elements

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msContentZooming](akashaproject_design_system._internal_.Properties.md#mscontentzooming)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6250

___

### msFilter

• `Optional` **msFilter**: [`MsFilter`](../modules/akashaproject_design_system._internal_.md#msfilter)

The `-ms-filter` CSS property is a Microsoft extension that sets or retrieves the filter or collection of filters applied to an object.

**Syntax**: `<string>`

**Initial value**: "" (the empty string)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFilter](akashaproject_design_system._internal_.Properties.md#msfilter)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6258

___

### msFlex

• `Optional` **msFlex**: [`Flex`](../modules/akashaproject_design_system._internal_.md#flex)<`string` \| `number`\>

The **`flex`** CSS shorthand property sets how a flex _item_ will grow or shrink to fit the space available in its flex container.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFlex](akashaproject_design_system._internal_.Properties.md#msflex)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7581

___

### msFlexDirection

• `Optional` **msFlexDirection**: [`FlexDirection`](../modules/akashaproject_design_system._internal_.md#flexdirection)

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFlexDirection](akashaproject_design_system._internal_.Properties.md#msflexdirection)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6266

___

### msFlexPositive

• `Optional` **msFlexPositive**: [`FlexGrow`](../modules/akashaproject_design_system._internal_.md#flexgrow)

The **`flex-grow`** CSS property sets the flex grow factor of a flex item main size.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFlexPositive](akashaproject_design_system._internal_.Properties.md#msflexpositive)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6274

___

### msFlowFrom

• `Optional` **msFlowFrom**: [`MsFlowFrom`](../modules/akashaproject_design_system._internal_.md#msflowfrom)

The **`-ms-flow-from`** CSS property is a Microsoft extension that gets or sets a value identifying a region container in the document that accepts the content flow from the data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFlowFrom](akashaproject_design_system._internal_.Properties.md#msflowfrom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6282

___

### msFlowInto

• `Optional` **msFlowInto**: [`MsFlowInto`](../modules/akashaproject_design_system._internal_.md#msflowinto)

The **`-ms-flow-into`** CSS property is a Microsoft extension that gets or sets a value identifying an iframe container in the document that serves as the region's data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msFlowInto](akashaproject_design_system._internal_.Properties.md#msflowinto)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6290

___

### msGridColumns

• `Optional` **msGridColumns**: [`MsGridColumns`](../modules/akashaproject_design_system._internal_.md#msgridcolumns)<`string` \| `number`\>

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msGridColumns](akashaproject_design_system._internal_.Properties.md#msgridcolumns)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6298

___

### msGridRows

• `Optional` **msGridRows**: [`MsGridRows`](../modules/akashaproject_design_system._internal_.md#msgridrows)<`string` \| `number`\>

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msGridRows](akashaproject_design_system._internal_.Properties.md#msgridrows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6306

___

### msHighContrastAdjust

• `Optional` **msHighContrastAdjust**: [`MsHighContrastAdjust`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjust)

The **`-ms-high-contrast-adjust`** CSS property is a Microsoft extension that gets or sets a value indicating whether to override any CSS properties that would have been set in high contrast mode.

**Syntax**: `auto | none`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msHighContrastAdjust](akashaproject_design_system._internal_.Properties.md#mshighcontrastadjust)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6314

___

### msHyphenateLimitChars

• `Optional` **msHyphenateLimitChars**: [`MsHyphenateLimitChars`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitchars)

The **`-ms-hyphenate-limit-chars`** CSS property is a Microsoft extension that specifies one to three values indicating the minimum number of characters in a hyphenated word. If the word does not meet the required minimum number of characters in the word, before the hyphen, or after the hyphen, then the word is not hyphenated.

**Syntax**: `auto | <integer>{1,3}`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msHyphenateLimitChars](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitchars)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6322

___

### msHyphenateLimitLines

• `Optional` **msHyphenateLimitLines**: [`MsHyphenateLimitLines`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlines)

The **`-ms-hyphenate-limit-lines`** CSS property is a Microsoft extension specifying the maximum number of consecutive lines in an element that may be ended with a hyphenated word.

**Syntax**: `no-limit | <integer>`

**Initial value**: `no-limit`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msHyphenateLimitLines](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitlines)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6330

___

### msHyphenateLimitZone

• `Optional` **msHyphenateLimitZone**: [`MsHyphenateLimitZone`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzone)<`string` \| `number`\>

The `**-ms-hyphenate-limit-zone**` CSS property is a Microsoft extension specifying the width of the hyphenation zone.

**Syntax**: `<percentage> | <length>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msHyphenateLimitZone](akashaproject_design_system._internal_.Properties.md#mshyphenatelimitzone)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6338

___

### msHyphens

• `Optional` **msHyphens**: [`Hyphens`](../modules/akashaproject_design_system._internal_.md#hyphens)

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. It can prevent hyphenation entirely, hyphenate at manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msHyphens](akashaproject_design_system._internal_.Properties.md#mshyphens)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6346

___

### msImeAlign

• `Optional` **msImeAlign**: [`MsImeAlign`](../modules/akashaproject_design_system._internal_.md#msimealign)

The **`-ms-ime-align`** CSS property is a Microsoft extension aligning the Input Method Editor (IME) candidate window box relative to the element on which the IME composition is active. The extension is implemented in Microsoft Edge and Internet Explorer 11.

**Syntax**: `auto | after`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msImeAlign](akashaproject_design_system._internal_.Properties.md#msimealign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[msImeMode](akashaproject_design_system._internal_.Properties.md#msimemode)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8420

___

### msJustifySelf

• `Optional` **msJustifySelf**: [`JustifySelf`](../modules/akashaproject_design_system._internal_.md#justifyself)

The CSS **`justify-self`** property sets the way a box is justified inside its alignment container along the appropriate axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ]`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msJustifySelf](akashaproject_design_system._internal_.Properties.md#msjustifyself)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6362

___

### msLineBreak

• `Optional` **msLineBreak**: [`LineBreak`](../modules/akashaproject_design_system._internal_.md#linebreak)

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msLineBreak](akashaproject_design_system._internal_.Properties.md#mslinebreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6370

___

### msOrder

• `Optional` **msOrder**: [`Order`](../modules/akashaproject_design_system._internal_.md#order)

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msOrder](akashaproject_design_system._internal_.Properties.md#msorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6378

___

### msOverflowStyle

• `Optional` **msOverflowStyle**: [`MsOverflowStyle`](../modules/akashaproject_design_system._internal_.md#msoverflowstyle)

The **`-ms-overflow-style`** CSS property is a Microsoft extension controlling the behavior of scrollbars when the content of an element overflows.

**Syntax**: `auto | none | scrollbar | -ms-autohiding-scrollbar`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msOverflowStyle](akashaproject_design_system._internal_.Properties.md#msoverflowstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6386

___

### msOverflowX

• `Optional` **msOverflowX**: [`OverflowX`](../modules/akashaproject_design_system._internal_.md#overflowx)

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msOverflowX](akashaproject_design_system._internal_.Properties.md#msoverflowx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6394

___

### msOverflowY

• `Optional` **msOverflowY**: [`OverflowY`](../modules/akashaproject_design_system._internal_.md#overflowy)

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msOverflowY](akashaproject_design_system._internal_.Properties.md#msoverflowy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6402

___

### msScrollChaining

• `Optional` **msScrollChaining**: [`MsScrollChaining`](../modules/akashaproject_design_system._internal_.md#msscrollchaining)

The `**-ms-scroll-chaining**` CSS property is a Microsoft extension that specifies the scrolling behavior that occurs when a user hits the scroll limit during a manipulation.

**Syntax**: `chained | none`

**Initial value**: `chained`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollChaining](akashaproject_design_system._internal_.Properties.md#msscrollchaining)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6410

___

### msScrollLimit

• `Optional` **msScrollLimit**: [`MsScrollLimit`](../modules/akashaproject_design_system._internal_.md#msscrolllimit)

The **\-ms-scroll-limit** CSS property is a Microsoft extension that specifies values for the `-ms-scroll-limit-x-min`, `-ms-scroll-limit-y-min`, `-ms-scroll-limit-x-max`, and `-ms-scroll-limit-y-max` properties.

**Syntax**: `<'-ms-scroll-limit-x-min'> <'-ms-scroll-limit-y-min'> <'-ms-scroll-limit-x-max'> <'-ms-scroll-limit-y-max'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollLimit](akashaproject_design_system._internal_.Properties.md#msscrolllimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7587

___

### msScrollLimitXMax

• `Optional` **msScrollLimitXMax**: [`MsScrollLimitXMax`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmax)<`string` \| `number`\>

The `**-ms-scroll-limit-x-max**` CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollLeft` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollLimitXMax](akashaproject_design_system._internal_.Properties.md#msscrolllimitxmax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6418

___

### msScrollLimitXMin

• `Optional` **msScrollLimitXMin**: [`MsScrollLimitXMin`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmin)<`string` \| `number`\>

The **`-ms-scroll-limit-x-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollLeft` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollLimitXMin](akashaproject_design_system._internal_.Properties.md#msscrolllimitxmin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6426

___

### msScrollLimitYMax

• `Optional` **msScrollLimitYMax**: [`MsScrollLimitYMax`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymax)<`string` \| `number`\>

The **`-ms-scroll-limit-y-max`** CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollTop` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollLimitYMax](akashaproject_design_system._internal_.Properties.md#msscrolllimitymax)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6434

___

### msScrollLimitYMin

• `Optional` **msScrollLimitYMin**: [`MsScrollLimitYMin`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymin)<`string` \| `number`\>

The **`-ms-scroll-limit-y-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollTop` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollLimitYMin](akashaproject_design_system._internal_.Properties.md#msscrolllimitymin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6442

___

### msScrollRails

• `Optional` **msScrollRails**: [`MsScrollRails`](../modules/akashaproject_design_system._internal_.md#msscrollrails)

The **`-ms-scroll-rails`** CSS property is a Microsoft extension that specifies whether scrolling locks to the primary axis of motion.

**Syntax**: `none | railed`

**Initial value**: `railed`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollRails](akashaproject_design_system._internal_.Properties.md#msscrollrails)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6450

___

### msScrollSnapPointsX

• `Optional` **msScrollSnapPointsX**: [`MsScrollSnapPointsX`](../modules/akashaproject_design_system._internal_.md#msscrollsnappointsx)

The **`-ms-scroll-snap-points-x`** CSS property is a Microsoft extension that specifies where snap-points will be located along the x-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#msscrollsnappointsx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6458

___

### msScrollSnapPointsY

• `Optional` **msScrollSnapPointsY**: [`MsScrollSnapPointsY`](../modules/akashaproject_design_system._internal_.md#msscrollsnappointsy)

The **`-ms-scroll-snap-points-y`** CSS property is a Microsoft extension that specifies where snap-points will be located along the y-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#msscrollsnappointsy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6466

___

### msScrollSnapType

• `Optional` **msScrollSnapType**: [`MsScrollSnapType`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptype)

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollSnapType](akashaproject_design_system._internal_.Properties.md#msscrollsnaptype)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6474

___

### msScrollSnapX

• `Optional` **msScrollSnapX**: [`MsScrollSnapX`](../modules/akashaproject_design_system._internal_.md#msscrollsnapx)

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-x` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-x'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollSnapX](akashaproject_design_system._internal_.Properties.md#msscrollsnapx)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7593

___

### msScrollSnapY

• `Optional` **msScrollSnapY**: [`MsScrollSnapY`](../modules/akashaproject_design_system._internal_.md#msscrollsnapy)

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-y` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-y'>`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollSnapY](akashaproject_design_system._internal_.Properties.md#msscrollsnapy)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7599

___

### msScrollTranslation

• `Optional` **msScrollTranslation**: [`MsScrollTranslation`](../modules/akashaproject_design_system._internal_.md#msscrolltranslation)

The **`-ms-scroll-translation`** CSS property is a Microsoft extension that specifies whether vertical-to-horizontal scroll wheel translation occurs on the specified element.

**Syntax**: `none | vertical-to-horizontal`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollTranslation](akashaproject_design_system._internal_.Properties.md#msscrolltranslation)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6482

___

### msScrollbar3dlightColor

• `Optional` **msScrollbar3dlightColor**: [`MsScrollbar3dlightColor`](../modules/akashaproject_design_system._internal_.md#msscrollbar3dlightcolor)

The **`-ms-scrollbar-3dlight-color`** CSS property is a Microsoft extension specifying the color of the top and left edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbar3dlightColor](akashaproject_design_system._internal_.Properties.md#msscrollbar3dlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6490

___

### msScrollbarArrowColor

• `Optional` **msScrollbarArrowColor**: [`MsScrollbarArrowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbararrowcolor)

The **`-ms-scrollbar-arrow-color`** CSS property is a Microsoft extension that specifies the color of the arrow elements of a scroll arrow.

**Syntax**: `<color>`

**Initial value**: `ButtonText`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarArrowColor](akashaproject_design_system._internal_.Properties.md#msscrollbararrowcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6498

___

### msScrollbarBaseColor

• `Optional` **msScrollbarBaseColor**: [`MsScrollbarBaseColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarbasecolor)

The `**-ms-scrollbar-base-color**` CSS property is a Microsoft extension that specifies the base color of the main elements of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarBaseColor](akashaproject_design_system._internal_.Properties.md#msscrollbarbasecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6506

___

### msScrollbarDarkshadowColor

• `Optional` **msScrollbarDarkshadowColor**: [`MsScrollbarDarkshadowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbardarkshadowcolor)

The **`-ms-scrollbar-darkshadow-color`** CSS property is a Microsoft extension that specifies the color of a scroll bar's gutter.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarDarkshadowColor](akashaproject_design_system._internal_.Properties.md#msscrollbardarkshadowcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6514

___

### msScrollbarFaceColor

• `Optional` **msScrollbarFaceColor**: [`MsScrollbarFaceColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarfacecolor)

The `**-ms-scrollbar-face-color**` CSS property is a Microsoft extension that specifies the color of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDFace`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarFaceColor](akashaproject_design_system._internal_.Properties.md#msscrollbarfacecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6522

___

### msScrollbarHighlightColor

• `Optional` **msScrollbarHighlightColor**: [`MsScrollbarHighlightColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarhighlightcolor)

The `**-ms-scrollbar-highlight-color**` CSS property is a Microsoft extension that specifies the color of the slider tray, the top and left edges of the scroll box, and the scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDHighlight`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarHighlightColor](akashaproject_design_system._internal_.Properties.md#msscrollbarhighlightcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6530

___

### msScrollbarShadowColor

• `Optional` **msScrollbarShadowColor**: [`MsScrollbarShadowColor`](../modules/akashaproject_design_system._internal_.md#msscrollbarshadowcolor)

The **`-ms-scrollbar-shadow-color`** CSS property is a Microsoft extension that specifies the color of the bottom and right edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarShadowColor](akashaproject_design_system._internal_.Properties.md#msscrollbarshadowcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[msScrollbarTrackColor](akashaproject_design_system._internal_.Properties.md#msscrollbartrackcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8430

___

### msTextAutospace

• `Optional` **msTextAutospace**: [`MsTextAutospace`](../modules/akashaproject_design_system._internal_.md#mstextautospace)

The **`-ms-text-autospace`** CSS property is a Microsoft extension that specifies the autospacing and narrow space width adjustment of text.

**Syntax**: `none | ideograph-alpha | ideograph-numeric | ideograph-parenthesis | ideograph-space`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTextAutospace](akashaproject_design_system._internal_.Properties.md#mstextautospace)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6546

___

### msTextCombineHorizontal

• `Optional` **msTextCombineHorizontal**: [`TextCombineUpright`](../modules/akashaproject_design_system._internal_.md#textcombineupright)

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTextCombineHorizontal](akashaproject_design_system._internal_.Properties.md#mstextcombinehorizontal)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6554

___

### msTextOverflow

• `Optional` **msTextOverflow**: [`TextOverflow`](../modules/akashaproject_design_system._internal_.md#textoverflow)

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTextOverflow](akashaproject_design_system._internal_.Properties.md#mstextoverflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6562

___

### msTouchAction

• `Optional` **msTouchAction**: [`TouchAction`](../modules/akashaproject_design_system._internal_.md#touchaction)

The **`touch-action`** CSS property sets how an element's region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTouchAction](akashaproject_design_system._internal_.Properties.md#mstouchaction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6570

___

### msTouchSelect

• `Optional` **msTouchSelect**: [`MsTouchSelect`](../modules/akashaproject_design_system._internal_.md#mstouchselect)

The **`-ms-touch-select`** CSS property is a Microsoft extension that toggles the gripper visual elements that enable touch text selection.

**Syntax**: `grippers | none`

**Initial value**: `grippers`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTouchSelect](akashaproject_design_system._internal_.Properties.md#mstouchselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6578

___

### msTransform

• `Optional` **msTransform**: [`Transform`](../modules/akashaproject_design_system._internal_.md#transform)

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransform](akashaproject_design_system._internal_.Properties.md#mstransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6586

___

### msTransformOrigin

• `Optional` **msTransformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`string` \| `number`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransformOrigin](akashaproject_design_system._internal_.Properties.md#mstransformorigin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6594

___

### msTransition

• `Optional` **msTransition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`string` & {}\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransition](akashaproject_design_system._internal_.Properties.md#mstransition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7605

___

### msTransitionDelay

• `Optional` **msTransitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`string` & {}\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransitionDelay](akashaproject_design_system._internal_.Properties.md#mstransitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6602

___

### msTransitionDuration

• `Optional` **msTransitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`string` & {}\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransitionDuration](akashaproject_design_system._internal_.Properties.md#mstransitionduration)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6610

___

### msTransitionProperty

• `Optional` **msTransitionProperty**: [`TransitionProperty`](../modules/akashaproject_design_system._internal_.md#transitionproperty)

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransitionProperty](akashaproject_design_system._internal_.Properties.md#mstransitionproperty)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6618

___

### msTransitionTimingFunction

• `Optional` **msTransitionTimingFunction**: [`TransitionTimingFunction`](../modules/akashaproject_design_system._internal_.md#transitiontimingfunction)

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msTransitionTimingFunction](akashaproject_design_system._internal_.Properties.md#mstransitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6626

___

### msUserSelect

• `Optional` **msUserSelect**: [`MsUserSelect`](../modules/akashaproject_design_system._internal_.md#msuserselect)

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `none | element | text`

**Initial value**: `text`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msUserSelect](akashaproject_design_system._internal_.Properties.md#msuserselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6634

___

### msWordBreak

• `Optional` **msWordBreak**: [`WordBreak`](../modules/akashaproject_design_system._internal_.md#wordbreak)

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msWordBreak](akashaproject_design_system._internal_.Properties.md#mswordbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6642

___

### msWrapFlow

• `Optional` **msWrapFlow**: [`MsWrapFlow`](../modules/akashaproject_design_system._internal_.md#mswrapflow)

The **`-ms-wrap-flow`** CSS property is a Microsoft extension that specifies how exclusions impact inline content within block-level elements.

**Syntax**: `auto | both | start | end | maximum | clear`

**Initial value**: `auto`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msWrapFlow](akashaproject_design_system._internal_.Properties.md#mswrapflow)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6650

___

### msWrapMargin

• `Optional` **msWrapMargin**: [`MsWrapMargin`](../modules/akashaproject_design_system._internal_.md#mswrapmargin)<`string` \| `number`\>

The **`-ms-wrap-margin`** CSS property is a Microsoft extension that specifies a margin that offsets the inner wrap shape from other shapes.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msWrapMargin](akashaproject_design_system._internal_.Properties.md#mswrapmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6658

___

### msWrapThrough

• `Optional` **msWrapThrough**: [`MsWrapThrough`](../modules/akashaproject_design_system._internal_.md#mswrapthrough)

The **`-ms-wrap-through`** CSS property is a Microsoft extension that specifies how content should wrap around an exclusion element.

**Syntax**: `wrap | none`

**Initial value**: `wrap`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msWrapThrough](akashaproject_design_system._internal_.Properties.md#mswrapthrough)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:6666

___

### msWritingMode

• `Optional` **msWritingMode**: [`WritingMode`](../modules/akashaproject_design_system._internal_.md#writingmode)

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (`html` element for HTML documents).

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[msWritingMode](akashaproject_design_system._internal_.Properties.md#mswritingmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[objectFit](akashaproject_design_system._internal_.Properties.md#objectfit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3138

___

### objectPosition

• `Optional` **objectPosition**: [`ObjectPosition`](../modules/akashaproject_design_system._internal_.md#objectposition)<`string` \| `number`\>

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **32** | **36**  | **10** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/object-position

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[objectPosition](akashaproject_design_system._internal_.Properties.md#objectposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3152

___

### offset

• `Optional` **offset**: [`Offset`](../modules/akashaproject_design_system._internal_.md#offset)<`string` \| `number`\>

The **`offset`** CSS shorthand property sets all the properties required for animating an element along a defined path.

**Syntax**: `[ <'offset-position'>? [ <'offset-path'> [ <'offset-distance'> || <'offset-rotate'> ]? ]? ]! [ / <'offset-anchor'> ]?`

|    Chrome     | Firefox | Safari |  Edge  | IE  |
| :-----------: | :-----: | :----: | :----: | :-: |
|    **55**     | **72**  |   No   | **79** | No  |
| 46 _(motion)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offset](akashaproject_design_system._internal_.Properties.md#offset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5618

___

### offsetAnchor

• `Optional` **offsetAnchor**: [`OffsetAnchor`](../modules/akashaproject_design_system._internal_.md#offsetanchor)<`string` \| `number`\>

**Syntax**: `auto | <position>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **79** | **72**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-anchor

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetAnchor](akashaproject_design_system._internal_.Properties.md#offsetanchor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3164

___

### offsetBlock

• `Optional` **offsetBlock**: [`InsetBlock`](../modules/akashaproject_design_system._internal_.md#insetblock)<`string` \| `number`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetBlock](akashaproject_design_system._internal_.Properties.md#offsetblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7846

___

### offsetBlockEnd

• `Optional` **offsetBlockEnd**: [`InsetBlockEnd`](../modules/akashaproject_design_system._internal_.md#insetblockend)<`string` \| `number`\>

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetBlockEnd](akashaproject_design_system._internal_.Properties.md#offsetblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7856

___

### offsetBlockStart

• `Optional` **offsetBlockStart**: [`InsetBlockStart`](../modules/akashaproject_design_system._internal_.md#insetblockstart)<`string` \| `number`\>

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetBlockStart](akashaproject_design_system._internal_.Properties.md#offsetblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7866

___

### offsetDistance

• `Optional` **offsetDistance**: [`OffsetDistance`](../modules/akashaproject_design_system._internal_.md#offsetdistance)<`string` \| `number`\>

The **`offset-distance`** CSS property specifies a position along an `offset-path` for an element to be placed.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetDistance](akashaproject_design_system._internal_.Properties.md#offsetdistance)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3179

___

### offsetInline

• `Optional` **offsetInline**: [`InsetInline`](../modules/akashaproject_design_system._internal_.md#insetinline)<`string` \| `number`\>

The **`inset-inline`** CSS property defines the logical start and end offsets of an element in the inline direction, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetInline](akashaproject_design_system._internal_.Properties.md#offsetinline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7876

___

### offsetInlineEnd

• `Optional` **offsetInlineEnd**: [`InsetInlineEnd`](../modules/akashaproject_design_system._internal_.md#insetinlineend)<`string` \| `number`\>

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetInlineEnd](akashaproject_design_system._internal_.Properties.md#offsetinlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7886

___

### offsetInlineStart

• `Optional` **offsetInlineStart**: [`InsetInlineStart`](../modules/akashaproject_design_system._internal_.md#insetinlinestart)<`string` \| `number`\>

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetInlineStart](akashaproject_design_system._internal_.Properties.md#offsetinlinestart)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetPath](akashaproject_design_system._internal_.Properties.md#offsetpath)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetRotate](akashaproject_design_system._internal_.Properties.md#offsetrotate)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[offsetRotation](akashaproject_design_system._internal_.Properties.md#offsetrotation)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[opacity](akashaproject_design_system._internal_.Properties.md#opacity)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[order](akashaproject_design_system._internal_.Properties.md#order)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[orphans](akashaproject_design_system._internal_.Properties.md#orphans)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3267

___

### outline

• `Optional` **outline**: [`Outline`](../modules/akashaproject_design_system._internal_.md#outline)<`string` \| `number`\>

The **`outline`** CSS shorthand property set all the outline properties in a single declaration.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[outline](akashaproject_design_system._internal_.Properties.md#outline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[outlineColor](akashaproject_design_system._internal_.Properties.md#outlinecolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3281

___

### outlineOffset

• `Optional` **outlineOffset**: [`OutlineOffset`](../modules/akashaproject_design_system._internal_.md#outlineoffset)<`string` \| `number`\>

The **`outline-offset`** CSS property sets the amount of space between an outline and the edge or border of an element.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **1**  | **1.5** | **1.2** | **15** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-offset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[outlineOffset](akashaproject_design_system._internal_.Properties.md#outlineoffset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[outlineStyle](akashaproject_design_system._internal_.Properties.md#outlinestyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3309

___

### outlineWidth

• `Optional` **outlineWidth**: [`OutlineWidth`](../modules/akashaproject_design_system._internal_.md#outlinewidth)<`string` \| `number`\>

The CSS **`outline-width`** property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[outlineWidth](akashaproject_design_system._internal_.Properties.md#outlinewidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflow](akashaproject_design_system._internal_.Properties.md#overflow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowAnchor](akashaproject_design_system._internal_.Properties.md#overflowanchor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowBlock](akashaproject_design_system._internal_.Properties.md#overflowblock)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowClipBox](akashaproject_design_system._internal_.Properties.md#overflowclipbox)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3361

___

### overflowClipMargin

• `Optional` **overflowClipMargin**: [`OverflowClipMargin`](../modules/akashaproject_design_system._internal_.md#overflowclipmargin)<`string` \| `number`\>

**Syntax**: `<visual-box> || <length [0,∞]>`

**Initial value**: `0px`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **90** |   No    |   No   | **90** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-clip-margin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowClipMargin](akashaproject_design_system._internal_.Properties.md#overflowclipmargin)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowInline](akashaproject_design_system._internal_.Properties.md#overflowinline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowWrap](akashaproject_design_system._internal_.Properties.md#overflowwrap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowX](akashaproject_design_system._internal_.Properties.md#overflowx)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overflowY](akashaproject_design_system._internal_.Properties.md#overflowy)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overscrollBehavior](akashaproject_design_system._internal_.Properties.md#overscrollbehavior)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overscrollBehaviorBlock](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorblock)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overscrollBehaviorInline](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorinline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overscrollBehaviorX](akashaproject_design_system._internal_.Properties.md#overscrollbehaviorx)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[overscrollBehaviorY](akashaproject_design_system._internal_.Properties.md#overscrollbehaviory)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3484

___

### padding

• `Optional` **padding**: [`Padding`](../modules/akashaproject_design_system._internal_.md#padding)<`string` \| `number`\>

The **`padding`** CSS shorthand property sets the padding area on all four sides of an element at once.

**Syntax**: `[ <length> | <percentage> ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[padding](akashaproject_design_system._internal_.Properties.md#padding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5670

___

### paddingBlock

• `Optional` **paddingBlock**: [`PaddingBlock`](../modules/akashaproject_design_system._internal_.md#paddingblock)<`string` \| `number`\>

The **`padding-block`** CSS shorthand property defines the logical block start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingBlock](akashaproject_design_system._internal_.Properties.md#paddingblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3498

___

### paddingBlockEnd

• `Optional` **paddingBlockEnd**: [`PaddingBlockEnd`](../modules/akashaproject_design_system._internal_.md#paddingblockend)<`string` \| `number`\>

The **`padding-block-end`** CSS property defines the logical block end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingBlockEnd](akashaproject_design_system._internal_.Properties.md#paddingblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3512

___

### paddingBlockStart

• `Optional` **paddingBlockStart**: [`PaddingBlockStart`](../modules/akashaproject_design_system._internal_.md#paddingblockstart)<`string` \| `number`\>

The **`padding-block-start`** CSS property defines the logical block start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingBlockStart](akashaproject_design_system._internal_.Properties.md#paddingblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3526

___

### paddingBottom

• `Optional` **paddingBottom**: [`PaddingBottom`](../modules/akashaproject_design_system._internal_.md#paddingbottom)<`string` \| `number`\>

The **`padding-bottom`** CSS property sets the height of the padding area on the bottom of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingBottom](akashaproject_design_system._internal_.Properties.md#paddingbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3540

___

### paddingInline

• `Optional` **paddingInline**: [`PaddingInline`](../modules/akashaproject_design_system._internal_.md#paddinginline)<`string` \| `number`\>

The **`padding-inline`** CSS shorthand property defines the logical inline start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingInline](akashaproject_design_system._internal_.Properties.md#paddinginline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3554

___

### paddingInlineEnd

• `Optional` **paddingInlineEnd**: [`PaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#paddinginlineend)<`string` \| `number`\>

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|          Chrome           |        Firefox         |          Safari           |  Edge  | IE  |
| :-----------------------: | :--------------------: | :-----------------------: | :----: | :-: |
|          **69**           |         **41**         |         **12.1**          | **79** | No  |
| 2 _(-webkit-padding-end)_ | 3 _(-moz-padding-end)_ | 3 _(-webkit-padding-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingInlineEnd](akashaproject_design_system._internal_.Properties.md#paddinginlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3569

___

### paddingInlineStart

• `Optional` **paddingInlineStart**: [`PaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#paddinginlinestart)<`string` \| `number`\>

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|           Chrome            |         Firefox          |           Safari            |  Edge  | IE  |
| :-------------------------: | :----------------------: | :-------------------------: | :----: | :-: |
|           **69**            |          **41**          |          **12.1**           | **79** | No  |
| 2 _(-webkit-padding-start)_ | 3 _(-moz-padding-start)_ | 3 _(-webkit-padding-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingInlineStart](akashaproject_design_system._internal_.Properties.md#paddinginlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3584

___

### paddingLeft

• `Optional` **paddingLeft**: [`PaddingLeft`](../modules/akashaproject_design_system._internal_.md#paddingleft)<`string` \| `number`\>

The **`padding-left`** CSS property sets the width of the padding area to the left of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingLeft](akashaproject_design_system._internal_.Properties.md#paddingleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3598

___

### paddingRight

• `Optional` **paddingRight**: [`PaddingRight`](../modules/akashaproject_design_system._internal_.md#paddingright)<`string` \| `number`\>

The **`padding-right`** CSS property sets the width of the padding area on the right of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingRight](akashaproject_design_system._internal_.Properties.md#paddingright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3612

___

### paddingTop

• `Optional` **paddingTop**: [`PaddingTop`](../modules/akashaproject_design_system._internal_.md#paddingtop)<`string` \| `number`\>

The **`padding-top`** CSS property sets the height of the padding area on the top of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[paddingTop](akashaproject_design_system._internal_.Properties.md#paddingtop)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[pageBreakAfter](akashaproject_design_system._internal_.Properties.md#pagebreakafter)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[pageBreakBefore](akashaproject_design_system._internal_.Properties.md#pagebreakbefore)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[pageBreakInside](akashaproject_design_system._internal_.Properties.md#pagebreakinside)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[paintOrder](akashaproject_design_system._internal_.Properties.md#paintorder)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3682

___

### perspective

• `Optional` **perspective**: [`Perspective`](../modules/akashaproject_design_system._internal_.md#perspective)<`string` \| `number`\>

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective.

**Syntax**: `none | <length>`

**Initial value**: `none`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[perspective](akashaproject_design_system._internal_.Properties.md#perspective)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3697

___

### perspectiveOrigin

• `Optional` **perspectiveOrigin**: [`PerspectiveOrigin`](../modules/akashaproject_design_system._internal_.md#perspectiveorigin)<`string` \| `number`\>

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective-origin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[perspectiveOrigin](akashaproject_design_system._internal_.Properties.md#perspectiveorigin)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[placeContent](akashaproject_design_system._internal_.Properties.md#placecontent)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[placeItems](akashaproject_design_system._internal_.Properties.md#placeitems)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[placeSelf](akashaproject_design_system._internal_.Properties.md#placeself)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[pointerEvents](akashaproject_design_system._internal_.Properties.md#pointerevents)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[position](akashaproject_design_system._internal_.Properties.md#position)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[quotes](akashaproject_design_system._internal_.Properties.md#quotes)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[resize](akashaproject_design_system._internal_.Properties.md#resize)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3782

___

### right

• `Optional` **right**: [`Right`](../modules/akashaproject_design_system._internal_.md#right)<`string` \| `number`\>

The **`right`** CSS property participates in specifying the horizontal position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[right](akashaproject_design_system._internal_.Properties.md#right)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[rotate](akashaproject_design_system._internal_.Properties.md#rotate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3810

___

### rowGap

• `Optional` **rowGap**: [`RowGap`](../modules/akashaproject_design_system._internal_.md#rowgap)<`string` \| `number`\>

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

[Properties](akashaproject_design_system._internal_.Properties.md).[rowGap](akashaproject_design_system._internal_.Properties.md#rowgap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[rubyAlign](akashaproject_design_system._internal_.Properties.md#rubyalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3853

___

### rubyMerge

• `Optional` **rubyMerge**: [`RubyMerge`](../modules/akashaproject_design_system._internal_.md#rubymerge)

**Syntax**: `separate | collapse | auto`

**Initial value**: `separate`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[rubyMerge](akashaproject_design_system._internal_.Properties.md#rubymerge)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[rubyPosition](akashaproject_design_system._internal_.Properties.md#rubyposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scale](akashaproject_design_system._internal_.Properties.md#scale)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollBehavior](akashaproject_design_system._internal_.Properties.md#scrollbehavior)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3902

___

### scrollMargin

• `Optional` **scrollMargin**: [`ScrollMargin`](../modules/akashaproject_design_system._internal_.md#scrollmargin)<`string` \| `number`\>

The **`scroll-margin`** shorthand property sets all of the scroll margins of an element at once, assigning values much like the `margin` property does for margins of an element.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** | **90**  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMargin](akashaproject_design_system._internal_.Properties.md#scrollmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3917

___

### scrollMarginBlock

• `Optional` **scrollMarginBlock**: [`ScrollMarginBlock`](../modules/akashaproject_design_system._internal_.md#scrollmarginblock)<`string` \| `number`\>

The `scroll-margin-block` shorthand property sets the scroll margins of an element in the block dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginBlock](akashaproject_design_system._internal_.Properties.md#scrollmarginblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3931

___

### scrollMarginBlockEnd

• `Optional` **scrollMarginBlockEnd**: [`ScrollMarginBlockEnd`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockend)<`string` \| `number`\>

The `scroll-margin-block-end` property defines the margin of the scroll snap area at the end of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginBlockEnd](akashaproject_design_system._internal_.Properties.md#scrollmarginblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3945

___

### scrollMarginBlockStart

• `Optional` **scrollMarginBlockStart**: [`ScrollMarginBlockStart`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockstart)<`string` \| `number`\>

The `scroll-margin-block-start` property defines the margin of the scroll snap area at the start of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginBlockStart](akashaproject_design_system._internal_.Properties.md#scrollmarginblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3959

___

### scrollMarginBottom

• `Optional` **scrollMarginBottom**: [`ScrollMarginBottom`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottom)<`string` \| `number`\>

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginBottom](akashaproject_design_system._internal_.Properties.md#scrollmarginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3974

___

### scrollMarginInline

• `Optional` **scrollMarginInline**: [`ScrollMarginInline`](../modules/akashaproject_design_system._internal_.md#scrollmargininline)<`string` \| `number`\>

The `scroll-margin-inline` shorthand property sets the scroll margins of an element in the inline dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **68**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginInline](akashaproject_design_system._internal_.Properties.md#scrollmargininline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:3988

___

### scrollMarginInlineEnd

• `Optional` **scrollMarginInlineEnd**: [`ScrollMarginInlineEnd`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineend)<`string` \| `number`\>

The `scroll-margin-inline-end` property defines the margin of the scroll snap area at the end of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginInlineEnd](akashaproject_design_system._internal_.Properties.md#scrollmargininlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4002

___

### scrollMarginInlineStart

• `Optional` **scrollMarginInlineStart**: [`ScrollMarginInlineStart`](../modules/akashaproject_design_system._internal_.md#scrollmargininlinestart)<`string` \| `number`\>

The `scroll-margin-inline-start` property defines the margin of the scroll snap area at the start of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginInlineStart](akashaproject_design_system._internal_.Properties.md#scrollmargininlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4016

___

### scrollMarginLeft

• `Optional` **scrollMarginLeft**: [`ScrollMarginLeft`](../modules/akashaproject_design_system._internal_.md#scrollmarginleft)<`string` \| `number`\>

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginLeft](akashaproject_design_system._internal_.Properties.md#scrollmarginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4031

___

### scrollMarginRight

• `Optional` **scrollMarginRight**: [`ScrollMarginRight`](../modules/akashaproject_design_system._internal_.md#scrollmarginright)<`string` \| `number`\>

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginRight](akashaproject_design_system._internal_.Properties.md#scrollmarginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4046

___

### scrollMarginTop

• `Optional` **scrollMarginTop**: [`ScrollMarginTop`](../modules/akashaproject_design_system._internal_.md#scrollmargintop)<`string` \| `number`\>

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollMarginTop](akashaproject_design_system._internal_.Properties.md#scrollmargintop)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4061

___

### scrollPadding

• `Optional` **scrollPadding**: [`ScrollPadding`](../modules/akashaproject_design_system._internal_.md#scrollpadding)<`string` \| `number`\>

The **`scroll-padding`** shorthand property sets scroll padding on all sides of an element at once, much like the `padding` property does for padding on an element.

**Syntax**: `[ auto | <length-percentage> ]{1,4}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPadding](akashaproject_design_system._internal_.Properties.md#scrollpadding)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4075

___

### scrollPaddingBlock

• `Optional` **scrollPaddingBlock**: [`ScrollPaddingBlock`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblock)<`string` \| `number`\>

The `scroll-padding-block` shorthand property sets the scroll padding of an element in the block dimension.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingBlock](akashaproject_design_system._internal_.Properties.md#scrollpaddingblock)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4089

___

### scrollPaddingBlockEnd

• `Optional` **scrollPaddingBlockEnd**: [`ScrollPaddingBlockEnd`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockend)<`string` \| `number`\>

The `scroll-padding-block-end` property defines offsets for the end edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingBlockEnd](akashaproject_design_system._internal_.Properties.md#scrollpaddingblockend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4103

___

### scrollPaddingBlockStart

• `Optional` **scrollPaddingBlockStart**: [`ScrollPaddingBlockStart`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockstart)<`string` \| `number`\>

The `scroll-padding-block-start` property defines offsets for the start edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingBlockStart](akashaproject_design_system._internal_.Properties.md#scrollpaddingblockstart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4117

___

### scrollPaddingBottom

• `Optional` **scrollPaddingBottom**: [`ScrollPaddingBottom`](../modules/akashaproject_design_system._internal_.md#scrollpaddingbottom)<`string` \| `number`\>

The `scroll-padding-bottom` property defines offsets for the bottom of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingBottom](akashaproject_design_system._internal_.Properties.md#scrollpaddingbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4131

___

### scrollPaddingInline

• `Optional` **scrollPaddingInline**: [`ScrollPaddingInline`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginline)<`string` \| `number`\>

The `scroll-padding-inline` shorthand property sets the scroll padding of an element in the inline dimension.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingInline](akashaproject_design_system._internal_.Properties.md#scrollpaddinginline)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4145

___

### scrollPaddingInlineEnd

• `Optional` **scrollPaddingInlineEnd**: [`ScrollPaddingInlineEnd`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineend)<`string` \| `number`\>

The `scroll-padding-inline-end` property defines offsets for the end edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-end

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingInlineEnd](akashaproject_design_system._internal_.Properties.md#scrollpaddinginlineend)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4159

___

### scrollPaddingInlineStart

• `Optional` **scrollPaddingInlineStart**: [`ScrollPaddingInlineStart`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlinestart)<`string` \| `number`\>

The `scroll-padding-inline-start` property defines offsets for the start edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-start

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingInlineStart](akashaproject_design_system._internal_.Properties.md#scrollpaddinginlinestart)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4173

___

### scrollPaddingLeft

• `Optional` **scrollPaddingLeft**: [`ScrollPaddingLeft`](../modules/akashaproject_design_system._internal_.md#scrollpaddingleft)<`string` \| `number`\>

The `scroll-padding-left` property defines offsets for the left of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingLeft](akashaproject_design_system._internal_.Properties.md#scrollpaddingleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4187

___

### scrollPaddingRight

• `Optional` **scrollPaddingRight**: [`ScrollPaddingRight`](../modules/akashaproject_design_system._internal_.md#scrollpaddingright)<`string` \| `number`\>

The `scroll-padding-right` property defines offsets for the right of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingRight](akashaproject_design_system._internal_.Properties.md#scrollpaddingright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4201

___

### scrollPaddingTop

• `Optional` **scrollPaddingTop**: [`ScrollPaddingTop`](../modules/akashaproject_design_system._internal_.md#scrollpaddingtop)<`string` \| `number`\>

The **`scroll-padding-top`** property defines offsets for the top of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollPaddingTop](akashaproject_design_system._internal_.Properties.md#scrollpaddingtop)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapAlign](akashaproject_design_system._internal_.Properties.md#scrollsnapalign)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4229

___

### scrollSnapCoordinate

• `Optional` **scrollSnapCoordinate**: [`ScrollSnapCoordinate`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinate)<`string` \| `number`\>

The **`scroll-snap-coordinate`** CSS property defines the x and y coordinate positions within an element that will align with its nearest ancestor scroll container's `scroll-snap-destination` for each respective axis.

**Syntax**: `none | <position>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapCoordinate](akashaproject_design_system._internal_.Properties.md#scrollsnapcoordinate)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7906

___

### scrollSnapDestination

• `Optional` **scrollSnapDestination**: [`ScrollSnapDestination`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestination)<`string` \| `number`\>

The **`scroll-snap-destination`** CSS property defines the position in x and y coordinates within the scroll container's visual viewport which element snap points align with.

**Syntax**: `<position>`

**Initial value**: `0px 0px`

**`deprecated`**

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapDestination](akashaproject_design_system._internal_.Properties.md#scrollsnapdestination)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:7916

___

### scrollSnapMargin

• `Optional` **scrollSnapMargin**: [`ScrollMargin`](../modules/akashaproject_design_system._internal_.md#scrollmargin)<`string` \| `number`\>

The **`scroll-margin`** shorthand property sets all of the scroll margins of an element at once, assigning values much like the `margin` property does for margins of an element.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** |  68-90  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapMargin](akashaproject_design_system._internal_.Properties.md#scrollsnapmargin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4244

___

### scrollSnapMarginBottom

• `Optional` **scrollSnapMarginBottom**: [`ScrollMarginBottom`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottom)<`string` \| `number`\>

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapMarginBottom](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginbottom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4259

___

### scrollSnapMarginLeft

• `Optional` **scrollSnapMarginLeft**: [`ScrollMarginLeft`](../modules/akashaproject_design_system._internal_.md#scrollmarginleft)<`string` \| `number`\>

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapMarginLeft](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginleft)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4274

___

### scrollSnapMarginRight

• `Optional` **scrollSnapMarginRight**: [`ScrollMarginRight`](../modules/akashaproject_design_system._internal_.md#scrollmarginright)<`string` \| `number`\>

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapMarginRight](akashaproject_design_system._internal_.Properties.md#scrollsnapmarginright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4289

___

### scrollSnapMarginTop

• `Optional` **scrollSnapMarginTop**: [`ScrollMarginTop`](../modules/akashaproject_design_system._internal_.md#scrollmargintop)<`string` \| `number`\>

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapMarginTop](akashaproject_design_system._internal_.Properties.md#scrollsnapmargintop)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapPointsX](akashaproject_design_system._internal_.Properties.md#scrollsnappointsx)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapPointsY](akashaproject_design_system._internal_.Properties.md#scrollsnappointsy)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapStop](akashaproject_design_system._internal_.Properties.md#scrollsnapstop)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapType](akashaproject_design_system._internal_.Properties.md#scrollsnaptype)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapTypeX](akashaproject_design_system._internal_.Properties.md#scrollsnaptypex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollSnapTypeY](akashaproject_design_system._internal_.Properties.md#scrollsnaptypey)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollbarColor](akashaproject_design_system._internal_.Properties.md#scrollbarcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollbarGutter](akashaproject_design_system._internal_.Properties.md#scrollbargutter)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollbarTrackColor](akashaproject_design_system._internal_.Properties.md#scrollbartrackcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[scrollbarWidth](akashaproject_design_system._internal_.Properties.md#scrollbarwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[shapeImageThreshold](akashaproject_design_system._internal_.Properties.md#shapeimagethreshold)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4389

___

### shapeMargin

• `Optional` **shapeMargin**: [`ShapeMargin`](../modules/akashaproject_design_system._internal_.md#shapemargin)<`string` \| `number`\>

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-margin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[shapeMargin](akashaproject_design_system._internal_.Properties.md#shapemargin)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[shapeOutside](akashaproject_design_system._internal_.Properties.md#shapeoutside)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4417

___

### shapeRendering

• `Optional` **shapeRendering**: [`ShapeRendering`](../modules/akashaproject_design_system._internal_.md#shaperendering)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[shapeRendering](akashaproject_design_system._internal_.Properties.md#shaperendering)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8788

___

### stopColor

• `Optional` **stopColor**: [`StopColor`](../modules/akashaproject_design_system._internal_.md#stopcolor)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[stopColor](akashaproject_design_system._internal_.Properties.md#stopcolor)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8789

___

### stopOpacity

• `Optional` **stopOpacity**: [`StopOpacity`](../modules/akashaproject_design_system._internal_.md#stopopacity)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[stopOpacity](akashaproject_design_system._internal_.Properties.md#stopopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8790

___

### stroke

• `Optional` **stroke**: [`Stroke`](../modules/akashaproject_design_system._internal_.md#stroke)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[stroke](akashaproject_design_system._internal_.Properties.md#stroke)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8791

___

### strokeDasharray

• `Optional` **strokeDasharray**: [`StrokeDasharray`](../modules/akashaproject_design_system._internal_.md#strokedasharray)<`string` \| `number`\>

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeDasharray](akashaproject_design_system._internal_.Properties.md#strokedasharray)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8792

___

### strokeDashoffset

• `Optional` **strokeDashoffset**: [`StrokeDashoffset`](../modules/akashaproject_design_system._internal_.md#strokedashoffset)<`string` \| `number`\>

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeDashoffset](akashaproject_design_system._internal_.Properties.md#strokedashoffset)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8793

___

### strokeLinecap

• `Optional` **strokeLinecap**: [`StrokeLinecap`](../modules/akashaproject_design_system._internal_.md#strokelinecap)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeLinecap](akashaproject_design_system._internal_.Properties.md#strokelinecap)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8794

___

### strokeLinejoin

• `Optional` **strokeLinejoin**: [`StrokeLinejoin`](../modules/akashaproject_design_system._internal_.md#strokelinejoin)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeLinejoin](akashaproject_design_system._internal_.Properties.md#strokelinejoin)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8795

___

### strokeMiterlimit

• `Optional` **strokeMiterlimit**: [`StrokeMiterlimit`](../modules/akashaproject_design_system._internal_.md#strokemiterlimit)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeMiterlimit](akashaproject_design_system._internal_.Properties.md#strokemiterlimit)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8796

___

### strokeOpacity

• `Optional` **strokeOpacity**: [`StrokeOpacity`](../modules/akashaproject_design_system._internal_.md#strokeopacity)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeOpacity](akashaproject_design_system._internal_.Properties.md#strokeopacity)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8797

___

### strokeWidth

• `Optional` **strokeWidth**: [`StrokeWidth`](../modules/akashaproject_design_system._internal_.md#strokewidth)<`string` \| `number`\>

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[strokeWidth](akashaproject_design_system._internal_.Properties.md#strokewidth)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8798

___

### tabSize

• `Optional` **tabSize**: [`TabSize`](../modules/akashaproject_design_system._internal_.md#tabsize)<`string` \| `number`\>

The **`tab-size`** CSS property is used to customize the width of tab characters (U+0009).

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **21** | **91**  | **7**  | **79** | No  |
|        | 4 _-x-_ |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/tab-size

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[tabSize](akashaproject_design_system._internal_.Properties.md#tabsize)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[tableLayout](akashaproject_design_system._internal_.Properties.md#tablelayout)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textAlign](akashaproject_design_system._internal_.Properties.md#textalign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textAlignLast](akashaproject_design_system._internal_.Properties.md#textalignlast)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4474

___

### textAnchor

• `Optional` **textAnchor**: [`TextAnchor`](../modules/akashaproject_design_system._internal_.md#textanchor)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textAnchor](akashaproject_design_system._internal_.Properties.md#textanchor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textCombineUpright](akashaproject_design_system._internal_.Properties.md#textcombineupright)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4489

___

### textDecoration

• `Optional` **textDecoration**: [`TextDecoration`](../modules/akashaproject_design_system._internal_.md#textdecoration)<`string` \| `number`\>

The **`text-decoration`** shorthand CSS property sets the appearance of decorative lines on text. It is a shorthand for `text-decoration-line`, `text-decoration-color`, `text-decoration-style`, and the newer `text-decoration-thickness` property.

**Syntax**: `<'text-decoration-line'> || <'text-decoration-style'> || <'text-decoration-color'> || <'text-decoration-thickness'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecoration](akashaproject_design_system._internal_.Properties.md#textdecoration)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationColor](akashaproject_design_system._internal_.Properties.md#textdecorationcolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationLine](akashaproject_design_system._internal_.Properties.md#textdecorationline)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationSkip](akashaproject_design_system._internal_.Properties.md#textdecorationskip)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationSkipInk](akashaproject_design_system._internal_.Properties.md#textdecorationskipink)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationStyle](akashaproject_design_system._internal_.Properties.md#textdecorationstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4563

___

### textDecorationThickness

• `Optional` **textDecorationThickness**: [`TextDecorationThickness`](../modules/akashaproject_design_system._internal_.md#textdecorationthickness)<`string` \| `number`\>

The **`text-decoration-thickness`** CSS property sets the stroke thickness of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **89** | **70**  | **12.1** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationThickness](akashaproject_design_system._internal_.Properties.md#textdecorationthickness)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4577

___

### textDecorationWidth

• `Optional` **textDecorationWidth**: [`TextDecorationThickness`](../modules/akashaproject_design_system._internal_.md#textdecorationthickness)<`string` \| `number`\>

The **`text-decoration-thickness`** CSS property sets the stroke thickness of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  | Edge  | IE  |
| :----: | :-----: | :------: | :---: | :-: |
| 87-89  | **70**  | **12.1** | 87-89 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textDecorationWidth](akashaproject_design_system._internal_.Properties.md#textdecorationwidth)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textEmphasis](akashaproject_design_system._internal_.Properties.md#textemphasis)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textEmphasisColor](akashaproject_design_system._internal_.Properties.md#textemphasiscolor)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textEmphasisPosition](akashaproject_design_system._internal_.Properties.md#textemphasisposition)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textEmphasisStyle](akashaproject_design_system._internal_.Properties.md#textemphasisstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4633

___

### textIndent

• `Optional` **textIndent**: [`TextIndent`](../modules/akashaproject_design_system._internal_.md#textindent)<`string` \| `number`\>

The **`text-indent`** CSS property sets the length of empty space (indentation) that is put before lines of text in a block.

**Syntax**: `<length-percentage> && hanging? && each-line?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-indent

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textIndent](akashaproject_design_system._internal_.Properties.md#textindent)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textJustify](akashaproject_design_system._internal_.Properties.md#textjustify)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textOrientation](akashaproject_design_system._internal_.Properties.md#textorientation)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textOverflow](akashaproject_design_system._internal_.Properties.md#textoverflow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textRendering](akashaproject_design_system._internal_.Properties.md#textrendering)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textShadow](akashaproject_design_system._internal_.Properties.md#textshadow)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textSizeAdjust](akashaproject_design_system._internal_.Properties.md#textsizeadjust)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textTransform](akashaproject_design_system._internal_.Properties.md#texttransform)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4746

___

### textUnderlineOffset

• `Optional` **textUnderlineOffset**: [`TextUnderlineOffset`](../modules/akashaproject_design_system._internal_.md#textunderlineoffset)<`string` \| `number`\>

The **`text-underline-offset`** CSS property sets the offset distance of an underline text decoration line (applied using `text-decoration`) from its original position.

**Syntax**: `auto | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **70**  | **12.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-underline-offset

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[textUnderlineOffset](akashaproject_design_system._internal_.Properties.md#textunderlineoffset)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[textUnderlinePosition](akashaproject_design_system._internal_.Properties.md#textunderlineposition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4775

___

### top

• `Optional` **top**: [`Top`](../modules/akashaproject_design_system._internal_.md#top)<`string` \| `number`\>

The **`top`** CSS property participates in specifying the vertical position of a positioned element. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/top

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[top](akashaproject_design_system._internal_.Properties.md#top)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[touchAction](akashaproject_design_system._internal_.Properties.md#touchaction)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[transform](akashaproject_design_system._internal_.Properties.md#transform)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[transformBox](akashaproject_design_system._internal_.Properties.md#transformbox)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4833

___

### transformOrigin

• `Optional` **transformOrigin**: [`TransformOrigin`](../modules/akashaproject_design_system._internal_.md#transformorigin)<`string` \| `number`\>

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

| Chrome  |  Firefox  | Safari  |  Edge  |   IE    |
| :-----: | :-------: | :-----: | :----: | :-----: |
| **36**  |  **16**   |  **9**  | **12** | **10**  |
| 1 _-x-_ | 3.5 _-x-_ | 2 _-x-_ |        | 9 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-origin

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[transformOrigin](akashaproject_design_system._internal_.Properties.md#transformorigin)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[transformStyle](akashaproject_design_system._internal_.Properties.md#transformstyle)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4863

___

### transition

• `Optional` **transition**: [`Transition`](../modules/akashaproject_design_system._internal_.md#transition)<`string` & {}\>

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[transition](akashaproject_design_system._internal_.Properties.md#transition)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5731

___

### transitionDelay

• `Optional` **transitionDelay**: [`TransitionDelay`](../modules/akashaproject_design_system._internal_.md#transitiondelay)<`string` & {}\>

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **26**  | **16**  |  **9**  | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-delay

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[transitionDelay](akashaproject_design_system._internal_.Properties.md#transitiondelay)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4878

___

### transitionDuration

• `Optional` **transitionDuration**: [`TransitionDuration`](../modules/akashaproject_design_system._internal_.md#transitionduration)<`string` & {}\>

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-duration

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[transitionDuration](akashaproject_design_system._internal_.Properties.md#transitionduration)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[transitionProperty](akashaproject_design_system._internal_.Properties.md#transitionproperty)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[transitionTimingFunction](akashaproject_design_system._internal_.Properties.md#transitiontimingfunction)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4923

___

### translate

• `Optional` **translate**: [`Translate`](../modules/akashaproject_design_system._internal_.md#translate)<`string` \| `number`\>

The **`translate`** CSS property allows you to specify translation transforms individually and independently of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <length-percentage> [ <length-percentage> <length>? ]?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/translate

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[translate](akashaproject_design_system._internal_.Properties.md#translate)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[unicodeBidi](akashaproject_design_system._internal_.Properties.md#unicodebidi)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[userSelect](akashaproject_design_system._internal_.Properties.md#userselect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:4966

___

### vectorEffect

• `Optional` **vectorEffect**: [`VectorEffect`](../modules/akashaproject_design_system._internal_.md#vectoreffect)

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[vectorEffect](akashaproject_design_system._internal_.Properties.md#vectoreffect)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:8803

___

### verticalAlign

• `Optional` **verticalAlign**: [`VerticalAlign`](../modules/akashaproject_design_system._internal_.md#verticalalign)<`string` \| `number`\>

The **`vertical-align`** CSS property sets vertical alignment of an inline, inline-block or table-cell box.

**Syntax**: `baseline | sub | super | text-top | text-bottom | middle | top | bottom | <percentage> | <length>`

**Initial value**: `baseline`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/vertical-align

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[verticalAlign](akashaproject_design_system._internal_.Properties.md#verticalalign)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[visibility](akashaproject_design_system._internal_.Properties.md#visibility)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[whiteSpace](akashaproject_design_system._internal_.Properties.md#whitespace)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[widows](akashaproject_design_system._internal_.Properties.md#widows)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5022

___

### width

• `Optional` **width**: [`Width`](../modules/akashaproject_design_system._internal_.md#width)<`string` \| `number`\>

The **`width`** CSS property sets an element's width. By default, it sets the width of the content area, but if `box-sizing` is set to `border-box`, it sets the width of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/width

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[width](akashaproject_design_system._internal_.Properties.md#width)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[willChange](akashaproject_design_system._internal_.Properties.md#willchange)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[wordBreak](akashaproject_design_system._internal_.Properties.md#wordbreak)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5064

___

### wordSpacing

• `Optional` **wordSpacing**: [`WordSpacing`](../modules/akashaproject_design_system._internal_.md#wordspacing)<`string` \| `number`\>

The **`word-spacing`** CSS property sets the length of space between words and between tags.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/word-spacing

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[wordSpacing](akashaproject_design_system._internal_.Properties.md#wordspacing)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5078

___

### wordWrap

• `Optional` **wordWrap**: [`WordWrap`](../modules/akashaproject_design_system._internal_.md#wordwrap)

The `**overflow-wrap**` CSS property applies to inline elements, setting whether the browser should insert line breaks within an otherwise unbreakable string to prevent text from overflowing its line box.

**Syntax**: `normal | break-word`

**Initial value**: `normal`

#### Inherited from

[Properties](akashaproject_design_system._internal_.Properties.md).[wordWrap](akashaproject_design_system._internal_.Properties.md#wordwrap)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[writingMode](akashaproject_design_system._internal_.Properties.md#writingmode)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[zIndex](akashaproject_design_system._internal_.Properties.md#zindex)

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

[Properties](akashaproject_design_system._internal_.Properties.md).[zoom](akashaproject_design_system._internal_.Properties.md#zoom)

#### Defined in

ui/design/node_modules/@types/react/node_modules/csstype/index.d.ts:5129
