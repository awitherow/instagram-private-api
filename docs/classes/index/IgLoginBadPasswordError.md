[instagram-private-api](../../README.md) / [index](../../modules/index.md) / IgLoginBadPasswordError

# Class: IgLoginBadPasswordError

[index](../../modules/index.md).IgLoginBadPasswordError

## Hierarchy

- [`IgResponseError`](IgResponseError.md)<[`AccountRepositoryLoginErrorResponse`](../../interfaces/index/AccountRepositoryLoginErrorResponse.md)\>

  ↳ **`IgLoginBadPasswordError`**

## Table of contents

### Constructors

- [constructor](IgLoginBadPasswordError.md#constructor)

### Properties

- [message](IgLoginBadPasswordError.md#message)
- [name](IgLoginBadPasswordError.md#name)
- [response](IgLoginBadPasswordError.md#response)
- [stack](IgLoginBadPasswordError.md#stack)
- [text](IgLoginBadPasswordError.md#text)
- [stackTraceLimit](IgLoginBadPasswordError.md#stacktracelimit)

### Methods

- [captureStackTrace](IgLoginBadPasswordError.md#capturestacktrace)
- [prepareStackTrace](IgLoginBadPasswordError.md#preparestacktrace)

## Constructors

### constructor

• **new IgLoginBadPasswordError**(`response`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | [`IgResponse`](../../modules/index.md#igresponse)<[`AccountRepositoryLoginErrorResponse`](../../interfaces/index/AccountRepositoryLoginErrorResponse.md)\> |

#### Inherited from

[IgResponseError](IgResponseError.md).[constructor](IgResponseError.md#constructor)

#### Defined in

[src/errors/ig-response.error.ts:11](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/errors/ig-response.error.ts#L11)

## Properties

### message

• **message**: `string`

#### Inherited from

[IgResponseError](IgResponseError.md).[message](IgResponseError.md#message)

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:974

___

### name

• **name**: `string`

#### Inherited from

[IgResponseError](IgResponseError.md).[name](IgResponseError.md#name)

#### Defined in

node_modules/ts-custom-error/dist/custom-error.d.ts:2

___

### response

• **response**: [`IgResponse`](../../modules/index.md#igresponse)<[`AccountRepositoryLoginErrorResponse`](../../interfaces/index/AccountRepositoryLoginErrorResponse.md)\>

#### Inherited from

[IgResponseError](IgResponseError.md).[response](IgResponseError.md#response)

#### Defined in

[src/errors/ig-response.error.ts:9](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/errors/ig-response.error.ts#L9)

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

[IgResponseError](IgResponseError.md).[stack](IgResponseError.md#stack)

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:975

___

### text

• **text**: `string`

#### Inherited from

[IgResponseError](IgResponseError.md).[text](IgResponseError.md#text)

#### Defined in

[src/errors/ig-response.error.ts:7](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/errors/ig-response.error.ts#L7)

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

[IgResponseError](IgResponseError.md).[stackTraceLimit](IgResponseError.md#stacktracelimit)

#### Defined in

node_modules/@types/node/globals.d.ts:142

## Methods

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `Object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

[IgResponseError](IgResponseError.md).[captureStackTrace](IgResponseError.md#capturestacktrace)

#### Defined in

node_modules/@types/node/globals.d.ts:133

___

### prepareStackTrace

▸ `Static` `Optional` **prepareStackTrace**(`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`see`** https://github.com/v8/v8/wiki/Stack%20Trace%20API#customizing-stack-traces

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

#### Returns

`any`

#### Inherited from

[IgResponseError](IgResponseError.md).[prepareStackTrace](IgResponseError.md#preparestacktrace)

#### Defined in

node_modules/@types/node/globals.d.ts:140
