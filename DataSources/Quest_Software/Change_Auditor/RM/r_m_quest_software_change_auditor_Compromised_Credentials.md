Vendor: Quest Software
======================
### Product: [Change Auditor](../ds_quest_software_change_auditor.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  13   |   3    |     7      |      8      |    8    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Models                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| ds-access    | <b>T1558 - Steal or Forge Kerberos Tickets</b><br> ↳ <b>ATP-AS-REP-2</b>: Suspicious UAC directory service change indicating AS-REP Roasting<br><br><b>T1003.006 - OS Credential Dumping: DCSync</b><br> ↳ <b>A-DCSync</b>: Possible DCSync Attack: New domain controller detected<br> ↳ <b>DCSync-ExistHost</b>: Possible DCSync attack - existing host has replicated Active Directory.<br> ↳ <b>DCSync-FirstDS</b>: Possible DCSync attack - first DS access event from host.<br><br><b>T1207 - Rogue Domain Controller</b><br> ↳ <b>A-DS-DCShadow</b>: Possible DCShadow attack by asset detected. |  • <b>DS-HOSTS</b>: Models hosts in an Active Directory environment |
| failed-logon | <b>T1212 - Exploitation for Credential Access</b><br> ↳ <b>A-Kerberos-Manipulation-Failure</b>: Possible Kerberos failure code triggered by manipulation of Kerberos messages on the asset.<br> ↳ <b>Kerberos-Manipulation-Failure</b>: Rare Kerberos failure code triggered by possible manipulation of Kerberos messages.<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-04</b>: Failed logon by a service account<br> ↳ <b>SEQ-UH-05</b>: Failed interactive logon by a service account                                                                                                       |  • <b>AE-UA</b>: All activity for users                             |
| remote-logon | <b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1021 - Remote Services</b><br> ↳ <b>A-RLA-AA-F</b>: First asset-to-asset communication<br> ↳ <b>A-RLA-AA-A</b>: Abnormal asset-to-asset communication                                                                                                                                                                                                                                    |  • <b>A-RLA-AA</b>: Asset to asset communication (DISABLED)         |