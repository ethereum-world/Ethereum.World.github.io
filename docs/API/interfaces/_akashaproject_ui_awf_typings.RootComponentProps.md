[AWF](../README.md) / [Exports](../modules.md) / [@akashaproject/ui-awf-typings](../modules/_akashaproject_ui_awf_typings.md) / RootComponentProps

# Interface: RootComponentProps

[@akashaproject/ui-awf-typings](../modules/_akashaproject_ui_awf_typings.md).RootComponentProps

## Table of contents

### Properties

- [activeModal](_akashaproject_ui_awf_typings.RootComponentProps.md#activemodal)
- [activeWhen](_akashaproject_ui_awf_typings.RootComponentProps.md#activewhen)
- [domElement](_akashaproject_ui_awf_typings.RootComponentProps.md#domelement)
- [extensionData](_akashaproject_ui_awf_typings.RootComponentProps.md#extensiondata)
- [i18n](_akashaproject_ui_awf_typings.RootComponentProps.md#i18n)
- [isMobile](_akashaproject_ui_awf_typings.RootComponentProps.md#ismobile)
- [layoutConfig](_akashaproject_ui_awf_typings.RootComponentProps.md#layoutconfig)
- [logger](_akashaproject_ui_awf_typings.RootComponentProps.md#logger)
- [name](_akashaproject_ui_awf_typings.RootComponentProps.md#name)
- [singleSpa](_akashaproject_ui_awf_typings.RootComponentProps.md#singlespa)
- [uiEvents](_akashaproject_ui_awf_typings.RootComponentProps.md#uievents)

### Methods

- [getMenuItems](_akashaproject_ui_awf_typings.RootComponentProps.md#getmenuitems)
- [installIntegration](_akashaproject_ui_awf_typings.RootComponentProps.md#installintegration)
- [mountParcel](_akashaproject_ui_awf_typings.RootComponentProps.md#mountparcel)
- [navigateToModal](_akashaproject_ui_awf_typings.RootComponentProps.md#navigatetomodal)
- [uninstallIntegration](_akashaproject_ui_awf_typings.RootComponentProps.md#uninstallintegration)

## Properties

### activeModal

• **activeModal**: `ModalNavigationOptions`

#### Defined in

[ui/typings/src/index.ts:33](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L33)

___

### activeWhen

• `Optional` **activeWhen**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `path` | `string` |

#### Defined in

[ui/typings/src/index.ts:19](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L19)

___

### domElement

• **domElement**: `HTMLElement`

#### Defined in

[ui/typings/src/index.ts:20](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L20)

___

### extensionData

• `Optional` **extensionData**: `EventDataTypes`

#### Defined in

[ui/typings/src/index.ts:34](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L34)

___

### i18n

• `Optional` **i18n**: `i18n`

#### Defined in

[ui/typings/src/index.ts:22](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L22)

___

### isMobile

• **isMobile**: `boolean`

#### Defined in

[ui/typings/src/index.ts:24](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L24)

___

### layoutConfig

• **layoutConfig**: `Omit`<`LayoutConfig`, ``"loadingFn"`` \| ``"mountsIn"`` \| ``"name"`` \| ``"title"``\>

#### Defined in

[ui/typings/src/index.ts:25](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L25)

___

### logger

• **logger**: `ILogger`

#### Defined in

[ui/typings/src/index.ts:26](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L26)

___

### name

• **name**: `string`

#### Defined in

[ui/typings/src/index.ts:28](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L28)

___

### singleSpa

• **singleSpa**: `__module`

#### Defined in

[ui/typings/src/index.ts:29](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L29)

___

### uiEvents

• **uiEvents**: `BehaviorSubject`<`UIEventData`\>

#### Defined in

[ui/typings/src/index.ts:21](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L21)

## Methods

### getMenuItems

▸ `Optional` **getMenuItems**(): `IMenuList`

#### Returns

`IMenuList`

#### Defined in

[ui/typings/src/index.ts:23](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L23)

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

[ui/typings/src/index.ts:30](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L30)

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

[ui/typings/src/index.ts:27](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L27)

___

### navigateToModal

▸ **navigateToModal**(`opts`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | `ModalNavigationOptions` |

#### Returns

`void`

#### Defined in

[ui/typings/src/index.ts:32](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L32)

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

[ui/typings/src/index.ts:31](https://github.com/AKASHAorg/akasha-world-framework/blob/83e542de/ui/typings/src/index.ts#L31)