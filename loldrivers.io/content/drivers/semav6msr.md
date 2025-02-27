+++

description = ""
title = "semav6msr.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# semav6msr.sys ![:inline](/images/twitter_verified.png) 


### Description

semav6msr.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/07f83829e7429e60298440cd1e601a6a.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create semav6msr.sys binPath=C:\windows\temp\semav6msr.sys type=kernel &amp;&amp; sc.exe start semav6msr.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md"> https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<li><a href="https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md">https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | semav6msr.sys |
| MD5                | [07f83829e7429e60298440cd1e601a6a](https://www.virustotal.com/gui/file/07f83829e7429e60298440cd1e601a6a) |
| SHA1               | [643383938d5e0d4fd30d302af3e9293a4798e392](https://www.virustotal.com/gui/file/643383938d5e0d4fd30d302af3e9293a4798e392) |
| SHA256             | [9f1229cd8dd9092c27a01f5d56e3c0d59c2bb9f0139abf042e56f343637fda33](https://www.virustotal.com/gui/file/9f1229cd8dd9092c27a01f5d56e3c0d59c2bb9f0139abf042e56f343637fda33) |
| Authentihash MD5   | [79553d83580570e382d3b9c7e101df2b](https://www.virustotal.com/gui/search/authentihash%253A79553d83580570e382d3b9c7e101df2b) |
| Authentihash SHA1  | [e3dbe2aa03847df621591a4cad69a5609de5c237](https://www.virustotal.com/gui/search/authentihash%253Ae3dbe2aa03847df621591a4cad69a5609de5c237) |
| Authentihash SHA256| [eb71a8ecef692e74ae356e8cb734029b233185ee5c2ccb6cc87cc6b36bea65cf](https://www.virustotal.com/gui/search/authentihash%253Aeb71a8ecef692e74ae356e8cb734029b233185ee5c2ccb6cc87cc6b36bea65cf) |
| Signature         | Intel(R) Code Signing External, Intel External Basic Issuing CA 3B, Intel External Basic Policy CA, Sectigo (AddTrust)   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* KeQueryActiveProcessors
* KeQueryActiveProcessorCount
* IoDeleteSymbolicLink
* KeSetSystemAffinityThreadEx
* RtlInitUnicodeString
* IoDeleteDevice
* MmUnmapIoSpace
* MmMapIoSpace
* IofCompleteRequest
* KeRevertToUserAffinityThreadEx
* IoCreateSymbolicLink
* IoCreateDevice
* RtlAssert
* DbgPrint
* KeBugCheckEx
* __C_specific_handler

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/semav6msr.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
