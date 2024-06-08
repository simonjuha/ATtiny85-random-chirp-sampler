# ATtiny85 Random Chirp Sample Player

This project is designed to play random chirp samples on an ATtiny85 microcontroller. It uses a PWM output to generate sound from raw PCM data stored in program memory. The chirp samples are played with various effects, including a folding wave effect and a low-fidelity mode.

## Features

- Plays random part of a chirp sample from program memory.
- Gate-triggered playback with configurable effects.
- Fold wave effect for sound inversion.
- Low-fidelity mode with adjustable playback speed.
- Utilizes a ring buffer for efficient sample playback.

## Wiring

- PB1: PWM output
- PB2: Trigger input
- PB3: Fold wave setting
- PB0: LoFi setting
- PB4: ADC input for sample size control

Schematics can be found [here](https://github.com/simonjuha/ATtiny85-random-chirp-sampler/blob/main/doc/schematics.pdf).

## Changing the sample
Use [this](https://tomeko.net/online_tools/file_to_hex.php?lang=en) to convert any file to usable sample data. You can export headerless raw wav files from Audacity etc.
