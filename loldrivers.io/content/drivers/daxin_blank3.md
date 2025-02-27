+++

description = ""
title = "daxin_blank3.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# daxin_blank3.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver used in the Daxin malware campaign.

- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/bd5b0514f3b40f139d8079138d01b5f6.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create daxin_blank3.sys binPath=C:\windows\temp\daxin_blank3.sys     type=kernel &amp;&amp; sc.exe start daxin_blank3.sys
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
| Filename           | daxin_blank3.sys |
| MD5                | [bd5b0514f3b40f139d8079138d01b5f6](https://www.virustotal.com/gui/file/bd5b0514f3b40f139d8079138d01b5f6) |
| SHA1               | [73bac306292b4e9107147db94d0d836fdb071e33](https://www.virustotal.com/gui/file/73bac306292b4e9107147db94d0d836fdb071e33) |
| SHA256             | [7a7e8df7173387aec593e4fe2b45520ea3156c5f810d2bb1b2784efd1c922376](https://www.virustotal.com/gui/file/7a7e8df7173387aec593e4fe2b45520ea3156c5f810d2bb1b2784efd1c922376) |
| Authentihash MD5   | [800a604e6039d6dc93d68d116c38b640](https://www.virustotal.com/gui/search/authentihash%253A800a604e6039d6dc93d68d116c38b640) |
| Authentihash SHA1  | [75670f26e2df371741e8832012e06fdcd179b64c](https://www.virustotal.com/gui/search/authentihash%253A75670f26e2df371741e8832012e06fdcd179b64c) |
| Authentihash SHA256| [afb9e6b70f707149e7243e41ffafbdda463da9a890c56091c454df60608efa0f](https://www.virustotal.com/gui/search/authentihash%253Aafb9e6b70f707149e7243e41ffafbdda463da9a890c56091c454df60608efa0f) |
| Publisher         | n/a |
| Signature         | U, n, s, i, g, n, e, d   |
| Date                | 12:54 AM 11/18/2009 |


#### Imports
{{< details "Expand" >}}
* NTOSKRNL.EXE
* HAL.DLL
* ntoskrnl.exe
* NDIS.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
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
* strlen
* RtlCompareUnicodeString
* IoFreeMdl
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
* strncmp
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
* MmMapLockedPages
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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/daxin_blank3.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
