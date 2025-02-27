+++

description = ""
title = "ntbios_2.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# ntbios_2.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver used in the Daxin malware campaign.

- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/50b39072d0ee9af5ef4824eca34be6e3.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create ntbios_2.sys binPath=C:\windows\temp \n \n \n  tbios_2.sys type=kernel &amp;&amp; sc.exe start ntbios_2.sys
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
| Filename           | ntbios_2.sys |
| MD5                | [50b39072d0ee9af5ef4824eca34be6e3](https://www.virustotal.com/gui/file/50b39072d0ee9af5ef4824eca34be6e3) |
| SHA1               | [064de88dbbea67c149e779aac05228e5405985c7](https://www.virustotal.com/gui/file/064de88dbbea67c149e779aac05228e5405985c7) |
| SHA256             | [c0d88db11d0f529754d290ed5f4c34b4dba8c4f2e5c4148866daabeab0d25f9c](https://www.virustotal.com/gui/file/c0d88db11d0f529754d290ed5f4c34b4dba8c4f2e5c4148866daabeab0d25f9c) |
| Authentihash MD5   | [a8e3b56b72814a842b557bfb6638b484](https://www.virustotal.com/gui/search/authentihash%253Aa8e3b56b72814a842b557bfb6638b484) |
| Authentihash SHA1  | [50231e21b8d8b2916d0fd53f3f58c6314473de1f](https://www.virustotal.com/gui/search/authentihash%253A50231e21b8d8b2916d0fd53f3f58c6314473de1f) |
| Authentihash SHA256| [59177fb7a0b11837368af1cc115f0d011ea19551070bd153795204ae1bd12e52](https://www.virustotal.com/gui/search/authentihash%253A59177fb7a0b11837368af1cc115f0d011ea19551070bd153795204ae1bd12e52) |
| Publisher         | n/a |
| Signature         | U, n, s, i, g, n, e, d   |
| Date                | 3:04 AM 5/18/2009 |
| Company           | Microsoft Corporation |
| Description       | ntbios driver |
| Product           |  Microsoft(R) Windows (R) NT Operating System |
| OriginalFilename  | ntbios.sys |


#### Imports
{{< details "Expand" >}}
* NTOSKRNL.EXE
* HAL.DLL
* ntoskrnl.exe
* NDIS.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* MmUnlockPages
* MmProbeAndLockPages
* IoAllocateMdl
* IoQueueWorkItem
* IoAllocateWorkItem
* IoGetCurrentProcess
* _stricmp
* IoFreeWorkItem
* RtlFreeUnicodeString
* ZwClose
* ZwWriteFile
* ZwCreateFile
* RtlAnsiStringToUnicodeString
* _strnicmp
* RtlUnwind
* RtlCopyUnicodeString
* wcsncmp
* swprintf
* IoCreateDevice
* IoCreateSymbolicLink
* KeInitializeSpinLock
* ExfInterlockedInsertTailList
* RtlInitUnicodeString
* MmMapLockedPagesSpecifyCache
* IoFreeMdl
* InterlockedDecrement
* InterlockedIncrement
* InterlockedExchange
* IoDeleteSymbolicLink
* IoDeleteDevice
* ExfInterlockedRemoveHeadList
* IofCompleteRequest
* ExAllocatePoolWithTag
* strncmp
* ExFreePool
* KfAcquireSpinLock
* KfReleaseSpinLock
* KeInitializeApc
* KeInsertQueueApc
* KeAttachProcess
* KeDetachProcess
* NtQuerySystemInformation
* NdisAllocatePacket
* NdisCopyFromPacketToPacket
* NdisAllocateMemory
* NdisFreePacket
* NdisAllocateBuffer
* NdisSetEvent
* NdisResetEvent
* NdisFreeBufferPool
* NdisFreePacketPool
* NdisFreeMemory
* NdisWaitEvent
* NdisQueryAdapterInstanceName
* NdisOpenAdapter
* NdisInitializeEvent
* NdisAllocatePacketPool
* NdisRegisterProtocol
* NdisAllocateBufferPool
* NdisCloseAdapter
* NdisDeregisterProtocol

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/ntbios_2.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
