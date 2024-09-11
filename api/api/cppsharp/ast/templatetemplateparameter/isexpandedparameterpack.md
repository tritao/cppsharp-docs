---
title: TemplateTemplateParameter.IsExpandedParameterPack
slug: api/cppsharp.ast.templatetemplateparameter.isexpandedparameterpack
---
Property in [TemplateTemplateParameter](/api/cppsharp/ast/templatetemplateparameter)

## Summary


Whether this parameter is a template template parameter pack that has a known list of different template parameter lists at different positions.
A parameter pack is an expanded parameter pack when the original parameter pack's template parameter list was itself a pack expansion, and that expansion has already been expanded. For exampe, given:
<p>
template&lt;typename...Types&gt; struct Outer { template&lt;template&lt;Types&gt; class...Templates&gt; struct Inner; };
</p> 
The parameter pack Templates is a pack expansion, which expands the pack Types.When Types is supplied with template arguments by instantiating Outer, the instantiation of Templates is an expanded parameter pack.


```csharp
public bool IsExpandedParameterPack { get; set; }
```

