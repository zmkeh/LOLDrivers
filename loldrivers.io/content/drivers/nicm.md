+++

description = ""
title = "nicm.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# nicm.sys ![:inline](/images/twitter_verified.png) 


### Description

nicm.sys is a vulnerable driver. CVE-2013-3956.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/22823fed979903f8dfe3b5d28537eb47.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create nicm.sys binPath=C:\windows\temp \n \n \n  icm.sys type=kernel &amp;&amp; sc.exe start nicm.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/jbaines-r7/dellicious"> https://github.com/jbaines-r7/dellicious</a></li>
<li><a href=" https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/"> https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<li><a href="https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/">https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | nicm.sys |
| MD5                | [22823fed979903f8dfe3b5d28537eb47](https://www.virustotal.com/gui/file/22823fed979903f8dfe3b5d28537eb47) |
| SHA1               | [d098600152e5ee6a8238d414d2a77a34da8afaaa](https://www.virustotal.com/gui/file/d098600152e5ee6a8238d414d2a77a34da8afaaa) |
| SHA256             | [e6056443537d4d2314dabca1b9168f1eaaf17a14eb41f6f5741b6b82b3119790](https://www.virustotal.com/gui/file/e6056443537d4d2314dabca1b9168f1eaaf17a14eb41f6f5741b6b82b3119790) |
| Authentihash MD5   | [4f9030161d60cde6099483f6763e75db](https://www.virustotal.com/gui/search/authentihash%253A4f9030161d60cde6099483f6763e75db) |
| Authentihash SHA1  | [6ec1c1cd8c38de77cb35260deeb491e563b5c721](https://www.virustotal.com/gui/search/authentihash%253A6ec1c1cd8c38de77cb35260deeb491e563b5c721) |
| Authentihash SHA256| [aa0a1de59d8697c5f39937edeb778fde7c596b71d64d3427c80fe4c060488990](https://www.virustotal.com/gui/search/authentihash%253Aaa0a1de59d8697c5f39937edeb778fde7c596b71d64d3427c80fe4c060488990) |
| Signature         | Novell, Inc., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |
| Company           | Novell, Inc. |
| Description       | Novell XTCOM Services Driver |
| Product           | Novell XTier |
| OriginalFilename  | libnicm.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExAcquireResourceExclusiveLite
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* strstr
* RtlInitAnsiString
* ExAcquireResourceSharedLite
* ExReleaseResourceLite
* RtlEqualString
* MmUnmapLockedPages
* ProbeForRead
* IoDeleteSymbolicLink
* IoRegisterShutdownNotification
* KeInitializeMutex
* KeLeaveCriticalRegion
* IoDeleteDevice
* ProbeForWrite
* IoFreeMdl
* KeEnterCriticalRegion
* KeReleaseMutex
* ZwCreateFile
* MmMapLockedPagesSpecifyCache
* IoUnregisterShutdownNotification
* ZwClose
* IofCompleteRequest
* IoSetTopLevelIrp
* KeWaitForSingleObject
* MmProbeAndLockPages
* MmUnlockPages
* ExDeleteResourceLite
* IoGetTopLevelIrp
* IoCreateSymbolicLink
* IoCreateDevice
* ExInitializeResourceLite
* NtSetSecurityObject
* DbgPrintEx
* IoAllocateMdl
* RtlCreateSecurityDescriptor
* IoGetCurrentProcess
* ZwCreateKey
* RtlAnsiStringToUnicodeString
* ZwReadFile
* RtlInitUnicodeString
* RtlAppendUnicodeToString
* RtlUnicodeStringToAnsiString
* ZwSetValueKey
* ZwQuerySystemInformation
* RtlInitString
* KeDelayExecutionThread
* RtlFreeUnicodeString
* ZwWaitForSingleObject
* ZwQueryValueKey
* ZwQueryDirectoryFile
* RtlAppendUnicodeStringToString
* RtlCopyString
* MmIsAddressValid
* ZwOpenFile
* ZwQueryInformationFile
* ZwLoadDriver
* ZwOpenKey
* KeBugCheckEx
* __C_specific_handler

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}
* NicmCreateInstance
* NicmDeregisterClassFactory
* NicmGetVersion
* NicmRegisterClassFactory
* XTComCreateInstance
* XTComDeregisterClassFactory
* XTComFreeUnusedLibrariesEx
* XTComGetClassObject
* XTComGetVersion
* XTComInitialize
* XTComRegisterClassFactory

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nicm.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
