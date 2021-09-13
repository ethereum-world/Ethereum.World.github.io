[AWF](../README.md) / [Exports](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/_akashaproject_ui_awf_testing_utils.md) / Config

# Interface: Config

[@akashaproject/ui-awf-testing-utils](../modules/_akashaproject_ui_awf_testing_utils.md).Config

## Table of contents

### Properties

- [asyncUtilTimeout](_akashaproject_ui_awf_testing_utils.Config.md#asyncutiltimeout)
- [computedStyleSupportsPseudoElements](_akashaproject_ui_awf_testing_utils.Config.md#computedstylesupportspseudoelements)
- [defaultHidden](_akashaproject_ui_awf_testing_utils.Config.md#defaulthidden)
- [showOriginalStackTrace](_akashaproject_ui_awf_testing_utils.Config.md#showoriginalstacktrace)
- [testIdAttribute](_akashaproject_ui_awf_testing_utils.Config.md#testidattribute)
- [throwSuggestions](_akashaproject_ui_awf_testing_utils.Config.md#throwsuggestions)

### Methods

- [asyncWrapper](_akashaproject_ui_awf_testing_utils.Config.md#asyncwrapper)
- [eventWrapper](_akashaproject_ui_awf_testing_utils.Config.md#eventwrapper)
- [getElementError](_akashaproject_ui_awf_testing_utils.Config.md#getelementerror)
- [unstable\_advanceTimersWrapper](_akashaproject_ui_awf_testing_utils.Config.md#unstable_advancetimerswrapper)

## Properties

### asyncUtilTimeout

• **asyncUtilTimeout**: `number`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:12

___

### computedStyleSupportsPseudoElements

• **computedStyleSupportsPseudoElements**: `boolean`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:13

___

### defaultHidden

• **defaultHidden**: `boolean`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:14

___

### showOriginalStackTrace

• **showOriginalStackTrace**: `boolean`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:15

___

### testIdAttribute

• **testIdAttribute**: `string`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:2

___

### throwSuggestions

• **throwSuggestions**: `boolean`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:16

## Methods

### asyncWrapper

▸ **asyncWrapper**(`cb`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (...`args`: `any`[]) => `any` |

#### Returns

`Promise`<`any`\>

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:9

___

### eventWrapper

▸ **eventWrapper**(`cb`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (...`args`: `any`[]) => `any` |

#### Returns

`void`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:11

___

### getElementError

▸ **getElementError**(`message`, `container`): `Error`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `container` | `Element` |

#### Returns

`Error`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:17

___

### unstable\_advanceTimersWrapper

▸ **unstable_advanceTimersWrapper**(`cb`): `unknown`

WARNING: `unstable` prefix means this API may change in patch and minor releases.

#### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (...`args`: `unknown`[]) => `unknown` |

#### Returns

`unknown`

#### Defined in

node_modules/@testing-library/dom/types/config.d.ts:7
