+++

description = ""
title = "daxin_blank6.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# daxin_blank6.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver used in the Daxin malware campaign.

- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/0ae30291c6cbfa7be39320badd6e8de0.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create daxin_blank6.sys binPath=C:\windows\temp\daxin_blank6.sys     type=kernel &amp;&amp; sc.exe start daxin_blank6.sys
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
| Filename           | daxin_blank6.sys |
| MD5                | [0ae30291c6cbfa7be39320badd6e8de0](https://www.virustotal.com/gui/file/0ae30291c6cbfa7be39320badd6e8de0) |
| SHA1               | [c257aa4094539719a3c7b7950598ef872dbf9518](https://www.virustotal.com/gui/file/c257aa4094539719a3c7b7950598ef872dbf9518) |
| SHA256             | [e6a7b0bc01a627a7d0ffb07faddb3a4dd96b6f5208ac26107bdaeb3ab1ec8217](https://www.virustotal.com/gui/file/e6a7b0bc01a627a7d0ffb07faddb3a4dd96b6f5208ac26107bdaeb3ab1ec8217) |
| Authentihash MD5   | [d59fbf4aa759286d1dd9abb40733f7b2](https://www.virustotal.com/gui/search/authentihash%253Ad59fbf4aa759286d1dd9abb40733f7b2) |
| Authentihash SHA1  | [3c34c7c5916b987420fbfb4f3e3fef7400471831](https://www.virustotal.com/gui/search/authentihash%253A3c34c7c5916b987420fbfb4f3e3fef7400471831) |
| Authentihash SHA256| [a8c558e74ebe35a095a5b79d4bb26c10b18f8ebb449365e742f856d4e032555c](https://www.virustotal.com/gui/search/authentihash%253Aa8c558e74ebe35a095a5b79d4bb26c10b18f8ebb449365e742f856d4e032555c) |
| Publisher         | n/a |
| Signature         | U, n, s, i, g, n, e, d   |
| Date                | 2:44 AM 3/26/2009 |


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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/daxin_blank6.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
