# Seq2Seq Machine Translation: English to Low-Resource Language(Hindi)

## Overview
This project focuses on implementing machine translation using Seq2Seq models for translating English to a low-resource language. The task involves utilizing various Seq2Seq models, including OPUS-MT, M2M-100, and MBART-50, to perform translation tasks on the Flores200 dataset.

## Goals
The primary goal of this project is to gain hands-on experience with Seq2Seq models for machine translation tasks, understand the translation process, and evaluate model performance using metrics like BLEU score. Additionally, the project aims to explore the challenges and nuances associated with translating from English to low-resource languages.

## Task Description
The project involves the following key tasks:
1. Data Preparation: Downloading and preprocessing the Flores200 dataset, selecting English and a target low-resource language for translation, and preparing 100 sentence pairs for the task.
2. Machine Translation with Seq2Seq Models: Implementing machine translation using various Seq2Seq models available in Hugging Face, including OPUS-MT, M2M-100, and MBART-50. Exploring different parameter settings and evaluating model performance.
3. Results Analysis and Evaluation: Evaluating translation quality using the BLEU score metric, comparing performance across different models, and providing insights based on evaluation results and analysis.

## Results
- OPUS-MT: Achieved a BLEU score of 2.26, indicating relatively low translation quality.
- M2M-100: Achieved a BLEU score of 21.82, indicating high-quality translation.
- MBART-50: Achieved a BLEU score of 20.33, also indicating high-quality translation.



## Credits
- Flores200 Dataset: [Link](https://huggingface.co/datasets/Muennighoff/flores200)
- Hugging Face Models used:
- Opus-mt-en-hi [link](https://huggingface.co/Helsinki-NLP/opus-mt-en-hi)
- m2m100_418M model [Link](https://huggingface.co/facebook/m2m100_418M)
- mbart-large-50-many-to-many-m model [Link](https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt)



