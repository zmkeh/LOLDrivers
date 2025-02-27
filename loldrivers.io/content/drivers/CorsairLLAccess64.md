+++

description = ""
title = "CorsairLLAccess64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# CorsairLLAccess64.sys ![:inline](/images/twitter_verified.png) 


### Description

CorsairLLAccess64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/803a371a78d528a44ef8777f67443b16.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create CorsairLLAccess64.sys binPath=C:\windows\temp\CorsairLLAccess64.sys     type=kernel &amp;&amp; sc.exe start CorsairLLAccess64.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/elastic/protections-artifacts/search?q=VulnDriver"> https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/search?q=VulnDriver">https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | CorsairLLAccess64.sys |
| MD5                | [803a371a78d528a44ef8777f67443b16](https://www.virustotal.com/gui/file/803a371a78d528a44ef8777f67443b16) |
| SHA1               | [5fb9421be8a8b08ec395d05e00fd45eb753b593a](https://www.virustotal.com/gui/file/5fb9421be8a8b08ec395d05e00fd45eb753b593a) |
| SHA256             | [000547560fea0dd4b477eb28bf781ea67bf83c748945ce8923f90fdd14eb7a4b](https://www.virustotal.com/gui/file/000547560fea0dd4b477eb28bf781ea67bf83c748945ce8923f90fdd14eb7a4b) |
| Authentihash MD5   | [daa859bc87e256d7cbf1d86285d96f9b](https://www.virustotal.com/gui/search/authentihash%253Adaa859bc87e256d7cbf1d86285d96f9b) |
| Authentihash SHA1  | [d29d73b2add87a7daf3c626d593599ef6b9560ca](https://www.virustotal.com/gui/search/authentihash%253Ad29d73b2add87a7daf3c626d593599ef6b9560ca) |
| Authentihash SHA256| [e4ac5c7fbb41ee988029b27d8b6be574725689fd1365f5a56f5a12d9120f86c6](https://www.virustotal.com/gui/search/authentihash%253Ae4ac5c7fbb41ee988029b27d8b6be574725689fd1365f5a56f5a12d9120f86c6) |
| Signature         | Microsoft Windows Hardware Compatibility Publisher, Microsoft Windows Third Party Component CA 2014, Microsoft Root Certificate Authority 2010   |
| Company           | Corsair Memory, Inc. |
| Description       | Corsair LL Access |
| Product           | Corsair LL Access |
| OriginalFilename  | Corsair LL Access |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* RtlInitUnicodeString
* RtlGetVersion
* KeInitializeMutex
* KeReleaseMutex
* KeWaitForSingleObject
* ExQueryDepthSList
* ExpInterlockedPopEntrySList
* ExpInterlockedPushEntrySList
* ExInitializeNPagedLookasideList
* ExDeleteNPagedLookasideList
* MmBuildMdlForNonPagedPool
* MmMapLockedPagesSpecifyCache
* wcsncmp
* MmMapIoSpace
* MmUnmapIoSpace
* IoAllocateMdl
* IofCompleteRequest
* IoCreateDevice
* IoCreateSymbolicLink
* IoDeleteDevice
* IoDeleteSymbolicLink
* IoFreeMdl
* IoGetRequestorProcessId
* __C_specific_handler
* KeBugCheckEx
* wcsncat_s
* MmUnmapLockedPages
* wcscpy_s
* HalSetBusDataByOffset
* HalGetBusDataByOffset

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/corsairllaccess64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
