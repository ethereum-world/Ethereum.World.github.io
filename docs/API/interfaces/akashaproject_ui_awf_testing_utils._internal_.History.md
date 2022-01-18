[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / History

# Interface: History

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).History

Allows manipulation of the browser session history, that is the pages visited in the tab or frame that the current page is loaded in.

## Table of contents

### Properties

- [length](akashaproject_ui_awf_testing_utils._internal_.History.md#length)
- [scrollRestoration](akashaproject_ui_awf_testing_utils._internal_.History.md#scrollrestoration)
- [state](akashaproject_ui_awf_testing_utils._internal_.History.md#state)

### Methods

- [back](akashaproject_ui_awf_testing_utils._internal_.History.md#back)
- [forward](akashaproject_ui_awf_testing_utils._internal_.History.md#forward)
- [go](akashaproject_ui_awf_testing_utils._internal_.History.md#go)
- [pushState](akashaproject_ui_awf_testing_utils._internal_.History.md#pushstate)
- [replaceState](akashaproject_ui_awf_testing_utils._internal_.History.md#replacestate)

## Properties

### length

• `Readonly` **length**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8927

___

### scrollRestoration

• **scrollRestoration**: [`ScrollRestoration`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#scrollrestoration)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8928

___

### state

• `Readonly` **state**: `any`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8929

## Methods

### back

▸ **back**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8930

___

### forward

▸ **forward**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8931

___

### go

▸ **go**(`delta?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delta?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8932

___

### pushState

▸ **pushState**(`data`, `unused`, `url?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |
| `unused` | `string` |
| `url?` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8933

___

### replaceState

▸ **replaceState**(`data`, `unused`, `url?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |
| `unused` | `string` |
| `url?` | `string` \| [`URL`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#url) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:8934
