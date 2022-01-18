[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / LayoutConfig

# Interface: LayoutConfig

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).LayoutConfig

## Table of contents

### Properties

- [focusedPluginSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#focusedpluginslotid)
- [modalSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#modalslotid)
- [mountsIn](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#mountsin)
- [name](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#name)
- [pluginSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#pluginslotid)
- [rootWidgetSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#rootwidgetslotid)
- [sidebarSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#sidebarslotid)
- [title](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#title)
- [topbarSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#topbarslotid)
- [widgetSlotId](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#widgetslotid)

### Methods

- [loadingFn](akashaproject_ui_awf_typings._internal_.LayoutConfig.md#loadingfn)

## Properties

### focusedPluginSlotId

• **focusedPluginSlotId**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:81](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L81)

___

### modalSlotId

• **modalSlotId**: `string`

load modals inside this node

#### Defined in

[ui/typings/src/app-loader.ts:56](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L56)

___

### mountsIn

• `Optional` **mountsIn**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:52](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L52)

___

### name

• **name**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:57](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L57)

___

### pluginSlotId

• **pluginSlotId**: `string`

main app and plugin area

#### Defined in

[ui/typings/src/app-loader.ts:61](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L61)

___

### rootWidgetSlotId

• **rootWidgetSlotId**: `string`

load root widgets inside this node
do not use this for app defined widgets

#### Defined in

[ui/typings/src/app-loader.ts:66](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L66)

___

### sidebarSlotId

• **sidebarSlotId**: `string`

#### Defined in

[ui/typings/src/app-loader.ts:80](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L80)

___

### title

• **title**: `string`

sidebar area slot

#### Defined in

[ui/typings/src/app-loader.ts:71](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L71)

___

### topbarSlotId

• **topbarSlotId**: `string`

topbar loading node

#### Defined in

[ui/typings/src/app-loader.ts:75](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L75)

___

### widgetSlotId

• **widgetSlotId**: `string`

load app defined widgets into this node

#### Defined in

[ui/typings/src/app-loader.ts:79](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L79)

## Methods

### loadingFn

▸ **loadingFn**(): `Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Returns

`Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_awf_typings._internal_.ISingleSpaLifecycle.md)\>

#### Defined in

[ui/typings/src/app-loader.ts:51](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/typings/src/app-loader.ts#L51)
