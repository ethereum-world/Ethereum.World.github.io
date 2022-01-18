[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ExtensionPointProps

# Interface: ExtensionPointProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ExtensionPointProps

## Table of contents

### Properties

- [className](akashaproject_design_system._internal_.ExtensionPointProps.md#classname)
- [mountOnRequest](akashaproject_design_system._internal_.ExtensionPointProps.md#mountonrequest)
- [name](akashaproject_design_system._internal_.ExtensionPointProps.md#name)
- [shouldMount](akashaproject_design_system._internal_.ExtensionPointProps.md#shouldmount)
- [style](akashaproject_design_system._internal_.ExtensionPointProps.md#style)

### Methods

- [onClick](akashaproject_design_system._internal_.ExtensionPointProps.md#onclick)
- [onMount](akashaproject_design_system._internal_.ExtensionPointProps.md#onmount)
- [onUnmount](akashaproject_design_system._internal_.ExtensionPointProps.md#onunmount)
- [onWrapperClick](akashaproject_design_system._internal_.ExtensionPointProps.md#onwrapperclick)

## Properties

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/utils/extension-point.tsx:4](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L4)

___

### mountOnRequest

• `Optional` **mountOnRequest**: `boolean`

#### Defined in

[ui/design/src/utils/extension-point.tsx:6](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L6)

___

### name

• **name**: `string`

#### Defined in

[ui/design/src/utils/extension-point.tsx:3](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L3)

___

### shouldMount

• `Optional` **shouldMount**: `boolean`

#### Defined in

[ui/design/src/utils/extension-point.tsx:7](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L7)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Defined in

[ui/design/src/utils/extension-point.tsx:5](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L5)

## Methods

### onClick

▸ `Optional` **onClick**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/utils/extension-point.tsx:8](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L8)

___

### onMount

▸ **onMount**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/utils/extension-point.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L10)

___

### onUnmount

▸ **onUnmount**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[ui/design/src/utils/extension-point.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L11)

___

### onWrapperClick

▸ `Optional` **onWrapperClick**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/utils/extension-point.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/utils/extension-point.tsx#L9)
