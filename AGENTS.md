# FL Studio Kick Builder — Codex instructions

Build an original, interactive uptempo hardcore kick sound-design learning tool for FL Studio users.

## Milestone 1
Create a TypeScript + Vite browser application with a functional kick synthesizer using Web Audio or deterministic offline DSP. Include editable base frequency, pitch drop, pitch decay, amplitude decay, transient/click and drive; playback after a user gesture; waveform preview; and export to valid 24-bit PCM WAV at 44.1 or 48 kHz.

## Quality rules
- Every visible sound control must audibly affect synthesis, not just a mock UI.
- Keep DSP independent from UI, with unit tests for finite samples, duration and WAV headers.
- Explain each parameter and listening exercise in Dutch.
- Support experimentation with punch, body and tail; prioritize deep tweakability over presets.
- Do not bundle or recreate copyrighted reference audio.
- Keep final playback level safe and avoid accidental clipping.
- Document setup, build, tests and limitations in README.

## Later milestones
Multiband distortion, oversampling, editable pitch envelopes, A/B comparison, spectral analysis, kick-to-riser/screech/impact FX, presets and guided lessons. Investigate VST3 only after the standalone engine is stable.
