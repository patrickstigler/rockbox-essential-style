# Changelog

## Rev. 1 — 2026-09-08

First release of **essential-style** for iPod 4G (160×128).

- Status bar: pause / ff / rew as in Flattery-B; codec bitmap only while playing (no bitrate). Stop stays blank (no stop square in the original icon strip)
- Rating under the progress bar (`%rr` 0–10)
  - 0: middle dot (`·`)
  - 1–4: broken heart
  - 5–10: heart
  - Hearts are 16×16 ListenBrainz / Font Awesome silhouettes (filled heart + heart-crack); progress bar sits 8px higher so the icons have a clear row; 8px inset left and right; elapsed time removed
- Titles use UI font 14-Nimbus (äöüß); 14-Nimbus is not loaded twice. Fonts are not bundled — theme uses Rockbox’s 10-Nimbus / 14-Nimbus
- 10-Nimbus only for compact labels
- Status bar on Now Playing shows the clock instead of the text “Now Playing”
- Disk-activity dash above the battery replaced by a spinning broken circle in the bottom-left corner (`%lh`)
