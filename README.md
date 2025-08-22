# Clinical NLP Toolkit: RAG-Based Chatbots Specializing on Turkish Clinical Notes and Diagnosis Classifier

A collection of Jupyter notebooks and resources for building, fine-tuning, and evaluating clinical natural language processing (NLP) models.  
Includes chatbots, diagnosis classifiers, and experiments with multiple large language models (LLMs) on Turkish clinical notes.

## 🚀 Features

- Fine-tuning of **Mistral 7B**, **Falcon RW 1B**, and **BERTurk** for clinical NLP tasks.
- Retrieval-Augmented Generation (RAG) for more accurate medical Q\&A.
- Multi-model chatbot implementations.
- Diagnosis classification pipeline with evaluation metrics.
- Fully reproducible Jupyter notebooks for each experiment.

## 📂 Repository Structure

| File | Description |
|------|-------------|
| **ClinicalChatbot_mistral7b.ipynb** | LLM-based clinical chatbot built using the Mistral 7B model. Handles patient-doctor style question answering with domain-specific context retrieval. |
| **DiagnosisClassifier_BerTurk.ipynb** | Fine-tuned BERTurk model for medical diagnosis classification from clinical notes. |
| **finetuned_falcon_rw_1b.ipynb** | LLM-based clinical chatbot, built with fine-tuned Falcon RW 1B model on Turkish medical text data. |
| **hamza_xl_modeli.ipynb** | Chatbot implementation using the Hamza XL model hosted on Hugging Face. |
| **clinical_notes.csv** | Dataset of 500 syntheticly created Turkish clinical notes used for training and evaluation (de-identified). |

## 📊 Models & Frameworks

- [Mistral 7B](https://mistral.ai/) — general-purpose LLM adapted for clinical dialogue.
- [BERTurk](https://huggingface.co/dbmdz/bert-base-turkish-cased) — fine-tuned for medical text classification.
- [Falcon RW 1B](https://huggingface.co/tiiuae/falcon-rw-1b) — domain-specific fine-tuning on clinical notes.
- [Hamza XL](https://huggingface.co/emrecanacikgoz/hamza_xl_modeli) — integrated for conversational medical Q\&A.
- Frameworks: **PyTorch**, **Transformers**, **Datasets**, **PEFT**.
