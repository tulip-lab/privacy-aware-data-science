[![GitHub issues](https://img.shields.io/github/issues/tulip-lab/privacy-aware-data-science)](https://github.com/tulip-lab/privacy-aware-data-science/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/tulip-lab/privacy-aware-data-science)](https://github.com/tulip-lab/privacy-aware-data-science/pulls) [![GitHub stars](https://img.shields.io/github/stars/tulip-lab/privacy-aware-data-science.svg?style=social&label=Star)](https://github.com/tulip-lab/privacy-aware-data-science/stargazers/) [![Companion Lab](https://img.shields.io/badge/companion-PaDS_Lab-1f6feb?logo=github)](https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop)

---

![TULIP Lab FLIP — Fundamentals of Learning and Intelligent Processing](https://raw.githubusercontent.com/tulip-lab/pattern-classification-lab/0cad4beb88a60a3b8d288f45b35c17d7ade4381a/Assets/images/flip-banner.png)

# FLIP: Privacy-aware Data Science

**FLIP** stands for **Fundamentals of Learning and Intelligent Processing**.
This open course from [TULIP Lab](https://www.tulip.academy) develops the theory
and practice of differential privacy, from privacy attacks and noise mechanisms
to composition, private learning and advanced privacy models.

The materials have supported research students at SRM Institute of Science and
Technology, Hunan University and the University of Chinese Academy of Sciences
since 2018.

> The companion Lab is being developed. Its first two practical guides link to
> existing public SIT742 notebooks; PaDS-specific notebooks are still planned.
> The assessment dates listed below are historical references.

## Start here

- [Welcome and course orientation](S00-Induction/README.md)
- [Learning outcomes and teaching approach](S00-Induction/S00C-Logistics.md#unit-learning-outcomes)
- [Session map](#sessions)
- [Companion Lab](https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop)
- [Offerings](offerings/README.md)
- [Assessment and historical offerings](#assessment-and-offerings)
- [Teaching team and contact details](S00-Induction/S00B-Team.md#contacts)

## Offerings

| Offering | Institution | Audience | Teaching allocation | Status |
| --- | --- | --- | --- | --- |
| [SRM 2026](offerings/srm/privacy-aware-data-science/2026/README.md) | SRM Institute of Science and Technology, Kattankulathur | Elite students | 14 sessions (50 minutes each) | Syllabus approved; dates to be confirmed |

See the [offering index](offerings/README.md) for offering pages and historical
references. Each offering selects from the common course; its own syllabus
defines the scope for that cohort.

## Prerequisites

You should be comfortable with linear algebra, probability and statistics,
optimisation, and basic machine learning. Python and familiarity with arrays,
plots and train/test splits are useful for the practicals. The
[Statistical Machine Learning course](https://github.com/tulip-lab/statistical-machine-learning)
provides related background.

## Course outcomes

The [unit learning outcomes](S00-Induction/S00C-Logistics.md#unit-learning-outcomes)
cover three areas:

1. **ULO1 — Understand** differential privacy principles, privacy models and
   the balance between privacy and utility.
2. **ULO2 — Apply** privacy-preserving algorithms and mechanisms in data analysis.
3. **ULO3 — Evaluate** ethical and legal implications of data privacy.

## Companion lab site

The [PaDS Lab](https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop)
provides practical navigation and planned learning activities. Use the two
sites together:

1. read the session overview and linked lecture handout here;
2. open the corresponding practical guide when one is listed;
3. follow the upstream notebook's setup instructions and run its baseline;
4. retain the requested evidence and explain the privacy assumptions.

The initial practical path covers private exploration and budget accounting
(S05A), followed by private classification and utility (S13A). Other sessions do
not yet have a PaDS practical listed.

## Sessions

The original teaching plan allocates **100 class hours**: **72** for teaching
and **28** for presentations and discussion. The two parts below can support
separate or consecutive units; each delivery should specify its actual schedule.
Session IDs identify content, not teaching weeks.

### Privacy-aware Data Science I

| Session | Category | Conceptual overview | Public practical |
| :---: | :---: | --- | --- |
| S00 | Preliminary | [Induction](S00-Induction/README.md) | — |
| S01 | Preliminary | [Theoretical Foundations](S01-Foundations/README.md) | — |
| S02 | Core | [Data Privacy](S02-DataPrivacy/README.md) | — |
| S03 | Core | [Privacy Attacks](S03-PrivacyAttacks/README.md) | — |
| S04 | Core | [Differential Privacy](S04-DifferentialPrivacy/README.md) | Prerequisite for S05A |
| S05 | Core | [Composition](S05-Composition/README.md) | [S05A — Private exploration and accounting](https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop/S05-Composition) — planned |
| S06 | Core | [Sparse Vector Technique](S06-SVT/README.md) | — |
| S07 | Core | [Query Release and the Net Mechanism](S07-NetMechanism/README.md) | — |
| S08 | Core | [Database Update Algorithm](S08-DUA/README.md) | — |
| S09 | Core | [Propose-Test-Release and Subsample-and-Aggregate](S09-PTR/README.md) | — |
| S10 | Core | [Information Reconstruction](S10-Reconstruction/README.md) | — |

### Privacy-aware Data Science II

| Session | Category | Conceptual overview | Public practical |
| :---: | :---: | --- | --- |
| S11 | Advanced | [PATE](S11-PATE/README.md) | — |
| S12 | Advanced | [Multi-party and Local DP](S12-LDP/README.md) | — |
| S13 | Advanced | [DP Learning](S13-DPLearning/README.md) | [S13A — Private Naive Bayes and utility](https://github.com/tulip-lab/privacy-aware-data-science-lab/tree/develop/S13-DPLearning) — planned |
| S14 | Advanced | [Objective Perturbation and DP-SGD](S14-DPSGD/README.md) | — |
| S15 | Advanced | [Output Perturbation and DP Clustering](S15-DPClustering/README.md) | — |
| S16 | Advanced | [Rényi DP and zCDP](S16-Renyi/README.md) | — |
| S17 | Advanced | [Privacy Amplification](S17-Amplification/README.md) | — |

The original plan also reserves three advanced-topic slots, student
presentations and an invited talk. Their topics and timing depend on the
particular delivery. The existing activity descriptions remain available:
[orientation](S00-Induction/S00D-Assessment.md#activity-0),
[early presentation](S00-Induction/S00D-Assessment.md#activity-a),
[topic presentation](S00-Induction/S00D-Assessment.md#activity-b) and
[project discussion](S00-Induction/S00D-Assessment.md#activity-c).

## Assessment and offerings

Assessment requirements depend on the university and teaching period. Confirm
current dates, collaboration rules and submission instructions with the
[teaching team](S00-Induction/S00B-Team.md#contacts).

<a id="spiral_calendar-submission-due-dates"></a>

### Historical offering references

| Offering | Public assessment reference | Recorded deadline |
| --- | --- | --- |
| HNU 2025 | [LLM-generated privacy regulation report](S00-Induction/S00D-Assessment-HNU2025.md) | 8 October 2025 |
| SRM 2024 | [Presentation and project](S00-Induction/S00D-Assessment.md) | 18 May 2024, originally tentative; individual work |

## References

This course uses several key references or textbooks, together with relevant publications from **[TULIP Lab](https://www.tulip.academy/members)**:

- Baobao Song, Shiva Raj Pokhrel, Mengyue Deng, Qiujun Lan, Robin Ram Doss,
  Tianqing Zhu and **Gang Li**.
  [Digital Privacy Under Attack: Challenges and Enablers](https://doi.org/10.1145/3770853).
  *ACM Computing Surveys*, **58**(4), pp. 1–35, 2026 (published online in 2025).
  [Open manuscript](https://arxiv.org/abs/2302.09258).
- Cynthia Dwork and Aaron Roth.
  [The Algorithmic Foundations of Differential Privacy](https://doi.org/10.1561/0400000042).
  *Foundations and Trends in Theoretical Computer Science*, **9**(3–4),
  pp. 211–407, 2014. Now Publishers.
- Tianqing Zhu, **Gang Li**, Wanlei Zhou and Philip S. Yu.
  [Differentially Private Data Publishing and Analysis: A Survey](https://doi.org/10.1109/TKDE.2017.2697856).
  *IEEE Transactions on Knowledge and Data Engineering*, **29**(8),
  pp. 1619–1638, 2017.
- Tianqing Zhu, **Gang Li**, Wanlei Zhou and Philip S. Yu.
  [Differential Privacy and Applications](https://doi.org/10.1007/978-3-319-62004-6).
  *Advances in Information Security*, vol. **69**. Springer International
  Publishing, 2017.
- [Research Publications](https://www.tulip.academy/publication), various resources and readings

## Contributors

Thanks goes to these wonderful people :tulip:

<a href="https://github.com/tulip-lab/privacy-aware-data-science/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tulip-lab/privacy-aware-data-science" />
</a>

Made with [contributors-img](https://contrib.rocks).

## Contributing and material reuse

Report course-page corrections through the
[issue tracker](https://github.com/tulip-lab/privacy-aware-data-science/issues).
Practical corrections belong in the
[Lab issue tracker](https://github.com/tulip-lab/privacy-aware-data-science-lab/issues).
The repository's existing [MPL-2.0 licence](LICENSE) remains in place; consult
source-specific notices for linked third-party materials.

Point of contact: [Prof. Gang Li](https://github.com/tuliplab).

Prepared by :tulip: **[TULIP Lab](https://www.tulip.academy), Australia**
