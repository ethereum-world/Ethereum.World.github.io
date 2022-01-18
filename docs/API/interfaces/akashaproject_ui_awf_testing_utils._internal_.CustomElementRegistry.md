[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / CustomElementRegistry

# Interface: CustomElementRegistry

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).CustomElementRegistry

## Table of contents

### Methods

- [define](akashaproject_ui_awf_testing_utils._internal_.CustomElementRegistry.md#define)
- [get](akashaproject_ui_awf_testing_utils._internal_.CustomElementRegistry.md#get)
- [upgrade](akashaproject_ui_awf_testing_utils._internal_.CustomElementRegistry.md#upgrade)
- [whenDefined](akashaproject_ui_awf_testing_utils._internal_.CustomElementRegistry.md#whendefined)

## Methods

### define

▸ **define**(`name`, `constructor`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `constructor` | [`CustomElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.CustomElementConstructor.md) |
| `options?` | [`ElementDefinitionOptions`](akashaproject_ui_awf_testing_utils._internal_.ElementDefinitionOptions.md) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3670

___

### get

▸ **get**(`name`): [`CustomElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.CustomElementConstructor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

[`CustomElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.CustomElementConstructor.md)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3671

___

### upgrade

▸ **upgrade**(`root`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `root` | [`Node`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#node) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3672

___

### whenDefined

▸ **whenDefined**(`name`): `Promise`<[`CustomElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.CustomElementConstructor.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`Promise`<[`CustomElementConstructor`](akashaproject_ui_awf_testing_utils._internal_.CustomElementConstructor.md)\>

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3673
