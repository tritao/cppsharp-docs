---
title: BlockCommandComment
slug: api/cppsharp.ast.blockcommandcomment
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`BlockContentComment`](/api/cppsharp/ast/blockcontentcomment)

## Summary


A command that has zero or more word-like arguments (number of
word-like arguments depends on command name) and a paragraph as
an argument (e. g., \brief).


```csharp
public class BlockCommandComment : BlockContentComment
```

## Constructors

|Name|Description|
|:---|:---|
|[BlockCommandComment\(\)](/api/cppsharp/ast/blockcommandcomment//ctor)||

## Fields

|Name|Description|
|:---|:---|
|[Arguments](/api/cppsharp/ast/blockcommandcomment/arguments)||
|[CommandId](/api/cppsharp/ast/blockcommandcomment/commandid)||

## Methods

|Name|Description|
|:---|:---|
|[Visit\(ICommentVisitor\<T\>\)](/api/cppsharp/ast/blockcommandcomment/visit)||

## Properties

|Name|Description|
|:---|:---|
|[CommandKind](/api/cppsharp/ast/blockcommandcomment/commandkind)||
|[ParagraphComment](/api/cppsharp/ast/blockcommandcomment/paragraphcomment)||

## Structs

|Name|Description|
|:---|:---|
|[Argument](/api/cppsharp/ast/blockcommandcomment/argument)||

