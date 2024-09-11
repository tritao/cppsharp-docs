---
title: Parameter.IsConst
slug: api/cppsharp.ast.parameter.isconst
---
Property in [Parameter](/api/cppsharp/ast/parameter)

## Summary


HACK: in many cases QualifiedType.Qualifiers.IsConst does not work.
It's false in Clang to begin with. I tried fixing it to no avail.
I don't have any more time at the moment.


```csharp
public bool IsConst { get };
```

