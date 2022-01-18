[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Performance

# Interface: Performance

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Performance

Provides access to performance-related information for the current page. It's part of the High Resolution Time API, but is enhanced by the Performance Timeline API, the Navigation Timing API, the User Timing API, and the Resource Timing API.

## Hierarchy

- `EventTarget`

  ↳ **`Performance`**

## Table of contents

### Properties

- [navigation](akashaproject_ui_awf_testing_utils._internal_.Performance.md#navigation)
- [onresourcetimingbufferfull](akashaproject_ui_awf_testing_utils._internal_.Performance.md#onresourcetimingbufferfull)
- [timeOrigin](akashaproject_ui_awf_testing_utils._internal_.Performance.md#timeorigin)
- [timing](akashaproject_ui_awf_testing_utils._internal_.Performance.md#timing)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.Performance.md#addeventlistener)
- [clearMarks](akashaproject_ui_awf_testing_utils._internal_.Performance.md#clearmarks)
- [clearMeasures](akashaproject_ui_awf_testing_utils._internal_.Performance.md#clearmeasures)
- [clearResourceTimings](akashaproject_ui_awf_testing_utils._internal_.Performance.md#clearresourcetimings)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.Performance.md#dispatchevent)
- [getEntries](akashaproject_ui_awf_testing_utils._internal_.Performance.md#getentries)
- [getEntriesByName](akashaproject_ui_awf_testing_utils._internal_.Performance.md#getentriesbyname)
- [getEntriesByType](akashaproject_ui_awf_testing_utils._internal_.Performance.md#getentriesbytype)
- [mark](akashaproject_ui_awf_testing_utils._internal_.Performance.md#mark)
- [measure](akashaproject_ui_awf_testing_utils._internal_.Performance.md#measure)
- [now](akashaproject_ui_awf_testing_utils._internal_.Performance.md#now)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.Performance.md#removeeventlistener)
- [setResourceTimingBufferSize](akashaproject_ui_awf_testing_utils._internal_.Performance.md#setresourcetimingbuffersize)
- [toJSON](akashaproject_ui_awf_testing_utils._internal_.Performance.md#tojson)

## Properties

### navigation

• `Readonly` **navigation**: [`PerformanceNavigation`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancenavigation)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11115

___

### onresourcetimingbufferfull

• **onresourcetimingbufferfull**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11116

___

### timeOrigin

• `Readonly` **timeOrigin**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11117

___

### timing

• `Readonly` **timing**: [`PerformanceTiming`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancetiming)

**`deprecated`**

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11119

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"resourcetimingbufferfull"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`PerformanceEventMap`](akashaproject_ui_awf_testing_utils._internal_.PerformanceEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11131

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11132

___

### clearMarks

▸ **clearMarks**(`markName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `markName?` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11120

___

### clearMeasures

▸ **clearMeasures**(`measureName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `measureName?` | `string` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11121

___

### clearResourceTimings

▸ **clearResourceTimings**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11122

___

### dispatchEvent

▸ **dispatchEvent**(`event`): `boolean`

Dispatches a synthetic event event to target and returns true if either event's cancelable attribute value is false or its preventDefault() method was not invoked, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Event` |

#### Returns

`boolean`

#### Inherited from

EventTarget.dispatchEvent

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5210

___

### getEntries

▸ **getEntries**(): [`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Returns

[`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11123

___

### getEntriesByName

▸ **getEntriesByName**(`name`, `type?`): [`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `type?` | `string` |

#### Returns

[`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11124

___

### getEntriesByType

▸ **getEntriesByType**(`type`): [`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |

#### Returns

[`PerformanceEntryList`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performanceentrylist)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11125

___

### mark

▸ **mark**(`markName`, `markOptions?`): [`PerformanceMark`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancemark)

#### Parameters

| Name | Type |
| :------ | :------ |
| `markName` | `string` |
| `markOptions?` | [`PerformanceMarkOptions`](akashaproject_ui_awf_testing_utils._internal_.PerformanceMarkOptions.md) |

#### Returns

[`PerformanceMark`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancemark)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11126

___

### measure

▸ **measure**(`measureName`, `startOrMeasureOptions?`, `endMark?`): [`PerformanceMeasure`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancemeasure)

#### Parameters

| Name | Type |
| :------ | :------ |
| `measureName` | `string` |
| `startOrMeasureOptions?` | `string` \| [`PerformanceMeasureOptions`](akashaproject_ui_awf_testing_utils._internal_.PerformanceMeasureOptions.md) |
| `endMark?` | `string` |

#### Returns

[`PerformanceMeasure`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#performancemeasure)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11127

___

### now

▸ **now**(): `number`

#### Returns

`number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11128

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"resourcetimingbufferfull"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`PerformanceEventMap`](akashaproject_ui_awf_testing_utils._internal_.PerformanceEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11133

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11134

___

### setResourceTimingBufferSize

▸ **setResourceTimingBufferSize**(`maxSize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `maxSize` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11129

___

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:11130
