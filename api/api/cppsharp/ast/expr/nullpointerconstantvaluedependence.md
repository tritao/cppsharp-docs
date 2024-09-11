---
title: NullPointerConstantValueDependence
slug: api/cppsharp.ast.expr.nullpointerconstantvaluedependence
---
Enum in [Expr](/api/cppsharp/ast/expr)

Inherits from `System.Enum`

## Summary



```csharp
public enum NullPointerConstantValueDependence
{
    NeverValueDependent = 0,
    ValueDependentIsNull = 1,
    ValueDependentIsNotNull = 2
}
```

## Members

|Name|Description|
|:---|:---|
|[NeverValueDependent](/api/cppsharp/ast/expr/nullpointerconstantvaluedependence/nevervaluedependent)|Specifies that the expression should never be value-dependent.|
|[ValueDependentIsNotNull](/api/cppsharp/ast/expr/nullpointerconstantvaluedependence/valuedependentisnotnull)|<p>Specifies that a value-dependent expression should be considered</p> <p>to never be a null pointer constant.</p>|
|[ValueDependentIsNull](/api/cppsharp/ast/expr/nullpointerconstantvaluedependence/valuedependentisnull)|<p>Specifies that a value-dependent expression of integral or</p> <p>dependent type should be considered a null pointer constant.</p>|

