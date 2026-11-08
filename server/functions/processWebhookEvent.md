[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / processWebhookEvent

# Function: processWebhookEvent()

> **processWebhookEvent**(`event`, `config`): `Promise`\<`void`\>

Defined in: [server/webhook.ts:177](https://github.com/Bates-Solutions/clover/blob/40568e0a95019adb2af4cb858720aefc035388af/src/server/webhook.ts#L177)

Dispatch an event to the handler registered for its `type`.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

### config

[`WebhookConfig`](../interfaces/WebhookConfig.md)

## Returns

`Promise`\<`void`\>
