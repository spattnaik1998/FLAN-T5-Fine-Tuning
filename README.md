# FLAN-T5-Fine-Tuning

This repository contains code for fine-tuning large language models (LLMs) using Parameter Efficient Fine-Tuning (PEFT) for dialogue summarization tasks. The code utilizes the Hugging Face Transformers library and implements both full fine-tuning and PEFT strategies for fine-tuning LLMs.

Full Fine-Tuning
The repository includes code for fine-tuning LLMs, such as T5, using full fine-tuning on dialogue summarization datasets.
It demonstrates how to preprocess datasets, fine-tune the models using the Trainer class from Hugging Face, and evaluate the models qualitatively and quantitatively using human evaluation and the ROUGE metric.

Parameter Efficient Fine-Tuning (PEFT)
PEFT is introduced as a more efficient fine-tuning strategy compared to full fine-tuning.
The code implements Low-Rank Adaptation (LoRA), a form of PEFT, to train adapters on top of pre-trained LLMs. These adapters are much smaller in size and require fewer computational resources.
It demonstrates how to set up and train LoRA adapters, evaluate the performance of the PEFT models, and use them for inference.

Contents
Notebooks: Jupyter notebooks are provided to demonstrate the full fine-tuning and PEFT processes step-by-step.
Scripts: Python scripts are available for fine-tuning models, evaluating them, and performing inference.
Datasets: Sample dialogue summarization datasets are included for experimentation.
Pre-trained Models: Pre-trained LLMs and checkpoints for PEFT models are provided for quick experimentation.

Requirements
Python 3.x
Hugging Face Transformers
PyTorch
Other dependencies listed in requirements.txt

Usage
Clone the repository and install the required dependencies.
Follow the instructions in the notebooks or scripts to fine-tune models or perform inference.
Experiment with different datasets, model architectures, and fine-tuning strategies to optimize performance for dialogue summarization tasks.
