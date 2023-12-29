# Mistral 7B Fine-Tuning 

## Overview

This repository contains the code for fine-tuning the Mistral 7B model on the MetaMathQA-40K dataset. The project aims to leverage Mistral's capabilities for natural language processing tasks, specifically in the context of mathematical questions and answers.

## Features

- Fine-tuning Mistral 7B on MetaMathQA-40K dataset
- Integration of BitsAndBytes quantization for model compression
- Implementation of LoraConfig for adapter-based training
- Monitoring training progress with Weights and Biases (WandB)
- Deployment of the fine-tuned model in Gradio for interactive use

## Project Structure

- `notebooks/`: Jupyter notebooks used for experimentation and analysis.
- `src/`: Source code for the project.
- `results/`: Directory to store training results and model checkpoints.
