[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / TextTrackCueList

# Interface: TextTrackCueList

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).TextTrackCueList

## Indexable

▪ [index: `number`]: [`TextTrackCue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#texttrackcue)

## Table of contents

### Properties

- [length](akashaproject_ui_awf_testing_utils._internal_.TextTrackCueList.md#length)

### Methods

- [getCueById](akashaproject_ui_awf_testing_utils._internal_.TextTrackCueList.md#getcuebyid)

## Properties

### length

• `Readonly` **length**: `number`

Returns the number of cues in the list.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14723

## Methods

### getCueById

▸ **getCueById**(`id`): [`TextTrackCue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#texttrackcue)

Returns the first text track cue (in text track cue order) with text track cue identifier id.

Returns null if none of the cues have the given identifier or if the argument is the empty string.

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |

#### Returns

[`TextTrackCue`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#texttrackcue)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:14729
