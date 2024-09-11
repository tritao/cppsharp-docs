---
title: ClassExtensions.FindHierarchy(Class,Func<Class, IEnumerable<T>>)
slug: api/cppsharp.ast.classextensions.findhierarchy-2
---
Method in [ClassExtensions](/api/cppsharp/ast/classextensions)

## Summary



```csharp
public static IEnumerable<T> FindHierarchy<T>(this Class @class,
    Func<Class, IEnumerable<T>> func)
    where T : Declaration
```

## Parameters

|Name|Description|
|:---|:---|
|[CppSharp.AST.Class](/api/cppsharp/ast/class) @class||
|`System.Func<CppSharp.AST.Class, System.Collections.Generic.IEnumerable<T>>` func||

