[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ThemedStyledFunctionBase

# Interface: ThemedStyledFunctionBase<C, T, O, A\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ThemedStyledFunctionBase

## Type parameters

| Name | Type |
| :------ | :------ |
| `C` | extends keyof `JSX.IntrinsicElements` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> |
| `T` | extends `object` |
| `O` | extends `object` = {} |
| `A` | extends keyof `any` = `never` |

## Hierarchy

- **`ThemedStyledFunctionBase`**

  ↳ [`ThemedStyledFunction`](akashaproject_design_system._internal_.ThemedStyledFunction.md)

## Callable

### ThemedStyledFunctionBase

▸ **ThemedStyledFunctionBase**(`first`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:197

### ThemedStyledFunctionBase

▸ **ThemedStyledFunctionBase**(`first`, ...`rest`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) \| [`InterpolationFunction`](../modules/akashaproject_design_system._internal_.md#interpolationfunction)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O`, `T`\>\> |
| `...rest` | [`Interpolation`](../modules/akashaproject_design_system._internal_.md#interpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O`, `T`\>\>[] |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:198

### ThemedStyledFunctionBase

▸ **ThemedStyledFunctionBase**<`U`\>(`first`, ...`rest`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O` & `U`, `A`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `U` | extends `object` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) \| [`InterpolationFunction`](../modules/akashaproject_design_system._internal_.md#interpolationfunction)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O` & `U`, `T`\>\> |
| `...rest` | [`Interpolation`](../modules/akashaproject_design_system._internal_.md#interpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O` & `U`, `T`\>\>[] |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O` & `U`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:205
