---
title: NonTypeTemplateParameter.IsPackExpansion
slug: api/cppsharp.ast.nontypetemplateparameter.ispackexpansion
---
Property in [NonTypeTemplateParameter](/api/cppsharp/ast/nontypetemplateparameter)

## Summary


Whether this parameter pack is a pack expansion.
<p>
A non-type template parameter pack is a pack expansion if its type contains an unexpanded parameter pack.In this case, we will have built a PackExpansionType wrapping the type.
</p>

```csharp
public bool IsPackExpansion { get; set; }
```

