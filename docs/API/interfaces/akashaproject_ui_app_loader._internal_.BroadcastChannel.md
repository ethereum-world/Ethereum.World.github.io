[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / BroadcastChannel

# Interface: BroadcastChannel

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).BroadcastChannel

## Hierarchy

- `EventTarget`

  ↳ **`BroadcastChannel`**

## Table of contents

### Properties

- [name](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#name)
- [onmessage](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#onmessage)
- [onmessageerror](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#onmessageerror)

### Methods

- [addEventListener](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#addeventlistener)
- [close](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#close)
- [dispatchEvent](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#dispatchevent)
- [postMessage](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#postmessage)
- [removeEventListener](akashaproject_ui_app_loader._internal_.BroadcastChannel.md#removeeventlistener)

## Properties

### name

• `Readonly` **name**: `string`

Returns the channel name (as passed to the constructor).

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2462

___

### onmessage

• **onmessage**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_app_loader._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_app_loader._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2463

___

### onmessageerror

• **onmessageerror**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_app_loader._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_app_loader._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2464

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`BroadcastChannelEventMap`](akashaproject_ui_app_loader._internal_.BroadcastChannelEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`BroadcastChannelEventMap`](akashaproject_ui_app_loader._internal_.BroadcastChannelEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_app_loader._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2473

▸ **addEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_app_loader._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_app_loader._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2474

___

### close

▸ **close**(): `void`

Closes the BroadcastChannel object, opening it up to garbage collection.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2468

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

### postMessage

▸ **postMessage**(`message`): `void`

Sends the given message to other BroadcastChannel objects set up for this channel. Messages can be structured objects, e.g. nested objects and arrays.

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2472

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`BroadcastChannelEventMap`](akashaproject_ui_app_loader._internal_.BroadcastChannelEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`BroadcastChannelEventMap`](akashaproject_ui_app_loader._internal_.BroadcastChannelEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_app_loader._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2475

▸ **removeEventListener**(`type`, `listener`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |
| `listener` | [`EventListenerOrEventListenerObject`](../modules/akashaproject_ui_app_loader._internal_.md#eventlisteneroreventlistenerobject) |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_app_loader._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2476
