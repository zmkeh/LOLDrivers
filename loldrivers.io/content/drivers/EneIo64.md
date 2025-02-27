+++

description = ""
title = "EneIo64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# EneIo64.sys ![:inline](/images/twitter_verified.png) 


### Description

EneIo64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/11fb599312cb1cf43ca5e879ed6fb71e.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create EneIo64.sys binPath=C:\windows\temp\EneIo64.sys type=kernel &amp;&amp; sc.exe start EneIo64.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://gist.github.com/k4nfr3/af970e7facb09195e56f2112e1c9549c"> https://gist.github.com/k4nfr3/af970e7facb09195e56f2112e1c9549c</a></li>
<li><a href="https://gist.github.com/k4nfr3/af970e7facb09195e56f2112e1c9549c">https://gist.github.com/k4nfr3/af970e7facb09195e56f2112e1c9549c</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | EneIo64.sys |
| MD5                | [11fb599312cb1cf43ca5e879ed6fb71e](https://www.virustotal.com/gui/file/11fb599312cb1cf43ca5e879ed6fb71e) |
| SHA1               | [b4d014b5edd6e19ce0e8395a64faedf49688ecb5](https://www.virustotal.com/gui/file/b4d014b5edd6e19ce0e8395a64faedf49688ecb5) |
| SHA256             | [9fc29480407e5179aa8ea41682409b4ea33f1a42026277613d6484e5419de374](https://www.virustotal.com/gui/file/9fc29480407e5179aa8ea41682409b4ea33f1a42026277613d6484e5419de374) |
| Authentihash MD5   | [198111fd73515aa7fe4387612f027f0f](https://www.virustotal.com/gui/search/authentihash%253A198111fd73515aa7fe4387612f027f0f) |
| Authentihash SHA1  | [651b953cb03928e41424ad59f21d4978d6f4952e](https://www.virustotal.com/gui/search/authentihash%253A651b953cb03928e41424ad59f21d4978d6f4952e) |
| Authentihash SHA256| [ebbaa44277a3ec6e20ad3f6aef5399fdc398306eb4c13aa96e45c9a281820a12](https://www.virustotal.com/gui/search/authentihash%253Aebbaa44277a3ec6e20ad3f6aef5399fdc398306eb4c13aa96e45c9a281820a12) |
| Signature         | Microsoft Windows Hardware Compatibility Publisher, Microsoft Windows Third Party Component CA 2014, Microsoft Root Certificate Authority 2010   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* RtlInitUnicodeString
* IoDeleteDevice
* ZwUnmapViewOfSection
* ZwClose
* IofCompleteRequest
* ObReferenceObjectByHandle
* ZwMapViewOfSection
* ObfDereferenceObject
* IoCreateDevice
* RtlAssert
* ZwOpenSection
* DbgPrint
* KeBugCheckEx
* IoCreateSymbolicLink
* IoDeleteSymbolicLink
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/eneio64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
