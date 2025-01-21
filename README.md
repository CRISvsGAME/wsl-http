# WSL HTTP

## Config

### config.ps1

```powershell
# Firewall Rule Variables
$Env:Name = "Allow_Inbound_HTTP"
$Env:DisplayName = "Allow Inbound HTTP"
$Env:Action = "Allow"
$Env:Direction = "Inbound"
$Env:Enabled = "True"
$Env:LocalPort = "80"
$Env:Protocol = "TCP"
```

## Create

### PowerShell

```powershell
powershell -ExecutionPolicy Bypass -File "create.ps1"
```
