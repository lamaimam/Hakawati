# Automatic Arabic Story Generation - Hakawaty

![Screenshot (1489)](https://github.com/user-attachments/assets/aadb0daf-0bdf-4ad4-b3de-b56cfd31b2e2)

# Fine-Tuning Qwen 2.5 & LLaMA 3.1

## Index
1. [Overview](#overview)  
2. [Features](#features)  
3. [Steps for Fine-Tuning](#steps-for-fine-tuning)  
4. [Dataset](#dataset)  
5. [Evaluation](#evaluation)  
6. [Project Structure](#project-structure)  
7. [Resources](#resources)  

## Overview
This repository is part of a graduation project focused on fine-tuning **Qwen 2.5**  
and **LLaMA 3.1** for Arabic story generation. The goal is to compare their capabilities  
using **LoRA (Low-Rank Adaptation)** fine-tuning on an **augmented dataset**.  
The project explores efficient fine-tuning techniques while optimizing performance  
on limited GPU resources.

## Features
- Fine-tuning **Qwen 2.5** and **LLaMA 3.1** for Arabic story generation  
- **LoRA** for efficient training  
- Support for **Google Colab** (T4 GPU, A100 GPU) and **local Ubuntu machines**  
- Deployment on **Hugging Face Hub** 

## Steps for Fine-Tuning
1. **Setup Environment**: Install required dependencies and configure the system.  
2. **Load Pretrained Model**: Use a base model such as **Qwen 2.5** or **LLaMA 3.1**.  
3. **Apply LoRA & Quantization**: Optimize model parameters to reduce memory usage and training cost.  
4. **Prepare Dataset**: Load and preprocess training data for fine-tuning.  
5. **Training Process**: Define training parameters and execute fine-tuning.  
6. **Deployment**: Push the trained model to **Hugging Face Hub** .  

## Dataset
This repository includes an **augmented open-source dataset** for training and evaluation.  
The dataset is formatted to align with the requirements of **Qwen 2.5** and **LLaMA 3.1** fine-tuning.  

## Evaluation
Evaluation scripts are provided to assess model performance on various benchmarks.  
These scripts measure key performance indicators to ensure high-quality Arabic story generation.  

## Project Structure

<img src="https://github.com/user-attachments/assets/2bd4720e-3421-463c-93b1-5156fa6d8323" alt="Screenshot" width="600">

## Resources
- [LoRA Paper](https://arxiv.org/abs/2106.09685)  
- [Hugging Face Documentation](https://huggingface.co/docs)  



