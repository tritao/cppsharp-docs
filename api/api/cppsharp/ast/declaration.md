---
title: Declaration
slug: api/cppsharp.ast.declaration
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from [`DeclarationBase`](/api/cppsharp/ast/declarationbase)

## Summary


Represents a C++ declaration.


```csharp
public abstract class Declaration : DeclarationBase, INamedDecl
```

## Fields

|Name|Description|
|:---|:---|
|[Comment](/api/cppsharp/ast/declaration/comment)||
|[CompleteDeclaration](/api/cppsharp/ast/declaration/completedeclaration)||
|[DebugText](/api/cppsharp/ast/declaration/debugtext)||
|[DefinitionOrder](/api/cppsharp/ast/declaration/definitionorder)||
|[ExcludeFromPasses](/api/cppsharp/ast/declaration/excludefrompasses)||
|[IsDependent](/api/cppsharp/ast/declaration/isdependent)||
|[IsDeprecated](/api/cppsharp/ast/declaration/isdeprecated)||
|[IsIncomplete](/api/cppsharp/ast/declaration/isincomplete)||
|[Location](/api/cppsharp/ast/declaration/location)||
|[OriginalNamespace](/api/cppsharp/ast/declaration/originalnamespace)||
|[OriginalPtr](/api/cppsharp/ast/declaration/originalptr)||
|[PreprocessedEntities](/api/cppsharp/ast/declaration/preprocessedentities)||
|[QualifiedNameSeparator](/api/cppsharp/ast/declaration/qualifiednameseparator)||
|[USR](/api/cppsharp/ast/declaration/usr)||

## Methods

|Name|Description|
|:---|:---|
|[GatherNamespaces\(DeclarationContext,bool\)](/api/cppsharp/ast/declaration/gathernamespaces)||
|[GetQualifiedName\(Func\<Declaration, string\>,Func\<Declaration, DeclarationContext\>,bool\)](/api/cppsharp/ast/declaration/getqualifiedname)||
|[ToString\(\)](/api/cppsharp/ast/declaration/tostring)||
|[Visit\(IDeclVisitor\<T\>\)](/api/cppsharp/ast/declaration/visit)||

## Properties

|Name|Description|
|:---|:---|
|[Access](/api/cppsharp/ast/declaration/access)||
|[AlignAs](/api/cppsharp/ast/declaration/alignas)||
|[AssociatedDeclaration](/api/cppsharp/ast/declaration/associateddeclaration)||
|[Attributes](/api/cppsharp/ast/declaration/attributes)||
|[DeclMap](/api/cppsharp/ast/declaration/declmap)||
|[GenerationKind](/api/cppsharp/ast/declaration/generationkind)||
|[IsImplicit](/api/cppsharp/ast/declaration/isimplicit)||
|[LineNumberEnd](/api/cppsharp/ast/declaration/linenumberend)||
|[LineNumberStart](/api/cppsharp/ast/declaration/linenumberstart)||
|[LogicalName](/api/cppsharp/ast/declaration/logicalname)|The effective name of a declaration is the logical name for the declaration. We need this to make the distiction between the real and the "effective" name of the declaration to properly support things like inline namespaces when handling type maps.|
|[LogicalOriginalName](/api/cppsharp/ast/declaration/logicaloriginalname)|The effective original name of a declaration is the logical original name for the declaration.|
|[MaxFieldAlignment](/api/cppsharp/ast/declaration/maxfieldalignment)||
|[Name](/api/cppsharp/ast/declaration/name)||
|[Namespace](/api/cppsharp/ast/declaration/namespace)||
|[OriginalName](/api/cppsharp/ast/declaration/originalname)||
|[QualifiedLogicalName](/api/cppsharp/ast/declaration/qualifiedlogicalname)||
|[QualifiedLogicalOriginalName](/api/cppsharp/ast/declaration/qualifiedlogicaloriginalname)||
|[QualifiedName](/api/cppsharp/ast/declaration/qualifiedname)||
|[QualifiedOriginalName](/api/cppsharp/ast/declaration/qualifiedoriginalname)||
|[Redeclarations](/api/cppsharp/ast/declaration/redeclarations)||
|[TranslationUnit](/api/cppsharp/ast/declaration/translationunit)||

