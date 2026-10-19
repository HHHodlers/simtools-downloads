# SimTools for Mac and Windows

Official SimTools desktop installers and update files. Access requires your existing SimTools account.

## Mac

[Download the latest Mac release](https://github.com/HHHodlers/simtools-downloads/releases/latest) — Intel and Apple silicon, macOS 13 or later.

Open the DMG and drag SimTools into Applications. Old unsigned previews require a one-time manual installation. Signed staff versions receive published Mac updates automatically and offer Restart to Update or Later. Mac releases are signed with Developer ID and notarized by Apple.

## Windows internal release

[Download SimTools 0.1.7 for Windows x64](https://github.com/HHHodlers/simtools-downloads/releases/download/v0.1.7-windows/SimTools-0.1.7-windows-x64.exe).

Install this version manually once over an existing Windows preview. From 0.1.7, future Windows releases download automatically and offer Restart to Update or Later. Save unfinished work before restarting.

Windows updates use a separate feed authenticated with a public Ed25519 key bundled in the app; downloaded installer bytes must match the signed SHA-512 checksum. The initial installer has no Windows Authenticode certificate and may show an unknown-publisher warning. Company security policies may block it.

## Keeping current

The published web workspace at https://sm.sim8.io loads on launch/reload. Native releases have their own version and update separately.

Updater-enabled apps check 30 seconds after startup and every four hours. Use Check for Updates in the SimTools menu to check sooner. Downloads happen in the background; installation requires choosing Restart to Update.

Mac and Windows feeds are independent. This repository hosts distribution files only. Application source is maintained separately.
