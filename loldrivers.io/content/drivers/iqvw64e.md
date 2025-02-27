+++

description = ""
title = "iqvw64e.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# iqvw64e.sys ![:inline](/images/twitter_verified.png) 


### Description

(1) IQVW32.sys before 1.3.1.0 and (2) IQVW64.sys before 1.3.1.0 in the Intel Ethernet diagnostics driver for Windows allows local users to cause a denial of service or possibly execute arbitrary code with kernel privileges via a crafted (a) 0x80862013, (b) 0x8086200B, (c) 0x8086200F, or (d) 0x80862007 IOCTL call.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/1898ceda3247213c084f43637ef163b3.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create iqvw64e.sys binPath=C:\windows\temp\iqvw64e.sys type=kernel &amp;&amp; sc.exe start iqvw64e.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://www.crowdstrike.com/blog/scattered-spider-attempts-to-avoid-detection-with-bring-your-own-vulnerable-driver-tactic/">https://www.crowdstrike.com/blog/scattered-spider-attempts-to-avoid-detection-with-bring-your-own-vulnerable-driver-tactic/</a></li>
<li><a href="https://expel.com/blog/well-that-escalated-quickly-how-a-red-team-went-from-domain-user-to-kernel-memory/">https://expel.com/blog/well-that-escalated-quickly-how-a-red-team-went-from-domain-user-to-kernel-memory/</a></li>
<li><a href="https://github.com/Exploitables/CVE-2015-2291">https://github.com/Exploitables/CVE-2015-2291</a></li>
<li><a href="https://github.com/Tare05/Intel-CVE-2015-2291">https://github.com/Tare05/Intel-CVE-2015-2291</a></li>
<li><a href="https://github.com/TheCruZ/kdmapper">https://github.com/TheCruZ/kdmapper</a></li>
<li><a href=""></a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | iqvw64e.sys |
| MD5                | [1898ceda3247213c084f43637ef163b3](https://www.virustotal.com/gui/file/1898ceda3247213c084f43637ef163b3) |
| SHA1               | [d04e5db5b6c848a29732bfd52029001f23c3da75](https://www.virustotal.com/gui/file/d04e5db5b6c848a29732bfd52029001f23c3da75) |
| SHA256             | [4429f32db1cc70567919d7d47b844a91cf1329a6cd116f582305f3b7b60cd60b](https://www.virustotal.com/gui/file/4429f32db1cc70567919d7d47b844a91cf1329a6cd116f582305f3b7b60cd60b) |
| Authentihash MD5   | [1789a16d20ca2b55f491ad71848166a2](https://www.virustotal.com/gui/search/authentihash%253A1789a16d20ca2b55f491ad71848166a2) |
| Authentihash SHA1  | [2cbfe4ad0e1231ff3e19c19ca9311d952ce170b7](https://www.virustotal.com/gui/search/authentihash%253A2cbfe4ad0e1231ff3e19c19ca9311d952ce170b7) |
| Authentihash SHA256| [785e87bc23a1353fe0726554fd009aca69c320a98445a604a64e23ab45108087](https://www.virustotal.com/gui/search/authentihash%253A785e87bc23a1353fe0726554fd009aca69c320a98445a604a64e23ab45108087) |
| Signature         | Intel Corporation, VeriSign Class 3 Code Signing 2010 CA, VeriSign   |
| Company           | Intel Corporation  |
| Description       | Intel(R) Network Adapter Diagnostic Driver |
| Product           | Intel(R) iQVW64.SYS |
| OriginalFilename  | iQVW64.SYS |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IoCreateSymbolicLink
* IoCreateDevice
* IofCompleteRequest
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* MmGetPhysicalAddress
* DbgPrint
* strncpy
* vsprintf
* IoFreeMdl
* MmMapLockedPagesSpecifyCache
* MmBuildMdlForNonPagedPool
* IoAllocateMdl
* MmUnmapIoSpace
* MmUnmapLockedPages
* MmAllocateContiguousMemory
* MmFreeContiguousMemory
* RtlInitUnicodeString
* ObfDereferenceObject
* KeWaitForSingleObject
* IofCallDriver
* IoBuildSynchronousFsdRequest
* KeInitializeEvent
* ZwClose
* RtlFreeAnsiString
* strstr
* RtlUnicodeStringToAnsiString
* ZwEnumerateValueKey
* ZwOpenKey
* wcsncpy
* IoGetDeviceObjectPointer
* IoGetDeviceInterfaces
* ObReferenceObjectByPointer
* KeBugCheckEx
* IoDeleteSymbolicLink
* MmMapIoSpace
* IoDeleteDevice
* KeStallExecutionProcessor
* KeQueryPerformanceCounter

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/iqvw64e.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
