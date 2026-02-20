# 3mpler (Max for Live)

**3mpler** is an experimental Max for Live device designed for soundscape exploration and rhythmic generation from a single audio source. It utilizes a triple-loop point logic where the duration of the samples directly influences the master transport of Ableton Live.

---

## 🎨 Concept
The core idea behind **3mpler** is to treat a single sample (specifically **soundscapes** and organic textures) as a rhythmic generator. By using three concurrent loop points within the same file, the device creates complex, overlapping patterns.

One of its most unique features is the **Loop-Driven Tempo**: The total duration of the loops (in milliseconds) is used to calculate time divisions, which then dynamically sets the **Ableton Live Master Tempo**.

## 🎹 Technical Features
- **Triple Playhead Engine:** Independent control over Start, Length, and Rate for three loop points.
- **Symmetrical MIDI Mapping:** - Range: **C3 to B5**.
    - **C3, C4, and C5** play the sample at its original rate.
    - All other notes shift the pitch using **F# as the symmetry axis**, allowing for balanced spectral exploration.
- **Transport Integration:** Real-time calculation of time divisions based on sample length.

## 🛠 Status: Exploratory Phase
This project is currently in a **testing/beta stage**. Some functions may feel experimental or unconventional. 

### Current Challenges (Help Wanted!):
I am specifically looking for feedback and contributions regarding:
* **Bang Quantization:** Implementing a stable way to quantize internal bangs relative to Ableton Live's transport while dealing with dynamic loop lengths.
* **Tempo Stability:** Refining the logic that updates the DAW's tempo to avoid jitter.

## 🚀 How to Test
1. Download the `.amxd` file.
2. Drop it into an Ableton Live MIDI track.
3. Load a long soundscape or sample.
4. Experiment with the three loop points and observe how the Master Tempo reacts.

**Feel free to open an Issue or a Pull Request if you have ideas on how to improve the quantization logic!**

---

## Author
**Julian Di Pietro** *Sound Artist, Composer, and Sound Designer.* Background in PD, Max/MSP, and TouchDesigner.

---
