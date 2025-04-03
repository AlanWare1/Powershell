# Commandes de base PowerShell

## 📂 Gestion des fichiers et dossiers
| Commande | Description |
|----------|------------|
| `Get-Location` ou `pwd` | Affiche le répertoire courant |
| `Set-Location` ou `cd` | Change de répertoire |
| `Get-ChildItem` ou `ls` | Liste les fichiers et dossiers |
| `New-Item fichier.txt` | Crée un fichier |
| `New-Item -ItemType Directory dossier` | Crée un dossier |
| `Remove-Item fichier.txt` | Supprime un fichier ou dossier |
| `Copy-Item source.txt destination.txt` | Copie un fichier |
| `Move-Item fichier.txt nouveau_dossier\` | Déplace ou renomme un fichier |
| `Clear-Host` | Efface l’écran |

## 🛠 Gestion des processus et services
| Commande | Description |
|----------|------------|
| `Get-Process` | Liste les processus en cours |
| `Stop-Process -Name notepad` | Arrête un processus |
| `Get-Service` | Liste les services système |
| `Start-Service NomService` | Démarre un service |
| `Stop-Service NomService` | Arrête un service |

## 📡 Réseau
| Commande | Description |
|----------|------------|
| `Test-Connection google.com` | Ping un hôte |
| `Get-NetIPAddress` | Affiche l’adresse IP |
| `Get-NetAdapter` | Liste les interfaces réseau |
| `Get-DnsClientServerAddress` | Affiche les DNS configurés |

## 🔐 Gestion des utilisateurs
| Commande | Description |
|----------|------------|
| `Get-LocalUser` | Liste les utilisateurs locaux |
| `New-LocalUser "Nom"` | Crée un utilisateur local |
| `Remove-LocalUser "Nom"` | Supprime un utilisateur |
| `Get-LocalGroup` | Liste les groupes locaux |
| `Add-LocalGroupMember -Group "Administrators" -Member "Nom"` | Ajoute un utilisateur à un groupe |

## 📋 Informations système
| Commande | Description |
|----------|------------|
| `Get-ComputerInfo` | Affiche les infos du PC |
| `Get-Date` | Affiche la date et l’heure |
| `Get-WmiObject Win32_OperatingSystem` | Infos sur l’OS |
