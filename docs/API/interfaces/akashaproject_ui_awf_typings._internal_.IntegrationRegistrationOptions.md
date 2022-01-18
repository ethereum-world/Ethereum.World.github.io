[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / IntegrationRegistrationOptions

# Interface: IntegrationRegistrationOptions

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).IntegrationRegistrationOptions

## Table of contents

### Properties

- [extensionData](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md#extensiondata)
- [integrations](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md#integrations)
- [layoutConfig](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md#layoutconfig)
- [uiEvents](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md#uievents)
- [worldConfig](akashaproject_ui_awf_typings._internal_.IntegrationRegistrationOptions.md#worldconfig)

## Properties

### extensionData

• `Optional` **extensionData**: [`EventDataTypes`](../modules/akashaproject_ui_awf_typings._internal_.md#eventdatatypes)

#### Defined in

[ui/typings/src/app-loader.ts:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L47)

___

### integrations

• `Optional` **integrations**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `configs` | [`Record`](../modules/akashaproject_ui_awf_typings._internal_.md#record)<`string`, [`IAppConfig`](akashaproject_ui_awf_typings._internal_.IAppConfig.md) \| [`IWidgetConfig`](akashaproject_ui_awf_typings._internal_.IWidgetConfig.md)\> |
| `infos` | ([`AppRegistryInfo`](akashaproject_ui_awf_typings._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](akashaproject_ui_awf_typings._internal_.WidgetRegistryInfo.md))[] |

#### Defined in

[ui/typings/src/app-loader.ts:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L43)

___

### layoutConfig

• `Optional` **layoutConfig**: [`LayoutConfig`](akashaproject_ui_awf_typings._internal_.LayoutConfig.md)

#### Defined in

[ui/typings/src/app-loader.ts:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L42)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](akashaproject_ui_awf_typings._internal_.UIEventData.md)\>

#### Defined in

[ui/typings/src/app-loader.ts:41](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L41)

___

### worldConfig

• **worldConfig**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `title` | `string` |

#### Defined in

[ui/typings/src/app-loader.ts:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L38)
