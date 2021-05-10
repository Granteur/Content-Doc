#### Parser Content
```Java
{
Name = digital-guardian-send-mail
  Product = Digital Guardian Network DLP
  DataType = "dlp-alert"
  Conditions = [ """ Agent_Local_Time="""", """ User_Name="""", """ Operation="28"""" ]
  Fields = ${DGParserTemplates.digital-guardian-activity.Fields}[
    """Email_Sender="({sender}[^@]+@[^.]+\.[^"]+)"""",
    """Email_Subject="({subject}[^"]+?)\s*"""",
    """Email_Recipient="({recipient}[^"]+)""""
  ]
}
digital-guardian-activity = {
  Vendor = Digital Guardian
  Product = Digital Guardian
  Lms = Splunk
  DataType = "file-operations"
  TimeFormat = "MM/dd/yyyy HH:mm:ss a"
  Fields = [
    """Agent_Local_Time="({time}\d+\/\d+\/\d\d\d\d\s\d+:\d+:\d+\s(AM|PM|am|pm))""",
    """\w+\s\d\d\s\d\d:\d\d:\d\d\s*({host}[\w\-.]+)\s\w+=""",
    """\sComputer_Name="(({domain}[^\\]+)?\\?({src_host}[^"]+))""",
    """\sUser_Name="(({domain}[^\\]+)?\\?({user}[^"]+))""",
    """\sSource_Directory="({src_file_dir}[^=]+?)\s*"\s*\w+=""",
    """\sDestination_Directory="({file_parent}[^=]+?)\s*"\s*\w+=""",
    """\sDestination_File="({file_name}[^=]+?)\s*"\s*\w+=""",
    """\sOperation="({event_code}\d+)""",
    """\sApplication="({process_name}[^"]+)""",
    """\sSource_File="({src_file_name}[^=]+?)\s*"\s*\w+=""",
  ]

```