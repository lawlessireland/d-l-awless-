# D_{L}@WLESS v3.03 — Final Deliverables Manifest

**Project:** D_{L}@WLESS — Hardware Synth Studio  
**Version:** 3.03 (Final)  
**Build Date:** March 7, 2026  
**Status:** ✓ Production Ready

---

## 📦 Files Included

### 1. **D_L_WLESS-v3_03.html** (220 KB, 3,924 lines)
**Main application — single HTML file, zero dependencies**

- Full Web Audio API synthesis engine
- 16 sound patches (acid, industrial, deep, rave, house, dub, melodic)
- 8 chord progressions (minor, phrygian, dorian, chromatic, minimal, ostinato)
- 16-step drum sequencer with kick, snare, closed/open hats
- Subtractive bass synthesizer with 10 synth paths
- Delay & reverb effects (FX panel)
- LFO filter modulation
- Pattern memory (A/B/C/D slots)
- Keyboard shortcuts (Space, 1–8, Q/W/E/R)
- Touch-optimized responsive layout (mobile/tablet/desktop)
- Neon red/cyan aesthetic with dark ink background
- Pro Mode toggle for Sequencer, Workflow, Settings tabs

**To run:** Open in Chrome, Firefox, or Safari. Click page once to activate AudioContext.

---

### 2. **D_L_WLESS-v3_03-Quick-Ref.md** (9.9 KB, 253 lines)
**Quick reference card for rapid deployment**

- First run checklist (10 steps to play)
- 16 patches index with artist credits
- 8 chord progressions with energy ratings
- Synth path presets (Acid Bass, Berlin Dark, Detroit Soul, etc.)
- Drum sequencer layout & controls
- Bass synth knob reference (all parameters explained)
- Keyboard shortcuts cheat sheet
- Audio mix panel summary
- LFO modulation quick-start
- Common issues & fixes troubleshooting table
- Workflow example: "Create an Acid Bassline" (10 steps)
- Pattern memory save/recall
- Pre-performance checklist

**Use this:** Before a gig, during soundcheck, or to learn controls fast.

---

### 3. **D_L_WLESS-v3_03-Testing-Guide.md** (15 KB, 407 lines)
**Comprehensive testing & verification guide**

- Initial load test (UI, fonts, browser compatibility)
- Sound patches test (all 16 patches verified with specs)
- Chord progressions test (all 8 progressions with details)
- Drum sequencer test (16-step grid, swing, random, pattern memory)
- Bass synth test (all parameters, envelope shapes, LFO)
- Effects test (delay, reverb, modulation)
- Audio mix test (routing, levels, muting)
- Keyboard shortcuts test (all 7 shortcuts verified)
- Workflow tests (acid bassline creation, progression playback)
- Edge cases & failure modes (audio context suspension, clicks/pops, distortion)
- Mobile/tablet testing (iPad, Android, responsive layout)
- Browser compatibility matrix (Chrome, Firefox, Safari, Edge)
- Performance benchmarks (CPU load, latency, browser memory)

**Use this:** For QA validation, troubleshooting, or documenting test results.

---

### 4. **README.txt** (22 KB, 466 lines)
**Full project documentation**

**Sections:**
- What is D_{L}@WLESS? (Concept, target use case)
- Features overview (Sounds, Progressions, Drums, Synth, FX)
- Hardware inspiration (TR-8, Behringer Crave, Digitone, SP-404MKII)
- Live performance workflow (from load to playback)
- Sound library catalog (all 16 patches with production credits)
- Chord progressions deep-dive (all 8 with emotional arcs)
- Drum patterns guide (genre-weighted random, 4 memory slots)
- Synth paths explained (10 preset oscillator/filter combinations)
- Effects chains (delay, reverb, LFO modulation)
- Keyboard shortcuts full reference
- Mobile/tablet layout notes
- Browser requirements & compatibility
- Known limitations & future roadmap
- Deployment: Netlify + Squarespace architecture
- Open source & licensing

**Use this:** For understanding design philosophy, technical architecture, and deployment strategy.

---

## 🎯 Quick Start

1. **Open the app:**
   - Extract D_L_WLESS-v3_03.html
   - Open in Chrome/Firefox/Safari
   - Click page once to start AudioContext

2. **Load a sound:**
   - Click "Sounds" tab
   - Choose any patch (try "303 Acid Sequence")
   - Return to Play tab

