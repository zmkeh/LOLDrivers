+++

description = ""
title = "GVCIDrv64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# GVCIDrv64.sys ![:inline](/images/twitter_verified.png) 


### Description

GVCIDrv64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/8b287636041792f640f92e77e560725e.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create GVCIDrv64.sys binPath=C:\windows\temp\GVCIDrv64.sys type=kernel &amp;&amp; sc.exe start GVCIDrv64.sys
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
| Filename           | GVCIDrv64.sys |
| MD5                | [8b287636041792f640f92e77e560725e](https://www.virustotal.com/gui/file/8b287636041792f640f92e77e560725e) |
| SHA1               | [e92817a8744ebc4e4fa5383cdce2b2977f01ecd4](https://www.virustotal.com/gui/file/e92817a8744ebc4e4fa5383cdce2b2977f01ecd4) |
| SHA256             | [42f0b036687cbd7717c9efed6991c00d4e3e7b032dc965a2556c02177dfdad0f](https://www.virustotal.com/gui/file/42f0b036687cbd7717c9efed6991c00d4e3e7b032dc965a2556c02177dfdad0f) |
| Authentihash MD5   | [263d00295d36d976b90f44aadc1faa90](https://www.virustotal.com/gui/search/authentihash%253A263d00295d36d976b90f44aadc1faa90) |
| Authentihash SHA1  | [4eae38e9dc262eb7b6ede4b3d3f4ad068933845e](https://www.virustotal.com/gui/search/authentihash%253A4eae38e9dc262eb7b6ede4b3d3f4ad068933845e) |
| Authentihash SHA256| [2ff09bb919a9909068166c30322c4e904befeba5429e9a11d011297fb8a73c07](https://www.virustotal.com/gui/search/authentihash%253A2ff09bb919a9909068166c30322c4e904befeba5429e9a11d011297fb8a73c07) |
| Signature         | GIGA-BYTE TECHNOLOGY CO., LTD., Symantec Class 3 SHA256 Code Signing CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll
* WDFLDR.SYS

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IoDeleteDevice
* IoDeleteSymbolicLink
* ObReferenceObjectByHandle
* IoCreateSymbolicLink
* ZwOpenSection
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* IoCreateDevice
* IofCompleteRequest
* RtlCopyUnicodeString
* DbgPrint
* ZwClose
* RtlInitUnicodeString
* HalTranslateBusAddress
* WdfVersionUnbind
* WdfVersionBind
* WdfVersionUnbindClass
* WdfVersionBindClass

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/gvcidrv64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
