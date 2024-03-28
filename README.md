# BLP(VITD) @ EMNLP2023
### This repository contains code implementation of share-task1 (*Violence Inciting Text Detection (VITD) of Bangla Social Media data*) at BLP@EMNLP 2023. Please visit <a href="https://github.com/blp-workshop/blp_task1#blp-shared-task-1-violence-inciting-text-detection-vitd">blp-workshop</a> for more details.

Please cite our [paper](https://aclanthology.org/2023.banglalp-1.21/)-
```@inproceedings{ahmed-etal-2023-score,
    title = "{S}core{\_}{I}s{A}ll{\_}{Y}ou{\_}{N}eed at {BLP}-2023 Task 1: A Hierarchical Classification Approach to Detect Violence Inciting Text using Transformers",
    author = "Ahmed, Kawsar  and
      Osama, Md  and
      Islam, Md. Sirajul  and
      Islam, Md Taosiful  and
      Das, Avishek  and
      Hoque, Mohammed Moshiul",
    editor = "Alam, Firoj  and
      Kar, Sudipta  and
      Chowdhury, Shammur Absar  and
      Sadeque, Farig  and
      Amin, Ruhul",
    booktitle = "Proceedings of the First Workshop on Bangla Language Processing (BLP-2023)",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.banglalp-1.21",
    doi = "10.18653/v1/2023.banglalp-1.21",
    pages = "185--189",
    abstract = "Violence-inciting text detection has become critical due to its significance in social media monitoring, online security, and the prevention of violent content. Developing an automatic text classification model for identifying violence in languages with limited resources, like Bangla, poses significant challenges due to the scarcity of resources and complex morphological structures. This work presents a transformer-based method that can classify Bangla texts into three violence classes: direct, passive, and non-violence. We leveraged transformer models, including BanglaBERT, XLM-R, and m-BERT, to develop a hierarchical classification model for the downstream task. In the first step, the BanglaBERT is employed to identify the presence of violence in the text. In the next step, the model classifies stem texts that incite violence as either direct or passive. The developed system scored 72.37 and ranked 14th among the participants.",
}
```
