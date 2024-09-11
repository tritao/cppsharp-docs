---
title: LiteralOperatorKind
slug: api/cppsharp.ast.userdefinedliteral.literaloperatorkind-1
---
Enum in [UserDefinedLiteral](/api/cppsharp/ast/userdefinedliteral)

Inherits from `System.Enum`

## Summary



```csharp
public enum LiteralOperatorKind
{
    Raw = 0,
    Template = 1,
    Integer = 2,
    Floating = 3,
    String = 4,
    Character = 5
}
```

## Members

|Name|Description|
|:---|:---|
|[Character](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/character)|operator "" X (CharT)|
|[Floating](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/floating)|operator "" X (long double)|
|[Integer](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/integer)|operator "" X (unsigned long long)|
|[Raw](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/raw)|Raw form: operator "" X (const char *)|
|[String](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/string)|operator "" X (const CharT *, size_t)|
|[Template](/api/cppsharp/ast/userdefinedliteral/literaloperatorkind/template)|Raw form: operator "" X...&gt; ()|

