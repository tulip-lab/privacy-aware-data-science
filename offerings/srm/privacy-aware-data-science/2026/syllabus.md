# Syllabus — SRM Privacy-aware Data Science 2026

[Offering home](README.md) · [Course portal](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop)

**Syllabus approved — 27 October 2026.** Dates and delivery format
are to be confirmed.

## Offering overview

| Item | Detail |
| --- | --- |
| Institution | SRM Institute of Science and Technology |
| Campus / location | Kattankulathur, Kanchipuram Dist, Chennai |
| Course | Privacy-aware Data Science |
| Year | 2026 |
| Audience | Elite students; advanced undergraduate preparation assumed |
| Instructor | Prof. Gang Li |
| Local contact (SRM) | G Suseela, Associate Professor |
| Teaching allocation | **14 sessions × 50 minutes = 700 minutes (11 hours 40 minutes)** |
| Structure | 12 foundation sessions, followed by 2 advanced overview sessions |

## Course description

This course develops the theoretical foundations of differential privacy
(DP), starting with privacy attacks and the limitations of de-identification.
Students study the privacy definition, neighbouring datasets, sensitivity,
the Laplace, exponential and Gaussian mechanisms, and composition. The final
two sessions introduce private machine learning through PATE and DP-SGD.

The foundation topics form a continuous sequence. Each occupies two
50-minute sessions, allowing time for the assumptions, mathematical reasoning
and worked examples. Short calculations and questions are integrated into
lectures. The course concludes by connecting these foundations to advanced
learning methods.

## Prerequisites

Students should be comfortable with conditional probability, expectation,
variance, logarithms, exponentials and basic vector norms. Familiarity with
Laplace and Gaussian distributions, classification and stochastic gradient
descent is useful. No previous study of DP or measure theory is assumed.
Python is useful for optional further exploration, but is not required for
following the lectures.

## Learning outcomes

The offering learning outcomes (OLOs) specify the expected achievement for
this short course and map to the [common course outcomes][outcomes].

| Outcome | Students should be able to… | Evidence within lectures | Alignment |
| --- | --- | --- | --- |
| OLO1 — Explain | Distinguish major privacy attacks, state a DP guarantee with its protected unit and adjacency relation, and explain its scope. | Attack analysis, interpretation of the definition and a simple counterexample | ULO1 |
| OLO2 — Calculate | Derive sensitivity for bounded examples, calibrate basic mechanisms and calculate the privacy cost of multiple releases. | Worked count, histogram, mean, private-selection and composition calculations | ULO1, ULO2 |
| OLO3 — Compare | Select a mechanism for a stated release task and compare privacy and utility under matched assumptions. | Short explanations of mechanism choice, error and budget allocation | ULO1, ULO2 |
| OLO4 — Interpret | Explain where PATE and DP-SGD introduce privacy protection and identify their main data-access and accounting assumptions. | An annotated teacher–student pipeline and DP-SGD algorithm trace | ULO1, ULO2 |

## Teaching sequence

`L01`–`L14` denote the fourteen 50-minute sessions in teaching order.
`Sxx` denotes the existing common-course resource identifiers. Reading labels
refer to the list below; each two-session foundation topic receives
**100 minutes**, including its worked examples.

