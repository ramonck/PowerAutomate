# Power Automate - Get versions
Get previous versions of either list or library items:
```
_api/web/lists/getByTitle('LIST/LIBRARYNAME')/items(ID)/versions
```
Get the previous version Status field
```
body('getVersions')?['d/results']?[1]?['Status']
```
