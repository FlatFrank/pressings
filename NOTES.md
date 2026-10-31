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

## v2.7 · the Atlas (first screen)
Pressings opens on a constellation map: 8 families on a wide ellipse, 43 styles as points of light on a ring around
each family name. Each family has its own colour (cumbia amber, dembow pink, hip hop coral, breaks green, electro cyan,
techno blue, house white, disco violet).
- Faint curves show lineage (what grew out of what: disco → Chicago, Detroit → tech house, reggaeton → moombahton…).
  Lines inside a family run straight; lines across families bow toward the centre. They brighten for the hovered or
  playing style.
- Hover a style for its card (name · family · place and time · BPM). Click it: the first click starts the sound and opens
  the live view; later clicks hand the style to the DJ (mixed on the next bar, as before) and open the live view.
- The playing style pulses at its tempo; "NOW PLAYING · X ▸ LIVE" at the bottom right goes back to the live view.
- From the live view: Esc, M or "◂ ATLAS" returns to the map. The music keeps playing. The views cross-fade in 0.5 s.
- Checked headless: 43 nodes, hover, click to live, Esc back, a second pick queues a mix, no errors.

## v2.8 · the story panel, the bottom menu
- **Split screen:** the rings sit in the left 66 %. The right 34 % tells the style's story, culture first:
  - origin (place, then when);
  - one or two short paragraphs on who made it, where and why;
  - "The sound" (the patterns and the structure, tied to what the rings play);
  - sources.
  At most four paragraphs. On a phone the panel moves under the rings. It changes with the title, once a mix is done, and it is
  hidden on the Atlas, in reels and with H.
- **Sources:**
  - Wikipedia for the established genres;
  - Sounds and Colours, Vice, Klof Mag and The Peninsula for the newer Latin American scenes that Wikipedia doesn't cover.
  All text is paraphrased, and each style lists its links. "Andean electronica", "Selva bass" and "Tribal techno" are this
  atlas's own names for real strands, and the text says so.
- **No pattern** below the rings.

## v3.5 · better sounds (first pass)
- I re-checked the libraries, listing them through the GitHub API and test-loading samples in a real browser:
  - **VCSL** has no accordion, guitars or basses. It has real upright pianos, vibraphone and tenor sax, but as long WAVs
    (2–4 MB each), too heavy to stream.
  - **tidal-drum-machines** has an E-mu SP-1200 kit.
  - **Dirt-Samples** (TidalCycles) has bird field recordings.
- **Acoustic instruments now use MusyngKite**, the same per-note files built from a richer soundfont, instead of FluidR3:
  accordion, nylon and electric guitars, upright, finger and slap bass, organ, brass, muted trumpet, flute, shakuhachi
  (quena), pan flute, steel drum, vibes, strings, Rhodes, clavinet and voices. All 231 note files used were checked to
  download and decode. Synth patches (pads, saw, square, synth bass) stay on FluidR3.
- **Boom bap** (and chopped & screwed) now uses an **E-mu SP-1200** kit, the boom bap machine, instead of the MPC60.
- **Birds** in the cumbia styles are now real bird recordings (Dirt-Samples), not synthesised chirps.
- Found while measuring the pitch of VCSL samples: VCSL names its notes an octave low (its "C3" is middle C). Kept in mind
  for any future VCSL instrument.
- **Panel:** "Origin" now sits on the same line and at the same size as the ATLAS / FAMILY / STYLE trail, and every
  section label in the panel matches.

## v3.4 · new navigation: trail, list, thread
- The bottom menu is gone. Its family row did two things at once: browse a family and play its first style.
- **Trail (top left):** `◂ ATLAS / FAMILY / STYLE ▾`, with the family in its colour.
  - ATLAS flies back to the map.
  - The family or the style opens the **list of every style**: all 8 families in map order, the playing one marked ●
    and a queued one →. Browsing never plays; only picking a style does (an 8-bar mix, or at once when paused).
  - The list closes with Esc, a click outside it, or a pick. L toggles it.
