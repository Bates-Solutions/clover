[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CloverHttp

# Class: CloverHttp

Defined in: [core/http.ts:53](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/http.ts#L53)

A small typed `fetch`-based HTTP client for the Clover Ecommerce and Platform
APIs. No SDK dependency; runs anywhere `fetch` and WebCrypto exist.

Non-2xx responses are thrown as typed errors (see cloverErrorFromResponse).

## Constructors

### Constructor

> **new CloverHttp**(`config`): `CloverHttp`

Defined in: [core/http.ts:56](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/http.ts#L56)

#### Parameters

##### config

[`CloverHttpConfig`](../interfaces/CloverHttpConfig.md)

#### Returns

`CloverHttp`

## Accessors

### merchantId

#### Get Signature

> **get** **merchantId**(): `string` \| `undefined`

Defined in: [core/http.ts:62](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/http.ts#L62)

The configured merchant id, if any.

##### Returns

`string` \| `undefined`

## Methods

### request()

> **request**\<`T`\>(`host`, `method`, `path`, `options?`): `Promise`\<`T`\>

Defined in: [core/http.ts:75](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/http.ts#L75)

Perform a request and return the parsed JSON body.

#### Type Parameters

##### T

`T`

#### Parameters

##### host

[`CloverHost`](../type-aliases/CloverHost.md)

##### method

`"GET"` \| `"POST"` \| `"PUT"` \| `"DELETE"`

##### path

`string`

##### options?

[`RequestOptions`](../interfaces/RequestOptions.md) = `{}`

#### Returns

`Promise`\<`T`\>

#### Throws

On a non-2xx response or a network failure.
