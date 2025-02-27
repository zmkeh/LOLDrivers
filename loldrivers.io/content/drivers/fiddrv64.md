+++

description = ""
title = "fiddrv64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# fiddrv64.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

fiddrv64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/-.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create fiddrv64.sys binPath=C:\windows\temp\fiddrv64.sys type=kernel &amp;&amp; sc.exe start fiddrv64.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules"> https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules">https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | fiddrv64.sys |
| MD5                | [-](https://www.virustotal.com/gui/file/-) |
| SHA1               | [10e15ba8ff8ed926ddd3636cec66a0f08c9860a4](https://www.virustotal.com/gui/file/10e15ba8ff8ed926ddd3636cec66a0f08c9860a4) |
| SHA256             | [-](https://www.virustotal.com/gui/file/-) |
| Signature         | -   |


#### Imports
{{< details "Expand" >}}

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----
| Property           | Value |
|:-------------------|:------|
| Filename           | fiddrv64.sys |
| MD5                | [-](https://www.virustotal.com/gui/file/-) |
| SHA1               | [e4436c8c42ba5ffabd58a3b2256f6e86ccc907ab](https://www.virustotal.com/gui/file/e4436c8c42ba5ffabd58a3b2256f6e86ccc907ab) |
| SHA256             | [-](https://www.virustotal.com/gui/file/-) |
| Signature         | -   |


#### Imports
{{< details "Expand" >}}

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/fiddrv64.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
