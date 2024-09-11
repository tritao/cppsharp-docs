---
title: ObjCBridgeCastKind
slug: api/cppsharp.ast.objcbridgecastkind
---
Enum in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Enum`

## Summary



```csharp
public enum ObjCBridgeCastKind
{
    Bridge = 0,
    BridgeTransfer = 1,
    BridgeRetained = 2
}
```

## Members

|Name|Description|
|:---|:---|
|[Bridge](/api/cppsharp/ast/objcbridgecastkind/bridge)|<p>Bridging via __bridge, which does nothing but reinterpret</p> <p>the bits.</p>|
|[BridgeRetained](/api/cppsharp/ast/objcbridgecastkind/bridgeretained)|<p>Bridging via __bridge_retain, which makes an ARC object available</p> <p>as a +1 C pointer.</p>|
|[BridgeTransfer](/api/cppsharp/ast/objcbridgecastkind/bridgetransfer)|<p>Bridging via __bridge_transfer, which transfers ownership of an</p> <p>Objective-C pointer into ARC.</p>|

