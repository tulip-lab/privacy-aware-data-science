[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-DP--Composition-orange)](README.md)

# Composition of Differential Privacy


The Composition Theorems in Differential Privacy are crucial for understanding how privacy guarantees accumulate when multiple differential privacy mechanisms are applied, either sequentially or in parallel. This concept is vital for managing and maintaining privacy guarantees across multiple data analyses or queries.

The Standard Composition Theorem addresses the scenario where multiple differentially private mechanisms are applied sequentially. It states that the total privacy loss is at most the sum of the individual losses from each mechanism. For example, if two mechanisms each offer ε-differential privacy, their sequential application results in at most 2ε-differential privacy.

Advanced Composition, a refinement of the Standard Composition, offers tighter bounds on the cumulative privacy loss, particularly beneficial for a large number of mechanisms. It incorporates a parameter δ, allowing a slight probability of exceeding the calculated privacy loss.

Element Level Privacy, a variation of differential privacy, is concerned with the privacy of individual entries in the dataset. It ensures that the inclusion or exclusion of any single data point does not significantly affect the outcome of the analysis.

Group Privacy extends differential privacy to groups of entries, providing privacy guarantees for groups of data points. This is particularly important when considering correlated data or when individuals contribute multiple data points.

Privacy Budget in differential privacy is a crucial concept that quantifies the allowable privacy loss. Each query or operation consumes part of this budget, and once depleted, no further queries are allowed. Managing the privacy budget is essential for ensuring that the cumulative privacy loss remains within acceptable limits.

Understanding these aspects of composition in differential privacy is fundamental for implementing privacy-preserving data analysis in a manner that ensures robust and quantifiable privacy guarantees while enabling meaningful insights from data.

## :notebook_with_decorative_cover: Lecture Slides Handouts

- [Lecture: Composition of Differential Privacy](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP24.pdf) 

