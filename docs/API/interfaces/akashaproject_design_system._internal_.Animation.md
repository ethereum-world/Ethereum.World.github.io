[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / Animation

# Interface: Animation

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).Animation

## Hierarchy

- `EventTarget`

  ↳ **`Animation`**

## Table of contents

### Properties

- [currentTime](akashaproject_design_system._internal_.Animation.md#currenttime)
- [effect](akashaproject_design_system._internal_.Animation.md#effect)
- [finished](akashaproject_design_system._internal_.Animation.md#finished)
- [id](akashaproject_design_system._internal_.Animation.md#id)
- [oncancel](akashaproject_design_system._internal_.Animation.md#oncancel)
- [onfinish](akashaproject_design_system._internal_.Animation.md#onfinish)
- [onremove](akashaproject_design_system._internal_.Animation.md#onremove)
- [pending](akashaproject_design_system._internal_.Animation.md#pending)
- [playState](akashaproject_design_system._internal_.Animation.md#playstate)
- [playbackRate](akashaproject_design_system._internal_.Animation.md#playbackrate)
- [ready](akashaproject_design_system._internal_.Animation.md#ready)
- [replaceState](akashaproject_design_system._internal_.Animation.md#replacestate)
- [startTime](akashaproject_design_system._internal_.Animation.md#starttime)
- [timeline](akashaproject_design_system._internal_.Animation.md#timeline)

### Methods

- [addEventListener](akashaproject_design_system._internal_.Animation.md#addeventlistener)
- [cancel](akashaproject_design_system._internal_.Animation.md#cancel)
- [commitStyles](akashaproject_design_system._internal_.Animation.md#commitstyles)
- [dispatchEvent](akashaproject_design_system._internal_.Animation.md#dispatchevent)
- [finish](akashaproject_design_system._internal_.Animation.md#finish)
- [pause](akashaproject_design_system._internal_.Animation.md#pause)
- [persist](akashaproject_design_system._internal_.Animation.md#persist)
- [play](akashaproject_design_system._internal_.Animation.md#play)
- [removeEventListener](akashaproject_design_system._internal_.Animation.md#removeeventlistener)
- [reverse](akashaproject_design_system._internal_.Animation.md#reverse)
- [updatePlaybackRate](akashaproject_design_system._internal_.Animation.md#updateplaybackrate)

## Properties

### currentTime

• **currentTime**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2007

___

### effect

• **effect**: [`AnimationEffect`](../modules/akashaproject_design_system._internal_.md#animationeffect)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2008

___

### finished

• `Readonly` **finished**: `Promise`<[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2009

___

### id

• **id**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2010

___

### oncancel

• **oncancel**: (`ev`: [`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2011

___

### onfinish

• **onfinish**: (`ev`: [`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`AnimationPlaybackEvent`](../modules/akashaproject_design_system._internal_.md#animationplaybackevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2012

___

### onremove

• **onremove**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2013

___

### pending

• `Readonly` **pending**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2014

___

### playState

• `Readonly` **playState**: [`AnimationPlayState`](../modules/akashaproject_design_system._internal_.md#animationplaystate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2015

___

### playbackRate

• **playbackRate**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2016

___

### ready

• `Readonly` **ready**: `Promise`<[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2017

___

### replaceState

• `Readonly` **replaceState**: [`AnimationReplaceState`](../modules/akashaproject_design_system._internal_.md#animationreplacestate)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2018

___

### startTime

• **startTime**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2019

___

### timeline

• **timeline**: [`AnimationTimeline`](../modules/akashaproject_design_system._internal_.md#animationtimeline)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2020

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`AnimationEventMap`](akashaproject_design_system._internal_.AnimationEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`AnimationEventMap`](akashaproject_design_system._internal_.AnimationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_design_system._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2029

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

node_modules/typescript/lib/lib.dom.d.ts:2030

___

### cancel

▸ **cancel**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2021

___

### commitStyles

▸ **commitStyles**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2022

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

### finish

▸ **finish**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2023

___

### pause

▸ **pause**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2024

___

### persist

▸ **persist**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2025

___

### play

▸ **play**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2026

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`AnimationEventMap`](akashaproject_design_system._internal_.AnimationEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`AnimationEventMap`](akashaproject_design_system._internal_.AnimationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_design_system._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2031

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

node_modules/typescript/lib/lib.dom.d.ts:2032

___

### reverse

▸ **reverse**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2027

___

### updatePlaybackRate

▸ **updatePlaybackRate**(`playbackRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `playbackRate` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2028
