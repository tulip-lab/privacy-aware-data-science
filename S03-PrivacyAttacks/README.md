[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Privacy--Attacks-orange)](README.md)

# Privacy Attacks

### Introduction to Privacy Attacks

In the landscape of data privacy, privacy attacks represent a critical threat to the confidentiality and integrity of sensitive information. These attacks are designed to exploit the vulnerabilities within data systems, often revealing information that was intended to remain private. Among the various types of privacy attacks, Data Reconstruction Attacks stand out due to their capacity to reverse-engineer original datasets from models or aggregated data summaries.

A Data Reconstruction Attack involves using the outputs of a machine learning model or other data summaries to recreate significant portions of the original dataset. This can lead to the exposure of sensitive details about individuals within the dataset, posing severe risks to privacy. As data processing techniques become more advanced, the potential for such attacks increases, especially in environments where large-scale data sharing and analysis are common.

While Data Reconstruction Attacks focus on recreating the data itself, other privacy attacks like Membership Inference Attacks aim to determine whether a particular individual's data was included in a model's training set. Although this type of attack is significant, it serves as just one of many privacy threats in the ever-evolving domain of data security.

These privacy attacks emphasize the urgent need for robust privacy-preserving mechanisms in data analysis and machine learning. As the complexity and scale of data processing continue to grow, so too must our efforts to develop and implement stronger safeguards against these types of vulnerabilities.


## :notebook_with_decorative_cover: Lecture Slides Handouts

- [Lecture: Privacy Attacks](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP22.pdf) 


![Readings](https://img.shields.io/badge/PaDS-Readings-red)


##### Fundamental Law of Information Recovery

- Cynthia Dwork, Adam Smith, Thomas Steinke, and Jonathan Ullman. [Exposed! A Survey of Attacks on Private Data](https://www.annualreviews.org/content/journals/10.1146/annurev-statistics-060116-054123). Annual Review of Statistics and Its Application, 4:61-84, 2017.

- Irit Dinur and Kobbi Nissim. [Revealing information while preserving privacy](https://crypto.stanford.edu/seclab/sem-03-04/psd.pdf). In Proceedings of the 22nd ACM Symposium on Principles of Database Systems, PODS '03. ACM, 2003

- Cynthia Dwork, Frank McSherry, Kobbi Nissim, and Adam Smith. [Calibrating noise to sensitivity in private data analysis](https://link.springer.com/chapter/10.1007/11681878_14). In Conference on Theory of Cryptography, TCC '06, 2006.


#####  Discussion of Reconstruction Attacks    

- https://differentialprivacy.org/reconstruction-theory/ 
- https://differentialprivacy.org/diffix-attack/
- https://tech.vijayp.ca/of-taxis-and-rainbows-f6bc289679a1
- https://chriswhong.com/open-data/foil_nyc_taxi/

