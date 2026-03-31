# 🎛️ Audio Lab

Application web d'outils audio professionnels — entièrement dans le navigateur, sans installation.

## Fonctionnalités

### Audio Tools
- **Signal Generator** — Oscillateur (Sine, Square, Saw, White/Pink noise) avec oscilloscope temps réel
- **EQ** — Égaliseur 7 bandes paramétrique avec visualisation de courbe interactive (drag & drop)
- **Compressor** — Compresseur dynamique avec courbe de transfert, VU-mètres et vue activité
- **Gate / Expander** — Noise gate avec seuil, range, attack/hold/release
- **Reverb** — Plusieurs types (Chamber, Plate, Spring, Room, Hall, Church) + IR convolution
- **Delay** — Multi-styles (Stereo, Ping-Pong, Tape Echo, Analog BBD…)
- **Modulation** — Chorus, Phaser, Flanger, Tremolo, Vibrato
- **Tape Saturation** — Émulation bande magnétique (wow, flutter, noise, bias)
- **Loudness Meter** — Analyse LUFS (Momentary, Short-term, Integrated, LRA) + True Peak
- **Calibration** — Table de référence SPL studio (EBU R128, SMPTE, broadcast…)

### Music Tools
- **Tuner** — Accordeur chromatique via micro (YIN algorithm), multi-instruments
- **Métronome** — Scheduler Web Audio précis, tap tempo, signatures rythmiques
- **Accords** — Bibliothèque d'accords guitare/piano avec écoute
- **Beat Sequencer** — Séquenceur 6 pistes × 16 pas avec sons synthétisés
- **Transform** — Détection BPM/tonalité, changement de tempo et de pitch

### Ear Training
- 9 modules : EQ, Compression, Loudness, Gate, Pan, Reverb, EQ Mirror, Balance Memory, Tone Training
- 5 niveaux de difficulté · 20 questions par niveau

## Utilisation

Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, Safari).
Aucune installation, aucun serveur requis.

## Technologies

- Web Audio API (nodes, OfflineAudioContext, AnalyserNode)
- Canvas 2D (visualisations temps réel)
- Vanilla JS / HTML5 / CSS3
