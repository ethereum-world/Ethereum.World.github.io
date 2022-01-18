[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ButtonType

# Interface: ButtonType

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ButtonType

## Table of contents

### Properties

- [active](akashaproject_design_system._internal_.ButtonType.md#active)
- [badge](akashaproject_design_system._internal_.ButtonType.md#badge)
- [border](akashaproject_design_system._internal_.ButtonType.md#border)
- [color](akashaproject_design_system._internal_.ButtonType.md#color)
- [default](akashaproject_design_system._internal_.ButtonType.md#default)
- [disabled](akashaproject_design_system._internal_.ButtonType.md#disabled)
- [extend](akashaproject_design_system._internal_.ButtonType.md#extend)
- [hover](akashaproject_design_system._internal_.ButtonType.md#hover)
- [maxWidth](akashaproject_design_system._internal_.ButtonType.md#maxwidth)
- [minWidth](akashaproject_design_system._internal_.ButtonType.md#minwidth)
- [option](akashaproject_design_system._internal_.ButtonType.md#option)
- [padding](akashaproject_design_system._internal_.ButtonType.md#padding)
- [primary](akashaproject_design_system._internal_.ButtonType.md#primary)
- [secondary](akashaproject_design_system._internal_.ButtonType.md#secondary)
- [size](akashaproject_design_system._internal_.ButtonType.md#size)
- [transition](akashaproject_design_system._internal_.ButtonType.md#transition)

## Properties

### active

• `Optional` **active**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) & { `default?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) ; `primary?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) ; `secondary?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)  }

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:180

___

### badge

• `Optional` **badge**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | `Object` |
| `container.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `container.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `container.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `size?` | `Object` |
| `size.medium?` | `string` |
| `text?` | `Object` |
| `text.size?` | `Object` |
| `text.size.medium?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:148

___

### border

• `Optional` **border**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `radius?` | `string` |
| `width?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:163

___

### color

• `Optional` **color**: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:168

___

### default

• `Optional` **default**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:176

___

### disabled

• `Optional` **disabled**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) & { `opacity?`: [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype)  }

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:185

___

### extend

• `Optional` **extend**: [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\>

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:169

___

### hover

• `Optional` **hover**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) & { `default?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) ; `primary?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md) ; `secondary?`: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)  }

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:186

___

### maxWidth

• `Optional` **maxWidth**: `string`

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:171

___

### minWidth

• `Optional` **minWidth**: `string`

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:170

___

### option

• `Optional` **option**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:179

___

### padding

• `Optional` **padding**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `horizontal?` | `string` |
| `vertical?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:172

___

### primary

• `Optional` **primary**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:177

___

### secondary

• `Optional` **secondary**: [`ButtonKindType`](akashaproject_design_system._internal_.ButtonKindType.md)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:178

___

### size

• `Optional` **size**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `large?` | `Object` |
| `large.border?` | `Object` |
| `large.border.radius?` | `string` |
| `large.pad?` | `Object` |
| `large.pad.horizontal?` | `string` |
| `large.pad.vertical?` | `string` |
| `medium?` | `Object` |
| `medium.border?` | `Object` |
| `medium.border.radius?` | `string` |
| `medium.pad?` | `Object` |
| `medium.pad.horizontal?` | `string` |
| `medium.pad.vertical?` | `string` |
| `small?` | `Object` |
| `small.border?` | `Object` |
| `small.border.radius?` | `string` |
| `small.pad?` | `Object` |
| `small.pad.horizontal?` | `string` |
| `small.pad.vertical?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:191

___

### transition

• `Optional` **transition**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `duration?` | `number` |
| `properties?` | `string`[] |
| `timing?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:220
