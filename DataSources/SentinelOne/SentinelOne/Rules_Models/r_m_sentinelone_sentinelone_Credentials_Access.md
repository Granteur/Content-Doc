Vendor: SentinelOne
===================
### Product: [SentinelOne](../ds_sentinelone_sentinelone.md)
### Use-Case: [Credentials Access](../../../../UseCases/uc_credentials_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   0    |     1      |     14      |   14    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                         | Models |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| process-created | <b>T1003 - OS Credential Dumping</b><br> ↳ <b>A-PC-Rundll-LsassDump</b>: Rundll32 was run with minidump via commandline on this asset.<br> ↳ <b>A-PC-Procdump-LsassDump</b>: Procdump was executed with lsass dump command line parameters on this asset.<br> ↳ <b>PC-Rundll-LsassDump</b>: Rundll32 was run with minidump via commandline<br> ↳ <b>PC-Procdump-LsassDump</b>: Procdump was executed with lsass dump command line parameters. |        |