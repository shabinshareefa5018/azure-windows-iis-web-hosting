# PowerShell Commands

## Install IIS

```powershell
Install-WindowsFeature -Name Web-Server -IncludeManagementTools
```

## Navigate to IIS Folder

```powershell
cd C:\inetpub\wwwroot
```

## Remove Default Page

```powershell
Remove-Item iisstart.htm
```

## Create New HTML File

```powershell
notepad index.html
```

## Check IIS Service

```powershell
Get-Service W3SVC
```

## Start IIS Service

```powershell
Start-Service W3SVC
```
