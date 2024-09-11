---
title: SourceLocation.IsInvalid
slug: api/cppsharp.ast.sourcelocation.isinvalid
---
Property in [SourceLocation](/api/cppsharp/ast/sourcelocation)

## Summary


Return true if this is an invalid SourceLocation object.
Invalid SourceLocations are often used when events have no corresponding
location in the source (e.g. a diagnostic is required for a command line
option).


```csharp
public bool IsInvalid
{
            get; }
```

