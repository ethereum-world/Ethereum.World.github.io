[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ImageData

# Interface: ImageData

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ImageData

The underlying pixel data of an area of a <canvas> element. It is created using the ImageData() constructor or creator methods on the CanvasRenderingContext2D object associated with a canvas: createImageData() and getImageData(). It can also be used to set a part of the canvas by using putImageData().

## Table of contents

### Properties

- [data](akashaproject_ui_awf_testing_utils._internal_.ImageData.md#data)
- [height](akashaproject_ui_awf_testing_utils._internal_.ImageData.md#height)
- [width](akashaproject_ui_awf_testing_utils._internal_.ImageData.md#width)

## Properties

### data

• `Readonly` **data**: `Uint8ClampedArray`

Returns the one-dimensional array containing the data in RGBA order, as integers in the range 0 to 255.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9488

___

### height

• `Readonly` **height**: `number`

Returns the actual dimensions of the data in the ImageData object, in pixels.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9492

___

### width

• `Readonly` **width**: `number`

Returns the actual dimensions of the data in the ImageData object, in pixels.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9496
