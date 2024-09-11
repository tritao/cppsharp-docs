---
title: TypeExtensions.GetFinalPointee(Type)
slug: api/cppsharp.ast.extensions.typeextensions.getfinalpointee
---
Method in [TypeExtensions](/api/cppsharp/ast/extensions/typeextensions)

## Summary


If t is a pointer type the type pointed to by t will be returned
after fully dereferencing it. Otherwise null.
For example int** -&gt; int.


```csharp
public static Type GetFinalPointee(this Type t)
```

## Parameters

|Name|Description|
|:---|:---|
|[CppSharp.AST.Type](/api/cppsharp/ast/type) t||

