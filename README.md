[LWM_DeepStorage][ERR] Failed to apply Harmony patches for LWM.DeepStorage. Exception was: HarmonyLib.HarmonyException: Patching exception in method static System.Reflection.MethodBase LWM.DeepStorage.Patch_StartCarryThing_Delegate::TargetMethod() ---> System.Exception: Method static System.Reflection.MethodBase LWM.DeepStorage.Patch_StartCarryThing_Delegate::TargetMethod() returned an unexpected result: null
  at HarmonyLib.PatchClassProcessor.RunMethod[S,T] (T defaultIfNotExisting, T defaultIfFailing, System.Func`2[T,TResult] failOnResult, System.Object[] parameters) [0x00117] in <c38a8c3281a047488dac8c9d063b7abb>:0 
   --- End of inner exception stack trace ---
  at HarmonyLib.PatchClassProcessor.ReportException (System.Exception exception, System.Reflection.MethodBase original) [0x0010f] in <c38a8c3281a047488dac8c9d063b7abb>:0 
  at HarmonyLib.PatchClassProcessor.Patch () [0x00082] in <c38a8c3281a047488dac8c9d063b7abb>:0 
  at HarmonyLib.Harmony.<PatchAll>b__10_0 (System.Type type) [0x00007] in <c38a8c3281a047488dac8c9d063b7abb>:0 
  at HarmonyLib.CollectionExtensions.Do[T] (System.Collections.Generic.IEnumerable`1[T] sequence, System.Action`1[T] action) [0x00014] in <c38a8c3281a047488dac8c9d063b7abb>:0 
  at HarmonyLib.Harmony.PatchAll (System.Reflection.Assembly assembly) [0x00006] in <c38a8c3281a047488dac8c9d063b7abb>:0 
  at HugsLib.ModBase.ApplyHarmonyPatches () [0x0009a] in <4dd8a30b2ddc479e878b55ffe02db6e8>:0 
UnityEngine.StackTraceUtility:ExtractStackTrace ()
(wrapper dynamic-method) Verse.Log:Verse.Log.Error_Patch2 (string)
HugsLib.Utils.ModLogger:Error (string,object[])
HugsLib.ModBase:ApplyHarmonyPatches ()
HugsLib.HugsLibController:EnumerateChildMods (bool)
HugsLib.HugsLibController:LoadReloadInitialize ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()
