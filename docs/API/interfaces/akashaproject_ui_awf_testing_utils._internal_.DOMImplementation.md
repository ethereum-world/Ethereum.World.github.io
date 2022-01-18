[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / DOMImplementation

# Interface: DOMImplementation

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).DOMImplementation

An object providing methods which are not dependent on any particular document. Such an object is returned by the Document.implementation property.

## Table of contents

### Methods

- [createDocument](akashaproject_ui_awf_testing_utils._internal_.DOMImplementation.md#createdocument)
- [createDocumentType](akashaproject_ui_awf_testing_utils._internal_.DOMImplementation.md#createdocumenttype)
- [createHTMLDocument](akashaproject_ui_awf_testing_utils._internal_.DOMImplementation.md#createhtmldocument)
- [hasFeature](akashaproject_ui_awf_testing_utils._internal_.DOMImplementation.md#hasfeature)

## Methods

### createDocument

▸ **createDocument**(`namespace`, `qualifiedName`, `doctype?`): [`XMLDocument`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#xmldocument)

#### Parameters

| Name | Type |
| :------ | :------ |
| `namespace` | `string` |
| `qualifiedName` | `string` |
| `doctype?` | [`DocumentType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#documenttype) |

#### Returns

[`XMLDocument`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#xmldocument)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3759

___

### createDocumentType

▸ **createDocumentType**(`qualifiedName`, `publicId`, `systemId`): [`DocumentType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#documenttype)

#### Parameters

| Name | Type |
| :------ | :------ |
| `qualifiedName` | `string` |
| `publicId` | `string` |
| `systemId` | `string` |

#### Returns

[`DocumentType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#documenttype)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3760

___

### createHTMLDocument

▸ **createHTMLDocument**(`title?`): `Document`

#### Parameters

| Name | Type |
| :------ | :------ |
| `title?` | `string` |

#### Returns

`Document`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3761

___

### hasFeature

▸ **hasFeature**(...`args`): ``true``

**`deprecated`**

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Returns

``true``

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:3763
