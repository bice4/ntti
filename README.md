# HOW TO MAKE YOUR LIFE EASIER

## Install Chocolatey :floppy_disk:

```ps  
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## Useful tools

**Run PowerShell/terminal "as Administrator"** :computer:

- ``choco install notepadplusplus -y`` - NotePad++  
- ``choco install nodejs-lts -y`` - NodeJs  
- ``choco install googlechrome -y`` - Google Chrome  
- ``choco install sql-server-management-studio -y`` - SQL Management studio  
- ``choco install vscode -y`` - VS Code  
- ``choco install 7zip.install -y`` - 7Zip  
- ``choco install dotnet-8.0-sdk -y`` - .NET 8 SDK  
- ``choco install docker-desktop -y`` - Docker desktop  
- ``choco install git -y`` - GIT
- ``choco install winscp`` - WinScp sftp client
- ``winget install -e --id Microsoft.Teams`` - MS Teams
- ``winget install -e --id Postman.Postman`` - Postman
- ``choco install mremoteng -y`` - mRemoteNG

_Cloud:_  

- ``choco install azure-cli -y`` - Azure CLI  
- ``choco install terraform --version 1.9.8 -y `` - Terraform  
- ``choco install kubernetes-helm -y`` - Helm  
- ``choco install python312 -y`` - Python  
- ``winget install --id Microsoft.PowerShell --source winget`` - PowerShell 7+

_Optional:_

- ``choco install cmder -y`` - Cmder  
- ``choco install ueli -y`` - Ueli  
- ``choco install ffmpeg -y`` - FFmpeg  
- ``choco install zoom -y`` - Zoom client  
- ``choco install sourcetree -y`` - SourceTree :poop:
- ``winget install -e --id Microsoft.OpenSSH.Beta`` - OpenSSH
- ``choco install ngrok -y`` - Ngrok
- ``choco install httpie-desktop`` - Postman analog
