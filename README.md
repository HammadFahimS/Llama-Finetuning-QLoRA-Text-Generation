# Fine-Tuning LLaMA Model with QLoRA for Product Description Generation

This repository contains code for fine-tuning the [LLaMA 3B v2 model](https://huggingface.co/openlm-research/open_llama_3b_v2) using QLoRA for the task of generating product descriptions. The fine-tuning process follows the guidelines from the [Databricks tutorial](https://www.databricks.com/blog/efficient-fine-tuning-lora-guide-llms).

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Requirements](#requirements)

## Introduction
This project demonstrates how to fine-tune a pre-trained LLaMA model using QLoRA. The goal is to generate high-quality product descriptions for various items. Fine-tuning is performed on the Red Dot Design Award product descriptions dataset.

## Dataset
The dataset used for this project is the [Red Dot Design Award Product Description](https://huggingface.co/datasets/xiyuez/red-dot-design-award-product-description) dataset available on Hugging Face.

## Model
The base model used is the [LLaMA 3B v2](https://huggingface.co/openlm-research/open_llama_3b_v2) model, a large language model known for its efficiency and effectiveness in natural language processing tasks.

## Requirements
To run the code, you need the following dependencies:
- Python 3.8 or higher
- PyTorch
- Transformers
- Datasets
- accelerate

You can install the required packages using the following command:
`pip install transformers==4.31.0 datasets==2.13.0 peft==0.4.0 accelerate==0.21.0 bitsandbytes==0.40.2 trl==0.4.7 mlflow`
