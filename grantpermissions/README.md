# Power Automate - Grant Permissions
Get role definitions
```
_api/web/roledefinitions
```

Filter Array From
```
body('getRoles')?['d/results']
```

Filter Array Item
```
item()?['Description']
```

Compose output
```
first(body('role'))?['Id']
```

Set group permission
```
_api/web/lists/getbytitle('LISTNAME')/items(ITEMID)/roleassignments/addroleassignment(principalid='GROUPID', roleDefId=ROLEID)
```
