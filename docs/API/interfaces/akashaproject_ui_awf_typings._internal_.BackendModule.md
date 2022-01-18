[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / BackendModule

# Interface: BackendModule<TOptions\>

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).BackendModule

Used to load data for i18next.
Can be provided as a singleton or as a prototype constructor (preferred for supporting multiple instances of i18next).
For singleton set property `type` to `'backend'` For a prototype constructor set static property.

## Type parameters

| Name | Type |
| :------ | :------ |
| `TOptions` | `object` |

## Hierarchy

- [`Module`](akashaproject_ui_awf_typings._internal_.Module.md)

  ↳ **`BackendModule`**

## Table of contents

### Properties

- [type](akashaproject_ui_awf_typings._internal_.BackendModule.md#type)

### Methods

- [create](akashaproject_ui_awf_typings._internal_.BackendModule.md#create)
- [init](akashaproject_ui_awf_typings._internal_.BackendModule.md#init)
- [read](akashaproject_ui_awf_typings._internal_.BackendModule.md#read)
- [readMulti](akashaproject_ui_awf_typings._internal_.BackendModule.md#readmulti)
- [save](akashaproject_ui_awf_typings._internal_.BackendModule.md#save)

## Properties

### type

• **type**: ``"backend"``

#### Overrides

[Module](akashaproject_ui_awf_typings._internal_.Module.md).[type](akashaproject_ui_awf_typings._internal_.Module.md#type)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:801

## Methods

### create

▸ `Optional` **create**(`languages`, `namespace`, `key`, `fallbackValue`): `void`

Save the missing translation

#### Parameters

| Name | Type |
| :------ | :------ |
| `languages` | readonly `string`[] |
| `namespace` | `string` |
| `key` | `string` |
| `fallbackValue` | `string` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:805

___

### init

▸ **init**(`services`, `backendOptions`, `i18nextOptions`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `services` | [`Services`](akashaproject_ui_awf_typings._internal_.Services.md) |
| `backendOptions` | `TOptions` |
| `i18nextOptions` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:802

___

### read

▸ **read**(`language`, `namespace`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `language` | `string` |
| `namespace` | `string` |
| `callback` | [`ReadCallback`](../modules/akashaproject_ui_awf_typings._internal_.md#readcallback) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:803

___

### readMulti

▸ `Optional` **readMulti**(`languages`, `namespaces`, `callback`): `void`

Load multiple languages and namespaces. For backends supporting multiple resources loading

#### Parameters

| Name | Type |
| :------ | :------ |
| `languages` | readonly `string`[] |
| `namespaces` | readonly `string`[] |
| `callback` | [`MultiReadCallback`](../modules/akashaproject_ui_awf_typings._internal_.md#multireadcallback) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:812

___

### save

▸ `Optional` **save**(`language`, `namespace`, `data`): `void`

Store the translation. For backends acting as cache layer

#### Parameters

| Name | Type |
| :------ | :------ |
| `language` | `string` |
| `namespace` | `string` |
| `data` | [`ResourceLanguage`](akashaproject_ui_awf_typings._internal_.ResourceLanguage.md) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:818
