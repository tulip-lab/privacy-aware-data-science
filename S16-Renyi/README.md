[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-RDP--zCDP-orange)](README.md)

# RDP and zCDP

Renyi Differential Privacy (RDP) and Zero-Concentrated Differential Privacy (zCDP) are two advanced variants of the traditional differential privacy model, each offering refined approaches to quantifying and managing privacy risks in data analysis.

Renyi Differential Privacy, introduced by Mironov, builds upon the classical notion of differential privacy by employing the Renyi divergence, a measure from information theory. RDP is characterized by its use of the Renyi divergence parameter, α, which provides a more nuanced control over the privacy-utility trade-off compared to the single ε parameter in traditional differential privacy. This flexibility allows for more efficient privacy accounting, especially in complex data analysis tasks involving multiple steps or in adaptive data analysis scenarios. RDP is particularly valuable in scenarios where a fine-grained analysis of the privacy guarantees is required, offering tighter control over the privacy budget.

Zero-Concentrated Differential Privacy, on the other hand, focuses on the concentration of the privacy loss around its expected value. zCDP provides a more refined analysis of the tails of the privacy loss distribution, ensuring that large deviations from the expected privacy loss are extremely unlikely. This model is beneficial in applications where it's crucial to bound the worst-case privacy loss. zCDP is particularly effective in scenarios involving complex data processing pipelines, as it allows for more accurate and tight privacy loss calculations over successive computations.

Both RDP and zCDP represent significant advancements in the field of differential privacy, addressing specific limitations of the traditional model and providing more precise tools for privacy-preserving data analysis. They highlight the ongoing evolution in the field, aiming to offer more flexible and mathematically rigorous frameworks to manage privacy risks in the era of big data.

## :notebook_with_decorative_cover: Lecture Slides Handouts  

- [Lecture: RDP and zCDP](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP35.pdf) 

