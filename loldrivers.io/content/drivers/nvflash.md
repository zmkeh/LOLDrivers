+++

description = ""
title = "nvflash.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# nvflash.sys ![:inline](/images/twitter_verified.png) 


### Description

nvflash.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/84fb76ee319073e77fb364bbbbff5461.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create nvflash.sys binPath=C:\windows\temp \n \n \n  vflash.sys type=kernel &amp;&amp; sc.exe start nvflash.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md"> https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<li><a href="https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md">https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | nvflash.sys |
| MD5                | [84fb76ee319073e77fb364bbbbff5461](https://www.virustotal.com/gui/file/84fb76ee319073e77fb364bbbbff5461) |
| SHA1               | [a4b2c56c12799855162ca3b004b4b2078c6ecf77](https://www.virustotal.com/gui/file/a4b2c56c12799855162ca3b004b4b2078c6ecf77) |
| SHA256             | [afdd66562dea51001c3a9de300f91fc3eb965d6848dfce92ccb9b75853e02508](https://www.virustotal.com/gui/file/afdd66562dea51001c3a9de300f91fc3eb965d6848dfce92ccb9b75853e02508) |
| Authentihash MD5   | [aa2051841a882c7080ddf6b224f838da](https://www.virustotal.com/gui/search/authentihash%253Aaa2051841a882c7080ddf6b224f838da) |
| Authentihash SHA1  | [ee9073dedb3f05797de41f79be5cc2e5e5028b61](https://www.virustotal.com/gui/search/authentihash%253Aee9073dedb3f05797de41f79be5cc2e5e5028b61) |
| Authentihash SHA256| [1c8cb72b9a011b60b1b9caea508b26fbbd95a1e3634af66082417381fe6544fb](https://www.virustotal.com/gui/search/authentihash%253A1c8cb72b9a011b60b1b9caea508b26fbbd95a1e3634af66082417381fe6544fb) |
| Signature         | NVIDIA Corporation, VeriSign Class 3 Code Signing 2010 CA, VeriSign   |
| Company           | NVIDIA Corporation |
| Description       | NVIDIA Flash Driver, Version 1.8.0 |
| Product           | NVIDIA Flash Driver |
| OriginalFilename  | nvflash.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExFreePoolWithTag
* IofCompleteRequest
* IoCreateSymbolicLink
* IoDeleteDevice
* IoDeleteSymbolicLink
* ObReferenceObjectByHandle
* ExAllocatePool
* ZwClose
* ZwOpenSection
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* KeBugCheckEx
* ObfDereferenceObject
* RtlInitUnicodeString
* MmGetSystemRoutineAddress
* ObOpenObjectByPointer
* IoDeviceObjectType
* IoCreateDevice
* ZwSetSecurityObject
* RtlGetOwnerSecurityDescriptor
* RtlGetDaclSecurityDescriptor
* RtlGetGroupSecurityDescriptor
* RtlGetSaclSecurityDescriptor
* SeCaptureSecurityDescriptor
* RtlLengthSecurityDescriptor
* _snwprintf
* RtlCreateSecurityDescriptor
* RtlLengthSid
* SeExports
* IoIsWdmVersionAvailable
* RtlAbsoluteToSelfRelativeSD
* RtlAddAccessAllowedAce
* RtlSetDaclSecurityDescriptor
* _wcsnicmp
* ExAllocatePoolWithTag
* wcschr
* ZwOpenKey
* ZwQueryValueKey
* RtlFreeUnicodeString
* ZwSetValueKey
* ZwCreateKey
* ExAllocatePoolWithQuotaTag
* ZwQuerySystemInformation
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nvflash.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
