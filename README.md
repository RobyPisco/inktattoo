# ◆ InkTattoo — Audio Waveform Tattoo Generator

> Turn any audio file into a tattoo-ready waveform artwork. Export as SVG, high-res PNG or PDF — ready to hand to your tattoo artist.

**[→ Try it live](https://robypisco.github.io/inktattoo/)** · Made by [piscofactory](https://github.com/RobyPisco)

---

## Features

- **4 visualization styles** — Horizontal bars, Circular radial, Rorschach mirror, Constellation
- **Organic tremor** — seeded RNG for hand-drawn feel, regenerate with one click
- **Flexible export** — SVG (vector), PNG at 300 DPI, PDF at custom physical dimensions (cm)
- **Real-time playback** — play your audio with a synced playhead overlay
- **Undo / Redo** — full 60-step history (Ctrl+Z / Ctrl+Y)
- **Presets** — save and reload your favourite settings
- **Zero dependencies** — pure vanilla JS + Web Audio API, no framework, no build step

## Styles

| Horizontal | Circular | Rorschach | Constellation |
|---|---|---|---|
| Bars, mirrored, strokes, filled silhouette | Radial burst from a central ring | Mirror-symmetric ink blot | Dots connected by lines |

## Usage

Open `index.html` in any modern browser — no server required.

```
git clone https://github.com/RobyPisco/inktattoo.git
cd inktattoo
# just open index.html
```

1. Drag & drop an audio file (MP3, WAV, OGG, M4A, AAC)
2. Choose a visualization style and tweak the controls
3. Set the physical width in cm for your tattoo
4. Export → SVG / PNG (300 dpi) / PDF

## Tech

- Web Audio API — audio decoding & amplitude extraction
- SVG — vector waveform rendering with Catmull-Rom spline smoothing
- jsPDF — PDF export
- localStorage — preset persistence

---

*Made with ♥ by **piscofactory***
