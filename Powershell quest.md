|__Commande Linux__| __Commande Powershell__|
|------------------|------------------------|
|cp| Copy-Item -Path "C:\Users\AlanWild\Documents\Quest\Cloud" -Destination "C:\Users\AlanWild\Desktop"|
|rm| Remove-Item -Path "C:\Users\AlanWild\Desktop\Cloud"|
|cd| PS C:\Users\AlanWild\Documents> cd..|
|mkdir|New-Item -Path "C:\Users\AlanWild\Documents" -Name "Quest" -ItemType "Directory"|
|man| PS C:\Windows\system32> Get-Help -Category Cmdlet|
|history| PS C:\Windows\system32> Get-History|
|alias|PS C:\Windows\system32> Get-Alias|
|cat| PS C:\Windows\system32> Get-Content C:\Users\AlanWild\Documents\Quest\Cloud|
|   |                                       Ceci est un essai|



New-Item -Path "C:\Users\AlanWild\Documents" -Name "Quest" -ItemType "Folder"
New-Item -Path "C:\Users\AlanWild\Documents" -Name "Quest" -ItemType "Directory"
New-Item -Path "C:\Users\AlanWild\Documents\Quest" -Name "Cloud" -ItemType "File"
PS C:\Users\AlanWild> cd .\Documents

PS C:\Users\AlanWild\Documents> cd..

PS C:\Users\AlanWild> cd .\Documents\Quest

PS C:\Users\AlanWild\Documents\Quest>
Copy-Item -Path "C:\Users\AlanWild\Documents\Quest\Cloud" -Destination "C:\Users\AlanWild\Desktop"
Remove-File -Path "C:\Users\AlanWild\Desktop\Cloud"
Remove-Item -Path "C:\Users\AlanWild\Desktop\Cloud"
Get-Help cat
Get-Content C:\Users\AlanWild\Documents
PS C:\Windows\system32> history

PS C:\Windows\system32> Get-History

  Id CommandLine                                                                     
  -- -----------                                                                     
   1 history   

PS C:\Windows\system32> Get-Alias Path
Get-Alias : Cette commande ne trouve pas d’alias correspondant, car l’alias avec 
name «Path» n’existe pas.

PS C:\Windows\system32> Get-Alias Mkdir
Get-Alias : Cette commande ne trouve pas d’alias correspondant, car l’alias avec 
name «Mkdir» n’existe pas.

PS C:\Windows\system32> Get-Alias
  
CommandType     Name                                               Version    Source 
-----------     ----                                               -------    ------ 
Alias           % -> ForEach-Object                                                  
Alias           ? -> Where-Object                                                    
Alias           ac -> Add-Content                                                    
Alias           asnp -> Add-PSSnapin                                                 
Alias           cat -> Get-Content    

PS C:\Windows\system32> Get-Content C:\Users\AlanWild\Documents\Quest\Cloud

PS C:\Windows\system32> Set-Content C:\Users\AlanWild\Documents\Quest\Cloud -Value "Ceci est un essai"

PS C:\Windows\system32> Get-Content C:\Users\AlanWild\Documents\Quest\Cloud
Ceci est un essai

PS C:\Windows\system32> Get-Help -Category Cmdlet
