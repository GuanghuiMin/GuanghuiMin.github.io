---
layout: project
title: Applications of LLMs in Financial Industry
subtitle: Fine-tune and apply Langchain to local deployed LLMs
---

{%
	include image_with_caption.html
	url="/assets/projects/nlp_llm/workflow.png"
	width="100%"
%}

**Experimental Equipment: A server equipped with dual NVIDIA RTX A6000 graphics cards.**

This project focuses on three main aspects: fine-tuning Language Models (LLMs) using internal corpora, connecting LLMs to an internal knowledge base to generate answers containing internal knowledge, and enabling LLMs to use tools for web scraping and functionalities such as email communication and contact directory queries.

The fine-tuning of LLMs involves several steps. Firstly, non-sensitive internal corpora are transformed into question-answer instructional data using the chatgpt interface. Then, the QLoRA method is applied to perform instructional fine-tuning on the LLM. The fine-tuned models are then tested by colleagues, who provide feedback by upvoting or downvoting the generated answers. The collected data is further used for Reinforcement Learning via Human Feedback (RLHF) using the Proximal Policy Optimization (PPO) algorithm. This iterative process leads to answers that incorporate internal language and decision-making capabilities.

For LLMs to answer questions based on the knowledge base, the project utilizes the text2vec tokenizer in practical applications. The overall architecture follows the Langchain framework, but with the addition of vector clustering after storing token vectors in the Milvus vector database. The process involves finding classes with high similarity to the question, and then selecting vectors with high similarity within the matching class as part of the prompt input for the LLM.

Finally, in terms of LLM tool integration, the project primarily utilizes a React-based solution. This involves including API usage instructions and an eos_token in the LLM prompt to facilitate LLM invocation.

Throughout the project, various LLM models have been deployed on the experimental server, including ChatGLM-6B, ChatGLM2-6B, Baichuan-13B-Chat, and Qwen-7B-Chat. These models have been tested and evaluated accordingly.

The ultimate goal of this project is to apply the achieved results in the field of marketing for public fund management. By leveraging the capabilities of LLMs, incorporating internal knowledge, and utilizing external information retrieval and communication tools, the project aims to enhance marketing efforts and improve customer interactions within the public fund industry.