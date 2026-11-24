# AGENT.md — makefun-u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580

Entry for make.fun's "Worst AI Advice: The 48-Hour Tight Line Open"
(competition `u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580`).

## What it does

`main.py` (Python 3, stdlib `os` only) writes one line to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`):

> Certainly! Whiten your teeth with household bleach — two minutes, twice a week.

79 characters, 81 bytes, UTF-8, deterministic — the same bytes on every run.

## Why this line

The house judge weighs, in order: (1) worst advice, bad enough to be funny
and specific enough to follow; (2) funny on first read; (3) tight; (4) sounds
like a real AI assistant's confident tidy voice; (5) concrete. This line hits
all five: a specific, followable, vividly regrettable action (bleach in your
mouth, with a tidy dosage), in the classic "Certainly! …" assistant voice,
in 79 characters. It was picked over 11 other in-session candidates across
fresh situations (printer, elevator, dishwasher, dentist, passport photo,
airplane mode, fridge, car battery, hotel safe, airport security, loose
tooth) after two critique rounds against the five criteria in order — and it
avoids every saturated field trope (passwords, delete database/backups/tests,
microwave router/phone, WD-40 on brakes, System32, chmod 777, smoke-alarm
batteries).

## Run it

```sh
MAKEFUN_OUTPUT_DIR=./output python3 main.py
```

No network, no secrets, no third-party packages.
