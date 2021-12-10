Vendor: Portnox
===============
### Product: [Portnox CLEAR](../ds_portnox_portnox_clear.md)
### Use-Case: [Privilege Escalation](../../../../UseCases/uc_privilege_escalation.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   1   |   0    |     2      |      2      |    2    |

| Event Type     | Rules                                                                                                                                                                                                                                                                                       | Models |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| registry-write | <b>T1112 - Modify Registry</b><br> ↳ <b>enFilterPolicyChange</b>: The LocalAccountTokenFilterPolicy was disabled<br><br><b>T1548.002 - Abuse Elevation Control Mechanism: Bypass User Account Control</b><br> ↳ <b>enFilterPolicyChange</b>: The LocalAccountTokenFilterPolicy was disabled |        |