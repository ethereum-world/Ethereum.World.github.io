[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / VisualViewport

# Interface: VisualViewport

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).VisualViewport

## Hierarchy

- `EventTarget`

  ↳ **`VisualViewport`**

## Table of contents

### Properties

- [height](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#height)
- [offsetLeft](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#offsetleft)
- [offsetTop](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#offsettop)
- [onresize](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#onresize)
- [onscroll](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#onscroll)
- [pageLeft](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#pageleft)
- [pageTop](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#pagetop)
- [scale](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#scale)
- [width](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#width)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#addeventlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.VisualViewport.md#removeeventlistener)

## Properties

### height

• `Readonly` **height**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15064

___

### offsetLeft

• `Readonly` **offsetLeft**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15065

___

### offsetTop

• `Readonly` **offsetTop**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15066

___

### onresize

• **onresize**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15067

___

### onscroll

• **onscroll**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15068

___

### pageLeft

• `Readonly` **pageLeft**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15069

___

### pageTop

• `Readonly` **pageTop**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15070

___

### scale

• `Readonly` **scale**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15071

___

### width

• `Readonly` **width**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15072

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`VisualViewportEventMap`](akashaproject_ui_awf_testing_utils._internal_.VisualViewportEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`VisualViewportEventMap`](akashaproject_ui_awf_testing_utils._internal_.VisualViewportEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15073

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

node_modules/typescript/lib/lib.dom.d.ts:15074

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

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`VisualViewportEventMap`](akashaproject_ui_awf_testing_utils._internal_.VisualViewportEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`VisualViewportEventMap`](akashaproject_ui_awf_testing_utils._internal_.VisualViewportEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:15075

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

node_modules/typescript/lib/lib.dom.d.ts:15076
