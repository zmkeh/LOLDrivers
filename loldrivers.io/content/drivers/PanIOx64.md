+++

description = ""
title = "PanIOx64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# PanIOx64.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

PanIOx64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/0d6fef14f8e1ce5753424bd22c46b1ce.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create PanIOx64.sys binPath=C:\windows\temp\PanIOx64.sys type=kernel &amp;&amp; sc.exe start PanIOx64.sys
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
| Filename           | PanIOx64.sys |
| MD5                | [0d6fef14f8e1ce5753424bd22c46b1ce](https://www.virustotal.com/gui/file/0d6fef14f8e1ce5753424bd22c46b1ce) |
| SHA1               | [814200191551faec65b21f5f6819b46c8fc227a3](https://www.virustotal.com/gui/file/814200191551faec65b21f5f6819b46c8fc227a3) |
| SHA256             | [6b830ea0db6546a044c9900d3f335e7820c2a80e147b0751641899d1a5aa8f74](https://www.virustotal.com/gui/file/6b830ea0db6546a044c9900d3f335e7820c2a80e147b0751641899d1a5aa8f74) |
| Authentihash MD5   | [7bd56fcd55d1fd188e5200b7db5cd7be](https://www.virustotal.com/gui/search/authentihash%253A7bd56fcd55d1fd188e5200b7db5cd7be) |
| Authentihash SHA1  | [519926b0b385e27141d88c5576aa9f86d8d3bb0d](https://www.virustotal.com/gui/search/authentihash%253A519926b0b385e27141d88c5576aa9f86d8d3bb0d) |
| Authentihash SHA256| [13aa698c09a31d642d3e2a9dd03be2363b11b4024689fb6c97234719446dbbd7](https://www.virustotal.com/gui/search/authentihash%253A13aa698c09a31d642d3e2a9dd03be2363b11b4024689fb6c97234719446dbbd7) |
| Signature         | PAN YAZILIM BILISIM TEKNOLOJILERI TICARET LTD. STI., GlobalSign CodeSigning CA - G2, GlobalSign   |
| Company           | Pan Yazilim Bilisim Teknolojileri Tic. Ltd. Sti. |
| Description       | Temperature and system information driver |
| Product           | PanIO Library |
| OriginalFilename  | PanIOx64.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* MmUnmapIoSpace
* MmMapIoSpace
* IofCompleteRequest
* IoDeleteDevice
* IoCreateDevice
* KeBugCheckEx
* RtlInitUnicodeString
* IoCreateSymbolicLink
* IoDeleteSymbolicLink
* __C_specific_handler
* HalSetBusDataByOffset
* HalGetBusDataByOffset

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/paniox64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
