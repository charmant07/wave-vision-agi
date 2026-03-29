# Wave Vision AGI

Biologically-inspired one-shot vision system.
No backpropagation. No pretrained weights.

## Results
- 5-Way 1-Shot Omniglot: 76.1% (K=1) → 92.4% (K=5)
- Stochastic resonance: +8.8pp accuracy FROM noise
- Temporal prediction: 100% after 3 observation cycles
- Self-tuning: adjusts 3 parameters autonomously

## Run it
Open wave_vision_agi.ipynb in Google Colab.
All dependencies install automatically.

## Architecture
Stage 1 — Perception   (FFT + Gabor + V1/V4)
Stage 2 — Memory       (Hebbian prototypes)
Stage 3 — Recall       (cosine similarity)
Stage 4 — Learning     (Hebbian update rule)
Stage 5 — Temporal     (transition matrix + prediction)
Stage 6 — Self-tuning  (performance monitor + auto-tune)
