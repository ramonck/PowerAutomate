# Power Automate - Get Sharepoint Site Users
Send HTTP Request, API code
```
_api/web/siteusers
```

Get array structure from within the API response
```
body('getUsers')?['d/results']
```

Get the value from each item.
```
item()?['UserPrincipalName']
```
