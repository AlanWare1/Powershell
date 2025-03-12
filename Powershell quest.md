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
