[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md) / [<internal\>](../modules/akashaproject_ui_awf_testing_utils._internal_.md) / RequestInit

# Interface: RequestInit

[@akashaproject/ui-awf-testing-utils](../modules/akashaproject_ui_awf_testing_utils.md).[<internal>](../modules/akashaproject_ui_awf_testing_utils._internal_.md).RequestInit

## Table of contents

### Properties

- [body](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#body)
- [cache](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#cache)
- [credentials](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#credentials)
- [headers](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#headers)
- [integrity](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#integrity)
- [keepalive](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#keepalive)
- [method](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#method)
- [mode](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#mode)
- [redirect](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#redirect)
- [referrer](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#referrer)
- [referrerPolicy](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#referrerpolicy)
- [signal](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#signal)
- [window](akashaproject_ui_awf_testing_utils._internal_.RequestInit.md#window)

## Properties

### body

• `Optional` **body**: [`BodyInit`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#bodyinit)

A BodyInit object or null to set request's body.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1481

___

### cache

• `Optional` **cache**: [`RequestCache`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestcache)

A string indicating how the request will interact with the browser's cache to set request's cache.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1485

___

### credentials

• `Optional` **credentials**: [`RequestCredentials`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestcredentials)

A string indicating whether credentials will be sent with the request always, never, or only when sent to a same-origin URL. Sets request's credentials.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1489

___

### headers

• `Optional` **headers**: [`HeadersInit`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#headersinit)

A Headers object, an object literal, or an array of two-item arrays to set request's headers.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1493

___

### integrity

• `Optional` **integrity**: `string`

A cryptographic hash of the resource to be fetched by request. Sets request's integrity.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1497

___

### keepalive

• `Optional` **keepalive**: `boolean`

A boolean to set request's keepalive.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1501

___

### method

• `Optional` **method**: `string`

A string to set request's method.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1505

___

### mode

• `Optional` **mode**: [`RequestMode`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestmode)

A string to indicate whether the request will use CORS, or will be restricted to same-origin URLs. Sets request's mode.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1509

___

### redirect

• `Optional` **redirect**: [`RequestRedirect`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#requestredirect)

A string indicating whether request follows redirects, results in an error upon encountering a redirect, or returns the redirect (in an opaque fashion). Sets request's redirect.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1513

___

### referrer

• `Optional` **referrer**: `string`

A string whose value is a same-origin URL, "about:client", or the empty string, to set request's referrer.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1517

___

### referrerPolicy

• `Optional` **referrerPolicy**: [`ReferrerPolicy`](../modules/akashaproject_ui_awf_testing_utils._internal_.md#referrerpolicy)

A referrer policy to set request's referrerPolicy.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1521

___

### signal

• `Optional` **signal**: `AbortSignal`

An AbortSignal to set request's signal.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1525

___

### window

• `Optional` **window**: `any`

Can only be null. Used to disassociate request from any Window.

#### Defined in

node_modules/typescript/lib/lib.dom.d.ts:1529
