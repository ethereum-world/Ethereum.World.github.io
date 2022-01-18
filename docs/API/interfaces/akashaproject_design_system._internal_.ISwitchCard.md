[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ISwitchCard

# Interface: ISwitchCard

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ISwitchCard

## Table of contents

### Properties

- [activeButton](akashaproject_design_system._internal_.ISwitchCard.md#activebutton)
- [buttonLabels](akashaproject_design_system._internal_.ISwitchCard.md#buttonlabels)
- [buttonValues](akashaproject_design_system._internal_.ISwitchCard.md#buttonvalues)
- [buttonsWrapperWidth](akashaproject_design_system._internal_.ISwitchCard.md#buttonswrapperwidth)
- [className](akashaproject_design_system._internal_.ISwitchCard.md#classname)
- [count](akashaproject_design_system._internal_.ISwitchCard.md#count)
- [countLabel](akashaproject_design_system._internal_.ISwitchCard.md#countlabel)
- [hasIcon](akashaproject_design_system._internal_.ISwitchCard.md#hasicon)
- [hasMobileDesign](akashaproject_design_system._internal_.ISwitchCard.md#hasmobiledesign)
- [loggedUser](akashaproject_design_system._internal_.ISwitchCard.md#loggeduser)
- [style](akashaproject_design_system._internal_.ISwitchCard.md#style)
- [tabButtons](akashaproject_design_system._internal_.ISwitchCard.md#tabbuttons)
- [wrapperMarginBottom](akashaproject_design_system._internal_.ISwitchCard.md#wrappermarginbottom)

### Methods

- [onIconClick](akashaproject_design_system._internal_.ISwitchCard.md#oniconclick)
- [onTabClick](akashaproject_design_system._internal_.ISwitchCard.md#ontabclick)

## Properties

### activeButton

• **activeButton**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L16)

___

### buttonLabels

• **buttonLabels**: `string`[]

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L18)

___

### buttonValues

• **buttonValues**: `string`[]

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L19)

___

### buttonsWrapperWidth

• `Optional` **buttonsWrapperWidth**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:22](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L22)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:26](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L26)

___

### count

• `Optional` **count**: `number`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L12)

___

### countLabel

• `Optional` **countLabel**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L15)

___

### hasIcon

• `Optional` **hasIcon**: `boolean`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L14)

___

### hasMobileDesign

• `Optional` **hasMobileDesign**: `boolean`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L20)

___

### loggedUser

• **loggedUser**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L13)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:25](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L25)

___

### tabButtons

• **tabButtons**: [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L17)

___

### wrapperMarginBottom

• `Optional` **wrapperMarginBottom**: `string`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:23](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L23)

## Methods

### onIconClick

▸ `Optional` **onIconClick**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:21](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L21)

___

### onTabClick

▸ **onTabClick**(`value`): () => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`fn`

▸ (): `void`

##### Returns

`void`

#### Defined in

[ui/design/src/components/SwitchCard/index.tsx:24](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/SwitchCard/index.tsx#L24)
