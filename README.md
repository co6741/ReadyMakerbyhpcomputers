# hp's maker — ReadyMaker restoration client

An independent restoration and modernization of the ReadyMaker client by ready.io. The original layout is preserved while the client uses the hp's maker service configuration.

This repository/release contains only the client installer. It does not include the server or moderator application, and it is not affiliated with or endorsed by ready.io.

## Install

Use the Windows installer with an authorized ReadyMaker installation:

```powershell
.\Install-HpMaker.ps1 -SourcePath "G:\ReadyMaker"
```

Or run `hp-maker-installer.exe`. A release ZIP may also be installed with:

```powershell
.\Install-HpMaker.ps1 -PackageUrl "https://github.com/OWNER/REPOSITORY/releases/download/v1.2/hps-maker-client.zip"
```

The installer places the client in `%LOCALAPPDATA%\hp's maker` by default.

## Legal and privacy

Only distribute ReadyMaker files when you own them or have permission from their copyright holder. Do not commit OAuth secrets, moderator tokens, or private account data.
