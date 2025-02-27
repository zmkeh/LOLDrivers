+++

description = ""
title = "GLCKIO2.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# GLCKIO2.sys ![:inline](/images/twitter_verified.png) 


### Description

GLCKIO2.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/e700a820f117f65e813b216fccbf78c9.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create GLCKIO2.sys binPath=C:\windows\temp\GLCKIO2.sys type=kernel &amp;&amp; sc.exe start GLCKIO2.sys
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
| Filename           | GLCKIO2.sys |
| MD5                | [e700a820f117f65e813b216fccbf78c9](https://www.virustotal.com/gui/file/e700a820f117f65e813b216fccbf78c9) |
| SHA1               | [2dfcb799b3c42ecb0472e27c19b24ac7532775ce](https://www.virustotal.com/gui/file/2dfcb799b3c42ecb0472e27c19b24ac7532775ce) |
| SHA256             | [3a5ec83fe670e5e23aef3afa0a7241053f5b6be5e6ca01766d6b5f9177183c25](https://www.virustotal.com/gui/file/3a5ec83fe670e5e23aef3afa0a7241053f5b6be5e6ca01766d6b5f9177183c25) |
| Authentihash MD5   | [505c5b85b442f9159ba715d4867f9ac4](https://www.virustotal.com/gui/search/authentihash%253A505c5b85b442f9159ba715d4867f9ac4) |
| Authentihash SHA1  | [83644f9ece6d6ef3517e1829595c52380922ed35](https://www.virustotal.com/gui/search/authentihash%253A83644f9ece6d6ef3517e1829595c52380922ed35) |
| Authentihash SHA256| [25a0854ef48a4dfbc7f04e94d2b11757e3613b241d39d46a19cb389ce42887e4](https://www.virustotal.com/gui/search/authentihash%253A25a0854ef48a4dfbc7f04e94d2b11757e3613b241d39d46a19cb389ce42887e4) |
| Publisher         | ASUSTeK Computer Inc. |
| Signature         | ASUSTeK Computer Inc., DigiCert SHA2 High Assurance Code Signing CA, DigiCert   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IofCompleteRequest
* IoCreateDevice
* IoCreateSymbolicLink
* IoDeleteDevice
* IoDeleteSymbolicLink
* MmGetSystemRoutineAddress
* ObfDereferenceObject
* ZwClose
* ZwOpenSection
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* KeBugCheckEx
* ObReferenceObjectByHandle
* RtlInitUnicodeString
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | GLCKIO2.sys |
| MD5                | [d253c19194a18030296ae62a10821640](https://www.virustotal.com/gui/file/d253c19194a18030296ae62a10821640) |
| SHA1               | [cc51be79ae56bc97211f6b73cc905c3492da8f9d](https://www.virustotal.com/gui/file/cc51be79ae56bc97211f6b73cc905c3492da8f9d) |
| SHA256             | [61a1bdddd3c512e681818debb5bee94db701768fc25e674fcad46592a3259bd0](https://www.virustotal.com/gui/file/61a1bdddd3c512e681818debb5bee94db701768fc25e674fcad46592a3259bd0) |
| Authentihash MD5   | [86b5239d6b6fe0d6fad286f809d7571a](https://www.virustotal.com/gui/search/authentihash%253A86b5239d6b6fe0d6fad286f809d7571a) |
| Authentihash SHA1  | [d99b80b3269d735cac43af5e43483e64ca7961c3](https://www.virustotal.com/gui/search/authentihash%253Ad99b80b3269d735cac43af5e43483e64ca7961c3) |
| Authentihash SHA256| [47dba240967fd0088be618163672dfbddf0138178cccd45b54037f622b221220](https://www.virustotal.com/gui/search/authentihash%253A47dba240967fd0088be618163672dfbddf0138178cccd45b54037f622b221220) |
| Publisher         | ASUSTeK Computer Inc. |
| Signature         | ASUSTeK Computer Inc., DigiCert SHA2 High Assurance Code Signing CA, DigiCert   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* HAL.dll

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* IofCompleteRequest
* IoCreateDevice
* IoCreateSymbolicLink
* IoDeleteDevice
* IoDeleteSymbolicLink
* MmGetSystemRoutineAddress
* ObfDereferenceObject
* ZwClose
* ZwOpenSection
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* KeBugCheckEx
* ObReferenceObjectByHandle
* RtlInitUnicodeString
* HalTranslateBusAddress

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/glckio2.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
