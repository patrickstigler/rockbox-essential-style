# Changelog

## Rev. 1 — 2026-09-15

First release of **essential-style** for iPod 4G (160×128).

- Status bar: pause / ff / rew as in Flattery-B; codec bitmap only while playing (no bitrate). Stop stays blank (no stop square in the original icon strip)
- Clock in the status bar on Now Playing instead of the text “Now Playing”
- Rating under the progress bar (`%rr` 0–10)
  - 0: middle dot (`·`)
  - 1–4: broken heart
  - 5–10: heart
  - 16×16 ListenBrainz / Font Awesome silhouettes (filled heart + heart-crack)
- Progress bar sits 8px higher so the hearts have a clear row; 8px inset left and right (144×9); rounded corners and grey fill as in Flattery-B; elapsed time removed
- Disk activity: 9×9 spinning broken circle, flush to the bottom-left corner (`%lh`), below the last menu line
- Titles use UI font 14-Nimbus (äöüß); 14-Nimbus is not loaded twice
- 10-Nimbus only for compact labels
- Fonts are not bundled — theme uses Rockbox’s 10-Nimbus / 14-Nimbus
