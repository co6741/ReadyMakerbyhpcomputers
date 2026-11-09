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
.\Install-HpMaker.ps1 -PackageUrl "https://github.com/co6741/readymakerbyhpcomputers/releases/download/v1.2/hps-maker-client.zip"
```

The installer places the client in `%LOCALAPPDATA%\hp's maker` by default.

## Legal and privacy

Feel free to make your own version/modifications, as this is **OPEN SOURCE!!**
Links to the web-pages that hp's maker uses for edit, help, learn, and more!
https://hp-maker-server.compep211.workers.dev/redirect/learn - **Basic learn about hp's maker**   
https://hp-maker-server.compep211.workers.dev/integrations - **Intergrations [was not in original Ready Maker, still a WIP!!]**
https://hp-maker-server.compep211.workers.dev/account - **Account Configuration**
https://hp-maker-server.compep211.workers.dev/home - **_Main home page of hp's maker. Replaced all dead links in original ReadyMaker, works with these worker links._**   
_______________________________________________________________________________
**Privacy
hp's maker stores only the account and project data needed to provide the app.
We do **NOT** distribute your GMail, your login credentials, or HWID.**
_______________________________________________________________________________
Email compep222@gmail.com for inquiries.
If you feel you have been falsely banned, appeal here at https://hp-maker-server.compep211.workers.dev/appeal.
Violation of the rules of hp's maker will result in a ban. Any attempt to bypass a ban will result in you getting permanently Hardware-ID **[hwid]** banned.
--------------------------------------------------------------------------------
Community & Project Rules

To ensure a safe and creative environment for everyone using hp's maker, all published projects must adhere to these simple guidelines:
• No Profanity or Swears: Keep project titles, descriptions, and scene text clean and free of offensive language.
• No "Like-Baiting" or Spam: Do not include misleading phrases in your titles like "Like for a follow," "Upvote this," or "Free currency if you like."
• No Inappropriate Content: Projects containing explicit content, excessive violence, or hateful imagery will be immediately removed.
• Respect Intellectual Property: Do not explicitly impersonate other creators or claim ownership over someone else's work.
• No Malicious Exploits: Any attempts to abuse the server database or inject malicious code will be penalized immediately.

⚠️ Enforcement & Ban Policy

• First Offenses: Minor infractions will result in project deletion or temporary warnings.
• Multiple Violations: Repeatedly breaking the community guidelines will result in a ban.
• Ban Evasion: Any attempt to bypass a restriction or ban will result in a permanent Hardware-ID (HWID) ban across the entire network.
___________________________________________________________________________________
With love from <3 hpcomputers
**OPEN SOURCE IS LOVE!**
