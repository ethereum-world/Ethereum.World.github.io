[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / BaseThemedCssFunction

# Interface: BaseThemedCssFunction<T\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).BaseThemedCssFunction

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `object` |

## Callable

### BaseThemedCssFunction

▸ **BaseThemedCssFunction**(`first`, ...`interpolations`): [`FlattenSimpleInterpolation`](../modules/akashaproject_design_system._internal_.md#flattensimpleinterpolation)

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) |
| `...interpolations` | [`SimpleInterpolation`](../modules/akashaproject_design_system._internal_.md#simpleinterpolation)[] |

#### Returns

[`FlattenSimpleInterpolation`](../modules/akashaproject_design_system._internal_.md#flattensimpleinterpolation)

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:292

### BaseThemedCssFunction

▸ **BaseThemedCssFunction**(`first`, ...`interpolations`): [`FlattenInterpolation`](../modules/akashaproject_design_system._internal_.md#flatteninterpolation)<[`ThemeProps`](akashaproject_design_system._internal_.ThemeProps.md)<`T`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) \| [`InterpolationFunction`](../modules/akashaproject_design_system._internal_.md#interpolationfunction)<[`ThemeProps`](akashaproject_design_system._internal_.ThemeProps.md)<`T`\>\> |
| `...interpolations` | [`Interpolation`](../modules/akashaproject_design_system._internal_.md#interpolation)<[`ThemeProps`](akashaproject_design_system._internal_.ThemeProps.md)<`T`\>\>[] |

#### Returns

[`FlattenInterpolation`](../modules/akashaproject_design_system._internal_.md#flatteninterpolation)<[`ThemeProps`](akashaproject_design_system._internal_.ThemeProps.md)<`T`\>\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:293

### BaseThemedCssFunction

▸ **BaseThemedCssFunction**<`P`\>(`first`, ...`interpolations`): [`FlattenInterpolation`](../modules/akashaproject_design_system._internal_.md#flatteninterpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<`P`, `T`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `P` | extends `object` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `first` | [`TemplateStringsArray`](akashaproject_design_system._internal_.TemplateStringsArray.md) \| [`CSSObject`](akashaproject_design_system._internal_.CSSObject.md) \| [`InterpolationFunction`](../modules/akashaproject_design_system._internal_.md#interpolationfunction)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<`P`, `T`\>\> |
| `...interpolations` | [`Interpolation`](../modules/akashaproject_design_system._internal_.md#interpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<`P`, `T`\>\>[] |

#### Returns

[`FlattenInterpolation`](../modules/akashaproject_design_system._internal_.md#flatteninterpolation)<[`ThemedStyledProps`](../modules/akashaproject_design_system._internal_.md#themedstyledprops)<`P`, `T`\>\>

#### Defined in

ui/design/node_modules/@types/styled-components/index.d.ts:297
