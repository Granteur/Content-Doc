Vendor: Microsoft
=================
### Product: [Windows](../ds_microsoft_windows.md)
### Use-Case: [Data Leak](../../../../UseCases/uc_data_leak.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   9    |     3      |     58      |   58    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Models                                                                                                                                                                                                                                                                                                                                             |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| usb-insert | <b>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB</b><br> ↳ <b>UW-UHD-011</b>: First USB activity event for user. The asset and the USB device (if present) have been seen in other USB events<br> ↳ <b>UW-UHD-110</b>: First USB activity event for USB device. The user and the asset have been seen in other USB events<br> ↳ <b>UW-UH-F</b>: First asset for user in USB event<br> ↳ <b>UW-UH-A</b>: Abnormal asset for user in USB event<br> ↳ <b>UW-UD-A</b>: Abnormal USB device for user<br> ↳ <b>UW-DH-A</b>: Abnormal asset for USB device                                                                           |  • <b>UW-DH</b>: Hosts that were used with USB Device<br> • <b>UW-UD</b>: USB Devices per User<br> • <b>UW-UH</b>: Hosts used with USB Device per User                                                                                                                                                                                             |
| vpn-logout | <b>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB</b><br> ↳ <b>UW-BSum</b>: Abnormal amount of data written to USB<br><br><b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>EM-FNum</b>: Abnormal number of outgoing emails<br> ↳ <b>EM-DNum</b>: Abnormal number of outgoing email domains<br> ↳ <b>EM-BSum-personal</b>: Abnormal size of outgoing emails to personal account<br> ↳ <b>EM-BSum</b>: Abnormal size of outgoing emails<br><br><b>T1052 - Exfiltration Over Physical Medium</b><br> ↳ <b>PR-BSum</b>: Abnormal size of print objects |  • <b>UW-BSum</b>: Sum of bytes written to USB<br> • <b>EM-BSum</b>: Sum of bytes in outgoing emails<br> • <b>EM-BSum-personal</b>: Sum of bytes in outgoing emails to personal domains<br> • <b>EM-DNum</b>: Number of distinct domains<br> • <b>EM-FNum</b>: Count of outgoing emails<br> • <b>PR-BSum</b>: Sum of bytes of data printed by user |