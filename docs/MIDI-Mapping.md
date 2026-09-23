# MIDI key maps

**English** · [Chinese](MIDI-Mapping.zh-CN.md) · [Back to the library](../README.md)

These mappings were read from the supplied `.sf2` preset and sample zones. MIDI numbers are authoritative; octave labels vary between music applications. Note names below use **MIDI 60 = C4**.

## Presets

| File | Bank | Program, zero-based |
| :--- | ---: | ---: |
| Ukulele (Original with Chords).sf2 | 0 | 1 |
| All other files | 0 | 0 |

If your application numbers programs from 1, select program 2 for the chord Ukulele and program 1 for the other files.

## Full range

Windsong Lyre, Floral Zither, Vintage Lyre, Nightwind Horn, Ukulele, Lingering Euphonia, Leaping Spirit Piano, Harmonic Keys, and Vodyanitsa each map **MIDI 0–127** in their plain-named `.sf2` files.

## Original notes

| Version | Playable single-note MIDI numbers |
| :--- | :--- |
| Lingering Euphonia (Original with Chords) | 48, 50, 52, 53, 55, 57, 59, 60, 62, 64, 65, 67, 69, 71 |
| Ukulele (Original with Chords) | 60, 62, 64, 65, 67, 69, 71, 72, 74, 76, 77, 79, 81, 83 |

## Built-in chords

Each listed key triggers one of the instrument's original chord samples. Chord labels below come from the embedded sample names. In the full-range files, these same MIDI keys play ordinary single notes instead.

| Chord | Lingering Euphonia | Ukulele |
| :--- | :---: | :---: |
| C major | 72 · C5 | 84 · C6 |
| D minor | 74 · D5 | 86 · D6 |
| E minor | 76 · E5 | 88 · E6 |
| F major | 77 · F5 | 89 · F6 |
| G major | 79 · G5 | 91 · G6 |
| A minor | 81 · A5 | 93 · A6 |
| G dominant seventh | 83 · B5 | 95 · B6 |

The trigger key for the G7 sample is B5 or B6; the trigger key's pitch name does not rename the chord.

## Percussion

| Instrument | Playable MIDI notes |
| :--- | :--- |
| Arataki's Great and Glorious Drum | 60 · C4, 62 · D4 |
| Djem Djem Drum | 60 · C4, 62 · D4, 64 · E4, 65 · F4, 72 · C5, 74 · D5, 76 · E5, 77 · F5 |

These SoundFonts store their drum presets in bank 0, program 0. Select the supplied preset explicitly if your player automatically switches a percussion channel to another bank.
