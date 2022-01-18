[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/design-system](../modules/akashaproject_design_system.md) / [<internal\>](../modules/akashaproject_design_system._internal_.md) / DocumentOrShadowRoot

# Interface: DocumentOrShadowRoot

[@akashaproject/design-system](../modules/akashaproject_design_system.md).[<internal>](../modules/akashaproject_design_system._internal_.md).DocumentOrShadowRoot

## Hierarchy

- **`DocumentOrShadowRoot`**

  ↳ [`ShadowRoot`](akashaproject_design_system._internal_.ShadowRoot.md)

## Table of contents

### Properties

- [activeElement](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#activeelement)
- [fullscreenElement](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#fullscreenelement)
- [pictureInPictureElement](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#pictureinpictureelement)
- [pointerLockElement](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#pointerlockelement)
- [styleSheets](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#stylesheets)

### Methods

- [getAnimations](akashaproject_design_system._internal_.DocumentOrShadowRoot.md#getanimations)

## Properties

### activeElement

• `Readonly` **activeElement**: `Element`

Returns the deepest element in the document through which or to which key events are being routed. This is, roughly speaking, the focused element in the document.

For the purposes of this API, when a child browsing context is focused, its container is focused in the parent browsing context. For example, if the user moves the focus to a text control in an iframe, the iframe is the element returned by the activeElement API in the iframe's node document.

Similarly, when the focused element is in a different node tree than documentOrShadowRoot, the element returned will be the host that's located in the same node tree as documentOrShadowRoot if documentOrShadowRoot is a shadow-including inclusive ancestor of the focused element, and null if not.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4758

___

### fullscreenElement

• `Readonly` **fullscreenElement**: `Element`

Returns document's fullscreen element.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4762

___

### pictureInPictureElement

• `Readonly` **pictureInPictureElement**: `Element`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4763

___

### pointerLockElement

• `Readonly` **pointerLockElement**: `Element`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4764

___

### styleSheets

• `Readonly` **styleSheets**: [`StyleSheetList`](../modules/akashaproject_design_system._internal_.md#stylesheetlist)

Retrieves a collection of styleSheet objects representing the style sheets that correspond to each instance of a link or style object in the document.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4768

## Methods

### getAnimations

▸ **getAnimations**(): [`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Returns

[`Animation`](../modules/akashaproject_design_system._internal_.md#animation)[]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:4769
