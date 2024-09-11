---
title: CppSharp.AST Namespace
slug: api/cppsharp.ast
---
## Summary

Contains all the AST (Abstract Syntax Tree) related types.


## Classes

|Name|Description|
|:---|:---|
|[AbstractConditionalOperator](/api/cppsharp/ast/abstractconditionaloperator)||
|[AccessSpecifierDecl](/api/cppsharp/ast/accessspecifierdecl)||
|[AddrLabelExpr](/api/cppsharp/ast/addrlabelexpr)||
|[ArrayInitIndexExpr](/api/cppsharp/ast/arrayinitindexexpr)||
|[ArrayInitLoopExpr](/api/cppsharp/ast/arrayinitloopexpr)||
|[ArraySubscriptExpr](/api/cppsharp/ast/arraysubscriptexpr)||
|[ArrayType](/api/cppsharp/ast/arraytype)|Represents an C/C++ array type.|
|[ArrayTypeTraitExpr](/api/cppsharp/ast/arraytypetraitexpr)||
|[AsmStmt](/api/cppsharp/ast/asmstmt)||
|[ASTContext](/api/cppsharp/ast/astcontext)|An AST context is a container for translation units.|
|[AstVisitor](/api/cppsharp/ast/astvisitor)|Base class for AST visitors. You can override the methods to customize the behaviour, by default this will visit all the nodes in a default way that should be useful for a lot of applications.|
|[AstVisitorOptions](/api/cppsharp/ast/astvisitoroptions)||
|[AsTypeExpr](/api/cppsharp/ast/astypeexpr)||
|[AtomicExpr](/api/cppsharp/ast/atomicexpr)||
|[Attribute](/api/cppsharp/ast/attribute)|Gives the ability to specify attributes to generate, for example ObsoleteAttribute.|
|[AttributedStmt](/api/cppsharp/ast/attributedstmt)||
|[AttributedType](/api/cppsharp/ast/attributedtype)|An attributed type is a type to which a type attribute has been applied.  For example, in the following attributed type: int32_t __attribute__((vector_size(16)))  The modified type is the TypedefType for int32_t The equivalent type is VectorType(16, int32_t)|
|[BaseClassSpecifier](/api/cppsharp/ast/baseclassspecifier)||
|[BinaryConditionalOperator](/api/cppsharp/ast/binaryconditionaloperator)||
|[BinaryOperator](/api/cppsharp/ast/binaryoperator)||
|[BinaryOperatorObsolete](/api/cppsharp/ast/binaryoperatorobsolete)||
|[BlockCommandComment](/api/cppsharp/ast/blockcommandcomment)|A command that has zero or more word-like arguments (number of word-like arguments depends on command name) and a paragraph as an argument (e. g., \brief).|
|[BlockContentComment](/api/cppsharp/ast/blockcontentcomment)|Block content (contains inline content).|
|[BlockExpr](/api/cppsharp/ast/blockexpr)||
|[BreakStmt](/api/cppsharp/ast/breakstmt)||
|[BuiltinType](/api/cppsharp/ast/builtintype)|Represents an instance of a C++ built-in type.|
|[BuiltinTypeExpressionObsolete](/api/cppsharp/ast/builtintypeexpressionobsolete)||
|[CallExpr](/api/cppsharp/ast/callexpr)||
|[CallExprObsolete](/api/cppsharp/ast/callexprobsolete)||
|[CapturedStmt](/api/cppsharp/ast/capturedstmt)||
|[CaseStmt](/api/cppsharp/ast/casestmt)||
|[CastExpr](/api/cppsharp/ast/castexpr)||
|[CharacterLiteral](/api/cppsharp/ast/characterliteral)||
|[ChooseExpr](/api/cppsharp/ast/chooseexpr)||
|[CILType](/api/cppsharp/ast/ciltype)|Represents a CIL type.|
|[Class](/api/cppsharp/ast/class)||
|[ClassExtensions](/api/cppsharp/ast/classextensions)||
|[ClassLayout](/api/cppsharp/ast/classlayout)||
|[ClassTemplate](/api/cppsharp/ast/classtemplate)|Declaration of a class template.|
|[ClassTemplatePartialSpecialization](/api/cppsharp/ast/classtemplatepartialspecialization)|Represents a class template partial specialization, which refers to a class template with a given partial set of template arguments.|
|[ClassTemplateSpecialization](/api/cppsharp/ast/classtemplatespecialization)|Represents a class template specialization, which refers to a class template with a given set of template arguments.|
|[CoawaitExpr](/api/cppsharp/ast/coawaitexpr)||
|[Comment](/api/cppsharp/ast/comment)|Any part of the comment.|
|[CompoundAssignOperator](/api/cppsharp/ast/compoundassignoperator)||
|[CompoundLiteralExpr](/api/cppsharp/ast/compoundliteralexpr)||
|[CompoundStmt](/api/cppsharp/ast/compoundstmt)||
|[ConditionalOperator](/api/cppsharp/ast/conditionaloperator)||
|[ConstantExpr](/api/cppsharp/ast/constantexpr)||
|[ContinueStmt](/api/cppsharp/ast/continuestmt)||
|[ConvertVectorExpr](/api/cppsharp/ast/convertvectorexpr)||
|[CoreturnStmt](/api/cppsharp/ast/coreturnstmt)||
|[CoroutineBodyStmt](/api/cppsharp/ast/coroutinebodystmt)||
|[CoroutineSuspendExpr](/api/cppsharp/ast/coroutinesuspendexpr)||
|[CoyieldExpr](/api/cppsharp/ast/coyieldexpr)||
|[CStyleCastExpr](/api/cppsharp/ast/cstylecastexpr)||
|[CUDAKernelCallExpr](/api/cppsharp/ast/cudakernelcallexpr)||
|[CustomType](/api/cppsharp/ast/customtype)||
|[CXXBindTemporaryExpr](/api/cppsharp/ast/cxxbindtemporaryexpr)||
|[CXXBoolLiteralExpr](/api/cppsharp/ast/cxxboolliteralexpr)||
|[CXXCatchStmt](/api/cppsharp/ast/cxxcatchstmt)||
|[CXXConstCastExpr](/api/cppsharp/ast/cxxconstcastexpr)||
|[CXXConstructExpr](/api/cppsharp/ast/cxxconstructexpr)||
|[CXXConstructExprObsolete](/api/cppsharp/ast/cxxconstructexprobsolete)||
|[CXXDefaultArgExpr](/api/cppsharp/ast/cxxdefaultargexpr)||
|[CXXDefaultInitExpr](/api/cppsharp/ast/cxxdefaultinitexpr)||
|[CXXDeleteExpr](/api/cppsharp/ast/cxxdeleteexpr)||
|[CXXDependentScopeMemberExpr](/api/cppsharp/ast/cxxdependentscopememberexpr)||
|[CXXDynamicCastExpr](/api/cppsharp/ast/cxxdynamiccastexpr)||
|[CXXFoldExpr](/api/cppsharp/ast/cxxfoldexpr)||
|[CXXForRangeStmt](/api/cppsharp/ast/cxxforrangestmt)||
|[CXXFunctionalCastExpr](/api/cppsharp/ast/cxxfunctionalcastexpr)||
|[CXXInheritedCtorInitExpr](/api/cppsharp/ast/cxxinheritedctorinitexpr)||
|[CXXMemberCallExpr](/api/cppsharp/ast/cxxmembercallexpr)||
|[CXXNamedCastExpr](/api/cppsharp/ast/cxxnamedcastexpr)||
|[CXXNewExpr](/api/cppsharp/ast/cxxnewexpr)||
|[CXXNoexceptExpr](/api/cppsharp/ast/cxxnoexceptexpr)||
|[CXXNullPtrLiteralExpr](/api/cppsharp/ast/cxxnullptrliteralexpr)||
|[CXXOperatorCallExpr](/api/cppsharp/ast/cxxoperatorcallexpr)||
|[CXXPseudoDestructorExpr](/api/cppsharp/ast/cxxpseudodestructorexpr)||
|[CXXReinterpretCastExpr](/api/cppsharp/ast/cxxreinterpretcastexpr)||
|[CXXScalarValueInitExpr](/api/cppsharp/ast/cxxscalarvalueinitexpr)||
|[CXXStaticCastExpr](/api/cppsharp/ast/cxxstaticcastexpr)||
|[CXXStdInitializerListExpr](/api/cppsharp/ast/cxxstdinitializerlistexpr)||
|[CXXTemporaryObjectExpr](/api/cppsharp/ast/cxxtemporaryobjectexpr)||
|[CXXThisExpr](/api/cppsharp/ast/cxxthisexpr)||
|[CXXThrowExpr](/api/cppsharp/ast/cxxthrowexpr)||
|[CXXTryStmt](/api/cppsharp/ast/cxxtrystmt)||
|[CXXTypeidExpr](/api/cppsharp/ast/cxxtypeidexpr)||
|[CXXUnresolvedConstructExpr](/api/cppsharp/ast/cxxunresolvedconstructexpr)||
|[CXXUuidofExpr](/api/cppsharp/ast/cxxuuidofexpr)||
|[DecayedType](/api/cppsharp/ast/decayedtype)|Represents a pointer type decayed from an array or function type.|
|[Declaration](/api/cppsharp/ast/declaration)|Represents a C++ declaration.|
|[DeclarationBase](/api/cppsharp/ast/declarationbase)||
|[DeclarationContext](/api/cppsharp/ast/declarationcontext)|Represents a declaration context.|
|[DeclarationsList](/api/cppsharp/ast/declarationslist)||
|[DeclRefExpr](/api/cppsharp/ast/declrefexpr)||
|[DeclStmt](/api/cppsharp/ast/declstmt)||
|[DefaultStmt](/api/cppsharp/ast/defaultstmt)||
|[Delegate](/api/cppsharp/ast/delegate)||
|[DependentCoawaitExpr](/api/cppsharp/ast/dependentcoawaitexpr)||
|[DependentNameType](/api/cppsharp/ast/dependentnametype)|Represents a qualified type name for which the type name is dependent.|
|[DependentScopeDeclRefExpr](/api/cppsharp/ast/dependentscopedeclrefexpr)||
|[DependentTemplateSpecializationType](/api/cppsharp/ast/dependenttemplatespecializationtype)|Represents a C++ dependent template specialization type.|
|[DesignatedInitExpr](/api/cppsharp/ast/designatedinitexpr)||
|[DesignatedInitUpdateExpr](/api/cppsharp/ast/designatedinitupdateexpr)||
|[DoStmt](/api/cppsharp/ast/dostmt)||
|[Enumeration](/api/cppsharp/ast/enumeration)|Represents a C/C++ enumeration declaration.|
|[Event](/api/cppsharp/ast/event)||
|[ExplicitCastExpr](/api/cppsharp/ast/explicitcastexpr)||
|[Expr](/api/cppsharp/ast/expr)||
|[ExpressionObsolete](/api/cppsharp/ast/expressionobsolete)||
|[ExpressionTraitExpr](/api/cppsharp/ast/expressiontraitexpr)||
|[ExprWithCleanups](/api/cppsharp/ast/exprwithcleanups)||
|[ExtVectorElementExpr](/api/cppsharp/ast/extvectorelementexpr)||
|[Field](/api/cppsharp/ast/field)|Represents a a C/C++ record field Decl.|
|[FixedPointLiteral](/api/cppsharp/ast/fixedpointliteral)||
|[FloatingLiteral](/api/cppsharp/ast/floatingliteral)||
|[ForStmt](/api/cppsharp/ast/forstmt)||
|[Friend](/api/cppsharp/ast/friend)||
|[FullComment](/api/cppsharp/ast/fullcomment)|A full comment attached to a declaration, contains block content.|
|[FullExpr](/api/cppsharp/ast/fullexpr)||
|[Function](/api/cppsharp/ast/function)||
|[FunctionExtensions](/api/cppsharp/ast/functionextensions)||
|[FunctionParmPackExpr](/api/cppsharp/ast/functionparmpackexpr)||
|[FunctionTemplate](/api/cppsharp/ast/functiontemplate)|Declaration of a template function.|
|[FunctionTemplateSpecialization](/api/cppsharp/ast/functiontemplatespecialization)|Represents a function template specialization, which refers to a function template with a given set of template arguments.|
|[FunctionType](/api/cppsharp/ast/functiontype)|Represents an C/C++ function type.|
|[GCCAsmStmt](/api/cppsharp/ast/gccasmstmt)||
|[GenericSelectionExpr](/api/cppsharp/ast/genericselectionexpr)||
|[GNUNullExpr](/api/cppsharp/ast/gnunullexpr)||
|[GotoStmt](/api/cppsharp/ast/gotostmt)||
|[HTMLEndTagComment](/api/cppsharp/ast/htmlendtagcomment)|A closing HTML tag.|
|[HTMLStartTagComment](/api/cppsharp/ast/htmlstarttagcomment)|An opening HTML tag with attributes.|
|[HTMLTagComment](/api/cppsharp/ast/htmltagcomment)|Abstract class for opening and closing HTML tags. HTML tags are always treated as inline content (regardless HTML semantics); opening and closing tags are not matched.|
|[IfStmt](/api/cppsharp/ast/ifstmt)||
|[ImaginaryLiteral](/api/cppsharp/ast/imaginaryliteral)||
|[ImplicitCastExpr](/api/cppsharp/ast/implicitcastexpr)||
|[ImplicitValueInitExpr](/api/cppsharp/ast/implicitvalueinitexpr)||
|[IndirectGotoStmt](/api/cppsharp/ast/indirectgotostmt)||
|[InitListExpr](/api/cppsharp/ast/initlistexpr)||
|[InjectedClassNameType](/api/cppsharp/ast/injectedclassnametype)|The injected class name of a C++ class template or class template partial specialization.|
|[InlineCommandComment](/api/cppsharp/ast/inlinecommandcomment)|A command with word-like arguments that is considered inline content.|
|[InlineContentComment](/api/cppsharp/ast/inlinecontentcomment)|Inline content (contained within a block).|
|[IntegerLiteral](/api/cppsharp/ast/integerliteral)||
|[LabelStmt](/api/cppsharp/ast/labelstmt)||
|[LambdaExpr](/api/cppsharp/ast/lambdaexpr)||
|[LayoutBase](/api/cppsharp/ast/layoutbase)||
|[LayoutField](/api/cppsharp/ast/layoutfield)||
|[MacroDefinition](/api/cppsharp/ast/macrodefinition)|Represents a C preprocessor macro definition.|
|[MacroExpansion](/api/cppsharp/ast/macroexpansion)|Represents a C preprocessor macro expansion.|
|[MaterializeTemporaryExpr](/api/cppsharp/ast/materializetemporaryexpr)||
|[MemberExpr](/api/cppsharp/ast/memberexpr)||
|[MemberPointerType](/api/cppsharp/ast/memberpointertype)|Represents a C++ member function pointer type.|
|[Method](/api/cppsharp/ast/method)|Represents a C++ record method declaration.|
|[Module](/api/cppsharp/ast/module)||
|[MSAsmStmt](/api/cppsharp/ast/msasmstmt)||
|[MSDependentExistsStmt](/api/cppsharp/ast/msdependentexistsstmt)||
|[MSPropertyRefExpr](/api/cppsharp/ast/mspropertyrefexpr)||
|[MSPropertySubscriptExpr](/api/cppsharp/ast/mspropertysubscriptexpr)||
|[Namespace](/api/cppsharp/ast/namespace)|Represents a C++ namespace.|
|[NativeLibrary](/api/cppsharp/ast/nativelibrary)|Represents a shared library or a static library archive.|
|[NoInitExpr](/api/cppsharp/ast/noinitexpr)||
|[NonTypeTemplateParameter](/api/cppsharp/ast/nontypetemplateparameter)|Represents a non-type template parameter.|
|[NullStmt](/api/cppsharp/ast/nullstmt)||
|[OffsetOfExpr](/api/cppsharp/ast/offsetofexpr)||
|[OpaqueValueExpr](/api/cppsharp/ast/opaquevalueexpr)||
|[OverloadExpr](/api/cppsharp/ast/overloadexpr)||
|[PackExpansionExpr](/api/cppsharp/ast/packexpansionexpr)||
|[PackExpansionType](/api/cppsharp/ast/packexpansiontype)||
|[ParagraphComment](/api/cppsharp/ast/paragraphcomment)|A single paragraph that contains inline content.|
|[ParamCommandComment](/api/cppsharp/ast/paramcommandcomment)|Doxygen \param command.|
|[Parameter](/api/cppsharp/ast/parameter)||
|[ParameterTypeComparer](/api/cppsharp/ast/parametertypecomparer)||
|[ParenExpr](/api/cppsharp/ast/parenexpr)||
|[ParenListExpr](/api/cppsharp/ast/parenlistexpr)||
|[PointerType](/api/cppsharp/ast/pointertype)|Represents a C++ pointer/reference type.|
|[PredefinedExpr](/api/cppsharp/ast/predefinedexpr)||
|[PreprocessedEntity](/api/cppsharp/ast/preprocessedentity)|Base class that describes a preprocessed entity, which may be a preprocessor directive or macro expansion.|
|[Property](/api/cppsharp/ast/property)|Represents a C++ property.|
|[PropertyExtensions](/api/cppsharp/ast/propertyextensions)||
|[PseudoObjectExpr](/api/cppsharp/ast/pseudoobjectexpr)||
|[RawComment](/api/cppsharp/ast/rawcomment)|Represents a raw C++ comment.|
|[ReturnStmt](/api/cppsharp/ast/returnstmt)||
|[SEHExceptStmt](/api/cppsharp/ast/sehexceptstmt)||
|[SEHFinallyStmt](/api/cppsharp/ast/sehfinallystmt)||
|[SEHLeaveStmt](/api/cppsharp/ast/sehleavestmt)||
|[SEHTryStmt](/api/cppsharp/ast/sehtrystmt)||
|[ShuffleVectorExpr](/api/cppsharp/ast/shufflevectorexpr)||
|[SizeOfPackExpr](/api/cppsharp/ast/sizeofpackexpr)||
|[Statement](/api/cppsharp/ast/statement)||
|[Stmt](/api/cppsharp/ast/stmt)||
|[StmtExpr](/api/cppsharp/ast/stmtexpr)||
|[StringLiteral](/api/cppsharp/ast/stringliteral)||
|[SubstNonTypeTemplateParmExpr](/api/cppsharp/ast/substnontypetemplateparmexpr)||
|[SubstNonTypeTemplateParmPackExpr](/api/cppsharp/ast/substnontypetemplateparmpackexpr)||
|[SwitchCase](/api/cppsharp/ast/switchcase)||
|[SwitchStmt](/api/cppsharp/ast/switchstmt)||
|[SymbolContext](/api/cppsharp/ast/symbolcontext)||
|[TagType](/api/cppsharp/ast/tagtype)|Represents a C++ tag type.|
|[TargetTriple](/api/cppsharp/ast/targettriple)||
|[Template](/api/cppsharp/ast/template)|The base class of all kinds of template declarations (e.g., class, function, etc.).|
|[TemplateArgument](/api/cppsharp/ast/templateargument)|Represents a template argument within a class template specialization.|
|[TemplateParameterSubstitutionType](/api/cppsharp/ast/templateparametersubstitutiontype)|Represents the result of substituting a type for a template type parameter.|
|[TemplateParameterType](/api/cppsharp/ast/templateparametertype)|Represents a C++ template parameter type.|
|[TemplateSpecializationType](/api/cppsharp/ast/templatespecializationtype)|Represents a C++ template specialization type.|
|[TemplateTemplateParameter](/api/cppsharp/ast/templatetemplateparameter)||
|[TextComment](/api/cppsharp/ast/textcomment)|Plain text.|
|[TParamCommandComment](/api/cppsharp/ast/tparamcommandcomment)|Doxygen \tparam command, describes a template parameter.|
|[TranslationUnit](/api/cppsharp/ast/translationunit)|Represents a source code unit.|
|[Type](/api/cppsharp/ast/type)|Represents a C++ type.|
|[TypeAlias](/api/cppsharp/ast/typealias)|Represents a type alias in C++.|
|[TypeAliasTemplate](/api/cppsharp/ast/typealiastemplate)|Declaration of a type alias template.|
|[TypedefDecl](/api/cppsharp/ast/typedefdecl)|Represents a type definition in C++.|
|[TypedefNameDecl](/api/cppsharp/ast/typedefnamedecl)|Base class for declarations which introduce a typedef-name.|
|[TypedefType](/api/cppsharp/ast/typedeftype)|Represents a C/C++ typedef type.|
|[TypeReference](/api/cppsharp/ast/typereference)|Represents a type reference.|
|[TypeTemplateParameter](/api/cppsharp/ast/typetemplateparameter)|Represents a type template parameter.|
|[TypeTraitExpr](/api/cppsharp/ast/typetraitexpr)||
|[TypoExpr](/api/cppsharp/ast/typoexpr)||
|[UnaryExprOrTypeTraitExpr](/api/cppsharp/ast/unaryexprortypetraitexpr)||
|[UnaryOperator](/api/cppsharp/ast/unaryoperator)||
|[UnaryTransformType](/api/cppsharp/ast/unarytransformtype)||
|[UnresolvedLookupExpr](/api/cppsharp/ast/unresolvedlookupexpr)||
|[UnresolvedMemberExpr](/api/cppsharp/ast/unresolvedmemberexpr)||
|[UnresolvedUsingType](/api/cppsharp/ast/unresolvedusingtype)||
|[UnresolvedUsingTypename](/api/cppsharp/ast/unresolvedusingtypename)|Represents a dependent using declaration which was marked with typename.|
|[UnsupportedType](/api/cppsharp/ast/unsupportedtype)||
|[UserDefinedLiteral](/api/cppsharp/ast/userdefinedliteral)||
|[VAArgExpr](/api/cppsharp/ast/vaargexpr)||
|[Variable](/api/cppsharp/ast/variable)||
|[VarTemplate](/api/cppsharp/ast/vartemplate)|Represents a declaration of a variable template.|
|[VarTemplatePartialSpecialization](/api/cppsharp/ast/vartemplatepartialspecialization)|Represents a variable template partial specialization, which refers to a variable template with a given partial set of template arguments.|
|[VarTemplateSpecialization](/api/cppsharp/ast/vartemplatespecialization)|Represents a var template specialization, which refers to a var template with a given set of template arguments.|
|[VectorType](/api/cppsharp/ast/vectortype)||
|[VerbatimBlockComment](/api/cppsharp/ast/verbatimblockcomment)|A verbatim block command (e. g., preformatted code). Verbatim block has an opening and a closing command and contains multiple lines of text (VerbatimBlockLineComment nodes).|
|[VerbatimBlockLineComment](/api/cppsharp/ast/verbatimblocklinecomment)|A line of text contained in a verbatim block.|
|[VerbatimLineComment](/api/cppsharp/ast/verbatimlinecomment)|A verbatim line command. Verbatim line has an opening command, a single line of text (up to the newline after the opening command) and has no closing command.|
|[VTableLayout](/api/cppsharp/ast/vtablelayout)|Represents a C++ virtual table layout.|
|[WhileStmt](/api/cppsharp/ast/whilestmt)||

