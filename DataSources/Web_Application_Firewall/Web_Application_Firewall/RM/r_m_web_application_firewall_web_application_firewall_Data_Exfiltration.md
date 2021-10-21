Vendor: Web Application Firewall
================================
### Product: [Web Application Firewall](../ds_web_application_firewall_web_application_firewall.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   5    |     4      |      9      |    9    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                                                                                                                                                                                 |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| file-write | <b>T1204 - User Execution</b><br> ↳ <b>FA-TEMP-DIRECTORY-F</b>: First time process has been executed from a temporary directory by this user during file activity<br> ↳ <b>FA-TEMP-DIRECTORY-A</b>: Abnormal process has been executed from a temporary directory by this user during file activity                                                                                                                                                                              |  • <b>FA-UP-TEMP</b>: Process executable TEMP directories for this user during file activity                                                                                                                                                                           |
| vpn-logout | <b>T1030 - Data Transfer Size Limits</b><br> ↳ <b>DLP-BSum</b>: Abnormal amount of data written during DLP policy violation<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>DLP-UPCOUNT</b>: Abnormal number of DLP policy violations for user<br> ↳ <b>DLP-GPCOUNT</b>: Abnormal number of DLP policy violations for peer group<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>VPN-BSum</b>: Abnormal amount of data uploaded during VPN Session |  • <b>DLP-BSum</b>: Sum of bytes written during DLP policy violation<br> • <b>DLP-GPCOUNT</b>: Count of DLP policy violations for peer group<br> • <b>DLP-UPCOUNT</b>: Count of DLP policy violations for user<br> • <b>VPN-BSum</b>: Sum of bytes uploaded during VPN |