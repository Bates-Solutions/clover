[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / parseWebhookEvent

# Function: parseWebhookEvent()

> **parseWebhookEvent**(`rawBody`): [`WebhookEvent`](../interfaces/WebhookEvent.md)

Defined in: [server/webhook.ts:136](https://github.com/Bates-Solutions/clover/blob/40568e0a95019adb2af4cb858720aefc035388af/src/server/webhook.ts#L136)

Parse a webhook request body into an event.

## Parameters

### rawBody

`string`

## Returns

[`WebhookEvent`](../interfaces/WebhookEvent.md)

## Throws

Error if the payload is not valid JSON
