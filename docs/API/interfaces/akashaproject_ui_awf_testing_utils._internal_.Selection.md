[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Selection

# Interface: Selection

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Selection

A Selection object represents the range of text selected by the user or the current position of the caret. To obtain a Selection object for examination or modification, call Window.getSelection().

## Table of contents

### Properties

- [anchorNode](akashaproject_ui_awf_testing_utils._internal_.Selection.md#anchornode)
- [anchorOffset](akashaproject_ui_awf_testing_utils._internal_.Selection.md#anchoroffset)
- [focusNode](akashaproject_ui_awf_testing_utils._internal_.Selection.md#focusnode)
- [focusOffset](akashaproject_ui_awf_testing_utils._internal_.Selection.md#focusoffset)
- [isCollapsed](akashaproject_ui_awf_testing_utils._internal_.Selection.md#iscollapsed)
- [rangeCount](akashaproject_ui_awf_testing_utils._internal_.Selection.md#rangecount)
- [type](akashaproject_ui_awf_testing_utils._internal_.Selection.md#type)

### Methods

- [addRange](akashaproject_ui_awf_testing_utils._internal_.Selection.md#addrange)
- [collapse](akashaproject_ui_awf_testing_utils._internal_.Selection.md#collapse)
- [collapseToEnd](akashaproject_ui_awf_testing_utils._internal_.Selection.md#collapsetoend)
- [collapseToStart](akashaproject_ui_awf_testing_utils._internal_.Selection.md#collapsetostart)
- [containsNode](akashaproject_ui_awf_testing_utils._internal_.Selection.md#containsnode)
- [deleteFromDocument](akashaproject_ui_awf_testing_utils._internal_.Selection.md#deletefromdocument)
- [empty](akashaproject_ui_awf_testing_utils._internal_.Selection.md#empty)
- [extend](akashaproject_ui_awf_testing_utils._internal_.Selection.md#extend)
- [getRangeAt](akashaproject_ui_awf_testing_utils._internal_.Selection.md#getrangeat)
- [removeAllRanges](akashaproject_ui_awf_testing_utils._internal_.Selection.md#removeallranges)
- [removeRange](akashaproject_ui_awf_testing_utils._internal_.Selection.md#removerange)
- [selectAllChildren](akashaproject_ui_awf_testing_utils._internal_.Selection.md#selectallchildren)
- [setBaseAndExtent](akashaproject_ui_awf_testing_utils._internal_.Selection.md#setbaseandextent)
- [setPosition](akashaproject_ui_awf_testing_utils._internal_.Selection.md#setposition)
- [toString](akashaproject_ui_awf_testing_utils._internal_.Selection.md#tostring)

## Properties

### anchorNode

• `Readonly` **anchorNode**: [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13966

___

### anchorOffset

• `Readonly` **anchorOffset**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13967

___

### focusNode

• `Readonly` **focusNode**: [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13968

___

### focusOffset

• `Readonly` **focusOffset**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13969

___

### isCollapsed

• `Readonly` **isCollapsed**: `boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13970

___

### rangeCount

• `Readonly` **rangeCount**: `number`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13971

___

### type

• `Readonly` **type**: `string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13972

## Methods

### addRange

▸ **addRange**(`range`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `range` | [`Range`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#range) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13973

___

### collapse

▸ **collapse**(`node`, `offset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `offset?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13974

___

### collapseToEnd

▸ **collapseToEnd**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13975

___

### collapseToStart

▸ **collapseToStart**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13976

___

### containsNode

▸ **containsNode**(`node`, `allowPartialContainment?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `allowPartialContainment?` | `boolean` |

#### Returns

`boolean`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13977

___

### deleteFromDocument

▸ **deleteFromDocument**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13978

___

### empty

▸ **empty**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13979

___

### extend

▸ **extend**(`node`, `offset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `offset?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13980

___

### getRangeAt

▸ **getRangeAt**(`index`): [`Range`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#range)

#### Parameters

| Name | Type |
| :------ | :------ |
| `index` | `number` |

#### Returns

[`Range`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#range)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13981

___

### removeAllRanges

▸ **removeAllRanges**(): `void`

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13982

___

### removeRange

▸ **removeRange**(`range`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `range` | [`Range`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#range) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13983

___

### selectAllChildren

▸ **selectAllChildren**(`node`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13984

___

### setBaseAndExtent

▸ **setBaseAndExtent**(`anchorNode`, `anchorOffset`, `focusNode`, `focusOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `anchorNode` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `anchorOffset` | `number` |
| `focusNode` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `focusOffset` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13985

___

### setPosition

▸ **setPosition**(`node`, `offset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |
| `offset?` | `number` |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13986

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:13987
