---
title: TypeTemplateParameter.IsParameterPack
slug: api/cppsharp.ast.typetemplateparameter.isparameterpack
---
Property in [TypeTemplateParameter](/api/cppsharp/ast/typetemplateparameter)

## Summary


Whether this parameter is a non-type template parameter pack.
<p>
If the parameter is a parameter pack, the type may be a PackExpansionType.In the following example, the Dims parameter is a parameter pack (whose type is 'unsigned').
<p>template&lt;typename T, unsigned...Dims&gt; struct multi_array;</p></p>

```csharp
public bool IsParameterPack { get; set; }
```

