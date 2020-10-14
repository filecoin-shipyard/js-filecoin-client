---
id: filecoin.js.jsonrpcprovider.syncincomingblocks
title: JsonRpcProvider.syncIncomingBlocks() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [syncIncomingBlocks](./filecoin.js.jsonrpcprovider.syncincomingblocks.md)

## JsonRpcProvider.syncIncomingBlocks() method

returns a channel streaming incoming, potentially not yet synced block headers.

<b>Signature:</b>

```typescript
syncIncomingBlocks(cb: (blockHeader: BlockHeader) => void): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  cb | (blockHeader: BlockHeader) =&gt; void |  |

<b>Returns:</b>

Promise&lt;void&gt;