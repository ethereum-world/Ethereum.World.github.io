[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / EventBus

# Class: EventBus

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).EventBus

## Hierarchy

- `ReplaySubject`<{ `args?`: `unknown` ; `data`: `unknown` ; `event`: `string`  }\>

  ↳ **`EventBus`**

## Table of contents

### Constructors

- [constructor](akashaproject_awf_sdk._internal_.EventBus.md#constructor)

## Constructors

### constructor

• **new EventBus**(`size?`, `time?`, `timeStampProvider?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `size?` | `number` |
| `time?` | `number` |
| `timeStampProvider?` | `TimestampProvider` |

#### Overrides

ReplaySubject&lt;{
  data: unknown;
  event: string;
  args?: unknown;
}\&gt;.constructor

#### Defined in

[sdk/src/common/event-bus.ts:12](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/sdk/src/common/event-bus.ts#L12)
