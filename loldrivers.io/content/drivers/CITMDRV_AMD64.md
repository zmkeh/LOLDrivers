+++

description = ""
title = "CITMDRV_AMD64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# CITMDRV_AMD64.sys ![:inline](/images/twitter_verified.png) 


### Description

CITMDRV_AMD64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/e076dadf37dd43a6b36aeed957abee9e.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create CITMDRV_AMD64.sys binPath=C:\windows\temp\CITMDRV_AMD64.sys     type=kernel &amp;&amp; sc.exe start CITMDRV_AMD64.sys
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
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [e076dadf37dd43a6b36aeed957abee9e](https://www.virustotal.com/gui/file/e076dadf37dd43a6b36aeed957abee9e) |
| SHA1               | [468e2e5505a3d924b14fedee4ddf240d09393776](https://www.virustotal.com/gui/file/468e2e5505a3d924b14fedee4ddf240d09393776) |
| SHA256             | [29e0062a017a93b2f2f5207a608a96df4d554c5de976bd0276c2590a03bd3e94](https://www.virustotal.com/gui/file/29e0062a017a93b2f2f5207a608a96df4d554c5de976bd0276c2590a03bd3e94) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [aa1ed3917928f04d97d8a217fe9b5cb1](https://www.virustotal.com/gui/file/aa1ed3917928f04d97d8a217fe9b5cb1) |
| SHA1               | [2e3de9bff43d7712707ef8a0b10f7e4ad8427fd8](https://www.virustotal.com/gui/file/2e3de9bff43d7712707ef8a0b10f7e4ad8427fd8) |
| SHA256             | [45abdbcd4c0916b7d9faaf1cd08543a3a5178871074628e0126a6eda890d26e0](https://www.virustotal.com/gui/file/45abdbcd4c0916b7d9faaf1cd08543a3a5178871074628e0126a6eda890d26e0) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [dd39a86852b498b891672ffbcd071c03](https://www.virustotal.com/gui/file/dd39a86852b498b891672ffbcd071c03) |
| SHA1               | [c9cbfdd0be7b35751a017ec59ff7237ffdc4df1f](https://www.virustotal.com/gui/file/c9cbfdd0be7b35751a017ec59ff7237ffdc4df1f) |
| SHA256             | [50db5480d0392a7dd6ab5df98389dc24d1ed1e9c98c9c35964b19dabcd6dc67f](https://www.virustotal.com/gui/file/50db5480d0392a7dd6ab5df98389dc24d1ed1e9c98c9c35964b19dabcd6dc67f) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [708ac9f7b12b6ca4553fd8d0c7299296](https://www.virustotal.com/gui/file/708ac9f7b12b6ca4553fd8d0c7299296) |
| SHA1               | [078ae07dec258db4376d5a2a05b9b508d68c0123](https://www.virustotal.com/gui/file/078ae07dec258db4376d5a2a05b9b508d68c0123) |
| SHA256             | [607dc4c75ac7aef82ae0616a453866b3b358c6cf5c8f9d29e4d37f844306b97c](https://www.virustotal.com/gui/file/607dc4c75ac7aef82ae0616a453866b3b358c6cf5c8f9d29e4d37f844306b97c) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [7a16fca3d56c6038c692ec75b2bfee15](https://www.virustotal.com/gui/file/7a16fca3d56c6038c692ec75b2bfee15) |
| SHA1               | [623cd2abef6c92255f79cbbd3309cb59176771da](https://www.virustotal.com/gui/file/623cd2abef6c92255f79cbbd3309cb59176771da) |
| SHA256             | [61d6e40601fa368800980801a662a5b3b36e3c23296e8ae1c85726a56ef18cc8](https://www.virustotal.com/gui/file/61d6e40601fa368800980801a662a5b3b36e3c23296e8ae1c85726a56ef18cc8) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [5970e8de1b337ca665114511b9d10806](https://www.virustotal.com/gui/file/5970e8de1b337ca665114511b9d10806) |
| SHA1               | [1f3a9265963b660392c4053329eb9436deeed339](https://www.virustotal.com/gui/file/1f3a9265963b660392c4053329eb9436deeed339) |
| SHA256             | [74a846c61adc53692d3040aff4c1916f32987ad72b07fe226e9e7dbeff1036c4](https://www.virustotal.com/gui/file/74a846c61adc53692d3040aff4c1916f32987ad72b07fe226e9e7dbeff1036c4) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [2509a71a02296aa65a3428ddfac22180](https://www.virustotal.com/gui/file/2509a71a02296aa65a3428ddfac22180) |
| SHA1               | [4a235f0b84ff615e2879fa9e0ec0d745fcfdaa5c](https://www.virustotal.com/gui/file/4a235f0b84ff615e2879fa9e0ec0d745fcfdaa5c) |
| SHA256             | [76fb4deaee57ef30e56c382c92abffe2cf616d08dbecb3368c8ee6b02e59f303](https://www.virustotal.com/gui/file/76fb4deaee57ef30e56c382c92abffe2cf616d08dbecb3368c8ee6b02e59f303) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [296bde4d0ed32c6069eb90c502187d0d](https://www.virustotal.com/gui/file/296bde4d0ed32c6069eb90c502187d0d) |
| SHA1               | [ace6b9e34e3e2e73fe584f3bbdb4e4ec106e0a7d](https://www.virustotal.com/gui/file/ace6b9e34e3e2e73fe584f3bbdb4e4ec106e0a7d) |
| SHA256             | [81939e5c12bd627ff268e9887d6fb57e95e6049f28921f3437898757e7f21469](https://www.virustotal.com/gui/file/81939e5c12bd627ff268e9887d6fb57e95e6049f28921f3437898757e7f21469) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [d1bac75205c389d6d5d6418f0457c29b](https://www.virustotal.com/gui/file/d1bac75205c389d6d5d6418f0457c29b) |
| SHA1               | [4268f30b79ce125a81d0d588bef0d4e2ad409bbb](https://www.virustotal.com/gui/file/4268f30b79ce125a81d0d588bef0d4e2ad409bbb) |
| SHA256             | [9790a7b9d624b2b18768bb655dda4a05a9929633cef0b1521e79e40d7de0a05b](https://www.virustotal.com/gui/file/9790a7b9d624b2b18768bb655dda4a05a9929633cef0b1521e79e40d7de0a05b) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [b2a9ac0600b12ec9819e049d7a6a0b75](https://www.virustotal.com/gui/file/b2a9ac0600b12ec9819e049d7a6a0b75) |
| SHA1               | [c834c4931b074665d56ccab437dfcc326649d612](https://www.virustotal.com/gui/file/c834c4931b074665d56ccab437dfcc326649d612) |
| SHA256             | [9a1d66036b0868bbb1b2823209fedea61a301d5dd245f8e7d390bd31e52d663e](https://www.virustotal.com/gui/file/9a1d66036b0868bbb1b2823209fedea61a301d5dd245f8e7d390bd31e52d663e) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., Symantec Class 3 SHA256 Code Signing CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [79f7e6f98a5d3ab6601622be4471027f](https://www.virustotal.com/gui/file/79f7e6f98a5d3ab6601622be4471027f) |
| SHA1               | [8f5cd4a56e6e15935491aa40adb1ecad61eafe7c](https://www.virustotal.com/gui/file/8f5cd4a56e6e15935491aa40adb1ecad61eafe7c) |
| SHA256             | [aa9ab1195dc866270e984f1bed5e1358d6ef24c515dfdb6c2a92d1e1b94bf608](https://www.virustotal.com/gui/file/aa9ab1195dc866270e984f1bed5e1358d6ef24c515dfdb6c2a92d1e1b94bf608) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary Certification Authority (PCA3 G1 SHA1)   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [2d465b4487dc81effaa84f122b71c24f](https://www.virustotal.com/gui/file/2d465b4487dc81effaa84f122b71c24f) |
| SHA1               | [51b60eaa228458dee605430aae1bc26f3fc62325](https://www.virustotal.com/gui/file/51b60eaa228458dee605430aae1bc26f3fc62325) |
| SHA256             | [af095de15a16255ca1b2c27dad365dff9ac32d2a75e8e288f5a1307680781685](https://www.virustotal.com/gui/file/af095de15a16255ca1b2c27dad365dff9ac32d2a75e8e288f5a1307680781685) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [4d17b32be70ef39eae5d5edeb5e89877](https://www.virustotal.com/gui/file/4d17b32be70ef39eae5d5edeb5e89877) |
| SHA1               | [3270720a066492b046d7180ca6e60602c764cac7](https://www.virustotal.com/gui/file/3270720a066492b046d7180ca6e60602c764cac7) |
| SHA256             | [d5586dc1e61796a9ae5e5d1ced397874753056c3df2eb963a8916287e1929a71](https://www.virustotal.com/gui/file/d5586dc1e61796a9ae5e5d1ced397874753056c3df2eb963a8916287e1929a71) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [c1d3a6bb423739a5e781f7eee04c9cfd](https://www.virustotal.com/gui/file/c1d3a6bb423739a5e781f7eee04c9cfd) |
| SHA1               | [2a6e6bd51c7062ad24c02a4d2c1b5e948908d131](https://www.virustotal.com/gui/file/2a6e6bd51c7062ad24c02a4d2c1b5e948908d131) |
| SHA256             | [d8459f7d707c635e2c04d6d6d47b63f73ba3f6629702c7a6e0df0462f6478ae2](https://www.virustotal.com/gui/file/d8459f7d707c635e2c04d6d6d47b63f73ba3f6629702c7a6e0df0462f6478ae2) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [054299e09cea38df2b84e6b29348b418](https://www.virustotal.com/gui/file/054299e09cea38df2b84e6b29348b418) |
| SHA1               | [19bd488fe54b011f387e8c5d202a70019a204adf](https://www.virustotal.com/gui/file/19bd488fe54b011f387e8c5d202a70019a204adf) |
| SHA256             | [e81230217988f3e7ec6f89a06d231ec66039bdba340fd8ebb2bbb586506e3293](https://www.virustotal.com/gui/file/e81230217988f3e7ec6f89a06d231ec66039bdba340fd8ebb2bbb586506e3293) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., Symantec Class 3 SHA256 Code Signing CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | CITMDRV_AMD64.sys |
| MD5                | [0ba6afe0ea182236f98365bd977adfdf](https://www.virustotal.com/gui/file/0ba6afe0ea182236f98365bd977adfdf) |
| SHA1               | [a6fe4f30ca7cb94d74bc6d42cdd09a136056952e](https://www.virustotal.com/gui/file/a6fe4f30ca7cb94d74bc6d42cdd09a136056952e) |
| SHA256             | [f88ebb633406a086d9cca6bc8b66a4ea940c5476529f9033a9e0463512a23a57](https://www.virustotal.com/gui/file/f88ebb633406a086d9cca6bc8b66a4ea940c5476529f9033a9e0463512a23a57) |
| Authentihash MD5   | [6df250bd96e46a522bd7536100737f13](https://www.virustotal.com/gui/search/authentihash%253A6df250bd96e46a522bd7536100737f13) |
| Authentihash SHA1  | [d917e8e8aee2cb3d01d1ba123098654cf370689f](https://www.virustotal.com/gui/search/authentihash%253Ad917e8e8aee2cb3d01d1ba123098654cf370689f) |
| Authentihash SHA256| [5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac](https://www.virustotal.com/gui/search/authentihash%253A5be61901f41d55e6fbd0994869015448f8eb0450ae38f67b75ddb594c3325aac) |
| Publisher         | IBM Polska Sp. z o.o. |
| Signature         | IBM Polska Sp. z o.o., Symantec Class 3 SHA256 Code Signing CA, VeriSign   |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ZwClose
* ZwOpenFile
* RtlInitUnicodeString
* ZwWriteFile
* DbgPrint
* ZwCreateFile
* vsprintf
* IoDeleteDevice
* IoDeleteSymbolicLink
* ZwMapViewOfSection
* ZwUnmapViewOfSection
* __C_specific_handler
* IoFreeMdl
* MmUnlockPages
* ZwOpenSection
* MmProbeAndLockPages
* IoAllocateMdl
* IofCompleteRequest
* IoCreateSymbolicLink
* IoCreateDevice
* KeBugCheckEx

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/citmdrv_amd64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
