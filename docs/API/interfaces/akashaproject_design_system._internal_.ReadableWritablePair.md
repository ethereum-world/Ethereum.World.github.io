[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / ReadableWritablePair

# Interface: ReadableWritablePair<R, W\>

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).ReadableWritablePair

## Type parameters

| Name | Type |
| :------ | :------ |
| `R` | `any` |
| `W` | `any` |

## Table of contents

### Properties

- [readable](akashaproject_design_system._internal_.ReadableWritablePair.md#readable)
- [writable](akashaproject_design_system._internal_.ReadableWritablePair.md#writable)

## Properties

### readable

• **readable**: [`ReadableStream`](../modules/akashaproject_design_system._internal_.md#readablestream)<`R`\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1462

___

### writable

• **writable**: [`WritableStream`](../modules/akashaproject_design_system._internal_.md#writablestream)<`W`\>

Provides a convenient, chainable way of piping this readable stream through a transform stream (or any other { writable, readable } pair). It simply pipes the stream into the writable side of the supplied pair, and returns the readable side for further use.

Piping a stream will lock it for the duration of the pipe, preventing any other consumer from acquiring a reader.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1468
