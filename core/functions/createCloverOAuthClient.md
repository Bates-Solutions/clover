[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / createCloverOAuthClient

# Function: createCloverOAuthClient()

> **createCloverOAuthClient**(`config`): [`CloverOAuthClient`](../classes/CloverOAuthClient.md)

Defined in: [core/oauth.ts:248](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/core/oauth.ts#L248)

Create an OAuth client for the app-credential endpoints.

## Parameters

### config

[`CloverOAuthClientConfig`](../interfaces/CloverOAuthClientConfig.md)

## Returns

[`CloverOAuthClient`](../classes/CloverOAuthClient.md)

## Example

```typescript
const oauth = createCloverOAuthClient({
  clientId: process.env.CLOVER_APP_ID!,
  clientSecret: process.env.CLOVER_APP_SECRET!,
  environment: 'production',
});
```
