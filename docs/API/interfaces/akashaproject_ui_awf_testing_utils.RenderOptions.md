[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / RenderOptions

# Interface: RenderOptions<Q, Container\>

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).RenderOptions

## Type parameters

| Name | Type |
| :------ | :------ |
| `Q` | extends [`Queries`](akashaproject_ui_awf_testing_utils.Queries.md) = typeof [`queries`](../modules/akashaproject_ui_awf_testing_utils.queries.md) |
| `Container` | extends `Element` \| `DocumentFragment` = `HTMLElement` |

## Table of contents

### Properties

- [baseElement](akashaproject_ui_awf_testing_utils.RenderOptions.md#baseelement)
- [container](akashaproject_ui_awf_testing_utils.RenderOptions.md#container)
- [hydrate](akashaproject_ui_awf_testing_utils.RenderOptions.md#hydrate)
- [queries](akashaproject_ui_awf_testing_utils.RenderOptions.md#queries)
- [wrapper](akashaproject_ui_awf_testing_utils.RenderOptions.md#wrapper)

## Properties

### baseElement

• `Optional` **baseElement**: `Element`

Defaults to the container if the container is specified. Otherwise `document.body` is used for the default. This is used as
 the base element for the queries as well as what is printed when you use `debug()`.

**`see`** https://testing-library.com/docs/react-testing-library/api/#baseelement

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:53

___

### container

• `Optional` **container**: `Container`

By default, React Testing Library will create a div and append that div to the document.body. Your React component will be rendered in the created div. If you provide your own HTMLElement container via this option,
 it will not be appended to the document.body automatically.

 For example: If you are unit testing a `<tbody>` element, it cannot be a child of a div. In this case, you can
 specify a table as the render container.

**`see`** https://testing-library.com/docs/react-testing-library/api/#container

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:46

___

### hydrate

• `Optional` **hydrate**: `boolean`

If `hydrate` is set to `true`, then it will render with `ReactDOM.hydrate`. This may be useful if you are using server-side
 rendering and use ReactDOM.hydrate to mount your components.

**`see`** https://testing-library.com/docs/react-testing-library/api/#hydrate)

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:60

___

### queries

• `Optional` **queries**: `Q`

Queries to bind. Overrides the default set from DOM Testing Library unless merged.

**`see`** https://testing-library.com/docs/react-testing-library/api/#queries

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:66

___

### wrapper

• `Optional` **wrapper**: [`ComponentType`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#componenttype)<{}\>

Pass a React Component as the wrapper option to have it rendered around the inner element. This is most useful for creating
 reusable custom render functions for common data providers. See setup for examples.

**`see`** https://testing-library.com/docs/react-testing-library/api/#wrapper

#### Defined in

node_modules/@testing-library/react/types/index.d.ts:73
