---
title: CastKind
slug: api/cppsharp.ast.castkind
---
Enum in [CppSharp.AST](/api/cppsharp/ast)

Inherits from `System.Enum`

## Summary



```csharp
public enum CastKind
{
    Dependent = 0,
    BitCast = 1,
    LValueBitCast = 2,
    LValueToRValue = 3,
    NoOp = 4,
    BaseToDerived = 5,
    DerivedToBase = 6,
    UncheckedDerivedToBase = 7,
    Dynamic = 8,
    ToUnion = 9,
    ArrayToPointerDecay = 10,
    FunctionToPointerDecay = 11,
    NullToPointer = 12,
    NullToMemberPointer = 13,
    BaseToDerivedMemberPointer = 14,
    DerivedToBaseMemberPointer = 15,
    MemberPointerToBoolean = 16,
    ReinterpretMemberPointer = 17,
    UserDefinedConversion = 18,
    ConstructorConversion = 19,
    IntegralToPointer = 20,
    PointerToIntegral = 21,
    PointerToBoolean = 22,
    ToVoid = 23,
    VectorSplat = 24,
    IntegralCast = 25,
    IntegralToBoolean = 26,
    IntegralToFloating = 27,
    FixedPointCast = 28,
    FixedPointToBoolean = 29,
    FloatingToIntegral = 30,
    FloatingToBoolean = 31,
    BooleanToSignedIntegral = 32,
    FloatingCast = 33,
    CPointerToObjCPointerCast = 34,
    BlockPointerToObjCPointerCast = 35,
    AnyPointerToBlockPointerCast = 36,
    ObjCObjectLValueCast = 37,
    FloatingRealToComplex = 38,
    FloatingComplexToReal = 39,
    FloatingComplexToBoolean = 40,
    FloatingComplexCast = 41,
    FloatingComplexToIntegralComplex = 42,
    IntegralRealToComplex = 43,
    IntegralComplexToReal = 44,
    IntegralComplexToBoolean = 45,
    IntegralComplexCast = 46,
    IntegralComplexToFloatingComplex = 47,
    ARCProduceObject = 48,
    ARCConsumeObject = 49,
    ARCReclaimReturnedObject = 50,
    ARCExtendBlockObject = 51,
    AtomicToNonAtomic = 52,
    NonAtomicToAtomic = 53,
    CopyAndAutoreleaseBlockObject = 54,
    BuiltinFnToFnPtr = 55,
    ZeroToOCLOpaqueType = 56,
    AddressSpaceConversion = 57,
    IntToOCLSampler = 58
}
```

## Members

