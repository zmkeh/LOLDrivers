+++

description = ""
title = "driver7-x86-withoutdbg.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# driver7-x86-withoutdbg.sys ![:inline](/images/twitter_verified.png) 


### Description

driver7-x86-withoutdbg.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/4f191abc652d8f7442ca2636725e1ed6.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create driver7-x86-withoutdbg.sys binPath=C:\windows\temp\driver7-x86-withoutdbg.sys     type=kernel &amp;&amp; sc.exe start driver7-x86-withoutdbg.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/Chigusa0w0/AsusDriversPrivEscala"> https://github.com/Chigusa0w0/AsusDriversPrivEscala</a></li>
<li><a href="https://github.com/Chigusa0w0/AsusDriversPrivEscala">https://github.com/Chigusa0w0/AsusDriversPrivEscala</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | driver7-x86-withoutdbg.sys |
| MD5                | [4f191abc652d8f7442ca2636725e1ed6](https://www.virustotal.com/gui/file/4f191abc652d8f7442ca2636725e1ed6) |
| SHA1               | [4243dbbf6e5719d723f24d0f862afd0fcb40bc35](https://www.virustotal.com/gui/file/4243dbbf6e5719d723f24d0f862afd0fcb40bc35) |
| SHA256             | [927c2a580d51a598177fa54c65e9d2610f5f212f1b6cb2fbf2740b64368f010a](https://www.virustotal.com/gui/file/927c2a580d51a598177fa54c65e9d2610f5f212f1b6cb2fbf2740b64368f010a) |
| Authentihash MD5   | [7776703e27df791bf1d4af2acb94115d](https://www.virustotal.com/gui/search/authentihash%253A7776703e27df791bf1d4af2acb94115d) |
| Authentihash SHA1  | [8c08885be9ec2ad64537038f6dca6654e475106a](https://www.virustotal.com/gui/search/authentihash%253A8c08885be9ec2ad64537038f6dca6654e475106a) |
| Authentihash SHA256| [baa89ffd5255e5c72112ed57937353ae48a050c9af423cbde6b380978ecc235c](https://www.virustotal.com/gui/search/authentihash%253Abaa89ffd5255e5c72112ed57937353ae48a050c9af423cbde6b380978ecc235c) |
| Signature         | ASUSTeK Computer Inc., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |
| Company           | ASUStek |
| Description       | The driver for the ECtool driver-based tools |
| Product           | EC tool |
| OriginalFilename  | Driver7 |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ObReferenceObjectByHandle
* ZwOpenSection
* RtlInitUnicodeString
* ZwUnmapViewOfSection
* MmGetPhysicalAddress
* ObfDereferenceObject
* ZwMapViewOfSection
* IoWMIOpenBlock
* IoDeleteDevice
* IoDeleteSymbolicLink
* IoCreateSymbolicLink
* IoCreateDevice
* KeTickCount
* KeBugCheckEx
* ZwClose
* memset
* memcpy
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* RtlAssert
* IofCompleteRequest
* IoWMIQueryAllData
* DbgPrint
* HalTranslateBusAddress
* WRITE_PORT_ULONG
* READ_PORT_ULONG
* WRITE_PORT_USHORT
* READ_PORT_USHORT
* WRITE_PORT_UCHAR
* READ_PORT_UCHAR
* KeGetCurrentIrql

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/driver7-x86-withoutdbg.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
