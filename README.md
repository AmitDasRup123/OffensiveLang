# OffensiveLang

## Overview
The OffensiveLang is a community based implicit offensive language dataset generated by ChatGPT 3.5 containing data for 38 different target groups. It has been meticulously annotated by Amazon MTurk workers, ensuring high-quality labeling of hate speech. Additionally, a prompt-based zero-shot method was employed with ChatGPT and the detection results were compared between human annotation and ChatGPT annotation. This dataset is invaluable for researchers and practitioners working on implicit hate speech detection and large language models.

**Source:** ChatGPT 3.5  
**Length:** 8270 texts
*train:* 6616 texts
*train:* 1654 texts

##OffensiveLang.csv_Details

Column1: Text: Contains text generated by ChatGPT 3.5.
Column2: Category: Represents the category of the target group.
Column3: Target Group: Specifies the target group for the text.
Column4: Final Annotation: The final human annotation determined by the majority vote among three MTurk annotators (this annotation will be used as the actual annotation for model training and evaluation).
Column5: OpenAI_Annotation: Annotation provided by ChatGPT 3.5.
Column6-8: Annotator1-3: Individual annotations from three human annotators.

## Paper
For a detailed investigation of the OffensiveLang dataset, refer to the associated paper: [OffensiveLang: A Community Based Implicit Offensive Language Dataset](https://arxiv.org/abs/2403.02472).

## Citation
If you use this dataset in your research, please cite the following paper:

@article{das2024offlandat,
  title={OffLanDat: A Community Based Implicit Offensive Language Dataset Generated by Large Language Model Through Prompt Engineering},
  author={Das, Amit and Rahgouy, Mostafa and Feng, Dongji and Zhang, Zheng and Bhattacharya, Tathagata and Raychawdhary, Nilanjana and Sandage, Mary and Pope, Lauramarie and Dozier, Gerry and Seals, Cheryl},
  journal={arXiv preprint arXiv:2403.02472},
  year={2024}
}

## License: CC BY

## Contact
For any questions or feedback, feel free to contact the authors of the paper or the dataset contributors.
Contact Information: azd0123@auburn.edu
---

This README provides an overview of the HateSpeechCorpus, including its source, length, annotators, keywords used for generation, and citation details. The dataset is a valuable resource for advancing the field of hate speech detection.

