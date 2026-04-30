# Workshop group work theme

## Prototype a listening experience

> **“Create a situation where listening changes what we see, understand, or feel.”**

## Option 1: The Voice Across Time Machine

### Group size

2–3 people

### Brief

Create a small TouchDesigner sketch where a voice message feels like it is coming from another time: past, future, memory, archive, ghost, or delayed transmission.

### Inputs

Use one of:

- recorded voice
- live microphone
- text-to-speech voice
- old archive audio
- whispered message
- reversed audio
- degraded recording

### TouchDesigner ingredients

- `Audio File In CHOP`
- `Audio Device In CHOP`
- `Analyze CHOP`
- `Filter CHOP`
- `Trail CHOP`
- `Noise TOP`
- `Feedback TOP`
- `Displace TOP`
- `Level TOP`
- `Text TOP`
- `Movie File Out TOP`

### Constraints

The group can include some **time effect**:

- delay
- echo
- degradation
- loop
- reverse
- memory trace
- ghost image
- old recording aesthetic

### Output

A 20–30 second visual/audio sketch.

### Discussion question

**What makes the voice feel like it belongs to another time?**

This is probably the strongest exercise for your presentation.

## Option 2: Sound as Evidence

### Brief

Create a visual interface for “investigating” a sound. The audience should feel like they are looking for a hidden clue inside the audio.

### Conceptual link

This connects to _The Conversation_, _Blow Out_, hidden messages, spectrograms, backward LPs, and Aphex Twin.

### Inputs

Use a short audio file with:

- speech
- noise
- footsteps
- room tone
- a hidden word
- a reversed phrase
- a sudden sound event

### TouchDesigner ingredients

- `Audio File In CHOP`
- `Analyze CHOP`
- `Audio Spectrum CHOP`
- `Trail CHOP`
- `TOP to CHOP` / `CHOP to TOP`
- `Level TOP`
- `Threshold TOP`
- `Text TOP`

### Challenge

Make the sound appear to reveal something:

- a word
- a shape
- a signal
- a face
- a warning
- a hidden pattern

### Output

A fake forensic listening interface.

### Discussion question

**At what point does listening become interpretation, projection, or paranoia?**

## Option 3: The Hotline

### Brief

Create a one-screen “hotline” experience. The viewer receives a voice, but cannot see the speaker. The interface should make the listener feel urgency, intimacy, or uncertainty.

### Conceptual link

This connects to _The Guilty_, _Locke_, _The Call_, _Buried_, phone booths, and voice-only drama.

### Inputs

Use:

- microphone input
- recorded phone message
- distorted speech
- emergency call style
- synthetic voice

### TouchDesigner ingredients

- `Audio Device In CHOP`
- `Audio File In CHOP`
- `Analyze CHOP`
- `Text TOP`
- `Noise TOP`
- `Feedback TOP`
- `Level TOP`
- `Switch TOP`
- simple UI buttons or keyboard triggers

### Constraints

No image of the speaker.
Only the voice, interface, text, waveform, noise, or signal can communicate the situation.

### Output

A short interactive call screen.

### Discussion question

**How much can we understand from a voice alone?**

## Option 4: Listening to the Room

### Brief

Make the room itself visible through sound. Use the microphone to translate ambient noise, silence, speech, or movement into visuals.

### Conceptual link

This connects to John Cage, Pauline Oliveros, Christina Kubisch, Janet Cardiff, and environmental listening.

### Inputs

Live microphone only.

### TouchDesigner ingredients

- `Audio Device In CHOP`
- `Analyze CHOP`
- `Math CHOP`
- `Filter CHOP`
- `Noise TOP`
- `Displace TOP`
- `Feedback TOP`
- `Level TOP`
- `Circle TOP`
- `Composite TOP`

### Constraints

The group cannot play a music file. They must use the actual room.

### Output

A “listening instrument” for the workshop space.

### Discussion question

**What did the system make you notice about the room?**

## Option 5: Collective Voice / Collective System

### Brief

Each group member contributes one small sound: a word, note, breath, clap, hum, or noise. The group combines these into one collective visual system.

### Conceptual link

This connects to Ryoji Ikeda’s distributed works, Moniker-style collective voice, Oliveros, choir logic, and dance/listening systems.

### Inputs

Each participant records:

- one word
- one vowel
- one breath
- one clap
- one tone
- one short sentence

### TouchDesigner ingredients

- multiple `Audio File In CHOP`s
- `Switch CHOP`
- `Merge CHOP`
- `Analyze CHOP`
- `Timer CHOP`
- `Composite TOP`
- `Layout TOP`
- `Feedback TOP`

### Constraints

No single voice should dominate.
The system should feel collective.

### Output

A visual choir, signal field, or multi-voice composition.

### Discussion question

**When do separate voices become one shared composition?**

## Option 6: The Listening Relay

Adaptation of the **Animation Relay** format, where participants pass projects around and each person adds a new layer. ([digitalideation.github.io](https://digitalideation.github.io/toolbox-touchdesigner/parkplatz/day01-exercises-ideas.html))

### Brief

Each group starts a simple audio-reactive sketch. Every 10–12 minutes, they pass it to another group, who must add a new “listening mode.”

### Round structure

Round 1: make sound visible
Round 2: add memory / delay / feedback
Round 3: add distortion / interference / hidden signal
Round 4: add a final title or interaction

### Output

Unexpected collective listening machines.

### Discussion question

**What changed when another group listened to your system differently?**

This one is playful and good for energy.

## Option 7: One-Minute Listening Film Festival

Adaptation of the “One-Minute Project” wrap-up challenge. ([digitalideation.github.io](https://digitalideation.github.io/toolbox-touchdesigner/parkplatz/day01-exercises-ideas.html))

### Brief

Each group exports a 10–20 second clip answering this prompt:

> **What does listening look like?**

### Categories for voting

- most intimate
- most uncanny
- most forensic
- most bodily
- most collective
- most unexpected
- best use of silence

## Sorting

| Complexity                 | Exercise                                 | Why                                                                                                                                                                                  |
| -------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **1 - Very easy**          | **One-Minute Listening Film Festival**   | Mostly about making a short output from whatever they already built. Good as a closing exercise, not a main technical challenge.                                                     |
| **2 - Easy**               | **Listening Scavenger Hunt**             | Small isolated tasks: volume to brightness, sound to scale, silence to image. Good for beginners and fast experimentation.                                                           |
| **3 - Easy / medium**      | **Listening to the Room**                | Uses live microphone input and simple audio-reactive visuals. Conceptually strong, technically manageable.                                                                           |
| **4 - Medium**             | **The Hotline**                          | Adds narrative and interface thinking. Still simple technically, but requires more decisions about mood, text, voice, and timing.                                                    |
| **5 - Medium**             | **Voice Across Time Machine**            | Needs a clearer atmosphere: delay, degradation, memory, archive, ghosting. Technically not too hard, but conceptually richer.                                                        |
| **6 - Medium / advanced**  | **Sound as Evidence**                    | More demanding because it needs to feel like investigation or decoding, not just audio-reactive visuals. Works best with spectrum, thresholds, hidden signals, text, or interaction. |
| **7 - Advanced**           | **Collective Voice / Collective System** | Requires coordinating multiple inputs or recordings. More moving parts: timing, balance, layout, collective logic.                                                                   |
| **8 - Advanced / chaotic** | **Listening Relay**                      | Technically flexible, but organizationally complex. Passing files between groups can create confusion unless the group already understands the basics.                               |