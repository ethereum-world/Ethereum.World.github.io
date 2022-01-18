[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / TextEncoder

# Interface: TextEncoder

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).TextEncoder

TextEncoder takes a stream of code points as input and emits a stream of bytes. For a more scalable, non-native library, see StringView – a C-like representation of strings based on typed arrays.

## Hierarchy

- [`TextEncoderCommon`](akashaproject_awf_sdk._internal_.TextEncoderCommon.md)

  ↳ **`TextEncoder`**

## Table of contents

### Properties

- [encoding](akashaproject_awf_sdk._internal_.TextEncoder.md#encoding)

### Methods

- [encode](akashaproject_awf_sdk._internal_.TextEncoder.md#encode)
- [encodeInto](akashaproject_awf_sdk._internal_.TextEncoder.md#encodeinto)

## Properties

### encoding

• `Readonly` **encoding**: `string`

Returns "utf-8".

#### Inherited from

[TextEncoderCommon](akashaproject_awf_sdk._internal_.TextEncoderCommon.md).[encoding](akashaproject_awf_sdk._internal_.TextEncoderCommon.md#encoding)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14557

## Methods

### encode

▸ **encode**(`input?`): `Uint8Array`

Returns the result of running UTF-8's encoder.

#### Parameters

| Name | Type |
| :------ | :------ |
| `input?` | `string` |

#### Returns

`Uint8Array`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14541

___

### encodeInto

▸ **encodeInto**(`source`, `destination`): [`TextEncoderEncodeIntoResult`](akashaproject_awf_sdk._internal_.TextEncoderEncodeIntoResult.md)

Runs the UTF-8 encoder on source, stores the result of that operation into destination, and returns the progress made as an object wherein read is the number of converted code units of source and written is the number of bytes modified in destination.

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | `string` |
| `destination` | `Uint8Array` |

#### Returns

[`TextEncoderEncodeIntoResult`](akashaproject_awf_sdk._internal_.TextEncoderEncodeIntoResult.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14545
