[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / DeprecatedLifecycle

# Interface: DeprecatedLifecycle<P, S\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).DeprecatedLifecycle

## Type parameters

| Name |
| :------ |
| `P` |
| `S` |

## Hierarchy

- **`DeprecatedLifecycle`**

  ↳ [`ComponentLifecycle`](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md)

## Table of contents

### Methods

- [UNSAFE\_componentWillMount](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillmount)
- [UNSAFE\_componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillreceiveprops)
- [UNSAFE\_componentWillUpdate](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillupdate)
- [componentWillMount](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillmount)
- [componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillreceiveprops)
- [componentWillUpdate](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillupdate)

## Methods

### UNSAFE\_componentWillMount

▸ `Optional` **UNSAFE_componentWillMount**(): `void`

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:711

___

### UNSAFE\_componentWillReceiveProps

▸ `Optional` **UNSAFE_componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:743

___

### UNSAFE\_componentWillUpdate

▸ `Optional` **UNSAFE_componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `nextState` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:771

___

### componentWillMount

▸ `Optional` **componentWillMount**(): `void`

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:697

___

### componentWillReceiveProps

▸ `Optional` **componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:726

___

### componentWillUpdate

▸ `Optional` **componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`deprecated`** 16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update

**`see`** https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `nextState` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:756
