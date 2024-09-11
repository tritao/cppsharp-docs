---
title: NonTypeTemplateParameter
slug: api/cppsharp.ast.nontypetemplateparameter
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Declaration`](/api/cppsharp/ast/declaration)

## Summary


Represents a non-type template parameter.


```csharp
public class NonTypeTemplateParameter : Declaration
```

## Methods

|Name|Description|
|:---|:---|
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/nontypetemplateparameter/visit)||

## Properties

|Name|Description|
|:---|:---|
|[DefaultArgument](/api/cppsharp/ast/nontypetemplateparameter/defaultargument)||
|[Depth](/api/cppsharp/ast/nontypetemplateparameter/depth)|Get the nesting depth of the template parameter.|
|[Index](/api/cppsharp/ast/nontypetemplateparameter/index)|Get the index of the template parameter within its parameter list.|
|[IsExpandedParameterPack](/api/cppsharp/ast/nontypetemplateparameter/isexpandedparameterpack)|Whether this parameter is a non-type template parameter pack that has a known list of different types at different positions. <p>A parameter pack is an expanded parameter pack when the original parameter pack's type was itself a pack expansion, and that expansion has already been expanded. For example, given:</p> <p> template&lt;typename...Types&gt; struct X { template&lt;Types...Values&gt; struct Y { /* ... */ }; }; </p>  The parameter pack Values has a PackExpansionType as its type, which expands Types.When Types is supplied with template arguments by instantiating X, the instantiation of Values becomes an expanded parameter pack.For example, instantiating X&lt;int, unsigned int&gt; results in Values being an expanded parameter pack with expansion types int and unsigned int.|
|[IsPackExpansion](/api/cppsharp/ast/nontypetemplateparameter/ispackexpansion)|Whether this parameter pack is a pack expansion. <p> A non-type template parameter pack is a pack expansion if its type contains an unexpanded parameter pack.In this case, we will have built a PackExpansionType wrapping the type. </p>|
|[IsParameterPack](/api/cppsharp/ast/nontypetemplateparameter/isparameterpack)|Whether this parameter is a non-type template parameter pack. <p> If the parameter is a parameter pack, the type may be a PackExpansionType.In the following example, the Dims parameter is a parameter pack (whose type is 'unsigned'). <p>template&lt;typename T, unsigned...Dims&gt; struct multi_array;</p></p>|
|[Position](/api/cppsharp/ast/nontypetemplateparameter/position)|Get the position of the template parameter within its parameter list.|
|[Type](/api/cppsharp/ast/nontypetemplateparameter/type)||

