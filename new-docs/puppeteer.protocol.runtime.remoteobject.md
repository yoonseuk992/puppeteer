<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Runtime](./puppeteer.protocol.runtime.md) &gt; [RemoteObject](./puppeteer.protocol.runtime.remoteobject.md)

## Protocol.Runtime.RemoteObject interface

Mirror object referencing original JavaScript object.

<b>Signature:</b>

```typescript
export interface RemoteObject 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [className](./puppeteer.protocol.runtime.remoteobject.classname.md) | string | Object class (constructor) name. Specified for <code>object</code> type values only. |
|  [customPreview](./puppeteer.protocol.runtime.remoteobject.custompreview.md) | [CustomPreview](./puppeteer.protocol.runtime.custompreview.md) |  |
|  [description](./puppeteer.protocol.runtime.remoteobject.description.md) | string | String representation of the object. |
|  [objectId](./puppeteer.protocol.runtime.remoteobject.objectid.md) | [RemoteObjectId](./puppeteer.protocol.runtime.remoteobjectid.md) | Unique object identifier (for non-primitive values). |
|  [preview](./puppeteer.protocol.runtime.remoteobject.preview.md) | [ObjectPreview](./puppeteer.protocol.runtime.objectpreview.md) | Preview containing abbreviated property values. Specified for <code>object</code> type values only. |
|  [subtype](./puppeteer.protocol.runtime.remoteobject.subtype.md) | ('array' \| 'null' \| 'node' \| 'regexp' \| 'date' \| 'map' \| 'set' \| 'weakmap' \| 'weakset' \| 'iterator' \| 'generator' \| 'error' \| 'proxy' \| 'promise' \| 'typedarray' \| 'arraybuffer' \| 'dataview' \| 'i32' \| 'i64' \| 'f32' \| 'f64' \| 'v128' \| 'anyref') | Object subtype hint. Specified for <code>object</code> or <code>wasm</code> type values only. |
|  [type](./puppeteer.protocol.runtime.remoteobject.type.md) | ('object' \| 'function' \| 'undefined' \| 'string' \| 'number' \| 'boolean' \| 'symbol' \| 'bigint' \| 'wasm') | Object type. |
|  [unserializableValue](./puppeteer.protocol.runtime.remoteobject.unserializablevalue.md) | [UnserializableValue](./puppeteer.protocol.runtime.unserializablevalue.md) | Primitive value which can not be JSON-stringified does not have <code>value</code>, but gets this property. |
|  [value](./puppeteer.protocol.runtime.remoteobject.value.md) | any | Remote object value in case of primitive values or JSON values (if it was requested). |

