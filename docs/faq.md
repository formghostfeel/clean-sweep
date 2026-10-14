# FAQ — clean-sweep

## Safety

### Is clean-sweep safe?
Yes. Fully open source (MIT) — every line auditable in this repo. Binaries are
built by public GitHub Actions CI from the tagged commit, with SHA-256
checksums in release notes. No telemetry, no ads, no bundles.

### Do I need to disable my antivirus?
**No — never.** Any tool asking you to turn off your antivirus should be
deleted. clean-sweep uses only documented OS APIs. If your AV shows a heuristic
warning, verify the SHA-256 hash against the release notes and whitelist —
see [troubleshooting](troubleshooting.md#antivirus-false-positive).

## Compatibility

### Which Windows versions are supported?
Windows 10 (build 18363+) and Windows 11, x64. Server 2019+ generally works,
untested. 32-bit is not supported.

### Does it work on Linux / Mac?
No. Windows only.

## Effects

### What results should I expect?
Measurable but depends on your setup. Run the built-in measurement/benchmark
feature for your own before/after numbers instead of trusting screenshots.

## Troubleshooting quick links

- Won't start → [troubleshooting.md](troubleshooting.md#app-does-not-start)
- Antivirus warning → [troubleshooting.md](troubleshooting.md#antivirus-false-positive)
- Hotkeys don't work → [troubleshooting.md](troubleshooting.md#hotkeys-not-working)
