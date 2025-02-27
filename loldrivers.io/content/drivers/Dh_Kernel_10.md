+++

description = ""
title = "Dh_Kernel_10.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# Dh_Kernel_10.sys ![:inline](/images/twitter_verified.png) 


### Description

Dh_Kernel_10.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/51207adb8dab983332d6b22c29fe8129.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create Dh_Kernel_10.sys binPath=C:\windows\temp\Dh_Kernel_10.sys     type=kernel &amp;&amp; sc.exe start Dh_Kernel_10.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/namazso/physmem_drivers"> https://github.com/namazso/physmem_drivers</a></li>
<li><a href="https://github.com/namazso/physmem_drivers">https://github.com/namazso/physmem_drivers</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | Dh_Kernel_10.sys |
| MD5                | [51207adb8dab983332d6b22c29fe8129](https://www.virustotal.com/gui/file/51207adb8dab983332d6b22c29fe8129) |
| SHA1               | [ddbe809b731a0962e404a045ab9e65a0b64917ad](https://www.virustotal.com/gui/file/ddbe809b731a0962e404a045ab9e65a0b64917ad) |
| SHA256             | [80cbba9f404df3e642f22c476664d63d7c229d45d34f5cd0e19c65eb41becec3](https://www.virustotal.com/gui/file/80cbba9f404df3e642f22c476664d63d7c229d45d34f5cd0e19c65eb41becec3) |
| Authentihash MD5   | [df4f1e566667e15b3d81c5c3e50e97ca](https://www.virustotal.com/gui/search/authentihash%253Adf4f1e566667e15b3d81c5c3e50e97ca) |
| Authentihash SHA1  | [b92959042d232605abba254bc0368b87ec047079](https://www.virustotal.com/gui/search/authentihash%253Ab92959042d232605abba254bc0368b87ec047079) |
| Authentihash SHA256| [c786f3ca229da18b2806af4d57ecad603859ee548549b19f71a623f477fc740e](https://www.virustotal.com/gui/search/authentihash%253Ac786f3ca229da18b2806af4d57ecad603859ee548549b19f71a623f477fc740e) |
| Publisher         | YY Inc. |
| Signature         | YY Inc., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |
| Company           | YY Inc. |
| Description       | dianhu |
| Product           | dianhu |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* WDFLDR.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExAllocatePool
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* ProbeForRead
* MmProbeAndLockPages
* MmBuildMdlForNonPagedPool
* MmMapLockedPages
* MmUnmapLockedPages
* MmCreateMdl
* IofCompleteRequest
* IoCreateDevice
* IoCreateSymbolicLink
* IoDeleteDevice
* IoDeleteSymbolicLink
* KeInitializeSpinLock
* ObfDereferenceObject
* MmIsAddressValid
* KeAttachProcess
* KeDetachProcess
* KeStackAttachProcess
* KeUnstackDetachProcess
* PsLookupProcessByProcessId
* PsGetProcessSectionBaseAddress
* __C_specific_handler
* RtlCopyUnicodeString
* DbgPrintEx
* MmGetSystemRoutineAddress
* RtlInitUnicodeString
* IoFreeMdl
* _stricmp
* WdfVersionBindClass
* WdfVersionUnbind
* WdfVersionBind
* WdfVersionUnbindClass

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/dh_kernel_10.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
