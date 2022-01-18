[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / IDBKeyRange

# Interface: IDBKeyRange

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).IDBKeyRange

A key range can be a single value or a range with upper and lower bounds or endpoints. If the key range has both upper and lower bounds, then it is bounded; if it has no bounds, it is unbounded. A bounded key range can either be open (the endpoints are excluded) or closed (the endpoints are included). To retrieve all keys within a certain range, you can use the following code constructs:

## Table of contents

### Properties

- [lower](akashaproject_ui_awf_testing_utils._internal_.IDBKeyRange.md#lower)
- [lowerOpen](akashaproject_ui_awf_testing_utils._internal_.IDBKeyRange.md#loweropen)
- [upper](akashaproject_ui_awf_testing_utils._internal_.IDBKeyRange.md#upper)
- [upperOpen](akashaproject_ui_awf_testing_utils._internal_.IDBKeyRange.md#upperopen)

### Methods

- [includes](akashaproject_ui_awf_testing_utils._internal_.IDBKeyRange.md#includes)

## Properties

### lower

• `Readonly` **lower**: `any`

Returns lower bound, or undefined if none.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9154

___

### lowerOpen

• `Readonly` **lowerOpen**: `boolean`

Returns true if the lower open flag is set, and false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9158

___

### upper

• `Readonly` **upper**: `any`

Returns upper bound, or undefined if none.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9162

___

### upperOpen

• `Readonly` **upperOpen**: `boolean`

Returns true if the upper open flag is set, and false otherwise.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9166

## Methods

### includes

▸ **includes**(`key`): `boolean`

Returns true if key is included in the range, and false otherwise.

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `any` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9170
