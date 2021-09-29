# Settings

Repository contains my configurations and settings for various tools.

Installation of most of the tools require `chocolatey` installed. In order to do that, execute following commands:

## Prerequisites

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

In order to install all packages from `chocolatey` run `choco install chocolatey-packages.config -y`
