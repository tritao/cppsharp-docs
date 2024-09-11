---
title: AstVisitor
slug: api/cppsharp.ast.astvisitor
---
Class in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Object`

## Summary


Base class for AST visitors.
You can override the methods to customize the behaviour, by default
this will visit all the nodes in a default way that should be useful
for a lot of applications.


```csharp
public abstract class AstVisitor : IAstVisitor<bool>, IAstVisited
```

## Methods

|Name|Description|
|:---|:---|
|[AlreadyVisited\(Declaration\)](/api/cppsharp/ast/astvisitor/alreadyvisited-2)||
|[AlreadyVisited\(Stmt\)](/api/cppsharp/ast/astvisitor/alreadyvisited-3)||
|[AlreadyVisited\(Type\)](/api/cppsharp/ast/astvisitor/alreadyvisited-1)||
|[VisitAbstractConditionalOperator\(AbstractConditionalOperator\)](/api/cppsharp/ast/astvisitor/visitabstractconditionaloperator)||
|[VisitAddrLabelExpr\(AddrLabelExpr\)](/api/cppsharp/ast/astvisitor/visitaddrlabelexpr)||
|[VisitArrayInitIndexExpr\(ArrayInitIndexExpr\)](/api/cppsharp/ast/astvisitor/visitarrayinitindexexpr)||
|[VisitArrayInitLoopExpr\(ArrayInitLoopExpr\)](/api/cppsharp/ast/astvisitor/visitarrayinitloopexpr)||
|[VisitArraySubscriptExpr\(ArraySubscriptExpr\)](/api/cppsharp/ast/astvisitor/visitarraysubscriptexpr)||
|[VisitArrayType\(ArrayType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitarraytype)||
|[VisitArrayTypeTraitExpr\(ArrayTypeTraitExpr\)](/api/cppsharp/ast/astvisitor/visitarraytypetraitexpr)||
|[VisitAsmStmt\(AsmStmt\)](/api/cppsharp/ast/astvisitor/visitasmstmt)||
|[VisitAsTypeExpr\(AsTypeExpr\)](/api/cppsharp/ast/astvisitor/visitastypeexpr)||
|[VisitAtomicExpr\(AtomicExpr\)](/api/cppsharp/ast/astvisitor/visitatomicexpr)||
|[VisitAttributedStmt\(AttributedStmt\)](/api/cppsharp/ast/astvisitor/visitattributedstmt)||
|[VisitAttributedType\(AttributedType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitattributedtype)||
|[VisitBinaryConditionalOperator\(BinaryConditionalOperator\)](/api/cppsharp/ast/astvisitor/visitbinaryconditionaloperator)||
|[VisitBinaryOperator\(BinaryOperator\)](/api/cppsharp/ast/astvisitor/visitbinaryoperator)||
|[VisitBlockExpr\(BlockExpr\)](/api/cppsharp/ast/astvisitor/visitblockexpr)||
|[VisitBreakStmt\(BreakStmt\)](/api/cppsharp/ast/astvisitor/visitbreakstmt)||
|[VisitBuiltinType\(BuiltinType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitbuiltintype)||
|[VisitCallExpr\(CallExpr\)](/api/cppsharp/ast/astvisitor/visitcallexpr)||
|[VisitCapturedStmt\(CapturedStmt\)](/api/cppsharp/ast/astvisitor/visitcapturedstmt)||
|[VisitCaseStmt\(CaseStmt\)](/api/cppsharp/ast/astvisitor/visitcasestmt)||
|[VisitCastExpr\(CastExpr\)](/api/cppsharp/ast/astvisitor/visitcastexpr)||
|[VisitCharacterLiteral\(CharacterLiteral\)](/api/cppsharp/ast/astvisitor/visitcharacterliteral)||
|[VisitChooseExpr\(ChooseExpr\)](/api/cppsharp/ast/astvisitor/visitchooseexpr)||
|[VisitCILType\(CILType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitciltype)||
|[VisitClassDecl\(Class\)](/api/cppsharp/ast/astvisitor/visitclassdecl)||
|[VisitClassTemplateDecl\(ClassTemplate\)](/api/cppsharp/ast/astvisitor/visitclasstemplatedecl)||
|[VisitClassTemplateSpecializationDecl\(ClassTemplateSpecialization\)](/api/cppsharp/ast/astvisitor/visitclasstemplatespecializationdecl)||
|[VisitCoawaitExpr\(CoawaitExpr\)](/api/cppsharp/ast/astvisitor/visitcoawaitexpr)||
|[VisitCompoundAssignOperator\(CompoundAssignOperator\)](/api/cppsharp/ast/astvisitor/visitcompoundassignoperator)||
|[VisitCompoundLiteralExpr\(CompoundLiteralExpr\)](/api/cppsharp/ast/astvisitor/visitcompoundliteralexpr)||
|[VisitCompoundStmt\(CompoundStmt\)](/api/cppsharp/ast/astvisitor/visitcompoundstmt)||
|[VisitConditionalOperator\(ConditionalOperator\)](/api/cppsharp/ast/astvisitor/visitconditionaloperator)||
|[VisitConstantExpr\(ConstantExpr\)](/api/cppsharp/ast/astvisitor/visitconstantexpr)||
|[VisitContinueStmt\(ContinueStmt\)](/api/cppsharp/ast/astvisitor/visitcontinuestmt)||
|[VisitConvertVectorExpr\(ConvertVectorExpr\)](/api/cppsharp/ast/astvisitor/visitconvertvectorexpr)||
|[VisitCoreturnStmt\(CoreturnStmt\)](/api/cppsharp/ast/astvisitor/visitcoreturnstmt)||
|[VisitCoroutineBodyStmt\(CoroutineBodyStmt\)](/api/cppsharp/ast/astvisitor/visitcoroutinebodystmt)||
|[VisitCoroutineSuspendExpr\(CoroutineSuspendExpr\)](/api/cppsharp/ast/astvisitor/visitcoroutinesuspendexpr)||
|[VisitCoyieldExpr\(CoyieldExpr\)](/api/cppsharp/ast/astvisitor/visitcoyieldexpr)||
|[VisitCStyleCastExpr\(CStyleCastExpr\)](/api/cppsharp/ast/astvisitor/visitcstylecastexpr)||
|[VisitCUDAKernelCallExpr\(CUDAKernelCallExpr\)](/api/cppsharp/ast/astvisitor/visitcudakernelcallexpr)||
|[VisitCXXBindTemporaryExpr\(CXXBindTemporaryExpr\)](/api/cppsharp/ast/astvisitor/visitcxxbindtemporaryexpr)||
|[VisitCXXBoolLiteralExpr\(CXXBoolLiteralExpr\)](/api/cppsharp/ast/astvisitor/visitcxxboolliteralexpr)||
|[VisitCXXCatchStmt\(CXXCatchStmt\)](/api/cppsharp/ast/astvisitor/visitcxxcatchstmt)||
|[VisitCXXConstCastExpr\(CXXConstCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxconstcastexpr)||
|[VisitCXXConstructExpr\(CXXConstructExpr\)](/api/cppsharp/ast/astvisitor/visitcxxconstructexpr)||
|[VisitCXXDefaultArgExpr\(CXXDefaultArgExpr\)](/api/cppsharp/ast/astvisitor/visitcxxdefaultargexpr)||
|[VisitCXXDefaultInitExpr\(CXXDefaultInitExpr\)](/api/cppsharp/ast/astvisitor/visitcxxdefaultinitexpr)||
|[VisitCXXDeleteExpr\(CXXDeleteExpr\)](/api/cppsharp/ast/astvisitor/visitcxxdeleteexpr)||
|[VisitCXXDependentScopeMemberExpr\(CXXDependentScopeMemberExpr\)](/api/cppsharp/ast/astvisitor/visitcxxdependentscopememberexpr)||
|[VisitCXXDynamicCastExpr\(CXXDynamicCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxdynamiccastexpr)||
|[VisitCXXFoldExpr\(CXXFoldExpr\)](/api/cppsharp/ast/astvisitor/visitcxxfoldexpr)||
|[VisitCXXForRangeStmt\(CXXForRangeStmt\)](/api/cppsharp/ast/astvisitor/visitcxxforrangestmt)||
|[VisitCXXFunctionalCastExpr\(CXXFunctionalCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxfunctionalcastexpr)||
|[VisitCXXInheritedCtorInitExpr\(CXXInheritedCtorInitExpr\)](/api/cppsharp/ast/astvisitor/visitcxxinheritedctorinitexpr)||
|[VisitCXXMemberCallExpr\(CXXMemberCallExpr\)](/api/cppsharp/ast/astvisitor/visitcxxmembercallexpr)||
|[VisitCXXNamedCastExpr\(CXXNamedCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxnamedcastexpr)||
|[VisitCXXNewExpr\(CXXNewExpr\)](/api/cppsharp/ast/astvisitor/visitcxxnewexpr)||
|[VisitCXXNoexceptExpr\(CXXNoexceptExpr\)](/api/cppsharp/ast/astvisitor/visitcxxnoexceptexpr)||
|[VisitCXXNullPtrLiteralExpr\(CXXNullPtrLiteralExpr\)](/api/cppsharp/ast/astvisitor/visitcxxnullptrliteralexpr)||
|[VisitCXXOperatorCallExpr\(CXXOperatorCallExpr\)](/api/cppsharp/ast/astvisitor/visitcxxoperatorcallexpr)||
|[VisitCXXPseudoDestructorExpr\(CXXPseudoDestructorExpr\)](/api/cppsharp/ast/astvisitor/visitcxxpseudodestructorexpr)||
|[VisitCXXReinterpretCastExpr\(CXXReinterpretCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxreinterpretcastexpr)||
|[VisitCXXScalarValueInitExpr\(CXXScalarValueInitExpr\)](/api/cppsharp/ast/astvisitor/visitcxxscalarvalueinitexpr)||
|[VisitCXXStaticCastExpr\(CXXStaticCastExpr\)](/api/cppsharp/ast/astvisitor/visitcxxstaticcastexpr)||
|[VisitCXXStdInitializerListExpr\(CXXStdInitializerListExpr\)](/api/cppsharp/ast/astvisitor/visitcxxstdinitializerlistexpr)||
|[VisitCXXTemporaryObjectExpr\(CXXTemporaryObjectExpr\)](/api/cppsharp/ast/astvisitor/visitcxxtemporaryobjectexpr)||
|[VisitCXXThisExpr\(CXXThisExpr\)](/api/cppsharp/ast/astvisitor/visitcxxthisexpr)||
|[VisitCXXThrowExpr\(CXXThrowExpr\)](/api/cppsharp/ast/astvisitor/visitcxxthrowexpr)||
|[VisitCXXTryStmt\(CXXTryStmt\)](/api/cppsharp/ast/astvisitor/visitcxxtrystmt)||
|[VisitCXXTypeidExpr\(CXXTypeidExpr\)](/api/cppsharp/ast/astvisitor/visitcxxtypeidexpr)||
|[VisitCXXUnresolvedConstructExpr\(CXXUnresolvedConstructExpr\)](/api/cppsharp/ast/astvisitor/visitcxxunresolvedconstructexpr)||
|[VisitCXXUuidofExpr\(CXXUuidofExpr\)](/api/cppsharp/ast/astvisitor/visitcxxuuidofexpr)||
|[VisitDecayedType\(DecayedType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitdecayedtype)||
|[VisitDeclaration\(Declaration,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitdeclaration-1)||
|[VisitDeclaration\(Declaration\)](/api/cppsharp/ast/astvisitor/visitdeclaration-2)||
|[VisitDeclarationContext\(DeclarationContext\)](/api/cppsharp/ast/astvisitor/visitdeclarationcontext)||
|[VisitDeclRefExpr\(DeclRefExpr\)](/api/cppsharp/ast/astvisitor/visitdeclrefexpr)||
|[VisitDeclStmt\(DeclStmt\)](/api/cppsharp/ast/astvisitor/visitdeclstmt)||
|[VisitDefaultStmt\(DefaultStmt\)](/api/cppsharp/ast/astvisitor/visitdefaultstmt)||
|[VisitDependentCoawaitExpr\(DependentCoawaitExpr\)](/api/cppsharp/ast/astvisitor/visitdependentcoawaitexpr)||
|[VisitDependentNameType\(DependentNameType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitdependentnametype)||
|[VisitDependentScopeDeclRefExpr\(DependentScopeDeclRefExpr\)](/api/cppsharp/ast/astvisitor/visitdependentscopedeclrefexpr)||
|[VisitDependentTemplateSpecializationType\(DependentTemplateSpecializationType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitdependenttemplatespecializationtype)||
|[VisitDesignatedInitExpr\(DesignatedInitExpr\)](/api/cppsharp/ast/astvisitor/visitdesignatedinitexpr)||
|[VisitDesignatedInitUpdateExpr\(DesignatedInitUpdateExpr\)](/api/cppsharp/ast/astvisitor/visitdesignatedinitupdateexpr)||
|[VisitDoStmt\(DoStmt\)](/api/cppsharp/ast/astvisitor/visitdostmt)||
|[VisitEnumDecl\(Enumeration\)](/api/cppsharp/ast/astvisitor/visitenumdecl)||
|[VisitEnumItemDecl\(Enumeration.Item\)](/api/cppsharp/ast/astvisitor/visitenumitemdecl)||
|[VisitEvent\(Event\)](/api/cppsharp/ast/astvisitor/visitevent)||
|[VisitExplicitCastExpr\(ExplicitCastExpr\)](/api/cppsharp/ast/astvisitor/visitexplicitcastexpr)||
|[VisitExpr\(Expr\)](/api/cppsharp/ast/astvisitor/visitexpr)||
|[VisitExpressionTraitExpr\(ExpressionTraitExpr\)](/api/cppsharp/ast/astvisitor/visitexpressiontraitexpr)||
|[VisitExprWithCleanups\(ExprWithCleanups\)](/api/cppsharp/ast/astvisitor/visitexprwithcleanups)||
|[VisitExtVectorElementExpr\(ExtVectorElementExpr\)](/api/cppsharp/ast/astvisitor/visitextvectorelementexpr)||
|[VisitFieldDecl\(Field\)](/api/cppsharp/ast/astvisitor/visitfielddecl)||
|[VisitFixedPointLiteral\(FixedPointLiteral\)](/api/cppsharp/ast/astvisitor/visitfixedpointliteral)||
|[VisitFloatingLiteral\(FloatingLiteral\)](/api/cppsharp/ast/astvisitor/visitfloatingliteral)||
|[VisitForStmt\(ForStmt\)](/api/cppsharp/ast/astvisitor/visitforstmt)||
|[VisitFriend\(Friend\)](/api/cppsharp/ast/astvisitor/visitfriend)||
|[VisitFullExpr\(FullExpr\)](/api/cppsharp/ast/astvisitor/visitfullexpr)||
|[VisitFunctionDecl\(Function\)](/api/cppsharp/ast/astvisitor/visitfunctiondecl)||
|[VisitFunctionParmPackExpr\(FunctionParmPackExpr\)](/api/cppsharp/ast/astvisitor/visitfunctionparmpackexpr)||
|[VisitFunctionTemplateDecl\(FunctionTemplate\)](/api/cppsharp/ast/astvisitor/visitfunctiontemplatedecl)||
|[VisitFunctionTemplateSpecializationDecl\(FunctionTemplateSpecialization\)](/api/cppsharp/ast/astvisitor/visitfunctiontemplatespecializationdecl)||
|[VisitFunctionType\(FunctionType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitfunctiontype)||
|[VisitGCCAsmStmt\(GCCAsmStmt\)](/api/cppsharp/ast/astvisitor/visitgccasmstmt)||
|[VisitGenericSelectionExpr\(GenericSelectionExpr\)](/api/cppsharp/ast/astvisitor/visitgenericselectionexpr)||
|[VisitGNUNullExpr\(GNUNullExpr\)](/api/cppsharp/ast/astvisitor/visitgnunullexpr)||
|[VisitGotoStmt\(GotoStmt\)](/api/cppsharp/ast/astvisitor/visitgotostmt)||
|[VisitIfStmt\(IfStmt\)](/api/cppsharp/ast/astvisitor/visitifstmt)||
|[VisitImaginaryLiteral\(ImaginaryLiteral\)](/api/cppsharp/ast/astvisitor/visitimaginaryliteral)||
|[VisitImplicitCastExpr\(ImplicitCastExpr\)](/api/cppsharp/ast/astvisitor/visitimplicitcastexpr)||
|[VisitImplicitValueInitExpr\(ImplicitValueInitExpr\)](/api/cppsharp/ast/astvisitor/visitimplicitvalueinitexpr)||
|[VisitIndirectGotoStmt\(IndirectGotoStmt\)](/api/cppsharp/ast/astvisitor/visitindirectgotostmt)||
|[VisitInitListExpr\(InitListExpr\)](/api/cppsharp/ast/astvisitor/visitinitlistexpr)||
|[VisitInjectedClassNameType\(InjectedClassNameType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitinjectedclassnametype)||
|[VisitIntegerLiteral\(IntegerLiteral\)](/api/cppsharp/ast/astvisitor/visitintegerliteral)||
|[VisitLabelStmt\(LabelStmt\)](/api/cppsharp/ast/astvisitor/visitlabelstmt)||
|[VisitLambdaExpr\(LambdaExpr\)](/api/cppsharp/ast/astvisitor/visitlambdaexpr)||
|[VisitMacroDefinition\(MacroDefinition\)](/api/cppsharp/ast/astvisitor/visitmacrodefinition)||
|[VisitMaterializeTemporaryExpr\(MaterializeTemporaryExpr\)](/api/cppsharp/ast/astvisitor/visitmaterializetemporaryexpr)||
|[VisitMemberExpr\(MemberExpr\)](/api/cppsharp/ast/astvisitor/visitmemberexpr)||
|[VisitMemberPointerType\(MemberPointerType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitmemberpointertype)||
|[VisitMethodDecl\(Method\)](/api/cppsharp/ast/astvisitor/visitmethoddecl)||
|[VisitMSAsmStmt\(MSAsmStmt\)](/api/cppsharp/ast/astvisitor/visitmsasmstmt)||
|[VisitMSDependentExistsStmt\(MSDependentExistsStmt\)](/api/cppsharp/ast/astvisitor/visitmsdependentexistsstmt)||
|[VisitMSPropertyRefExpr\(MSPropertyRefExpr\)](/api/cppsharp/ast/astvisitor/visitmspropertyrefexpr)||
|[VisitMSPropertySubscriptExpr\(MSPropertySubscriptExpr\)](/api/cppsharp/ast/astvisitor/visitmspropertysubscriptexpr)||
|[VisitNamespace\(Namespace\)](/api/cppsharp/ast/astvisitor/visitnamespace)||
|[VisitNoInitExpr\(NoInitExpr\)](/api/cppsharp/ast/astvisitor/visitnoinitexpr)||
|[VisitNonTypeTemplateParameterDecl\(NonTypeTemplateParameter\)](/api/cppsharp/ast/astvisitor/visitnontypetemplateparameterdecl)||
|[VisitNullStmt\(NullStmt\)](/api/cppsharp/ast/astvisitor/visitnullstmt)||
|[VisitOffsetOfExpr\(OffsetOfExpr\)](/api/cppsharp/ast/astvisitor/visitoffsetofexpr)||
|[VisitOpaqueValueExpr\(OpaqueValueExpr\)](/api/cppsharp/ast/astvisitor/visitopaquevalueexpr)||
|[VisitOverloadExpr\(OverloadExpr\)](/api/cppsharp/ast/astvisitor/visitoverloadexpr)||
|[VisitPackExpansionExpr\(PackExpansionExpr\)](/api/cppsharp/ast/astvisitor/visitpackexpansionexpr)||
|[VisitPackExpansionType\(PackExpansionType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitpackexpansiontype)||
|[VisitParameterDecl\(Parameter\)](/api/cppsharp/ast/astvisitor/visitparameterdecl)||
|[VisitParenExpr\(ParenExpr\)](/api/cppsharp/ast/astvisitor/visitparenexpr)||
|[VisitParenListExpr\(ParenListExpr\)](/api/cppsharp/ast/astvisitor/visitparenlistexpr)||
|[VisitPointerType\(PointerType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitpointertype)||
|[VisitPredefinedExpr\(PredefinedExpr\)](/api/cppsharp/ast/astvisitor/visitpredefinedexpr)||
|[VisitPrimitiveType\(PrimitiveType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitprimitivetype)||
|[VisitProperty\(Property\)](/api/cppsharp/ast/astvisitor/visitproperty)||
|[VisitPseudoObjectExpr\(PseudoObjectExpr\)](/api/cppsharp/ast/astvisitor/visitpseudoobjectexpr)||
|[VisitQualifiedType\(QualifiedType\)](/api/cppsharp/ast/astvisitor/visitqualifiedtype)||
|[VisitReturnStmt\(ReturnStmt\)](/api/cppsharp/ast/astvisitor/visitreturnstmt)||
|[VisitSEHExceptStmt\(SEHExceptStmt\)](/api/cppsharp/ast/astvisitor/visitsehexceptstmt)||
|[VisitSEHFinallyStmt\(SEHFinallyStmt\)](/api/cppsharp/ast/astvisitor/visitsehfinallystmt)||
|[VisitSEHLeaveStmt\(SEHLeaveStmt\)](/api/cppsharp/ast/astvisitor/visitsehleavestmt)||
|[VisitSEHTryStmt\(SEHTryStmt\)](/api/cppsharp/ast/astvisitor/visitsehtrystmt)||
|[VisitShuffleVectorExpr\(ShuffleVectorExpr\)](/api/cppsharp/ast/astvisitor/visitshufflevectorexpr)||
|[VisitSizeOfPackExpr\(SizeOfPackExpr\)](/api/cppsharp/ast/astvisitor/visitsizeofpackexpr)||
|[VisitStmt\(Stmt\)](/api/cppsharp/ast/astvisitor/visitstmt)||
|[VisitStmtExpr\(StmtExpr\)](/api/cppsharp/ast/astvisitor/visitstmtexpr)||
|[VisitStringLiteral\(StringLiteral\)](/api/cppsharp/ast/astvisitor/visitstringliteral)||
|[VisitSubstNonTypeTemplateParmExpr\(SubstNonTypeTemplateParmExpr\)](/api/cppsharp/ast/astvisitor/visitsubstnontypetemplateparmexpr)||
|[VisitSubstNonTypeTemplateParmPackExpr\(SubstNonTypeTemplateParmPackExpr\)](/api/cppsharp/ast/astvisitor/visitsubstnontypetemplateparmpackexpr)||
|[VisitSwitchCase\(SwitchCase\)](/api/cppsharp/ast/astvisitor/visitswitchcase)||
|[VisitSwitchStmt\(SwitchStmt\)](/api/cppsharp/ast/astvisitor/visitswitchstmt)||
|[VisitTagType\(TagType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittagtype)||
|[VisitTemplateParameterDecl\(TypeTemplateParameter\)](/api/cppsharp/ast/astvisitor/visittemplateparameterdecl)||
|[VisitTemplateParameterSubstitutionType\(TemplateParameterSubstitutionType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittemplateparametersubstitutiontype)||
|[VisitTemplateParameterType\(TemplateParameterType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittemplateparametertype)||
|[VisitTemplateSpecializationType\(TemplateSpecializationType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittemplatespecializationtype)||
|[VisitTemplateTemplateParameterDecl\(TemplateTemplateParameter\)](/api/cppsharp/ast/astvisitor/visittemplatetemplateparameterdecl)||
|[VisitTranslationUnit\(TranslationUnit\)](/api/cppsharp/ast/astvisitor/visittranslationunit)||
|[VisitType\(Type,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittype)||
|[VisitTypeAliasDecl\(TypeAlias\)](/api/cppsharp/ast/astvisitor/visittypealiasdecl)||
|[VisitTypeAliasTemplateDecl\(TypeAliasTemplate\)](/api/cppsharp/ast/astvisitor/visittypealiastemplatedecl)||
|[VisitTypedefDecl\(TypedefDecl\)](/api/cppsharp/ast/astvisitor/visittypedefdecl)||
|[VisitTypedefNameDecl\(TypedefNameDecl\)](/api/cppsharp/ast/astvisitor/visittypedefnamedecl)||
|[VisitTypedefType\(TypedefType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visittypedeftype)||
|[VisitTypeTraitExpr\(TypeTraitExpr\)](/api/cppsharp/ast/astvisitor/visittypetraitexpr)||
|[VisitTypoExpr\(TypoExpr\)](/api/cppsharp/ast/astvisitor/visittypoexpr)||
|[VisitUnaryExprOrTypeTraitExpr\(UnaryExprOrTypeTraitExpr\)](/api/cppsharp/ast/astvisitor/visitunaryexprortypetraitexpr)||
|[VisitUnaryOperator\(UnaryOperator\)](/api/cppsharp/ast/astvisitor/visitunaryoperator)||
|[VisitUnaryTransformType\(UnaryTransformType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitunarytransformtype)||
|[VisitUnresolvedLookupExpr\(UnresolvedLookupExpr\)](/api/cppsharp/ast/astvisitor/visitunresolvedlookupexpr)||
|[VisitUnresolvedMemberExpr\(UnresolvedMemberExpr\)](/api/cppsharp/ast/astvisitor/visitunresolvedmemberexpr)||
|[VisitUnresolvedUsingDecl\(UnresolvedUsingTypename\)](/api/cppsharp/ast/astvisitor/visitunresolvedusingdecl)||
|[VisitUnresolvedUsingType\(UnresolvedUsingType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitunresolvedusingtype)||
|[VisitUnsupportedType\(UnsupportedType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitunsupportedtype)||
|[VisitUserDefinedLiteral\(UserDefinedLiteral\)](/api/cppsharp/ast/astvisitor/visituserdefinedliteral)||
|[VisitVAArgExpr\(VAArgExpr\)](/api/cppsharp/ast/astvisitor/visitvaargexpr)||
|[VisitVariableDecl\(Variable\)](/api/cppsharp/ast/astvisitor/visitvariabledecl)||
|[VisitVarTemplateDecl\(VarTemplate\)](/api/cppsharp/ast/astvisitor/visitvartemplatedecl)||
|[VisitVarTemplateSpecializationDecl\(VarTemplateSpecialization\)](/api/cppsharp/ast/astvisitor/visitvartemplatespecializationdecl)||
|[VisitVectorType\(VectorType,TypeQualifiers\)](/api/cppsharp/ast/astvisitor/visitvectortype)||
|[VisitWhileStmt\(WhileStmt\)](/api/cppsharp/ast/astvisitor/visitwhilestmt)||

## Properties

|Name|Description|
|:---|:---|
|[Visited](/api/cppsharp/ast/astvisitor/visited)||
|[VisitOptions](/api/cppsharp/ast/astvisitor/visitoptions)||

