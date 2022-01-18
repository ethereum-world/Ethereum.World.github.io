[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / ILoaderConfig

# Interface: ILoaderConfig

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).ILoaderConfig

World configuration object

## Table of contents

### Properties

- [defaultApps](akashaproject_ui_app_loader._internal_.ILoaderConfig.md#defaultapps)
- [defaultWidgets](akashaproject_ui_app_loader._internal_.ILoaderConfig.md#defaultwidgets)
- [homepageApp](akashaproject_ui_app_loader._internal_.ILoaderConfig.md#homepageapp)
- [layout](akashaproject_ui_app_loader._internal_.ILoaderConfig.md#layout)
- [title](akashaproject_ui_app_loader._internal_.ILoaderConfig.md#title)

## Properties

### defaultApps

• **defaultApps**: [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition)[]

Apps that are installed by default on this world.
homePageApp is loaded by default, no need to be specified here

#### Defined in

ui/typings/lib/app-loader.d.ts:174

___

### defaultWidgets

• **defaultWidgets**: [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition)[]

Widgets that are installed by default on this world.
layout widget is loaded by default, no need to be specified here

#### Defined in

ui/typings/lib/app-loader.d.ts:179

___

### homepageApp

• **homepageApp**: [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition)

The app to load when you navigate to the home page.

#### Defined in

ui/typings/lib/app-loader.d.ts:187

___

### layout

• **layout**: [`AppOrWidgetDefinition`](../modules/akashaproject_ui_app_loader._internal_.md#apporwidgetdefinition)

The layout widget of this world. This widget always mounts in the root element.

#### Defined in

ui/typings/lib/app-loader.d.ts:183

___

### title

• **title**: `string`

Define this world's title

#### Defined in

ui/typings/lib/app-loader.d.ts:191