3. **Load a progression:**
   - Click "Progressions" tab
   - Select progression (try "Dark Minor")
   - See chords update in Play tab sidebar

4. **Play:**
   - Press big red ▶ button on Play tab
   - Or press Spacebar
   - Adjust BPM with slider or ←/→ keys

5. **Go pro:**
   - Toggle "Pro Mode" in nav
   - Click "Sequencer" tab
   - Edit drum grid & bass synth parameters

---

## 🎹 The 16 Sounds

| # | Name | BPM | Type | Synth Path |
|---|------|-----|------|-----------|
| 1 | 303 Acid Sequence | 132 | Acid | Acid Bass |
| 2 | 303 Dark Mutation | 128 | Acid | Acid Bass |
| 3 | Berghain Floor | 138 | Industrial | Berlin Dark |
| 4 | Ostgut Bassline | 136 | Industrial | Berlin Dark |
| 5 | Model 500 Deep | 122 | Deep | Detroit Soul |
| 6 | Underground Resist. | 126 | Deep | Detroit Soul |
| 7 | Rave Stab | 150 | Rave | UK Rave Stab |
| 8 | Jungle Stab | 165 | Rave | UK Rave Stab |
| 9 | Reese Classic | 128 | Deep | Reese Bass |
| 10 | Fingers Deep | 120 | House | Chicago Deep |
| 11 | Warehouse Acid | 130 | House | — |
| 12 | Dub Chord | 115 | Dub | Dub Pad |
| 13 | Peak Hour Destroyer | 140 | Hard | Hard Techno |
| 14 | Kompakt Minimal | 124 | Minimal | — |
| 15 | Innervisions Float | 124 | Melodic | Melodic Lead |
| 16 | Afterlife Arp | 122 | Melodic | Pluck |

---

## 🎛️ The 8 Progressions

| # | Name | Chords | Key | Energy |
|---|------|--------|-----|--------|
| 1 | Dark Minor | Dm–Bb–F–C | D minor | 7/10 |
| 2 | Phrygian Edge | Am–G–F–E | A Phrygian | 8/10 |
| 3 | Dorian Groove | Em–D–C–D | E Dorian | 6/10 |
| 4 | Dark Descent | Fm–E♭–D♭–Cm | F minor | 9/10 |
| 5 | Ostinato | Dm–Dm–Dm–Dm | D minor | 4/10 |
| 6 | Hypno Loop | Am–Am–G–Am | A minor | 3/10 |
| 7 | Motor City Soul | Gm–Cm–F–B♭ | G minor | 6/10 |
| 8 | Peak Arc | Cm–A♭–B♭–Cm | C minor | 9/10 |

---

## 🥁 Drum Library

The drum sequencer features 4-row × 16-step grid with:
- **Kick:** Low-frequency sweep (160→42 Hz, fast attack)
- **Snare:** Noise burst with envelope
- **Closed Hat:** High-frequency short decay
- **Open Hat:** High-frequency longer sustain

Genre-weighted random patterns based on loaded patch type:
- Acid: 4-on-the-floor kick, sparse snare
- Industrial: Offsetting kick, hard snare backbeat
- Deep: Sidechain-style kick syncopation
- Rave: Fast closed hat rolls, snare on 2/4
- House: Straight 4/4, syncopated hats
- Minimal: Sparse, breathing kick patterns

---

## ⚙️ Synth Paths (10 Presets)

Each path pre-configures oscillator types, filter settings, and envelope:

1. **Acid Bass** — Saw+Saw, high reso, fast env, TB-303 squelch
2. **Berlin Dark** — Saw+Saw detuned, heavy drive, low cutoff
3. **Detroit Soul** — Triangle+Sine, warm sub, slow filter
4. **UK Rave Stab** — Square+Saw, punchy, zero sustain
5. **Reese Bass** — Saw+Saw (−14 cents), natural chorus
6. **Chicago Deep** — Sine+Triangle, warm groove, no drive
7. **Hard Techno** — Saw+Square, maximum drive, slammed filter
8. **Dub Pad** — Saw+Saw detuned, foggy texture, slow decay
9. **Melodic Lead** — Triangle+Saw, emotional floating lines
10. **Pluck** — Triangle+Sine, zero sustain, arpeggio-perfect

---

## 🎧 Effects

### Delay
- Wet amount: 0–100%
- Feedback: 0–100% (self-reinforcing repeats)
- Subdivision: 1/16, 1/8, 1/4, 1/2 (BPM-synced)
- Default: 60% wet, 40% feedback, 1/8 subdivision