| Sessions | Topic | First session | Second session | Reading and course resources |
| --- | --- | --- | --- | --- |
| L01–L02 | Privacy attacks and the limits of de-identification | Identifiers and quasi-identifiers; linkage attacks; auxiliary information; limitations of anonymity-based protection. | Aggregate reconstruction; membership and attribute inference; distinguish the attacker's knowledge, target and conclusions in worked cases. | [T1][t1], [T2][t2]; [S02][s02], [S03][s03] |
| L03–L04 | DP definitions and sensitivity | Randomised mechanisms; add/remove and replacement adjacency; the ε-DP inequality; protected records versus people; counterexamples. | L1 and L2 global sensitivity; bounded contributions; sensitivity of counts, histograms, sums and fixed-size means; post-processing. | [T2][t2], [T3][t3], [R1][r1]; [S04][s04] |
| L05–L06 | The Laplace mechanism and numeric releases | Laplace noise calibration; the density-ratio proof; scalar and vector-valued releases; the role of public bounds. | Worked histogram, sum and mean releases; error and sample-size effects; clipping bias; choosing ε and interpreting the privacy–utility trade-off. | [T2][t2], [T3][t3], [R1][r1]; [S04][s04] |
| L07–L08 | The exponential mechanism and private selection | Fixed candidate sets, utility functions and score sensitivity; normalisation; sampling probabilities and the privacy argument. | A worked finite selection example; probability ratios, utility-loss bounds and confidence levels; data-dependent support pitfalls; comparison with numeric perturbation. | [T2][t2], [T3][t3], [R1][r1]; [S04][s04] |
| L09–L10 | Approximate DP and the Gaussian mechanism | The (ε,δ)-DP definition; interpretation of δ; L2 sensitivity and Gaussian calibration under explicitly stated conditions. | Bounded scalar and vector examples; Gaussian versus Laplace error under matched assumptions; dimension, sample size and the limits of each calibration rule. | [T2][t2], [T3][t3], [R1][r1]; [S04][s04] |
| L11–L12 | Composition and privacy budgets | Sequential composition; repeated and adaptive releases; parallel composition on disjoint protected units; pure-DP group privacy. | Budget allocation across a release sequence; privacy–utility implications; a supplied advanced-composition bound and its delta terms; synthesis of the mechanism-selection principles. | [T2][t2], [T3][t3], [R1][r1]; [S05][s05] |

The final **two sessions (100 minutes total)** provide an advanced overview.
They draw on the preceding mechanisms and composition results.

| Session | Topic | Scope | Reading and course resources |
| --- | --- | --- | --- |
| L13 | PATE — Private Aggregation of Teacher Ensembles | Disjoint teacher training; noisy aggregation of teacher votes; student learning; a small voting example; the privacy boundary and accounting for repeated label queries. | [T3][t3], [R2][r2]; [S11][s11] |
| L14 | DP-SGD — Differentially Private Stochastic Gradient Descent | Per-example clipping; Gaussian noise and averaging; sampling rate, noise multiplier and training steps; interpretation of a supplied privacy report; comparison with PATE. | [T3][t3], [R3][r3]; [S14][s14] |

**Total: 12 × 50 + 2 × 50 = 700 minutes.** Breaks and independent reading
are additional to this contact time.

## Depth of treatment

The foundation sessions develop definitions, proof ideas and numerical
examples. Students should be able to reproduce basic sensitivity, mechanism
and composition calculations. Gaussian calibration and advanced composition
are taught with their validity conditions; lengthy concentration proofs are
not required.

PATE and DP-SGD are taught at the level of algorithm structure, assumptions
and privacy interpretation. Subsampling is introduced only as needed to
explain a training privacy report. Local DP and randomized response, PTR,
full RDP/zCDP theory, general amplification theorems and private clustering
are further-study topics outside the scheduled core.

## Teaching and learning

Lectures combine explanation, board-work derivations, worked examples and
short comprehension questions. Examples use public or synthetic data and
explicit assumptions about the protected unit, public bounds and released
outputs. Feedback focuses on correct reasoning, calculations and limitations.

The [PaDS Lab][lab] offers optional follow-up guides for
[private exploration and budget accounting][lab05] and
[private Naive Bayes and utility][lab13]. They link to existing SIT742
notebooks; the PaDS adaptations remain in development. These resources support
independent exploration outside the fourteen scheduled sessions.

Formal assessment arrangements, if required, are to be confirmed with SRM.

## Reading

TULIP Lab's publications provide the main reading sequence. Read the portions
relevant to each lecture topic; entire books and papers are not required.
The foundational reference and original PATE/DP-SGD papers supplement that
sequence where a specific definition, theorem or algorithm is needed.

