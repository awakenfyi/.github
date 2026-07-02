# Lyra Labs — awaken.fyi

**Coherence infrastructure for the age of agents.** One formula, measured at three depths:

```
L = x − x̂        the residual: what's actually present, minus what the default predicts
O = x̂ − x        overhang: the part of the default that outlived what's present
```

```
 depth            x (present)              x̂ (default)             O > 0 means
 ─────────────────────────────────────────────────────────────────────────────
 activation   →   internal pull            output logits            unbacked confidence
 response     →   what the moment needs    the template             performing
 procedure    →   the present warrant      the inherited stance     overhang
```

Every AI system drifts the same way: the default (`x̂`) keeps winning after the reason for it is gone. Lyra measures that drift; xOP refuses to reward it. The rule that does not move:

> **`false_positive_on_warranted == 0`** — never override a state that is still warranted. A system may improve only by surfacing more honestly, never by agreeing more.

## Start here

| If you want to… | Go to |
|---|---|
| Understand the formula in five minutes | [lyra → FORMULA.md](https://github.com/awakenfyi/lyra/blob/main/FORMULA.md) |
| Measure coherence inside a transformer's forward pass | [lyra](https://github.com/awakenfyi/lyra) — JSD coherence, drift memory, silence permission |
| Scan text for conduct drift right now | [xop-kit](https://github.com/awakenfyi/xop-kit) — 7 deterministic Guards, CLI, 95/95 fixtures |
| Read the standard behind the Guards | [xop](https://github.com/awakenfyi/xop) — the contract, the gate, the governance |
| Test a detector against blind human gold | overhang-bench *(coming — held-response-constant minimal pairs)* |

## Where the evidence actually stands

We publish status honestly, per component, and the misses alongside the hits: the Guards are deterministic and rule-tested; the gate has **not yet** been validated against blind human labels; the 250-run experiment series is a self-research loop, not an independent benchmark. Every claim on every README is limited to the evidence attached to it. The evidence ladder (`DESIGNED → FIELD-VALIDATED`) never skips rungs, and no model output becomes ground truth.

**Receipts, not vibes.** MIT licensed. Contributions welcome — authoring one minimal pair for the benchmark is the ideal first PR.

*[awaken.fyi](https://awaken.fyi)*
