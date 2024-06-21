# Symptom_Dx_ICD
From description of symptom, find possible diagnosis and infer ICD code for the diagnosis

## Project Overview

In this simple clinical setting, the process is straightforward:


1. A patient visits a doctor’s office and describes their symptoms.
2. The physician writes a diagnosis in the visit note.
3. Medical coders extract ICD codes for the diagnoses from the visit note.

This project aims to simplify and implement this clinical scenario using Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and fine-tuning techniques. It integrates and builds upon my previous two GitHub projects: [FineTuning_Llama_3_8b_Symptom_Dx](https://github.com/oldflag/FineTuning_Llama_3_8b_Symptom_Dx) and [GenAI_RAG_ICDcoding](https://github.com/oldflag/GenAI_RAG_ICDcoding).

## Previous Projects Integration

### FineTuning_Llama_3_8b_Symptom_Dx:
In this project, I fine-tuned the Llama 3 8b model with symptom and diagnosis Q&A data. The goal was to enable the model to provide accurate diagnoses based on given symptom descriptions.

### GenAI_RAG_ICDcoding:
In this project, I developed an RAG application using OpenAI ChatGPT APIs and a subset of ICD code descriptions from CMS. The application is designed to extract and suggest appropriate ICD codes based on clinical notes.

## Project Goals

This project combines the strengths of the above two projects to create a comprehensive solution for clinical note processing. The primary objectives are:

* Symptom to Diagnosis: Utilizing the fine-tuned Llama 3 8b model to interpret patient symptoms and provide probable diagnoses.
* Diagnosis to ICD Coding: Implementing an RAG approach to accurately extract ICD codes from the diagnoses mentioned in clinical notes.

By integrating these advanced AI techniques, this project aims to streamline the workflow in clinical settings, enhancing the efficiency and accuracy of medical coding
