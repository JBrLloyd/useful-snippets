```sql
sys.Label LIKE ‘%Bus%’
Filters all messages that contains the string “Bus” in the Label of the BrokeredMessage object.
user.Country = ‘Austria’
same as: Country = ‘Austria’
Exists([My Date])
Returns items that have the custom property “My Date”. You need to enclose the property name with square brackets if the property name contains a space.
UserName = ‘armin’
UserName != ‘armin’
sys.Size < 1000
Costs > 500 AND Costs < 5000
myId = 12
sys.ForcePersistence = false
sys.Size < 1000 AND sys.Label LIKE ‘Service%’ and (city = ‘Vienna’ OR city = ‘Graz’)
sys.Size < 100 * sys.SequenceNumber
UserName + Country <> ‘arminAustria’
UserName IS NULL
UserName IS NOT NULL
Tags IN (‘azure’, ‘servicebus’, ‘codehollow’)
```
