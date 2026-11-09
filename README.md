# hp's maker — ReadyMaker restoration client
<img width="1026" height="800" alt="20261109-2052-08 2379627" src="https://github.com/user-attachments/assets/183ebb99-c357-4fde-8ccf-8280faea37b8" />

An independent restoration and modernization of the ReadyMaker client by ready.io. The original layout is preserved while the client uses the hp's maker service configuration.

This repository contains the complete hp's maker client runtime. It does not include the server or moderator application, and it is not affiliated with or endorsed by ready.io.

## Install

Download the repository files, keep the folder structure intact, and launch `hp's maker.exe` on Windows. Git LFS must be enabled when cloning because Unity runtime assets are included.

The previous client ZIP is also available in the repository for users who prefer a packaged download.

The local `log.txt` file is intentionally not published because it contains machine-specific HWID and diagnostic data.

For an installer, use an authorized ReadyMaker installation:

```powershell
.\Install-HpMaker.ps1 -SourcePath "G:\ReadyMaker"
```

Or run `hp-maker-installer.exe`. A release ZIP may also be installed with:

```powershell
.\Install-HpMaker.ps1 -PackageUrl "https://github.com/OWNER/REPOSITORY/releases/download/v1.2/hps-maker-client.zip"
```

The installer places the client in `%LOCALAPPDATA%\hp's maker` by default.

## Legal and privacy

Feel free to make your own version/modifications, as this is **OPEN SOURCE!!**
We do **NOT** distribute your GMail, your login credentials, or HWID.
Violation of the rules of hp's maker will result in a ban. Any attempt to bypass a ban will result in you getting permanently Hardware-ID **[hwid]** banned.
With love from <3 hpcomputers
**OPEN SOURCE IS LOVE!**
