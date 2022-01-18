[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ThemedStyledFunction

# Interface: ThemedStyledFunction<C, T, O, A\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ThemedStyledFunction

## Type parameters

| Name | Type |
| :------ | :------ |
| `C` | extends keyof `JSX.IntrinsicElements` \| [`ComponentType`](../modules/akashaproject_design_system._internal_.md#componenttype)<`any`\> |
| `T` | extends `object` |
| `O` | extends `object` = {} |
| `A` | extends keyof `any` = `never` |

## Hierarchy

- [`ThemedStyledFunctionBase`](akashaproject_design_system._internal_.ThemedStyledFunctionBase.md)<`C`, `T`, `O`, `A`\>

  ↳ **`ThemedStyledFunction`**

## Callable

### ThemedStyledFunction

▸ **ThemedStyledFunction**(`first`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:197

### ThemedStyledFunction

▸ **ThemedStyledFunction**(`first`, ...`rest`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) \| [`InterpolationFunction`](../modules/akashaproject_design_system._internal_.md#interpolationfunction)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O`, `T`\>\> |
| `...rest` | [`Interpolation`](../modules/akashaproject_design_system._internal_.md#interpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `O`, `T`\>\>[] |

#### Returns

[`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:198

### ThemedStyledFunction

▸ **ThemedStyledFunction**<`U`\>(`first`, ...`rest`): [`StyledComponent`](../modules/akashaproject_design_system._internal_.md#styledcomponent)<`C`, `T`, `O` & `U`, `A`\>

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

## Table of contents

### Methods

- [attrs](akashaproject_design_system._internal_.ThemedStyledFunction.md#attrs)
- [withConfig](akashaproject_design_system._internal_.ThemedStyledFunction.md#withconfig)

## Methods

### attrs

▸ **attrs**<`U`, `NewA`\>(`attrs`): [`ThemedStyledFunction`](akashaproject_design_system._internal_.ThemedStyledFunction.md)<`C`, `T`, `O` & `NewA`, `A` \| keyof `NewA`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `U` | `U` |
| `NewA` | extends [`Partial`](../modules/akashaproject_design_system._internal_.md#partial)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `U`\> & { [others: string]: `any`;  } = {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `attrs` | [`Attrs`](../modules/akashaproject_design_system._internal_.md#attrs)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `U`, `NewA`, `T`\> |

#### Returns

[`ThemedStyledFunction`](akashaproject_design_system._internal_.ThemedStyledFunction.md)<`C`, `T`, `O` & `NewA`, `A` \| keyof `NewA`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:222

___

### withConfig

▸ **withConfig**<`Props`\>(`config`): [`ThemedStyledFunction`](akashaproject_design_system._internal_.ThemedStyledFunction.md)<`C`, `T`, `Props`, `A`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Props` | extends `object` = `O` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`StyledConfig`](akashaproject_design_system._internal_.StyledConfig.md)<[`StyledComponentPropsWithRef`](../modules/akashaproject_design_system._internal_.md#styledcomponentpropswithref)<`C`\> & `Props`\> |

#### Returns

[`ThemedStyledFunction`](akashaproject_design_system._internal_.ThemedStyledFunction.md)<`C`, `T`, `Props`, `A`\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:231
