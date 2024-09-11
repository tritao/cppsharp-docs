---
title: InitializationStyle
slug: api/cppsharp.ast.cxxnewexpr.initializationstyle-1
---
Enum in [CXXNewExpr](/api/cppsharp/ast/cxxnewexpr)

Inherits from `System.Enum`

## Summary



```csharp
public enum InitializationStyle
{
    NoInit = 0,
    CallInit = 1,
    ListInit = 2
}
```

## Members

|Name|Description|
|:---|:---|
|[CallInit](/api/cppsharp/ast/cxxnewexpr/initializationstyle/callinit)|New-expression has a C++98 paren-delimited initializer.|
|[ListInit](/api/cppsharp/ast/cxxnewexpr/initializationstyle/listinit)|New-expression has a C++11 list-initializer.|
|[NoInit](/api/cppsharp/ast/cxxnewexpr/initializationstyle/noinit)|New-expression has no initializer as written.|

