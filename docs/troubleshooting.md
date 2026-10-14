# Troubleshooting — clean-sweep

## App does not start

1. Check Windows version — Win 10 1909+ / Win 11 x64 (`winver`)
2. Install [VC++ Redistributable x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)
   (bundled in installer, not in portable)
3. Check the log: `%APPDATA%\clean-sweep\logs\latest.log`
4. SmartScreen blocked it? Verify hash first, then More info → Run anyway

## Antivirus false positive

Heuristic false positives happen because system-tuning APIs are also used by
malware. **Never disable your antivirus.** Instead:

1. Verify the hash against official release notes:
   ```powershell
   Get-FileHash .\clean-sweep.exe -Algorithm SHA256
   ```
2. Hash matches → official binary; add folder to AV exclusions
   *(Windows Security → Virus & threat protection → Exclusions)*
3. Hash does NOT match → you downloaded from an unofficial mirror. Get the
   real one from [GitHub Releases](https://github.com/yourname/clean-sweep/releases/latest)
   and tell us where the fake came from.

Report false positives to Microsoft:
[file submission](https://www.microsoft.com/en-us/wdsi/filesubmission).

## Hotkeys not working

1. Check conflicts — Discord, GeForce Experience, OBS register global hotkeys
2. Same elevation level: enable "Launch with Windows"
3. Exclusive fullscreen swallows hotkeys — switch the game to borderless

## Still stuck?

- 💬 [Discord #support](https://discord.gg/yourinvite)
- 🐛 [Bug report](../.github/ISSUE_TEMPLATE/bug_report.md) — attach `latest.log`
