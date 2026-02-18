# 🎵 Ambient Composer

A browser-based tool for generating evolving chord progressions and bass lines for ambient music — designed with hardware synths in mind.

**[→ Open the Tool](https://craigdamlo.github.io/Ambient-Composer/ambientchord.html)**

---

## What It Does

Ambient Composer generates looping chord progressions with intelligent voice leading, paired with a synchronized bass line. Everything runs in the browser — no installs, no sign-ups.

**Chord Progressions**
- Choose a key, mode (Major / Minor / Dorian), and progression length
- Voicing modes: Fixed, Varied, or Random — from triads up to 11th chords
- Smart Inversions minimize voice movement between chords and across the loop boundary
- Loop quality score shows how smoothly the progression wraps

**Bass Line**
- Five styles: Root Only, Root + Fifth, Walking, Arpeggiated, Pedal Point
- Configurable octave, density, syncopation, rests, and octave jumps
- Regenerates automatically whenever the chord progression changes

**Timeline View**
- Combined piano-roll-style visualization showing chords (purple) and bass (blue) together on a single responsive canvas
- Fully scales to your browser window — no scrolling required

---

## Usage

1. Open the [tool](https://craigdamlo.github.io/Ambient-Composer/ambientchord.html) in any modern browser
2. Select a key and mode
3. Hit **↻ Generate New** to create a progression
4. Dial in your bass line style and settings
5. Use **📋 Copy to Clipboard** to export the full note list for your synth or DAW

The exported text includes chord names, voicings, inversions, note names, beat durations, and the complete bass line — everything you need to program a sequencer by hand.

---

## Running Locally

No build step required. Just clone and open:

```bash
git clone https://github.com/craigdamlo/Ambient-Composer.git
cd Ambient-Composer
open ambientchord.html
```

---
