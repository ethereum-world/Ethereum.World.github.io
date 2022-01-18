[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / MutationObserverInit

# Interface: MutationObserverInit

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).MutationObserverInit

## Table of contents

### Properties

- [attributeFilter](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#attributefilter)
- [attributeOldValue](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#attributeoldvalue)
- [attributes](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#attributes)
- [characterData](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#characterdata)
- [characterDataOldValue](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#characterdataoldvalue)
- [childList](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#childlist)
- [subtree](akashaproject_ui_awf_testing_utils._internal_.MutationObserverInit.md#subtree)

## Properties

### attributeFilter

• `Optional` **attributeFilter**: `string`[]

Set to a list of attribute local names (without namespace) if not all attribute mutations need to be observed and attributes is true or omitted.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:904

___

### attributeOldValue

• `Optional` **attributeOldValue**: `boolean`

Set to true if attributes is true or omitted and target's attribute value before the mutation needs to be recorded.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:908

___

### attributes

• `Optional` **attributes**: `boolean`

Set to true if mutations to target's attributes are to be observed. Can be omitted if attributeOldValue or attributeFilter is specified.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:912

___

### characterData

• `Optional` **characterData**: `boolean`

Set to true if mutations to target's data are to be observed. Can be omitted if characterDataOldValue is specified.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:916

___

### characterDataOldValue

• `Optional` **characterDataOldValue**: `boolean`

Set to true if characterData is set to true or omitted and target's data before the mutation needs to be recorded.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:920

___

### childList

• `Optional` **childList**: `boolean`

Set to true if mutations to target's children are to be observed.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:924

___

### subtree

• `Optional` **subtree**: `boolean`

Set to true if mutations to not just target, but also target's descendants are to be observed.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:928
