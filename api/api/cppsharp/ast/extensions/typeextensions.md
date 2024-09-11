---
title: TypeExtensions
slug: api/cppsharp.ast.extensions.typeextensions
---
Class in [CppSharp.AST.Extensions](/api/cppsharp/ast/extensions)

Inherits from `System.Object`

## Summary



```csharp
public static class TypeExtensions
```

## Methods

|Name|Description|
|:---|:---|
|[Desugar\(Type,bool\)](/api/cppsharp/ast/extensions/typeextensions/desugar)||
|[GetFinalPointee\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getfinalpointee)|If t is a pointer type the type pointed to by t will be returned after fully dereferencing it. Otherwise null. For example int** -&gt; int.|
|[GetFinalPointer\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getfinalpointer)||
|[GetFinalQualifiedPointee\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getfinalqualifiedpointee)|If t is a pointer type the type pointed to by t will be returned after fully dereferencing it. Otherwise the default qualified type. For example int** -&gt; int.|
|[GetModule\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getmodule)||
|[GetPointee\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getpointee)|If t is a pointer type the type pointed to by t will be returned. Otherwise null.|
|[GetQualifiedPointee\(Type\)](/api/cppsharp/ast/extensions/typeextensions/getqualifiedpointee)|If t is a pointer type the type pointed to by t will be returned. Otherwise the default qualified type.|
|[GetSizeInBits\(ArrayType\)](/api/cppsharp/ast/extensions/typeextensions/getsizeinbits)||
|[GetSizeInBytes\(ArrayType\)](/api/cppsharp/ast/extensions/typeextensions/getsizeinbytes)||
|[IsAddress\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isaddress)||
|[IsClass\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isclass)||
|[IsConst\(QualifiedType\)](/api/cppsharp/ast/extensions/typeextensions/isconst)||
|[IsConstCharString\(PointerType\)](/api/cppsharp/ast/extensions/typeextensions/isconstcharstring-2)||
|[IsConstCharString\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isconstcharstring-1)||
|[IsConstRef\(QualifiedType\)](/api/cppsharp/ast/extensions/typeextensions/isconstref)||
|[IsConstRefToPrimitive\(QualifiedType\)](/api/cppsharp/ast/extensions/typeextensions/isconstreftoprimitive)||
|[IsDependentPointer\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isdependentpointer)||
|[IsEnum\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isenum)||
|[IsEnumType\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isenumtype)||
|[IsPointer\(Type\)](/api/cppsharp/ast/extensions/typeextensions/ispointer)||
|[IsPointerTo\(Type,T\)](/api/cppsharp/ast/extensions/typeextensions/ispointerto)||
|[IsPointerToEnum\(Type,Enumeration\)](/api/cppsharp/ast/extensions/typeextensions/ispointertoenum-2)||
|[IsPointerToEnum\(Type\)](/api/cppsharp/ast/extensions/typeextensions/ispointertoenum-1)||
|[IsPointerToPrimitiveType\(Type,PrimitiveType\)](/api/cppsharp/ast/extensions/typeextensions/ispointertoprimitivetype-3)||
|[IsPointerToPrimitiveType\(Type,PrimitiveType\)](/api/cppsharp/ast/extensions/typeextensions/ispointertoprimitivetype-2)||
|[IsPointerToPrimitiveType\(Type\)](/api/cppsharp/ast/extensions/typeextensions/ispointertoprimitivetype-1)||
|[IsPrimitiveType\(Type,PrimitiveType\)](/api/cppsharp/ast/extensions/typeextensions/isprimitivetype-3)||
|[IsPrimitiveType\(Type,PrimitiveType\)](/api/cppsharp/ast/extensions/typeextensions/isprimitivetype-2)||
|[IsPrimitiveType\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isprimitivetype-1)||
|[IsReference\(Type\)](/api/cppsharp/ast/extensions/typeextensions/isreference)||
|[IsTemplateParameterType\(Type\)](/api/cppsharp/ast/extensions/typeextensions/istemplateparametertype)||
|[ResolvesTo\(QualifiedType,QualifiedType\)](/api/cppsharp/ast/extensions/typeextensions/resolvesto)||
|[SkipPointerRefs\(Type\)](/api/cppsharp/ast/extensions/typeextensions/skippointerrefs)||
|[StripConst\(QualifiedType\)](/api/cppsharp/ast/extensions/typeextensions/stripconst)||
|[TryGetClass\(Type,Class,Class\)](/api/cppsharp/ast/extensions/typeextensions/trygetclass)||
|[TryGetDeclaration\(Type,T,T\)](/api/cppsharp/ast/extensions/typeextensions/trygetdeclaration)||
|[TryGetEnum\(Type,Enumeration\)](/api/cppsharp/ast/extensions/typeextensions/trygetenum)||

