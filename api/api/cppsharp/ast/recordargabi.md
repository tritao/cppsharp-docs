---
title: RecordArgABI
slug: api/cppsharp.ast.recordargabi
---
Enum in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Enum`

## Summary



```csharp
public enum RecordArgABI
{
    Default = 0,
    DirectInMemory = 1,
    Indirect = 2
};
```

## Members

|Name|Description|
|:---|:---|
|[Default](/api/cppsharp/ast/recordargabi/default)|<p>Pass it using the normal C aggregate rules for the ABI,</p> <p>potentially introducing extra copies and passing some</p> <p>or all of it in registers.</p>|
|[DirectInMemory](/api/cppsharp/ast/recordargabi/directinmemory)|<p>Pass it on the stack using its defined layout.</p> <p>The argument must be evaluated directly into the correct</p> <p>stack position in the arguments area, and the call machinery</p> <p>must not move it or introduce extra copies.</p>|
|[Indirect](/api/cppsharp/ast/recordargabi/indirect)|Pass it as a pointer to temporary memory.|

