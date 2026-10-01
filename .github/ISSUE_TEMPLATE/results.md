---
name: Share your results
about: Ran the lab (or your own variant)? Post your numbers so others can compare
title: "[results] <model> · <what you changed>"
labels: results
---

**What you ran:** <!-- e.g. v2 notebooks 01–04 unchanged; or v2 with Qwen3-1.7B; or your own domain -->

**Model and adapter:** <!-- e.g. Qwen2.5-0.5B-Instruct, LoRA r16 / alpha 32, 7 modules -->

**What you changed from the repo:** <!-- data mix, hyperparameters, prompt, retrieval settings, judge… -->

**Hardware and time:** <!-- e.g. Apple M4 24 GB, MPS, float32, SFT took 119 min -->

**Results** (copy from `v2/runs/final_eval/scoreboard.csv` or the notebook tables):

| Eval set | Model | Condition | Accuracy (answerable) | Hallucination | Over-refusal | Correct refusals (unanswerable) |
|---|---|---|---|---|---|---|
| dev_v2 | | rag_rerank | | | | |
| dev_v2 | | engineered | | | | |
| dev_v1 | | rag_rerank | | | | |

**Scorer:** <!-- Gemini judge (model version, calibration agreement) and/or the keyword scorer -->

**What surprised you / what you would try next:**

**Your own domain?** <!-- if you replaced Meridian with your data: what kind of domain, how many facts/documents, how you built the unanswerable set -->
