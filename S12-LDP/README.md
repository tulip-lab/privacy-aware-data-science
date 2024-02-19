[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-MDP--LDP-orange)](README.md)

# Multi-Party Differential Privacy and Local Differential Privacy

Multi-Party Differential Privacy and Local Differential Privacy are two important variants of the differential privacy framework, each addressing unique challenges in preserving privacy in different data sharing and collection scenarios.

Multi-Party Differential Privacy (MPDP) is designed for situations where data is distributed across multiple parties or databases, and these parties want to collaboratively analyze their combined data without revealing their individual datasets to each other. This scenario is common in joint research projects or consortiums where each entity holds sensitive data. MPDP involves mechanisms and protocols that allow for the collective analysis of data, ensuring that the privacy of individual records in each party's dataset is protected, even as useful insights are gleaned from the aggregate data. Techniques such as secure multi-party computation and homomorphic encryption are often employed in MPDP to facilitate private data aggregation and analysis.

Local Differential Privacy (LDP), on the other hand, shifts the privacy-preserving process to the data collection stage. In LDP, each data point is privatized at the source, i.e., before it is shared with the aggregator or analyst. This is done by applying a privacy-preserving mechanism, such as adding noise, directly to the data on the user’s device. As a result, the analyst never accesses the raw data, only the already privatized version. LDP is particularly relevant for large-scale data collection applications, such as usage data collection by tech companies, where direct trust between the data collector and the individual may not be established.

Both MPDP and LDP extend the reach of differential privacy to more complex and realistic data environments. They represent crucial advancements in the field, addressing the need for privacy-preserving data analysis in decentralized and distributed data settings, and ensuring individual privacy is maintained in the face of large-scale data collection efforts.

## :notebook_with_decorative_cover: Lecture Slides Handouts  

- [Lecture: MDP & LDP](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP29.pdf) 

