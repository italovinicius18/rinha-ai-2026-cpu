# rinha-ai-2026-cpu — variant v2

Submission branch only. Config of [italovinicius18/rinha-ai-2026-ignore](https://github.com/italovinicius18/rinha-ai-2026-ignore).

**v2 config**: NPROBE=5 + squeeze data-prep CPU (0.05 → 0.03) giving 0.02 extra to each API replica (0.40 → 0.41). HAProxy stays at the safe 0.15 floor.

Same images: `italovinicius18/rinha-2026-api:v1`, `italovinicius18/rinha-2026-data-prep:v1`.
