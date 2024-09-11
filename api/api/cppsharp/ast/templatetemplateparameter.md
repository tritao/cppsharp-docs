---
title: TemplateTemplateParameter
slug: api/cppsharp.ast.templatetemplateparameter
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Template`](/api/cppsharp/ast/template)

## Summary



```csharp
public class TemplateTemplateParameter : Template
```

## Methods

|Name|Description|
|:---|:---|
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/templatetemplateparameter/visit)||

## Properties

|Name|Description|
|:---|:---|
|[IsExpandedParameterPack](/api/cppsharp/ast/templatetemplateparameter/isexpandedparameterpack)|Whether this parameter is a template template parameter pack that has a known list of different template parameter lists at different positions. A parameter pack is an expanded parameter pack when the original parameter pack's template parameter list was itself a pack expansion, and that expansion has already been expanded. For exampe, given: <p> template&lt;typename...Types&gt; struct Outer { template&lt;template&lt;Types&gt; class...Templates&gt; struct Inner; }; </p>  The parameter pack Templates is a pack expansion, which expands the pack Types.When Types is supplied with template arguments by instantiating Outer, the instantiation of Templates is an expanded parameter pack.|
|[IsPackExpansion](/api/cppsharp/ast/templatetemplateparameter/ispackexpansion)|Whether this parameter pack is a pack expansion. <p>A template template parameter pack is a pack expansion if its template parameter list contains an unexpanded parameter pack.</p>|
|[IsParameterPack](/api/cppsharp/ast/templatetemplateparameter/isparameterpack)|Whether this template template parameter is a template parameter pack. <p>template&lt;template&lt;class T&gt; ...MetaFunctions&gt; struct Apply;</p>|

