[**@bates-solutions/clover API Reference v1.0.4**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / parseCloverError

# Function: parseCloverError()

> **parseCloverError**(`error`): [`CloverError`](../classes/CloverError.md)

Defined in: [core/errors.ts:203](https://github.com/Bates-Solutions/clover/blob/6c43fd8b921349fda8f7a4741fd607329f81f3cc/src/core/errors.ts#L203)

Parse any thrown value into a typed Clover error.

Passes through errors this library already produced (including those thrown
by the HTTP client) and wraps everything else — e.g. a `fetch` network
failure — as a base [CloverError](../classes/CloverError.md).

## Parameters

### error

`unknown`

## Returns

[`CloverError`](../classes/CloverError.md)
