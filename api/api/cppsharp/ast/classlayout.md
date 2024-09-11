---
title: ClassLayout
slug: api/cppsharp.ast.classlayout
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Object`

## Summary



```csharp
public class ClassLayout
```

## Constructors

|Name|Description|
|:---|:---|
|[ClassLayout\(\)](/api/cppsharp/ast/classlayout//ctor-1)||
|[ClassLayout\(ClassLayout\)](/api/cppsharp/ast/classlayout//ctor-2)||

## Fields

|Name|Description|
|:---|:---|
|[Alignment](/api/cppsharp/ast/classlayout/alignment)||
|[DataSize](/api/cppsharp/ast/classlayout/datasize)||
|[HasOwnVFPtr](/api/cppsharp/ast/classlayout/hasownvfptr)|Does this class provide its own virtual-function table pointer, rather than inheriting one from a primary base class? If so, it is at offset zero.|
|[HasVirtualBases](/api/cppsharp/ast/classlayout/hasvirtualbases)||
|[PrimaryBase](/api/cppsharp/ast/classlayout/primarybase)|Primary base for this record.|
|[Size](/api/cppsharp/ast/classlayout/size)||
|[VBPtrOffset](/api/cppsharp/ast/classlayout/vbptroffset)|Get the offset for virtual base table pointer. This is only meaningful with the Microsoft ABI.|

## Properties

|Name|Description|
|:---|:---|
|[ABI](/api/cppsharp/ast/classlayout/abi)||
|[ArgABI](/api/cppsharp/ast/classlayout/argabi)||
|[Bases](/api/cppsharp/ast/classlayout/bases)||
|[Fields](/api/cppsharp/ast/classlayout/fields)||
|[HasSubclassAtNonZeroOffset](/api/cppsharp/ast/classlayout/hassubclassatnonzerooffset)|Indicates whether this class layout has a subclass at a non-zero offset.|
|[Layout](/api/cppsharp/ast/classlayout/layout)||
|[VFTables](/api/cppsharp/ast/classlayout/vftables)||
|[VTablePointers](/api/cppsharp/ast/classlayout/vtablepointers)||

