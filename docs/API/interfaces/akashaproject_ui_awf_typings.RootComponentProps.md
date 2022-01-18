[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / RootComponentProps

# Interface: RootComponentProps

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).RootComponentProps

## Table of contents

### Properties

- [activeModal](akashaproject_ui_awf_typings.RootComponentProps.md#activemodal)
- [activeWhen](akashaproject_ui_awf_typings.RootComponentProps.md#activewhen)
- [domElement](akashaproject_ui_awf_typings.RootComponentProps.md#domelement)
- [extensionData](akashaproject_ui_awf_typings.RootComponentProps.md#extensiondata)
- [homepageApp](akashaproject_ui_awf_typings.RootComponentProps.md#homepageapp)
- [i18n](akashaproject_ui_awf_typings.RootComponentProps.md#i18n)
- [layoutConfig](akashaproject_ui_awf_typings.RootComponentProps.md#layoutconfig)
- [logger](akashaproject_ui_awf_typings.RootComponentProps.md#logger)
- [name](akashaproject_ui_awf_typings.RootComponentProps.md#name)
- [singleSpa](akashaproject_ui_awf_typings.RootComponentProps.md#singlespa)
- [uiEvents](akashaproject_ui_awf_typings.RootComponentProps.md#uievents)

### Methods

- [getAppRoutes](akashaproject_ui_awf_typings.RootComponentProps.md#getapproutes)
- [getMenuItems](akashaproject_ui_awf_typings.RootComponentProps.md#getmenuitems)
- [installIntegration](akashaproject_ui_awf_typings.RootComponentProps.md#installintegration)
- [mountParcel](akashaproject_ui_awf_typings.RootComponentProps.md#mountparcel)
- [navigateTo](akashaproject_ui_awf_typings.RootComponentProps.md#navigateto)
- [navigateToModal](akashaproject_ui_awf_typings.RootComponentProps.md#navigatetomodal)
- [parseQueryString](akashaproject_ui_awf_typings.RootComponentProps.md#parsequerystring)
- [uninstallIntegration](akashaproject_ui_awf_typings.RootComponentProps.md#uninstallintegration)

## Properties

### activeModal

• **activeModal**: [`ModalNavigationOptions`](akashaproject_ui_awf_typings._internal_.ModalNavigationOptions.md)

#### Defined in

[ui/typings/src/index.ts:59](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L59)

___

### activeWhen

• `Optional` **activeWhen**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `path` | `string` |

#### Defined in

[ui/typings/src/index.ts:46](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L46)

___

### domElement

• **domElement**: `HTMLElement`

#### Defined in

[ui/typings/src/index.ts:47](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L47)

___

### extensionData

• `Optional` **extensionData**: [`EventDataTypes`](../modules/akashaproject_ui_awf_typings._internal_.md#eventdatatypes)

#### Defined in

[ui/typings/src/index.ts:60](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L60)

___

### homepageApp

• `Optional` **homepageApp**: `string`

#### Defined in

[ui/typings/src/index.ts:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L61)

___

### i18n

• `Optional` **i18n**: [`i18n`](akashaproject_ui_awf_typings._internal_.i18n.md)

#### Defined in

[ui/typings/src/index.ts:49](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L49)

___

### layoutConfig

• **layoutConfig**: [`Omit`](../modules/akashaproject_ui_awf_typings._internal_.md#omit)<[`LayoutConfig`](akashaproject_ui_awf_typings._internal_.LayoutConfig.md), ``"loadingFn"`` \| ``"mountsIn"`` \| ``"name"`` \| ``"title"``\>

#### Defined in

[ui/typings/src/index.ts:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L51)

___

### logger

• **logger**: [`ILogger`](akashaproject_ui_awf_typings._internal_.ILogger.md)

#### Defined in

[ui/typings/src/index.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L52)

___

### name

• **name**: `string`

#### Defined in

[ui/typings/src/index.ts:54](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L54)

___

### singleSpa

• **singleSpa**: [`"single-spa"`](../modules/akashaproject_ui_awf_typings._internal_._single_spa_.md)

#### Defined in

[ui/typings/src/index.ts:55](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L55)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<[`UIEventData`](akashaproject_ui_awf_typings._internal_.UIEventData.md)\>

#### Defined in

[ui/typings/src/index.ts:48](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L48)

## Methods

### getAppRoutes

▸ `Optional` **getAppRoutes**(`appId`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `appId` | `string` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `rootRoute` | `string` |

#### Defined in

[ui/typings/src/index.ts:62](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L62)

___

### getMenuItems

▸ `Optional` **getMenuItems**(): [`IMenuList`](akashaproject_ui_awf_typings._internal_.IMenuList.md)

#### Returns

[`IMenuList`](akashaproject_ui_awf_typings._internal_.IMenuList.md)

#### Defined in

[ui/typings/src/index.ts:50](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L50)

___

### installIntegration

▸ `Optional` **installIntegration**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[ui/typings/src/index.ts:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L56)

___

### mountParcel

▸ **mountParcel**(`parcel`, `config?`): `unknown`

#### Parameters

| Name | Type |
| :------ | :------ |
| `parcel` | `unknown` |
| `config?` | `unknown` |

#### Returns

`unknown`

#### Defined in

[ui/typings/src/index.ts:53](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L53)

___

### navigateTo

▸ **navigateTo**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `string` \| [`NavigationOptions`](akashaproject_ui_awf_typings.NavigationOptions.md) \| [`NavigationFn`](../modules/akashaproject_ui_awf_typings.md#navigationfn) |

#### Returns

`void`

#### Defined in

[ui/typings/src/index.ts:63](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L63)

___

### navigateToModal

▸ **navigateToModal**(`opts`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | [`ModalNavigationOptions`](akashaproject_ui_awf_typings._internal_.ModalNavigationOptions.md) |

#### Returns

`void`

#### Defined in

[ui/typings/src/index.ts:58](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L58)

___

### parseQueryString

▸ **parseQueryString**(`queryString`): [`QueryStringType`](akashaproject_ui_awf_typings.QueryStringType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `queryString` | `string` |

#### Returns

[`QueryStringType`](akashaproject_ui_awf_typings.QueryStringType.md)

#### Defined in

[ui/typings/src/index.ts:64](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L64)

___

### uninstallIntegration

▸ `Optional` **uninstallIntegration**(`name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`void`

#### Defined in

[ui/typings/src/index.ts:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/index.ts#L57)
