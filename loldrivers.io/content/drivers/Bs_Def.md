+++

description = ""
title = "Bs_Def.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# Bs_Def.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

Bs_Def.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/a9f220b1507a3c9a327a99995ff99c82.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create Bs_Def.sys binPath=C:\windows\temp\Bs_Def.sys type=kernel &amp;&amp; sc.exe start Bs_Def.sys
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
| Filename           | Bs_Def.sys |
| MD5                | [a9f220b1507a3c9a327a99995ff99c82](https://www.virustotal.com/gui/file/a9f220b1507a3c9a327a99995ff99c82) |
| SHA1               | [2c5ff272bd345962ed41ab8869aef41da0dfe697](https://www.virustotal.com/gui/file/2c5ff272bd345962ed41ab8869aef41da0dfe697) |
| SHA256             | [5f5e5f1c93d961985624768b7c676d488c7c7c1d4c043f6fc1ea1904fefb75be](https://www.virustotal.com/gui/file/5f5e5f1c93d961985624768b7c676d488c7c7c1d4c043f6fc1ea1904fefb75be) |
| Authentihash MD5   | [f27b347b5124473a3a9a46986889e408](https://www.virustotal.com/gui/search/authentihash%253Af27b347b5124473a3a9a46986889e408) |
| Authentihash SHA1  | [69ca963ec00bdd2a92a9777e91d0174bbe97e29c](https://www.virustotal.com/gui/search/authentihash%253A69ca963ec00bdd2a92a9777e91d0174bbe97e29c) |
| Authentihash SHA256| [410f02303292798ab2a8b3e7d253938b466e83071b15e7d3aaa25f4995b27187](https://www.virustotal.com/gui/search/authentihash%253A410f02303292798ab2a8b3e7d253938b466e83071b15e7d3aaa25f4995b27187) |
| Signature         | ASUSTeK Computer Inc., VeriSign Class 3 Code Signing 2004 CA, VeriSign Class 3 Public Primary CA   |
| Company           | AsusTek Computer Inc. |
| Description       | Default BIOS Flash Driver |
| Product           | Support SST39SF020,SST29EE020,AT49F002T,AT29C020,AM29F002NT,AM29F002NB,V29C51002T,V29C51002B,M29F002T,W29C020. |
| OriginalFilename  | Bs_Def64.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* MmBuildMdlForNonPagedPool
* IoAllocateMdl
* MmGetPhysicalAddress
* MmAllocateContiguousMemory
* IoFreeMdl
* MmUnmapLockedPages
* KeDelayExecutionThread
* DbgPrint
* MmUnmapIoSpace
* MmMapIoSpace
* RtlZeroMemory
* IoDeleteDevice
* IoCreateSymbolicLink
* IoCreateDevice
* MmMapLockedPages
* IofCompleteRequest
* IoDeleteSymbolicLink
* ZwClose
* ZwMapViewOfSection
* ObReferenceObjectByHandle
* ZwOpenSection
* ZwUnmapViewOfSection
* strncpy
* KeLeaveCriticalRegion
* KeEnterCriticalRegion
* IoIs32bitProcess
* strstr
* strncmp
* RtlInitUnicodeString
* MmFreeContiguousMemory
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/bs_def.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
