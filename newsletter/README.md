# Power Automate - Send Newsletter

```
replace(replace(replace(replace(replace(string(body('Select')),'{"email":"',''),',',''),'[',''),']',''),'"}',';')
```
