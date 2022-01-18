[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / ReadableStreamDefaultReader

# Interface: ReadableStreamDefaultReader<R\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).ReadableStreamDefaultReader

## Type parameters

| Name | Type |
| :------ | :------ |
| `R` | `any` |

## Hierarchy

- [`ReadableStreamGenericReader`](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamGenericReader.md)

  ↳ **`ReadableStreamDefaultReader`**

## Table of contents

### Properties

- [closed](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamDefaultReader.md#closed)

### Methods

- [cancel](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamDefaultReader.md#cancel)
- [read](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamDefaultReader.md#read)
- [releaseLock](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamDefaultReader.md#releaselock)

## Properties

### closed

• `Readonly` **closed**: `Promise`<`undefined`\>

#### Inherited from

[ReadableStreamGenericReader](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamGenericReader.md).[closed](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamGenericReader.md#closed)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12017

## Methods

### cancel

▸ **cancel**(`reason?`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `reason?` | `any` |

#### Returns

`Promise`<`void`\>

#### Inherited from

[ReadableStreamGenericReader](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamGenericReader.md).[cancel](akashaproject_ui_awf_testing_utils._internal_.ReadableStreamGenericReader.md#cancel)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12018

___

### read

▸ **read**(): `Promise`<[`ReadableStreamDefaultReadResult`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#readablestreamdefaultreadresult)<`R`\>\>

#### Returns

`Promise`<[`ReadableStreamDefaultReadResult`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#readablestreamdefaultreadresult)<`R`\>\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12007

___

### releaseLock

▸ **releaseLock**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12008
