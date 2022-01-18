[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ThemeType

# Interface: ThemeType

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ThemeType

## Hierarchy

- **`ThemeType`**

  ↳ [`DefaultTheme`](akashaproject_design_system._internal_.DefaultTheme-1.md)

## Table of contents

### Properties

- [accordion](akashaproject_design_system._internal_.ThemeType.md#accordion)
- [anchor](akashaproject_design_system._internal_.ThemeType.md#anchor)
- [avatar](akashaproject_design_system._internal_.ThemeType.md#avatar)
- [box](akashaproject_design_system._internal_.ThemeType.md#box)
- [button](akashaproject_design_system._internal_.ThemeType.md#button)
- [calendar](akashaproject_design_system._internal_.ThemeType.md#calendar)
- [card](akashaproject_design_system._internal_.ThemeType.md#card)
- [carousel](akashaproject_design_system._internal_.ThemeType.md#carousel)
- [chart](akashaproject_design_system._internal_.ThemeType.md#chart)
- [checkBox](akashaproject_design_system._internal_.ThemeType.md#checkbox)
- [checkBoxGroup](akashaproject_design_system._internal_.ThemeType.md#checkboxgroup)
- [clock](akashaproject_design_system._internal_.ThemeType.md#clock)
- [collapsible](akashaproject_design_system._internal_.ThemeType.md#collapsible)
- [dataTable](akashaproject_design_system._internal_.ThemeType.md#datatable)
- [dateInput](akashaproject_design_system._internal_.ThemeType.md#dateinput)
- [diagram](akashaproject_design_system._internal_.ThemeType.md#diagram)
- [drop](akashaproject_design_system._internal_.ThemeType.md#drop)
- [fileInput](akashaproject_design_system._internal_.ThemeType.md#fileinput)
- [formField](akashaproject_design_system._internal_.ThemeType.md#formfield)
- [global](akashaproject_design_system._internal_.ThemeType.md#global)
- [grommet](akashaproject_design_system._internal_.ThemeType.md#grommet)
- [heading](akashaproject_design_system._internal_.ThemeType.md#heading)
- [icon](akashaproject_design_system._internal_.ThemeType.md#icon)
- [layer](akashaproject_design_system._internal_.ThemeType.md#layer)
- [list](akashaproject_design_system._internal_.ThemeType.md#list)
- [maskedInput](akashaproject_design_system._internal_.ThemeType.md#maskedinput)
- [menu](akashaproject_design_system._internal_.ThemeType.md#menu)
- [meter](akashaproject_design_system._internal_.ThemeType.md#meter)
- [pagination](akashaproject_design_system._internal_.ThemeType.md#pagination)
- [paragraph](akashaproject_design_system._internal_.ThemeType.md#paragraph)
- [radioButton](akashaproject_design_system._internal_.ThemeType.md#radiobutton)
- [radioButtonGroup](akashaproject_design_system._internal_.ThemeType.md#radiobuttongroup)
- [rangeInput](akashaproject_design_system._internal_.ThemeType.md#rangeinput)
- [rangeSelector](akashaproject_design_system._internal_.ThemeType.md#rangeselector)
- [select](akashaproject_design_system._internal_.ThemeType.md#select)
- [skipLinks](akashaproject_design_system._internal_.ThemeType.md#skiplinks)
- [spinner](akashaproject_design_system._internal_.ThemeType.md#spinner)
- [tab](akashaproject_design_system._internal_.ThemeType.md#tab)
- [table](akashaproject_design_system._internal_.ThemeType.md#table)
- [tabs](akashaproject_design_system._internal_.ThemeType.md#tabs)
- [text](akashaproject_design_system._internal_.ThemeType.md#text)
- [textArea](akashaproject_design_system._internal_.ThemeType.md#textarea)
- [textInput](akashaproject_design_system._internal_.ThemeType.md#textinput)
- [tip](akashaproject_design_system._internal_.ThemeType.md#tip)
- [video](akashaproject_design_system._internal_.ThemeType.md#video)
- [worldMap](akashaproject_design_system._internal_.ThemeType.md#worldmap)

## Properties

### accordion

• `Optional` **accordion**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |
| `heading?` | `Object` |
| `heading.level?` | `string` |
| `heading.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `hover?` | `Object` |
| `hover.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `hover.heading?` | `Object` |
| `hover.heading.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons?` | `Object` |
| `icons.collapse?` | `any` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.expand?` | `any` |
| `panel?` | `Object` |
| `panel.border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:408

___

### anchor

• `Optional` **anchor**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`AnchorExtendedProps`](akashaproject_design_system._internal_.AnchorExtendedProps.md)\> |
| `fontWeight?` | `number` |
| `hover?` | `Object` |
| `hover.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`AnchorExtendedProps`](akashaproject_design_system._internal_.AnchorExtendedProps.md)\> |
| `hover.textDecoration?` | `string` |
| `textDecoration?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:429

___

### avatar

• `Optional` **avatar**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `size?` | `Object` |
| `size.large?` | `string` |
| `size.medium?` | `string` |
| `size.small?` | `string` |
| `size.xlarge?` | `string` |
| `size.xsmall?` | `string` |
| `text?` | `Object` |
| `text.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `text.fontWeight?` | `number` |
| `text.size?` | `Object` |
| `text.size.large?` | `string` |
| `text.size.medium?` | `string` |
| `text.size.small?` | `string` |
| `text.size.xlarge?` | `string` |
| `text.size.xsmall?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:439

___

### box

• `Optional` **box**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `responsiveBreakpoint?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:462

___

### button

• `Optional` **button**: [`ButtonType`](akashaproject_design_system._internal_.ButtonType.md)

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:466

___

### calendar

• `Optional` **calendar**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `day?` | `Object` |
| `day.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `heading?` | `Object` |
| `heading.level?` | `string` |
| `icons?` | `Object` |
| `icons.next?` | `any` |
| `icons.previous?` | `any` |
| `icons.small?` | `Object` |
| `icons.small.next?` | `any` |
| `icons.small.previous?` | `any` |
| `large?` | `Object` |
| `large.daySize?` | `string` |
| `large.fontSize?` | `string` |
| `large.lineHeight?` | `number` |
| `large.slideDuration?` | `string` |
| `medium?` | `Object` |
| `medium.daySize?` | `string` |
| `medium.fontSize?` | `string` |
| `medium.lineHeight?` | `number` |
| `medium.slideDuration?` | `string` |
| `small?` | `Object` |
| `small.daySize?` | `string` |
| `small.fontSize?` | `string` |
| `small.lineHeight?` | `number` |
| `small.slideDuration?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:467

___

### card

• `Optional` **card**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `body?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `footer?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `header?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:502

___

### carousel

• `Optional` **carousel**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `animation?` | `Object` |
| `animation.duration?` | `number` |
| `disabled?` | `Object` |
| `disabled.icons?` | `Object` |
| `disabled.icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons?` | `Object` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.current?` | `any` |
| `icons.next?` | `any` |
| `icons.previous?` | `any` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:508

___

### chart

• `Optional` **chart**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:524

___

### checkBox

• `Optional` **checkBox**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `border?` | `Object` |
| `border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.width?` | `string` |
| `check?` | `Object` |
| `check.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `check.radius?` | `string` |
| `check.thickness?` | `string` |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `gap?` | `string` |
| `hover?` | `Object` |
| `hover.background?` | `Object` |
| `hover.background.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `hover.border?` | `Object` |
| `hover.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icon?` | `Object` |
| `icon.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `icon.size?` | `string` |
| `icons?` | `Object` |
| `icons.checked?` | `any` |
| `icons.indeterminate?` | `any` |
| `label?` | `Object` |
| `label.align?` | `string` |
| `pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `size?` | `string` |
| `toggle?` | `Object` |
| `toggle.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `toggle.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `toggle.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `toggle.knob?` | `Object` |
| `toggle.knob.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `toggle.radius?` | `string` |
| `toggle.size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:528

___

### checkBoxGroup

• `Optional` **checkBoxGroup**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:573

___

### clock

• `Optional` **clock**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `analog?` | `Object` |
| `analog.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `analog.hour?` | `Object` |
| `analog.hour.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `analog.hour.shape?` | `string` |
| `analog.hour.size?` | `string` |
| `analog.hour.width?` | `string` |
| `analog.minute?` | `Object` |
| `analog.minute.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `analog.minute.shape?` | `string` |
| `analog.minute.size?` | `string` |
| `analog.minute.width?` | `string` |
| `analog.second?` | `Object` |
| `analog.second.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `analog.second.shape?` | `string` |
| `analog.second.size?` | `string` |
| `analog.second.width?` | `string` |
| `analog.size?` | `Object` |
| `analog.size.huge?` | `string` |
| `analog.size.large?` | `string` |
| `analog.size.medium?` | `string` |
| `analog.size.small?` | `string` |
| `analog.size.xlarge?` | `string` |
| `digital?` | `Object` |
| `digital.text?` | `Object` |
| `digital.text.large?` | `Object` |
| `digital.text.large.height?` | `number` |
| `digital.text.large.size?` | `string` |
| `digital.text.medium?` | `Object` |
| `digital.text.medium.height?` | `number` |
| `digital.text.medium.size?` | `string` |
| `digital.text.small?` | `Object` |
| `digital.text.small.height?` | `number` |
| `digital.text.small.size?` | `string` |
| `digital.text.xlarge?` | `Object` |
| `digital.text.xlarge.height?` | `number` |
| `digital.text.xlarge.size?` | `string` |
| `digital.text.xsmall?` | `Object` |
| `digital.text.xsmall.height?` | `number` |
| `digital.text.xsmall.size?` | `string` |
| `digital.text.xxlarge?` | `Object` |
| `digital.text.xxlarge.height?` | `number` |
| `digital.text.xxlarge.size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:576

___

### collapsible

• `Optional` **collapsible**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `baseline?` | `number` |
| `minSpeed?` | `number` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:634

___

### dataTable

• `Optional` **dataTable**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `body?` | `Object` |
| `body.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `groupEnd?` | `Object` |
| `groupEnd.border?` | `Object` |
| `groupEnd.border.side?` | `string` |
| `groupEnd.border.size?` | `string` |
| `groupHeader?` | `Object` |
| `groupHeader.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `groupHeader.border?` | `Object` |
| `groupHeader.border.side?` | `string` |
| `groupHeader.border.size?` | `string` |
| `groupHeader.fill?` | `string` |
| `groupHeader.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `header?` | `Object` |
| `header.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `header.border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |
| `header.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `header.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `header.font?` | `Object` |
| `header.font.size?` | `string` |
| `header.font.weight?` | `string` |
| `header.gap?` | `string` |
| `header.hover?` | `Object` |
| `header.hover.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `header.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `header.units?` | [`TextProps`](akashaproject_design_system._internal_.TextProps.md) |
| `icons?` | `Object` |
| `icons.ascending?` | `any` |
| `icons.contract?` | `any` |
| `icons.descending?` | `any` |
| `icons.expand?` | `any` |
| `icons.sortable?` | `any` |
| `pinned?` | `Object` |
| `pinned.body?` | `Object` |
| `pinned.body.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `pinned.body.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `pinned.footer?` | `Object` |
| `pinned.footer.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `pinned.footer.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `pinned.header?` | `Object` |
| `pinned.header.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `pinned.header.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `primary?` | `Object` |
| `primary.weight?` | `string` |
| `resize?` | `Object` |
| `resize.border?` | `Object` |
| `resize.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `resize.border.side?` | `string` |
| `resize.hover?` | `Object` |
| `resize.hover.border?` | `Object` |
| `resize.hover.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `resize.hover.border.side` | `string` |
| `resize.hover.border.size` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:643

___

### dateInput

• `Optional` **dateInput**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `icon?` | `Object` |
| `icon.size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:638

___

### diagram

• `Optional` **diagram**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `line?` | `Object` |
| `line.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:717

___

### drop

• `Optional` **drop**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `maxHeight?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:723

___

### fileInput

• `Optional` **fileInput**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |
| `dragOver?` | `Object` |
| `dragOver.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `dragOver.border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |
| `dragOver.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `dragOver.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `hover?` | `Object` |
| `hover.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `hover.border?` | [`BorderType`](../modules/akashaproject_design_system._internal_.md#bordertype) |
| `hover.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `hover.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `icons?` | `Object` |
| `icons.remove?` | `any` |
| `label?` | [`TextProps`](akashaproject_design_system._internal_.TextProps.md) & { `extend?`: [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\>  } |
| `margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `message?` | [`TextProps`](akashaproject_design_system._internal_.TextProps.md) & { `extend?`: [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\>  } |
| `pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `round?` | [`RoundType`](../modules/akashaproject_design_system._internal_.md#roundtype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:727

___

### formField

• `Optional` **formField**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `border?` | ``false`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``true`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"end"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"start"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"left"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"right"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"top"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"bottom"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"horizontal"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"vertical"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"all"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"between"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  } ; `position?`: `string` ; `side?`: [`BoxSideType`](../modules/akashaproject_design_system._internal_.md#boxsidetype) ; `size?`: `string` ; `style?`: [`BoxStyleType`](../modules/akashaproject_design_system._internal_.md#boxstyletype)  } & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  } ; `position?`: `string` ; `side?`: [`BoxSideType`](../modules/akashaproject_design_system._internal_.md#boxsidetype) ; `size?`: `string` ; `style?`: [`BoxStyleType`](../modules/akashaproject_design_system._internal_.md#boxstyletype)  }[] & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } |
| `content?` | `Object` |
| `content.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `content.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `disabled?` | `Object` |
| `disabled.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `disabled.border?` | `Object` |
| `disabled.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `disabled.label?` | `Object` |
| `disabled.label.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `error?` | `Object` |
| `error.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `error.border?` | ``false`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``true`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"end"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"start"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"left"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"right"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"top"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"bottom"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"horizontal"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"vertical"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"all"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & ``"between"`` & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  } ; `position?`: `string` ; `side?`: [`BoxSideType`](../modules/akashaproject_design_system._internal_.md#boxsidetype) ; `size?`: `string` ; `style?`: [`BoxStyleType`](../modules/akashaproject_design_system._internal_.md#boxstyletype)  } & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } & { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  } ; `position?`: `string` ; `side?`: [`BoxSideType`](../modules/akashaproject_design_system._internal_.md#boxsidetype) ; `size?`: `string` ; `style?`: [`BoxStyleType`](../modules/akashaproject_design_system._internal_.md#boxstyletype)  }[] & { `error?`: { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  }  } |
| `error.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `error.container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `error.icon?` | `any` |
| `error.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `focus?` | `Object` |
| `focus.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `focus.border?` | `Object` |
| `focus.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `help?` | `Object` |
| `help.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `help.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `info?` | `Object` |
| `info.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `info.container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `info.icon?` | `any` |
| `info.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `label?` | [`FormFieldLabelType`](akashaproject_design_system._internal_.FormFieldLabelType.md) |
| `margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `round?` | [`RoundType`](../modules/akashaproject_design_system._internal_.md#roundtype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:752

___

### global

• `Optional` **global**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `active?` | `Object` |
| `active.background?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) \| { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `opacity?`: [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype)  } |
| `active.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `animation?` | `Object` |
| `animation.duration?` | `string` |
| `animation.jiggle?` | `Object` |
| `animation.jiggle.duration?` | `string` |
| `borderSize?` | `Object` |
| `borderSize.large?` | `string` |
| `borderSize.medium?` | `string` |
| `borderSize.small?` | `string` |
| `borderSize.xlarge?` | `string` |
| `borderSize.xsmall?` | `string` |
| `breakpoints?` | `Object` |
| `breakpoints.large?` | `Object` |
| `breakpoints.large.borderSize?` | `Object` |
| `breakpoints.large.borderSize.large?` | `string` |
| `breakpoints.large.borderSize.medium?` | `string` |
| `breakpoints.large.borderSize.small?` | `string` |
| `breakpoints.large.borderSize.xlarge?` | `string` |
| `breakpoints.large.borderSize.xsmall?` | `string` |
| `breakpoints.large.edgeSize?` | `Object` |
| `breakpoints.large.edgeSize.hair?` | `string` |
| `breakpoints.large.edgeSize.large?` | `string` |
| `breakpoints.large.edgeSize.medium?` | `string` |
| `breakpoints.large.edgeSize.none?` | `string` |
| `breakpoints.large.edgeSize.small?` | `string` |
| `breakpoints.large.edgeSize.xlarge?` | `string` |
| `breakpoints.large.edgeSize.xsmall?` | `string` |
| `breakpoints.large.edgeSize.xxsmall?` | `string` |
| `breakpoints.large.size?` | `Object` |
| `breakpoints.large.size.full?` | `string` |
| `breakpoints.large.size.large?` | `string` |
| `breakpoints.large.size.medium?` | `string` |
| `breakpoints.large.size.small?` | `string` |
| `breakpoints.large.size.xlarge?` | `string` |
| `breakpoints.large.size.xsmall?` | `string` |
| `breakpoints.large.size.xxsmall?` | `string` |
| `breakpoints.large.value?` | `number` |
| `breakpoints.medium?` | `Object` |
| `breakpoints.medium.borderSize?` | `Object` |
| `breakpoints.medium.borderSize.large?` | `string` |
| `breakpoints.medium.borderSize.medium?` | `string` |
| `breakpoints.medium.borderSize.small?` | `string` |
| `breakpoints.medium.borderSize.xlarge?` | `string` |
| `breakpoints.medium.borderSize.xsmall?` | `string` |
| `breakpoints.medium.edgeSize?` | `Object` |
| `breakpoints.medium.edgeSize.hair?` | `string` |
| `breakpoints.medium.edgeSize.large?` | `string` |
| `breakpoints.medium.edgeSize.medium?` | `string` |
| `breakpoints.medium.edgeSize.none?` | `string` |
| `breakpoints.medium.edgeSize.small?` | `string` |
| `breakpoints.medium.edgeSize.xlarge?` | `string` |
| `breakpoints.medium.edgeSize.xsmall?` | `string` |
| `breakpoints.medium.edgeSize.xxsmall?` | `string` |
| `breakpoints.medium.size?` | `Object` |
| `breakpoints.medium.size.full?` | `string` |
| `breakpoints.medium.size.large?` | `string` |
| `breakpoints.medium.size.medium?` | `string` |
| `breakpoints.medium.size.small?` | `string` |
| `breakpoints.medium.size.xlarge?` | `string` |
| `breakpoints.medium.size.xsmall?` | `string` |
| `breakpoints.medium.size.xxsmall?` | `string` |
| `breakpoints.medium.value?` | `number` |
| `breakpoints.small?` | `Object` |
| `breakpoints.small.borderSize?` | `Object` |
| `breakpoints.small.borderSize.large?` | `string` |
| `breakpoints.small.borderSize.medium?` | `string` |
| `breakpoints.small.borderSize.small?` | `string` |
| `breakpoints.small.borderSize.xlarge?` | `string` |
| `breakpoints.small.borderSize.xsmall?` | `string` |
| `breakpoints.small.edgeSize?` | `Object` |
| `breakpoints.small.edgeSize.hair?` | `string` |
| `breakpoints.small.edgeSize.large?` | `string` |
| `breakpoints.small.edgeSize.medium?` | `string` |
| `breakpoints.small.edgeSize.none?` | `string` |
| `breakpoints.small.edgeSize.small?` | `string` |
| `breakpoints.small.edgeSize.xlarge?` | `string` |
| `breakpoints.small.edgeSize.xsmall?` | `string` |
| `breakpoints.small.edgeSize.xxsmall?` | `string` |
| `breakpoints.small.size?` | `Object` |
| `breakpoints.small.size.full?` | `string` |
| `breakpoints.small.size.large?` | `string` |
| `breakpoints.small.size.medium?` | `string` |
| `breakpoints.small.size.small?` | `string` |
| `breakpoints.small.size.xlarge?` | `string` |
| `breakpoints.small.size.xsmall?` | `string` |
| `breakpoints.small.size.xxsmall?` | `string` |
| `breakpoints.small.value?` | `number` |
| `colors?` | [`Colors`](../modules/akashaproject_design_system._internal_.md#colors) |
| `control?` | `Object` |
| `control.border?` | `Object` |
| `control.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `control.border.radius?` | `string` |
| `control.border.width?` | `string` |
| `control.disabled?` | `Object` |
| `control.disabled.opacity` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `debounceDelay?` | `number` |
| `deviceBreakpoints?` | `Object` |
| `deviceBreakpoints.computer?` | `string` |
| `deviceBreakpoints.phone?` | `string` |
| `deviceBreakpoints.tablet?` | `string` |
| `drop?` | `Object` |
| `drop.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `drop.border?` | `Object` |
| `drop.border.radius?` | `string` |
| `drop.border.width?` | `string` |
| `drop.intelligentMargin?` | `boolean` |
| `drop.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `drop.shadowSize?` | `string` |
| `drop.zIndex?` | `string` |
| `edgeSize?` | `Object` |
| `edgeSize.hair?` | `string` |
| `edgeSize.large?` | `string` |
| `edgeSize.medium?` | `string` |
| `edgeSize.none?` | `string` |
| `edgeSize.responsiveBreakpoint?` | `string` |
| `edgeSize.small?` | `string` |
| `edgeSize.xlarge?` | `string` |
| `edgeSize.xsmall?` | `string` |
| `edgeSize.xxsmall?` | `string` |
| `elevation?` | `Object` |
| `elevation.dark?` | `Object` |
| `elevation.dark.large?` | `string` |
| `elevation.dark.medium?` | `string` |
| `elevation.dark.none?` | `string` |
| `elevation.dark.small?` | `string` |
| `elevation.dark.xlarge?` | `string` |
| `elevation.dark.xsmall?` | `string` |
| `elevation.light?` | `Object` |
| `elevation.light.large?` | `string` |
| `elevation.light.medium?` | `string` |
| `elevation.light.none?` | `string` |
| `elevation.light.small?` | `string` |
| `elevation.light.xlarge?` | `string` |
| `elevation.light.xsmall?` | `string` |
| `focus?` | `Object` |
| `focus.border?` | `Object` |
| `focus.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `focus.outline?` | `Object` |
| `focus.outline.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `focus.outline.size?` | `string` |
| `focus.shadow?` | `Object` |
| `focus.shadow.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `focus.shadow.size?` | `string` |
| `font?` | `Object` |
| `font.face?` | `string` |
| `font.family?` | `string` |
| `font.height?` | `string` |
| `font.maxWidth?` | `string` |
| `font.size?` | `string` |
| `font.weight?` | `string` \| `number` |
| `graph?` | `Object` |
| `graph.colors?` | [`GraphColorsType`](../modules/akashaproject_design_system._internal_.md#graphcolorstype) |
| `hover?` | `Object` |
| `hover.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `hover.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `input?` | `Object` |
| `input.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `input.font?` | `Object` |
| `input.font.height?` | `string` |
| `input.font.size?` | `string` |
| `input.font.weight?` | `string` \| `number` |
| `input.padding?` | `string` \| { `bottom?`: `string` ; `horizontal?`: `string` ; `left?`: `string` ; `right?`: `string` ; `top?`: `string` ; `vertical?`: `string`  } |
| `input.weight?` | `string` \| `number` |
| `opacity?` | `Object` |
| `opacity.medium?` | `number` |
| `opacity.strong?` | `number` |
| `opacity.weak?` | `number` |
| `selected?` | `Object` |
| `selected.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `selected.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `size?` | `Object` |
| `size.full?` | `string` |
| `size.large?` | `string` |
| `size.medium?` | `string` |
| `size.small?` | `string` |
| `size.xlarge?` | `string` |
| `size.xsmall?` | `string` |
| `size.xxlarge?` | `string` |
| `size.xxsmall?` | `string` |
| `spacing?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:231

___

### grommet

• `Optional` **grommet**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:804

___

### heading

• `Optional` **heading**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `font?` | `Object` |
| `level?` | `Object` |
| `level.1?` | `Object` |
| `level.1.font?` | `Object` |
| `level.1.large?` | `Object` |
| `level.1.large.height?` | `string` |
| `level.1.large.maxWidth?` | `string` |
| `level.1.large.size?` | `string` |
| `level.1.medium?` | `Object` |
| `level.1.medium.height?` | `string` |
| `level.1.medium.maxWidth?` | `string` |
| `level.1.medium.size?` | `string` |
| `level.1.small?` | `Object` |
| `level.1.small.height?` | `string` |
| `level.1.small.maxWidth?` | `string` |
| `level.1.small.size?` | `string` |
| `level.1.xlarge?` | `Object` |
| `level.1.xlarge.height?` | `string` |
| `level.1.xlarge.maxWidth?` | `string` |
| `level.1.xlarge.size?` | `string` |
| `level.2?` | `Object` |
| `level.2.font?` | `Object` |
| `level.2.large?` | `Object` |
| `level.2.large.height?` | `string` |
| `level.2.large.maxWidth?` | `string` |
| `level.2.large.size?` | `string` |
| `level.2.medium?` | `Object` |
| `level.2.medium.height?` | `string` |
| `level.2.medium.maxWidth?` | `string` |
| `level.2.medium.size?` | `string` |
| `level.2.small?` | `Object` |
| `level.2.small.height?` | `string` |
| `level.2.small.maxWidth?` | `string` |
| `level.2.small.size?` | `string` |
| `level.2.xlarge?` | `Object` |
| `level.2.xlarge.height?` | `string` |
| `level.2.xlarge.maxWidth?` | `string` |
| `level.2.xlarge.size?` | `string` |
| `level.3?` | `Object` |
| `level.3.font?` | `Object` |
| `level.3.large?` | `Object` |
| `level.3.large.height?` | `string` |
| `level.3.large.maxWidth?` | `string` |
| `level.3.large.size?` | `string` |
| `level.3.medium?` | `Object` |
| `level.3.medium.height?` | `string` |
| `level.3.medium.maxWidth?` | `string` |
| `level.3.medium.size?` | `string` |
| `level.3.small?` | `Object` |
| `level.3.small.height?` | `string` |
| `level.3.small.maxWidth?` | `string` |
| `level.3.small.size?` | `string` |
| `level.3.xlarge?` | `Object` |
| `level.3.xlarge.height?` | `string` |
| `level.3.xlarge.maxWidth?` | `string` |
| `level.3.xlarge.size?` | `string` |
| `level.4?` | `Object` |
| `level.4.font?` | `Object` |
| `level.4.large?` | `Object` |
| `level.4.large.height?` | `string` |
| `level.4.large.maxWidth?` | `string` |
| `level.4.large.size?` | `string` |
| `level.4.medium?` | `Object` |
| `level.4.medium.height?` | `string` |
| `level.4.medium.maxWidth?` | `string` |
| `level.4.medium.size?` | `string` |
| `level.4.small?` | `Object` |
| `level.4.small.height?` | `string` |
| `level.4.small.maxWidth?` | `string` |
| `level.4.small.size?` | `string` |
| `level.4.xlarge?` | `Object` |
| `level.4.xlarge.height?` | `string` |
| `level.4.xlarge.maxWidth?` | `string` |
| `level.4.xlarge.size?` | `string` |
| `level.5?` | `Object` |
| `level.5.font?` | `Object` |
| `level.5.large?` | `Object` |
| `level.5.large.height?` | `string` |
| `level.5.large.maxWidth?` | `string` |
| `level.5.large.size?` | `string` |
| `level.5.medium?` | `Object` |
| `level.5.medium.height?` | `string` |
| `level.5.medium.maxWidth?` | `string` |
| `level.5.medium.size?` | `string` |
| `level.5.small?` | `Object` |
| `level.5.small.height?` | `string` |
| `level.5.small.maxWidth?` | `string` |
| `level.5.small.size?` | `string` |
| `level.5.xlarge?` | `Object` |
| `level.5.xlarge.height?` | `string` |
| `level.5.xlarge.maxWidth?` | `string` |
| `level.5.xlarge.size?` | `string` |
| `level.6?` | `Object` |
| `level.6.font?` | `Object` |
| `level.6.large?` | `Object` |
| `level.6.large.height?` | `string` |
| `level.6.large.maxWidth?` | `string` |
| `level.6.large.size?` | `string` |
| `level.6.medium?` | `Object` |
| `level.6.medium.height?` | `string` |
| `level.6.medium.maxWidth?` | `string` |
| `level.6.medium.size?` | `string` |
| `level.6.small?` | `Object` |
| `level.6.small.height?` | `string` |
| `level.6.small.maxWidth?` | `string` |
| `level.6.small.size?` | `string` |
| `level.6.xlarge?` | `Object` |
| `level.6.xlarge.height?` | `string` |
| `level.6.xlarge.maxWidth?` | `string` |
| `level.6.xlarge.size?` | `string` |
| `responsiveBreakpoint?` | `string` |
| `weight?` | `number` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:807

___

### icon

• `Optional` **icon**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `size?` | `Object` |
| `size.large?` | `string` |
| `size.medium?` | `string` |
| `size.small?` | `string` |
| `size.xlarge?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:954

___

### layer

• `Optional` **layer**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `border?` | `Object` |
| `border.intelligentRounding?` | `boolean` |
| `border.radius?` | `string` |
| `container?` | `Object` |
| `container.elevation?` | `string` |
| `container.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `container.zIndex?` | `string` |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `overlay?` | `Object` |
| `overlay.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `responsiveBreakpoint?` | `string` |
| `zIndex?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:964

___

### list

• `Optional` **list**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `icons?` | `Object` |
| `icons.down?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `icons.up?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `item?` | `Object` |
| `item.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `item.border?` | `string` \| { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) ; `side?`: `string` ; `size?`: `string`  } |
| `item.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `item.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:982

___

### maskedInput

• `Optional` **maskedInput**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | `Object` |
| `container.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `disabled?` | `Object` |
| `disabled.opacity?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1002

___

### menu

• `Optional` **menu**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `drop?` | [`DropProps`](akashaproject_design_system._internal_.DropProps.md) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `icons?` | `Object` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.down?` | `any` |
| `icons.up?` | `any` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1011

___

### meter

• `Optional` **meter**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `colors?` | [`GraphColorsType`](../modules/akashaproject_design_system._internal_.md#graphcolorstype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1021

___

### pagination

• `Optional` **pagination**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `button?` | [`ButtonType`](akashaproject_design_system._internal_.ButtonType.md) |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `controls?` | `Object` |
| `controls.align?` | `string` |
| `controls.direction?` | [`DirectionType`](../modules/akashaproject_design_system._internal_.md#directiontype) |
| `controls.gap?` | `string` |
| `controls.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `controls.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `icons?` | `Object` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.next?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `icons.previous?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1026

___

### paragraph

• `Optional` **paragraph**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `large?` | `Object` |
| `large.height?` | `string` |
| `large.maxWidth?` | `string` |
| `large.size?` | `string` |
| `medium?` | `Object` |
| `medium.height?` | `string` |
| `medium.maxWidth?` | `string` |
| `medium.size?` | `string` |
| `small?` | `Object` |
| `small.height?` | `string` |
| `small.maxWidth?` | `string` |
| `small.size?` | `string` |
| `xlarge?` | `Object` |
| `xlarge.height?` | `string` |
| `xlarge.maxWidth?` | `string` |
| `xlarge.size?` | `string` |
| `xxlarge?` | `Object` |
| `xxlarge.height?` | `string` |
| `xxlarge.maxWidth?` | `string` |
| `xxlarge.size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1042

___

### radioButton

• `Optional` **radioButton**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `border?` | `Object` |
| `border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.width?` | `string` |
| `check?` | `Object` |
| `check.background?` | `Object` |
| `check.background.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `check.radius?` | `string` |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `font?` | `Object` |
| `font.weight?` | `string` \| `number` |
| `gap?` | `string` |
| `hover?` | `Object` |
| `hover.background?` | `Object` |
| `hover.background.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `hover.border?` | `Object` |
| `hover.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icon?` | `Object` |
| `icon.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `icon.size?` | `string` |
| `icons?` | `Object` |
| `icons.circle?` | `string` |
| `size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1070

___

### radioButtonGroup

• `Optional` **radioButtonGroup**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1103

___

### rangeInput

• `Optional` **rangeInput**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `thumb?` | `Object` |
| `thumb.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `track?` | `Object` |
| `track.color?` | `any` |
| `track.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `track.height?` | `string` |
| `track.lower?` | `Object` |
| `track.lower.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `track.lower.opacity?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `track.opacity?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `track.upper?` | `Object` |
| `track.upper.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `track.upper.opacity?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1106

___

### rangeSelector

• `Optional` **rangeSelector**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | `Object` |
| `background.invert?` | `Object` |
| `background.invert.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `edge?` | `Object` |
| `edge.type?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1126

___

### select

• `Optional` **select**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `clear?` | `Object` |
| `clear.container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `clear.text?` | [`TextProps`](akashaproject_design_system._internal_.TextProps.md) |
| `container?` | `Object` |
| `container.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `control?` | `Object` |
| `control.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `control.open?` | `string` \| `object` |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `icons?` | `Object` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.down?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `icons.margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `icons.up?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `options?` | `Object` |
| `options.container?` | [`BoxExtendedProps`](akashaproject_design_system._internal_.BoxExtendedProps.md) |
| `options.text?` | [`TextExtendedProps`](akashaproject_design_system._internal_.TextExtendedProps.md) |
| `searchInput?` | [`ReactComponentElement`](akashaproject_design_system._internal_.ReactComponentElement.md)<`any`, [`Pick`](../modules/akashaproject_design_system._internal_.md#pick)<`any`, `string` \| `number` \| `symbol`\>\> |
| `step?` | `number` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1136

___

### skipLinks

• `Optional` **skipLinks**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `label?` | [`TextProps`](akashaproject_design_system._internal_.TextProps.md) |
| `position?` | [`LayerPositionType`](../modules/akashaproject_design_system._internal_.md#layerpositiontype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1164

___

### spinner

• `Optional` **spinner**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) \| { `color?`: [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype)  } \| { `size?`: `string`  } |
| `icon?` | [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode) |
| `size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1169

___

### tab

• `Optional` **tab**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `active?` | `Object` |
| `active.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `active.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `border?` | `Object` |
| `border.active?` | `Object` |
| `border.active.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.disabled?` | `Object` |
| `border.disabled.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.hover?` | `Object` |
| `border.hover.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `border.hover.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `border.side?` | `string` |
| `border.size?` | `string` |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `disabled?` | `Object` |
| `disabled.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `hover?` | `Object` |
| `hover.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `hover.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `hover.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `margin?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1177

___

### table

• `Optional` **table**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `body?` | `Object` |
| `body.align?` | `string` |
| `body.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `body.border?` | `string` |
| `body.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `body.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `footer?` | `Object` |
| `footer.align?` | `string` |
| `footer.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `footer.border?` | `string` |
| `footer.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `footer.fill?` | `string` |
| `footer.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `footer.verticalAlign?` | `string` |
| `header?` | `Object` |
| `header.align?` | `string` |
| `header.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `header.border?` | `string` |
| `header.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `header.fill?` | `string` |
| `header.pad?` | [`EdgeType`](../modules/akashaproject_design_system._internal_.md#edgetype) |
| `header.verticalAlign?` | `string` |
| `row?` | `Object` |
| `row.hover?` | `Object` |
| `row.hover.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `row.hover.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1229

___

### tabs

• `Optional` **tabs**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `gap?` | `string` |
| `header?` | `Object` |
| `header.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `header.border?` | `Object` |
| `header.border.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `header.border.side?` | `string` |
| `header.border.size?` | `string` |
| `header.border.style?` | `string` |
| `header.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `panel?` | `Object` |
| `panel.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1211

___

### text

• `Optional` **text**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `2xl?` | `Object` |
| `2xl.height?` | `string` |
| `2xl.maxWidth?` | `string` |
| `2xl.size?` | `string` |
| `3xl?` | `Object` |
| `3xl.height?` | `string` |
| `3xl.maxWidth?` | `string` |
| `3xl.size?` | `string` |
| `4xl?` | `Object` |
| `4xl.height?` | `string` |
| `4xl.maxWidth?` | `string` |
| `4xl.size?` | `string` |
| `5xl?` | `Object` |
| `5xl.height?` | `string` |
| `5xl.maxWidth?` | `string` |
| `5xl.size?` | `string` |
| `6xl?` | `Object` |
| `6xl.height?` | `string` |
| `6xl.maxWidth?` | `string` |
| `6xl.size?` | `string` |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `large?` | `Object` |
| `large.height?` | `string` |
| `large.maxWidth?` | `string` |
| `large.size?` | `string` |
| `medium?` | `Object` |
| `medium.height?` | `string` |
| `medium.maxWidth?` | `string` |
| `medium.size?` | `string` |
| `small?` | `Object` |
| `small.height?` | `string` |
| `small.maxWidth?` | `string` |
| `small.size?` | `string` |
| `xlarge?` | `Object` |
| `xlarge.height?` | `string` |
| `xlarge.maxWidth?` | `string` |
| `xlarge.size?` | `string` |
| `xsmall?` | `Object` |
| `xsmall.height?` | `string` |
| `xsmall.maxWidth?` | `string` |
| `xsmall.size?` | `string` |
| `xxlarge?` | `Object` |
| `xxlarge.height?` | `string` |
| `xxlarge.maxWidth?` | `string` |
| `xxlarge.size?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1262

___

### textArea

• `Optional` **textArea**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `disabled?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1320

___

### textInput

• `Optional` **textInput**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `container?` | `Object` |
| `container.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `disabled?` | [`OpacityType`](../modules/akashaproject_design_system._internal_.md#opacitytype) |
| `extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `placeholder?` | `Object` |
| `placeholder.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |
| `suggestions?` | `Object` |
| `suggestions.extend?` | [`ExtendType`](../modules/akashaproject_design_system._internal_.md#extendtype)<[`Record`](../modules/akashaproject_design_system._internal_.md#record)<`string`, `any`\>\> |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1324

___

### tip

• `Optional` **tip**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `content?` | [`BoxProps`](akashaproject_design_system._internal_.BoxProps.md) |
| `drop?` | [`DropProps`](akashaproject_design_system._internal_.DropProps.md) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1337

___

### video

• `Optional` **video**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `captions?` | `Object` |
| `captions.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `controls?` | `Object` |
| `controls.background?` | [`BackgroundType`](../modules/akashaproject_design_system._internal_.md#backgroundtype) |
| `icons?` | `Object` |
| `icons.closedCaption?` | `any` |
| `icons.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `icons.configure?` | `any` |
| `icons.fullScreen?` | `any` |
| `icons.pause?` | `any` |
| `icons.play?` | `any` |
| `icons.reduceVolume?` | `any` |
| `icons.volume?` | `any` |
| `scrubber?` | `Object` |
| `scrubber.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1341

___

### worldMap

• `Optional` **worldMap**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `continent?` | `Object` |
| `continent.active?` | `string` |
| `continent.base?` | `string` |
| `hover?` | `Object` |
| `hover.color?` | [`ColorType`](../modules/akashaproject_design_system._internal_.md#colortype) |
| `place?` | `Object` |
| `place.active?` | `string` |
| `place.base?` | `string` |

#### Defined in

ui/design/node_modules/grommet/themes/base.d.ts:1362
