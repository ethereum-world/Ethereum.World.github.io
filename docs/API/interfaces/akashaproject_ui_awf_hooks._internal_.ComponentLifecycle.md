[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / ComponentLifecycle

# Interface: ComponentLifecycle<P, S, SS\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).ComponentLifecycle

## Type parameters

| Name | Type |
| :------ | :------ |
| `P` | `P` |
| `S` | `S` |
| `SS` | `any` |

## Hierarchy

- [`NewLifecycle`](akashaproject_ui_awf_hooks._internal_.NewLifecycle.md)<`P`, `S`, `SS`\>

- [`DeprecatedLifecycle`](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md)<`P`, `S`\>

  ↳ **`ComponentLifecycle`**

  ↳↳ [`Component`](../classes/akashaproject_ui_awf_hooks._internal_.Component.md)

## Table of contents

### Methods

- [UNSAFE\_componentWillMount](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillmount)
- [UNSAFE\_componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillreceiveprops)
- [UNSAFE\_componentWillUpdate](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillupdate)
- [componentDidCatch](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidcatch)
- [componentDidMount](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidmount)
- [componentDidUpdate](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidupdate)
- [componentWillMount](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillmount)
- [componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillreceiveprops)
- [componentWillUnmount](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillunmount)
- [componentWillUpdate](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillupdate)
- [getSnapshotBeforeUpdate](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#getsnapshotbeforeupdate)
- [shouldComponentUpdate](akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#shouldcomponentupdate)

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[UNSAFE_componentWillMount](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillmount)

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[UNSAFE_componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillreceiveprops)

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[UNSAFE_componentWillUpdate](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#unsafe_componentwillupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:771

___

### componentDidCatch

▸ `Optional` **componentDidCatch**(`error`, `errorInfo`): `void`

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | [`Error`](../modules/akashaproject_ui_awf_hooks._internal_.md#error) |
| `errorInfo` | [`ErrorInfo`](akashaproject_ui_awf_hooks._internal_.ErrorInfo.md) |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:640

___

### componentDidMount

▸ `Optional` **componentDidMount**(): `void`

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:619

___

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `snapshot?`): `void`

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `prevState` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\> |
| `snapshot?` | `SS` |

#### Returns

`void`

#### Inherited from

[NewLifecycle](akashaproject_ui_awf_hooks._internal_.NewLifecycle.md).[componentDidUpdate](akashaproject_ui_awf_hooks._internal_.NewLifecycle.md#componentdidupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:682

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[componentWillMount](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillmount)

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillreceiveprops)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:726

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:635

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

#### Inherited from

[DeprecatedLifecycle](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md).[componentWillUpdate](akashaproject_ui_awf_hooks._internal_.DeprecatedLifecycle.md#componentwillupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:756

___

### getSnapshotBeforeUpdate

▸ `Optional` **getSnapshotBeforeUpdate**(`prevProps`, `prevState`): `SS`

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `prevState` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\> |

#### Returns

`SS`

#### Inherited from

[NewLifecycle](akashaproject_ui_awf_hooks._internal_.NewLifecycle.md).[getSnapshotBeforeUpdate](akashaproject_ui_awf_hooks._internal_.NewLifecycle.md#getsnapshotbeforeupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:676

___

### shouldComponentUpdate

▸ `Optional` **shouldComponentUpdate**(`nextProps`, `nextState`, `nextContext`): `boolean`

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |
| `nextState` | [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:630
