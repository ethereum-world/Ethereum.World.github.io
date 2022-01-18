[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / i18n

# Interface: i18n

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).i18n

## Table of contents

### Properties

- [exists](akashaproject_ui_awf_typings._internal_.i18n.md#exists)
- [format](akashaproject_ui_awf_typings._internal_.i18n.md#format)
- [isInitialized](akashaproject_ui_awf_typings._internal_.i18n.md#isinitialized)
- [language](akashaproject_ui_awf_typings._internal_.i18n.md#language)
- [languages](akashaproject_ui_awf_typings._internal_.i18n.md#languages)
- [modules](akashaproject_ui_awf_typings._internal_.i18n.md#modules)
- [options](akashaproject_ui_awf_typings._internal_.i18n.md#options)
- [services](akashaproject_ui_awf_typings._internal_.i18n.md#services)
- [store](akashaproject_ui_awf_typings._internal_.i18n.md#store)
- [t](akashaproject_ui_awf_typings._internal_.i18n.md#t)

### Methods

- [addResource](akashaproject_ui_awf_typings._internal_.i18n.md#addresource)
- [addResourceBundle](akashaproject_ui_awf_typings._internal_.i18n.md#addresourcebundle)
- [addResources](akashaproject_ui_awf_typings._internal_.i18n.md#addresources)
- [changeLanguage](akashaproject_ui_awf_typings._internal_.i18n.md#changelanguage)
- [cloneInstance](akashaproject_ui_awf_typings._internal_.i18n.md#cloneinstance)
- [createInstance](akashaproject_ui_awf_typings._internal_.i18n.md#createinstance)
- [dir](akashaproject_ui_awf_typings._internal_.i18n.md#dir)
- [emit](akashaproject_ui_awf_typings._internal_.i18n.md#emit)
- [getDataByLanguage](akashaproject_ui_awf_typings._internal_.i18n.md#getdatabylanguage)
- [getFixedT](akashaproject_ui_awf_typings._internal_.i18n.md#getfixedt)
- [getResource](akashaproject_ui_awf_typings._internal_.i18n.md#getresource)
- [getResourceBundle](akashaproject_ui_awf_typings._internal_.i18n.md#getresourcebundle)
- [hasResourceBundle](akashaproject_ui_awf_typings._internal_.i18n.md#hasresourcebundle)
- [init](akashaproject_ui_awf_typings._internal_.i18n.md#init)
- [loadLanguages](akashaproject_ui_awf_typings._internal_.i18n.md#loadlanguages)
- [loadNamespaces](akashaproject_ui_awf_typings._internal_.i18n.md#loadnamespaces)
- [loadResources](akashaproject_ui_awf_typings._internal_.i18n.md#loadresources)
- [off](akashaproject_ui_awf_typings._internal_.i18n.md#off)
- [on](akashaproject_ui_awf_typings._internal_.i18n.md#on)
- [reloadResources](akashaproject_ui_awf_typings._internal_.i18n.md#reloadresources)
- [removeResourceBundle](akashaproject_ui_awf_typings._internal_.i18n.md#removeresourcebundle)
- [setDefaultNamespace](akashaproject_ui_awf_typings._internal_.i18n.md#setdefaultnamespace)
- [use](akashaproject_ui_awf_typings._internal_.i18n.md#use)

## Properties

### exists

• **exists**: [`ExistsFunction`](akashaproject_ui_awf_typings._internal_.ExistsFunction.md)<`string`, [`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap)\>

Uses similar args as the t function and returns true if a key exists.

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:939

___

### format

• **format**: [`FormatFunction`](../modules/akashaproject_ui_awf_typings._internal_.md#formatfunction)

Exposes interpolation.format function added on init.

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1010

___

### isInitialized

• **isInitialized**: `boolean`

Is initialized

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1132

___

### language

• **language**: `string`

Is set to the current detected or set language.
If you need the primary used language depending on your configuration (supportedLngs, load) you will prefer using i18next.languages[0].

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:970

___

### languages

• **languages**: readonly `string`[]

Is set to an array of language-codes that will be used it order to lookup the translation value.

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:975

___

### modules

• **modules**: [`Modules`](akashaproject_ui_awf_typings._internal_.Modules.md)

List of modules used

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:924

___

### options

• **options**: [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md)

Current options

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1127

___

### services

• **services**: [`Services`](akashaproject_ui_awf_typings._internal_.Services.md)

Internal container for all used plugins and implementation details like languageUtils, pluralResolvers, etc.

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:929

___

### store

• **store**: [`ResourceStore`](../classes/akashaproject_ui_awf_typings._internal_.ResourceStore.md)

Internal container for translation resources

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:934

___

### t

• **t**: [`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:899

## Methods

### addResource

▸ **addResource**(`lng`, `ns`, `key`, `value`, `options?`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Adds one key/value.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |
| `key` | `string` |
| `value` | `string` |
| `options?` | `Object` |
| `options.keySeparator?` | `string` |
| `options.silent?` | `boolean` |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1083

___

### addResourceBundle

▸ **addResourceBundle**(`lng`, `ns`, `resources`, `deep?`, `overwrite?`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Adds a complete bundle.
Setting deep param to true will extend existing translations in that file.
Setting overwrite to true it will overwrite existing translations in that file.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |
| `resources` | `any` |
| `deep?` | `boolean` |
| `overwrite?` | `boolean` |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1101

___

### addResources

▸ **addResources**(`lng`, `ns`, `resources`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Adds multiple key/values.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |
| `resources` | `any` |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1094

___

### changeLanguage

▸ **changeLanguage**(`lng?`, `callback?`): `Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

Changes the language. The callback will be called as soon translations were loaded or an error occurs while loading.
HINT: For easy testing - setting lng to 'cimode' will set t function to always return the key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng?` | `string` |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

`Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:964

___

### cloneInstance

▸ **cloneInstance**(`options?`, `callback?`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Creates a clone of the current instance. Shares store, plugins and initial configuration.
Can be used to create an instance sharing storage but being independent on set language or namespaces.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1024

___

### createInstance

▸ **createInstance**(`options?`, `callback?`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Will return a new i18next instance.
Please read the options page for details on configuration options.
Providing a callback will automatically call init.
The callback will be called after all translations were loaded or with an error when failed (in case of using a backend).

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1018

___

### dir

▸ **dir**(`lng?`): ``"ltr"`` \| ``"rtl"``

Returns rtl or ltr depending on languages read direction.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng?` | `string` |

#### Returns

``"ltr"`` \| ``"rtl"``

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1005

___

### emit

▸ **emit**(`eventName`): `void`

Emit event

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1137

___

### getDataByLanguage

▸ **getDataByLanguage**(`lng`): `Object`

Returns a resource data by language.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `translation` | `Object` |

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:944

___

### getFixedT

▸ **getFixedT**(`lng`, `ns?`, `keyPrefix?`): [`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)

Returns a t function that defaults to given language or namespace.
Both params could be arrays of languages or namespaces and will be treated as fallbacks in that case.
On the returned function you can like in the t function override the languages or namespaces by passing them in options or by prepending namespace.

Accepts optional keyPrefix that will be automatically applied to returned t function.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` \| readonly `string`[] |
| `ns?` | `string` \| readonly `string`[] |
| `keyPrefix?` | `string` |

#### Returns

[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:953

▸ **getFixedT**(`lng`, `ns`, `keyPrefix?`): [`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | ``null`` |
| `ns` | `string` \| readonly `string`[] |
| `keyPrefix?` | `string` |

#### Returns

[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:958

___

### getResource

▸ **getResource**(`lng`, `ns`, `key`, `options?`): `any`

Gets one value by given key.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |
| `key` | `string` |
| `options?` | [`Pick`](../modules/akashaproject_ui_awf_typings._internal_.md#pick)<[`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md), ``"keySeparator"`` \| ``"ignoreJSONStructure"``\> |

#### Returns

`any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1073

___

### getResourceBundle

▸ **getResourceBundle**(`lng`, `ns`): `any`

Returns a resource bundle.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |

#### Returns

`any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1117

___

### hasResourceBundle

▸ **hasResourceBundle**(`lng`, `ns`): `boolean`

Checks if a resource bundle exists.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |

#### Returns

`boolean`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1112

___

### init

▸ **init**(`callback?`): `Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

The default of the i18next module is an i18next instance ready to be initialized by calling init.
You can create additional instances using the createInstance function.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) | will be called after all translations were loaded or with an error when failed (in case of using a backend). |

#### Returns

`Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:908

▸ **init**(`options`, `callback?`): `Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

`Promise`<[`TFunction`](akashaproject_ui_awf_typings._internal_.TFunction.md)\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:909

___

### loadLanguages

▸ **loadLanguages**(`lngs`, `callback?`): `Promise`<`void`\>

Loads additional languages not defined in init options (preload).

#### Parameters

| Name | Type |
| :------ | :------ |
| `lngs` | `string` \| readonly `string`[] |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:985

___

### loadNamespaces

▸ **loadNamespaces**(`ns`, `callback?`): `Promise`<`void`\>

Loads additional namespaces not defined in init options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ns` | `string` \| readonly `string`[] |
| `callback?` | [`Callback`](../modules/akashaproject_ui_awf_typings._internal_.md#callback) |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:980

___

### loadResources

▸ **loadResources**(`callback?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback?` | (`err`: `any`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:911

___

### off

▸ **off**(`event`, `listener?`): `void`

Remove event listener
removes all callback when callback not specified

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `string` |
| `listener?` | (...`args`: `any`[]) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1068

___

### on

▸ **on**(`event`, `callback`): `void`

Gets fired after initialization.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"initialized"`` |
| `callback` | (`options`: [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md)) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1029

▸ **on**(`event`, `callback`): `void`

Gets fired on loaded resources.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"loaded"`` |
| `callback` | (`loaded`: { [language: string]: readonly `string`[];  }) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1034

▸ **on**(`event`, `callback`): `void`

Gets fired if loading resources failed.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"failedLoading"`` |
| `callback` | (`lng`: `string`, `ns`: `string`, `msg`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1039

▸ **on**(`event`, `callback`): `void`

Gets fired on accessing a key not existing.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"missingKey"`` |
| `callback` | (`lngs`: readonly `string`[], `namespace`: `string`, `key`: `string`, `res`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1044

▸ **on**(`event`, `callback`): `void`

Gets fired when resources got added or removed.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"added"`` \| ``"removed"`` |
| `callback` | (`lng`: `string`, `ns`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1052

▸ **on**(`event`, `callback`): `void`

Gets fired when changeLanguage got called.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | ``"languageChanged"`` |
| `callback` | (`lng`: `string`) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1057

▸ **on**(`event`, `listener`): `void`

Event listener

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `string` |
| `listener` | (...`args`: `any`[]) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1062

___

### reloadResources

▸ **reloadResources**(`lngs?`, `ns?`, `callback?`): `Promise`<`void`\>

Reloads resources on given state. Optionally you can pass an array of languages and namespaces as params if you don't want to reload all.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lngs?` | `string` \| readonly `string`[] |
| `ns?` | `string` \| readonly `string`[] |
| `callback?` | () => `void` |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:990

▸ **reloadResources**(`lngs`, `ns`, `callback?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `lngs` | ``null`` |
| `ns` | `string` \| readonly `string`[] |
| `callback?` | () => `void` |

#### Returns

`Promise`<`void`\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:995

___

### removeResourceBundle

▸ **removeResourceBundle**(`lng`, `ns`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

Removes an existing bundle.

#### Parameters

| Name | Type |
| :------ | :------ |
| `lng` | `string` |
| `ns` | `string` |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1122

___

### setDefaultNamespace

▸ **setDefaultNamespace**(`ns`): `void`

Changes the default namespace.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ns` | `string` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:1000

___

### use

▸ **use**<`T`\>(`module`): [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

The use function is there to load additional plugins to i18next.
For available module see the plugins page and don't forget to read the documentation of the plugin.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Module`](akashaproject_ui_awf_typings._internal_.Module.md) |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `module` | `T` \| [`NewableModule`](akashaproject_ui_awf_typings._internal_.NewableModule.md)<`T`\> \| [`Newable`](akashaproject_ui_awf_typings._internal_.Newable.md)<`T`\> | Accepts a class or object |

#### Returns

[`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:919
