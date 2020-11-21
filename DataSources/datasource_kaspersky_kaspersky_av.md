Vendor: Kaspersky
=================
Product: Kaspersky AV
---------------------
|                                 Use-Case                                  | Activity Types                                                                   | Event Types/Parsers                                                                                                                                                                                                                                                                                                                             | MITRE TTP                                                                                                                                                                                      | Content                    |
|:-------------------------------------------------------------------------:| -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Critical System Activity<br>- Security Alert                                   |  dlp-email-alert-in<br> -- [cef-kaspersky-dlp-email](../Parsers/parserContent_cef-kaspersky-dlp-email.md)<br><br> file-alert<br> -- [cef-kaspersky-file-alert](../Parsers/parserContent_cef-kaspersky-file-alert.md)<br><br> security-alert<br> -- [cef-kaspersky-security-alert](../Parsers/parserContent_cef-kaspersky-security-alert.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>                           |  - 18 Rules<br> - 4 Models |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Endpoint Activity<br>- File Activity<br>- Process Activity<br>- Security Alert |  dlp-email-alert-in<br> -- [cef-kaspersky-dlp-email](../Parsers/parserContent_cef-kaspersky-dlp-email.md)<br><br> file-alert<br> -- [cef-kaspersky-file-alert](../Parsers/parserContent_cef-kaspersky-file-alert.md)<br><br> security-alert<br> -- [cef-kaspersky-security-alert](../Parsers/parserContent_cef-kaspersky-security-alert.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>T1204 - User Execution<br> |  - 11 Rules<br> - 4 Models |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | - Executives                                                                     |  dlp-email-alert-in<br> -- [cef-kaspersky-dlp-email](../Parsers/parserContent_cef-kaspersky-dlp-email.md)<br><br> file-alert<br> -- [cef-kaspersky-file-alert](../Parsers/parserContent_cef-kaspersky-file-alert.md)<br><br> security-alert<br> -- [cef-kaspersky-security-alert](../Parsers/parserContent_cef-kaspersky-security-alert.md)<br> | T1068 - Exploitation for Privilege Escalation<br>                                                                                                                                              |  - 1 Rules<br>             |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Endpoint Activity<br>- File Activity<br>- Process Activity<br>- Security Alert |  dlp-email-alert-in<br> -- [cef-kaspersky-dlp-email](../Parsers/parserContent_cef-kaspersky-dlp-email.md)<br><br> file-alert<br> -- [cef-kaspersky-file-alert](../Parsers/parserContent_cef-kaspersky-file-alert.md)<br><br> security-alert<br> -- [cef-kaspersky-security-alert](../Parsers/parserContent_cef-kaspersky-security-alert.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>T1204 - User Execution<br> |  - 11 Rules<br> - 4 Models |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                                                                                                                                                                                                                       | Persistence                                                         | Privilage escalation                                                                                                                                          | Defense evasion                                                                                                                                                                                                                                                               | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[User Execution](https://attack.mitre.org/techniques/T1204)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br> |                   |           |                  |            |                     |              |        |