# Powershell terminal

In order to configure terminal, complete following steps:

1. Install following packages via `chocolatey`:

```powershell
choco install microsoft-windows-terminal -y
choco install cascadiacode -y
choco install cascadiacodepl -y
choco install starship -y
choco install zoxide -y
choco install fzf -y
```

1. Replace following configs content with the provided in this directory:

`Windows Terminal` - 'C:\Users\<Username>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json'
`PowerShell` profile - `$PROFILE`
`starship` - '$HOME\.config\starship.toml' or specify a new path: `$ENV:STARSHIP_CONFIG = "<new\path\starship-config.toml>"`