### Reverb
- Wet amount: 0–100%
- Room size: Controls diffusion (hall vs. chamber)
- Decay time: 0.1s–8s tail length
- Default: 60% wet, medium room, 2s decay

### LFO (Filter Modulation)
- Shape: Sine, Triangle, Square, Sawtooth
- Rate: 1/1, 1/2, 1/4, 1/8, 1/16 (synced to BPM)
- Depth: 0–2000 Hz (modulation range)

---

## 🎮 Controls & Shortcuts

**Mouse/Touch:**
- Drag knobs vertically to adjust (up = increase, down = decrease)
- Scroll wheel on knobs for fine control
- Click cells in drum grid to toggle steps
- Touch-drag on mobile (optimized for iPad/Android)

**Keyboard:**
- **Spacebar:** Play/Stop
- **1–8:** Load progression 1–8
- **←/→:** Decrease/increase BPM
- **Q:** Fire kick pad
- **W:** Fire snare pad
- **E:** Fire bass pad
- **R:** Fire chord stab pad

---

## 📱 Mobile Optimization

- Responsive layout (flexbox, no absolute positioning)
- Safe-area padding for notched devices (iPhone X+)
- 100dvh viewport height (dynamic height units)
- Touch-action manipulation enabled
- Knobs work with touch-drag and wheel scroll
- Tested on iPad (2021+) and Android (8.0+)

---

## 🌐 Deployment

**Architecture:** Netlify (app) + Squarespace (branding)

1. Deploy `D_L_WLESS-v3_03.html` to Netlify
2. Create Squarespace site with navigation hub
3. Embed Netlify app in Squarespace via iframe or link
4. Squarespace handles: hero messaging, marketing copy, CMS
5. Netlify handles: Web Audio API context, synthesis, touch events

**Why split:** Squarespace strips JavaScript contexts; Netlify preserves Web Audio API.

---

## 📋 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome 90+ | ✓ Full | Best Web Audio API support |
| Firefox 88+ | ✓ Full | Excellent compatibility |
| Safari 14+ | ✓ Full | iOS 14+ recommended |
| Edge 90+ | ✓ Full | Chromium-based |

**Mobile:**
- iPhone/iPad: Safari (iOS 14+)
- Android: Chrome, Firefox (Android 8+)

---

## 🐛 Troubleshooting

**No sound at all?**
- Click page once (AudioContext requires user gesture)
- Check browser console (F12 → Console) for errors
- Try a different browser

**Drums but no bass?**
- Load a patch from Sounds tab first
- Check Audio Mix panel: Bass volume not at 0%
- Check Bass synth Vol knob

**Knobs unresponsive?**
- Drag vertically (up to increase, down to decrease)
- Not horizontal drag

**Audio distortion?**
- Lower Drive knob in Bass Synth
- Lower bass volume in Audio Mix panel

**Sequencer won't play?**
- Enable "Pro Mode" toggle
- Click "Sequencer" tab
- Click ▶ Play button (or Spacebar)

---

## 📄 File Specifications

| File | Size | Format | Lines | Purpose |
|------|------|--------|-------|---------|
| D_L_WLESS-v3_03.html | 220 KB | HTML5 | 3,924 | Main app |
| D_L_WLESS-v3_03-Quick-Ref.md | 9.9 KB | Markdown | 253 | Fast reference |
| D_L_WLESS-v3_03-Testing-Guide.md | 15 KB | Markdown | 407 | QA validation |
| README.txt | 22 KB | Text | 466 | Full documentation |

**Total size:** 266 KB (compressed)

---

## 🎯 Next Steps

1. **Deploy:** Upload `D_L_WLESS-v3_03.html` to Netlify
2. **Test:** Use Quick-Ref and Testing-Guide to verify all features
3. **Brand:** Create Squarespace landing page with links to app
4. **Perform:** Use with TR-8, Crave, Digitone, SP-404 rig
5. **Iterate:** Gather performer feedback and plan v4.0

---

## 📞 Support

For issues or feature requests, refer to:
- **Quick-Ref:** 2-minute troubleshooting
- **Testing-Guide:** Comprehensive issue matrix
- **README:** Deep technical documentation

---

**Project:** D_{L}@WLESS Hardware Synth Studio  
**Version:** 3.03 Final  
**Status:** Production Ready ✓  
**Maintained by:** Neville  
**Last Updated:** March 7, 2026
