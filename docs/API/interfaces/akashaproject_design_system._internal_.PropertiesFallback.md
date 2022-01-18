[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / PropertiesFallback

# Interface: PropertiesFallback<TLength\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).PropertiesFallback

## Type parameters

| Name | Type |
| :------ | :------ |
| `TLength` | `string` \| ``0`` |

## Hierarchy

- [`StandardPropertiesFallback`](akashaproject_design_system._internal_.StandardPropertiesFallback.md)<`TLength`\>

- [`VendorPropertiesFallback`](akashaproject_design_system._internal_.VendorPropertiesFallback.md)<`TLength`\>

- [`ObsoletePropertiesFallback`](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md)<`TLength`\>

- [`SvgPropertiesFallback`](akashaproject_design_system._internal_.SvgPropertiesFallback.md)<`TLength`\>

  ↳ **`PropertiesFallback`**

## Table of contents

### Properties

- [KhtmlBoxAlign](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxalign)
- [KhtmlBoxDirection](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxdirection)
- [KhtmlBoxFlex](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxflex)
- [KhtmlBoxFlexGroup](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxflexgroup)
- [KhtmlBoxLines](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxlines)
- [KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxordinalgroup)
- [KhtmlBoxOrient](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxorient)
- [KhtmlBoxPack](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlboxpack)
- [KhtmlLineBreak](akashaproject_design_system._internal_.PropertiesFallback.md#khtmllinebreak)
- [KhtmlOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#khtmlopacity)
- [KhtmlUserSelect](akashaproject_design_system._internal_.PropertiesFallback.md#khtmluserselect)
- [MozAnimation](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimation)
- [MozAnimationDelay](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationdelay)
- [MozAnimationDirection](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationdirection)
- [MozAnimationDuration](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationduration)
- [MozAnimationFillMode](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationfillmode)
- [MozAnimationIterationCount](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationiterationcount)
- [MozAnimationName](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationname)
- [MozAnimationPlayState](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationplaystate)
- [MozAnimationTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#mozanimationtimingfunction)
- [MozAppearance](akashaproject_design_system._internal_.PropertiesFallback.md#mozappearance)
- [MozBackfaceVisibility](akashaproject_design_system._internal_.PropertiesFallback.md#mozbackfacevisibility)
- [MozBackgroundClip](akashaproject_design_system._internal_.PropertiesFallback.md#mozbackgroundclip)
- [MozBackgroundInlinePolicy](akashaproject_design_system._internal_.PropertiesFallback.md#mozbackgroundinlinepolicy)
- [MozBackgroundOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#mozbackgroundorigin)
- [MozBackgroundSize](akashaproject_design_system._internal_.PropertiesFallback.md#mozbackgroundsize)
- [MozBinding](akashaproject_design_system._internal_.PropertiesFallback.md#mozbinding)
- [MozBorderBottomColors](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderbottomcolors)
- [MozBorderEndColor](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderendcolor)
- [MozBorderEndStyle](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderendstyle)
- [MozBorderEndWidth](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderendwidth)
- [MozBorderImage](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderimage)
- [MozBorderLeftColors](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderleftcolors)
- [MozBorderRadius](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderradius)
- [MozBorderRadiusBottomleft](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderradiusbottomleft)
- [MozBorderRadiusBottomright](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderradiusbottomright)
- [MozBorderRadiusTopleft](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderradiustopleft)
- [MozBorderRadiusTopright](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderradiustopright)
- [MozBorderRightColors](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderrightcolors)
- [MozBorderStartColor](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderstartcolor)
- [MozBorderStartStyle](akashaproject_design_system._internal_.PropertiesFallback.md#mozborderstartstyle)
- [MozBorderTopColors](akashaproject_design_system._internal_.PropertiesFallback.md#mozbordertopcolors)
- [MozBoxAlign](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxalign)
- [MozBoxDirection](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxdirection)
- [MozBoxFlex](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxflex)
- [MozBoxOrdinalGroup](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxordinalgroup)
- [MozBoxOrient](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxorient)
- [MozBoxPack](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxpack)
- [MozBoxShadow](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxshadow)
- [MozBoxSizing](akashaproject_design_system._internal_.PropertiesFallback.md#mozboxsizing)
- [MozColumnCount](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumncount)
- [MozColumnFill](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnfill)
- [MozColumnGap](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumngap)
- [MozColumnRule](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnrule)
- [MozColumnRuleColor](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnrulecolor)
- [MozColumnRuleStyle](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnrulestyle)
- [MozColumnRuleWidth](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnrulewidth)
- [MozColumnWidth](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumnwidth)
- [MozColumns](akashaproject_design_system._internal_.PropertiesFallback.md#mozcolumns)
- [MozContextProperties](akashaproject_design_system._internal_.PropertiesFallback.md#mozcontextproperties)
- [MozFloatEdge](akashaproject_design_system._internal_.PropertiesFallback.md#mozfloatedge)
- [MozFontFeatureSettings](akashaproject_design_system._internal_.PropertiesFallback.md#mozfontfeaturesettings)
- [MozFontLanguageOverride](akashaproject_design_system._internal_.PropertiesFallback.md#mozfontlanguageoverride)
- [MozForceBrokenImageIcon](akashaproject_design_system._internal_.PropertiesFallback.md#mozforcebrokenimageicon)
- [MozHyphens](akashaproject_design_system._internal_.PropertiesFallback.md#mozhyphens)
- [MozImageRegion](akashaproject_design_system._internal_.PropertiesFallback.md#mozimageregion)
- [MozMarginEnd](akashaproject_design_system._internal_.PropertiesFallback.md#mozmarginend)
- [MozMarginStart](akashaproject_design_system._internal_.PropertiesFallback.md#mozmarginstart)
- [MozOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#mozopacity)
- [MozOrient](akashaproject_design_system._internal_.PropertiesFallback.md#mozorient)
- [MozOsxFontSmoothing](akashaproject_design_system._internal_.PropertiesFallback.md#mozosxfontsmoothing)
- [MozOutline](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutline)
- [MozOutlineColor](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlinecolor)
- [MozOutlineRadius](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlineradius)
- [MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlineradiusbottomleft)
- [MozOutlineRadiusBottomright](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlineradiusbottomright)
- [MozOutlineRadiusTopleft](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlineradiustopleft)
- [MozOutlineRadiusTopright](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlineradiustopright)
- [MozOutlineStyle](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlinestyle)
- [MozOutlineWidth](akashaproject_design_system._internal_.PropertiesFallback.md#mozoutlinewidth)
- [MozPaddingEnd](akashaproject_design_system._internal_.PropertiesFallback.md#mozpaddingend)
- [MozPaddingStart](akashaproject_design_system._internal_.PropertiesFallback.md#mozpaddingstart)
- [MozPerspective](akashaproject_design_system._internal_.PropertiesFallback.md#mozperspective)
- [MozPerspectiveOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#mozperspectiveorigin)
- [MozStackSizing](akashaproject_design_system._internal_.PropertiesFallback.md#mozstacksizing)
- [MozTabSize](akashaproject_design_system._internal_.PropertiesFallback.md#moztabsize)
- [MozTextAlignLast](akashaproject_design_system._internal_.PropertiesFallback.md#moztextalignlast)
- [MozTextBlink](akashaproject_design_system._internal_.PropertiesFallback.md#moztextblink)
- [MozTextDecorationColor](akashaproject_design_system._internal_.PropertiesFallback.md#moztextdecorationcolor)
- [MozTextDecorationLine](akashaproject_design_system._internal_.PropertiesFallback.md#moztextdecorationline)
- [MozTextDecorationStyle](akashaproject_design_system._internal_.PropertiesFallback.md#moztextdecorationstyle)
- [MozTextSizeAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#moztextsizeadjust)
- [MozTransformOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#moztransformorigin)
- [MozTransformStyle](akashaproject_design_system._internal_.PropertiesFallback.md#moztransformstyle)
- [MozTransition](akashaproject_design_system._internal_.PropertiesFallback.md#moztransition)
- [MozTransitionDelay](akashaproject_design_system._internal_.PropertiesFallback.md#moztransitiondelay)
- [MozTransitionDuration](akashaproject_design_system._internal_.PropertiesFallback.md#moztransitionduration)
- [MozTransitionProperty](akashaproject_design_system._internal_.PropertiesFallback.md#moztransitionproperty)
- [MozTransitionTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#moztransitiontimingfunction)
- [MozUserFocus](akashaproject_design_system._internal_.PropertiesFallback.md#mozuserfocus)
- [MozUserInput](akashaproject_design_system._internal_.PropertiesFallback.md#mozuserinput)
- [MozUserModify](akashaproject_design_system._internal_.PropertiesFallback.md#mozusermodify)
- [MozUserSelect](akashaproject_design_system._internal_.PropertiesFallback.md#mozuserselect)
- [MozWindowDragging](akashaproject_design_system._internal_.PropertiesFallback.md#mozwindowdragging)
- [MozWindowShadow](akashaproject_design_system._internal_.PropertiesFallback.md#mozwindowshadow)
- [OAnimation](akashaproject_design_system._internal_.PropertiesFallback.md#oanimation)
- [OAnimationDelay](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationdelay)
- [OAnimationDirection](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationdirection)
- [OAnimationDuration](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationduration)
- [OAnimationFillMode](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationfillmode)
- [OAnimationIterationCount](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationiterationcount)
- [OAnimationName](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationname)
- [OAnimationPlayState](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationplaystate)
- [OAnimationTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#oanimationtimingfunction)
- [OBackgroundSize](akashaproject_design_system._internal_.PropertiesFallback.md#obackgroundsize)
- [OBorderImage](akashaproject_design_system._internal_.PropertiesFallback.md#oborderimage)
- [OObjectFit](akashaproject_design_system._internal_.PropertiesFallback.md#oobjectfit)
- [OObjectPosition](akashaproject_design_system._internal_.PropertiesFallback.md#oobjectposition)
- [OTabSize](akashaproject_design_system._internal_.PropertiesFallback.md#otabsize)
- [OTextOverflow](akashaproject_design_system._internal_.PropertiesFallback.md#otextoverflow)
- [OTransform](akashaproject_design_system._internal_.PropertiesFallback.md#otransform)
- [OTransformOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#otransformorigin)
- [OTransition](akashaproject_design_system._internal_.PropertiesFallback.md#otransition)
- [OTransitionDelay](akashaproject_design_system._internal_.PropertiesFallback.md#otransitiondelay)
- [OTransitionDuration](akashaproject_design_system._internal_.PropertiesFallback.md#otransitionduration)
- [OTransitionProperty](akashaproject_design_system._internal_.PropertiesFallback.md#otransitionproperty)
- [OTransitionTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#otransitiontimingfunction)
- [WebkitAlignContent](akashaproject_design_system._internal_.PropertiesFallback.md#webkitaligncontent)
- [WebkitAlignItems](akashaproject_design_system._internal_.PropertiesFallback.md#webkitalignitems)
- [WebkitAlignSelf](akashaproject_design_system._internal_.PropertiesFallback.md#webkitalignself)
- [WebkitAnimation](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimation)
- [WebkitAnimationDelay](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationdelay)
- [WebkitAnimationDirection](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationdirection)
- [WebkitAnimationDuration](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationduration)
- [WebkitAnimationFillMode](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationfillmode)
- [WebkitAnimationIterationCount](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationiterationcount)
- [WebkitAnimationName](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationname)
- [WebkitAnimationPlayState](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationplaystate)
- [WebkitAnimationTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#webkitanimationtimingfunction)
- [WebkitAppearance](akashaproject_design_system._internal_.PropertiesFallback.md#webkitappearance)
- [WebkitBackdropFilter](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbackdropfilter)
- [WebkitBackfaceVisibility](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbackfacevisibility)
- [WebkitBackgroundClip](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbackgroundclip)
- [WebkitBackgroundOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbackgroundorigin)
- [WebkitBackgroundSize](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbackgroundsize)
- [WebkitBorderBefore](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbefore)
- [WebkitBorderBeforeColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbeforecolor)
- [WebkitBorderBeforeStyle](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbeforestyle)
- [WebkitBorderBeforeWidth](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbeforewidth)
- [WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbottomleftradius)
- [WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderbottomrightradius)
- [WebkitBorderImage](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderimage)
- [WebkitBorderImageSlice](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderimageslice)
- [WebkitBorderRadius](akashaproject_design_system._internal_.PropertiesFallback.md#webkitborderradius)
- [WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbordertopleftradius)
- [WebkitBorderTopRightRadius](akashaproject_design_system._internal_.PropertiesFallback.md#webkitbordertoprightradius)
- [WebkitBoxAlign](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxalign)
- [WebkitBoxDecorationBreak](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxdecorationbreak)
- [WebkitBoxDirection](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxdirection)
- [WebkitBoxFlex](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxflex)
- [WebkitBoxFlexGroup](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxflexgroup)
- [WebkitBoxLines](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxlines)
- [WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxordinalgroup)
- [WebkitBoxOrient](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxorient)
- [WebkitBoxPack](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxpack)
- [WebkitBoxReflect](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxreflect)
- [WebkitBoxShadow](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxshadow)
- [WebkitBoxSizing](akashaproject_design_system._internal_.PropertiesFallback.md#webkitboxsizing)
- [WebkitClipPath](akashaproject_design_system._internal_.PropertiesFallback.md#webkitclippath)
- [WebkitColumnCount](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumncount)
- [WebkitColumnFill](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnfill)
- [WebkitColumnGap](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumngap)
- [WebkitColumnRule](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnrule)
- [WebkitColumnRuleColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnrulecolor)
- [WebkitColumnRuleStyle](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnrulestyle)
- [WebkitColumnRuleWidth](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnrulewidth)
- [WebkitColumnSpan](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnspan)
- [WebkitColumnWidth](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumnwidth)
- [WebkitColumns](akashaproject_design_system._internal_.PropertiesFallback.md#webkitcolumns)
- [WebkitFilter](akashaproject_design_system._internal_.PropertiesFallback.md#webkitfilter)
- [WebkitFlex](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflex)
- [WebkitFlexBasis](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexbasis)
- [WebkitFlexDirection](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexdirection)
- [WebkitFlexFlow](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexflow)
- [WebkitFlexGrow](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexgrow)
- [WebkitFlexShrink](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexshrink)
- [WebkitFlexWrap](akashaproject_design_system._internal_.PropertiesFallback.md#webkitflexwrap)
- [WebkitFontFeatureSettings](akashaproject_design_system._internal_.PropertiesFallback.md#webkitfontfeaturesettings)
- [WebkitFontKerning](akashaproject_design_system._internal_.PropertiesFallback.md#webkitfontkerning)
- [WebkitFontSmoothing](akashaproject_design_system._internal_.PropertiesFallback.md#webkitfontsmoothing)
- [WebkitFontVariantLigatures](akashaproject_design_system._internal_.PropertiesFallback.md#webkitfontvariantligatures)
- [WebkitHyphens](akashaproject_design_system._internal_.PropertiesFallback.md#webkithyphens)
- [WebkitJustifyContent](akashaproject_design_system._internal_.PropertiesFallback.md#webkitjustifycontent)
- [WebkitLineBreak](akashaproject_design_system._internal_.PropertiesFallback.md#webkitlinebreak)
- [WebkitLineClamp](akashaproject_design_system._internal_.PropertiesFallback.md#webkitlineclamp)
- [WebkitMarginEnd](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmarginend)
- [WebkitMarginStart](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmarginstart)
- [WebkitMask](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmask)
- [WebkitMaskAttachment](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskattachment)
- [WebkitMaskBoxImage](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximage)
- [WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximageoutset)
- [WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximagerepeat)
- [WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximageslice)
- [WebkitMaskBoxImageSource](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximagesource)
- [WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskboximagewidth)
- [WebkitMaskClip](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskclip)
- [WebkitMaskComposite](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskcomposite)
- [WebkitMaskImage](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskimage)
- [WebkitMaskOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskorigin)
- [WebkitMaskPosition](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskposition)
- [WebkitMaskPositionX](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskpositionx)
- [WebkitMaskPositionY](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskpositiony)
- [WebkitMaskRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskrepeat)
- [WebkitMaskRepeatX](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskrepeatx)
- [WebkitMaskRepeatY](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaskrepeaty)
- [WebkitMaskSize](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmasksize)
- [WebkitMaxInlineSize](akashaproject_design_system._internal_.PropertiesFallback.md#webkitmaxinlinesize)
- [WebkitOrder](akashaproject_design_system._internal_.PropertiesFallback.md#webkitorder)
- [WebkitOverflowScrolling](akashaproject_design_system._internal_.PropertiesFallback.md#webkitoverflowscrolling)
- [WebkitPaddingEnd](akashaproject_design_system._internal_.PropertiesFallback.md#webkitpaddingend)
- [WebkitPaddingStart](akashaproject_design_system._internal_.PropertiesFallback.md#webkitpaddingstart)
- [WebkitPerspective](akashaproject_design_system._internal_.PropertiesFallback.md#webkitperspective)
- [WebkitPerspectiveOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#webkitperspectiveorigin)
- [WebkitPrintColorAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#webkitprintcoloradjust)
- [WebkitRubyPosition](akashaproject_design_system._internal_.PropertiesFallback.md#webkitrubyposition)
- [WebkitScrollSnapPointsX](akashaproject_design_system._internal_.PropertiesFallback.md#webkitscrollsnappointsx)
- [WebkitScrollSnapPointsY](akashaproject_design_system._internal_.PropertiesFallback.md#webkitscrollsnappointsy)
- [WebkitScrollSnapType](akashaproject_design_system._internal_.PropertiesFallback.md#webkitscrollsnaptype)
- [WebkitShapeMargin](akashaproject_design_system._internal_.PropertiesFallback.md#webkitshapemargin)
- [WebkitTapHighlightColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkittaphighlightcolor)
- [WebkitTextCombine](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextcombine)
- [WebkitTextDecorationColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextdecorationcolor)
- [WebkitTextDecorationLine](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextdecorationline)
- [WebkitTextDecorationSkip](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextdecorationskip)
- [WebkitTextDecorationStyle](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextdecorationstyle)
- [WebkitTextEmphasis](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextemphasis)
- [WebkitTextEmphasisColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextemphasiscolor)
- [WebkitTextEmphasisPosition](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextemphasisposition)
- [WebkitTextEmphasisStyle](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextemphasisstyle)
- [WebkitTextFillColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextfillcolor)
- [WebkitTextOrientation](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextorientation)
- [WebkitTextSizeAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextsizeadjust)
- [WebkitTextStroke](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextstroke)
- [WebkitTextStrokeColor](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextstrokecolor)
- [WebkitTextStrokeWidth](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextstrokewidth)
- [WebkitTextUnderlinePosition](akashaproject_design_system._internal_.PropertiesFallback.md#webkittextunderlineposition)
- [WebkitTouchCallout](akashaproject_design_system._internal_.PropertiesFallback.md#webkittouchcallout)
- [WebkitTransform](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransform)
- [WebkitTransformOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransformorigin)
- [WebkitTransformStyle](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransformstyle)
- [WebkitTransition](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransition)
- [WebkitTransitionDelay](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransitiondelay)
- [WebkitTransitionDuration](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransitionduration)
- [WebkitTransitionProperty](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransitionproperty)
- [WebkitTransitionTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#webkittransitiontimingfunction)
- [WebkitUserModify](akashaproject_design_system._internal_.PropertiesFallback.md#webkitusermodify)
- [WebkitUserSelect](akashaproject_design_system._internal_.PropertiesFallback.md#webkituserselect)
- [WebkitWritingMode](akashaproject_design_system._internal_.PropertiesFallback.md#webkitwritingmode)
- [accentColor](akashaproject_design_system._internal_.PropertiesFallback.md#accentcolor)
- [alignContent](akashaproject_design_system._internal_.PropertiesFallback.md#aligncontent)
- [alignItems](akashaproject_design_system._internal_.PropertiesFallback.md#alignitems)
- [alignSelf](akashaproject_design_system._internal_.PropertiesFallback.md#alignself)
- [alignTracks](akashaproject_design_system._internal_.PropertiesFallback.md#aligntracks)
- [alignmentBaseline](akashaproject_design_system._internal_.PropertiesFallback.md#alignmentbaseline)
- [all](akashaproject_design_system._internal_.PropertiesFallback.md#all)
- [animation](akashaproject_design_system._internal_.PropertiesFallback.md#animation)
- [animationDelay](akashaproject_design_system._internal_.PropertiesFallback.md#animationdelay)
- [animationDirection](akashaproject_design_system._internal_.PropertiesFallback.md#animationdirection)
- [animationDuration](akashaproject_design_system._internal_.PropertiesFallback.md#animationduration)
- [animationFillMode](akashaproject_design_system._internal_.PropertiesFallback.md#animationfillmode)
- [animationIterationCount](akashaproject_design_system._internal_.PropertiesFallback.md#animationiterationcount)
- [animationName](akashaproject_design_system._internal_.PropertiesFallback.md#animationname)
- [animationPlayState](akashaproject_design_system._internal_.PropertiesFallback.md#animationplaystate)
- [animationTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#animationtimingfunction)
- [appearance](akashaproject_design_system._internal_.PropertiesFallback.md#appearance)
- [aspectRatio](akashaproject_design_system._internal_.PropertiesFallback.md#aspectratio)
- [azimuth](akashaproject_design_system._internal_.PropertiesFallback.md#azimuth)
- [backdropFilter](akashaproject_design_system._internal_.PropertiesFallback.md#backdropfilter)
- [backfaceVisibility](akashaproject_design_system._internal_.PropertiesFallback.md#backfacevisibility)
- [background](akashaproject_design_system._internal_.PropertiesFallback.md#background)
- [backgroundAttachment](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundattachment)
- [backgroundBlendMode](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundblendmode)
- [backgroundClip](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundclip)
- [backgroundColor](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundcolor)
- [backgroundImage](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundimage)
- [backgroundOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundorigin)
- [backgroundPosition](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundposition)
- [backgroundPositionX](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundpositionx)
- [backgroundPositionY](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundpositiony)
- [backgroundRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundrepeat)
- [backgroundSize](akashaproject_design_system._internal_.PropertiesFallback.md#backgroundsize)
- [baselineShift](akashaproject_design_system._internal_.PropertiesFallback.md#baselineshift)
- [blockOverflow](akashaproject_design_system._internal_.PropertiesFallback.md#blockoverflow)
- [blockSize](akashaproject_design_system._internal_.PropertiesFallback.md#blocksize)
- [border](akashaproject_design_system._internal_.PropertiesFallback.md#border)
- [borderBlock](akashaproject_design_system._internal_.PropertiesFallback.md#borderblock)
- [borderBlockColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockcolor)
- [borderBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockend)
- [borderBlockEndColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockendcolor)
- [borderBlockEndStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockendstyle)
- [borderBlockEndWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockendwidth)
- [borderBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockstart)
- [borderBlockStartColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockstartcolor)
- [borderBlockStartStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockstartstyle)
- [borderBlockStartWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockstartwidth)
- [borderBlockStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockstyle)
- [borderBlockWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderblockwidth)
- [borderBottom](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottom)
- [borderBottomColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottomcolor)
- [borderBottomLeftRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottomleftradius)
- [borderBottomRightRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottomrightradius)
- [borderBottomStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottomstyle)
- [borderBottomWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderbottomwidth)
- [borderCollapse](akashaproject_design_system._internal_.PropertiesFallback.md#bordercollapse)
- [borderColor](akashaproject_design_system._internal_.PropertiesFallback.md#bordercolor)
- [borderEndEndRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderendendradius)
- [borderEndStartRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderendstartradius)
- [borderImage](akashaproject_design_system._internal_.PropertiesFallback.md#borderimage)
- [borderImageOutset](akashaproject_design_system._internal_.PropertiesFallback.md#borderimageoutset)
- [borderImageRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#borderimagerepeat)
- [borderImageSlice](akashaproject_design_system._internal_.PropertiesFallback.md#borderimageslice)
- [borderImageSource](akashaproject_design_system._internal_.PropertiesFallback.md#borderimagesource)
- [borderImageWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderimagewidth)
- [borderInline](akashaproject_design_system._internal_.PropertiesFallback.md#borderinline)
- [borderInlineColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinecolor)
- [borderInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlineend)
- [borderInlineEndColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlineendcolor)
- [borderInlineEndStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlineendstyle)
- [borderInlineEndWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlineendwidth)
- [borderInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinestart)
- [borderInlineStartColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinestartcolor)
- [borderInlineStartStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinestartstyle)
- [borderInlineStartWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinestartwidth)
- [borderInlineStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinestyle)
- [borderInlineWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderinlinewidth)
- [borderLeft](akashaproject_design_system._internal_.PropertiesFallback.md#borderleft)
- [borderLeftColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderleftcolor)
- [borderLeftStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderleftstyle)
- [borderLeftWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderleftwidth)
- [borderRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderradius)
- [borderRight](akashaproject_design_system._internal_.PropertiesFallback.md#borderright)
- [borderRightColor](akashaproject_design_system._internal_.PropertiesFallback.md#borderrightcolor)
- [borderRightStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderrightstyle)
- [borderRightWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderrightwidth)
- [borderSpacing](akashaproject_design_system._internal_.PropertiesFallback.md#borderspacing)
- [borderStartEndRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderstartendradius)
- [borderStartStartRadius](akashaproject_design_system._internal_.PropertiesFallback.md#borderstartstartradius)
- [borderStyle](akashaproject_design_system._internal_.PropertiesFallback.md#borderstyle)
- [borderTop](akashaproject_design_system._internal_.PropertiesFallback.md#bordertop)
- [borderTopColor](akashaproject_design_system._internal_.PropertiesFallback.md#bordertopcolor)
- [borderTopLeftRadius](akashaproject_design_system._internal_.PropertiesFallback.md#bordertopleftradius)
- [borderTopRightRadius](akashaproject_design_system._internal_.PropertiesFallback.md#bordertoprightradius)
- [borderTopStyle](akashaproject_design_system._internal_.PropertiesFallback.md#bordertopstyle)
- [borderTopWidth](akashaproject_design_system._internal_.PropertiesFallback.md#bordertopwidth)
- [borderWidth](akashaproject_design_system._internal_.PropertiesFallback.md#borderwidth)
- [bottom](akashaproject_design_system._internal_.PropertiesFallback.md#bottom)
- [boxAlign](akashaproject_design_system._internal_.PropertiesFallback.md#boxalign)
- [boxDecorationBreak](akashaproject_design_system._internal_.PropertiesFallback.md#boxdecorationbreak)
- [boxDirection](akashaproject_design_system._internal_.PropertiesFallback.md#boxdirection)
- [boxFlex](akashaproject_design_system._internal_.PropertiesFallback.md#boxflex)
- [boxFlexGroup](akashaproject_design_system._internal_.PropertiesFallback.md#boxflexgroup)
- [boxLines](akashaproject_design_system._internal_.PropertiesFallback.md#boxlines)
- [boxOrdinalGroup](akashaproject_design_system._internal_.PropertiesFallback.md#boxordinalgroup)
- [boxOrient](akashaproject_design_system._internal_.PropertiesFallback.md#boxorient)
- [boxPack](akashaproject_design_system._internal_.PropertiesFallback.md#boxpack)
- [boxShadow](akashaproject_design_system._internal_.PropertiesFallback.md#boxshadow)
- [boxSizing](akashaproject_design_system._internal_.PropertiesFallback.md#boxsizing)
- [breakAfter](akashaproject_design_system._internal_.PropertiesFallback.md#breakafter)
- [breakBefore](akashaproject_design_system._internal_.PropertiesFallback.md#breakbefore)
- [breakInside](akashaproject_design_system._internal_.PropertiesFallback.md#breakinside)
- [captionSide](akashaproject_design_system._internal_.PropertiesFallback.md#captionside)
- [caretColor](akashaproject_design_system._internal_.PropertiesFallback.md#caretcolor)
- [clear](akashaproject_design_system._internal_.PropertiesFallback.md#clear)
- [clip](akashaproject_design_system._internal_.PropertiesFallback.md#clip)
- [clipPath](akashaproject_design_system._internal_.PropertiesFallback.md#clippath)
- [clipRule](akashaproject_design_system._internal_.PropertiesFallback.md#cliprule)
- [color](akashaproject_design_system._internal_.PropertiesFallback.md#color)
- [colorAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#coloradjust)
- [colorInterpolation](akashaproject_design_system._internal_.PropertiesFallback.md#colorinterpolation)
- [colorRendering](akashaproject_design_system._internal_.PropertiesFallback.md#colorrendering)
- [colorScheme](akashaproject_design_system._internal_.PropertiesFallback.md#colorscheme)
- [columnCount](akashaproject_design_system._internal_.PropertiesFallback.md#columncount)
- [columnFill](akashaproject_design_system._internal_.PropertiesFallback.md#columnfill)
- [columnGap](akashaproject_design_system._internal_.PropertiesFallback.md#columngap)
- [columnRule](akashaproject_design_system._internal_.PropertiesFallback.md#columnrule)
- [columnRuleColor](akashaproject_design_system._internal_.PropertiesFallback.md#columnrulecolor)
- [columnRuleStyle](akashaproject_design_system._internal_.PropertiesFallback.md#columnrulestyle)
- [columnRuleWidth](akashaproject_design_system._internal_.PropertiesFallback.md#columnrulewidth)
- [columnSpan](akashaproject_design_system._internal_.PropertiesFallback.md#columnspan)
- [columnWidth](akashaproject_design_system._internal_.PropertiesFallback.md#columnwidth)
- [columns](akashaproject_design_system._internal_.PropertiesFallback.md#columns)
- [contain](akashaproject_design_system._internal_.PropertiesFallback.md#contain)
- [content](akashaproject_design_system._internal_.PropertiesFallback.md#content)
- [contentVisibility](akashaproject_design_system._internal_.PropertiesFallback.md#contentvisibility)
- [counterIncrement](akashaproject_design_system._internal_.PropertiesFallback.md#counterincrement)
- [counterReset](akashaproject_design_system._internal_.PropertiesFallback.md#counterreset)
- [counterSet](akashaproject_design_system._internal_.PropertiesFallback.md#counterset)
- [cursor](akashaproject_design_system._internal_.PropertiesFallback.md#cursor)
- [direction](akashaproject_design_system._internal_.PropertiesFallback.md#direction)
- [display](akashaproject_design_system._internal_.PropertiesFallback.md#display)
- [dominantBaseline](akashaproject_design_system._internal_.PropertiesFallback.md#dominantbaseline)
- [emptyCells](akashaproject_design_system._internal_.PropertiesFallback.md#emptycells)
- [fill](akashaproject_design_system._internal_.PropertiesFallback.md#fill)
- [fillOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#fillopacity)
- [fillRule](akashaproject_design_system._internal_.PropertiesFallback.md#fillrule)
- [filter](akashaproject_design_system._internal_.PropertiesFallback.md#filter)
- [flex](akashaproject_design_system._internal_.PropertiesFallback.md#flex)
- [flexBasis](akashaproject_design_system._internal_.PropertiesFallback.md#flexbasis)
- [flexDirection](akashaproject_design_system._internal_.PropertiesFallback.md#flexdirection)
- [flexFlow](akashaproject_design_system._internal_.PropertiesFallback.md#flexflow)
- [flexGrow](akashaproject_design_system._internal_.PropertiesFallback.md#flexgrow)
- [flexShrink](akashaproject_design_system._internal_.PropertiesFallback.md#flexshrink)
- [flexWrap](akashaproject_design_system._internal_.PropertiesFallback.md#flexwrap)
- [float](akashaproject_design_system._internal_.PropertiesFallback.md#float)
- [floodColor](akashaproject_design_system._internal_.PropertiesFallback.md#floodcolor)
- [floodOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#floodopacity)
- [font](akashaproject_design_system._internal_.PropertiesFallback.md#font)
- [fontFamily](akashaproject_design_system._internal_.PropertiesFallback.md#fontfamily)
- [fontFeatureSettings](akashaproject_design_system._internal_.PropertiesFallback.md#fontfeaturesettings)
- [fontKerning](akashaproject_design_system._internal_.PropertiesFallback.md#fontkerning)
- [fontLanguageOverride](akashaproject_design_system._internal_.PropertiesFallback.md#fontlanguageoverride)
- [fontOpticalSizing](akashaproject_design_system._internal_.PropertiesFallback.md#fontopticalsizing)
- [fontSize](akashaproject_design_system._internal_.PropertiesFallback.md#fontsize)
- [fontSizeAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#fontsizeadjust)
- [fontSmooth](akashaproject_design_system._internal_.PropertiesFallback.md#fontsmooth)
- [fontStretch](akashaproject_design_system._internal_.PropertiesFallback.md#fontstretch)
- [fontStyle](akashaproject_design_system._internal_.PropertiesFallback.md#fontstyle)
- [fontSynthesis](akashaproject_design_system._internal_.PropertiesFallback.md#fontsynthesis)
- [fontVariant](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariant)
- [fontVariantAlternates](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariantalternates)
- [fontVariantCaps](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariantcaps)
- [fontVariantEastAsian](akashaproject_design_system._internal_.PropertiesFallback.md#fontvarianteastasian)
- [fontVariantLigatures](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariantligatures)
- [fontVariantNumeric](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariantnumeric)
- [fontVariantPosition](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariantposition)
- [fontVariationSettings](akashaproject_design_system._internal_.PropertiesFallback.md#fontvariationsettings)
- [fontWeight](akashaproject_design_system._internal_.PropertiesFallback.md#fontweight)
- [forcedColorAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#forcedcoloradjust)
- [gap](akashaproject_design_system._internal_.PropertiesFallback.md#gap)
- [glyphOrientationVertical](akashaproject_design_system._internal_.PropertiesFallback.md#glyphorientationvertical)
- [grid](akashaproject_design_system._internal_.PropertiesFallback.md#grid)
- [gridArea](akashaproject_design_system._internal_.PropertiesFallback.md#gridarea)
- [gridAutoColumns](akashaproject_design_system._internal_.PropertiesFallback.md#gridautocolumns)
- [gridAutoFlow](akashaproject_design_system._internal_.PropertiesFallback.md#gridautoflow)
- [gridAutoRows](akashaproject_design_system._internal_.PropertiesFallback.md#gridautorows)
- [gridColumn](akashaproject_design_system._internal_.PropertiesFallback.md#gridcolumn)
- [gridColumnEnd](akashaproject_design_system._internal_.PropertiesFallback.md#gridcolumnend)
- [gridColumnGap](akashaproject_design_system._internal_.PropertiesFallback.md#gridcolumngap)
- [gridColumnStart](akashaproject_design_system._internal_.PropertiesFallback.md#gridcolumnstart)
- [gridGap](akashaproject_design_system._internal_.PropertiesFallback.md#gridgap)
- [gridRow](akashaproject_design_system._internal_.PropertiesFallback.md#gridrow)
- [gridRowEnd](akashaproject_design_system._internal_.PropertiesFallback.md#gridrowend)
- [gridRowGap](akashaproject_design_system._internal_.PropertiesFallback.md#gridrowgap)
- [gridRowStart](akashaproject_design_system._internal_.PropertiesFallback.md#gridrowstart)
- [gridTemplate](akashaproject_design_system._internal_.PropertiesFallback.md#gridtemplate)
- [gridTemplateAreas](akashaproject_design_system._internal_.PropertiesFallback.md#gridtemplateareas)
- [gridTemplateColumns](akashaproject_design_system._internal_.PropertiesFallback.md#gridtemplatecolumns)
- [gridTemplateRows](akashaproject_design_system._internal_.PropertiesFallback.md#gridtemplaterows)
- [hangingPunctuation](akashaproject_design_system._internal_.PropertiesFallback.md#hangingpunctuation)
- [height](akashaproject_design_system._internal_.PropertiesFallback.md#height)
- [hyphens](akashaproject_design_system._internal_.PropertiesFallback.md#hyphens)
- [imageOrientation](akashaproject_design_system._internal_.PropertiesFallback.md#imageorientation)
- [imageRendering](akashaproject_design_system._internal_.PropertiesFallback.md#imagerendering)
- [imageResolution](akashaproject_design_system._internal_.PropertiesFallback.md#imageresolution)
- [imeMode](akashaproject_design_system._internal_.PropertiesFallback.md#imemode)
- [initialLetter](akashaproject_design_system._internal_.PropertiesFallback.md#initialletter)
- [inlineSize](akashaproject_design_system._internal_.PropertiesFallback.md#inlinesize)
- [inset](akashaproject_design_system._internal_.PropertiesFallback.md#inset)
- [insetBlock](akashaproject_design_system._internal_.PropertiesFallback.md#insetblock)
- [insetBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#insetblockend)
- [insetBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#insetblockstart)
- [insetInline](akashaproject_design_system._internal_.PropertiesFallback.md#insetinline)
- [insetInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#insetinlineend)
- [insetInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#insetinlinestart)
- [isolation](akashaproject_design_system._internal_.PropertiesFallback.md#isolation)
- [justifyContent](akashaproject_design_system._internal_.PropertiesFallback.md#justifycontent)
- [justifyItems](akashaproject_design_system._internal_.PropertiesFallback.md#justifyitems)
- [justifySelf](akashaproject_design_system._internal_.PropertiesFallback.md#justifyself)
- [justifyTracks](akashaproject_design_system._internal_.PropertiesFallback.md#justifytracks)
- [left](akashaproject_design_system._internal_.PropertiesFallback.md#left)
- [letterSpacing](akashaproject_design_system._internal_.PropertiesFallback.md#letterspacing)
- [lightingColor](akashaproject_design_system._internal_.PropertiesFallback.md#lightingcolor)
- [lineBreak](akashaproject_design_system._internal_.PropertiesFallback.md#linebreak)
- [lineClamp](akashaproject_design_system._internal_.PropertiesFallback.md#lineclamp)
- [lineHeight](akashaproject_design_system._internal_.PropertiesFallback.md#lineheight)
- [lineHeightStep](akashaproject_design_system._internal_.PropertiesFallback.md#lineheightstep)
- [listStyle](akashaproject_design_system._internal_.PropertiesFallback.md#liststyle)
- [listStyleImage](akashaproject_design_system._internal_.PropertiesFallback.md#liststyleimage)
- [listStylePosition](akashaproject_design_system._internal_.PropertiesFallback.md#liststyleposition)
- [listStyleType](akashaproject_design_system._internal_.PropertiesFallback.md#liststyletype)
- [margin](akashaproject_design_system._internal_.PropertiesFallback.md#margin)
- [marginBlock](akashaproject_design_system._internal_.PropertiesFallback.md#marginblock)
- [marginBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#marginblockend)
- [marginBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#marginblockstart)
- [marginBottom](akashaproject_design_system._internal_.PropertiesFallback.md#marginbottom)
- [marginInline](akashaproject_design_system._internal_.PropertiesFallback.md#margininline)
- [marginInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#margininlineend)
- [marginInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#margininlinestart)
- [marginLeft](akashaproject_design_system._internal_.PropertiesFallback.md#marginleft)
- [marginRight](akashaproject_design_system._internal_.PropertiesFallback.md#marginright)
- [marginTop](akashaproject_design_system._internal_.PropertiesFallback.md#margintop)
- [marker](akashaproject_design_system._internal_.PropertiesFallback.md#marker)
- [markerEnd](akashaproject_design_system._internal_.PropertiesFallback.md#markerend)
- [markerMid](akashaproject_design_system._internal_.PropertiesFallback.md#markermid)
- [markerStart](akashaproject_design_system._internal_.PropertiesFallback.md#markerstart)
- [mask](akashaproject_design_system._internal_.PropertiesFallback.md#mask)
- [maskBorder](akashaproject_design_system._internal_.PropertiesFallback.md#maskborder)
- [maskBorderMode](akashaproject_design_system._internal_.PropertiesFallback.md#maskbordermode)
- [maskBorderOutset](akashaproject_design_system._internal_.PropertiesFallback.md#maskborderoutset)
- [maskBorderRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#maskborderrepeat)
- [maskBorderSlice](akashaproject_design_system._internal_.PropertiesFallback.md#maskborderslice)
- [maskBorderSource](akashaproject_design_system._internal_.PropertiesFallback.md#maskbordersource)
- [maskBorderWidth](akashaproject_design_system._internal_.PropertiesFallback.md#maskborderwidth)
- [maskClip](akashaproject_design_system._internal_.PropertiesFallback.md#maskclip)
- [maskComposite](akashaproject_design_system._internal_.PropertiesFallback.md#maskcomposite)
- [maskImage](akashaproject_design_system._internal_.PropertiesFallback.md#maskimage)
- [maskMode](akashaproject_design_system._internal_.PropertiesFallback.md#maskmode)
- [maskOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#maskorigin)
- [maskPosition](akashaproject_design_system._internal_.PropertiesFallback.md#maskposition)
- [maskRepeat](akashaproject_design_system._internal_.PropertiesFallback.md#maskrepeat)
- [maskSize](akashaproject_design_system._internal_.PropertiesFallback.md#masksize)
- [maskType](akashaproject_design_system._internal_.PropertiesFallback.md#masktype)
- [mathStyle](akashaproject_design_system._internal_.PropertiesFallback.md#mathstyle)
- [maxBlockSize](akashaproject_design_system._internal_.PropertiesFallback.md#maxblocksize)
- [maxHeight](akashaproject_design_system._internal_.PropertiesFallback.md#maxheight)
- [maxInlineSize](akashaproject_design_system._internal_.PropertiesFallback.md#maxinlinesize)
- [maxLines](akashaproject_design_system._internal_.PropertiesFallback.md#maxlines)
- [maxWidth](akashaproject_design_system._internal_.PropertiesFallback.md#maxwidth)
- [minBlockSize](akashaproject_design_system._internal_.PropertiesFallback.md#minblocksize)
- [minHeight](akashaproject_design_system._internal_.PropertiesFallback.md#minheight)
- [minInlineSize](akashaproject_design_system._internal_.PropertiesFallback.md#mininlinesize)
- [minWidth](akashaproject_design_system._internal_.PropertiesFallback.md#minwidth)
- [mixBlendMode](akashaproject_design_system._internal_.PropertiesFallback.md#mixblendmode)
- [motion](akashaproject_design_system._internal_.PropertiesFallback.md#motion)
- [motionDistance](akashaproject_design_system._internal_.PropertiesFallback.md#motiondistance)
- [motionPath](akashaproject_design_system._internal_.PropertiesFallback.md#motionpath)
- [motionRotation](akashaproject_design_system._internal_.PropertiesFallback.md#motionrotation)
- [msAccelerator](akashaproject_design_system._internal_.PropertiesFallback.md#msaccelerator)
- [msAlignSelf](akashaproject_design_system._internal_.PropertiesFallback.md#msalignself)
- [msBlockProgression](akashaproject_design_system._internal_.PropertiesFallback.md#msblockprogression)
- [msContentZoomChaining](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomchaining)
- [msContentZoomLimit](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomlimit)
- [msContentZoomLimitMax](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomlimitmax)
- [msContentZoomLimitMin](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomlimitmin)
- [msContentZoomSnap](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomsnap)
- [msContentZoomSnapPoints](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomsnappoints)
- [msContentZoomSnapType](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzoomsnaptype)
- [msContentZooming](akashaproject_design_system._internal_.PropertiesFallback.md#mscontentzooming)
- [msFilter](akashaproject_design_system._internal_.PropertiesFallback.md#msfilter)
- [msFlex](akashaproject_design_system._internal_.PropertiesFallback.md#msflex)
- [msFlexDirection](akashaproject_design_system._internal_.PropertiesFallback.md#msflexdirection)
- [msFlexPositive](akashaproject_design_system._internal_.PropertiesFallback.md#msflexpositive)
- [msFlowFrom](akashaproject_design_system._internal_.PropertiesFallback.md#msflowfrom)
- [msFlowInto](akashaproject_design_system._internal_.PropertiesFallback.md#msflowinto)
- [msGridColumns](akashaproject_design_system._internal_.PropertiesFallback.md#msgridcolumns)
- [msGridRows](akashaproject_design_system._internal_.PropertiesFallback.md#msgridrows)
- [msHighContrastAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#mshighcontrastadjust)
- [msHyphenateLimitChars](akashaproject_design_system._internal_.PropertiesFallback.md#mshyphenatelimitchars)
- [msHyphenateLimitLines](akashaproject_design_system._internal_.PropertiesFallback.md#mshyphenatelimitlines)
- [msHyphenateLimitZone](akashaproject_design_system._internal_.PropertiesFallback.md#mshyphenatelimitzone)
- [msHyphens](akashaproject_design_system._internal_.PropertiesFallback.md#mshyphens)
- [msImeAlign](akashaproject_design_system._internal_.PropertiesFallback.md#msimealign)
- [msImeMode](akashaproject_design_system._internal_.PropertiesFallback.md#msimemode)
- [msJustifySelf](akashaproject_design_system._internal_.PropertiesFallback.md#msjustifyself)
- [msLineBreak](akashaproject_design_system._internal_.PropertiesFallback.md#mslinebreak)
- [msOrder](akashaproject_design_system._internal_.PropertiesFallback.md#msorder)
- [msOverflowStyle](akashaproject_design_system._internal_.PropertiesFallback.md#msoverflowstyle)
- [msOverflowX](akashaproject_design_system._internal_.PropertiesFallback.md#msoverflowx)
- [msOverflowY](akashaproject_design_system._internal_.PropertiesFallback.md#msoverflowy)
- [msScrollChaining](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollchaining)
- [msScrollLimit](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolllimit)
- [msScrollLimitXMax](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolllimitxmax)
- [msScrollLimitXMin](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolllimitxmin)
- [msScrollLimitYMax](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolllimitymax)
- [msScrollLimitYMin](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolllimitymin)
- [msScrollRails](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollrails)
- [msScrollSnapPointsX](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollsnappointsx)
- [msScrollSnapPointsY](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollsnappointsy)
- [msScrollSnapType](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollsnaptype)
- [msScrollSnapX](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollsnapx)
- [msScrollSnapY](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollsnapy)
- [msScrollTranslation](akashaproject_design_system._internal_.PropertiesFallback.md#msscrolltranslation)
- [msScrollbar3dlightColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbar3dlightcolor)
- [msScrollbarArrowColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbararrowcolor)
- [msScrollbarBaseColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbarbasecolor)
- [msScrollbarDarkshadowColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbardarkshadowcolor)
- [msScrollbarFaceColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbarfacecolor)
- [msScrollbarHighlightColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbarhighlightcolor)
- [msScrollbarShadowColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbarshadowcolor)
- [msScrollbarTrackColor](akashaproject_design_system._internal_.PropertiesFallback.md#msscrollbartrackcolor)
- [msTextAutospace](akashaproject_design_system._internal_.PropertiesFallback.md#mstextautospace)
- [msTextCombineHorizontal](akashaproject_design_system._internal_.PropertiesFallback.md#mstextcombinehorizontal)
- [msTextOverflow](akashaproject_design_system._internal_.PropertiesFallback.md#mstextoverflow)
- [msTouchAction](akashaproject_design_system._internal_.PropertiesFallback.md#mstouchaction)
- [msTouchSelect](akashaproject_design_system._internal_.PropertiesFallback.md#mstouchselect)
- [msTransform](akashaproject_design_system._internal_.PropertiesFallback.md#mstransform)
- [msTransformOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#mstransformorigin)
- [msTransition](akashaproject_design_system._internal_.PropertiesFallback.md#mstransition)
- [msTransitionDelay](akashaproject_design_system._internal_.PropertiesFallback.md#mstransitiondelay)
- [msTransitionDuration](akashaproject_design_system._internal_.PropertiesFallback.md#mstransitionduration)
- [msTransitionProperty](akashaproject_design_system._internal_.PropertiesFallback.md#mstransitionproperty)
- [msTransitionTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#mstransitiontimingfunction)
- [msUserSelect](akashaproject_design_system._internal_.PropertiesFallback.md#msuserselect)
- [msWordBreak](akashaproject_design_system._internal_.PropertiesFallback.md#mswordbreak)
- [msWrapFlow](akashaproject_design_system._internal_.PropertiesFallback.md#mswrapflow)
- [msWrapMargin](akashaproject_design_system._internal_.PropertiesFallback.md#mswrapmargin)
- [msWrapThrough](akashaproject_design_system._internal_.PropertiesFallback.md#mswrapthrough)
- [msWritingMode](akashaproject_design_system._internal_.PropertiesFallback.md#mswritingmode)
- [objectFit](akashaproject_design_system._internal_.PropertiesFallback.md#objectfit)
- [objectPosition](akashaproject_design_system._internal_.PropertiesFallback.md#objectposition)
- [offset](akashaproject_design_system._internal_.PropertiesFallback.md#offset)
- [offsetAnchor](akashaproject_design_system._internal_.PropertiesFallback.md#offsetanchor)
- [offsetBlock](akashaproject_design_system._internal_.PropertiesFallback.md#offsetblock)
- [offsetBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#offsetblockend)
- [offsetBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#offsetblockstart)
- [offsetDistance](akashaproject_design_system._internal_.PropertiesFallback.md#offsetdistance)
- [offsetInline](akashaproject_design_system._internal_.PropertiesFallback.md#offsetinline)
- [offsetInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#offsetinlineend)
- [offsetInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#offsetinlinestart)
- [offsetPath](akashaproject_design_system._internal_.PropertiesFallback.md#offsetpath)
- [offsetRotate](akashaproject_design_system._internal_.PropertiesFallback.md#offsetrotate)
- [offsetRotation](akashaproject_design_system._internal_.PropertiesFallback.md#offsetrotation)
- [opacity](akashaproject_design_system._internal_.PropertiesFallback.md#opacity)
- [order](akashaproject_design_system._internal_.PropertiesFallback.md#order)
- [orphans](akashaproject_design_system._internal_.PropertiesFallback.md#orphans)
- [outline](akashaproject_design_system._internal_.PropertiesFallback.md#outline)
- [outlineColor](akashaproject_design_system._internal_.PropertiesFallback.md#outlinecolor)
- [outlineOffset](akashaproject_design_system._internal_.PropertiesFallback.md#outlineoffset)
- [outlineStyle](akashaproject_design_system._internal_.PropertiesFallback.md#outlinestyle)
- [outlineWidth](akashaproject_design_system._internal_.PropertiesFallback.md#outlinewidth)
- [overflow](akashaproject_design_system._internal_.PropertiesFallback.md#overflow)
- [overflowAnchor](akashaproject_design_system._internal_.PropertiesFallback.md#overflowanchor)
- [overflowBlock](akashaproject_design_system._internal_.PropertiesFallback.md#overflowblock)
- [overflowClipBox](akashaproject_design_system._internal_.PropertiesFallback.md#overflowclipbox)
- [overflowClipMargin](akashaproject_design_system._internal_.PropertiesFallback.md#overflowclipmargin)
- [overflowInline](akashaproject_design_system._internal_.PropertiesFallback.md#overflowinline)
- [overflowWrap](akashaproject_design_system._internal_.PropertiesFallback.md#overflowwrap)
- [overflowX](akashaproject_design_system._internal_.PropertiesFallback.md#overflowx)
- [overflowY](akashaproject_design_system._internal_.PropertiesFallback.md#overflowy)
- [overscrollBehavior](akashaproject_design_system._internal_.PropertiesFallback.md#overscrollbehavior)
- [overscrollBehaviorBlock](akashaproject_design_system._internal_.PropertiesFallback.md#overscrollbehaviorblock)
- [overscrollBehaviorInline](akashaproject_design_system._internal_.PropertiesFallback.md#overscrollbehaviorinline)
- [overscrollBehaviorX](akashaproject_design_system._internal_.PropertiesFallback.md#overscrollbehaviorx)
- [overscrollBehaviorY](akashaproject_design_system._internal_.PropertiesFallback.md#overscrollbehaviory)
- [padding](akashaproject_design_system._internal_.PropertiesFallback.md#padding)
- [paddingBlock](akashaproject_design_system._internal_.PropertiesFallback.md#paddingblock)
- [paddingBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#paddingblockend)
- [paddingBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#paddingblockstart)
- [paddingBottom](akashaproject_design_system._internal_.PropertiesFallback.md#paddingbottom)
- [paddingInline](akashaproject_design_system._internal_.PropertiesFallback.md#paddinginline)
- [paddingInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#paddinginlineend)
- [paddingInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#paddinginlinestart)
- [paddingLeft](akashaproject_design_system._internal_.PropertiesFallback.md#paddingleft)
- [paddingRight](akashaproject_design_system._internal_.PropertiesFallback.md#paddingright)
- [paddingTop](akashaproject_design_system._internal_.PropertiesFallback.md#paddingtop)
- [pageBreakAfter](akashaproject_design_system._internal_.PropertiesFallback.md#pagebreakafter)
- [pageBreakBefore](akashaproject_design_system._internal_.PropertiesFallback.md#pagebreakbefore)
- [pageBreakInside](akashaproject_design_system._internal_.PropertiesFallback.md#pagebreakinside)
- [paintOrder](akashaproject_design_system._internal_.PropertiesFallback.md#paintorder)
- [perspective](akashaproject_design_system._internal_.PropertiesFallback.md#perspective)
- [perspectiveOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#perspectiveorigin)
- [placeContent](akashaproject_design_system._internal_.PropertiesFallback.md#placecontent)
- [placeItems](akashaproject_design_system._internal_.PropertiesFallback.md#placeitems)
- [placeSelf](akashaproject_design_system._internal_.PropertiesFallback.md#placeself)
- [pointerEvents](akashaproject_design_system._internal_.PropertiesFallback.md#pointerevents)
- [position](akashaproject_design_system._internal_.PropertiesFallback.md#position)
- [quotes](akashaproject_design_system._internal_.PropertiesFallback.md#quotes)
- [resize](akashaproject_design_system._internal_.PropertiesFallback.md#resize)
- [right](akashaproject_design_system._internal_.PropertiesFallback.md#right)
- [rotate](akashaproject_design_system._internal_.PropertiesFallback.md#rotate)
- [rowGap](akashaproject_design_system._internal_.PropertiesFallback.md#rowgap)
- [rubyAlign](akashaproject_design_system._internal_.PropertiesFallback.md#rubyalign)
- [rubyMerge](akashaproject_design_system._internal_.PropertiesFallback.md#rubymerge)
- [rubyPosition](akashaproject_design_system._internal_.PropertiesFallback.md#rubyposition)
- [scale](akashaproject_design_system._internal_.PropertiesFallback.md#scale)
- [scrollBehavior](akashaproject_design_system._internal_.PropertiesFallback.md#scrollbehavior)
- [scrollMargin](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmargin)
- [scrollMarginBlock](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginblock)
- [scrollMarginBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginblockend)
- [scrollMarginBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginblockstart)
- [scrollMarginBottom](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginbottom)
- [scrollMarginInline](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmargininline)
- [scrollMarginInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmargininlineend)
- [scrollMarginInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmargininlinestart)
- [scrollMarginLeft](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginleft)
- [scrollMarginRight](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmarginright)
- [scrollMarginTop](akashaproject_design_system._internal_.PropertiesFallback.md#scrollmargintop)
- [scrollPadding](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpadding)
- [scrollPaddingBlock](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingblock)
- [scrollPaddingBlockEnd](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingblockend)
- [scrollPaddingBlockStart](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingblockstart)
- [scrollPaddingBottom](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingbottom)
- [scrollPaddingInline](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddinginline)
- [scrollPaddingInlineEnd](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddinginlineend)
- [scrollPaddingInlineStart](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddinginlinestart)
- [scrollPaddingLeft](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingleft)
- [scrollPaddingRight](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingright)
- [scrollPaddingTop](akashaproject_design_system._internal_.PropertiesFallback.md#scrollpaddingtop)
- [scrollSnapAlign](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapalign)
- [scrollSnapCoordinate](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapcoordinate)
- [scrollSnapDestination](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapdestination)
- [scrollSnapMargin](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapmargin)
- [scrollSnapMarginBottom](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapmarginbottom)
- [scrollSnapMarginLeft](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapmarginleft)
- [scrollSnapMarginRight](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapmarginright)
- [scrollSnapMarginTop](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapmargintop)
- [scrollSnapPointsX](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnappointsx)
- [scrollSnapPointsY](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnappointsy)
- [scrollSnapStop](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnapstop)
- [scrollSnapType](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnaptype)
- [scrollSnapTypeX](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnaptypex)
- [scrollSnapTypeY](akashaproject_design_system._internal_.PropertiesFallback.md#scrollsnaptypey)
- [scrollbarColor](akashaproject_design_system._internal_.PropertiesFallback.md#scrollbarcolor)
- [scrollbarGutter](akashaproject_design_system._internal_.PropertiesFallback.md#scrollbargutter)
- [scrollbarTrackColor](akashaproject_design_system._internal_.PropertiesFallback.md#scrollbartrackcolor)
- [scrollbarWidth](akashaproject_design_system._internal_.PropertiesFallback.md#scrollbarwidth)
- [shapeImageThreshold](akashaproject_design_system._internal_.PropertiesFallback.md#shapeimagethreshold)
- [shapeMargin](akashaproject_design_system._internal_.PropertiesFallback.md#shapemargin)
- [shapeOutside](akashaproject_design_system._internal_.PropertiesFallback.md#shapeoutside)
- [shapeRendering](akashaproject_design_system._internal_.PropertiesFallback.md#shaperendering)
- [stopColor](akashaproject_design_system._internal_.PropertiesFallback.md#stopcolor)
- [stopOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#stopopacity)
- [stroke](akashaproject_design_system._internal_.PropertiesFallback.md#stroke)
- [strokeDasharray](akashaproject_design_system._internal_.PropertiesFallback.md#strokedasharray)
- [strokeDashoffset](akashaproject_design_system._internal_.PropertiesFallback.md#strokedashoffset)
- [strokeLinecap](akashaproject_design_system._internal_.PropertiesFallback.md#strokelinecap)
- [strokeLinejoin](akashaproject_design_system._internal_.PropertiesFallback.md#strokelinejoin)
- [strokeMiterlimit](akashaproject_design_system._internal_.PropertiesFallback.md#strokemiterlimit)
- [strokeOpacity](akashaproject_design_system._internal_.PropertiesFallback.md#strokeopacity)
- [strokeWidth](akashaproject_design_system._internal_.PropertiesFallback.md#strokewidth)
- [tabSize](akashaproject_design_system._internal_.PropertiesFallback.md#tabsize)
- [tableLayout](akashaproject_design_system._internal_.PropertiesFallback.md#tablelayout)
- [textAlign](akashaproject_design_system._internal_.PropertiesFallback.md#textalign)
- [textAlignLast](akashaproject_design_system._internal_.PropertiesFallback.md#textalignlast)
- [textAnchor](akashaproject_design_system._internal_.PropertiesFallback.md#textanchor)
- [textCombineUpright](akashaproject_design_system._internal_.PropertiesFallback.md#textcombineupright)
- [textDecoration](akashaproject_design_system._internal_.PropertiesFallback.md#textdecoration)
- [textDecorationColor](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationcolor)
- [textDecorationLine](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationline)
- [textDecorationSkip](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationskip)
- [textDecorationSkipInk](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationskipink)
- [textDecorationStyle](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationstyle)
- [textDecorationThickness](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationthickness)
- [textDecorationWidth](akashaproject_design_system._internal_.PropertiesFallback.md#textdecorationwidth)
- [textEmphasis](akashaproject_design_system._internal_.PropertiesFallback.md#textemphasis)
- [textEmphasisColor](akashaproject_design_system._internal_.PropertiesFallback.md#textemphasiscolor)
- [textEmphasisPosition](akashaproject_design_system._internal_.PropertiesFallback.md#textemphasisposition)
- [textEmphasisStyle](akashaproject_design_system._internal_.PropertiesFallback.md#textemphasisstyle)
- [textIndent](akashaproject_design_system._internal_.PropertiesFallback.md#textindent)
- [textJustify](akashaproject_design_system._internal_.PropertiesFallback.md#textjustify)
- [textOrientation](akashaproject_design_system._internal_.PropertiesFallback.md#textorientation)
- [textOverflow](akashaproject_design_system._internal_.PropertiesFallback.md#textoverflow)
- [textRendering](akashaproject_design_system._internal_.PropertiesFallback.md#textrendering)
- [textShadow](akashaproject_design_system._internal_.PropertiesFallback.md#textshadow)
- [textSizeAdjust](akashaproject_design_system._internal_.PropertiesFallback.md#textsizeadjust)
- [textTransform](akashaproject_design_system._internal_.PropertiesFallback.md#texttransform)
- [textUnderlineOffset](akashaproject_design_system._internal_.PropertiesFallback.md#textunderlineoffset)
- [textUnderlinePosition](akashaproject_design_system._internal_.PropertiesFallback.md#textunderlineposition)
- [top](akashaproject_design_system._internal_.PropertiesFallback.md#top)
- [touchAction](akashaproject_design_system._internal_.PropertiesFallback.md#touchaction)
- [transform](akashaproject_design_system._internal_.PropertiesFallback.md#transform)
- [transformBox](akashaproject_design_system._internal_.PropertiesFallback.md#transformbox)
- [transformOrigin](akashaproject_design_system._internal_.PropertiesFallback.md#transformorigin)
- [transformStyle](akashaproject_design_system._internal_.PropertiesFallback.md#transformstyle)
- [transition](akashaproject_design_system._internal_.PropertiesFallback.md#transition)
- [transitionDelay](akashaproject_design_system._internal_.PropertiesFallback.md#transitiondelay)
- [transitionDuration](akashaproject_design_system._internal_.PropertiesFallback.md#transitionduration)
- [transitionProperty](akashaproject_design_system._internal_.PropertiesFallback.md#transitionproperty)
- [transitionTimingFunction](akashaproject_design_system._internal_.PropertiesFallback.md#transitiontimingfunction)
- [translate](akashaproject_design_system._internal_.PropertiesFallback.md#translate)
- [unicodeBidi](akashaproject_design_system._internal_.PropertiesFallback.md#unicodebidi)
- [userSelect](akashaproject_design_system._internal_.PropertiesFallback.md#userselect)
- [vectorEffect](akashaproject_design_system._internal_.PropertiesFallback.md#vectoreffect)
- [verticalAlign](akashaproject_design_system._internal_.PropertiesFallback.md#verticalalign)
- [visibility](akashaproject_design_system._internal_.PropertiesFallback.md#visibility)
- [whiteSpace](akashaproject_design_system._internal_.PropertiesFallback.md#whitespace)
- [widows](akashaproject_design_system._internal_.PropertiesFallback.md#widows)
- [width](akashaproject_design_system._internal_.PropertiesFallback.md#width)
- [willChange](akashaproject_design_system._internal_.PropertiesFallback.md#willchange)
- [wordBreak](akashaproject_design_system._internal_.PropertiesFallback.md#wordbreak)
- [wordSpacing](akashaproject_design_system._internal_.PropertiesFallback.md#wordspacing)
- [wordWrap](akashaproject_design_system._internal_.PropertiesFallback.md#wordwrap)
- [writingMode](akashaproject_design_system._internal_.PropertiesFallback.md#writingmode)
- [zIndex](akashaproject_design_system._internal_.PropertiesFallback.md#zindex)
- [zoom](akashaproject_design_system._internal_.PropertiesFallback.md#zoom)

## Properties

### KhtmlBoxAlign

• `Optional` **KhtmlBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25584

___

### KhtmlBoxDirection

• `Optional` **KhtmlBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25594

___

### KhtmlBoxFlex

• `Optional` **KhtmlBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25604

___

### KhtmlBoxFlexGroup

• `Optional` **KhtmlBoxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxflexgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25614

___

### KhtmlBoxLines

• `Optional` **KhtmlBoxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25624

___

### KhtmlBoxOrdinalGroup

• `Optional` **KhtmlBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxordinalgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25634

___

### KhtmlBoxOrient

• `Optional` **KhtmlBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25644

___

### KhtmlBoxPack

• `Optional` **KhtmlBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlboxpack)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25654

___

### KhtmlLineBreak

• `Optional` **KhtmlLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlLineBreak](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmllinebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25664

___

### KhtmlOpacity

• `Optional` **KhtmlOpacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

The **`opacity`** CSS property sets the transparency of an element or the degree to which content behind an element is visible.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlOpacity](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmlopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25674

___

### KhtmlUserSelect

• `Optional` **KhtmlUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[KhtmlUserSelect](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#khtmluserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25684

___

### MozAnimation

• `Optional` **MozAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25147

___

### MozAnimationDelay

• `Optional` **MozAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23354

___

### MozAnimationDirection

• `Optional` **MozAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23362

___

### MozAnimationDuration

• `Optional` **MozAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23370

___

### MozAnimationFillMode

• `Optional` **MozAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationFillMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23378

___

### MozAnimationIterationCount

• `Optional` **MozAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationIterationCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23386

___

### MozAnimationName

• `Optional` **MozAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationName](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23394

___

### MozAnimationPlayState

• `Optional` **MozAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationPlayState](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23402

___

### MozAnimationTimingFunction

• `Optional` **MozAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAnimationTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozanimationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23410

___

### MozAppearance

• `Optional` **MozAppearance**: [`MozAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#mozappearanceproperty) \| [`MozAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#mozappearanceproperty)[]

The **`-moz-appearance`** CSS property is used in Gecko (Firefox) to display an element using platform-native styling based on the operating system's theme.

**Syntax**: `none | button | button-arrow-down | button-arrow-next | button-arrow-previous | button-arrow-up | button-bevel | button-focus | caret | checkbox | checkbox-container | checkbox-label | checkmenuitem | dualbutton | groupbox | listbox | listitem | menuarrow | menubar | menucheckbox | menuimage | menuitem | menuitemtext | menulist | menulist-button | menulist-text | menulist-textfield | menupopup | menuradio | menuseparator | meterbar | meterchunk | progressbar | progressbar-vertical | progresschunk | progresschunk-vertical | radio | radio-container | radio-label | radiomenuitem | range | range-thumb | resizer | resizerpanel | scale-horizontal | scalethumbend | scalethumb-horizontal | scalethumbstart | scalethumbtick | scalethumb-vertical | scale-vertical | scrollbarbutton-down | scrollbarbutton-left | scrollbarbutton-right | scrollbarbutton-up | scrollbarthumb-horizontal | scrollbarthumb-vertical | scrollbartrack-horizontal | scrollbartrack-vertical | searchfield | separator | sheet | spinner | spinner-downbutton | spinner-textfield | spinner-upbutton | splitter | statusbar | statusbarpanel | tab | tabpanel | tabpanels | tab-scroll-arrow-back | tab-scroll-arrow-forward | textfield | textfield-multiline | toolbar | toolbarbutton | toolbarbutton-dropdown | toolbargripper | toolbox | tooltip | treeheader | treeheadercell | treeheadersortarrow | treeitem | treeline | treetwisty | treetwistyopen | treeview | -moz-mac-unified-toolbar | -moz-win-borderless-glass | -moz-win-browsertabbar-toolbox | -moz-win-communicationstext | -moz-win-communications-toolbox | -moz-win-exclude-glass | -moz-win-glass | -moz-win-mediatext | -moz-win-media-toolbox | -moz-window-button-box | -moz-window-button-box-maximized | -moz-window-button-close | -moz-window-button-maximize | -moz-window-button-minimize | -moz-window-button-restore | -moz-window-frame-bottom | -moz-window-frame-left | -moz-window-frame-right | -moz-window-titlebar | -moz-window-titlebar-maximized`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozAppearance](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozappearance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23418

___

### MozBackfaceVisibility

• `Optional` **MozBackfaceVisibility**: [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty) \| [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty)[]

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBackfaceVisibility](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozbackfacevisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23426

___

### MozBackgroundClip

• `Optional` **MozBackgroundClip**: `string` \| `string`[]

The **`background-clip`** CSS property sets whether an element's background `<color>` or `<image>` extends underneath its border.

**Syntax**: `<box>#`

**Initial value**: `border-box`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBackgroundClip](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25694

___

### MozBackgroundInlinePolicy

• `Optional` **MozBackgroundInlinePolicy**: [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty) \| [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty)[]

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBackgroundInlinePolicy](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundinlinepolicy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25704

___

### MozBackgroundOrigin

• `Optional` **MozBackgroundOrigin**: `string` \| `string`[]

The **`background-origin`** CSS property sets the _background positioning area_. In other words, it sets the origin position of an image set with the `background-image` property.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBackgroundOrigin](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25714

___

### MozBackgroundSize

• `Optional` **MozBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBackgroundSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbackgroundsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25724

___

### MozBinding

• `Optional` **MozBinding**: `string` \| `string`[]

The **`-moz-binding`** CSS property is used by Mozilla-based applications to attach an XBL binding to a DOM element.

**Syntax**: `<url> | none`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBinding](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozbinding)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25734

___

### MozBorderBottomColors

• `Optional` **MozBorderBottomColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-bottom-colors`** CSS property sets a list of colors for the bottom border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderBottomColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderbottomcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23434

___

### MozBorderEndColor

• `Optional` **MozBorderEndColor**: `string` \| `string`[]

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderEndColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23442

___

### MozBorderEndStyle

• `Optional` **MozBorderEndStyle**: [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty) \| [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty)[]

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderEndStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23450

___

### MozBorderEndWidth

• `Optional` **MozBorderEndWidth**: [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\> \| [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\>[]

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderEndWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderendwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23458

___

### MozBorderImage

• `Optional` **MozBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25153

___

### MozBorderLeftColors

• `Optional` **MozBorderLeftColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-left-colors`** CSS property sets a list of colors for the left border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderLeftColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderleftcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23466

___

### MozBorderRadius

• `Optional` **MozBorderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBorderRadius](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25742

___

### MozBorderRadiusBottomleft

• `Optional` **MozBorderRadiusBottomleft**: [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\> \| [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\>[]

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBorderRadiusBottomleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiusbottomleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25752

___

### MozBorderRadiusBottomright

• `Optional` **MozBorderRadiusBottomright**: [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\> \| [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\>[]

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBorderRadiusBottomright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiusbottomright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25762

___

### MozBorderRadiusTopleft

• `Optional` **MozBorderRadiusTopleft**: [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\> \| [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\>[]

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBorderRadiusTopleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiustopleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25772

___

### MozBorderRadiusTopright

• `Optional` **MozBorderRadiusTopright**: [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\> \| [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\>[]

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBorderRadiusTopright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozborderradiustopright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25782

___

### MozBorderRightColors

• `Optional` **MozBorderRightColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-right-colors`** CSS property sets a list of colors for the right border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderRightColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderrightcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23474

___

### MozBorderStartColor

• `Optional` **MozBorderStartColor**: `string` \| `string`[]

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderStartColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderstartcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23482

___

### MozBorderStartStyle

• `Optional` **MozBorderStartStyle**: [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty) \| [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty)[]

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderStartStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozborderstartstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23490

___

### MozBorderTopColors

• `Optional` **MozBorderTopColors**: `string` \| `string`[]

In Mozilla applications like Firefox, the **`-moz-border-top-colors`** CSS property sets a list of colors for the top border.

**Syntax**: `<color>+ | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBorderTopColors](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozbordertopcolors)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23498

___

### MozBoxAlign

• `Optional` **MozBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25792

___

### MozBoxDirection

• `Optional` **MozBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25802

___

### MozBoxFlex

• `Optional` **MozBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25812

___

### MozBoxOrdinalGroup

• `Optional` **MozBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxordinalgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25822

___

### MozBoxOrient

• `Optional` **MozBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25832

___

### MozBoxPack

• `Optional` **MozBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxpack)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25842

___

### MozBoxShadow

• `Optional` **MozBoxShadow**: `string` \| `string`[]

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozBoxShadow](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozboxshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25852

___

### MozBoxSizing

• `Optional` **MozBoxSizing**: [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty) \| [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty)[]

The **`box-sizing`** CSS property defines how the user agent should calculate the total width and height of an element.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozBoxSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozboxsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23506

___

### MozColumnCount

• `Optional` **MozColumnCount**: [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty) \| [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty)[]

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumncount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23514

___

### MozColumnFill

• `Optional` **MozColumnFill**: [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty) \| [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty)[]

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnFill](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnfill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23522

___

### MozColumnGap

• `Optional` **MozColumnGap**: [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\> \| [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnGap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23530

___

### MozColumnRule

• `Optional` **MozColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnRule](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25159

___

### MozColumnRuleColor

• `Optional` **MozColumnRuleColor**: `string` \| `string`[]

The **`column-rule-color`** CSS property sets the color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnRuleColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23538

___

### MozColumnRuleStyle

• `Optional` **MozColumnRuleStyle**: `string` \| `string`[]

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnRuleStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23546

___

### MozColumnRuleWidth

• `Optional` **MozColumnRuleWidth**: [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\> \| [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\>[]

The **`column-rule-width`** CSS property sets the width of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnRuleWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnrulewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23554

___

### MozColumnWidth

• `Optional` **MozColumnWidth**: [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\> \| [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\>[]

The **`column-width`** CSS property specifies the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumnWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumnwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23562

___

### MozColumns

• `Optional` **MozColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25165

___

### MozContextProperties

• `Optional` **MozContextProperties**: `string` \| `string`[]

If you reference an SVG image in a webpage (such as with the `<img>` element or as a background image), the SVG image can coordinate with the embedding element (its context) to have the image adopt property values set on the embedding element. To do this the embedding element needs to list the properties that are to be made available to the image by listing them as values of the **`-moz-context-properties`** property, and the image needs to opt in to using those properties by using values such as the `context-fill` value.

**Syntax**: `none | [ fill | fill-opacity | stroke | stroke-opacity ]#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozContextProperties](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozcontextproperties)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23570

___

### MozFloatEdge

• `Optional` **MozFloatEdge**: [`MozFloatEdgeProperty`](../modules/akashaproject_design_system._internal_.md#mozfloatedgeproperty) \| [`MozFloatEdgeProperty`](../modules/akashaproject_design_system._internal_.md#mozfloatedgeproperty)[]

The non-standard **`-moz-float-edge`** CSS property specifies whether the height and width properties of the element include the margin, border, or padding thickness.

**Syntax**: `border-box | content-box | margin-box | padding-box`

**Initial value**: `content-box`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozFloatEdge](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozfloatedge)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25862

___

### MozFontFeatureSettings

• `Optional` **MozFontFeatureSettings**: `string` \| `string`[]

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozFontFeatureSettings](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozfontfeaturesettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23578

___

### MozFontLanguageOverride

• `Optional` **MozFontLanguageOverride**: `string` \| `string`[]

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozFontLanguageOverride](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozfontlanguageoverride)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23586

___

### MozForceBrokenImageIcon

• `Optional` **MozForceBrokenImageIcon**: [`MozForceBrokenImageIconProperty`](../modules/akashaproject_design_system._internal_.md#mozforcebrokenimageiconproperty) \| [`MozForceBrokenImageIconProperty`](../modules/akashaproject_design_system._internal_.md#mozforcebrokenimageiconproperty)[]

The **`-moz-force-broken-image-icon`** extended CSS property can be used to force the broken image icon to be shown even when a broken image has an `alt` attribute.

**Syntax**: `0 | 1`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozForceBrokenImageIcon](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozforcebrokenimageicon)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25872

___

### MozHyphens

• `Optional` **MozHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozhyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23594

___

### MozImageRegion

• `Optional` **MozImageRegion**: `string` \| `string`[]

For certain XUL elements and pseudo-elements that use an image from the `list-style-image` property, this property specifies a region of the image that is used in place of the whole image. This allows elements to use different pieces of the same image to improve performance.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozImageRegion](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozimageregion)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23602

___

### MozMarginEnd

• `Optional` **MozMarginEnd**: [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\> \| [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\>[]

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozMarginEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozmarginend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23610

___

### MozMarginStart

• `Optional` **MozMarginStart**: [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\> \| [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\>[]

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozMarginStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozmarginstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23618

___

### MozOpacity

• `Optional` **MozOpacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

The **`opacity`** CSS property sets the transparency of an element or the degree to which content behind an element is visible.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOpacity](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25882

___

### MozOrient

• `Optional` **MozOrient**: [`MozOrientProperty`](../modules/akashaproject_design_system._internal_.md#mozorientproperty) \| [`MozOrientProperty`](../modules/akashaproject_design_system._internal_.md#mozorientproperty)[]

The **`-moz-orient`** CSS property specifies the orientation of the element to which it's applied.

**Syntax**: `inline | block | horizontal | vertical`

**Initial value**: `inline`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozOrient](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23626

___

### MozOsxFontSmoothing

• `Optional` **MozOsxFontSmoothing**: [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\> \| [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\>[]

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozOsxFontSmoothing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozosxfontsmoothing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23634

___

### MozOutline

• `Optional` **MozOutline**: [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\> \| [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\>[]

The **`outline`** CSS property is a shorthand to set various outline properties in a single declaration: `outline-style`, `outline-width`, and `outline-color`.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutline](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25890

___

### MozOutlineColor

• `Optional` **MozOutlineColor**: `string` \| `string`[]

The **`outline-color`** CSS property sets the color of an element's outline.

**Syntax**: `<color> | invert`

**Initial value**: `invert`, for browsers supporting it, `currentColor` for the other

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25900

___

### MozOutlineRadius

• `Optional` **MozOutlineRadius**: [`MozOutlineRadiusProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusproperty)<`TLength`\> \| [`MozOutlineRadiusProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusproperty)<`TLength`\>[]

In Mozilla applications like Firefox, the **`-moz-outline-radius`** CSS property can be used to give an element's `outline` rounded corners.

**Syntax**: `<outline-radius>{1,4} [ / <outline-radius>{1,4} ]?`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineRadius](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25908

___

### MozOutlineRadiusBottomleft

• `Optional` **MozOutlineRadiusBottomleft**: [`MozOutlineRadiusBottomleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleftproperty)<`TLength`\> \| [`MozOutlineRadiusBottomleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomleftproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-bottomleft`** CSS property can be used to round the bottom-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineRadiusBottomleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiusbottomleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25918

___

### MozOutlineRadiusBottomright

• `Optional` **MozOutlineRadiusBottomright**: [`MozOutlineRadiusBottomrightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomrightproperty)<`TLength`\> \| [`MozOutlineRadiusBottomrightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiusbottomrightproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-bottomright`** CSS property can be used to round the bottom-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineRadiusBottomright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiusbottomright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25928

___

### MozOutlineRadiusTopleft

• `Optional` **MozOutlineRadiusTopleft**: [`MozOutlineRadiusTopleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleftproperty)<`TLength`\> \| [`MozOutlineRadiusTopleftProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustopleftproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-topleft`** CSS property can be used to round the top-left corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineRadiusTopleft](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiustopleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25938

___

### MozOutlineRadiusTopright

• `Optional` **MozOutlineRadiusTopright**: [`MozOutlineRadiusToprightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustoprightproperty)<`TLength`\> \| [`MozOutlineRadiusToprightProperty`](../modules/akashaproject_design_system._internal_.md#mozoutlineradiustoprightproperty)<`TLength`\>[]

In Mozilla applications, the **`-moz-outline-radius-topright`** CSS property can be used to round the top-right corner of an element's `outline`.

**Syntax**: `<outline-radius>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineRadiusTopright](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlineradiustopright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25948

___

### MozOutlineStyle

• `Optional` **MozOutlineStyle**: `string` \| `string`[]

The **`outline-style`** CSS property sets the style of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `auto | <'border-style'>`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineStyle](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25958

___

### MozOutlineWidth

• `Optional` **MozOutlineWidth**: [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\> \| [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\>[]

The **`outline-width`** CSS property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozOutlineWidth](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozoutlinewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25968

___

### MozPaddingEnd

• `Optional` **MozPaddingEnd**: [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\> \| [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\>[]

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozPaddingEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozpaddingend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23642

___

### MozPaddingStart

• `Optional` **MozPaddingStart**: [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\> \| [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\>[]

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozPaddingStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozpaddingstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23650

___

### MozPerspective

• `Optional` **MozPerspective**: [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\> \| [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\>[]

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective. Each 3D element with z>0 becomes larger; each 3D-element with z<0 becomes smaller. The strength of the effect is determined by the value of this property.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozPerspective](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozperspective)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23658

___

### MozPerspectiveOrigin

• `Optional` **MozPerspectiveOrigin**: [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\> \| [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\>[]

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozPerspectiveOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozperspectiveorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23666

___

### MozStackSizing

• `Optional` **MozStackSizing**: [`MozStackSizingProperty`](../modules/akashaproject_design_system._internal_.md#mozstacksizingproperty) \| [`MozStackSizingProperty`](../modules/akashaproject_design_system._internal_.md#mozstacksizingproperty)[]

**`-moz-stack-sizing`** is an extended CSS property. Normally, a `stack` will change its size so that all of its child elements are completely visible. For example, moving a child of the stack far to the right will widen the stack so the child remains visible.

**Syntax**: `ignore | stretch-to-fit`

**Initial value**: `stretch-to-fit`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozStackSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozstacksizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23674

___

### MozTabSize

• `Optional` **MozTabSize**: [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\> \| [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\>[]

The **`tab-size`** CSS property is used to customize the width of a tab (`U+0009`) character.

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTabSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztabsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23682

___

### MozTextAlignLast

• `Optional` **MozTextAlignLast**: [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty) \| [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty)[]

The **`text-align-last`** CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

**Syntax**: `auto | start | end | left | right | center | justify`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozTextAlignLast](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextalignlast)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25978

___

### MozTextBlink

• `Optional` **MozTextBlink**: [`MozTextBlinkProperty`](../modules/akashaproject_design_system._internal_.md#moztextblinkproperty) \| [`MozTextBlinkProperty`](../modules/akashaproject_design_system._internal_.md#moztextblinkproperty)[]

The **`-moz-text-blink`** non-standard Mozilla CSS extension specifies the blink mode.

**Syntax**: `none | blink`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTextBlink](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztextblink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23690

___

### MozTextDecorationColor

• `Optional` **MozTextDecorationColor**: `string` \| `string`[]

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozTextDecorationColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25988

___

### MozTextDecorationLine

• `Optional` **MozTextDecorationLine**: `string` \| `string`[]

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozTextDecorationLine](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25998

___

### MozTextDecorationStyle

• `Optional` **MozTextDecorationStyle**: [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty) \| [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty)[]

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozTextDecorationStyle](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#moztextdecorationstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26008

___

### MozTextSizeAdjust

• `Optional` **MozTextSizeAdjust**: `string` \| `string`[]

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTextSizeAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztextsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23698

___

### MozTransformOrigin

• `Optional` **MozTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23706

___

### MozTransformStyle

• `Optional` **MozTransformStyle**: [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty) \| [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty)[]

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransformStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransformstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23714

___

### MozTransition

• `Optional` **MozTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25171

___

### MozTransitionDelay

• `Optional` **MozTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23722

___

### MozTransitionDuration

• `Optional` **MozTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23730

___

### MozTransitionProperty

• `Optional` **MozTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23738

___

### MozTransitionTimingFunction

• `Optional` **MozTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#moztransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23746

___

### MozUserFocus

• `Optional` **MozUserFocus**: [`MozUserFocusProperty`](../modules/akashaproject_design_system._internal_.md#mozuserfocusproperty) \| [`MozUserFocusProperty`](../modules/akashaproject_design_system._internal_.md#mozuserfocusproperty)[]

The **`-moz-user-focus`** CSS property is used to indicate whether an element can have the focus.

**Syntax**: `ignore | normal | select-after | select-before | select-menu | select-same | select-all | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozUserFocus](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozuserfocus)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23754

___

### MozUserInput

• `Optional` **MozUserInput**: [`MozUserInputProperty`](../modules/akashaproject_design_system._internal_.md#mozuserinputproperty) \| [`MozUserInputProperty`](../modules/akashaproject_design_system._internal_.md#mozuserinputproperty)[]

In Mozilla applications, **`-moz-user-input`** determines if an element will accept user input.

**Syntax**: `auto | none | enabled | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[MozUserInput](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#mozuserinput)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26018

___

### MozUserModify

• `Optional` **MozUserModify**: [`MozUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#mozusermodifyproperty) \| [`MozUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#mozusermodifyproperty)[]

The **`user-modify`** property has no effect in Firefox. It was originally planned to determine whether or not the content of an element can be edited by a user.

**Syntax**: `read-only | read-write | write-only`

**Initial value**: `read-only`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozUserModify](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozusermodify)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23762

___

### MozUserSelect

• `Optional` **MozUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozuserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23770

___

### MozWindowDragging

• `Optional` **MozWindowDragging**: [`MozWindowDraggingProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowdraggingproperty) \| [`MozWindowDraggingProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowdraggingproperty)[]

The **`-moz-window-dragging`** CSS property specifies whether a window is draggable or not. It only works in Chrome code, and only on Mac OS X.

**Syntax**: `drag | no-drag`

**Initial value**: `drag`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozWindowDragging](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozwindowdragging)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23778

___

### MozWindowShadow

• `Optional` **MozWindowShadow**: [`MozWindowShadowProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowshadowproperty) \| [`MozWindowShadowProperty`](../modules/akashaproject_design_system._internal_.md#mozwindowshadowproperty)[]

The **`-moz-window-shadow`** CSS property specifies whether a window will have a shadow. It only works on Mac OS X.

**Syntax**: `default | menu | tooltip | sheet | none`

**Initial value**: `default`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[MozWindowShadow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mozwindowshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23786

___

### OAnimation

• `Optional` **OAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimation](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26046

___

### OAnimationDelay

• `Optional` **OAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationDelay](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26056

___

### OAnimationDirection

• `Optional` **OAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26066

___

### OAnimationDuration

• `Optional` **OAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationDuration](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26076

___

### OAnimationFillMode

• `Optional` **OAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationFillMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26086

___

### OAnimationIterationCount

• `Optional` **OAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationIterationCount](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26096

___

### OAnimationName

• `Optional` **OAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationName](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26106

___

### OAnimationPlayState

• `Optional` **OAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationPlayState](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26116

___

### OAnimationTimingFunction

• `Optional` **OAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OAnimationTimingFunction](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oanimationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26126

___

### OBackgroundSize

• `Optional` **OBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OBackgroundSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#obackgroundsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26136

___

### OBorderImage

• `Optional` **OBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OBorderImage](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oborderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26144

___

### OObjectFit

• `Optional` **OObjectFit**: [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty) \| [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty)[]

The **`object-fit`** CSS property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container.

**Syntax**: `fill | contain | cover | none | scale-down`

**Initial value**: `fill`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OObjectFit](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oobjectfit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26154

___

### OObjectPosition

• `Optional` **OObjectPosition**: [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\> \| [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\>[]

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OObjectPosition](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#oobjectposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26164

___

### OTabSize

• `Optional` **OTabSize**: [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\> \| [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\>[]

The **`tab-size`** CSS property is used to customize the width of a tab (`U+0009`) character.

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTabSize](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otabsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26174

___

### OTextOverflow

• `Optional` **OTextOverflow**: `string` \| `string`[]

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTextOverflow](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otextoverflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26184

___

### OTransform

• `Optional` **OTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransform](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26194

___

### OTransformOrigin

• `Optional` **OTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransformOrigin](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26204

___

### OTransition

• `Optional` **OTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransition](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26212

___

### OTransitionDelay

• `Optional` **OTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransitionDelay](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26222

___

### OTransitionDuration

• `Optional` **OTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransitionDuration](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26232

___

### OTransitionProperty

• `Optional` **OTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransitionProperty](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26242

___

### OTransitionTimingFunction

• `Optional` **OTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[OTransitionTimingFunction](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#otransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26252

___

### WebkitAlignContent

• `Optional` **WebkitAlignContent**: `string` \| `string`[]

The CSS **`align-content`** property sets how the browser distributes space between and around content items along the cross-axis of a flexbox container, and the main-axis of a grid container.

**Syntax**: `normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position>`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAlignContent](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitaligncontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24290

___

### WebkitAlignItems

• `Optional` **WebkitAlignItems**: `string` \| `string`[]

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. The align-self property sets the alignment of an item within its containing block. In Flexbox it controls the alignment of items on the Cross Axis, in Grid Layout it controls the alignment of items on the Block Axis within their grid area.

**Syntax**: `normal | stretch | <baseline-position> | [ <overflow-position>? <self-position> ]`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAlignItems](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitalignitems)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24298

___

### WebkitAlignSelf

• `Optional` **WebkitAlignSelf**: `string` \| `string`[]

The **`align-self`** CSS property aligns flex items of the current flex line overriding the `align-items` value. If any of the item's cross-axis margin is set to `auto`, then `align-self` is ignored. In Grid layout `align-self` aligns the item inside the grid area.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAlignSelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitalignself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24306

___

### WebkitAnimation

• `Optional` **WebkitAnimation**: [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty) \| [`AnimationProperty`](../modules/akashaproject_design_system._internal_.md#animationproperty)[]

The **`animation`** shorthand CSS property sets an animated transition between styles. It is a shorthand for `animation-name`, `animation-duration`, `animation-timing-function`, `animation-delay`, `animation-iteration-count`, `animation-direction`, `animation-fill-mode`, and `animation-play-state`.

**Syntax**: `<single-animation>#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25219

___

### WebkitAnimationDelay

• `Optional` **WebkitAnimationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24314

___

### WebkitAnimationDirection

• `Optional` **WebkitAnimationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24322

___

### WebkitAnimationDuration

• `Optional` **WebkitAnimationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24330

___

### WebkitAnimationFillMode

• `Optional` **WebkitAnimationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationFillMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24338

___

### WebkitAnimationIterationCount

• `Optional` **WebkitAnimationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationIterationCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24346

___

### WebkitAnimationName

• `Optional` **WebkitAnimationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationName](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24354

___

### WebkitAnimationPlayState

• `Optional` **WebkitAnimationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationPlayState](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24362

___

### WebkitAnimationTimingFunction

• `Optional` **WebkitAnimationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAnimationTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitanimationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24370

___

### WebkitAppearance

• `Optional` **WebkitAppearance**: [`WebkitAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#webkitappearanceproperty) \| [`WebkitAppearanceProperty`](../modules/akashaproject_design_system._internal_.md#webkitappearanceproperty)[]

The **`-moz-appearance`** CSS property is used in Gecko (Firefox) to display an element using platform-native styling based on the operating system's theme.

**Syntax**: `none | button | button-bevel | caret | checkbox | default-button | inner-spin-button | listbox | listitem | media-controls-background | media-controls-fullscreen-background | media-current-time-display | media-enter-fullscreen-button | media-exit-fullscreen-button | media-fullscreen-button | media-mute-button | media-overlay-play-button | media-play-button | media-seek-back-button | media-seek-forward-button | media-slider | media-sliderthumb | media-time-remaining-display | media-toggle-closed-captions-button | media-volume-slider | media-volume-slider-container | media-volume-sliderthumb | menulist | menulist-button | menulist-text | menulist-textfield | meter | progress-bar | progress-bar-value | push-button | radio | searchfield | searchfield-cancel-button | searchfield-decoration | searchfield-results-button | searchfield-results-decoration | slider-horizontal | slider-vertical | sliderthumb-horizontal | sliderthumb-vertical | square-button | textarea | textfield | -apple-pay-button`

**Initial value**: `none` (but this value is overridden in the user agent CSS)

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitAppearance](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitappearance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24378

___

### WebkitBackdropFilter

• `Optional` **WebkitBackdropFilter**: `string` \| `string`[]

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBackdropFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackdropfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24386

___

### WebkitBackfaceVisibility

• `Optional` **WebkitBackfaceVisibility**: [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty) \| [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty)[]

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBackfaceVisibility](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackfacevisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24394

___

### WebkitBackgroundClip

• `Optional` **WebkitBackgroundClip**: `string` \| `string`[]

The **`background-clip`** CSS property sets whether an element's background `<color>` or `<image>` extends underneath its border.

**Syntax**: `<box>#`

**Initial value**: `border-box`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBackgroundClip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24402

___

### WebkitBackgroundOrigin

• `Optional` **WebkitBackgroundOrigin**: `string` \| `string`[]

The **`background-origin`** CSS property sets the _background positioning area_. In other words, it sets the origin position of an image set with the `background-image` property.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBackgroundOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24410

___

### WebkitBackgroundSize

• `Optional` **WebkitBackgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBackgroundSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbackgroundsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24418

___

### WebkitBorderBefore

• `Optional` **WebkitBorderBefore**: [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\> \| [`WebkitBorderBeforeProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforeproperty)<`TLength`\>[]

The **`-webkit-border-before`** CSS property is a shorthand property for setting the individual logical block start border property values in a single place in the style sheet.

**Syntax**: `<'border-width'> || <'border-style'> || <color>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBefore](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbefore)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25225

___

### WebkitBorderBeforeColor

• `Optional` **WebkitBorderBeforeColor**: `string` \| `string`[]

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBeforeColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24424

___

### WebkitBorderBeforeStyle

• `Optional` **WebkitBorderBeforeStyle**: `string` \| `string`[]

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBeforeStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24430

___

### WebkitBorderBeforeWidth

• `Optional` **WebkitBorderBeforeWidth**: [`WebkitBorderBeforeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidthproperty)<`TLength`\> \| [`WebkitBorderBeforeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkitborderbeforewidthproperty)<`TLength`\>[]

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBeforeWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbeforewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24436

___

### WebkitBorderBottomLeftRadius

• `Optional` **WebkitBorderBottomLeftRadius**: [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\> \| [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\>[]

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBottomLeftRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbottomleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24444

___

### WebkitBorderBottomRightRadius

• `Optional` **WebkitBorderBottomRightRadius**: [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\> \| [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\>[]

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderBottomRightRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderbottomrightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24452

___

### WebkitBorderImage

• `Optional` **WebkitBorderImage**: [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty) \| [`BorderImageProperty`](../modules/akashaproject_design_system._internal_.md#borderimageproperty)[]

The **`border-image`** CSS property draws an image in place of an element's `border-style`.

**Syntax**: `<'border-image-source'> || <'border-image-slice'> [ / <'border-image-width'> | / <'border-image-width'>? / <'border-image-outset'> ]? || <'border-image-repeat'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25231

___

### WebkitBorderImageSlice

• `Optional` **WebkitBorderImageSlice**: [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty) \| [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty)[]

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderImageSlice](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderimageslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24460

___

### WebkitBorderRadius

• `Optional` **WebkitBorderRadius**: [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\> \| [`BorderRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderradiusproperty)<`TLength`\>[]

The **`border-radius`** CSS property rounds the corners of an element's outer border edge. You can set a single radius to make circular corners, or two radii to make elliptical corners.

**Syntax**: `<length-percentage>{1,4} [ / <length-percentage>{1,4} ]?`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitborderradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25237

___

### WebkitBorderTopLeftRadius

• `Optional` **WebkitBorderTopLeftRadius**: [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\> \| [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\>[]

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderTopLeftRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbordertopleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24468

___

### WebkitBorderTopRightRadius

• `Optional` **WebkitBorderTopRightRadius**: [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\> \| [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\>[]

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBorderTopRightRadius](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitbordertoprightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24476

___

### WebkitBoxAlign

• `Optional` **WebkitBoxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26262

___

### WebkitBoxDecorationBreak

• `Optional` **WebkitBoxDecorationBreak**: [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty) \| [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty)[]

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBoxDecorationBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxdecorationbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24484

___

### WebkitBoxDirection

• `Optional` **WebkitBoxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26272

___

### WebkitBoxFlex

• `Optional` **WebkitBoxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26282

___

### WebkitBoxFlexGroup

• `Optional` **WebkitBoxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxflexgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26292

___

### WebkitBoxLines

• `Optional` **WebkitBoxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26302

___

### WebkitBoxOrdinalGroup

• `Optional` **WebkitBoxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxordinalgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26312

___

### WebkitBoxOrient

• `Optional` **WebkitBoxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26322

___

### WebkitBoxPack

• `Optional` **WebkitBoxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitBoxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitboxpack)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26332

___

### WebkitBoxReflect

• `Optional` **WebkitBoxReflect**: [`WebkitBoxReflectProperty`](../modules/akashaproject_design_system._internal_.md#webkitboxreflectproperty)<`TLength`\> \| [`WebkitBoxReflectProperty`](../modules/akashaproject_design_system._internal_.md#webkitboxreflectproperty)<`TLength`\>[]

The **`-webkit-box-reflect`** CSS property lets you reflect the content of an element in one specific direction.

**Syntax**: `[ above | below | right | left ]? <length>? <image>?`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBoxReflect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxreflect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24492

___

### WebkitBoxShadow

• `Optional` **WebkitBoxShadow**: `string` \| `string`[]

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBoxShadow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24500

___

### WebkitBoxSizing

• `Optional` **WebkitBoxSizing**: [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty) \| [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty)[]

The **`box-sizing`** CSS property defines how the user agent should calculate the total width and height of an element.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitBoxSizing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitboxsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24508

___

### WebkitClipPath

• `Optional` **WebkitClipPath**: `string` \| `string`[]

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitClipPath](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitclippath)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24516

___

### WebkitColumnCount

• `Optional` **WebkitColumnCount**: [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty) \| [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty)[]

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnCount](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumncount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24524

___

### WebkitColumnFill

• `Optional` **WebkitColumnFill**: [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty) \| [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty)[]

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnFill](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnfill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24532

___

### WebkitColumnGap

• `Optional` **WebkitColumnGap**: [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\> \| [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `normal | <length-percentage>`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnGap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24540

___

### WebkitColumnRule

• `Optional` **WebkitColumnRule**: [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\> \| [`ColumnRuleProperty`](../modules/akashaproject_design_system._internal_.md#columnruleproperty)<`TLength`\>[]

The **`column-rule`** CSS property sets the width, style, and color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'column-rule-width'> || <'column-rule-style'> || <'column-rule-color'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnRule](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25243

___

### WebkitColumnRuleColor

• `Optional` **WebkitColumnRuleColor**: `string` \| `string`[]

The **`column-rule-color`** CSS property sets the color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnRuleColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24548

___

### WebkitColumnRuleStyle

• `Optional` **WebkitColumnRuleStyle**: `string` \| `string`[]

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnRuleStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24556

___

### WebkitColumnRuleWidth

• `Optional` **WebkitColumnRuleWidth**: [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\> \| [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\>[]

The **`column-rule-width`** CSS property sets the width of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnRuleWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnrulewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24564

___

### WebkitColumnSpan

• `Optional` **WebkitColumnSpan**: [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty) \| [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty)[]

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnSpan](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnspan)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24572

___

### WebkitColumnWidth

• `Optional` **WebkitColumnWidth**: [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\> \| [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\>[]

The **`column-width`** CSS property specifies the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumnWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumnwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24580

___

### WebkitColumns

• `Optional` **WebkitColumns**: [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\> \| [`ColumnsProperty`](../modules/akashaproject_design_system._internal_.md#columnsproperty)<`TLength`\>[]

The **`columns`** CSS property sets the column width and column count of an element.

**Syntax**: `<'column-width'> || <'column-count'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25249

___

### WebkitFilter

• `Optional` **WebkitFilter**: `string` \| `string`[]

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24588

___

### WebkitFlex

• `Optional` **WebkitFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlex](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25255

___

### WebkitFlexBasis

• `Optional` **WebkitFlexBasis**: [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\> \| [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\>[]

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexBasis](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexbasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24596

___

### WebkitFlexDirection

• `Optional` **WebkitFlexDirection**: [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty) \| [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty)[]

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24604

___

### WebkitFlexFlow

• `Optional` **WebkitFlexFlow**: `string` \| `string`[]

The **`flex-flow`** CSS property is a shorthand property for `flex-direction` and `flex-wrap` properties.

**Syntax**: `<'flex-direction'> || <'flex-wrap'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexFlow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25261

___

### WebkitFlexGrow

• `Optional` **WebkitFlexGrow**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-grow`** CSS property sets how much of the available space in the flex container should be assigned to that item (the flex grow factor). If all sibling items have the same flex grow factor, then all items will receive the same share of available space, otherwise it is distributed according to the ratio defined by the different flex grow factors.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexGrow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexgrow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24612

___

### WebkitFlexShrink

• `Optional` **WebkitFlexShrink**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexShrink](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexshrink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24620

___

### WebkitFlexWrap

• `Optional` **WebkitFlexWrap**: [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty) \| [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty)[]

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFlexWrap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitflexwrap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24628

___

### WebkitFontFeatureSettings

• `Optional` **WebkitFontFeatureSettings**: `string` \| `string`[]

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFontFeatureSettings](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontfeaturesettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24636

___

### WebkitFontKerning

• `Optional` **WebkitFontKerning**: [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty) \| [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty)[]

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFontKerning](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontkerning)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24644

___

### WebkitFontSmoothing

• `Optional` **WebkitFontSmoothing**: [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\> \| [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\>[]

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFontSmoothing](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontsmoothing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24652

___

### WebkitFontVariantLigatures

• `Optional` **WebkitFontVariantLigatures**: `string` \| `string`[]

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitFontVariantLigatures](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitfontvariantligatures)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24660

___

### WebkitHyphens

• `Optional` **WebkitHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkithyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24668

___

### WebkitJustifyContent

• `Optional` **WebkitJustifyContent**: `string` \| `string`[]

The CSS **`justify-content`** property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

**Syntax**: `normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ]`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitJustifyContent](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitjustifycontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24676

___

### WebkitLineBreak

• `Optional` **WebkitLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitLineBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitlinebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24684

___

### WebkitLineClamp

• `Optional` **WebkitLineClamp**: [`WebkitLineClampProperty`](../modules/akashaproject_design_system._internal_.md#webkitlineclampproperty) \| [`WebkitLineClampProperty`](../modules/akashaproject_design_system._internal_.md#webkitlineclampproperty)[]

The **`-webkit-line-clamp`** CSS property allows limiting of the contents of a block container to the specified number of lines.

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitLineClamp](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitlineclamp)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24692

___

### WebkitMarginEnd

• `Optional` **WebkitMarginEnd**: [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\> \| [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\>[]

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMarginEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmarginend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24700

___

### WebkitMarginStart

• `Optional` **WebkitMarginStart**: [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\> \| [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\>[]

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMarginStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmarginstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24708

___

### WebkitMask

• `Optional` **WebkitMask**: [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\> \| [`WebkitMaskProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskproperty)<`TLength`\>[]

The **`mask`** CSS property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `[ <mask-reference> || <position> [ / <bg-size> ]? || <repeat-style> || [ <box> | border | padding | content | text ] || [ <box> | border | padding | content ] ]#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMask](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmask)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25267

___

### WebkitMaskAttachment

• `Optional` **WebkitMaskAttachment**: `string` \| `string`[]

If a `-webkit-mask-image` is specified, `-webkit-mask-attachment` determines whether the mask image's position is fixed within the viewport, or scrolls along with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskAttachment](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskattachment)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24716

___

### WebkitMaskBoxImage

• `Optional` **WebkitMaskBoxImage**: [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty) \| [`MaskBorderProperty`](../modules/akashaproject_design_system._internal_.md#maskborderproperty)[]

The **`mask-border`** CSS property lets you create a mask along the edge of an element's border.

**Syntax**: `<'mask-border-source'> || <'mask-border-slice'> [ / <'mask-border-width'>? [ / <'mask-border-outset'> ]? ]? || <'mask-border-repeat'> || <'mask-border-mode'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25273

___

### WebkitMaskBoxImageOutset

• `Optional` **WebkitMaskBoxImageOutset**: [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\> \| [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\>[]

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImageOutset](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximageoutset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24724

___

### WebkitMaskBoxImageRepeat

• `Optional` **WebkitMaskBoxImageRepeat**: `string` \| `string`[]

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImageRepeat](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagerepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24732

___

### WebkitMaskBoxImageSlice

• `Optional` **WebkitMaskBoxImageSlice**: [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty) \| [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty)[]

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImageSlice](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximageslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24740

___

### WebkitMaskBoxImageSource

• `Optional` **WebkitMaskBoxImageSource**: `string` \| `string`[]

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImageSource](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagesource)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24748

___

### WebkitMaskBoxImageWidth

• `Optional` **WebkitMaskBoxImageWidth**: [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\> \| [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\>[]

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskBoxImageWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskboximagewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24756

___

### WebkitMaskClip

• `Optional` **WebkitMaskClip**: `string` \| `string`[]

The **`mask-clip`** CSS property determines the area, which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <box> | border | padding | content | text ]#`

**Initial value**: `border`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskClip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24764

___

### WebkitMaskComposite

• `Optional` **WebkitMaskComposite**: `string` \| `string`[]

The **`-webkit-mask-composite`** property specifies the manner in which multiple mask images applied to the same element are composited with one another. Mask images are composited in the opposite order that they are declared with the `-webkit-mask-image` property.

**Syntax**: `<composite-style>#`

**Initial value**: `source-over`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskComposite](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskcomposite)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24772

___

### WebkitMaskImage

• `Optional` **WebkitMaskImage**: `string` \| `string`[]

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskImage](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24780

___

### WebkitMaskOrigin

• `Optional` **WebkitMaskOrigin**: `string` \| `string`[]

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `[ <box> | border | padding | content ]#`

**Initial value**: `padding`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24788

___

### WebkitMaskPosition

• `Optional` **WebkitMaskPosition**: [`WebkitMaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionproperty)<`TLength`\> \| [`WebkitMaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionproperty)<`TLength`\>[]

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `0% 0%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24796

___

### WebkitMaskPositionX

• `Optional` **WebkitMaskPositionX**: [`WebkitMaskPositionXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionxproperty)<`TLength`\> \| [`WebkitMaskPositionXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionxproperty)<`TLength`\>[]

The `-webkit-mask-position-x` CSS property sets the initial horizontal position of a mask image.

**Syntax**: `[ <length-percentage> | left | center | right ]#`

**Initial value**: `0%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskPositionX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskpositionx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24804

___

### WebkitMaskPositionY

• `Optional` **WebkitMaskPositionY**: [`WebkitMaskPositionYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionyproperty)<`TLength`\> \| [`WebkitMaskPositionYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskpositionyproperty)<`TLength`\>[]

The `-webkit-mask-position-y` CSS property sets the initial vertical position of a mask image.

**Syntax**: `[ <length-percentage> | top | center | bottom ]#`

**Initial value**: `0%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskPositionY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskpositiony)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24812

___

### WebkitMaskRepeat

• `Optional` **WebkitMaskRepeat**: `string` \| `string`[]

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskRepeat](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24820

___

### WebkitMaskRepeatX

• `Optional` **WebkitMaskRepeatX**: [`WebkitMaskRepeatXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatxproperty) \| [`WebkitMaskRepeatXProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatxproperty)[]

The `-webkit-mask-repeat-x` property specifies whether and how a mask image is repeated (tiled) horizontally.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskRepeatX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeatx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24828

___

### WebkitMaskRepeatY

• `Optional` **WebkitMaskRepeatY**: [`WebkitMaskRepeatYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatyproperty) \| [`WebkitMaskRepeatYProperty`](../modules/akashaproject_design_system._internal_.md#webkitmaskrepeatyproperty)[]

The `-webkit-mask-repeat-y` property sets whether and how a mask image is repeated (tiled) vertically.

**Syntax**: `repeat | no-repeat | space | round`

**Initial value**: `repeat`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskRepeatY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaskrepeaty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24836

___

### WebkitMaskSize

• `Optional` **WebkitMaskSize**: [`WebkitMaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#webkitmasksizeproperty)<`TLength`\> \| [`WebkitMaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#webkitmasksizeproperty)<`TLength`\>[]

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaskSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmasksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24844

___

### WebkitMaxInlineSize

• `Optional` **WebkitMaxInlineSize**: [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\> \| [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\>[]

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block depending on its writing mode. It corresponds to the `max-width` or the `max-height` property depending on the value defined for `writing-mode`. If the writing mode is vertically oriented, the value of `max-inline-size` relates to the maximal height of the element, otherwise it relates to the maximal width of the element. It relates to `max-block-size`, which defines the other dimension of the element.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitMaxInlineSize](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitmaxinlinesize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24852

___

### WebkitOrder

• `Optional` **WebkitOrder**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitOrder](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitorder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24860

___

### WebkitOverflowScrolling

• `Optional` **WebkitOverflowScrolling**: [`WebkitOverflowScrollingProperty`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrollingproperty) \| [`WebkitOverflowScrollingProperty`](../modules/akashaproject_design_system._internal_.md#webkitoverflowscrollingproperty)[]

The `-webkit-overflow-scrolling` CSS property controls whether or not touch devices use momentum-based scrolling for a given element.

**Syntax**: `auto | touch`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitOverflowScrolling](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitoverflowscrolling)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24868

___

### WebkitPaddingEnd

• `Optional` **WebkitPaddingEnd**: [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\> \| [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\>[]

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitPaddingEnd](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitpaddingend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24876

___

### WebkitPaddingStart

• `Optional` **WebkitPaddingStart**: [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\> \| [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\>[]

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitPaddingStart](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitpaddingstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24884

___

### WebkitPerspective

• `Optional` **WebkitPerspective**: [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\> \| [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\>[]

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective. Each 3D element with z>0 becomes larger; each 3D-element with z<0 becomes smaller. The strength of the effect is determined by the value of this property.

**Syntax**: `none | <length>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitPerspective](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitperspective)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24892

___

### WebkitPerspectiveOrigin

• `Optional` **WebkitPerspectiveOrigin**: [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\> \| [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\>[]

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitPerspectiveOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitperspectiveorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24900

___

### WebkitPrintColorAdjust

• `Optional` **WebkitPrintColorAdjust**: [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty) \| [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty)[]

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitPrintColorAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitprintcoloradjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24908

___

### WebkitRubyPosition

• `Optional` **WebkitRubyPosition**: `string` \| `string`[]

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitRubyPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitrubyposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24916

___

### WebkitScrollSnapPointsX

• `Optional` **WebkitScrollSnapPointsX**: `string` \| `string`[]

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitScrollSnapPointsX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitscrollsnappointsx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26342

___

### WebkitScrollSnapPointsY

• `Optional` **WebkitScrollSnapPointsY**: `string` \| `string`[]

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[WebkitScrollSnapPointsY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#webkitscrollsnappointsy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26352

___

### WebkitScrollSnapType

• `Optional` **WebkitScrollSnapType**: `string` \| `string`[]

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitScrollSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitscrollsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24924

___

### WebkitShapeMargin

• `Optional` **WebkitShapeMargin**: [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\> \| [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\>[]

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitShapeMargin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitshapemargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24932

___

### WebkitTapHighlightColor

• `Optional` **WebkitTapHighlightColor**: `string` \| `string`[]

**`-webkit-tap-highlight-color`** is a non-standard CSS property that sets the color of the highlight that appears over a link while it's being tapped. The highlighting indicates to the user that their tap is being successfully recognized, and indicates which element they're tapping on.

**Syntax**: `<color>`

**Initial value**: `black`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTapHighlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittaphighlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24940

___

### WebkitTextCombine

• `Optional` **WebkitTextCombine**: `string` \| `string`[]

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextCombine](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextcombine)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24948

___

### WebkitTextDecorationColor

• `Optional` **WebkitTextDecorationColor**: `string` \| `string`[]

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextDecorationColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24956

___

### WebkitTextDecorationLine

• `Optional` **WebkitTextDecorationLine**: `string` \| `string`[]

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextDecorationLine](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24964

___

### WebkitTextDecorationSkip

• `Optional` **WebkitTextDecorationSkip**: `string` \| `string`[]

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextDecorationSkip](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationskip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24972

___

### WebkitTextDecorationStyle

• `Optional` **WebkitTextDecorationStyle**: [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty) \| [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty)[]

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextDecorationStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextdecorationstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24980

___

### WebkitTextEmphasis

• `Optional` **WebkitTextEmphasis**: `string` \| `string`[]

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextEmphasis](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25279

___

### WebkitTextEmphasisColor

• `Optional` **WebkitTextEmphasisColor**: `string` \| `string`[]

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextEmphasisColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasiscolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24988

___

### WebkitTextEmphasisPosition

• `Optional` **WebkitTextEmphasisPosition**: `string` \| `string`[]

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextEmphasisPosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasisposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24996

___

### WebkitTextEmphasisStyle

• `Optional` **WebkitTextEmphasisStyle**: `string` \| `string`[]

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextEmphasisStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextemphasisstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25004

___

### WebkitTextFillColor

• `Optional` **WebkitTextFillColor**: `string` \| `string`[]

The **`-webkit-text-fill-color`** CSS property specifies the fill color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextFillColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextfillcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25012

___

### WebkitTextOrientation

• `Optional` **WebkitTextOrientation**: [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty) \| [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty)[]

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextOrientation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextorientation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25020

___

### WebkitTextSizeAdjust

• `Optional` **WebkitTextSizeAdjust**: `string` \| `string`[]

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextSizeAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25028

___

### WebkitTextStroke

• `Optional` **WebkitTextStroke**: [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\> \| [`WebkitTextStrokeProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokeproperty)<`TLength`\>[]

The **`-webkit-text-stroke`** CSS property specifies the width and color of strokes for text characters. This is a shorthand property for the longhand properties `-webkit-text-stroke-width` and `-webkit-text-stroke-color`.

**Syntax**: `<length> || <color>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextStroke](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstroke)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25285

___

### WebkitTextStrokeColor

• `Optional` **WebkitTextStrokeColor**: `string` \| `string`[]

The **`-webkit-text-stroke-color`** CSS property specifies the stroke color of characters of text. If this property is not set, the value of the `color` property is used.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextStrokeColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstrokecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25036

___

### WebkitTextStrokeWidth

• `Optional` **WebkitTextStrokeWidth**: [`WebkitTextStrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidthproperty)<`TLength`\> \| [`WebkitTextStrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#webkittextstrokewidthproperty)<`TLength`\>[]

The **`-webkit-text-stroke-width`** CSS property specifies the width of the stroke for text.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextStrokeWidth](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextstrokewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25044

___

### WebkitTextUnderlinePosition

• `Optional` **WebkitTextUnderlinePosition**: `string` \| `string`[]

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTextUnderlinePosition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittextunderlineposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25052

___

### WebkitTouchCallout

• `Optional` **WebkitTouchCallout**: [`WebkitTouchCalloutProperty`](../modules/akashaproject_design_system._internal_.md#webkittouchcalloutproperty) \| [`WebkitTouchCalloutProperty`](../modules/akashaproject_design_system._internal_.md#webkittouchcalloutproperty)[]

The `-webkit-touch-callout` CSS property controls the display of the default callout shown when you touch and hold a touch target.

**Syntax**: `default | none`

**Initial value**: `default`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTouchCallout](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittouchcallout)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25060

___

### WebkitTransform

• `Optional` **WebkitTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransform](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25068

___

### WebkitTransformOrigin

• `Optional` **WebkitTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25076

___

### WebkitTransformStyle

• `Optional` **WebkitTransformStyle**: [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty) \| [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty)[]

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransformStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransformstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25084

___

### WebkitTransition

• `Optional` **WebkitTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25291

___

### WebkitTransitionDelay

• `Optional` **WebkitTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25092

___

### WebkitTransitionDuration

• `Optional` **WebkitTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25100

___

### WebkitTransitionProperty

• `Optional` **WebkitTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25108

___

### WebkitTransitionTimingFunction

• `Optional` **WebkitTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkittransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25116

___

### WebkitUserModify

• `Optional` **WebkitUserModify**: [`WebkitUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#webkitusermodifyproperty) \| [`WebkitUserModifyProperty`](../modules/akashaproject_design_system._internal_.md#webkitusermodifyproperty)[]

**Syntax**: `read-only | read-write | read-write-plaintext-only`

**Initial value**: `read-only`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitUserModify](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitusermodify)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25122

___

### WebkitUserSelect

• `Optional` **WebkitUserSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkituserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25130

___

### WebkitWritingMode

• `Optional` **WebkitWritingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress.

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[WebkitWritingMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#webkitwritingmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25138

___

### accentColor

• `Optional` **accentColor**: `string` \| `string`[]

The **`accent-color`** CSS property sets the color of the elements accent. An accent appears in elements such as `<input>` of `type="checkbox"`, or `type="radio"`.

**Syntax**: `auto | <color>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **93** | **92**  |   No   | **93** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/accent-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[accentColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#accentcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17629

___

### alignContent

• `Optional` **alignContent**: `string` \| `string`[]

The CSS **`align-content`** property sets how the browser distributes space between and around content items along the cross-axis of a flexbox container, and the main-axis of a grid container.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[alignContent](akashaproject_design_system._internal_.StandardPropertiesFallback.md#aligncontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17658

___

### alignItems

• `Optional` **alignItems**: `string` \| `string`[]

The CSS **`align-items`** property sets the `align-self` value on all direct children as a group. The align-self property sets the alignment of an item within its containing block. In Flexbox it controls the alignment of items on the Cross Axis, in Grid Layout it controls the alignment of items on the Block Axis within their grid area.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[alignItems](akashaproject_design_system._internal_.StandardPropertiesFallback.md#alignitems)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17687

___

### alignSelf

• `Optional` **alignSelf**: `string` \| `string`[]

The **`align-self`** CSS property aligns flex items of the current flex line overriding the `align-items` value. If any of the item's cross-axis margin is set to `auto`, then `align-self` is ignored. In Grid layout `align-self` aligns the item inside the grid area.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[alignSelf](akashaproject_design_system._internal_.StandardPropertiesFallback.md#alignself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17716

___

### alignTracks

• `Optional` **alignTracks**: `string` \| `string`[]

The **`align-tracks`** CSS property sets the alignment in the masonry axis for grid containers that have masonry in their block axis.

**Syntax**: `[ normal | <baseline-position> | <content-distribution> | <overflow-position>? <content-position> ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   n/a   |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/align-tracks

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[alignTracks](akashaproject_design_system._internal_.StandardPropertiesFallback.md#aligntracks)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17730

___

### alignmentBaseline

• `Optional` **alignmentBaseline**: [`AlignmentBaselineProperty`](../modules/akashaproject_design_system._internal_.md#alignmentbaselineproperty) \| [`AlignmentBaselineProperty`](../modules/akashaproject_design_system._internal_.md#alignmentbaselineproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[alignmentBaseline](akashaproject_design_system._internal_.SvgPropertiesFallback.md#alignmentbaseline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26356

___

### all

• `Optional` **all**: [`Globals`](../modules/akashaproject_design_system._internal_.md#globals) \| [`Globals`](../modules/akashaproject_design_system._internal_.md#globals)[]

The `**all**` CSS shorthand property sets all of an element's properties (other than `unicode-bidi` and `direction`) to their initial or inherited values, or to the values specified in another stylesheet origin.

**Syntax**: `initial | inherit | unset | revert`

**Initial value**: There is no practical initial value for it.

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **37** | **27**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/all

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[all](akashaproject_design_system._internal_.StandardPropertiesFallback.md#all)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22769

___

### animationDelay

• `Optional` **animationDelay**: `string` \| `string`[]

The **`animation-delay`** CSS property sets when an animation starts. The animation can start later, immediately from its beginning, or immediately and partway through the animation.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-delay

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationDelay](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationdelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17745

___

### animationDirection

• `Optional` **animationDirection**: `string` \| `string`[]

The **`animation-direction`** CSS property sets whether an animation should play forwards, backwards, or alternating back and forth.

**Syntax**: `<single-animation-direction>#`

**Initial value**: `normal`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-direction

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationDirection](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17760

___

### animationDuration

• `Optional` **animationDuration**: `string` \| `string`[]

The **`animation-duration`** CSS property sets the length of time that an animation takes to complete one cycle.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-duration

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationDuration](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17775

___

### animationFillMode

• `Optional` **animationFillMode**: `string` \| `string`[]

The **`animation-fill-mode`** CSS property sets how a CSS animation applies styles to its target before and after its execution.

**Syntax**: `<single-animation-fill-mode>#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 5 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-fill-mode

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationFillMode](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationfillmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17790

___

### animationIterationCount

• `Optional` **animationIterationCount**: [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty) \| [`AnimationIterationCountProperty`](../modules/akashaproject_design_system._internal_.md#animationiterationcountproperty)[]

The **`animation-iteration-count`** CSS property sets the number of times an animation cycle should be played before stopping.

**Syntax**: `<single-animation-iteration-count>#`

**Initial value**: `1`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-iteration-count

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationIterationCount](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationiterationcount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17805

___

### animationName

• `Optional` **animationName**: `string` \| `string`[]

The **`animation-name`** CSS property sets one or more animations to apply to an element. Each name is an `@keyframes` at-rule that sets the property values for the animation sequence.

**Syntax**: `[ none | <keyframes-name> ]#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-name

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationName](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationname)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17820

___

### animationPlayState

• `Optional` **animationPlayState**: `string` \| `string`[]

The **`animation-play-state`** CSS property sets whether an animation is running or paused.

**Syntax**: `<single-animation-play-state>#`

**Initial value**: `running`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-play-state

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationPlayState](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationplaystate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17835

___

### animationTimingFunction

• `Optional` **animationTimingFunction**: `string` \| `string`[]

The `**animation-timing-function**` CSS property sets how an animation progresses through the duration of each cycle.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **43**  | **16**  |  **9**  | **12** | **10** |
| 3 _-x-_ | 5 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/animation-timing-function

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[animationTimingFunction](akashaproject_design_system._internal_.StandardPropertiesFallback.md#animationtimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17850

___

### appearance

• `Optional` **appearance**: [`AppearanceProperty`](../modules/akashaproject_design_system._internal_.md#appearanceproperty) \| [`AppearanceProperty`](../modules/akashaproject_design_system._internal_.md#appearanceproperty)[]

The **`-moz-appearance`** CSS property is used in Gecko (Firefox) to display an element using platform-native styling based on the operating system's theme.

**Syntax**: `none | auto | textfield | menulist-button | <compat-auto>`

**Initial value**: `auto`

| Chrome  | Firefox |   Safari    |   Edge   | IE  |
| :-----: | :-----: | :---------: | :------: | :-: |
| **84**  | **80**  | **3** _-x-_ |  **84**  | No  |
| 1 _-x-_ | 1 _-x-_ |             | 12 _-x-_ |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/appearance

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[appearance](akashaproject_design_system._internal_.StandardPropertiesFallback.md#appearance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17865

___

### aspectRatio

• `Optional` **aspectRatio**: `string` \| `string`[]

The **`aspect-ratio`**    CSS property sets a _**preferred aspect ratio**_ for the box, which will be used in the calculation of auto sizes and some other layout functions.

**Syntax**: `auto | <ratio>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **88** | **89**  | **15** | **88** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/aspect-ratio

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[aspectRatio](akashaproject_design_system._internal_.StandardPropertiesFallback.md#aspectratio)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17879

___

### azimuth

• `Optional` **azimuth**: `string` \| `string`[]

In combination with `elevation`, the **`azimuth`** CSS property enables different audio sources to be positioned spatially for aural presentation. This is important in that it provides a natural way to tell several voices apart, as each can be positioned to originate at a different location on the sound stage. Stereo output produce a lateral sound stage, while binaural headphones and multi-speaker setups allow for a fully three-dimensional stage.

**Syntax**: `<angle> | [ [ left-side | far-left | left | center-left | center | center-right | right | far-right | right-side ] || behind ] | leftwards | rightwards`

**Initial value**: `center`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[azimuth](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#azimuth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25306

___

### backdropFilter

• `Optional` **backdropFilter**: `string` \| `string`[]

The **`backdrop-filter`** CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything _behind_ the element, to see the effect you must make the element or its background at least partially transparent.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

| Chrome | Firefox |   Safari    |  Edge  | IE  |
| :----: | :-----: | :---------: | :----: | :-: |
| **76** |   n/a   | **9** _-x-_ | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/backdrop-filter

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backdropFilter](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backdropfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17893

___

### backfaceVisibility

• `Optional` **backfaceVisibility**: [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty) \| [`BackfaceVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#backfacevisibilityproperty)[]

The **`backface-visibility`** CSS property sets whether the back face of an element is visible when turned towards the user.

**Syntax**: `visible | hidden`

**Initial value**: `visible`

|  Chrome  | Firefox  |    Safari     |  Edge  |   IE   |
| :------: | :------: | :-----------: | :----: | :----: |
|  **36**  |  **16**  | **5.1** _-x-_ | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ |               |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/backface-visibility

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backfaceVisibility](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backfacevisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17908

___

### background

• `Optional` **background**: [`BackgroundProperty`](../modules/akashaproject_design_system._internal_.md#backgroundproperty)<`TLength`\> \| [`BackgroundProperty`](../modules/akashaproject_design_system._internal_.md#backgroundproperty)<`TLength`\>[]

The **`background`** shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.

**Syntax**: `[ <bg-layer> , ]* <final-bg-layer>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[background](akashaproject_design_system._internal_.StandardPropertiesFallback.md#background)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22781

___

### backgroundAttachment

• `Optional` **backgroundAttachment**: `string` \| `string`[]

The **`background-attachment`** CSS property sets whether a background image's position is fixed within the viewport, or scrolls with its containing block.

**Syntax**: `<attachment>#`

**Initial value**: `scroll`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-attachment

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundAttachment](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundattachment)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17922

___

### backgroundBlendMode

• `Optional` **backgroundBlendMode**: `string` \| `string`[]

The **`background-blend-mode`** CSS property sets how an element's background images should blend with each other and with the element's background color.

**Syntax**: `<blend-mode>#`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **35** | **30**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-blend-mode

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundBlendMode](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundblendmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17936

___

### backgroundClip

• `Optional` **backgroundClip**: `string` \| `string`[]

The **`background-clip`** CSS property sets whether an element's background `<color>` or `<image>` extends underneath its border.

**Syntax**: `<box>#`

**Initial value**: `border-box`

| Chrome | Firefox |   Safari    |  Edge  |  IE   |
| :----: | :-----: | :---------: | :----: | :---: |
| **1**  |  **4**  | **3** _-x-_ | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-clip

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundClip](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17950

___

### backgroundColor

• `Optional` **backgroundColor**: `string` \| `string`[]

The **`background-color`** CSS property sets the background color of an element.

**Syntax**: `<color>`

**Initial value**: `transparent`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17964

___

### backgroundImage

• `Optional` **backgroundImage**: `string` \| `string`[]

The **`background-image`** CSS property sets one or more background images on an element.

**Syntax**: `<bg-image>#`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-image

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundImage](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17978

___

### backgroundOrigin

• `Optional` **backgroundOrigin**: `string` \| `string`[]

The **`background-origin`** CSS property sets the _background positioning area_. In other words, it sets the origin position of an image set with the `background-image` property.

**Syntax**: `<box>#`

**Initial value**: `padding-box`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **4**  | **3**  | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-origin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundOrigin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:17992

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22795

___

### backgroundPositionX

• `Optional` **backgroundPositionX**: [`BackgroundPositionXProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionxproperty)<`TLength`\> \| [`BackgroundPositionXProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionxproperty)<`TLength`\>[]

The **`background-position-x`** CSS property sets the initial horizontal position for each background image. The position is relative to the position layer set by `background-origin`.

**Syntax**: `[ center | [ [ left | right | x-start | x-end ]? <length-percentage>? ]! ]#`

**Initial value**: `left`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-x

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundPositionX](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundpositionx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18006

___

### backgroundPositionY

• `Optional` **backgroundPositionY**: [`BackgroundPositionYProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionyproperty)<`TLength`\> \| [`BackgroundPositionYProperty`](../modules/akashaproject_design_system._internal_.md#backgroundpositionyproperty)<`TLength`\>[]

The **`background-position-y`** CSS property sets the initial vertical position, relative to the background position layer defined by `background-origin`, for each defined background image.

**Syntax**: `[ center | [ [ top | bottom | y-start | y-end ]? <length-percentage>? ]! ]#`

**Initial value**: `top`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **49**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-position-y

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundPositionY](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundpositiony)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18020

___

### backgroundRepeat

• `Optional` **backgroundRepeat**: `string` \| `string`[]

The **`background-repeat`** CSS property sets how background images are repeated. A background image can be repeated along the horizontal and vertical axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `repeat`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-repeat

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundRepeat](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundrepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18034

___

### backgroundSize

• `Optional` **backgroundSize**: [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\> \| [`BackgroundSizeProperty`](../modules/akashaproject_design_system._internal_.md#backgroundsizeproperty)<`TLength`\>[]

The **`background-size`** CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

**Syntax**: `<bg-size>#`

**Initial value**: `auto auto`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **3**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/background-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[backgroundSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#backgroundsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18049

___

### baselineShift

• `Optional` **baselineShift**: [`BaselineShiftProperty`](../modules/akashaproject_design_system._internal_.md#baselineshiftproperty)<`TLength`\> \| [`BaselineShiftProperty`](../modules/akashaproject_design_system._internal_.md#baselineshiftproperty)<`TLength`\>[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[baselineShift](akashaproject_design_system._internal_.SvgPropertiesFallback.md#baselineshift)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26357

___

### blockOverflow

• `Optional` **blockOverflow**: `string` \| `string`[]

**Syntax**: `clip | ellipsis | <string>`

**Initial value**: `clip`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[blockOverflow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#blockoverflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18055

___

### blockSize

• `Optional` **blockSize**: [`BlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#blocksizeproperty)<`TLength`\> \| [`BlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#blocksizeproperty)<`TLength`\>[]

The **`block-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/block-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[blockSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#blocksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18069

___

### border

• `Optional` **border**: [`BorderProperty`](../modules/akashaproject_design_system._internal_.md#borderproperty)<`TLength`\> \| [`BorderProperty`](../modules/akashaproject_design_system._internal_.md#borderproperty)<`TLength`\>[]

The **`border`** CSS property sets an element's border. It's a shorthand for `border-width`, `border-style`, and `border-color`.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[border](akashaproject_design_system._internal_.StandardPropertiesFallback.md#border)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22819

___

### borderBlockColor

• `Optional` **borderBlockColor**: `string` \| `string`[]

The **`border-block-color`** CSS property defines the color of the logical block borders of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color` and `border-bottom-color`, or `border-right-color` and `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>{1,2}`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18083

___

### borderBlockEnd

• `Optional` **borderBlockEnd**: [`BorderBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendproperty)<`TLength`\> \| [`BorderBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendproperty)<`TLength`\>[]

The **`border-block-end`** CSS property is a shorthand property for setting the individual logical block-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22831

___

### borderBlockEndColor

• `Optional` **borderBlockEndColor**: `string` \| `string`[]

The **`border-block-end-color`** CSS property defines the color of the logical block-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockEndColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockendcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18097

___

### borderBlockEndStyle

• `Optional` **borderBlockEndStyle**: [`BorderBlockEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendstyleproperty) \| [`BorderBlockEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendstyleproperty)[]

The **`border-block-end-style`** CSS property defines the style of the logical block end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockEndStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockendstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18111

___

### borderBlockEndWidth

• `Optional` **borderBlockEndWidth**: [`BorderBlockEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendwidthproperty)<`TLength`\> \| [`BorderBlockEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockendwidthproperty)<`TLength`\>[]

The **`border-block-end-width`** CSS property defines the width of the logical block-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-end-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockEndWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockendwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18125

___

### borderBlockStart

• `Optional` **borderBlockStart**: [`BorderBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartproperty)<`TLength`\> \| [`BorderBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartproperty)<`TLength`\>[]

The **`border-block-start`** CSS property is a shorthand property for setting the individual logical block-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22843

___

### borderBlockStartColor

• `Optional` **borderBlockStartColor**: `string` \| `string`[]

The **`border-block-start-color`** CSS property defines the color of the logical block-start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockStartColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockstartcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18139

___

### borderBlockStartStyle

• `Optional` **borderBlockStartStyle**: [`BorderBlockStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartstyleproperty) \| [`BorderBlockStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartstyleproperty)[]

The **`border-block-start-style`** CSS property defines the style of the logical block start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockStartStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockstartstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18153

___

### borderBlockStartWidth

• `Optional` **borderBlockStartWidth**: [`BorderBlockStartWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartwidthproperty)<`TLength`\> \| [`BorderBlockStartWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstartwidthproperty)<`TLength`\>[]

The **`border-block-start-width`** CSS property defines the width of the logical block-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-start-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockStartWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockstartwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18167

___

### borderBlockStyle

• `Optional` **borderBlockStyle**: [`BorderBlockStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstyleproperty) \| [`BorderBlockStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderblockstyleproperty)[]

The **`border-block-style`** CSS property defines the style of the logical block borders of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style` and `border-bottom-style`, or `border-left-style` and `border-right-style` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18181

___

### borderBlockWidth

• `Optional` **borderBlockWidth**: [`BorderBlockWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockwidthproperty)<`TLength`\> \| [`BorderBlockWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderblockwidthproperty)<`TLength`\>[]

The **`border-block-width`** CSS property defines the width of the logical block borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-block-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBlockWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderblockwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18195

___

### borderBottom

• `Optional` **borderBottom**: [`BorderBottomProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomproperty)<`TLength`\> \| [`BorderBottomProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomproperty)<`TLength`\>[]

The **`border-bottom`** CSS property is a shorthand that sets the values of `border-bottom-width`, `border-bottom-style` and `border-bottom-color`. These properties set an element's bottom border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22855

___

### borderBottomColor

• `Optional` **borderBottomColor**: `string` \| `string`[]

The **`border-bottom-color`** CSS property sets the color of an element's bottom border. It can also be set with the shorthand CSS properties `border-color` or `border-bottom`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottomColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottomcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18209

___

### borderBottomLeftRadius

• `Optional` **borderBottomLeftRadius**: [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\> \| [`BorderBottomLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomleftradiusproperty)<`TLength`\>[]

The **`border-bottom-left-radius`** CSS property rounds the bottom-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-left-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottomLeftRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottomleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18224

___

### borderBottomRightRadius

• `Optional` **borderBottomRightRadius**: [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\> \| [`BorderBottomRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomrightradiusproperty)<`TLength`\>[]

The **`border-bottom-right-radius`** CSS property rounds the bottom-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-right-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottomRightRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottomrightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18239

___

### borderBottomStyle

• `Optional` **borderBottomStyle**: [`BorderBottomStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomstyleproperty) \| [`BorderBottomStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomstyleproperty)[]

The **`border-bottom-style`** CSS property sets the line style of an element's bottom `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottomStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottomstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18253

___

### borderBottomWidth

• `Optional` **borderBottomWidth**: [`BorderBottomWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomwidthproperty)<`TLength`\> \| [`BorderBottomWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderbottomwidthproperty)<`TLength`\>[]

The **`border-bottom-width`** CSS property sets the width of the bottom border of a box.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-bottom-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderBottomWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderbottomwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18267

___

### borderCollapse

• `Optional` **borderCollapse**: [`BorderCollapseProperty`](../modules/akashaproject_design_system._internal_.md#bordercollapseproperty) \| [`BorderCollapseProperty`](../modules/akashaproject_design_system._internal_.md#bordercollapseproperty)[]

The **`border-collapse`** CSS property sets whether cells inside a `<table>` have shared or separate borders.

**Syntax**: `collapse | separate`

**Initial value**: `separate`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-collapse

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderCollapse](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordercollapse)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18281

___

### borderColor

• `Optional` **borderColor**: `string` \| `string`[]

The **`border-color`** shorthand CSS property sets the color of all sides of an element's border.

**Syntax**: `<color>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordercolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22867

___

### borderEndEndRadius

• `Optional` **borderEndEndRadius**: [`BorderEndEndRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderendendradiusproperty)<`TLength`\> \| [`BorderEndEndRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderendendradiusproperty)<`TLength`\>[]

The **`border-end-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on on the element's `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-end-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderEndEndRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderendendradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18295

___

### borderEndStartRadius

• `Optional` **borderEndStartRadius**: [`BorderEndStartRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderendstartradiusproperty)<`TLength`\> \| [`BorderEndStartRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderendstartradiusproperty)<`TLength`\>[]

The **`border-end-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-end-start-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderEndStartRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderendstartradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18309

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImage](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22880

___

### borderImageOutset

• `Optional` **borderImageOutset**: [`BorderImageOutsetProperty`](../modules/akashaproject_design_system._internal_.md#borderimageoutsetproperty)<`TLength`\> \| [`BorderImageOutsetProperty`](../modules/akashaproject_design_system._internal_.md#borderimageoutsetproperty)<`TLength`\>[]

The **`border-image-outset`** CSS property sets the distance by which an element's border image is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-outset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImageOutset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimageoutset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18323

___

### borderImageRepeat

• `Optional` **borderImageRepeat**: `string` \| `string`[]

The **`border-image-repeat`** CSS property defines how the edge regions of a source image are adjusted to fit the dimensions of an element's border image.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-repeat

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImageRepeat](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimagerepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18337

___

### borderImageSlice

• `Optional` **borderImageSlice**: [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty) \| [`BorderImageSliceProperty`](../modules/akashaproject_design_system._internal_.md#borderimagesliceproperty)[]

The **`border-image-slice`** CSS property divides the image specified by `border-image-source` into regions. These regions form the components of an element's border image.

**Syntax**: `<number-percentage>{1,4} && fill?`

**Initial value**: `100%`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-slice

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImageSlice](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimageslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18351

___

### borderImageSource

• `Optional` **borderImageSource**: `string` \| `string`[]

The **`border-image-source`** CSS property sets the source image used to create an element's border image.

**Syntax**: `none | <image>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **15**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-source

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImageSource](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimagesource)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18365

___

### borderImageWidth

• `Optional` **borderImageWidth**: [`BorderImageWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderimagewidthproperty)<`TLength`\> \| [`BorderImageWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderimagewidthproperty)<`TLength`\>[]

The **`border-image-width`** CSS property sets the width of an element's border image.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `1`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **15** | **13**  | **6**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-image-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderImageWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderimagewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18379

___

### borderInline

• `Optional` **borderInline**: [`BorderInlineProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineproperty)<`TLength`\> \| [`BorderInlineProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineproperty)<`TLength`\>[]

The **`border-inline`** CSS property is a shorthand property for setting the individual logical inline border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22892

___

### borderInlineColor

• `Optional` **borderInlineColor**: `string` \| `string`[]

The **`border-inline-color`** CSS property defines the color of the logical inline borders of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color` and `border-bottom-color`, or `border-right-color` and `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>{1,2}`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18393

___

### borderInlineEnd

• `Optional` **borderInlineEnd**: [`BorderInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendproperty)<`TLength`\> \| [`BorderInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendproperty)<`TLength`\>[]

The **`border-inline-end`** CSS property is a shorthand property for setting the individual logical inline-end border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22904

___

### borderInlineEndColor

• `Optional` **borderInlineEndColor**: `string` \| `string`[]

The **`border-inline-end-color`** CSS property defines the color of the logical inline-end border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-color)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineEndColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlineendcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18408

___

### borderInlineEndStyle

• `Optional` **borderInlineEndStyle**: [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty) \| [`BorderInlineEndStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendstyleproperty)[]

The **`border-inline-end-style`** CSS property defines the style of the logical inline end border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-style)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineEndStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlineendstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18423

___

### borderInlineEndWidth

• `Optional` **borderInlineEndWidth**: [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\> \| [`BorderInlineEndWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlineendwidthproperty)<`TLength`\>[]

The **`border-inline-end-width`** CSS property defines the width of the logical inline-end border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome |           Firefox           |  Safari  |  Edge  | IE  |
| :----: | :-------------------------: | :------: | :----: | :-: |
| **69** |           **41**            | **12.1** | **79** | No  |
|        | 3 _(-moz-border-end-width)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-end-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineEndWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlineendwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18438

___

### borderInlineStart

• `Optional` **borderInlineStart**: [`BorderInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartproperty)<`TLength`\> \| [`BorderInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartproperty)<`TLength`\>[]

The **`border-inline-start`** CSS property is a shorthand property for setting the individual logical inline-start border property values in a single place in the style sheet.

**Syntax**: `<'border-top-width'> || <'border-top-style'> || <color>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22916

___

### borderInlineStartColor

• `Optional` **borderInlineStartColor**: `string` \| `string`[]

The **`border-inline-start-color`** CSS property defines the color of the logical inline start border of an element, which maps to a physical border color depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-color`, `border-right-color`, `border-bottom-color`, or `border-left-color` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-color'>`

**Initial value**: `currentcolor`

| Chrome |            Firefox            |  Safari  |  Edge  | IE  |
| :----: | :---------------------------: | :------: | :----: | :-: |
| **69** |            **41**             | **12.1** | **79** | No  |
|        | 3 _(-moz-border-start-color)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineStartColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinestartcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18453

___

### borderInlineStartStyle

• `Optional` **borderInlineStartStyle**: [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty) \| [`BorderInlineStartStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartstyleproperty)[]

The **`border-inline-start-style`** CSS property defines the style of the logical inline start border of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style`, `border-right-style`, `border-bottom-style`, or `border-left-style` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome |            Firefox            |  Safari  |  Edge  | IE  |
| :----: | :---------------------------: | :------: | :----: | :-: |
| **69** |            **41**             | **12.1** | **79** | No  |
|        | 3 _(-moz-border-start-style)_ |          |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineStartStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinestartstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18468

___

### borderInlineStartWidth

• `Optional` **borderInlineStartWidth**: [`BorderInlineStartWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartwidthproperty)<`TLength`\> \| [`BorderInlineStartWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestartwidthproperty)<`TLength`\>[]

The **`border-inline-start-width`** CSS property defines the width of the logical inline-start border of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width`, `border-right-width`, `border-bottom-width`, or `border-left-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-start-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineStartWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinestartwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18482

___

### borderInlineStyle

• `Optional` **borderInlineStyle**: [`BorderInlineStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestyleproperty) \| [`BorderInlineStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinestyleproperty)[]

The **`border-inline-style`** CSS property defines the style of the logical inline borders of an element, which maps to a physical border style depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-style` and `border-bottom-style`, or `border-left-style` and `border-right-style` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-style'>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18496

___

### borderInlineWidth

• `Optional` **borderInlineWidth**: [`BorderInlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinewidthproperty)<`TLength`\> \| [`BorderInlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderinlinewidthproperty)<`TLength`\>[]

The **`border-inline-width`** CSS property defines the width of the logical inline borders of an element, which maps to a physical border width depending on the element's writing mode, directionality, and text orientation. It corresponds to the `border-top-width` and `border-bottom-width`, or `border-left-width`, and `border-right-width` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'border-top-width'>`

**Initial value**: `medium`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-inline-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderInlineWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderinlinewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18510

___

### borderLeft

• `Optional` **borderLeft**: [`BorderLeftProperty`](../modules/akashaproject_design_system._internal_.md#borderleftproperty)<`TLength`\> \| [`BorderLeftProperty`](../modules/akashaproject_design_system._internal_.md#borderleftproperty)<`TLength`\>[]

The **`border-left`** CSS property is a shorthand that sets the values of `border-left-width`, `border-left-style` and `border-left-color`. These properties set an element's left border.

**Syntax**: `<line-width> || <line-style> || <color>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22928

___

### borderLeftColor

• `Optional` **borderLeftColor**: `string` \| `string`[]

The **`border-left-color`** CSS property sets the color of an element's left border. It can also be set with the shorthand CSS properties `border-color` or `border-left`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderLeftColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderleftcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18524

___

### borderLeftStyle

• `Optional` **borderLeftStyle**: [`BorderLeftStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderleftstyleproperty) \| [`BorderLeftStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderleftstyleproperty)[]

The **`border-left-style`** CSS property sets the line style of an element's left `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderLeftStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderleftstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18538

___

### borderLeftWidth

• `Optional` **borderLeftWidth**: [`BorderLeftWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderleftwidthproperty)<`TLength`\> \| [`BorderLeftWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderleftwidthproperty)<`TLength`\>[]

The **`border-left-width`** CSS property sets the width of the left border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-left-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderLeftWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderleftwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18552

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderradius)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22953

___

### borderRightColor

• `Optional` **borderRightColor**: `string` \| `string`[]

The **`border-right-color`** CSS property sets the color of an element's right border. It can also be set with the shorthand CSS properties `border-color` or `border-right`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderRightColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderrightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18566

___

### borderRightStyle

• `Optional` **borderRightStyle**: [`BorderRightStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderrightstyleproperty) \| [`BorderRightStyleProperty`](../modules/akashaproject_design_system._internal_.md#borderrightstyleproperty)[]

The **`border-right-style`** CSS property sets the line style of an element's right `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderRightStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderrightstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18580

___

### borderRightWidth

• `Optional` **borderRightWidth**: [`BorderRightWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderrightwidthproperty)<`TLength`\> \| [`BorderRightWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderrightwidthproperty)<`TLength`\>[]

The **`border-right-width`** CSS property sets the width of the right border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-right-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderRightWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderrightwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18594

___

### borderSpacing

• `Optional` **borderSpacing**: [`BorderSpacingProperty`](../modules/akashaproject_design_system._internal_.md#borderspacingproperty)<`TLength`\> \| [`BorderSpacingProperty`](../modules/akashaproject_design_system._internal_.md#borderspacingproperty)<`TLength`\>[]

The **`border-spacing`** CSS property sets the distance between the borders of adjacent `<table>` cells. This property applies only when `border-collapse` is `separate`.

**Syntax**: `<length> <length>?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-spacing

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderSpacing](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderspacing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18608

___

### borderStartEndRadius

• `Optional` **borderStartEndRadius**: [`BorderStartEndRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderstartendradiusproperty)<`TLength`\> \| [`BorderStartEndRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderstartendradiusproperty)<`TLength`\>[]

The **`border-start-end-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius depending on the element's `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-end-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderStartEndRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderstartendradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18622

___

### borderStartStartRadius

• `Optional` **borderStartStartRadius**: [`BorderStartStartRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderstartstartradiusproperty)<`TLength`\> \| [`BorderStartStartRadiusProperty`](../modules/akashaproject_design_system._internal_.md#borderstartstartradiusproperty)<`TLength`\>[]

The **`border-start-start-radius`** CSS property defines a logical border radius on an element, which maps to a physical border radius that depends on the element's `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **89** | **66**  | **15** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-start-start-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderStartStartRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderstartstartradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18636

___

### borderStyle

• `Optional` **borderStyle**: `string` \| `string`[]

The **`border-style`** CSS property is a shorthand property that sets the line style for all four sides of an element's border.

**Syntax**: `<line-style>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderstyle)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22977

___

### borderTopColor

• `Optional` **borderTopColor**: `string` \| `string`[]

The **`border-top-color`** CSS property sets the color of an element's top border. It can also be set with the shorthand CSS properties `border-color` or `border-top`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTopColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertopcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18650

___

### borderTopLeftRadius

• `Optional` **borderTopLeftRadius**: [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\> \| [`BorderTopLeftRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertopleftradiusproperty)<`TLength`\>[]

The **`border-top-left-radius`** CSS property rounds the top-left corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-left-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTopLeftRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertopleftradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18665

___

### borderTopRightRadius

• `Optional` **borderTopRightRadius**: [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\> \| [`BorderTopRightRadiusProperty`](../modules/akashaproject_design_system._internal_.md#bordertoprightradiusproperty)<`TLength`\>[]

The **`border-top-right-radius`** CSS property rounds the top-right corner of an element.

**Syntax**: `<length-percentage>{1,2}`

**Initial value**: `0`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
|  **4**  |  **4**  |  **5**  | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-right-radius

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTopRightRadius](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertoprightradius)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18680

___

### borderTopStyle

• `Optional` **borderTopStyle**: [`BorderTopStyleProperty`](../modules/akashaproject_design_system._internal_.md#bordertopstyleproperty) \| [`BorderTopStyleProperty`](../modules/akashaproject_design_system._internal_.md#bordertopstyleproperty)[]

The **`border-top-style`** CSS property sets the line style of an element's top `border`.

**Syntax**: `<line-style>`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTopStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertopstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18694

___

### borderTopWidth

• `Optional` **borderTopWidth**: [`BorderTopWidthProperty`](../modules/akashaproject_design_system._internal_.md#bordertopwidthproperty)<`TLength`\> \| [`BorderTopWidthProperty`](../modules/akashaproject_design_system._internal_.md#bordertopwidthproperty)<`TLength`\>[]

The **`border-top-width`** CSS property sets the width of the top border of an element.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-top-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderTopWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bordertopwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18708

___

### borderWidth

• `Optional` **borderWidth**: [`BorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderwidthproperty)<`TLength`\> \| [`BorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#borderwidthproperty)<`TLength`\>[]

The **`border-width`** shorthand CSS property sets the widths of all four sides of an element's border.

**Syntax**: `<line-width>{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/border-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[borderWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#borderwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22989

___

### bottom

• `Optional` **bottom**: [`BottomProperty`](../modules/akashaproject_design_system._internal_.md#bottomproperty)<`TLength`\> \| [`BottomProperty`](../modules/akashaproject_design_system._internal_.md#bottomproperty)<`TLength`\>[]

The **`bottom`** CSS property participates in specifying the vertical position of a _positioned element_. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[bottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#bottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18722

___

### boxAlign

• `Optional` **boxAlign**: [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty) \| [`BoxAlignProperty`](../modules/akashaproject_design_system._internal_.md#boxalignproperty)[]

The **`box-align`** CSS property specifies how an element aligns its contents across its layout in a perpendicular direction. The effect of the property is only visible if there is extra space in the box.

**Syntax**: `start | center | end | baseline | stretch`

**Initial value**: `stretch`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxAlign](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25316

___

### boxDecorationBreak

• `Optional` **boxDecorationBreak**: [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty) \| [`BoxDecorationBreakProperty`](../modules/akashaproject_design_system._internal_.md#boxdecorationbreakproperty)[]

The **`box-decoration-break`** CSS property specifies how an element's fragments should be rendered when broken across multiple lines, columns, or pages.

**Syntax**: `slice | clone`

**Initial value**: `slice`

|    Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :----------: | :-----: | :---------: | :----------: | :-: |
| **22** _-x-_ | **32**  | **7** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-decoration-break

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[boxDecorationBreak](akashaproject_design_system._internal_.StandardPropertiesFallback.md#boxdecorationbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18736

___

### boxDirection

• `Optional` **boxDirection**: [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty) \| [`BoxDirectionProperty`](../modules/akashaproject_design_system._internal_.md#boxdirectionproperty)[]

The **`box-direction`** CSS property specifies whether a box lays out its contents normally (from the top or left edge), or in reverse (from the bottom or right edge).

**Syntax**: `normal | reverse | inherit`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxDirection](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25326

___

### boxFlex

• `Optional` **boxFlex**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`-moz-box-flex`** and **`-webkit-box-flex`** CSS properties specify how a `-moz-box` or `-webkit-box` grows to fill the box that contains it, in the direction of the containing box's layout.

**Syntax**: `<number>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxFlex](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25336

___

### boxFlexGroup

• `Optional` **boxFlexGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-flex-group`** CSS property assigns the flexbox's child elements to a flex group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxFlexGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxflexgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25346

___

### boxLines

• `Optional` **boxLines**: [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty) \| [`BoxLinesProperty`](../modules/akashaproject_design_system._internal_.md#boxlinesproperty)[]

The **`box-lines`** CSS property determines whether the box may have a single or multiple lines (rows for horizontally oriented boxes, columns for vertically oriented boxes).

**Syntax**: `single | multiple`

**Initial value**: `single`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxLines](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25356

___

### boxOrdinalGroup

• `Optional` **boxOrdinalGroup**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`box-ordinal-group`** CSS property assigns the flexbox's child elements to an ordinal group.

**Syntax**: `<integer>`

**Initial value**: `1`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxOrdinalGroup](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxordinalgroup)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25366

___

### boxOrient

• `Optional` **boxOrient**: [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty) \| [`BoxOrientProperty`](../modules/akashaproject_design_system._internal_.md#boxorientproperty)[]

The **`box-orient`** CSS property specifies whether an element lays out its contents horizontally or vertically.

**Syntax**: `horizontal | vertical | inline-axis | block-axis | inherit`

**Initial value**: `inline-axis` (`horizontal` in XUL)

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxOrient](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxorient)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25376

___

### boxPack

• `Optional` **boxPack**: [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty) \| [`BoxPackProperty`](../modules/akashaproject_design_system._internal_.md#boxpackproperty)[]

The **`-moz-box-pack`** and **`-webkit-box-pack`** CSS properties specify how a `-moz-box` or `-webkit-box` packs its contents in the direction of its layout. The effect of this is only visible if there is extra space in the box.

**Syntax**: `start | center | end | justify`

**Initial value**: `start`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[boxPack](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#boxpack)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25386

___

### boxShadow

• `Optional` **boxShadow**: `string` \| `string`[]

The **`box-shadow`** CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

**Syntax**: `none | <shadow>#`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
| **10**  |  **4**  | **5.1** | **12** | **9** |
| 1 _-x-_ |         | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-shadow

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[boxShadow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#boxshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18751

___

### boxSizing

• `Optional` **boxSizing**: [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty) \| [`BoxSizingProperty`](../modules/akashaproject_design_system._internal_.md#boxsizingproperty)[]

The **`box-sizing`** CSS property defines how the user agent should calculate the total width and height of an element.

**Syntax**: `content-box | border-box`

**Initial value**: `content-box`

| Chrome  | Firefox | Safari  |  Edge  |  IE   |
| :-----: | :-----: | :-----: | :----: | :---: |
| **10**  | **29**  | **5.1** | **12** | **8** |
| 1 _-x-_ | 1 _-x-_ | 3 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/box-sizing

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[boxSizing](akashaproject_design_system._internal_.StandardPropertiesFallback.md#boxsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18766

___

### breakAfter

• `Optional` **breakAfter**: [`BreakAfterProperty`](../modules/akashaproject_design_system._internal_.md#breakafterproperty) \| [`BreakAfterProperty`](../modules/akashaproject_design_system._internal_.md#breakafterproperty)[]

The **`break-after`** CSS property defines how page, column, or region breaks should behave after a generated box. If there is no generated box, the property is ignored.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[breakAfter](akashaproject_design_system._internal_.StandardPropertiesFallback.md#breakafter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18794

___

### breakBefore

• `Optional` **breakBefore**: [`BreakBeforeProperty`](../modules/akashaproject_design_system._internal_.md#breakbeforeproperty) \| [`BreakBeforeProperty`](../modules/akashaproject_design_system._internal_.md#breakbeforeproperty)[]

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[breakBefore](akashaproject_design_system._internal_.StandardPropertiesFallback.md#breakbefore)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18822

___

### breakInside

• `Optional` **breakInside**: [`BreakInsideProperty`](../modules/akashaproject_design_system._internal_.md#breakinsideproperty) \| [`BreakInsideProperty`](../modules/akashaproject_design_system._internal_.md#breakinsideproperty)[]

The **`break-inside`** CSS property defines how page, column, or region breaks should behave inside a generated box. If there is no generated box, the property is ignored.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[breakInside](akashaproject_design_system._internal_.StandardPropertiesFallback.md#breakinside)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18850

___

### captionSide

• `Optional` **captionSide**: [`CaptionSideProperty`](../modules/akashaproject_design_system._internal_.md#captionsideproperty) \| [`CaptionSideProperty`](../modules/akashaproject_design_system._internal_.md#captionsideproperty)[]

The **`caption-side`** CSS property puts the content of a table's `<caption>` on the specified side. The values are relative to the `writing-mode` of the table.

**Syntax**: `top | bottom | block-start | block-end | inline-start | inline-end`

**Initial value**: `top`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/caption-side

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[captionSide](akashaproject_design_system._internal_.StandardPropertiesFallback.md#captionside)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18864

___

### caretColor

• `Optional` **caretColor**: `string` \| `string`[]

The **`caret-color`** CSS property sets the color of the insertion caret, the visible marker where the next character typed will be inserted. The caret appears in elements such as `<input>` or those with the `contenteditable` attribute. The caret is typically a thin vertical line that flashes to help make it more noticeable. By default, it is black, but its color can be altered with this property.

**Syntax**: `auto | <color>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **53**  | **11.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/caret-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[caretColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#caretcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18878

___

### clear

• `Optional` **clear**: [`ClearProperty`](../modules/akashaproject_design_system._internal_.md#clearproperty) \| [`ClearProperty`](../modules/akashaproject_design_system._internal_.md#clearproperty)[]

The **`clear`** CSS property sets whether an element must be moved below (cleared) floating elements that precede it. The `clear` property applies to floating and non-floating elements.

**Syntax**: `none | left | right | both | inline-start | inline-end`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/clear

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[clear](akashaproject_design_system._internal_.StandardPropertiesFallback.md#clear)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18892

___

### clip

• `Optional` **clip**: `string` \| `string`[]

The **`clip`** CSS property defines what portion of an element is visible. The `clip` property applies only to absolutely positioned elements, that is elements with `position:absolute` or `position:fixed`.

**Syntax**: `<shape> | auto`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[clip](akashaproject_design_system._internal_.SvgPropertiesFallback.md#clip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25396

___

### clipPath

• `Optional` **clipPath**: `string` \| `string`[]

The `**clip-path**` CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

**Syntax**: `<clip-source> | [ <basic-shape> || <geometry-box> ] | none`

**Initial value**: `none`

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **55**  | **3.5** |  **9.1**  | **12** | **10** |
| 23 _-x-_ |         | 6.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/clip-path

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[clipPath](akashaproject_design_system._internal_.SvgPropertiesFallback.md#clippath)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18907

___

### clipRule

• `Optional` **clipRule**: [`ClipRuleProperty`](../modules/akashaproject_design_system._internal_.md#clipruleproperty) \| [`ClipRuleProperty`](../modules/akashaproject_design_system._internal_.md#clipruleproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[clipRule](akashaproject_design_system._internal_.SvgPropertiesFallback.md#cliprule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26360

___

### color

• `Optional` **color**: `string` \| `string`[]

The **`color`** CSS property sets the foreground color value of an element's text and text decorations, and sets the `currentcolor` value. `currentcolor` may be used as an indirect value on _other_ properties and is the default for other color properties, such as `border-color`.

**Syntax**: `<color>`

**Initial value**: Varies from one browser to another

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[color](akashaproject_design_system._internal_.SvgPropertiesFallback.md#color)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18921

___

### colorAdjust

• `Optional` **colorAdjust**: [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty) \| [`ColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#coloradjustproperty)[]

The **`color-adjust`** CSS property sets what, if anything, the user agent may do to optimize the appearance of the element on the output device. By default, the browser is allowed to make any adjustments to the element's appearance it determines to be necessary and prudent given the type and capabilities of the output device.

**Syntax**: `economy | exact`

**Initial value**: `economy`

|                Chrome                 | Firefox |                Safari                |                 Edge                  | IE  |
| :-----------------------------------: | :-----: | :----------------------------------: | :-----------------------------------: | :-: |
| **49** _(-webkit-print-color-adjust)_ | **48**  | **6** _(-webkit-print-color-adjust)_ | **79** _(-webkit-print-color-adjust)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color-adjust

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[colorAdjust](akashaproject_design_system._internal_.StandardPropertiesFallback.md#coloradjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18935

___

### colorInterpolation

• `Optional` **colorInterpolation**: [`ColorInterpolationProperty`](../modules/akashaproject_design_system._internal_.md#colorinterpolationproperty) \| [`ColorInterpolationProperty`](../modules/akashaproject_design_system._internal_.md#colorinterpolationproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[colorInterpolation](akashaproject_design_system._internal_.SvgPropertiesFallback.md#colorinterpolation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26362

___

### colorRendering

• `Optional` **colorRendering**: [`ColorRenderingProperty`](../modules/akashaproject_design_system._internal_.md#colorrenderingproperty) \| [`ColorRenderingProperty`](../modules/akashaproject_design_system._internal_.md#colorrenderingproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[colorRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#colorrendering)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26363

___

### colorScheme

• `Optional` **colorScheme**: `string` \| `string`[]

The **`color-scheme`** CSS property allows an element to indicate which color schemes it can comfortably be rendered in.

**Syntax**: `normal | [ light | dark | <custom-ident> ]+`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **81** |   No    | **13** | **81** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/color-scheme

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[colorScheme](akashaproject_design_system._internal_.StandardPropertiesFallback.md#colorscheme)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18949

___

### columnCount

• `Optional` **columnCount**: [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty) \| [`ColumnCountProperty`](../modules/akashaproject_design_system._internal_.md#columncountproperty)[]

The **`column-count`** CSS property breaks an element's content into the specified number of columns.

**Syntax**: `<integer> | auto`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-count

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnCount](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columncount)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18964

___

### columnFill

• `Optional` **columnFill**: [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty) \| [`ColumnFillProperty`](../modules/akashaproject_design_system._internal_.md#columnfillproperty)[]

The **`column-fill`** CSS property controls how an element's contents are balanced when broken into columns.

**Syntax**: `auto | balance | balance-all`

**Initial value**: `balance`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **50** | **52**  |  **9**  | **12** | **10** |
|        |         | 8 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-fill

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnFill](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnfill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:18979

___

### columnGap

• `Optional` **columnGap**: [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\> \| [`ColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#columngapproperty)<`TLength`\>[]

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnGap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19017

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnRule](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23002

___

### columnRuleColor

• `Optional` **columnRuleColor**: `string` \| `string`[]

The **`column-rule-color`** CSS property sets the color of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnRuleColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnrulecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19032

___

### columnRuleStyle

• `Optional` **columnRuleStyle**: `string` \| `string`[]

The **`column-rule-style`** CSS property sets the style of the line drawn between columns in a multi-column layout.

**Syntax**: `<'border-style'>`

**Initial value**: `none`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnRuleStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnrulestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19047

___

### columnRuleWidth

• `Optional` **columnRuleWidth**: [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\> \| [`ColumnRuleWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnrulewidthproperty)<`TLength`\>[]

The **`column-rule-width`** CSS property sets the width of the rule (line) drawn between columns in a multi-column layout.

**Syntax**: `<'border-width'>`

**Initial value**: `medium`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **52**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-rule-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnRuleWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnrulewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19062

___

### columnSpan

• `Optional` **columnSpan**: [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty) \| [`ColumnSpanProperty`](../modules/akashaproject_design_system._internal_.md#columnspanproperty)[]

The **`column-span`** CSS property makes it possible for an element to span across all columns when its value is set to `all`.

**Syntax**: `none | all`

**Initial value**: `none`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **50**  | **71**  |   **9**   | **12** | **10** |
| 6 _-x-_ |         | 5.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-span

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnSpan](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnspan)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19077

___

### columnWidth

• `Optional` **columnWidth**: [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\> \| [`ColumnWidthProperty`](../modules/akashaproject_design_system._internal_.md#columnwidthproperty)<`TLength`\>[]

The **`column-width`** CSS property specifies the ideal column width in a multi-column layout. The container will have as many columns as can fit without any of them having a width less than the `column-width` value. If the width of the container is narrower than the specified value, the single column's width will be smaller than the declared column width.

**Syntax**: `<length> | auto`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **50**  | **50**  |  **9**  | **12** | **10** |
| 1 _-x-_ |         | 3 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/column-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columnWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columnwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19092

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[columns](akashaproject_design_system._internal_.StandardPropertiesFallback.md#columns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23015

___

### contain

• `Optional` **contain**: `string` \| `string`[]

The **`contain`** CSS property allows an author to indicate that an element and its contents are, as much as possible, _independent_ of the rest of the document tree. This allows the browser to recalculate layout, style, paint, size, or any combination of them for a limited area of the DOM and not the entire page.

**Syntax**: `none | strict | content | [ size || layout || style || paint ]`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **52** | **69**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/contain

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[contain](akashaproject_design_system._internal_.StandardPropertiesFallback.md#contain)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19106

___

### content

• `Optional` **content**: `string` \| `string`[]

The **`content`** CSS property replaces an element with a generated value. Objects inserted using the `content` property are _anonymous replaced elements._

**Syntax**: `normal | none | [ <content-replacement> | <content-list> ] [/ <string> ]?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/content

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[content](akashaproject_design_system._internal_.StandardPropertiesFallback.md#content)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19120

___

### contentVisibility

• `Optional` **contentVisibility**: [`ContentVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#contentvisibilityproperty) \| [`ContentVisibilityProperty`](../modules/akashaproject_design_system._internal_.md#contentvisibilityproperty)[]

The **`content-visibility`** CSS property controls whether or not an element renders its contents at all, along with forcing a strong set of containments, allowing user agents to potentially omit large swathes of layout and rendering work until it becomes needed. Basically it enables the user agent to skip an element's rendering work, including layout and painting, until it is needed, makes the initial page load much faster.

**Syntax**: `visible | auto | hidden`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **85** |   No    |   No   | **85** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/content-visibility

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[contentVisibility](akashaproject_design_system._internal_.StandardPropertiesFallback.md#contentvisibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19134

___

### counterIncrement

• `Optional` **counterIncrement**: `string` \| `string`[]

The **`counter-increment`** CSS property increases or decreases the value of a CSS counter by a given value.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **3**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-increment

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[counterIncrement](akashaproject_design_system._internal_.StandardPropertiesFallback.md#counterincrement)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19148

___

### counterReset

• `Optional` **counterReset**: `string` \| `string`[]

The **`counter-reset`** CSS property resets a CSS counter to a given value.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **3**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-reset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[counterReset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#counterreset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19162

___

### counterSet

• `Optional` **counterSet**: `string` \| `string`[]

The **`counter-set`** CSS property sets a CSS counter to a given value. It manipulates the value of existing counters, and will only create new counters if there isn't already a counter of the given name on the element.

**Syntax**: `[ <custom-ident> <integer>? ]+ | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **85** | **68**  |   No   | **85** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/counter-set

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[counterSet](akashaproject_design_system._internal_.StandardPropertiesFallback.md#counterset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19176

___

### cursor

• `Optional` **cursor**: `string` \| `string`[]

The **`cursor`** CSS property sets mouse cursor to display when the mouse pointer is over an element.

**Syntax**: `[ [ <url> [ <x> <y> ]? , ]* [ auto | default | none | context-menu | help | pointer | progress | wait | cell | crosshair | text | vertical-text | alias | copy | move | no-drop | not-allowed | e-resize | n-resize | ne-resize | nw-resize | s-resize | se-resize | sw-resize | w-resize | ew-resize | ns-resize | nesw-resize | nwse-resize | col-resize | row-resize | all-scroll | zoom-in | zoom-out | grab | grabbing ] ]`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/cursor

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[cursor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#cursor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19190

___

### direction

• `Optional` **direction**: [`DirectionProperty`](../modules/akashaproject_design_system._internal_.md#directionproperty) \| [`DirectionProperty`](../modules/akashaproject_design_system._internal_.md#directionproperty)[]

The **`direction`** CSS property sets the direction of text, table columns, and horizontal overflow. Use `rtl` for languages written from right to left (like Hebrew or Arabic), and `ltr` for those written from left to right (like English and most other languages).

**Syntax**: `ltr | rtl`

**Initial value**: `ltr`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **2**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/direction

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[direction](akashaproject_design_system._internal_.SvgPropertiesFallback.md#direction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19204

___

### display

• `Optional` **display**: `string` \| `string`[]

The **`display`** CSS property defines the _display type_ of an element, which consists of the two basic qualities of how an element generates boxes — the **outer display type** defining how the box participates in flow layout, and the **inner display type** defining how the children of the box are laid out.

**Syntax**: `[ <display-outside> || <display-inside> ] | <display-listitem> | <display-internal> | <display-box> | <display-legacy>`

**Initial value**: `inline`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/display

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[display](akashaproject_design_system._internal_.SvgPropertiesFallback.md#display)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19218

___

### dominantBaseline

• `Optional` **dominantBaseline**: [`DominantBaselineProperty`](../modules/akashaproject_design_system._internal_.md#dominantbaselineproperty) \| [`DominantBaselineProperty`](../modules/akashaproject_design_system._internal_.md#dominantbaselineproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[dominantBaseline](akashaproject_design_system._internal_.SvgPropertiesFallback.md#dominantbaseline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26367

___

### emptyCells

• `Optional` **emptyCells**: [`EmptyCellsProperty`](../modules/akashaproject_design_system._internal_.md#emptycellsproperty) \| [`EmptyCellsProperty`](../modules/akashaproject_design_system._internal_.md#emptycellsproperty)[]

The **`empty-cells`** CSS property sets whether borders and backgrounds appear around `<table>` cells that have no visible content.

**Syntax**: `show | hide`

**Initial value**: `show`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/empty-cells

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[emptyCells](akashaproject_design_system._internal_.StandardPropertiesFallback.md#emptycells)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19232

___

### fill

• `Optional` **fill**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fill](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fill)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26368

___

### fillOpacity

• `Optional` **fillOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fillOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fillopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26369

___

### fillRule

• `Optional` **fillRule**: [`FillRuleProperty`](../modules/akashaproject_design_system._internal_.md#fillruleproperty) \| [`FillRuleProperty`](../modules/akashaproject_design_system._internal_.md#fillruleproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fillRule](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fillrule)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26370

___

### filter

• `Optional` **filter**: `string` \| `string`[]

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

**Syntax**: `none | <filter-function-list>`

**Initial value**: `none`

|  Chrome  | Firefox | Safari  |  Edge  | IE  |
| :------: | :-----: | :-----: | :----: | :-: |
|  **53**  | **35**  | **9.1** | **12** | No  |
| 18 _-x-_ |         | 6 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/filter

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[filter](akashaproject_design_system._internal_.SvgPropertiesFallback.md#filter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19247

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flex](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23028

___

### flexBasis

• `Optional` **flexBasis**: [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\> \| [`FlexBasisProperty`](../modules/akashaproject_design_system._internal_.md#flexbasisproperty)<`TLength`\>[]

The **`flex-basis`** CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with `box-sizing`.

**Syntax**: `content | <'width'>`

**Initial value**: `auto`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **22**  |  **9**  | **12** | **11** |
| 22 _-x-_ |         | 7 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-basis

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexBasis](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexbasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19262

___

### flexDirection

• `Optional` **flexDirection**: [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty) \| [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty)[]

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-direction

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexDirection](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19277

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexFlow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23041

___

### flexGrow

• `Optional` **flexGrow**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-grow`** CSS property sets how much of the available space in the flex container should be assigned to that item (the flex grow factor). If all sibling items have the same flex grow factor, then all items will receive the same share of available space, otherwise it is distributed according to the ratio defined by the different flex grow factors.

**Syntax**: `<number>`

**Initial value**: `0`

|  Chrome  | Firefox | Safari  |  Edge  |            IE            |
| :------: | :-----: | :-----: | :----: | :----------------------: |
|  **29**  | **20**  |  **9**  | **12** |          **11**          |
| 22 _-x-_ |         | 7 _-x-_ |        | 10 _(-ms-flex-positive)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-grow

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexGrow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexgrow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19292

___

### flexShrink

• `Optional` **flexShrink**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-shrink`** CSS property sets the flex shrink factor of a flex item. If the size of flex items is larger than the flex container, items shrink to fit according to `flex-shrink`.

**Syntax**: `<number>`

**Initial value**: `1`

|  Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :------: | :-----: | :-----: | :----: | :----: |
|  **29**  | **20**  |  **9**  | **12** | **10** |
| 22 _-x-_ |         | 8 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-shrink

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexShrink](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexshrink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19307

___

### flexWrap

• `Optional` **flexWrap**: [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty) \| [`FlexWrapProperty`](../modules/akashaproject_design_system._internal_.md#flexwrapproperty)[]

The **`flex-wrap`** CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

**Syntax**: `nowrap | wrap | wrap-reverse`

**Initial value**: `nowrap`

|  Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :------: | :-----: | :-------: | :----: | :----: |
|  **29**  | **28**  |   **9**   | **12** | **11** |
| 21 _-x-_ |         | 6.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/flex-wrap

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[flexWrap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#flexwrap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19322

___

### float

• `Optional` **float**: [`FloatProperty`](../modules/akashaproject_design_system._internal_.md#floatproperty) \| [`FloatProperty`](../modules/akashaproject_design_system._internal_.md#floatproperty)[]

The **`float`** CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

**Syntax**: `left | right | none | inline-start | inline-end`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/float

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[float](akashaproject_design_system._internal_.StandardPropertiesFallback.md#float)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19336

___

### floodColor

• `Optional` **floodColor**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[floodColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#floodcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26372

___

### floodOpacity

• `Optional` **floodOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[floodOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#floodopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26373

___

### font

• `Optional` **font**: `string` \| `string`[]

The **`font`** CSS property is a shorthand for `font-style`, `font-variant`, `font-weight`, `font-size`, `line-height`, and `font-family`. Alternatively, it sets an element's font to a system font.

**Syntax**: `[ [ <'font-style'> || <font-variant-css21> || <'font-weight'> || <'font-stretch'> ]? <'font-size'> [ / <'line-height'> ]? <'font-family'> ] | caption | icon | menu | message-box | small-caption | status-bar`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[font](akashaproject_design_system._internal_.SvgPropertiesFallback.md#font)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23053

___

### fontFamily

• `Optional` **fontFamily**: `string` \| `string`[]

The **`font-family`** CSS property specifies a prioritized list of one or more font family names and/or generic family names for the selected element.

**Syntax**: `[ <family-name> | <generic-family> ]#`

**Initial value**: depends on user agent

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-family

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontFamily](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontfamily)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19350

___

### fontFeatureSettings

• `Optional` **fontFeatureSettings**: `string` \| `string`[]

The **`font-feature-settings`** CSS property controls advanced typographic features in OpenType fonts.

**Syntax**: `normal | <feature-tag-value>#`

**Initial value**: `normal`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **48**  |  **34**  | **9.1** | **15** | **10** |
| 16 _-x-_ | 15 _-x-_ |         |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-feature-settings

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontFeatureSettings](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontfeaturesettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19365

___

### fontKerning

• `Optional` **fontKerning**: [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty) \| [`FontKerningProperty`](../modules/akashaproject_design_system._internal_.md#fontkerningproperty)[]

The **`font-kerning`** CSS property sets the use of the kerning information stored in a font.

**Syntax**: `auto | normal | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **33** | **32**  |  **9**  | **79** | No  |
|        |         | 6 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-kerning

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontKerning](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontkerning)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19380

___

### fontLanguageOverride

• `Optional` **fontLanguageOverride**: `string` \| `string`[]

The **`font-language-override`** CSS property controls the use of language-specific glyphs in a typeface.

**Syntax**: `normal | <string>`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **34**  |   No   |  No  | No  |
|        | 4 _-x-_ |        |      |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-language-override

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontLanguageOverride](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontlanguageoverride)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19395

___

### fontOpticalSizing

• `Optional` **fontOpticalSizing**: [`FontOpticalSizingProperty`](../modules/akashaproject_design_system._internal_.md#fontopticalsizingproperty) \| [`FontOpticalSizingProperty`](../modules/akashaproject_design_system._internal_.md#fontopticalsizingproperty)[]

The **`font-optical-sizing`** CSS property sets whether text rendering is optimized for viewing at different sizes. This only works for fonts that have an optical size variation axis.

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **79** | **62**  | **11** | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-optical-sizing

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontOpticalSizing](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontopticalsizing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19409

___

### fontSize

• `Optional` **fontSize**: [`FontSizeProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeproperty)<`TLength`\> \| [`FontSizeProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeproperty)<`TLength`\>[]

The **`font-size`** CSS property sets the size of the font. This property is also used to compute the size of `em`, `ex`, and other relative `<length>` units.

**Syntax**: `<absolute-size> | <relative-size> | <length-percentage>`

**Initial value**: `medium`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-size

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontSize](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19423

___

### fontSizeAdjust

• `Optional` **fontSizeAdjust**: [`FontSizeAdjustProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeadjustproperty) \| [`FontSizeAdjustProperty`](../modules/akashaproject_design_system._internal_.md#fontsizeadjustproperty)[]

The **`font-size-adjust`** CSS property sets how the font size should be chosen based on the height of lowercase rather than capital letters.

**Syntax**: `none | [ ex-height | cap-height | ch-width | ic-width | ic-height ]? [ from-font | <number> ]`

**Initial value**: `none`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |  **1**  |   No   | n/a  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-size-adjust

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontSizeAdjust](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19437

___

### fontSmooth

• `Optional` **fontSmooth**: [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\> \| [`FontSmoothProperty`](../modules/akashaproject_design_system._internal_.md#fontsmoothproperty)<`TLength`\>[]

The **`font-smooth`** CSS property controls the application of anti-aliasing when fonts are rendered.

**Syntax**: `auto | never | always | <absolute-size> | <length>`

**Initial value**: `auto`

|              Chrome              |              Firefox               |              Safari              |               Edge                | IE  |
| :------------------------------: | :--------------------------------: | :------------------------------: | :-------------------------------: | :-: |
| **5** _(-webkit-font-smoothing)_ | **25** _(-moz-osx-font-smoothing)_ | **4** _(-webkit-font-smoothing)_ | **79** _(-webkit-font-smoothing)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-smooth

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontSmooth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontsmooth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19451

___

### fontStretch

• `Optional` **fontStretch**: `string` \| `string`[]

The **`font-stretch`** CSS property selects a normal, condensed, or expanded face from a font.

**Syntax**: `<font-stretch-absolute>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **60** |  **9**  | **11** | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-stretch

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontStretch](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontstretch)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19465

___

### fontStyle

• `Optional` **fontStyle**: `string` \| `string`[]

The **`font-style`** CSS property sets whether a font should be styled with a normal, italic, or oblique face from its `font-family`.

**Syntax**: `normal | italic | oblique <angle>?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-style

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontStyle](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19479

___

### fontSynthesis

• `Optional` **fontSynthesis**: `string` \| `string`[]

The **`font-synthesis`** CSS property controls which missing typefaces, bold or italic, may be synthesized by the browser.

**Syntax**: `none | [ weight || style || small-caps ]`

**Initial value**: `weight style`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **34**  | **9**  |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-synthesis

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontSynthesis](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontsynthesis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19493

___

### fontVariant

• `Optional` **fontVariant**: `string` \| `string`[]

The **font-variant** CSS property is a shorthand for the longhand properties `font-variant-caps`, `font-variant-numeric`, `font-variant-alternates`, `font-variant-ligatures`, and `font-variant-east-asian`. You can also set the CSS Level 2 (Revision 1) values of `font-variant`, (that is, `normal` or `small-caps`), by using the `font` shorthand.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> || stylistic( <feature-value-name> ) || historical-forms || styleset( <feature-value-name># ) || character-variant( <feature-value-name># ) || swash( <feature-value-name> ) || ornaments( <feature-value-name> ) || annotation( <feature-value-name> ) || [ small-caps | all-small-caps | petite-caps | all-petite-caps | unicase | titling-caps ] || <numeric-figure-values> || <numeric-spacing-values> || <numeric-fraction-values> || ordinal || slashed-zero || <east-asian-variant-values> || <east-asian-width-values> || ruby ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontVariant](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontvariant)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19507

___

### fontVariantAlternates

• `Optional` **fontVariantAlternates**: `string` \| `string`[]

The **`font-variant-alternates`** CSS property controls the usage of alternate glyphs. These alternate glyphs may be referenced by alternative names defined in `@font-feature-values`.

**Syntax**: `normal | [ stylistic( <feature-value-name> ) || historical-forms || styleset( <feature-value-name># ) || character-variant( <feature-value-name># ) || swash( <feature-value-name> ) || ornaments( <feature-value-name> ) || annotation( <feature-value-name> ) ]`

**Initial value**: `normal`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[fontVariantAlternates](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#fontvariantalternates)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25406

___

### fontVariantCaps

• `Optional` **fontVariantCaps**: [`FontVariantCapsProperty`](../modules/akashaproject_design_system._internal_.md#fontvariantcapsproperty) \| [`FontVariantCapsProperty`](../modules/akashaproject_design_system._internal_.md#fontvariantcapsproperty)[]

The **`font-variant-caps`** CSS property controls the use of alternate glyphs for capital letters.

**Syntax**: `normal | small-caps | all-small-caps | petite-caps | all-petite-caps | unicase | titling-caps`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **52** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-caps

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariantCaps](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvariantcaps)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19521

___

### fontVariantEastAsian

• `Optional` **fontVariantEastAsian**: `string` \| `string`[]

The **`font-variant-east-asian`** CSS property controls the use of alternate glyphs for East Asian scripts, like Japanese and Chinese.

**Syntax**: `normal | [ <east-asian-variant-values> || <east-asian-width-values> || ruby ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **63** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-east-asian

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariantEastAsian](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvarianteastasian)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19535

___

### fontVariantLigatures

• `Optional` **fontVariantLigatures**: `string` \| `string`[]

The **`font-variant-ligatures`** CSS property controls which ligatures and contextual forms are used in textual content of the elements it applies to. This leads to more harmonized forms in the resulting text.

**Syntax**: `normal | none | [ <common-lig-values> || <discretionary-lig-values> || <historical-lig-values> || <contextual-alt-values> ]`

**Initial value**: `normal`

|  Chrome  | Firefox | Safari  |  Edge  | IE  |
| :------: | :-----: | :-----: | :----: | :-: |
|  **34**  | **34**  | **9.1** | **79** | No  |
| 31 _-x-_ |         | 7 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-ligatures

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariantLigatures](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvariantligatures)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19550

___

### fontVariantNumeric

• `Optional` **fontVariantNumeric**: `string` \| `string`[]

The **`font-variant-numeric`** CSS property controls the usage of alternate glyphs for numbers, fractions, and ordinal markers.

**Syntax**: `normal | [ <numeric-figure-values> || <numeric-spacing-values> || <numeric-fraction-values> || ordinal || slashed-zero ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **52** | **34**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-numeric

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariantNumeric](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvariantnumeric)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19564

___

### fontVariantPosition

• `Optional` **fontVariantPosition**: [`FontVariantPositionProperty`](../modules/akashaproject_design_system._internal_.md#fontvariantpositionproperty) \| [`FontVariantPositionProperty`](../modules/akashaproject_design_system._internal_.md#fontvariantpositionproperty)[]

The **`font-variant-position`** CSS property controls the use of alternate, smaller glyphs that are positioned as superscript or subscript.

**Syntax**: `normal | sub | super`

**Initial value**: `normal`

| Chrome | Firefox | Safari  | Edge | IE  |
| :----: | :-----: | :-----: | :--: | :-: |
|   No   | **34**  | **9.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variant-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariantPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvariantposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19578

___

### fontVariationSettings

• `Optional` **fontVariationSettings**: `string` \| `string`[]

The **`font-variation-settings`** CSS property provides low-level control over variable font characteristics, by specifying the four letter axis names of the characteristics you want to vary, along with their values.

**Syntax**: `normal | [ <string> <number> ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **62** | **62**  | **11** | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-variation-settings

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[fontVariationSettings](akashaproject_design_system._internal_.StandardPropertiesFallback.md#fontvariationsettings)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19592

___

### fontWeight

• `Optional` **fontWeight**: [`FontWeightProperty`](../modules/akashaproject_design_system._internal_.md#fontweightproperty) \| [`FontWeightProperty`](../modules/akashaproject_design_system._internal_.md#fontweightproperty)[]

The **`font-weight`** CSS property specifies the weight (or boldness) of the font. The font weights available to you will depend on the `font-family` you are using. Some fonts are only available in `normal` and `bold`.

**Syntax**: `<font-weight-absolute> | bolder | lighter`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **2**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/font-weight

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[fontWeight](akashaproject_design_system._internal_.SvgPropertiesFallback.md#fontweight)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19606

___

### forcedColorAdjust

• `Optional` **forcedColorAdjust**: [`ForcedColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#forcedcoloradjustproperty) \| [`ForcedColorAdjustProperty`](../modules/akashaproject_design_system._internal_.md#forcedcoloradjustproperty)[]

The **`forced-color-adjust`** CSS property allows authors to opt certain elements out of forced colors mode. This then restores the control of those values to CSS.

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |              Edge               |                 IE                  |
| :----: | :-----: | :----: | :-----------------------------: | :---------------------------------: |
| **89** |   No    |   No   |             **79**              | **10** _(-ms-high-contrast-adjust)_ |
|        |         |        | 12 _(-ms-high-contrast-adjust)_ |                                     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/forced-color-adjust

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[forcedColorAdjust](akashaproject_design_system._internal_.StandardPropertiesFallback.md#forcedcoloradjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19621

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23088

___

### glyphOrientationVertical

• `Optional` **glyphOrientationVertical**: [`GlyphOrientationVerticalProperty`](../modules/akashaproject_design_system._internal_.md#glyphorientationverticalproperty) \| [`GlyphOrientationVerticalProperty`](../modules/akashaproject_design_system._internal_.md#glyphorientationverticalproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[glyphOrientationVertical](akashaproject_design_system._internal_.SvgPropertiesFallback.md#glyphorientationvertical)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26382

___

### grid

• `Optional` **grid**: `string` \| `string`[]

The **`grid`** CSS property is a shorthand property that sets all of the explicit grid properties (`grid-template-rows`, `grid-template-columns`, and `grid-template-areas`), and all the implicit grid properties (`grid-auto-rows`, `grid-auto-columns`, and `grid-auto-flow`), in a single declaration.

**Syntax**: `<'grid-template'> | <'grid-template-rows'> / [ auto-flow && dense? ] <'grid-auto-columns'>? | [ auto-flow && dense? ] <'grid-auto-rows'>? / <'grid-template-columns'>`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[grid](akashaproject_design_system._internal_.StandardPropertiesFallback.md#grid)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridArea](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridarea)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23112

___

### gridAutoColumns

• `Optional` **gridAutoColumns**: [`GridAutoColumnsProperty`](../modules/akashaproject_design_system._internal_.md#gridautocolumnsproperty)<`TLength`\> \| [`GridAutoColumnsProperty`](../modules/akashaproject_design_system._internal_.md#gridautocolumnsproperty)<`TLength`\>[]

The **`grid-auto-columns`** CSS property specifies the size of an implicitly-created grid column track.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-columns

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridAutoColumns](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridautocolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19635

___

### gridAutoFlow

• `Optional` **gridAutoFlow**: `string` \| `string`[]

The **`grid-auto-flow`** CSS property controls how the auto-placement algorithm works, specifying exactly how auto-placed items get flowed into the grid.

**Syntax**: `[ row | column ] || dense`

**Initial value**: `row`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-flow

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridAutoFlow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridautoflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19649

___

### gridAutoRows

• `Optional` **gridAutoRows**: [`GridAutoRowsProperty`](../modules/akashaproject_design_system._internal_.md#gridautorowsproperty)<`TLength`\> \| [`GridAutoRowsProperty`](../modules/akashaproject_design_system._internal_.md#gridautorowsproperty)<`TLength`\>[]

The **`grid-auto-rows`** CSS property specifies the size of an implicitly-created grid row track.

**Syntax**: `<track-size>+`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **70**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-auto-rows

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridAutoRows](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridautorows)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19663

___

### gridColumn

• `Optional` **gridColumn**: [`GridColumnProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnproperty) \| [`GridColumnProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnproperty)[]

The **`grid-column`** CSS property is a shorthand property for `grid-column-start` and `grid-column-end` specifying a grid item's size and location within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridColumn](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridcolumn)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23124

___

### gridColumnEnd

• `Optional` **gridColumnEnd**: [`GridColumnEndProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnendproperty) \| [`GridColumnEndProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnendproperty)[]

The **`grid-column-end`** CSS property specifies a grid item’s end position within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the block-end edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridColumnEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridcolumnend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19677

___

### gridColumnGap

• `Optional` **gridColumnGap**: [`GridColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumngapproperty)<`TLength`\> \| [`GridColumnGapProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumngapproperty)<`TLength`\>[]

The **`column-gap`** CSS property sets the size of the gap (gutter) between an element's columns.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[gridColumnGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridcolumngap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25416

___

### gridColumnStart

• `Optional` **gridColumnStart**: [`GridColumnStartProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnstartproperty) \| [`GridColumnStartProperty`](../modules/akashaproject_design_system._internal_.md#gridcolumnstartproperty)[]

The **`grid-column-start`** CSS property specifies a grid item’s start position within the grid column by contributing a line, a span, or nothing (automatic) to its grid placement. This start position defines the block-start edge of the grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-column-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridColumnStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridcolumnstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19691

___

### gridGap

• `Optional` **gridGap**: [`GridGapProperty`](../modules/akashaproject_design_system._internal_.md#gridgapproperty)<`TLength`\> \| [`GridGapProperty`](../modules/akashaproject_design_system._internal_.md#gridgapproperty)<`TLength`\>[]

The **`gap`** CSS property sets the gaps (gutters) between rows and columns. It is a shorthand for `row-gap` and `column-gap`.

**Syntax**: `<'grid-row-gap'> <'grid-column-gap'>?`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[gridGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridgap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25424

___

### gridRow

• `Optional` **gridRow**: [`GridRowProperty`](../modules/akashaproject_design_system._internal_.md#gridrowproperty) \| [`GridRowProperty`](../modules/akashaproject_design_system._internal_.md#gridrowproperty)[]

The **`grid-row`** CSS property is a shorthand property for `grid-row-start` and `grid-row-end` specifying a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

**Syntax**: `<grid-line> [ / <grid-line> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridRow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridrow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23136

___

### gridRowEnd

• `Optional` **gridRowEnd**: [`GridRowEndProperty`](../modules/akashaproject_design_system._internal_.md#gridrowendproperty) \| [`GridRowEndProperty`](../modules/akashaproject_design_system._internal_.md#gridrowendproperty)[]

The **`grid-row-end`** CSS property specifies a grid item’s end position within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-end edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridRowEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridrowend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19705

___

### gridRowGap

• `Optional` **gridRowGap**: [`GridRowGapProperty`](../modules/akashaproject_design_system._internal_.md#gridrowgapproperty)<`TLength`\> \| [`GridRowGapProperty`](../modules/akashaproject_design_system._internal_.md#gridrowgapproperty)<`TLength`\>[]

The **`row-gap`** CSS property sets the size of the gap (gutter) between an element's grid rows.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[gridRowGap](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#gridrowgap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25434

___

### gridRowStart

• `Optional` **gridRowStart**: [`GridRowStartProperty`](../modules/akashaproject_design_system._internal_.md#gridrowstartproperty) \| [`GridRowStartProperty`](../modules/akashaproject_design_system._internal_.md#gridrowstartproperty)[]

The **`grid-row-start`** CSS property specifies a grid item’s start position within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start edge of its grid area.

**Syntax**: `<grid-line>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-row-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridRowStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridrowstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19719

___

### gridTemplate

• `Optional` **gridTemplate**: `string` \| `string`[]

The **`grid-template`** CSS property is a shorthand property for defining grid columns, rows, and areas.

**Syntax**: `none | [ <'grid-template-rows'> / <'grid-template-columns'> ] | [ <line-names>? <string> <track-size>? <line-names>? ]+ [ / <explicit-track-list> ]?`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridTemplate](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridtemplate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23148

___

### gridTemplateAreas

• `Optional` **gridTemplateAreas**: `string` \| `string`[]

The **`grid-template-areas`** CSS property specifies named grid areas.

**Syntax**: `none | <string>+`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **52**  | **10.1** | **16** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-areas

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridTemplateAreas](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridtemplateareas)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19733

___

### gridTemplateColumns

• `Optional` **gridTemplateColumns**: [`GridTemplateColumnsProperty`](../modules/akashaproject_design_system._internal_.md#gridtemplatecolumnsproperty)<`TLength`\> \| [`GridTemplateColumnsProperty`](../modules/akashaproject_design_system._internal_.md#gridtemplatecolumnsproperty)<`TLength`\>[]

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |             IE              |
| :----: | :-----: | :------: | :----: | :-------------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-columns)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-columns

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridTemplateColumns](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridtemplatecolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19747

___

### gridTemplateRows

• `Optional` **gridTemplateRows**: [`GridTemplateRowsProperty`](../modules/akashaproject_design_system._internal_.md#gridtemplaterowsproperty)<`TLength`\> \| [`GridTemplateRowsProperty`](../modules/akashaproject_design_system._internal_.md#gridtemplaterowsproperty)<`TLength`\>[]

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list> | subgrid <line-name-list>?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  |            IE            |
| :----: | :-----: | :------: | :----: | :----------------------: |
| **57** | **52**  | **10.1** | **16** | **10** _(-ms-grid-rows)_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/grid-template-rows

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[gridTemplateRows](akashaproject_design_system._internal_.StandardPropertiesFallback.md#gridtemplaterows)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19761

___

### hangingPunctuation

• `Optional` **hangingPunctuation**: `string` \| `string`[]

The **`hanging-punctuation`** CSS property specifies whether a punctuation mark should hang at the start or end of a line of text. Hanging punctuation may be placed outside the line box.

**Syntax**: `none | [ first || [ force-end | allow-end ] || last ]`

**Initial value**: `none`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   No    | **10** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/hanging-punctuation

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[hangingPunctuation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#hangingpunctuation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19775

___

### height

• `Optional` **height**: [`HeightProperty`](../modules/akashaproject_design_system._internal_.md#heightproperty)<`TLength`\> \| [`HeightProperty`](../modules/akashaproject_design_system._internal_.md#heightproperty)<`TLength`\>[]

The **`height`** CSS property specifies the height of an element. By default, the property defines the height of the content area. If `box-sizing` is set to `border-box`, however, it instead determines the height of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/height

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[height](akashaproject_design_system._internal_.StandardPropertiesFallback.md#height)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19789

___

### hyphens

• `Optional` **hyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

|  Chrome  | Firefox |    Safari     |  Edge  |      IE      |
| :------: | :-----: | :-----------: | :----: | :----------: |
|  **55**  | **43**  | **5.1** _-x-_ | **79** | **10** _-x-_ |
| 13 _-x-_ | 6 _-x-_ |               |        |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/hyphens

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[hyphens](akashaproject_design_system._internal_.StandardPropertiesFallback.md#hyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19804

___

### imageOrientation

• `Optional` **imageOrientation**: `string` \| `string`[]

The **`image-orientation`** CSS property specifies a layout-independent correction to the orientation of an image. It should _not_ be used for any other orientation adjustments; instead, the `transform` property should be used with the `rotate` `<transform-function>`.

**Syntax**: `from-image | <angle> | [ <angle>? flip ]`

**Initial value**: `from-image`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **81** | **26**  | **13.1** | **81** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/image-orientation

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[imageOrientation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#imageorientation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19818

___

### imageRendering

• `Optional` **imageRendering**: [`ImageRenderingProperty`](../modules/akashaproject_design_system._internal_.md#imagerenderingproperty) \| [`ImageRenderingProperty`](../modules/akashaproject_design_system._internal_.md#imagerenderingproperty)[]

The **`image-rendering`** CSS property sets an image scaling algorithm. The property applies to an element itself, to any images set in its other properties, and to its descendants.

**Syntax**: `auto | crisp-edges | pixelated`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **13** | **3.6** | **6**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/image-rendering

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[imageRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#imagerendering)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19832

___

### imageResolution

• `Optional` **imageResolution**: `string` \| `string`[]

**Syntax**: `[ from-image || <resolution> ] && snap?`

**Initial value**: `1dppx`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[imageResolution](akashaproject_design_system._internal_.StandardPropertiesFallback.md#imageresolution)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19838

___

### imeMode

• `Optional` **imeMode**: [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty) \| [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty)[]

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[imeMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#imemode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25444

___

### initialLetter

• `Optional` **initialLetter**: [`InitialLetterProperty`](../modules/akashaproject_design_system._internal_.md#initialletterproperty) \| [`InitialLetterProperty`](../modules/akashaproject_design_system._internal_.md#initialletterproperty)[]

The `initial-letter` CSS property sets styling for dropped, raised, and sunken initial letters.

**Syntax**: `normal | [ <number> <integer>? ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   No    | **9**  |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/initial-letter

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[initialLetter](akashaproject_design_system._internal_.StandardPropertiesFallback.md#initialletter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19852

___

### inlineSize

• `Optional` **inlineSize**: [`InlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#inlinesizeproperty)<`TLength`\> \| [`InlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#inlinesizeproperty)<`TLength`\>[]

The **`inline-size`** CSS property defines the horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `width` or the `height` property, depending on the value of `writing-mode`.

**Syntax**: `<'width'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inline-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[inlineSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#inlinesize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19866

___

### inset

• `Optional` **inset**: [`InsetProperty`](../modules/akashaproject_design_system._internal_.md#insetproperty)<`TLength`\> \| [`InsetProperty`](../modules/akashaproject_design_system._internal_.md#insetproperty)<`TLength`\>[]

The **`inset`** CSS property defines the logical block and inline start and end offsets of an element, which map to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,4}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[inset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#inset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19880

___

### insetBlock

• `Optional` **insetBlock**: [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\> \| [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\>[]

The **`inset-block`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19894

___

### insetBlockEnd

• `Optional` **insetBlockEnd**: [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\> \| [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\>[]

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19908

___

### insetBlockStart

• `Optional` **insetBlockStart**: [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\> \| [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\>[]

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19922

___

### insetInline

• `Optional` **insetInline**: [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\> \| [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\>[]

The **`inset-inline`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetinline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19936

___

### insetInlineEnd

• `Optional` **insetInlineEnd**: [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\> \| [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\>[]

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetinlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19950

___

### insetInlineStart

• `Optional` **insetInlineStart**: [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\> \| [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\>[]

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **63**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/inset-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[insetInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#insetinlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19964

___

### isolation

• `Optional` **isolation**: [`IsolationProperty`](../modules/akashaproject_design_system._internal_.md#isolationproperty) \| [`IsolationProperty`](../modules/akashaproject_design_system._internal_.md#isolationproperty)[]

The **`isolation`** CSS property determines whether an element must create a new stacking context.

**Syntax**: `auto | isolate`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **41** | **36**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/isolation

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[isolation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#isolation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:19978

___

### justifyContent

• `Optional` **justifyContent**: `string` \| `string`[]

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[justifyContent](akashaproject_design_system._internal_.StandardPropertiesFallback.md#justifycontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20007

___

### justifyItems

• `Optional` **justifyItems**: `string` \| `string`[]

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[justifyItems](akashaproject_design_system._internal_.StandardPropertiesFallback.md#justifyitems)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20035

___

### justifySelf

• `Optional` **justifySelf**: `string` \| `string`[]

The CSS **`justify-self`** property set the way a box is justified inside its alignment container along the appropriate axis.

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[justifySelf](akashaproject_design_system._internal_.StandardPropertiesFallback.md#justifyself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20063

___

### justifyTracks

• `Optional` **justifyTracks**: `string` \| `string`[]

The **`justify-tracks`** CSS property sets the alignment in the masonry axis for grid containers that have masonry in their inline axis.

**Syntax**: `[ normal | <content-distribution> | <overflow-position>? [ <content-position> | left | right ] ]#`

**Initial value**: `normal`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   |   n/a   |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/justify-tracks

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[justifyTracks](akashaproject_design_system._internal_.StandardPropertiesFallback.md#justifytracks)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20077

___

### left

• `Optional` **left**: [`LeftProperty`](../modules/akashaproject_design_system._internal_.md#leftproperty)<`TLength`\> \| [`LeftProperty`](../modules/akashaproject_design_system._internal_.md#leftproperty)<`TLength`\>[]

The **`left`** CSS property participates in specifying the horizontal position of a _positioned element_. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[left](akashaproject_design_system._internal_.StandardPropertiesFallback.md#left)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20091

___

### letterSpacing

• `Optional` **letterSpacing**: [`LetterSpacingProperty`](../modules/akashaproject_design_system._internal_.md#letterspacingproperty)<`TLength`\> \| [`LetterSpacingProperty`](../modules/akashaproject_design_system._internal_.md#letterspacingproperty)<`TLength`\>[]

The **`letter-spacing`** CSS property sets the spacing behavior between text characters.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/letter-spacing

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[letterSpacing](akashaproject_design_system._internal_.SvgPropertiesFallback.md#letterspacing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20105

___

### lightingColor

• `Optional` **lightingColor**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[lightingColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#lightingcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26385

___

### lineBreak

• `Optional` **lineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

| Chrome  | Firefox | Safari  |  Edge  |   IE    |
| :-----: | :-----: | :-----: | :----: | :-----: |
| **58**  | **69**  | **11**  | **14** | **5.5** |
| 1 _-x-_ |         | 3 _-x-_ |        |         |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-break

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[lineBreak](akashaproject_design_system._internal_.StandardPropertiesFallback.md#linebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20120

___

### lineClamp

• `Optional` **lineClamp**: [`LineClampProperty`](../modules/akashaproject_design_system._internal_.md#lineclampproperty) \| [`LineClampProperty`](../modules/akashaproject_design_system._internal_.md#lineclampproperty)[]

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[lineClamp](akashaproject_design_system._internal_.StandardPropertiesFallback.md#lineclamp)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23154

___

### lineHeight

• `Optional` **lineHeight**: [`LineHeightProperty`](../modules/akashaproject_design_system._internal_.md#lineheightproperty)<`TLength`\> \| [`LineHeightProperty`](../modules/akashaproject_design_system._internal_.md#lineheightproperty)<`TLength`\>[]

The **`line-height`** CSS property sets the amount of space used for lines, such as in text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.

**Syntax**: `normal | <number> | <length> | <percentage>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[lineHeight](akashaproject_design_system._internal_.SvgPropertiesFallback.md#lineheight)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20134

___

### lineHeightStep

• `Optional` **lineHeightStep**: [`LineHeightStepProperty`](../modules/akashaproject_design_system._internal_.md#lineheightstepproperty)<`TLength`\> \| [`LineHeightStepProperty`](../modules/akashaproject_design_system._internal_.md#lineheightstepproperty)<`TLength`\>[]

The **`line-height-step`** CSS property sets the step unit for line box heights. When the property is set, line box heights are rounded up to the closest multiple of the unit.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |   No    |   No   | n/a  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/line-height-step

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[lineHeightStep](akashaproject_design_system._internal_.StandardPropertiesFallback.md#lineheightstep)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20148

___

### listStyle

• `Optional` **listStyle**: `string` \| `string`[]

The **`list-style`** CSS property is a shorthand to set list style properties `list-style-type`, `list-style-image`, and `list-style-position`.

**Syntax**: `<'list-style-type'> || <'list-style-position'> || <'list-style-image'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[listStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#liststyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23166

___

### listStyleImage

• `Optional` **listStyleImage**: `string` \| `string`[]

The **`list-style-image`** CSS property sets an image to be used as the list item marker.

**Syntax**: `<image> | none`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-image

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[listStyleImage](akashaproject_design_system._internal_.StandardPropertiesFallback.md#liststyleimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20162

___

### listStylePosition

• `Optional` **listStylePosition**: [`ListStylePositionProperty`](../modules/akashaproject_design_system._internal_.md#liststylepositionproperty) \| [`ListStylePositionProperty`](../modules/akashaproject_design_system._internal_.md#liststylepositionproperty)[]

The **`list-style-position`** CSS property sets the position of the `::marker` relative to a list item.

**Syntax**: `inside | outside`

**Initial value**: `outside`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[listStylePosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#liststyleposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20176

___

### listStyleType

• `Optional` **listStyleType**: `string` \| `string`[]

The **`list-style-type`** CSS property sets the marker (such as a disc, character, or custom counter style) of a list item element.

**Syntax**: `<counter-style> | <string> | none`

**Initial value**: `disc`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/list-style-type

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[listStyleType](akashaproject_design_system._internal_.StandardPropertiesFallback.md#liststyletype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20190

___

### margin

• `Optional` **margin**: [`MarginProperty`](../modules/akashaproject_design_system._internal_.md#marginproperty)<`TLength`\> \| [`MarginProperty`](../modules/akashaproject_design_system._internal_.md#marginproperty)<`TLength`\>[]

The **`margin`** CSS property sets the margin area on all four sides of an element. It is a shorthand for `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`.

**Syntax**: `[ <length> | <percentage> | auto ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[margin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#margin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23178

___

### marginBlock

• `Optional` **marginBlock**: [`MarginBlockProperty`](../modules/akashaproject_design_system._internal_.md#marginblockproperty)<`TLength`\> \| [`MarginBlockProperty`](../modules/akashaproject_design_system._internal_.md#marginblockproperty)<`TLength`\>[]

The **`margin-block`** CSS property defines the logical block start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20204

___

### marginBlockEnd

• `Optional` **marginBlockEnd**: [`MarginBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#marginblockendproperty)<`TLength`\> \| [`MarginBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#marginblockendproperty)<`TLength`\>[]

The **`margin-block-end`** CSS property defines the logical block end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20218

___

### marginBlockStart

• `Optional` **marginBlockStart**: [`MarginBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#marginblockstartproperty)<`TLength`\> \| [`MarginBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#marginblockstartproperty)<`TLength`\>[]

The **`margin-block-start`** CSS property defines the logical block start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20232

___

### marginBottom

• `Optional` **marginBottom**: [`MarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#marginbottomproperty)<`TLength`\> \| [`MarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#marginbottomproperty)<`TLength`\>[]

The **`margin-bottom`** CSS property sets the margin area on the bottom of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20246

___

### marginInline

• `Optional` **marginInline**: [`MarginInlineProperty`](../modules/akashaproject_design_system._internal_.md#margininlineproperty)<`TLength`\> \| [`MarginInlineProperty`](../modules/akashaproject_design_system._internal_.md#margininlineproperty)<`TLength`\>[]

The **`margin-inline`** CSS property defines the logical inline start and end margins of an element, which maps to physical margins depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'margin-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#margininline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20260

___

### marginInlineEnd

• `Optional` **marginInlineEnd**: [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\> \| [`MarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#margininlineendproperty)<`TLength`\>[]

The **`margin-inline-end`** CSS property defines the logical inline end margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. In other words, it corresponds to the `margin-top`, `margin-right`, `margin-bottom` or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|          Chrome          |        Firefox        |          Safari          |  Edge  | IE  |
| :----------------------: | :-------------------: | :----------------------: | :----: | :-: |
|          **69**          |        **41**         |         **12.1**         | **79** | No  |
| 2 _(-webkit-margin-end)_ | 3 _(-moz-margin-end)_ | 3 _(-webkit-margin-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#margininlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20275

___

### marginInlineStart

• `Optional` **marginInlineStart**: [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\> \| [`MarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#margininlinestartproperty)<`TLength`\>[]

The **`margin-inline-start`** CSS property defines the logical inline start margin of an element, which maps to a physical margin depending on the element's writing mode, directionality, and text orientation. It corresponds to the `margin-top`, `margin-right`, `margin-bottom`, or `margin-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'margin-left'>`

**Initial value**: `0`

|           Chrome           |         Firefox         |           Safari           |  Edge  | IE  |
| :------------------------: | :---------------------: | :------------------------: | :----: | :-: |
|           **69**           |         **41**          |          **12.1**          | **79** | No  |
| 2 _(-webkit-margin-start)_ | 3 _(-moz-margin-start)_ | 3 _(-webkit-margin-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#margininlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20290

___

### marginLeft

• `Optional` **marginLeft**: [`MarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#marginleftproperty)<`TLength`\> \| [`MarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#marginleftproperty)<`TLength`\>[]

The **`margin-left`** CSS property sets the margin area on the left side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20304

___

### marginRight

• `Optional` **marginRight**: [`MarginRightProperty`](../modules/akashaproject_design_system._internal_.md#marginrightproperty)<`TLength`\> \| [`MarginRightProperty`](../modules/akashaproject_design_system._internal_.md#marginrightproperty)<`TLength`\>[]

The **`margin-right`** CSS property sets the margin area on the right side of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#marginright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20318

___

### marginTop

• `Optional` **marginTop**: [`MarginTopProperty`](../modules/akashaproject_design_system._internal_.md#margintopproperty)<`TLength`\> \| [`MarginTopProperty`](../modules/akashaproject_design_system._internal_.md#margintopproperty)<`TLength`\>[]

The **`margin-top`** CSS property sets the margin area on the top of an element. A positive value places it farther from its neighbors, while a negative value places it closer.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/margin-top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[marginTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#margintop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20332

___

### marker

• `Optional` **marker**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[marker](akashaproject_design_system._internal_.SvgPropertiesFallback.md#marker)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26387

___

### markerEnd

• `Optional` **markerEnd**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[markerEnd](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markerend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26388

___

### markerMid

• `Optional` **markerMid**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[markerMid](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markermid)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26389

___

### markerStart

• `Optional` **markerStart**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[markerStart](akashaproject_design_system._internal_.SvgPropertiesFallback.md#markerstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26390

___

### mask

• `Optional` **mask**: [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\> \| [`MaskProperty`](../modules/akashaproject_design_system._internal_.md#maskproperty)<`TLength`\>[]

The **`mask`** CSS property hides an element (partially or fully) by masking or clipping the image at specific points.

**Syntax**: `<mask-layer>#`

| Chrome | Firefox | Safari  | Edge  | IE  |
| :----: | :-----: | :-----: | :---: | :-: |
| **1**  |  **2**  | **3.1** | 12-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[mask](akashaproject_design_system._internal_.SvgPropertiesFallback.md#mask)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorder](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskborder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23202

___

### maskBorderMode

• `Optional` **maskBorderMode**: [`MaskBorderModeProperty`](../modules/akashaproject_design_system._internal_.md#maskbordermodeproperty) \| [`MaskBorderModeProperty`](../modules/akashaproject_design_system._internal_.md#maskbordermodeproperty)[]

The **`mask-border-mode`** CSS property specifies the blending mode used in a mask border.

**Syntax**: `luminance | alpha`

**Initial value**: `alpha`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderMode](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskbordermode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20340

___

### maskBorderOutset

• `Optional` **maskBorderOutset**: [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\> \| [`MaskBorderOutsetProperty`](../modules/akashaproject_design_system._internal_.md#maskborderoutsetproperty)<`TLength`\>[]

The **`mask-border-outset`** CSS property specifies the distance by which an element's mask border is set out from its border box.

**Syntax**: `[ <length> | <number> ]{1,4}`

**Initial value**: `0`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-outset)_ |   No    | **3.1** _(-webkit-mask-box-image-outset)_ | **79** _(-webkit-mask-box-image-outset)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-outset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderOutset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskborderoutset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20354

___

### maskBorderRepeat

• `Optional` **maskBorderRepeat**: `string` \| `string`[]

The **`mask-border-repeat`** CSS property sets how the edge regions of a source image are adjusted to fit the dimensions of an element's mask border.

**Syntax**: `[ stretch | repeat | round | space ]{1,2}`

**Initial value**: `stretch`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-repeat)_ |   No    | **3.1** _(-webkit-mask-box-image-repeat)_ | **79** _(-webkit-mask-box-image-repeat)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-repeat

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderRepeat](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskborderrepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20368

___

### maskBorderSlice

• `Optional` **maskBorderSlice**: [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty) \| [`MaskBorderSliceProperty`](../modules/akashaproject_design_system._internal_.md#maskbordersliceproperty)[]

The **`mask-border-slice`** CSS property divides the image set by `mask-border-source` into regions. These regions are used to form the components of an element's mask border.

**Syntax**: `<number-percentage>{1,4} fill?`

**Initial value**: `0`

|                 Chrome                 | Firefox |                  Safari                  |                  Edge                   | IE  |
| :------------------------------------: | :-----: | :--------------------------------------: | :-------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-slice)_ |   No    | **3.1** _(-webkit-mask-box-image-slice)_ | **79** _(-webkit-mask-box-image-slice)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-slice

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderSlice](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskborderslice)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20382

___

### maskBorderSource

• `Optional` **maskBorderSource**: `string` \| `string`[]

The **`mask-border-source`** CSS property sets the source image used to create an element's mask border.

**Syntax**: `none | <image>`

**Initial value**: `none`

|                 Chrome                  | Firefox |                  Safari                   |                   Edge                   | IE  |
| :-------------------------------------: | :-----: | :---------------------------------------: | :--------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-source)_ |   No    | **3.1** _(-webkit-mask-box-image-source)_ | **79** _(-webkit-mask-box-image-source)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-source

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderSource](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskbordersource)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20396

___

### maskBorderWidth

• `Optional` **maskBorderWidth**: [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\> \| [`MaskBorderWidthProperty`](../modules/akashaproject_design_system._internal_.md#maskborderwidthproperty)<`TLength`\>[]

The **`mask-border-width`** CSS property sets the width of an element's mask border.

**Syntax**: `[ <length-percentage> | <number> | auto ]{1,4}`

**Initial value**: `auto`

|                 Chrome                 | Firefox |                  Safari                  |                  Edge                   | IE  |
| :------------------------------------: | :-----: | :--------------------------------------: | :-------------------------------------: | :-: |
| **1** _(-webkit-mask-box-image-width)_ |   No    | **3.1** _(-webkit-mask-box-image-width)_ | **79** _(-webkit-mask-box-image-width)_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-border-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskBorderWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskborderwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20410

___

### maskClip

• `Optional` **maskClip**: `string` \| `string`[]

The **`mask-clip`** CSS property determines the area, which is affected by a mask. The painted content of an element must be restricted to this area.

**Syntax**: `[ <geometry-box> | no-clip ]#`

**Initial value**: `border-box`

|   Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :---------: | :-----: | :---------: | :----------: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-clip

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskClip](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskclip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20424

___

### maskComposite

• `Optional` **maskComposite**: `string` \| `string`[]

The **`mask-composite`** CSS property represents a compositing operation used on the current mask layer with the mask layers below it.

**Syntax**: `<compositing-operator>#`

**Initial value**: `add`

| Chrome | Firefox | Safari | Edge  | IE  |
| :----: | :-----: | :----: | :---: | :-: |
|   No   | **53**  |   No   | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-composite

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskComposite](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskcomposite)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20438

___

### maskImage

• `Optional` **maskImage**: `string` \| `string`[]

The **`mask-image`** CSS property sets the image that is used as mask layer for an element.

**Syntax**: `<mask-reference>#`

**Initial value**: `none`

|   Chrome    | Firefox |   Safari    | Edge  | IE  |
| :---------: | :-----: | :---------: | :---: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | 16-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-image

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskImage](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskimage)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20452

___

### maskMode

• `Optional` **maskMode**: `string` \| `string`[]

The **`mask-mode`** CSS property sets whether the mask reference defined by `mask-image` is treated as a luminance or alpha mask.

**Syntax**: `<masking-mode>#`

**Initial value**: `match-source`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **53**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-mode

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskMode](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20466

___

### maskOrigin

• `Optional` **maskOrigin**: `string` \| `string`[]

The **`mask-origin`** CSS property sets the origin of a mask.

**Syntax**: `<geometry-box>#`

**Initial value**: `border-box`

|   Chrome    | Firefox |   Safari    |     Edge     | IE  |
| :---------: | :-----: | :---------: | :----------: | :-: |
| **1** _-x-_ | **53**  | **4** _-x-_ | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-origin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskOrigin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20480

___

### maskPosition

• `Optional` **maskPosition**: [`MaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#maskpositionproperty)<`TLength`\> \| [`MaskPositionProperty`](../modules/akashaproject_design_system._internal_.md#maskpositionproperty)<`TLength`\>[]

The **`mask-position`** CSS property sets the initial position, relative to the mask position layer set by `mask-origin`, for each defined mask image.

**Syntax**: `<position>#`

**Initial value**: `center`

|   Chrome    | Firefox |    Safari     | Edge  | IE  |
| :---------: | :-----: | :-----------: | :---: | :-: |
| **1** _-x-_ | **53**  | **3.1** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20494

___

### maskRepeat

• `Optional` **maskRepeat**: `string` \| `string`[]

The **`mask-repeat`** CSS property sets how mask images are repeated. A mask image can be repeated along the horizontal axis, the vertical axis, both axes, or not repeated at all.

**Syntax**: `<repeat-style>#`

**Initial value**: `no-repeat`

|   Chrome    | Firefox |    Safari     | Edge  | IE  |
| :---------: | :-----: | :-----------: | :---: | :-: |
| **1** _-x-_ | **53**  | **3.1** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-repeat

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskRepeat](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maskrepeat)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20508

___

### maskSize

• `Optional` **maskSize**: [`MaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#masksizeproperty)<`TLength`\> \| [`MaskSizeProperty`](../modules/akashaproject_design_system._internal_.md#masksizeproperty)<`TLength`\>[]

The **`mask-size`** CSS property specifies the sizes of the mask images. The size of the image can be fully or partially constrained in order to preserve its intrinsic ratio.

**Syntax**: `<bg-size>#`

**Initial value**: `auto`

|   Chrome    | Firefox |   Safari    | Edge  | IE  |
| :---------: | :-----: | :---------: | :---: | :-: |
| **4** _-x-_ | **53**  | **4** _-x-_ | 18-79 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#masksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20522

___

### maskType

• `Optional` **maskType**: [`MaskTypeProperty`](../modules/akashaproject_design_system._internal_.md#masktypeproperty) \| [`MaskTypeProperty`](../modules/akashaproject_design_system._internal_.md#masktypeproperty)[]

The **`mask-type`** CSS property sets whether an SVG `<mask>` element is used as a _luminance_ or an _alpha_ mask. It applies to the `<mask>` element itself.

**Syntax**: `luminance | alpha`

**Initial value**: `luminance`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **24** | **35**  | **7**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mask-type

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maskType](akashaproject_design_system._internal_.StandardPropertiesFallback.md#masktype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20536

___

### mathStyle

• `Optional` **mathStyle**: [`MathStyleProperty`](../modules/akashaproject_design_system._internal_.md#mathstyleproperty) \| [`MathStyleProperty`](../modules/akashaproject_design_system._internal_.md#mathstyleproperty)[]

The `math-style` property indicates whether MathML equations should render with normal or compact height.

**Syntax**: `normal | compact`

**Initial value**: `normal`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|  n/a   |   n/a   | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/math-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[mathStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#mathstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20550

___

### maxBlockSize

• `Optional` **maxBlockSize**: [`MaxBlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxblocksizeproperty)<`TLength`\> \| [`MaxBlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxblocksizeproperty)<`TLength`\>[]

The `**max-block-size**` CSS property specifies the maximum size of an element in the direction opposite that of the writing direction as specified by `writing-mode`. That is, if the writing direction is horizontal, then `max-block-size` is equivalent to `max-height`; if the writing direction is vertical, `max-block-size` is the same as `max-width`.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-block-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maxBlockSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maxblocksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20564

___

### maxHeight

• `Optional` **maxHeight**: [`MaxHeightProperty`](../modules/akashaproject_design_system._internal_.md#maxheightproperty)<`TLength`\> \| [`MaxHeightProperty`](../modules/akashaproject_design_system._internal_.md#maxheightproperty)<`TLength`\>[]

The **`max-height`** CSS property sets the maximum height of an element. It prevents the used value of the `height` property from becoming larger than the value specified for `max-height`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **18** |  **1**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-height

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maxHeight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maxheight)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20578

___

### maxInlineSize

• `Optional` **maxInlineSize**: [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\> \| [`MaxInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#maxinlinesizeproperty)<`TLength`\>[]

The **`max-inline-size`** CSS property defines the horizontal or vertical maximum size of an element's block depending on its writing mode. It corresponds to the `max-width` or the `max-height` property depending on the value defined for `writing-mode`. If the writing mode is vertically oriented, the value of `max-inline-size` relates to the maximal height of the element, otherwise it relates to the maximal width of the element. It relates to `max-block-size`, which defines the other dimension of the element.

**Syntax**: `<'max-width'>`

**Initial value**: `0`

| Chrome | Firefox |   Safari   |  Edge  | IE  |
| :----: | :-----: | :--------: | :----: | :-: |
| **57** | **41**  |  **12.1**  | **79** | No  |
|        |         | 10.1 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-inline-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maxInlineSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maxinlinesize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20593

___

### maxLines

• `Optional` **maxLines**: [`MaxLinesProperty`](../modules/akashaproject_design_system._internal_.md#maxlinesproperty) \| [`MaxLinesProperty`](../modules/akashaproject_design_system._internal_.md#maxlinesproperty)[]

**Syntax**: `none | <integer>`

**Initial value**: `none`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maxLines](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maxlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20599

___

### maxWidth

• `Optional` **maxWidth**: [`MaxWidthProperty`](../modules/akashaproject_design_system._internal_.md#maxwidthproperty)<`TLength`\> \| [`MaxWidthProperty`](../modules/akashaproject_design_system._internal_.md#maxwidthproperty)<`TLength`\>[]

The **`max-width`** CSS property sets the maximum width of an element. It prevents the used value of the `width` property from becoming larger than the value specified by `max-width`.

**Syntax**: `none | <length-percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/max-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[maxWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#maxwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20613

___

### minBlockSize

• `Optional` **minBlockSize**: [`MinBlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#minblocksizeproperty)<`TLength`\> \| [`MinBlockSizeProperty`](../modules/akashaproject_design_system._internal_.md#minblocksizeproperty)<`TLength`\>[]

The **`min-block-size`** CSS property defines the minimum horizontal or vertical size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-block-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[minBlockSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#minblocksize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20627

___

### minHeight

• `Optional` **minHeight**: [`MinHeightProperty`](../modules/akashaproject_design_system._internal_.md#minheightproperty)<`TLength`\> \| [`MinHeightProperty`](../modules/akashaproject_design_system._internal_.md#minheightproperty)<`TLength`\>[]

The **`min-height`** CSS property sets the minimum height of an element. It prevents the used value of the `height` property from becoming smaller than the value specified for `min-height`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **3**  | **1.3** | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-height

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[minHeight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#minheight)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20641

___

### minInlineSize

• `Optional` **minInlineSize**: [`MinInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#mininlinesizeproperty)<`TLength`\> \| [`MinInlineSizeProperty`](../modules/akashaproject_design_system._internal_.md#mininlinesizeproperty)<`TLength`\>[]

The **`min-inline-size`** CSS property defines the horizontal or vertical minimal size of an element's block, depending on its writing mode. It corresponds to either the `min-width` or the `min-height` property, depending on the value of `writing-mode`.

**Syntax**: `<'min-width'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-inline-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[minInlineSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#mininlinesize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20655

___

### minWidth

• `Optional` **minWidth**: [`MinWidthProperty`](../modules/akashaproject_design_system._internal_.md#minwidthproperty)<`TLength`\> \| [`MinWidthProperty`](../modules/akashaproject_design_system._internal_.md#minwidthproperty)<`TLength`\>[]

The **`min-width`** CSS property sets the minimum width of an element. It prevents the used value of the `width` property from becoming smaller than the value specified for `min-width`.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **7** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/min-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[minWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#minwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20669

___

### mixBlendMode

• `Optional` **mixBlendMode**: [`MixBlendModeProperty`](../modules/akashaproject_design_system._internal_.md#mixblendmodeproperty) \| [`MixBlendModeProperty`](../modules/akashaproject_design_system._internal_.md#mixblendmodeproperty)[]

The **`mix-blend-mode`** CSS property sets how an element's content should blend with the content of the element's parent and the element's background.

**Syntax**: `<blend-mode>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **41** | **32**  | **8**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/mix-blend-mode

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[mixBlendMode](akashaproject_design_system._internal_.StandardPropertiesFallback.md#mixblendmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20683

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[motion](akashaproject_design_system._internal_.StandardPropertiesFallback.md#motion)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23215

___

### motionDistance

• `Optional` **motionDistance**: [`OffsetDistanceProperty`](../modules/akashaproject_design_system._internal_.md#offsetdistanceproperty)<`TLength`\> \| [`OffsetDistanceProperty`](../modules/akashaproject_design_system._internal_.md#offsetdistanceproperty)<`TLength`\>[]

The **`offset-distance`** CSS property specifies a position along an `offset-path`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[motionDistance](akashaproject_design_system._internal_.StandardPropertiesFallback.md#motiondistance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20698

___

### motionPath

• `Optional` **motionPath**: `string` \| `string`[]

The **`offset-path`** CSS property specifies a motion path for an element to follow and defines the element's positioning within the parent container or SVG coordinate system.

**Syntax**: `none | ray( [ <angle> && <size> && contain? ] ) | <path()> | <url> | [ <basic-shape> || <geometry-box> ]`

**Initial value**: `none`

|       Chrome       | Firefox | Safari |  Edge  | IE  |
| :----------------: | :-----: | :----: | :----: | :-: |
|       **55**       | **72**  |   No   | **79** | No  |
| 46 _(motion-path)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-path

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[motionPath](akashaproject_design_system._internal_.StandardPropertiesFallback.md#motionpath)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20713

___

### motionRotation

• `Optional` **motionRotation**: `string` \| `string`[]

The **`offset-rotate`** CSS property defines the direction of the element while positioning along the offset path.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[motionRotation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#motionrotation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20728

___

### msAccelerator

• `Optional` **msAccelerator**: [`MsAcceleratorProperty`](../modules/akashaproject_design_system._internal_.md#msacceleratorproperty) \| [`MsAcceleratorProperty`](../modules/akashaproject_design_system._internal_.md#msacceleratorproperty)[]

The **`-ms-accelerator`** CSS property is a Microsoft extension that sets or retrieves a string indicating whether the object represents a keyboard shortcut.

**Syntax**: `false | true`

**Initial value**: `false`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msAccelerator](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msaccelerator)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23794

___

### msAlignSelf

• `Optional` **msAlignSelf**: `string` \| `string`[]

The **`align-self`** CSS property aligns flex items of the current flex line overriding the `align-items` value. If any of the item's cross-axis margin is set to `auto`, then `align-self` is ignored. In Grid layout `align-self` aligns the item inside the grid area.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? <self-position>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msAlignSelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msalignself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23802

___

### msBlockProgression

• `Optional` **msBlockProgression**: [`MsBlockProgressionProperty`](../modules/akashaproject_design_system._internal_.md#msblockprogressionproperty) \| [`MsBlockProgressionProperty`](../modules/akashaproject_design_system._internal_.md#msblockprogressionproperty)[]

The **`-ms-block-progression`** CSS property is a Microsoft extension that specifies the block progression and layout orientation.

**Syntax**: `tb | rl | bt | lr`

**Initial value**: `tb`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msBlockProgression](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msblockprogression)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23810

___

### msContentZoomChaining

• `Optional` **msContentZoomChaining**: [`MsContentZoomChainingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchainingproperty) \| [`MsContentZoomChainingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomchainingproperty)[]

The **`-ms-content-zoom-chaining`** CSS property is a Microsoft extension specifying the zoom behavior that occurs when a user hits the zoom limit during page manipulation.

**Syntax**: `none | chained`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomChaining](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomchaining)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23818

___

### msContentZoomLimit

• `Optional` **msContentZoomLimit**: `string` \| `string`[]

The **`-ms-content-zoom-limit`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-limit-min` and `-ms-content-zoom-limit-max` properties.

**Syntax**: `<'-ms-content-zoom-limit-min'> <'-ms-content-zoom-limit-max'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomLimit](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25177

___

### msContentZoomLimitMax

• `Optional` **msContentZoomLimitMax**: `string` \| `string`[]

The **`-ms-content-zoom-limit-max`** CSS property is a Microsoft extension that specifies the selected elements' maximum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `400%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomLimitMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimitmax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23826

___

### msContentZoomLimitMin

• `Optional` **msContentZoomLimitMin**: `string` \| `string`[]

The **`-ms-content-zoom-limit-min`** CSS property is a Microsoft extension that specifies the minimum zoom factor.

**Syntax**: `<percentage>`

**Initial value**: `100%`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomLimitMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomlimitmin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23834

___

### msContentZoomSnap

• `Optional` **msContentZoomSnap**: `string` \| `string`[]

The **`-ms-content-zoom-snap`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-content-zoom-snap-type` and `-ms-content-zoom-snap-points` properties.

**Syntax**: `<'-ms-content-zoom-snap-type'> || <'-ms-content-zoom-snap-points'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomSnap](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25183

___

### msContentZoomSnapPoints

• `Optional` **msContentZoomSnapPoints**: `string` \| `string`[]

The **`-ms-content-zoom-snap-points`** CSS property is a Microsoft extension that specifies where zoom snap-points are located.

**Syntax**: `snapInterval( <percentage>, <percentage> ) | snapList( <percentage># )`

**Initial value**: `snapInterval(0%, 100%)`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomSnapPoints](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnappoints)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23842

___

### msContentZoomSnapType

• `Optional` **msContentZoomSnapType**: [`MsContentZoomSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptypeproperty) \| [`MsContentZoomSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomsnaptypeproperty)[]

The **`-ms-content-zoom-snap-type`** CSS property is a Microsoft extension that specifies how zooming is affected by defined snap-points.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZoomSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzoomsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23850

___

### msContentZooming

• `Optional` **msContentZooming**: [`MsContentZoomingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomingproperty) \| [`MsContentZoomingProperty`](../modules/akashaproject_design_system._internal_.md#mscontentzoomingproperty)[]

The **`-ms-content-zooming`** CSS property is a Microsoft extension that specifies whether zooming is enabled.

**Syntax**: `none | zoom`

**Initial value**: zoom for the top level element, none for all other elements

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msContentZooming](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mscontentzooming)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23858

___

### msFilter

• `Optional` **msFilter**: `string` \| `string`[]

The `-ms-filter` CSS property is a Microsoft extension that sets or retrieves the filter or collection of filters applied to an object.

**Syntax**: `<string>`

**Initial value**: "" (the empty string)

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFilter](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msfilter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23866

___

### msFlex

• `Optional` **msFlex**: [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\> \| [`FlexProperty`](../modules/akashaproject_design_system._internal_.md#flexproperty)<`TLength`\>[]

The **`flex`** CSS property sets how a flex item will grow or shrink to fit the space available in its flex container. It is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.

**Syntax**: `none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFlex](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25189

___

### msFlexDirection

• `Optional` **msFlexDirection**: [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty) \| [`FlexDirectionProperty`](../modules/akashaproject_design_system._internal_.md#flexdirectionproperty)[]

The **`flex-direction`** CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

**Syntax**: `row | row-reverse | column | column-reverse`

**Initial value**: `row`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFlexDirection](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflexdirection)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23874

___

### msFlexPositive

• `Optional` **msFlexPositive**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`flex-grow`** CSS property sets how much of the available space in the flex container should be assigned to that item (the flex grow factor). If all sibling items have the same flex grow factor, then all items will receive the same share of available space, otherwise it is distributed according to the ratio defined by the different flex grow factors.

**Syntax**: `<number>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFlexPositive](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflexpositive)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23882

___

### msFlowFrom

• `Optional` **msFlowFrom**: `string` \| `string`[]

The **`-ms-flow-from`** CSS property is a Microsoft extension that gets or sets a value identifying a region container in the document that accepts the content flow from the data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFlowFrom](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflowfrom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23890

___

### msFlowInto

• `Optional` **msFlowInto**: `string` \| `string`[]

The **`-ms-flow-into`** CSS property is a Microsoft extension that gets or sets a value identifying an iframe container in the document that serves as the region's data source.

**Syntax**: `[ none | <custom-ident> ]#`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msFlowInto](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msflowinto)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23898

___

### msGridColumns

• `Optional` **msGridColumns**: [`MsGridColumnsProperty`](../modules/akashaproject_design_system._internal_.md#msgridcolumnsproperty)<`TLength`\> \| [`MsGridColumnsProperty`](../modules/akashaproject_design_system._internal_.md#msgridcolumnsproperty)<`TLength`\>[]

The **`grid-template-columns`** CSS property defines the line names and track sizing functions of the grid columns.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msGridColumns](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msgridcolumns)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23906

___

### msGridRows

• `Optional` **msGridRows**: [`MsGridRowsProperty`](../modules/akashaproject_design_system._internal_.md#msgridrowsproperty)<`TLength`\> \| [`MsGridRowsProperty`](../modules/akashaproject_design_system._internal_.md#msgridrowsproperty)<`TLength`\>[]

The **`grid-template-rows`** CSS property defines the line names and track sizing functions of the grid rows.

**Syntax**: `none | <track-list> | <auto-track-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msGridRows](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msgridrows)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23914

___

### msHighContrastAdjust

• `Optional` **msHighContrastAdjust**: [`MsHighContrastAdjustProperty`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjustproperty) \| [`MsHighContrastAdjustProperty`](../modules/akashaproject_design_system._internal_.md#mshighcontrastadjustproperty)[]

The **`-ms-high-contrast-adjust`** CSS property is a Microsoft extension that gets or sets a value indicating whether to override any CSS properties that would have been set in high contrast mode.

**Syntax**: `auto | none`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msHighContrastAdjust](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshighcontrastadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23922

___

### msHyphenateLimitChars

• `Optional` **msHyphenateLimitChars**: [`MsHyphenateLimitCharsProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitcharsproperty) \| [`MsHyphenateLimitCharsProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitcharsproperty)[]

The **`-ms-hyphenate-limit-chars`** CSS property is a Microsoft extension that specifies one to three values indicating the minimum number of characters in a hyphenated word. If the word does not meet the required minimum number of characters in the word, before the hyphen, or after the hyphen, then the word is not hyphenated.

**Syntax**: `auto | <integer>{1,3}`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msHyphenateLimitChars](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitchars)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23930

___

### msHyphenateLimitLines

• `Optional` **msHyphenateLimitLines**: [`MsHyphenateLimitLinesProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlinesproperty) \| [`MsHyphenateLimitLinesProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitlinesproperty)[]

The **`-ms-hyphenate-limit-lines`** CSS property is a Microsoft extension specifying the maximum number of consecutive lines in an element that may be ended with a hyphenated word.

**Syntax**: `no-limit | <integer>`

**Initial value**: `no-limit`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msHyphenateLimitLines](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitlines)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23938

___

### msHyphenateLimitZone

• `Optional` **msHyphenateLimitZone**: [`MsHyphenateLimitZoneProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzoneproperty)<`TLength`\> \| [`MsHyphenateLimitZoneProperty`](../modules/akashaproject_design_system._internal_.md#mshyphenatelimitzoneproperty)<`TLength`\>[]

The `**-ms-hyphenate-limit-zone**` CSS property is a Microsoft extension specifying the width of the hyphenation zone.

**Syntax**: `<percentage> | <length>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msHyphenateLimitZone](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphenatelimitzone)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23946

___

### msHyphens

• `Optional` **msHyphens**: [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty) \| [`HyphensProperty`](../modules/akashaproject_design_system._internal_.md#hyphensproperty)[]

The **`hyphens`** CSS property specifies how words should be hyphenated when text wraps across multiple lines. You can prevent hyphenation entirely, use hyphenation in manually-specified points within the text, or let the browser automatically insert hyphens where appropriate.

**Syntax**: `none | manual | auto`

**Initial value**: `manual`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msHyphens](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mshyphens)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23954

___

### msImeAlign

• `Optional` **msImeAlign**: [`MsImeAlignProperty`](../modules/akashaproject_design_system._internal_.md#msimealignproperty) \| [`MsImeAlignProperty`](../modules/akashaproject_design_system._internal_.md#msimealignproperty)[]

The **`-ms-ime-align`** CSS property is a Microsoft extension aligning the Input Method Editor (IME) candidate window box relative to the element on which the IME composition is active. The extension is implemented in Microsoft Edge and Internet Explorer 11.

**Syntax**: `auto | after`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msImeAlign](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msimealign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23962

___

### msImeMode

• `Optional` **msImeMode**: [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty) \| [`ImeModeProperty`](../modules/akashaproject_design_system._internal_.md#imemodeproperty)[]

The **`ime-mode`** CSS property controls the state of the input method editor (IME) for text fields. This property is obsolete.

**Syntax**: `auto | normal | active | inactive | disabled`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[msImeMode](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#msimemode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26028

___

### msJustifySelf

• `Optional` **msJustifySelf**: `string` \| `string`[]

The CSS **`justify-self`** property set the way a box is justified inside its alignment container along the appropriate axis.

**Syntax**: `auto | normal | stretch | <baseline-position> | <overflow-position>? [ <self-position> | left | right ]`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msJustifySelf](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msjustifyself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23970

___

### msLineBreak

• `Optional` **msLineBreak**: [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty) \| [`LineBreakProperty`](../modules/akashaproject_design_system._internal_.md#linebreakproperty)[]

The **`line-break`** CSS property sets how to break lines of Chinese, Japanese, or Korean (CJK) text when working with punctuation and symbols.

**Syntax**: `auto | loose | normal | strict | anywhere`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msLineBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mslinebreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23978

___

### msOrder

• `Optional` **msOrder**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msOrder](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msorder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23986

___

### msOverflowStyle

• `Optional` **msOverflowStyle**: [`MsOverflowStyleProperty`](../modules/akashaproject_design_system._internal_.md#msoverflowstyleproperty) \| [`MsOverflowStyleProperty`](../modules/akashaproject_design_system._internal_.md#msoverflowstyleproperty)[]

The **`-ms-overflow-style`** CSS property is a Microsoft extension controlling the behavior of scrollbars when the content of an element overflows.

**Syntax**: `auto | none | scrollbar | -ms-autohiding-scrollbar`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msOverflowStyle](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23994

___

### msOverflowX

• `Optional` **msOverflowX**: [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty) \| [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty)[]

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msOverflowX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24002

___

### msOverflowY

• `Optional` **msOverflowY**: [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty) \| [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty)[]

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msOverflowY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msoverflowy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24010

___

### msScrollChaining

• `Optional` **msScrollChaining**: [`MsScrollChainingProperty`](../modules/akashaproject_design_system._internal_.md#msscrollchainingproperty) \| [`MsScrollChainingProperty`](../modules/akashaproject_design_system._internal_.md#msscrollchainingproperty)[]

The `**-ms-scroll-chaining**` CSS property is a Microsoft extension that specifies the scrolling behavior that occurs when a user hits the scroll limit during a manipulation.

**Syntax**: `chained | none`

**Initial value**: `chained`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollChaining](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollchaining)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24018

___

### msScrollLimit

• `Optional` **msScrollLimit**: `string` \| `string`[]

The **\-ms-scroll-limit** CSS property is a Microsoft extension that specifies values for the `-ms-scroll-limit-x-min`, `-ms-scroll-limit-y-min`, `-ms-scroll-limit-x-max`, and `-ms-scroll-limit-y-max` properties.

**Syntax**: `<'-ms-scroll-limit-x-min'> <'-ms-scroll-limit-y-min'> <'-ms-scroll-limit-x-max'> <'-ms-scroll-limit-y-max'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollLimit](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25195

___

### msScrollLimitXMax

• `Optional` **msScrollLimitXMax**: [`MsScrollLimitXMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmaxproperty)<`TLength`\> \| [`MsScrollLimitXMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxmaxproperty)<`TLength`\>[]

The `**-ms-scroll-limit-x-max**` CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollLeft` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollLimitXMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitxmax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24026

___

### msScrollLimitXMin

• `Optional` **msScrollLimitXMin**: [`MsScrollLimitXMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxminproperty)<`TLength`\> \| [`MsScrollLimitXMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitxminproperty)<`TLength`\>[]

The **`-ms-scroll-limit-x-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollLeft` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollLimitXMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitxmin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24034

___

### msScrollLimitYMax

• `Optional` **msScrollLimitYMax**: [`MsScrollLimitYMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymaxproperty)<`TLength`\> \| [`MsScrollLimitYMaxProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimitymaxproperty)<`TLength`\>[]

The **`-ms-scroll-limit-y-max`** CSS property is a Microsoft extension that specifies the maximum value for the `Element.scrollTop` property.

**Syntax**: `auto | <length>`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollLimitYMax](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitymax)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24042

___

### msScrollLimitYMin

• `Optional` **msScrollLimitYMin**: [`MsScrollLimitYMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimityminproperty)<`TLength`\> \| [`MsScrollLimitYMinProperty`](../modules/akashaproject_design_system._internal_.md#msscrolllimityminproperty)<`TLength`\>[]

The **`-ms-scroll-limit-y-min`** CSS property is a Microsoft extension that specifies the minimum value for the `Element.scrollTop` property.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollLimitYMin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolllimitymin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24050

___

### msScrollRails

• `Optional` **msScrollRails**: [`MsScrollRailsProperty`](../modules/akashaproject_design_system._internal_.md#msscrollrailsproperty) \| [`MsScrollRailsProperty`](../modules/akashaproject_design_system._internal_.md#msscrollrailsproperty)[]

The **`-ms-scroll-rails`** CSS property is a Microsoft extension that specifies whether scrolling locks to the primary axis of motion.

**Syntax**: `none | railed`

**Initial value**: `railed`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollRails](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollrails)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24058

___

### msScrollSnapPointsX

• `Optional` **msScrollSnapPointsX**: `string` \| `string`[]

The **`-ms-scroll-snap-points-x`** CSS property is a Microsoft extension that specifies where snap-points will be located along the x-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollSnapPointsX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnappointsx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24066

___

### msScrollSnapPointsY

• `Optional` **msScrollSnapPointsY**: `string` \| `string`[]

The **`-ms-scroll-snap-points-y`** CSS property is a Microsoft extension that specifies where snap-points will be located along the y-axis.

**Syntax**: `snapInterval( <length-percentage>, <length-percentage> ) | snapList( <length-percentage># )`

**Initial value**: `snapInterval(0px, 100%)`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollSnapPointsY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnappointsy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24074

___

### msScrollSnapType

• `Optional` **msScrollSnapType**: [`MsScrollSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptypeproperty) \| [`MsScrollSnapTypeProperty`](../modules/akashaproject_design_system._internal_.md#msscrollsnaptypeproperty)[]

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | proximity | mandatory`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollSnapType](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24082

___

### msScrollSnapX

• `Optional` **msScrollSnapX**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-x` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-x'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollSnapX](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnapx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25201

___

### msScrollSnapY

• `Optional` **msScrollSnapY**: `string` \| `string`[]

The **`-ms-scroll-snap-x`** CSS shorthand property is a Microsoft extension that specifies values for the `-ms-scroll-snap-type` and `-ms-scroll-snap-points-y` properties.

**Syntax**: `<'-ms-scroll-snap-type'> <'-ms-scroll-snap-points-y'>`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollSnapY](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollsnapy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25207

___

### msScrollTranslation

• `Optional` **msScrollTranslation**: [`MsScrollTranslationProperty`](../modules/akashaproject_design_system._internal_.md#msscrolltranslationproperty) \| [`MsScrollTranslationProperty`](../modules/akashaproject_design_system._internal_.md#msscrolltranslationproperty)[]

The **`-ms-scroll-translation`** CSS property is a Microsoft extension that specifies whether vertical-to-horizontal scroll wheel translation occurs on the specified element.

**Syntax**: `none | vertical-to-horizontal`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollTranslation](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrolltranslation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24090

___

### msScrollbar3dlightColor

• `Optional` **msScrollbar3dlightColor**: `string` \| `string`[]

The **`-ms-scrollbar-3dlight-color`** CSS property is a Microsoft extension specifying the color of the top and left edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbar3dlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbar3dlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24098

___

### msScrollbarArrowColor

• `Optional` **msScrollbarArrowColor**: `string` \| `string`[]

The **`-ms-scrollbar-arrow-color`** CSS property is a Microsoft extension that specifies the color of the arrow elements of a scroll arrow.

**Syntax**: `<color>`

**Initial value**: `ButtonText`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarArrowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbararrowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24106

___

### msScrollbarBaseColor

• `Optional` **msScrollbarBaseColor**: `string` \| `string`[]

The `**-ms-scrollbar-base-color**` CSS property is a Microsoft extension that specifies the base color of the main elements of a scroll bar.

**Syntax**: `<color>`

**Initial value**: depends on user agent

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarBaseColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarbasecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24114

___

### msScrollbarDarkshadowColor

• `Optional` **msScrollbarDarkshadowColor**: `string` \| `string`[]

The **`-ms-scrollbar-darkshadow-color`** CSS property is a Microsoft extension that specifies the color of a scroll bar's gutter.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarDarkshadowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbardarkshadowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24122

___

### msScrollbarFaceColor

• `Optional` **msScrollbarFaceColor**: `string` \| `string`[]

The `**-ms-scrollbar-face-color**` CSS property is a Microsoft extension that specifies the color of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDFace`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarFaceColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarfacecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24130

___

### msScrollbarHighlightColor

• `Optional` **msScrollbarHighlightColor**: `string` \| `string`[]

The `**-ms-scrollbar-highlight-color**` CSS property is a Microsoft extension that specifies the color of the slider tray, the top and left edges of the scroll box, and the scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDHighlight`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarHighlightColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarhighlightcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24138

___

### msScrollbarShadowColor

• `Optional` **msScrollbarShadowColor**: `string` \| `string`[]

The **`-ms-scrollbar-shadow-color`** CSS property is a Microsoft extension that specifies the color of the bottom and right edges of the scroll box and scroll arrows of a scroll bar.

**Syntax**: `<color>`

**Initial value**: `ThreeDDarkShadow`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msScrollbarShadowColor](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msscrollbarshadowcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24146

___

### msScrollbarTrackColor

• `Optional` **msScrollbarTrackColor**: `string` \| `string`[]

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[msScrollbarTrackColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#msscrollbartrackcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26038

___

### msTextAutospace

• `Optional` **msTextAutospace**: [`MsTextAutospaceProperty`](../modules/akashaproject_design_system._internal_.md#mstextautospaceproperty) \| [`MsTextAutospaceProperty`](../modules/akashaproject_design_system._internal_.md#mstextautospaceproperty)[]

The **`-ms-text-autospace`** CSS property is a Microsoft extension that specifies the autospacing and narrow space width adjustment of text.

**Syntax**: `none | ideograph-alpha | ideograph-numeric | ideograph-parenthesis | ideograph-space`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTextAutospace](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextautospace)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24154

___

### msTextCombineHorizontal

• `Optional` **msTextCombineHorizontal**: `string` \| `string`[]

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTextCombineHorizontal](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextcombinehorizontal)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24162

___

### msTextOverflow

• `Optional` **msTextOverflow**: `string` \| `string`[]

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTextOverflow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstextoverflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24170

___

### msTouchAction

• `Optional` **msTouchAction**: `string` \| `string`[]

The **`touch-action`** CSS property sets how a region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTouchAction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstouchaction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24178

___

### msTouchSelect

• `Optional` **msTouchSelect**: [`MsTouchSelectProperty`](../modules/akashaproject_design_system._internal_.md#mstouchselectproperty) \| [`MsTouchSelectProperty`](../modules/akashaproject_design_system._internal_.md#mstouchselectproperty)[]

The **`-ms-touch-select`** CSS property is a Microsoft extension that toggles the gripper visual elements that enable touch text selection.

**Syntax**: `grippers | none`

**Initial value**: `grippers`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTouchSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstouchselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24186

___

### msTransform

• `Optional` **msTransform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransform](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24194

___

### msTransformOrigin

• `Optional` **msTransformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransformOrigin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24202

___

### msTransition

• `Optional` **msTransition**: `string` \| `string`[]

The **`transition`** CSS property is a shorthand property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

**Syntax**: `<single-transition>#`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransition](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25213

___

### msTransitionDelay

• `Optional` **msTransitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransitionDelay](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24210

___

### msTransitionDuration

• `Optional` **msTransitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransitionDuration](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24218

___

### msTransitionProperty

• `Optional` **msTransitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransitionProperty](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24226

___

### msTransitionTimingFunction

• `Optional` **msTransitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msTransitionTimingFunction](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mstransitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24234

___

### msUserSelect

• `Optional` **msUserSelect**: [`MsUserSelectProperty`](../modules/akashaproject_design_system._internal_.md#msuserselectproperty) \| [`MsUserSelectProperty`](../modules/akashaproject_design_system._internal_.md#msuserselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `none | element | text`

**Initial value**: `text`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msUserSelect](akashaproject_design_system._internal_.VendorPropertiesFallback.md#msuserselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24242

___

### msWordBreak

• `Optional` **msWordBreak**: [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty) \| [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty)[]

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msWordBreak](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswordbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24250

___

### msWrapFlow

• `Optional` **msWrapFlow**: [`MsWrapFlowProperty`](../modules/akashaproject_design_system._internal_.md#mswrapflowproperty) \| [`MsWrapFlowProperty`](../modules/akashaproject_design_system._internal_.md#mswrapflowproperty)[]

The **`-ms-wrap-flow`** CSS property is a Microsoft extension that specifies how exclusions impact inline content within block-level elements.

**Syntax**: `auto | both | start | end | maximum | clear`

**Initial value**: `auto`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msWrapFlow](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24258

___

### msWrapMargin

• `Optional` **msWrapMargin**: [`MsWrapMarginProperty`](../modules/akashaproject_design_system._internal_.md#mswrapmarginproperty)<`TLength`\> \| [`MsWrapMarginProperty`](../modules/akashaproject_design_system._internal_.md#mswrapmarginproperty)<`TLength`\>[]

The **`-ms-wrap-margin`** CSS property is a Microsoft extension that specifies a margin that offsets the inner wrap shape from other shapes.

**Syntax**: `<length>`

**Initial value**: `0`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msWrapMargin](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapmargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24266

___

### msWrapThrough

• `Optional` **msWrapThrough**: [`MsWrapThroughProperty`](../modules/akashaproject_design_system._internal_.md#mswrapthroughproperty) \| [`MsWrapThroughProperty`](../modules/akashaproject_design_system._internal_.md#mswrapthroughproperty)[]

The **`-ms-wrap-through`** CSS property is a Microsoft extension that specifies how content should wrap around an exclusion element.

**Syntax**: `wrap | none`

**Initial value**: `wrap`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msWrapThrough](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswrapthrough)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24274

___

### msWritingMode

• `Optional` **msWritingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress.

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

#### Inherited from

[VendorPropertiesFallback](akashaproject_design_system._internal_.VendorPropertiesFallback.md).[msWritingMode](akashaproject_design_system._internal_.VendorPropertiesFallback.md#mswritingmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:24282

___

### objectFit

• `Optional` **objectFit**: [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty) \| [`ObjectFitProperty`](../modules/akashaproject_design_system._internal_.md#objectfitproperty)[]

The **`object-fit`** CSS property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container.

**Syntax**: `fill | contain | cover | none | scale-down`

**Initial value**: `fill`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **32** | **36**  | **10** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/object-fit

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[objectFit](akashaproject_design_system._internal_.StandardPropertiesFallback.md#objectfit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20742

___

### objectPosition

• `Optional` **objectPosition**: [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\> \| [`ObjectPositionProperty`](../modules/akashaproject_design_system._internal_.md#objectpositionproperty)<`TLength`\>[]

The **`object-position`** CSS property specifies the alignment of the selected replaced element's contents within the element's box. Areas of the box which aren't covered by the replaced element's object will show the element's background.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **32** | **36**  | **10** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/object-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[objectPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#objectposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20756

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23228

___

### offsetAnchor

• `Optional` **offsetAnchor**: [`OffsetAnchorProperty`](../modules/akashaproject_design_system._internal_.md#offsetanchorproperty)<`TLength`\> \| [`OffsetAnchorProperty`](../modules/akashaproject_design_system._internal_.md#offsetanchorproperty)<`TLength`\>[]

**Syntax**: `auto | <position>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **79** | **72**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-anchor

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offsetAnchor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offsetanchor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20768

___

### offsetBlock

• `Optional` **offsetBlock**: [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\> \| [`InsetBlockProperty`](../modules/akashaproject_design_system._internal_.md#insetblockproperty)<`TLength`\>[]

The **`inset-block`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetBlock](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25454

___

### offsetBlockEnd

• `Optional` **offsetBlockEnd**: [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\> \| [`InsetBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#insetblockendproperty)<`TLength`\>[]

The **`inset-block-end`** CSS property defines the logical block end offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetBlockEnd](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25464

___

### offsetBlockStart

• `Optional` **offsetBlockStart**: [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\> \| [`InsetBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#insetblockstartproperty)<`TLength`\>[]

The **`inset-block-start`** CSS property defines the logical block start offset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetBlockStart](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25474

___

### offsetDistance

• `Optional` **offsetDistance**: [`OffsetDistanceProperty`](../modules/akashaproject_design_system._internal_.md#offsetdistanceproperty)<`TLength`\> \| [`OffsetDistanceProperty`](../modules/akashaproject_design_system._internal_.md#offsetdistanceproperty)<`TLength`\>[]

The **`offset-distance`** CSS property specifies a position along an `offset-path`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **55**         | **72**  |   No   | **79** | No  |
| 46 _(motion-distance)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-distance

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offsetDistance](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offsetdistance)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20783

___

### offsetInline

• `Optional` **offsetInline**: [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\> \| [`InsetInlineProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineproperty)<`TLength`\>[]

The **`inset-inline`** CSS property defines the logical block start and end offsets of an element, which maps to physical offsets depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top` and `bottom`, or `right` and `left` properties depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>{1,2}`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetInline](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25484

___

### offsetInlineEnd

• `Optional` **offsetInlineEnd**: [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\> \| [`InsetInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#insetinlineendproperty)<`TLength`\>[]

The **`inset-inline-end`** CSS property defines the logical inline end inset of an element, which maps to a physical inset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetInlineEnd](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25494

___

### offsetInlineStart

• `Optional` **offsetInlineStart**: [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\> \| [`InsetInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#insetinlinestartproperty)<`TLength`\>[]

The **`inset-inline-start`** CSS property defines the logical inline start inset of an element, which maps to a physical offset depending on the element's writing mode, directionality, and text orientation. It corresponds to the `top`, `right`, `bottom`, or `left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'top'>`

**Initial value**: `auto`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[offsetInlineStart](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#offsetinlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25504

___

### offsetPath

• `Optional` **offsetPath**: `string` \| `string`[]

The **`offset-path`** CSS property specifies a motion path for an element to follow and defines the element's positioning within the parent container or SVG coordinate system.

**Syntax**: `none | ray( [ <angle> && <size> && contain? ] ) | <path()> | <url> | [ <basic-shape> || <geometry-box> ]`

**Initial value**: `none`

|       Chrome       | Firefox | Safari |  Edge  | IE  |
| :----------------: | :-----: | :----: | :----: | :-: |
|       **55**       | **72**  |   No   | **79** | No  |
| 46 _(motion-path)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-path

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offsetPath](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offsetpath)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20798

___

### offsetRotate

• `Optional` **offsetRotate**: `string` \| `string`[]

The **`offset-rotate`** CSS property defines the direction of the element while positioning along the offset path.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offsetRotate](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offsetrotate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20813

___

### offsetRotation

• `Optional` **offsetRotation**: `string` \| `string`[]

The **`offset-rotate`** CSS property defines the direction of the element while positioning along the offset path.

**Syntax**: `[ auto | reverse ] || <angle>`

**Initial value**: `auto`

|         Chrome         | Firefox | Safari |  Edge  | IE  |
| :--------------------: | :-----: | :----: | :----: | :-: |
|         **56**         | **72**  |   No   | **79** | No  |
| 46 _(motion-rotation)_ |         |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/offset-rotate

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[offsetRotation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#offsetrotation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20828

___

### opacity

• `Optional` **opacity**: [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty) \| [`OpacityProperty`](../modules/akashaproject_design_system._internal_.md#opacityproperty)[]

The **`opacity`** CSS property sets the transparency of an element or the degree to which content behind an element is visible.

**Syntax**: `<alpha-value>`

**Initial value**: `1.0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **2**  | **12** | **9** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/opacity

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[opacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#opacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20842

___

### order

• `Optional` **order**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`order`** CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending `order` value and then by their source code order.

**Syntax**: `<integer>`

**Initial value**: `0`

|  Chrome  | Firefox | Safari  |  Edge  |    IE    |
| :------: | :-----: | :-----: | :----: | :------: |
|  **29**  | **20**  |  **9**  | **12** |  **11**  |
| 21 _-x-_ |         | 7 _-x-_ |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/order

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[order](akashaproject_design_system._internal_.StandardPropertiesFallback.md#order)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20857

___

### orphans

• `Optional` **orphans**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`orphans`** CSS property sets the minimum number of lines in a block container that must be shown at the _bottom_ of a page, region, or column.

**Syntax**: `<integer>`

**Initial value**: `2`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **25** |   No    | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/orphans

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[orphans](akashaproject_design_system._internal_.StandardPropertiesFallback.md#orphans)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20871

___

### outline

• `Optional` **outline**: [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\> \| [`OutlineProperty`](../modules/akashaproject_design_system._internal_.md#outlineproperty)<`TLength`\>[]

The **`outline`** CSS property is a shorthand to set various outline properties in a single declaration: `outline-style`, `outline-width`, and `outline-color`.

**Syntax**: `[ <'outline-color'> || <'outline-style'> || <'outline-width'> ]`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[outline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#outline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23240

___

### outlineColor

• `Optional` **outlineColor**: `string` \| `string`[]

The **`outline-color`** CSS property sets the color of an element's outline.

**Syntax**: `<color> | invert`

**Initial value**: `invert`, for browsers supporting it, `currentColor` for the other

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[outlineColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#outlinecolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20885

___

### outlineOffset

• `Optional` **outlineOffset**: [`OutlineOffsetProperty`](../modules/akashaproject_design_system._internal_.md#outlineoffsetproperty)<`TLength`\> \| [`OutlineOffsetProperty`](../modules/akashaproject_design_system._internal_.md#outlineoffsetproperty)<`TLength`\>[]

The **`outline-offset`** CSS property sets the amount of space between an outline and the edge or border of an element.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **1**  | **1.5** | **1.2** | **15** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-offset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[outlineOffset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#outlineoffset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20899

___

### outlineStyle

• `Optional` **outlineStyle**: `string` \| `string`[]

The **`outline-style`** CSS property sets the style of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `auto | <'border-style'>`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[outlineStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#outlinestyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20913

___

### outlineWidth

• `Optional` **outlineWidth**: [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\> \| [`OutlineWidthProperty`](../modules/akashaproject_design_system._internal_.md#outlinewidthproperty)<`TLength`\>[]

The **`outline-width`** CSS property sets the thickness of an element's outline. An outline is a line that is drawn around an element, outside the `border`.

**Syntax**: `<line-width>`

**Initial value**: `medium`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **1.5** | **1.2** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/outline-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[outlineWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#outlinewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20927

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

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[overflow](akashaproject_design_system._internal_.SvgPropertiesFallback.md#overflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23254

___

### overflowAnchor

• `Optional` **overflowAnchor**: [`OverflowAnchorProperty`](../modules/akashaproject_design_system._internal_.md#overflowanchorproperty) \| [`OverflowAnchorProperty`](../modules/akashaproject_design_system._internal_.md#overflowanchorproperty)[]

**Syntax**: `auto | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **56** | **66**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-anchor

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowAnchor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowanchor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20939

___

### overflowBlock

• `Optional` **overflowBlock**: [`OverflowBlockProperty`](../modules/akashaproject_design_system._internal_.md#overflowblockproperty) \| [`OverflowBlockProperty`](../modules/akashaproject_design_system._internal_.md#overflowblockproperty)[]

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **69**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20951

___

### overflowClipBox

• `Optional` **overflowClipBox**: [`OverflowClipBoxProperty`](../modules/akashaproject_design_system._internal_.md#overflowclipboxproperty) \| [`OverflowClipBoxProperty`](../modules/akashaproject_design_system._internal_.md#overflowclipboxproperty)[]

The **`overflow-clip-box`** CSS property specifies relative to which box the clipping happens when there is an overflow. It is short hand for the `overflow-clip-box-inline` and `overflow-clip-box-block` properties.

**Syntax**: `padding-box | content-box`

**Initial value**: `padding-box`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **29**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Mozilla/Gecko/Chrome/CSS/overflow-clip-box

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowClipBox](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowclipbox)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20965

___

### overflowClipMargin

• `Optional` **overflowClipMargin**: [`OverflowClipMarginProperty`](../modules/akashaproject_design_system._internal_.md#overflowclipmarginproperty)<`TLength`\> \| [`OverflowClipMarginProperty`](../modules/akashaproject_design_system._internal_.md#overflowclipmarginproperty)<`TLength`\>[]

**Syntax**: `<visual-box> || <length [0,∞]>`

**Initial value**: `0px`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **90** |   No    |   No   | **90** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-clip-margin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowClipMargin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowclipmargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20977

___

### overflowInline

• `Optional` **overflowInline**: [`OverflowInlineProperty`](../modules/akashaproject_design_system._internal_.md#overflowinlineproperty) \| [`OverflowInlineProperty`](../modules/akashaproject_design_system._internal_.md#overflowinlineproperty)[]

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **69**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowinline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:20989

___

### overflowWrap

• `Optional` **overflowWrap**: [`OverflowWrapProperty`](../modules/akashaproject_design_system._internal_.md#overflowwrapproperty) \| [`OverflowWrapProperty`](../modules/akashaproject_design_system._internal_.md#overflowwrapproperty)[]

The `**overflow-wrap**` CSS property sets whether the browser should insert line breaks within words to prevent text from overflowing its content box.

**Syntax**: `normal | break-word | anywhere`

**Initial value**: `normal`

|     Chrome      |      Firefox      |     Safari      |       Edge       |          IE           |
| :-------------: | :---------------: | :-------------: | :--------------: | :-------------------: |
|     **23**      |      **49**       |      **7**      |      **18**      | **5.5** _(word-wrap)_ |
| 1 _(word-wrap)_ | 3.5 _(word-wrap)_ | 1 _(word-wrap)_ | 12 _(word-wrap)_ |                       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-wrap

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowWrap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowwrap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21004

___

### overflowX

• `Optional` **overflowX**: [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty) \| [`OverflowXProperty`](../modules/akashaproject_design_system._internal_.md#overflowxproperty)[]

The **`overflow-x`** CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **3.5** | **3**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-x

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowX](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21018

___

### overflowY

• `Optional` **overflowY**: [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty) \| [`OverflowYProperty`](../modules/akashaproject_design_system._internal_.md#overflowyproperty)[]

The **`overflow-y`** CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

**Syntax**: `visible | hidden | clip | scroll | auto`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  | **3.5** | **3**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overflow-y

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overflowY](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overflowy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21032

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overscrollBehavior](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overscrollbehavior)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23268

___

### overscrollBehaviorBlock

• `Optional` **overscrollBehaviorBlock**: [`OverscrollBehaviorBlockProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorblockproperty) \| [`OverscrollBehaviorBlockProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorblockproperty)[]

The **`overscroll-behavior-block`** CSS property sets the browser's behavior when the block direction boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **77** | **73**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overscrollBehaviorBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overscrollbehaviorblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21046

___

### overscrollBehaviorInline

• `Optional` **overscrollBehaviorInline**: [`OverscrollBehaviorInlineProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorinlineproperty) \| [`OverscrollBehaviorInlineProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorinlineproperty)[]

The **`overscroll-behavior-inline`** CSS property sets the browser's behavior when the inline direction boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **77** | **73**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overscrollBehaviorInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overscrollbehaviorinline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21060

___

### overscrollBehaviorX

• `Optional` **overscrollBehaviorX**: [`OverscrollBehaviorXProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorxproperty) \| [`OverscrollBehaviorXProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehaviorxproperty)[]

The **`overscroll-behavior-x`** CSS property sets the browser's behavior when the horizontal boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-x

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overscrollBehaviorX](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overscrollbehaviorx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21074

___

### overscrollBehaviorY

• `Optional` **overscrollBehaviorY**: [`OverscrollBehaviorYProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehavioryproperty) \| [`OverscrollBehaviorYProperty`](../modules/akashaproject_design_system._internal_.md#overscrollbehavioryproperty)[]

The **`overscroll-behavior-y`** CSS property sets the browser's behavior when the vertical boundary of a scrolling area is reached.

**Syntax**: `contain | none | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **63** | **59**  |   No   | **18** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/overscroll-behavior-y

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[overscrollBehaviorY](akashaproject_design_system._internal_.StandardPropertiesFallback.md#overscrollbehaviory)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21088

___

### padding

• `Optional` **padding**: [`PaddingProperty`](../modules/akashaproject_design_system._internal_.md#paddingproperty)<`TLength`\> \| [`PaddingProperty`](../modules/akashaproject_design_system._internal_.md#paddingproperty)<`TLength`\>[]

The **`padding`** CSS property sets the padding area on all four sides of an element. It is a shorthand for `padding-top`, `padding-right`, `padding-bottom`, and `padding-left`.

**Syntax**: `[ <length> | <percentage> ]{1,4}`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[padding](akashaproject_design_system._internal_.StandardPropertiesFallback.md#padding)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23280

___

### paddingBlock

• `Optional` **paddingBlock**: [`PaddingBlockProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockproperty)<`TLength`\> \| [`PaddingBlockProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockproperty)<`TLength`\>[]

The **`padding-block`** CSS property defines the logical block start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21102

___

### paddingBlockEnd

• `Optional` **paddingBlockEnd**: [`PaddingBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockendproperty)<`TLength`\> \| [`PaddingBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockendproperty)<`TLength`\>[]

The **`padding-block-end`** CSS property defines the logical block end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21116

___

### paddingBlockStart

• `Optional` **paddingBlockStart**: [`PaddingBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockstartproperty)<`TLength`\> \| [`PaddingBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#paddingblockstartproperty)<`TLength`\>[]

The **`padding-block-start`** CSS property defines the logical block start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **41**  | **12.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21130

___

### paddingBottom

• `Optional` **paddingBottom**: [`PaddingBottomProperty`](../modules/akashaproject_design_system._internal_.md#paddingbottomproperty)<`TLength`\> \| [`PaddingBottomProperty`](../modules/akashaproject_design_system._internal_.md#paddingbottomproperty)<`TLength`\>[]

The **`padding-bottom`** CSS property sets the height of the padding area on the bottom of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21144

___

### paddingInline

• `Optional` **paddingInline**: [`PaddingInlineProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineproperty)<`TLength`\> \| [`PaddingInlineProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineproperty)<`TLength`\>[]

The **`padding-inline`** CSS property defines the logical inline start and end padding of an element, which maps to physical padding properties depending on the element's writing mode, directionality, and text orientation.

**Syntax**: `<'padding-left'>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **66**  | **14.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddinginline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21158

___

### paddingInlineEnd

• `Optional` **paddingInlineEnd**: [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\> \| [`PaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlineendproperty)<`TLength`\>[]

The **`padding-inline-end`** CSS property defines the logical inline end padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|          Chrome           |        Firefox         |          Safari           |  Edge  | IE  |
| :-----------------------: | :--------------------: | :-----------------------: | :----: | :-: |
|          **69**           |         **41**         |         **12.1**          | **79** | No  |
| 2 _(-webkit-padding-end)_ | 3 _(-moz-padding-end)_ | 3 _(-webkit-padding-end)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddinginlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21173

___

### paddingInlineStart

• `Optional` **paddingInlineStart**: [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\> \| [`PaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#paddinginlinestartproperty)<`TLength`\>[]

The **`padding-inline-start`** CSS property defines the logical inline start padding of an element, which maps to a physical padding depending on the element's writing mode, directionality, and text orientation. It corresponds to the `padding-top`, `padding-right`, `padding-bottom`, or `padding-left` property depending on the values defined for `writing-mode`, `direction`, and `text-orientation`.

**Syntax**: `<'padding-left'>`

**Initial value**: `0`

|           Chrome            |         Firefox          |           Safari            |  Edge  | IE  |
| :-------------------------: | :----------------------: | :-------------------------: | :----: | :-: |
|           **69**            |          **41**          |          **12.1**           | **79** | No  |
| 2 _(-webkit-padding-start)_ | 3 _(-moz-padding-start)_ | 3 _(-webkit-padding-start)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddinginlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21188

___

### paddingLeft

• `Optional` **paddingLeft**: [`PaddingLeftProperty`](../modules/akashaproject_design_system._internal_.md#paddingleftproperty)<`TLength`\> \| [`PaddingLeftProperty`](../modules/akashaproject_design_system._internal_.md#paddingleftproperty)<`TLength`\>[]

The **`padding-left`** CSS property sets the width of the padding area on the left side of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21202

___

### paddingRight

• `Optional` **paddingRight**: [`PaddingRightProperty`](../modules/akashaproject_design_system._internal_.md#paddingrightproperty)<`TLength`\> \| [`PaddingRightProperty`](../modules/akashaproject_design_system._internal_.md#paddingrightproperty)<`TLength`\>[]

The **`padding-right`** CSS property sets the width of the padding area on the right side of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21216

___

### paddingTop

• `Optional` **paddingTop**: [`PaddingTopProperty`](../modules/akashaproject_design_system._internal_.md#paddingtopproperty)<`TLength`\> \| [`PaddingTopProperty`](../modules/akashaproject_design_system._internal_.md#paddingtopproperty)<`TLength`\>[]

The **`padding-top`** padding area on the top of an element.

**Syntax**: `<length> | <percentage>`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/padding-top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[paddingTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#paddingtop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21230

___

### pageBreakAfter

• `Optional` **pageBreakAfter**: [`PageBreakAfterProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakafterproperty) \| [`PageBreakAfterProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakafterproperty)[]

The **`page-break-after`** CSS property adjusts page breaks _after_ the current element.

**Syntax**: `auto | always | avoid | left | right | recto | verso`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-after

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[pageBreakAfter](akashaproject_design_system._internal_.StandardPropertiesFallback.md#pagebreakafter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21244

___

### pageBreakBefore

• `Optional` **pageBreakBefore**: [`PageBreakBeforeProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakbeforeproperty) \| [`PageBreakBeforeProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakbeforeproperty)[]

The **`page-break-before`** CSS property adjusts page breaks _before_ the current element.

**Syntax**: `auto | always | avoid | left | right | recto | verso`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **1**  | **1.2** | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-before

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[pageBreakBefore](akashaproject_design_system._internal_.StandardPropertiesFallback.md#pagebreakbefore)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21258

___

### pageBreakInside

• `Optional` **pageBreakInside**: [`PageBreakInsideProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakinsideproperty) \| [`PageBreakInsideProperty`](../modules/akashaproject_design_system._internal_.md#pagebreakinsideproperty)[]

The **`page-break-inside`** CSS property adjusts page breaks _inside_ the current element.

**Syntax**: `auto | avoid`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  | **19**  | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/page-break-inside

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[pageBreakInside](akashaproject_design_system._internal_.StandardPropertiesFallback.md#pagebreakinside)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21272

___

### paintOrder

• `Optional` **paintOrder**: `string` \| `string`[]

The **`paint-order`** CSS property lets you control the order in which the fill and stroke (and painting markers) of text content and shapes are drawn.

**Syntax**: `normal | [ fill || stroke || markers ]`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **35** | **60**  | **8**  | **17** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/paint-order

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[paintOrder](akashaproject_design_system._internal_.SvgPropertiesFallback.md#paintorder)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21286

___

### perspective

• `Optional` **perspective**: [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\> \| [`PerspectiveProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveproperty)<`TLength`\>[]

The **`perspective`** CSS property determines the distance between the z=0 plane and the user in order to give a 3D-positioned element some perspective. Each 3D element with z>0 becomes larger; each 3D-element with z<0 becomes smaller. The strength of the effect is determined by the value of this property.

**Syntax**: `none | <length>`

**Initial value**: `none`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[perspective](akashaproject_design_system._internal_.StandardPropertiesFallback.md#perspective)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21301

___

### perspectiveOrigin

• `Optional` **perspectiveOrigin**: [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\> \| [`PerspectiveOriginProperty`](../modules/akashaproject_design_system._internal_.md#perspectiveoriginproperty)<`TLength`\>[]

The **`perspective-origin`** CSS property determines the position at which the viewer is looking. It is used as the _vanishing point_ by the `perspective` property.

**Syntax**: `<position>`

**Initial value**: `50% 50%`

|  Chrome  | Firefox  | Safari  |  Edge  |   IE   |
| :------: | :------: | :-----: | :----: | :----: |
|  **36**  |  **16**  |  **9**  | **12** | **10** |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/perspective-origin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[perspectiveOrigin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#perspectiveorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21316

___

### placeContent

• `Optional` **placeContent**: `string` \| `string`[]

The `**place-content**` CSS property is a shorthand for `align-content` and `justify-content`. It can be used in any layout method which utilizes both of these alignment values.

**Syntax**: `<'align-content'> <'justify-content'>?`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **9**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-content

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[placeContent](akashaproject_design_system._internal_.StandardPropertiesFallback.md#placecontent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21330

___

### placeItems

• `Optional` **placeItems**: `string` \| `string`[]

The CSS **`place-items`** shorthand property sets the `align-items` and `justify-items` properties, respectively. If the second value is not set, the first value is also used for it.

**Syntax**: `<'align-items'> <'justify-items'>?`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **59** | **45**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/place-items

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[placeItems](akashaproject_design_system._internal_.StandardPropertiesFallback.md#placeitems)

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[placeSelf](akashaproject_design_system._internal_.StandardPropertiesFallback.md#placeself)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23304

___

### pointerEvents

• `Optional` **pointerEvents**: [`PointerEventsProperty`](../modules/akashaproject_design_system._internal_.md#pointereventsproperty) \| [`PointerEventsProperty`](../modules/akashaproject_design_system._internal_.md#pointereventsproperty)[]

The **`pointer-events`** CSS property sets under what circumstances (if any) a particular graphic element can become the target of mouse events.

**Syntax**: `auto | none | visiblePainted | visibleFill | visibleStroke | visible | painted | fill | stroke | all | inherit`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
| **1**  | **1.5** | **4**  | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/pointer-events

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[pointerEvents](akashaproject_design_system._internal_.SvgPropertiesFallback.md#pointerevents)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21344

___

### position

• `Optional` **position**: [`PositionProperty`](../modules/akashaproject_design_system._internal_.md#positionproperty) \| [`PositionProperty`](../modules/akashaproject_design_system._internal_.md#positionproperty)[]

The **`position`** CSS property sets how an element is positioned in a document. The `top`, `right`, `bottom`, and `left` properties determine the final location of positioned elements.

**Syntax**: `static | relative | absolute | sticky | fixed`

**Initial value**: `static`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[position](akashaproject_design_system._internal_.StandardPropertiesFallback.md#position)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21358

___

### quotes

• `Optional` **quotes**: `string` \| `string`[]

The **`quotes`** CSS property sets how quotation marks appear.

**Syntax**: `none | auto | [ <string> <string> ]+`

**Initial value**: depends on user agent

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **11** | **1.5** | **9**  | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/quotes

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[quotes](akashaproject_design_system._internal_.StandardPropertiesFallback.md#quotes)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21372

___

### resize

• `Optional` **resize**: [`ResizeProperty`](../modules/akashaproject_design_system._internal_.md#resizeproperty) \| [`ResizeProperty`](../modules/akashaproject_design_system._internal_.md#resizeproperty)[]

The **`resize`** CSS property sets whether an element is resizable, and if so, in which directions.

**Syntax**: `none | both | horizontal | vertical | block | inline`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **1**  |  **4**  | **3**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/resize

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[resize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#resize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21386

___

### right

• `Optional` **right**: [`RightProperty`](../modules/akashaproject_design_system._internal_.md#rightproperty)<`TLength`\> \| [`RightProperty`](../modules/akashaproject_design_system._internal_.md#rightproperty)<`TLength`\>[]

The **`right`** CSS property participates in specifying the horizontal position of a _positioned element_. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[right](akashaproject_design_system._internal_.StandardPropertiesFallback.md#right)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21400

___

### rotate

• `Optional` **rotate**: `string` \| `string`[]

The **`rotate`** CSS property allows you to specify rotation transforms individually and independantly of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <angle> | [ x | y | z | <number>{3} ] && <angle>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/rotate

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[rotate](akashaproject_design_system._internal_.StandardPropertiesFallback.md#rotate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21414

___

### rowGap

• `Optional` **rowGap**: [`RowGapProperty`](../modules/akashaproject_design_system._internal_.md#rowgapproperty)<`TLength`\> \| [`RowGapProperty`](../modules/akashaproject_design_system._internal_.md#rowgapproperty)<`TLength`\>[]

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

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[rowGap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#rowgap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21443

___

### rubyAlign

• `Optional` **rubyAlign**: [`RubyAlignProperty`](../modules/akashaproject_design_system._internal_.md#rubyalignproperty) \| [`RubyAlignProperty`](../modules/akashaproject_design_system._internal_.md#rubyalignproperty)[]

The `**ruby-align**` CSS property defines the distribution of the different ruby elements over the base.

**Syntax**: `start | center | space-between | space-around`

**Initial value**: `space-around`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **38**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/ruby-align

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[rubyAlign](akashaproject_design_system._internal_.StandardPropertiesFallback.md#rubyalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21457

___

### rubyMerge

• `Optional` **rubyMerge**: [`RubyMergeProperty`](../modules/akashaproject_design_system._internal_.md#rubymergeproperty) \| [`RubyMergeProperty`](../modules/akashaproject_design_system._internal_.md#rubymergeproperty)[]

**Syntax**: `separate | collapse | auto`

**Initial value**: `separate`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[rubyMerge](akashaproject_design_system._internal_.StandardPropertiesFallback.md#rubymerge)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21463

___

### rubyPosition

• `Optional` **rubyPosition**: `string` \| `string`[]

The `**ruby-position**` CSS property defines the position of a ruby element relatives to its base element. It can be position over the element (`over`), under it (`under`), or between the characters, on their right side (`inter-character`).

**Syntax**: `[ alternate || [ over | under ] ] | inter-character`

**Initial value**: `alternate`

| Chrome  | Firefox |    Safari     | Edge  | IE  |
| :-----: | :-----: | :-----------: | :---: | :-: |
| **84**  | **38**  | **6.1** _-x-_ | 12-79 | No  |
| 1 _-x-_ |         |               |       |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/ruby-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[rubyPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#rubyposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21478

___

### scale

• `Optional` **scale**: [`ScaleProperty`](../modules/akashaproject_design_system._internal_.md#scaleproperty) \| [`ScaleProperty`](../modules/akashaproject_design_system._internal_.md#scaleproperty)[]

The **`scale`** CSS property allows you to specify scale transforms individually and independantly of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <number>{1,3}`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scale

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scale](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scale)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21492

___

### scrollBehavior

• `Optional` **scrollBehavior**: [`ScrollBehaviorProperty`](../modules/akashaproject_design_system._internal_.md#scrollbehaviorproperty) \| [`ScrollBehaviorProperty`](../modules/akashaproject_design_system._internal_.md#scrollbehaviorproperty)[]

The **`scroll-behavior`** CSS property sets the behavior for a scrolling box when scrolling is triggered by the navigation or CSSOM scrolling APIs.

**Syntax**: `auto | smooth`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **61** | **36**  |  n/a   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-behavior

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollBehavior](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollbehavior)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21506

___

### scrollMargin

• `Optional` **scrollMargin**: [`ScrollMarginProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginproperty)<`TLength`\> \| [`ScrollMarginProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginproperty)<`TLength`\>[]

The **`scroll-margin`** property is a shorthand property which sets all of the `scroll-margin` longhands, assigning values much like the `margin` property does for the `margin-*` longhands.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** | **90**  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMargin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21521

___

### scrollMarginBlock

• `Optional` **scrollMarginBlock**: [`ScrollMarginBlockProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockproperty)<`TLength`\> \| [`ScrollMarginBlockProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockproperty)<`TLength`\>[]

The `scroll-margin-block` property is a shorthand property which sets the scroll-margin longhands in the block dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21535

___

### scrollMarginBlockEnd

• `Optional` **scrollMarginBlockEnd**: [`ScrollMarginBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockendproperty)<`TLength`\> \| [`ScrollMarginBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockendproperty)<`TLength`\>[]

The `scroll-margin-block-end` property defines the margin of the scroll snap area at the end of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21549

___

### scrollMarginBlockStart

• `Optional` **scrollMarginBlockStart**: [`ScrollMarginBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockstartproperty)<`TLength`\> \| [`ScrollMarginBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginblockstartproperty)<`TLength`\>[]

The `scroll-margin-block-start` property defines the margin of the scroll snap area at the start of the block dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21563

___

### scrollMarginBottom

• `Optional` **scrollMarginBottom**: [`ScrollMarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottomproperty)<`TLength`\> \| [`ScrollMarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottomproperty)<`TLength`\>[]

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21578

___

### scrollMarginInline

• `Optional` **scrollMarginInline**: [`ScrollMarginInlineProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineproperty)<`TLength`\> \| [`ScrollMarginInlineProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineproperty)<`TLength`\>[]

The `scroll-margin-inline` property is a shorthand property which sets the scroll-margin longhands in the inline dimension.

**Syntax**: `<length>{1,2}`

**Initial value**: `0`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **68**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmargininline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21592

___

### scrollMarginInlineEnd

• `Optional` **scrollMarginInlineEnd**: [`ScrollMarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineendproperty)<`TLength`\> \| [`ScrollMarginInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlineendproperty)<`TLength`\>[]

The `scroll-margin-inline-end` property defines the margin of the scroll snap area at the end of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmargininlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21606

___

### scrollMarginInlineStart

• `Optional` **scrollMarginInlineStart**: [`ScrollMarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlinestartproperty)<`TLength`\> \| [`ScrollMarginInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargininlinestartproperty)<`TLength`\>[]

The `scroll-margin-inline-start` property defines the margin of the scroll snap area at the start of the inline dimension that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **69** | **68**  | **14.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmargininlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21620

___

### scrollMarginLeft

• `Optional` **scrollMarginLeft**: [`ScrollMarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginleftproperty)<`TLength`\> \| [`ScrollMarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginleftproperty)<`TLength`\>[]

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21635

___

### scrollMarginRight

• `Optional` **scrollMarginRight**: [`ScrollMarginRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginrightproperty)<`TLength`\> \| [`ScrollMarginRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginrightproperty)<`TLength`\>[]

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmarginright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21650

___

### scrollMarginTop

• `Optional` **scrollMarginTop**: [`ScrollMarginTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargintopproperty)<`TLength`\> \| [`ScrollMarginTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargintopproperty)<`TLength`\>[]

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollMarginTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollmargintop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21665

___

### scrollPadding

• `Optional` **scrollPadding**: [`ScrollPaddingProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingproperty)<`TLength`\> \| [`ScrollPaddingProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingproperty)<`TLength`\>[]

The scroll-padding property is a shorthand property which sets all of the scroll-padding longhands, assigning values much like the padding property does for the padding-\* longhands.

The scroll-padding properties define offsets for the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `[ auto | <length-percentage> ]{1,4}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPadding](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpadding)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21681

___

### scrollPaddingBlock

• `Optional` **scrollPaddingBlock**: [`ScrollPaddingBlockProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockproperty)<`TLength`\> \| [`ScrollPaddingBlockProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockproperty)<`TLength`\>[]

The `scroll-padding-block` property is a shorthand property which sets the scroll-padding longhands for the block dimension.

The scroll-padding properties define offsets for the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingBlock](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingblock)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21697

___

### scrollPaddingBlockEnd

• `Optional` **scrollPaddingBlockEnd**: [`ScrollPaddingBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockendproperty)<`TLength`\> \| [`ScrollPaddingBlockEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockendproperty)<`TLength`\>[]

The `scroll-padding-block-end` property defines offsets for the end edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingBlockEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingblockend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21711

___

### scrollPaddingBlockStart

• `Optional` **scrollPaddingBlockStart**: [`ScrollPaddingBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockstartproperty)<`TLength`\> \| [`ScrollPaddingBlockStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingblockstartproperty)<`TLength`\>[]

The `scroll-padding-block-start` property defines offsets for the start edge in the block dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-block-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingBlockStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingblockstart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21725

___

### scrollPaddingBottom

• `Optional` **scrollPaddingBottom**: [`ScrollPaddingBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingbottomproperty)<`TLength`\> \| [`ScrollPaddingBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingbottomproperty)<`TLength`\>[]

The `scroll-padding-bottom` property defines offsets for the bottom of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21739

___

### scrollPaddingInline

• `Optional` **scrollPaddingInline**: [`ScrollPaddingInlineProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineproperty)<`TLength`\> \| [`ScrollPaddingInlineProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineproperty)<`TLength`\>[]

The `scroll-padding-inline` property is a shorthand property which sets the scroll-padding longhands for the inline dimension.

The scroll-padding properties define offsets for the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `[ auto | <length-percentage> ]{1,2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingInline](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddinginline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21755

___

### scrollPaddingInlineEnd

• `Optional` **scrollPaddingInlineEnd**: [`ScrollPaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineendproperty)<`TLength`\> \| [`ScrollPaddingInlineEndProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlineendproperty)<`TLength`\>[]

The `scroll-padding-inline-end` property defines offsets for the end edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-end

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingInlineEnd](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddinginlineend)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21769

___

### scrollPaddingInlineStart

• `Optional` **scrollPaddingInlineStart**: [`ScrollPaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlinestartproperty)<`TLength`\> \| [`ScrollPaddingInlineStartProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddinginlinestartproperty)<`TLength`\>[]

The `scroll-padding-inline-start` property defines offsets for the start edge in the inline dimension of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-inline-start

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingInlineStart](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddinginlinestart)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21783

___

### scrollPaddingLeft

• `Optional` **scrollPaddingLeft**: [`ScrollPaddingLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingleftproperty)<`TLength`\> \| [`ScrollPaddingLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingleftproperty)<`TLength`\>[]

The `scroll-padding-left` property defines offsets for the left of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21797

___

### scrollPaddingRight

• `Optional` **scrollPaddingRight**: [`ScrollPaddingRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingrightproperty)<`TLength`\> \| [`ScrollPaddingRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingrightproperty)<`TLength`\>[]

The `scroll-padding-right` property defines offsets for the right of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21811

___

### scrollPaddingTop

• `Optional` **scrollPaddingTop**: [`ScrollPaddingTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingtopproperty)<`TLength`\> \| [`ScrollPaddingTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollpaddingtopproperty)<`TLength`\>[]

The `scroll-padding-top` property defines offsets for the top of the optimal viewing region of the scrollport: the region used as the target region for placing things in view of the user. This allows the author to exclude regions of the scrollport that are obscured by other content (such as fixed-positioned toolbars or sidebars) or simply to put more breathing room between a targetted element and the edges of the scrollport.

**Syntax**: `auto | <length-percentage>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-padding-top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollPaddingTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollpaddingtop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21825

___

### scrollSnapAlign

• `Optional` **scrollSnapAlign**: `string` \| `string`[]

The `scroll-snap-align` property specifies the box’s snap position as an alignment of its snap area (as the alignment subject) within its snap container’s snapport (as the alignment container). The two values specify the snapping alignment in the block axis and inline axis, respectively. If only one value is specified, the second value defaults to the same value.

**Syntax**: `[ none | start | end | center ]{1,2}`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **69** | **68**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-align

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapAlign](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21839

___

### scrollSnapCoordinate

• `Optional` **scrollSnapCoordinate**: [`ScrollSnapCoordinateProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinateproperty)<`TLength`\> \| [`ScrollSnapCoordinateProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapcoordinateproperty)<`TLength`\>[]

The **`scroll-snap-coordinate`** CSS property defines the x and y coordinate positions within an element that will align with its nearest ancestor scroll container's `scroll-snap-destination` for each respective axis.

**Syntax**: `none | <position>#`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapCoordinate](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnapcoordinate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25514

___

### scrollSnapDestination

• `Optional` **scrollSnapDestination**: [`ScrollSnapDestinationProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestinationproperty)<`TLength`\> \| [`ScrollSnapDestinationProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapdestinationproperty)<`TLength`\>[]

The **`scroll-snap-destination`** CSS property defines the position in x and y coordinates within the scroll container's visual viewport which element snap points align with.

**Syntax**: `<position>`

**Initial value**: `0px 0px`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapDestination](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnapdestination)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25524

___

### scrollSnapMargin

• `Optional` **scrollSnapMargin**: [`ScrollMarginProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginproperty)<`TLength`\> \| [`ScrollMarginProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginproperty)<`TLength`\>[]

The **`scroll-margin`** property is a shorthand property which sets all of the `scroll-margin` longhands, assigning values much like the `margin` property does for the `margin-*` longhands.

**Syntax**: `<length>{1,4}`

**Initial value**: `0`

| Chrome | Firefox |          Safari           |  Edge  | IE  |
| :----: | :-----: | :-----------------------: | :----: | :-: |
| **69** |  68-90  |         **14.1**          | **79** | No  |
|        |         | 11 _(scroll-snap-margin)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapMargin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapmargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21854

___

### scrollSnapMarginBottom

• `Optional` **scrollSnapMarginBottom**: [`ScrollMarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottomproperty)<`TLength`\> \| [`ScrollMarginBottomProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginbottomproperty)<`TLength`\>[]

The `scroll-margin-bottom` property defines the bottom margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |              Safari              |  Edge  | IE  |
| :----: | :-----: | :------------------------------: | :----: | :-: |
| **69** | **68**  |             **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-bottom)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-bottom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapMarginBottom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapmarginbottom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21869

___

### scrollSnapMarginLeft

• `Optional` **scrollSnapMarginLeft**: [`ScrollMarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginleftproperty)<`TLength`\> \| [`ScrollMarginLeftProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginleftproperty)<`TLength`\>[]

The `scroll-margin-left` property defines the left margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari             |  Edge  | IE  |
| :----: | :-----: | :----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-left)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-left

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapMarginLeft](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapmarginleft)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21884

___

### scrollSnapMarginRight

• `Optional` **scrollSnapMarginRight**: [`ScrollMarginRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginrightproperty)<`TLength`\> \| [`ScrollMarginRightProperty`](../modules/akashaproject_design_system._internal_.md#scrollmarginrightproperty)<`TLength`\>[]

The `scroll-margin-right` property defines the right margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |             Safari              |  Edge  | IE  |
| :----: | :-----: | :-----------------------------: | :----: | :-: |
| **69** | **68**  |            **14.1**             | **79** | No  |
|        |         | 11 _(scroll-snap-margin-right)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-right

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapMarginRight](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapmarginright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21899

___

### scrollSnapMarginTop

• `Optional` **scrollSnapMarginTop**: [`ScrollMarginTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargintopproperty)<`TLength`\> \| [`ScrollMarginTopProperty`](../modules/akashaproject_design_system._internal_.md#scrollmargintopproperty)<`TLength`\>[]

The `scroll-margin-top` property defines the top margin of the scroll snap area that is used for snapping this box to the snapport. The scroll snap area is determined by taking the transformed border box, finding its rectangular bounding box (axis-aligned in the scroll container’s coordinate space), then adding the specified outsets.

**Syntax**: `<length>`

**Initial value**: `0`

| Chrome | Firefox |            Safari             |  Edge  | IE  |
| :----: | :-----: | :---------------------------: | :----: | :-: |
| **69** | **68**  |           **14.1**            | **79** | No  |
|        |         | 11 _(scroll-snap-margin-top)_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-margin-top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapMarginTop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapmargintop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21914

___

### scrollSnapPointsX

• `Optional` **scrollSnapPointsX**: `string` \| `string`[]

The **`scroll-snap-points-x`** CSS property defines the horizontal positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapPointsX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnappointsx)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25534

___

### scrollSnapPointsY

• `Optional` **scrollSnapPointsY**: `string` \| `string`[]

The **`scroll-snap-points-y`** CSS property defines the vertical positioning of snap points within the content of the scroll container they are applied to.

**Syntax**: `none | repeat( <length-percentage> )`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapPointsY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnappointsy)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25544

___

### scrollSnapStop

• `Optional` **scrollSnapStop**: [`ScrollSnapStopProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapstopproperty) \| [`ScrollSnapStopProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnapstopproperty)[]

The **`scroll-snap-stop`** CSS property defines whether the scroll container is allowed to "pass over" possible snap positions.

**Syntax**: `normal | always`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **75** |   No    | **15** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-stop

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapStop](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnapstop)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21928

___

### scrollSnapType

• `Optional` **scrollSnapType**: `string` \| `string`[]

The **`scroll-snap-type`** CSS property sets how strictly snap points are enforced on the scroll container in case there is one.

**Syntax**: `none | [ x | y | block | inline | both ] [ mandatory | proximity ]?`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |      IE      |
| :----: | :-----: | :-----: | :----: | :----------: |
| **69** |  39-68  | **11**  | **79** | **10** _-x-_ |
|        |         | 9 _-x-_ |        |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scroll-snap-type

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollSnapType](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollsnaptype)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21943

___

### scrollSnapTypeX

• `Optional` **scrollSnapTypeX**: [`ScrollSnapTypeXProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypexproperty) \| [`ScrollSnapTypeXProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypexproperty)[]

The **`scroll-snap-type-x`** CSS property defines how strictly snap points are enforced on the horizontal axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapTypeX](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnaptypex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25554

___

### scrollSnapTypeY

• `Optional` **scrollSnapTypeY**: [`ScrollSnapTypeYProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypeyproperty) \| [`ScrollSnapTypeYProperty`](../modules/akashaproject_design_system._internal_.md#scrollsnaptypeyproperty)[]

The **`scroll-snap-type-y`** CSS property defines how strictly snap points are enforced on the vertical axis of the scroll container in case there is one.

**Syntax**: `none | mandatory | proximity`

**Initial value**: `none`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollSnapTypeY](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollsnaptypey)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25564

___

### scrollbarColor

• `Optional` **scrollbarColor**: `string` \| `string`[]

The **`scrollbar-color`** CSS property sets the color of the scrollbar track and thumb.

**Syntax**: `auto | <color>{2}`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **64**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollbarColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollbarcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21957

___

### scrollbarGutter

• `Optional` **scrollbarGutter**: `string` \| `string`[]

The **`scrollbar-gutter`** CSS property allows authors to reserve space for the scrollbar, preventing unwanted layout changes as the content grows while also avoiding unnecessary visuals when scrolling isn't needed.

**Syntax**: `auto | stable && both-edges?`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|  n/a   |   No    |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-gutter

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollbarGutter](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollbargutter)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21971

___

### scrollbarTrackColor

• `Optional` **scrollbarTrackColor**: `string` \| `string`[]

The **`-ms-scrollbar-track-color`** CSS property is a Microsoft extension that specifies the color of the track element of a scrollbar.

**Syntax**: `<color>`

**Initial value**: `Scrollbar`

**`deprecated`**

#### Inherited from

[ObsoletePropertiesFallback](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md).[scrollbarTrackColor](akashaproject_design_system._internal_.ObsoletePropertiesFallback.md#scrollbartrackcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:25574

___

### scrollbarWidth

• `Optional` **scrollbarWidth**: [`ScrollbarWidthProperty`](../modules/akashaproject_design_system._internal_.md#scrollbarwidthproperty) \| [`ScrollbarWidthProperty`](../modules/akashaproject_design_system._internal_.md#scrollbarwidthproperty)[]

The `scrollbar-width` property allows the author to set the maximum thickness of an element’s scrollbars when they are shown.

**Syntax**: `auto | thin | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari | Edge | IE  |
| :----: | :-----: | :----: | :--: | :-: |
|   No   | **64**  |   No   |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/scrollbar-width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[scrollbarWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#scrollbarwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21985

___

### shapeImageThreshold

• `Optional` **shapeImageThreshold**: [`ShapeImageThresholdProperty`](../modules/akashaproject_design_system._internal_.md#shapeimagethresholdproperty) \| [`ShapeImageThresholdProperty`](../modules/akashaproject_design_system._internal_.md#shapeimagethresholdproperty)[]

The **`shape-image-threshold`** CSS property sets the alpha channel threshold used to extract the shape using an image as the value for `shape-outside`.

**Syntax**: `<alpha-value>`

**Initial value**: `0.0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-image-threshold

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[shapeImageThreshold](akashaproject_design_system._internal_.StandardPropertiesFallback.md#shapeimagethreshold)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:21999

___

### shapeMargin

• `Optional` **shapeMargin**: [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\> \| [`ShapeMarginProperty`](../modules/akashaproject_design_system._internal_.md#shapemarginproperty)<`TLength`\>[]

The **`shape-margin`** CSS property sets a margin for a CSS shape created using `shape-outside`.

**Syntax**: `<length-percentage>`

**Initial value**: `0`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-margin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[shapeMargin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#shapemargin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22013

___

### shapeOutside

• `Optional` **shapeOutside**: `string` \| `string`[]

The **`shape-outside`** CSS property defines a shape—which may be non-rectangular—around which adjacent inline content should wrap. By default, inline content wraps around its margin box; `shape-outside` provides a way to customize this wrapping, making it possible to wrap text around complex objects rather than simple boxes.

**Syntax**: `none | [ <shape-box> || <basic-shape> ] | <image>`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **37** | **62**  | **10.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/shape-outside

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[shapeOutside](akashaproject_design_system._internal_.StandardPropertiesFallback.md#shapeoutside)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22027

___

### shapeRendering

• `Optional` **shapeRendering**: [`ShapeRenderingProperty`](../modules/akashaproject_design_system._internal_.md#shaperenderingproperty) \| [`ShapeRenderingProperty`](../modules/akashaproject_design_system._internal_.md#shaperenderingproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[shapeRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#shaperendering)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26396

___

### stopColor

• `Optional` **stopColor**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[stopColor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stopcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26397

___

### stopOpacity

• `Optional` **stopOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[stopOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stopopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26398

___

### stroke

• `Optional` **stroke**: `string` \| `string`[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[stroke](akashaproject_design_system._internal_.SvgPropertiesFallback.md#stroke)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26399

___

### strokeDasharray

• `Optional` **strokeDasharray**: [`StrokeDasharrayProperty`](../modules/akashaproject_design_system._internal_.md#strokedasharrayproperty)<`TLength`\> \| [`StrokeDasharrayProperty`](../modules/akashaproject_design_system._internal_.md#strokedasharrayproperty)<`TLength`\>[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeDasharray](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokedasharray)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26400

___

### strokeDashoffset

• `Optional` **strokeDashoffset**: [`StrokeDashoffsetProperty`](../modules/akashaproject_design_system._internal_.md#strokedashoffsetproperty)<`TLength`\> \| [`StrokeDashoffsetProperty`](../modules/akashaproject_design_system._internal_.md#strokedashoffsetproperty)<`TLength`\>[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeDashoffset](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokedashoffset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26401

___

### strokeLinecap

• `Optional` **strokeLinecap**: [`StrokeLinecapProperty`](../modules/akashaproject_design_system._internal_.md#strokelinecapproperty) \| [`StrokeLinecapProperty`](../modules/akashaproject_design_system._internal_.md#strokelinecapproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeLinecap](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokelinecap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26402

___

### strokeLinejoin

• `Optional` **strokeLinejoin**: [`StrokeLinejoinProperty`](../modules/akashaproject_design_system._internal_.md#strokelinejoinproperty) \| [`StrokeLinejoinProperty`](../modules/akashaproject_design_system._internal_.md#strokelinejoinproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeLinejoin](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokelinejoin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26403

___

### strokeMiterlimit

• `Optional` **strokeMiterlimit**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeMiterlimit](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokemiterlimit)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26404

___

### strokeOpacity

• `Optional` **strokeOpacity**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeOpacity](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokeopacity)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26405

___

### strokeWidth

• `Optional` **strokeWidth**: [`StrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#strokewidthproperty)<`TLength`\> \| [`StrokeWidthProperty`](../modules/akashaproject_design_system._internal_.md#strokewidthproperty)<`TLength`\>[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[strokeWidth](akashaproject_design_system._internal_.SvgPropertiesFallback.md#strokewidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26406

___

### tabSize

• `Optional` **tabSize**: [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\> \| [`TabSizeProperty`](../modules/akashaproject_design_system._internal_.md#tabsizeproperty)<`TLength`\>[]

The **`tab-size`** CSS property is used to customize the width of a tab (`U+0009`) character.

**Syntax**: `<integer> | <length>`

**Initial value**: `8`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **21** | **91**  | **7**  | **79** | No  |
|        | 4 _-x-_ |        |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/tab-size

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[tabSize](akashaproject_design_system._internal_.StandardPropertiesFallback.md#tabsize)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22042

___

### tableLayout

• `Optional` **tableLayout**: [`TableLayoutProperty`](../modules/akashaproject_design_system._internal_.md#tablelayoutproperty) \| [`TableLayoutProperty`](../modules/akashaproject_design_system._internal_.md#tablelayoutproperty)[]

The **`table-layout`** CSS property sets the algorithm used to lay out `<table>` cells, rows, and columns.

**Syntax**: `auto | fixed`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **14** |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/table-layout

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[tableLayout](akashaproject_design_system._internal_.StandardPropertiesFallback.md#tablelayout)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22056

___

### textAlign

• `Optional` **textAlign**: [`TextAlignProperty`](../modules/akashaproject_design_system._internal_.md#textalignproperty) \| [`TextAlignProperty`](../modules/akashaproject_design_system._internal_.md#textalignproperty)[]

The **`text-align`** CSS property sets the horizontal alignment of an inline or table-cell box. This means it works like `vertical-align` but in the horizontal direction.

**Syntax**: `start | end | left | right | center | justify | match-parent`

**Initial value**: `start`, or a nameless value that acts as `left` if _direction_ is `ltr`, `right` if _direction_ is `rtl` if `start` is not supported by the browser.

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-align

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textAlign](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22070

___

### textAlignLast

• `Optional` **textAlignLast**: [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty) \| [`TextAlignLastProperty`](../modules/akashaproject_design_system._internal_.md#textalignlastproperty)[]

The **`text-align-last`** CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

**Syntax**: `auto | start | end | left | right | center | justify`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **47** | **49**  |   No   | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-align-last

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textAlignLast](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textalignlast)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22084

___

### textAnchor

• `Optional` **textAnchor**: [`TextAnchorProperty`](../modules/akashaproject_design_system._internal_.md#textanchorproperty) \| [`TextAnchorProperty`](../modules/akashaproject_design_system._internal_.md#textanchorproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[textAnchor](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textanchor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26407

___

### textCombineUpright

• `Optional` **textCombineUpright**: `string` \| `string`[]

The **`text-combine-upright`** CSS property sets the combination of characters into the space of a single character. If the combined text is wider than 1em, the user agent must fit the contents within 1em. The resulting composition is treated as a single upright glyph for layout and decoration. This property only has an effect in vertical writing modes.

**Syntax**: `none | all | [ digits <integer>? ]`

**Initial value**: `none`

|           Chrome           | Firefox |              Safari              | Edge  |                   IE                   |
| :------------------------: | :-----: | :------------------------------: | :---: | :------------------------------------: |
|           **48**           | **48**  | **5.1** _(-webkit-text-combine)_ | 15-79 | **11** _(-ms-text-combine-horizontal)_ |
| 9 _(-webkit-text-combine)_ |         |                                  |       |                                        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-combine-upright

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textCombineUpright](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textcombineupright)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22099

___

### textDecoration

• `Optional` **textDecoration**: [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\> \| [`TextDecorationProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationproperty)<`TLength`\>[]

The **`text-decoration`** CSS property sets the appearance of decorative lines on text. It is a shorthand for `text-decoration-line`, `text-decoration-color`, and `text-decoration-style`.

**Syntax**: `<'text-decoration-line'> || <'text-decoration-style'> || <'text-decoration-color'> || <'text-decoration-thickness'>`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[textDecoration](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textdecoration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23316

___

### textDecorationColor

• `Optional` **textDecorationColor**: `string` \| `string`[]

The **`text-decoration-color`** CSS property sets the color of decorations added to text by `text-decoration-line`.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationcolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22114

___

### textDecorationLine

• `Optional` **textDecorationLine**: `string` \| `string`[]

The **`text-decoration-line`** CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

**Syntax**: `none | [ underline || overline || line-through || blink ] | spelling-error | grammar-error`

**Initial value**: `none`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-line

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationLine](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationline)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22129

___

### textDecorationSkip

• `Optional` **textDecorationSkip**: `string` \| `string`[]

The **`text-decoration-skip`** CSS property sets what parts of an element’s content any text decoration affecting the element must skip over. It controls all text decoration lines drawn by the element and also any text decoration lines drawn by its ancestors.

**Syntax**: `none | [ objects || [ spaces | [ leading-spaces || trailing-spaces ] ] || edges || box-decoration ]`

**Initial value**: `objects`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
| 57-64  |   No    | **12.1** |  No  | No  |
|        |         | 7 _-x-_  |      |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-skip

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationSkip](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationskip)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22144

___

### textDecorationSkipInk

• `Optional` **textDecorationSkipInk**: [`TextDecorationSkipInkProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationskipinkproperty) \| [`TextDecorationSkipInkProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationskipinkproperty)[]

The **`text-decoration-skip-ink`** CSS property specifies how overlines and underlines are drawn when they pass over glyph ascenders and descenders.

**Syntax**: `auto | all | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **64** | **70**  |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-skip-ink

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationSkipInk](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationskipink)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22158

___

### textDecorationStyle

• `Optional` **textDecorationStyle**: [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty) \| [`TextDecorationStyleProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationstyleproperty)[]

The **`text-decoration-style`** CSS property sets the style of the lines specified by `text-decoration-line`. The style applies to all lines that are set with `text-decoration-line`.

**Syntax**: `solid | double | dotted | dashed | wavy`

**Initial value**: `solid`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **57** | **36**  | **12.1** | **79** | No  |
|        |         | 8 _-x-_  |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22173

___

### textDecorationThickness

• `Optional` **textDecorationThickness**: [`TextDecorationThicknessProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationthicknessproperty)<`TLength`\> \| [`TextDecorationThicknessProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationthicknessproperty)<`TLength`\>[]

The **`text-decoration-thickness`** CSS property sets the thickness, or width, of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **89** | **70**  | **12.1** | **89** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationThickness](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationthickness)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22187

___

### textDecorationWidth

• `Optional` **textDecorationWidth**: [`TextDecorationThicknessProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationthicknessproperty)<`TLength`\> \| [`TextDecorationThicknessProperty`](../modules/akashaproject_design_system._internal_.md#textdecorationthicknessproperty)<`TLength`\>[]

The **`text-decoration-thickness`** CSS property sets the thickness, or width, of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

**Syntax**: `auto | from-font | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  | Edge  | IE  |
| :----: | :-----: | :------: | :---: | :-: |
| 87-89  | **70**  | **12.1** | 87-89 | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-decoration-thickness

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textDecorationWidth](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textdecorationwidth)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22201

___

### textEmphasis

• `Optional` **textEmphasis**: `string` \| `string`[]

The **`text-emphasis`** CSS property applies emphasis marks to text (except spaces and control characters). It is a shorthand for `text-emphasis-style` and `text-emphasis-color`.

**Syntax**: `<'text-emphasis-style'> || <'text-emphasis-color'>`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textEmphasis](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textemphasis)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23328

___

### textEmphasisColor

• `Optional` **textEmphasisColor**: `string` \| `string`[]

The **`text-emphasis-color`** CSS property sets the color of emphasis marks. This value can also be set using the `text-emphasis` shorthand.

**Syntax**: `<color>`

**Initial value**: `currentcolor`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-color

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textEmphasisColor](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textemphasiscolor)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22215

___

### textEmphasisPosition

• `Optional` **textEmphasisPosition**: `string` \| `string`[]

The **`text-emphasis-position`** CSS property sets where emphasis marks are drawn. Like ruby text, if there isn't enough room for emphasis marks, the line height is increased.

**Syntax**: `[ over | under ] && [ right | left ]`

**Initial value**: `over right`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textEmphasisPosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textemphasisposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22229

___

### textEmphasisStyle

• `Optional` **textEmphasisStyle**: `string` \| `string`[]

The **`text-emphasis-style`** CSS property sets the appearance of emphasis marks. It can also be set, and reset, using the `text-emphasis` shorthand.

**Syntax**: `none | [ [ filled | open ] || [ dot | circle | double-circle | triangle | sesame ] ] | <string>`

**Initial value**: `none`

|    Chrome    | Firefox | Safari |     Edge     | IE  |
| :----------: | :-----: | :----: | :----------: | :-: |
| **25** _-x-_ | **46**  | **7**  | **79** _-x-_ | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-emphasis-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textEmphasisStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textemphasisstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22243

___

### textIndent

• `Optional` **textIndent**: [`TextIndentProperty`](../modules/akashaproject_design_system._internal_.md#textindentproperty)<`TLength`\> \| [`TextIndentProperty`](../modules/akashaproject_design_system._internal_.md#textindentproperty)<`TLength`\>[]

The **`text-indent`** CSS property sets the length of empty space (indentation) that is put before lines of text in a block.

**Syntax**: `<length-percentage> && hanging? && each-line?`

**Initial value**: `0`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **3** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-indent

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textIndent](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textindent)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22257

___

### textJustify

• `Optional` **textJustify**: [`TextJustifyProperty`](../modules/akashaproject_design_system._internal_.md#textjustifyproperty) \| [`TextJustifyProperty`](../modules/akashaproject_design_system._internal_.md#textjustifyproperty)[]

The **`text-justify`** CSS property sets what type of justification should be applied to text when `text-align``: justify;` is set on an element.

**Syntax**: `auto | inter-character | inter-word | none`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |   IE   |
| :----: | :-----: | :----: | :----: | :----: |
|  n/a   | **55**  |   No   | **12** | **11** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-justify

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textJustify](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textjustify)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22271

___

### textOrientation

• `Optional` **textOrientation**: [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty) \| [`TextOrientationProperty`](../modules/akashaproject_design_system._internal_.md#textorientationproperty)[]

The **`text-orientation`** CSS property sets the orientation of the text characters in a line. It only affects text in vertical mode (when `writing-mode` is not `horizontal-tb`). It is useful for controlling the display of languages that use vertical script, and also for making vertical table headers.

**Syntax**: `mixed | upright | sideways`

**Initial value**: `mixed`

|  Chrome  | Firefox |  Safari   |  Edge  | IE  |
| :------: | :-----: | :-------: | :----: | :-: |
|  **48**  | **41**  |  **14**   | **79** | No  |
| 11 _-x-_ |         | 5.1 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-orientation

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textOrientation](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textorientation)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22286

___

### textOverflow

• `Optional` **textOverflow**: `string` \| `string`[]

The **`text-overflow`** CSS property sets how hidden overflow content is signaled to users. It can be clipped, display an ellipsis ('`…`'), or display a custom string.

**Syntax**: `[ clip | ellipsis | <string> ]{1,2}`

**Initial value**: `clip`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **1**  |  **7**  | **1.3** | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-overflow

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textOverflow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textoverflow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22300

___

### textRendering

• `Optional` **textRendering**: [`TextRenderingProperty`](../modules/akashaproject_design_system._internal_.md#textrenderingproperty) \| [`TextRenderingProperty`](../modules/akashaproject_design_system._internal_.md#textrenderingproperty)[]

The **`text-rendering`** CSS property provides information to the rendering engine about what to optimize for when rendering text.

**Syntax**: `auto | optimizeSpeed | optimizeLegibility | geometricPrecision`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **4**  |  **1**  | **5**  | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-rendering

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[textRendering](akashaproject_design_system._internal_.SvgPropertiesFallback.md#textrendering)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22314

___

### textShadow

• `Optional` **textShadow**: `string` \| `string`[]

The **`text-shadow`** CSS property adds shadows to text. It accepts a comma-separated list of shadows to be applied to the text and any of its `decorations`. Each shadow is described by some combination of X and Y offsets from the element, blur radius, and color.

**Syntax**: `none | <shadow-t>#`

**Initial value**: `none`

| Chrome | Firefox | Safari  |  Edge  |   IE   |
| :----: | :-----: | :-----: | :----: | :----: |
| **2**  | **3.5** | **1.1** | **12** | **10** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-shadow

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textShadow](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textshadow)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22328

___

### textSizeAdjust

• `Optional` **textSizeAdjust**: `string` \| `string`[]

The **`text-size-adjust`** CSS property controls the text inflation algorithm used on some smartphones and tablets. Other browsers will ignore this property.

**Syntax**: `none | auto | <percentage>`

**Initial value**: `auto` for smartphone browsers supporting inflation, `none` in other cases (and then not modifiable).

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **54** |   No    |   No   | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-size-adjust

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textSizeAdjust](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textsizeadjust)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22342

___

### textTransform

• `Optional` **textTransform**: [`TextTransformProperty`](../modules/akashaproject_design_system._internal_.md#texttransformproperty) \| [`TextTransformProperty`](../modules/akashaproject_design_system._internal_.md#texttransformproperty)[]

The **`text-transform`** CSS property specifies how to capitalize an element's text. It can be used to make text appear in all-uppercase or all-lowercase, or with each word capitalized. It also can help improve legibility for ruby

**Syntax**: `none | capitalize | uppercase | lowercase | full-width | full-size-kana`

**Initial value**: `none`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-transform

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textTransform](akashaproject_design_system._internal_.StandardPropertiesFallback.md#texttransform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22356

___

### textUnderlineOffset

• `Optional` **textUnderlineOffset**: [`TextUnderlineOffsetProperty`](../modules/akashaproject_design_system._internal_.md#textunderlineoffsetproperty)<`TLength`\> \| [`TextUnderlineOffsetProperty`](../modules/akashaproject_design_system._internal_.md#textunderlineoffsetproperty)<`TLength`\>[]

The **`text-underline-offset`** CSS property sets the offset distance of an underline text decoration line (applied using `text-decoration`) from its original position.

**Syntax**: `auto | <length> | <percentage> `

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  | IE  |
| :----: | :-----: | :------: | :----: | :-: |
| **87** | **70**  | **12.1** | **87** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-underline-offset

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textUnderlineOffset](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textunderlineoffset)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22370

___

### textUnderlinePosition

• `Optional` **textUnderlinePosition**: `string` \| `string`[]

The **`text-underline-position`** CSS property specifies the position of the underline which is set using the `text-decoration` property's `underline` value.

**Syntax**: `auto | from-font | [ under || [ left | right ] ]`

**Initial value**: `auto`

| Chrome | Firefox |  Safari  |  Edge  |  IE   |
| :----: | :-----: | :------: | :----: | :---: |
| **33** | **74**  | **12.1** | **12** | **6** |
|        |         | 9 _-x-_  |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/text-underline-position

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[textUnderlinePosition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#textunderlineposition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22385

___

### top

• `Optional` **top**: [`TopProperty`](../modules/akashaproject_design_system._internal_.md#topproperty)<`TLength`\> \| [`TopProperty`](../modules/akashaproject_design_system._internal_.md#topproperty)<`TLength`\>[]

The **`top`** CSS property participates in specifying the vertical position of a _positioned element_. It has no effect on non-positioned elements.

**Syntax**: `<length> | <percentage> | auto`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/top

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[top](akashaproject_design_system._internal_.StandardPropertiesFallback.md#top)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22399

___

### touchAction

• `Optional` **touchAction**: `string` \| `string`[]

The **`touch-action`** CSS property sets how a region can be manipulated by a touchscreen user (for example, by zooming features built into the browser).

**Syntax**: `auto | none | [ [ pan-x | pan-left | pan-right ] || [ pan-y | pan-up | pan-down ] || pinch-zoom ] | manipulation`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |    IE    |
| :----: | :-----: | :----: | :----: | :------: |
| **36** | **52**  | **13** | **12** |  **11**  |
|        |         |        |        | 10 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/touch-action

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[touchAction](akashaproject_design_system._internal_.StandardPropertiesFallback.md#touchaction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22414

___

### transform

• `Optional` **transform**: `string` \| `string`[]

The **`transform`** CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

**Syntax**: `none | <transform-list>`

**Initial value**: `none`

| Chrome  | Firefox |  Safari   |  Edge  |   IE    |
| :-----: | :-----: | :-------: | :----: | :-----: |
| **36**  | **16**  |   **9**   | **12** | **10**  |
| 1 _-x-_ |         | 3.1 _-x-_ |        | 9 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transform](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transform)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22429

___

### transformBox

• `Optional` **transformBox**: [`TransformBoxProperty`](../modules/akashaproject_design_system._internal_.md#transformboxproperty) \| [`TransformBoxProperty`](../modules/akashaproject_design_system._internal_.md#transformboxproperty)[]

The **`transform-box`** CSS property defines the layout box to which the `transform` and `transform-origin` properties relate.

**Syntax**: `content-box | border-box | fill-box | stroke-box | view-box`

**Initial value**: `view-box`

| Chrome | Firefox | Safari |  Edge  | IE  |
| :----: | :-----: | :----: | :----: | :-: |
| **64** | **55**  | **11** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-box

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transformBox](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transformbox)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22443

___

### transformOrigin

• `Optional` **transformOrigin**: [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\> \| [`TransformOriginProperty`](../modules/akashaproject_design_system._internal_.md#transformoriginproperty)<`TLength`\>[]

The **`transform-origin`** CSS property sets the origin for an element's transformations.

**Syntax**: `[ <length-percentage> | left | center | right | top | bottom ] | [ [ <length-percentage> | left | center | right ] && [ <length-percentage> | top | center | bottom ] ] <length>?`

**Initial value**: `50% 50% 0`

| Chrome  |  Firefox  | Safari  |  Edge  |   IE    |
| :-----: | :-------: | :-----: | :----: | :-----: |
| **36**  |  **16**   |  **9**  | **12** | **10**  |
| 1 _-x-_ | 3.5 _-x-_ | 2 _-x-_ |        | 9 _-x-_ |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-origin

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transformOrigin](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transformorigin)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22458

___

### transformStyle

• `Optional` **transformStyle**: [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty) \| [`TransformStyleProperty`](../modules/akashaproject_design_system._internal_.md#transformstyleproperty)[]

The **`transform-style`** CSS property sets whether children of an element are positioned in the 3D space or are flattened in the plane of the element.

**Syntax**: `flat | preserve-3d`

**Initial value**: `flat`

|  Chrome  | Firefox  | Safari  |  Edge  | IE  |
| :------: | :------: | :-----: | :----: | :-: |
|  **36**  |  **16**  |  **9**  | **12** | No  |
| 12 _-x-_ | 10 _-x-_ | 4 _-x-_ |        |     |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transform-style

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transformStyle](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transformstyle)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22473

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

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transition](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transition)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:23341

___

### transitionDelay

• `Optional` **transitionDelay**: `string` \| `string`[]

The **`transition-delay`** CSS property specifies the duration to wait before starting a property's transition effect when its value changes.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox | Safari  |  Edge  |   IE   |
| :-----: | :-----: | :-----: | :----: | :----: |
| **26**  | **16**  |  **9**  | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 4 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-delay

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transitionDelay](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transitiondelay)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22488

___

### transitionDuration

• `Optional` **transitionDuration**: `string` \| `string`[]

The **`transition-duration`** CSS property sets the length of time a transition animation should take to complete. By default, the value is `0s`, meaning that no animation will occur.

**Syntax**: `<time>#`

**Initial value**: `0s`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-duration

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transitionDuration](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transitionduration)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22503

___

### transitionProperty

• `Optional` **transitionProperty**: `string` \| `string`[]

The **`transition-property`** CSS property sets the CSS properties to which a transition effect should be applied.

**Syntax**: `none | <single-transition-property>#`

**Initial value**: all

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-property

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transitionProperty](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transitionproperty)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22518

___

### transitionTimingFunction

• `Optional` **transitionTimingFunction**: `string` \| `string`[]

The **`transition-timing-function`** CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

**Syntax**: `<easing-function>#`

**Initial value**: `ease`

| Chrome  | Firefox |  Safari   |  Edge  |   IE   |
| :-----: | :-----: | :-------: | :----: | :----: |
| **26**  | **16**  |   **9**   | **12** | **10** |
| 1 _-x-_ | 4 _-x-_ | 3.1 _-x-_ |        |        |

**`see`** https://developer.mozilla.org/docs/Web/CSS/transition-timing-function

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[transitionTimingFunction](akashaproject_design_system._internal_.StandardPropertiesFallback.md#transitiontimingfunction)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22533

___

### translate

• `Optional` **translate**: [`TranslateProperty`](../modules/akashaproject_design_system._internal_.md#translateproperty)<`TLength`\> \| [`TranslateProperty`](../modules/akashaproject_design_system._internal_.md#translateproperty)<`TLength`\>[]

The **`translate`** CSS property allows you to specify translation transforms individually and independantly of the `transform` property. This maps better to typical user interface usage, and saves having to remember the exact order of transform functions to specify in the `transform` value.

**Syntax**: `none | <length-percentage> [ <length-percentage> <length>? ]?`

**Initial value**: `none`

| Chrome | Firefox |  Safari  | Edge | IE  |
| :----: | :-----: | :------: | :--: | :-: |
|   No   | **72**  | **14.1** |  No  | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/translate

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[translate](akashaproject_design_system._internal_.StandardPropertiesFallback.md#translate)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22547

___

### unicodeBidi

• `Optional` **unicodeBidi**: [`UnicodeBidiProperty`](../modules/akashaproject_design_system._internal_.md#unicodebidiproperty) \| [`UnicodeBidiProperty`](../modules/akashaproject_design_system._internal_.md#unicodebidiproperty)[]

The **`unicode-bidi`** CSS property, together with the `direction` property, determines how bidirectional text in a document is handled. For example, if a block of content contains both left-to-right and right-to-left text, the user-agent uses a complex Unicode algorithm to decide how to display the text. The `unicode-bidi` property overrides this algorithm and allows the developer to control the text embedding.

**Syntax**: `normal | embed | isolate | bidi-override | isolate-override | plaintext`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  |   IE    |
| :----: | :-----: | :-----: | :----: | :-----: |
| **2**  |  **1**  | **1.3** | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/unicode-bidi

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[unicodeBidi](akashaproject_design_system._internal_.SvgPropertiesFallback.md#unicodebidi)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22561

___

### userSelect

• `Optional` **userSelect**: [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty) \| [`UserSelectProperty`](../modules/akashaproject_design_system._internal_.md#userselectproperty)[]

The `**user-select**` CSS property controls whether the user can select text. This doesn't have any effect on content loaded as chrome, except in textboxes.

**Syntax**: `auto | text | none | contain | all`

**Initial value**: `auto`

| Chrome  | Firefox |   Safari    |   Edge   |      IE      |
| :-----: | :-----: | :---------: | :------: | :----------: |
| **54**  | **69**  | **3** _-x-_ |  **79**  | **10** _-x-_ |
| 1 _-x-_ | 1 _-x-_ |             | 12 _-x-_ |              |

**`see`** https://developer.mozilla.org/docs/Web/CSS/user-select

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[userSelect](akashaproject_design_system._internal_.StandardPropertiesFallback.md#userselect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22576

___

### vectorEffect

• `Optional` **vectorEffect**: [`VectorEffectProperty`](../modules/akashaproject_design_system._internal_.md#vectoreffectproperty) \| [`VectorEffectProperty`](../modules/akashaproject_design_system._internal_.md#vectoreffectproperty)[]

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[vectorEffect](akashaproject_design_system._internal_.SvgPropertiesFallback.md#vectoreffect)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:26411

___

### verticalAlign

• `Optional` **verticalAlign**: [`VerticalAlignProperty`](../modules/akashaproject_design_system._internal_.md#verticalalignproperty)<`TLength`\> \| [`VerticalAlignProperty`](../modules/akashaproject_design_system._internal_.md#verticalalignproperty)<`TLength`\>[]

The **`vertical-align`** CSS property sets vertical alignment of an inline or table-cell box.

**Syntax**: `baseline | sub | super | text-top | text-bottom | middle | top | bottom | <percentage> | <length>`

**Initial value**: `baseline`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/vertical-align

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[verticalAlign](akashaproject_design_system._internal_.StandardPropertiesFallback.md#verticalalign)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22590

___

### visibility

• `Optional` **visibility**: [`VisibilityProperty`](../modules/akashaproject_design_system._internal_.md#visibilityproperty) \| [`VisibilityProperty`](../modules/akashaproject_design_system._internal_.md#visibilityproperty)[]

The **`visibility`** CSS property shows or hides an element without changing the layout of a document. The property can also hide rows or columns in a `<table>`.

**Syntax**: `visible | hidden | collapse`

**Initial value**: `visible`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/visibility

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[visibility](akashaproject_design_system._internal_.SvgPropertiesFallback.md#visibility)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22604

___

### whiteSpace

• `Optional` **whiteSpace**: [`WhiteSpaceProperty`](../modules/akashaproject_design_system._internal_.md#whitespaceproperty) \| [`WhiteSpaceProperty`](../modules/akashaproject_design_system._internal_.md#whitespaceproperty)[]

The **`white-space`** CSS property sets how white space inside an element is handled.

**Syntax**: `normal | pre | nowrap | pre-wrap | pre-line | break-spaces`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  |  **1**  | **1**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/white-space

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[whiteSpace](akashaproject_design_system._internal_.SvgPropertiesFallback.md#whitespace)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22618

___

### widows

• `Optional` **widows**: [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber) \| [`GlobalsNumber`](../modules/akashaproject_design_system._internal_.md#globalsnumber)[]

The **`widows`** CSS property sets the minimum number of lines in a block container that must be shown at the _top_ of a page, region, or column.

**Syntax**: `<integer>`

**Initial value**: `2`

| Chrome | Firefox | Safari  |  Edge  |  IE   |
| :----: | :-----: | :-----: | :----: | :---: |
| **25** |   No    | **1.3** | **12** | **8** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/widows

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[widows](akashaproject_design_system._internal_.StandardPropertiesFallback.md#widows)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22632

___

### width

• `Optional` **width**: [`WidthProperty`](../modules/akashaproject_design_system._internal_.md#widthproperty)<`TLength`\> \| [`WidthProperty`](../modules/akashaproject_design_system._internal_.md#widthproperty)<`TLength`\>[]

The **`width`** CSS property sets an element's width. By default it sets the width of the content area, but if `box-sizing` is set to `border-box`, it sets the width of the border area.

**Syntax**: `auto | <length> | <percentage> | min-content | max-content | fit-content | fit-content(<length-percentage>)`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/width

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[width](akashaproject_design_system._internal_.StandardPropertiesFallback.md#width)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22646

___

### willChange

• `Optional` **willChange**: `string` \| `string`[]

The **`will-change`** CSS property hints to browsers how an element is expected to change. Browsers may set up optimizations before an element is actually changed. These kinds of optimizations can increase the responsiveness of a page by doing potentially expensive work before they are actually required.

**Syntax**: `auto | <animateable-feature>#`

**Initial value**: `auto`

| Chrome | Firefox | Safari  |  Edge  | IE  |
| :----: | :-----: | :-----: | :----: | :-: |
| **36** | **36**  | **9.1** | **79** | No  |

**`see`** https://developer.mozilla.org/docs/Web/CSS/will-change

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[willChange](akashaproject_design_system._internal_.StandardPropertiesFallback.md#willchange)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22660

___

### wordBreak

• `Optional` **wordBreak**: [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty) \| [`WordBreakProperty`](../modules/akashaproject_design_system._internal_.md#wordbreakproperty)[]

The **`word-break`** CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

**Syntax**: `normal | break-all | keep-all | break-word`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |   IE    |
| :----: | :-----: | :----: | :----: | :-----: |
| **1**  | **15**  | **3**  | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/word-break

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[wordBreak](akashaproject_design_system._internal_.StandardPropertiesFallback.md#wordbreak)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22674

___

### wordSpacing

• `Optional` **wordSpacing**: [`WordSpacingProperty`](../modules/akashaproject_design_system._internal_.md#wordspacingproperty)<`TLength`\> \| [`WordSpacingProperty`](../modules/akashaproject_design_system._internal_.md#wordspacingproperty)<`TLength`\>[]

The **`word-spacing`** CSS property sets the length of space between words and between tags.

**Syntax**: `normal | <length>`

**Initial value**: `normal`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **6** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/word-spacing

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[wordSpacing](akashaproject_design_system._internal_.SvgPropertiesFallback.md#wordspacing)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22688

___

### wordWrap

• `Optional` **wordWrap**: [`WordWrapProperty`](../modules/akashaproject_design_system._internal_.md#wordwrapproperty) \| [`WordWrapProperty`](../modules/akashaproject_design_system._internal_.md#wordwrapproperty)[]

The `**overflow-wrap**` CSS property sets whether the browser should insert line breaks within words to prevent text from overflowing its content box.

**Syntax**: `normal | break-word`

**Initial value**: `normal`

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[wordWrap](akashaproject_design_system._internal_.StandardPropertiesFallback.md#wordwrap)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22696

___

### writingMode

• `Optional` **writingMode**: [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty) \| [`WritingModeProperty`](../modules/akashaproject_design_system._internal_.md#writingmodeproperty)[]

The **`writing-mode`** CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress.

**Syntax**: `horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr`

**Initial value**: `horizontal-tb`

| Chrome  | Firefox |  Safari   |  Edge  |  IE   |
| :-----: | :-----: | :-------: | :----: | :---: |
| **48**  | **41**  | **10.1**  | **12** | **9** |
| 8 _-x-_ |         | 5.1 _-x-_ |        |       |

**`see`** https://developer.mozilla.org/docs/Web/CSS/writing-mode

#### Inherited from

[SvgPropertiesFallback](akashaproject_design_system._internal_.SvgPropertiesFallback.md).[writingMode](akashaproject_design_system._internal_.SvgPropertiesFallback.md#writingmode)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22711

___

### zIndex

• `Optional` **zIndex**: [`ZIndexProperty`](../modules/akashaproject_design_system._internal_.md#zindexproperty) \| [`ZIndexProperty`](../modules/akashaproject_design_system._internal_.md#zindexproperty)[]

The **`z-index`** CSS property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.

**Syntax**: `auto | <integer>`

**Initial value**: `auto`

| Chrome | Firefox | Safari |  Edge  |  IE   |
| :----: | :-----: | :----: | :----: | :---: |
| **1**  |  **1**  | **1**  | **12** | **4** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/z-index

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[zIndex](akashaproject_design_system._internal_.StandardPropertiesFallback.md#zindex)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22725

___

### zoom

• `Optional` **zoom**: [`ZoomProperty`](../modules/akashaproject_design_system._internal_.md#zoomproperty) \| [`ZoomProperty`](../modules/akashaproject_design_system._internal_.md#zoomproperty)[]

The non-standard **`zoom`** CSS property can be used to control the magnification level of an element. `transform: scale()` should be used instead of this property, if possible. However, unlike CSS Transforms, `zoom` affects the layout size of the element.

**Syntax**: `normal | reset | <number> | <percentage>`

**Initial value**: `normal`

| Chrome | Firefox | Safari  |  Edge  |   IE    |
| :----: | :-----: | :-----: | :----: | :-----: |
| **1**  |   No    | **3.1** | **12** | **5.5** |

**`see`** https://developer.mozilla.org/docs/Web/CSS/zoom

#### Inherited from

[StandardPropertiesFallback](akashaproject_design_system._internal_.StandardPropertiesFallback.md).[zoom](akashaproject_design_system._internal_.StandardPropertiesFallback.md#zoom)

#### Defined in

ui/design/node_modules/csstype/index.d.ts:22739
