+++

description = ""
title = "PcieCubed.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# PcieCubed.sys ![:inline](/images/twitter_verified.png) 


### Description

Driver categorized as POORTRY by Mandiant.

- **Created**: 2023-03-04
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/22949977ce5cd96ba674b403a9c81285.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the malicious driver!

{{< /tip >}}

### Commands

```
sc.exe create PcieCubed.sys binPath=C:\windows\temp\PcieCubed.sys type=kernel &amp;&amp; sc.exe start PcieCubed.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware">https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware</a></li>
<li><a href=""></a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | PcieCubed.sys |
| MD5                | [22949977ce5cd96ba674b403a9c81285](https://www.virustotal.com/gui/file/22949977ce5cd96ba674b403a9c81285) |
| SHA1               | [745335bcdf02fb42df7d890a24858e16094f48fd](https://www.virustotal.com/gui/file/745335bcdf02fb42df7d890a24858e16094f48fd) |
| SHA256             | [fd223833abffa9cd6cc1848d77599673643585925a7ee51259d67c44d361cce8](https://www.virustotal.com/gui/file/fd223833abffa9cd6cc1848d77599673643585925a7ee51259d67c44d361cce8) |
| Authentihash MD5   | [489c034fa8dcfc9d211fc7e8e80c24e6](https://www.virustotal.com/gui/search/authentihash%253A489c034fa8dcfc9d211fc7e8e80c24e6) |
| Authentihash SHA1  | [0a2da48019251954888ff3963ef21ccb624c1aba](https://www.virustotal.com/gui/search/authentihash%253A0a2da48019251954888ff3963ef21ccb624c1aba) |
| Authentihash SHA256| [2bbbe2ae5aa51868e7afc2c16c3a0a79fa3302e6830feeccca7f0363a62dddb4](https://www.virustotal.com/gui/search/authentihash%253A2bbbe2ae5aa51868e7afc2c16c3a0a79fa3302e6830feeccca7f0363a62dddb4) |
| Signature         | Microsoft Windows Hardware Compatibility Publisher, Microsoft Windows Third Party Component CA 2014, Microsoft Root Certificate Authority 2010   |
| Company           | Legal Corp. |
| Description       | PCIe Video Capture |
| Product           | PCI Express Video Capture |
| OriginalFilename  | PcieCubed.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.DLL
* ks.sys

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* KeDelayExecutionThread
* KeWaitForMultipleObjects
* ZwReadFile
* RtlInitUnicodeString
* MmMapLockedPagesSpecifyCache
* ZwQueryInformationFile
* IoAllocateMdl
* RtlAnsiStringToUnicodeString
* IoBuildSynchronousFsdRequest
* RtlAppendUnicodeToString
* RtlQueryRegistryValues
* RtlInitAnsiString
* ZwSetValueKey
* ObfDereferenceObject
* ZwQueryValueKey
* ExAllocatePool
* RtlAppendUnicodeStringToString
* IoFreeIrp
* IoGetAttachedDeviceReference
* IoAllocateIrp
* RtlCopyUnicodeString
* IoOpenDeviceRegistryKey
* IoGetDeviceProperty
* ZwEnumerateKey
* IofCallDriver
* ZwQueryKey
* ZwOpenKey
* PoUnregisterSystemState
* PoRegisterSystemState
* RtlCompareMemory
* KeBugCheckEx
* KeReleaseSemaphore
* KeWaitForSingleObject
* ObReferenceObjectByHandle
* KeInitializeSemaphore
* ZwClose
* PsTerminateSystemThread
* PsCreateSystemThread
* KeInitializeEvent
* KeSetEvent
* KeSetPriorityThread
* KeClearEvent
* ExFreePool
* KeAcquireSpinLockRaiseToDpc
* KeReleaseSpinLock
* DbgPrint
* ExFreePoolWithTag
* RtlFreeUnicodeString
* ExAllocatePoolWithTag
* ZwOpenFile
* IoConnectInterrupt
* IoDisconnectInterrupt
* IoGetDmaAdapter
* IoFreeMdl
* KeInsertQueueDpc
* MmProbeAndLockPages
* MmUnlockPages
* MmUnmapIoSpace
* KeInitializeDpc
* MmMapIoSpace
* KeSetTimerEx
* KeInitializeTimerEx
* KeCancelTimer
* MmGetSystemRoutineAddress
* PsGetVersion
* __C_specific_handler
* memcmp
* KeQueryPerformanceCounter
* KsPinGetLeadingEdgeStreamPointer
* KsPinGetParentFilter
* KsStreamPointerUnlock
* KsGetPinFromIrp
* KsGetFilterFromIrp
* KsGetDevice
* _KsEdit
* KsReleaseDevice
* KsCreateFilterFactory
* KsAddItemToObjectBag
* KsInitializeDriver
* KsFilterFactoryUpdateCacheData
* KsPinReleaseProcessingMutex
* KsPinAcquireProcessingMutex
* KsAcquireDevice
* KsPinGetReferenceClockInterface

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/pciecubed.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
