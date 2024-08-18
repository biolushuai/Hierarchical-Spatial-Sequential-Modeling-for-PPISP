# Hierarchical-Spatial-Sequential-Modeling-for-PPISP


# Abstract
Protein-protein interactions play a fundamental role in biological systems. Accurate detection of protein-protein interaction sites (PPIS) remains a challenge. And, the methods of PPIS prediction based on biological experiments are expensive. Recently, a lot of computation-based methods have been developed and made great progress. However, current computational methods only focus on one form of protein, using only protein spatial conformation or primary sequence, and ignore the protein’s natural hierarchical structure. Here, we propose a novel network architecture, **HSSPPISP**, through **H**ierarchical and **S**patial-**S**equential modeling of protein for **P**rotein-**P**rotein **I**nteraction **S**ites **P**rediction. In this network, we represent protein as a hierarchical graph, in which a node in the protein is a residue (residue-level graph) and a node in the residue is an atom (atom-level graph). Moreover, we design a spatial-sequential block for capturing complex interaction relationships from spatial and sequential forms of protein. We evaluate HSSPPISP on public benchmark datasets and the predicting results outperform the comparative models. This indicates the effectiveness of hierarchical protein modeling and also illustrates that HSSPPISP has a strong feature extraction ability by considering spatial and sequential information at the same time.


## 1. Datasets and trainded models
The datasets used for training HSSPPISP and the trained models mentioned in our manuscrpit can be downloaded from https://pan.baidu.com/s/1R1d3ixNpBgTuCY0WvRMftQ （Password: PBRS）

## 2. Requirement
* Python = 3.9.10  
* Pytorch = 1.10.2  
* Scikit-learn = 1.0.2

## 3. Usage


## 4. Citation
If you are 




## 5. References
[1] 


## 6. Contact
For questions and comments, feel free to contact: ieslu@zzu.edu.cn.
