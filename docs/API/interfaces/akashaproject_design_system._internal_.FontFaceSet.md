[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / FontFaceSet

# Interface: FontFaceSet

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).FontFaceSet

## Hierarchy

- `EventTarget`

  ↳ **`FontFaceSet`**

## Table of contents

### Properties

- [onloading](akashaproject_design_system._internal_.FontFaceSet.md#onloading)
- [onloadingdone](akashaproject_design_system._internal_.FontFaceSet.md#onloadingdone)
- [onloadingerror](akashaproject_design_system._internal_.FontFaceSet.md#onloadingerror)
- [ready](akashaproject_design_system._internal_.FontFaceSet.md#ready)
- [status](akashaproject_design_system._internal_.FontFaceSet.md#status)

### Methods

- [addEventListener](akashaproject_design_system._internal_.FontFaceSet.md#addeventlistener)
- [check](akashaproject_design_system._internal_.FontFaceSet.md#check)
- [dispatchEvent](akashaproject_design_system._internal_.FontFaceSet.md#dispatchevent)
- [forEach](akashaproject_design_system._internal_.FontFaceSet.md#foreach)
- [load](akashaproject_design_system._internal_.FontFaceSet.md#load)
- [removeEventListener](akashaproject_design_system._internal_.FontFaceSet.md#removeeventlistener)

## Properties

### onloading

• **onloading**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5398

___

### onloadingdone

• **onloadingdone**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5399

___

### onloadingerror

• **onloadingerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5400

___

### ready

• `Readonly` **ready**: `Promise`<[`FontFaceSet`](../modules/akashaproject_design_system._internal_.md#fontfaceset)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5401

___

### status

• `Readonly` **status**: [`FontFaceSetLoadStatus`](../modules/akashaproject_design_system._internal_.md#fontfacesetloadstatus)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5402

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`FontFaceSetEventMap`](akashaproject_design_system._internal_.FontFaceSetEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`FontFaceSetEventMap`](akashaproject_design_system._internal_.FontFaceSetEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5406

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5407

___

### check

▸ **check**(`font`, `text?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `font` | `string` |
| `text?` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5403

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

### forEach

▸ **forEach**(`callbackfn`, `thisArg?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callbackfn` | (`value`: [`FontFace`](../modules/akashaproject_design_system._internal_.md#fontface), `key`: [`FontFace`](../modules/akashaproject_design_system._internal_.md#fontface), `parent`: [`FontFaceSet`](../modules/akashaproject_design_system._internal_.md#fontfaceset)) => `void` |
| `thisArg?` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5405

___

### load

▸ **load**(`font`, `text?`): `Promise`<[`FontFace`](../modules/akashaproject_design_system._internal_.md#fontface)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `font` | `string` |
| `text?` | `string` |

#### Returns

`Promise`<[`FontFace`](../modules/akashaproject_design_system._internal_.md#fontface)[]\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5404

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`FontFaceSetEventMap`](akashaproject_design_system._internal_.FontFaceSetEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`FontFaceSetEventMap`](akashaproject_design_system._internal_.FontFaceSetEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5408

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_design_system._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:5409
