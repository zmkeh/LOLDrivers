+++

description = ""
title = "nt3.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# nt3.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

nt3.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/-.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create nt3.sys binPath=C:\windows\temp \n \n \n  t3.sys type=kernel &amp;&amp; sc.exe start nt3.sys
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
| Filename           | nt3.sys |
| MD5                | [-](https://www.virustotal.com/gui/file/-) |
| SHA1               | [-](https://www.virustotal.com/gui/file/-) |
| SHA256             | [7d8937c18d6e11a0952e53970a0934cf0e65515637ac24d6ca52ccf4b93d385f](https://www.virustotal.com/gui/file/7d8937c18d6e11a0952e53970a0934cf0e65515637ac24d6ca52ccf4b93d385f) |
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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nt3.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
