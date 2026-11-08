[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CloverClientConfig

# Interface: CloverClientConfig

Defined in: [core/client.ts:11](https://github.com/Bates-Solutions/clover/blob/181205b4567df95fcdb4571f6793b7967773cadb/src/core/client.ts#L11)

Configuration options for the Clover client.

## Properties

### apiToken

> **apiToken**: `string`

Defined in: [core/client.ts:13](https://github.com/Bates-Solutions/clover/blob/181205b4567df95fcdb4571f6793b7967773cadb/src/core/client.ts#L13)

Clover API token (OAuth access token or API key)

***

### environment?

> `optional` **environment?**: [`CloverEnvironment`](../type-aliases/CloverEnvironment.md)

Defined in: [core/client.ts:23](https://github.com/Bates-Solutions/clover/blob/181205b4567df95fcdb4571f6793b7967773cadb/src/core/client.ts#L23)

Environment.

#### Default

```ts
'sandbox'
```

***

### fetchImpl?

> `optional` **fetchImpl?**: \{(`input`, `init?`): `Promise`\<`Response`\>; (`input`, `init?`): `Promise`\<`Response`\>; \}

Defined in: [core/client.ts:25](https://github.com/Bates-Solutions/clover/blob/181205b4567df95fcdb4571f6793b7967773cadb/src/core/client.ts#L25)

Override the `fetch` implementation (mainly for tests).

#### Call Signature

> (`input`, `init?`): `Promise`\<`Response`\>

[MDN Reference](https://developer.mozilla.org/docs/Web/API/Window/fetch)

##### Parameters

###### input

`URL` \| `RequestInfo`

###### init?

`RequestInit`

##### Returns

`Promise`\<`Response`\>

#### Call Signature

> (`input`, `init?`): `Promise`\<`Response`\>

[MDN Reference](https://developer.mozilla.org/docs/Web/API/Window/fetch)

##### Parameters

###### input

`string` \| `URL` \| `Request`

###### init?

`RequestInit`

##### Returns

`Promise`\<`Response`\>

***

### merchantId?

> `optional` **merchantId?**: `string`

Defined in: [core/client.ts:18](https://github.com/Bates-Solutions/clover/blob/181205b4567df95fcdb4571f6793b7967773cadb/src/core/client.ts#L18)

Merchant id. Required for platform (`/v3/merchants/{mId}`) operations such
as `customers` and `inventory`; not needed for Ecommerce charges/refunds.
