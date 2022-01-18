[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / DOMMatrix

# Interface: DOMMatrix

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).DOMMatrix

## Hierarchy

- [`DOMMatrixReadOnly`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrixreadonly)

  ↳ **`DOMMatrix`**

## Table of contents

### Properties

- [a](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#a)
- [b](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#b)
- [c](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#c)
- [d](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#d)
- [e](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#e)
- [f](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#f)
- [is2D](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#is2d)
- [isIdentity](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#isidentity)
- [m11](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m11)
- [m12](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m12)
- [m13](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m13)
- [m14](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m14)
- [m21](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m21)
- [m22](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m22)
- [m23](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m23)
- [m24](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m24)
- [m31](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m31)
- [m32](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m32)
- [m33](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m33)
- [m34](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m34)
- [m41](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m41)
- [m42](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m42)
- [m43](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m43)
- [m44](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#m44)

### Methods

- [flipX](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#flipx)
- [flipY](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#flipy)
- [inverse](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#inverse)
- [invertSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#invertself)
- [multiply](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#multiply)
- [multiplySelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#multiplyself)
- [preMultiplySelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#premultiplyself)
- [rotate](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotate)
- [rotateAxisAngle](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotateaxisangle)
- [rotateAxisAngleSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotateaxisangleself)
- [rotateFromVector](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotatefromvector)
- [rotateFromVectorSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotatefromvectorself)
- [rotateSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#rotateself)
- [scale](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#scale)
- [scale3d](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#scale3d)
- [scale3dSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#scale3dself)
- [scaleNonUniform](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#scalenonuniform)
- [scaleSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#scaleself)
- [setMatrixValue](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#setmatrixvalue)
- [skewX](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#skewx)
- [skewXSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#skewxself)
- [skewY](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#skewy)
- [skewYSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#skewyself)
- [toFloat32Array](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#tofloat32array)
- [toFloat64Array](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#tofloat64array)
- [toJSON](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#tojson)
- [toString](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#tostring)
- [transformPoint](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#transformpoint)
- [translate](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#translate)
- [translateSelf](akashaproject_ui_awf_testing_utils._internal_.DOMMatrix.md#translateself)

## Properties

### a

• **a**: `number`

#### Overrides

DOMMatrixReadOnly.a

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3772

___

### b

• **b**: `number`

#### Overrides

DOMMatrixReadOnly.b

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3773

___

### c

• **c**: `number`

#### Overrides

DOMMatrixReadOnly.c

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3774

___

### d

• **d**: `number`

#### Overrides

DOMMatrixReadOnly.d

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3775

___

### e

• **e**: `number`

#### Overrides

DOMMatrixReadOnly.e

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3776

___

### f

• **f**: `number`

#### Overrides

DOMMatrixReadOnly.f

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3777

___

### is2D

• `Readonly` **is2D**: `boolean`

#### Inherited from

DOMMatrixReadOnly.is2D

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3829

___

### isIdentity

• `Readonly` **isIdentity**: `boolean`

#### Inherited from

DOMMatrixReadOnly.isIdentity

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3830

___

### m11

• **m11**: `number`

#### Overrides

DOMMatrixReadOnly.m11

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3778

___

### m12

• **m12**: `number`

#### Overrides

DOMMatrixReadOnly.m12

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3779

___

### m13

• **m13**: `number`

#### Overrides

DOMMatrixReadOnly.m13

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3780

___

### m14

• **m14**: `number`

#### Overrides

DOMMatrixReadOnly.m14

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3781

___

### m21

• **m21**: `number`

#### Overrides

DOMMatrixReadOnly.m21

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3782

___

### m22

• **m22**: `number`

#### Overrides

DOMMatrixReadOnly.m22

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3783

___

### m23

• **m23**: `number`

#### Overrides

DOMMatrixReadOnly.m23

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3784

___

### m24

• **m24**: `number`

#### Overrides

DOMMatrixReadOnly.m24

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3785

___

### m31

• **m31**: `number`

#### Overrides

DOMMatrixReadOnly.m31

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3786

___

### m32

• **m32**: `number`

#### Overrides

DOMMatrixReadOnly.m32

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3787

___

### m33

• **m33**: `number`

#### Overrides

DOMMatrixReadOnly.m33

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3788

___

### m34

• **m34**: `number`

#### Overrides

DOMMatrixReadOnly.m34

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3789

___

### m41

• **m41**: `number`

#### Overrides

DOMMatrixReadOnly.m41

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3790

___

### m42

• **m42**: `number`

#### Overrides

DOMMatrixReadOnly.m42

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3791

___

### m43

• **m43**: `number`

#### Overrides

DOMMatrixReadOnly.m43

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3792

___

### m44

• **m44**: `number`

#### Overrides

DOMMatrixReadOnly.m44

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3793

## Methods

### flipX

▸ **flipX**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.flipX

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3847

___

### flipY

▸ **flipY**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.flipY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3848

___

### inverse

▸ **inverse**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.inverse

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3849

___

### invertSelf

▸ **invertSelf**(): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3794

___

### multiply

▸ **multiply**(`other?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other?` | [`DOMMatrixInit`](akashaproject_ui_awf_testing_utils._internal_.DOMMatrixInit.md) |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.multiply

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3850

___

### multiplySelf

▸ **multiplySelf**(`other?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other?` | [`DOMMatrixInit`](akashaproject_ui_awf_testing_utils._internal_.DOMMatrixInit.md) |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3795

___

### preMultiplySelf

▸ **preMultiplySelf**(`other?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other?` | [`DOMMatrixInit`](akashaproject_ui_awf_testing_utils._internal_.DOMMatrixInit.md) |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3796

___

### rotate

▸ **rotate**(`rotX?`, `rotY?`, `rotZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotX?` | `number` |
| `rotY?` | `number` |
| `rotZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.rotate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3851

___

### rotateAxisAngle

▸ **rotateAxisAngle**(`x?`, `y?`, `z?`, `angle?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `number` |
| `y?` | `number` |
| `z?` | `number` |
| `angle?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.rotateAxisAngle

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3852

___

### rotateAxisAngleSelf

▸ **rotateAxisAngleSelf**(`x?`, `y?`, `z?`, `angle?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `number` |
| `y?` | `number` |
| `z?` | `number` |
| `angle?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3797

___

### rotateFromVector

▸ **rotateFromVector**(`x?`, `y?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `number` |
| `y?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.rotateFromVector

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3853

___

### rotateFromVectorSelf

▸ **rotateFromVectorSelf**(`x?`, `y?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `number` |
| `y?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3798

___

### rotateSelf

▸ **rotateSelf**(`rotX?`, `rotY?`, `rotZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `rotX?` | `number` |
| `rotY?` | `number` |
| `rotZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3799

___

### scale

▸ **scale**(`scaleX?`, `scaleY?`, `scaleZ?`, `originX?`, `originY?`, `originZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `scaleX?` | `number` |
| `scaleY?` | `number` |
| `scaleZ?` | `number` |
| `originX?` | `number` |
| `originY?` | `number` |
| `originZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.scale

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3854

___

### scale3d

▸ **scale3d**(`scale?`, `originX?`, `originY?`, `originZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale?` | `number` |
| `originX?` | `number` |
| `originY?` | `number` |
| `originZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.scale3d

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3855

___

### scale3dSelf

▸ **scale3dSelf**(`scale?`, `originX?`, `originY?`, `originZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale?` | `number` |
| `originX?` | `number` |
| `originY?` | `number` |
| `originZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3800

___

### scaleNonUniform

▸ **scaleNonUniform**(`scaleX?`, `scaleY?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `scaleX?` | `number` |
| `scaleY?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.scaleNonUniform

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3857

___

### scaleSelf

▸ **scaleSelf**(`scaleX?`, `scaleY?`, `scaleZ?`, `originX?`, `originY?`, `originZ?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `scaleX?` | `number` |
| `scaleY?` | `number` |
| `scaleZ?` | `number` |
| `originX?` | `number` |
| `originY?` | `number` |
| `originZ?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3801

___

### setMatrixValue

▸ **setMatrixValue**(`transformList`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `transformList` | `string` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3802

___

### skewX

▸ **skewX**(`sx?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sx?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.skewX

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3858

___

### skewXSelf

▸ **skewXSelf**(`sx?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sx?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3803

___

### skewY

▸ **skewY**(`sy?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sy?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.skewY

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3859

___

### skewYSelf

▸ **skewYSelf**(`sy?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `sy?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3804

___

### toFloat32Array

▸ **toFloat32Array**(): `Float32Array`

#### Returns

`Float32Array`

#### Inherited from

DOMMatrixReadOnly.toFloat32Array

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3860

___

### toFloat64Array

▸ **toFloat64Array**(): `Float64Array`

#### Returns

`Float64Array`

#### Inherited from

DOMMatrixReadOnly.toFloat64Array

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3861

___

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Inherited from

DOMMatrixReadOnly.toJSON

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3862

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Inherited from

DOMMatrixReadOnly.toString

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3865

___

### transformPoint

▸ **transformPoint**(`point?`): [`DOMPoint`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dompoint)

#### Parameters

| Name | Type |
| :------ | :------ |
| `point?` | [`DOMPointInit`](akashaproject_ui_awf_testing_utils._internal_.DOMPointInit.md) |

#### Returns

[`DOMPoint`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dompoint)

#### Inherited from

DOMMatrixReadOnly.transformPoint

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3863

___

### translate

▸ **translate**(`tx?`, `ty?`, `tz?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx?` | `number` |
| `ty?` | `number` |
| `tz?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Inherited from

DOMMatrixReadOnly.translate

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3864

___

### translateSelf

▸ **translateSelf**(`tx?`, `ty?`, `tz?`): [`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx?` | `number` |
| `ty?` | `number` |
| `tz?` | `number` |

#### Returns

[`DOMMatrix`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#dommatrix)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3805
