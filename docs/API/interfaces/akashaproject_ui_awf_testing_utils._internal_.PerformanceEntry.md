[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PerformanceEntry

# Interface: PerformanceEntry

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PerformanceEntry

Encapsulates a single performance metric that is part of the performance timeline. A performance entry can be directly created by making a performance mark or measure (for example by calling the mark() method) at an explicit point in an application. Performance entries are also created in indirect ways such as loading a resource (such as an image).

## Table of contents

### Properties

- [duration](akashaproject_ui_awf_testing_utils._internal_.PerformanceEntry.md#duration)
- [entryType](akashaproject_ui_awf_testing_utils._internal_.PerformanceEntry.md#entrytype)
- [name](akashaproject_ui_awf_testing_utils._internal_.PerformanceEntry.md#name)
- [startTime](akashaproject_ui_awf_testing_utils._internal_.PerformanceEntry.md#starttime)

### Methods

- [toJSON](akashaproject_ui_awf_testing_utils._internal_.PerformanceEntry.md#tojson)

## Properties

### duration

• `Readonly` **duration**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11144

___

### entryType

• `Readonly` **entryType**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11145

___

### name

• `Readonly` **name**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11146

___

### startTime

• `Readonly` **startTime**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11147

## Methods

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11148
