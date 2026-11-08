[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / processWebhookEvent

# Function: processWebhookEvent()

> **processWebhookEvent**(`event`, `config`): `Promise`\<`void`\>

Defined in: [server/webhook.ts:177](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/server/webhook.ts#L177)

Dispatch an event to the handler registered for its `type`.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

### config

[`WebhookConfig`](../interfaces/WebhookConfig.md)

## Returns

`Promise`\<`void`\>
