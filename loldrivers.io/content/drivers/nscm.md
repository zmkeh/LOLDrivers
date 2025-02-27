+++

description = ""
title = "nscm.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# nscm.sys ![:inline](/images/twitter_verified.png) 


### Description

nscm.sys is a vulnerable driver. CVE-2013-3956.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/4a23e0f2c6f926a41b28d574cbc6ac30.bin" "Download" >}}
{{< tip "warning" >}}
This download link contains the vulnerable driver!

{{< /tip >}}

### Commands

```
sc.exe create nscm.sys binPath=C:\windows\temp \n \n \n  scm.sys type=kernel &amp;&amp; sc.exe start nscm.sys
```

| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/jbaines-r7/dellicious"> https://github.com/jbaines-r7/dellicious</a></li>
<li><a href=" https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/"> https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<li><a href="https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/">https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<br>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | nscm.sys |
| MD5                | [4a23e0f2c6f926a41b28d574cbc6ac30](https://www.virustotal.com/gui/file/4a23e0f2c6f926a41b28d574cbc6ac30) |
| SHA1               | [64e4ac8b9ea2f050933b7ec76a55dd04e97773b4](https://www.virustotal.com/gui/file/64e4ac8b9ea2f050933b7ec76a55dd04e97773b4) |
| SHA256             | [76660e91f1ff3cb89630df5af4fe09de6098d09baa66b1a130c89c3c5edd5b22](https://www.virustotal.com/gui/file/76660e91f1ff3cb89630df5af4fe09de6098d09baa66b1a130c89c3c5edd5b22) |
| Authentihash MD5   | [0d1a4e506e7c928f1683a9cf38eb0835](https://www.virustotal.com/gui/search/authentihash%253A0d1a4e506e7c928f1683a9cf38eb0835) |
| Authentihash SHA1  | [50471608c91621cb84ba646974311da0abf6b3e9](https://www.virustotal.com/gui/search/authentihash%253A50471608c91621cb84ba646974311da0abf6b3e9) |
| Authentihash SHA256| [0e291148da43ea6a491b8b94bdf573365087940c9b90f6a15a4e589da86a518d](https://www.virustotal.com/gui/search/authentihash%253A0e291148da43ea6a491b8b94bdf573365087940c9b90f6a15a4e589da86a518d) |
| Signature         | Novell, Inc., VeriSign Class 3 Code Signing 2009-2 CA, VeriSign Class 3 Public Primary CA   |
| Company           | Novell, Inc. |
| Description       | Novell XTier Session Manager |
| Product           | Novell XTier |
| OriginalFilename  | nscm.sys |


#### Imports
{{< details "Expand" >}}
* ntoskrnl.exe
* nicm.sys

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}
* ExAllocatePoolWithTag
* ExFreePoolWithTag
* KeInitializeMutex
* IoQueueWorkItemEx
* IoDeleteDevice
* IoFreeWorkItem
* RtlEqualUnicodeString
* ZwOpenProcessTokenEx
* IoAllocateWorkItem
* ZwClose
* ZwOpenProcess
* DbgPrint
* PsGetCurrentProcessId
* IoCreateDevice
* ZwQueryInformationToken
* PsSetCreateProcessNotifyRoutine
* SeRegisterLogonSessionTerminatedRoutine
* SeUnregisterLogonSessionTerminatedRoutine
* ZwOpenThreadTokenEx
* IoGetCurrentProcess
* SeMarkLogonSessionForTerminationNotification
* KeBugCheckEx
* KeWaitForSingleObject
* ZwQueryInformationProcess
* KeReleaseMutex
* NicmCreateInstance
* NicmDeregisterClassFactory

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}
* DllGetClassObject
* XTCOM_Table

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/nscm.yaml)

*last_updated:* 2023-04-27








{{< /column >}}
{{< /block >}}