- **Follow the thread (story panel):** one sentence built from the map's lineage, e.g. "Breakbeat grew from Electro and
  Boom bap, and led to Jungle." Each name is a link in its own colour, and clicking it mixes to that style.
  - Two links I couldn't back with a source were removed: grime → dubstep and screwed → trap.
- **Keys:** ↑/↓ and 1–9 move within the family, and ←/→ walk through all 42 styles in map order.
- The mix technique now sits next to the progress bar ("→ DUB TECHNO 11% · ECHO OUT · FILTER IN · TEMPO RIDE").

## v3.3 · grime, bridges, long mixes, still background
- **Grime** (East London, early 2000s, 140 BPM) joins hip hop at Paco's request; Wikipedia counts it as its own genre and
  the panel says so. The arrangement: syncopated 808 kick, clap, sparse hats, "eski" woodblock clicks, a sliding sub,
  string stabs and a square-wave lead. On the map it links to UK garage, jungle and dubstep.
- **Bridges on the map:** breakbeat now links to boom bap (Kool Herc's breaks are the root of hip hop). Each family's ring is
  turned so its bridge style faces the family it links to: breakbeat faces hip hop and grime faces breaks & bass, so the
  two sit side by side between the families.
- **Every mix is long (8 bars):**
  - The short ones were the "cut on the one", used for another family or a tempo more than 9 % away. Blends were also
    shortened to finish before the next drop, sometimes leaving only 1–2 bars.
  - The cut is gone. Far-apart records now mix as **echo out · filter in · tempo ride**: the incoming record fades up
    high-passed and opens, while the outgoing one closes, loses its lows and is thrown into the echo. The tempo is ridden
    the whole way, e.g. boom bap 90 → grime 140 over eight bars.
  - The pitch-fader ride (cumbia ↔ rebajada, boom bap ↔ screwed) now also takes 8 bars instead of 2.
- **Background:** the moving liquid field is gone. A still, soft glow in the style's colour sits behind the rings, and the
  map is plain black with its family halos.

## v3.2 · transformations instead of build–snare–drop
The old template is gone: no snare or percussion roll, no rising sweep, no crescendo sample, no beat of silence and no crash
on the drop. Every style now gets through its break with a **transformation of its own sound**, and the arrangement
re-assembles bit by bit. Over the break the record changes shape; over the next bars it comes back, until it is whole
again on the return.
- **Re-assembly (all styles):** in the build, parts come back one per bar (hats, percussion, textures). The kick, bass and
  backbeat (snare, clap, caja) wait and return together.
- **Filter sweep:** the whole record closes to a muffle (to ~420 Hz) and opens as the parts return. Used for Chicago, tech
  house, Detroit, Italo, nu-disco, French touch, breakbeat, moombahton and electro house.
- **Resonant sweep:** the same, through a singing resonant filter (Q up to 6). Used for acid house, acid techno, industrial,
  Hi-NRG, electro and electroclash.
- **Reverb wash:** the record dissolves into its own reverb and darkens, then re-forms. Used for deep, ambient, jazz hop,
  lo-fi, chopped & screwed, liquid and cumbia rebajada.
- **Dub echo:** everything goes into the delay as its feedback rises, then settles. Used for dub techno, digital cumbia,
  tropical bass, jungle, dubstep and dancehall.
- **Layer by layer:** no effect at all, only the arrangement thinning and rebuilding. Used for cumbia, chicha, microhouse,
  minimal techno, hardgroove, disco, boom bap, trap, UK garage, reggaeton, Dominican dembow, boogie and Miami bass.
- Each record has its own transformation stage (a low-pass and reverb/delay sends after its fader), separate from the DJ's
  EQ and filters, so a mix and a transformation never fight. Logged in a headless browser through break → build →
  return for five styles: every move lands back at neutral on the return.

## v3.1 · colour code, instant change when paused, mix feedback
- **Colour code:** every style is drawn in shades of its family's colour: the rings, the light trails, the spectrum, the liquid
  field and its node on the map. Breaks & bass is greens, house is whites and greys, techno is blues, and so on. Within a
  family each style leans slightly warmer or cooler, so they stay distinguishable.
- **When paused:** picking a style (on the map, in the menu or with the keys) switches at once and starts playing. There's no
  DJ and no waiting for the next bar, since no bar is coming.
- **During a mix:**
  - the title alternates with a scrambled "TRANSITIONING" every ~2.6 s;
  - a hairline under it fills with the mix's progress, and "→ NEXT STYLE  42%" sits next to it;
  - before the mix starts, the bar shows "NEXT BAR" and a pulse at its head.
  The title still changes to the new style, with the letter reveal, once the mix is done.

## v3.0 · the zoom
- **Zoom in:** clicking a style flies one camera from the map into its record (1.5 s, cubic ease in-out):
  - the map scales up around the chosen node (up to ×9) as the node slides to where the rings sit;
  - the live view grows out of the node, from 1/9 size, through a round iris;
  - everything travels with the camera: field, dots, lineage, labels, rings, ring labels, title and menu;
  - after that, the story panel slides in from the right, its lines rising one after another.
- **Zoom out** (Esc, M or ◂ ATLAS): the reverse (1.3 s). The rings fold back into the playing style's node, the map
  comes back into frame, and the panel slides away first.
- Each layer is drawn sharp at its own scale (not a scaled screenshot), then cross-faded. Clicks wait until the camera lands.
  The music never stops.

## v2.9 · only real names, every panel checked
Five independent fact-checks (one per group of families) checked every style's name, meta line and panel against sources.
- **Dropped:**
  - "Andean electronica" and "Selva bass" were names I made up. Chancha Vía Circuito now sits under Digital cumbia, and
    the Lima producers under Tropical bass.
  - Now 41 styles; the cumbia family has 5.
- **Renamed:**
  - "Tribal techno" → **Hardgroove**: Ben Sims named it around 1996 (MusicRadar). It's the same percussive, loop-based techno.
  - "Electro-funk" → **Boogie**: Wikipedia treats electro-funk as just another name for electro. Boogie is the post-disco
    style the slap bass, handclaps and 115 BPM match.
  - "Minimal house" → **Microhouse**: the standard name (Wikipedia, AllMusic, Bandcamp Daily), and it no longer sits next
    to "Minimal techno".
  - "Rebajada" → **Cumbia rebajada**.
  - Family "Dembow" → **Dancehall & dembow**: dancehall is the parent, and "Dem Bow" is one 1990 dancehall riddim.
- **Facts fixed:**
  - Gabriel Duéñez's spelling, and the rebajada story is his own account.
  - Zizek and ZZK began in 2007–08, not 2006.
  - Chicha uses congas, not bongos.
  - "Tropical futurism" was the press's label, not the band's.
  - Akufen is from Montreal and Luomo from Finland.
  - Where Kompakt, Perlon and M-nus are based.
  - ZYX licensing (1982) vs the "Italo disco" tag (1983).
  - Lo-fi streams started in 2017, not 2013.
  - "Planet Rock" is by Afrika Bambaataa & the Soulsonic Force, produced by Arthur Baker. Cybotron came in parallel, not after.
  - The 2 Live Crew ruling (1990) and its reversal (1992).
  - "Dem Bow" (1990) was produced by Bobby Digital on a Steely & Clevie riddim, and named the beat, not the genre "reggaeton".
  - Meta lines now match the panels: dancehall, reggaeton, electroclash, minimal and industrial techno, and others.
  - Unsourced figures removed.
- **Menu at the bottom:** families (with ◂ ATLAS) on the first row, the open family's styles under it; the rows wrap on narrow screens.
  The title and meta stay top left.
