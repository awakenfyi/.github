<h1 align="center">L = x − x̂</h1>

<p align="center"><em>Coherence-guided inference. Open operating rules.</em></p>

<p align="center">
<a href="https://awaken.fyi">awaken.fyi</a> · MIT License
</p>

---

**Two lines under one brand:**

**Lyra** — the inference core. Measures the gap between a model's internal direction and its output. Coherence metric, drift memory, coherence-aware decoding. `L = x − x̂`

**Lyra xOP** — the operating rules family. An open format for reusable AI judgment rules, with a reference implementation that runs them.

### Repos

| Repo | What |
|------|------|
| [**xop**](https://github.com/awakenfyi/xop) | xOP Standard — open format for reusable AI operating rules. Contract, spec, catalog, Guards. |
| [**xop-kit**](https://github.com/awakenfyi/xop-kit) | xOP Kit — reference implementation. 7 Guards, CLI, 95/95 fixtures. `pip install -e .` |
| [**lyra**](https://github.com/awakenfyi/lyra) | Lyra — coherence metric, drift memory, inference interventions. `pip install lyra-ai` |
| [**auto-awakening**](https://github.com/awakenfyi/auto-awakening) | 250-run autonomous research loop: behavioral optimization at inference time. |

> **Alpha, honest:** every xOP starts at `DESIGNED`. Status climbs a ladder — `DESIGNED → EVALUATION-READY → RULE-TESTED → HUMAN-EVALUATED → FIELD-VALIDATED`. No step is skipped. No model output becomes ground truth.

---

<p align="center"><strong>Lyra Labs</strong> · Morgan Sage · 2026<br><a href="https://awaken.fyi">awaken.fyi</a></p>
