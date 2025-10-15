# PowerShell запрос директории устройства в AD
```
Get-adcomputer -filter "name -like 'PC-NAME-HERE'" |select-object -property name, distinguishedname
```
