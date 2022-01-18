[AWF](../README.md) / [Modules](../modules.md) / [@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md) / [<internal\>](../modules/akashaproject_awf_sdk._internal_.md) / CallSite

# Interface: CallSite

[@akashaproject/awf-sdk](../modules/akashaproject_awf_sdk.md).[<internal>](../modules/akashaproject_awf_sdk._internal_.md).CallSite

## Table of contents

### Methods

- [getColumnNumber](akashaproject_awf_sdk._internal_.CallSite.md#getcolumnnumber)
- [getEvalOrigin](akashaproject_awf_sdk._internal_.CallSite.md#getevalorigin)
- [getFileName](akashaproject_awf_sdk._internal_.CallSite.md#getfilename)
- [getFunction](akashaproject_awf_sdk._internal_.CallSite.md#getfunction)
- [getFunctionName](akashaproject_awf_sdk._internal_.CallSite.md#getfunctionname)
- [getLineNumber](akashaproject_awf_sdk._internal_.CallSite.md#getlinenumber)
- [getMethodName](akashaproject_awf_sdk._internal_.CallSite.md#getmethodname)
- [getThis](akashaproject_awf_sdk._internal_.CallSite.md#getthis)
- [getTypeName](akashaproject_awf_sdk._internal_.CallSite.md#gettypename)
- [isConstructor](akashaproject_awf_sdk._internal_.CallSite.md#isconstructor)
- [isEval](akashaproject_awf_sdk._internal_.CallSite.md#iseval)
- [isNative](akashaproject_awf_sdk._internal_.CallSite.md#isnative)
- [isToplevel](akashaproject_awf_sdk._internal_.CallSite.md#istoplevel)

## Methods

### getColumnNumber

▸ **getColumnNumber**(): `number`

Current column number [if this function was defined in a script]

#### Returns

`number`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:154

___

### getEvalOrigin

▸ **getEvalOrigin**(): `string`

A call site object representing the location where eval was called
[if this function was created using a call to eval]

#### Returns

`string`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:160

___

### getFileName

▸ **getFileName**(): `string`

Name of the script [if this function was defined in a script]

#### Returns

`string`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:144

___

### getFunction

▸ **getFunction**(): `Function`

Current function

#### Returns

`Function`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:126

___

### getFunctionName

▸ **getFunctionName**(): `string`

Name of the current function, typically its name property.
If a name property is not available an attempt will be made to try
to infer a name from the function's context.

#### Returns

`string`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:133

___

### getLineNumber

▸ **getLineNumber**(): `number`

Current line number [if this function was defined in a script]

#### Returns

`number`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:149

___

### getMethodName

▸ **getMethodName**(): `string`

Name of the property [of "this" or one of its prototypes] that holds
the current function

#### Returns

`string`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:139

___

### getThis

▸ **getThis**(): `unknown`

Value of "this"

#### Returns

`unknown`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:113

___

### getTypeName

▸ **getTypeName**(): `string`

Type of "this" as a string.
This is the name of the function stored in the constructor field of
"this", if available.  Otherwise the object's [[Class]] internal
property.

#### Returns

`string`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:121

___

### isConstructor

▸ **isConstructor**(): `boolean`

Is this a constructor call?

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:180

___

### isEval

▸ **isEval**(): `boolean`

Does this call take place in code defined by a call to eval?

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:170

___

### isNative

▸ **isNative**(): `boolean`

Is this call in native V8 code?

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:175

___

### isToplevel

▸ **isToplevel**(): `boolean`

Is this a toplevel invocation, that is, is "this" the global object?

#### Returns

`boolean`

#### Defined in

sdk/node_modules/@types/node/globals.d.ts:165
