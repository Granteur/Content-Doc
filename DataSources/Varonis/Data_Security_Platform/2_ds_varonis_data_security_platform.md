|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|      [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)      |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1003 - OS Credential Dumping<br>    | [<ul><li>4 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_varonis_data_security_platform_Brute_Force_Attack.md)        |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1003.003 - T1003.003<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>16 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_varonis_data_security_platform_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1110 - Brute Force<br>    | [<ul><li>8 Rules</li></ul><ul><li>8 Models</li></ul>](RM/r_m_varonis_data_security_platform_Data_Access.md)    |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1204 - User Execution<br>    | [<ul><li>17 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_varonis_data_security_platform_Data_Exfiltration.md)       |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1204 - User Execution<br> | [<ul><li>21 Rules</li></ul><ul><li>15 Models</li></ul>](RM/r_m_varonis_data_security_platform_Data_Leak.md)    |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_varonis_data_security_platform_Evasion.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_varonis_data_security_platform_Lateral_Movement.md)          |
|    [Malware](../../../UseCases/uc_malware.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1003.002 - T1003.002<br>T1027 - Obfuscated Files or Information<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>T1218.011 - Signed Binary Proxy Execution: Rundll32<br>    | [<ul><li>9 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_varonis_data_security_platform_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1566 - Phishing<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_varonis_data_security_platform_Phishing.md)    |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_varonis_data_security_platform_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1003 - OS Credential Dumping<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>    | [<ul><li>5 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_varonis_data_security_platform_Privilege_Escalation.md)      |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_varonis_data_security_platform_Privileged_Activity.md)       |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  authentication-failed<br> ↳[openvpn-auth-failed](Ps/pC_openvpnauthfailed.md)<br><br> authentication-successful<br> ↳[openvpn-auth-successful](Ps/pC_openvpnauthsuccessful.md)<br><br> dlp-alert<br> ↳[varonis-dlp-alert-1](Ps/pC_varonisdlpalert1.md)<br> ↳[varonis-dlp-alert](Ps/pC_varonisdlpalert.md)<br><br> file-delete<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-permission-change<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br><br> file-read<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> file-write<br> ↳[q-varonis-file-activity](Ps/pC_qvaronisfileactivity.md)<br> ↳[varonis-file-activity](Ps/pC_varonisfileactivity.md)<br><br> vpn-login<br> ↳[openvpn-vpn-login-1](Ps/pC_openvpnvpnlogin1.md)<br><br> vpn-logout<br> ↳[openvpn-vpn-end](Ps/pC_openvpnvpnend.md)<br> ↳[openvpn-vpn-end-1](Ps/pC_openvpnvpnend1.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_varonis_data_security_platform_Ransomware.md)    |