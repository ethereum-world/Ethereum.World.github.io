[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md) / [<internal\>](../modules/akashaproject_ui_app_loader._internal_.md) / BigNumber

# Class: BigNumber

[@akashaproject/ui-app-loader](../modules/akashaproject_ui_app_loader.md).[<internal>](../modules/akashaproject_ui_app_loader._internal_.md).BigNumber

## Implements

- [`Hexable`](../interfaces/akashaproject_ui_app_loader._internal_.Hexable.md)

## Table of contents

### Constructors

- [constructor](akashaproject_ui_app_loader._internal_.BigNumber.md#constructor)

### Properties

- [\_hex](akashaproject_ui_app_loader._internal_.BigNumber.md#_hex)
- [\_isBigNumber](akashaproject_ui_app_loader._internal_.BigNumber.md#_isbignumber)

### Methods

- [abs](akashaproject_ui_app_loader._internal_.BigNumber.md#abs)
- [add](akashaproject_ui_app_loader._internal_.BigNumber.md#add)
- [and](akashaproject_ui_app_loader._internal_.BigNumber.md#and)
- [div](akashaproject_ui_app_loader._internal_.BigNumber.md#div)
- [eq](akashaproject_ui_app_loader._internal_.BigNumber.md#eq)
- [fromTwos](akashaproject_ui_app_loader._internal_.BigNumber.md#fromtwos)
- [gt](akashaproject_ui_app_loader._internal_.BigNumber.md#gt)
- [gte](akashaproject_ui_app_loader._internal_.BigNumber.md#gte)
- [isNegative](akashaproject_ui_app_loader._internal_.BigNumber.md#isnegative)
- [isZero](akashaproject_ui_app_loader._internal_.BigNumber.md#iszero)
- [lt](akashaproject_ui_app_loader._internal_.BigNumber.md#lt)
- [lte](akashaproject_ui_app_loader._internal_.BigNumber.md#lte)
- [mask](akashaproject_ui_app_loader._internal_.BigNumber.md#mask)
- [mod](akashaproject_ui_app_loader._internal_.BigNumber.md#mod)
- [mul](akashaproject_ui_app_loader._internal_.BigNumber.md#mul)
- [or](akashaproject_ui_app_loader._internal_.BigNumber.md#or)
- [pow](akashaproject_ui_app_loader._internal_.BigNumber.md#pow)
- [shl](akashaproject_ui_app_loader._internal_.BigNumber.md#shl)
- [shr](akashaproject_ui_app_loader._internal_.BigNumber.md#shr)
- [sub](akashaproject_ui_app_loader._internal_.BigNumber.md#sub)
- [toBigInt](akashaproject_ui_app_loader._internal_.BigNumber.md#tobigint)
- [toHexString](akashaproject_ui_app_loader._internal_.BigNumber.md#tohexstring)
- [toJSON](akashaproject_ui_app_loader._internal_.BigNumber.md#tojson)
- [toNumber](akashaproject_ui_app_loader._internal_.BigNumber.md#tonumber)
- [toString](akashaproject_ui_app_loader._internal_.BigNumber.md#tostring)
- [toTwos](akashaproject_ui_app_loader._internal_.BigNumber.md#totwos)
- [xor](akashaproject_ui_app_loader._internal_.BigNumber.md#xor)
- [from](akashaproject_ui_app_loader._internal_.BigNumber.md#from)
- [isBigNumber](akashaproject_ui_app_loader._internal_.BigNumber.md#isbignumber)

## Constructors

### constructor

• **new BigNumber**(`constructorGuard`, `hex`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `constructorGuard` | `any` |
| `hex` | `string` |

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:7

## Properties

### \_hex

• `Readonly` **\_hex**: `string`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:5

___

### \_isBigNumber

• `Readonly` **\_isBigNumber**: `boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:6

## Methods

### abs

▸ **abs**(): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:10

___

### add

▸ **add**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:11

___

### and

▸ **and**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:17

___

### div

▸ **div**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:13

___

### eq

▸ **eq**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:23

___

### fromTwos

▸ **fromTwos**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:8

___

### gt

▸ **gt**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:26

___

### gte

▸ **gte**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:27

___

### isNegative

▸ **isNegative**(): `boolean`

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:28

___

### isZero

▸ **isZero**(): `boolean`

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:29

___

### lt

▸ **lt**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:24

___

### lte

▸ **lte**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:25

___

### mask

▸ **mask**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:20

___

### mod

▸ **mod**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:15

___

### mul

▸ **mul**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:14

___

### or

▸ **or**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:18

___

### pow

▸ **pow**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:16

___

### shl

▸ **shl**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:21

___

### shr

▸ **shr**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:22

___

### sub

▸ **sub**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:12

___

### toBigInt

▸ **toBigInt**(): `bigint`

#### Returns

`bigint`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:31

___

### toHexString

▸ **toHexString**(): `string`

#### Returns

`string`

#### Implementation of

[Hexable](../interfaces/akashaproject_ui_app_loader._internal_.Hexable.md).[toHexString](../interfaces/akashaproject_ui_app_loader._internal_.Hexable.md#tohexstring)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:33

___

### toJSON

▸ **toJSON**(`key?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key?` | `string` |

#### Returns

`any`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:34

___

### toNumber

▸ **toNumber**(): `number`

#### Returns

`number`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:30

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:32

___

### toTwos

▸ **toTwos**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:9

___

### xor

▸ **xor**(`other`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`BigNumberish`](../modules/akashaproject_ui_app_loader._internal_.md#bignumberish) |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:19

___

### from

▸ `Static` **from**(`value`): [`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`BigNumber`](akashaproject_ui_app_loader._internal_.BigNumber.md)

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:35

___

### isBigNumber

▸ `Static` **isBigNumber**(`value`): value is BigNumber

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

value is BigNumber

#### Defined in

sdk/node_modules/@ethersproject/bignumber/lib/bignumber.d.ts:36
