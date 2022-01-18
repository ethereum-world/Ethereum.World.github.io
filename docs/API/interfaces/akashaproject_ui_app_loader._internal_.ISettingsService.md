[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / ISettingsService

# Interface: ISettingsService

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).ISettingsService

## Implemented by

- [`Settings`](../classes/akashaproject_ui_app_loader._internal_.Settings.md)

## Table of contents

### Methods

- [get](akashaproject_ui_app_loader._internal_.ISettingsService.md#get)
- [remove](akashaproject_ui_app_loader._internal_.ISettingsService.md#remove)
- [set](akashaproject_ui_app_loader._internal_.ISettingsService.md#set)

## Methods

### get

▸ **get**(`moduleName`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:4

___

### remove

▸ **remove**(`moduleName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |

#### Returns

`void`

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:5

___

### set

▸ **set**(`moduleName`, `value`): [`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `moduleName` | `string` |
| `value` | [`Record`](../modules/akashaproject_ui_app_loader._internal_.md#record)<`string`, `unknown`\> \| [[`string`, `unknown`]] |

#### Returns

[`ServiceCallResult`](../modules/akashaproject_ui_app_loader._internal_.md#servicecallresult)<`unknown`\>

#### Defined in

sdk/typings/lib/interfaces/settings.d.ts:3
