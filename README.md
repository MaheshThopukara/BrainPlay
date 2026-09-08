# BrainPlay — site

Marketing site for **BrainPlay**, a learning arcade for Android TV.

Live at <https://maheshthopukara.github.io/BrainPlay/>

## How this is built

Every word and image is generated from the app itself, never hand-written here:

- module structure and one-line descriptions come from `GameCatalog.kt`
- `about` / skills / how-to-play / fun facts / ages come from `GameIntros*.kt`
- the 151 screenshots are captured off a TV emulator at 1920x1080 @ 320dpi,
  which is the same 960x540dp logical viewport the television uses

Regenerate rather than editing the HTML by hand — hand edits are lost on the next run.
