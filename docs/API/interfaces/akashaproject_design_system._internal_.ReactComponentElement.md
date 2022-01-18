[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ReactComponentElement

# Interface: ReactComponentElement<T, P\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ReactComponentElement

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends keyof `JSX.IntrinsicElements` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\> |
| `P` | [`Pick`](../modules/akashaproject_design_system._internal_.md#pick)<[`ComponentProps`](../modules/akashaproject_design_system._internal_.md#componentprops)<`T`\>, [`Exclude`](../modules/akashaproject_design_system._internal_.md#exclude)<keyof [`ComponentProps`](../modules/akashaproject_design_system._internal_.md#componentprops)<`T`\>, ``"key"`` \| ``"ref"``\>\> |

## Hierarchy

- [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<`P`, [`Exclude`](../modules/akashaproject_design_system._internal_.md#exclude)<`T`, `number`\>\>

  ↳ **`ReactComponentElement`**

## Table of contents

### Properties

- [key](akashaproject_design_system._internal_.ReactComponentElement.md#key)
- [props](akashaproject_design_system._internal_.ReactComponentElement.md#props)
- [type](akashaproject_design_system._internal_.ReactComponentElement.md#type)

## Properties

### key

• **key**: [`Key`](../modules/akashaproject_design_system._internal_.md#key)

#### Inherited from

[ReactElement](akashaproject_design_system._internal_.ReactElement.md).[key](akashaproject_design_system._internal_.ReactElement.md#key)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:149

___

### props

• **props**: `P`

#### Inherited from

[ReactElement](akashaproject_design_system._internal_.ReactElement.md).[props](akashaproject_design_system._internal_.ReactElement.md#props)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:148

___

### type

• **type**: [`Exclude`](../modules/akashaproject_design_system._internal_.md#exclude)<`T`, `number`\>

#### Inherited from

[ReactElement](akashaproject_design_system._internal_.ReactElement.md).[type](akashaproject_design_system._internal_.ReactElement.md#type)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:147
