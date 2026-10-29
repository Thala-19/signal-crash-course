# Signals in Six Sessions — exam crash course

A single-page, zero-dependency interactive crash course for the digital signal
processing exam. Built from the course decks (Sessions 01–06) plus three bonus
lessons condensed from the Velardo audio-DSP lecture PDFs.

**Live site:** https://thala-19.github.io/signal-crash-course/ (GitHub Pages, main branch)

## What's inside

| Lesson | Source |
|---|---|
| 01 Introduction to Signal Processing | Course deck, Session 1 |
| 02 Data Acquisition & Signal Input | Course deck, Session 2 |
| 03 Signal Visualization | Course deck, Session 3 |
| 04 Digital Filtering | Course deck, Session 4 |
| 05 Practical Digital Filtering | Course deck, Session 5 |
| 06 Event & Feature Detection | Course deck, Session 6 |
| Bonus A — Sound & Waveforms | Audio-DSP PDF (Part 2) |
| Bonus B — Intensity, Loudness & Timbre | Audio-DSP PDF (Part 3) |
| Bonus C — Audio Signals, ADC & Quantization | Audio-DSP PDF (Part 4) |

## Features

- Condensed lesson notes with definitions, pipelines, tables and Python snippets
- 5-question quiz after every lesson (45 questions total) with instant explanations
- Shuffled answer order — the correct letter changes every run
- Mixed final check: 10 random questions from the whole pool, graded at 70% pass mark
- Progress and best scores persisted in the browser (localStorage, reset button included)
- Home-page demo of the Session 04 moving-average filter (window size adjustable)

Sessions 07–10 of the source deck set are intentionally not covered.

## Running

Everything is in `index.html` — no build step. Open it in any browser, or let
GitHub Pages serve it. Web fonts load from Google Fonts and degrade gracefully offline.
