Vendor: SFTP
============
Product: SFTP
-------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  115  |   50   |     14     |      7      |    7    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Application Access.Privileged Asset Activity](../../../UseCases/uc_abnormal_application_access.privileged_asset_activity.md) |  app-activity<br> ↳[sftp-file-download](Ps/pC_sftpfiledownload.md)<br><br> app-login<br> ↳[sftp-failed-app-login](Ps/pC_sftpfailedapplogin.md)<br><br> file-delete<br> ↳[sftp-app-login](Ps/pC_sftpapplogin.md)<br><br> file-download<br> ↳[sftp-file-read](Ps/pC_sftpfileread.md)<br><br> file-read<br> ↳[sftp-file-upload](Ps/pC_sftpfileupload.md)<br><br> file-upload<br> ↳[sftp-file-write-2](Ps/pC_sftpfilewrite2.md)<br> ↳[sftp-file-write-1](Ps/pC_sftpfilewrite1.md)<br><br> file-write<br> ↳[sftp-file-delete](Ps/pC_sftpfiledelete.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_sftp_sftp_Abnormal_Application_Access.Privileged_Asset_Activity.md) |
|    [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md)    |  app-activity<br> ↳[sftp-file-download](Ps/pC_sftpfiledownload.md)<br><br> app-login<br> ↳[sftp-failed-app-login](Ps/pC_sftpfailedapplogin.md)<br><br> file-delete<br> ↳[sftp-app-login](Ps/pC_sftpapplogin.md)<br><br> file-download<br> ↳[sftp-file-read](Ps/pC_sftpfileread.md)<br><br> file-read<br> ↳[sftp-file-upload](Ps/pC_sftpfileupload.md)<br><br> file-upload<br> ↳[sftp-file-write-2](Ps/pC_sftpfilewrite2.md)<br> ↳[sftp-file-write-1](Ps/pC_sftpfilewrite1.md)<br><br> file-write<br> ↳[sftp-file-delete](Ps/pC_sftpfiledelete.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>14 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_sftp_sftp_Abnormal_Authentication_&_Access.md)    |
[Next Page -->>](2_ds_sftp_sftp.md)

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                                                                                                                                                                                                                 | Privilege Escalation                                                | Defense Evasion                                                                                                                                                                                                                                    | Credential Access                                                          | Discovery                                                                         | Lateral Movement | Collection                                                                                                                                                            | Command and Control                                                                                                                       | Exfiltration | Impact                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br>[Account Manipulation: Exchange Email Delegate Permissions](https://attack.mitre.org/techniques/T1098/002)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Indicator Removal on Host: File Deletion](https://attack.mitre.org/techniques/T1070/004)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Indicator Removal on Host](https://attack.mitre.org/techniques/T1070)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  | [Email Collection](https://attack.mitre.org/techniques/T1114)<br><br>[Email Collection: Email Forwarding Rule](https://attack.mitre.org/techniques/T1114/003)<br><br> | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Data Destruction](https://attack.mitre.org/techniques/T1485)<br><br>[Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486)<br><br> |