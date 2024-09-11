---
title: Parameter
slug: api/cppsharp.ast.parameter
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Declaration`](/api/cppsharp/ast/declaration)

## Summary



```csharp
public class Parameter : Declaration, ITypedDecl
```

## Constructors

|Name|Description|
|:---|:---|
|[Parameter\(\)](/api/cppsharp/ast/parameter//ctor-1)||
|[Parameter\(Parameter\)](/api/cppsharp/ast/parameter//ctor-2)||

## Methods

|Name|Description|
|:---|:---|
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/parameter/visit)||

## Properties

|Name|Description|
|:---|:---|
|[DefaultArgument](/api/cppsharp/ast/parameter/defaultargument)||
|[DefaultValue](/api/cppsharp/ast/parameter/defaultvalue)||
|[HasDefaultValue](/api/cppsharp/ast/parameter/hasdefaultvalue)||
|[Index](/api/cppsharp/ast/parameter/index)||
|[IsConst](/api/cppsharp/ast/parameter/isconst)|HACK: in many cases QualifiedType.Qualifiers.IsConst does not work. It's false in Clang to begin with. I tried fixing it to no avail. I don't have any more time at the moment.|
|[IsIn](/api/cppsharp/ast/parameter/isin)||
|[IsIndirect](/api/cppsharp/ast/parameter/isindirect)||
|[IsInOut](/api/cppsharp/ast/parameter/isinout)||
|[IsOut](/api/cppsharp/ast/parameter/isout)||
|[IsSynthetized](/api/cppsharp/ast/parameter/issynthetized)||
|[Kind](/api/cppsharp/ast/parameter/kind)||
|[OriginalDefaultArgument](/api/cppsharp/ast/parameter/originaldefaultargument)||
|[OriginalDefaultValue](/api/cppsharp/ast/parameter/originaldefaultvalue)||
|[QualifiedType](/api/cppsharp/ast/parameter/qualifiedtype)||
|[Type](/api/cppsharp/ast/parameter/type)||
|[Usage](/api/cppsharp/ast/parameter/usage)||

