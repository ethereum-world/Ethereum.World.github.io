[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IFilterCard

# Interface: IFilterCard

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IFilterCard

## Hierarchy

- [`IFilterBox`](akashaproject_design_system._internal_.IFilterBox.md)

  ↳ **`IFilterCard`**

## Table of contents

### Properties

- [allLabel](akashaproject_design_system._internal_.IFilterCard.md#alllabel)
- [className](akashaproject_design_system._internal_.IFilterCard.md#classname)
- [closeLabel](akashaproject_design_system._internal_.IFilterCard.md#closelabel)
- [currentlySeeingLabel](akashaproject_design_system._internal_.IFilterCard.md#currentlyseeinglabel)
- [filtersLabel](akashaproject_design_system._internal_.IFilterCard.md#filterslabel)
- [followingLabel](akashaproject_design_system._internal_.IFilterCard.md#followinglabel)
- [latestLabel](akashaproject_design_system._internal_.IFilterCard.md#latestlabel)
- [oldestLabel](akashaproject_design_system._internal_.IFilterCard.md#oldestlabel)
- [rootNodeRef](akashaproject_design_system._internal_.IFilterCard.md#rootnoderef)
- [sortByLabel](akashaproject_design_system._internal_.IFilterCard.md#sortbylabel)
- [style](akashaproject_design_system._internal_.IFilterCard.md#style)
- [titleElement](akashaproject_design_system._internal_.IFilterCard.md#titleelement)

### Methods

- [handleClickAll](akashaproject_design_system._internal_.IFilterCard.md#handleclickall)
- [handleClickFollowing](akashaproject_design_system._internal_.IFilterCard.md#handleclickfollowing)
- [handleClickLatest](akashaproject_design_system._internal_.IFilterCard.md#handleclicklatest)
- [handleClickOldest](akashaproject_design_system._internal_.IFilterCard.md#handleclickoldest)

## Properties

### allLabel

• `Optional` **allLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[allLabel](akashaproject_design_system._internal_.IFilterBox.md#alllabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L13)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L12)

___

### closeLabel

• `Optional` **closeLabel**: `string`

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:9](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L9)

___

### currentlySeeingLabel

• `Optional` **currentlySeeingLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[currentlySeeingLabel](akashaproject_design_system._internal_.IFilterBox.md#currentlyseeinglabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:11](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L11)

___

### filtersLabel

• `Optional` **filtersLabel**: `string`

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:8](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L8)

___

### followingLabel

• `Optional` **followingLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[followingLabel](akashaproject_design_system._internal_.IFilterBox.md#followinglabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L14)

___

### latestLabel

• `Optional` **latestLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[latestLabel](akashaproject_design_system._internal_.IFilterBox.md#latestlabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:15](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L15)

___

### oldestLabel

• `Optional` **oldestLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[oldestLabel](akashaproject_design_system._internal_.IFilterBox.md#oldestlabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:16](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L16)

___

### rootNodeRef

• `Optional` **rootNodeRef**: [`Ref`](../modules/akashaproject_design_system._internal_.md#ref)<`HTMLDivElement`\>

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:14](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L14)

___

### sortByLabel

• `Optional` **sortByLabel**: `string`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[sortByLabel](akashaproject_design_system._internal_.IFilterBox.md#sortbylabel)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L12)

___

### style

• `Optional` **style**: [`CSSProperties`](akashaproject_design_system._internal_.CSSProperties.md)

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:13](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L13)

___

### titleElement

• **titleElement**: [`ReactElement`](akashaproject_design_system._internal_.ReactElement.md)<`any`, `string` \| [`JSXElementConstructor`](../modules/akashaproject_design_system._internal_.md#jsxelementconstructor)<`any`\>\>

#### Defined in

[ui/design/src/components/FilterCard/index.tsx:10](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/index.tsx#L10)

## Methods

### handleClickAll

▸ **handleClickAll**(): `void`

#### Returns

`void`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[handleClickAll](akashaproject_design_system._internal_.IFilterBox.md#handleclickall)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:17](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L17)

___

### handleClickFollowing

▸ **handleClickFollowing**(): `void`

#### Returns

`void`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[handleClickFollowing](akashaproject_design_system._internal_.IFilterBox.md#handleclickfollowing)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:18](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L18)

___

### handleClickLatest

▸ **handleClickLatest**(): `void`

#### Returns

`void`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[handleClickLatest](akashaproject_design_system._internal_.IFilterBox.md#handleclicklatest)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:19](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L19)

___

### handleClickOldest

▸ **handleClickOldest**(): `void`

#### Returns

`void`

#### Inherited from

[IFilterBox](akashaproject_design_system._internal_.IFilterBox.md).[handleClickOldest](akashaproject_design_system._internal_.IFilterBox.md#handleclickoldest)

#### Defined in

[ui/design/src/components/FilterCard/filter-box.tsx:20](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/FilterCard/filter-box.tsx#L20)
