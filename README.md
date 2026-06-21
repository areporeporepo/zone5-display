# zone5-display

Public display artifacts for Anh Nguyen's Zone 5 cardio tracker, embedded on
<https://web.stanford.edu/~qanh/>. Rebuilt by a GitHub Action; do not edit by hand.

## Files
- `zone5.svg` — contribution-style grid, last 26 weeks. Lit squares = Zone 5 days.
- `data.json` — peak HR, day count, current streak, and today's paper.
- `workouts.csv` — the open dataset: `date,zone,maxHR,minutes`.

## Methods
Sessions captured on Apple Watch. A day counts as **Zone 5** when peak heart
rate exceeds **171 bpm**. `maxHR` is blank for sessions logged before HR capture
was added; peak HR shows once real values flow in.

Open n=1 dataset, published under Anh Nguyen's name. CC BY 4.0.
