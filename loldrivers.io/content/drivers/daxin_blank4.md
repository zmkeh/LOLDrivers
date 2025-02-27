+++

description = ""
title = "daxin_blank4.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# daxin_blank4.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver used in the Daxin malware campaign.

- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/491aec2249ad8e2020f9f9b559ab68a8.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create daxin_blank4.sys binPath=C:\windows\temp\daxin_blank4.sys     type=kernel &amp;&amp; sc.exe start daxin_blank4.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://gist.github.com/MHaggis/9ab3bb795a6018d70fb11fa7c31f8f48">https://gist.github.com/MHaggis/9ab3bb795a6018d70fb11fa7c31f8f48</a></li>
<li><a href="https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/daxin-backdoor-espionage">https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/daxin-backdoor-espionage</a></li>
<li><a href=""></a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | daxin_blank4.sys |
| MD5                | [491aec2249ad8e2020f9f9b559ab68a8](https://www.virustotal.com/gui/file/491aec2249ad8e2020f9f9b559ab68a8) |
| SHA1               | [8692274681e8d10c26ddf2b993f31974b04f5bf0](https://www.virustotal.com/gui/file/8692274681e8d10c26ddf2b993f31974b04f5bf0) |
| SHA256             | [8dafe5f3d0527b66f6857559e3c81872699003e0f2ffda9202a1b5e29db2002e](https://www.virustotal.com/gui/file/8dafe5f3d0527b66f6857559e3c81872699003e0f2ffda9202a1b5e29db2002e) |
| Authentihash MD5   | [f66f4d6b97b9e7b0e467daed2ed69bed](https://www.virustotal.com/gui/search/authentihash%253Af66f4d6b97b9e7b0e467daed2ed69bed) |
| Authentihash SHA1  | [c8f227b45d27c43db4b661ef610efbfacfda8a75](https://www.virustotal.com/gui/search/authentihash%253Ac8f227b45d27c43db4b661ef610efbfacfda8a75) |
| Authentihash SHA256| [15b081ec83a89182b5bb0a642d56513f40810b5b0a42e904ab6d3fa8f34c0446](https://www.virustotal.com/gui/search/authentihash%253A15b081ec83a89182b5bb0a642d56513f40810b5b0a42e904ab6d3fa8f34c0446) |
| Publisher         | n/a |
| Signature         | U, n, s, i, g, n, e, d   |
| Date                | 8:42 AM 4/20/2010 |


#### Imports
{{< details "Expand" >}}
* NTOSKRNL.EXE
* HAL.DLL
* ntoskrnl.exe
* NDIS.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* strlen
* IoFreeMdl
* MmMapLockedPagesSpecifyCache
* ZwClose
* IofCompleteRequest
* KeResetEvent
* InterlockedIncrement
* KeSetEvent
* InterlockedDecrement
* RtlUnicodeStringToInteger
* RtlInitUnicodeString
* KeInitializeEvent
* wcsncmp
* wcscat
* wcslen
* wcscpy
* MmBuildMdlForNonPagedPool
* IoAllocateMdl
* strncmp
* MmMapLockedPages
* MmProbeAndLockPages
* MmUnlockPages
* MmUnmapLockedPages
* RtlFreeUnicodeString
* ZwWriteFile
* ZwCreateFile
* RtlAnsiStringToUnicodeString
* strcat
* ZwReadFile
* ZwQueryInformationFile
* _wcsnicmp
* strcmp
* _stricmp
* MmGetSystemRoutineAddress
* ZwQueryValueKey
* ZwOpenKey
* IoCreateFile
* KeWaitForMultipleObjects
* strcpy
* RtlUnwind
* vsprintf
* KeWaitForSingleObject
* KeDelayExecutionThread
* PsTerminateSystemThread
* PsCreateSystemThread
* ObReferenceObjectByHandle
* ExFreePool
* KeInitializeSpinLock
* KeTickCount
* memset
* memcpy
* RtlCompareUnicodeString
* ExAllocatePoolWithTag
* KfAcquireSpinLock
* KfReleaseSpinLock
* PsGetVersion
* ZwTerminateProcess
* ZwOpenProcess
* RtlSetDaclSecurityDescriptor
* RtlAddAccessAllowedAce
* RtlCreateAcl
* RtlLengthSid
* RtlCreateSecurityDescriptor
* ZwWaitForSingleObject
* NtFsControlFile
* NtWriteFile
* NtReadFile
* RtlLengthRequiredSid
* RtlImageDirectoryEntryToData
* ZwQueryInformationProcess
* ZwQuerySystemInformation
* PsLookupProcessByProcessId
* KeAttachProcess
* KeDetachProcess
* PsLookupThreadByThreadId
* KeInitializeApc
* KeInsertQueueApc
* ZwOpenFile
* ZwDeviceIoControlFile
* PsThreadType
* NtQuerySystemInformation
* NdisAllocateMemory
* NdisAllocatePacket
* NdisCopyFromPacketToPacket
* NdisFreePacket
* NdisAllocateBuffer
* NdisDeregisterProtocol
* NdisRegisterProtocol
* NdisAllocateBufferPool
* NdisAllocatePacketPool
* NdisFreeBufferPool
* NdisFreePacketPool
* NdisFreeMemory

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/daxin_blank4.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
