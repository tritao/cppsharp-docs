---
title: NullPointerConstantKind
slug: api/cppsharp.ast.expr.nullpointerconstantkind
---
Enum in [Expr](/api/cppsharp/ast/expr)

Inherits from `System.Enum`

## Summary



```csharp
public enum NullPointerConstantKind
{
    NotNull = 0,
    ZeroExpression = 1,
    ZeroLiteral = 2,
    CXX11_nullptr = 3,
    GNUNull = 4
}
```

## Members

|Name|Description|
|:---|:---|
|[CXX11_nullptr](/api/cppsharp/ast/expr/nullpointerconstantkind/cxx11_nullptr)|Expression is a C++11 nullptr.|
|[GNUNull](/api/cppsharp/ast/expr/nullpointerconstantkind/gnunull)|Expression is a GNU-style __null constant.|
|[NotNull](/api/cppsharp/ast/expr/nullpointerconstantkind/notnull)|Expression is not a Null pointer constant.|
|[ZeroExpression](/api/cppsharp/ast/expr/nullpointerconstantkind/zeroexpression)|<p>Expression is a Null pointer constant built from a zero integer</p> <p>expression that is not a simple, possibly parenthesized, zero literal.</p> <p>C++ Core Issue 903 will classify these expressions as "not pointers"</p> <p>once it is adopted.</p> <p>http://www.open-std.org/jtc1/sc22/wg21/docs/cwg_active.html#903</p>|
|[ZeroLiteral](/api/cppsharp/ast/expr/nullpointerconstantkind/zeroliteral)|Expression is a Null pointer constant built from a literal zero.|

