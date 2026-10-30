# Pressings · an atlas of music

A procedural music piece that runs in your browser. It opens on a constellation map of **8 families and 43 styles**:
cumbia, dembow, hip hop, breaks & bass, electro, techno, house and disco. Pick a style and you hear it played live on
real recorded instruments. The rhythm, harmony and form are generated as it plays. Pick another style and a DJ mixes
it in on the next bar, using the basic real techniques: an EQ blend with a bass swap, a filter mix, a pitch-fader ride,
or a cut on the one. The song carries on through the mix rather than starting again.

**Play it:** https://flatfrank.github.io/pressings/

## How to use it
- **Atlas:** hover a style to see where it comes from and its tempo, then click it to hear it.
- **Live view:**
  - click a style, or use ↑/↓ or 1–9, to mix to it;
  - use ←/→ to change family;
  - Space plays and pauses;
  - click a ring to mute it, or shift-click to solo it;
  - V records a 9:16 reel and H hides the readouts;
  - Esc, M or ◂ ATLAS goes back to the map.

It is a single `index.html` with no build step. The samples load from public CDNs when the page opens.

## Samples and credits
- **VCSL** (Versilian Community Sample Library, CC0): hand percussion, güiro, bombo, frame drums, strumstick, balafon, ocarina and more.
- **Salamander Grand Piano** (Alexander Holm, CC-BY 3.0).
- **FluidR3 GM** (Frank Wen, CC-BY 3.0), via gleitz/midi-js-soundfonts.
- **tidal-drum-machines** (909, 808, 707, LinnDrum, MPC). No license is stated; they are credited here.
- The TB-303 lines, 808 subs, reese and wobble basses, and the birds are synthesised in the browser.

See `NOTES.md` for the full design notes: the families and styles, the DJ's techniques, the screen, and the sources.
