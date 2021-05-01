# Plastic Tube

[Download](https://github.com/markfeit/ampero/raw/master/patches/Plastic-Tube.prst) | [License](README.md#License) | [More Patches](https://github.com/markfeit/ampero/tree/master/patches)

| Firmware | 3.7 |
|----------|-----|

If you feel like we do, this patch attempts to recreate a some of the
sounds of talkbox effects popular during the 1970s.

The ballpark is as close as this gets because the human vocal tract is
incredibly complex, which makes it difficult to model.  The handful of
effects available on the Ampero (or most other effects units, for that
matter) crudely approximate it with some wah (Toucher in bass mode), an envelope
filter (Dynamic Basso) and equalization that cuts out most of what
isn't in the male speaking vocal range.

This patch needs some compression to offset the effect of using
dynamics to drive the tone filtering as was done on the _1970s Porno_
patch.  Unfortunately, the Ampero doesn't have enough available effect
blocks to add it to this one.

Tips:

 * The amplification in this patch is based that in another patch
   called _Stevie Ray Spawn_ that hasn't been released yet.  You can
   get a preview of it by disabling all of the vocal tract simulation
   with the `CTRL` button.

 * This patch does best with notes below the 12th fret.

 * Single notes work best, although chording can be accommodated by
   rolling back the sensitivity on `EXP1`.


## Controls

| Control | Description |
| ------- | ----------- |
| **CTRL** | Vocal Tract Enabled (Green) / Disabled (Red) |
| **EXP1** | Sensitivity |
| **EXP2** | None |
| **Knob 1** | Tube Screamer Tone |
| **Knob 2** | Dynamic Basso Resonance |
| **Knob 3** | Dynamic Basso Decay |
