---
title: PointerType
slug: api/cppsharp.ast.pointertype
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`Type`](/api/cppsharp/ast/type)

## Summary


Represents a C++ pointer/reference type.


```csharp
public class PointerType : Type
```

## Constructors

|Name|Description|
|:---|:---|
|[PointerType\(\)](/api/cppsharp/ast/pointertype//ctor-2)||
|[PointerType\(PointerType\)](/api/cppsharp/ast/pointertype//ctor-3)||
|[PointerType\(QualifiedType\)](/api/cppsharp/ast/pointertype//ctor-1)||

## Enums

|Name|Description|
|:---|:---|
|[TypeModifier](/api/cppsharp/ast/pointertype/typemodifier)|Represents the modifiers on a C++ type reference.|

## Fields

|Name|Description|
|:---|:---|
|[Modifier](/api/cppsharp/ast/pointertype/modifier)||
|[QualifiedPointee](/api/cppsharp/ast/pointertype/qualifiedpointee)||

## Methods

|Name|Description|
|:---|:---|
|[Clone\(\)](/api/cppsharp/ast/pointertype/clone)||
|[Equals\(object\)](/api/cppsharp/ast/pointertype/equals)||
|[GetHashCode\(\)](/api/cppsharp/ast/pointertype/gethashcode)||
|[Visit\(ITypeVisitor\<T\>,TypeQualifiers\)](/api/cppsharp/ast/pointertype/visit)||

## Properties

|Name|Description|
|:---|:---|
|[IsReference](/api/cppsharp/ast/pointertype/isreference)||
|[Pointee](/api/cppsharp/ast/pointertype/pointee)||

