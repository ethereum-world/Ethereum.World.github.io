[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / AutoSizerProps

# Interface: AutoSizerProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).AutoSizerProps

## Table of contents

### Properties

- [className](akashaproject_design_system._internal_.AutoSizerProps.md#classname)
- [defaultHeight](akashaproject_design_system._internal_.AutoSizerProps.md#defaultheight)
- [defaultWidth](akashaproject_design_system._internal_.AutoSizerProps.md#defaultwidth)
- [disableHeight](akashaproject_design_system._internal_.AutoSizerProps.md#disableheight)
- [disableWidth](akashaproject_design_system._internal_.AutoSizerProps.md#disablewidth)
- [nonce](akashaproject_design_system._internal_.AutoSizerProps.md#nonce)
- [onResize](akashaproject_design_system._internal_.AutoSizerProps.md#onresize)
- [style](akashaproject_design_system._internal_.AutoSizerProps.md#style)

### Methods

- [children](akashaproject_design_system._internal_.AutoSizerProps.md#children)

## Properties

### className

• `Optional` **className**: `string`

Optional custom CSS class name to attach to root AutoSizer element.

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:19

___

### defaultHeight

• `Optional` **defaultHeight**: `number`

Default height to use for initial render; useful for SSR

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:22

___

### defaultWidth

• `Optional` **defaultWidth**: `number`

Default width to use for initial render; useful for SSR

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:25

___

### disableHeight

• `Optional` **disableHeight**: `boolean`

Disable dynamic :height property

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:28

___

### disableWidth

• `Optional` **disableWidth**: `boolean`

Disable dynamic :width property

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:31

___

### nonce

• `Optional` **nonce**: `string`

Nonce of the inlined stylesheet for Content Security Policy

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:34

___

### onResize

• `Optional` **onResize**: (`size`: [`Size`](akashaproject_design_system._internal_.Size.md)) => `void`

#### Type declaration

▸ (`size`): `void`

Callback to be invoked on-resize

##### Parameters

| Name | Type |
| :------ | :------ |
| `size` | [`Size`](akashaproject_design_system._internal_.Size.md) |

##### Returns

`void`

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:37

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

Optional inline style

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:40

## Methods

### children

▸ **children**(`size`): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

Function responsible for rendering children.

#### Parameters

| Name | Type |
| :------ | :------ |
| `size` | [`Size`](akashaproject_design_system._internal_.Size.md) |

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Defined in

ui/design/node_modules/@types/react-virtualized-auto-sizer/index.d.ts:16
