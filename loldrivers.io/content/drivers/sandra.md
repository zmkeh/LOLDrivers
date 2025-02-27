+++

description = ""
title = "sandra.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# sandra.sys ![:inline](/images/twitter_verified.png) 


### Description

sandra.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/9a237fa07ce3ed06ea924a9bed4a6b99.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create sandra.sys binPath=C:\windows\temp\sandra.sys type=kernel &amp;&amp; sc.exe start sandra.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/jbaines-r7/dellicious"> https://github.com/jbaines-r7/dellicious</a></li>
<li><a href=" https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/"> https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<li><a href="https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/">https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | sandra.sys |
| MD5                | [9a237fa07ce3ed06ea924a9bed4a6b99](https://www.virustotal.com/gui/file/9a237fa07ce3ed06ea924a9bed4a6b99) |
| SHA1               | [82ba5513c33e056c3f54152c8555abf555f3e745](https://www.virustotal.com/gui/file/82ba5513c33e056c3f54152c8555abf555f3e745) |
| SHA256             | [1aaf4c1e3cb6774857e2eef27c17e68dc1ae577112e4769665f516c2e8c4e27b](https://www.virustotal.com/gui/file/1aaf4c1e3cb6774857e2eef27c17e68dc1ae577112e4769665f516c2e8c4e27b) |
| Authentihash MD5   | [6f72f204305c65af27c9f97fe4296b54](https://www.virustotal.com/gui/search/authentihash%253A6f72f204305c65af27c9f97fe4296b54) |
| Authentihash SHA1  | [b785192962dd159acd960c8f8f9f211747c83610](https://www.virustotal.com/gui/search/authentihash%253Ab785192962dd159acd960c8f8f9f211747c83610) |
| Authentihash SHA256| [b9661dd0dcf81d2ee8e5eb3b728c907b4eb861806971051ad772f7fe4d09eb6a](https://www.virustotal.com/gui/search/authentihash%253Ab9661dd0dcf81d2ee8e5eb3b728c907b4eb861806971051ad772f7fe4d09eb6a) |
| Signature         | SiSoftware Ltd, GeoTrust TrustCenter CodeSigning CA I, GeoTrust   |
| Company           | SiSoftware |
| Description       | Sandra Device Driver (Win64 x64)(Unicode) |
| Product           | SiSoftware Sandra |
| OriginalFilename  | SANDRA |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwSetValueKey
* NtQueryInformationProcess
* ZwClose
* MmMapIoSpace
* MmUnmapIoSpace
* IoQueryDeviceDescription
* ZwSetInformationThread
* RtlUnicodeStringToAnsiString
* IoAllocateMdl
* MmBuildMdlForNonPagedPool
* MmMapLockedPagesSpecifyCache
* MmUnmapLockedPages
* IoFreeMdl
* ZwCreateKey
* MmResetDriverPaging
* KeAcquireSpinLockRaiseToDpc
* KeReleaseSpinLock
* IofCompleteRequest
* MmPageEntireDriver
* IoUnregisterShutdownNotification
* IoDeleteSymbolicLink
* IoDeleteDevice
* RtlQueryRegistryValues
* IoCreateDevice
* IoCreateSymbolicLink
* IoRegisterShutdownNotification
* KeBugCheckEx
* RtlAppendUnicodeToString
* IoReportResourceUsage
* RtlInitUnicodeString
* __C_specific_handler
* HalSetBusDataByOffset
* HalGetBusDataByOffset
* HalTranslateBusAddress
* KeStallExecutionProcessor

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/sandra.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
