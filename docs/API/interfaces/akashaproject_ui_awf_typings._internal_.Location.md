[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md) / [<internal\>](../modules/akashaproject_ui_awf_typings._internal_.md) / Location

# Interface: Location

[@akashaproject/ui-awf-typings](../modules/akashaproject_ui_awf_typings.md).[<internal>](../modules/akashaproject_ui_awf_typings._internal_.md).Location

The location (URL) of the object it is linked to. Changes done on it are reflected on the object it relates to. Both the Document and Window interface have such a linked Location, accessible via Document.location and Window.location respectively.

## Table of contents

### Properties

- [ancestorOrigins](akashaproject_ui_awf_typings._internal_.Location.md#ancestororigins)
- [hash](akashaproject_ui_awf_typings._internal_.Location.md#hash)
- [host](akashaproject_ui_awf_typings._internal_.Location.md#host)
- [hostname](akashaproject_ui_awf_typings._internal_.Location.md#hostname)
- [href](akashaproject_ui_awf_typings._internal_.Location.md#href)
- [origin](akashaproject_ui_awf_typings._internal_.Location.md#origin)
- [pathname](akashaproject_ui_awf_typings._internal_.Location.md#pathname)
- [port](akashaproject_ui_awf_typings._internal_.Location.md#port)
- [protocol](akashaproject_ui_awf_typings._internal_.Location.md#protocol)
- [search](akashaproject_ui_awf_typings._internal_.Location.md#search)

### Methods

- [assign](akashaproject_ui_awf_typings._internal_.Location.md#assign)
- [reload](akashaproject_ui_awf_typings._internal_.Location.md#reload)
- [replace](akashaproject_ui_awf_typings._internal_.Location.md#replace)
- [toString](akashaproject_ui_awf_typings._internal_.Location.md#tostring)

## Properties

### ancestorOrigins

• `Readonly` **ancestorOrigins**: [`DOMStringList`](../modules/akashaproject_ui_awf_typings._internal_.md#domstringlist)

Returns a DOMStringList object listing the origins of the ancestor browsing contexts, from the parent browsing context to the top-level browsing context.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9615

___

### hash

• **hash**: `string`

Returns the Location object's URL's fragment (includes leading "#" if non-empty).

Can be set, to navigate to the same URL with a changed fragment (ignores leading "#").

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9621

___

### host

• **host**: `string`

Returns the Location object's URL's host and port (if different from the default port for the scheme).

Can be set, to navigate to the same URL with a changed host and port.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9627

___

### hostname

• **hostname**: `string`

Returns the Location object's URL's host.

Can be set, to navigate to the same URL with a changed host.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9633

___

### href

• **href**: `string`

Returns the Location object's URL.

Can be set, to navigate to the given URL.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9639

___

### origin

• `Readonly` **origin**: `string`

Returns the Location object's URL's origin.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9644

___

### pathname

• **pathname**: `string`

Returns the Location object's URL's path.

Can be set, to navigate to the same URL with a changed path.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9650

___

### port

• **port**: `string`

Returns the Location object's URL's port.

Can be set, to navigate to the same URL with a changed port.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9656

___

### protocol

• **protocol**: `string`

Returns the Location object's URL's scheme.

Can be set, to navigate to the same URL with a changed scheme.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9662

___

### search

• **search**: `string`

Returns the Location object's URL's query (includes leading "?" if non-empty).

Can be set, to navigate to the same URL with a changed query (ignores leading "?").

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9668

## Methods

### assign

▸ **assign**(`url`): `void`

Navigates to the given URL.

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` \| [`URL`](../modules/akashaproject_ui_awf_typings._internal_.md#url) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9672

___

### reload

▸ **reload**(): `void`

Reloads the current page.

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9676

___

### replace

▸ **replace**(`url`): `void`

Removes the current page from the session history and navigates to the given URL.

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` \| [`URL`](../modules/akashaproject_ui_awf_typings._internal_.md#url) |

#### Returns

`void`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9680

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:9640
