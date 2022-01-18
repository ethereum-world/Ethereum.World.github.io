[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MediaQueryList

# Interface: MediaQueryList

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MediaQueryList

Stores information on a media query applied to a document, and handles sending notifications to listeners when the media query state change (i.e. when the media query test starts or stops evaluating to true).

## Hierarchy

- `EventTarget`

  ↳ **`MediaQueryList`**

## Table of contents

### Properties

- [matches](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#matches)
- [media](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#media)
- [onchange](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#onchange)

### Methods

- [addEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#addeventlistener)
- [addListener](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#addlistener)
- [dispatchEvent](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#dispatchevent)
- [removeEventListener](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#removeeventlistener)
- [removeListener](akashaproject_ui_awf_testing_utils._internal_.MediaQueryList.md#removelistener)

## Properties

### matches

• `Readonly` **matches**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9897

___

### media

• `Readonly` **media**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9898

___

### onchange

• **onchange**: (`ev`: [`MediaQueryListEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylistevent)) => `any`

#### Type declaration

▸ (`ev`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `ev` | [`MediaQueryListEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylistevent) |

##### Returns

`any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9899

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
| `listener` | (`ev`: [`MediaQueryListEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaQueryListEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`AddEventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.AddEventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.addEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9904

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

node_modules/typescript/lib/lib.dom.d.ts:9905

___

### addListener

▸ **addListener**(`callback`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`ev`: [`MediaQueryListEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylistevent)) => `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9901

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
| `K` | extends ``"change"`` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `K` |
| `listener` | (`ev`: [`MediaQueryListEventMap`](akashaproject_ui_awf_testing_utils._internal_.MediaQueryListEventMap.md)[`K`]) => `any` |
| `options?` | `boolean` \| [`EventListenerOptions`](akashaproject_ui_awf_testing_utils._internal_.EventListenerOptions.md) |

#### Returns

`void`

#### Overrides

EventTarget.removeEventListener

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9906

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

node_modules/typescript/lib/lib.dom.d.ts:9907

___

### removeListener

▸ **removeListener**(`callback`): `void`

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`ev`: [`MediaQueryListEvent`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#mediaquerylistevent)) => `any` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9903
