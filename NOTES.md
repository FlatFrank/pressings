# Pressings: notes (v2 · families, styles, a DJ)

## Idea
Two families, eleven styles, played on real recorded instruments. Pick a style and a DJ mixes it in on the next bar,
with no other input. All the styles in a family share one skeleton (key, form, seven roles = seven rings), so a mix is
visibly the same ring changing hands: during a mix both records' rhythms are drawn on each ring, weighted by their faders
(the outgoing one dashed).

## Families and styles
| Family | Style | BPM | What makes it that style |
|---|---|---|---|
| Cumbia (A minor) | Cumbia (Colombia) | 92 | bombo, rope snare, güiro long-short-short, congas, upright bass root–fifth, nylon guitar off-beats, accordion in thirds |
| | Chicha (Peru, '60s–'70s) | 96 | timbal, bongos (martillo), organ off-beats, wah electric guitar lead |
| | Rebajada (Monterrey) | 75 | the cumbia record slowed ×0.82, pitch and all |
| | Digital cumbia (Buenos Aires, 2000s) | 96 | 808 kick, clap and congas, sub bass, dub stabs, accordion chops with delay |
| | Tropical bass (Lima, 2010s) | 100 | tresillo kick, cajón (Afro-Peruvian), maracas, heavy bass, dark pad, pan flute; in the spirit of Dengue Dengue Dengue |
| House (F minor) | Chicago house (mid-'80s) | 124 | 909 kick, clap, open hats, tambourine, octave bass, piano stabs, organ riff |
| | Deep house | 120 | rim, shaker, finger bass, Rhodes 9ths, pad |
| | Acid house (1987) | 124 | 909 + a synthesised TB-303 line (accents, slides, resonance sweep); no chords |
| | Tech house (late '90s) | 126 | 16th hats, rim syncopation, rolling one-note bass; no chords |
| | Ambient house (~1990) | 116 | soft kick, shaker, long bass, halo pad, sparse piano |
| | Minimal house (2000s) | 124 | rotating clicks, wood ticks, bass blips, one dub stab every two bars |

## The DJ (basic, real techniques; no FX)
- Always beat-matched (one clock) and started on the next bar. **The song never restarts**: the incoming record joins at the
  same section and bar the outgoing one is on, so the structure runs straight through the mix (styles in a family share
  chord roots, so they agree harmonically at every bar). A mix is timed to finish by the next drop (up to 8 bars); the
  incoming record then plays the build, the beat of silence and the drop.
- **EQ blend + bass swap** (same family, tempos within 9 %): incoming fader up over two bars with LOW cut (−30 dB) and HIGH
  down; both decks gain-matched (−1.4 dB) while they overlap; on the downbeat of bar 5 the basses are swapped; then the
  outgoing record's highs and fader go out over the last four bars. Tempo ridden from one record to the other over 8 bars.
- **Filter mix** (into or out of ambient house): incoming high-pass opens (1 kHz → 20 Hz) as the outgoing low-pass closes.
- **Pitch fader** (cumbia ↔ rebajada): the same record slowed down (or back up) over two bars, tempo and pitch together,
  the way the Monterrey sonidero sound happened.
- **Cut on the one** (another family, or tempos too far apart): the new record drops on the downbeat; the old one's lows
  are pulled and it fades within the bar.
- Asking for another style during a mix queues it; it starts when the current mix ends.
- Checked in a headless browser across a chain of 11 mixes (all four kinds): no gaps, no errors; the EQ moves logged beat by beat.

## Screen (v2.2)
- The full look: liquid contour field, dot matrix, the mix as a polar slit-scan, light trails off the hits, neon rings with
  the shape of each bar's rhythm (both records during a mix, the outgoing one dashed), ring callouts.
- Rings are fixed and round: no helix, no spin, no tilt. Nothing flashes: no drop flash or burst; a hit just brightens and
  swells slightly. The beat of silence is a gentle dim, no text.
- Below: a hairline step pattern (each hit a line 2 px high at most), same colours and order as the rings, playhead line,
  section and bar in tiny type.
- Family tabs, style name, tempo · key · place; the style row (a line slides from old to new during a mix); volume slider.

## Controls
Click a style, ↑/↓ or 1–6: mix to it · click a family or ←/→: change family · Space play/pause · click a ring: mute,
shift-click: solo · V record a 9:16 reel · H hide readouts · 0 help.

## Samples
VCSL (CC0) via jsDelivr: congas, güiro, bombo, rope snare, modern snare (timbal), bongos, cajón, tambourine, claves, shakers,
woodblock, marimba, suspended cymbal · Salamander Grand Piano (Alexander Holm, CC-BY 3.0) · FluidR3 GM (Frank Wen, CC-BY 3.0):
basses, Rhodes, nylon and electric guitar, organ, accordion, pads, pan flute · tidal-drum-machines (909, 808, LinnDrum, MPC;
no license stated, credited). The TB-303 line is synthesised in the browser (as the 303 itself is a synth).
All sample files verified to download and decode in a real browser (2026-10-30). Each recording is loudness-normalised on load.

## Sources
- Cumbia rebajada: https://en.wikipedia.org/wiki/Cumbia_rebajada (Sonido Dueñez, Monterrey, ~76 bpm)
- ZZK Records / digital cumbia: https://soundsandcolours.com/articles/argentina/the-story-of-zzk-records-argentinas-home-of-digital-cumbia-1281/
- Dengue Dengue Dengue: https://soundsandcolours.com/articles/argentina/sc-meets-dengue-dengue-dengue-in-buenos-aires-exclusive-interview-23897/
- EQ mixing / bass swap basics: https://digitaldjpool.com/blog/dj-eq-mixing-for-beginners/
- Earlier references: Maxim Codex (teardowns/maxim-codex.md), Tone Matrix, Patatap, Paco's art direction board.

## Known limits / next
- Claude can't listen; levels come from measured loudness and design. Tell me what sits wrong.
- Cross-family mixes are cuts for now (tempos 92 vs 124). Next: the endless radio on top of this DJ.

## v2.4 · six more families (8 families, 41 styles)
| Family (key) | Styles (BPM) |
|---|---|
| Techno (A minor) | Detroit 128 · Minimal 126 · Dub techno 124 (filter mixes) · Acid techno 134 (303) · Industrial 134 (distorted kick, anvil, brake drum) · Tribal 132 (909 toms in 3-3-2, congas) |
| Disco (D minor) | Disco 118 (octave bass, muted-guitar chops, strings) · Italo disco 122 (LinnDrum, galloping bass, DX piano) · Hi-NRG 128 (707, octave 16ths, synth brass) · Nu-disco 116 (slap bass, Rhodes) · French touch 124 (filtered loop breathing over 8 bars, heavy sidechain) |
| Hip hop (C minor) | Boom bap 90 · Jazz hop 88 (walking bass, Rhodes, muted trumpet) · Lo-fi 80 (lazy snare, felt piano, vibes) · Trap 70 (808 sub with glides, hat rolls in 32nds and triplets, flute) · Chopped & screwed 65 (boom bap slowed ×0.72 on the pitch fader, DJ Screw) |
| Breaks & bass (E minor) | Breakbeat 130 · UK garage 132 (2-step, shuffled hats, organ, vocal chops) · Jungle 165 (chopped acoustic break, sub) · Liquid drum & bass 174 (reese, Rhodes) · Dubstep 140 (half-time snare, wobble bass) |
| Dembow (G minor) | Dancehall 98 · Reggaeton 92 (dembow snare, 808 sub, timbal fills) · Moombahton 108 (Dave Nada, D.C. 2009; thick bass, rave stabs) · Dominican dembow 122 (güira, fast dembow) |
| Electro (F♯ minor) | Electro 127 (808, robot riff) · Electro-funk 115 (slap bass, clav, handclaps) · Miami bass 130 (808 boom + sub, orchestra hits) · Electroclash 128 (distorted LinnDrum, dirty bass) · Electro house 128 (saw bass, supersaw stabs) |

New synth voices (in the browser): 808 sub with pitch punch and glides; reese (two detuned saws + sub); wobble (saw + square
through a resonant low-pass swung by a tempo-synced LFO). New recordings: VCSL hi-hat, anvil, brake drum; 707, LinnDrum
toms/clap/cowbell, 808 snare/toms/long boom, 909 toms; FluidR3 slap bass, muted guitar, orchestra hit, synth brass, DX piano,
clavinet, voice "oohs", muted trumpet, steel drums, synth strings, vibraphone, flute. Four VCSL files that browsers can't
decode were left out. Checked: all styles compose without out-of-range notes; a chain of 21 mixes across the new families
used the right technique each time (blend, filter, pitch fader, cut) with no errors.
Sources: Dominican dembow https://en.wikipedia.org/wiki/Dominican_dembow · Moombahton https://en.wikipedia.org/wiki/Moombahton

## v2.5 · the new wave of cumbia (7 cumbia styles)
Reworked after Paco's references (Dengue Dengue Dengue, Animal Chuki, Shushupe, Chancha Vía Circuito). The cumbia family now
has an eighth layer, AIR (birds, voices), and these styles:
- **Digital cumbia** (Buenos Aires, late 2000s, ZZK): 808, bombo legüero with rim hits, real güiro, 808 sub with slides,
  charango off-beat strums, quena line with dub delay, birds.
- **Andean electronica** (Andes, 2010s; in the spirit of Chancha Vía Circuito): huayno lilt on the bombo legüero, frame drum,
  caxixi, balafon arpeggios, quena on the pentatonic, deep bass, birds; mixed with filter moves.
- **Tropical bass** (Lima, 2010s; in the spirit of Dengue Dengue Dengue): tresillo kick, cajón, quijada, log drum, dark 808 sub,
  dark pad, wah chicha-guitar fragments in a long delay, voices.
- **Selva bass** (Peruvian Amazon; chicha meets dembow, in the spirit of Shushupe / Animal Chuki): four-on-the-floor 808,
  dembow on the timbal, güiro, log drum, Amazon guitar picking, synth bleeps, birds.
Instrument stand-ins, said plainly: no free charango, quena or quijada recordings were found, so a strummed strumstick (VCSL)
plays the charango, a shakuhachi (FluidR3, an end-blown bamboo flute) plays the quena, and a vibraslap (VCSL, the instrument
that replaced the jawbone) plays the quijada. The bombo legüero is a mallet tom with frame-drum rim hits. Birds are synthesised.
Sources: ZZK Records / Sounds and Colours on Chancha Vía Circuito, Dengue Dengue Dengue (Native Instruments blog), Peru Boom review.
