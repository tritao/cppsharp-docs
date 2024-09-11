---
title: Declaration.LogicalName
slug: api/cppsharp.ast.declaration.logicalname
---
Property in [Declaration](/api/cppsharp/ast/declaration)

## Summary


The effective name of a declaration is the logical name
for the declaration. We need this to make the distiction between
the real and the "effective" name of the declaration to properly
support things like inline namespaces when handling type maps.


```csharp
public virtual string LogicalName { get };
```

