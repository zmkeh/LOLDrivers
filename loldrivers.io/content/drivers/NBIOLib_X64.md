+++

description = ""
title = "NBIOLib_X64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# NBIOLib_X64.sys ![:inline](/images/twitter_verified.png) 


### Description

NBIOLib_X64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/f2f728d2f69765f5dfda913d407783d2.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create NBIOLib_X64.sys binPath=C:\windows\temp\NBIOLib_X64.sys     type=kernel &amp;&amp; sc.exe start NBIOLib_X64.sys
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
| Filename           | NBIOLib_X64.sys |
| MD5                | [f2f728d2f69765f5dfda913d407783d2](https://www.virustotal.com/gui/file/f2f728d2f69765f5dfda913d407783d2) |
| SHA1               | [35829e096a15e559fcbabf3441d99e580ca3b26e](https://www.virustotal.com/gui/file/35829e096a15e559fcbabf3441d99e580ca3b26e) |
| SHA256             | [3f2fda9a7a9c57b7138687bbce49a2e156d6095dddabb3454ea09737e02c3fa5](https://www.virustotal.com/gui/file/3f2fda9a7a9c57b7138687bbce49a2e156d6095dddabb3454ea09737e02c3fa5) |
| Authentihash MD5   | [2d87365d63e81ef0edc577bf0cb33995](https://www.virustotal.com/gui/search/authentihash%253A2d87365d63e81ef0edc577bf0cb33995) |
| Authentihash SHA1  | [b472d32094e258b2af60914db8604cd0bf439c4b](https://www.virustotal.com/gui/search/authentihash%253Ab472d32094e258b2af60914db8604cd0bf439c4b) |
| Authentihash SHA256| [d33f19a12cd8e8649a56ce2a41e2b56d2ed80f203e5ededc4114c78ef773ffa8](https://www.virustotal.com/gui/search/authentihash%253Ad33f19a12cd8e8649a56ce2a41e2b56d2ed80f203e5ededc4114c78ef773ffa8) |
| Signature         | MICRO-STAR INTERNATIONAL CO., LTD., GlobalSign CodeSigning CA - G2, GlobalSign Root CA - R1   |
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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nbiolib_x64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
