[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / StyledComponentBase

# Interface: StyledComponentBase<C, T, O, A\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).StyledComponentBase

## Type parameters

| Name | Type |
| :------ | :------ |
| `C` | extends `string` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> |
| `T` | extends `object` |
| `O` | extends `object` = {} |
| `A` | extends keyof `any` = `never` |

## Hierarchy

- [`ForwardRefExoticBase`](../modules/akashaproject_design_system._internal_.md#forwardrefexoticbase)<[`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`\>\>

  ↳ **`StyledComponentBase`**

## Callable

### StyledComponentBase

▸ **StyledComponentBase**(`props`): [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<[`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`, `C`\>, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`, `C`\> & { `as?`: `undefined` ; `forwardedAs?`: `undefined`  } |

#### Returns

[`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<[`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`, `C`\>, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:171

### StyledComponentBase

▸ **StyledComponentBase**<`AsC`, `FAsC`\>(`props`): [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<[`StyledComponentPropsWithAs`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithas)<`AsC`, `T`, `O`, `A`, `AsC`, `FAsC`\>, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `AsC` | extends `string` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> = `C` |
| `FAsC` | extends `string` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> = `AsC` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`StyledComponentPropsWithAs`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithas)<`AsC`, `T`, `O`, `A`, `AsC`, `FAsC`\> |

#### Returns

[`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<[`StyledComponentPropsWithAs`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithas)<`AsC`, `T`, `O`, `A`, `AsC`, `FAsC`\>, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:174

## Table of contents

### Properties

- [$$typeof](akashaproject_design_system._internal_.StyledComponentBase.md#$$typeof)
- [defaultProps](akashaproject_design_system._internal_.StyledComponentBase.md#defaultprops)
- [displayName](akashaproject_design_system._internal_.StyledComponentBase.md#displayname)
- [propTypes](akashaproject_design_system._internal_.StyledComponentBase.md#proptypes)

### Methods

- [withComponent](akashaproject_design_system._internal_.StyledComponentBase.md#withcomponent)

## Properties

### $$typeof

• `Readonly` **$$typeof**: `symbol`

#### Inherited from

ForwardRefExoticBase.$$typeof

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:358

___

### defaultProps

• `Optional` **defaultProps**: [`Partial`](../modules/akashaproject_design_system._internal_.md#partial)<[`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`, `C`\>\>

#### Inherited from

ForwardRefExoticBase.defaultProps

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:800

___

### displayName

• `Optional` **displayName**: `string`

#### Inherited from

ForwardRefExoticBase.displayName

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:362

___

### propTypes

• `Optional` **propTypes**: [`WeakValidationMap`](../modules/akashaproject_design_system._internal_.md#weakvalidationmap)<[`StyledComponentProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentprops)<`C`, `T`, `O`, `A`, `C`\>\>

#### Inherited from

ForwardRefExoticBase.propTypes

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:801

## Methods

### withComponent

▸ **withComponent**<`WithC`\>(`component`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<[`StyledComponentInnerComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnercomponent)<`WithC`\>, `T`, `O` & [`StyledComponentInnerOtherProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnerotherprops)<`WithC`\>, `A` \| [`StyledComponentInnerAttrs`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnerattrs)<`WithC`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `WithC` | extends [`AnyStyledComponent`](../modules/akashaproject_design_system._internal_.md#anystyledcomponent) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | `WithC` |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<[`StyledComponentInnerComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnercomponent)<`WithC`\>, `T`, `O` & [`StyledComponentInnerOtherProps`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnerotherprops)<`WithC`\>, `A` \| [`StyledComponentInnerAttrs`](../modules/akashaproject_design_system._internal_.md#styledcomponentinnerattrs)<`WithC`\>\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:178

▸ **withComponent**<`WithC`\>(`component`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`WithC`, `T`, `O`, `A`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `WithC` | extends keyof `IntrinsicElements` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | `WithC` |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`WithC`, `T`, `O`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:186
