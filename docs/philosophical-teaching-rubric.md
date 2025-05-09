# Evaluating Philosophical Teachings  
*A scoring rubric for The Common Path “Wisdom Canon”*

---

## 1. Scoring Rubric

| Dimension | 1 pt *(Low)* | 3 pts *(Medium)* | 5 pts *(High)* | Evidence Guide |
|-----------|--------------|------------------|---------------|----------------|
| **Universality** | Isolated to one culture or period. | Appears in multiple cultures **or** modern psychology. | Independently emerges across ≥ 3 cultures **and** maps to well-replicated psychological findings. | • Cross-cultural surveys<br>• Anthropological meta-analyses |
| **Coherence** | Requires metaphysical claims that conflict with science or contradict other core teachings. | Mostly compatible with empirical evidence but has unresolved tensions. | Fully compatible with current science **and** dovetails with existing Common Path principles. | • Peer-reviewed literature<br>• Philosophical analysis |
| **Practical Leverage** | Weak or anecdotal impact on well-being/behavior. | Moderate impact supported by qualitative or small-sample studies. | Large, replicable effect on behavior or mental health in RCTs **or** long-standing pragmatic traditions. | • Clinical trials<br>• Longitudinal studies<br>• Historical outcomes |

**Composite Score**  
\[
\text{Total} = U \times w_U \;+\; C \times w_C \;+\; P \times w_P
\]

Default weights \(w_U = w_C = w_P = 1\).  
Adjust weights in special contexts (e.g., youth curriculum might set \(w_P = 2\)).

---

## 2. Rating Procedure

1. **Desk Review** – Curator gathers primary sources & empirical studies.  
2. **Expert Panel** – Interdisciplinary reviewers (philosophy, psych, anthropology) assign provisional scores.  
3. **Community Feedback** – Pilot study-circle trials; collect reflections & metrics.  
4. **Revision & Ratification** – Update scores; publish in Canon.  
5. **Biennial Audit** – Re-evaluate as new evidence emerges.

All scoring sheets and references live in `/data/teaching-scores/`.

---

## 3. Example Scorecard

| Teaching | U | C | P | Total /15 |
|----------|---|---|---|-----------|
| Three Doors of Liberation | 4 | 5 | 4 | **13** |
| Stoic Dichotomy of Control | 5 | 5 | 3 | **13** |
| Growth Mindset | 3 | 5 | 5 | **13** |
| Law of Attraction | 1 | 1 | 2 | **4** |

*Scores use equal weights; see raw sheets for citations.*

---

## 4. Tier Classification

| Tier | Range | Canon Status |
|------|-------|--------------|
| **Core Insight** | 12-15 | Included in primary curriculum |
| **Supplemental** | 8-11 | Optional study, noted caveats |
| **Anecdotal / Review** | ≤ 7 | Archive; not in teaching rotation |

---

## 5. Contribution Guide (Pull Requests)

1. Fork repo and add a new file under `/proposals/<teaching-name>.md`.  
2. Provide a 150-word summary **plus** preliminary U/C/P justification with citations.  
3. Submit PR; template triggers CI script that checks formatting and adds to the review queue.

---

*Maintained by the Wisdom Canon Working Group | v0.3 (2025-05-09)*
