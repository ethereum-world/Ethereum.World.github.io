[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / InitOptions

# Interface: InitOptions

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).InitOptions

## Hierarchy

- [`MergeBy`](../modules/akashaproject_ui_awf_typings._internal_.md#mergeby)<[`DefaultPluginOptions`](akashaproject_ui_awf_typings._internal_.DefaultPluginOptions.md), [`PluginOptions`](akashaproject_ui_awf_typings._internal_.PluginOptions.md)\>

  ↳ **`InitOptions`**

## Table of contents

### Properties

- [appendNamespaceToCIMode](akashaproject_ui_awf_typings._internal_.InitOptions.md#appendnamespacetocimode)
- [appendNamespaceToMissingKey](akashaproject_ui_awf_typings._internal_.InitOptions.md#appendnamespacetomissingkey)
- [backend](akashaproject_ui_awf_typings._internal_.InitOptions.md#backend)
- [cache](akashaproject_ui_awf_typings._internal_.InitOptions.md#cache)
- [cleanCode](akashaproject_ui_awf_typings._internal_.InitOptions.md#cleancode)
- [compatibilityJSON](akashaproject_ui_awf_typings._internal_.InitOptions.md#compatibilityjson)
- [contextSeparator](akashaproject_ui_awf_typings._internal_.InitOptions.md#contextseparator)
- [debug](akashaproject_ui_awf_typings._internal_.InitOptions.md#debug)
- [defaultNS](akashaproject_ui_awf_typings._internal_.InitOptions.md#defaultns)
- [detection](akashaproject_ui_awf_typings._internal_.InitOptions.md#detection)
- [editor](akashaproject_ui_awf_typings._internal_.InitOptions.md#editor)
- [fallbackLng](akashaproject_ui_awf_typings._internal_.InitOptions.md#fallbacklng)
- [fallbackNS](akashaproject_ui_awf_typings._internal_.InitOptions.md#fallbackns)
- [i18nFormat](akashaproject_ui_awf_typings._internal_.InitOptions.md#i18nformat)
- [ignoreJSONStructure](akashaproject_ui_awf_typings._internal_.InitOptions.md#ignorejsonstructure)
- [initImmediate](akashaproject_ui_awf_typings._internal_.InitOptions.md#initimmediate)
- [interpolation](akashaproject_ui_awf_typings._internal_.InitOptions.md#interpolation)
- [joinArrays](akashaproject_ui_awf_typings._internal_.InitOptions.md#joinarrays)
- [keySeparator](akashaproject_ui_awf_typings._internal_.InitOptions.md#keyseparator)
- [lng](akashaproject_ui_awf_typings._internal_.InitOptions.md#lng)
- [load](akashaproject_ui_awf_typings._internal_.InitOptions.md#load)
- [locizeLastUsed](akashaproject_ui_awf_typings._internal_.InitOptions.md#locizelastused)
- [lowerCaseLng](akashaproject_ui_awf_typings._internal_.InitOptions.md#lowercaselng)
- [missingKeyHandler](akashaproject_ui_awf_typings._internal_.InitOptions.md#missingkeyhandler)
- [missingKeyNoValueFallbackToKey](akashaproject_ui_awf_typings._internal_.InitOptions.md#missingkeynovaluefallbacktokey)
- [nonExplicitSupportedLngs](akashaproject_ui_awf_typings._internal_.InitOptions.md#nonexplicitsupportedlngs)
- [nonExplicitWhitelist](akashaproject_ui_awf_typings._internal_.InitOptions.md#nonexplicitwhitelist)
- [ns](akashaproject_ui_awf_typings._internal_.InitOptions.md#ns)
- [nsSeparator](akashaproject_ui_awf_typings._internal_.InitOptions.md#nsseparator)
- [partialBundledLanguages](akashaproject_ui_awf_typings._internal_.InitOptions.md#partialbundledlanguages)
- [pluralSeparator](akashaproject_ui_awf_typings._internal_.InitOptions.md#pluralseparator)
- [postProcess](akashaproject_ui_awf_typings._internal_.InitOptions.md#postprocess)
- [postProcessPassResolved](akashaproject_ui_awf_typings._internal_.InitOptions.md#postprocesspassresolved)
- [preload](akashaproject_ui_awf_typings._internal_.InitOptions.md#preload)
- [react](akashaproject_ui_awf_typings._internal_.InitOptions.md#react)
- [resources](akashaproject_ui_awf_typings._internal_.InitOptions.md#resources)
- [returnEmptyString](akashaproject_ui_awf_typings._internal_.InitOptions.md#returnemptystring)
- [returnNull](akashaproject_ui_awf_typings._internal_.InitOptions.md#returnnull)
- [returnObjects](akashaproject_ui_awf_typings._internal_.InitOptions.md#returnobjects)
- [saveMissing](akashaproject_ui_awf_typings._internal_.InitOptions.md#savemissing)
- [saveMissingTo](akashaproject_ui_awf_typings._internal_.InitOptions.md#savemissingto)
- [simplifyPluralSuffix](akashaproject_ui_awf_typings._internal_.InitOptions.md#simplifypluralsuffix)
- [supportedLngs](akashaproject_ui_awf_typings._internal_.InitOptions.md#supportedlngs)
- [updateMissing](akashaproject_ui_awf_typings._internal_.InitOptions.md#updatemissing)
- [whitelist](akashaproject_ui_awf_typings._internal_.InitOptions.md#whitelist)

### Methods

- [missingInterpolationHandler](akashaproject_ui_awf_typings._internal_.InitOptions.md#missinginterpolationhandler)
- [overloadTranslationOptionHandler](akashaproject_ui_awf_typings._internal_.InitOptions.md#overloadtranslationoptionhandler)
- [parseMissingKeyHandler](akashaproject_ui_awf_typings._internal_.InitOptions.md#parsemissingkeyhandler)
- [returnedObjectHandler](akashaproject_ui_awf_typings._internal_.InitOptions.md#returnedobjecthandler)

## Properties

### appendNamespaceToCIMode

• `Optional` **appendNamespaceToCIMode**: `boolean`

Prefixes the namespace to the returned key when using `cimode`

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:481

___

### appendNamespaceToMissingKey

• `Optional` **appendNamespaceToMissingKey**: `boolean`

Appends namespace to missing key

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:372

___

### backend

• `Optional` **backend**: `object`

Options for backend - check documentation of plugin

**`default`** undefined

#### Inherited from

MergeBy.backend

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:205

___

### cache

• `Optional` **cache**: `object`

Options for cache layer - check documentation of plugin

**`default`** undefined

#### Inherited from

MergeBy.cache

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:211

___

### cleanCode

• `Optional` **cleanCode**: `boolean`

Language will be lowercased EN --> en while leaving full locales like en-US

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:300

___

### compatibilityJSON

• `Optional` **compatibilityJSON**: ``"v1"`` \| ``"v2"`` \| ``"v3"``

Compatibility JSON version

**`default`** 'v3'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:487

___

### contextSeparator

• `Optional` **contextSeparator**: `string`

Char to split context from key

**`default`** '_'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:475

___

### debug

• `Optional` **debug**: `boolean`

Logs info level to console output. Helps finding issues with loading not working.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:225

___

### defaultNS

• `Optional` **defaultNS**: `string`

Default namespace used if not passed to translation function

**`default`** 'translation'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:312

___

### detection

• `Optional` **detection**: `object`

Options for language detection - check documentation of plugin

**`default`** undefined

#### Inherited from

MergeBy.detection

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:199

___

### editor

• `Optional` **editor**: `Object`

Options for https://github.com/locize/locize-editor

**`default`** undefined

#### Type declaration

| Name | Type | Description |
| :------ | :------ | :------ |
| `autoOpen?` | `boolean` | If set to false you will need to open the editor via API  **`default`** true |
| `bodyStyle?` | `string` | Styles to adapt layout in iframe mode to your website layout. This will add a style to `<body>`  **`default`** 'margin-right: 605px;' |
| `enableByQS?` | `string` \| ``false`` | Enable by adding querystring locize=true; can be set to another value or turned off by setting to false  **`default`** 'locize' |
| `enabled?` | `boolean` | Enable on init without the need of adding querystring locize=true  **`default`** false |
| `iframeContainerStyle?` | `string` | Styles to adapt layout in iframe mode to your website layout. This will add a style to the `<iframe>`  **`default`** 'z-index: 2000; position: fixed; top: 0; right: 0; bottom: 0; width: 600px; box-shadow: -3px 0 5px 0 rgba(0,0,0,0.5);' |
| `iframeStyle?` | `string` | Styles to adapt layout in iframe mode to your website layout. This will add a style to the parent of `<iframe>`  **`default`** 'height: 100%; width: 600px; border: none;' |
| `lngOverride?` | `string` | Use lng in editor, eg. if running with lng=cimode (i18next, locize)  **`default`** null |
| `lngOverrideQS?` | `string` | Use lng in editor taken from query string, eg. if running with lng=cimode (i18next, locize)  **`default`** 'useLng' |
| `mode?` | ``"iframe"`` \| ``"window"`` | How the editor will open. Setting to window will open a new window/tab instead  **`default`** 'iframe' |
| `toggleKeyCode?` | `number` | Turn on/off by pressing key combination. Combine this with `toggleKeyModifier`  **`default`** 24 (x) |
| `toggleKeyModifier?` | ``"ctrlKey"`` \| ``"metaKey"`` \| ``"altKey"`` \| ``"shiftKey"`` | Turn on/off by pressing key combination. Combine this with `toggleKeyCode`  **`default`** 'ctrlKey' |
| `onEditorSaved?` | (`lng`: ``null``, `ns`: `string` \| readonly `string`[]) => `void` | Handle when locize saved the edited translations, eg. reload website  **`default`** noop |

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:493

___

### fallbackLng

• `Optional` **fallbackLng**: ``false`` \| [`FallbackLng`](../modules/akashaproject_ui_awf_typings._internal_.md#fallbacklng)

Language to use if translations in user language are not available.

**`default`** 'dev'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:249

___

### fallbackNS

• `Optional` **fallbackNS**: `string` \| ``false`` \| readonly `string`[]

String or array of namespaces to lookup key if not found in given namespace.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:318

___

### i18nFormat

• `Optional` **i18nFormat**: `object`

Options for i18n message format - check documentation of plugin

**`default`** undefined

#### Inherited from

MergeBy.i18nFormat

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:217

___

### ignoreJSONStructure

• `Optional` **ignoreJSONStructure**: `boolean`

Automatically lookup for a flat key if a nested key is not found an vice-versa

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:612

___

### initImmediate

• `Optional` **initImmediate**: `boolean`

Triggers resource loading in init function inside a setTimeout (default async behaviour).
Set it to false if your backend loads resources sync - that way calling i18next.t after
init is possible without relaying on the init callback.

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:451

___

### interpolation

• `Optional` **interpolation**: [`InterpolationOptions`](akashaproject_ui_awf_typings._internal_.InterpolationOptions.md)

**`see`** https://www.i18next.com/interpolation.html

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:437

___

### joinArrays

• `Optional` **joinArrays**: `string` \| ``false``

Char, eg. '\n' that arrays will be joined by

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:426

___

### keySeparator

• `Optional` **keySeparator**: `string` \| ``false``

Char to separate keys

**`default`** '.'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:457

___

### lng

• `Optional` **lng**: `string`

Language to use (overrides language detection)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:243

___

### load

• `Optional` **load**: ``"all"`` \| ``"currentOnly"`` \| ``"languageOnly"``

Language codes to lookup, given set language is
'en-US': 'all' --> ['en-US', 'en', 'dev'],
'currentOnly' --> 'en-US',
'languageOnly' --> 'en'

**`default`** 'all'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:282

___

### locizeLastUsed

• `Optional` **locizeLastUsed**: `Object`

Options for https://github.com/locize/locize-lastused

**`default`** undefined

#### Type declaration

| Name | Type | Description |
| :------ | :------ | :------ |
| `allowedHosts?` | readonly `string`[] | Hostnames that are allowed to send last used data. Please keep those to your local system, staging, test servers (not production)  **`default`** ['localhost'] |
| `apiKey?` | `string` | An api key if you want to send missing keys |
| `debounceSubmit?` | `number` | Debounce interval to send data in milliseconds  **`default`** 90000 |
| `projectId` | `string` | The id of your locize project |
| `referenceLng?` | `string` | The reference language of your project  **`default`** 'en' |
| `version?` | `string` | Version  **`default`** 'latest' |

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:571

___

### lowerCaseLng

• `Optional` **lowerCaseLng**: `boolean`

Language will be lowercased eg. en-US --> en-us

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:294

___

### missingKeyHandler

• `Optional` **missingKeyHandler**: ``false`` \| (`lngs`: readonly `string`[], `ns`: `string`, `key`: `string`, `fallbackValue`: `string`, `updateMissing`: `boolean`, `options`: `any`) => `void`

Used for custom missing key handling (needs saveMissing set to true!)

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:351

___

### missingKeyNoValueFallbackToKey

• `Optional` **missingKeyNoValueFallbackToKey**: `boolean`

Used to not fallback to the key as default value, when using saveMissing functionality.
i.e. when using with i18next-http-backend this will result in having a key with an empty string value.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:345

___

### nonExplicitSupportedLngs

• `Optional` **nonExplicitSupportedLngs**: `boolean`

If true will pass eg. en-US if finding en in supportedLngs

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:273

___

### nonExplicitWhitelist

• `Optional` **nonExplicitWhitelist**: `boolean`

DEPRECTADED use nonExplicitSupportedLngs

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:261

___

### ns

• `Optional` **ns**: `string` \| readonly `string`[]

String or array of namespaces to load

**`default`** 'translation'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:306

___

### nsSeparator

• `Optional` **nsSeparator**: `string` \| ``false``

Char to split namespace from key

**`default`** ':'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:463

___

### partialBundledLanguages

• `Optional` **partialBundledLanguages**: `boolean`

Allow initializing with bundled resources while using a backend to load non bundled ones.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:237

___

### pluralSeparator

• `Optional` **pluralSeparator**: `string`

Char to split plural from key

**`default`** '_'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:469

___

### postProcess

• `Optional` **postProcess**: `string` \| ``false`` \| readonly `string`[]

String or array of postProcessors to apply per default

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:390

___

### postProcessPassResolved

• `Optional` **postProcessPassResolved**: `boolean`

passthrough the resolved object including 'usedNS', 'usedLang' etc into options object of postprocessors as 'i18nResolved' property

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:396

___

### preload

• `Optional` **preload**: ``false`` \| readonly `string`[]

Array of languages to preload. Important on server-side to assert translations are loaded before rendering views.

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:288

___

### react

• `Optional` **react**: [`ReactOptions`](akashaproject_ui_awf_typings._internal_.ReactOptions.md)

Options for react - check documentation of plugin

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:443

___

### resources

• `Optional` **resources**: [`Resource`](akashaproject_ui_awf_typings._internal_.Resource.md)

Resources to initialize with (if not using loading or not appending using addResourceBundle)

**`default`** undefined

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:231

___

### returnEmptyString

• `Optional` **returnEmptyString**: `boolean`

Allows empty string as valid translation

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:408

___

### returnNull

• `Optional` **returnNull**: `boolean`

Allows null values as valid translation

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:402

___

### returnObjects

• `Optional` **returnObjects**: `boolean`

Allows objects as valid translation result

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:414

___

### saveMissing

• `Optional` **saveMissing**: `boolean`

Calls save missing key function on backend if key not found

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:324

___

### saveMissingTo

• `Optional` **saveMissingTo**: ``"all"`` \| ``"current"`` \| ``"fallback"``

**`default`** 'fallback'

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:338

___

### simplifyPluralSuffix

• `Optional` **simplifyPluralSuffix**: `boolean`

Will use 'plural' as suffix for languages only having 1 plural form, setting it to false will suffix all with numbers

**`default`** true

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:384

___

### supportedLngs

• `Optional` **supportedLngs**: ``false`` \| readonly `string`[]

Array of allowed languages

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:267

___

### updateMissing

• `Optional` **updateMissing**: `boolean`

Experimental: enable to update default values using the saveMissing
(Works only if defaultValue different from translated value.
Only useful on initial development or when keeping code as source of truth not changing values outside of code.
Only supported if backend supports it already)

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:333

___

### whitelist

• `Optional` **whitelist**: ``false`` \| readonly `string`[]

DEPRECATED use supportedLngs

**`default`** false

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:255

## Methods

### missingInterpolationHandler

▸ `Optional` **missingInterpolationHandler**(`text`, `value`, `options`): `any`

Gets called in case a interpolation value is undefined. This method will not be called if the value is empty string or null

**`default`** noop

#### Parameters

| Name | Type |
| :------ | :------ |
| `text` | `string` |
| `value` | `any` |
| `options` | [`InitOptions`](akashaproject_ui_awf_typings._internal_.InitOptions.md) |

#### Returns

`any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:378

___

### overloadTranslationOptionHandler

▸ `Optional` **overloadTranslationOptionHandler**(`args`): [`TOptions`](../modules/akashaproject_ui_awf_typings._internal_.md#toptions)<[`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap)\>

Sets defaultValue

**`default`** args => ({ defaultValue: args[1] })

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `string`[] |

#### Returns

[`TOptions`](../modules/akashaproject_ui_awf_typings._internal_.md#toptions)<[`StringMap`](../modules/akashaproject_ui_awf_typings._internal_.md#stringmap)\>

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:432

___

### parseMissingKeyHandler

▸ `Optional` **parseMissingKeyHandler**(`key`): `any`

Receives a key that was not found in `t()` and returns a value, that will be returned by `t()`

**`default`** noop

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`any`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:366

___

### returnedObjectHandler

▸ `Optional` **returnedObjectHandler**(`key`, `value`, `options`): `void`

Gets called if object was passed in as key but returnObjects was set to false

**`default`** noop

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `value` | `string` |
| `options` | `any` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/i18next/index.d.ts:420
