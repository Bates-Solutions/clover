[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / BuildAuthorizeUrlOptions

# Interface: BuildAuthorizeUrlOptions

Defined in: [core/oauth.ts:18](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L18)

Options for [buildAuthorizeUrl](../functions/buildAuthorizeUrl.md)

## Properties

### clientId

> **clientId**: `string`

Defined in: [core/oauth.ts:20](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L20)

App ID from the Clover Developer Dashboard

***

### environment?

> `optional` **environment?**: [`CloverEnvironment`](../type-aliases/CloverEnvironment.md)

Defined in: [core/oauth.ts:26](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L26)

Selects the authorize host: `www.clover.com` (production) or
`sandbox.dev.clover.com` (sandbox).

#### Default

```ts
'sandbox'
```

***

### redirectUri?

> `optional` **redirectUri?**: `string`

Defined in: [core/oauth.ts:37](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L37)

Where Clover sends the merchant back. Must be on the site URL configured
for the app; when omitted Clover uses that site URL.

***

### state

> **state**: `string`

Defined in: [core/oauth.ts:32](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L32)

Unguessable CSRF token, returned unchanged on the redirect. Verify it in
your callback before exchanging the code. You can also use it to carry
which tenant started the flow.
