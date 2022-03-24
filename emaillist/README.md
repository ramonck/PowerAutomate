# Power Automate - Email List - Bulk Email

Code to cleanup the Select Json into a clean email format for sending email.

```
replace(replace(replace(replace(replace(string(body('Select')),'{"email":"',''),',',''),'[',''),']',''),'"}',';')
```
