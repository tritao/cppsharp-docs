---
title: AttributedType
slug: api/cppsharp.ast.attributedtype
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Type`](/api/cppsharp/ast/type)

## Summary


An attributed type is a type to which a type attribute has been
applied.

For example, in the following attributed type:
int32_t __attribute__((vector_size(16)))

The modified type is the TypedefType for int32_t
The equivalent type is VectorType(16, int32_t)


```csharp
public class AttributedType : Type
```

## Constructors

|Name|Description|
|:---|:---|
|[AttributedType\(\)](/api/cppsharp/ast/attributedtype//ctor-1)||
|[AttributedType\(AttributedType\)](/api/cppsharp/ast/attributedtype//ctor-2)||

## Fields

|Name|Description|
|:---|:---|
|[Equivalent](/api/cppsharp/ast/attributedtype/equivalent)||
|[Modified](/api/cppsharp/ast/attributedtype/modified)||

## Methods

|Name|Description|
|:---|:---|
|[Clone\(\)](/api/cppsharp/ast/attributedtype/clone)||
|[Equals\(object\)](/api/cppsharp/ast/attributedtype/equals)||
|[GetHashCode\(\)](/api/cppsharp/ast/attributedtype/gethashcode)||
|[Visit\(ITypeVisitor\<T\>,TypeQualifiers\)](/api/cppsharp/ast/attributedtype/visit)||

