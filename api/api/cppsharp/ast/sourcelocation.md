---
title: SourceLocation
slug: api/cppsharp.ast.sourcelocation
---
Struct in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.ValueType`

## Summary


Encodes a location in the source.
The SourceManager can decode this to get at the full include stack,
line and column information.


```csharp
public struct SourceLocation
```

## Constructors

|Name|Description|
|:---|:---|
|[SourceLocation\(uint\)](/api/cppsharp/ast/sourcelocation//ctor)||

## Fields

|Name|Description|
|:---|:---|
|[ID](/api/cppsharp/ast/sourcelocation/id)||

## Methods

|Name|Description|
|:---|:---|
|[Equals\(SourceLocation\)](/api/cppsharp/ast/sourcelocation/equals-1)||
|[Equals\(object\)](/api/cppsharp/ast/sourcelocation/equals-2)||
|[GetHashCode\(\)](/api/cppsharp/ast/sourcelocation/gethashcode)||
|[ToString\(\)](/api/cppsharp/ast/sourcelocation/tostring)||

## Properties

|Name|Description|
|:---|:---|
|[IsFileID](/api/cppsharp/ast/sourcelocation/isfileid)||
|[IsInvalid](/api/cppsharp/ast/sourcelocation/isinvalid)|Return true if this is an invalid SourceLocation object. Invalid SourceLocations are often used when events have no corresponding location in the source (e.g. a diagnostic is required for a command line option).|
|[IsMacroID](/api/cppsharp/ast/sourcelocation/ismacroid)||
|[IsValid](/api/cppsharp/ast/sourcelocation/isvalid)|Return true if this is a valid SourceLocation object.|
|[Offset](/api/cppsharp/ast/sourcelocation/offset)|Offset into the source manager's global input view.|

## TYPENAME_UNKNOWN_PLURAL

|Name|Description|
|:---|:---|
|[M:CppSharp.AST.SourceLocation.op_Equality\(CppSharp.AST.SourceLocation,CppSharp.AST.SourceLocation\)~System.Boolean](/api/cppsharp/ast/sourcelocation/op_equality)||
|[M:CppSharp.AST.SourceLocation.op_Inequality\(CppSharp.AST.SourceLocation,CppSharp.AST.SourceLocation\)~System.Boolean](/api/cppsharp/ast/sourcelocation/op_inequality)||

