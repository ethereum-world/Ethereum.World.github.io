[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PerformanceMeasure

# Interface: PerformanceMeasure

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PerformanceMeasure

PerformanceMeasure is an abstract interface for PerformanceEntry objects with an entryType of "measure". Entries of this type are created by calling performance.measure() to add a named DOMHighResTimeStamp (the measure) between two marks to the browser's performance timeline.

## Hierarchy

- [`PerformanceEntry`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentry)

  ↳ **`PerformanceMeasure`**

## Table of contents

### Properties

- [detail](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#detail)
- [duration](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#duration)
- [entryType](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#entrytype)
- [name](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#name)
- [startTime](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#starttime)

### Methods

- [toJSON](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasure.md#tojson)

## Properties

### detail

• `Readonly` **detail**: `any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11180

___

### duration

• `Readonly` **duration**: `number`

#### Inherited from

PerformanceEntry.duration

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11144

___

### entryType

• `Readonly` **entryType**: `string`

#### Inherited from

PerformanceEntry.entryType

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11145

___

### name

• `Readonly` **name**: `string`

#### Inherited from

PerformanceEntry.name

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11146

___

### startTime

• `Readonly` **startTime**: `number`

#### Inherited from

PerformanceEntry.startTime

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11147

## Methods

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Inherited from

PerformanceEntry.toJSON

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11148
