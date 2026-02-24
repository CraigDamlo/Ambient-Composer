# 🎵 Ambient Composer

A browser-based tool for generating evolving chord progressions and bass lines for ambient music — designed with hardware synths in mind.

**[→ Open the Tool](https://craigdamlo.github.io/Ambient-Composer/ambientchord.html)**

---

## What It Does

Ambient Composer generates a complete harmonic foundation — chords with intelligent voice leading, a synchronized bass line, and in-browser audio preview. Everything runs in the browser with no installs or sign-ups.

**Quick Mood**
- Two independent selectors that configure the tool in one click
- **Tempo Feel** (Slow / Mid / Fast) — sets BPM, change rate, timing complexity, bass style, density, and envelope attack/release
- **Tone** (Dark / Neutral / Bright) — sets mode (Minor / Dorian / Major), voicing complexity, and envelope decay/sustain
- Defaults to Mid + Neutral; all nine combinations produce a distinct character
- Individual settings can still be tweaked freely after picking a mood

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
- Combined piano-roll-style visualization showing chords (purple) and bass (blue) on a single responsive canvas
- Each note displays as a duration bar so you can see exactly how long it's held
- Hover over any note for details — chord name, voice, voicing type, inversion, and beat duration
- Fully scales to your browser window — no scrolling required

**Playback**
- In-browser audio preview using sine wave oscillators with reverb
- Full ADSR envelope controls (Attack, Decay, Sustain, Release) for the chord layer
- **Sustain Repeated Notes** — when a pitch carries over between chords, it holds as one continuous tone rather than restarting (on by default)
- BPM slider (20–120, default 60) with optional looping
- A playhead cursor sweeps across the timeline in sync with playback

**Export**
- **Copy to Clipboard** — full text export with chord names, voicings, inversions, note names, beat durations, and the complete bass line
- **Download MIDI** — standard Type-1 MIDI file with two tracks (Chords + Bass), ready to drop into any DAW or hardware sequencer

---

## Usage

1. Open the [tool](https://craigdamlo.github.io/Ambient-Composer/ambientchord.html) in any modern browser
2. Pick a **Tempo Feel** and **Tone** to set the overall character, or skip straight to the individual settings
3. Hit **↻ Generate New** to create a progression
4. Dial in your bass line style and settings
5. Preview with **▶ Play** — adjust BPM and ADSR envelope to taste
6. Export via **📋 Copy to Clipboard** or **⬇ Download MIDI**

---

## Running Locally

No build step required. Just clone and open:

```bash
git clone https://github.com/craigdamlo/Ambient-Composer.git
cd Ambient-Composer
open ambientchord.html
```

---
