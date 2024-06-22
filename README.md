# LLaMA and Gemma 2b Model Setup and Comparison

This repository contains instructions and scripts for setting up and comparing OpenAI's LLaMA and Gemma 2b language models.

## Repository Structure

- `setup_scripts/`: Contains shell scripts for setting up each model
- `config/`: Contains configuration files for the models
- `comparison/`: Contains a script for comparing the models

## Setup Instructions

1. Install Ollama by following the instructions at [[https://ollama.ai/](https://ollama.ai/)]
2. Run the setup scripts for each model:
   bash setup_scripts/setup_llama.sh
   bash setup_scripts/setup_gemma.sh
3. Follow the instructions in each script to interact with the models

## Comparison

To compare the models, run:
bash comparison/compare_models.sh
This script will prompt both models with the same question and display their responses for comparison.

## Model Interactions

You can interact with each model using curl commands. Examples are provided in the setup scripts.

## Note

Make sure you have sufficient disk space and a good internet connection, as these models can be quite large.

OR 

Follow the steps in the YouTube video:

[[YouTube Link](https://www.youtube.com/watch?v=3K_wJjrc66M)]
