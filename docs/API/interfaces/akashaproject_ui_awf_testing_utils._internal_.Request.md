[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / Request

# Interface: Request

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).Request

This Fetch API interface represents a resource request.

## Hierarchy

- [`Body`](akashaproject_ui_awf_testing_utils._internal_.Body.md)

  ↳ **`Request`**

## Table of contents

### Properties

- [body](akashaproject_ui_awf_testing_utils._internal_.Request.md#body)
- [bodyUsed](akashaproject_ui_awf_testing_utils._internal_.Request.md#bodyused)
- [cache](akashaproject_ui_awf_testing_utils._internal_.Request.md#cache)
- [credentials](akashaproject_ui_awf_testing_utils._internal_.Request.md#credentials)
- [destination](akashaproject_ui_awf_testing_utils._internal_.Request.md#destination)
- [headers](akashaproject_ui_awf_testing_utils._internal_.Request.md#headers)
- [integrity](akashaproject_ui_awf_testing_utils._internal_.Request.md#integrity)
- [keepalive](akashaproject_ui_awf_testing_utils._internal_.Request.md#keepalive)
- [method](akashaproject_ui_awf_testing_utils._internal_.Request.md#method)
- [mode](akashaproject_ui_awf_testing_utils._internal_.Request.md#mode)
- [redirect](akashaproject_ui_awf_testing_utils._internal_.Request.md#redirect)
- [referrer](akashaproject_ui_awf_testing_utils._internal_.Request.md#referrer)
- [referrerPolicy](akashaproject_ui_awf_testing_utils._internal_.Request.md#referrerpolicy)
- [signal](akashaproject_ui_awf_testing_utils._internal_.Request.md#signal)
- [url](akashaproject_ui_awf_testing_utils._internal_.Request.md#url)

### Methods

- [arrayBuffer](akashaproject_ui_awf_testing_utils._internal_.Request.md#arraybuffer)
- [blob](akashaproject_ui_awf_testing_utils._internal_.Request.md#blob)
- [clone](akashaproject_ui_awf_testing_utils._internal_.Request.md#clone)
- [formData](akashaproject_ui_awf_testing_utils._internal_.Request.md#formdata)
- [json](akashaproject_ui_awf_testing_utils._internal_.Request.md#json)
- [text](akashaproject_ui_awf_testing_utils._internal_.Request.md#text)

## Properties

### body

• `Readonly` **body**: [`ReadableStream`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#readablestream)<`Uint8Array`\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[body](akashaproject_ui_awf_testing_utils._internal_.Body.md#body)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2444

___

### bodyUsed

• `Readonly` **bodyUsed**: `boolean`

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[bodyUsed](akashaproject_ui_awf_testing_utils._internal_.Body.md#bodyused)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2445

___

### cache

• `Readonly` **cache**: [`RequestCache`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestcache)

Returns the cache mode associated with request, which is a string indicating how the request will interact with the browser's cache when fetching.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12051

___

### credentials

• `Readonly` **credentials**: [`RequestCredentials`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestcredentials)

Returns the credentials mode associated with request, which is a string indicating whether credentials will be sent with the request always, never, or only when sent to a same-origin URL.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12055

___

### destination

• `Readonly` **destination**: [`RequestDestination`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestdestination)

Returns the kind of resource requested by request, e.g., "document" or "script".

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12059

___

### headers

• `Readonly` **headers**: [`Headers`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#headers)

Returns a Headers object consisting of the headers associated with request. Note that headers added in the network layer by the user agent will not be accounted for in this object, e.g., the "Host" header.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12063

___

### integrity

• `Readonly` **integrity**: `string`

Returns request's subresource integrity metadata, which is a cryptographic hash of the resource being fetched. Its value consists of multiple hashes separated by whitespace. [SRI]

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12067

___

### keepalive

• `Readonly` **keepalive**: `boolean`

Returns a boolean indicating whether or not request can outlive the global in which it was created.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12071

___

### method

• `Readonly` **method**: `string`

Returns request's HTTP method, which is "GET" by default.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12075

___

### mode

• `Readonly` **mode**: [`RequestMode`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestmode)

Returns the mode associated with request, which is a string indicating whether the request will use CORS, or will be restricted to same-origin URLs.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12079

___

### redirect

• `Readonly` **redirect**: [`RequestRedirect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestredirect)

Returns the redirect mode associated with request, which is a string indicating how redirects for the request will be handled during fetching. A request will follow redirects by default.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12083

___

### referrer

• `Readonly` **referrer**: `string`

Returns the referrer of request. Its value can be a same-origin URL if explicitly set in init, the empty string to indicate no referrer, and "about:client" when defaulting to the global's default. This is used during fetching to determine the value of the `Referer` header of the request being made.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12087

___

### referrerPolicy

• `Readonly` **referrerPolicy**: [`ReferrerPolicy`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#referrerpolicy)

Returns the referrer policy associated with request. This is used during fetching to compute the value of the request's referrer.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12091

___

### signal

• `Readonly` **signal**: `AbortSignal`

Returns the signal associated with request, which is an AbortSignal object indicating whether or not request has been aborted, and its abort event handler.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12095

___

### url

• `Readonly` **url**: `string`

Returns the URL of request as a string.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12099

## Methods

### arrayBuffer

▸ **arrayBuffer**(): `Promise`<`ArrayBuffer`\>

#### Returns

`Promise`<`ArrayBuffer`\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[arrayBuffer](akashaproject_ui_awf_testing_utils._internal_.Body.md#arraybuffer)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2446

___

### blob

▸ **blob**(): `Promise`<`Blob`\>

#### Returns

`Promise`<`Blob`\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[blob](akashaproject_ui_awf_testing_utils._internal_.Body.md#blob)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2447

___

### clone

▸ **clone**(): [`Request`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#request)

#### Returns

[`Request`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#request)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:12100

___

### formData

▸ **formData**(): `Promise`<[`FormData`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#formdata)\>

#### Returns

`Promise`<[`FormData`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#formdata)\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[formData](akashaproject_ui_awf_testing_utils._internal_.Body.md#formdata)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2448

___

### json

▸ **json**(): `Promise`<`any`\>

#### Returns

`Promise`<`any`\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[json](akashaproject_ui_awf_testing_utils._internal_.Body.md#json)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2449

___

### text

▸ **text**(): `Promise`<`string`\>

#### Returns

`Promise`<`string`\>

#### Inherited from

[Body](akashaproject_ui_awf_testing_utils._internal_.Body.md).[text](akashaproject_ui_awf_testing_utils._internal_.Body.md#text)

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:2450
