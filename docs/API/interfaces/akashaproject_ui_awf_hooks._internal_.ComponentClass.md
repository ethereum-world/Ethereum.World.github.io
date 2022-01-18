[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / ComponentClass

# Interface: ComponentClass<P, S\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).ComponentClass

## Type parameters

| Name | Type |
| :------ | :------ |
| `P` | {} |
| `S` | [`ComponentState`](../modules/akashaproject_ui_awf_hooks._internal_.md#componentstate) |

## Hierarchy

- [`StaticLifecycle`](akashaproject_ui_awf_hooks._internal_.StaticLifecycle.md)<`P`, `S`\>

  ↳ **`ComponentClass`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#constructor)

### Properties

- [childContextTypes](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#childcontexttypes)
- [contextType](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#contexttype)
- [contextTypes](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#contexttypes)
- [defaultProps](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#defaultprops)
- [displayName](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#displayname)
- [getDerivedStateFromError](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#getderivedstatefromerror)
- [getDerivedStateFromProps](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#getderivedstatefromprops)
- [propTypes](akashaproject_ui_awf_hooks._internal_.ComponentClass.md#proptypes)

## Constructors

### constructor

• **new ComponentClass**(`props`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `P` |
| `context?` | `any` |

#### Inherited from

StaticLifecycle<P, S\>.constructor

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:585

## Properties

### childContextTypes

• `Optional` **childContextTypes**: [`ValidationMap`](../modules/akashaproject_ui_awf_hooks._internal_.md#validationmap)<`any`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:589

___

### contextType

• `Optional` **contextType**: [`Context`](akashaproject_ui_awf_hooks._internal_.Context.md)<`any`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:587

___

### contextTypes

• `Optional` **contextTypes**: [`ValidationMap`](../modules/akashaproject_ui_awf_hooks._internal_.md#validationmap)<`any`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:588

___

### defaultProps

• `Optional` **defaultProps**: [`Partial`](../modules/akashaproject_ui_awf_hooks._internal_.md#partial)<`P`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:590

___

### displayName

• `Optional` **displayName**: `string`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:591

___

### getDerivedStateFromError

• `Optional` **getDerivedStateFromError**: [`GetDerivedStateFromError`](../modules/akashaproject_ui_awf_hooks._internal_.md#getderivedstatefromerror)<`P`, `S`\>

#### Inherited from

[StaticLifecycle](akashaproject_ui_awf_hooks._internal_.StaticLifecycle.md).[getDerivedStateFromError](akashaproject_ui_awf_hooks._internal_.StaticLifecycle.md#getderivedstatefromerror)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:646

___

### getDerivedStateFromProps

• `Optional` **getDerivedStateFromProps**: [`GetDerivedStateFromProps`](../modules/akashaproject_ui_awf_hooks._internal_.md#getderivedstatefromprops)<`P`, `S`\>

#### Inherited from

[StaticLifecycle](akashaproject_ui_awf_hooks._internal_.StaticLifecycle.md).[getDerivedStateFromProps](akashaproject_ui_awf_hooks._internal_.StaticLifecycle.md#getderivedstatefromprops)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:645

___

### propTypes

• `Optional` **propTypes**: [`WeakValidationMap`](../modules/akashaproject_ui_awf_hooks._internal_.md#weakvalidationmap)<`P`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:586
