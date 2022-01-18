[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MessagePort

# Interface: MessagePort

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MessagePort

This Channel Messaging API interface represents one of the two ports of a MessageChannel, allowing messages to be sent from one port and listening out for them arriving at the other.

## Hierarchy

- `EventTarget`

  ↳ **`MessagePort`**

## Table of contents

### Properties

- [onmessage](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#onmessage)
- [onmessageerror](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#onmessageerror)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#addeventlistener)
- [close](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#close)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#dispatchevent)
- [postMessage](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#postmessage)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#removeeventlistener)
- [start](akashaproject_ui_awf_testing_utils._internal_.MessagePort.md#start)

## Properties

### onmessage

• **onmessage**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10166

___

### onmessageerror

• **onmessageerror**: (`ev`: [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\>) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MessageEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#messageevent)<`any`\> |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10167

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MessagePortEventMap`](akashaproject_ui_awf_testing_utils._internal_.MessagePortEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MessagePortEventMap`](akashaproject_ui_awf_testing_utils._internal_.MessagePortEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10183

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

node_modules/typescript/lib/lib.dom.d.ts:10184

___

### close

▸ **close**(): `void`

Disconnects the port, so that it is no longer active.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10171

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

▸ **postMessage**(`message`, `transfer`): `void`

Posts a message through the channel. Objects listed in transfer are transferred, not just cloned, meaning that they are no longer usable on the sending side.

Throws a "DataCloneError" DOMException if transfer contains duplicate objects or port, or if message could not be cloned.

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `transfer` | [`Transferable`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#transferable)[] |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10177

▸ **postMessage**(`message`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |
| `options?` | [`PostMessageOptions`](akashaproject_ui_awf_testing_utils._internal_.PostMessageOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10178

___

### removeEventListener

▸ **removeEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`MessagePortEventMap`](akashaproject_ui_awf_testing_utils._internal_.MessagePortEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MessagePortEventMap`](akashaproject_ui_awf_testing_utils._internal_.MessagePortEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10185

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

node_modules/typescript/lib/lib.dom.d.ts:10186

___

### start

▸ **start**(): `void`

Begins dispatching messages received on the port.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10182
