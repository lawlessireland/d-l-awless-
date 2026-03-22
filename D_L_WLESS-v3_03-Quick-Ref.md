# D_{L}@WLESS v3.03 — Quick Reference Card

## 🚀 FIRST RUN CHECKLIST

| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | Open HTML file in Chrome/Firefox/Safari | See red/cyan neon interface with dark background |
| 2 | Check header | See "128 BPM" badge and "IDLE" status dot |
| 3 | Click "Sounds" tab | See searchable patch grid with 16 sound cards |
| 4 | Click any patch card (try "303 Acid Sequence") | Play tab updates with patch name, BPM, type |
| 5 | Return to Play tab | See patch info in hero section |
| 6 | Press big red ▶ button | Drums + bass begin playing |
| 7 | Adjust BPM slider or ←/→ arrows | Tempo changes in real time |
| 8 | Toggle "Pro Mode" switch in nav bar | Reveals Sequencer, Workflow, Settings tabs |
| 9 | Visit Sequencer tab | See 16-step drum grid + bass synth |
| 10 | Click drum grid cells to edit pattern | Gold cells = active steps, green = current beat |

---

## 🎵 16 PATCHES — QUICK INDEX

### Acid Group
- **303 Acid Sequence** (132 BPM) — Richie Hawtin / Plastikman — Classic TB-303 squelch
- **303 Dark Mutation** (128 BPM) — DJ Pierre / Phuture — Slower, darker acid

### Berlin / Industrial Group
- **Berghain Floor** (138 BPM) — Surgeon / Paula Temple — Detuned saws + distortion
- **Ostgut Bassline** (136 BPM) — Blawan / Objekt — Heavy subsonic beating

### Detroit Group
- **Model 500 Deep** (122 BPM) — Juan Atkins / Model 500 — Warm triangle sub
- **Underground Resist.** (126 BPM) — Mike Banks / UR — Purposeful deep bass

### UK Rave Group
- **Rave Stab** (150 BPM) — The Prodigy / LFO — 92 hardcore stab, maximum impact
- **Jungle Stab** (165 BPM) — Acen / Remarc — Pitched square, zero sustain

### Deep / Reese Group
- **Reese Classic** (128 BPM) — Kevin Saunderson — Two detuned saws, natural chorus

### House Group
- **Fingers Deep** (120 BPM) — Larry Heard / Mr. Fingers — Warm sine sub, pure soul
- **Warehouse Acid** (130 BPM) — Marshall Jefferson — Chicago house meets acid

### Dub / Hard / Melodic Group
- **Dub Chord** (115 BPM) — Basic Channel / Rhythm & Sound — Foggy dub techno
- **Peak Hour Destroyer** (140 BPM) — Alignment / DJ Stingray — Maximum drive
- **Innervisions Float** (124 BPM) — Dixon / Âme — Emotional melodic techno
- **Afterlife Arp** (122 BPM) — Tale Of Us / Recondite — Plucked arp, cinematic
- **Kompakt Minimal** (124 BPM) — Michael Mayer — Warm minimal techno

---

## 🎹 8 CHORD PROGRESSIONS

| # | Name | Key | Steps | Energy | Character |
|---|------|-----|-------|--------|-----------|
| 1 | Dark Minor | D minor | Dm–Bb–F–C | ███████░ 7 | Workhorse dark techno |
| 2 | Phrygian Edge | A Phrygian | Am–G–F–E | ████████ 8 | Menacing, Arabic tension |
| 3 | Dorian Groove | E Dorian | Em–D–C–D | ██████░░ 6 | Soulful, Detroit/Chicago |
| 4 | Dark Descent | F minor | Fm–E♭–D♭–Cm | █████████ 9 | Crushing chromatic drop |
| 5 | Ostinato | D minor | Dm–Dm–Dm–Dm | ████░░░░ 4 | Minimal, dub techno |
| 6 | Hypno Loop | A minor | Am–Am–G–Am | ███░░░░░ 3 | Ambient spiral |
| 7 | Motor City Soul | G minor | Gm–Cm–F–B♭ | ██████░░ 6 | Detroit/Chicago soul |
| 8 | Peak Arc | C minor | Cm–A♭–B♭–Cm | █████████ 9 | Peak-hour tension-release |

