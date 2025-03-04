|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|      [Brute Force Attack](../../../UseCases/uc_brute_force_attack.md)      |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1110 - Brute Force<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Brute_Force_Attack.md)        |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1078 - Valid Accounts<br>T1110 - Brute Force<br>T1133 - External Remote Services<br>    | [<ul><li>26 Rules</li></ul><ul><li>12 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Compromised_Credentials.md) |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1110 - Brute Force<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Data_Access.md)    |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1133 - External Remote Services<br>TA0010 - TA0010<br>    | [<ul><li>4 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Data_Exfiltration.md)         |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1052 - Exfiltration Over Physical Medium<br>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB<br>T1133 - External Remote Services<br>TA0010 - TA0010<br> | [<ul><li>11 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Data_Leak.md)    |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1021 - Remote Services<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting<br>    | [<ul><li>9 Rules</li></ul><ul><li>3 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Lateral_Movement.md)          |
|    [Malware](../../../UseCases/uc_malware.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_fortinet_fortinet_vpn_Malware.md)    |
|    [Phishing](../../../UseCases/uc_phishing.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1566 - Phishing<br>    | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Phishing.md)    |
|       [Physical Security](../../../UseCases/uc_physical_security.md)       |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1133 - External Remote Services<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Physical_Security.md)         |
|         [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)         |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1078 - Valid Accounts<br>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1133 - External Remote Services<br>    | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Privilege_Abuse.md)    |
|    [Privilege Escalation](../../../UseCases/uc_privilege_escalation.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1098.002 - Account Manipulation: Exchange Email Delegate Permissions<br>T1555.005 - T1555.005<br>    | [<ul><li>5 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_fortinet_fortinet_vpn_Privilege_Escalation.md)      |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  authentication-successful<br> ↳[fortinet-auth-successful](Ps/pC_fortinetauthsuccessful.md)<br> ↳[fortinet-0102043039](Ps/pC_fortinet0102043039.md)<br><br> failed-vpn-login<br> ↳[fortinet-ssl-failed-vpn-login](Ps/pC_fortinetsslfailedvpnlogin.md)<br><br> vpn-login<br> ↳[fortinet-ipsec-vpn-start](Ps/pC_fortinetipsecvpnstart.md)<br> ↳[fortinet-ssl-vpn-start-1](Ps/pC_fortinetsslvpnstart1.md)<br> ↳[fortinet-ssl-vpn-start](Ps/pC_fortinetsslvpnstart.md)<br><br> vpn-logout<br> ↳[fortinet-ipsec-vpn-end](Ps/pC_fortinetipsecvpnend.md)<br> ↳[fortinet-ssl-vpn-end-3](Ps/pC_fortinetsslvpnend3.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_fortinet_fortinet_vpn_Ransomware.md)    |