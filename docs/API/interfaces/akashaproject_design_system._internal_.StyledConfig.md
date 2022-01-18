[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / StyledConfig

# Interface: StyledConfig<O\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).StyledConfig

## Type parameters

| Name | Type |
| :------ | :------ |
| `O` | extends `object` = {} |

## Table of contents

### Properties

- [componentId](akashaproject_design_system._internal_.StyledConfig.md#componentid)
- [displayName](akashaproject_design_system._internal_.StyledConfig.md#displayname)
- [shouldForwardProp](akashaproject_design_system._internal_.StyledConfig.md#shouldforwardprop)

## Properties

### componentId

• `Optional` **componentId**: `string`

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:142

___

### displayName

• `Optional` **displayName**: `string`

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:143

___

### shouldForwardProp

• `Optional` **shouldForwardProp**: (`prop`: keyof `O`, `defaultValidatorFn`: (`prop`: keyof `O`) => `boolean`) => `boolean`

#### Type declaration

▸ (`prop`, `defaultValidatorFn`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `prop` | keyof `O` |
| `defaultValidatorFn` | (`prop`: keyof `O`) => `boolean` |

##### Returns

`boolean`

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:144