---

## 🎛️ 10 SYNTH PATH PRESETS

| Path | Oscillators | Character |
|------|-------------|-----------|
| Acid Bass | Saw + Saw | TB-303 squelch, high resonance, fast env |
| Berlin Dark | Saw + Saw (detuned) | Berghain basement, heavy drive, low cutoff |
| Detroit Soul | Triangle + Sine | Warm sub, slow filter, spiritual |
| UK Rave Stab | Square + Saw | Punchy 92 stab, zero sustain |
| Reese Bass | Saw + Saw (detuned −14) | Natural chorus movement |
| Chicago Deep | Sine + Triangle | No aggression, warm groove |
| Hard Techno | Saw + Square | Maximum drive, slammed filter |
| Dub Pad | Saw + Saw (detuned) | Foggy, emerging texture |
| Melodic Lead | Triangle + Saw | Emotional floating lines |
| Pluck | Triangle + Sine | Zero sustain, arpeggio-perfect |

---

## 🥁 DRUM SEQUENCER LAYOUT

### 16-Step Grid (4 Rows × 16 Steps)
```
DRUM        1  2  3  4  5  6  7  8  9  10 11 12 13 14 15 16
─────────────────────────────────────────────────────────────
KICK        [●][ ][ ][ ][●][ ][ ][ ][●][ ][ ][ ][●][ ][ ][ ]
SNARE       [ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ]
CLOSED HAT  [ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ]
OPEN HAT    [ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ][ ]
```
**Gold cells** = Active step | **Green outline** = Current beat

### Controls
| Control | Location | Function |
|---------|----------|----------|
| BPM field | Top-right of drum card | Set sequencer tempo |
| ▶ Play | Top-right | Start sequencer |
| ⏹ Stop | Top-right | Stop sequencer |
| Clear | Top-right | Remove all steps |
| 🎲 Random | Top-right | Genre-weighted random pattern |
| Swing slider | Below grid | 0–33% shuffle amount |
| Pattern A/B/C/D | Below swing | Save & recall 4 patterns |

---

## 🎛️ BASS SYNTH KNOBS

### Oscillators
| Knob | Range | What it does |
|------|-------|-------------|
| Detune | −100 to +100 | Pitch offset between OSC1 and OSC2 |
| OSC Mix | 0 to 1 | Balance between OSC1 (left) and OSC2 (right) |

### Filter
| Knob | Range | What it does |
|------|-------|-------------|
| Cutoff | 80–18000 Hz | Filter brightness (logarithmic) |
| Reso | 0.1–20 | Resonance peak at cutoff frequency |
| Env Amt | 0–1 | How much the filter envelope opens the filter |

### Filter ADSR
| Knob | Range | What it does |
|------|-------|-------------|
| A | 0.001–2s | Filter attack time |
| D | 0.001–2s | Filter decay time |
| S | 0–1 | Filter sustain level |
| R | 0.001–4s | Filter release time |

### Amp ADSR
| Knob | Range | What it does |
|------|-------|-------------|
| A | 0.001–2s | Volume attack time |
| D | 0.001–2s | Volume decay time |
| S | 0–1 | Volume sustain level |
| R | 0.001–4s | Volume release time |

### Master
| Knob | Range | What it does |
|------|-------|-------------|
| Drive | 0–2 | Soft-clip saturation / warmth |
| Vol | 0–1 | Overall synth output level |

**Interaction:** Drag up/down on knob, scroll mouse wheel, or touch-drag on mobile.

---

## ⌨️ KEYBOARD SHORTCUTS

| Key | Action |
|-----|--------|
| `Space` | Play / Stop sequencer |
| `1`–`8` | Load progression by number |
| `←` / `→` | Decrease / increase BPM |
| `Q` | Fire kick pad |
| `W` | Fire snare pad |
| `E` | Fire bass pad |
| `R` | Fire chord stab pad |

