+++

description = ""
title = "PCHunter.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# PCHunter.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

PCHunter.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/c2c1b8c00b99e913d992a870ed478a24.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create PCHunter.sys binPath=C:\windows\temp\PCHunter.sys type=kernel &amp;&amp; sc.exe start PCHunter.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules"> https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules">https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | PCHunter.sys |
| MD5                | [c2c1b8c00b99e913d992a870ed478a24](https://www.virustotal.com/gui/file/c2c1b8c00b99e913d992a870ed478a24) |
| SHA1               | [a64354aac2d68b4fa74b5829a9d42d90d83b040c](https://www.virustotal.com/gui/file/a64354aac2d68b4fa74b5829a9d42d90d83b040c) |
| SHA256             | [1b7fb154a7b7903a3c81f12f4b094f24a3c60a6a8cffca894c67c264ab7545fa](https://www.virustotal.com/gui/file/1b7fb154a7b7903a3c81f12f4b094f24a3c60a6a8cffca894c67c264ab7545fa) |
| Authentihash MD5   | [9655d43fd874e7a6720b36e7fd9fa6b7](https://www.virustotal.com/gui/search/authentihash%253A9655d43fd874e7a6720b36e7fd9fa6b7) |
| Authentihash SHA1  | [a14261c290339995b7430495f2dfdd1da64dcfc5](https://www.virustotal.com/gui/search/authentihash%253Aa14261c290339995b7430495f2dfdd1da64dcfc5) |
| Authentihash SHA256| [c2d209ed240027608003f8d32b621f8baaf5601aaf348e64269e4457a594c7c3](https://www.virustotal.com/gui/search/authentihash%253Ac2d209ed240027608003f8d32b621f8baaf5601aaf348e64269e4457a594c7c3) |
| Signature         | -   |
| Company           | 一普明为（北京）信息技术有限公司 |
| Description       | Epoolsoft Windows Information View Tools |
| Product           | PCHunter |
| OriginalFilename  | PCHunter.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* FLTMGR.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwCreateKey
* RtlInitUnicodeString
* ZwSetValueKey
* ExGetPreviousMode
* PsGetCurrentProcessId
* KeInitializeEvent
* ExFreePoolWithTag
* ZwQuerySymbolicLinkObject
* SeCreateAccessState
* KeSetEvent
* IoGetFileObjectGenericMapping
* ObCreateObject
* IoCreateFile
* MmBuildMdlForNonPagedPool
* ZwOpenSymbolicLinkObject
* IoFreeMdl
* IoFileObjectType
* ExAllocatePool
* ObReferenceObjectByHandle
* KeWaitForSingleObject
* IoFreeIrp
* MmProbeAndLockPages
* ZwClose
* MmUnlockPages
* ObOpenObjectByPointer
* IoAllocateMdl
* MmSectionObjectType
* _wcsicmp
* NtDeviceIoControlFile
* NtFsControlFile
* swprintf
* MmGetSystemRoutineAddress
* ExAllocatePoolWithTag
* ObQueryNameString
* KeBugCheckEx
* PsLookupThreadByThreadId
* IoDeleteSymbolicLink
* IoDeleteDevice
* wcsncat
* KeDelayExecutionThread
* wcsrchr
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* MmUnmapLockedPages
* MmMapLockedPagesSpecifyCache
* KeStackAttachProcess
* ObfDereferenceObject
* MmIsAddressValid
* KeUnstackDetachProcess
* PsLookupProcessByProcessId
* ProbeForRead
* IoGetCurrentProcess
* MmUserProbeAddress
* ProbeForWrite
* NtBuildNumber
* IoAllocateIrp
* MmSystemRangeStart
* __C_specific_handler
* FltReleaseFileNameInformation
* FltClose
* FltStartFiltering
* FltParseFileNameInformation
* FltCreateFile
* FltRegisterFilter
* FltUnregisterFilter
* FltGetFileNameInformation

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/pchunter.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
