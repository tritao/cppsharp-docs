---
title: UnaryExprOrTypeTrait
slug: api/cppsharp.ast.unaryexprortypetrait
---
Enum in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Enum`

## Summary



```csharp
public enum UnaryExprOrTypeTrait
{
    SizeOf = 0,
    AlignOf = 1,
    VecStep = 2,
    OpenMPRequiredSimdAlign = 3,
    PreferredAlignOf = 4
}
```

## Members

|Name|Description|
|:---|:---|
|[AlignOf](/api/cppsharp/ast/unaryexprortypetrait/alignof)|<p>Used for C's _Alignof and C++'s alignof.</p> <p>_Alignof and alignof return the required ABI alignment.</p>|
|[OpenMPRequiredSimdAlign](/api/cppsharp/ast/unaryexprortypetrait/openmprequiredsimdalign)|<p>Used for C's _Alignof and C++'s alignof.</p> <p>_Alignof and alignof return the required ABI alignment.</p>|
|[PreferredAlignOf](/api/cppsharp/ast/unaryexprortypetrait/preferredalignof)|<p>Used for GCC's __alignof.</p> <p>__alignof returns the preferred alignment of a type, the alignment</p> <p>clang will attempt to give an object of the type if allowed by ABI.</p>|
|[SizeOf](/api/cppsharp/ast/unaryexprortypetrait/sizeof)||
|[VecStep](/api/cppsharp/ast/unaryexprortypetrait/vecstep)|<p>Used for C's _Alignof and C++'s alignof.</p> <p>_Alignof and alignof return the required ABI alignment.</p>|

