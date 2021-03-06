# [分析](index.md)
## [分析概述](profiling-overview.md)
## [设置分析环境](setting-up-a-profiling-environment.md)
## [CLR 探查器和 Windows 应用商店应用](clr-profilers-and-windows-store-apps.md)
## [CORPROF_E_UNSUPPORTED_CALL_SEQUENCE HRESULT](corprof-e-unsupported-call-sequence-hresult.md)
## [Profiling 接口](profiling-interfaces.md)
### [ICLRProfiling 接口](iclrprofiling-interface.md)
#### [AttachProfiler 方法](iclrprofiling-attachprofiler-method.md)
### [ICorProfilerAssemblyReferenceProvider 接口](icorprofilerassemblyreferenceprovider-interface.md)
#### [AddAssemblyReference 方法](icorprofilerassemblyreferenceprovider-addassemblyreference-method.md)
### [ICorProfilerCallback 接口](icorprofilercallback-interface.md)
#### [AppDomainCreationFinished 方法](icorprofilercallback-appdomaincreationfinished-method.md)
#### [AppDomainCreationStarted 方法](icorprofilercallback-appdomaincreationstarted-method.md)
#### [AppDomainShutdownFinished 方法](icorprofilercallback-appdomainshutdownfinished-method.md)
#### [AppDomainShutdownStarted 方法](icorprofilercallback-appdomainshutdownstarted-method.md)
#### [AssemblyLoadFinished 方法](icorprofilercallback-assemblyloadfinished-method.md)
#### [AssemblyLoadStarted 方法](icorprofilercallback-assemblyloadstarted-method.md)
#### [AssemblyUnloadFinished 方法](icorprofilercallback-assemblyunloadfinished-method.md)
#### [AssemblyUnloadStarted 方法](icorprofilercallback-assemblyunloadstarted-method.md)
#### [ClassLoadFinished 方法](icorprofilercallback-classloadfinished-method.md)
#### [ClassLoadStarted 方法](icorprofilercallback-classloadstarted-method.md)
#### [ClassUnloadFinished 方法](icorprofilercallback-classunloadfinished-method.md)
#### [ClassUnloadStarted 方法](icorprofilercallback-classunloadstarted-method.md)
#### [COMClassicVTableCreated 方法](icorprofilercallback-comclassicvtablecreated-method.md)
#### [COMClassicVTableDestroyed 方法](icorprofilercallback-comclassicvtabledestroyed-method.md)
#### [ExceptionCatcherEnter 方法](icorprofilercallback-exceptioncatcherenter-method.md)
#### [ExceptionCatcherLeave 方法](icorprofilercallback-exceptioncatcherleave-method.md)
#### [ExceptionCLRCatcherExecute 方法](icorprofilercallback-exceptionclrcatcherexecute-method.md)
#### [ExceptionCLRCatcherFound 方法](icorprofilercallback-exceptionclrcatcherfound-method.md)
#### [ExceptionOSHandlerEnter 方法](icorprofilercallback-exceptionoshandlerenter-method.md)
#### [ExceptionOSHandlerLeave 方法](icorprofilercallback-exceptionoshandlerleave-method.md)
#### [ExceptionSearchCatcherFound 方法](icorprofilercallback-exceptionsearchcatcherfound-method.md)
#### [ExceptionSearchFilterEnter 方法](icorprofilercallback-exceptionsearchfilterenter-method.md)
#### [ExceptionSearchFilterLeave 方法](icorprofilercallback-exceptionsearchfilterleave-method.md)
#### [ExceptionSearchFunctionEnter 方法](icorprofilercallback-exceptionsearchfunctionenter-method.md)
#### [ExceptionSearchFunctionLeave 方法](icorprofilercallback-exceptionsearchfunctionleave-method.md)
#### [ExceptionThrown 方法](icorprofilercallback-exceptionthrown-method.md)
#### [ExceptionUnwindFinallyEnter 方法](icorprofilercallback-exceptionunwindfinallyenter-method.md)
#### [ExceptionUnwindFinallyLeave 方法](icorprofilercallback-exceptionunwindfinallyleave-method.md)
#### [ExceptionUnwindFunctionEnter 方法](icorprofilercallback-exceptionunwindfunctionenter-method.md)
#### [ExceptionUnwindFunctionLeave 方法](icorprofilercallback-exceptionunwindfunctionleave-method.md)
#### [FunctionUnloadStarted 方法](icorprofilercallback-functionunloadstarted-method.md)
#### [Initialize 方法](icorprofilercallback-initialize-method.md)
#### [JITCachedFunctionSearchFinished 方法](icorprofilercallback-jitcachedfunctionsearchfinished-method.md)
#### [JITCachedFunctionSearchStarted 方法](icorprofilercallback-jitcachedfunctionsearchstarted-method.md)
#### [JITCompilationFinished 方法](icorprofilercallback-jitcompilationfinished-method.md)
#### [JITCompilationStarted 方法](icorprofilercallback-jitcompilationstarted-method.md)
#### [JITFunctionPitched 方法](icorprofilercallback-jitfunctionpitched-method.md)
#### [JITInlining 方法](icorprofilercallback-jitinlining-method.md)
#### [ManagedToUnmanagedTransition 方法](icorprofilercallback-managedtounmanagedtransition-method.md)
#### [ModuleAttachedToAssembly 方法](icorprofilercallback-moduleattachedtoassembly-method.md)
#### [ModuleLoadFinished 方法](icorprofilercallback-moduleloadfinished-method.md)
#### [ModuleLoadStarted 方法](icorprofilercallback-moduleloadstarted-method.md)
#### [ModuleUnloadFinished 方法](icorprofilercallback-moduleunloadfinished-method.md)
#### [ModuleUnloadStarted 方法](icorprofilercallback-moduleunloadstarted-method.md)
#### [MovedReferences 方法](icorprofilercallback-movedreferences-method.md)
#### [ObjectAllocated 方法](icorprofilercallback-objectallocated-method.md)
#### [ObjectReferences 方法](icorprofilercallback-objectreferences-method.md)
#### [ObjectsAllocatedByClass 方法](icorprofilercallback-objectsallocatedbyclass-method.md)
#### [RemotingClientInvocationFinished 方法](icorprofilercallback-remotingclientinvocationfinished-method.md)
#### [RemotingClientInvocationStarted 方法](icorprofilercallback-remotingclientinvocationstarted-method.md)
#### [RemotingClientReceivingReply 方法](icorprofilercallback-remotingclientreceivingreply-method.md)
#### [RemotingClientSendingMessage 方法](icorprofilercallback-remotingclientsendingmessage-method.md)
#### [RemotingServerInvocationReturned 方法](icorprofilercallback-remotingserverinvocationreturned-method.md)
#### [RemotingServerInvocationStarted 方法](icorprofilercallback-remotingserverinvocationstarted-method.md)
#### [RemotingServerReceivingMessage 方法](icorprofilercallback-remotingserverreceivingmessage-method.md)
#### [RemotingServerSendingReply 方法](icorprofilercallback-remotingserversendingreply-method.md)
#### [RootReferences 方法](icorprofilercallback-rootreferences-method.md)
#### [RuntimeResumeFinished 方法](icorprofilercallback-runtimeresumefinished-method.md)
#### [RuntimeResumeStarted 方法](icorprofilercallback-runtimeresumestarted-method.md)
#### [RuntimeSuspendAborted 方法](icorprofilercallback-runtimesuspendaborted-method.md)
#### [RuntimeSuspendFinished 方法](icorprofilercallback-runtimesuspendfinished-method.md)
#### [RuntimeSuspendStarted 方法](icorprofilercallback-runtimesuspendstarted-method.md)
#### [RuntimeThreadResumed 方法](icorprofilercallback-runtimethreadresumed-method.md)
#### [RuntimeThreadSuspended 方法](icorprofilercallback-runtimethreadsuspended-method.md)
#### [Shutdown 方法](icorprofilercallback-shutdown-method.md)
#### [ThreadAssignedToOSThread 方法](icorprofilercallback-threadassignedtoosthread-method.md)
#### [ThreadCreated 方法](icorprofilercallback-threadcreated-method.md)
#### [ThreadDestroyed 方法](icorprofilercallback-threaddestroyed-method.md)
#### [UnmanagedToManagedTransition 方法](icorprofilercallback-unmanagedtomanagedtransition-method.md)
### [ICorProfilerCallback2 接口](icorprofilercallback2-interface.md)
#### [FinalizeableObjectQueued 方法](icorprofilercallback2-finalizeableobjectqueued-method.md)
#### [GarbageCollectionFinished 方法](icorprofilercallback2-garbagecollectionfinished-method.md)
#### [GarbageCollectionStarted 方法](icorprofilercallback2-garbagecollectionstarted-method.md)
#### [HandleCreated 方法](icorprofilercallback2-handlecreated-method.md)
#### [HandleDestroyed 方法](icorprofilercallback2-handledestroyed-method.md)
#### [RootReferences2 方法](icorprofilercallback2-rootreferences2-method.md)
#### [SurvivingReferences 方法](icorprofilercallback2-survivingreferences-method.md)
#### [ThreadNameChanged 方法](icorprofilercallback2-threadnamechanged-method.md)
### [ICorProfilerCallback3 接口](icorprofilercallback3-interface.md)
#### [InitializeForAttach 方法](icorprofilercallback3-initializeforattach-method.md)
#### [ProfilerAttachComplete 方法](icorprofilercallback3-profilerattachcomplete-method.md)
#### [ProfilerDetachSucceeded 方法](icorprofilercallback3-profilerdetachsucceeded-method.md)
### [ICorProfilerCallback4 接口](icorprofilercallback4-interface.md)
#### [GetReJITParameters 方法](icorprofilercallback4-getrejitparameters-method.md)
#### [MovedReferences2 方法](icorprofilercallback4-movedreferences2-method.md)
#### [ReJITCompilationFinished 方法](icorprofilercallback4-rejitcompilationfinished-method.md)
#### [ReJITCompilationStarted 方法](icorprofilercallback4-rejitcompilationstarted-method.md)
#### [ReJITError 方法](icorprofilercallback4-rejiterror-method.md)
#### [SurvivingReferences2 方法](icorprofilercallback4-survivingreferences2-method.md)
### [ICorProfilerCallback5 接口](icorprofilercallback5-interface.md)
#### [ConditionalWeakTableElementReferences 方法](icorprofilercallback5-conditionalweaktableelementreferences-method.md)
### [ICorProfilerCallback6 接口](icorprofilercallback6-interface.md)
#### [GetAssemblyReferences 方法](icorprofilercallback6-getassemblyreferences-method.md)
### [ICorProfilerCallback7 接口](icorprofilercallback7-interface.md)
#### [ModuleInMemorySymbolsUpdated 方法](icorprofilercallback7-moduleinmemorysymbolsupdated-method.md)
### [ICorProfilerFunctionControl 接口](icorprofilerfunctioncontrol-interface.md)
#### [SetCodegenFlags 方法](icorprofilerfunctioncontrol-setcodegenflags-method.md)
#### [SetILFunctionBody 方法](icorprofilerfunctioncontrol-setilfunctionbody-method.md)
#### [SetILInstrumentedCodeMap 方法](icorprofilerfunctioncontrol-setilinstrumentedcodemap-method.md)
### [ICorProfilerCallback8 接口](icorprofilercallback8-interface.md)
#### [DynamicMethodJITCompilationStarted 方法](icorprofilercallback8-dynamicmethodjitcompilationstarted-method.md)
#### [DynamicMethodJITCompilationFinished 方法](icorprofilercallback8-dynamicmethodjitcompilationfinished-method.md)
### [ICorProfilerCallback9 接口](icorprofilercallback9-interface.md)
#### [DynamicMethodUnloaded 方法](icorprofilercallback9-dynamicmethodunloaded-method.md)
### [ICorProfilerFunctionEnum 接口](icorprofilerfunctionenum-interface.md)
#### [Clone 方法](icorprofilerfunctionenum-clone-method.md)
#### [GetCount 方法](icorprofilerfunctionenum-getcount-method.md)
#### [Next 方法](icorprofilerfunctionenum-next-method.md)
#### [Reset 方法](icorprofilerfunctionenum-reset-method.md)
#### [Skip 方法](icorprofilerfunctionenum-skip-method.md)
### [ICorProfilerInfo 接口](icorprofilerinfo-interface.md)
#### [BeginInprocDebugging 方法](icorprofilerinfo-begininprocdebugging-method.md)
#### [EndInprocDebugging 方法](icorprofilerinfo-endinprocdebugging-method.md)
#### [ForceGC 方法](icorprofilerinfo-forcegc-method.md)
#### [GetAppDomainInfo 方法](icorprofilerinfo-getappdomaininfo-method.md)
#### [GetAssemblyInfo 方法](icorprofilerinfo-getassemblyinfo-method.md)
#### [GetClassFromObject 方法](icorprofilerinfo-getclassfromobject-method.md)
#### [GetClassFromToken 方法](icorprofilerinfo-getclassfromtoken-method.md)
#### [GetClassIDInfo 方法](icorprofilerinfo-getclassidinfo-method.md)
#### [GetCodeInfo 方法](icorprofilerinfo-getcodeinfo-method.md)
#### [GetCurrentThreadID 方法](icorprofilerinfo-getcurrentthreadid-method.md)
#### [GetEventMask 方法](icorprofilerinfo-geteventmask-method.md)
#### [GetFunctionFromIP 方法](icorprofilerinfo-getfunctionfromip-method.md)
#### [GetFunctionFromToken 方法](icorprofilerinfo-getfunctionfromtoken-method.md)
#### [GetFunctionInfo 方法](icorprofilerinfo-getfunctioninfo-method.md)
#### [GetHandleFromThread 方法](icorprofilerinfo-gethandlefromthread-method.md)
#### [GetILFunctionBody 方法](icorprofilerinfo-getilfunctionbody-method.md)
#### [GetILFunctionBodyAllocator 方法](icorprofilerinfo-getilfunctionbodyallocator-method.md)
#### [GetILToNativeMapping 方法](icorprofilerinfo-getiltonativemapping-method.md)
#### [GetInprocInspectionInterface 方法](icorprofilerinfo-getinprocinspectioninterface-method.md)
#### [GetInprocInspectionIThisThread 方法](icorprofilerinfo-getinprocinspectionithisthread-method.md)
#### [GetModuleInfo 方法](icorprofilerinfo-getmoduleinfo-method.md)
#### [GetModuleMetaData 方法](icorprofilerinfo-getmodulemetadata-method.md)
#### [GetObjectSize 方法](icorprofilerinfo-getobjectsize-method.md)
#### [GetThreadContext 方法](icorprofilerinfo-getthreadcontext-method.md)
#### [GetThreadInfo 方法](icorprofilerinfo-getthreadinfo-method.md)
#### [GetTokenAndMetadataFromFunction 方法](icorprofilerinfo-gettokenandmetadatafromfunction-method.md)
#### [IsArrayClass 方法](icorprofilerinfo-isarrayclass-method.md)
#### [SetEnterLeaveFunctionHooks 方法](icorprofilerinfo-setenterleavefunctionhooks-method.md)
#### [SetEventMask 方法](icorprofilerinfo-seteventmask-method.md)
#### [SetFunctionIDMapper 方法](icorprofilerinfo-setfunctionidmapper-method.md)
#### [SetFunctionReJIT 方法](icorprofilerinfo-setfunctionrejit-method.md)
#### [SetILFunctionBody 方法](icorprofilerinfo-setilfunctionbody-method.md)
#### [SetILInstrumentedCodeMap 方法](icorprofilerinfo-setilinstrumentedcodemap-method.md)
### [ICorProfilerInfo2 接口](icorprofilerinfo2-interface.md)
#### [DoStackSnapshot 方法](icorprofilerinfo2-dostacksnapshot-method.md)
#### [EnumModuleFrozenObjects 方法](icorprofilerinfo2-enummodulefrozenobjects-method.md)
#### [GetAppDomainStaticAddress 方法](icorprofilerinfo2-getappdomainstaticaddress-method.md)
#### [GetArrayObjectInfo 方法](icorprofilerinfo2-getarrayobjectinfo-method.md)
#### [GetBoxClassLayout 方法](icorprofilerinfo2-getboxclasslayout-method.md)
#### [GetClassFromTokenAndTypeArgs 方法](icorprofilerinfo2-getclassfromtokenandtypeargs-method.md)
#### [GetClassIDInfo2 方法](icorprofilerinfo2-getclassidinfo2-method.md)
#### [GetClassLayout 方法](icorprofilerinfo2-getclasslayout-method.md)
#### [GetCodeInfo2 方法](icorprofilerinfo2-getcodeinfo2-method.md)
#### [GetContextStaticAddress 方法](icorprofilerinfo2-getcontextstaticaddress-method.md)
#### [GetFunctionFromTokenAndTypeArgs 方法](icorprofilerinfo2-getfunctionfromtokenandtypeargs-method.md)
#### [GetFunctionInfo2 方法](icorprofilerinfo2-getfunctioninfo2-method.md)
#### [GetGenerationBounds 方法](icorprofilerinfo2-getgenerationbounds-method.md)
#### [GetNotifiedExceptionClauseInfo 方法](icorprofilerinfo2-getnotifiedexceptionclauseinfo-method.md)
#### [GetObjectGeneration 方法](icorprofilerinfo2-getobjectgeneration-method.md)
#### [GetRVAStaticAddress 方法](icorprofilerinfo2-getrvastaticaddress-method.md)
#### [GetStaticFieldInfo 方法](icorprofilerinfo2-getstaticfieldinfo-method.md)
#### [GetStringLayout 方法](icorprofilerinfo2-getstringlayout-method.md)
#### [GetThreadAppDomain 方法](icorprofilerinfo2-getthreadappdomain-method.md)
#### [GetThreadStaticAddress 方法](icorprofilerinfo2-getthreadstaticaddress-method.md)
#### [SetEnterLeaveFunctionHooks2 方法](icorprofilerinfo2-setenterleavefunctionhooks2-method.md)
### [ICorProfilerInfo3 接口](icorprofilerinfo3-interface.md)
#### [EnumJITedFunctions 方法](icorprofilerinfo3-enumjitedfunctions-method.md)
#### [EnumModules 方法](icorprofilerinfo3-enummodules-method.md)
#### [GetAppDomainsContainingModule 方法](icorprofilerinfo3-getappdomainscontainingmodule-method.md)
#### [GetFunctionEnter3Info 方法](icorprofilerinfo3-getfunctionenter3info-method.md)
#### [GetFunctionLeave3Info 方法](icorprofilerinfo3-getfunctionleave3info-method.md)
#### [GetFunctionTailcall3Info 方法](icorprofilerinfo3-getfunctiontailcall3info-method.md)
#### [GetModuleInfo2 方法](icorprofilerinfo3-getmoduleinfo2-method.md)
#### [GetRuntimeInformation 方法](icorprofilerinfo3-getruntimeinformation-method.md)
#### [GetStringLayout2 方法](icorprofilerinfo3-getstringlayout2-method.md)
#### [GetThreadStaticAddress2 方法](icorprofilerinfo3-getthreadstaticaddress2-method.md)
#### [RequestProfilerDetach 方法](icorprofilerinfo3-requestprofilerdetach-method.md)
#### [SetEnterLeaveFunctionHooks3 方法](icorprofilerinfo3-setenterleavefunctionhooks3-method.md)
#### [SetEnterLeaveFunctionHooks3WithInfo 方法](icorprofilerinfo3-setenterleavefunctionhooks3withinfo-method.md)
#### [SetFunctionIDMapper2 方法](icorprofilerinfo3-setfunctionidmapper2-method.md)
### [ICorProfilerInfo4 接口](icorprofilerinfo4-interface.md)
#### [EnumJITedFunctions2 方法](icorprofilerinfo4-enumjitedfunctions2-method.md)
#### [EnumThreads 方法](icorprofilerinfo4-enumthreads-method.md)
#### [GetCodeInfo3 方法](icorprofilerinfo4-getcodeinfo3-method.md)
#### [GetFunctionFromIP2 方法](icorprofilerinfo4-getfunctionfromip2-method.md)
#### [GetILToNativeMapping2 方法](icorprofilerinfo4-getiltonativemapping2-method.md)
#### [GetObjectSize2 方法](icorprofilerinfo4-getobjectsize2-method.md)
#### [GetReJITIDs 方法](icorprofilerinfo4-getrejitids-method.md)
#### [InitializeCurrentThread 方法](icorprofilerinfo4-initializecurrentthread-method.md)
#### [RequestReJIT 方法](icorprofilerinfo4-requestrejit-method.md)
#### [RequestRevert 方法](icorprofilerinfo4-requestrevert-method.md)
### [ICorProfilerInfo5 接口](icorprofilerinfo5-interface.md)
#### [GetEventMask2 方法](icorprofilerinfo5-geteventmask2-method.md)
#### [SetEventMask2 方法](icorprofilerinfo5-seteventmask2-method.md)
### [ICorProfilerInfo6 接口](icorprofilerinfo6-interface.md)
#### [ICorProfilerInfo6::EnumNgenModuleMethodsInliningThisMethod 方法](icorprofilerinfo6-enumngenmodulemethodsinliningthismethod-method.md)
### [ICorProfilerInfo7 接口](icorprofilerinfo7-interface.md)
#### [ApplyMetaData 方法](icorprofilerinfo7-applymetadata-method.md)
#### [GetInMemorySymbolsLength 方法](icorprofilerinfo7-getinmemorysymbolslength-method.md)
#### [ReadInMemorySymbols](icorprofilerinfo7-readinmemorysymbols.md)
### [ICorProfilerModuleEnum 接口](icorprofilermoduleenum-interface.md)
#### [Clone 方法](icorprofilermoduleenum-clone-method.md)
#### [GetCount 方法](icorprofilermoduleenum-getcount-method.md)
#### [Next 方法](icorprofilermoduleenum-next-method.md)
#### [Reset 方法](icorprofilermoduleenum-reset-method.md)
#### [Skip 方法](icorprofilermoduleenum-skip-method.md)
### [ICorProfilerObjectEnum 接口](icorprofilerobjectenum-interface.md)
#### [Clone 方法](icorprofilerobjectenum-clone-method.md)
#### [GetCount 方法](icorprofilerobjectenum-getcount-method.md)
#### [Next 方法](icorprofilerobjectenum-next-method.md)
#### [Reset 方法](icorprofilerobjectenum-reset-method.md)
#### [Skip 方法](icorprofilerobjectenum-skip-method.md)
### [ICorProfilerThreadEnum 接口](icorprofilerthreadenum-interface.md)
#### [Clone 方法](icorprofilerthreadenum-clone-method.md)
#### [GetCount 方法](icorprofilerthreadenum-getcount-method.md)
#### [Next 方法](icorprofilerthreadenum-next-method.md)
#### [Reset 方法](icorprofilerthreadenum-reset-method.md)
#### [Skip 方法](icorprofilerthreadenum-skip-method.md)
### [IMethodMalloc 接口](imethodmalloc-interface.md)
#### [Alloc 方法](imethodmalloc-alloc-method.md)
## [分析全局静态函数](profiling-global-static-functions.md)
### [FunctionEnter 函数](functionenter-function.md)
### [FunctionEnter2 函数](functionenter2-function.md)
### [FunctionEnter3 函数](functionenter3-function.md)
### [FunctionEnter3WithInfo 函数](functionenter3withinfo-function.md)
### [FunctionIDMapper 函数](functionidmapper-function.md)
### [FunctionIDMapper2 函数](functionidmapper2-function.md)
### [FunctionLeave 函数](functionleave-function.md)
### [FunctionLeave2 函数](functionleave2-function.md)
### [FunctionLeave3 函数](functionleave3-function.md)
### [FunctionLeave3WithInfo 函数](functionleave3withinfo-function.md)
### [FunctionTailcall 函数](functiontailcall-function.md)
### [FunctionTailcall2 函数](functiontailcall2-function.md)
### [FunctionTailcall3 函数](functiontailcall3-function.md)
### [FunctionTailcall3WithInfo 函数](functiontailcall3withinfo-function.md)
### [StackSnapshotCallback 函数](stacksnapshotcallback-function.md)
## [分析枚举](profiling-enumerations.md)
### [COR_PRF_CLAUSE_TYPE 枚举](cor-prf-clause-type-enumeration.md)
### [COR_PRF_CODEGEN_FLAGS 枚举](cor-prf-codegen-flags-enumeration.md)
### [COR_PRF_FINALIZER_FLAGS 枚举](cor-prf-finalizer-flags-enumeration.md)
### [COR_PRF_GC_GENERATION 枚举](cor-prf-gc-generation-enumeration.md)
### [COR_PRF_GC_REASON 枚举](cor-prf-gc-reason-enumeration.md)
### [COR_PRF_GC_ROOT_FLAGS 枚举](cor-prf-gc-root-flags-enumeration.md)
### [COR_PRF_GC_ROOT_KIND 枚举](cor-prf-gc-root-kind-enumeration.md)
### [COR_PRF_HIGH_MONITOR 枚举](cor-prf-high-monitor-enumeration.md)
### [COR_PRF_JIT_CACHE 枚举](cor-prf-jit-cache-enumeration.md)
### [COR_PRF_MISC 枚举](cor-prf-misc-enumeration.md)
### [COR_PRF_MODULE_FLAGS 枚举](cor-prf-module-flags-enumeration.md)
### [COR_PRF_MONITOR 枚举](cor-prf-monitor-enumeration.md)
### [COR_PRF_RUNTIME_TYPE 枚举](cor-prf-runtime-type-enumeration.md)
### [COR_PRF_SNAPSHOT_INFO 枚举](cor-prf-snapshot-info-enumeration.md)
### [COR_PRF_STATIC_TYPE 枚举](cor-prf-static-type-enumeration.md)
### [COR_PRF_SUSPEND_REASON 枚举](cor-prf-suspend-reason-enumeration.md)
### [COR_PRF_TRANSITION_REASON 枚举](cor-prf-transition-reason-enumeration.md)
## [分析结构](profiling-structures.md)
### [COR_PRF_ASSEMBLY_REFERENCE_INFO 结构](cor-prf-assembly-reference-info-structure.md)
### [COR_PRF_CODE_INFO 结构](cor-prf-code-info-structure.md)
### [COR_PRF_EX_CLAUSE_INFO 结构](cor-prf-ex-clause-info-structure.md)
### [COR_PRF_FUNCTION 结构](cor-prf-function-structure.md)
### [COR_PRF_FUNCTION_ARGUMENT_INFO 结构](cor-prf-function-argument-info-structure.md)
### [COR_PRF_FUNCTION_ARGUMENT_RANGE 结构](cor-prf-function-argument-range-structure.md)
### [COR_PRF_GC_GENERATION_RANGE 结构](cor-prf-gc-generation-range-structure.md)
