---
title: NonTypeTemplateParameter.IsExpandedParameterPack
slug: api/cppsharp.ast.nontypetemplateparameter.isexpandedparameterpack
---
Property in [NonTypeTemplateParameter](/api/cppsharp/ast/nontypetemplateparameter)

## Summary


Whether this parameter is a non-type template parameter pack that has a known list of different types at different positions.
<p>A parameter pack is an expanded parameter pack when the original parameter pack's type was itself a pack expansion, and that expansion has already been expanded. For example, given:</p> <p>
template&lt;typename...Types&gt;
struct X {
template&lt;Types...Values&gt;
struct Y { /* ... */ };
};
</p> 
The parameter pack Values has a PackExpansionType as its type, which expands Types.When Types is supplied with template arguments by instantiating X,
the instantiation of Values becomes an expanded parameter pack.For example, instantiating X&lt;int, unsigned int&gt;
results in Values being an expanded parameter pack with expansion types int and unsigned int.


```csharp
public bool IsExpandedParameterPack { get; set; }
```

