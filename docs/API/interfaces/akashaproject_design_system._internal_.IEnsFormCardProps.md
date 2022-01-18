[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / IEnsFormCardProps

# Interface: IEnsFormCardProps

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).IEnsFormCardProps

## Table of contents

### Properties

- [cancelLabel](akashaproject_design_system._internal_.IEnsFormCardProps.md#cancellabel)
- [className](akashaproject_design_system._internal_.IEnsFormCardProps.md#classname)
- [disableInputOnOption](akashaproject_design_system._internal_.IEnsFormCardProps.md#disableinputonoption)
- [ensSubdomain](akashaproject_design_system._internal_.IEnsFormCardProps.md#enssubdomain)
- [errorLabel](akashaproject_design_system._internal_.IEnsFormCardProps.md#errorlabel)
- [errorMessage](akashaproject_design_system._internal_.IEnsFormCardProps.md#errormessage)
- [isValidating](akashaproject_design_system._internal_.IEnsFormCardProps.md#isvalidating)
- [nameLabel](akashaproject_design_system._internal_.IEnsFormCardProps.md#namelabel)
- [options](akashaproject_design_system._internal_.IEnsFormCardProps.md#options)
- [registrationStatus](akashaproject_design_system._internal_.IEnsFormCardProps.md#registrationstatus)
- [saveLabel](akashaproject_design_system._internal_.IEnsFormCardProps.md#savelabel)
- [saving](akashaproject_design_system._internal_.IEnsFormCardProps.md#saving)
- [titleLabel](akashaproject_design_system._internal_.IEnsFormCardProps.md#titlelabel)

### Methods

- [onCancel](akashaproject_design_system._internal_.IEnsFormCardProps.md#oncancel)
- [onSave](akashaproject_design_system._internal_.IEnsFormCardProps.md#onsave)

## Properties

### cancelLabel

• **cancelLabel**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:33](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L33)

___

### className

• `Optional` **className**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:29](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L29)

___

### disableInputOnOption

• `Optional` **disableInputOnOption**: `Object`

#### Index signature

▪ [key: `string`]: `boolean`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:39](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L39)

___

### ensSubdomain

• `Optional` **ensSubdomain**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:38](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L38)

___

### errorLabel

• **errorLabel**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:32](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L32)

___

### errorMessage

• `Optional` **errorMessage**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:40](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L40)

___

### isValidating

• `Optional` **isValidating**: `boolean`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:37](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L37)

___

### nameLabel

• **nameLabel**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:31](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L31)

___

### options

• **options**: [`EnsFormOption`](akashaproject_design_system._internal_.EnsFormOption.md)[]

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:42](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L42)

___

### registrationStatus

• `Optional` **registrationStatus**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `claiming` | `boolean` |
| `registering` | `boolean` |

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:41](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L41)

___

### saveLabel

• **saveLabel**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:34](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L34)

___

### saving

• `Optional` **saving**: `boolean`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:43](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L43)

___

### titleLabel

• **titleLabel**: `string`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:30](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L30)

## Methods

### onCancel

▸ `Optional` **onCancel**(): `void`

#### Returns

`void`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:36](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L36)

___

### onSave

▸ **onSave**(`option`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `option` | [`EnsFormOption`](akashaproject_design_system._internal_.EnsFormOption.md) |

#### Returns

`void`

#### Defined in

[ui/design/src/components/EnsFormCard/index.tsx:35](https://github.com/AKASHAorg/akasha-world-framework/blob/d81a7246/ui/design/src/components/EnsFormCard/index.tsx#L35)
