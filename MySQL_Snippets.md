## MySQL Snippets

Get orders with order history records for checking remakes. 

```sql 
SELECT oo.OrderNo,
oo.RemakeNo,
oo.TransactionID,
oo.Patient,
oo.CheckInDate, 
oo.CheckInBy,
oo.DispenseBy,
oo.DispenseDate
FROM optimart_ospre.orders oo 
INNER JOIN optimart_ospre.orders_history oh 
ON  oo.Job_ID = oh.JobID
WHERE CheckInDate = '' OR CheckInDate is null 
AND CheckInBy = '' OR CheckInBy is null 
AND  DispenseBy = '' OR DispenseBy is null 
AND  DispenseDate = '' OR DispenseDate is null
AND RemakeNo > 0;
```

