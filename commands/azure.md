# Importar o modulo Azure
```powershell
Import-Module Azure
```
# Adicionar uma conta azure
```powershell
Add-AzureAccount
```
# Ver lista Vms
```powershell
Get-AzureVm
```
# Ver Assinaturas azure
```powershell
Get-AzureSubscription
```
# Remover uma assinatura
```powershell
Remove-AzureSubscription 'Free Trial'
```
# Download arquivo assinatura
```powershell
Get-AzurePublishSettingsFile
```
# Importa o cert 
```powershell
Import-AzurePublishSettingsFile 'Caminho do Cert'
```

# Mapear unidade de rede no storage do azure
```powershell
net use g: \\
```
