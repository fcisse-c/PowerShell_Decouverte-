# PowerShell_Decouverte

## Liste des commandes Unix et leurs équivalents PowerShell

| Commande Unix | Commande PowerShell |
|----------------|---------------------|
| `cp`           | `Copy-Item`         |
| `rm`           | `Remove-Item`       |
| `cd`           | `Set-Location`      |
| `mkdir`        | `New-Item -ItemType Directory` |
| `man`          | `Get-Help`          |
| `history`      | `Get-History`       |
| `alias`        | `Set-Alias`         |
| `cat`          | `Get-Content`       |

---

## Commandes PowerShell utilisées :

1. `cp` (copy) :
   ```powershell
   Get-Command *copy*
   
2. rm (remove) :
   ```powershell
   Get-Command *remove*

3. cd (change directory) :
    ```powershell
    Get-Command *location*

4. mkdir (make directory) :
    ```powershell
   Get-Command *item* | where { $_.CommandType -eq "Cmdlet" }
    
5. man (manual) :
    ```powershell
   Get-Help *

6. history (history) :
     ```powershell
     Get-Command *history*

7. Recherche pour alias :
   ```powershell
   Get-Command *alias*

8.cat (concatenate) :
```powershell
Get-Command *content*



   
