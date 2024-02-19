[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Privacy--Attacks-orange)](README.md)

# Privacy Attacks

Privacy attacks in the realm of data security are sophisticated methods by which malicious entities exploit vulnerabilities to gain unauthorized access to sensitive information. Among these, Membership Inference Attacks and Data Reconstruction Attacks are particularly notable for their potential to compromise individual privacy.

Membership Inference Attacks focus on determining whether a specific individual's data was used in a machine learning model's training dataset. Attackers use the model's output to infer the presence of individual data points in the training set. This type of attack poses significant risks, especially in scenarios involving sensitive data like medical records or financial information. For instance, if an attacker can infer the presence of a person’s data in a model trained on a dataset of disease records, it can lead to privacy breaches and potential discrimination.

Data Reconstruction Attacks, on the other hand, aim to recreate the original dataset or significant portions of it from a model or aggregated data summaries. These attacks exploit the model or data summaries to reverse-engineer the original data, which can lead to the exposure of sensitive attributes of individuals in the dataset. This is particularly concerning in the age of big data and advanced analytics, where vast amounts of detailed information are often processed and shared.

Both these types of attacks underscore the growing challenges in data privacy. They highlight the need for robust privacy-preserving techniques in data analysis and machine learning, such as differential privacy, secure multiparty computation, and homomorphic encryption, to safeguard against such vulnerabilities. As data-driven technologies advance, the importance of evolving and implementing stronger privacy protection measures becomes increasingly critical.

## :notebook_with_decorative_cover: Lecture Slides Handouts

- [Lecture: Privacy Attacks](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP22.pdf) 
