---
title: VisitFlags
slug: api/cppsharp.ast.visitflags
---
Enum in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Enum`

## Summary



```csharp
public enum VisitFlags
{
    Default = 0,
    ClassBases = 1 << 0,
    ClassFields = 1 << 1,
    ClassProperties = 1 << 2,
    ClassMethods = 1 << 3,
    ClassTemplateSpecializations = 1 << 4,
    PropertyAccessors = 1 << 5,
    NamespaceEnums = 1 << 6,
    NamespaceTemplates = 1 << 7,
    NamespaceTypedefs = 1 << 8,
    NamespaceEvents = 1 << 9,
    NamespaceVariables = 1 << 10,
    NamespaceClasses = 1 << 15,
    NamespaceFunctions = 1 << 16,
    FunctionReturnType = 1 << 11,
    FunctionParameters = 1 << 12,
    EventParameters = 1 << 13,
    TemplateArguments = 1 << 14,
    Any = ClassBases | ClassFields | ClassProperties | ClassMethods |
ClassTemplateSpecializations | PropertyAccessors |
NamespaceEnums | NamespaceTemplates | NamespaceTypedefs |
NamespaceEvents | NamespaceVariables | NamespaceClasses | NamespaceFunctions |
FunctionReturnType | FunctionParameters |
EventParameters | TemplateArguments
}
```

## Members

|Name|Description|
|:---|:---|
|[Any](/api/cppsharp/ast/visitflags/any)||
|[ClassBases](/api/cppsharp/ast/visitflags/classbases)||
|[ClassFields](/api/cppsharp/ast/visitflags/classfields)||
|[ClassMethods](/api/cppsharp/ast/visitflags/classmethods)||
|[ClassProperties](/api/cppsharp/ast/visitflags/classproperties)||
|[ClassTemplateSpecializations](/api/cppsharp/ast/visitflags/classtemplatespecializations)||
|[Default](/api/cppsharp/ast/visitflags/default)|We always visit declaration contexts.|
|[EventParameters](/api/cppsharp/ast/visitflags/eventparameters)||
|[FunctionParameters](/api/cppsharp/ast/visitflags/functionparameters)||
|[FunctionReturnType](/api/cppsharp/ast/visitflags/functionreturntype)||
|[NamespaceClasses](/api/cppsharp/ast/visitflags/namespaceclasses)||
|[NamespaceEnums](/api/cppsharp/ast/visitflags/namespaceenums)||
|[NamespaceEvents](/api/cppsharp/ast/visitflags/namespaceevents)||
|[NamespaceFunctions](/api/cppsharp/ast/visitflags/namespacefunctions)||
|[NamespaceTemplates](/api/cppsharp/ast/visitflags/namespacetemplates)||
|[NamespaceTypedefs](/api/cppsharp/ast/visitflags/namespacetypedefs)||
|[NamespaceVariables](/api/cppsharp/ast/visitflags/namespacevariables)||
|[PropertyAccessors](/api/cppsharp/ast/visitflags/propertyaccessors)||
|[TemplateArguments](/api/cppsharp/ast/visitflags/templatearguments)||

