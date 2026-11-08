[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / createCloverOAuthClient

# Function: createCloverOAuthClient()

> **createCloverOAuthClient**(`config`): [`CloverOAuthClient`](../classes/CloverOAuthClient.md)

Defined in: [core/oauth.ts:248](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/oauth.ts#L248)

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
