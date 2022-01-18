[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md) / [<internal\>](../modules/akashaproject_ui_awf_hooks._internal_.md) / Component

# Class: Component<P, S, SS\>

[@akashaproject/ui-awf-hooks](../modules/akashaproject_ui_awf_hooks.md).[<internal>](../modules/akashaproject_ui_awf_hooks._internal_.md).Component

## Type parameters

| Name | Type |
| :------ | :------ |
| `P` | {} |
| `S` | {} |
| `SS` | `any` |

## Hierarchy

- [`ComponentLifecycle`](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md)<`P`, `S`, `SS`\>

  ↳ **`Component`**

## Table of contents

### Constructors

- [constructor](akashaproject_ui_awf_hooks._internal_.Component.md#constructor)

### Properties

- [context](akashaproject_ui_awf_hooks._internal_.Component.md#context)
- [props](akashaproject_ui_awf_hooks._internal_.Component.md#props)
- [refs](akashaproject_ui_awf_hooks._internal_.Component.md#refs)
- [state](akashaproject_ui_awf_hooks._internal_.Component.md#state)
- [contextType](akashaproject_ui_awf_hooks._internal_.Component.md#contexttype)

### Methods

- [UNSAFE\_componentWillMount](akashaproject_ui_awf_hooks._internal_.Component.md#unsafe_componentwillmount)
- [UNSAFE\_componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.Component.md#unsafe_componentwillreceiveprops)
- [UNSAFE\_componentWillUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#unsafe_componentwillupdate)
- [componentDidCatch](akashaproject_ui_awf_hooks._internal_.Component.md#componentdidcatch)
- [componentDidMount](akashaproject_ui_awf_hooks._internal_.Component.md#componentdidmount)
- [componentDidUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#componentdidupdate)
- [componentWillMount](akashaproject_ui_awf_hooks._internal_.Component.md#componentwillmount)
- [componentWillReceiveProps](akashaproject_ui_awf_hooks._internal_.Component.md#componentwillreceiveprops)
- [componentWillUnmount](akashaproject_ui_awf_hooks._internal_.Component.md#componentwillunmount)
- [componentWillUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#componentwillupdate)
- [forceUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#forceupdate)
- [getSnapshotBeforeUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#getsnapshotbeforeupdate)
- [render](akashaproject_ui_awf_hooks._internal_.Component.md#render)
- [setState](akashaproject_ui_awf_hooks._internal_.Component.md#setstate)
- [shouldComponentUpdate](akashaproject_ui_awf_hooks._internal_.Component.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Component**<`P`, `S`, `SS`\>(`props`)

#### Type parameters

| Name | Type |
| :------ | :------ |
| `P` | {} |
| `S` | {} |
| `SS` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `P` \| [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> |

#### Inherited from

ComponentLifecycle<P, S, SS\>.constructor

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:475

• **new Component**<`P`, `S`, `SS`\>(`props`, `context`)

**`deprecated`**

**`see`** https://reactjs.org/docs/legacy-context.html

#### Type parameters

| Name | Type |
| :------ | :------ |
| `P` | {} |
| `S` | {} |
| `SS` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `P` |
| `context` | `any` |

#### Inherited from

ComponentLifecycle<P, S, SS\>.constructor

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:480

## Properties

### context

• **context**: `any`

If using the new style context, re-declare this in your class to be the
`React.ContextType` of your `static contextType`.
Should be used with type annotation or static contextType.

```ts
static contextType = MyContext
// For TS pre-3.7:
context!: React.ContextType<typeof MyContext>
// For TS 3.7 and above:
declare context: React.ContextType<typeof MyContext>
```

**`see`** https://reactjs.org/docs/context.html

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:473

___

### props

• `Readonly` **props**: [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\> & [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<{ `children?`: [`ReactNode`](../modules/akashaproject_ui_awf_hooks._internal_.md#reactnode)  }\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:498

___

### refs

• **refs**: `Object`

**`deprecated`**
https://reactjs.org/docs/refs-and-the-dom.html#legacy-api-string-refs

#### Index signature

▪ [key: `string`]: [`ReactInstance`](../modules/akashaproject_ui_awf_hooks._internal_.md#reactinstance)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:504

___

### state

• **state**: [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\>

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:499

___

### contextType

▪ `Static` `Optional` **contextType**: [`Context`](../interfaces/akashaproject_ui_awf_hooks._internal_.Context.md)<`any`\>

If set, `this.context` will be set at runtime to the current value of the given Context.

Usage:

```ts
type MyContext = number
const Ctx = React.createContext<MyContext>(0)

class Foo extends React.Component {
  static contextType = Ctx
  context!: React.ContextType<typeof Ctx>
  render () {
    return <>My context's value: {this.context}</>;
  }
}
```

**`see`** https://reactjs.org/docs/context.html#classcontexttype

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:455

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[UNSAFE_componentWillMount](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillmount)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[UNSAFE_componentWillReceiveProps](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillreceiveprops)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[UNSAFE_componentWillUpdate](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#unsafe_componentwillupdate)

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
| `errorInfo` | [`ErrorInfo`](../interfaces/akashaproject_ui_awf_hooks._internal_.ErrorInfo.md) |

#### Returns

`void`

#### Inherited from

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentDidCatch](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidcatch)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:640

___

### componentDidMount

▸ `Optional` **componentDidMount**(): `void`

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

#### Returns

`void`

#### Inherited from

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentDidMount](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidmount)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentDidUpdate](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentdidupdate)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentWillMount](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillmount)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentWillReceiveProps](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillreceiveprops)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:726

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

#### Returns

`void`

#### Inherited from

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentWillUnmount](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillunmount)

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[componentWillUpdate](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#componentwillupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:756

___

### forceUpdate

▸ **forceUpdate**(`callback?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback?` | () => `void` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:490

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

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[getSnapshotBeforeUpdate](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#getsnapshotbeforeupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:676

___

### render

▸ **render**(): [`ReactNode`](../modules/akashaproject_ui_awf_hooks._internal_.md#reactnode)

#### Returns

[`ReactNode`](../modules/akashaproject_ui_awf_hooks._internal_.md#reactnode)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:491

___

### setState

▸ **setState**<`K`\>(`state`, `callback?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends `string` \| `number` \| `symbol` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | `S` \| (`prevState`: [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`S`\>, `props`: [`Readonly`](../modules/akashaproject_ui_awf_hooks._internal_.md#readonly)<`P`\>) => `S` \| [`Pick`](../modules/akashaproject_ui_awf_hooks._internal_.md#pick)<`S`, `K`\> \| [`Pick`](../modules/akashaproject_ui_awf_hooks._internal_.md#pick)<`S`, `K`\> |
| `callback?` | () => `void` |

#### Returns

`void`

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:485

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

#### Inherited from

[ComponentLifecycle](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md).[shouldComponentUpdate](../interfaces/akashaproject_ui_awf_hooks._internal_.ComponentLifecycle.md#shouldcomponentupdate)

#### Defined in

ui/hooks/node_modules/@types/react/index.d.ts:630
