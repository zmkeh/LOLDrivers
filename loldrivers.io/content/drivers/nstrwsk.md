+++

description = ""
title = "nstrwsk.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# nstrwsk.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

nstrwsk.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/-.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create nstrwsk.sys binPath=C:\windows\temp \n \n \n  strwsk.sys type=kernel &amp;&amp; sc.exe start nstrwsk.sys
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
| Filename           | nstrwsk.sys |
| MD5                | [-](https://www.virustotal.com/gui/file/-) |
| SHA1               | [-](https://www.virustotal.com/gui/file/-) |
| SHA256             | [3390919bb28d5c36cc348f9ef23be5fa49bfd81263eb7740826e4437cbe904cd](https://www.virustotal.com/gui/file/3390919bb28d5c36cc348f9ef23be5fa49bfd81263eb7740826e4437cbe904cd) |
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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nstrwsk.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
