
UVA is an experimental  VCV → VOCALOID3 Japanese DB  generator.
---

## Status

UVA is experimental.

It is not intended to be a fully automatic commercial-quality converter. What it does is quite obvious, ain't it?
## The works of it
The tool works by converting each valid VCV alias into a split articulation with its own .wav, .trans, and .seg files. 
It uses the original UTAU timing as a base, then refines C/V boundaries with audio analysis, including loudness, spectral changes, noise detection, burst detection, voicing, and formant cues.
UVA also includes a local WebUI for reviewing and correcting the generated segmentation.
---
## What you still have to do
- Make a new singer
- Segment and add articulations to the db
- Add stationaries to the db
