![Genshin Impact Instrument SoundFonts](assets/banner.svg)

# Genshin Impact Instrument SoundFonts

**English** · [简体中文](README.zh-CN.md)

Bring the sounds of Teyvat to your MIDI keyboard. A collection of Genshin Impact instruments and Vodyanitsa vocals in **SoundFont 2 / `.sf2`** format, with English filenames and a bilingual instrument index.

原神乐器与沃雅妮莎人声音源合集，提供全音域版本、原版带和弦版本及鼓音源。[阅读中文说明 →](README.zh-CN.md)

**[Download all SoundFonts · ZIP](https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/releases/download/v1.0.0/Genshin-Impact-Instrument-SoundFonts-v1.0.0.zip)** · [Release notes](https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/releases/latest) · [MIDI key maps](docs/MIDI-Mapping.md) · [Browse files](soundfonts)

| Collection | Full MIDI range | Original with chords | Percussion | Uncompressed audio files |
| :---: | :---: | :---: | :---: | :---: |
| **13 files** | **9 files** | **2 files** | **2 files** | **228.70 MiB** |

## Choose a version

- **Full range:** all **128 MIDI notes, 0–127**, are mapped. The filename is simply `Instrument Name.sf2`, with no range suffix or parentheses. This describes keyboard coverage, not 128 separately recorded samples.
- **Original with Chords:** the original instrument notes **plus the chords built into the original in-game instrument**. Only these versions use `(Original with Chords)` in their filenames. Their mapped keys follow the supplied original layout; they are not the full-range versions.
- **Percussion:** the two drums retain their supplied drum-key mappings and use plain English filenames. See the [MIDI key maps](docs/MIDI-Mapping.md) for the playable keys.

For example, `Lingering Euphonia.sf2` is the full-range version; `Lingering Euphonia (Original with Chords).sf2` contains the original notes and built-in chords.

## SoundFont library

Click a filename to download that individual `.sf2` file.

### Full range · MIDI 0–127

| Download SoundFont | Chinese name | Size |
| :--- | :--- | ---: |
| [Windsong Lyre.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Windsong%20Lyre.sf2) | 风物之诗琴 | 11.30 MiB |
| [Floral Zither.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Floral%20Zither.sf2) | 镜花之琴 | 25.71 MiB |
| [Vintage Lyre.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Vintage%20Lyre.sf2) | 老旧的诗琴 | 69.09 MiB |
| [Nightwind Horn.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Nightwind%20Horn.sf2) | 晚风圆号 | 31.38 MiB |
| [Ukulele.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Ukulele.sf2) | 悠可琴／尤克里里 | 6.88 MiB |
| [Lingering Euphonia.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Lingering%20Euphonia.sf2) | 「余音」 | 9.31 MiB |
| [Leaping Spirit Piano.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Leaping%20Spirit%20Piano.sf2) | 跃律琴 | 16.24 MiB |
| [Harmonic Keys.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Harmonic%20Keys.sf2) | 谐律键琴 | 18.51 MiB |
| [Vodyanitsa.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Vodyanitsa.sf2) | 沃雅妮莎人声 | 18.39 MiB |

### Original with chords

| Download SoundFont | Chinese name | Size |
| :--- | :--- | ---: |
| [Lingering Euphonia (Original with Chords).sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Lingering%20Euphonia%20%28Original%20with%20Chords%29.sf2) | 「余音」 | 9.31 MiB |
| [Ukulele (Original with Chords).sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Ukulele%20%28Original%20with%20Chords%29.sf2) | 悠可琴／尤克里里 | 10.62 MiB |

### Percussion

| Download SoundFont | Chinese name | Size |
| :--- | :--- | ---: |
| [Arataki's Great and Glorious Drum.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Arataki%27s%20Great%20and%20Glorious%20Drum.sf2) | 荒泷・盛世豪鼓 | 78.6 KiB |
| [Djem Djem Drum.sf2](https://raw.githubusercontent.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/main/soundfonts/Djem%20Djem%20Drum.sf2) | 聚聚鼓 | 1.88 MiB |

The source names “风物琴” and “谐律钢琴” correspond to **Windsong Lyre / 风物之诗琴** and **Harmonic Keys / 谐律键琴**. See the complete [filename and translation reference](docs/File-Names.md).

## Getting started

1. Download an individual `.sf2` above or the [complete ZIP package](https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/releases/download/v1.0.0/Genshin-Impact-Instrument-SoundFonts-v1.0.0.zip), then extract the ZIP if needed.
2. Load the `.sf2` in a SoundFont-compatible synthesizer, sampler, or music application.
3. Select its preset and route your MIDI keyboard or MIDI track to it.
4. For the original-with-chords versions and drums, use the mapped notes in the [MIDI reference](docs/MIDI-Mapping.md).

**Preset selection:** all supplied files use bank **0**. `Ukulele (Original with Chords).sf2` uses program **1**; every other file uses program **0**. These are zero-based values. A player that counts from 1 may display them as programs **2** and **1**, respectively.

If a key is silent, check the selected preset and the file's mapped notes above.

### More download options

- [Download the repository ZIP](https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/archive/refs/heads/main.zip) for the current files and documentation.
- [Browse the `soundfonts/` folder](soundfonts) and use the file page's **Download raw file** button.
- Git users can clone the repository directly; **Git LFS is not required**.

```sh
git clone https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont.git
```

## File integrity and credits

All 13 SoundFonts are published byte-for-byte as supplied, with filenames standardized for this collection. Sample data, presets, and embedded metadata are preserved. [SHA256SUMS.txt](SHA256SUMS.txt) lists file checksums; [catalog.json](catalog.json) provides names, versions, sizes, and MIDI mapping information.

Collection maintained by [StarryCosmosPiano](https://github.com/StarryCosmosPiano). Original game audio: **Genshin Impact / HoYoverse / miHoYo**. Embedded author fields in the supplied SoundFonts credit **StarryCosmos** and **Best**; those credits remain in the files.

Found a broken download or a mapping issue? [Open an issue](https://github.com/StarryCosmosPiano/Genshin-Impact-Instrument-SoundFont/issues) with the filename, application, and MIDI note number.
