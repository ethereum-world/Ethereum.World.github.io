[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-widget-login-cta](akashaproject_ui_widget_login_cta.md) / <internal\>

# Namespace: <internal\>

[@akashaproject/ui-widget-login-cta](akashaproject_ui_widget_login_cta.md).<internal>

## Table of contents

### Enumerations

- [EventTypes](../enums/akashaproject_ui_widget_login_cta._internal_.EventTypes.md)
- [ItemTypes](../enums/akashaproject_ui_widget_login_cta._internal_.ItemTypes.md)
- [LogoTypeSource](../enums/akashaproject_ui_widget_login_cta._internal_.LogoTypeSource.md)
- [MenuItemAreaType](../enums/akashaproject_ui_widget_login_cta._internal_.MenuItemAreaType.md)
- [MenuItemType](../enums/akashaproject_ui_widget_login_cta._internal_.MenuItemType.md)

### Interfaces

- [AppRegistryInfo](../interfaces/akashaproject_ui_widget_login_cta._internal_.AppRegistryInfo.md)
- [DOMStringList](../interfaces/akashaproject_ui_widget_login_cta._internal_.DOMStringList.md)
- [ExtensionPointDefinition](../interfaces/akashaproject_ui_widget_login_cta._internal_.ExtensionPointDefinition.md)
- [IAppConfig](../interfaces/akashaproject_ui_widget_login_cta._internal_.IAppConfig.md)
- [IMenuItem](../interfaces/akashaproject_ui_widget_login_cta._internal_.IMenuItem.md)
- [ISingleSpaLifecycle](../interfaces/akashaproject_ui_widget_login_cta._internal_.ISingleSpaLifecycle.md)
- [IWidgetConfig](../interfaces/akashaproject_ui_widget_login_cta._internal_.IWidgetConfig.md)
- [IntegrationRegistrationOptions](../interfaces/akashaproject_ui_widget_login_cta._internal_.IntegrationRegistrationOptions.md)
- [IntegrationRegistryInfo](../interfaces/akashaproject_ui_widget_login_cta._internal_.IntegrationRegistryInfo.md)
- [LayoutConfig](../interfaces/akashaproject_ui_widget_login_cta._internal_.LayoutConfig.md)
- [Location](../interfaces/akashaproject_ui_widget_login_cta._internal_.Location.md)
- [LogoSourceType](../interfaces/akashaproject_ui_widget_login_cta._internal_.LogoSourceType.md)
- [UIEventData](../interfaces/akashaproject_ui_widget_login_cta._internal_.UIEventData.md)
- [URL](../interfaces/akashaproject_ui_widget_login_cta._internal_.URL.md)
- [URLSearchParams](../interfaces/akashaproject_ui_widget_login_cta._internal_.URLSearchParams.md)
- [WidgetRegistryInfo](../interfaces/akashaproject_ui_widget_login_cta._internal_.WidgetRegistryInfo.md)

### Type aliases

- [ActivityFn](akashaproject_ui_widget_login_cta._internal_.md#activityfn)
- [EventDataTypes](akashaproject_ui_widget_login_cta._internal_.md#eventdatatypes)
- [Record](akashaproject_ui_widget_login_cta._internal_.md#record)

### Variables

- [DOMStringList](akashaproject_ui_widget_login_cta._internal_.md#domstringlist)
- [Location](akashaproject_ui_widget_login_cta._internal_.md#location)
- [URL](akashaproject_ui_widget_login_cta._internal_.md#url)
- [URLSearchParams](akashaproject_ui_widget_login_cta._internal_.md#urlsearchparams)

## Type aliases

### ActivityFn

Ƭ **ActivityFn**: (`location`: [`Location`](akashaproject_ui_widget_login_cta._internal_.md#location), `pathToActiveWhen`: (`path`: `string`, `exact?`: `boolean`) => (`location`: [`Location`](akashaproject_ui_widget_login_cta._internal_.md#location)) => `boolean`, `layoutConfig?`: [`LayoutConfig`](../interfaces/akashaproject_ui_widget_login_cta._internal_.LayoutConfig.md)) => `boolean`

#### Type declaration

▸ (`location`, `pathToActiveWhen`, `layoutConfig?`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](akashaproject_ui_widget_login_cta._internal_.md#location) |
| `pathToActiveWhen` | (`path`: `string`, `exact?`: `boolean`) => (`location`: [`Location`](akashaproject_ui_widget_login_cta._internal_.md#location)) => `boolean` |
| `layoutConfig?` | [`LayoutConfig`](../interfaces/akashaproject_ui_widget_login_cta._internal_.LayoutConfig.md) |

##### Returns

`boolean`

#### Defined in

ui/typings/lib/app-loader.d.ts:15

___

### EventDataTypes

Ƭ **EventDataTypes**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `entryId?` | `string` |
| `entryType?` | [`ItemTypes`](../enums/akashaproject_ui_widget_login_cta._internal_.ItemTypes.md) |
| `name` | `string` |
| `version?` | `string` |

#### Defined in

ui/typings/lib/app-loader.d.ts:240

___

### Record

Ƭ **Record**<`K`, `T`\>: { [P in K]: T }

Construct a type with a set of properties K of type T

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof `any` |
| `T` | `T` |

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1499

## Variables

### DOMStringList

• **DOMStringList**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `prototype` | [`DOMStringList`](akashaproject_ui_widget_login_cta._internal_.md#domstringlist) |

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4005

___

### Location

• **Location**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `prototype` | [`Location`](akashaproject_ui_widget_login_cta._internal_.md#location) |

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9683

___

### URL

• **URL**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `prototype` | [`URL`](akashaproject_ui_widget_login_cta._internal_.md#url) |
| `createObjectURL` | (`object`: `any`) => `string` |
| `revokeObjectURL` | (`url`: `string`) => `void` |

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14936

___

### URLSearchParams

• **URLSearchParams**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `prototype` | [`URLSearchParams`](akashaproject_ui_widget_login_cta._internal_.md#urlsearchparams) |
| `toString` | () => `string` |

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14979
