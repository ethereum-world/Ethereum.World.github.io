[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](akashaproject_ui_awf_typings.md) / [<internal\>](akashaproject_ui_awf_typings._internal_.md) / "single-spa"

# Namespace: "single-spa"

[@akashaproject/ui-awf-typings](akashaproject_ui_awf_typings.md).[<internal>](akashaproject_ui_awf_typings._internal_.md)."single-spa"

## Table of contents

### Interfaces

- [CustomProps](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md)
- [SingleSpaAppsByNewStatus](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.SingleSpaAppsByNewStatus.md)
- [SingleSpaNewAppStatus](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.SingleSpaNewAppStatus.md)

### Type aliases

- [Activity](akashaproject_ui_awf_typings._internal_._single_spa_.md#activity)
- [ActivityFn](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn)
- [AppError](akashaproject_ui_awf_typings._internal_._single_spa_.md#apperror)
- [AppProps](akashaproject_ui_awf_typings._internal_._single_spa_.md#appprops)
- [Application](akashaproject_ui_awf_typings._internal_._single_spa_.md#application)
- [CustomPropsFn](akashaproject_ui_awf_typings._internal_._single_spa_.md#custompropsfn)
- [LifeCycleFn](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)
- [LifeCycles](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecycles)
- [Parcel](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcel)
- [ParcelConfig](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfig)
- [ParcelConfigObject](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfigobject)
- [ParcelProps](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelprops)
- [RegisterApplicationConfig](akashaproject_ui_awf_typings._internal_._single_spa_.md#registerapplicationconfig)
- [SingleSpaCustomEventDetail](akashaproject_ui_awf_typings._internal_._single_spa_.md#singlespacustomeventdetail)
- [StartOpts](akashaproject_ui_awf_typings._internal_._single_spa_.md#startopts)

### Variables

- [BOOTSTRAPPING](akashaproject_ui_awf_typings._internal_._single_spa_.md#bootstrapping)
- [LOADING\_SOURCE\_CODE](akashaproject_ui_awf_typings._internal_._single_spa_.md#loading_source_code)
- [LOAD\_ERROR](akashaproject_ui_awf_typings._internal_._single_spa_.md#load_error)
- [MOUNTED](akashaproject_ui_awf_typings._internal_._single_spa_.md#mounted)
- [MOUNTING](akashaproject_ui_awf_typings._internal_._single_spa_.md#mounting)
- [NOT\_BOOTSTRAPPED](akashaproject_ui_awf_typings._internal_._single_spa_.md#not_bootstrapped)
- [NOT\_LOADED](akashaproject_ui_awf_typings._internal_._single_spa_.md#not_loaded)
- [NOT\_MOUNTED](akashaproject_ui_awf_typings._internal_._single_spa_.md#not_mounted)
- [SKIP\_BECAUSE\_BROKEN](akashaproject_ui_awf_typings._internal_._single_spa_.md#skip_because_broken)
- [UNLOADING](akashaproject_ui_awf_typings._internal_._single_spa_.md#unloading)
- [UNMOUNTING](akashaproject_ui_awf_typings._internal_._single_spa_.md#unmounting)
- [UPDATING](akashaproject_ui_awf_typings._internal_._single_spa_.md#updating)

### Functions

- [addErrorHandler](akashaproject_ui_awf_typings._internal_._single_spa_.md#adderrorhandler)
- [checkActivityFunctions](akashaproject_ui_awf_typings._internal_._single_spa_.md#checkactivityfunctions)
- [ensureJQuerySupport](akashaproject_ui_awf_typings._internal_._single_spa_.md#ensurejquerysupport)
- [getAppNames](akashaproject_ui_awf_typings._internal_._single_spa_.md#getappnames)
- [getAppStatus](akashaproject_ui_awf_typings._internal_._single_spa_.md#getappstatus)
- [getMountedApps](akashaproject_ui_awf_typings._internal_._single_spa_.md#getmountedapps)
- [mountRootParcel](akashaproject_ui_awf_typings._internal_._single_spa_.md#mountrootparcel)
- [navigateToUrl](akashaproject_ui_awf_typings._internal_._single_spa_.md#navigatetourl)
- [pathToActiveWhen](akashaproject_ui_awf_typings._internal_._single_spa_.md#pathtoactivewhen)
- [registerApplication](akashaproject_ui_awf_typings._internal_._single_spa_.md#registerapplication)
- [removeErrorHandler](akashaproject_ui_awf_typings._internal_._single_spa_.md#removeerrorhandler)
- [setBootstrapMaxTime](akashaproject_ui_awf_typings._internal_._single_spa_.md#setbootstrapmaxtime)
- [setMountMaxTime](akashaproject_ui_awf_typings._internal_._single_spa_.md#setmountmaxtime)
- [setUnloadMaxTime](akashaproject_ui_awf_typings._internal_._single_spa_.md#setunloadmaxtime)
- [setUnmountMaxTime](akashaproject_ui_awf_typings._internal_._single_spa_.md#setunmountmaxtime)
- [start](akashaproject_ui_awf_typings._internal_._single_spa_.md#start)
- [triggerAppChange](akashaproject_ui_awf_typings._internal_._single_spa_.md#triggerappchange)
- [unloadApplication](akashaproject_ui_awf_typings._internal_._single_spa_.md#unloadapplication)
- [unregisterApplication](akashaproject_ui_awf_typings._internal_._single_spa_.md#unregisterapplication)

## Type aliases

### Activity

Ƭ **Activity**: [`ActivityFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn) \| `string` \| ([`ActivityFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn) \| `string`)[]

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:88

___

### ActivityFn

Ƭ **ActivityFn**: (`location`: [`Location`](akashaproject_ui_awf_typings._internal_.md#location)) => `boolean`

#### Type declaration

▸ (`location`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](akashaproject_ui_awf_typings._internal_.md#location) |

##### Returns

`boolean`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:86

___

### AppError

Ƭ **AppError**: [`Error`](akashaproject_ui_awf_typings._internal_.md#error) & { `appOrParcelName`: `string`  }

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:179

___

### AppProps

Ƭ **AppProps**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `singleSpa` | `any` |
| `mountParcel` | (`parcelConfig`: [`ParcelConfig`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfig)<[`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md)\>, `customProps`: [`ParcelProps`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelprops) & [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md)) => [`Parcel`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcel)<[`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md)\> |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:12

___

### Application

Ƭ **Application**<`ExtraProps`\>: [`LifeCycles`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecycles)<`ExtraProps`\> \| (`config`: `ExtraProps` & [`AppProps`](akashaproject_ui_awf_typings._internal_._single_spa_.md#appprops)) => `Promise`<[`LifeCycles`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecycles)<`ExtraProps`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | {} |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:82

___

### CustomPropsFn

Ƭ **CustomPropsFn**<`ExtraProps`\>: (`name`: `string`, `location`: [`Location`](akashaproject_ui_awf_typings._internal_.md#location)) => `ExtraProps`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | extends [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) = [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) |

#### Type declaration

▸ (`name`, `location`): `ExtraProps`

##### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `location` | [`Location`](akashaproject_ui_awf_typings._internal_.md#location) |

##### Returns

`ExtraProps`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:7

___

### LifeCycleFn

Ƭ **LifeCycleFn**<`ExtraProps`\>: (`config`: `ExtraProps` & [`AppProps`](akashaproject_ui_awf_typings._internal_._single_spa_.md#appprops)) => `Promise`<`any`\>

#### Type parameters

| Name |
| :------ |
| `ExtraProps` |

#### Type declaration

▸ (`config`): `Promise`<`any`\>

##### Parameters

| Name | Type |
| :------ | :------ |
| `config` | `ExtraProps` & [`AppProps`](akashaproject_ui_awf_typings._internal_._single_spa_.md#appprops) |

##### Returns

`Promise`<`any`\>

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:53

___

### LifeCycles

Ƭ **LifeCycles**<`ExtraProps`\>: `Object`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | {} |

#### Type declaration

| Name | Type |
| :------ | :------ |
| `bootstrap` | [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\> \| [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\>[] |
| `mount` | [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\> \| [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\>[] |
| `unmount` | [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\> \| [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\>[] |
| `update?` | [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\> \| [`LifeCycleFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecyclefn)<`ExtraProps`\>[] |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:56

___

### Parcel

Ƭ **Parcel**<`ExtraProps`\>: `Object`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) |

#### Type declaration

| Name | Type |
| :------ | :------ |
| `bootstrapPromise` | `Promise`<``null``\> |
| `loadPromise` | `Promise`<``null``\> |
| `mountPromise` | `Promise`<``null``\> |
| `unmountPromise` | `Promise`<``null``\> |
| `getStatus` | () => ``"NOT_LOADED"`` \| ``"LOADING_SOURCE_CODE"`` \| ``"NOT_BOOTSTRAPPED"`` \| ``"BOOTSTRAPPING"`` \| ``"NOT_MOUNTED"`` \| ``"MOUNTING"`` \| ``"MOUNTED"`` \| ``"UPDATING"`` \| ``"UNMOUNTING"`` \| ``"UNLOADING"`` \| ``"SKIP_BECAUSE_BROKEN"`` \| ``"LOAD_ERROR"`` |
| `mount` | () => `Promise`<``null``\> |
| `unmount` | () => `Promise`<``null``\> |
| `update?` | (`customProps`: `ExtraProps`) => `Promise`<`any`\> |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:30

___

### ParcelConfig

Ƭ **ParcelConfig**<`ExtraProps`\>: [`ParcelConfigObject`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfigobject)<`ExtraProps`\> \| () => `Promise`<[`ParcelConfigObject`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfigobject)<`ExtraProps`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:21

___

### ParcelConfigObject

Ƭ **ParcelConfigObject**<`ExtraProps`\>: { `name?`: `string`  } & [`LifeCycles`](akashaproject_ui_awf_typings._internal_._single_spa_.md#lifecycles)<`ExtraProps`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:26

___

### ParcelProps

Ƭ **ParcelProps**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `domElement` | `HTMLElement` |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:25

___

### RegisterApplicationConfig

Ƭ **RegisterApplicationConfig**<`ExtraProps`\>: `Object`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | extends [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) = {} |

#### Type declaration

| Name | Type |
| :------ | :------ |
| `activeWhen` | [`Activity`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activity) |
| `app` | [`Application`](akashaproject_ui_awf_typings._internal_._single_spa_.md#application)<`ExtraProps`\> |
| `customProps?` | `ExtraProps` \| [`CustomPropsFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#custompropsfn)<`ExtraProps`\> |
| `name` | `string` |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:90

___

### SingleSpaCustomEventDetail

Ƭ **SingleSpaCustomEventDetail**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `appsByNewStatus` | [`SingleSpaAppsByNewStatus`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.SingleSpaAppsByNewStatus.md) |
| `navigationIsCanceled` | `boolean` |
| `newAppStatuses` | [`SingleSpaNewAppStatus`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.SingleSpaNewAppStatus.md) |
| `newUrl` | `string` |
| `oldUrl` | `string` |
| `originalEvent?` | `Event` |
| `totalAppChanges` | `number` |
| `cancelNavigation?` | () => `void` |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:110

___

### StartOpts

Ƭ **StartOpts**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `urlRerouteOnly?` | `boolean` |

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:63

## Variables

### BOOTSTRAPPING

• **BOOTSTRAPPING**: ``"BOOTSTRAPPING"``

___

### LOADING\_SOURCE\_CODE

• **LOADING\_SOURCE\_CODE**: ``"LOADING_SOURCE_CODE"``

___

### LOAD\_ERROR

• **LOAD\_ERROR**: ``"LOAD_ERROR"``

___

### MOUNTED

• **MOUNTED**: ``"MOUNTED"``

___

### MOUNTING

• **MOUNTING**: ``"MOUNTING"``

___

### NOT\_BOOTSTRAPPED

• **NOT\_BOOTSTRAPPED**: ``"NOT_BOOTSTRAPPED"``

___

### NOT\_LOADED

• **NOT\_LOADED**: ``"NOT_LOADED"``

___

### NOT\_MOUNTED

• **NOT\_MOUNTED**: ``"NOT_MOUNTED"``

___

### SKIP\_BECAUSE\_BROKEN

• **SKIP\_BECAUSE\_BROKEN**: ``"SKIP_BECAUSE_BROKEN"``

___

### UNLOADING

• **UNLOADING**: ``"UNLOADING"``

___

### UNMOUNTING

• **UNMOUNTING**: ``"UNMOUNTING"``

___

### UPDATING

• **UPDATING**: ``"UPDATING"``

## Functions

### addErrorHandler

▸ **addErrorHandler**(`handler`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | (`error`: [`AppError`](akashaproject_ui_awf_typings._internal_._single_spa_.md#apperror)) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:182

___

### checkActivityFunctions

▸ **checkActivityFunctions**(`location`): `string`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `location` | [`Location`](akashaproject_ui_awf_typings._internal_.md#location) |

#### Returns

`string`[]

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:159

___

### ensureJQuerySupport

▸ **ensureJQuerySupport**(`jQuery?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `jQuery?` | `any` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:71

___

### getAppNames

▸ **getAppNames**(): `string`[]

#### Returns

`string`[]

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:160

___

### getAppStatus

▸ **getAppStatus**(`appName`): `string` \| ``null``

#### Parameters

| Name | Type |
| :------ | :------ |
| `appName` | `string` |

#### Returns

`string` \| ``null``

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:152

___

### getMountedApps

▸ **getMountedApps**(): `string`[]

#### Returns

`string`[]

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:135

___

### mountRootParcel

▸ **mountRootParcel**<`ExtraProps`\>(`parcelConfig`, `parcelProps`): [`Parcel`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcel)<`ExtraProps`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `parcelConfig` | [`ParcelConfig`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelconfig)<`ExtraProps`\> |
| `parcelProps` | [`ParcelProps`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcelprops) & `ExtraProps` |

#### Returns

[`Parcel`](akashaproject_ui_awf_typings._internal_._single_spa_.md#parcel)<`ExtraProps`\>

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:186

___

### navigateToUrl

▸ **navigateToUrl**(`obj`, `opts?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `string` \| { `currentTarget`: { `href`: `string`  } ; `preventDefault`: `any`  } |
| `opts?` | [`Object`](akashaproject_ui_awf_typings._internal_.md#object) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:163

___

### pathToActiveWhen

▸ **pathToActiveWhen**(`path`, `exactMatch?`): [`ActivityFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn)

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |
| `exactMatch?` | `boolean` |

#### Returns

[`ActivityFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn)

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:191

___

### registerApplication

▸ **registerApplication**<`ExtraProps`\>(`appName`, `applicationOrLoadingFn`, `activityFn`, `customProps?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | extends [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) = {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `appName` | `string` |
| `applicationOrLoadingFn` | [`Application`](akashaproject_ui_awf_typings._internal_._single_spa_.md#application)<`ExtraProps`\> |
| `activityFn` | [`ActivityFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#activityfn) |
| `customProps?` | `ExtraProps` \| [`CustomPropsFn`](akashaproject_ui_awf_typings._internal_._single_spa_.md#custompropsfn)<`ExtraProps`\> |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:122

▸ **registerApplication**<`ExtraProps`\>(`config`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `ExtraProps` | extends [`CustomProps`](../interfaces/akashaproject_ui_awf_typings._internal_._single_spa_.CustomProps.md) = {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`RegisterApplicationConfig`](akashaproject_ui_awf_typings._internal_._single_spa_.md#registerapplicationconfig)<`ExtraProps`\> |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:129

___

### removeErrorHandler

▸ **removeErrorHandler**(`handler`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `handler` | (`error`: [`AppError`](akashaproject_ui_awf_typings._internal_._single_spa_.md#apperror)) => `void` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:183

___

### setBootstrapMaxTime

▸ **setBootstrapMaxTime**(`time`, `dieOnTimeout?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `time` | `number` |
| `dieOnTimeout?` | `boolean` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:74

___

### setMountMaxTime

▸ **setMountMaxTime**(`time`, `dieOnTimeout?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `time` | `number` |
| `dieOnTimeout?` | `boolean` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:78

___

### setUnloadMaxTime

▸ **setUnloadMaxTime**(`time`, `dieOnTimeout?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `time` | `number` |
| `dieOnTimeout?` | `boolean` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:80

___

### setUnmountMaxTime

▸ **setUnmountMaxTime**(`time`, `dieOnTimeout?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `time` | `number` |
| `dieOnTimeout?` | `boolean` |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:79

___

### start

▸ **start**(`opts?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts?` | [`StartOpts`](akashaproject_ui_awf_typings._internal_._single_spa_.md#startopts) |

#### Returns

`void`

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:68

___

### triggerAppChange

▸ **triggerAppChange**(): `Promise`<`any`\>

#### Returns

`Promise`<`any`\>

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:176

___

### unloadApplication

▸ **unloadApplication**(`appName`, `opts?`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `appName` | `string` |
| `opts?` | `Object` |
| `opts.waitForUnmount` | `boolean` |

#### Returns

`Promise`<`any`\>

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:154

___

### unregisterApplication

▸ **unregisterApplication**(`appName`): `Promise`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `appName` | `string` |

#### Returns

`Promise`<`any`\>

#### Defined in

ui/typings/node_modules/single-spa/typings/single-spa.d.ts:133
