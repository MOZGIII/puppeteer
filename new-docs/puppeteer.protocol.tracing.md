<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Tracing](./puppeteer.protocol.tracing.md)

## Protocol.Tracing namespace

<b>Signature:</b>

```typescript
export namespace Tracing 
```

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [StartRequestTransferMode](./puppeteer.protocol.tracing.startrequesttransfermode.md) |  |
|  [TraceConfigRecordMode](./puppeteer.protocol.tracing.traceconfigrecordmode.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [BufferUsageEvent](./puppeteer.protocol.tracing.bufferusageevent.md) |  |
|  [DataCollectedEvent](./puppeteer.protocol.tracing.datacollectedevent.md) | Contains an bucket of collected trace events. When tracing is stopped collected events will be send as a sequence of dataCollected events followed by tracingComplete event. |
|  [GetCategoriesResponse](./puppeteer.protocol.tracing.getcategoriesresponse.md) |  |
|  [MemoryDumpConfig](./puppeteer.protocol.tracing.memorydumpconfig.md) | Configuration for memory dump. Used only when "memory-infra" category is enabled. |
|  [RecordClockSyncMarkerRequest](./puppeteer.protocol.tracing.recordclocksyncmarkerrequest.md) |  |
|  [RequestMemoryDumpRequest](./puppeteer.protocol.tracing.requestmemorydumprequest.md) |  |
|  [RequestMemoryDumpResponse](./puppeteer.protocol.tracing.requestmemorydumpresponse.md) |  |
|  [StartRequest](./puppeteer.protocol.tracing.startrequest.md) |  |
|  [TraceConfig](./puppeteer.protocol.tracing.traceconfig.md) |  |
|  [TracingCompleteEvent](./puppeteer.protocol.tracing.tracingcompleteevent.md) | Signals that tracing is stopped and there is no trace buffers pending flush, all data were delivered via dataCollected events. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [StreamCompression](./puppeteer.protocol.tracing.streamcompression.md) | Compression type to use for traces returned via streams. |
|  [StreamFormat](./puppeteer.protocol.tracing.streamformat.md) | Data format of a trace. Can be either the legacy JSON format or the protocol buffer format. Note that the JSON format will be deprecated soon. |
