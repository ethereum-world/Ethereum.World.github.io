[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Navigator

# Interface: Navigator

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Navigator

The state and the identity of the user agent. It allows scripts to query it and to register themselves to carry on some activities.

## Hierarchy

- [`NavigatorAutomationInformation`](akashaproject_ui_awf_testing_utils._internal_.NavigatorAutomationInformation.md)

- [`NavigatorConcurrentHardware`](akashaproject_ui_awf_testing_utils._internal_.NavigatorConcurrentHardware.md)

- [`NavigatorContentUtils`](akashaproject_ui_awf_testing_utils._internal_.NavigatorContentUtils.md)

- [`NavigatorCookies`](akashaproject_ui_awf_testing_utils._internal_.NavigatorCookies.md)

- [`NavigatorID`](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md)

- [`NavigatorLanguage`](akashaproject_ui_awf_testing_utils._internal_.NavigatorLanguage.md)

- [`NavigatorNetworkInformation`](akashaproject_ui_awf_testing_utils._internal_.NavigatorNetworkInformation.md)

- [`NavigatorOnLine`](akashaproject_ui_awf_testing_utils._internal_.NavigatorOnLine.md)

- [`NavigatorPlugins`](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md)

- [`NavigatorStorage`](akashaproject_ui_awf_testing_utils._internal_.NavigatorStorage.md)

  ↳ **`Navigator`**

## Table of contents

### Properties

- [appCodeName](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#appcodename)
- [appName](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#appname)
- [appVersion](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#appversion)
- [clipboard](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#clipboard)
- [connection](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#connection)
- [cookieEnabled](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#cookieenabled)
- [credentials](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#credentials)
- [doNotTrack](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#donottrack)
- [geolocation](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#geolocation)
- [hardwareConcurrency](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#hardwareconcurrency)
- [language](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#language)
- [languages](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#languages)
- [maxTouchPoints](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#maxtouchpoints)
- [mediaCapabilities](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#mediacapabilities)
- [mediaDevices](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#mediadevices)
- [mediaSession](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#mediasession)
- [mimeTypes](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#mimetypes)
- [onLine](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#online)
- [permissions](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#permissions)
- [platform](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#platform)
- [plugins](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#plugins)
- [pointerEnabled](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#pointerenabled)
- [product](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#product)
- [productSub](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#productsub)
- [serviceWorker](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#serviceworker)
- [storage](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#storage)
- [userAgent](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#useragent)
- [vendor](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#vendor)
- [vendorSub](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#vendorsub)
- [webdriver](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#webdriver)

### Methods

- [getGamepads](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#getgamepads)
- [javaEnabled](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#javaenabled)
- [registerProtocolHandler](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#registerprotocolhandler)
- [requestMediaKeySystemAccess](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#requestmediakeysystemaccess)
- [sendBeacon](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#sendbeacon)
- [share](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#share)
- [vibrate](akashaproject_ui_awf_testing_utils._internal_.Navigator.md#vibrate)

## Properties

### appCodeName

• `Readonly` **appCodeName**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[appCodeName](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#appcodename)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10438

___

### appName

• `Readonly` **appName**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[appName](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#appname)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10440

___

### appVersion

• `Readonly` **appVersion**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[appVersion](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#appversion)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10442

___

### clipboard

• `Readonly` **clipboard**: [`Clipboard`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#clipboard)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10397

___

### connection

• `Readonly` **connection**: [`NetworkInformation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#networkinformation)

#### Inherited from

[NavigatorNetworkInformation](akashaproject_ui_awf_testing_utils._internal_.NavigatorNetworkInformation.md).[connection](akashaproject_ui_awf_testing_utils._internal_.NavigatorNetworkInformation.md#connection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10461

___

### cookieEnabled

• `Readonly` **cookieEnabled**: `boolean`

#### Inherited from

[NavigatorCookies](akashaproject_ui_awf_testing_utils._internal_.NavigatorCookies.md).[cookieEnabled](akashaproject_ui_awf_testing_utils._internal_.NavigatorCookies.md#cookieenabled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10433

___

### credentials

• `Readonly` **credentials**: [`CredentialsContainer`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#credentialscontainer)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10398

___

### doNotTrack

• `Readonly` **doNotTrack**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10399

___

### geolocation

• `Readonly` **geolocation**: [`Geolocation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#geolocation)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10400

___

### hardwareConcurrency

• `Readonly` **hardwareConcurrency**: `number`

#### Inherited from

[NavigatorConcurrentHardware](akashaproject_ui_awf_testing_utils._internal_.NavigatorConcurrentHardware.md).[hardwareConcurrency](akashaproject_ui_awf_testing_utils._internal_.NavigatorConcurrentHardware.md#hardwareconcurrency)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10425

___

### language

• `Readonly` **language**: `string`

#### Inherited from

[NavigatorLanguage](akashaproject_ui_awf_testing_utils._internal_.NavigatorLanguage.md).[language](akashaproject_ui_awf_testing_utils._internal_.NavigatorLanguage.md#language)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10456

___

### languages

• `Readonly` **languages**: readonly `string`[]

#### Inherited from

[NavigatorLanguage](akashaproject_ui_awf_testing_utils._internal_.NavigatorLanguage.md).[languages](akashaproject_ui_awf_testing_utils._internal_.NavigatorLanguage.md#languages)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10457

___

### maxTouchPoints

• `Readonly` **maxTouchPoints**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10401

___

### mediaCapabilities

• `Readonly` **mediaCapabilities**: [`MediaCapabilities`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediacapabilities)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10402

___

### mediaDevices

• `Readonly` **mediaDevices**: [`MediaDevices`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediadevices)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10403

___

### mediaSession

• `Readonly` **mediaSession**: [`MediaSession`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediasession)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10404

___

### mimeTypes

• `Readonly` **mimeTypes**: [`MimeTypeArray`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mimetypearray)

**`deprecated`**

#### Inherited from

[NavigatorPlugins](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md).[mimeTypes](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md#mimetypes)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10470

___

### onLine

• `Readonly` **onLine**: `boolean`

#### Inherited from

[NavigatorOnLine](akashaproject_ui_awf_testing_utils._internal_.NavigatorOnLine.md).[onLine](akashaproject_ui_awf_testing_utils._internal_.NavigatorOnLine.md#online)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10465

___

### permissions

• `Readonly` **permissions**: [`Permissions`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#permissions)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10405

___

### platform

• `Readonly` **platform**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[platform](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#platform)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10444

___

### plugins

• `Readonly` **plugins**: [`PluginArray`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#pluginarray)

**`deprecated`**

#### Inherited from

[NavigatorPlugins](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md).[plugins](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md#plugins)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10472

___

### pointerEnabled

• `Readonly` **pointerEnabled**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10406

___

### product

• `Readonly` **product**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[product](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#product)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10446

___

### productSub

• `Readonly` **productSub**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[productSub](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#productsub)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10448

___

### serviceWorker

• `Readonly` **serviceWorker**: [`ServiceWorkerContainer`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#serviceworkercontainer)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10407

___

### storage

• `Readonly` **storage**: [`StorageManager`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#storagemanager)

#### Inherited from

[NavigatorStorage](akashaproject_ui_awf_testing_utils._internal_.NavigatorStorage.md).[storage](akashaproject_ui_awf_testing_utils._internal_.NavigatorStorage.md#storage)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10478

___

### userAgent

• `Readonly` **userAgent**: `string`

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[userAgent](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#useragent)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10449

___

### vendor

• `Readonly` **vendor**: `string`

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[vendor](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#vendor)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10450

___

### vendorSub

• `Readonly` **vendorSub**: `string`

**`deprecated`**

#### Inherited from

[NavigatorID](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md).[vendorSub](akashaproject_ui_awf_testing_utils._internal_.NavigatorID.md#vendorsub)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10452

___

### webdriver

• `Readonly` **webdriver**: `boolean`

#### Inherited from

[NavigatorAutomationInformation](akashaproject_ui_awf_testing_utils._internal_.NavigatorAutomationInformation.md).[webdriver](akashaproject_ui_awf_testing_utils._internal_.NavigatorAutomationInformation.md#webdriver)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10421

## Methods

### getGamepads

▸ **getGamepads**(): [`Gamepad`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#gamepad)[]

#### Returns

[`Gamepad`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#gamepad)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10408

___

### javaEnabled

▸ **javaEnabled**(): `boolean`

**`deprecated`**

#### Returns

`boolean`

#### Inherited from

[NavigatorPlugins](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md).[javaEnabled](akashaproject_ui_awf_testing_utils._internal_.NavigatorPlugins.md#javaenabled)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10474

___

### registerProtocolHandler

▸ **registerProtocolHandler**(`scheme`, `url`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `scheme` | `string` |
| `url` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |

#### Returns

`void`

#### Inherited from

[NavigatorContentUtils](akashaproject_ui_awf_testing_utils._internal_.NavigatorContentUtils.md).[registerProtocolHandler](akashaproject_ui_awf_testing_utils._internal_.NavigatorContentUtils.md#registerprotocolhandler)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10429

___

### requestMediaKeySystemAccess

▸ **requestMediaKeySystemAccess**(`keySystem`, `supportedConfigurations`): `Promise`<[`MediaKeySystemAccess`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysystemaccess)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `keySystem` | `string` |
| `supportedConfigurations` | [`MediaKeySystemConfiguration`](akashaproject_ui_awf_testing_utils._internal_.MediaKeySystemConfiguration.md)[] |

#### Returns

`Promise`<[`MediaKeySystemAccess`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediakeysystemaccess)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10409

___

### sendBeacon

▸ **sendBeacon**(`url`, `data?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |
| `data?` | [`BodyInit`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#bodyinit) |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10410

___

### share

▸ **share**(`data?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ShareData`](akashaproject_ui_awf_testing_utils._internal_.ShareData.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10411

___

### vibrate

▸ **vibrate**(`pattern`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pattern` | [`VibratePattern`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#vibratepattern) |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10412
