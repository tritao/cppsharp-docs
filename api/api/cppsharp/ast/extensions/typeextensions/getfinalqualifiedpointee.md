---
title: TypeExtensions.GetFinalQualifiedPointee(Type)
slug: api/cppsharp.ast.extensions.typeextensions.getfinalqualifiedpointee
---
Method in [TypeExtensions](/api/cppsharp/ast/extensions/typeextensions)

## Summary


If t is a pointer type the type pointed to by t will be returned
after fully dereferencing it. Otherwise the default qualified type.
For example int** -&gt; int.


```csharp
public static QualifiedType GetFinalQualifiedPointee(this Type t)
```

## Parameters

|Name|Description|
|:---|:---|
|[CppSharp.AST.Type](/api/cppsharp/ast/type) t||

