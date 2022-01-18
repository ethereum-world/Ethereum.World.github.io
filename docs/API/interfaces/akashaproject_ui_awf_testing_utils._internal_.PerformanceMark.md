[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / PerformanceMark

# Interface: PerformanceMark

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).PerformanceMark

PerformanceMark is an abstract interface for PerformanceEntry objects with an entryType of "mark". Entries of this type are created by calling performance.mark() to add a named DOMHighResTimeStamp (the mark) to the browser's performance timeline.

## Hierarchy

- [`PerformanceEntry`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentry)

  ↳ **`PerformanceMark`**

## Table of contents

### Properties

- [detail](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#detail)
- [duration](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#duration)
- [entryType](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#entrytype)
- [name](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#name)
- [startTime](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#starttime)

### Methods

- [toJSON](akashaproject_ui_awf_testing_utils._internal_.PerformanceMark.md#tojson)

## Properties

### detail

• `Readonly` **detail**: `any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11170

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
