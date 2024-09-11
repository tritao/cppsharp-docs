---
title: SideEffectsKind
slug: api/cppsharp.ast.expr.sideeffectskind
---
Enum in [Expr](/api/cppsharp/ast/expr)

Inherits from `System.Enum`

## Summary



```csharp
public enum SideEffectsKind
{
    NoSideEffects = 0,
    AllowUndefinedBehavior = 1,
    AllowSideEffects = 2
}
```

## Members

|Name|Description|
|:---|:---|
|[AllowSideEffects](/api/cppsharp/ast/expr/sideeffectskind/allowsideeffects)|Allow any unmodeled side effect.|
|[AllowUndefinedBehavior](/api/cppsharp/ast/expr/sideeffectskind/allowundefinedbehavior)|<p>Allow UB that we can give a value, but not</p> <p>arbitrary unmodeled side effects.</p>|
|[NoSideEffects](/api/cppsharp/ast/expr/sideeffectskind/nosideeffects)|Strictly evaluate the expression.|

