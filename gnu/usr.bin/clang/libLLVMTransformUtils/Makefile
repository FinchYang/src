# $OpenBSD: Makefile,v 1.5 2017/10/04 20:57:09 patrick Exp $

LIB=	LLVMTransformUtils
NOPIC=
NOPROFILE=

CPPFLAGS+=	-I${LLVM_SRCS}/include/llvm/Transforms
CPPFLAGS+=	-I${LLVM_SRCS}/include/llvm/Transforms/Utils

.include <bsd.own.mk>
SRCS=	ASanStackFrameLayout.cpp \
	AddDiscriminators.cpp \
	BasicBlockUtils.cpp \
	BreakCriticalEdges.cpp \
	BuildLibCalls.cpp \
	BypassSlowDivision.cpp \
	CloneFunction.cpp \
	CloneModule.cpp \
	CmpInstAnalysis.cpp \
	CodeExtractor.cpp \
	CtorUtils.cpp \
	DemoteRegToStack.cpp \
	EscapeEnumerator.cpp \
	Evaluator.cpp \
	FlattenCFG.cpp \
	FunctionComparator.cpp \
	FunctionImportUtils.cpp \
	GlobalStatus.cpp \
	ImportedFunctionsInliningStatistics.cpp \
	InlineFunction.cpp \
	InstructionNamer.cpp \
	IntegerDivision.cpp \
	LCSSA.cpp \
	LibCallsShrinkWrap.cpp \
	Local.cpp \
	LoopSimplify.cpp \
	LoopUnroll.cpp \
	LoopUnrollPeel.cpp \
	LoopUnrollRuntime.cpp \
	LoopUtils.cpp \
	LoopVersioning.cpp \
	LowerInvoke.cpp \
	LowerSwitch.cpp \
	Mem2Reg.cpp \
	MetaRenamer.cpp \
	ModuleUtils.cpp \
	NameAnonGlobals.cpp \
	OrderedInstructions.cpp \
	PredicateInfo.cpp \
	PromoteMemoryToRegister.cpp \
	SSAUpdater.cpp \
	SanitizerStats.cpp \
	SimplifyCFG.cpp \
	SimplifyIndVar.cpp \
	SimplifyInstructions.cpp \
	SimplifyLibCalls.cpp \
	SplitModule.cpp \
	SymbolRewriter.cpp \
	UnifyFunctionExitNodes.cpp \
	Utils.cpp \
	VNCoercion.cpp \
	ValueMapper.cpp

.PATH:	${.CURDIR}/../../../llvm/lib/Transforms/Utils

install:
	@# Nothing here so far ...

.include <bsd.lib.mk>
