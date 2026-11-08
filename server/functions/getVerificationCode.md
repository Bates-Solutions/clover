[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / getVerificationCode

# Function: getVerificationCode()

> **getVerificationCode**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:150](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/server/webhook.ts#L150)

The verification code Clover sends when first validating a webhook URL.

Clover POSTs `{ "verificationCode": "..." }` (with no signature) to confirm
the endpoint; respond `200` to complete setup.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

## Returns

`string` \| `undefined`
