+++

description = ""
title = "ADV64DRV.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# ADV64DRV.sys ![:inline](/images/twitter_verified.png) 


### Description

ADV64DRV.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/778b7feea3c750d44745d3bf294bd4ce.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create ADV64DRV.sys binPath=C:\windows\temp\ADV64DRV.sys type=kernel &amp;&amp; sc.exe start ADV64DRV.sys
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
| Filename           | ADV64DRV.sys |
| MD5                | [778b7feea3c750d44745d3bf294bd4ce](https://www.virustotal.com/gui/file/778b7feea3c750d44745d3bf294bd4ce) |
| SHA1               | [2261198385d62d2117f50f631652eded0ecc71db](https://www.virustotal.com/gui/file/2261198385d62d2117f50f631652eded0ecc71db) |
| SHA256             | [04a85e359525d662338cae86c1e59b1d7aa9bd12b920e8067503723dc1e03162](https://www.virustotal.com/gui/file/04a85e359525d662338cae86c1e59b1d7aa9bd12b920e8067503723dc1e03162) |
| Authentihash MD5   | [e1c188570d8720f9c35e194e17a7fd36](https://www.virustotal.com/gui/search/authentihash%253Ae1c188570d8720f9c35e194e17a7fd36) |
| Authentihash SHA1  | [ca6b0d932e5ac9dbe1242aca48ba93a14cf9d151](https://www.virustotal.com/gui/search/authentihash%253Aca6b0d932e5ac9dbe1242aca48ba93a14cf9d151) |
| Authentihash SHA256| [b2b37ef379ada79d2abe78375312bfcd4b518139bc525a522c2a6329ba097cc4](https://www.virustotal.com/gui/search/authentihash%253Ab2b37ef379ada79d2abe78375312bfcd4b518139bc525a522c2a6329ba097cc4) |
| Publisher         | FUJITSU LIMITED |
| Signature         | FUJITSU LIMITED , VeriSign Class 3 Code Signing 2004 CA, VeriSign Class 3 Public Primary CA   |
| Date                | 01:30 AM 08/29/2006 |
| Company           | FUJITSU LIMITED. |
| Product           | MicrosoftR WindowsR Operating System |
| OriginalFilename  | ADV64DRV.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* RtlAppendUnicodeToString
* RtlInitUnicodeString
* MmUnmapIoSpace
* MmMapIoSpace
* IoWriteErrorLogEntry
* IoDeleteSymbolicLink
* IoDeleteDevice
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx
* IoAllocateErrorLogEntry
* IofCompleteRequest
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/adv64drv.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
