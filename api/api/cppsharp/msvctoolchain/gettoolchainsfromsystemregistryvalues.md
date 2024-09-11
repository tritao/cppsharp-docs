---
title: MSVCToolchain.GetToolchainsFromSystemRegistryValues(string,string,RegistryView)
slug: api/cppsharp.msvctoolchain.gettoolchainsfromsystemregistryvalues
---
Method in [MSVCToolchain](/api/cppsharp/msvctoolchain)

## Summary


Read registry strings looking for matching values.


```csharp
public static List<ToolchainVersion> GetToolchainsFromSystemRegistryValues(
    string keyPath, string matchValue, RegistryView view)
```

## Parameters

|Name|Description|
|:---|:---|
|`string` keyPath|The path to the key in the registry.|
|`string` matchValue|The value to match in the located key, if any.|
|`Microsoft.Win32.RegistryView` view|The type of registry, 32 or 64, to target.|

