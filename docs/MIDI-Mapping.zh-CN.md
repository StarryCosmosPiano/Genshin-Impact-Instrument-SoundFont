# MIDI 按键与和弦表

[English](MIDI-Mapping.md) · **简体中文** · [返回音源目录](../README.zh-CN.md)

以下映射依据所提供 `.sf2` 文件的预设及采样区域整理。请以 **MIDI 编号**为准；不同软件的八度命名可能不同。本文采用 **MIDI 60 = C4**。

## 预设

| 文件 | Bank | Program，从 0 编号 |
| :--- | ---: | ---: |
| Ukulele (Original with Chords).sf2／悠可琴原版带和弦 | 0 | 1 |
| 其他所有文件 | 0 | 0 |

如果软件的 Program 从 1 开始显示，悠可琴原版带和弦版请选择 2，其他音源请选择 1。

## 全音域

Windsong Lyre（风物之诗琴）、Floral Zither（镜花之琴）、Vintage Lyre（老旧的诗琴）、Nightwind Horn（晚风圆号）、Ukulele（悠可琴）、Lingering Euphonia（「余音」）、Leaping Spirit Piano（跃律琴）、Harmonic Keys（谐律键琴）及 Vodyanitsa（沃雅妮莎）的无括号音源版本，均覆盖 **MIDI 0–127**。

## 原版单音

| 版本 | 单音 MIDI 编号 |
| :--- | :--- |
| Lingering Euphonia (Original with Chords)／「余音」原版带和弦 | 48, 50, 52, 53, 55, 57, 59, 60, 62, 64, 65, 67, 69, 71 |
| Ukulele (Original with Chords)／悠可琴原版带和弦 | 60, 62, 64, 65, 67, 69, 71, 72, 74, 76, 77, 79, 81, 83 |

## 原版自带和弦

每个按键触发该乐器原本自带的和弦采样，下表和弦名称依据文件内采样名称整理。在全音域版本中，相同 MIDI 按键演奏的是普通单音。

| 和弦 | Lingering Euphonia／「余音」 | Ukulele／悠可琴 |
| :--- | :---: | :---: |
| C major／C 大三和弦 | 72 · C5 | 84 · C6 |
| D minor／D 小三和弦 | 74 · D5 | 86 · D6 |
| E minor／E 小三和弦 | 76 · E5 | 88 · E6 |
| F major／F 大三和弦 | 77 · F5 | 89 · F6 |
| G major／G 大三和弦 | 79 · G5 | 91 · G6 |
| A minor／A 小三和弦 | 81 · A5 | 93 · A6 |
| G dominant seventh／G 属七和弦 | 83 · B5 | 95 · B6 |

G7 和弦的触发键是 B5 或 B6；触发按键的音名并不代表和弦根音。

## 鼓音源

| 乐器 | 可用 MIDI 按键 |
| :--- | :--- |
| Arataki's Great and Glorious Drum／荒泷・盛世豪鼓 | 60 · C4, 62 · D4 |
| Djem Djem Drum／聚聚鼓 | 60 · C4, 62 · D4, 64 · E4, 65 · F4, 72 · C5, 74 · D5, 76 · E5, 77 · F5 |

这两个鼓音源的预设位于 Bank 0、Program 0。如果播放器会自动为打击乐通道切换 Bank，请手动选中所提供的鼓音源预设。
