#### Parser Content
```Java
{
Name = netskope-web-activity
    Vendor = Netskope
    Product = Security Cloud
    Lms = Direct
    DataType = "web-activity"
    TimeFormat = "yyyy-MM-dd HH:mm:ss"
    Conditions = [ """ http_transaction """ ]
    Fields = [
      """exabeam_host=([^=]{1,2000}@\s{0,100})?({host}\S+)""",
      """({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
      """\d\d:\d\d:\d\d\s{1,100}(?:-|\d{1,100}\s{1,100}){4}(?:-|({dest_ip}[^\s]{1,2000}))\s{1,100}(?:-|({src_ip}[^\s]{1,2000}))\s{1,100}(?:-|"{0,20}({user_email}[^"]{1,2000})"{0,20})\s{1,100}(?:-|({method}[^\s]{1,2000}))\s{1,100}(?:-|({protocol}[^\s]{1,2000}))\s{1,100}(?:-|({uri_query}[^\s]{1,2000}))\s{1,100}(?:-|"{0,20}({user_agent}[^"]{1,2000})"{0,20})\s{1,100}(?:-|"{0,20}({category}[^"]{1,2000})"{0,20})\s{1,100}(?:-|({result_code}\d{1,100}))\s{1,100}(?:-|"{0,20}({mime}[^"]{1,2000})"{0,20})\s{1,100}(?:-|({web_domain}[^\s]{1,2000}))\s{1,100}(?:-|([^\s]{1,2000}))\s{1,100}(?:-|({uri_path}[^\s]{1,2000}))\s{1,100}(?:-|\d{1,100})\s{1,100}(?:-|({full_url}[^\s]{1,2000}))\s{1,100}(?:-|\d{1,100})\s{1,100}(?:-|"{0,20}([^"]{1,2000})"{0,20})\s{1,100}(?:-|"{0,20}({app}[^"]{1,2000})"{0,20})\s{1,100}(?:-|"{0,20}({country_code}[^"]{1,2000})"{0,20})\s{1,100}(?:-|({latitude}[^\s]{1,2000}))\s{1,100}(?:-|({longitude}[^\s]{1,2000}))\s{1,100}(?:-|"{0,20}({location_city}[^"]{1,2000})"{0,20})\s{1,100}(?:-|"{0,20}({location_state}[^"]{1,2000})"{0,20})\s{1,100}(?:N\/A|-|\d{1,100})\s{1,100}(?:-|"{0,20}({country}[^"]{1,2000})"{0,20})""",
      """(?:-|"({additional_info}[^"]{1,2000})")\s{1,100}http_transaction"""
    ]
  

}
```