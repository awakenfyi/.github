# awaken.fyi

**The quality gate for AI agents — testable rules for what ships, before it ships.**

Like CI for agent judgment. One folder. Red/green before release.

```bash
pip install git+https://github.com/awakenfyi/xop-kit
echo "All set — consider it booked." | xop scan -
```

---

Agents don't usually fail because they can't do the work.
They fail because they round up:

- **"Done."** — The venue was never confirmed. The deploy never finished.
- **"73% of customers prefer us."** — No source. They wrote it because it fit.
- **"You're right, I'll drop that."** — It was a real objection. They caved anyway.

These are predictable. Detectable. Testable.

---

## The folder

```
my-agent/
├── conduct/
│   ├── done-means-verified.md   # can't say "done" without the receipt
│   ├── claims-need-receipts.md  # can't ship a statistic without a source
│   └── fixtures/
│       ├── rule.hold.json       # case where it must hold
│       └── rule.drop.json       # case where it must drop
```

```bash
xop init my-agent   # scaffold the folder
xop test            # red/green proof before ship
```

A rule without both test cases hasn't been found yet. The pair is the definition.

---

## Why we built this

<!-- Morgan: rewrite this in your own words — one paragraph, first person, the actual moment.
     What kept breaking? What correction kept coming back? Why a folder instead of a prompt?
     See REPO-CLARITY-STANDARD.md for the worked example. -->

---

## The repos

| | |
|---|---|
| **[xop-kit](https://github.com/awakenfyi/xop-kit)** | The tool — scan any output, scaffold any agent, test any rule |
| **[xop](https://github.com/awakenfyi/xop)** | The standard — what the rules mean, how they're tested, the gate |
| **[lyra](https://github.com/awakenfyi/lyra)** | The research — measuring the gap inside the model's forward pass |
| **[xop-labs](https://github.com/awakenfyi/xop-labs)** | Domain rules in the wild — marketing, design, more |

---

*Alpha. The scanners work and are rule-tested (95/95 fixtures). The gate claim (`fp_on_warranted == 0`) requires a blind-label pilot we haven't run yet. [Receipts, not vibes.](https://github.com/awakenfyi/xop) MIT licensed.*

*[awaken.fyi](https://awaken.fyi)*
