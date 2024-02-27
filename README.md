Запуск программы и длительное подключение к телефону


---------------------------- PROCESS STARTED (31173) for package com.example.happybirthday ----------------------------
--------- beginning of system
2024-02-28 00:59:33.787  1931-4124  WindowManager           pid-1931                             E  check permission error, current package is com.example.happybirthday , it is not systemApp, callers is com.hihonor.android.view.IHwWindowManager$Stub.onTransact:949 android.os.Binder.execTransactInternal:1318 android.os.Binder.execTransact:1279 <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> 
2024-02-28 00:59:35.899  1931-3004  WindowManager           pid-1931                             E  check permission error, current package is com.example.happybirthday , it is not systemApp, callers is com.hihonor.android.view.IHwWindowManager$Stub.onTransact:949 android.os.Binder.execTransactInternal:1318 android.os.Binder.execTransact:1279 <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> 
2024-02-28 00:59:41.921 31173-31173 ActivityThread          com.example.happybirthday            I  preloadStatus:1
2024-02-28 00:59:41.951 31173-31173 ActivityThread          com.example.happybirthday            D  Attach thread to application
2024-02-28 00:59:42.951 31173-31194 HwActivityThreadImpl    com.example.happybirthday            I  mSocketName: bf7247a3-1d86-415f-9c6b-3a85d4035432
2024-02-28 00:59:42.951 31173-31194 HwActivityThreadImpl    com.example.happybirthday            I  initPreloadedSocked end mPreloadStatus 2
2024-02-28 00:59:42.953 31173-31195 HwActivityThreadImpl    com.example.happybirthday            I  before connect app.socketName:bf7247a3-1d86-415f-9c6b-3a85d4035432
2024-02-28 00:59:42.953  1931-3832  WindowManager           system_server                        E  check permission error, current package is com.example.happybirthday , it is not systemApp, callers is com.hihonor.android.view.IHwWindowManager$Stub.onTransact:949 android.os.Binder.execTransactInternal:1318 android.os.Binder.execTransact:1279 <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> <bottom of call stack> 
2024-02-28 00:59:42.954 31173-31192 ActivityThread          com.example.happybirthday            I  Init compatible state: true
2024-02-28 00:59:43.151 31173-31195 HwActivityThreadImpl    com.example.happybirthday            E  connect Error.
2024-02-28 00:59:43.151 31173-31195 HwActivityThreadImpl    com.example.happybirthday            I  connectContinuePreload end mPreloadStatus 3
2024-02-28 00:59:43.196 31173-31173 ActivityThread          com.example.happybirthday            I  finishPreloaded preloadStatus 3
2024-02-28 00:59:43.197 31173-31173 ActivityThread          com.example.happybirthday            I  finishPreloaded end preloadStatus 3
2024-02-28 00:59:43.199 31173-31173 ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 00:59:43.222 31173-31173 ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 00:59:43.265 31173-31173 ActivityThread          com.example.happybirthday            I  add activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 00:59:44.236 31173-31173 HwForceDarkManager      com.example.happybirthday            I  setAllowedHwForceDark:false package:com.example.happybirthday mCurrProcessState:0 mIsPackageNameChange:false hwForceDarkState:0 isViewAllowedForceDark:true isLastHonorForceDark:false
2024-02-28 00:59:44.645 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 00:59:44.667 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 00:59:44.677 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 00:59:45.095  1931-3832  ActivityTaskManager     system_server                        E  START {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10000000 hwFlg=0x10 cmp=com.example.happybirthday/.MainActivity} result: 3
2024-02-28 00:59:59.594 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 00:59:59.595 31173-31173 ViewRootImpl            com.example.happybirthday            I  focus window changed, set pointer icon to default
2024-02-28 01:00:00.046 31173-31173 RtgSched                com.example.happybirthday            D  resetRtgSchedHandle failed enable:0
2024-02-28 01:00:14.074  1931-3279  ActivityTaskManager     system_server                        E  START {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10600000 hwFlg=0x10 cmp=com.example.happybirthday/.MainActivity bnds=[39,1709][293,2018] (has extras)} result: 2
2024-02-28 01:00:14.088 31173-31173 ActivityThread          com.example.happybirthday            D  Won't deliver top position change in state=5
2024-02-28 01:00:14.108 31173-31173 ActivityThread          com.example.happybirthday            I  Performing restart of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} start=false callers:android.app.servertransaction.TransactionExecutor.performLifecycleSequence:258 android.app.servertransaction.TransactionExecutor.cycleToPath:215 android.app.servertransaction.TransactionExecutor.executeLifecycleState:187 android.app.servertransaction.TransactionExecutor.execute:105 android.app.ActivityThread$H.handleMessage:2838 android.os.Handler.dispatchMessage:114 android.os.Looper.loopOnce:206 android.os.Looper.loop:296 android.app.ActivityThread.main:9159 java.lang.reflect.Method.invoke:-2 
2024-02-28 01:00:14.216 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:00:14.543 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 01:00:23.391 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:00:23.648 31173-31173 RtgSched                com.example.happybirthday            D  resetRtgSchedHandle failed enable:0
2024-02-28 01:00:26.352 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 01:00:26.360 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:00:26.998 31173-31173 ActivityThread          com.example.happybirthday            I  Remove activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 01:00:26.999 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  dispatchDetachedFromWindow in doDie
2024-02-28 01:00:27.019 31173-31173 ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:00:27.032 31173-31173 ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 01:00:27.050 31173-31173 ActivityThread          com.example.happybirthday            I  add activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 01:00:27.084  1931-3718  WindowManager           system_server                        E  setOnBackInvokedCallback(): No window state for package:com.example.happybirthday
2024-02-28 01:00:27.254 31173-31173 HwForceDarkManager      com.example.happybirthday            I  setAllowedHwForceDark:false package:com.example.happybirthday mCurrProcessState:0 mIsPackageNameChange:false hwForceDarkState:0 isViewAllowedForceDark:true isLastHonorForceDark:false
2024-02-28 01:00:27.291 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:00:56.164 31173-31173 ActivityThread          com.example.happybirthday            I  Remove activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 01:00:56.165 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  dispatchDetachedFromWindow in doDie
2024-02-28 01:00:56.202 31173-31173 ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:00:56.214 31173-31173 ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 01:00:56.236 31173-31173 ActivityThread          com.example.happybirthday            I  add activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 01:00:56.678 31173-31173 HwForceDarkManager      com.example.happybirthday            I  setAllowedHwForceDark:false package:com.example.happybirthday mCurrProcessState:0 mIsPackageNameChange:false hwForceDarkState:0 isViewAllowedForceDark:true isLastHonorForceDark:false
--------- beginning of main
2024-02-28 01:00:56.731 31173-31173 HwViewRootImpl          com.example.happybirthday            I  removeInvalidNode jank list is null
2024-02-28 01:00:56.732 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:00:56.733 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058116a0 count: 2
2024-02-28 01:00:56.733 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058116a0
2024-02-28 01:00:56.739 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058111d0 count: 2
2024-02-28 01:00:56.739 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058111d0
2024-02-28 01:00:56.740 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811e30 count: 2
2024-02-28 01:00:56.740 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811e30
2024-02-28 01:00:56.741 31173-31173 RemoteInpu...ectionImpl com.example.happybirthday            W  getExtractedText on inactive InputConnection
2024-02-28 01:00:56.752 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405801a50 count: 2
2024-02-28 01:00:56.752 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405801a50
2024-02-28 01:00:56.753 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405803d60 count: 2
2024-02-28 01:00:56.753 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405803d60
2024-02-28 01:00:56.754 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405810e60 count: 2
2024-02-28 01:00:56.755 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405810e60
2024-02-28 01:00:56.755 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405810ba0 count: 2
2024-02-28 01:00:56.755 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405810ba0
2024-02-28 01:00:56.756 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811960 count: 2
2024-02-28 01:00:56.756 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811960
2024-02-28 01:00:56.756 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811a10 count: 2
2024-02-28 01:00:56.756 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811a10
2024-02-28 01:00:56.757 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=true; winMode=1; isMrgNull=true
2024-02-28 01:00:56.758 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 1
2024-02-28 01:00:56.833 31173-31191 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057fa8e0
2024-02-28 01:00:56.833 31173-31191 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f60b0
2024-02-28 01:00:56.834 31173-31191 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074058007c0
2024-02-28 01:00:56.836 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fc930 count: 2
2024-02-28 01:00:56.836 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fc930
2024-02-28 01:00:56.836 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811540 count: 2
2024-02-28 01:00:56.836 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811540
2024-02-28 01:01:26.064 31173-31173 RtgSchedManager         com.example.happybirthday            E  endActivityTransaction: margin state not match
2024-02-28 01:01:26.065 31173-31173 Lifecycle               com.example.happybirthday            D  onPause
2024-02-28 01:01:26.071  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:12 fg:false mUid:10341
2024-02-28 01:01:26.082 31173-31173 RtgSchedManager         com.example.happybirthday            E  endActivityTransaction: margin state not match
2024-02-28 01:01:26.087 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fc5c0 count: 4
2024-02-28 01:01:26.087 31173-31173 Lifecycle               com.example.happybirthday            D  onStop
2024-02-28 01:01:26.092 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 4
2024-02-28 01:01:26.093 31173-31173 RtgSchedManager         com.example.happybirthday            E  endActivityTransaction: margin state not match
2024-02-28 01:01:26.103 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#3(BLAST Consumer)3](id:79c500000003,api:1,p:31173,c:31173) disconnect: api 1
2024-02-28 01:01:26.103 31173-31219 BufferQueueConsumer     com.example.happybirthday            I  [VRI[MainActivity]#3(BLAST Consumer)3](id:79c500000003,api:0,p:-1,c:31173) disconnect
2024-02-28 01:01:26.105 31173-31219 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fc5c0
2024-02-28 01:01:26.124 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405811540
2024-02-28 01:01:26.126 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057fc930
2024-02-28 01:01:26.127 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405811a10
2024-02-28 01:01:26.129 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058007c0 count: 2
2024-02-28 01:01:26.129 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058007c0
2024-02-28 01:01:26.129 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f60b0 count: 2
2024-02-28 01:01:26.129 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f60b0
2024-02-28 01:01:26.130 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fa8e0 count: 2
2024-02-28 01:01:26.130 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fa8e0
2024-02-28 01:01:26.210 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:01:26.210 31173-31173 ViewRootImpl            com.example.happybirthday            I  focus window changed, set pointer icon to default
2024-02-28 01:01:26.212 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=false; winMode=1; isMrgNull=true
2024-02-28 01:01:26.262 31173-31173 RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:01:26.263 31173-31173 RtgSched                com.example.happybirthday            D  resetRtgSchedHandle failed enable:0
2024-02-28 01:01:26.272 31173-31211 ZrHung.AppEyeUiProbe    com.example.happybirthday            D  not watching, wait.
2024-02-28 01:01:26.417 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb40000740581a650
2024-02-28 01:01:26.419 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811a10 count: 2
2024-02-28 01:01:26.419 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811a10
2024-02-28 01:01:26.420 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fc930 count: 2
2024-02-28 01:01:26.420 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fc930
2024-02-28 01:01:26.420 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811540 count: 2
2024-02-28 01:01:26.420 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811540
2024-02-28 01:01:27.774 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb40000740581a650 count: 2
2024-02-28 01:01:27.774 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb40000740581a650
2024-02-28 01:01:31.114 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  handleReleaseCache: pid=31173
2024-02-28 01:01:31.115 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  init lrucache size: 4194304 pid=31173
2024-02-28 01:03:36.680 31173-31173 Choreographer           com.example.happybirthday            D  still have 2 traversal callbacks
2024-02-28 01:03:37.480 31173-31173 ActivityThread          com.example.happybirthday            D  Won't deliver top position change in state=5
2024-02-28 01:03:37.488 31173-31173 ActivityThread          com.example.happybirthday            I  Performing restart of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} start=false callers:android.app.servertransaction.TransactionExecutor.performLifecycleSequence:258 android.app.servertransaction.TransactionExecutor.cycleToPath:215 android.app.servertransaction.TransactionExecutor.executeLifecycleState:187 android.app.servertransaction.TransactionExecutor.execute:105 android.app.ActivityThread$H.handleMessage:2838 android.os.Handler.dispatchMessage:114 android.os.Looper.loopOnce:206 android.os.Looper.loop:296 android.app.ActivityThread.main:9159 java.lang.reflect.Method.invoke:-2 

