+++

description = ""
title = "hw.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# hw.sys ![:inline](/images/twitter_verified.png) 


### Description

hw.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Guus Verbeek
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/3247014ba35d406475311a2eab0c4657.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create hw_sys binPath=C:\windows\temp\hw.sys type=kernel &amp;&amp; sc.exe start hw.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules">https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<li><a href="https://decoded.avast.io/janvojtesek/the-return-of-candiru-zero-days-in-the-middle-east/">https://decoded.avast.io/janvojtesek/the-return-of-candiru-zero-days-in-the-middle-east/</a></li>
<li><a href="https://www.virustotal.com/gui/file/6a4875ae86131a594019dec4abd46ac6ba47e57a88287b814d07d929858fe3e5/detection">https://www.virustotal.com/gui/file/6a4875ae86131a594019dec4abd46ac6ba47e57a88287b814d07d929858fe3e5/detection</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | hw.sys |
| MD5                | [3247014ba35d406475311a2eab0c4657](https://www.virustotal.com/gui/file/3247014ba35d406475311a2eab0c4657) |
| SHA1               | [74e4e3006b644392f5fcea4a9bae1d9d84714b57](https://www.virustotal.com/gui/file/74e4e3006b644392f5fcea4a9bae1d9d84714b57) |
| SHA256             | [4880f40f2e557cff38100620b9aa1a3a753cb693af16cd3d95841583edcb57a8](https://www.virustotal.com/gui/file/4880f40f2e557cff38100620b9aa1a3a753cb693af16cd3d95841583edcb57a8) |
| Authentihash MD5   | [6eafc9b68f2047adf6879e955d3b69e8](https://www.virustotal.com/gui/search/authentihash%253A6eafc9b68f2047adf6879e955d3b69e8) |
| Authentihash SHA1  | [8a6d85617bc601b818ddf1b8e8d5db6cf7ae31c1](https://www.virustotal.com/gui/search/authentihash%253A8a6d85617bc601b818ddf1b8e8d5db6cf7ae31c1) |
| Authentihash SHA256| [615a7c647eba3f2dcea463d5705d5d59ca70b4250f895ad20ce6876076a8fa28](https://www.virustotal.com/gui/search/authentihash%253A615a7c647eba3f2dcea463d5705d5d59ca70b4250f895ad20ce6876076a8fa28) |
| Signature         | Marvin Test Solutions, Inc., GlobalSign Extended Validation CodeSigning CA - SHA256 - G3, GlobalSign, GlobalSign Root CA - R1   |
| Company           | Marvin Test Solutions, Inc. |
| Description       | HW - Windows NT-10 (32/64 bit) kernel mode driver for PC ports/memory/PCI access |
| Product           | HW |
| OriginalFilename  | HW.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* KeReleaseMutex
* KeWaitForSingleObject
* PsGetCurrentProcessId
* KeInitializeDpc
* MmGetSystemRoutineAddress
* IoDeleteDevice
* IoCreateSymbolicLink
* KeInitializeMutex
* IoCreateDevice
* IoDeleteSymbolicLink
* memcpy
* PsGetVersion
* ZwUnmapViewOfSection
* ZwMapViewOfSection
* ObReferenceObjectByHandle
* ZwOpenSection
* IoFreeMdl
* MmMapLockedPages
* MmBuildMdlForNonPagedPool
* IoAllocateMdl
* MmMapIoSpace
* MmUnmapLockedPages
* MmUnmapIoSpace
* IoGetDmaAdapter
* IofCallDriver
* IoBuildSynchronousFsdRequest
* ZwOpenProcess
* KeInitializeEvent
* ObfDereferenceObject
* ExAllocatePoolWithTag
* ObReferenceObjectByName
* IoDriverObjectType
* IofCompleteRequest
* WRITE_REGISTER_BUFFER_ULONG
* WRITE_REGISTER_BUFFER_USHORT
* WRITE_REGISTER_BUFFER_UCHAR
* WRITE_REGISTER_ULONG
* WRITE_REGISTER_USHORT
* WRITE_REGISTER_UCHAR
* READ_REGISTER_BUFFER_ULONG
* READ_REGISTER_BUFFER_USHORT
* READ_REGISTER_BUFFER_UCHAR
* READ_REGISTER_ULONG
* READ_REGISTER_USHORT
* READ_REGISTER_UCHAR
* IoConnectInterrupt
* IoDisconnectInterrupt
* KeReleaseInterruptSpinLock
* KeAcquireInterruptSpinLock
* ExEventObjectType
* KeDelayExecutionThread
* KeInsertQueueDpc
* ZwClose
* KeSetEvent
* IoCreateNotificationEvent
* KeClearEvent
* RtlQueryRegistryValues
* RtlAppendUnicodeStringToString
* RtlInitUnicodeString
* memset
* ExFreePoolWithTag
* IoGetDeviceProperty
* ExAllocatePool
* READ_PORT_UCHAR
* READ_PORT_USHORT
* READ_PORT_ULONG
* READ_PORT_BUFFER_UCHAR
* READ_PORT_BUFFER_USHORT
* READ_PORT_BUFFER_ULONG
* WRITE_PORT_UCHAR
* WRITE_PORT_USHORT
* WRITE_PORT_ULONG
* WRITE_PORT_BUFFER_UCHAR
* WRITE_PORT_BUFFER_USHORT
* WRITE_PORT_BUFFER_ULONG
* HalAssignSlotResources
* HalTranslateBusAddress
* HalGetBusDataByOffset
* HalGetInterruptVector

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | HW.sys |
| MD5                | [45c2d133d41d2732f3653ed615a745c8](https://www.virustotal.com/gui/file/45c2d133d41d2732f3653ed615a745c8) |
| SHA1               | [4e56e0b1d12664c05615c69697a2f5c5d893058a](https://www.virustotal.com/gui/file/4e56e0b1d12664c05615c69697a2f5c5d893058a) |
| SHA256             | [6a4875ae86131a594019dec4abd46ac6ba47e57a88287b814d07d929858fe3e5](https://www.virustotal.com/gui/file/6a4875ae86131a594019dec4abd46ac6ba47e57a88287b814d07d929858fe3e5) |
| Company           | Marvin Test Solutions, Inc. |
| Description       | HW - Windows NT-8 (32/64 bit) kernel mode driver for PC ports/memory/PCI access |
| Product           | HW |
| OriginalFilename  | HW.sys |


#### Imports
{{< details "Expand" >}}

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/hw.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