## Enums

|Name|Description|
|:---|:---|
|[AccessSpecifier](/api/cppsharp/ast/accessspecifier)||
|[ArchType](/api/cppsharp/ast/archtype)||
|[BinaryOperatorKind](/api/cppsharp/ast/binaryoperatorkind)||
|[CallingConvention](/api/cppsharp/ast/callingconvention)||
|[CastKind](/api/cppsharp/ast/castkind)||
|[ClassType](/api/cppsharp/ast/classtype)||
|[CommentCommandKind](/api/cppsharp/ast/commentcommandkind)|Kinds of comment commands. Synchronized from "clang/AST/CommentCommandList.inc".|
|[CommentKind](/api/cppsharp/ast/commentkind)|Comment kind.|
|[CppAbi](/api/cppsharp/ast/cppabi)||
|[CXXMethodKind](/api/cppsharp/ast/cxxmethodkind)||
|[CXXOperatorArity](/api/cppsharp/ast/cxxoperatorarity)||
|[CXXOperatorKind](/api/cppsharp/ast/cxxoperatorkind)||
|[DocumentationCommentKind](/api/cppsharp/ast/documentationcommentkind)||
|[ExceptionSpecType](/api/cppsharp/ast/exceptionspectype)||
|[FriendKind](/api/cppsharp/ast/friendkind)||
|[FunctionSynthKind](/api/cppsharp/ast/functionsynthkind)||
|[GenerationKind](/api/cppsharp/ast/generationkind)|Kind of the generated declaration|
|[MacroLocation](/api/cppsharp/ast/macrolocation)||
|[MethodConversionKind](/api/cppsharp/ast/methodconversionkind)||
|[ObjCBridgeCastKind](/api/cppsharp/ast/objcbridgecastkind)||
|[OverloadedOperatorKind](/api/cppsharp/ast/overloadedoperatorkind)||
|[ParameterKind](/api/cppsharp/ast/parameterkind)||
|[ParameterUsage](/api/cppsharp/ast/parameterusage)||
|[PrimitiveType](/api/cppsharp/ast/primitivetype)|Represents the C++ built-in types.|
|[RecordArgABI](/api/cppsharp/ast/recordargabi)||
|[RefQualifier](/api/cppsharp/ast/refqualifier)||
|[StatementClass](/api/cppsharp/ast/statementclass)||
|[StmtClass](/api/cppsharp/ast/stmtclass)||
|[TagKind](/api/cppsharp/ast/tagkind)||
|[TemplateSpecializationKind](/api/cppsharp/ast/templatespecializationkind)|Describes the kind of template specialization that a particular template specialization declaration represents.|
|[TypeQualifiersMode](/api/cppsharp/ast/typequalifiersmode)||
|[UnaryExprOrTypeTrait](/api/cppsharp/ast/unaryexprortypetrait)||
|[UnaryOperatorKind](/api/cppsharp/ast/unaryoperatorkind)||
|[VisitFlags](/api/cppsharp/ast/visitflags)||
|[VTableComponentKind](/api/cppsharp/ast/vtablecomponentkind)|Virtual table component kind.|

