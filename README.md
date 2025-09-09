# Exploring Speech Pattern Disorders in Autism using Machine Learning
 
This repository contains the datasets, prompts, and supplementary materials for the paper:  
**"Exploring Speech Pattern Disorders in Autism using Machine Learning"**  
by **Chuanbo Hu, Jacob Thrasher, Wenqi Li, Mindi Ruan, Xiangxu Yu, Lynn K. Paul, Shuo Wang, and Xin Li**.

---

## Abstract

Diagnosing Autism Spectrum Disorder (ASD) based on speech patterns in examiner-patient dialogues presents significant challenges due to the subtle and varied nature of speech-related symptoms. This study analyzes recorded dialogues using the Autism Diagnostic Observation Schedule (ADOS-2) to identify distinctive speech characteristics. We extracted 40 speech-related features, categorized into intonation, volume, rate, pauses, spectral characteristics, chroma, and duration. These features, analyzed using advanced speech tools, captured complex speech patterns associated with ASD. Machine learning techniques were then applied to classify individuals with ASD, achieving an f1-score of 84.49%. We removed MFCC and Chroma features to focus on prosodic, rhythmic, energy, and selected spectral features associated with the ADOS-2 Module 4 A2 score (i.e., speech abnormalities) to reduce redundancy and balance feature importance. This reduced feature set improved performance, with an accuracy of 85.77% and an F1-score of 86.27%, highlighting the effectiveness of a diverse combination of non-spectral features in ASD diagnosis. While spectral features (e.g., Spectral Centroid, Flux, Rolloff)  emerged as key features in the reduced feature set, MFCC 6 and Chroma 4 significantly contributed to classification performance in the full feature set, indicating their role in capturing fine-grained speech variations. Together, these findings support the development of advanced, context-aware models to enhance ASD diagnosis.

---

## Dataset

The sample features extracted from the dataset are available for download at the following link:  
[Download Dataset](https://drive.google.com/file/d/10KCjexmi30uL46elPi9TaxqClwBKNCih/view?usp=sharing)

Additional data may be added in the future.  

---


## Citation
If you use our data or prompts in your research, please cite our paper:
```text
@article{hu2024exploring,
  title={Exploring speech pattern disorders in autism using machine learning},
  author={Hu, Chuanbo and Thrasher, Jacob and Li, Wenqi and Ruan, Mindi and Yu, Xiangxu and Paul, Lynn K and Wang, Shuo and Li, Xin},
  journal={arXiv preprint arXiv:2405.05126},
  year={2024}
}
```
