---
title: Class.TemplateParameters
slug: api/cppsharp.ast.class.templateparameters
---
Property in [Class](/api/cppsharp/ast/class)

## Summary


If this class is a template, this list contains all of its template parameters.
<p>
<a href="cppsharp.ast.classtemplate.md">ClassTemplate</a> cannot be relied upon to contain all of them because
ClassTemplateDecl in Clang is not a complete declaration, it only serves to forward template classes.
</p>

```csharp
public List<Declaration> TemplateParameters
{
            get; }
```