## Interfaces

|Name|Description|
|:---|:---|
|[IAstVisited](/api/cppsharp/ast/iastvisited)||
|[IAstVisitor](/api/cppsharp/ast/iastvisitor)||
|[ICommentVisitor](/api/cppsharp/ast/icommentvisitor)|Visitor for comments.|
|[IDeclVisitor](/api/cppsharp/ast/ideclvisitor)||
|[IExpressionPrinter](/api/cppsharp/ast/iexpressionprinter-1)||
|[IExpressionPrinter](/api/cppsharp/ast/iexpressionprinter-2)||
|[IExpressionVisitorObsolete](/api/cppsharp/ast/iexpressionvisitorobsolete)||
|[IMangledDecl](/api/cppsharp/ast/imangleddecl)||
|[INamedDecl](/api/cppsharp/ast/inameddecl)||
|[IRedeclarableDecl](/api/cppsharp/ast/iredeclarabledecl)||
|[IStmtVisitor](/api/cppsharp/ast/istmtvisitor)||
|[ITypedDecl](/api/cppsharp/ast/itypeddecl)||
|[ITypeVisitor](/api/cppsharp/ast/itypevisitor)||

## Namespaces

|Name|Description|
|:---|:---|
|[CppSharp.AST.Extensions](/api/cppsharp/ast/extensions)||

## Structs

|Name|Description|
|:---|:---|
|[QualifiedType](/api/cppsharp/ast/qualifiedtype)|Represents a qualified C++ type.|
|[SourceLocation](/api/cppsharp/ast/sourcelocation)|Encodes a location in the source. The SourceManager can decode this to get at the full include stack, line and column information.|
|[SourceRange](/api/cppsharp/ast/sourcerange)||
|[TypeQualifiers](/api/cppsharp/ast/typequalifiers)|Represents C++ type qualifiers.|
|[VFTableInfo](/api/cppsharp/ast/vftableinfo)|Contains information about virtual function pointers.|
|[VTableComponent](/api/cppsharp/ast/vtablecomponent)|Represents a C++ virtual table component.|

