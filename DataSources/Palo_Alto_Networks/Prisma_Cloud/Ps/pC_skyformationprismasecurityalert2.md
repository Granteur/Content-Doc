#### Parser Content
```Java
{
Name = skyformation-prisma-security-alert-2
 Vendor = Palo Alto Networks
 Product = Prisma Cloud
 Lms = Direct
 DataType = "alert"
 TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
 Conditions = [  """destinationServiceName=""", """"service":"Prisma Cloud"""", """"policy":""", """"policyType":""" ]
 Fields = [
   """exabeam_host=([^=]{1,2000}@\s{0,100})?({host}\S{1,2000})""",
   """({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d.\d{1,100}Z)\s[\w\-.]{1,2000}\s{1,100}Skyformation""",
   """"name":"({alert_name}[^"]{1,2000})","policyTs":"""",
   """"policy":\{[^\}]{1,2000},"name":"({alert_name}[^"]{1,2000})"""",
   """"severity":"({alert_severity}[^"]{1,2000})"""",
   """"alertId":"({alert_id}[^"]{1,2000})"""",
   """"description":"({additional_info}[^"]{1,2000})"""",
   """"service":"({app}[^"]{1,2000})"""",
   """"account":\{[^}]{1,2000},"name":"({user}[^"]{1,2000})"""",
   """"alertRuleName":"({alert_type}[^"]{1,2000})""""
 ]
}
```