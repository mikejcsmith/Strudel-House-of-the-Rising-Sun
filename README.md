# Strudel-House-of-the-Rising-Sun

[latest Strudel](https://strudel.cc/#Ly8gMS4gVEVNUE8gKDYvOCBGZWVsIC0gU2xvdyBTd2luZykKc2V0Y3BzKDAuNik7CgovLyAtLS0gMi4gVEhFIERBVEEgKEJhY2t0aWNrcyBmb3IgQnVsbGV0cHJvb2YgUGFyc2luZykgLS0tCmNvbnN0IGNob3JkU3RyaW5nID0gYAogIFthMixjMyxlMyxhM10KICBbYzMsZTMsZzMsYzRdCiAgW2QzLGdiMyxhMyxkNF0KICBbZjMsYTMsYzQsZjRdCiAgW2EyLGMzLGUzLGEzXQogIFtjMyxlMyxnMyxjNF0KICBbZTMsZ3MzLGIzLGU0XQogIFtlMyxnczMsYjMsZTRdCmA7Cgpjb25zdCBiYXNzU3RyaW5nID0gYAogIGExIGMyIGQyIGYyCiAgYTEgYzIgZTIgZTIKYDsKCi8vIC0tLSAzLiBUSEUgSU5TVFJVTUVOVFMgLS0tCgovLyBHVUlUQVIgKFRoZSAiUmFrZSIgVHJpcGxldCkKLy8gV2UgdXNlIHRoZSBbMCAxIDJdIHRyaXBsZXQgdG8gc2ltdWxhdGUgdGhlIHBpY2sgc3dlZXBpbmcgYWNyb3NzIHN0cmluZ3MKY29uc3QgZ3VpdGFyID0gbm90ZShjaG9yZFN0cmluZykuc2xvdygxNikKICAucygidHJpYW5nbGUiKQogIC5hcnAoIjAgWzAgMSAyXSAyIDMgMiAxIikgCiAgLmxlZ2F0bygwLjUpLnN1c3RhaW4oMCkuZGVjYXkoMC4xNSkgLy8gQ3Jpc3AgcGx1Y2tzCiAgLmxwZigxNTAwKQogIC5nYWluKDAuNSk7CgovLyBPUkdBTiAoTGVzbGllIFNwZWFrZXIgU2ltdWxhdGlvbikKY29uc3Qgb3JnYW4gPSBub3RlKGNob3JkU3RyaW5nKS5zbG93KDE2KQogIC5zKCJnbV9yb2NrX29yZ2FuIikKICAucGhhc2VyKDcpLnBoYXNlcmRlcHRoKDAuNikgLy8gU3dpcmxpbmcgZWZmZWN0CiAgLnN1c3RhaW4oMSkKICAuZ2FpbigwLjYpOwoKLy8gQkFTUyAoV2FybSBGb3VuZGF0aW9uKQpjb25zdCBiYXNzID0gbm90ZShiYXNzU3RyaW5nKS5zbG93KDE2KQogIC5zKCJzcXVhcmUiKQogIC5scGYoMzAwKS5kZWNheSgwLjQpLnN1c3RhaW4oMCkKICAuZ2FpbigwLjYpOwoKLy8gLS0tIDQuIFRIRSBEUlVNUyAoU2VwYXJhdGVkIE1peCkgLS0tCgovLyBLSUNLICYgU05BUkUgKEJhY2tib25lKQpjb25zdCBraWNrU25hcmUgPSBzKCJiZCB%2BIH4gc2QgfiB%2BIikKICAubigzKQogIC5nYWluKDAuMik7CgovLyBISS1IQVRTIChEeW5hbWljczogT05FLXR3by10aHJlZSBGT1VSLWZpdmUtc2l4KQpjb25zdCBoaWhhdHMgPSBzKCJoaDowLjUgaGg6MC4yIGhoOjAuMiBoaDowLjUgaGg6MC4yIGhoOjAuMiIpCiAgLm4oMTQpCiAgLmN1dCgxKQogIC5nYWluKDAuMyk7CgovLyBDUkFTSCAoVGhlIExvb3AgTWFya2VyKQovLyBIaXRzIG9uIEJlYXQgMSwgdGhlbiB3YWl0cyAxNiBiYXJzCmNvbnN0IGNyYXNoID0gcygiY3IiKQogIC5zbG93KDE2KQogIC5nYWluKDAuNCk7IAoKLy8gLS0tIDUuIFBMQVlCQUNLIC0tLQpzdGFjaygKICBraWNrU25hcmUsCiAgaGloYXRzLAogIGNyYXNoLAogIGJhc3MsCiAgb3JnYW4sCiAgZ3VpdGFyCik%3D){:target="_blank"}


This is a fantastic idea. Documenting the "Why" behind the code is just as important as the code itself, especially in a live coding environment where syntax quirks can be tricky.

Here is a complete **README.md** file formatted for GitHub. You can create a file named `README.md` in your repository and paste this Markdown content directly into it.

***

# 🏠 House of the Rising Sun (Strudel Interpretation)

This repository contains a live-coding interpretation of **"House of the Rising Sun"** (inspired by The Animals' version), written in [Strudel](https://strudel.cc/).

It demonstrates how to handle **6/8 compound time**, **generative arpeggiation**, and **vintage sound synthesis** (Hammond Organ/Leslie Speaker) using pure code.

## 🎵 How to Play
1. Copy the code from `rising_sun.js` (or the main code file).
2. Go to [Strudel.cc](https://strudel.cc/).
3. Paste the code into the editor.
4. Press `Ctrl + Enter` (or `Cmd + Enter`) to run.

---

## 🏗️ System Architecture

The code is structured to be "Bulletproof"—prioritizing stability and timing synchronization over brevity.

### 1. Data Separation
We separate the musical data (Notes/Chords) from the instrument logic.
- **`const chordString`**: Uses specific 4-note voicings to ensure the Arpeggiator triggers correctly.
- **`const bassString`**: Separate monophonic root notes for the bassline to avoid muddy polyphony.

### 2. The "Slow Grid" Method
We use `.slow(16)` immediately after loading the note data.
- The song is built on a 16-bar progression.
- By slowing the pattern to `16` cycles, we create a fixed grid where **1 Cycle = 1 Bar**.
- This allows the Arpeggiator (`.arp`) to subdivide that bar precisely into 6 notes (6/8 time).

---

## 🧠 Lessons Learned (Strudel REPL Limitations)

During the development of this track, we identified several specific constraints within the Strudel Web REPL. The code in this repo is optimized to work around these issues.

### 1. The `.layer()` Instability
* **Issue:** Using `.layer(settings)` to apply sound parameters often results in `[eval] error: n is not a function`.
* **Solution:** We use **Direct Chaining**. All parameters (`.s()`, `.gain()`, `.lpf()`) are chained directly to the `note()` function.

### 2. "Zombie" Variables
* **Issue:** Defining single-letter variables (e.g., `const n = ...` or `const s = ...`) conflicts with internal Strudel functions, breaking the session until a browser refresh.
* **Solution:** We use descriptive variable names (e.g., `guitar`, `organ`, `chordData`).

### 3. The Arpeggiator Octave Wrap
* **Issue:** When `.arp()` runs out of notes (e.g., requesting index 3 on a 3-note triad), it wraps to the start *without* shifting the octave up.
* **Solution:** We use **Explicit 4-Note Voicings**.
    * *Bad:* `[a, c, e]` (Index 3 wraps to low A).
    * *Good:* `[a, c, e, a]` (Index 3 is explicitly high A).

### 4. Note Masking / Re-triggering
* **Issue:** When repeating notes quickly (e.g., end of one bar -> start of next bar), the browser sometimes fails to re-trigger the sound, resulting in silence.
* **Solution:** We apply **`.legato(0.5)`** and **`.sustain(0)`**. This forces a silence gap between notes, ensuring the envelope resets for a crisp attack.

### 5. The "Sample & Hold" Effect Issue
* **Issue:** Standard `.pan()` only calculates position at the *start* of a note. For long sustained chords, the sound sits statically in one ear.
* **Solution:** To create the "Leslie Speaker" swirl, we use **`.phaser()`**. This is a post-processing effect that modulates the audio continuously, creating movement even within a sustained note.

### 6. Sample Syntax
* **Issue:** The colon syntax for General MIDI (e.g., `gm:rock_organ`) is unreliable in some network environments.
* **Solution:** We use the underscore alias `gm_rock_organ`, which proved more robust.

---

## 🎹 Sound Design Breakdown

| Instrument | Source | Technique |
| :--- | :--- | :--- |
| **Guitar** | `triangle` | Subtractive synthesis (`lpf`) with `.arp("0 1 2 3 2 1")` to mimic 12-string picking. |
| **Organ** | `gm_rock_organ` | Uses `.phaser(7)` to simulate a rotating Leslie speaker cabinet. |
| **Bass** | `square` | Low-passed at 300Hz to remove digital buzz, providing a warm foundation. |
| **Drums** | `bd`, `sd` | Programmed in groups of 6 (`bd ~ ~ sd ~ ~`) to establish the 6/8 Waltz feel. |
| **Crash** | `cr`| Triggered once every 16 bars (.slow(16)) to mark the top of the loop. |

---

*Code developed with the assistance of Strudel Helper AI.*
