[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / parseWebhookEvent

# Function: parseWebhookEvent()

> **parseWebhookEvent**(`rawBody`): [`WebhookEvent`](../interfaces/WebhookEvent.md)

Defined in: [server/webhook.ts:136](https://github.com/Bates-Solutions/clover/blob/186c4d6bc05073aef1987a8e63dfb83e16bf2c21/src/server/webhook.ts#L136)

Parse a webhook request body into an event.

## Parameters

### rawBody

`string`

## Returns

[`WebhookEvent`](../interfaces/WebhookEvent.md)

## Throws

Error if the payload is not valid JSON
