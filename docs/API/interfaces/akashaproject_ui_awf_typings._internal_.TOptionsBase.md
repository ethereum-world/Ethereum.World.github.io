[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / TOptionsBase

# Interface: TOptionsBase

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).TOptionsBase

## Table of contents

### Properties

- [context](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#context)
- [count](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#count)
- [defaultValue](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#defaultvalue)
- [fallbackLng](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#fallbacklng)
- [interpolation](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#interpolation)
- [joinArrays](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#joinarrays)
- [keySeparator](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#keyseparator)
- [lng](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#lng)
- [lngs](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#lngs)
- [ns](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#ns)
- [nsSeparator](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#nsseparator)
- [postProcess](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#postprocess)
- [replace](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#replace)
- [returnObjects](akashaproject_ui_awf_typings._internal_.TOptionsBase.md#returnobjects)

## Properties

### context

• `Optional` **context**: `any`

Used for contexts (eg. male\female)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:627

___

### count

• `Optional` **count**: `number`

Count value used for plurals

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:623

___

### defaultValue

• `Optional` **defaultValue**: `any`

Default value to return if a translation was not found

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:619

___

### fallbackLng

• `Optional` **fallbackLng**: [`FallbackLng`](../modules/akashaproject_ui_awf_typings._internal_.md#fallbacklng)

Override language to lookup key if not found see fallbacks for details

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:643

___

### interpolation

• `Optional` **interpolation**: [`InterpolationOptions`](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md)

Override interpolation options

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:671

___

### joinArrays

• `Optional` **joinArrays**: `string`

Char, eg. '\n' that arrays will be joined by (can be set globally too)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:663

___

### keySeparator

• `Optional` **keySeparator**: `string` \| ``false``

Override char to separate keys

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:651

___

### lng

• `Optional` **lng**: `string`

Override language to use

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:635

___

### lngs

• `Optional` **lngs**: readonly `string`[]

Override languages to use

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:639

___

### ns

• `Optional` **ns**: `string` \| readonly `string`[]

Override namespaces (string or array)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:647

___

### nsSeparator

• `Optional` **nsSeparator**: `string` \| ``false``

Override char to split namespace from key

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:655

___

### postProcess

• `Optional` **postProcess**: `string` \| readonly `string`[]

String or array of postProcessors to apply see interval plurals as a sample

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:667

___

### replace

• `Optional` **replace**: `any`

Object with vars for interpolation - or put them directly in options

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:631

___

### returnObjects

• `Optional` **returnObjects**: `boolean`

Accessing an object not a translation string (can be set globally too)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:659
