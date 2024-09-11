---
title: TypeTemplateParameter
slug: api/cppsharp.ast.typetemplateparameter
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Declaration`](/api/cppsharp/ast/declaration)

## Summary


Represents a type template parameter.


```csharp
public class TypeTemplateParameter : Declaration
```

## Fields

|Name|Description|
|:---|:---|
|[Constraint](/api/cppsharp/ast/typetemplateparameter/constraint)||

## Methods

|Name|Description|
|:---|:---|
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/typetemplateparameter/visit)||

## Properties

|Name|Description|
|:---|:---|
|[DefaultArgument](/api/cppsharp/ast/typetemplateparameter/defaultargument)||
|[Depth](/api/cppsharp/ast/typetemplateparameter/depth)|Get the nesting depth of the template parameter.|
|[Index](/api/cppsharp/ast/typetemplateparameter/index)|Get the index of the template parameter within its parameter list.|
|[IsParameterPack](/api/cppsharp/ast/typetemplateparameter/isparameterpack)|Whether this parameter is a non-type template parameter pack. <p> If the parameter is a parameter pack, the type may be a PackExpansionType.In the following example, the Dims parameter is a parameter pack (whose type is 'unsigned'). <p>template&lt;typename T, unsigned...Dims&gt; struct multi_array;</p></p>|