_____________________________________________________________________________________________
Приложение запущено

2024-02-28 01:03:37.489 31173-31173 Lifecycle               com.example.happybirthday            D  onStart
2024-02-28 01:03:37.499 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 0
2024-02-28 01:03:37.504 31173-31211 ZrHung.AppEyeUiProbe    com.example.happybirthday            D  restart watching
2024-02-28 01:03:37.505 31173-31173 Lifecycle               com.example.happybirthday            D  onResume
2024-02-28 01:03:37.513 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 0
2024-02-28 01:03:37.533  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:2 fg:true mUid:10341
2024-02-28 01:03:37.545 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f8050
2024-02-28 01:03:37.555 31173-31173 BufferQueueConsumer     com.example.happybirthday            I  [](id:79c500000004,api:0,p:-1,c:31173) connect: controlledByApp=false
2024-02-28 01:03:37.564 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#4(BLAST Consumer)4](id:79c500000004,api:0,p:-1,c:31173) connect: api=1 producerControlledByApp=true
2024-02-28 01:03:37.564 31173-31219 OpenGLRenderer          com.example.happybirthday            E  Unable to match the desired swap behavior.
2024-02-28 01:03:37.572 31173-31173 HwViewRootImpl          com.example.happybirthday            I  removeInvalidNode all the node in jank list is out of time
2024-02-28 01:03:37.575 31173-31173 RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:03:37.575 31173-31191 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057fdb10
2024-02-28 01:03:37.575 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 01:03:37.575 31173-31191 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405803aa0
2024-02-28 01:03:37.595 31173-31219 BLASTBufferQueue        com.example.happybirthday            I  [VRI[MainActivity]#4](f:0,a:1) [syncNextTransaction] hasPrevCallback:0 mSyncTransaction:0 mTransactionReadyCallback:0 mAcquireSingleBuffer:1
2024-02-28 01:03:37.627 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:03:37.628 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=true; winMode=1; isMrgNull=true
2024-02-28 01:03:37.628 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 1
2024-02-28 01:03:37.636 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 6
2024-02-28 01:03:37.662 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f62c0
2024-02-28 01:03:37.662 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057ffcc0
2024-02-28 01:03:37.662 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405811490
2024-02-28 01:03:37.664 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405803aa0 count: 2
2024-02-28 01:03:37.664 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405803aa0
2024-02-28 01:03:37.664 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fdb10 count: 2
2024-02-28 01:03:37.664 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fdb10
2024-02-28 01:03:37.894 31173-31173 RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:03:37.895 31173-31173 RtgSchedEvent           com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 01:03:38.093 31173-664   SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405800500 count: 2
2024-02-28 01:03:38.093 31173-664   SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405800500
2024-02-28 01:03:40.908 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:03:40.908 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=false; winMode=1; isMrgNull=true
2024-02-28 01:03:40.924  3994-3994  HnLauncher              com.hihonor.android.launcher         E  BubbleTextView draw: mIsBadgeNeedHide is false, com.hihonor.android.launcher.BubbleTextView{85d4f2a VFED..CL. ........ 32,1665-286,1974 #9c010005}, BubbleTextView: {ShortcutInfo: title: Happy Birthday, component: ComponentInfo{com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:03:40.931 31173-31173 RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:03:40.931 31173-31173 RtgSched                com.example.happybirthday            D  resetRtgSchedHandle failed enable:0
2024-02-28 01:03:41.562 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f7080
2024-02-28 01:03:41.577 31173-31173 Lifecycle               com.example.happybirthday            D  onPause
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405811490 count: 2
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405811490
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057ffcc0 count: 2
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057ffcc0
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f62c0 count: 2
2024-02-28 01:03:41.578 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f62c0
2024-02-28 01:03:41.589 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#4(BLAST Consumer)4](id:79c500000004,api:1,p:31173,c:31173) disconnect: api 1
2024-02-28 01:03:41.599  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:15 fg:false mUid:10341
2024-02-28 01:03:41.601 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f8050 count: 3
2024-02-28 01:03:41.601 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f62c0
2024-02-28 01:03:41.606 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f7080 count: 2
2024-02-28 01:03:41.606 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f7080
2024-02-28 01:03:41.607 31173-31173 BufferQueueConsumer     com.example.happybirthday            I  [VRI[MainActivity]#4(BLAST Consumer)4](id:79c500000004,api:0,p:-1,c:31173) disconnect



___________________________________________________________
Выход из приложения, следующий этап жизненного цикла активити





2024-02-28 01:03:41.607 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f8050
2024-02-28 01:03:41.616 31173-31173 Lifecycle               com.example.happybirthday            D  onStop
2024-02-28 01:03:41.617 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 4
2024-02-28 01:03:41.619 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f62c0 count: 2
2024-02-28 01:03:41.619 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f62c0
2024-02-28 01:03:42.546 31173-31211 ZrHung.AppEyeUiProbe    com.example.happybirthday            D  not watching, wait.
2024-02-28 01:03:44.716 31173-31219 skia                    com.example.happybirthday            D  purge small: dur=0.0ms, request=144842, total=0, limit=16777216, totalcnt=0, limitcnt=2048, tryfree=144842, tryfreecnt=0, freed=144842, freedcnt=4
2024-02-28 01:03:45.755 31173-31508 skia                    com.example.happybirthday            D  SkBackgroundThread work in batch 0.3ms, 4
2024-02-28 01:03:46.618 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  handleReleaseCache: pid=31173
2024-02-28 01:03:46.619 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  init lrucache size: 4194304 pid=31173
__________________________
Включен режим поворота экрана и экран повернут

024-02-28 01:04:43.456 31173-31173 Choreographer           com.example.happybirthday            D  still have 2 traversal callbacks
2024-02-28 01:05:14.699  1931-2095  ActivityTaskManager     system_server                        E  START {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10600000 hwFlg=0x10 cmp=com.example.happybirthday/.MainActivity bnds=[35,1705][289,2014] (has extras)} result: 2
2024-02-28 01:05:14.755  3994-3994  HnLauncher              com.hihonor.android.launcher         E  BubbleTextView draw: mIsBadgeNeedHide is false, com.hihonor.android.launcher.BubbleTextView{85d4f2a VFED..CL. ........ 32,1665-286,1974 #9c010005}, BubbleTextView: {ShortcutInfo: title: Happy Birthday, component: ComponentInfo{com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:05:15.079 31173-31173 ActivityThread          com.example.happybirthday            D  Won't deliver top position change in state=5
2024-02-28 01:05:15.093 31173-31173 ActivityThread          com.example.happybirthday            I  Performing restart of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} start=false callers:android.app.servertransaction.TransactionExecutor.performLifecycleSequence:258 android.app.servertransaction.TransactionExecutor.cycleToPath:215 android.app.servertransaction.TransactionExecutor.executeLifecycleState:187 android.app.servertransaction.TransactionExecutor.execute:105 android.app.ActivityThread$H.handleMessage:2838 android.os.Handler.dispatchMessage:114 android.os.Looper.loopOnce:206 android.os.Looper.loop:296 android.app.ActivityThread.main:9159 java.lang.reflect.Method.invoke:-2 

_______________________________________________
еще раз запустил приложение

2024-02-28 01:05:15.095 31173-31173 Lifecycle               com.example.happybirthday            D  onStart
2024-02-28 01:05:15.105 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 0
2024-02-28 01:05:15.111 31173-31211 ZrHung.AppEyeUiProbe    com.example.happybirthday            D  restart watching
2024-02-28 01:05:15.113 31173-31173 Lifecycle               com.example.happybirthday            D  onResume
2024-02-28 01:05:15.119 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 0
2024-02-28 01:05:15.123  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:2 fg:true mUid:10341
2024-02-28 01:05:15.161 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057fc5c0
2024-02-28 01:05:15.173 31173-31173 BufferQueueConsumer     com.example.happybirthday            I  [](id:79c500000005,api:0,p:-1,c:31173) connect: controlledByApp=false
2024-02-28 01:05:15.176 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057fd9b0
2024-02-28 01:05:15.176 31173-31195 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405801f20
2024-02-28 01:05:15.181 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#5(BLAST Consumer)5](id:79c500000005,api:0,p:-1,c:31173) connect: api=1 producerControlledByApp=true
2024-02-28 01:05:15.182 31173-31219 OpenGLRenderer          com.example.happybirthday            E  Unable to match the desired swap behavior.
2024-02-28 01:05:15.245 31173-31173 HwViewRootImpl          com.example.happybirthday            I  removeInvalidNode all the node in jank list is out of time
2024-02-28 01:05:15.254 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:05:15.255 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=true; winMode=1; isMrgNull=true
2024-02-28 01:05:15.257 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 1
2024-02-28 01:05:15.276 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 6
2024-02-28 01:05:15.306 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074058024a0
2024-02-28 01:05:15.306 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074058033c0
2024-02-28 01:05:15.306 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405803940
2024-02-28 01:05:15.309 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405801f20 count: 2
2024-02-28 01:05:15.309 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405801f20
2024-02-28 01:05:15.309 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fd9b0 count: 2
2024-02-28 01:05:15.309 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fd9b0
2024-02-28 01:05:15.351 31173-31173 RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:05:15.351 31173-31173 RtgSchedEvent     

_____________________________________________
свернул приложение, этап паузы жизненного цикла



      com.example.happybirthday            I  current pid:31173 AppType:-1
2024-02-28 01:05:16.169 31173-31173 Lifecycle               com.example.happybirthday            D  onPause
2024-02-28 01:05:16.170 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057fc5c0 count: 4
2024-02-28 01:05:16.170 31173-31173 Lifecycle               com.example.happybirthday            D  onStop
2024-02-28 01:05:16.174 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074058045a0
2024-02-28 01:05:16.174 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405802760
2024-02-28 01:05:16.174 31173-31215 SurfaceControl          com.example.happybirthday    
______________________________________________________
закрыл приложение, что вызвало метод разрушения




        I  SurfaceControl 0xb400007405803730
2024-02-28 01:05:16.176 31173-31173 Lifecycle               com.example.happybirthday            D  onDestroy
2024-02-28 01:05:16.176 31173-31173 ActivityThread          com.example.happybirthday            I  Remove activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
2024-02-28 01:05:16.176 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  dispatchDetachedFromWindow in doDie
2024-02-28 01:05:16.179 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#5(BLAST Consumer)5](id:79c500000005,api:1,p:31173,c:31173) disconnect: api 1
2024-02-28 01:05:16.179 31173-31219 BufferQueueConsumer     com.example.happybirthday            I  [VRI[MainActivity]#5(BLAST Consumer)5](id:79c500000005,api:0,p:-1,c:31173) disconnect
2024-02-28 01:05:16.180 31173-31219 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057fc5c0
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405803940 count: 2
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405803940
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058033c0 count: 2
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058033c0
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058024a0 count: 2
2024-02-28 01:05:16.190 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058024a0
2024-02-28 01:05:16.192 31173-31173 ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:05:16.199  1931-3786  WindowManager           system_server                        E  setOnBackInvokedCallback(): No window state for package:com.example.happybirthday
2024-02-28 01:05:16.202 31173-31173 ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 01:05:16.209 31173-31173 DecorView[]             com.example.happybirthday            I   old windowMode:0 new windoMode:1
2024-02-28 01:05:16.216 31173-31173 ActivityThread          com.example.happybirthday            I  add activity client record, r= ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@5c852be
_____________________________________________________________
снова запустил приложение

2024-02-28 01:05:16.217 31173-31173 Lifecycle               com.example.happybirthday            D  onStart
2024-02-28 01:05:16.219 31173-31173 Lifecycle               com.example.happybirthday            D  onResume
2024-02-28 01:05:16.219 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 4
2024-02-28 01:05:16.229 31173-31173 InputEventReceiver      com.example.happybirthday            D  dispatchInputInterval 1000000
2024-02-28 01:05:16.230 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 0
2024-02-28 01:05:16.235 31173-31173 PhoneWindow             com.example.happybirthday            D  onViewRootImplSet activityToken android.os.BinderProxy@5c852be,activityClientRecord ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}},isHnNavigationHide false isHidePrivateFlag = false
2024-02-28 01:05:16.235 31173-31173 HwPhoneWindow           com.example.happybirthday            D  onViewRootImplSet activityToken android.os.BinderProxy@5c852be,activityClientRecord ActivityRecord{c754f1f token=android.os.BinderProxy@5c852be {com.example.happybirthday/com.example.happybirthday.MainActivity}},isHwNavigationHide false
2024-02-28 01:05:16.236 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb400007405802e40
2024-02-28 01:05:16.237 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f6a50
2024-02-28 01:05:16.240  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:2 fg:true mUid:10341
2024-02-28 01:05:16.240 31173-2190  HiTouch_HiTouchSensor   com.example.happybirthday            W  depended package hiTouch does n't exist!
2024-02-28 01:05:16.240 31173-2190  HiTouch_HiTouchSensor   com.example.happybirthday            I  HiTouch restricted: system app HiTouch don't exist.
2024-02-28 01:05:16.240 31173-2190  HiTouch_Pr...reDetector com.example.happybirthday            D  onAttached, package=com.example.happybirthday, windowType=1, mHiTouchRestricted=true
2024-02-28 01:05:16.290 31173-31173 DecorView[]             com.example.happybirthday            I   old windowMode:1 new windoMode:1
2024-02-28 01:05:16.299 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f8050
2024-02-28 01:05:16.299 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb40000740581a650
2024-02-28 01:05:16.300 31173-31173 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f7080
2024-02-28 01:05:16.301 31173-31173 BufferQueueConsumer     com.example.happybirthday            I  [](id:79c500000006,api:0,p:-1,c:31173) connect: controlledByApp=false
2024-02-28 01:05:16.304 31173-31219 BufferQueueProducer     com.example.happybirthday            I  [VRI[MainActivity]#6(BLAST Consumer)6](id:79c500000006,api:0,p:-1,c:31173) connect: api=1 producerControlledByApp=true
2024-02-28 01:05:16.305 31173-31219 OpenGLRenderer          com.example.happybirthday            E  Unable to match the desired swap behavior.
2024-02-28 01:05:16.310 31173-31173 HwForceDarkManager      com.example.happybirthday            I  setAllowedHwForceDark:false package:com.example.happybirthday mCurrProcessState:0 mIsPackageNameChange:false hwForceDarkState:0 isViewAllowedForceDark:true isLastHonorForceDark:false
2024-02-28 01:05:16.334 31173-31219 Parcel                  com.example.happybirthday            W  Expecting binder but got null!
2024-02-28 01:05:16.336 31173-31173 RemoteInpu...ectionImpl com.example.happybirthday            W  getExtractedText on inactive InputConnection
2024-02-28 01:05:16.336 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058045a0 count: 2
2024-02-28 01:05:16.336 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058045a0
2024-02-28 01:05:16.336 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405802760 count: 2
2024-02-28 01:05:16.337 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405802760
2024-02-28 01:05:16.337 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405803730 count: 2
2024-02-28 01:05:16.337 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405803730
2024-02-28 01:05:16.343 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f7080 count: 2
2024-02-28 01:05:16.343 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f7080
2024-02-28 01:05:16.343 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb40000740581a650 count: 2
2024-02-28 01:05:16.343 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb40000740581a650
2024-02-28 01:05:16.343 31173-31173 RemoteInpu...ectionImpl com.example.happybirthday            W  getTextBeforeCursor on inactive InputConnection
2024-02-28 01:05:16.360 31173-31173 VRI[MainActivity]       com.example.happybirthday            I  send MSG_WINDOW_FOCUS_CHANGED msg
2024-02-28 01:05:16.361 31173-31173 DecorView               com.example.happybirthday            D  showOrHideHighlightView: hasFocus=true; winMode=1; isMrgNull=true
2024-02-28 01:05:16.361 31173-31173 InputMethodManager      com.example.happybirthday            W  startInputReason = 1
2024-02-28 01:05:16.490 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f66e0
2024-02-28 01:05:16.490 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057faf10
2024-02-28 01:05:16.490 31173-31215 SurfaceControl          com.example.happybirthday            I  SurfaceControl 0xb4000074057f62c0
2024-02-28 01:05:16.492 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074057f6a50 count: 2
2024-02-28 01:05:16.492 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074057f6a50
2024-02-28 01:05:16.492 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb400007405802e40 count: 2
2024-02-28 01:05:16.492 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb400007405802e40
____________________________________________________
свернул приложение

2024-02-28 01:07:56.552 31173-31173 Lifecycle               com.example.happybirthday            D  onStop
2024-02-28 01:07:56.553 31173-31173 DecorView[]             com.example.happybirthday            I  set decor visibility 4
2024-02-28 01:07:56.567  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:15 fg:false mUid:10341
2024-02-28 01:07:56.571 31173-31173 SurfaceControl          com.example.happybirthday            I  nativeRelease 0xb4000074058153d0 count: 2
2024-02-28 01:07:56.571 31173-31173 SurfaceControl          com.example.happybirthday            I  ~SurfaceControl 0xb4000074058153d0
2024-02-28 01:07:56.723 31173-31211 ZrHung.AppEyeUiProbe    com.example.happybirthday            D  not watching, wait.
2024-02-28 01:07:59.533 31173-31219 skia                    com.example.happybirthday            D  purge small: dur=0.0ms, request=144842, total=0, limit=16777216, totalcnt=0, limitcnt=2048, tryfree=144842, tryfreecnt=0, freed=144842, freedcnt=4
2024-02-28 01:08:00.572 31173-31508 skia                    com.example.happybirthday            D  SkBackgroundThread work in batch 0.3ms, 4
2024-02-28 01:08:01.553 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  handleReleaseCache: pid=31173
2024-02-28 01:08:01.554 31173-31173 AwareBitmapCacher       com.example.happybirthday            I  init lrucache size: 4194304 pid=31173
_____________________________________________________________________________________________________
после вызова метода finish()

2024-02-28 01:17:11.713  8068-8085  AwareBitmapCacher       com.example.happybirthday            I  init processName:com.example.happybirthday pid=8068 uid=10341
2024-02-28 01:17:11.719  8068-8086  AwareLog                com.example.happybirthday            W  AwareAppScheduleManager: dalvik.system.DexFile.isOatBootImageOutOfDate reflect failed
2024-02-28 01:17:11.735  8068-8068  SystemFonts             com.example.happybirthday            I  loadHwSystemFonts, isNightMode true, fontWeightScale is 100
2024-02-28 01:17:11.737  8068-8068  HwTypeface              com.example.happybirthday            I  update default font
2024-02-28 01:17:11.739  8068-8068  ActivityThread          com.example.happybirthday            I  finishPreloaded preloadStatus 0
2024-02-28 01:17:11.741  8068-8068  RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:17:11.741  8068-8068  RmeSchedManager         com.example.happybirthday            I  init Rme, version is: v1.0
2024-02-28 01:17:11.741  8068-8068  RtgSchedEvent           com.example.happybirthday            I  current pid:8068 AppType:-1
2024-02-28 01:17:11.743  8068-8068  ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{1303035 token=android.os.BinderProxy@d08526c {com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:17:11.746  8068-8068  e.happybirthday         com.example.happybirthday            W  ApkAssets1 has N = 0
2024-02-28 01:17:11.746  8068-8068  e.happybirthday         com.example.happybirthday            W  ApkAssets1 has N = 0
2024-02-28 01:17:11.751  8068-8103  GamesAware              com.example.happybirthday            E  isInSupportList 'com.example.happybirthday' is a game? no; or product supported? no
2024-02-28 01:17:11.752  8068-8103  iGraphics               com.example.happybirthday            I  [GetTotalMemory] total memory =7615028KB
2024-02-28 01:17:11.752  8068-8103  iGraphics               com.example.happybirthday            I  [0020080c] pn: com.example.happybirthday, p: 8068
2024-02-28 01:17:11.752  8068-8103  e.happybirthday         com.example.happybirthday            I  HwCustType is 0
2024-02-28 01:17:11.753  8068-8103  e.happybirthday         com.example.happybirthday            E  open file error
2024-02-28 01:17:11.753  8068-8103  e.happybirthday         com.example.happybirthday            I  no cota live update cust policy found
2024-02-28 01:17:11.753  8068-8103  e.happybirthday         com.example.happybirthday            I  GetCfgDirRealPolicyValue: custPolicyDirs: /system/magic/base:/system/magic/oversea:/system/magic/oversea_honor:/vendor/etc:/odm/etc:/odm/hn_odm/FNE-N29:/product_h/etc:/product_h/region_comm/oversea:/preas/oversea:/product_h/hn_oem/FNE-N29:/preload/FNE-N29/def/meafnaf:/cust/global:/cust/def/meafnaf:/product_h/special_cust/FNE-N29/def/meafnaf:/cust/cotalite:/cust/ecota
2024-02-28 01:17:11.756  8068-8103  iGraphics               com.example.happybirthday            I  [0030080c] no spt app: com.example.happybirthday

__________________________________________
попытался запустить приложение, но оно не открывалось из-за внутренней ошибки, вызванной методом finish()


2024-02-28 01:17:11.771  8068-8068  ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 01:17:11.792  8068-8068  Lifecycle               com.example.happybirthday            D  finish
2024-02-28 01:17:11.820  8068-8068  DecorView[]             com.example.happybirthday            I   old windowMode:0 new windoMode:1
2024-02-28 01:17:11.844  8068-8068  ActivityThread          com.example.happybirthday            I  add activity client record, r= ActivityRecord{1303035 token=android.os.BinderProxy@d08526c {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@d08526c
2024-02-28 01:17:11.847  8068-8068  ActivityThread          com.example.happybirthday            D  Won't deliver top position change in state=1
2024-02-28 01:17:11.847  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:2 fg:true mUid:10341
2024-02-28 01:17:11.852  8068-8068  ActivityThread          com.example.happybirthday            D  Won't deliver top position change in state=1
2024-02-28 01:17:11.901  3877-4135  DollieAdapterService    com.hihonor.systemserver             E  notifyActivityState pkg:com.example.happybirthday/com.example.happybirthday.MainActivity state:18 fg:false mUid:10341
2024-02-28 01:17:12.284  8068-8068  RtgSchedIpcFile         com.example.happybirthday            D  setCommandByIoctl failed ret:-1, cmdid:22, errno:103

____________________________________________________________
в итоге закрыл приложение


2024-02-28 01:17:12.295  8068-8068  Lifecycle               com.example.happybirthday            D  onDestroy
2024-02-28 01:17:12.296  8068-8068  ActivityThread          com.example.happybirthday            I  Remove activity client record, r= ActivityRecord{1303035 token=android.os.BinderProxy@d08526c {com.example.happybirthday/com.example.happybirthday.MainActivity}} token= android.os.BinderProxy@d08526c
2024-02-28 01:17:12.297  8068-8068  RtgSchedIpcFile         com.example.happybirthday            D  setCommandByIoctl failed ret:-1, cmdid:23, errno:103
2024-02-28 01:17:12.785  8068-8088  ZrHung.AppEyeUiProbe    com.example.happybirthday            D  not watching, wait.
2024-02-28 01:17:16.736  8068-8068  AwareBitmapCacher       com.example.happybirthday            I  init lrucache size: 4194304 pid=8068
2024-02-28 01:17:16.738  8068-8068  Resource                com.example.happybirthday            V  printErrorResource, maybe not an error because module has entative action to load resource.
2024-02-28 01:17:17.118  8068-8148  ProfileInstaller        com.example.happybirthday            D  Installing profile for com.example.happybirthday
2024-02-28 01:17:19.275  3994-3994  HnLauncher              com.hihonor.android.launcher         E  BubbleTextView draw: mIsBadgeNeedHide is false, com.hihonor.android.launcher.BubbleTextView{85d4f2a VFED..CL. ........ 32,1665-286,1974 #9c010005}, BubbleTextView: {ShortcutInfo: title: Happy Birthday, component: ComponentInfo{com.example.happybirthday/com.example.happybirthday.MainActivity}}
2024-02-28 01:17:19.280  8068-8088  ZrHung.AppEyeUiProbe    com.example.happybirthday            D  restart watching
2024-02-28 01:17:19.283  8068-8068  ActivityThread          com.example.happybirthday            V  Handling launch of ActivityRecord{f3576cc token=android.os.BinderProxy@208c8ff {com.example.happybirthday/com.example.happybirthday.MainActivity}}

____________________________________
попытался еще раз безрезультатно его открыть


2024-02-28 01:17:19.318  8068-8068  ActivityThread          com.example.happybirthday            V  callActivityOnCreate
2024-02-28 01:17:19.330  8068-8068  Lifecycle               com.example.happybirthday            D  finish

