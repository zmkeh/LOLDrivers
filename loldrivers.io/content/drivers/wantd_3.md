+++

description = ""
title = "wantd_3.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# wantd_3.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver used in the Daxin malware campaign.

- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/fb7c61ef427f9b2fdff3574ee6b1819b.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create wantd_3.sys binPath=C:\windows\temp\wantd_3.sys type=kernel &amp;&amp; sc.exe start wantd_3.sys
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
| Filename           | wantd_3.sys |
| MD5                | [fb7c61ef427f9b2fdff3574ee6b1819b](https://www.virustotal.com/gui/file/fb7c61ef427f9b2fdff3574ee6b1819b) |
| SHA1               | [1f25f54e9b289f76604e81e98483309612c5a471](https://www.virustotal.com/gui/file/1f25f54e9b289f76604e81e98483309612c5a471) |
| SHA256             | [81c7bb39100d358f8286da5e9aa838606c98dfcc263e9a82ed91cd438cb130d1](https://www.virustotal.com/gui/file/81c7bb39100d358f8286da5e9aa838606c98dfcc263e9a82ed91cd438cb130d1) |
| Authentihash MD5   | [cbb18883d7893156620f084ff40b2fbf](https://www.virustotal.com/gui/search/authentihash%253Acbb18883d7893156620f084ff40b2fbf) |
| Authentihash SHA1  | [df59532dbae676b3fb2653a1bbd9cd5f1cd3ba78](https://www.virustotal.com/gui/search/authentihash%253Adf59532dbae676b3fb2653a1bbd9cd5f1cd3ba78) |
| Authentihash SHA256| [a1ee0b8a7974f3d11c10241027c0e7171c798a28589aae9ff8c5a86228642af7](https://www.virustotal.com/gui/search/authentihash%253Aa1ee0b8a7974f3d11c10241027c0e7171c798a28589aae9ff8c5a86228642af7) |
| Publisher         | n/a |
| Signature         | U, n, s, i, g, n, e, d   |
| Date                | 7:52 AM 4/30/2014 |
| Company           | Microsoft Corporation |
| Description       | WAN Transport Driver |
| Product           | Microsoft Windows Operating System |
| OriginalFilename  | wantd.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll
* NDIS.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
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
* KeInsertQueueApc
* KeInitializeApc
* KeDetachProcess
* KeAttachProcess
* PsLookupThreadByThreadId
* ZwAllocateVirtualMemory
* RtlCompareUnicodeString
* PsLookupProcessByProcessId
* ZwFreeVirtualMemory
* _wcsnicmp
* ZwQuerySystemInformation
* ZwQueryInformationProcess
* RtlImageDirectoryEntryToData
* _stricmp
* NtQuerySystemInformation
* ZwOpenFile
* MmGetSystemRoutineAddress
* ZwQueryValueKey
* ZwOpenKey
* ZwTerminateProcess
* ZwOpenProcess
* IoCreateFile
* RtlSetDaclSecurityDescriptor
* RtlAddAccessAllowedAce
* RtlCreateAcl
* RtlLengthSid
* RtlCreateSecurityDescriptor
* NtWriteFile
* NtReadFile
* KeWaitForMultipleObjects
* NtFsControlFile
* ZwWaitForSingleObject
* RtlLengthRequiredSid
* IoCreateSymbolicLink
* DbgPrint
* IoCreateDevice
* IoDeleteDevice
* IoDeleteSymbolicLink
* sprintf
* ZwCreateFile
* RtlAnsiStringToUnicodeString
* ZwWriteFile
* ZwReadFile
* ZwQueryInformationFile
* vsprintf
* ZwDeviceIoControlFile
* MmMapLockedPagesSpecifyCache
* IoFreeMdl
* KeWaitForSingleObject
* ObfDereferenceObject
* KeDelayExecutionThread
* PsTerminateSystemThread
* PsCreateSystemThread
* PsThreadType
* ObReferenceObjectByHandle
* ZwClose
* KeQueryTimeIncrement
* KeTickCount
* KeInitializeSpinLock
* ExAllocatePoolWithTag
* PsGetVersion
* ExFreePool
* KfReleaseSpinLock
* KfAcquireSpinLock
* NdisAllocatePacketPool
* NdisAllocateBufferPool
* NdisRegisterProtocol
* NdisDeregisterProtocol
* NdisUnchainBufferAtFront
* NdisAllocatePacket
* NdisAllocateMemory
* NdisFreePacket
* NdisAllocateBuffer
* NdisFreeMemory
* NdisFreeBufferPool
* NdisCopyFromPacketToPacket
* NdisFreePacketPool

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/wantd_3.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