---

## 🔊 AUDIO MIX PANEL

| Channel | Default Volume | Controls |
|---------|---------------|----------|
| 🥁 Drums | 90% | ON/OFF toggle + volume slider |
| 🎛 Bass | 25% | ON/OFF toggle + volume slider |
| 🎵 Chords | 15% | ON/OFF toggle + volume slider |

### Effects
| Effect | Controls |
|--------|----------|
| ⏱ Delay | ON/OFF, Wet %, Feedback %, Subdivision (1/16, 1/8, 1/4, 1/2) |
| ✨ Reverb | ON/OFF, Wet %, Room size, Decay time |

---

## 🔄 LFO — FILTER MODULATION

| Control | Options |
|---------|---------|
| Toggle | LFO ON / LFO OFF |
| Shape | Sine, Triangle, Square, Sawtooth |
| Sync Rate | 1/1, 1/2, 1/4, 1/8, 1/16 (BPM-synced) |
| Depth | 0–2000 Hz modulation range |

---

## 🐛 COMMON ISSUES & FIXES

| Problem | Cause | Solution |
|---------|-------|----------|
| No sound at all | AudioContext not started | Click anywhere on the page first |
| No sound | Volume at 0% | Check Audio Mix sliders and Bass synth Vol knob |
| No bass sound | No patch loaded | Click a patch in the Sounds tab |
| Drums but no bass | Bass channel muted | Check Audio Mix → Bass → ON |
| Sequencer won't play | Not started | Click ▶ Play in the Sequencer tab |
| Clicks/pops | Note envelope too short | Increase Amp Release knob |
| Audio muddy | Too much reverb | Lower Reverb Wet slider |
| Distortion | Drive too high | Lower Drive knob in Bass Synth |
| No Pro tabs | Pro mode not enabled | Toggle "Pro Mode" switch in nav bar |
| Font not loading | No internet connection | App still works; falls back to system sans-serif |
| Knobs unresponsive | Not dragging vertically | Drag UP to increase, DOWN to decrease |

---

## 🎵 WORKFLOW — Create an Acid Bassline

1. **Load patch:** Sounds tab → click "303 Acid Sequence"
2. **Check progression:** Play tab sidebar → see Dm–Bb–F–C loaded
3. **Enable Pro Mode:** Toggle in nav bar
4. **Open Sequencer:** Click Sequencer tab
5. **Edit drum pattern:** Click grid cells for 4-on-the-floor kick pattern
6. **Edit bass synth:** Scroll down to Bass Synth section
7. **Select "Acid Bass" path:** Click the path button
8. **Tweak sound:** Drag Cutoff knob down, Reso knob up
9. **Add movement:** Enable LFO → Sine shape → 1/8 rate → 400 Hz depth
10. **Add space:** Turn on Delay → 1/8 subdivision → 30% wet
11. **Press Play** and enjoy

---

## 💾 PATTERN MEMORY

- **Save:** Click "Save → slot" to store current drum grid to the selected slot (A/B/C/D)
- **Recall:** Click a slot button (A/B/C/D) to load that saved pattern
- **Overwrite:** Save to an already-used slot to replace its contents

---

## 📋 PRE-PERFORMANCE CHECKLIST

- [ ] Open app in Chrome (best Web Audio support)
- [ ] Click page once to activate AudioContext
- [ ] Load primary patches and test each (Sounds tab)
- [ ] Set BPM for your set
- [ ] Create 2–3 drum patterns and save to A/B/C/D slots
- [ ] Test Delay and Reverb FX
- [ ] Set Audio Mix levels (drums dominant)
- [ ] Verify Play/Stop works via Space bar
- [ ] Adjust master volume to safe listening level
- [ ] Have backup browser/device ready

---

**App:** D_{L}@WLESS v3.03 — Hardware Synth Studio
**Status:** 100% Operational ✓
**File:** Single HTML file • Zero dependencies • ~204 KB