|Name|Description|
|:---|:---|
|[AddressSpaceConversion](/api/cppsharp/ast/castkind/addressspaceconversion)||
|[AnyPointerToBlockPointerCast](/api/cppsharp/ast/castkind/anypointertoblockpointercast)||
|[ARCConsumeObject](/api/cppsharp/ast/castkind/arcconsumeobject)||
|[ARCExtendBlockObject](/api/cppsharp/ast/castkind/arcextendblockobject)||
|[ARCProduceObject](/api/cppsharp/ast/castkind/arcproduceobject)||
|[ARCReclaimReturnedObject](/api/cppsharp/ast/castkind/arcreclaimreturnedobject)||
|[ArrayToPointerDecay](/api/cppsharp/ast/castkind/arraytopointerdecay)||
|[AtomicToNonAtomic](/api/cppsharp/ast/castkind/atomictononatomic)||
|[BaseToDerived](/api/cppsharp/ast/castkind/basetoderived)||
|[BaseToDerivedMemberPointer](/api/cppsharp/ast/castkind/basetoderivedmemberpointer)||
|[BitCast](/api/cppsharp/ast/castkind/bitcast)||
|[BlockPointerToObjCPointerCast](/api/cppsharp/ast/castkind/blockpointertoobjcpointercast)||
|[BooleanToSignedIntegral](/api/cppsharp/ast/castkind/booleantosignedintegral)||
|[BuiltinFnToFnPtr](/api/cppsharp/ast/castkind/builtinfntofnptr)||
|[ConstructorConversion](/api/cppsharp/ast/castkind/constructorconversion)||
|[CopyAndAutoreleaseBlockObject](/api/cppsharp/ast/castkind/copyandautoreleaseblockobject)||
|[CPointerToObjCPointerCast](/api/cppsharp/ast/castkind/cpointertoobjcpointercast)||
|[Dependent](/api/cppsharp/ast/castkind/dependent)||
|[DerivedToBase](/api/cppsharp/ast/castkind/derivedtobase)||
|[DerivedToBaseMemberPointer](/api/cppsharp/ast/castkind/derivedtobasememberpointer)||
|[Dynamic](/api/cppsharp/ast/castkind/dynamic)||
|[FixedPointCast](/api/cppsharp/ast/castkind/fixedpointcast)||
|[FixedPointToBoolean](/api/cppsharp/ast/castkind/fixedpointtoboolean)||
|[FloatingCast](/api/cppsharp/ast/castkind/floatingcast)||
|[FloatingComplexCast](/api/cppsharp/ast/castkind/floatingcomplexcast)||
|[FloatingComplexToBoolean](/api/cppsharp/ast/castkind/floatingcomplextoboolean)||
|[FloatingComplexToIntegralComplex](/api/cppsharp/ast/castkind/floatingcomplextointegralcomplex)||
|[FloatingComplexToReal](/api/cppsharp/ast/castkind/floatingcomplextoreal)||
|[FloatingRealToComplex](/api/cppsharp/ast/castkind/floatingrealtocomplex)||
|[FloatingToBoolean](/api/cppsharp/ast/castkind/floatingtoboolean)||
|[FloatingToIntegral](/api/cppsharp/ast/castkind/floatingtointegral)||
|[FunctionToPointerDecay](/api/cppsharp/ast/castkind/functiontopointerdecay)||
|[IntegralCast](/api/cppsharp/ast/castkind/integralcast)||
|[IntegralComplexCast](/api/cppsharp/ast/castkind/integralcomplexcast)||
|[IntegralComplexToBoolean](/api/cppsharp/ast/castkind/integralcomplextoboolean)||
|[IntegralComplexToFloatingComplex](/api/cppsharp/ast/castkind/integralcomplextofloatingcomplex)||
|[IntegralComplexToReal](/api/cppsharp/ast/castkind/integralcomplextoreal)||
|[IntegralRealToComplex](/api/cppsharp/ast/castkind/integralrealtocomplex)||
|[IntegralToBoolean](/api/cppsharp/ast/castkind/integraltoboolean)||
|[IntegralToFloating](/api/cppsharp/ast/castkind/integraltofloating)||
|[IntegralToPointer](/api/cppsharp/ast/castkind/integraltopointer)||
|[IntToOCLSampler](/api/cppsharp/ast/castkind/inttooclsampler)||
|[LValueBitCast](/api/cppsharp/ast/castkind/lvaluebitcast)||
|[LValueToRValue](/api/cppsharp/ast/castkind/lvaluetorvalue)||
|[MemberPointerToBoolean](/api/cppsharp/ast/castkind/memberpointertoboolean)||
|[NonAtomicToAtomic](/api/cppsharp/ast/castkind/nonatomictoatomic)||
|[NoOp](/api/cppsharp/ast/castkind/noop)||
|[NullToMemberPointer](/api/cppsharp/ast/castkind/nulltomemberpointer)||
|[NullToPointer](/api/cppsharp/ast/castkind/nulltopointer)||
|[ObjCObjectLValueCast](/api/cppsharp/ast/castkind/objcobjectlvaluecast)||
|[PointerToBoolean](/api/cppsharp/ast/castkind/pointertoboolean)||
|[PointerToIntegral](/api/cppsharp/ast/castkind/pointertointegral)||
|[ReinterpretMemberPointer](/api/cppsharp/ast/castkind/reinterpretmemberpointer)||
|[ToUnion](/api/cppsharp/ast/castkind/tounion)||
|[ToVoid](/api/cppsharp/ast/castkind/tovoid)||
|[UncheckedDerivedToBase](/api/cppsharp/ast/castkind/uncheckedderivedtobase)||
|[UserDefinedConversion](/api/cppsharp/ast/castkind/userdefinedconversion)||
|[VectorSplat](/api/cppsharp/ast/castkind/vectorsplat)||
|[ZeroToOCLOpaqueType](/api/cppsharp/ast/castkind/zerotooclopaquetype)||

