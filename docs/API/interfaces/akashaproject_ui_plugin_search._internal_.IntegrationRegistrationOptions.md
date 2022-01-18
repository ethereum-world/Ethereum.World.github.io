[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-plugin-search](../modules/akashaproject_ui_plugin_search.md) / [<internal\>](../modules/akashaproject_ui_plugin_search._internal_.md) / IntegrationRegistrationOptions

# Interface: IntegrationRegistrationOptions

[@akashaproject/ui-plugin-search](../modules/akashaproject_ui_plugin_search.md).[<internal>](../modules/akashaproject_ui_plugin_search._internal_.md).IntegrationRegistrationOptions

## Table of contents

### Properties

- [extensionData](akashaproject_ui_plugin_search._internal_.IntegrationRegistrationOptions.md#extensiondata)
- [integrations](akashaproject_ui_plugin_search._internal_.IntegrationRegistrationOptions.md#integrations)
- [layoutConfig](akashaproject_ui_plugin_search._internal_.IntegrationRegistrationOptions.md#layoutconfig)
- [uiEvents](akashaproject_ui_plugin_search._internal_.IntegrationRegistrationOptions.md#uievents)
- [worldConfig](akashaproject_ui_plugin_search._internal_.IntegrationRegistrationOptions.md#worldconfig)

## Properties

### extensionData

• `Optional` **extensionData**: [`EventDataTypes`](../modules/akashaproject_ui_plugin_search._internal_.md#eventdatatypes)

#### Defined in

ui/typings/lib/app-loader.d.ts:37

___

### integrations

• `Optional` **integrations**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `configs` | [`Record`](../modules/akashaproject_ui_plugin_search._internal_.md#record)<`string`, [`IAppConfig`](akashaproject_ui_plugin_search._internal_.IAppConfig.md) \| [`IWidgetConfig`](akashaproject_ui_plugin_search._internal_.IWidgetConfig.md)\> |
| `infos` | ([`AppRegistryInfo`](akashaproject_ui_plugin_search._internal_.AppRegistryInfo.md) \| [`WidgetRegistryInfo`](akashaproject_ui_plugin_search._internal_.WidgetRegistryInfo.md))[] |

#### Defined in

ui/typings/lib/app-loader.d.ts:33

___

### layoutConfig

• `Optional` **layoutConfig**: [`LayoutConfig`](akashaproject_ui_plugin_search._internal_.LayoutConfig.md)

#### Defined in

ui/typings/lib/app-loader.d.ts:32

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](akashaproject_ui_plugin_search._internal_.UIEventData.md)\>

#### Defined in

ui/typings/lib/app-loader.d.ts:31

___

### worldConfig

• **worldConfig**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `title` | `string` |

#### Defined in

ui/typings/lib/app-loader.d.ts:28
