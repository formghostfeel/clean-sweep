# Assets to create for clean-sweep

## logo.png вЂ” 256x256, transparent, dark theme
🧽 Neon shield/gear motif matching $clean-sweep$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $clean-sweep$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
Scan results — category cards with sizes, checkboxes

## screenshots/settings.png вЂ” 1280x800
Cleaner in action — progress with per-category counts

## screenshots/results.png вЂ” 1280x800
Whitelist editor — protected paths and apps

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"