[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / SVGTransform

# Interface: SVGTransform

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).SVGTransform

SVGTransform is the interface for one of the component transformations within an SVGTransformList; thus, an SVGTransform object corresponds to a single component (e.g., scale(…) or matrix(…)) within a transform attribute.

## Table of contents

### Properties

- [SVG\_TRANSFORM\_MATRIX](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_matrix)
- [SVG\_TRANSFORM\_ROTATE](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_rotate)
- [SVG\_TRANSFORM\_SCALE](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_scale)
- [SVG\_TRANSFORM\_SKEWX](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_skewx)
- [SVG\_TRANSFORM\_SKEWY](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_skewy)
- [SVG\_TRANSFORM\_TRANSLATE](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_translate)
- [SVG\_TRANSFORM\_UNKNOWN](akashaproject_design_system._internal_.SVGTransform.md#svg_transform_unknown)
- [angle](akashaproject_design_system._internal_.SVGTransform.md#angle)
- [matrix](akashaproject_design_system._internal_.SVGTransform.md#matrix)
- [type](akashaproject_design_system._internal_.SVGTransform.md#type)

### Methods

- [setMatrix](akashaproject_design_system._internal_.SVGTransform.md#setmatrix)
- [setRotate](akashaproject_design_system._internal_.SVGTransform.md#setrotate)
- [setScale](akashaproject_design_system._internal_.SVGTransform.md#setscale)
- [setSkewX](akashaproject_design_system._internal_.SVGTransform.md#setskewx)
- [setSkewY](akashaproject_design_system._internal_.SVGTransform.md#setskewy)
- [setTranslate](akashaproject_design_system._internal_.SVGTransform.md#settranslate)

## Properties

### SVG\_TRANSFORM\_MATRIX

• `Readonly` **SVG\_TRANSFORM\_MATRIX**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13790

___

### SVG\_TRANSFORM\_ROTATE

• `Readonly` **SVG\_TRANSFORM\_ROTATE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13791

___

### SVG\_TRANSFORM\_SCALE

• `Readonly` **SVG\_TRANSFORM\_SCALE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13792

___

### SVG\_TRANSFORM\_SKEWX

• `Readonly` **SVG\_TRANSFORM\_SKEWX**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13793

___

### SVG\_TRANSFORM\_SKEWY

• `Readonly` **SVG\_TRANSFORM\_SKEWY**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13794

___

### SVG\_TRANSFORM\_TRANSLATE

• `Readonly` **SVG\_TRANSFORM\_TRANSLATE**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13795

___

### SVG\_TRANSFORM\_UNKNOWN

• `Readonly` **SVG\_TRANSFORM\_UNKNOWN**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13796

___

### angle

• `Readonly` **angle**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13781

___

### matrix

• `Readonly` **matrix**: [`DOMMatrix`](../modules/akashaproject_design_system._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13782

___

### type

• `Readonly` **type**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13783

## Methods

### setMatrix

▸ **setMatrix**(`matrix?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `matrix?` | [`DOMMatrix2DInit`](akashaproject_design_system._internal_.DOMMatrix2DInit.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13784

___

### setRotate

▸ **setRotate**(`angle`, `cx`, `cy`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |
| `cx` | `number` |
| `cy` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13785

___

### setScale

▸ **setScale**(`sx`, `sy`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `sx` | `number` |
| `sy` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13786

___

### setSkewX

▸ **setSkewX**(`angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13787

___

### setSkewY

▸ **setSkewY**(`angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `angle` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13788

___

### setTranslate

▸ **setTranslate**(`tx`, `ty`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `number` |
| `ty` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13789
