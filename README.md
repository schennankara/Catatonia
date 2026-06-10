# Catatonia Scales — CQS · PCRS · BFCRS

A de-identified bedside calculator for catatonia rating scales, built for inpatient
child & adolescent psychiatry.

- **CQS** — Catatonia Quick Screen (4 signs; any one positive → full rating)
- **PCRS** — Pediatric Catatonia Rating Scale (20 items, /60, threshold ≥9)
- **BFCRS** — Bush–Francis Catatonia Rating Scale (23 items, /69; screening items 1–14, ≥2 positive)

## Features
- Live scoring with screen-positive flags
- Longitudinal tracking per patient (same day or across days) with trend sparklines
- Lorazepam-challenge comparison (≥50% reduction = positive response)
- One-tap copy of a formatted result block for pasting into the EMR
- JSON export / import for backup

## Privacy
**No PHI.** The tool stores only initials, age, sex, date/time, and a free-text comment,
and all data is held locally in the user's own browser — nothing is sent to a server.
Do not enter names, MRNs, or dates of birth.

## Disclaimer
A clinical decision-support aid, not a diagnostic device. Clinical judgement governs.
The PCRS item set approximates the published scale (Benarous et al., 2016); verify exact
anchors against the source before clinical use.

## Usage
Open `index.html` in any browser. To host it, this repo is set up for GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root).
