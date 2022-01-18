[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Notification

# Interface: Notification

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Notification

This Notifications API interface is used to configure and display desktop notifications to the user.

## Hierarchy

- `EventTarget`

  ↳ **`Notification`**

## Table of contents

### Properties

- [body](akashaproject_ui_awf_testing_utils._internal_.Notification.md#body)
- [data](akashaproject_ui_awf_testing_utils._internal_.Notification.md#data)
- [dir](akashaproject_ui_awf_testing_utils._internal_.Notification.md#dir)
- [icon](akashaproject_ui_awf_testing_utils._internal_.Notification.md#icon)
- [lang](akashaproject_ui_awf_testing_utils._internal_.Notification.md#lang)
- [onclick](akashaproject_ui_awf_testing_utils._internal_.Notification.md#onclick)
- [onclose](akashaproject_ui_awf_testing_utils._internal_.Notification.md#onclose)
- [onerror](akashaproject_ui_awf_testing_utils._internal_.Notification.md#onerror)
- [onshow](akashaproject_ui_awf_testing_utils._internal_.Notification.md#onshow)
- [tag](akashaproject_ui_awf_testing_utils._internal_.Notification.md#tag)
- [title](akashaproject_ui_awf_testing_utils._internal_.Notification.md#title)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.Notification.md#addeventlistener)
- [close](akashaproject_ui_awf_testing_utils._internal_.Notification.md#close)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.Notification.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.Notification.md#removeeventlistener)

## Properties

### body

• `Readonly` **body**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10779

___

### data

• `Readonly` **data**: `any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10780

___

### dir

• `Readonly` **dir**: [`NotificationDirection`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#notificationdirection)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10781

___

### icon

• `Readonly` **icon**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10782

___

### lang

• `Readonly` **lang**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10783

___

### onclick

• **onclick**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10784

___

### onclose

• **onclose**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10785

___

### onerror

• **onerror**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10786

___

### onshow

• **onshow**: (`ev`: `Event`) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | `Event` |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10787

___

### tag

• `Readonly` **tag**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10788

___

### title

• `Readonly` **title**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10789

## Methods

### addEventListener

▸ **addEventListener**<`K`\>(`type`, `listener`, `options?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends keyof [`NotificationEventMap`](akashaproject_ui_awf_testing_utils._internal_.NotificationEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`NotificationEventMap`](akashaproject_ui_awf_testing_utils._internal_.NotificationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10791

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

node_modules/typescript/lib/lib.dom.d.ts:10792

___

### close

▸ **close**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10790

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
| `K` | extends keyof [`NotificationEventMap`](akashaproject_ui_awf_testing_utils._internal_.NotificationEventMap.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`NotificationEventMap`](akashaproject_ui_awf_testing_utils._internal_.NotificationEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:10793

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

node_modules/typescript/lib/lib.dom.d.ts:10794
