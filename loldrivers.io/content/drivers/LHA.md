+++

description = ""
title = "LHA.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# LHA.sys ![:inline](/images/twitter_verified.png) 


### Description

LHA.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/748cf64b95ca83abc35762ad2c25458f.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create LHA.sys binPath=C:\windows\temp\LHA.sys type=kernel &amp;&amp; sc.exe start LHA.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/elastic/protections-artifacts/search?q=VulnDriver"> https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/search?q=VulnDriver">https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | LHA.sys |
| MD5                | [748cf64b95ca83abc35762ad2c25458f](https://www.virustotal.com/gui/file/748cf64b95ca83abc35762ad2c25458f) |
| SHA1               | [fcd615df88645d1f57ff5702bd6758b77efea6d0](https://www.virustotal.com/gui/file/fcd615df88645d1f57ff5702bd6758b77efea6d0) |
| SHA256             | [e75714f8e0ff45605f6fc7689a1a89c7dcd34aab66c6131c63fefaca584539cf](https://www.virustotal.com/gui/file/e75714f8e0ff45605f6fc7689a1a89c7dcd34aab66c6131c63fefaca584539cf) |
| Authentihash MD5   | [8a3fb969d6edfb9a860e13a556a9d64f](https://www.virustotal.com/gui/search/authentihash%253A8a3fb969d6edfb9a860e13a556a9d64f) |
| Authentihash SHA1  | [d9cf173dd75bf410c2f7f35247cd4db186af9a41](https://www.virustotal.com/gui/search/authentihash%253Ad9cf173dd75bf410c2f7f35247cd4db186af9a41) |
| Authentihash SHA256| [fe14940b5d3068b7ceffd28a529196811f1d0e175522f4dfab26573e7aca0bb4](https://www.virustotal.com/gui/search/authentihash%253Afe14940b5d3068b7ceffd28a529196811f1d0e175522f4dfab26573e7aca0bb4) |
| Signature         | Microsoft Windows Hardware Compatibility Publisher, Microsoft Windows Third Party Component CA 2014, Microsoft Root Certificate Authority 2010   |
| Company           | LG Electronics Inc. |
| Description       | LHA |
| Product           | Microsoft® Windows® Operating System |
| OriginalFilename  | LHA.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExFreePoolWithTag
* RtlInitUnicodeString
* IoDeleteDevice
* IoFreeWorkItem
* KeReleaseSpinLock
* MmUnmapIoSpace
* MmFreeNonCachedMemory
* MmGetPhysicalAddress
* IoAllocateWorkItem
* MmMapIoSpace
* IofCompleteRequest
* IoCreateSymbolicLink
* IoDeleteSymbolicLink
* KeAcquireSpinLockRaiseToDpc
* ExUnregisterCallback
* PoRegisterPowerSettingCallback
* ExRegisterCallback
* ObfDereferenceObject
* IoQueueWorkItem
* ExCreateCallback
* DbgPrint
* IoWMIQueryAllData
* MmGetSystemRoutineAddress
* KeBugCheckEx
* ExAllocatePoolWithTag
* MmAllocateNonCachedMemory
* IoCreateDevice
* ZwClose
* ObOpenObjectByPointer
* ZwSetSecurityObject
* IoDeviceObjectType
* _snwprintf
* RtlLengthSecurityDescriptor
* SeCaptureSecurityDescriptor
* RtlCreateSecurityDescriptor
* RtlSetDaclSecurityDescriptor
* RtlAbsoluteToSelfRelativeSD
* IoIsWdmVersionAvailable
* SeExports
* wcschr
* _wcsnicmp
* RtlLengthSid
* RtlAddAccessAllowedAce
* RtlGetSaclSecurityDescriptor
* RtlGetDaclSecurityDescriptor
* RtlGetGroupSecurityDescriptor
* RtlGetOwnerSecurityDescriptor
* ZwOpenKey
* ZwCreateKey
* ZwQueryValueKey
* ZwSetValueKey
* RtlFreeUnicodeString
* KeStallExecutionProcessor

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/lha.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
