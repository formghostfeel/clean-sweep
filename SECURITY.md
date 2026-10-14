# Security Policy — clean-sweep

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.2.x   | :white_check_mark: |
| 1.1.x   | :x:                |
| 1.0.x   | :x:                |

## Reporting a Vulnerability

- **DO NOT** open a public GitHub issue for security vulnerabilities.
- Email: **security@clean-sweep.dev**
- Include: affected version, OS build, reproduction steps, impact.

**Response targets:** Critical — 24h / High — 48h / Medium — 5d / Low — next minor.

## Verification of official binaries

Official binaries are published **only** on GitHub Releases, built by public CI
from the tagged commit, with SHA-256 checksums attached:

```powershell
Get-FileHash CleanSweep.exe -Algorithm SHA256
```

Anything distributed through file-hosting sites is not ours and is not safe.

## Safe Harbor

Good-faith security research following this policy is authorized.
