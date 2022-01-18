[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ILinkInput

# Interface: ILinkInput

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ILinkInput

## Table of contents

### Properties

- [className](akashaproject_design_system._internal_.ILinkInput.md#classname)
- [elevation](akashaproject_design_system._internal_.ILinkInput.md#elevation)
- [errorMsg](akashaproject_design_system._internal_.ILinkInput.md#errormsg)
- [hasError](akashaproject_design_system._internal_.ILinkInput.md#haserror)
- [inputInvalid](akashaproject_design_system._internal_.ILinkInput.md#inputinvalid)
- [inputPlaceholder](akashaproject_design_system._internal_.ILinkInput.md#inputplaceholder)
- [inputValue](akashaproject_design_system._internal_.ILinkInput.md#inputvalue)
- [margin](akashaproject_design_system._internal_.ILinkInput.md#margin)
- [noArrowRight](akashaproject_design_system._internal_.ILinkInput.md#noarrowright)
- [noDisable](akashaproject_design_system._internal_.ILinkInput.md#nodisable)
- [submitted](akashaproject_design_system._internal_.ILinkInput.md#submitted)
- [submitting](akashaproject_design_system._internal_.ILinkInput.md#submitting)
- [success](akashaproject_design_system._internal_.ILinkInput.md#success)

### Methods

- [onChange](akashaproject_design_system._internal_.ILinkInput.md#onchange)
- [validateTokenFn](akashaproject_design_system._internal_.ILinkInput.md#validatetokenfn)

## Properties

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L12)

___

### elevation

• `Optional` **elevation**: `string`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L21)

___

### errorMsg

• `Optional` **errorMsg**: `string`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L19)

___

### hasError

• `Optional` **hasError**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L18)

___

### inputInvalid

• `Optional` **inputInvalid**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L22)

___

### inputPlaceholder

• `Optional` **inputPlaceholder**: `string`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L14)

___

### inputValue

• **inputValue**: `string`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L13)

___

### margin

• `Optional` **margin**: `string` \| { `bottom?`: `string` ; `end?`: `string` ; `horizontal?`: `string` ; `left?`: `string` ; `right?`: `string` ; `start?`: `string` ; `top?`: `string` ; `vertical?`: `string`  }

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L20)

___

### noArrowRight

• `Optional` **noArrowRight**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L23)

___

### noDisable

• `Optional` **noDisable**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L24)

___

### submitted

• `Optional` **submitted**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L15)

___

### submitting

• `Optional` **submitting**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L16)

___

### success

• `Optional` **success**: `boolean`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L17)

## Methods

### onChange

▸ `Optional` **onChange**(`ev`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`ChangeEvent`](akashaproject_design_system._internal_.ChangeEvent.md)<`HTMLInputElement`\> |

#### Returns

`void`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L10)

___

### validateTokenFn

▸ `Optional` **validateTokenFn**(`ev`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `unknown` |

#### Returns

`void`

#### Defined in

[ui/design/src/components/TextInputIconForm/index.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/TextInputIconForm/index.tsx#L11)
