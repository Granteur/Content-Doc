#### Parser Content
```Java
{
Name = checkpoint-dlp-email-alert
  DataType = "dlp-email-alert"
  IsHVF = false
  Conditions = [ """product:"VPN-1 & FireWall-1"""", """email_recipients_num:"""", """from:"""" ]
  Fields = ${CheckpointParserTemplates.checkpoint-firewall-1.Fields}[
    """\Wemail_recipients_num:"({num_recipients}\d{1,100})""",
    """\Wfrom:"({sender}[^"\s]{1,2000})""",
  ]
  DupFields = [ "action->event_name" ]

checkpoint-firewall-1 = {
  Vendor = Check Point 
  Product = NGFW
  Lms = Direct
  DataType = "network-connection"
  IsHVF = true
  TimeFormat = "epoch_sec"
  Fields = [
    """exabeam_host=([^=]{1,2000}@\s{0,100})?({host}\S+)""",
    """ time:"({time}\d{1,100})""",
    """\W({host}[\w\-.]{1,2000}) CheckPoint""",
    """ src:"({src_ip}[A-Fa-f:\d.]{1,2000})""",
    """\Wxlatesrc:"({src_translated_ip}[A-Fa-f:\d.]{1,2000})""",
    """ dst:"(0\.0\.0\.0|({dest_ip}[A-Fa-f:\d.]{1,2000}))""",
    """\Wdst:"({dest_translated_ip}[A-Fa-f:\d.]{1,2000})""",
    """ xlatedst:"(0\.0\.0\.0|({dest_ip}[A-Fa-f:\d.]{1,2000}))""",
    """\Wdst:"({dest_ip}[A-Fa-f:\d.]{1,2000})""",
    """ xlatedst:"({dest_translated_ip}0\.0\.0\.0)""",
    """ service_id:"({app_protocol}[^"]{1,2000})""",
    """\Waction:"({action}[^"]{1,2000})""",
    """\Wrule:"({rule}[^"]{1,2000}?)\s{0,100}"""",
    """ rule_name:"({rule}[^"]{1,2000}?)\s{0,100}"""",
    """\Wapp_rule_name:"({rule}[^"]{1,2000}?)\s{0,100}"""",
    """ s_port:"({src_port}\d{1,100})""",
    """\Wxlatesport:"({src_translated_port}\d{1,100})""",
    """\Wxlatedport:"({dest_translated_port}\d{1,100})""",
    """ ifdir:"({direction}[^"]{1,2000})""",
    """ origin:"({origin_ip}[A-Fa-f:\d.]{1,2000})""",
    """ origin_?sic_?name:"CN=({origin_name}[^",]{1,2000})""",
    """product:"({product_name}[^"]{1,2000})""",
    #slow (15ms -> 8ms)"""\W__policy_id_tag:"({product_name}[^"\[\{]{1,2000}).+?product:"Log Update"""",
    #slow (15ms -> 8ms)"""product:"Log Update".+?__policy_id_tag:"({product_name}[^"\[\{]{1,2000})""",
    """ service:"({dest_port}\d{1,100})""",
    """ proto:"({protocol}[^"]{1,2000})""",
    """\Wpeer_gateway:"({src_translated_ip}[A-Fa-f:\d.]{1,2000})""",
    """ rule_uid:"\{?({rule_id}[^"\}]{1,2000})""",
    """\Wapp_rule_id:"\{({rule_id}[^"\}]{1,2000})""",
    """\Wsrc_machine_name:"({src_host}[^"]{1,2000}?)\s{0,100}"""",
    """\Wsrc_machine_name:"({src_host}[^"@]{1,2000})@({domain}[^"]{1,2000})""",
    """\Wdst_machine_name:"({dest_host}[^"]{1,2000}?)\s{0,100}"""",
    """\Wdst_machine_name:"({dest_host}[^"@]{1,2000})@({domain}[^"]{1,2000})""",
    """\Wuser:"({user}[^"\(\)@]{1,2000}?)\s{0,100}"""",
    """\Wuser:"({user_email}[^\(\)"@]{1,2000}@[^\(\)"@]{1,2000})\s{0,100}"""",
    """\Wsrc_user_name:"(({user}[^"\(\)@]{1,2000}?)|({user_email}[^"@\(\)]{1,2000}@[\(\)^"@]{1,2000}))\s{0,100}"""",
    """\Wdst_user_name:"(({user}[^"\(\)@]{1,2000}?)|({user_email}[^"@]{1,2000}@[^"@]{1,2000}))\s{0,100}"""",
    """\Wuser:"({user_lastname}[^,"]{1,2000}),\s{0,100}({user_firstname}[\w\s]{1,2000}\S)\s{0,100}\(({account}[^"]{1,2000}?)\)""",
    """\Wuser:"({user_firstname}[\w\s]{1,2000}[^\s,\(])\s{1,100}({user_lastname}[^\s,\(]{1,2000})\s{0,100}\(({account}[^"]{1,2000}?)\)""",
    """\Wuser:"({user_lastname}[^,"\(]{1,2000}),\s{0,100}({user_firstname}[\w\s]{1,2000}\S)\s{0,100}\([^\)]{1,2000}?\)[^"]{1,2000}?\(({user}[^"@\)]{1,2000}?)(@({domain}[^"\)]{1,2000}?))?\)"""
    """\Wuser:"({user_firstname}[\w\s]{1,2000}[^\s,\(])\s{1,100}({user_lastname}[^\s,\(]{1,2000})\s{0,100}\([^\)]{1,2000}?\)[^"]{1,2000}?\(({user}[^"@\)]{1,2000}?)(@({domain}[^"\)]{1,2000}?))?\)"""
    """\Wreceived_bytes:"({bytes_in}\d{1,100})""",
    """\Wsent_bytes:"({bytes_out}\d{1,100})""",
    """\Wifname:"({interface_name}[^"]{1,2000})""",
    """\W(user|src_user_name|dst_user_name):"(?:[^_"\s]{1,2000}_)?({user}[^"\s]{1,2000}?)\s{0,100}""""
  ]
  DupFields = [ "action->outcome" 
}
```