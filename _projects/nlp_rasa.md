---
layout: project
title: Finance Task-oriented chatbot with Rasa
subtitle: A financial research assistant
---

{%
	include image_with_caption.html
	url="/assets/projects/nlp_rasa/workflow.png"
	width="100%"
%}

[[code]](https://github.com/GuanghuiMin/Rasa_Fin_Faq)

This project involved the development of a task-oriented dialogue system using the Rasa framework. The chatbot serves as a valuable tool for investment researchers.

Upon receiving a dialogue input, the system first employs the Bert-chinese-large model for tokenization and feature extraction. Intent recognition is achieved by matching the provided intent with examples of questions using similarity measures. Entity extraction is performed using the CRF algorithm combined with rule-based matching. This enables the chatbot to provide targeted responses by invoking APIs based on the extracted entities. Additionally, for responses beyond enumerated intents, I fine-tuned a GPT-2 chat model using Chinese internet forum data, allowing the chatbot to engage in casual conversations.

In addition to natural language understanding (NLU), the project also includes engineering work such as question-answering feedback and session management. For the frontend, the Alibaba ChatUI framework was utilized, and data visualization and richer response displays were achieved through the integration of Echarts and Plotly.

The chatbot developed in this project serves as a versatile toolbox for investment researchers. Its implementation using the Rasa framework, along with the integration of advanced models and user-friendly features, has led to its widespread adoption within the organization. The chatbot effectively handles various tasks related to investment research, demonstrating its practicality and effectiveness in assisting researchers with their work.