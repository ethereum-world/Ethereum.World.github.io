[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / default

# Class: default

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).default

## Hierarchy

- [`Component`](akashaproject_design_system._internal_.Component.md)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\>

  ↳ **`default`**

## Table of contents

### Constructors

- [constructor](akashaproject_design_system._internal_.default.md#constructor)

### Properties

- [context](akashaproject_design_system._internal_.default.md#context)
- [props](akashaproject_design_system._internal_.default.md#props)
- [refs](akashaproject_design_system._internal_.default.md#refs)
- [state](akashaproject_design_system._internal_.default.md#state)
- [contextType](akashaproject_design_system._internal_.default.md#contexttype)

### Methods

- [UNSAFE\_componentWillMount](akashaproject_design_system._internal_.default.md#unsafe_componentwillmount)
- [UNSAFE\_componentWillReceiveProps](akashaproject_design_system._internal_.default.md#unsafe_componentwillreceiveprops)
- [UNSAFE\_componentWillUpdate](akashaproject_design_system._internal_.default.md#unsafe_componentwillupdate)
- [componentDidCatch](akashaproject_design_system._internal_.default.md#componentdidcatch)
- [componentDidMount](akashaproject_design_system._internal_.default.md#componentdidmount)
- [componentDidUpdate](akashaproject_design_system._internal_.default.md#componentdidupdate)
- [componentWillMount](akashaproject_design_system._internal_.default.md#componentwillmount)
- [componentWillReceiveProps](akashaproject_design_system._internal_.default.md#componentwillreceiveprops)
- [componentWillUnmount](akashaproject_design_system._internal_.default.md#componentwillunmount)
- [componentWillUpdate](akashaproject_design_system._internal_.default.md#componentwillupdate)
- [forceUpdate](akashaproject_design_system._internal_.default.md#forceupdate)
- [getSnapshotBeforeUpdate](akashaproject_design_system._internal_.default.md#getsnapshotbeforeupdate)
- [render](akashaproject_design_system._internal_.default.md#render)
- [setState](akashaproject_design_system._internal_.default.md#setstate)
- [shouldComponentUpdate](akashaproject_design_system._internal_.default.md#shouldcomponentupdate)

## Constructors

### constructor

• **new default**(`props`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md) \| [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[constructor](akashaproject_design_system._internal_.Component.md#constructor)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:475

• **new default**(`props`, `context`)

**`deprecated`**

**`see`** https://reactjs.org/docs/legacy-context.html

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md) |
| `context` | `any` |

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[constructor](akashaproject_design_system._internal_.Component.md#constructor)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:480

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

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[context](akashaproject_design_system._internal_.Component.md#context)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:473

___

### props

• `Readonly` **props**: [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> & [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{ `children?`: [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)  }\>

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[props](akashaproject_design_system._internal_.Component.md#props)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:498

___

### refs

• **refs**: `Object`

**`deprecated`**
https://reactjs.org/docs/refs-and-the-dom.html#legacy-api-string-refs

#### Index signature

▪ [key: `string`]: [`ReactInstance`](../modules/akashaproject_design_system._internal_.md#reactinstance)

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[refs](akashaproject_design_system._internal_.Component.md#refs)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:504

___

### state

• **state**: [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\>

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[state](akashaproject_design_system._internal_.Component.md#state)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:499

___

### contextType

▪ `Static` `Optional` **contextType**: [`Context`](../interfaces/akashaproject_design_system._internal_.Context.md)<`any`\>

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

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[contextType](akashaproject_design_system._internal_.Component.md#contexttype)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:455

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

[Component](akashaproject_design_system._internal_.Component.md).[UNSAFE_componentWillMount](akashaproject_design_system._internal_.Component.md#unsafe_componentwillmount)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:711

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
| `nextProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[UNSAFE_componentWillReceiveProps](akashaproject_design_system._internal_.Component.md#unsafe_componentwillreceiveprops)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:743

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
| `nextProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `nextState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[UNSAFE_componentWillUpdate](akashaproject_design_system._internal_.Component.md#unsafe_componentwillupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:771

___

### componentDidCatch

▸ `Optional` **componentDidCatch**(`error`, `errorInfo`): `void`

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | [`Error`](../modules/akashaproject_design_system._internal_.md#error) |
| `errorInfo` | [`ErrorInfo`](../interfaces/akashaproject_design_system._internal_.ErrorInfo.md) |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentDidCatch](akashaproject_design_system._internal_.Component.md#componentdidcatch)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:640

___

### componentDidMount

▸ `Optional` **componentDidMount**(): `void`

Called immediately after a component is mounted. Setting state here will trigger re-rendering.

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentDidMount](akashaproject_design_system._internal_.Component.md#componentdidmount)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:619

___

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `snapshot?`): `void`

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `prevState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\> |
| `snapshot?` | `any` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentDidUpdate](akashaproject_design_system._internal_.Component.md#componentdidupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:682

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

[Component](akashaproject_design_system._internal_.Component.md).[componentWillMount](akashaproject_design_system._internal_.Component.md#componentwillmount)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:697

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
| `nextProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentWillReceiveProps](akashaproject_design_system._internal_.Component.md#componentwillreceiveprops)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:726

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentWillUnmount](akashaproject_design_system._internal_.Component.md#componentwillunmount)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:635

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
| `nextProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `nextState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[componentWillUpdate](akashaproject_design_system._internal_.Component.md#componentwillupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:756

___

### forceUpdate

▸ **forceUpdate**(`callback?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback?` | () => `void` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[forceUpdate](akashaproject_design_system._internal_.Component.md#forceupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:490

___

### getSnapshotBeforeUpdate

▸ `Optional` **getSnapshotBeforeUpdate**(`prevProps`, `prevState`): `any`

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `prevState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\> |

#### Returns

`any`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[getSnapshotBeforeUpdate](akashaproject_design_system._internal_.Component.md#getsnapshotbeforeupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:676

___

### render

▸ **render**(): [`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Returns

[`ReactNode`](../modules/akashaproject_design_system._internal_.md#reactnode)

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[render](akashaproject_design_system._internal_.Component.md#render)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:491

___

### setState

▸ **setState**<`K`\>(`state`, `callback?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends `never` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | {} \| (`prevState`: [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\>, `props`: [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\>) => {} \| [`Pick`](../modules/akashaproject_design_system._internal_.md#pick)<{}, `K`\> \| [`Pick`](../modules/akashaproject_design_system._internal_.md#pick)<{}, `K`\> |
| `callback?` | () => `void` |

#### Returns

`void`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[setState](akashaproject_design_system._internal_.Component.md#setstate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:485

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
| `nextProps` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<[`AutoSizerProps`](../interfaces/akashaproject_design_system._internal_.AutoSizerProps.md)\> |
| `nextState` | [`Readonly`](../modules/akashaproject_design_system._internal_.md#readonly)<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

[Component](akashaproject_design_system._internal_.Component.md).[shouldComponentUpdate](akashaproject_design_system._internal_.Component.md#shouldcomponentupdate)

#### Defined in

ui/design/node_modules/@types/react/index.d.ts:630
