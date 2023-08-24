---
layout: project
title: Evaluation of Question Answering Methods with different ways of preprocessing
subtitle: Evaluation based on SQuAD 2.0
---

[[Poster]](https://drive.google.com/file/d/1uxej0NKdNBpZfQXGd4ZnSXHpamm0U1i9/view?usp=drive_link)

[[Code]](https://github.com/GuanghuiMin/EmbedQA)


### Background and Task

Text understanding and reasoning are prominent areas of research in Natural Language Processing (NLP), offering potential applications in virtual assistants and automated customer service. The success of these applications relies on the ability of models to comprehend and process textual information. One common method for evaluating a model's comprehension capability is through question answering (QA). QA tasks involve answering queries presented in natural language based on a given context paragraph that contains the relevant information. This project focuses on building and comparing the performance of two neural network QA models based on two seminal papers.

### Approaches

The project explores two primary approaches for question answering:

**·** Bi-Directional Attention Flow (BiDAF): This approach leverages bidirectional attention to enable the model to focus on relevant information in both the context paragraph and the query. By incorporating complex embeddings, the BiDAF model aims to enhance its performance in understanding and answering questions accurately.

**·** Document Reader Question Answering (DrQA): The DrQA model emphasizes the inclusion of various types of features during the embedding step. By incorporating a wide range of features, such as token features and aligned question embeddings, DrQA aims to improve its overall performance in question answering tasks.

### Analysis

The project conducts a comprehensive analysis of the two QA models, yielding valuable insights into their performance:

**·** BiDAF: The analysis reveals that more complex embeddings result in improved performance for the BiDAF model. By incorporating advanced embedding techniques, the model achieves better comprehension and accuracy in answering questions. However, the analysis also indicates that the current set of hyperparameters for BiDAF may not be optimal. As part of future work, the project aims to search for and identify the most suitable hyperparameters that enable the model to converge globally and enhance its overall performance.

**·** DrQA: The analysis demonstrates that the inclusion of a broader range of features during the embedding step leads to improved performance for the DrQA model. By incorporating multiple types of features, such as token features and aligned question embeddings, DrQA achieves enhanced comprehension and more accurate answers to questions.

The project's findings highlight the importance of leveraging sophisticated embeddings and diverse feature sets to improve the performance of QA models. Additionally, the identification of areas for improvement, such as hyperparameter tuning for BiDAF, suggests avenues for future research and refinement of the models.

In conclusion, this project focuses on the development and evaluation of two neural network QA models: Bi-Directional Attention Flow (BiDAF) and Document Reader Question Answering (DrQA). Through a comprehensive analysis, the project showcases the impact of complex embeddings and diverse feature sets on the models' performance. The findings contribute to the advancement of text understanding and reasoning in NLP and provide insights for future improvements in QA-based applications, including virtual assistants and automated customer service.

