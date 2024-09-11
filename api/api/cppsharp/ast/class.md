---
title: Class
slug: api/cppsharp.ast.class
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`DeclarationContext`](/api/cppsharp/ast/declarationcontext)

## Summary



```csharp
public class Class : DeclarationContext
```

## Constructors

|Name|Description|
|:---|:---|
|[Class\(\)](/api/cppsharp/ast/class//ctor)||

## Fields

|Name|Description|
|:---|:---|
|[Bases](/api/cppsharp/ast/class/bases)||
|[Fields](/api/cppsharp/ast/class/fields)||
|[HasNonTrivialCopyConstructor](/api/cppsharp/ast/class/hasnontrivialcopyconstructor)||
|[HasNonTrivialDefaultConstructor](/api/cppsharp/ast/class/hasnontrivialdefaultconstructor)||
|[HasNonTrivialDestructor](/api/cppsharp/ast/class/hasnontrivialdestructor)||
|[IsAbstract](/api/cppsharp/ast/class/isabstract)||
|[IsDynamic](/api/cppsharp/ast/class/isdynamic)||
|[IsPOD](/api/cppsharp/ast/class/ispod)||
|[IsPolymorphic](/api/cppsharp/ast/class/ispolymorphic)||
|[IsStatic](/api/cppsharp/ast/class/isstatic)||
|[IsUnion](/api/cppsharp/ast/class/isunion)||
|[Layout](/api/cppsharp/ast/class/layout)||
|[Methods](/api/cppsharp/ast/class/methods)||
|[Properties](/api/cppsharp/ast/class/properties)||
|[Specifiers](/api/cppsharp/ast/class/specifiers)||
|[Type](/api/cppsharp/ast/class/type)||

## Methods

|Name|Description|
|:---|:---|
|[FindMethod\(string\)](/api/cppsharp/ast/class/findmethod)||
|[FindMethodByUSR\(string\)](/api/cppsharp/ast/class/findmethodbyusr)||
|[FindOperator\(CXXOperatorKind\)](/api/cppsharp/ast/class/findoperator)||
|[FindVariable\(string\)](/api/cppsharp/ast/class/findvariable)||
|[GetOverloads\(Function\)](/api/cppsharp/ast/class/getoverloads)||
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/class/visit)||

## Properties

|Name|Description|
|:---|:---|
|[BaseClass](/api/cppsharp/ast/class/baseclass)||
|[Constructors](/api/cppsharp/ast/class/constructors)||
|[Destructors](/api/cppsharp/ast/class/destructors)||
|[HasBase](/api/cppsharp/ast/class/hasbase)||
|[HasBaseClass](/api/cppsharp/ast/class/hasbaseclass)||
|[HasNonIgnoredBase](/api/cppsharp/ast/class/hasnonignoredbase)||
|[HasUnionFields](/api/cppsharp/ast/class/hasunionfields)||
|[IsAbstractImpl](/api/cppsharp/ast/class/isabstractimpl)||
|[IsFinal](/api/cppsharp/ast/class/isfinal)||
|[IsInjected](/api/cppsharp/ast/class/isinjected)||
|[IsInterface](/api/cppsharp/ast/class/isinterface)||
|[IsOpaque](/api/cppsharp/ast/class/isopaque)||
|[IsRefType](/api/cppsharp/ast/class/isreftype)||
|[IsTemplate](/api/cppsharp/ast/class/istemplate)||
|[IsValueType](/api/cppsharp/ast/class/isvaluetype)||
|[NeedsBase](/api/cppsharp/ast/class/needsbase)||
|[Operators](/api/cppsharp/ast/class/operators)||
|[OriginalClass](/api/cppsharp/ast/class/originalclass)||
|[Specializations](/api/cppsharp/ast/class/specializations)|If this class is a template, this list contains all of its specializations. <a href="cppsharp.ast.classtemplate.md">ClassTemplate</a>  cannot be relied upon to contain all of them because ClassTemplateDecl in Clang is not a complete declaration, it only serves to forward template classes.|
|[TagKind](/api/cppsharp/ast/class/tagkind)||
|[TemplateParameters](/api/cppsharp/ast/class/templateparameters)|If this class is a template, this list contains all of its template parameters. <p> <a href="cppsharp.ast.classtemplate.md">ClassTemplate</a> cannot be relied upon to contain all of them because ClassTemplateDecl in Clang is not a complete declaration, it only serves to forward template classes. </p>|

