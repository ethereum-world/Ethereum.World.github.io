[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Crypto

# Interface: Crypto

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Crypto

Basic cryptography features available in the current context. It allows access to a cryptographically strong random number generator and to cryptographic primitives.

## Table of contents

### Properties

- [subtle](akashaproject_ui_awf_testing_utils._internal_.Crypto.md#subtle)

### Methods

- [getRandomValues](akashaproject_ui_awf_testing_utils._internal_.Crypto.md#getrandomvalues)

## Properties

### subtle

• `Readonly` **subtle**: [`SubtleCrypto`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#subtlecrypto)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3647

## Methods

### getRandomValues

▸ **getRandomValues**<`T`\>(`array`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`ArrayBufferView`](akashaproject_ui_awf_testing_utils._internal_.ArrayBufferView.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `array` | `T` |

#### Returns

`T`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3648
