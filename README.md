# When KPIs Lie
## Governance Signals for AI-Optimized Call Centers

📄 **Paper (PDF):**  
**When KPIs Lie: Governance Signals for AI-Optimized Call Centers** — *Gina Aulabaugh, February 2026* :contentReference[oaicite:0]{index=0}

---

## What this paper argues (in one breath)
When a KPI becomes **a performance target**, **an incentive lever**, and **a machine-learning label** at the same time, it stops behaving like a neutral measurement. Under AI acceleration, this creates a reinforcing loop where proxy metrics improve while durable customer outcomes quietly degrade. :contentReference[oaicite:1]{index=1}

This paper proposes a control layer—**Trust Signal Health**—to detect and constrain that drift before it becomes systemic. :contentReference[oaicite:2]{index=2}

---

## The core diagnosis: KPI Self-Reinforcement Drift
Modern call centers increasingly operate as a closed loop:

**Proxy KPI → Incentive pressure → Behavior shifts → Proxy-based labels → Model retraining → Recommendations → More proxy optimization**

The scarier part is that nobody has to “cheat.” The architecture does it by itself once the feedback loop gets fast enough. :contentReference[oaicite:3]{index=3}

---

## The proposed solution: an integrity control layer
This paper introduces governance signals designed to sit *next to* performance KPIs—not replace them.

**Performance dashboards optimize. Integrity signals constrain.** :contentReference[oaicite:4]{index=4}

### Governance signals defined
- **DAR — Delayed Adverse Rate**: instability after “successful” interactions :contentReference[oaicite:5]{index=5}  
- **DRL — Downstream Remediation Load**: drift in post-success workload distribution :contentReference[oaicite:6]{index=6}  
- **DOV — Durable Outcome Validation**: decay in predictive validity over time :contentReference[oaicite:7]{index=7}  
- **POR — Proxy Overfit Ratio**: proxy improvement outpacing durable outcome improvement :contentReference[oaicite:8]{index=8}  
- **TER — Terminal Exit Rate**: terminal exits following “success” (listed in abstract as a governance signal) :contentReference[oaicite:9]{index=9}  
- **SII — System Integrity Index**: weighted composite integrity constraint (with optional gating) :contentReference[oaicite:10]{index=10}  

**Key point:** **SII is not a performance score.** It’s a *velocity regulator*—a veto condition when KPI acceleration is no longer aligned with durable outcomes. :contentReference[oaicite:11]{index=11}

---

## Why this matters beyond call centers
This isn’t “a telecom thing.” It’s an **architecture thing**.

Any environment where a metric is simultaneously:
- a compensation driver,
- a ranking input,
- a dashboard target,
- and a machine-learning label,

…is vulnerable to the same distortion pattern. :contentReference[oaicite:12]{index=12}

---

## How to use this repository
This repository is intentionally minimal: it exists to host and version the paper.

### Suggested structure
```text
<repo-root>/
  When_KPIs_Lie__Governance_Signals_for_AI_Optimized_Call_Centers.pdf
  README.md
  LICENSE   (optional)
```
MIT License

Copyright (c) 2026 Gina Aulabaugh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

🌐 **PixelKraze Analytics (Portfolio):** https://pixelkraze.com/?utm_source=github&utm_medium=readme&utm_campaign=portfolio&utm_content=homepage
