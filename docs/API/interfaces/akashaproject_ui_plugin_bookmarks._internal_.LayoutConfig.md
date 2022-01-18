[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-plugin-bookmarks](../modules/akashaproject_ui_plugin_bookmarks.md) / [<internal\>](../modules/akashaproject_ui_plugin_bookmarks._internal_.md) / LayoutConfig

# Interface: LayoutConfig

[@akashaproject/ui-plugin-bookmarks](../modules/akashaproject_ui_plugin_bookmarks.md).[<internal>](../modules/akashaproject_ui_plugin_bookmarks._internal_.md).LayoutConfig

## Table of contents

### Properties

- [focusedPluginSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#focusedpluginslotid)
- [modalSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#modalslotid)
- [mountsIn](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#mountsin)
- [name](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#name)
- [pluginSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#pluginslotid)
- [rootWidgetSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#rootwidgetslotid)
- [sidebarSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#sidebarslotid)
- [title](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#title)
- [topbarSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#topbarslotid)
- [widgetSlotId](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#widgetslotid)

### Methods

- [loadingFn](akashaproject_ui_plugin_bookmarks._internal_.LayoutConfig.md#loadingfn)

## Properties

### focusedPluginSlotId

• **focusedPluginSlotId**: `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:69

___

### modalSlotId

• **modalSlotId**: `string`

load modals inside this node

#### Defined in

ui/typings/lib/app-loader.d.ts:45

___

### mountsIn

• `Optional` **mountsIn**: `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:41

___

### name

• **name**: `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:46

___

### pluginSlotId

• **pluginSlotId**: `string`

main app and plugin area

#### Defined in

ui/typings/lib/app-loader.d.ts:50

___

### rootWidgetSlotId

• **rootWidgetSlotId**: `string`

load root widgets inside this node
do not use this for app defined widgets

#### Defined in

ui/typings/lib/app-loader.d.ts:55

___

### sidebarSlotId

• **sidebarSlotId**: `string`

#### Defined in

ui/typings/lib/app-loader.d.ts:68

___

### title

• **title**: `string`

sidebar area slot

#### Defined in

ui/typings/lib/app-loader.d.ts:59

___

### topbarSlotId

• **topbarSlotId**: `string`

topbar loading node

#### Defined in

ui/typings/lib/app-loader.d.ts:63

___

### widgetSlotId

• **widgetSlotId**: `string`

load app defined widgets into this node

#### Defined in

ui/typings/lib/app-loader.d.ts:67

## Methods

### loadingFn

▸ **loadingFn**(): `Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_plugin_bookmarks._internal_.ISingleSpaLifecycle.md)\>

#### Returns

`Promise`<[`ISingleSpaLifecycle`](akashaproject_ui_plugin_bookmarks._internal_.ISingleSpaLifecycle.md)\>

#### Defined in

ui/typings/lib/app-loader.d.ts:40
