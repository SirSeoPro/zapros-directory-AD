#### PowerShell запрос директории устройства в AD
```
Get-adcomputer -filter "name -like 'PC-NAME-HERE'" |select-object -property name, distinguishedname
```

#### PowerShell запрос примененных политик
В формате html, в указанную директорию
```
gpresult /H c:/temp/result.html
```
