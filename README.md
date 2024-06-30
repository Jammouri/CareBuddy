# CareBuddy

### Fine-tuning a Language Model with Lora for Text Generation

This project demonstrates how to fine-tune a language model using Hugging Face's Transformers library, incorporating Lora for enhanced training efficiency. The example model used here is based on the Llama2 model fine-tuned for medical terms generation.

# Overview

In this project, we fine-tuned the Llama2 model (aboonaji/llama2finetune-v2) on a dataset of medical terms formatted for causal language modeling (CAUSAL_LM). The goal was to improve the model's ability to generate coherent medical text based on specific prompts.

# Key Features

1-Model Fine-tuning: We utilized the Hugging Face Transformers library to fine-tune the Llama2 model for text generation tasks related to medical terms.

2-Lora Integration: Lora, a technique for optimizing neural network training, was employed with configurable parameters (r, lora_alpha, lora_dropout) to enhance training efficiency and model performance.

3-Dataset: The training dataset used is sourced from the "aboonaji/wiki_medical_terms_llam2_format" dataset available through Hugging Face's dataset library.

# Requirements

Python 3.x

PyTorch

Transformers

trl (Temporal Reparameterization Layer)

peft (Probabilistic Error Function Transfer)
