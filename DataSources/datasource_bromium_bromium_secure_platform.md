Vendor: Bromium
===============
Product: Bromium Secure Platform
--------------------------------
|                                 Use-Case                                  | Activity Types                                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                | MITRE TTP                                                          | Content                   |
|:-------------------------------------------------------------------------:| --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Critical System Activity<br>- File Activity |  file-permission-change<br> -- [cef-bromium-file-permission-change](../Parsers/parserContent_cef-bromium-file-permission-change.md)<br><br> file-read<br> -- [cef-bromium-file-read](../Parsers/parserContent_cef-bromium-file-read.md)<br><br> file-write<br> -- [cef-bromium-file-write](../Parsers/parserContent_cef-bromium-file-write.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br> |  - 3 Rules<br> - 2 Models |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | - File Activity                               |  file-permission-change<br> -- [cef-bromium-file-permission-change](../Parsers/parserContent_cef-bromium-file-permission-change.md)<br><br> file-read<br> -- [cef-bromium-file-read](../Parsers/parserContent_cef-bromium-file-read.md)<br><br> file-write<br> -- [cef-bromium-file-write](../Parsers/parserContent_cef-bromium-file-write.md)<br> | T1083 - File and Directory Discovery<br>                           |  - 3 Rules<br> - 3 Models |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Endpoint Activity<br>- File Activity        |  file-permission-change<br> -- [cef-bromium-file-permission-change](../Parsers/parserContent_cef-bromium-file-permission-change.md)<br><br> file-read<br> -- [cef-bromium-file-read](../Parsers/parserContent_cef-bromium-file-read.md)<br><br> file-write<br> -- [cef-bromium-file-write](../Parsers/parserContent_cef-bromium-file-write.md)<br> | T1204 - User Execution<br>                                         |  - 3 Rules<br> - 1 Models |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Endpoint Activity<br>- File Activity        |  file-permission-change<br> -- [cef-bromium-file-permission-change](../Parsers/parserContent_cef-bromium-file-permission-change.md)<br><br> file-read<br> -- [cef-bromium-file-read](../Parsers/parserContent_cef-bromium-file-read.md)<br><br> file-write<br> -- [cef-bromium-file-write](../Parsers/parserContent_cef-bromium-file-write.md)<br> | T1204 - User Execution<br>                                         |  - 3 Rules<br> - 1 Models |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilage escalation                                                | Defense evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     |              |        |