### Main reading — TULIP Lab

- **T1.** Baobao Song, Shiva Raj Pokhrel, Mengyue Deng, Qiujun Lan,
  Robin Ram Doss, Tianqing Zhu and Gang Li.
  [Digital Privacy Under Attack: Challenges and Enablers][t1].
  *ACM Computing Surveys*, **58**(4), pp. 1–35, 2026
  (published online in 2025).
  Main reading for L01–L02: attacks on anonymous data, statistical aggregates
  and learning models. [Open manuscript](https://arxiv.org/abs/2302.09258).
- **T2.** Tianqing Zhu, Gang Li, Wanlei Zhou and Philip S. Yu.
  [Differentially Private Data Publishing and Analysis: A Survey][t2].
  *IEEE Transactions on Knowledge and Data Engineering*, **29**(8),
  pp. 1619–1638, 2017. Provides the organising view of private publishing
  and analysis for the foundation sequence.
- **T3.** Tianqing Zhu, Gang Li, Wanlei Zhou and Philip S. Yu.
  [Differential Privacy and Applications][t3].
  *Advances in Information Security*, vol. **69**.
  Springer International Publishing, 2017.
  Main course book: selected material from *Preliminary of Differential
  Privacy*, the data-publishing and data-analysis chapters, and
  *Differentially Private Deep Learning*.

### Supporting references

- **R1.** Cynthia Dwork and Aaron Roth.
  [The Algorithmic Foundations of Differential Privacy][r1].
  *Foundations and Trends in Theoretical Computer Science*, **9**(3–4),
  pp. 211–407, 2014. Now Publishers.
  Chapters 2–3 support the formal definitions, mechanisms and composition.
  [Author-hosted copy](https://www.cis.upenn.edu/~aaroth/privacybook.html).
- **R2.** Nicolas Papernot, Martín Abadi, Úlfar Erlingsson, Ian Goodfellow
  and Kunal Talwar.
  [Semi-supervised Knowledge Transfer for Deep Learning from Private Training Data][r2].
  *5th International Conference on Learning Representations (ICLR)*, 2017.
  The PATE framework and noisy teacher aggregation for L13.
  [Open manuscript](https://arxiv.org/abs/1610.05755).
- **R3.** Martín Abadi, Andy Chu, Ian Goodfellow, H. Brendan McMahan,
  Ilya Mironov, Kunal Talwar and Li Zhang.
  [Deep Learning with Differential Privacy][r3].
  *Proceedings of the 2016 ACM SIGSAC Conference on Computer and
  Communications Security (CCS)*, pp. 308–318. ACM, 2016.
  Algorithm 1 and the privacy-accounting discussion for L14.
  [Open manuscript](https://arxiv.org/abs/1607.00133).

[outcomes]: https://github.com/tulip-lab/privacy-aware-data-science/blob/develop/S00-Induction/S00C-Logistics.md#unit-learning-outcomes
[s02]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S02-DataPrivacy
[s03]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S03-PrivacyAttacks
[s04]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S04-DifferentialPrivacy
[s05]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S05-Composition
[s11]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S11-PATE
[s14]: https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S14-DPSGD
[lab]: https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop
[lab05]: https://github.com/tulip-lab/privacy-aware-data-science-lab/blob/develop/S05-Composition/README.md
[lab13]: https://github.com/tulip-lab/privacy-aware-data-science-lab/blob/develop/S13-DPLearning/README.md
[t1]: https://doi.org/10.1145/3770853
[t2]: https://doi.org/10.1109/TKDE.2017.2697856
[t3]: https://link.springer.com/book/10.1007/978-3-319-62004-6
[r1]: https://doi.org/10.1561/0400000042
[r2]: https://openreview.net/forum?id=HkwoSDPgg
[r3]: https://doi.org/10.1145/2976749.2978318
