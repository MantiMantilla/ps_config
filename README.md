# ps_config

A PowerShell setup guide for a shell experience similar to ZSH on linux.

## Setup

### Default terminal application

Launch the new Windows Terminal and open it's settings tab. Select it as the default terminal application.

### Fonts

Install Caskaydia NerdFonts and change the default font for PowerShell to it.

### Theme

Add the bubbles theme to the `\Themes\` directory next to your PowerShell profile script.

```pwsh
[Environment]::GetFolderPath("MyDocuments") + "MicrosoftPowerShell"
```

To setup a different theme, update the last line of the `Microsoft.PowerShell_profile.ps1` file.

### Profile

You can add a symbolic link to the file in this repo to create or replace the file specified by the `$PROFILE variable`.
