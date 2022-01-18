[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ScreenOrientation

# Interface: ScreenOrientation

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ScreenOrientation

## Hierarchy

- `EventTarget`

  ↳ **`ScreenOrientation`**

## Table of contents

### Properties

- [angle](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#angle)
- [onchange](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#onchange)
- [type](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#type)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#dispatchevent)
- [lock](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#lock)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#removeeventlistener)
- [unlock](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientation.md#unlock)

## Properties

### angle

• `Readonly` **angle**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13902

___

### onchange

• **onchange**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13903

___

### type

• `Readonly` **type**: [`OrientationType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#orientationtype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13904

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"change"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ScreenOrientationEventMap`](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13907

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

node_modules/typescript/lib/lib.dom.d.ts:13908

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

### lock

▸ **lock**(`orientation`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `orientation` | [`OrientationLockType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#orientationlocktype) |

#### Returns

`Promise`<`void`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13905

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends ``"change"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`ScreenOrientationEventMap`](akashaproject_ui_awf_testing_utils._internal_.ScreenOrientationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13909

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

node_modules/typescript/lib/lib.dom.d.ts:13910

___

### unlock

▸ **unlock**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13906
