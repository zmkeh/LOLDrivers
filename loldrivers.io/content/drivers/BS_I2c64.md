+++

description = ""
title = "BS_I2c64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# BS_I2c64.sys ![:inline](/images/twitter_verified.png) 


### Description

BS_I2c64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/83601bbe5563d92c1fdb4e960d84dc77.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create BS_I2c64.sys binPath=C:\windows\temp\BS_I2c64.sys type=kernel &amp;&amp; sc.exe start BS_I2c64.sys
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
| Filename           | BS_I2c64.sys |
| MD5                | [83601bbe5563d92c1fdb4e960d84dc77](https://www.virustotal.com/gui/file/83601bbe5563d92c1fdb4e960d84dc77) |
| SHA1               | [dc55217b6043d819eadebd423ff07704ee103231](https://www.virustotal.com/gui/file/dc55217b6043d819eadebd423ff07704ee103231) |
| SHA256             | [55fee54c0d0d873724864dc0b2a10b38b7f40300ee9cae4d9baaf8a202c4049a](https://www.virustotal.com/gui/file/55fee54c0d0d873724864dc0b2a10b38b7f40300ee9cae4d9baaf8a202c4049a) |
| Authentihash MD5   | [bcc1ae726001fdbabb8159e3b333f3fd](https://www.virustotal.com/gui/search/authentihash%253Abcc1ae726001fdbabb8159e3b333f3fd) |
| Authentihash SHA1  | [7885fb33d8800fa3c036252af70e0a8391ab367d](https://www.virustotal.com/gui/search/authentihash%253A7885fb33d8800fa3c036252af70e0a8391ab367d) |
| Authentihash SHA256| [85ac17aec836d5125db7407d2dc3af8e5b01241fea781b2fd55aae796b3912b4](https://www.virustotal.com/gui/search/authentihash%253A85ac17aec836d5125db7407d2dc3af8e5b01241fea781b2fd55aae796b3912b4) |
| Signature         | BIOSTAR MICROTECH INT&#39;L CORP, VeriSign Class 3 Code Signing 2004 CA, VeriSign Class 3 Public Primary CA   |
| Company           | BIOSTAR Group |
| Description       | I/O Interface driver file |
| Product           | BIOSTAR I/O driver fle |
| OriginalFilename  | BS_I2cIo.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IoDeleteSymbolicLink
* IoStartNextPacket
* IoReleaseCancelSpinLock
* IoAcquireCancelSpinLock
* MmUnmapIoSpace
* RtlInitUnicodeString
* KeRemoveEntryDeviceQueue
* IofCompleteRequest
* IoStartPacket
* IoCreateDevice
* IoCreateSymbolicLink
* MmMapIoSpace
* IoDeleteDevice
* HalSetBusDataByOffset
* HalTranslateBusAddress
* HalGetBusDataByOffset

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/bs_i2c64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
