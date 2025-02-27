+++

description = ""
title = "HOSTNT.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# HOSTNT.sys ![:inline](/images/twitter_verified.png) 


### Description

HOSTNT.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/e8ebba56ea799e1e62748c59e1a4c586.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create HOSTNT.sys binPath=C:\windows\temp\HOSTNT.sys type=kernel &amp;&amp; sc.exe start HOSTNT.sys
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
| Filename           | HOSTNT.sys |
| MD5                | [e8ebba56ea799e1e62748c59e1a4c586](https://www.virustotal.com/gui/file/e8ebba56ea799e1e62748c59e1a4c586) |
| SHA1               | [ac13941f436139b909d105ad55637e1308f49d9a](https://www.virustotal.com/gui/file/ac13941f436139b909d105ad55637e1308f49d9a) |
| SHA256             | [07b6d69bafcfd767f1b63a490a8843c3bb1f8e1bbea56176109b5743c8f7d357](https://www.virustotal.com/gui/file/07b6d69bafcfd767f1b63a490a8843c3bb1f8e1bbea56176109b5743c8f7d357) |
| Authentihash MD5   | [143dd36b65e3550323812614f6952d95](https://www.virustotal.com/gui/search/authentihash%253A143dd36b65e3550323812614f6952d95) |
| Authentihash SHA1  | [925f076cef081c0c2f6dded10c1349b4e65f7dde](https://www.virustotal.com/gui/search/authentihash%253A925f076cef081c0c2f6dded10c1349b4e65f7dde) |
| Authentihash SHA256| [8920dedd3c5488ecc1db2ace55b2000d4cebf899c5e591b429d3f7767eee2216](https://www.virustotal.com/gui/search/authentihash%253A8920dedd3c5488ecc1db2ace55b2000d4cebf899c5e591b429d3f7767eee2216) |
| Publisher         | &#34;SafeNet, Inc.&#34; |
| Signature         | SafeNet, Inc., VeriSign Class 3 Code Signing 2004 CA, VeriSign Class 3 Public Primary CA   |
| Company           | SafeNet, Inc. |
| Description       | Hostnt 64-bit driver |
| Product           | Hostnt |
| OriginalFilename  | Hostnt.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IoDeleteDevice
* ZwUnmapViewOfSection
* ZwClose
* IofCompleteRequest
* ObReferenceObjectByHandle
* RtlInitUnicodeString
* IoCreateDevice
* ZwOpenSection
* IoDeleteSymbolicLink
* KeBugCheckEx
* IoCreateSymbolicLink
* ZwMapViewOfSection
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/hostnt.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
