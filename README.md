# Large Language Models


The <a href="https://github.com/burcuozek/LLMrepo/blob/main/LLM.ipynb">LLM.ipynb</a> file serves as an introduction to the fundamentals of LLM, demonstrating how to customize and apply it in different contexts using Hugging Face. The document offers insights into selecting appropriate models and tokenizers, providing detailed explanations of their configurations.

Projects are follows: 
- Summarization
- Sentiment analysis
- Zero-shot classification
- Few-shot learning


The <a href="https://github.com/burcuozek/LLMrepo/blob/main/Rag_Tutorial.ipynb">Rag_Tutorial.ipynb</a> file includes the adaptation of RAG Retrieval Augmented Generation to LLM. It talks about the key components. It uses <a href="https://huggingface.co/datasets/databricks/databricks-dolly-15k ">databricks-dolly-15k dataset</a>.


[RAG_LLM_QuestionAnswering_DocumentPDF.ipynb](https://github.com/burcuozek/LLMrepo/blob/main/RAG_LLM_QuestionAnswering_DocumentPDF.ipynb) file presents a question-answering system utilizing Large Language Models (LLM). You can upload any research article, and the algorithm will provide answers based on the relevant context.


Large Language Models (LLMs) are advanced artificial intelligence systems designed to process and generate human-like text based on vast amounts of training data. They employ deep learning techniques, particularly transformer architectures, to understand and produce language with high proficiency. LLMs have applications in natural language processing tasks such as translation, text generation, sentiment analysis, and question answering, revolutionizing various fields including machine translation, content creation, and virtual assistants.

This project will explore the following subjects:
- Examining the applications of encoder-only, decoder-only, and encoder-decoder architectures. 
- Understanding Transformers and their constituent elements. 
- Delving into the concept and implementation of word embeddings.

Examining the applications of encoder-only, decoder-only, and encoder-decoder architectures. 

Decoder-Only Model:
•	Use Case: Decoder-only models are often employed in tasks where the output sequence is generated step by step based on some input context.
•	Example: In language modeling or text generation, where the model predicts the next word in a sequence given the preceding context.

Encoder-Only Model:
•	Use Case: Encoder-only models are useful when the task involves understanding or encoding information from the input sequence without the need for generating a corresponding output sequence.
•	Example: Sentence embeddings or document embeddings, where the goal is to represent the input text in a fixed-size vector for downstream tasks like classification.

Encoder-Decoder Model:
•	Use Case: Encoder-decoder models are common in sequence-to-sequence tasks where the input sequence is mapped to a fixed-size context vector by an encoder, and the decoder generates an output sequence based on this context.
•	Example: Machine translation, where the encoder processes the source language and the decoder generates the target language.
