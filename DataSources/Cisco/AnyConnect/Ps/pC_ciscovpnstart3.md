#### Parser Content
```Java
{
Name = cisco-vpn-start-3
  Vendor = Cisco
  Product = AnyConnect
  Lms = Splunk
  DataType = "vpn-login"
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """Connection AnyConnect: The following DAP records were selected for this connection: DfltAccessPolicy"""]
  Fields = [
    """exabeam_host=({host}[\w\-.]{1,2000})""",
    """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
    """\w{1,3}\s{1,2}\d{1,2}\s\d\d:\d\d:\d\d\s({host}[\w.\-]{1,2000})\s%ASA-""",
    """({host}[^\s]{1,2000})\s{1,20}:\s{1,20}%FTD-""",
    """User\s(({user_email}[^@,]{1,2000}@[^,]{1,2000})|({user}[^,]{1,2000}))""",
    """Addr\s({src_ip}\d{1,100}.\d{1,100}.\d{1,100}.\d{1,100})""",
  ]


}
```