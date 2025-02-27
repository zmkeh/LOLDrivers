+++

description = ""
title = "NTIOLib_X64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# NTIOLib_X64.sys ![:inline](/images/twitter_verified.png) 


### Description

NTIOLib_X64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/c02f70960fa934b8defa16a03d7f6556.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create NTIOLib_X64.sys binPath=C:\windows\temp\NTIOLib_X64.sys     type=kernel &amp;&amp; sc.exe start NTIOLib_X64.sys
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
| Filename           | NTIOLib_X64.sys |
| MD5                | [c02f70960fa934b8defa16a03d7f6556](https://www.virustotal.com/gui/file/c02f70960fa934b8defa16a03d7f6556) |
| SHA1               | [3805e4e08ad342d224973ecdade8b00c40ed31be](https://www.virustotal.com/gui/file/3805e4e08ad342d224973ecdade8b00c40ed31be) |
| SHA256             | [d8b58f6a89a7618558e37afc360cd772b6731e3ba367f8d58734ecee2244a530](https://www.virustotal.com/gui/file/d8b58f6a89a7618558e37afc360cd772b6731e3ba367f8d58734ecee2244a530) |
| Authentihash MD5   | [c6830e904e56ea951005ea7639eedd35](https://www.virustotal.com/gui/search/authentihash%253Ac6830e904e56ea951005ea7639eedd35) |
| Authentihash SHA1  | [c57c0dd18135bca5fdb094858a70033c006cd281](https://www.virustotal.com/gui/search/authentihash%253Ac57c0dd18135bca5fdb094858a70033c006cd281) |
| Authentihash SHA256| [4a05ad47cd63932b3df2d0f1f42617321729772211bec651fe061140d3e75957](https://www.virustotal.com/gui/search/authentihash%253A4a05ad47cd63932b3df2d0f1f42617321729772211bec651fe061140d3e75957) |
| Signature         | Micro-Star Int&#39;l Co. Ltd., GlobalSign ObjectSign CA, GlobalSign Primary Object Publishing CA, GlobalSign Root CA - R1   |
| Company           | MSI |
| Description       | NTIOLib |
| Product           | NTIOLib |
| OriginalFilename  | NTIOLib.sys |


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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/ntiolib_x64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
