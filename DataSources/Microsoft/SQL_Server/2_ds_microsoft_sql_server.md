|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|         [Data Access](../../../UseCases/uc_data_access.md)         |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Data_Access.md)         |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Evasion.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Malware.md)    |
|     [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)     |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Privilege_Abuse.md)     |
| [Privileged Activity](../../../UseCases/uc_privileged_activity.md) |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Privileged_Activity.md) |
|          [Ransomware](../../../UseCases/uc_ransomware.md)          |  database-access<br> ↳[cef-mssql-database-access](Ps/pC_cefmssqldatabaseaccess.md)<br><br> database-activity-failed<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> database-delete<br> ↳[cef-microsoft-database-delete](Ps/pC_cefmicrosoftdatabasedelete.md)<br><br> database-failed-login<br> ↳[cef-microsoft-database-failed-login](Ps/pC_cefmicrosoftdatabasefailedlogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[mssql-database-login-1](Ps/pC_mssqldatabaselogin1.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-login<br> ↳[s-database-login-18454](Ps/pC_sdatabaselogin18454.md)<br> ↳[s-database-login-18453](Ps/pC_sdatabaselogin18453.md)<br> ↳[cef-syslog-microsoft-db-login](Ps/pC_cefsyslogmicrosoftdblogin.md)<br> ↳[cef-syslog-microsoft-db-impersonate](Ps/pC_cefsyslogmicrosoftdbimpersonate.md)<br> ↳[mssql-database-login](Ps/pC_mssqldatabaselogin.md)<br> ↳[cef-microsoft-database-login](Ps/pC_cefmicrosoftdatabaselogin.md)<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[xml-mssql-database-login-1](Ps/pC_xmlmssqldatabaselogin1.md)<br> ↳[cef-mssql-database-login](Ps/pC_cefmssqldatabaselogin.md)<br> ↳[s-microsoft-database-login](Ps/pC_smicrosoftdatabaselogin.md)<br><br> database-query<br> ↳[xml-mssql-database-login](Ps/pC_xmlmssqldatabaselogin.md)<br> ↳[mssql-database-query-3](Ps/pC_mssqldatabasequery3.md)<br> ↳[mssql-database-query-2](Ps/pC_mssqldatabasequery2.md)<br><br> failed-app-login<br> ↳[s-failed-app-login](Ps/pC_sfailedapplogin.md)<br> ↳[exalms-sqlserver-failed-login](Ps/pC_exalmssqlserverfailedlogin.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_sql_server_Ransomware.md)          |