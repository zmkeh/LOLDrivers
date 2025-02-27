+++

description = ""
title = "krpocesshacker.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# krpocesshacker.sys ![:inline](/images/twitter_verified.png) 


### Description

krpocesshacker.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/bbbc9a6cc488cfb0f6c6934b193891eb.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create krpocesshacker.sys binPath=C:\windows\temp\krpocesshacker.sys     type=kernel &amp;&amp; sc.exe start krpocesshacker.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html">https://www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html</a></li>
<li><a href="https://www.unknowncheats.me/forum/anti-cheat-bypass/312791-bypaph-process-hackers-bypass-read-write-process-virtual-memory-kernel-mem.html#post2315763">https://www.unknowncheats.me/forum/anti-cheat-bypass/312791-bypaph-process-hackers-bypass-read-write-process-virtual-memory-kernel-mem.html#post2315763</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/search?q=VulnDriver">https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | krpocesshacker.sys |
| MD5                | [bbbc9a6cc488cfb0f6c6934b193891eb](https://www.virustotal.com/gui/file/bbbc9a6cc488cfb0f6c6934b193891eb) |
| SHA1               | [d8498707f295082f6a95fd9d32c9782951f5a082](https://www.virustotal.com/gui/file/d8498707f295082f6a95fd9d32c9782951f5a082) |
| SHA256             | [c725919e6357126d512c638f993cf572112f323da359645e4088f789eb4c7b8c](https://www.virustotal.com/gui/file/c725919e6357126d512c638f993cf572112f323da359645e4088f789eb4c7b8c) |
| Authentihash MD5   | [a9ccdbae433c4377abce8f514e4fe43e](https://www.virustotal.com/gui/search/authentihash%253Aa9ccdbae433c4377abce8f514e4fe43e) |
| Authentihash SHA1  | [61b55bb7c111f93bd3ea9ac71591e1a6b89feee1](https://www.virustotal.com/gui/search/authentihash%253A61b55bb7c111f93bd3ea9ac71591e1a6b89feee1) |
| Authentihash SHA256| [c7b1bb39dcd7f0331989f16fcc7cd29a9ae126bee47746a4be385160da3c5a29](https://www.virustotal.com/gui/search/authentihash%253Ac7b1bb39dcd7f0331989f16fcc7cd29a9ae126bee47746a4be385160da3c5a29) |
| Signature         | Wen Jia Liu, DigiCert High Assurance Code Signing CA-1, DigiCert   |
| Company           | wj32 |
| Description       | KProcessHacker |
| Product           | KProcessHacker |
| OriginalFilename  | kprocesshacker.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* RtlInitUnicodeString
* IoDeleteDevice
* ProbeForWrite
* ZwQuerySystemInformation
* ZwQueryValueKey
* ZwClose
* IofCompleteRequest
* PsGetCurrentProcessId
* IoCreateDevice
* SePrivilegeCheck
* ZwOpenKey
* ProbeForRead
* RtlGetVersion
* RtlCompareMemory
* MmGetSystemRoutineAddress
* PsProcessType
* ObOpenObjectByName
* ZwQueryObject
* RtlEqualUnicodeString
* KeUnstackDetachProcess
* ExEnumHandleTable
* ObQueryNameString
* IoFileObjectType
* IoDriverObjectType
* IoGetCurrentProcess
* ObReferenceObjectByHandle
* ObCloseHandle
* PsInitialSystemProcess
* ObSetHandleAttributes
* ZwQueryInformationProcess
* ObfDereferenceObject
* ExAllocatePoolWithQuotaTag
* ZwQueryInformationThread
* ObOpenObjectByPointer
* KeStackAttachProcess
* ExAcquireRundownProtection
* PsLookupProcessByProcessId
* PsJobType
* PsReferencePrimaryToken
* SeTokenObjectType
* ExReleaseRundownProtection
* ZwSetInformationProcess
* PsGetProcessJob
* PsLookupProcessThreadByCid
* ZwTerminateProcess
* PsDereferencePrimaryToken
* IoThreadToProcess
* RtlWalkFrameChain
* KeInitializeApc
* KeSetEvent
* KeInsertQueueApc
* KeInitializeEvent
* PsSetContextThread
* PsGetThreadWin32Thread
* ZwSetInformationThread
* KeWaitForSingleObject
* PsThreadType
* PsAssignImpersonationToken
* PsGetContextThread
* PsLookupThreadByThreadId
* MmUnmapLockedPages
* ExRaiseStatus
* MmHighestUserAddress
* MmMapLockedPagesSpecifyCache
* MmProbeAndLockPages
* MmUnlockPages
* MmIsAddressValid
* KeBugCheckEx
* __C_specific_handler

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/krpocesshacker.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
