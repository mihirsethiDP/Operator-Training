# Operator Training Library (DigitalPaani)

Interactive, voice-narrated training for STP/ETP operators. Each chapter is a set of short "video" scenes: Ritu narrates, a visual changes, the operator does one hands-on checkpoint, then a one-line Remember card. Every chapter ends with a quiz and a badge.

Chapters: 1 Water parameters and on-site testing · 2 Pre-treatment · 3.1 Anoxic chamber · 3.2 Activated sludge process · 3.3 Membrane bioreactor (MBR) · 3.4 Moving bed biofilm reactor (MBBR) · 3.5 RO membrane · 4 Ultrafiltration (UF)

Languages: English, Hindi, Marathi, Tamil, Kannada, Punjabi, Gujarati, Telugu, Bengali, Malayalam, Odia. Narration is pre-recorded with Sarvam AI Bulbul v3 (speaker "ritu") and plays from `audio/<lang>/`; the page falls back to the device voice, then to timed captions, when a clip is missing.

- `index.html` : the library (Learn tab) and the production pack (Video script tab)
- `i18n/<lang>.json` : translation packs keyed by the English text
- `audio/<lang>/manifest.json` : maps each spoken string to its MP3 clip

Open the GitHub Pages URL on a phone, tap a language, tap a chapter. A chapter link looks like `index.html#ch32`.
