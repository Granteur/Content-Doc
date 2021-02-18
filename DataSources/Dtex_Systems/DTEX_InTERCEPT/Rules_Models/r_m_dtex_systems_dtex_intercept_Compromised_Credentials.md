Vendor: Dtex Systems
====================
### Product: [DTEX InTERCEPT](../ds_dtex_systems_dtex_intercept.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  59   |   14   |     17     |      9      |    9    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Models                                                                                                                                                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| file-write           | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group                                                                                                                                                                        |
| local-logon          | <b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>AS-PV-UHWoPC</b>: Access to Password Vault managed asset with no password checkout for user<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>NEW-USER-F</b>: User with no event history<br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1078.003 - Valid Accounts: Local Accounts</b><br> ↳ <b>LL-GH-A-new</b>: Abnormal local logon to asset for group by new user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>LL-GH</b>: Local logon hosts (peer groups)<br> • <b>AS-PV-OA</b>: Password retrieval based accounts<br> • <b>AE-UA</b>: All activity for users                                                                                                                                                |
| process-created      | <b>T1047 - Windows Management Instrumentation</b><b>T1098 - Account Manipulation</b><br> ↳ <b>EXE-RENAME-ORG-F</b>: First time WMIC.exe has been used to rename a user account by this user.<br> ↳ <b>RENAME-GRP-ORG-F</b>: First time WMIC.exe has been used to rename a group by this user.<br> ↳ <b>EXE-RENAME-ORG-A</b>: Abnormal usage of WMIC.exe to rename a group by this user.<br><br><b>T1098 - Account Manipulation</b><b>T1531 - Account Access Removal</b><br> ↳ <b>EXE-DELETE-ORG-F</b>: First time net.exe has been used to delete a user account by this user.<br> ↳ <b>EXE-DELETE-ORG-A</b>: Abnormal usage of net.exe to delete a user account by this user.<br><br><b>T1078 - Valid Accounts</b><b>T1098 - Account Manipulation</b><br> ↳ <b>EXE-ACTIVE-ORG-F</b>: First time net.exe has been used to disable/enable a user account by this user.<br> ↳ <b>EXE-ACTIVE-ORG-A</b>: Abnormal usage of net.exe to disable/enable a user account by this user.<br><br><b>T1078 - Valid Accounts</b><b>T1098 - Account Manipulation</b><b>T1136 - Create Account</b><br> ↳ <b>ADD-GRP-ORG-F</b>: First time net.exe has been used to create/add to a group by this user.<br> ↳ <b>ADD-GRP-ORG-A</b>: Abnormal usage of net.exe to create/add to a group by this user.<br><br><b>T1136.001 - Create Account: Create: Local Account</b><br> ↳ <b>EXE-ADD-ORG-F</b>: First time net.exe has been used to create a user account by this user.<br> ↳ <b>EXE-ADD-ORG-A</b>: Abnormal usage of net.exe to create a user account by this user.<br><br><b>T1047 - Windows Management Instrumentation</b><b>T1175 - T1175</b><br> ↳ <b>A-Impacket-Lateral-Detection</b>: Activity related to Impacket framework using wmiexec, dcomexe, or smbexec processes via command line have been found on this asset.<br> ↳ <b>Impacket-Lateral-Detection</b>: Activity related to Impacket framework using wmiexec, dcomexe, or smbexec processes via command line have been found.<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>Mimikatz-process</b>: A highly dangerous attacker tool, Mimikatz, has been used<br><br><b>T1059.001 - Command and Scripting Interperter: PowerShell</b><br> ↳ <b>A-ALERT-COMPROMISED-POWERSHELL</b>: Powershell and security alerts                                                                                                                                                                                                                                                                                                                                                                                            |  • <b>WMIC-EXE-RENAME-ORG</b>: Using WMIC.exe to rename a user account<br> • <b>NET-EXE-DELETE-ORG</b>: Using net.exe to delete a user account<br> • <b>NET-EXE-ACTIVE-ORG</b>: Using net.exe to disable/enable a user account<br> • <b>NET-EXE-ADD-ORG</b>: Using net.exe to add a user account    |
| remote-logon         | <b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>AS-PV-UHWoPC</b>: Access to Password Vault managed asset with no password checkout for user<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>NEW-USER-F</b>: User with no event history<br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-A</b>: Abnormal activity from country for user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>A-KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for asset<br> ↳ <b>A-KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining the kerberos TGTs using non kerberos service for this asset<br> ↳ <b>KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining kerberos TGTs using non kerberos service<br> ↳ <b>KL-OEt-F</b>: First kerberos ticket encryption type for organization<br> ↳ <b>KL-OEt-A</b>: Abnormal kerberos ticket encryption type for organization<br> ↳ <b>KL-OTo-F</b>: First kerberos ticket options for organization<br> ↳ <b>KL-OTo-A</b>: Abnormal kerberos ticket options for organization<br> ↳ <b>KL-UTo-F</b>: First kerberos ticket options for user<br> ↳ <b>KL-UTo-A</b>: Abnormal kerberos ticket options for user<br> ↳ <b>KL-UToE-F</b>: First kerberos ticket options and encryption type combination for user<br> ↳ <b>KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for user<br> ↳ <b>KL-USn-A</b>: Abnormal service to obtain TGTs for user<br><br><b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br><br><b>T1550.002 - Use Alternate Authentication Material: Pass the Hash</b><br> ↳ <b>A-PTH-ALERT-sH</b>: Possible pass the hash attack from this source host<br> ↳ <b>PTH-ALERT-sH</b>: Possible pass the hash attack from the source<br> ↳ <b>NTLM-mismatch</b>: <br><br><b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user |  • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer group<br> • <b>UA-UC</b>: Countries for user<br> • <b>AS-PV-OA</b>: Password retrieval based accounts<br> • <b>AE-NTLM</b>: Models ntlm hostnames in the organization<br> • <b>AE-UA</b>: All activity for users |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-GUa-OS-F</b>: First web activity using this operating system for the peer group<br> ↳ <b>WEB-OUa-OS-F</b>: First web activity using this operating system for the organization<br> ↳ <b>WEB-UUa-MobileBrowser-F</b>: First activity using this mobile web browser/app for this user to a new domain<br> ↳ <b>WEB-OsUa-MobileBrowser-F</b>: First activity using this mobile web browser for this mobile operating system<br> ↳ <b>WEB-UUa-Browser-F</b>: First activity using this web browser for this user to a new domain<br> ↳ <b>WEB-GUa-Browser-F</b>: First activity using this web browser for the peer group<br> ↳ <b>WEB-OUa-Browser-F</b>: First activity using this web browser for the organization<br> ↳ <b>WEB-UU-Reputation</b>: User attempted access to a url with bad reputation<br> ↳ <b>WEB-UD-ALERT-F</b>: First security alert accessing this malicious domain for user<br> ↳ <b>WEB-UD-ALERT-A</b>: Abnormal security alert accessing this malicious domain for user<br> ↳ <b>WEB-UD-ALERT-N</b>: Common security alert on this malicious domain for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |  • <b>WEB-UD-ALERT</b>: Top malicious web domain accessed by the user                                                                                                                                                                                                                               |